# Library Management System

A comprehensive web-based library management system built with HTML, CSS, JavaScript, and Bootstrap.

## Project Structure

```
dileep wdt.project/
├── index.html                 # Dashboard/Home page
├── signin.html               # User login page
├── signup.html               # User registration page
├── browse-books.html         # Browse and search books
├── book-details.html         # Detailed book information
├── my-books.html             # User's borrowed books and history
├── search-results.html       # Search results page
├── user-profile.html         # User profile management
├── settings.html             # User settings and preferences
├── admin-dashboard.html      # Admin control panel
├── assets/
│   ├── css/
│   │   └── style.css        # Global styles with Bootstrap
│   ├── js/
│   │   └── script.js        # JavaScript functionality
│   └── images/              # Image placeholder folder
└── README.md                # This file
```

## Pages Overview

### 1. **Sign In Page** (signin.html)
- User login interface
- Email and password authentication
- Remember me checkbox
- Link to sign up page
- Demo credentials: email: demo@library.com, password: demo123

### 2. **Sign Up Page** (signup.html)
- User registration form
- Full name, email, password fields
- Password confirmation
- Terms and conditions acceptance

### 3. **Dashboard** (index.html)
- Welcome message
- Statistics cards (books borrowed, books read, wishlist)
- Search functionality
- Featured books carousel
- New arrivals section
- Quick access to borrow/view books

### 4. **Browse Books** (browse-books.html)
- Complete book catalog
- Filter by category, rating, and language
- Search functionality
- Book cards with borrowing option
- Responsive grid layout

### 5. **Book Details** (book-details.html)
- Comprehensive book information
- ISBN, pages, publication year
- Full book description
- Borrow, wishlist, and share options
- Related books section
- Reader reviews and rating system
- Submit review functionality

### 6. **My Books** (my-books.html)
- Currently borrowed books with due dates
- Return history
- Wishlist of books
- Reading statistics
- Notifications and alerts
- Days left counter

### 7. **Search Results** (search-results.html)
- Dynamic search functionality
- Results count and query display
- Book grid with sorting
- No results handling
- Quick borrow/view options

### 8. **User Profile** (user-profile.html)
- User avatar and basic information
- Personal information section
- Reading statistics
- Membership details
- Preferences management
- Recent activity timeline
- Modal for profile editing

### 9. **Settings** (settings.html)
- Account settings (username, email, password)
- Notification preferences
- Privacy and security options
- Two-factor authentication
- Active sessions management
- Language and theme preferences
- Billing and subscription details
- Account deletion option

### 10. **Admin Dashboard** (admin-dashboard.html)
- Key metrics and statistics
- Book inventory management
- User management
- Active borrowings and overdue books
- Recent activities log
- Quick action buttons
- Report generation
- System backup functionality

## Features

### Authentication & Security
- Sign in/Sign up functionality
- Local storage for user sessions
- Session management
- Logout functionality

### Book Management
- Browse books by category
- Search by title or author
- Filter books by rating and language
- View detailed book information
- Borrow and return books
- Wishlist functionality

### User Features
- Personal dashboard
- Profile management
- Reading statistics
- Borrowing history
- Notification preferences
- Settings customization

### Admin Features
- Book inventory management
- User management
- Borrowing/return tracking
- Overdue book management
- Report generation
- System backup

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript** - DOM manipulation and local storage
- **Bootstrap 5** - Responsive framework
- **LocalStorage** - Client-side data persistence

## Demo Credentials

- **Email**: demo@library.com
- **Password**: demo123

## Color Scheme

- Primary: `#667eea` (Purple Blue)
- Secondary: `#764ba2` (Dark Purple)
- Success: `#28a745` (Green)
- Danger: `#dc3545` (Red)
- Background: `#f8f9fa` (Light Gray)

## How to Use

1. Open `signin.html` in your web browser
2. Use demo credentials or create a new account
3. Navigate through different pages using the navbar
4. Test features like borrowing books, updating profile, etc.
5. Admin features are accessible from the admin dashboard

## Data Storage

The application uses browser LocalStorage for:
- Current user session
- Borrowed books
- User preferences
- Wishlist

## Sample Books Data

The system includes 10 pre-loaded books:
1. The Great Gatsby
2. To Kill a Mockingbird
3. 1984
4. Pride and Prejudice
5. The Hobbit
6. Sapiens
7. The Catcher in the Rye
8. Educated
9. The Lord of the Rings
10. Atomic Habits

## Features Implemented

✅ Responsive design (mobile and desktop)
✅ User authentication
✅ Book browsing and searching
✅ Book borrowing system
✅ User profile management
✅ Settings and preferences
✅ Admin dashboard
✅ Notifications and alerts
✅ Bootstrap integration
✅ Smooth transitions and animations

## Future Enhancements

- Backend database integration
- Payment gateway
- Email notifications
- Advanced reporting
- Book ratings and reviews system
- Social sharing features
- Mobile app version

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for educational and personal use.

---

**Created**: April 2024
**Version**: 1.0
