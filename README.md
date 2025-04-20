# Digital Business Card Application

A modern web application for creating and sharing digital business cards with QR codes.

## 📋 Overview

This Flask-based web application allows users to create personalized digital business cards that can be shared via QR codes. Users can register an account, customize their profile with professional information, upload a profile picture, and generate QR codes that link directly to their profile page.

## ✨ Features

- **User Authentication**: Secure registration and login system
- **Profile Management**: Create and edit comprehensive professional profiles
- **QR Code Generation**: Automatically generate QR codes for easy profile sharing
- **Responsive Design**: Works on both desktop and mobile devices
- **Profile Images**: Upload and resize profile pictures
- **Social Media Integration**: Add links to LinkedIn, Twitter, GitHub and more

## 🛠️ Technologies

- **Backend**: Python, Flask
- **Database**: SQLAlchemy with SQLite
- **Security**: Werkzeug security for password hashing
- **Image Processing**: Pillow (PIL)
- **QR Code Generation**: qrcode library

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/prajwal032004/digital-business-card.git
cd digital-business-card

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Run the application
flask run
or
python app.py
```

## 📦 Dependencies

Create a `requirements.txt` file with the following:

```
Flask==2.0.1
Flask-SQLAlchemy==2.5.1
Werkzeug==2.0.1
Pillow==8.3.1
qrcode==7.3
```
Download All Requirements
```
pip install -r requirements.txt
```
## 📝 Usage

1. Register a new account
2. Log in to access your dashboard
3. Edit your profile with professional details
4. Share your profile via the generated QR code

## 🧩 Project Structure

```
digital-business-card/
├── static/
│   ├── css/
│   ├── js/
│   └── uploads/     # User profile images and QR codes
├── templates/       # HTML templates
├── app.py           # Main application file
├── requirements.txt
└── README.md
```

## 📸 Screenshots

*[Add screenshots of your application here]*

## 🔒 Security Features

- Password hashing with Werkzeug
- Secure file uploads with validation
- CSRF protection
- User session management

## 🚧 Future Improvements

- [ ] Add support for vCard export
- [ ] Implement email verification
- [ ] Add theme customization options
- [ ] Create mobile app version
- [ ] Add analytics for profile views

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

Your Name - [Your GitHub Profile](https://github.com/prajwal032004)
