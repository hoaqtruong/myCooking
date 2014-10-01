**myCooking project

Drupal version: 7.31

***Subtheming of Omega: 
sites/all/themes/my_cooking_theme

***Custom modules:
sites/all/modules/custom/myCooking  --> defines "Duration" and handles numeric field types, converts total minutes into hour(s) and quater/minutes format.
sites/all/modules/custom/myCooking_admin --> "add recipe" implements hook_block_view(), force past as plain text on ckeditor field
sites/all/modules/custom/nutritioninfo --> implements hook_field "nutritionInfo" table

TODO:

DONE #WYSIWYG contribute module doesn't work w/ most editor plugins.Error "The version of ... is not dectectd"
--> worked when pasting the following line in the very first line of sites/all/libraries/ckeditor/ckeditor.js
// version:'4.4.3',revision:'4391' 

