# 42_camagru

An Instagram-like web application with photo editing, filters, and social media functionality, created as part of the 42 School curriculum.

## 📖 About

**Camagru** is a full-stack web application that allows users to capture photos, apply filters and stickers, share them in a gallery, and interact through likes and comments.

## 🚀 Features

- **Photo Capture**: Webcam integration for real-time photo taking
- **Image Editing**: Apply filters and overlay stickers
- **User Authentication**: Secure registration, login, and email verification
- **Social Gallery**: Public gallery with photo sharing
- **Interactive Features**: Like, comment, and notification system
- **Responsive Design**: Mobile-friendly interface
- **Email Notifications**: Automated email alerts for interactions

## 🔧 Build Instructions

### Prerequisites

- Web server (Apache/Nginx)
- PHP 7.0+
- MySQL/MariaDB
- SMTP server for email functionality

### Setup

```bash
# Clone and configure
git clone [repository]
cd 42_camagru

# Database setup
mysql -u root -p < database/setup.sql

# Configure email settings
cp private/config/config.php.example private/config/config.php
# Edit config.php with your settings
```

## 📝 Usage

### Access the Application

```
http://localhost/42_camagru/public/
```

### Core Features

- **Registration**: Create account with email verification
- **Login**: Secure authentication system
- **Photo Studio**: Capture photos with webcam
- **Gallery**: Browse and interact with photos
- **Profile**: Manage account settings

### Photo Creation Process

1. Access photo studio
2. Position camera and select filters
3. Add stickers and effects
4. Capture and save photo
5. Share to public gallery

## 🔍 Implementation Details

### Architecture

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP with MVC pattern
- **Database**: MySQL with prepared statements
- **Security**: Input validation, CSRF protection, XSS prevention

### Key Components

- **Camera Integration**: WebRTC for webcam access
- **Image Processing**: Server-side image manipulation
- **User Management**: Registration, authentication, email verification
- **Social Features**: Likes, comments, notifications
- **Gallery System**: Photo display and interaction

### Security Features

- **SQL Injection Prevention**: Prepared statements
- **XSS Protection**: Input sanitization
- **CSRF Tokens**: Form protection
- **Password Security**: Hashing and validation
- **Email Verification**: Account activation

## 🧪 Testing

### User Registration

```
1. Navigate to registration page
2. Fill form with valid email
3. Check email for verification link
4. Activate account and login
```

### Photo Creation

```
1. Login to application
2. Access photo studio
3. Grant camera permissions
4. Select filters and stickers
5. Capture and save photo
```

### Social Interaction

```
1. Browse public gallery
2. Like photos from other users
3. Add comments to photos
4. Check notifications for interactions
```

## 🎨 Features Overview

### Photo Studio

- **Real-time Preview**: Live camera feed
- **Filter Selection**: Multiple visual effects
- **Sticker Overlay**: Decorative elements
- **Capture Interface**: Easy photo taking

### Gallery System

- **Public Feed**: All user photos
- **User Profiles**: Individual photo collections
- **Interaction Tools**: Like and comment system
- **Responsive Grid**: Mobile-optimized layout

## 🔗 Dependencies

- **PHP**: Server-side scripting
- **MySQL**: Database management
- **JavaScript**: Client-side interactivity
- **HTML5/CSS3**: Frontend structure and styling
- **WebRTC**: Camera access functionality

---

_Full-stack web development project demonstrating modern web technologies, user authentication, real-time features, and social media functionality._
