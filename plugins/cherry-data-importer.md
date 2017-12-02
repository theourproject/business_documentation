### Cherry Data Importer {#cherry-data-importer}

This plugin will help you export posts, comments, widgets, settings etc., from one site to another. With a single click of a button the plugin generates an XML file that can be imported to another website.

After the installation the plugin adds a new block -**Demo Content**where you can export or import the content.

![](/assets/oiugfimport.png)



Note: The images are not exported separately, they are downloaded from the server during the import.

#### File Import

To import the content, you need to upload the XML file and press**Start Import**.

Once the import begins you will see a box with progress bars.

![](/assets/\import.png)

After the import is complete you can view the site or customize it.

![](/assets/limport.png)

#### File Export

To export the data, you only need to press an Export button and an XML file will be created automatically.

![](/assets/8520259import.png)

#### Array Structure

**XML importer settings. Features:**

* enabled
  enable/disable XML importer;
* use\_upload
  show/hide the files upload form;
* path
  path to the pre-installed sample-data;
* import
  import settings;
* chunk\_size
  number of processed items at 1 importing step. The less this number is, the more steps will be during the importing process, and less time will be spent for 1 step. For this reason, it is strongly recommended to reduce this number for the themes with large sample data to avoid problems with importing files on weak servers;
* remap
  data post-processing settings. Here you need to add keys with posts IDs that can be changed during the import;
* post\_meta
  post metadata settings;
* term\_meta
  terms metadata settings;
* options
  options.

**Export Settings**

* message
  message displayed in the export block;
* logo
  url of the logo displayed in the export block;
* options
  options array for the additional export.

* success links
  associative array of links displayed on successful installation page. Link ID is used as a key. The plugin contains IDs for the homepage and for customizer;
* label
  link text;
* type
  type of displayed button \(default, primary, success, danger, warning\);
* target
  \_balnk, \_self;
* url
  link url.







