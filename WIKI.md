# Project Summary

The AI Image Background Remover Pro is an advanced web application that leverages AI technology to help users efficiently remove backgrounds from their images. This innovative tool is designed for a variety of users, including e-commerce platforms, social media managers, and graphic designers, seeking to enhance the visual appeal of their products and images. The application allows users to upload images, apply background removal with customizable settings, and download the processed images, thus streamlining the workflow and improving productivity. With multiple options for backgrounds and enhanced interaction through a user-friendly interface, it addresses the needs of users looking for both efficiency and quality in image processing.

---

# Project Module Description

## Functional Modules

1. **Image Uploading**: Users can upload their images using a simple drag-and-drop interface or through a file selection dialog.

2. **Background Removal**: Utilizes a powerful AI algorithm to detect and eliminate backgrounds from images, providing options for precision and edge smoothing.

3. **Image Preview**: Displays side-by-side comparisons of the original and processed images, allowing users to assess the quality of background removal.

4. **Download Functionality**: Users can easily download the processed images once background removal is complete.

5. **User Accounts**: Supports user authentication, enabling tracking of processed images and settings.

6. **Background Options**: Users can select different backgrounds (transparent, solid colors, gradients) for their images directly within the application.

7. **Settings Control**: Users can adjust image processing settings, such as precision and edge smoothing, through an intuitive control panel.

---

# Directory Tree

```bash
/data/chats/oa4si/workspace
+-- ai_tshirt_background_removal_class_diagram.mermaid
+-- ai_tshirt_background_removal_sequence_diagram.mermaid
+-- ai_tshirt_background_removal_system_design.md
+-- background_removal_feature_prd.md
+-- react_template
|   +-- README.md
|   +-- WIKI.md
|   +-- eslint.config.js
|   +-- index.html
|   +-- package.json
|   +-- postcss.config.js
|   +-- src
|   |   +-- App.jsx
|   |   +-- components
|   |   |   +-- BackgroundRemover.jsx
|   |   |   +-- ControlPanel.jsx
|   |   |   +-- ImagePreview.jsx
|   |   |   +-- LanguageSelector.jsx
|   |   +-- hooks
|   |   |   +-- useBackgroundRemoval.js
|   |   +-- index.css
|   |   +-- main.jsx
|   |   +-- services
|   |   |   +-- ImageProcessor.js
|   |   +-- utils
|   |       +-- LanguageContext.jsx
|   |       +-- imageUtils.js
|   |       +-- translations
|   |           +-- en.js
|   |           +-- zh.js
|   +-- tailwind.config.js
|   +-- template_config.json
|   +-- test-import.js
|   +-- vite.config.js
+-- uploads
    +-- 截屏2025-03-01 12.56.19.png
    +-- 截屏2025-03-01 13.42.16.png
    +-- 截屏2025-03-01 13.47.21.png
    +-- 截屏2025-03-01 18.05.08.png
    +-- 截屏2025-03-01 18.05.12.png
    +-- 截屏2025-03-02 12.37.59.png
```

---

# File Description Inventory

- **ai_tshirt_background_removal_class_diagram.mermaid**: Class diagram of the project.
- **ai_tshirt_background_removal_sequence_diagram.mermaid**: Sequence diagram outlining the interactions.
- **ai_tshirt_background_removal_system_design.md**: Documentation of system architecture and design decisions.
- **background_removal_feature_prd.md**: Product requirements document detailing features and specifications.
- **react_template/**: Contains the main project files including source code.
  - **src/**
    - **App.jsx**: Main application component.
    - **components/**: Contains reusable components such as BackgroundRemover, ControlPanel, ImagePreview, LanguageSelector.
    - **hooks/**: Contains custom hooks for business logic.
      - **useBackgroundRemoval.js**: Hook for handling background removal functionality.
    - **services/**: Contains services for image processing.
      - **ImageProcessor.js**: Service responsible for processing images.
    - **utils/**: Utility functions including language management and image utilities.
    - **index.css**: Global styles for the application.
  - **package.json**: Manages project dependencies and scripts.
  - **vite.config.js**: Configuration file for Vite.
  - **tailwind.config.js**: Configuration file for Tailwind CSS.

---

# Technology Stack

- **React**: JavaScript library for building user interfaces.
- **Vite**: Build tool that enhances the development experience with fast reloading.
- **Tailwind CSS**: Utility-first CSS framework for styling components.
- **JavaScript**: Provides application logic.
- **HTML**: Markup language for structuring web pages.

---

# Usage

### Installation

1. Install dependencies:
   ```bash
   pnpm install
   ```

### Development

1. Start the development server:
   ```bash
   pnpm run dev
   ```

### Building

1. Build the project:
   ```bash
   pnpm run build
   ```

### Running Tests

1. Lint source files:
   ```bash
   pnpm run lint
   ```



# INSTRUCTION
- Project Path:`/data/chats/oa4si/workspace/react_template`
- You can search for the file path in the 'Directory Tree';
- After modifying the project files, if this project can be previewed, then you need to reinstall dependencies, restart service and preview;
