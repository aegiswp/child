# Aegis Child Theme

Welcome to the Aegis Child Theme repository.

Aegis Child is the blank canvas of the Aegis framework: clean by default, built for precise overrides, and ready for production customization.

Built to pair with its [parent theme](https://github.com/aegiswp/theme), Aegis Child keeps your customizations isolated from framework updates while giving you a focused layer for templates, patterns, global styles, and project-specific functionality.

![Aegis Child Theme](https://github.com/user-attachments/assets/f6108dab-38e7-41b1-b020-5100fa2b36c5)

##### Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Method 1: Using the WordPress Dashboard](#method-1-using-the-wordpress-dashboard)
  - [Method 2: Using FTP](#method-2-using-ftp)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

## Prerequisites

Before installing the Aegis Child Theme, ensure you have:
- The [Aegis Theme](https://github.com/aegiswp/theme) installed and activated.
- A working WordPress installation.

## Installation

### Method 1: Using the WordPress Dashboard
1. Download the latest `aegis-child.zip` release from the GitHub repository.
2. Navigate to your WordPress dashboard.
3. Go to `Appearance` > `Themes` > `Add New`.
4. Click on `Upload Theme`.
5. Choose the downloaded `.zip` file and click `Install Now`.
6. After the installation is complete, click `Activate`.

### Method 2: Using FTP
1. Extract the `aegis-child.zip` file.
2. Using an FTP client (like FileZilla), connect to your web server.
3. Navigate to the `/wp-content/themes/` directory.
4. Upload the extracted `aegis-child` folder here.
5. Once uploaded, go to your WordPress dashboard.
6. Navigate to `Appearance` > `Themes`.
7. You should see the Aegis Child Theme listed. Click `Activate`.

## Usage

After activating the Aegis Child Theme, you can start customizing it:

1. Go to `Appearance` > `Editor` in your WordPress dashboard.
2. All customization options will be available here. Any changes you make will not affect the parent theme.
3. Do not forget to click `Save` after making your desired changes.

## Support

For support, please raise [an issue](https://github.com/aegiswp/child/issues) in the GitHub repository.

## Contributing

Please read our [CONTRIBUTING.md](https://github.com/aegiswp/theme/blob/main/CONTRIBUTING.md) file for guidelines on how to contribute.

## Changelog

### 1.0.3 - 2026-05-04
* Clarified parent-child loading requirements, including the Template: aegis directory dependency (/wp-content/themes/aegis).
* Expanded installation and usage documentation to describe block theme inheritance and child override behavior.
* Updated theme package metadata to version 1.0.3 and aligned minimum PHP to 8.1.
* Added root theme compatibility file (index.php) guidance for distribution expectations.
* Aligned licensing with the parent theme (GNU GPL v2 or later) across headers, package metadata, docs, and LICENSE text.

### 1.0.2 - 2026-01-19
* Added GitHub Actions workflow for automated releases.
* Updated theme branding and description.
* Documentation improvements.

### 1.0.1 - 2025-07-11
* Set the version number to 1.0.1.

### 1.0.0 - 2023-11-01
* Initial release.

## License

The Aegis Child Theme is licensed under the GNU General Public License v2 or later, the same terms as the Aegis parent theme. For the full text, see the [LICENSE](LICENSE) file.

## Suggestions?

To propose improvements to this repository, please open an [issue](https://github.com/aegiswp/child/issues) or [pull request](https://github.com/aegiswp/child/pulls).