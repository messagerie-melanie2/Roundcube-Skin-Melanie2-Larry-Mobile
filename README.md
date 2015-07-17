melanie2_larry_mobile
=====================

This is the mobile version of melanie2_larry skin for Roundcube 1.1.2

Presentation
------------

Skin mobile for Roundcube. 
It needs the jquery_mobile plugin and the mobile plugin.
This is a beta version
Mobile view for mails and contacts
Infinite scroll, ajax open pages & responsive design
Missing the settings task

Version
-------

Mobile Melanie2 Skin 0.3


Author
------

PNE Annuaire et Messagerie/MEDDE


Installation
------------

Works on Roundcube 1.1.2

You need to add mobile plugin (https://github.com/messagerie-melanie2/roundcube_mobile) and jquery_mobile plugin (https://github.com/messagerie-melanie2/roundcube_jquery_mobile) in plugins folder

Rename the folder to "melanie2_larry_mobile" and add it to your Roundcube instance/skins directory.
Rename "roundcube_jquery_mobile" to "jquery_mobile"
Rename "roundcube_mobile" to "mobile"

Add "mobile" in the Roundcube config.inc.php file in "plugins", ex: 
// List of active plugins (in plugins/ directory)
$config['plugins'] = array(
    'mobile',
);
