# AI HR Assistant Blueprint

## Overview

This document outlines the design, features, and development plan for the AI-powered HR Assistant, "Vignesh." The application is a web-based chat interface that allows users to interact with a Gemini-powered AI to get answers to their HR-related questions.

## Implemented Features & Design

This section documents all the style, design, and features implemented in the application from the initial version to the current version.

### Core Architecture
- **Frameworkless Web App:** Built with modern, standard HTML, CSS, and JavaScript.
- **Modular JavaScript:** Uses ES Modules and event listeners for clean, organized code.
- **AI Integration:** Connects to the Google Gemini API for natural language processing and responses.
- **System Prompt Engineering:** A detailed system prompt guides the AI ("Vignesh") to adopt the correct tone and provide accurate information based on the user's query context (casual vs. professional).

### Visual Design & UI
- **Modern & Clean UI:** A visually balanced layout with clean spacing and polished styles.
- **Theming:** Supports light and dark modes, along with accent color customization (teal, purple, blue) using CSS variables.
- **Responsive Layout:** The interface is designed to be responsive and work on different screen sizes.
- **Loading Indicator:** A "typing" animation provides visual feedback to the user while the AI is generating a response, improving the user experience.
- **Subtle Textures & Shadows:** The main background has a subtle noise texture, and cards have soft, deep shadows to create a sense of depth and a premium feel.

### Chat Interface Features
- **Real-time Messaging:** A familiar chat interface for user and AI interactions.
- **Smooth Scrolling:** The chat window automatically scrolls smoothly to the latest message, ensuring the most recent part of the conversation is always in view.
- **Auto-Expanding Text Area:** The input text area dynamically resizes based on the content.
- **Character Counter:** Provides users with feedback on their message length.
- **Clear Input Button:** Allows users to quickly clear the text area with a single click.
- **Send on Enter:** Users can send messages by pressing the "Enter" key.

## Current Development Plan

This section outlines the plan and steps for the current requested change: **"check the over all code 'all code'. and make it working make it usefull"**.

### 1. Create `blueprint.md`
- **Action:** Create this `blueprint.md` file to document the project.
- **Status:** Completed.

### 2. Implement the Settings Page
- **Action:** Add UI elements (input field, save button) and corresponding JavaScript to `settings.html` to allow users to save their Gemini API Key to local storage.
- **Status:** Pending.

### 3. Enable Chat Persistence
- **Action:** Modify `chat.html` to save the conversation history to `sessionStorage` and restore it on page load.
- **Status:** Pending.

### 4. Improve Accessibility
- **Action:** Add `aria-label` attributes to icon-only buttons (`send-button`, `clear-button`) in `chat.html`.
- **Status:** Pending.

### 5. Clean Up Project Structure
- **Action:** Rename `chat (1).html` to `chat.html` to maintain consistency with navigation links.
- **Status:** Pending.
