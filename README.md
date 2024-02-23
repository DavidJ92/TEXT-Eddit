# TEXT- EDDIT Text Editor with Offline Support

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)



## Introduction

This text editor is designed to provide users with a powerful yet simple tool for creating and editing text documents directly in their web browser. It leverages modern web technologies to offer a seamless experience, including offline support and data persistence using IndexedDB.

## Features

- **Text Editing**: Create, edit, and format text documents with ease.
- **Offline Support**: The application works even when offline, allowing users to continue working on their documents without an internet connection.
- **Progressive Web App**: The text editor meets the criteria for a Progressive Web App, enabling users to install it on their devices and access it like a native application.
- **Data Persistence**: Utilizes IndexedDB for storing and retrieving data, ensuring that documents are saved securely and reliably.
- **Cross-platform Compatibility**: Works on various devices and operating systems, providing a consistent experience across different platforms.

## Technologies Used

- HTML, CSS, JavaScript: For building the user interface and functionality of the text editor.
- IndexedDB: For data storage and retrieval within the browser.
- Service Workers: To enable offline support and provide a seamless user experience.
- Webpack: For bundling and managing dependencies.
- idb (IndexedDB Promised): A lightweight wrapper around the IndexedDB API for simplified database interactions.

## Installation

To install the text editor locally, follow these steps:

1. Clone the repository: git clone <repository-url>

2. Navigate to the project directory: cd text-editor

3. Install dependencies: npm install

4. Build the project: npm run build


5. Start the development server: npm start

6. Open the text editor in your web browser at `http://localhost:8080`.

## Usage

Once the text editor is running, you can perform the following actions:

- Create a new document by clicking on the "New Document" button.
- Edit the text content directly in the editor area.
- Format text using the provided toolbar options (e.g., bold, italic, underline).
- Save the document using the "Save" button.
- Access saved documents from the sidebar.
- Work offline without an internet connection, with changes automatically synced when online again.





