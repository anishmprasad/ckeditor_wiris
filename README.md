Requirements

CKEditor 3.0 or higher installed.
A valid license to install the integration in a production environment; otherwise, you can use the downloaded file just for demo purposes.

usage / Include it in your platform

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


