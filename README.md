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

# ✅ Development Report
  **Date:** May 26, 2025  
  **Module:** UI Navigation Changes

## ✅ Adding Colapsible functionality

### 1. Side nav colapsible
  - Implemented a circular toggle button to control the collapsible panel.
  - Integrated a controller method and set up a listener to respond to state changes (open/close) using the provider.
    
![image](https://github.com/user-attachments/assets/29097913-8588-4251-9473-ebd56bb8a95c) ![image](https://github.com/user-attachments/assets/5f43d957-c8a5-46fe-80dc-9acd0bc908fe)![isopen](https://github.com/user-attachments/assets/90726b2a-3632-4ff4-a195-294efff0488b)

### 2. Sub Menu Overlay
  - implemented overlap on sub menu in colapsed.
  - added overlay toggle method

![image](https://github.com/user-attachments/assets/12573ed8-dc82-43e3-9f0b-575ce110ab02)  ![overlay](https://github.com/user-attachments/assets/bee68312-3ea6-4bf7-81b5-55c8b4e7633e)

### 3. Revert to previous design as per the feedback
  - Removed the Overlay implementation for submenu display.
  - Introduced a SubMenuController to handle submenu open/close logic.
  - Refactored submenu behavior to align with the original inline rendering approach.

![image](https://github.com/user-attachments/assets/0a1faba0-4a8c-4045-92ca-8cb3bb7d6bb8) ![image](https://github.com/user-attachments/assets/6772368d-c437-4184-a0d7-55fd393d1423)



# ✅ Development Report
**Date:** May 27, 2025  
**Module:** Common page header

### 1. Collapsible Sidebar Menu & Navigation State Handling
- open() / close()	Dynamically controls sidebar visibility
- mannuallyOpen()	Allows manual override of sidebar state
- fnSelectMenu()	Sets main menu selection and optional submenu
- subMenuProductIndex()	Targets a submenu directly using index

![collapsible_logic](https://github.com/user-attachments/assets/fcbb4c34-9c3b-49d5-8a88-6440d905de34)
![image](https://github.com/user-attachments/assets/63b0a335-a8b7-4604-af60-d23f1ef74ee0) ![image](https://github.com/user-attachments/assets/9233ba27-fdaa-4c30-9a49-cbcac72214f6)

### 2. Common header 
- Add common header to all the the pages and fix to top

![image](https://github.com/user-attachments/assets/9de0b3a2-d369-4fa9-aab8-91c59429b11b)

- Side Sub Menu page navigation
-  header background color matched with side nav and breadcrumb sub menu color to grey.
-  unwanted blue color scrollbar removed
-  Company logo top gap decreased
-  Code share for integration
![image](https://github.com/user-attachments/assets/37e7adcf-b8a0-44e7-bf3b-364e39ae4a26)

![image](https://github.com/user-attachments/assets/2547e30b-1798-4a9e-a985-edd29ce18dba) ![image](https://github.com/user-attachments/assets/3aa80997-a93b-45f5-9e5d-0318d3a20cae)

# ✅ Development Report
**Date:** May 27, 2025  
**Module:** Changes as per the feedback

### 1. Zomato API
- Researched API integration options for POS systems.
- Sent an official email to Zomato regarding POS integration.
- Email has been forwarded to the development team for follow-up.
 
![image](https://github.com/user-attachments/assets/8a05bd9e-928b-47aa-ba7b-6e41a5e4c461)


### 2. Common header changes as per feedback
- Removed repetitive code to improve maintainability.
- Eliminated the unused icon list.
- Side menu hover animation issue identified but not yet resolved.
- Updated the scaffold background color to a lighter shade and applied a card layout to the body for better UI consistency.

![image](https://github.com/user-attachments/assets/c8f6300b-572e-4f11-9316-90fb7564e7e5) ![image](https://github.com/user-attachments/assets/7e4a366c-f708-4dde-919c-a2baba5e4687)


### 3. Code Integration
- Replace the side nav to new Code
- Replace Dashboard layout

# ✅ Development Summary
**Date:** May 31, 2025
**Module:** Flutter PDF Invoice Dialog Redesign

### 📝 Overview
The invoice dialog has been redesigned for improved layout, styling, and functionality. Supporting files and integration updates were made across the app.

### 📂 New Files
- dialog.dart: Contains the new PdfDialog widget.

- pdf.controller.dart: Defines InvoiceProvider for managing invoice state.

### ⚙️ Key Changes
- main.dart: Added ChangeNotifierProvider for InvoiceProvider.

- salescreate.dart: Integrated PdfDialog (notably at line 753).

### 🧱 Key Components
#### PdfDialog:
- Split-screen layout (invoice details & controls).
- Formatted to A4 size.
#### InvoiceScreen:
- Improved layout: headers, company/customer info, items, tax, totals, declaration.
- Uses InvoiceProvider for dynamic updates.

### ⚠️ Issues & Suggestions
 - Logo Not Loading: Check image URL or use local asset.
 - Error Handling: Add validation and error guards.
 - Refactoring: Extract reusable widgets.
 - Responsiveness: Use MediaQuery for adaptive UI.

![image](https://github.com/user-attachments/assets/b778a666-892d-4079-a1d6-d54c1c6dd0b7)


### ✅ Conclusion
The redesign significantly enhances the invoice dialog. With minor improvements in image handling, code structure, and error resilience, the module will be production-ready.


# ✅ Development Summary
**Date:** JUNE 2, 2025
**Module:** PDF Invoice

### 1. Provider
- Added provider method to update received amount dynamically via onChanged in TextField.

### 2. Dashboard Key Changes

- **Layoutdashboard** -> Removed SafeArea, SingleChildScrollView, and PageHeader due to scroll and layout issues.
- **Responsive Layout** -> Implemented using LayoutBuilder to dynamically adjust the number of columns based on screen width.
- **LicenseCheck Widget** -> Added a separate widget (LicenseCheck) for license-related UI and logic to improve modularity.
- **Chart Height** -> Set to a fixed value (450.0) for consistency across different screen sizes.
- **Scrollbar** -> resolve rendering issues with overflow and nested scrolling on larger screens.

![1](https://github.com/user-attachments/assets/92f0724a-ab45-49d5-8f6a-646fdda22ac0) to ![1 1](https://github.com/user-attachments/assets/8dde395f-7444-4bec-990a-455b220d0ab6)

Issue on graph
![image](https://github.com/user-attachments/assets/cfe72a4e-53ba-4fb4-932e-bb32e3e8e3bf)
![image](https://github.com/user-attachments/assets/27079e59-982d-4adc-ae8d-09e24f4b0d2b)



### ✅ Conclusion
The dashboard was optimized for responsiveness and scroll issues were resolved by simplifying the layout. Chart rendering was fixed with defined heights, and a modular LicenseCheck widget was added for better license management. Overall, the UI is now cleaner and more user-friendly across devices.

# ✅ Development Report
**Date:** June 3, 2025  
**Module:** Dashboard card hide/show content

### Refactored
 - The DashboardCardsWidget has been refactored to improve its structure and functionality.
 - Visibility settings are fetched from the database and applied to the UI. Only visible items are rendered.
### integrated Code and dashboard side setting (Incomplete)
 - Hide/Show 


# ✅ Development Report
**Date:** June 4, 2025  
**Module:** Dashboard Setting Contents

### Setup and insert new rows data in db 
 - Implemented group-wise settings for dashboard items to control visibility (hide/show) dynamically.
 - Integrated the new settings code with the latest codebase.
 - Added group-based controls for the "About" section in the sidebar navigation and its visibility via controller.
 - Made About Fields responsive using LayoutBuilder and Wrap widgets for flexible field arrangement across screen sizes.
 - Refactored focus management:
   - Removed all RawKeyboardListener usage.
   - Introduced FocusTraversalGroup for structured focus navigation using the Tab key.

![image](https://github.com/user-attachments/assets/cbd9868b-2837-4aa1-be25-dc770ebc12f6)

![image](https://github.com/user-attachments/assets/5eeec398-e373-40d9-9744-483115428344)

### ✅ Conclusion Summary:
This update enhances the dashboard settings module with structured, group-wise visibility controls and improved UI responsiveness. Focus management is now cleaner and more intuitive using FocusTraversalGroup, eliminating the need for RawKeyboardListener. These changes collectively improve maintainability, user experience, and adaptability across devices.



