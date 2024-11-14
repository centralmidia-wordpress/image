# AnytoWEBP noGif Secure

**Version:** 1.1  
**Author:** Daniel Oliveira da Paixao  
**License:** GPL v2 or later

## Overview

The **AnytoWEBP noGif Secure** plugin for WordPress converts uploaded images (excluding GIFs) into the WebP format, providing optimized file sizes and faster loading times without sacrificing quality. This plugin also includes options to resize images, maintain the original aspect ratio, preserve or delete original files after conversion, and ensure security for uploads. Large images are resized to prevent performance issues, and you can configure quality, EXIF data preservation, and memory usage limits.

## Features

- Converts uploaded images (JPEG, PNG) to WebP format, excluding GIF files.
- Resizes images to a maximum dimension you set (default: 1200 pixels).
- Maintains the original aspect ratio during resizing.
- Configurable quality settings for WebP images (default: 80).
- Option to delete the original image file after conversion to WebP.
- Option to preserve EXIF metadata for converted images.
- Supports secure file renaming using post IDs.
- Compatibility checks for PHP, WordPress, and WebP support.
- Admin settings panel for customization.

## Requirements

- **PHP version**: 7.4 or higher.
- **WordPress version**: 5.3 or higher.
- **WebP support**: Requires PHP with WebP support enabled.

## Installation

1. Download the plugin and upload it to your WordPress installation in the `wp-content/plugins` directory.
2. Activate the plugin through the WordPress Plugins menu.
3. After activation, the plugin will check for compatibility with your WordPress and PHP versions.
4. Configure settings under **Settings > AnytoWEBP** in the WordPress admin dashboard.

## Usage

Once activated, the plugin will automatically convert eligible images (JPEG and PNG) to WebP format upon upload. Admins can customize the following settings from the plugin options page:

- **WebP Quality**: Adjust the quality for converted WebP images (1-100).
- **Max Dimension**: Set the maximum dimension (in pixels) for images. Large images will be resized.
- **Delete Original**: Enable to delete the original image file after conversion.
- **Preserve EXIF**: Enable to retain EXIF metadata in the converted image.

### Logging

If `WP_DEBUG` mode is enabled, the plugin logs both successful conversions and errors for troubleshooting.

## Troubleshooting

If the plugin is deactivated due to requirements not being met, ensure that:
- PHP is updated to at least version 7.4.
- WordPress is updated to version 5.3 or higher.
- PHP WebP support is enabled (check with your hosting provider if unsure).

## License

This plugin is open-source software licensed under the [GPL v2 or later](https://www.gnu.org/licenses/gpl-2.0.html).

---

For more information or questions, please visit the plugin author’s website: https://rd5.com.br/dev
