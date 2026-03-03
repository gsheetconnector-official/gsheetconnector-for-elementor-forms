=== GSheetConnector for Elementor Forms – Sync Elementor Forms to Google Sheets ===
Contributors: westerndeal, abdullah17, gsheetconnector
Donate link: https://www.paypal.me/WesternDeal
Author URI: https://www.gsheetconnector.com/
Tags: elementor google sheets, elementor forms to google sheets, metform google sheets, sync elementor to google sheets, google spreadsheet integration, elementor automation, export elementor form entries
Requires at least: 5.6
Tested up to: 6.9
Requires PHP: 7.4
Stable tag: 1.2.9
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Sync Elementor Forms and MetForm to Google Sheets in real-time with secure Google Sheets integration and automatic form submission sync.

== Description ==

**GSheetConnector for Elementor Forms** is a powerful **Elementor Google Sheets integration plugin** that connects Elementor Forms and MetForm directly to Google Sheets.

GSheetConnector acts as a secure bridge between your WordPress site, Elementor Pro Forms or MetForm, and Google Sheets — enabling real-time form submission sync and automated spreadsheet management without manual exports.

Automatically sync Elementor form submissions to Google Sheets in real-time and eliminate manual exports, CSV downloads, or copy-paste workflows. Every submission is securely transferred to your selected Google Spreadsheet instantly after form submission.

Whether you collect leads, contact inquiries, bookings, registrations, or customer data, GSheetConnector ensures reliable Google Sheets sync and structured spreadsheet management directly from your WordPress site.

Built specifically for Elementor Pro Forms and MetForm, this plugin delivers seamless Google Sheets integration with secure authentication and automatic data synchronization.

---

== Why Choose GSheetConnector? ==

✔ Sync Elementor Forms to Google Sheets instantly  
✔ Direct Google Sheets integration without third-party automation tools  
✔ Support for Elementor Pro and MetForm  
✔ Secure Google OAuth 2.0 authentication  
✔ Automatic sheet column creation and mapping  
✔ Lightweight, fast, and performance optimized  

Built specifically for Elementor Pro Forms and MetForm users who need secure, real-time Google Sheets integration and reliable form submission sync.
---

== How Elementor to Google Sheets Sync Works ==

When a visitor submits an Elementor Form (Elementor Pro) or MetForm (Free or Pro), GSheetConnector automatically syncs the form submission to Google Sheets in real-time by creating a new row in your connected Google Spreadsheet.

All form field types, including advanced fields, are fully supported. The plugin can also record submission metadata such as submission date and time, IP address, and additional entry details for structured spreadsheet management.

Secure Google OAuth authentication ensures safe data transfer without complex API configuration.

---

== Core Features (Free Version) ==

= 🔄 Real-Time Elementor Forms to Google Sheets Sync =
Automatically sync Elementor Forms and MetForm submissions to Google Sheets in real-time. Each form submission is added as a new row in your connected Google Spreadsheet.

= ⚡ One-Time Google Authentication =
Authenticate once with Google and enable continuous automatic form submission sync without repeated setup or manual exports.

= 📊 Field & Column Mapping =
Map Elementor form fields directly to Google Sheet columns for structured spreadsheet integration.

= 🕒 Submission Date Capture =
Automatically record submission date with every form entry added to Google Sheets.

= 📥 View Connected Google Spreadsheet =
Access and open your linked Google Sheet directly from plugin settings.

= 🔐 Secure Google OAuth Authentication =
Includes simple one-click Google authentication using official Google Sheets and Google Drive APIs for secure data transfer.

= ⚙ Full Compatibility =
Works with Elementor Pro Forms, MetForm (Free & Pro), latest WordPress versions, and modern PHP environments.

== Live Demo ==

Homepage: https://www.gsheetconnector.com/  
Documentation: https://www.gsheetconnector.com/docs/elementor-google-sheet-connector  
Support: https://www.gsheetconnector.com/support  
Demo: https://demo.gsheetconnector.com/elementor-forms-gsheetconnector-pro/  
Premium Version: https://www.gsheetconnector.com/elementor-forms-google-sheet-connector-pro  

---

== 🛠️ How to Send Elementor Forms Entries to Google Sheets ==

After installing and activating GSheetConnector, follow these simple steps:

= Step 1: Authenticate with Google =
Use the one-click Google authentication button to securely connect your WordPress site to your Google Sheets account.

= Step 2: Configure Sheet Details =
Enter your Google Sheet Name, Sheet ID, Tab Name, and Tab ID inside the GSheetConnector settings or directly within the Elementor Form editor under “Actions After Submit” → select “GSheetConnector” and add your sheet details.

= Step 3: Match Form Fields with Sheet Columns =
Ensure your Google Spreadsheet has column headers in the first row that match your Elementor form field labels. Each form submission will populate the corresponding columns automatically.

Save the form and submit a test entry — your data will instantly sync to Google Sheets in real-time.

---

== Video Tutorial ==

How to Install, Authenticate, and Integrate Elementor Forms with Google Sheets:

https://youtu.be/m7hy8lQRFrg

---
== 🚀 Pro Features ==

Upgrade to Elementor Forms Google Sheets Connector PRO for advanced Elementor Google Sheets automation and enhanced control over your form data synchronization.

= 📑 Automatic Header Creation =
Automatically generate Google Sheet column headers based on your Elementor form field labels — no manual column setup required.

= 🔁 Synchronize Existing Entries =
Sync previously submitted Elementor or MetForm entries to Google Sheets with a single click.

= 📊 Advanced Field & Column Management =
Edit, reorder, enable, or disable specific form fields before syncing to your Google Spreadsheet.

= 🕒 Extended Submission Metadata =
Capture additional entry details including submission time, IP address, browser information, and extended metadata for better tracking.

= ❄ Freeze Header Rows =
Enable freeze header rows in Google Sheets for improved spreadsheet navigation and structured data viewing.

= 🎨 Header & Row Styling =
Customize header colors and alternate row styling for better spreadsheet readability.

= 🔐 Manual API & Service Account Authentication =
Supports **manual Google API credential configuration** and **Service Account authentication** for advanced or enterprise-level setups.

= ⚙ Enhanced Control & Flexibility =
Designed for agencies, developers, and businesses that require secure, scalable Elementor to Google Sheets integration.

---

== Important Notes ==

Ensure your Google Sheet Name, Sheet ID, Tab Name, Tab ID, and Column Headers match exactly with the values entered in the plugin settings. Incorrect details may prevent proper Elementor to Google Sheets synchronization.

For best results:

• Use exact labels from your Elementor form fields as column headers in the first row of your Google Sheet  
• Avoid special characters in column names  
• Keep column headers consistent with your form field labels  

Proper formatting ensures accurate real-time form submission sync to Google Sheets.

---

== Frequently Asked Questions ==

= Why is my Elementor form submission spinning and not sending data to Google Sheets? =

If your Elementor form keeps spinning and does not complete submission, this usually indicates an authentication, configuration, or API issue.

First, go to the Integration tab and click the “View Debug Log” button to check detailed error information.

Ensure that WordPress debugging is enabled in your `wp-config.php` file.  
Refer to this guide to enable debugging:  
https://www.gsheetconnector.com/docs/general/how-to-enable-debugging-in-wordpress

Also confirm that your authenticated Google email address is visible under the Integration tab. If the email address is not displayed, reauthenticate your Google account.

If submissions are still not appearing in Google Sheets, copy the error logs and contact our support team at helpdesk@gsheetconnector.com or create a support ticket. Our team will assist you in resolving the issue.

---

= I configured the plugin, but Elementor form entries are not syncing to Google Sheets. What should I check? =

If your Elementor Forms are properly configured but entries are not appearing in Google Sheets, verify the following:

1. Google authentication is valid and not expired  
2. Sheet Name, Sheet ID, Tab Name, and Tab ID are entered correctly  
3. Column headers in Google Sheets exactly match your Elementor form field labels  

Avoid using dynamic mail tags or special placeholders as column header names. Column headers must match the actual form field labels.

Incorrect sheet configuration or mismatched column headers can prevent proper Elementor to Google Sheets synchronization.

= Can I sync multiple Elementor forms to different Google Sheets? =

Yes. You can connect each Elementor Form or MetForm to a different Google Spreadsheet by configuring separate sheet details.

In the Pro version, you can also create multiple feeds for a single form and sync the same form submission to multiple Google Sheets.

= Does this plugin work with Elementor Free? =

No. Elementor Pro is required because the Form widget is available only in the Pro version of Elementor.

= Is MetForm supported? =

Yes. GSheetConnector supports MetForm (Free & Pro versions) for Google Sheets integration and real-time form submission sync.

= What happens if the form confirmation email fails — will entries still sync? =

Yes. Form data is sent to Google Sheets before the confirmation email is triggered, ensuring your form submissions are safely recorded.

= Can I reorder or edit Google Sheet columns? =

Advanced column management, including reordering and editing headers, is available in the Pro version.

= Can I freeze header rows in Google Sheets? =

Yes. The Pro version includes the option to freeze header rows for improved spreadsheet readability.

= Why do I see a “This app isn’t verified” warning during Google authentication? =

This may appear when using custom Google API credentials for manual authentication (Pro version). Click “Advanced” and proceed to continue authentication. This is safe when configuring your own Google project.

The free version uses simplified one-click Google authentication and does not require manual API configuration.

= Why do I see a “Range exceeds grid limits” error in Google Sheets? =

This error occurs when your Google Sheet has reached its row or column limit. Increase the number of rows or columns in your Google Spreadsheet to resolve the issue.

= Is manual Google API configuration required? =

No. The free version supports simple one-click Google authentication.

Manual API credentials and Service Account authentication are available in the Pro version for advanced or enterprise-level setups.

---


== Installation ==

1. Upload `gsheetconnector-for-elementor-forms` to the `/wp-content/plugins/` directory, or install it directly from the WordPress Plugins screen.  
2. Activate the plugin through the WordPress **Plugins** menu.  
3. Navigate to **Elementor Form → Google Sheets** in your WordPress admin dashboard.  
4. Authenticate your Google account and configure your sheet details.  

Your Elementor Forms and MetForm submissions will now sync to Google Sheets in real-time.

== Screenshots ==

1. Google Sheet Authentication Screen  
2. Elementor Form Settings  
3. Feed Configuration  
4. System Status  
5. Extensions  

---

== Changelog ==

= 1.2.9 (25-02-2026) =
* Added: Compatibility for Elementor Landing Pages in the Feed Settings dropdown.

= 1.2.8 (20-02-2026) =
* Fixed: Compatibility issues with GSheetConnector for Elementor Free and Pro.

= 1.2.7 (16-02-2026) =
* Fixed: Data not being saved to the Google Sheet if sheet settings are done under Elementor Page -> Form -> GSheetConnector ( Action After Submit ).

= 1.2.6 (24-12-2025) =
* Fixed: An issue where special characters (such as &, ", and ') were being encoded when syncing form data. Input values are now properly sanitized before saving to Google Sheets.

= 1.2.5 (21-11-2025) =
* Fixed: Responsive CSS.

= 1.2.4 (24-09-2025) =
* Updated: Readme file updated.
* Fixed: UI improvements.
* Added: Extensions tab.

= 1.2.3 (05-09-2025) =
* Fixed: security issue while fetching sheet details on Integration page and Elementor editor.

= 1.2.2 (07-08-2025) =
* Fixed : After selecting a sheet and a tab name in the Elementor widget, the tab name selection disappears (gets removed) after some time — possibly after page reload or re-render.
* Fixed : MetForm compatibility for form feeds.

= 1.2.1 (21-07-2025) =
* Fixed: Solved  Licensing/Trademark issues in main plugin file and readme.
* Removed direct links to 5-star reviews to comply with WordPress plugin guidelines.
* Updated “Tested Up To” value to reflect compatibility with the latest WordPress version.
* Replaced static <script> and <link> tags with wp_enqueue_script and wp_enqueue_style for proper asset loading and dependency management.
* Eliminated all remote file inclusions to improve security and meet WordPress repository requirements.
* Removed plugin folder write operations and any instructions requiring users to manually edit/write files inside the plugin directory.
* Escaped all variables and options before outputting to the frontend or admin interface.
* Replaced generic function/class/constant/option names with properly prefixed versions to avoid naming collisions.
* Corrected text domain to match the plugin slug for consistent internationalization support.
* Blocked direct file access by adding appropriate file-level checks (e.g., defined( 'ABSPATH' ) || exit;).
* Implemented proper nonce verification and security best practices throughout AJAX and form submissions.
* Passed Plugin Check review with all critical issues resolved.

= 1.0.25 = (17-06-2025)
* Improved: MetForm settings are now organized under the "Form Feed Settings" section for better accessibility.
* Added: Manual sheet configuration options are now available within the Elementor form's Page Settings panel.
* Added: Date and time fields are now included in MetForm submissions.
* Enhanced: A new section showcasing MetForm PRO features has been added.
* Added: Date and time fields are now included in elementor form submissions.
* Added: "Run Activation" button to resolve the "Something went wrong!" error if it appears.

= 1.0.24 = (21-04-2025)
* Added: Moved saving of credentials to database for Auto API Integration.

= 1.0.23 = (05-02-2025)
* Fixed : Minor UI changes.

= 1.0.22 = (03-02-2025)
* Fixed : Uncaught fatal error (json_decode).

= 1.0.21 = (27-01-2025)
* Fixed : Minor UI changes.

= 1.0.20 = (04-01-2025)
* Added PRO showcase: Date Filter for Sync - Added a date filter option to streamline syncing for users handling large data entries.
* Added: Advanced Feed Settings - Introduced an improved configuration system for better usability.
* Added: The "Copy Log" button has been added.
* Deprecated: Manual Client/Secret Key - Replaced with Google API Configuration for enhanced security and simplicity.
* Fixed: Enhanced Form Feed Settings UI - Upgraded the user interface for improved design and usability.
* Fixed: Addressed various CSS issues and made small adjustments for a smoother experience.
* Fixed: CF7 GSheetConnector Conflict Resolved - Fixed compatibility issues for seamless integration.
* Fixed: Undefined error when clicking the "Copy to Clipboard" button in the System Info tab.
* Fixed: The issue with the Debug Log view and the close button has been fixed.
* Fixed: Dashboard widget formatting has been improved.

= 1.0.19 = (21-08-2024)
* Fixed : Google hasn’t verified this app error.

= 1.0.18 = (15-07-2024)
* Fixed: Some fields to show in sheet, while Enabling Manual Adding Headers for Fields entering into the Google Sheet.
* Added: UI changes for showcasing PRO Features.

= 1.0.18-beta1 = (01-07-2024)
* Compatibility : Compatible with PRO Elements Plugin.

= 1.0.17 = (04-05-2024)
* Fixed : undefined array key issues.

= 1.0.16 = (12-04-2024)
- UI Changes.

= 1.0.15 = (07-03-2024)
* UI and Add links for support,docs,upgrade to pro.
* Changed UI of MetForm Settings Page.

= 1.0.14 = (12-01-2024)
* Fixed data saving issue when both free and pro versions are active. 
* Fixed plugin not getting activated for multisite setup.

= 1.0.13 = (30-12-2023)
* Fixed validate parent plugin exists or not then show alert message display issue.

= 1.0.12 = (18-12-2023)
* Compatible with metform to send metforms submissions to google sheet, option given in Elementor --> Google Sheet, Metform Tab will be seen if Metforms is installed.

= 1.0.11 = (26-10-2023)

* Updated Google API Client Library to Version-2.12.6
* Redesigned plugin Debug log, System Status and WordPress debug log view for improved functionality and user experience.
* Developed a streamlined mechanism of Debug Log View And Close.
* For users without Google Drive and Google Sheets permissions for Authentication displayed an alert with a message.
* Fixed plugin not getting activated for multisite setup.

= 1.0.10 = (14-08-2023)

* Fixed Vulnerability to ensure data security.
* UI Changes.
* Added system status tab to assists in troubleshooting.

= 1.0.9  = (05-07-2023)
* Updated Freemius SDK version to 2.5.10

= 1.0.8 = (17-05-2023)
* compatible with pro-element plugins.


= 1.0.7 = (27-04-2023)
* Fixed : Vulnerabilities issue resolved.

= 1.0.6 = (16-03-2023)
* Fixed : New tabs are not showing in google sheet tab drop-down.

= 1.0.5 = (06-03-2023)
* Fixed : Solved compatiblity issue with Elementor Forms Google Sheet Connector Pro plugins with header of google sheet.
* Fixed : Permission validation displayed with authentication of google, if not given permissions.

= 1.0.4 = (30-11-2022)
* Fixed : Solved compatiblity issue with Elementor Forms Google Sheet Connector Pro plugins.

= 1.0.3 = (10-11-2022)
* Fixed : undefined class issues.

= 1.0.2 = (31-10-2022)
* Freemius Integration.

= 1.0.1 = (29-10-2022)
* Added Screenshot

= 1.0.0 =
* First public release
* Integrated Elementor Form with Google sheets.

# gsheetconnector-for-elementor-forms
Elementor Forms Google Sheet Connector
