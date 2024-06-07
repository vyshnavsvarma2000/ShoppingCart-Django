# Django Shopping Cart

Welcome to the **Django Shopping Cart** project! This repository contains a complete e-commerce web application built with Django as the backend and HTML/CSS for the frontend. This application provides functionalities for browsing products, adding them to a cart, and managing the shopping cart.

## Features

- **Product Browsing:** View and search products with detailed information and images.
- **Shopping Cart:** Add products to a cart, update quantities, and remove items.
- **Responsive Design:** Fully responsive UI using Bootstrap 5 for a great experience on both desktop and mobile devices.
- **Secure:** Implements Django's CSRF protection and form validation.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.8 or later
- Django 4.0 or later
- Bootstrap 5
- Git

### Installation

```bash
git clone https://github.com/your-username/django-shopping-cart.git
cd django-shopping-cart
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

### Configuration

- **Static Files:** Make sure your static files are correctly set up. You may need to run `python manage.py collectstatic` for production environments.
- **Environment Variables:** Create a `.env` file for secret keys and configuration settings if needed.

## Usage

- **Browse Products:** Visit the home page to view available products.
- **Add to Cart:** Click on a product to view its details and add it to your cart.
- **Manage Cart:** Go to the cart page to update quantities or remove items.
- **Continue Shopping:** Return to the product list to add more items.
- **Checkout:** Proceed to checkout to finalize your purchase (future enhancement).

## Screenshots

### Home Page
![Home Page](screenshots/home.png)

### Product Detail
![Product Detail](screenshots/product_detail.png)

### Shopping Cart
![Shopping Cart](screenshots/cart.png)

## Project Structure

```
django-shopping-cart/
│
├── cart/                     # Cart app
│   ├── templates/            # Cart templates
│   └── ...                   # Cart views, models, forms
│
├── shop_app/                 # Main app
│   ├── templates/            # Main app templates
│   └── ...                   # Main app views, models, forms
│
├── static/                   # Static files (CSS, JS, images)
├── templates/                # Global templates
├── manage.py                 # Django management script
└── requirements.txt          # Python dependencies
```

## Documentation

- **[Django Documentation](https://docs.djangoproject.com/):** Official Django documentation for detailed information on Django features and usage.
- **[Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/):** Learn more about using Bootstrap for responsive design.

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository.**
2. **Create a new branch:**

   ```bash
   git checkout -b feature/my-feature
   ```

3. **Make your changes.**
4. **Commit your changes:**

   ```bash
   git commit -m 'Add my feature'
   ```

5. **Push to the branch:**

   ```bash
   git push origin feature/my-feature
   ```

6. **Submit a pull request.**

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Django:** For the robust and scalable web framework.
- **Bootstrap:** For the beautiful and responsive UI components.
- **Contributors:** Thanks to all the contributors for their valuable contributions.

## Contact

For any inquiries or feedback, feel free to reach out to me at [vyshnav.s.varma@gmail.com](mailto:vyshnav.s.varma@gmail.com).
