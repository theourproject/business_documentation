## Introduction {#introduction}

Thank you for purchasing a WordPress template. This documentation consists of several parts and covers the entire process of installing and setting up a WordPress website from scratch.

### What is WordPress CMS? {#what-is-wordpress-cms}

WordPress is a free open-source blogging tool and content management system \(CMS\) based on PHP and MySQL. With its help you can create and administrate websites or powerful on-line applications without possessing any special technical skills. Due to the ease of use and flexibility, WordPress has become the most popular platform for website development.[Learn More.](http://wordpress.org/about/)

### What is a WordPress Template? {#what-is-a-wordpress-template}

WordPress template is a theme for the WordPress CMS platform. You can easily change your website appearance by installing a new WordPress template in a few easy steps. Despite its simplicity, a WordPress template contains all the necessary source files that can be altered the way you need.

### Template Structure {#template-structure}

The template package includes several folders. Let’s check what’s inside:

* **theme**
  * contains WordPress theme files.
  * **manual\_install**
    * contains files that make the WordPress website look like on our live demo.
    * **uploads**
      * contains theme images.
    * **provel.sql**
      * database file \(contains theme content\).
* **documentation.pdf**
  * contains documentation information.

### Preparation {#preparation}

Before installing a WordPress website, you need to get fully prepared. We recommend you to get the following aspects covered:

#### Software {#software}

Before you start working with the WordPress template, you should download the required software. You can check the required software on the template preview page.

* First of all, you will need the right software to extract files from the password protected sources\_\#\#\#\#\#\#\#\#\#.zip archive. You can use WinZip 9 or a later version \(if you have Windows OS\) or Stuffit Expander 10 or a later version \(if you have Mac OS\).

* You might also need Adobe Photoshop. It is used to edit the source .PSD files in case you need to change the graphic design and images of the template.

* To edit the source code of the template, you can use code editors like Adobe Dreamweaver, Notepad++, Sublime Text, etc.

* To upload the files to a hosting server, you will need an FTP manager like Total Commander, FileZilla, CuteFTP, etc.

#### Hosting {#hosting}

Since WordPress CMS is a PHP/MySQL platform, you need to have the hosting server prepared for it.

In case you already have a hosting server, you need to check whether it is compatibile with [WordPress hosting requirements](http://wordpress.org/about/requirements/) or not. In other words, whether you can host a WordPress website with it.

This theme itself requires Apache or Nginx hosting servers.

To eliminate **Fatal error: Maximum execution time of 30 seconds exceeded**, modify the value of “max\_execution\_time” to a greater value say 600.

We also recommend to use the following**configuration settings**:

* 50 MB of disk space.

* Memory limit per process: 64mb \(128mb or more recommended\).

##### PHP and MySQL; {#php-and-mysql}

Minimal required version of PHP is 5.2.4 and MySQL 5. PHP 5.2 is already not safe as contains critical vulnerabilities that can be used to harm your website. Some Theme extensions will not work with PHP 5.2 and require version 5.4 or later.

Recommended settings are:

1. PHP 5.4;
2. MySQL 5.5 or later;
3. mod\_rewrite;
4. php fopen;
5. suPHP.

You can also install WordPress on your PC or laptop through a local server. You can use the following software to create a local server: **WAMP**, **AppServ**, **MAMP**, etc. All of these support WordPress and can be installed as a regular software.

