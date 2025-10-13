# Sticky Notes App

A simple, web-based sticky notes application that allows you to create, edit, and organize digital notes with Markdown-style formatting support.

Suitable only for desktop browsers.

## Features

- Create draggable and resizable sticky notes
- Markdown-style text formatting
- Interactive checkboxes for task lists
- Customizable app title
- Automatic saving to browser storage
- Clean, intuitive interface

## Getting started

Open the HTML file in any modern web browser to start using the app. No installation or setup required.

## How to use

### Creating notes

- Click the **+** button in the top-right corner to create a new sticky note
- New notes appear with default text that you can immediately edit

### Editing notes

- **Single-click** anywhere in a note's text area to enter edit mode
- The note will show a distinct shadow when in edit mode
- **Ctrl+Enter** (Windows/Linux) or **Cmd+Enter** (Mac) to save and exit edit mode
- **Click outside** the note to automatically save and exit edit mode

### Moving and resizing notes

- **Drag** the yellow header bar to move notes around the canvas
- **Drag** the small resize handle in the bottom-right corner to resize notes
- Notes automatically come to the front when clicked

### Deleting notes

- Hover over a note to reveal the **×** button in the top-right corner
- Click the **×** button and confirm deletion in the dialog

### Customizing the app

- Click the **settings** button (gear icon) in the top-left corner to change the app title

## Markdown-style formatting

The app supports several Markdown-style formatting options:

### Text Formatting

- **Bold text**: Wrap text in double asterisks `**bold text**`
- **Monospace text**: Wrap text in backticks `` `code text` ``

### Interactive Checkboxes

Create task lists with clickable checkboxes:

- **Unchecked**: `- [ ] Task to do`
- **Checked**: `- [x] Completed task`

Checkboxes can be toggled by clicking them in view mode.

### Example note content

```
**My Task List**

- [ ] Buy groceries
- [x] Walk the dog
- [ ] Review `project.js` code

Use **bold** for emphasis and `backticks` for code.
```

## Data storage

### Automatic saving

- All notes are automatically saved as you create, edit, move, or resize them
- No manual save action is required
- Changes are saved instantly when exiting edit mode

### Storage Location

⚠️ **Important**: All note content is stored in your browser's localStorage. This means:

- Notes are only available in the specific browser where they were created
- **Notes will be permanently lost if you clear your browser's data/cache**
- Notes are not synchronized across different browsers or devices
- Consider backing up important notes by copying the text elsewhere

### Backup Recommendations

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
- **Cross-platform**: Works on Windows, Mac, Linux, and mobile devices

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

## Development

This application was created using AI assistance to demonstrate modern web development practices including:
- CSS custom properties for theming
- Template-based DOM manipulation
- Event delegation and optimization
- Progressive enhancement techniques

## Changelog

1.0.1 - Added keyboard shortcut to create a sticky note - `Command`/`Control` + `.`

1.0.0 - Initial release

## Contributing

Contributions are welcome! Please ensure any changes maintain compatibility with the GPL-3.0 license.

## Troubleshooting

### Notes not saving
- Ensure JavaScript is enabled in your browser
- Check that localStorage is available (not in private/incognito mode)
- Verify sufficient storage space is available

### Performance issues
- Consider reducing the number of notes if performance degrades
- Close and reopen the browser if memory usage seems high

### Formatting not working
- Ensure you're using the correct Markdown syntax
- Double-check that text is properly wrapped in formatting characters
- Try refreshing the page if formatting appears broken

---

*Last updated: 2025*