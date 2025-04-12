# Sauce Demo Automation Project

This project automates various functionalities of the [Sauce Demo](https://www.saucedemo.com/) website using Selenium, PyTest, and Allure reporting.

## Project Structure

```bash
.
├── pages/
│   ├── base_page.py                # Base page class
│   ├── cart_and_checkout_page.py    # Page object for cart and checkout
│   ├── footer_page.py               # Page object for footer social media links
│   ├── login_page.py                # Page object for login functionality
│   ├── logout_page.py               # Page object for logout functionality
│   ├── product_page.py              # Page object for product-related actions
├── reports/
│   ├── allure-results/              # Allure results directory for test reports
├── tests/
│   ├── test_checkout.py             # Test script for checkout functionality
│   ├── test_footer.py               # Test script for social media footer links
│   ├── test_login.py                # Test script for login functionality
│   ├── test_logout.py               # Test script for logout functionality
│   ├── test_product.py              # Test script for product-related tests
├── utils/
│   ├── config.py                    # Configuration file
│   ├── driver_factory.py            # WebDriver setup and management
├── venv/                            # Python virtual environment
├── conftest.py                      # PyTest fixture configuration
├── requirements.txt                 # Python dependencies






