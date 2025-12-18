# LifePrint 🌟

A comprehensive personal wellness and self-discovery platform that helps users understand themselves better through personality assessments, nutrition tracking, story journaling, and future goal planning.

## 🚀 Features

### Core Modules

- **personaPrint** - Personality assessment and identity exploration
  - 10-question personality assessment
  - Trait identification and analysis
  - Communication style insights

- **FoodPrint** - Nutrition and meal tracking
  - Daily meal logging
  - Calorie and nutrient tracking
  - Eating habit analysis

- **StoryWeaver** - Life narrative and journaling
  - Story creation and documentation
  - Memory preservation
  - Personal narrative building

- **Time Capsule 2040** - Future goals and vision
  - Goal setting and tracking
  - Future message creation
  - Milestone planning

- **Analytics & Insights** - Progress tracking
  - Weekly summaries
  - Trend analysis
  - Key insights dashboard

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: PHP 7.4+
- **Database**: MySQL 5.7+
- **UI Framework**: Custom CSS with glassmorphism design
- **Icons**: Font Awesome 6
- **Notifications**: SweetAlert2

## 📦 Installation

### Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx) or PHP built-in server

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/LifePrint.git
   cd LifePrint
   ```

2. **Configure environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Edit `.env` with your database credentials:
   ```
   DB_HOST=localhost
   DB_PORT=3306
   DB_NAME=your_database_name
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   ```

3. **Set up the database**
   
   Import the schema:
   ```bash
   mysql -u your_username -p your_database_name < config/schema.sql
   ```

4. **Start the development server**
   ```bash
   cd public
   php -S localhost:8000
   ```

5. **Access the application**
   
   Open your browser and navigate to: `http://localhost:8000`

## 📁 Project Structure

```
LifePrint/
├── .env.example          # Environment template
├── .gitignore            # Git ignore rules
├── config/
│   ├── db.php            # Database configuration
│   └── schema.sql        # Database schema
├── public/
│   ├── index.html        # Entry point
│   ├── router.php        # PHP router
│   ├── api/              # Backend API endpoints
│   │   ├── auth.php      # Authentication
│   │   ├── profiles.php  # User profiles
│   │   ├── food-logs.php # Meal tracking
│   │   ├── stories.php   # Story management
│   │   └── ...
│   ├── assets/
│   │   ├── css/          # Stylesheets
│   │   ├── js/           # JavaScript files
│   │   └── images/       # Static images
│   └── pages/            # HTML pages
│       ├── home.html
│       ├── login.html
│       ├── signup.html
│       ├── dashboard-new.html
│       └── ...
└── README.md
```

## 🔐 Security

- Database credentials are stored in environment variables
- Passwords are hashed using PHP's `password_hash()`
- PDO prepared statements prevent SQL injection
- XSS protection through output encoding

## 🌐 Deployment

### Server Requirements

- PHP 7.4+ with PDO extension
- MySQL 5.7+
- HTTPS recommended for production

### Production Setup

1. Upload files to your web server
2. Create `.env` file with production credentials
3. Import database schema
4. Configure web server to point to `/public` directory
5. Set appropriate file permissions

## 📱 Responsive Design

LifePrint is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Athanase Abayo**
- GitHub: [@athanase-abayo](https://github.com/athanase-abayo)

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts (Inter) for typography
- SweetAlert2 for beautiful notifications

---

Made with ❤️ for Web Technologies Course 2025
