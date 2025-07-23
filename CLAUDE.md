# Random Name Picker Project

## Project Overview
A single-page web application for randomizing lists of names with a mobile-friendly interface. Built with vanilla JavaScript, jQuery, and Tailwind CSS via CDN.

## Current Version
**v1.5.0** (filename: `randname-v1.5.0.html`)

## Technical Stack
- **HTML5** - Single file application
- **Tailwind CSS** (via CDN) - Styling and responsive design
- **jQuery 3.7.1** (via CDN) - DOM manipulation and event handling
- **LocalStorage** - Data persistence
- **No build process required** - Direct browser execution

## Features Implemented

### Core Features
1. **Name Management**
   - Default 10 entries (Name 1, Name 2, etc.)
   - Click-to-edit functionality on name cards
   - Add new names via "Add a Name" button
   - Automatic camelCase formatting (e.g., "john doe" → "JohnDoe")
   - Minimum 2 names enforced

2. **Visual Design**
   - 20 unique colors cycling for name backgrounds
   - Responsive grid layout (1-4 columns based on screen size)
   - Hover tooltips on name cards
   - Smooth transitions and animations

3. **Randomization**
   - Randomizes name order on button click
   - Displays results in numbered pills with original colors maintained
   - Results shown in responsive grid layout

4. **Theme System**
   - 6 themes: Light, Dark, Ocean, Sunset, Forest, Purple
   - Custom CSS variables for theme colors
   - Background image support via URL
   - Persistent theme selection

5. **Import/Export**
   - Import from .txt and .csv files
   - Smart CSV parsing:
     - Skips numeric fields
     - Detects and skips headers
     - Finds first non-numeric column as name field
     - Handles quoted values properly
   - Export to CSV with position and name columns
   - Share on Twitter/X with formatted list

6. **Settings Modal**
   - Number input (2-100) with validation
   - Theme selector
   - Background image URL input
   - Name editor with color indicators
   - Remove individual names (minimum 2 required)

7. **Data Persistence**
   - Names saved to localStorage
   - Theme preference saved
   - Background image URL saved
   - Automatic loading on page refresh

8. **Additional Features**
   - CLEAR button with confirmation dialog
   - Dynamic copyright year
   - MIT License link
   - EVOKNOW company link

## Storage Keys
- `randomPickerNames` - Array of name strings
- `randomPickerTheme` - Theme name string
- `randomPickerBgImage` - Background image URL string

## Color Classes
Uses 20 predefined Tailwind colors cycling through indices:
- name-color-0 through name-color-19
- Colors range from red through purple, including grays

## Import Format Support
1. **Text Files (.txt)**
   - One name per line OR
   - Comma-separated names
   - Filters out numeric values

2. **CSV Files (.csv)**
   - Intelligent field detection
   - Header keyword detection: name, student, participant, member, etc.
   - Skips pure numeric columns
   - Takes first non-numeric field as name

## Name Processing Rules
1. Trim all whitespace
2. Convert to camelCase (capitalize first letter of each word)
3. Remove duplicates
4. Filter empty strings
5. Minimum 2 unique names required

## UI Components
- Header with app title and control buttons
- Main grid for name display
- Action buttons (RANDOMIZE, CLEAR)
- Results section with share/export buttons
- Settings modal
- Hidden file input for imports

## Future Considerations
- The app is designed to be extended easily
- All functionality is in a single file for portability
- No external dependencies beyond CDN resources
- Mobile-first responsive design
- Accessibility considerations with hover states and color contrast

## UI/UX Design Guidelines
- Input labels and input items (text box, dropdown, etc) need to be on their own line