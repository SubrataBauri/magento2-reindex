# magento2-reindex
Add Reindex option for Magento2 Admin

As every Magento 2 admin would be familiar with the fact that we don't have the privilege anymore
to re-index from the admin panel as we used to have in Magento 1.x

Although there are technical reasons for not giving Admin the option to re-index from Admin
we sometimes need that to move things faster.

This module will add the option to re-index from admin section.
 
 ## How to install
 
 ### Composer method
 Install the module via composer.
 
 **Install Extension**:
 
 ```
 composer require subrata/reindex:*
 php bin/magento cache:clean
 php bin/magento cache:flush
 
 ```
 
 
 **Update Extension**:
 
 ```
 composer update subrata/reindex:*
 php bin/magento cache:clean
 php bin/magento cache:flush
 
 ```
 
 #### Authentication required (Optional)
 
 ![Authentication required](https://i.imgur.com/dmryiPk.png)
 
 If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)
 

