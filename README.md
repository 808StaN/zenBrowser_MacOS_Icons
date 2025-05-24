-----
![ZenBrowser macOS Icons Demo](https://github.com/808StaN/zenBrowser_MacOS_Icons/raw/main/MacOS_Icons.gif?raw=true)
-----

## 🛠 Instalacja `userChrome.css` (Firefox)  

### 1. Włącz obsługę stylów użytkownika  
- Otwórz Firefox i wpisz w pasku adresu:  
  ```about:config```  
- Wyszukaj:  
  ```toolkit.legacyUserProfileCustomizations.stylesheets```  
- Zmień wartość na **`true`** (kliknij dwukrotnie).  

### 2. Znajdź folder profilu  
- Wpisz w pasku adresu:  
  ```about:support```  
- W sekcji **"Plik folderu profilu"** kliknij przycisk **"Otwórz folder"**.  

### 3. Stwórz wymagane pliki i foldery  
- W folderze profilu utwórz folder o nazwie:  
  ```chrome```  
- Wewnątrz folderu `chrome` utwórz plik:  
  ```userChrome.css```  
- Wklej do niego swój kod CSS (np. style dotyczące `pasek_mac.gif`).  

### 4. Zrestartuj Firefox  
- Zamknij i ponownie uruchom przeglądarkę, aby zmiany zaczęły obowiązywać.  

### 🔍 Gdzie znaleźć mój profil?  
- **Windows:**  
  ```C:\Users\[Twoja_Nazwa]\AppData\Roaming\Mozilla\Firefox\Profiles\[nazwa_profilu]```  
- **macOS:**  
  ```~/Library/Application Support/Firefox/Profiles/[nazwa_profilu]```  
- **Linux:**  
  ```~/.mozilla/firefox/[nazwa_profilu]```  

> ⚠️ **Uwaga:** Jeśli folder `chrome` lub plik `userChrome.css` nie działają, upewnij się, że Firefox nie został zaktualizowany (czasami resetuje ustawienia).  
