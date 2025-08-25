# Learn3 - Multilingual Vocabulary Learning Platform

*Learn3 is a responsive web application designed to help users master vocabulary across three languages: English, German, and Russian. The platform offers a structured learning path from A1 to B1 level with 2400 words organized into 240 daily lessons.*
Powered by **AlgoNestUz** - Innovative solutions for language learning

**Features**

Multilingual Support: Learn words in English, German, and Russian simultaneously
Structured Curriculum: 240 days of vocabulary organized by topics
Responsive Design: Works seamlessly on desktop, tablet, and mobile devices
Modern UI: Dark theme with glassmorphism effects and smooth animations
Flexible Navigation: Browse by day with next/previous buttons or jump to specific days
Social Integration: Connect via Telegram, LinkedIn, and Instagram

**Technology Stack**

Frontend: HTML5, CSS3, JavaScript (Vanilla)
Styling: Custom CSS with CSS Variables
Icons: Font Awesome
Fonts: Google Fonts (Inter)
No Frameworks: Pure vanilla implementation for optimal performance
Developed by: **AlgoNestUz**

**Project Structure**

text
learn3/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # Main JavaScript functionality
├── vocabulary.js       # Vocabulary data (2400 words)
├── img/
│   └── logo.png        # Website logo
└── README.md           # Project documentation

Getting Started

**Prerequisites**

No special prerequisites needed. Just a modern web browser.

**Installation**

Clone the repository:

bash
git clone https://github.com/ixtiyorai/learn3.git
Navigate to the project directory:

bash
cd learn3
Open index.html in your web browser or use a local server:

bash
**Using Python**

python -m http.server 8000

**Using Node.js**

npx http-server

**Using PHP**

php -S localhost:8000

**Usage**

Browse Vocabulary: Use the navigation buttons to move between days or jump to a specific day
Learn Words: Each day contains 10 words across three languages on a specific topic
Track Progress: The interface shows your current day and topic
Connect: Use the contact section to reach out on various platforms

**Vocabulary Structure**

The vocabulary is organized in the following structure:

javascript
const vocabulary = [
  {
    day: 1,
    topic: "Greetings",
    words: [
      { en: "Hello", de: "Hallo", ru: "Привет" },
      // ... more words
    ]
  },
  // ... more days
];

**Customization**

Adding New Vocabulary
Edit the vocabulary.js file to add new words or modify existing ones following the same structure.

**Styling Changes**

Modify the CSS variables in the :root selector to change the color scheme:

css
:root {
  --bg-primary: #0d1117;          /* Dark background */
  --accent-teal: #00ffa3;         /* Teal accent color */
  --accent-orange: #ff7f11;       /* Orange accent color */
  /* ... more variables */
}

**Social Links**

Update the contact section in the HTML with your actual social media URLs:

html
<a href="https://t.me/algonestuz" class="social-link" target="_blank">Join Channel</a>

**Browser Support**

Learn3 supports all modern browsers including:
Chrome (latest)
Firefox (latest)
Safari (latest)
Edge (latest)

**Contributing**

Contributions are welcome! Please feel free to submit a Pull Request.

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Developed by: AlgoNestUz

Telegram Channel: @algonestuz

Telegram Account: @IxtiyorQoshmuratov

LinkedIn: Ixtiyor Qo'shmuratov

Instagram: @algonestuz @lanimircc

**Acknowledgments**

Design inspired by GitHub's dark theme
Icons provided by Font Awesome
Fonts provided by Google Fonts

****Developed by AlgoNestUz****__

**Future Enhancements**

User accounts and progress tracking
Spaced repetition system
Pronunciation audio for words
Practice exercises and quizzes
Mobile application version

# Powered by AlgoNestUz - Innovative solutions for language learning

Happy Learning! 🌟
