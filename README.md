# Project Name

The project consists of a color palette where you can create new colours by combining hex values and you can copy them.


## Screenshots

<img width="1094" height="550" alt="ScreenShot Tool -20260428151736" src="https://github.com/user-attachments/assets/2bd0cea1-0020-4167-b286-dcaee3025f98" />



## Features

- Feature 1: A user can generate different color palettes by combining hex values with js.
- Feature 2: A user can copy the hex values with the clipboard function.
- Responsive design
- Cross-browser compatible

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and layout
- **JavaScript** - Interactivity and functionality

## Installation

1. Clone the repository:
```bash
git@github.com:kingcollinsdev/color-palette-generator.git
```

2. Navigate to the project directory:
```bash
cd color-palette-generator
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

## Usage

Creates the hex values by combing letters and numbers.

```javascript
// Example code snippet
 const letters = "0123456789ABCDEF";
    let color = "#";

    for (let i = 0; i < 6; i++) {
        color += letters[Math.floor(Math.random() * 16)];
    }

    return color;
```

## Project Structure

```
project-name/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Main JavaScript file
├── images/             # Image assets
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)


## Contact

Your Name - Collins Wachira - collinswachira2004@gmail.com

Project Link: [https://color-palette-generator-mu-nine.vercel.app/](https://github.com/kingcollinsdev/color-palette-generator.git)

## Acknowledgements
Inspiration :- https://www.youtube.com/watch?v=kAiX0itnonM&t=13648s
