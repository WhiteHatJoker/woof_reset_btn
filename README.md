# Woof reset button action #
If you have installed the Woocommerce Products Filter (woof) plugin and you have custom page that you would like your users to return when they press the reset button no matter where they are, please follow my instructions. Keep in mind: Permalinks are turned on.

## Instructions ##
1. You need to have the woof plugin installed or downloaded.
2. Download current repository and place the content within woof plugin directory overwriting changes
3. Open `views/woof.php` and replace the http://your_link on line 479 `data-link="http://your_link"` with your url where you would like your users to go when they hit refresh.
4. Enjoy!

## Note ##
It worked with WooCommerce Products Filter version 2.1.5.1, so if you just want to know the changes made to the original plugin files, look at the previous commit history of respective files. 
