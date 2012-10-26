WordpressWebserviceMutant
=========================

Hi guys, this project is a fork of the Wordpress Webservice plugin which allow you to search for PostMeta.
Why i did this? Because the original plugin dont allow you to search for PostMetas.

So i added a new method called getPostMeta (which is very similar to the getPost method), and changed the WSDL Template manually to allow the Webservice function with the native get_post_meta.

The original project is not Mine, so if you want to test the original plugin (it was at 0.2.1v when i changed), you can try at:
http://wordpress.org/extend/plugins/wordpress-web-service/

Hope you enjoy!