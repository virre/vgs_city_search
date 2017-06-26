VGS Stockholm inner city district search
===

Introduction
---
Veganistan is an excellent resource for Vegans in Stockholm and to some extent the rest of Sweden. However the search function could be better and I previously wrote VGS tools to have a cli mode and a libary to do better searches. However because that needs to download the content of the page and prosses it local it creates a bit of a heavy load on a thin resource. This is a try to better the filtering in Stockholm for at least the inner city using part of the VGS Tools code.

Install
---

This module is rather targeted to the database structure that is used in the original commit of a tarball to veganistans github repo. However this is not really possible to post an module to so this is why this is created as it's own repo. This should however be no problem to install this in the module/custom directory or just in the module directory. This also need to be selected in the module list to turn on. The path to the search page to add to the menus are in this case is: sok/stadsdel_sthlm. You also need to translate some terms.

Updates
---

More towns are possible to add, and better config sure would be good if this would be used. However it is nothing that is worth investing time in developing if it is not used.

Notes
---

I no longer work with neither Drupal nor PHP so my knowledge is a bit off. But this have been tested on my local machine with localised data. 