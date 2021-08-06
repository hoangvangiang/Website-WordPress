=== Easy WP SMTP ===
Contributors: wpecommerce
Donate link: http://wp-ecommerce.net/?p=2197
Tags: mail, wordpress smtp, phpmailer, smtp, wp_mail, email, gmail, outgoing mail, privacy, security, sendmail, ssl, tls, wp-phpmailer, mail smtp, wp smtp
Requires at least: 3.0
Tested up to: 3.8
Stable tag: 1.0.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily send emails from your WordPress blog using your preferred SMTP server

== Description ==

Easy WP SMTP allows you to configure and send all outgoing emails via a SMTP server. This will prevent your emails from going into the junk/spam folder of the recipients.

= Easy WP SMTP Features =

* Send email using a SMTP sever.
* You can use Gmail, Yahoo, Hotmail's SMTP server if you have an account with them.
* Seamlessly connect your WordPress blog with a mail server to handle all outgoing emails (it's as if the email has been composed inside your mail account).
* Securely deliver emails to your recipients.

= Easy WP SMTP Plugin Usage =

Once you have installed the plugin there are some options that you need to configure in the plugin setttings (go to `Settings->Easy WP SMTP` from your WordPress Dashboard).

**a)** Easy WP SMTP General Settings

The general settings section consists of the following options

* From Email Address: The email address that will be used to send emails to your recipients
* From Name: The name your recipients will see as part of the "from" or "sender" value when they receive your message
* SMTP Host: Your outgoing mail server (example: smtp.gmail.com)
* Type of Encryption: none/SSL/TLS
* SMTP Port: The port that will be used to relay outbound mail to your mail server (example: 465)
* SMTP Authentication: No/Yes (This option should always be checked "Yes")
* Username: The username that you use to login to your mail server
* Password: The password that you use to login to your mail server
* Enable Debug: Use this option if you are having issues with sending emails since it allows you to see the SMTP debug output on the screen.

For detailed documentation on how you can configure these options please visit the [Easy WordPress SMTP](http://wp-ecommerce.net/easy-wordpress-smtp-send-emails-from-your-wordpress-site-using-a-smtp-server-2197) plugin page

**b)** Easy WP SMTP Testing & Debugging Settings

This section allows you to perform some email testing to make sure that your WordPress site is ready to relay all outgoing emails to your configured SMTP server. It consists of the following options:

* To: The email address that will be used to send emails to your recipients
* Subject: The subject of your message
* Message: A textarea to write your test message.

Once you click the "Send Test Email" button the plugin will try to send an email to the recipient specified in the "To" field.

== Installation ==

1. Go to the Add New plugins screen in your WordPress admin area
1. Click the upload tab
1. Browse for the plugin file (easy-wp-smtp.zip)
1. Click Install Now and then activate the plugin
1. Now, go to the settings menu of the plugin and follow the instructions

== Frequently Asked Questions ==

= Can this plugin be used to send emails via SMTP? =

Yes.

== Screenshots ==

For screenshots please visit the [Easy WordPress SMTP](http://wp-ecommerce.net/easy-wordpress-smtp-send-emails-from-your-wordpress-site-using-a-smtp-server-2197) plugin page

== Changelog ==

= 1.0.1 =

* First commit of the plugin

= 1.0.2 =

* Fixed a bug where the debug output was being displayed on the front end

= 1.0.3 =

* Added a new option to the settings which allows a user to enable/disable SMTP debug

= 1.0.4 =

* Plugin is now compatible with WordPress 3.6

= 1.0.5 =

* "Reply-To" text will no longer be added to the email header
* From Name field can now contain quotes. It will no longer be converted to '\'

= 1.0.6 =

* Plugin is now compatible with WordPress 3.7

= 1.0.7 =

* Plugin now works with WordPress 3.8

== Upgrade Notice ==
none
