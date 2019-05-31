Frequently Asked Questions for Facebook Ads Extension
====
- The latest version of the plugin can be found at [here](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)
- The latest version of the README can be found at [here](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/README.md)
- The latest version of the INSTALL_GUIDE can be found at [here](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE.md)
- The latest version of the FAQ can be found at [here](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/FAQ.md)
- For other questions or bug reporting, please create a ticket at our [github](https://github.com/facebookincubator/Facebook-For-OpenCart/issues)

====
Always check that you have installed the latest version of the plugin as we are continously improving the plugin.


# Plugin Installation
1. Do you support installation via VQMOD?
    - No, we do not support installation via VQMOD. The mode of plugin installation is via OCMOD.

2. I am getting "Directory containing files to be uploaded could not be found!" error when I am installing the plugin zip file to OpenCart.
    - If you need to create the plugin zip file manually, you need to ensure there is no additional top level folder inside the plugin file. [Screenshot](https://drive.google.com/open?id=1A_EwXnTBc8OOES6D1D0yiEzp4NTN1VbU)

3. I am getting "Invalid file type" error when I am installing the plugin zip file to OpenCart.
    - You need to ensure that the plugin file ends with the extension ".ocmod.zip". Files which do not end with this extension will result in OpenCart showing "Invalid file type" when you install the plugin throught the installer. [Screenshot](https://drive.google.com/open?id=1NH0yR9X6C49M_CMGtuh2qvNoX_iMuIp-)

4. I do not see the menu for Facebook Ads Extension after installing the plugin.
    - You will need to perform a refresh for the modifications after the plugin installation. Go to the admin panel of OpenCart and click on Menu -> Extensions -> Modifications and click on the Refresh button. You may need to refresh your webpage after doing this. [Screenshot](https://drive.google.com/open?id=1qy-ipwK1HCk8oSnUmGuy6MCJxQdUyGfw)


# Accessing the Facebook Ads Extension module
1. I am getting "Page not found" error when accessing the Facebook Ads Extension. [Screenshot](https://drive.google.com/open?id=1R2t3gS4smJgmYTtLeTerJ-8yTUOr_wLD)
    - To access the Facebook Ads Extension, go to the admin panel of OpenCart and click on Menu -> Facebook Ads Extension -> Facebook Ads Extension. [Screenshot](https://drive.google.com/open?id=1xC5hQLqn-6AR7mxPME3y-safDTY-LFya)
    - Do NOT access the Facebook Ads Extension through Menu -> Extensions -> Extensions and clicking on the Edit button. [Screenshot](https://drive.google.com/open?id=1xC5hQLqn-6AR7mxPME3y-safDTY-LFya)
    - Check that the file admin/controller/extension/facebookadsextension.php exists on your webserver. If this file is not available, you need to give read+write+execute permissions to the admin, catalog and system folders and their child folders. After that, you need to remove the plugin and reinstall the plugin. [Screenshot](https://drive.google.com/open?id=1M9hh6ZkR6y-gCl8LEFsuY4wJ3EDpI6rM)

2. I am getting "We have detected missing files for Facebook Ads Extension." error at the Facebook Ads Extension module. [Screenshot](https://drive.google.com/open?id=1nQ_C51kqngNRZc0y9FREPgGsnOgCaHo3)
    - We need to copy some new files to your webserver, and there are some files which may not have been copied over correctly. Check that you have given read+write+execute permissions to the admin, catalog and system folders and their child folders. After that, you need to remove the plugin and reinstall the plugin. [Screenshot](https://drive.google.com/open?id=1M9hh6ZkR6y-gCl8LEFsuY4wJ3EDpI6rM)

3. I am getting "We are unable to locate the admin/controller/extension/facebookadsextension.php file on your webserver." error. [Screenshot](https://drive.google.com/open?id=1kOpwredZx505yTPSlMntgskqZfhJuFKv)
    - We need to copy some new files to your webserver, and we are unable to locate the file admin/controller/extension/facebookadsextension.php which may not have been copied over correctly. Check that you have given read+write+execute permissions to the admin, catalog and system folders and their child folders. After that, you need to remove the plugin and reinstall the plugin. [Screenshot](https://drive.google.com/open?id=1M9hh6ZkR6y-gCl8LEFsuY4wJ3EDpI6rM)

4. I am getting "Permission Denied" error at the Facebook Ads Extension module. [Screenshot](https://drive.google.com/open?id=1wgBr11M5ikAVNXtxYw0bkYMsksTGW2ri)
    - If you are on OpenCart 3.x, ensure that you have performed the additional installation step. [Video guide](https://drive.google.com/open?id=1-ljN_pNcyZBbN2LoXtxwaJEy0dfnxAum)
    - By default, the plugin will automatically enable the Access and Modify permission for the default OpenCart Adminstrator user group. Please give the required permissions if you are using a different user group. [Video guide](https://drive.google.com/open?id=1JUwZPlUNIhFO7I8U0slbJSQNjyu4al_J)

5. I have installed the OpenCart plugin but I am unable to see the Facebook Ads Extension module from the menu bar. [Screenshot](https://drive.google.com/open?id=1YUDir2bkB5dWPyNi-xpd7APZsKnrbj0M)
    - Check that you have refreshed the plugin modifications. Click on Refresh button to refresh the existing plugins on your OpenCart server. [Screenshot](https://drive.google.com/open?id=1Mfr49CzavKogSrOvZurJIvadfCwtR_6p)

# Setup for Facebook pixel, catalog and page shop
1. I am unable to see the pixel fired on my webstore after completing the setup. [Screenshot](https://drive.google.com/open?id=1rSQYT9mQViGkloFkRJKpEmfxl4iOU161)
    - Check that you have refreshed the plugin modifications. Click on Refresh button to refresh the existing plugins on your OpenCart server. [Screenshot](https://drive.google.com/open?id=1Mfr49CzavKogSrOvZurJIvadfCwtR_6p)
    - If you are using OpenCart 3.x, check that you have disabled the theme cache. [Screenshot](https://drive.google.com/open?id=1bY-bworYxX36b88HDvFW0_32C3Wtq_Tm)
    - Please check if you are using the version 2.1.4 and above for the Facebook for OpenCart plugin.

2. I am getting "There is an error with Facebook Ads Extension setup. Click on Facebook Ads Extension, Manage Settings, go to Advanced options and click on Delete Settings to restart the setup." error after completing the setup. [Screenshot](https://drive.google.com/open?id=1PadMA4cE1M-l_PgmyYo3_qg2JGU8E0Iy)
    - If you have a large catalog, eg more than 5000 products, there could be memory limitations due to your webserver/database configurations. Please refer to the next section "Syncing of OpenCart products to Facebook catalog" for more details.
    - The problem may occur if there is some connection problem during the setup process. You can delete away the existing settings and re-setup fpr Facebook Ads Extension again. [Video guide](https://drive.google.com/open?id=1PenBy_xizQGszdiS5BrmVFPypn5HKnkL)

3. I see an error that says We're unable to proceed since the selected page has already been configured for the Facebook Ads Extension.
    - If you see this error, it means that your Page is associated with another store. You'll need to decide whether you want to keep the Facebook Page associated with your old OpenCart store, or associate it with a different store. [Screenshot](https://drive.google.com/open?id=1gntxIF0YGa5XQEk2Pe-ichA-yQ5ZMr-J)

4. I see an error that says the access token is invalid.
    - If you see that the access token is invalid due to password change or invalid user session, you will need to update your access token and check that you do not log out of Facebook on your browser.
    - If you see that the access token is invalid due to unable to decrypt reasons, you will need to update your access token.
    - To refresh your access token, you can follow the steps in this screenshot. [Screenshot](https://drive.google.com/open?id=18koOQZmV3ra6wMsjsaWUPDuYZR_phl3J)

# Syncing of OpenCart products to Facebook catalog
1. How does the plugin sync the OpenCart products to Facebook catalog?
    - We are adopting a 2 mechanism approach to ensure a good experience for you when you setup the Facebook Ads Extension. When you first complete the setup, we will automatically create a Facebook product catalog and sync all your OpenCart products through the use of a one time feed file. This ensures a smooth operation even if you have a large number of products on your store. Subsequently, we will send real time product updates to Facebook whenever you make changes or new additions to your OpenCart products using the default OpenCart product management module.

2. I made changes to my OpenCart products by using 3rd party extensions, such as importing new products in bulk or updating product prices in bulk. Why are my changes not reflected on Facebook catalog.
    - Our plugin integrates with the default OpenCart product management module to directly send real time product updates. Our plugin does not cater for 3rd party extensions and so product changes made through these 3rd party extensions are not reflected on Facebook catalog.

3. I am getting "There is an error with Facebook Ads Extension setup. Click on Facebook Ads Extension, Manage Settings, go to Advanced options and click on Delete Settings to restart the setup." or "MYSQL server has gone away" errors.
    - If you have a large catalog, eg more than 5000 products, there could be memory limitations due to your webserver/database configurations when we are pulling all the available products to generate the initial product catalog feed file. Here are some suggestions for you to solve the problem.
      - We are only syncing products which are enabled to Facebook catalog. You can set products which are no longer in use to disabled. [Screenshot](https://drive.google.com/open?id=1cKfe_oIX9Hbvcuqop4-Zxsgeyk3rZa_J)
      - Check the error logs for your webserver and database to understand if there are any errors logged.
      - If you are On MYSQL database server and you are getting errors such as "MYSQL server has gone away" and "InnoDB: mmap(134217728 bytes) failed; errno 12", you can look into reducing the innodb_buffer_pool_size variable on your MYSQL server. The reason could be that the MYSQL server is trying to take up more memory than the allowed memory permissible on your server, resulting in MYSQL server crashing. Please refer to the MYSQL documentation [here](https://dev.mysql.com/doc/refman/8.0/en/innodb-parameters.html)
      - If you are on MYSQL database server, you can look into increasing the wait_timeout and max_allowed_packet variables on your MYSQL server. Please refer to the MYSQL documentation [here](https://dev.mysql.com/doc/refman/8.0/en/gone-away.html) for more details.
      - If you are on a shared hosting service, you may need to increase the memory configurations to be able to cater for generating the large catalog.

4. How many product catalogs can I use with this setup?
    - You may only use 1 product catalog.

# Product configurations and settings
1. Facebook product catalog showing "This url is classified as malicious" warning message.
    - Facebook has detected that your website URL may be malicious. You can reach to Facebook team, share with us the context and submit an appeal to review your website URL again [here](https://www.facebook.com/help/contact/571927962827151).

2. How is the plugin syncing OpenCart product discount prices to Facebook catalog?
    - The plugin takes the Special prices of the OpenCart products and sync them to Facebook catalog. If a date period is set, the discount will be for that date period. Otherwise, the discount will be treated as always-on discount. [Screenshot](https://drive.google.com/open?id=1j23IFfCvVz87mPUARDhoXZvmkKZjVGcH)

3. Why is my OpenCart product options not configured to Facebook Page Shop?
    - As the OpenCart product options structure is different from as Facebook product group structure, the plugin does not sync the OpenCart product options to Facebook catalog. Instead, when a consumer clicks on the checkout link on Facebook page shop, he/she will be brought to the product details page on your website for the consumer to specify the product options.

4. The currency listed on the Facebook catalog is not the correct currency. How do I change it?
    - You need to create the right currency on OpenCart, and then select the currency on the Store Settings. [Screenshot](https://drive.google.com/open?id=11Sh6AiyPpQrv2ki7-oBAQvZnnlyxcyRV) [Screenshot](https://drive.google.com/open?id=1yL-RFUhWI-qX-Mo2u4dpNNW0B6nOHAvl)
  - For the existing Facebook catalog, you can delete away the existing Facebook Ads Extension settings and re-setup again. [Video guide](https://drive.google.com/open?id=1PenBy_xizQGszdiS5BrmVFPypn5HKnkL)

5. Why are my available products is shown as Out of Stock on Facebook catalog? Why are my out of stock products shown as In Stock on Facebook catalog?
    - The plugin will set the Facebook product as Out of Stock if the OpenCart product has zero quantity and has enabled the product to deduct stock. If the OpenCart product does not deduct stock, the Facebook product will always be set as In Stock. [Screenshot](https://drive.google.com/open?id=1WVfHJKLERTi5Lfz4tMEenR7EXNGAo5VF)
    - The plugin will set the Facebook product as Out of Stock if the OpenCart product status is set as the predefined Out of stock.

# Cookie bar shown on Web store
1. Why am I unable to see the option to disable cookie bar on web store?
    - Please check if you are using the version 2.1.0 and above for the Facebook for OpenCart plugin.

2. Why is the webstore still showing cookie bar when I disable the cookie bar option settings? The settings does not seem to be saving correctly into the system.
    - Your web browser may be caching the previous copy of the Javascript files of the plugin. Please clear the cache by forcing the browser to "Empty cache and hard reload". [Screenshot](https://drive.google.com/open?id=1NuUS-bEyIHAacbui6HsFMK6DxWGtllVE)

# Facebook Messenger Chat plugin
1. I am unable to see the Messenger chat plugin on my website
    - Please check that you have enabled the Messenger chat plugin. [Video guide](https://drive.google.com/open?id=1XubpAUFYw6m7lB9A8RqrdOPq3IjEQvIq)
    - If you are on OpenCart v3.x, please check that you have not made any changes to the common/header.twig template file using the Theme Editor. It is a known issue that the Theme Editor is not compatible with ocmod plugins, and the Facebook for OpenCart plugin is using ocmod. [Screenshot](https://drive.google.com/open?id=1c5lnHR0fw9laZXOs9UEyhpMpsDaij_mU)

# Setting up for running ads on Facebook
1. What should I do if I already have the Facebook pixel installed on my OpenCart website?
    - If you've already installed the Facebook pixel and are running Facebook dynamic ads, you don't have to use the Facebook Ads Extension in OpenCart.
    - If you've set up the Facebook pixel but not dynamic ads, or you think you may have set up the Facebook pixel incorrectly, you should use the Facebook Ads Extension to get everything set up. Keep in mind you'll have to manually remove your existing Facebook pixel code from your website before starting, otherwise you'll have 2 versions of your pixel on your website.
    - Having 2 versions on the Facebook pixel can lead to:
      - Campaign results doubling (ex: 2x the number of actual conversions)
      - Cost per result being halved in your reports
    - If you remove your existing pixel and start over with the OpenCart plugin, we recommend pausing your active campaigns first and re-installing right away. This way, you'll minimize any impact on your website Custom Audiences and conversion counts.

2. Will Facebook dynamic ads stay up to date with my stock changes?
    - Yes, we'll sync with your OpenCart site immediately when you make any modifications to the products.

3. I want to also reach people who have not visited my website or app, what should I do?
    - You can drive new potential customers to visit your website, or to take a specific action, by creating an ad campaign using the website conversions objective. Learn more about how to optimize your ad sets for conversions 

4. My advertiser pays a third party to manage their OpenCart site, what should I do?
    - That's fine. Just be sure that the third party is added as an administrator to the advertiser's Facebook page and ad account.
