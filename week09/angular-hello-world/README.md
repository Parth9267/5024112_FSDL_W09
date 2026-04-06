# AngularJS Hello World

A simple yet interactive Hello World project using AngularJS framework demonstrating ng-controller, ng-model, expressions, and more directives.

## Features
- **ng-app**: Defines the AngularJS application
- **ng-controller**: Binds the controller to the view
- **ng-model**: Two-way data binding for inputs
- **Expressions**: {{name}} displays dynamic data
- **ng-click**: Button interactions
- **ng-style**: Dynamic styling
- **ng-show**: Conditional display

## UI/UX Enhancements
- Gradient background with centered card layout
- Bootstrap for responsive design
- Interactive buttons: Toggle case, random color, reset
- Color picker for custom greeting color
- Smooth transitions and hover effects
- Conditional welcome message

## How to Run
1. Open `index.html` in a web browser.
2. Type in the input field to see the greeting update in real-time.
3. Use the buttons to change the greeting style and color.
4. Pick a custom color using the color input.

Note: Due to browser security policies, you may need to serve the file via a local web server if opening directly doesn't work. You can use Python's built-in server:

```bash
cd angular-hello-world
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.