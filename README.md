# ALX Listing App

---

## About the Project

The ALX Listing App project aims to scaffold and lay the foundational structure for a modern Airbnb clone. This initial milestone focuses on setting up a well-organized and scalable codebase using **Next.js**, **TypeScript**, **TailwindCSS**, and **ESLint**. By establishing a clean folder structure, reusable components, and adhering to best practices, the project ensures a solid starting point for building a dynamic, responsive, and user-friendly property listing page.

---

## Learning Objectives

This milestone is designed for professional developers to strengthen their expertise in modern web application development. By completing this milestone, learners will:

* Gain hands-on experience scaffolding a Next.js project tailored for production readiness.
* Implement TypeScript for type safety and reusable interfaces to enhance code maintainability and robustness.
* Configure TailwindCSS for building responsive, accessible, and visually appealing UI components.
* Structure a Next.js project following industry-standard best practices, ensuring scalability and readability.
* Create foundational reusable components and organize assets effectively for real-world applications.

---

## Project Structure

This project is organized to promote a clean, scalable, and maintainable codebase. Here's an overview of the key directories and their purposes:

* **`components/`**: This directory houses all the **reusable UI components** for the application. You'll find things like `Card.tsx` for displaying property information and `Button.tsx` for interactive elements, promoting reusability and consistency. Specifically:
    * `components/common/Card.tsx`: Defines a reusable `Card` component for displaying property details.
    * `components/common/Button.tsx`: Defines a reusable `Button` component for various actions (e.g., "Book Now", "Details").

* **`interfaces/`**: This folder is dedicated to **TypeScript interfaces**. The `index.ts` file within defines the shapes of data structures and component props (like `CardProps` and `ButtonProps`), ensuring strong type-checking and improving code maintainability.

* **`constants/`**: In this directory, you'll find `index.ts`, which stores application-wide **constants**. This includes things like API URLs, configuration settings, or static text, making them easy to manage and access throughout the project.

* **`public/assets/`**: This directory is where **static assets** like images, fonts, or other media files that need to be publicly accessible are stored.

---

## Getting Started

To get the ALX Listing App up and running on your local machine, follow these simple steps:

1.  **Install Dependencies**:
    Open your terminal in the project's root directory and run the following command to install all the necessary packages and libraries:
    ```bash
    npm install
    ```

2.  **Run the Development Server**:
    Once the dependencies are installed, you can start the development server. This will compile the project and make it accessible in your web browser, typically at `http://localhost:3000`:
    ```bash
    npm run dev
    ```

---