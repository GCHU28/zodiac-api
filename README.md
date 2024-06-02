Random Zodiac Plugin by GCHU28 Github
Description
The Random Zodiac Plugin is a WordPress plugin designed to generate random zodiac signs via a REST API. This plugin includes a shortcode for displaying the generated zodiac signs on your website and saves the generated signs to the database. It also provides an admin settings page to control allowed IP addresses for accessing the API.

Features
Generate Random Zodiac Signs: Fetch and display three random zodiac signs with associated images and numbers.

IP Restriction: 

Only allows access to the API for specific IP addresses configured in the settings.
Admin Settings Page:
Easily manage allowed IP addresses from the WordPress admin dashboard.
Database Integration: 
Saves the generated zodiac signs to the WordPress database.
Shortcode Support: 
Use the [display_random_zodiac] shortcode to display the random zodiac signs on any post or page.
AJAX Save: 
Automatically save the generated zodiac signs to the database via an AJAX request.
Custom Styles: 
Includes custom CSS for styling the zodiac sign display.
Installation

Upload the Plugin:

Download the plugin files and upload them to the /wp-content/plugins/random-zodiac-plugin directory.
Alternatively, upload the zip file through the WordPress admin interface.
Activate the Plugin:

Go to the 'Plugins' menu in WordPress and activate the Random Zodiac Plugin.
Configure Settings:

Navigate to 'Settings' -> 'Custom Settings' to set the allowed IP addresses for API access.
Usage
Display Random Zodiac Signs
Use the [display_random_zodiac] shortcode to display the random zodiac signs on any page or post.
Use the [latest_zodiac_values] shortcode to display the latest saved zodiac values from the database.
Shortcode Example
[display_random_zodiac]
[latest_zodiac_values]
IP Restriction
Add the allowed IP addresses in the settings page under 'Settings' -> 'Custom Settings'. Multiple IP addresses should be separated by commas.
Development
REST API Endpoint
Endpoint: 
/wp-json/random-zodiac/v1/generate
Method: GET
Description: 
Generates three random zodiac signs with English and Chinese names, images, and numbers.
AJAX Actions
Save Zodiac Signs to Database:
AJAX action: 
save_zodiac_to_database
Endpoint: 
admin-ajax.php
Method: POST
Enqueue Styles
Custom styles for displaying zodiac signs are enqueued automatically when using the plugin.
Admin Settings Page
The plugin adds a custom settings page under 'Settings' -> 'Custom Settings' for managing allowed IP addresses.
License
This plugin is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Contributions are welcome! Please submit a pull request or open an issue for any bugs or feature requests.

Author
Zodiac - GCHU28 Developer of the Random Zodiac Plugin
