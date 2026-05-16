<p align="center">
  <img src="https://img.shields.io/badge/Backend-Django%205.2-092E20?style=flat&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL-003B57?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/API%20Docs-Swagger-85EA2D?style=flat&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/Auth-JWT-black?style=flat&logo=json-web-tokens&logoColor=white" />
</p>

<h1 align="center">🔐 Django Google Allauth Integration</h1>

<p align="center"><strong>A professional, production-ready REST API for modern inventory tracking and warehouse management systems 🚀</strong></p>

<div align="center">
  <h3>
    <a href="https://umit8110.pythonanywhere.com">
      🖥️ Live Demo
    </a>
     | 
    <a href="https://github.com/umitarat-dev/django-google-allauth-integration.git">
      📂 Repository
    </a>
  </h3>
</div>

<p align="center">
  <a href="https://umit8110.pythonanywhere.com">
    <img src="./assets/stock-management.gif" alt="Interactive Swagger Documentation" width="700"/>
  </a>
</p>

## 📚 Navigation
- [🚀 Live API Documentation](#-live-api-documentation)
- [📦 Key Features](#-key-features)
- [🛠️ Built With](#️-built-with)
- [⚙️ Setup & Installation](#️-setup--installation)
- [📊 Data Model (ERD)](#-data-model-erd)
- [📬 Contact Information](#-contact-information)



## About This Project

This project allows users to easily register and log in via their Google account with Django. 
Its main features are:

- Fast and secure authentication with Google account.
- Support registration and login with traditional username and password.
- Social authentication management with Django Allauth.
- User-friendly message notifications and stylish design with Bootstrap.

---

Bu proje, Django ile kullanıcıların Google hesabı üzerinden kolayca kayıt ve giriş yapmasını sağlamaktadır. 
Başlıca özellikleri şunlardır:

- Google hesabı ile hızlı ve güvenli kimlik doğrulama.
- Geleneksel kullanıcı adı ve şifre ile kayıt ve giriş desteği.
- Django Allauth ile sosyal kimlik doğrulama yönetimi.
- Kullanıcı dostu mesaj bildirimleri ve Bootstrap ile şık tasarım.

<!-- OVERVIEW -->

## Overview

### Social Account Authentication
<!-- ![screenshot](project_screenshot/Social_Account_Auth_App.gif) -->
<img src="project_screenshot/Social_Account_Auth_App.gif" alt="Social Account Authentication" width="400"/>
➡ The screen where users log in with their Google accounts and access the home page.

---


## Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->
This project was developed using the following tools and libraries:

- [Django Templates](https://docs.djangoproject.com/en/5.1/topics/templates/): For creating dynamic web pages.
- [Bootstrap5](https://getbootstrap.com/docs/5.0/getting-started/introduction/): To provide a responsive and modern user interface.
- [django-crispy-forms](https://django-crispy-forms.readthedocs.io/en/latest/): To easily style forms.
- [django-allauth](https://django-allauth.readthedocs.io/en/latest/index.html) - Social Account Authentication Management



## How To Use

<!-- This is an example, please update according to your application -->

To clone and run this application, you'll need [Git](https://github.com/Umit8098/Project_Django_Templates_Todo_App_FB_Authantication-1_CH-11)

When installing the required packages in the requirements.txt file, review the package differences for windows/macOS/Linux environments. 

Complete the installation by uncommenting the appropriate package.

---

requirements.txt dosyasındaki gerekli paketlerin kurulumu esnasında windows/macOS/Linux ortamları için paket farklılıklarını inceleyin. 

Uygun olan paketi yorumdan kurtararak kurulumu gerçekleştirin.

```bash
# Clone this repository
$ git clone https://github.com/Umit8098/Project_Django_Templates_Todo_App_FB_Authantication-1_CH-11.git

# Install dependencies
    $ python -m venv env
    $ python3 -m venv env (for macOs/linux OS)
    $ env/Scripts/activate (for win OS)
    $ source env/bin/activate (for macOs/linux OS)
    $ pip install -r requirements.txt
    $ python manage.py migrate (for win OS)
    $ python3 manage.py migrate (for macOs/linux OS)

# Create and Edit .env
# Add Your SECRET_KEY in .env file

# Google API Ayarları

For Google authentication, follow these steps:
Google kimlik doğrulaması için şu adımları takip edin:

1. [Google API Console](https://console.cloud.google.com/) Go to and create a new project.
2. "OAuth Consent Screen" configure settings.
3. Get `GOOGLE_CLIENT_ID` and `GOOGLE_SECRET` information from the "Credentials" tab.
4. Add this information to your `.env` file.


"""
# example .env;

SECRET_KEY =123456789abcdefg...

GOOGLE_CLIENT_ID={YOUR_GOOGLE_CLIENT_ID}
GOOGLE_SECRET={YOUR_GOOGLE_SECRET}

"""

# Run the app
    $ python manage.py runserver
```

## Key Features

- **Authentication with Google Account**: Users can quickly log in using their Google account.
- **Traditional Authentication**: Support user registration and login with email and password.
- **Profile Management**: Registered users can edit account information.
- **User Notifications**: Feedback is provided about the actions taken.

---

- **Google Hesabı ile Kimlik Doğrulama**: Kullanıcılar Google hesaplarını kullanarak hızlı giriş yapabilir.
- **Geleneksel Kimlik Doğrulama**: E-posta ve şifre ile kullanıcı kaydı ve giriş desteği.
- **Profil Yönetimi**: Kayıtlı kullanıcılar hesap bilgilerini düzenleyebilir.
- **Kullanıcı Bildirimleri**: Yapılan işlemler hakkında geri bildirim sağlanır.


## 📬 Contact Information

I am open to discussing backend architecture, API design, and professional collaborations.

* **LinkedIn:** [linkedin.com/in/umit-arat](https://www.linkedin.com/in/umit-arat/)
* **Email:** [umitarat8098@gmail.com](mailto:umitarat8098@gmail.com)
* **GitHub:** [github.com/umitarat-dev](https://github.com/umitarat-dev) (Current Workspace)
