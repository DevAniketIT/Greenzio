# Greenzio

A modern, comprehensive web-based e-commerce platform designed specifically for grocery stores and food retailers. The Greenzio provides a complete solution for managing online grocery operations with separate customer and administrative interfaces, real-time inventory management, and secure payment processing.

Built with PHP, MySQL, and Bootstrap 5, this platform offers a professional-grade solution for grocery retailers looking to establish or enhance their online presence. The system features a mobile-first responsive design, advanced security measures, and a complete RESTful API for seamless integration.

## Key Features

- **Complete E-commerce Platform** - Full-featured online grocery shopping experience
- **Dual-Interface System** - Separate customer shopping portal and comprehensive admin panel
- **Real-time Inventory Management** - Live stock tracking with automated low-stock alerts
- **Advanced Shopping Cart** - Session-based cart with save-for-later functionality
- **Secure Payment Processing** - Multiple payment gateway integration with PCI compliance
- **Order Management System** - Complete order lifecycle from placement to delivery tracking
- **User Authentication & Authorization** - Role-based access control with secure session management
- **RESTful API** - JSON-based API for mobile app integration and third-party services
- **Responsive Design** - Mobile-optimized interface using Bootstrap 5
- **Advanced Security** - CSRF protection, SQL injection prevention, and comprehensive input validation
- **Product Catalog Management** - Category organization with image management and bulk operations
- **Customer Dashboard** - Order history, profile management, and account features
- **Admin Analytics** - Sales overview, inventory reports, and customer insights

## System Requirements

**Minimum Requirements:**
- **Web Server:** Apache 2.4+ or Nginx 1.18+
- **PHP:** Version 7.4 or higher (PHP 8.1+ recommended)
- **Database:** MySQL 5.7+ or MariaDB 10.4+
- **Memory:** 512MB RAM minimum (2GB+ recommended for production)
- **Storage:** 1GB free disk space minimum

**Required PHP Extensions:**
- `pdo_mysql` - Database connectivity
- `mbstring` - Multibyte string handling
- `fileinfo` - File type detection
- `gd` - Image processing
- `curl` - HTTP requests
- `json` - JSON handling
- `session` - Session management
- `openssl` - Encryption support

## Quick Installation

1. **Download and Extract**
   ```bash
   git clone [repository-url] grocery-management-system
   cd grocery-management-system
   ```

2. **Database Setup**
   ```sql
   CREATE DATABASE gms CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
   mysql -u root -p gms < database/gms.sql
   ```

3. **Configure Application**
   - Edit `includes/config.php` with your database credentials
   - Set proper file permissions for uploads directory
   - Configure web server (Apache/Nginx)

4. **Complete Installation**
   - Navigate to your installation URL
   - Follow the setup wizard to create admin account
   - Configure initial categories and products

For detailed installation instructions, system requirements, and configuration options, please refer to our complete documentation.

## Documentation

📖 **[Complete Project Documentation](docs/PROJECT_DOCUMENTATION.md)**

The comprehensive documentation includes:
- Detailed installation guide with step-by-step instructions
- System architecture and database schema
- Security implementation and best practices
- API documentation with examples
- User guide for customers and administrators
- Deployment guide for production environments
- Troubleshooting and maintenance procedures

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Version Information

**Current Version:** 2.0  
**Release Date:** 2024  
**Status:** Production Ready

---

*Greenzio - Professional e-commerce solution for grocery retailers*
