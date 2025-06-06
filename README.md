# Datamuse API Integration

## Overview
A JavaScript application that integrates with the Datamuse API to provide word-related queries and linguistic analysis. This project demonstrates API integration, word processing, and web development with external data sources.

## Features
- **Datamuse API Integration**: Connects to the powerful Datamuse word-finding API
- **Word Queries**: Find words that match specific criteria
- **Linguistic Analysis**: Explore word relationships and meanings
- **Client-Side Processing**: Pure JavaScript implementation
- **Educational Tool**: Perfect for learning API integration

## Technologies Used
- **JavaScript (ES6+)** - Core application logic
- **Datamuse API** - Word and language data
- **HTML5** - Structure and markup
- **CSS3** - Styling and presentation
- **Fetch API** - HTTP requests

## Datamuse API Features
The Datamuse API provides:
- Words with similar meanings
- Words that rhyme
- Words that sound alike
- Words that often appear near each other
- Words with specific spelling patterns

## Getting Started

### Prerequisites
- Modern web browser with JavaScript support
- Internet connection for API access
- Text editor for development

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/oskarcode/datamuseapi.git
   cd datamuseapi
   ```

2. Open the HTML file in your browser:
   ```bash
   open index.html
   # or simply double-click the HTML file
   ```

## Usage

### API Query Examples
```javascript
// Find words that rhyme with "cat"
fetch('https://api.datamuse.com/words?rel_rhy=cat')

// Find words that mean similar to "happy"
fetch('https://api.datamuse.com/words?ml=happy')

// Find words that sound like "elephant"
fetch('https://api.datamuse.com/words?sl=elephant')

// Find words that often follow "hot"
fetch('https://api.datamuse.com/words?lc=hot')
```

### Query Parameters
- `ml=` - Words with similar meaning
- `rel_rhy=` - Words that rhyme
- `rel_nry=` - Words that nearly rhyme
- `sl=` - Words that sound like
- `sp=` - Words spelled like (supports wildcards)
- `lc=` - Words that come after
- `rc=` - Words that come before

## Project Structure
```
datamuseapi/
├── index.html          # Main HTML file
├── script.js           # JavaScript logic
├── style.css           # CSS styling
└── README.md           # This file
```

## Example Applications
- **Poetry Tools**: Find rhyming words for creative writing
- **Word Games**: Develop word-based games and puzzles
- **Language Learning**: Explore word relationships and meanings
- **Content Creation**: Enhance vocabulary and writing
- **Educational Apps**: Teaching tools for linguistics

## API Limits
- Datamuse API is free to use
- Rate limits apply for high-volume usage
- No API key required for basic usage

## Contributing
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is open source and available under the [MIT License](LICENSE).

## Resources
- [Datamuse API Documentation](https://www.datamuse.com/api/)
- [API Query Examples](https://www.datamuse.com/api/)

## Contact
- GitHub: [@oskarcode](https://github.com/oskarcode)
- Project Link: [https://github.com/oskarcode/datamuseapi](https://github.com/oskarcode/datamuseapi)

## Acknowledgments
- Datamuse for providing the free word API
- The linguistics community for language data

---
*Word exploration and linguistic analysis with the Datamuse API*