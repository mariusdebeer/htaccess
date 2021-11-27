# .htaccess
# Location : /public_html/ or wherever your Wordpress root is.
This is meant to go into the root of your Wordpress website.  The idea is to block as much as possible in terms of bat bots, certain exploits and other things.
The code should be self-explanitory.

#.htaccess-WP-Uploads
# Location : /wp-content/uploads/
This file has the following functions:
1.  Allow only documents and images to be uploaded
2.  Disable upload of double-extention files
3.  Disable scripts from running should they be uploaded ( think images with shells in the Exim data)
