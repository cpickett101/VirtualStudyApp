# Virtual Flashcard Application

A web-based flashcard application for studying concepts and other subjects. This application allows users to create, import, and study flashcards with an interactive interface.

![Flashcard App Screenshot](https://raw.githubusercontent.com/cpickett101/VirtualStudyApp/main/Virtual_Flashcard.png)

## Features

- **Interactive Flashcards**: Click to flip between question and answer
- **Category Filtering**: Focus on specific categories or study all cards
- **Multiple Import Formats**:
  - Markdown with "Front/Back" format
  - CSV with column headers
  - JSON structured data
- **Template Downloads**: Get sample templates to create your own flashcards
- **Character Encoding Fixes**: Automatically corrects common encoding issues
- **Responsive Design**: Works on desktop and mobile devices
- **No Installation Required**: Single HTML file with no dependencies

## How to Use

### Quick Start

1. Download the `index.html` file
2. Open it in any modern web browser
3. Begin studying with the included sample cards or import your own

### Studying Cards

- Click on a card to flip between question and answer
- Use "Previous" and "Next" buttons to navigate between cards
- Select a specific category from the dropdown menu
- Click "Shuffle" to randomize the card order

### Importing Custom Cards

1. Select your preferred format (Markdown, CSV, or JSON)
2. Click "Get Template" to download a sample file in that format
3. Edit the template with your own content
4. Click "Import New" and select your file

## File Formats

### Markdown Format

```markdown
# Flashcard Set Title

## Category Name

### Subcategory Name
**Front:** What is your question?
**Back:** This is the answer to your question.

**Front:** Another question?
**Back:** Another answer.
```

### CSV Format

```csv
front,back,category,subcategory
"What is your question?","This is the answer.","Category Name","Subcategory Name"
"Another question?","Another answer.","Category Name","Subcategory Name"
```

### JSON Format

```json
[
  {
    "front": "What is your question?",
    "back": "This is the answer.",
    "category": "Category Name",
    "subcategory": "Subcategory Name"
  },
  {
    "front": "Another question?",
    "back": "Another answer.",
    "category": "Category Name",
    "subcategory": "Subcategory Name"
  }
]
```

## Technical Details

The application is built using:
- HTML5
- CSS3 with Tailwind CSS
- JavaScript with React
- No server or build process required

All dependencies are loaded from CDN:
- React and ReactDOM
- Babel for JSX transformation
- Lodash for utility functions
- PapaParse for CSV parsing

## Deployment

### GitHub Pages

1. Fork this repository
2. Go to Settings > Pages
3. Select your main branch as source
4. Your app will be available at `https://[your-username].github.io/[repo-name]/`

### Local Server

For testing or development:

```bash
# Using Python
python -m http.server

# Using Node.js
npx serve
```

Then open `http://localhost:8000` or the URL shown in your terminal.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for new features or bug fixes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE]([LICENSE.md]) below for details.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Developer

[Created by Christopher Pickett - 2025]([https://www.linkedin.com/in/christopher-p-a4908979/])

