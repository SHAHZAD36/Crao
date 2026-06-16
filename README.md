# Chaudhary Traders 🏪

A complete offline business management app for Chaudhary Traders — built with Flutter.

## Features
- 📦 Product & Inventory Management
- 👥 Customer Management with Ledger
- 🧾 Sales with Invoice Generation
- 💰 Collections & Payment Tracking
- 🛒 Purchase Management
- 💸 Expense Tracking
- 📒 Cash Book (IN/OUT)
- 📊 Reports & Analytics
- 💾 Backup & Restore
- 🌙 Dark/Light Mode
- 🔐 PIN Login

## Project Structure
```
lib/
├── main.dart
├── database/
│   └── database_helper.dart
├── models/
│   ├── product.dart
│   ├── customer.dart
│   ├── sale.dart
│   ├── collection.dart
│   ├── purchase.dart
│   ├── expense.dart
│   └── cash_book.dart
├── providers/
│   ├── auth_provider.dart
│   ├── settings_provider.dart
│   ├── product_provider.dart
│   ├── customer_provider.dart
│   ├── sale_provider.dart
│   ├── collection_provider.dart
│   ├── purchase_provider.dart
│   └── expense_provider.dart
├── screens/
│   ├── auth/
│   ├── dashboard/
│   ├── products/
│   ├── customers/
│   ├── sales/
│   ├── collections/
│   ├── purchases/
│   ├── expenses/
│   ├── cash_book/
│   ├── reports/
│   ├── backup/
│   └── settings/
├── widgets/
│   ├── app_drawer.dart
│   ├── dashboard_card.dart
│   └── custom_text_field.dart
└── utils/
    ├── constants.dart
    ├── helpers.dart
    └── theme.dart
```

## Build APK via GitHub Actions
1. Push code to `main` branch
2. Go to **Actions** tab in GitHub
3. Click **Build Flutter APK** workflow
4. Wait ~5 minutes for build
5. Download APK from **Artifacts** section

## Local Setup
```bash
flutter pub get
flutter run
flutter build apk --release
```

## Default Login
- Username: `admin`
- Password: `admin123`
