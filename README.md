# super_search_xml

This is the standard xml file format for the super search function in the yealink phones.

The xml files provides a master list of which directory lists will be searched to auto-complete your dialing.

You can enable a list and also prioritise the match order.

For freepbx users, add the file to /var/www/html/filename.xml

Then add this config setting to your base file:

super_search.url = http://ipaddress_or_domain/filename.xml

chown to asterisk:asterisk
chmod to 644
