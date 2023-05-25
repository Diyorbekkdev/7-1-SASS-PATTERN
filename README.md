# Project Folder Structure

This project follows the 7-1 SASS pattern, a modular and efficient approach to organizing your stylesheets. The folder structure is designed to promote maintainability, reusability, and scalability. Here's an overview of each directory and file within this project:

## base
This directory contains global styles that are applied throughout the project. It includes resets, typography styles, and common styles that establish the foundation for the entire application.

## abstracts
The abstracts directory houses `mixins`, functions, and variables. These powerful tools enhance code efficiency and promote reusability. Mixins provide reusable snippets of CSS code, functions enable dynamic styling, and variables store commonly used values such as colors, font sizes, or breakpoints.

## components/
Each component in the project has its own file within this directory. By separating the styles of individual UI elements, it becomes easier to locate and update specific styles. This approach promotes modularity and reusability, allowing components to be used across different pages or sections of the application.

## layouts/
The layouts directory contains styles related to the overall layout structure of the application. Grid systems, headers, footers, and other structural elements reside here. Separating layout-specific styles into this directory ensures a consistent and organized approach to managing the visual arrangement of elements.

## pages/
For unique page styles, a separate file is created within the pages directory. This segregation allows for clean separation of page-specific styles from global or component styles. It ensures that styles remain focused and easily manageable, especially as the project expands with additional pages.

## themes/
If the project supports different themes or variations, such as light mode and dark mode, this directory is the home for theme-specific styles. Each theme has its own file, allowing for easy customization and theming of the application. Embrace your creativity and create distinct visual experiences for different themes within this directory.

## vendors/
When using third-party libraries or frameworks with their own stylesheets, it's important to keep them separate from your custom styles. The vendors directory serves as a dedicated space for storing these external stylesheets. By isolating them, you can maintain a clear distinction between custom styles and imported dependencies.

## _main.scss
The `main.scss` file acts as the entry point for your stylesheets. It serves as a central hub where all other partials are imported and compiled into a single CSS file. Importing partials from different directories, such as base, abstracts, components, layouts, pages, themes, and vendors, ensures that the final compiled CSS includes all the necessary styles for your project.



