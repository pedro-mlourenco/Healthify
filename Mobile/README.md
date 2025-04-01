<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/pedro-mlourenco/Healthify/tree/main/Mobile">
    <img src="app\src\main\ic_healthify-playstore.png" alt="Logo" width="80" height="80" style="border-radius: 30%">
  </a>

<h3 align="center">Healthify Android Platform</h3>
<p align="center">
    Healthify Platform for restaurants is a comprehensive solution that allows restaurants to efficiently manage bookings, inventory, kitchen orders, and employees, while seamlessly integrating with an Android app for clients and employees.
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#platform-usage">Platform Usage</a>
      <ul>
        <li><a href="#booking-management">Booking Management</a></li>
        <li><a href="#inventory-control">Inventory Control</a></li>
        <li><a href="#kitchen-order-system">Kitchen Order System</a></li>
        <li><a href="#employee-management">Employee Management</a></li>
        <li><a href="#integration-features">Integration Features</a></li>
      </ul>
    </li>
  </ol>
</details>

## Getting Started

These instructions will help you set up and run the Healthify Android Platform on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
* [Android Studio](https://developer.android.com/studio) (latest version)
* JDK 11 or higher
* Android SDK (minimum SDK version 21)
* Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/pedro-mlourenco/Healthify-Mobile.git
```

2. Open Android Studio and select 'Open an Existing Project'

3. Navigate to the cloned repository and select it

4. Wait for Gradle sync to complete

5. Configure your local.properties file with your SDK path
```properties
sdk.dir=C\:\\Users\\YourUsername\\AppData\\Local\\Android\\Sdk
```

6. Build the project
```bash
./gradlew build
```

### Platform Usage

The Healthify Android Platform provides the following key features:

1. **Booking Management**
   - View and manage restaurant reservations
   - Real-time booking updates
   - Capacity management

2. **Inventory Control**
   - Track ingredient stock levels
   - Manage suppliers
   - Automated stock alerts

3. **Kitchen Order System**
   - Real-time order tracking
   - Order prioritization
   - Kitchen staff assignment

4. **Employee Management**
   - Staff scheduling
   - Performance tracking
   - Role-based access control

5. **Integration Features**
   - Seamless connection with web services
   - Real-time data synchronization
   - API integration for external services

To run the app in debug mode, connect an Android device or use an emulator and click the 'Run' button in Android Studio.