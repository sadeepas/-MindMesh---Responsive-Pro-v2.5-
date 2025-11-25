# -MindMesh---Responsive-Pro-v2.5-
MindMesh is a comprehensive, browser-based spinning wheel application designed for interactive events, classrooms, giveaways, and decision-making.

# MindMesh - Responsive Pro (v2.5)

MindMesh is a comprehensive, browser-based spinning wheel application designed for interactive events, classrooms, giveaways, and decision-making. It's built as a single, self-contained HTML file, requiring no server or build steps. All your data—wheel entries, users, and history—is saved directly in your browser via IndexedDB, ensuring privacy and offline functionality.

## Description

This isn't just a simple spinning wheel. MindMesh is a full-featured application packed with tools for managing participants, tracking results, and customizing the experience. It was created to be a robust, all-in-one solution for any scenario that could benefit from a fair, engaging, and visually appealing random selector.

The core philosophy is "Spin, Solve, and Succeed." Users can spin the wheel to select an item, start a timed challenge for a participant, and track their success over time. This v2.5 "Responsive Pro" release focuses heavily on a polished, mobile-first user experience and a more streamlined workflow.

## ✨ Features

MindMesh is packed with features that go far beyond a basic spinning wheel.

#### 🎡 Core Wheel Functionality
*   **Weighted Entries:** Give certain items a higher chance of being selected by adjusting their "weight".
*   **Enable/Disable Items:** Easily toggle items on or off the wheel without deleting them.
*   **"Remove on Win" Option:** Automatically removes an item from the wheel after it has been won, with the option to restore it later.
*   **Customizable Spin Duration:** Set the spin duration in the settings for faster or more dramatic reveals.
*   **Advanced Animations:** Smooth, physics-based `ease-out-quint` animation for the wheel spin and a bouncing pointer for a more dynamic feel.

#### 💎 UI & UX Enhancements (New in v2.5)
*   **Polished Loading Screen:** A clean, animated loading screen ensures a smooth and professional application startup.
*   **Modern Floating Navigation:** A redesigned, floating navigation bar at the bottom of the screen is more intuitive, accessible, and mobile-friendly, with support for iPhone safe areas.
*   **Adaptive Modals:** All modal windows (like the Control Panel and editors) now intelligently resize on smaller screens, using available height and enabling internal scrolling for a seamless mobile experience.
*   **Searchable Participant Selection:** The "Start Challenge" form has been completely redesigned with a searchable dropdown, making it effortless to find a participant even in a long list. It also includes a streamlined flow for adding new users on the fly.

#### 💾 Data Persistence & Management
*   **Browser-Based Storage:** All data (items, users, history, settings) is saved in your browser's IndexedDB. No account or internet connection is required after the initial load.
*   **Import/Export JSON:** Backup your entire application state (all items, users, history, and settings) to a JSON file and import it later or on another device.
*   **Export to CSV:** Export your user list or challenge history to CSV files for easy use in spreadsheets.
*   **Full Control Panel:** A responsive grid view of all wheel items allows for quick editing and management.

#### 🏆 Challenge & History Mode
*   **Timed Challenges:** After the wheel lands on an item, you can start a timed challenge for a selected participant.
*   **User Management:** Maintain a list of participants, including their name, school/organization, status (active/inactive), and notes.
*   **Detailed History:** Every challenge is logged with the item number, participant, timestamp, and final status (solved, stopped, time's up).
*   **Statistics Dashboard:** View key statistics, including total attempts, number of solved challenges, and the most frequently landed-on items.

#### 🎨 Customization & Settings
*   **Custom Item Details:** Edit item numbers, descriptions, and add a custom image for each entry on the wheel.
*   **Color Themes:** Choose from multiple color themes (Indigo, Teal, Rose, Amber) to personalize the look and feel.
*   **Sound Effects:** Engaging sound effects for clicks, spins, and wins (can be disabled).
*   **Confetti Celebration:** A fun confetti explosion celebrates a successful spin (can be disabled).

## 🛠️ Technical Stack

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+ Classes)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) for a utility-first CSS workflow, embedded directly in the HTML for simplicity.
*   **Client-Side Storage:** [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) wrapped in a promise-based service for robust local data persistence.
*   **Architecture:** The application is built using an object-oriented approach with distinct classes for the main app logic (`MindMeshApp`), UI manipulation (`UIService`), database interactions (`DBService`), modal management (`ModalService`), and event handling (`Handlers`).

## 🚀 How to Use

No installation is needed!

1.  Download the `puzzel.html` file.
2.  Open it with any modern web browser like Chrome, Firefox, Edge, or Safari.
3.  That's it! The application will initialize, create its local database, and be ready to use.

## 👨‍💻 Author

*   **Sadeepa Lakshan**
*   **GitHub:** [https://github.com/sadeepas](https://github.com/sadeepas)
