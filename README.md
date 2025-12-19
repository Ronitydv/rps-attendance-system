# RPS School Attendance System

A comprehensive web-based attendance management system for RPS School's Class 11 Non-Medical A, built with HTML, CSS, and JavaScript.

## Features

### Main Attendance Page (`index.html`)
- **Student Management**: Add, edit, or remove up to 47 students
- **Date Navigation**: Easy date selection with Prev/Today/Next buttons
- **Attendance Marking**: Mark students as Present or Absent with visual feedback
- **Holiday Management**: Mark days as holidays
- **Data Security**: Past attendance cannot be edited for integrity
- **Records View**: See attendance history with summaries

### Student Data Analytics (`student-data.html`)
- **Search Students**: Find students by name
- **Monthly Reports**: View attendance statistics for the current month
- **Visual Charts**: Pie chart showing Present/Absent/Holidays distribution
- **Detailed History**: Day-by-day attendance breakdown

### Administrative Features
- **Manage Students**: Edit student names and class roster
- **Clear Data**: Password-protected data reset (password: admin123)
- **Data Persistence**: All data saved locally in browser storage

## Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript (ES6+)**: Dynamic functionality and data management
- **Chart.js**: Data visualization for attendance analytics
- **Local Storage**: Client-side data persistence

## Installation & Setup

1. **Clone or Download** the repository
2. **Open** `index.html` in any modern web browser
3. **No server required** - runs entirely in the browser

## Usage

### Daily Attendance
1. Select the date using the navigation buttons
2. Mark each student as Present or Absent
3. Click "Submit Attendance" to save

### Managing Students
1. Click "Manage Students" in the header
2. Edit names in the input fields
3. Click "Save Changes" to update

### Viewing Analytics
1. Click "View Student Data" link
2. Search for a student by name
3. View their monthly attendance chart and details

### Administrative Tasks
- Mark holidays using the "Mark as Holiday" button
- Clear all data with password protection

## Security Features
- Past attendance records are locked from editing
- Password protection for data clearing
- Client-side data storage (no server required)

## Browser Compatibility
- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## File Structure
```
├── index.html              # Main attendance page
├── style.css               # Styles and animations
├── script.js               # Main application logic
├── student-data.html       # Analytics page
├── student-data.js         # Analytics logic
└── README.md              # This file
```

## Contributing
Feel free to fork and improve the system. Pull requests are welcome!

## License
This project is open source and available under the MIT License.

## Support
For issues or questions, please open an issue on GitHub.</content>
<parameter name="filePath">c:\Users\raoya\vs code\New folder20\README.md