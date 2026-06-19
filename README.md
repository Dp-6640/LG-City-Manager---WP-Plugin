# LG City Manager

LG City Manager is a WordPress plugin for managing city-specific service pages, dynamic location switching, and URL rewriting for HVAC and local service websites.

It helps store the selected city, rewrite internal links based on location rules, manage full and selective locations, and control city/service mapping from the WordPress dashboard without editing code.

## Features

- City selection and persistence using localStorage and cookies
- Dynamic URL rewriting for city and service pages
- Full location and selective location handling
- 404 and fallback redirect handling
- Reverse osmosis path support
- Admin dashboard for managing:
  - locations
  - services
  - sub-services
  - plugin settings
- AJAX-based saving for easier admin updates
- Front-end toolbar city switcher
- Debug mode for troubleshooting

## Requirements

- WordPress
- PHP 7.4 or higher
- JavaScript enabled in the browser

## Installation

1. Upload the plugin folder to `/wp-content/plugins/`
2. Activate the plugin from the WordPress admin panel
3. Configure locations and services from the plugin dashboard
4. Save settings and test city-based URLs on the front end

## Usage

- Add city pages under your location structure
- Configure full locations and selective locations in the dashboard
- Set up services and sub-services
- Use the generated URLs for city-specific service routing
- Test redirects and link behavior on live and staging sites

## Plugin Structure

```text
lg-city-manager/
├── lg-city-manager.php
├── readme.txt
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── includes/
├── admin/
└── README.md
