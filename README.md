# AI Resume Analyzer

This project is a web application that analyzes resumes using AI. It provides features like ATS-friendliness checks, keyword analysis, and a summary of the resume's content.

## Demo

https://github.com/user-attachments/assets/d8b921af-2e45-4c6b-9fe3-aac64d83359f

## Features

*   **Resume Upload:** Users can upload their resumes in PDF format.
*   **ATS-Friendliness Score:** The application provides a score indicating how well the resume is optimized for Applicant Tracking Systems (ATS).
*   **Keyword Analysis:** It checks for the presence of important keywords relevant to the job description.
*   **Resume Summary:** The tool generates a concise summary of the resume.
*   **Detailed Analysis:** Provides a detailed breakdown of the resume's strengths and weaknesses.

## Getting Started

### Prerequisites

*   Node.js (v20 or later)
*   npm

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/adilzhanY/ai-cv-analyzer.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd ai-cv-analyzer
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the Application

To run the application in development mode, use the following command:

```bash
npm run dev
```

This will start the development server, and you can view the application at `http://localhost:5173`.

To build the application for production, use the following command:

```bash
npm run build
```

To start the production server, use the following command:

```bash
npm run start
```

## Technologies Used

*   **React:** A JavaScript library for building user interfaces.
*   **React Router:** For handling routing in the application.
*   **Vite:** A fast build tool and development server.
*   **TypeScript:** A typed superset of JavaScript.
*   **Tailwind CSS:** A utility-first CSS framework.
*   **Zustand:** A small, fast, and scalable state management solution for React.
*   **PDF.js:** A library for parsing and rendering PDF files.

## Project Structure

The project is organized into the following directories:

*   `app/`: Contains the main application logic, including components, routes, and utility functions.
*   `constants/`: Contains constant values used throughout the application.
*   `public/`: Contains static assets like images and icons.
*   `types/`: Contains TypeScript type definitions.
