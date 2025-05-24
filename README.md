<div align="center">
  <img src="https://github.com/808StaN/zenBrowser_MacOS_Icons/raw/main/MacOS_Icons.gif?raw=true" alt="ZenBrowser macOS Icons Demo">
</div>


## 🛠 Installing `macOSicons.css`  

### 1. Enable user styles support  
- Open Firefox and type in the address bar:  
  ```about:config```  
- Search for:  
  ```toolkit.legacyUserProfileCustomizations.stylesheets```  
- Change the value to **`true`** (double-click).  

### 2. Find your profile folder  
- Type in the address bar:  
  ```about:support```  
- In the **"Profile Folder"** section, click the **"Open Folder"** button.  

### 3. Create required files and folders  
- In your profile folder, create a new directory called:  
  ```chrome```
  - Copy the file to the `chrome` folder:  
  ```macOSicons.css```    
- Inside the `chrome` folder, create a file:  
  ```userChrome.css```  
- Add this import statement to the file:
  ```@import url("macOSicons.css");```
- (Alternatively, you can paste the entire content of:
  ```macOSicons.css``` into:
  ```userChrome.css```  

### 4. Restart ZenBrowser  
- Close and reopen your browser for changes to take effect.  
