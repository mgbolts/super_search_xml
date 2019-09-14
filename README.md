# super_search_xml

This is the standard xml file format for the super search function in the yealink phones.

The xml files provides a master list of which directory lists will be searched to auto-complete your dialing.

You can enable a list and also prioritise which list to prioritse when there are multiuple matches.

You can also type the name using the shortcut method to the letters. eg. just press the key that matches the letter you want once. eg. for mgbolts, just type 6426587

For freepbx users, add the file to /var/www/html/filename.xml

Then add this config setting to your base file:

super_search.url = http(s)://ipaddress_or_domain/filename.xml

If you are using openvpn on fpbx, use 10.8.0.1

chown to asterisk:asterisk
chmod to 644
