James Cook University Website Development README
Group 5 SP53 CP3402 Content Management Systems

### Overview

This document will provide all necessary information for subsequent developers (you can think of it as a template). This website was created using WordPress to promote openhouse related information.

### a2.html
This file contains our team's Names & Profiles, Goal/s, Project Links, Local Environments, References


### Local Development Environment
The website was developed using XAMPP v3.3.0 and vvv as the local server environment with WordPress 6.4.2 installed on it.
https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/vvv_xampp.png

Installation
---------------

### Prerequisites:

* XAMPP v3.3.0 
* WordPress 6.4.2
* Visual Studio Code
* Oracle VM VirtualBox VVV v.3.12

### Setup:

* Extract the WordPress 6.4.2.. ZIP archive to the htdocs directory in your XAMPP installation.
* Configure XAMPP to run the MySQL database and Apache server.
* Access the WordPress installation through https://localhost/wordpress-6.4.2/wordpress/ and complete the setup.
* Activate the custom theme from the WordPress admin dashboard under Appearance > Themes.

* For this project, access the staging/ live site through WP admin and export the backup through your choice of plug-in and import it to your WP environment.

### Theme Details
Name: School Open House

Base: Underscores

Main Technologies: PHP, JavaScript, HTML, CSS, MySQL

Custom Theme Files:
style.css: The main stylesheet.
functions.php: Theme functions and WordPress hooks.
header.php: The header template.
footer.php: The footer template.
index.php: The main template file.
page.php: Template for individual pages.
single.php: Template for single posts.
archive.php: Archive template.
Additional custom templates and partials are included within the theme directory.
### Workflow for Development
1. Pull the Latest Code: Team members must always have the latest version of the code to prevent duplication and meaningless work.
2. Develop Locally: Local modifications can be made in your XAMPP environment.
3. Test Changes: Extensively test your modifications in the neighborhood.
4. Commit: Every change must be committed to tell others what has been changed to improve work efficiency.
5. Push: Push your all the things to the remote repository.
6. We used VVV be our enbironment to test and set our projects.

![vvv](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/vvv_xampp.png)
![vvv](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/vvv.png)

### Deployment
Step 1: Install the All-in-One WP Migration Plugin on the Local Site
* Log in to your local WordPress site's admin dashboard.
* Go to "Plugins" -> "Add New."
* Search for "All-in-One WP Migration."
* Install and activate the "All-in-One WP Migration" plugin.
Step 2: Export Data from the Local Site
* In the WordPress admin dashboard, go to "All-in-One WP Migration."
* Hover over the menu item and select "Export."
* Choose "Export to File" in the export options.
* The plugin will start packaging your entire WordPress site and generate a .wpress file.
Step 3: Import the Local Site to SiteGround
* Log in to SiteGround's cPanel (or your hosting panel).
* Find and open the "MySQL Database" tool, and create a new database and user. Note the database name, username, and password.
* In cPanel, go to "File Manager" and enter the root directory of your website (usually public_html).
* Upload the previously exported .wpress file to the website's root directory.
* Access your website's root directory through a browser, find the uploaded .wpress file, and click on it. Choose the "Import" option, and the plugin will start importing the local site to SiteGround.
Step 4: Update WordPress Configuration
* Open SiteGround's cPanel, and find "File Manager."
* Enter the website's root directory, locate wp-config.php, right-click, and choose "Edit."
* Update the database name, username, and password to match the ones you created in Step 3.
* Save and close the file.

### Project Documentation
---------------

### Goals
* Deliver a product that serves as an effective digital front door that welcomes, informs, and converts visitors through a high-quality online experience that mirrors the institution's respectable standards.
* Increase conversion rate
* Increase acceptance rate: 5%
* Increase open house attendance rate: 10%

### Deployment

We considered a lot of software when choosing hosting, such as siteground and bluehost. In the end, we chose the former. Later, I will compare them in detail and summarize them in the end.


SiteGround: SiteGround is renowned for its high-speed performance, utilizing SSD storage, NGINX server technology, and the SuperCacher caching system.
Bluehost: Bluehost also provides good performance, but SiteGround is often considered more outstanding in this regard.
Price:


SiteGround: SiteGround's pricing is relatively higher, but it offers high-quality services.
Bluehost: Bluehost is generally more competitively priced, especially for startups.
Features:


SiteGround: SiteGround offers many advanced features, including automated backups, free SSL certificates, Content Delivery Network (CDN), and WordPress-specific optimizations.
Bluehost: Bluehost provides similar features, including free SSL certificates and built-in CDN, but some advanced features may be part of higher-tier plans.
Customer Support:


SiteGround: SiteGround is known for its excellent customer support, offering 24/7 live chat, email, and phone support.
Bluehost: Bluehost also offers 24/7 support, but some users consider SiteGround's support to be more responsive and professional.
Server Locations:


SiteGround: SiteGround has multiple data centers, allowing users to choose the geographical location of their website.
Bluehost: Bluehost also has multiple data centers, but the choices may be relatively limited.
Target Audience:


SiteGround: SiteGround is suitable for various websites, from small blogs to large enterprise sites.
Bluehost: Bluehost is widely used, particularly suitable for startups and personal websites.
Hosting Site: Siteground
The advantages of SiteGround include:


High-performance server configuration: SiteGround uses Google Cloud servers, distributed SSD storage, NGINX, and HTTP/2. It can deliver static content directly and has deployed seven data centers and CDN acceleration services on four continents. Its unique SuperCacher has three levels of cache acceleration, and its self-developed optimization plug-in can maximize Google’s website speed score. It has always provided the top speed technology, such as the latest PHP version, the fastest compression algorithm Brotli, which can significantly reduce the first byte time TTFB, and improve the overall website loading speed, especially suitable for cross-border foreign trade independent stations1.


Easy-to-use website control panel: SiteGround’s control panel is very suitable for novice foreign trade website construction. You don’t need to configure the server environment or upload source code. Just click a few times to install popular website building systems such as WordPress, Magento, and WooCommerce. After the website building system is installed, it has a novice guide and provides dozens of free themes and a series of free plug-ins, which can help you build a beautiful B2B/B2C website in the fastest time. In addition to website building, it also provides many additional functions, such as domain name management, free email, free SSL certificate, free CDN, free website optimization, free website migration. Everything you can think of, it has it all1.


World-class customer service support: SiteGround’s customer service is world-class. You can choose phone or instant chat. The response speed is almost instant, and the professionalism is bursting. Other hosts either do not have this service or need to wait for a few minutes or tens of minutes. Ticket support usually responds within 10 minutes. If you don’t know how to install WordPress, move the website, or have any technical problems, you can find customer service. They are knowledgeable and very patient. It provides a 30-day unconditional refund. If you are not satisfied, you can refund at any time1.


The disadvantages of SiteGround include:

Limited monthly traffic: SiteGround limits monthly traffic2.

Price increase upon renewal: SiteGround’s price increases upon renewal, which may make some users dissatisfied2.

Small storage space: SiteGround’s storage space is not as large as that of some other hosting providers2.

Overall, SiteGround is an easy-to-use, very popular foreign host with 2.8 million users worldwide. If you want to know whether it is suitable for building an independent station, you can check its pros and cons evaluation in various aspects12.

So in the end we choose Siteground to post our website.


#### Conclusion
Reason for choosing siteground:
Because we had a student account, a six-month free trial period, and the convenience and stability of siteground, we chose siteground in the end.

### Workflow
------------------------------------------------------------------------------------------
Trello -> Slack -> XAMPP -> Wordpress -> VSCode -> Github -> Staging -> Siteground 

### Version Control (Screenshots)
| Version 1 | Version 2 | Version 3 |
|:----------------------:|:---------------------------:|:---------------------:|
| <img src="https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/Screen%20shot%20for%20version1.png" width="100px" /> | <img src="https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/screen%20shot%20for%20version2-2.png" width="100px" /> | <img src="https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/Screen%20shot%20for%20version3.png" width="100px" /> |
| [Version 1](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/tree/main/Version%201) | [Version 2](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/tree/main/Version%202) | [Version 3](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/tree/main/Version%203) |
------------------------------------------------------------------------------------------

  
### Team Management Links
* [GitHub](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5) 
* [Slack](https://app.slack.com/client/T06B3PBHUDU/C06B7FASBUM) 
* [Trello](https://trello.com/b/lMVxzQ6v/group-five) 

#### Team Management reference material
![slack](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/slack.png)
![trello](https://github.com/Liu1xuan/CP3402-a2-2023-PBGroup5/blob/main/Screenshot%20for%20A2/Trello.png)

