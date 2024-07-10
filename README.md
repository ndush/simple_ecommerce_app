# E-commerce App

A simple e-commerce application built with Flutter. This app fetches product data from an API and displays it in a user-friendly manner with proper navigation and state management using Provider.

## Features

- **Product Listing Page**: Displays a list of products fetched from the provided API.
- **Product Detail Page**: Shows detailed information about a selected product, including name, image, price, and description.
- **Add to Cart**: Includes an "Add to Cart" button (Shows a Snackbar message saying "Added to Cart").
- **Responsive UI**: Ensures the application looks good on different screen sizes.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/ecommerce_app.git
    cd ecommerce_app
    ```

2. **Install dependencies**:
    ```sh
    flutter pub get
    ```

3. **Run the app**:
    ```sh
    flutter run
    ```
## ScreenShots

![Screenshot_20240710_145858](https://github.com/ndush/simple_ecommerce_app/assets/13904670/d37d00c7-c6a2-4128-8ab3-0ac980baec29)
![Screenshot_20240710_150040](https://github.com/ndush/simple_ecommerce_app/assets/13904670/57d8efa5-d7e7-40a0-8d01-a30ebf126e0a)


## Project Structure

```plaintext
ecommerce_app/
├── lib/
│   ├── models/
│   │   └── product.dart         # Product model
│   ├── screens/
│   │   ├── product_listing_page.dart  # Product listing page
│   │   └── product_detail_page.dart   # Product detail page
│   ├── services/
│   │   └── api_service.dart     # API service to fetch product data
│   └── main.dart                # Main entry point of the application
└── pubspec.yaml                 # Project dependencies

