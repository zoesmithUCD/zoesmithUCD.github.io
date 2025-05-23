# WFC 70: Data Shortcuts and Their Uses
Keyboard shortcuts are a combination of keys, that when presed, preform a certan command on your computer. Comands can range from copying a piece of information, to switching to a new window. They are there to make doing certan tasks much faster and smoother, by bypasing mouse clicks and keeping both hands on the keyboard. Most Shortcuts are universal, which means they work in many different applications. RStudio does have some differences though that will be pointed out later in the article. 




## Why Should we Learn Shortcuts?
1. Making workflows more efficient
2. Increase productivity
3. Spend less time moving your hand(s) away from the keyboard 
4. Eliminates the possibility of misclicking

## Computer shortcuts
These shortcuts should work whether or not you are in RStudios, and are helpful for everyday use.  

### Switching Tabs  
<video width="720" height="540" controls loop="" muted="">
    <source src="https://github.com/user-attachments/assets/925f4f59-ff14-4acc-88e7-d2b50d23a74c">
</video>

**Ctrl+Tab** allows us to switch tabs in google chrome or RStudio without having to move our cursor. 


### Adding and Deleating Tabs
<video width="720" height="540" controls loop="" muted="">
    <source src="https://github.com/user-attachments/assets/a738fb82-7b81-40b0-abe8-4c4d8c116c75">
</video>

These keyboard shortcuts are helpful while using google chrome and other simmilar browsers. **Ctrl+T** opens a new tab, while **Ctrl+W** will close the tab that you're on. If you want to get a bit more bold, **Ctrl+Shift+W** will close all the tabs in your current window. I know we all have closed out of a tab we didn't mean to before, and have had to go and find it in our search history. With the shortcut, **Ctrl+Shift+T**, you are able to reopen the last closed tab in your browser. For macbook users, just substitute the **Ctrl** for **Commmand** and you're all set!


### Switching Between Windows
<video width="720" height="500" controls loop="" muted="">
    <source src="https://github.com/user-attachments/assets/e6efeeeb-c63e-4173-af58-0b75eb20ed43">
</video>

**Alt+Tab** (or **Command+Tab** for macbook users), allows us to quickly switch between windows (e.g. between Google and RStudio). To move in the other direction, use **Alt+Shift+Tab**. Both of these commands can be held down to view a menu of all the windows, or quickly executed to toggle between windows. 


### Moving Windows
<video width="720" height="540" controls loop="" muted="">
    <source src="https://github.com/user-attachments/assets/7e2fe559-58bc-42bf-bd72-6a9fdad71045">
</video>

By using **Win+↑** (**Command+Ctrl+F for macbook users) you are able to easily make a current window full screen. Since RStudio opens by default in windowed mode, it is helpful to use this every time it's opened. There are other simmilar movements you can make with your widows tat we have listed below int he additional computer shortcuts section. 





## Additional Computer Shortcuts
#### (If you want to be fancy) 

-   **Ctrl+Z**: undo

-   **Ctrl+Y**: redo

    -   Note: in RStudio, the default shortcut for redo is **Ctrl+Shift+Z**, not **Ctrl+Y**, because **Ctrl+Y** is assigned to a different command. You can change this (and other shortcuts) by navigating to Tools → Modify keyboard shortcuts… → search “Paste Last Yank” → disable it (i.e. click in the “Shortcut” section and delete the existing shortcut), or following the steps from the R team [here](https://support.posit.co/hc/en-us/articles/206382178-Customizing-Keyboard-Shortcuts-in-the-RStudio-IDE)
    
-   **Alt+D**: selects the address bar (e.g. Google)

-   **Ctrl+Backspace**: delete the word left of the cursor

-   **Win+(1-9)**: runs the program listed in the task bar according to its order. If the program is already running, it switches to it

    -   ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdMlo04cz9pWg6_r9i3tLLBzQfRincxfLOd4wnNZ51gTOq8CAFkTDCWozDWkmy-FiaaSMfs8cGvDD0i-MAKRq1Eyt02EwRGNKLWINpk-kOJaVJZ4RNA0IOpzKvIw465EoG7NF8h?key=YWdbpxiSjg1ykqZRVzbV5svS)

        -   **Win+1** will open File Explorer

        -   **Win+7** will switch to RStudio

-   **Win+←** (left arrow): snap window to the left

    -   Useful if you want to view multiple windows at once

-   **Win+→** (right arrow): snap window to the right

-   **Win+↓** (down arrow): make current window windowed

    -   Press **Win+↓** an additional time to minimize a window

        -   **Command+Control+F** for macbooks

-   **Win+Shift+S**: opens a screenshot tool to take partial screenshots

    -   **Command+Shift+4** for macbooks
 
## R-related shortcuts

R-Studios has a lot of great keyboard shortcuts that can save you time while coding. We have compiled a list of some that will be the most usefull for us in WFC 70. You can find a full list of R-related shortcuts by going to R-studios webcite, where they have compiled a couple different master sheets depending on what program you're using. 

You can also easily see a list of shortcuts while in R-studios by clicling **Tools > Keyboard Shortcut Help**. Another way to view this is by using a keyboard shotcut yourself! To access this, type **Alt+Shift+K** for windows users or **Option+Shift+K** for macbook users. 


### 1) Running your code
<video width="720" height="540" controls loop="" muted="">
    <source src="https://github.com/user-attachments/assets/8dd5f53e-f22d-4747-8247-3d18a2a529a5">
</video>

You are able to use **Ctrl+Enter** (**Command+return** for macbook users) to easily run code in RMarkdown. This shortcut works from anywhere in the code line, so your cursor can be anywhere in the code and the entire command will run. You Don't have to be in the firts line of the command. 


### 2) Interting a Code Chunk
<video width="720" height="540" controls loop="" muted="">
    <source src="https://github.com/user-attachments/assets/331fd760-12a5-4c5d-8027-b204ed0b209a">
</video>

By using **Ctrl+Alt+I** (**Command+Option+I** for mackbook users), you can easilty make a new coding chunck in your markdown file. This will become more useful for when you get in to writing your final project. 

## Aditional R-related Shortcuts

-   **Ctrl+Shift+M**: inserts a piping tool

      -  **Command+Shift+M** for macbook users

          -  Note: this piping took is not the same one you will be introduced to in lab. It will look like this %>% insted of this l> . The one we are introduced to is universal and works everywhere in RStudios. The first piping tool, %>%, only works when a package called magrittr is loaded. When we use tidyverse, this tool will work becasue magrittr is attached to the tidyverse package. You can also edit this shortcut by following the same steps we outlined earlier for **Ctrl+Y**
       
-    **Shift+Home**: Selects all text to the left of the cursor in the current line 
  
-    **Shift+End**: Selects all text to the right of the cursor in the current line 
  
-    **Ctrl+Home**: Navigates cursor to the begining of the file 

      -    **Command+↑** (Up arrow) for macbook users
    
-    **Ctrl+End**: Navigates cursor to the end of the file 

      -  **Command+↓** (Down arrow) for macbook users
 
  
