# Student Records Management - AngularJS

A comprehensive student records management application built with AngularJS, featuring modern UI/UX design, form validations, and interactive functionality.

## Features

### Core Functionality
- **Add Students**: Create new student records with validation
- **Edit Students**: Modify existing student information
- **Delete Students**: Remove students with confirmation
- **View Records**: Display all students in a responsive table
- **Statistics**: Real-time statistics including total students, average age, and grade distribution

### AngularJS Concepts Demonstrated
- **ng-app**: Application initialization
- **ng-controller**: Controller binding
- **ng-model**: Two-way data binding
- **ng-submit**: Form submission handling
- **ng-click**: Button click events
- **ng-repeat**: Dynamic list rendering
- **ng-show/ng-hide**: Conditional display
- **ng-class**: Dynamic CSS classes
- **ng-disabled**: Conditional button states
- **Expressions**: Data display and calculations
- **Filters**: Ordering students by name

### Form Validations
- **Required Fields**: Name, age, grade, and email are mandatory
- **Data Type Validation**: Age must be a number between 5-25
- **Email Validation**: Proper email format checking
- **Real-time Feedback**: Visual indicators for valid/invalid fields
- **Form State Management**: Pristine/touched states

### Events and Interactions
- **Form Submission**: Add/update student records
- **Button Clicks**: Edit, delete, cancel operations
- **Input Changes**: Real-time validation feedback
- **Confirmation Dialogs**: Delete confirmations
- **Success Messages**: Temporary feedback on operations

### UI/UX Features
- **Responsive Design**: Bootstrap-based mobile-friendly layout
- **Modern Styling**: Gradient backgrounds, cards, shadows, and animations
- **Interactive Elements**: Hover effects, transitions, and visual feedback
- **Color-coded Grades**: Visual grade indicators
- **Icons**: Font Awesome icons for better visual hierarchy
- **Loading States**: Disabled states during form processing

## Technologies Used
- **AngularJS 1.8.2**: Core framework
- **Bootstrap 5.1.3**: CSS framework for responsive design
- **Font Awesome 6.0.0**: Icon library
- **HTML5**: Semantic markup
- **CSS3**: Custom styling with gradients and animations

## How to Run
1. Open `index.html` in a web browser
2. The application loads with sample student data
3. Add new students using the form
4. Edit or delete existing records
5. View statistics at the bottom

Note: For local development, you may need to serve the file via a web server:

```bash
cd student-records-app
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Sample Data
The application includes sample student records to demonstrate functionality:
- Alice Johnson (Age 20, Grade A)
- Bob Smith (Age 19, Grade B)
- Charlie Brown (Age 21, Grade C)

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Requires JavaScript enabled
- Responsive design works on mobile devices