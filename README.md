# Extend_CustomCartOffer
Custom code for PAS, to adjust the cart offers for Product Protection


This add-on solves the issue where cart offers are not displayed correctly. This add-on moves the offer below the item-options in the cart.

To install, the code has to be put in app/code/Extend, so you will end up with app/code/Extend/CustomCartOffers

After copying the code, run

bin/magento module:enable Extend_CustomCartOffers
and run the magento commands

bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento setup:static-content:deploy -f -j5
bin/magento cache:clean
