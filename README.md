Editable Fields
======================

Editable Fields module allows node fields to be edited on a node's display
(e.g. at node/123), not just on the node edit pages (e.g. node/123/edit).
It also works within views allowing you to edit multiple nodes on a single page.
Anywhere a formatter can be selected, you can select "Editable".


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- To make one or more fields of a content type editable,
  go to "Structure >Content types", and click "manage display" for that
  content type. For a field to be editable, choose "Editable" from the
  format drop-down select box. This will make the field editable anywhere the
  node is displayed (also in views displaying teasers or full content).

- To make a view with editable fields, you don't need to do the previous step.
  Create a view and add some fields to it. On the settings page for each field,
  choose "Editable" from the "Formatter" select box.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/editable_fields/issues.

Current Maintainers
-------------------

- [Robert Garrigos](https://github.com/robertgarrigos).

Credits
-------

- Port on the Drupal module [Editable Fields](https://www.drupal.org/project/editablefields) by [these commiters](https://www.drupal.org/node/165016/committers).


License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
