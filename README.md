# JEWELUX - Luxury E-commerce Platform

JEWELUX is a premium, production-level luxury jewellery e-commerce platform built with Python (Flask) and MySQL. It features a stunning, responsive design with smooth animations and comprehensive shopping functionality.

## ✨ Features

- **Premium UI/UX**: Modern, elegant design with a focus on luxury aesthetics.
- **Responsive Design**: Seamless experience across mobile, tablet, and desktop devices.
- **Product Catalog**: Categorized products with advanced filtering (price, category, sort).
- **Search**: AJAX-powered live search for quick product discovery.
- **User Accounts**: Secure authentication, profile management, and order history.
- **Shopping Cart & Wishlist**: Fully functional cart and wishlist systems.
- **Admin Panel**: Comprehensive dashboard to manage products, categories, and orders.
- **Image Management**: Support for primary and gallery images.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla CSS3 (Custom Design System), JavaScript (ES6+).
- **Backend**: Python 3.11+, Flask.
- **Database**: MySQL with `Flask-MySQLdb`.
- **Authentication**: Werkzeug security (PBKDF2 with salt).

## 🚀 Getting Started

### Prerequisites

- Python 3.11+
- MySQL Server
- Git

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Rishi737-beep/jewelux.git
   cd jewelux
   ```

2. **Set up a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Database Setup**:
   - Create a MySQL database named `jewelux`.
   - Import the schema:
     ```bash
     mysql -u your_username -p jewelux < schema.sql
     ```

5. **Configuration**:
   - Create a `.env` file in the root directory (copy from `.env.example` if available).
   - Update your database credentials in `config.py` or `.env`.

6. **Run the application**:
   ```bash
   python app.py
   ```
   Open `http://localhost:5000` in your browser.

## 📂 Project Structure

- `app.py`: Main Flask application and routes.
- `config.py`: Environment-specific configurations.
- `schema.sql`: Database schema and seed data.
- `static/`: CSS, JS, and image assets.
- `templates/`: Jinja2 HTML templates.

## 📄 License

This project is for demonstration purposes.

---
Built with ❤️ by [Rishi](https://github.com/Rishi737-beep)
