# Description

WP_erfolgsrechnung is a Wordpress Plugin to allow simplified bookings and financial overview.

The code is an extract and modification under the AGPL license from the following original copyrighted source:

=== Plugin Name ===
- Plugin Name: WP Accounting
- Plugin URI: http://www.advancedstyle.com
- Description: Simple accounting system for recording income and expenses
- Version: 0.7.2
- Author: David Barnes
- Author URI: http://www.advancedstyle.com
- License: AGPLv3.0 or later
- License URI: http://opensource.org/licenses/AGPL-3.0
- Contributors: dave111223

The Plugin was obtained originally from the wordpress repository (no more downloadable): https://wordpress.org/plugins/wp-accounting and modified on 21.06.2023.

# Description

This heavy modified Plugin is dedicated to small Swiss companies, especially, without any comsiderations for VAT taxes. However, it might not provide full ledger requirements and might be used in conjunction withe a larger booking system as a master. 
It is currently in experimental, development, testing state and should not be used in production environment 
(There are some conceptional and technical bugs and you should not risk wrong analysis of your financial situation or a break on a successful running wordpress installation).
However, you are free to try out this plugin at your own risk, highly recommended on a test environment only.

# Functionalities

- It allows to do some bookings, having the Swiss standard of account bookings via "Soll" and "Haben". 
- In addition you can define and add some Cost Centres in the transactions. 
- Further, you can mark some specific cost centres as public and use the shortcode [public_projects] to show a list with these cost centres and Details to the public (with the idea to use a cost centre for a specific project, you want to show as a list to the public, like a portfolio).
- You also  will have an overview in the dashboard of accounts and cost centres based on cost and income accounts.
- Finally, there is a detail menu link, which shows you the accounts and bookings on a raw detailed view, you might use in adjusted form for your dedicated bookkeeping application.

# Concept
  
- Some Functions and views are still very basic and on the post type setup, not a lot has been changed, if not really needed, allowing you to use it as prototype for other projects.
- the architecture has been separated as good as possible to allow extensions (there are som compromises).




