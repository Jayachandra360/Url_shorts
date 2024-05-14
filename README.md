# Url_shorts

# SelfShort

SelfShort is a self-hosted URL shortening service that gives users full control over their links. It is designed to be lightweight, easy to install, and customizable to fit specific needs. With SelfShort, users can enjoy the convenience of URL shortening while maintaining data privacy and stability.

## Features

- **Self-Hosting**: Host the URL shortening service on your own web server, ensuring data privacy and stability.
- **LAMP Stack Compatibility**: Compatible with a standard LAMP (Linux, Apache, MySQL, PHP) stack for easy installation and integration.
- **Simple Installation**: Clone the repository, import the database, and configure settings to get started quickly.
- **Customizable Configuration**: Customize settings such as URL length, allowed characters, and password protection.
- **Click-Through Statistics**: Track visits to shortened links and view click-through statistics.
- **Support for Various URL Schemes**: Supports URLs with any scheme, making it suitable for deep-linking into mobile and desktop applications.
- **JSON API**: Access a simple URL-based API, with support for JSON responses.

## Installation

1. Clone the repository into your web server directory:

```bash
git clone https://github.com/your_username/selfshort.git
```

2. Import the provided `database.sql` file into a MySQL database.

3. Edit the configuration settings in `config.php` to customize the service according to your preferences.

4. Ensure that mod_rewrite rules are enabled for Apache2 to process the `.htaccess` file.

## Usage

- To create a new short link, append the full URL to be shortened to the SelfShort domain.
- Access click-through statistics by visiting the `/stats/` endpoint on the domain.

## Requirements

- Apache2 with mod_rewrite enabled
- PHP 5.4+ or 7+
- MySQL

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to contribute to the development of SelfShort.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize and expand upon this README file to include any additional information or instructions specific to your project.
