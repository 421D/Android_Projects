# Daily Finance App（今日理财资讯）


### Project Overview
This is an **Android finance management application** developed using **Java** in **Android Studio**. The app allows users to view a list of financial items, add new entries, and manage displayed content. It features a **splash screen**, **data-driven main interface**, and interactive UI components.  

Key features:  
- Splash screen with a short launch animation/video  
- Main interface displays items with **image, title, and description** in a list  
- Add new entries dynamically through input fields at the top of the main interface  
- Local JSON-based data storage for content persistence  





### Libraries & Tools
- **Java 8+**: Core programming language  
- **Android Studio**: IDE and build tools  
- **Android SDK**: For UI components and system integration  
- **RecyclerView**: Display lists efficiently  
- **JSON**: Local data storage and retrieval  
- **MediaPlayer**: Play MP4 video for splash screen  



### Technical Details
- **Activities & UI Flow**:  
  - `SplashActivity` → short video splash screen  
  - `MainActivity` → main dashboard, list display, data entry  
  - `XianshiActivity` → additional display/activity for detailed view or other content  
- **Data Management**:  
  - `DayData.java` defines the data model  
  - JSON file stores financial entries, loaded at app start  
  - Adding a new entry updates the list in real-time  
- **Layouts**:  
  - XML layout files separate UI from logic  
  - Includes responsive design for multiple screen densities  
- **Resource Management**:  
  - `drawable` folders store icons, images  
  - `mipmap` folders store app launcher icons for various screen densities  
  - `values` folders manage strings, colors, dimensions  


### Notes
Originally developed during undergraduate study. 
Project no longer actively maintained.
