### Manual Installation {#manual-installation}

To use this method, you need to have access to your WordPress site files on FTP through the File Manager of your hosting control panel or an FTP client like Filezilla, CuteFTP, Total Commander, etc.

1. Unzip the **theme-name.zip **files to any folder on your hard drive \(first, right-click each of the .zip files, select Unzip to **theme name **respectively, so you get the one folder called theme-name\).
2. Upload the **theme-name **folder to the **/wp-content/themes/ **directory on your FTP server.
3. Log in to your WordPress admin panel \(add /wp-admin after your domain name in the browser address bar\).
4. Go to the menu **Appearance &gt; Themes**.
5. Under the **Available Themes **section find **theme-name **and activate it by clicking the **Activate **button.



#### Manual Plugin Installation

If you need to install plugins manually, you can do it this way.

* install plugins from **theme/\(your theme name\)/assets/includes/plugins**;

* go to [Wordpress.org](https://wordpress.org/) and download the necessary plugins;

* go to **plugins **tab on your administration panel and click on **add new **button;![](/assets/987import.png)
* you will see the the search field that can help you search the necessary plugins by keywords, you can install them from your administration panel at once;![](/assets/454import.png)

* you can also upload the plugins from your PC if you already have them on your computer in .zip format. Just click on

  **upload plugin **button and choose the needed files.

![](/assets/452452import.png)

#### Manual sample data installation {#manual-sample-data-installation}

##### For installing the sample data manualy please follow the instructions listed below. {#for-installing-the-sample-data-manualy-please-follow-the-instructions-listed-below}



* Open the**theme/manual\_install**folder of your downloaded template package.

* Upload the**uploads**folder to the wp-content directory of your WordPress installation, accept folder\(s\) replacement. Please note that your images may be replaced with sample images.

* Open the **theme-name.sql **file that is located in the **theme/manual\_install **folder in any text editor \(preferably Sublime Text or Notepad\) and replace all instances of **your\_website\_url\_here **with your website URL in the entire document using the
  **Find and Replace **tool \(hit Ctrl+H hot keys to open this window\). E.g.: http://www.mywebsite.com. Please, make sure that you do not have the forward slash**/**sign at the end of the address and the url starts with http://www. Save your changes and close the file.
* Open the**theme-name.sql**file that is located in the**theme/manual\_install**folder in any text editor \(preferably Sublime Text or Notepad\) and replace all instances of**your\_website\_url\_here**with your website URL in the entire document using the**Find and Replace**tool \(hit Ctrl+H hot keys to open this window\). E.g.: http://www.mywebsite.com. Please, make sure that you do not have the forward slash**/**sign at the end of the address and the url starts with http://www. Save your changes and close the file.

![](/assets/4140import.png)

* Now you can import the dump file with the **phpMyAdmin **tool or some other database management tool.

![](/assets/9541import.png)![](/assets/452import.png)

* Open your WordPress database using a database management tool. Usually, the database tool is called**PhpMyadmi**

* Go to the**Import**tab and import the**.sql**file.

![](/assets/7678import.png)

* Navigate to WordPress dashboard and go to**Settings &gt; Permalinks**.

* Click the**Save Changes**button.

* Refresh your home page. That’s it, the template has been installed with demo sample content.



