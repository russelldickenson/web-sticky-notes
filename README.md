# Sticky Notes App

A simple, web-based sticky notes application that allows you to create, edit, and organize digital
notes with Markdown-style formatting support.

Suitable only for desktop browsers.

## Features

- Create draggable and resizable sticky notes.
- Limited content styling (bold and bullet points).
- Automatic saving to browser storage.
- Clean, intuitive interface.
- Light and dark theme.

## Getting started

Open the HTML file in any modern web browser to start using the app. No installation or setup
required.

> [!NOTE]
> All notes are stored in your browser's local storage. To use multiple copies of this app, add
> this to the end of the URL - `?board=<name>`. For example, to have one copy for personal notes and
> another for work note, you would add `?board=personal` to the personal copy and `?board=work` to
> the work copy.

## How to use

### Create a note

To create a new note, select the **+** button in the top-right corner.

### Edit a note

Single click** anywhere in a note's text area to enter edit mode. Click outside to exit edit mode.
The note's content is saved automatically.

### Move and resize a note

- **Drag** the yellow header bar to move notes around the canvas.
- **Drag** the small resize handle in the bottom-right corner to resize notes.
- Notes automatically come to the front when clicked.

### Delete a note

1. Hover over a note to reveal the **×** button in the top-right corner.
2. Click the **×** button and confirm deletion.

## Content formatting

The app supports on plain text.

### Example note content

```
My Task List

- Buy groceries
- Walk the dog
- Review project.js code
```

## Data storage

### Automatic saving

- All notes are automatically saved as you create, edit, move, or resize them.
- No manual save action is required.
- Changes are saved instantly when exiting edit mode.

### Storage location

⚠️ **Important**: All note content is stored in your browser's localStorage. This means:

- Notes are only available in the specific browser where they were created
- **Notes will be permanently lost if you clear your browser's data/cache**
- Notes are not synchronized across different browsers or devices
- Consider backing up important notes by copying the text elsewhere

### Backup recommendations

For important notes, consider:
- Copying text to a separate document
- Taking screenshots

## Browser compatibility

This app works in all modern web browsers that support:
- HTML5
- CSS3
- ES6 JavaScript
- localStorage API

## Technical Details

- **Single-file application**: Everything contained in one HTML file
- **No external dependencies**: Works offline without internet connection
- **Responsive design**: Adapts to different screen sizes

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

## Changelog

### 2.0.1

Added a favicon.

### 2.0.0

Completely rewritten by using Google Gemini.

### 1.1.1

- Fixed an issue where the size of manually resized notes was not being saved to local storage.

### 1.1.0

- Complete rewrite

### 1.0.1

- Added keyboard shortcut to create a sticky note - `Command`/`Control` + `.`

### 1.0.0

- Initial release

## Contributing

Contributions are welcome! Please ensure any changes maintain compatibility with the GPL-3.0 license.

## Troubleshooting

### Notes not saving
- Ensure JavaScript is enabled in your browser
- Check that localStorage is available (not in private/incognito mode)
- Verify sufficient storage space is available

### Formatting not working
- Ensure you're using the correct formatting syntax
- Double-check that text is properly wrapped in formatting characters
- Try refreshing the page if formatting appears broken
