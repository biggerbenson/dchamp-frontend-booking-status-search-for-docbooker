=== Dchamp Frontend Booking Status Search for DocBooker ===
Contributors: biggerbenson
Tags: booking search, appointment lookup, docbooker, frontend search, ajax
Requires at least: 5.8
Tested up to: 6.9
Requires PHP: 7.4
Stable tag: 1.2.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Frontend booking status search for DocBooker sites. Allows visitors to securely search booking details using Booking ID only.

== Description ==

Dchamp Frontend Booking Status Search for DocBooker is a lightweight frontend search plugin designed for websites using the DocBooker booking system.

It enables patients or clients to check their booking details using a unique Booking ID, without logging in or accessing the WordPress admin dashboard.

The plugin is secure, fast, and easy to use, making it ideal for medical facilities, clinics, appointment-based services, and booking platforms powered by DocBooker.

Ideal for:
* Clinics & hospitals
* Medical booking systems
* Appointment-based service providers
* Any website using DocBooker booking tables

== Features ==

* Booking ID–only search (no names or emails)
* AJAX-powered instant search results
* Clean and modern frontend UI
* Secure input validation
* Works for logged-in users and guests
* Mobile-friendly and responsive
* Simple shortcode implementation
* No admin configuration required

== How It Works ==

Users enter a valid Booking ID (for example #WPDB-5932) into the search field.

If the booking exists, the plugin displays:
* Booking ID
* Patient full name
* Booking status
* Present status

If no booking is found, a friendly message is displayed.

== Installation ==

1. Download the plugin ZIP file
2. Go to WordPress Admin → Plugins → Add New → Upload Plugin
3. Upload dchamp-frontend-booking-status-search-for-docbooker.zip
4. Activate the plugin
5. Add the shortcode to any page

== Usage ==

Place the shortcode below on any page or post:

[docbooker_search]

Only Booking IDs are accepted. Other inputs will be rejected for security reasons.

== Database Compatibility ==

This plugin works with DocBooker database tables including:
* wp_wpddb_bookings
* wp_wpddb_patients

The WordPress table prefix is detected automatically.

== Security ==

* Strict Booking ID validation
* Uses WordPress AJAX APIs
* Read-only access
* No sensitive data exposure


== Ownership & Links ==

Plugin URL: https://dchamplegacy.com/plugins/docbooker-search/
Author URL: https://dchamplegacy.com/

== Screenshots ==

1. Booking ID search form
2. Successful booking search result
3. Booking not found message
4. Mobile responsive view

== Changelog ==

= 1.2.2 =
* Updated plugin name and metadata for clearer unaffiliated positioning
* Updated plugin and author URLs
* Added text domain header
* Added plugin header license fields
* Updated compatibility metadata for current WordPress
* Preserved existing frontend functionality and design

== Upgrade Notice ==

= 1.2.2 =
Recommended update. Aligns plugin naming and metadata with WordPress.org review requirements while preserving the same frontend functionality and design.

== Developer ==

Dchamp Legacy
https://dchamplegacy.com
