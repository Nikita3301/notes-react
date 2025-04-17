# Notes React App

A simple yet powerful note-taking application built with React. This application allows users to create, edit, and manage notes with Markdown support.

## Features

- Create and edit notes with Markdown support
- Live preview of Markdown formatting
- Local storage persistence
- Responsive split-pane interface
- Simple and intuitive UI

## Technologies Used

- React
- Vite
- React Split
- React MDE (Markdown Editor)
- Showdown (Markdown converter)
- Nanoid (for unique IDs)

## Installation

1. Clone this repository
   ```bash
   git clone https://github.com/Nikita3301/notes-react.git
   ```

2. Navigate to the project directory
   ```bash
   cd notes-react
   ```

3. Install dependencies
   ```bash
   npm install
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

## Usage

- Click the "+" button to create a new note
- Select a note from the sidebar to edit it
- Use Markdown syntax in the editor to format your notes
- Notes are automatically saved to local storage

## Markdown Features

This editor supports various Markdown features:

- **Bold** and *italic* text
- # Headers of different levels
- Lists (ordered and unordered)
- [Links](https://example.com)
- Code blocks
- Tables
- And more!

## Build for Production

```bash
npm run build
```

This will generate a `dist` folder with optimized production files.

## Preview Production Build

```bash
npm run preview
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
