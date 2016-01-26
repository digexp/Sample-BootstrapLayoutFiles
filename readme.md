# IBM Simple Theme Bootstrap Layouts

The Simple Theme is a simplified theme which can be used as a starting point for the development of custom themes. It is included in Portal 8.5 starting with CF08.

The Simple Theme initially includes four layouts, One Column, Two Column Left, Two Column Right, and Top Column 2 Column Unequal. These use the Simple Theme's grid layout which can be found in the theme's st_layoutGrid module. During CF09, some modifications were made to the Simple Theme to simplify its layouts and to make it easier to create layouts using the Bootstrap framework's grid system instead. To use that grid, be sure you are using the profile called profile_bootstrap.json, or that the wp_bootstrap_ext module is included in your custom profile.

### Accessing the sample Bootstrap layouts
The bootstrapLayoutFiles.zip file contains four sample layouts which use the Bootstrap framework grid system, which is included in the Simple Theme's static files. You can examine the contents of the zip file to learn how to create your own layouts. Or you can unzip the file and merge the content into your theme's WebDAV directory. Be careful when updating your existing files to avoid overwriting your own customizations.

