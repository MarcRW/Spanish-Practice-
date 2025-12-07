# Spanish Practice App - README

## 📚 About This App

This is a comprehensive Spanish learning app with multiple practice sections including conjugations, ser/estar, sentence completion, prepositions, direct/indirect objects, word order, flashcards, and a **writing practice section**.

Everything is contained in a **single HTML file** - no external dependencies needed!

## 🚀 How to Use

### Option 1: Open Directly
Just double-click the `index.html` file and it will open in your browser.

### Option 2: Host on GitHub Pages
1. Fork or clone this repository
2. Go to Settings → Pages
3. Select your main branch as source
4. Your app will be live at: `https://yourusername.github.io/Spanish-Practice-/`

### Option 3: Download and Customize
1. Download the `index.html` file
2. Open it in any text editor (VS Code, Sublime, even Notepad)
3. Customize the content, colors, exercises
4. Save and open in browser

## ✍️ Writing Practice Section Features

### For Students:
- **Write freely** with Spanish accent keyboard built-in
- **Auto-saves** every 2 seconds (no more lost work!)
- **Save as New** to start a fresh piece
- **Load** previous work to continue editing
- **Copy to Clipboard** to paste elsewhere
- **Download as .txt** to save to computer
- **Delete Current** if you hate what you're working on

### For Teachers:
- Students can save multiple pieces of writing
- Each piece has a timestamp
- You can review directly in the app when meeting with student
- Click "Eliminar" after grading to remove from their list

## 🎨 Customization Ideas

### Add More Exercises
Find the data arrays in the `<script>` section:
- `irregularVerbs` - add more verb conjugations
- `serEstarExercises` - add more ser/estar examples
- `sentences` - add more fill-in-the-blank sentences
- `flashcards` - add more vocabulary

### Change Colors
The main colors are defined in CSS:
- Primary purple: `#667eea`
- Secondary purple: `#764ba2`
- Search for these in the `<style>` section to change

### Add New Sections
Follow the pattern of existing sections:
1. Add a nav button
2. Create a section div
3. Add the JavaScript functions
4. Update `showSection()` to load your content

## 💾 Data Storage

All saved writings are stored in the browser's **localStorage**:
- Persists between sessions
- Stored locally on the student's device
- Not sent to any server
- Survives browser refresh
- Cleared if browser data is cleared

## 🔧 How Editing Works

1. Student clicks "Cargar" on a saved piece
2. Text appears in the editor with status: "Editando trabajo de [date]"
3. As they type, it auto-saves every 2 seconds
4. The original saved piece is updated
5. They can:
   - Click "Guardar como Nuevo" to save current text as a separate new piece
   - Click "Eliminar Actual" to delete the loaded piece and start fresh
   - Click "Limpiar Texto" to clear the editor without deleting the saved piece

## 🔒 Privacy Note

This app runs entirely in the browser. No data is sent to any server. All student work is stored locally on their device only.

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - no frameworks
- **localStorage API** for data persistence
- **Responsive design** - works on mobile and desktop
- **Accent keyboard** - custom implementation for Spanish characters
- **Self-contained** - single file, no external dependencies

## 📝 Copyright & Usage

© 2024 Marc. All rights reserved.

This application and its contents are proprietary. Unauthorized copying, distribution, or commercial use is prohibited.


---

