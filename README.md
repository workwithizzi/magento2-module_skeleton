
# Magento 2 Skeleton Module

Used as a boilerplate for building Magento modules

## Install
1. In your Magento environment, go to `app/code` and create a directory with your vendor name
2. `git clone` or download zip of repo into the vendor name and name that directory the name of your module.
3. Change the module name in `composer.json
4. Do a find/replace for change `Izzi_Skeleton` to your `VendorName_Module`
5. Run the following commands:
a)  Enable the extension: `bin/magento module:enable VendorName_Module --clear-static-content`
b)  Flush cache `bin/magento cache:flush`