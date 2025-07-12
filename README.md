# Random Name Picker

A beautiful, mobile-friendly web application for randomizing lists of names. Perfect for classroom activities, team selections, giveaways, or any situation where you need to randomly order a list of participants.

## Features

### 🎯 Core Functionality
- **Easy Name Management**: Click any name to edit it directly
- **Random Ordering**: Click RANDOMIZE to shuffle names into a random order
- **Visual Results**: Each name gets a unique color that persists through randomization
- **Add/Remove Names**: Easily add new names or remove existing ones (minimum 2 required)

### 🎨 Customization
- **6 Beautiful Themes**: Light, Dark, Ocean, Sunset, Forest, and Purple
- **Background Images**: Add custom background images via URL
- **20 Unique Colors**: Names cycle through 20 different colors for easy identification
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop

### 📤 Import/Export
- **Import Names**: Upload .txt or .csv files with your name lists
- **Smart CSV Parsing**: Automatically detects headers and finds name columns
- **Export to CSV**: Download your randomized results as a CSV file
- **Share on Twitter/X**: Share your randomized list directly to social media

### 💾 Data Persistence
- All names are automatically saved to your browser
- Theme preferences are remembered
- No account or login required

## How to Use

### Getting Started
1. Open `randname-v1.5.0.html` in any modern web browser
2. You'll see 10 default entries (Name 1, Name 2, etc.)
3. Click any name to edit it
4. Click "Add a Name" to add more entries

### Randomizing Names
1. Click the **RANDOMIZE** button to shuffle the names
2. Results appear below with position numbers
3. Each name keeps its original color for easy tracking

### Importing Names
1. Click the cloud upload icon (↓) in the header
2. Select a .txt or .csv file
3. Supported formats:
   - **Text files**: One name per line or comma-separated
   - **CSV files**: Automatically detects the name column

### Settings
1. Click the gear icon (⚙️) to open settings
2. Options available:
   - Change number of names (2-100)
   - Select a theme
   - Add a background image URL
   - Edit individual names
   - Remove names (X button)

### Sharing & Exporting
After randomizing:
- **Share on Twitter**: Creates a formatted tweet with your list
- **Export CSV**: Downloads a CSV file with positions and names

### Clearing the List
- Click the **CLEAR** button to reset everything
- You'll be asked to confirm before clearing

## File Formats

### Text File Import (.txt)
```
John Doe
Jane Smith
Bob Johnson
```
Or comma-separated:
```
John Doe, Jane Smith, Bob Johnson
```

### CSV File Import (.csv)
The app intelligently detects name columns:
```csv
ID,Name,Score
1,John Doe,95
2,Jane Smith,87
```

## Technical Details

- **No Installation Required**: Just open the HTML file
- **No Internet Required**: After initial load, works offline
- **Privacy**: All data stored locally in your browser
- **Cross-Platform**: Works on any device with a modern browser

## Browser Compatibility

Works best on:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT License - Feel free to use and modify!

## Credits

Created by EVOKNOW | [Visit Website](https://evoknow.com)

---

**Version**: 1.5.0  
**Last Updated**: 2025