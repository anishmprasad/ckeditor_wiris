# ckeditor_wiris

A WIRIS Plugin for CKEditor

## Requirements

* CKEditor 3.0 or higher installed.
* A valid license to install the integration in a production environment; otherwise, you can use the downloaded file just for demo purposes.

## Usage / Include it in your platform

You must include some content on your CKEditor configuration file ckeditor/config.js (see CKEditor documentation).

```js
/*
Copyright (c) 2003-2010, CKSource - Frederico Knabben. All rights reserved.
For licensing, see LICENSE.html or http://ckeditor.com/license
*/
CKEDITOR.editorConfig = function( config )
{
    // Add[MT]to the integration list
    config.extraPlugins += (config.extraPlugins.length == 0 ? '' : ',') + 'ckeditor_wiris';
};
If you use the Full MathML mode and for CKeditor versions higher than 4.0 you have to add this line as well:
 
config.allowedContent = true;
```


## Licence

GNU Global Public Licence v3.0
=========================

[![GNU GPL v3.0](http://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl.html)

View official GNU site <http://www.gnu.org/licenses/gpl.html>.


### Related : 
 - [Wikipedia - GNU General Public License](http://en.wikipedia.org/wiki/GNU_General_Public_License) - 
   [(fr)](http://fr.wikipedia.org/wiki/Licence_publique_générale_GNU)
   [(de)](http://de.wikipedia.org/wiki/GNU_General_Public_License)
   [(es)](http://es.wikipedia.org/wiki/GNU_General_Public_License)
   [(it)](http://it.wikipedia.org/wiki/GNU_General_Public_License) - 
   _from Wikipedia_
 - [Frequently Asked Questions about the GNU Licenses](http://www.gnu.org/licenses/gpl-faq.en.html) - 
   [(fr)](http://www.gnu.org/licenses/gpl-faq.fr.html)
   [(es)](http://www.gnu.org/licenses/gpl-faq.es.html)
   [(it)](http://www.gnu.org/licenses/gpl-faq.it.html) - 
   _from GNU official web site_
 - [A Practical Guide to GPL Compliance](http://www.softwarefreedom.org/resources/2008/compliance-guide.html) - 
   _from Software Freedom Law Center_

## Source :
 - gpl-3.0-or.txt : from official GNU site <http://www.gnu.org/licenses/gpl-3.0.txt>
 - gpl-3.0.md : from gpl-3.0-or.txt format with Markdown by Techniv
 - gpl-3.0-fr-noff.txt : non-official translation by Philippe Verdy 
   from <http://www.gnu.org/licenses/gpl-3.0.txt>
 - gpl-3.0-fr-noff.md : from gpl-3.0-fr-noff.txt format with Markdown by Techniv



