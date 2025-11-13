# MAST5112-PART3
# Project Setup and Installation Guide

Welcome to the Golden Pallete Resturant! Follow the steps below to set up and run the application locally. This README also includes the changelog for recent updates and refactoring.


## Setup Instructions

To get started with the project, follow these steps:

```bash
# Clone the repository
git clone github.com/ST10447475/MAST5112-PART3

# Navigate to the project directory
cd project_directory

# Install the dependencies
npm install
# Open the AddedItems.js file to ensure assets such as the chef hat icon are correctly linked


```
**Important**: Make sure all dependencies are installed before running the app.
*Note*: If you encounter any issues, feel free to open an issue.
---





## Changelog
Part 3 Changes (Refactoring and Updates)


### New Features:
- **Dark Mode Toggle**: Added a toggle button to switch between light and dark modes.
- **Add/Remove Menu Items**: Implemented functionality to dynamically add and remove items from the menu.
- **Password Protected Deletion**: Added password protection when deleting menu items (password: `1234`).

### Refactoring:
- **Code Structure**: Improved code modularity by separating concerns, especially in state management.
- **Optimized Rendering**: Enhanced performance by reducing unnecessary re-renders in the menu list using React hooks.
- **UI Updates**: Updated button styles and layout for better user experience, including clearer visual feedback on actions.

### Bug Fixes:
- **Asset Path Fixes**: Fixed issues with incorrect asset paths for images in the menu list (e.g., the chef hat icon).
- **State Management**: Corrected some issues where the state was not updating correctly when deleting or adding menu items.

---

## Styling Summary

This README utilizes various Markdown styles to ensure clarity and enhance the presentation:

- **Code Blocks**: Used to display commands or code snippets (e.g., `git clone`, `npm install`).
- **Headers**: Organize content into clearly defined sections (e.g., `## Setup Instructions`, `## Changelog`).
- **Bold Text**: Highlights important information such as warnings or key actions.
- **Italic Text**: Adds emphasis to specific details or notes.
- **Lists**: Both ordered and unordered lists for step-by-step instructions and features.
- **Blockquotes**: Used to emphasize important notes, warnings, or quotes.
- **Images**: Included to showcase visual elements of the project (e.g., the chef hat icon).
- **Task Lists**: Track completed and pending tasks for project progress.

---

## YouTube Link

[Click here to view the video tutorial](https://youtu.be/E2kv8KYJCZA)

