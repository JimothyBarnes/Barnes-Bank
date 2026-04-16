# Barnes Bank - Dual Currency Family Banking System

A modern, mobile-first banking application for families that manages both Barnes Bucks (BB) and USD currencies with real-time synchronization across devices.

## Features

- **Dual Currency System**: Manage both Barnes Bucks (BB) and USD
- **User Roles**: Admin (parents) and Kid accounts
- **Job/Contract System**: Fixed-rate and hourly punch clock jobs
- **Time Tracking**: Hourly jobs with clock in/out functionality
- **Transfer System**: Send funds between family members
- **Real-time Sync**: Multi-device synchronization via Firebase
- **Mobile Responsive**: Optimized for phones and tablets
- **Modern UI**: Dark theme with gold/green accents

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Database**: Firebase Firestore
- **Styling**: Custom CSS with CSS Variables
- **Icons**: Font Awesome
- **Fonts**: Inter (Google Fonts)

## Getting Started

### Local Development

1. Clone this repository
2. Run a local web server:
   ```bash
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser

### Firebase Setup

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Set up Firestore Database in test mode
3. Update the `firebaseConfig` object in `index.html` with your project credentials

### Default Login

- **Admin**: Username: `admin`, Password: `parent`

## Project Structure

```
barnes-bank/
|-- index.html          # Main application file
|-- README.md           # Project documentation
|-- .gitignore         # Git ignore file
```

## Usage

### For Parents (Admin)
- Create and manage kid accounts
- Issue contracts and hourly jobs
- Approve completed work
- Manual balance adjustments

### For Kids
- View balances and transaction history
- Claim available jobs
- Clock in/out for hourly work
- Transfer funds to siblings

## Deployment

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source as "main" branch
4. Access at `https://username.github.io/repository-name`

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For issues and feature requests, please open an issue on GitHub.
