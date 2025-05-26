# Daily-Report

# ✅ Development Report
**Date:** May 21, 2025  
**Module:** UI Navigation & State Management

## ✅ Changes Made for Desktop screen

### 1. Removed `TabBar`
- Replaced the traditional top `TabBar` with a cleaner layout.
- Simplified UI to better suit larger screens or desktop-like environments.

### 2. Implemented Left-Side Expandable Tabs
- Created a custom **vertical tab list** on the left side of the UI.
- Tabs **expand on click** to reveal their corresponding views.


### 3. Added New Provider Controller
- Centralized state management for:
  - Selected tab index.
  - Expansion logic.
  - View Submenu.
![image](https://github.com/user-attachments/assets/07671c6f-da5e-48a3-b4cd-33f45528b1fd)

### 4. DataTable Enhancements
 - Implemented alternating row striping (gray for odd/even rows) to improve readability and visual clarity.
![image](https://github.com/user-attachments/assets/7185b3d1-02ca-42f1-be89-16f81776f7e9)
 - Create custom datatbale for reuse
![image](https://github.com/user-attachments/assets/3114e0b8-f2aa-4c27-9391-2b3988d20292)



## ✅ Changes Made for Mobile screen

### 1. Add Icon to close
- added each screen closed button and made it visisble only if it is mobile size
- Popup fullscreen page

 ![image](https://github.com/user-attachments/assets/2be3ba40-ce7c-42ad-a969-065059142227)


# ✅ Development Report
**Date:** May 24, 2025  
**Module:** UI Navigation Changes

### 1. Side Navigation Submenu Design Updated
- Changed layout from Tab to Row widget
- Researched various navigation UI designs for reference and inspiration

![image](https://github.com/user-attachments/assets/3138a9cf-d8b4-4c17-8b65-f285b9ba61a5)

-Redesign Side Menu for desktop

![image](https://github.com/user-attachments/assets/991023b6-5062-4dd3-b32a-cf6b07b81635)

-Redesign Side Menu for Mobile and Tablet

![image](https://github.com/user-attachments/assets/58a58fd1-7866-41e3-8655-626eb83ec218)

### 2. Revert to previous design as per the feedback and changes
- check if the width is < 1000, and swicth the widget to icon only
- chnage the selected tab color to black
- Wrap the item tab to ExpandTile and on expanded color to light grey.

![image](https://github.com/user-attachments/assets/9307fbcc-2a9c-4878-82d8-152e81bb46a4) ![image](https://github.com/user-attachments/assets/4c63adad-f033-46ca-8cdf-76ec9f079c25) ![image](https://github.com/user-attachments/assets/34ece997-d865-4133-bf21-0d9ed84dbb4c)
![image](https://github.com/user-attachments/assets/ccebb054-55df-4520-9131-1ce437865f51)


- added two new sidemenucontroller method

  ![image](https://github.com/user-attachments/assets/8d5a4fc3-2636-4a77-9b05-8b6c890b6e0f)

  ## Adding Colapsible functionality
  - Implemented a circular toggle button to control the collapsible panel.
  - Integrated a controller method and set up a listener to respond to state changes (open/close) using the provider.
    
![image](https://github.com/user-attachments/assets/29097913-8588-4251-9473-ebd56bb8a95c) ![image](https://github.com/user-attachments/assets/5f43d957-c8a5-46fe-80dc-9acd0bc908fe)










