# Poster Marketplace

A web-based marketplace application for buying and selling posters, built with Python and Flask.

## 📌 Overview

Poster Marketplace is a lightweight e-commerce platform that allows users to browse a collection of posters and list their own for sale. The application handles user data and product listings using a local SQLite database, ensuring a simple yet functional backend.

## 🚀 Features

- **User Authentication**: Secure user registration and login functionality.
- **Product Listing**: Browse available posters with details.
- **Sell Your Art**: Users can upload and list their own posters for sale.
- **Image Management**: Uploaded poster images are securely stored in the `uploads/` directory.
- **Database Integration**: Utilizes SQLite (`sellers.db`) for persistent data storage of users and products.

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS (stored in `static/` and `templates/`)
- **Database**: SQLite
- **File Handling**: Local filesystem storage for images

## 📂 Project Structure

```text
poster_marketplace/
├── order/           # Order processing logic
├── seed_images/     # Default/Initial images for the application
├── static/          # CSS, JavaScript, and static images
├── templates/       # HTML templates for the UI
├── uploads/         # Directory for user-uploaded poster images
├── app.py           # Main application entry point (Flask app)
├── sellers.db       # SQLite database file
├── requirements.txt # Python dependencies
├── .gitignore       # Git ignore file
└── README.md        # Project documentation
⚙️ Installation & Setup
Follow these steps to get a copy of the project up and running on your local machine.

Prerequisites
Python 3.x installed on your system.

pip (Python package manager).

Steps
Clone the Repository

Bash
git clone [https://github.com/yashsoloman7/poster_marketplace.git](https://github.com/yashsoloman7/poster_marketplace.git)
cd poster_marketplace
Create a Virtual Environment (Optional but Recommended)

Bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
Install Dependencies

Bash
pip install -r requirements.txt
Run the Application

Bash
python app.py
Access the App Open your web browser and go to: http://127.0.0.1:5000

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is open source.
