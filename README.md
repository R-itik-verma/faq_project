# FAQ Management System

This project is a Django-based FAQ management system that supports multi-language translation, caching, and WYSIWYG editor integration. It provides a REST API to manage FAQs, supports different languages, and ensures fast responses using caching.

## Features

- Django models to store FAQs with multilingual support
- WYSIWYG editor (using `django-ckeditor`) for formatting answers
- REST API for fetching FAQs with language selection
- Google Translate API integration for automatic translation
- Redis caching to improve translation performance
- Admin panel for easy FAQ management
- Unit tests for models and API endpoints

## Prerequisites

Before setting up the project, make sure you have the following installed:

- Python 3.8+
- Django 4.x+
- Redis (for caching)
- Docker (optional for deployment)

## Installation

### 1. Clone the Repository

```bash
https://github.com/R-itik-verma/faq_project.git
