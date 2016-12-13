melanie2_larry_mobile
=====================

This is the mobile version of melanie2_larry skin for Roundcube 1.2.3

Presentation
------------

Mobile skin for Roundcube. 
It needs the jquery_mobile plugin and the mobile plugin.
Mobile view for mails, contacts and settings.
Infinite scroll, ajax open pages & responsive design

Version
-------

Mobile Melanie2 Skin 0.4.7


Author
------

PNE Annuaire et Messagerie/MEDDE


Installation
------------

Works on Roundcube 1.2.3

You need to add mobile plugin (https://github.com/messagerie-melanie2/roundcube_mobile) and jquery_mobile plugin (https://github.com/messagerie-melanie2/roundcube_jquery_mobile) in plugins folder

Rename the folder to "melanie2_larry_mobile" and add it to your Roundcube instance/skins directory.
Rename "roundcube_jquery_mobile" to "jquery_mobile"
Rename "roundcube_mobile" to "mobile"

Add "mobile" in the Roundcube config.inc.php file in "plugins", ex: 
// List of active plugins (in plugins/ directory)
$config['plugins'] = array(
    'mobile',
);

For an installation with plugins manager you can follow the Roundcube Team's how-to : https://roundcubeinbox.wordpress.com/2016/04/26/roundcube-for-mobile-devices/


Attention
---------

You should only activate "mobile" plugin in config file, not the "jquery_mobile" plugin or you will have displays trouble in desktop view. jquery_mobile plugin is automatically activated by the mobile plugin when needed.

Screenshots
-----------
Messages

![capture d ecran 2015-07-17 a 14 34 15](https://cloud.githubusercontent.com/assets/3693239/8747236/57569d74-2c91-11e5-91f0-99b33b3edef7.png)

Open a message

![capture d ecran 2015-07-17 a 14 34 27](https://cloud.githubusercontent.com/assets/3693239/8747241/5fe40cb0-2c91-11e5-9c0d-2f111080e5da.png)

Compose a message

![capture d ecran 2015-07-17 a 14 34 51](https://cloud.githubusercontent.com/assets/3693239/8747255/7cdc4fe4-2c91-11e5-9c26-260680f1f15b.png)

Select messages on the list

![capture d ecran 2015-07-17 a 14 35 12](https://cloud.githubusercontent.com/assets/3693239/8747260/85d17034-2c91-11e5-8e3d-340210754a2a.png)

Contacts list

![capture d ecran 2015-07-17 a 14 35 25](https://cloud.githubusercontent.com/assets/3693239/8747281/a149343c-2c91-11e5-81a2-c48e098e9cfd.png)

Settings

![capture d ecran 2015-07-27 a 18 29 38](https://cloud.githubusercontent.com/assets/3693239/8911422/c17097d4-348c-11e5-906a-456b09872bc1.png)

