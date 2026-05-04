=== Aegis Child Theme ===
Contributors: atmostfearentertainment
Requires at least: 6.6
Tested up to: 6.9
Requires PHP: 8.1
Stable tag: 1.0.3
License: GNU General Public License v2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Tags: full-site-editing, block-patterns

== Description ==

Aegis Child is the blank canvas of the Aegis framework: clean by default, built for precise overrides, and ready for production customization.

Built to pair with its parent theme, Aegis Child keeps your customizations isolated from framework updates while giving you a focused layer for templates, patterns, global styles, and project-specific functionality.

== Installation ==

Before installing, ensure the Aegis parent theme is installed. You can activate the child theme even if the parent is not currently active, but the parent must be present on the server.

= Parent theme directory name =

The child theme header `Template: aegis` refers to the parent theme's directory name under `wp-content/themes/`, not the human-readable "Theme Name" in the parent's `style.css`. The folder must be exactly `aegis`. Official `aegis.zip` releases from the Aegis theme repository extract to that folder. If you are working from a git clone and the parent lives in a directory named `theme` (or any other name), copy or rename it to `aegis` inside `wp-content/themes/` before activating the child theme. Otherwise WordPress will report the child theme as broken or it will not load.

= Using the WordPress Dashboard =

1. Download the latest `aegis-child.zip` release from the GitHub repository.
2. From your WordPress dashboard, navigate to `Appearance` > `Themes` > `Add New`.
3. Click on `Upload Theme`.
4. Choose the downloaded `.zip` file and click `Install Now`.
5. After the installation is complete, click `Activate`.

= Using FTP =

1. Extract the `aegis-child.zip` file.
2. Using an FTP client (like FileZilla), connect to your web server.
3. Navigate to the `/wp-content/themes/` directory.
4. Upload the extracted `aegis-child` folder.
5. Once uploaded, go to your WordPress dashboard.
6. Navigate to `Appearance` > `Themes`.
7. You should see the Aegis Child Theme listed. Click `Activate`.

== Usage ==

After activating the Aegis Child Theme, you can start customizing it:

1. Go to `Appearance` > `Editor` in your WordPress dashboard.
2. All customization options will be available here. Any changes you make will not affect the parent theme.
3. Do not forget to click `Save` after making your desired changes.

== Support ==

For support, please raise an issue in the GitHub repository.

== Contributing ==

Please read our CONTRIBUTING.md file for guidelines on how to contribute.

== Changelog ==

= 1.0.3 - 2026-05-04 =
* Clarified parent-child loading requirements, including the Template: aegis directory dependency (/wp-content/themes/aegis).
* Expanded installation and usage documentation to describe block theme inheritance and child override behavior.
* Updated theme package metadata to version 1.0.3 and aligned minimum PHP to 8.1.
* Added root theme compatibility file (index.php) guidance for distribution expectations.
* Aligned licensing with the parent theme (GNU GPL v2 or later) across headers, package metadata, docs, and LICENSE text.

= 1.0.2 - 2026-01-19 =
* Added GitHub Actions workflow for automated releases.
* Updated theme branding and description.
* Documentation improvements.

= 1.0.1 - 2025-07-11 =
* Set the version number to 1.0.1.

= 1.0.0 - 2023-11-01 =
* Initial release