Cluck o' Clock - Egg Timer App 🐣 
===================
Tired of guessing when your eggs are perfectly cooked? Meet **Cluck o' Clock** – the pixel-perfect timer that hatches precision into every egg dish!
<br>
**Cluck o’ Clock** is a  desktop application built with **Electron**, designed to add joy and precision to your egg-cooking. Whether you're a breakfast enthusiast or a culinary beginner, this delightful app helps you time your eggs—**hard-boiled**, **fried**, **soft-boiled**, or **scrambled** eggactly on time.

Featuring a cute **pixelated interface**, **animated art**, and **sound effects**, Cluck o’ Clock brings fun to your kitchen routine. it ensures your eggs are cooked *"eggactly"* right—every time.



## **Features**

- **4 Egg Cooking Modes**:
  - **Soft Boiled** – 5 minutes  
  - **Hard Boiled** – 10 minutes  
  - **Fried Egg** – 3 minutes  
  - **Scrambled** – 4 minutes  
-  sound effects  
-  egg hatching animation  
-  pixel art design  
-  countdown timer  
-  Completion notification  


Screenshots
-----------

![image](https://github.com/user-attachments/assets/513ca111-494f-47a0-beee-ad838aaffa63)
![image](https://github.com/user-attachments/assets/bff48a46-5f8b-459c-afd0-2470b999a375)
![image](https://github.com/user-attachments/assets/ce0e4a6f-2d41-4bb5-98fa-42be5b9658eb)
![image](https://github.com/user-attachments/assets/26c2dee7-08e2-4afa-acad-6dbdb467fc9f)





Prerequisites
-------------

Before you begin, ensure you have the following installed:

-   [Node.js](https://nodejs.org/) (v14 or higher recommended)
-   [npm](https://www.npmjs.com/) (comes with Node.js)
-   [Git](https://git-scm.com/) (optional, for cloning the repository)

Installation
------------

1.  **Clone the Repository** (or download the ZIP file):

    ```
    git clone https://github.com/abhiramiramadas/clucko-clock.git
    cd clucko-clock

    ```

2.  **Install Dependencies**:

    ```
    npm install

    ```

3.  **Run the App**:

    ```
    npm start

    ```

Usage
-----

1.  **Start Page**: Launch the app to see the start page. Click the "Start" button to begin.
2.  **Menu Page**: Choose your egg type (e.g., Hard Boiled, Fried Egg). Each option has a pre-set cooking time.
3.  **Timer Page**: Watch the timer count down with a cute chick animation.
4.  **Ending Page**: When the timer finishes, you'll hear a sound and see an egg animation. Choose "Snooze" to add 1 more minute or "Done" to return to the start page.

File Structure
--------------

-   `index.js`: Main Electron process script to create the window and handle navigation.
-   `preload.js`: Preload script for secure IPC communication between renderer and main processes.
-   `startpage.html`: Start page with the initial welcome screen.
-   `menupage.html`: Menu page for selecting egg types.
-   `timerpage.html`: Timer page with countdown and pause/resume functionality.
-   `endingpage.html`: Ending page shown when the timer completes.
-   `styles.css`: Consolidated CSS file for styling all pages.
-   `assets/`: Folder containing images (e.g., `bg.png`, `chick1.png`, `egg1.png`) and audio files (`click.wav`, `timer.wav`).

Project Details
---------------
## 🛠Techstack
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=for-the-badge&logo=electron&logoColor=9FEAF9)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Creative Tools
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![LibreSprite](https://img.shields.io/badge/LibreSprite-642CA9?style=for-the-badge&logo=aseprite&logoColor=white)

### Design System
**Typography**  
[![Pixelify Sans](https://img.shields.io/badge/Font-Pixelify_Sans-FFE979?style=flat-square&logo=google-fonts&logoColor=white)](https://fonts.google.com/specimen/Pixelify+Sans)

**Color Palette**  
<img src="https://img.shields.io/badge/FFE979-Sunny_Yellow?style=for-the-badge&color=FFE979"/>  <img src="https://img.shields.io/badge/F8BA03-Golden_Orange?style=for-the-badge&color=F8BA03"/>  <img src="https://img.shields.io/badge/F47730-Accent_Orange?style=for-the-badge&color=F47730"/>  <img src="https://img.shields.io/badge/512B22-Dark_Brown?style=for-the-badge&color=512B22"/>


**Design Process**  
- **UI/UX mockups**: created in [Figma](https://figma.com)  
- **Code implementation**: using Figma Dev Mode
- **Assets**: Pixel art crafted in LibreSprite
- **Animation**: Sprite sheets exported as PNG sequences

Contributing
------------

Contributions are welcome! If you'd like to contribute:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature`).
3.  Make your changes and commit (`git commit -m "Add your feature"`).
4.  Push to your branch (`git push origin feature/your-feature`).
5.  Open a pull request.

License
-------

This project is licensed under the MIT License - see the [LICENSE](https://grok.com/chat/LICENSE) file for details.

Acknowledgments
---------------

-   Built with [Electron](https://www.electronjs.org/) for cross-platform desktop app development.
-   Fonts provided by [Google Fonts](https://fonts.google.com/).
-   Inspired by the joy of cooking eggs perfectly!

* * * * *

