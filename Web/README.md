<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/pedro-mlourenco/Healthify-Web.git">
    <img src="images/logo.png" alt="Logo" width="80" height="80" style="border-radius: 30%">
  </a>

<h3 align="center">Healthify Web Platform</h3>

  <p align="center">
    Healthify Platform for restaurants is a comprehensive solution that allows restaurants to efficiently manage bookings, inventory, kitchen orders, and employees, while seamlessly integrating with an Android app for clients and employees.
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#platform-usage">Platform Usage</a></li>
  </ol>
</details>

## About The Project

- [PHP 7.4](https://www.php.net/)
- [Yii2](https://www.yiiframework.com/)
- [Bootstrap](https://getbootstrap.com)
- [JQuery](https://jquery.com)

<p align="right">(<a href="#top">back to top</a>)</p>

## Getting Started

### Prerequisites

- Composer
- MySQL

### Installation

1. Get a free API Key at [https://calorieninjas.com/](https://calorieninjas.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/pedro-mlourenco/Healthify-Web.git
   ```
3. Install Composer packages
   ```sh
   composer install
   ```
4. Run the database script in `db/healthifyLive.sql`

5. Enter your API in `backend/web/js/customJs.js`
   ```js
   var apiKey = "useYourOwn";
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

## Platform Usage

Frontend webpage location: `frontend/web/`

Credentials if using included DB:

```
Username: tonnyjohnny213
Password: 12345678
```

Backend webpage location: `backend/web/`

Credentials if using included DB:

```
Username: admin
Password: 12345678
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Directory Structure

```
common
    config/              contains shared configurations
    mail/                contains view files for e-mails
    models/              contains model classes used in both backend and frontend
    tests/               contains tests for common classes
console
    config/              contains console configurations
    controllers/         contains console controllers (commands)
    migrations/          contains database migrations
    models/              contains console-specific model classes
    runtime/             contains files generated during runtime
backend
    assets/              contains application assets such as JavaScript and CSS
    config/              contains backend configurations
    controllers/         contains Web controller classes
    models/              contains backend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for backend application
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
frontend
    assets/              contains application assets such as JavaScript and CSS
    config/              contains frontend configurations
    controllers/         contains Web controller classes
    models/              contains frontend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for frontend application
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
    widgets/             contains frontend widgets
vendor/                  contains dependent 3rd-party packages
environments/            contains environment-based overrides
```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Links -->

[product-screenshot]: images/dashboard_login.png
