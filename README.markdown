## IP to Label Mapping for Drupal

This module provides a method of converting IP's or IP ranges into labels for use with other modules. Nothing else is done by this module alone. An admin interface is provided for configuring the ranges and labels. How those labels are integrated with other modules is up to them.

If you are looking for a module that integrates with locales, permissions, etc there are many already on drupal.org

### Example

* 192.168.100.0 - 192.168.100.50 -> homeoffice
* 10.0.0.1 - 10.0.0.254 -> myoffice

In the admin interface you would set ranges like range:label,range:label

* 192.168.100.0/24:DMZ,10.0.1.1-10.0.1.5:Office,10.0.*.*:internal