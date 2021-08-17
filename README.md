# moodle-css-styling
Raw-CSS for moodle to make stylesheet changes inside the theme or as inline-CSS for signly activities/ courses.

------------------
------------------

## General information
### Please read the following instructions before using the codes.

- __Be careful__ when change css - also by using the examples in this repository. 

- __Duplicate the page on which you change something__ with a new tab to retain the __chance for making things undone__.

- After changing css you have to __delete the cache__ for making changes active. You can press __CTRL+F5__ therefore.

- The codes in this repository are __tested in the classic theme__ if there is no other information. __In many cases there are also tests in the boost theme__. In many cases the codes are compatible. Otherwise there will arise different versions by getting feedback. 

__Thanks for help by giving comments or making pull-requests.__


------------------

## Use the codes in the theme of your moodle-site

This is the cleanest way for writing css in moodle.
- Navigate to __site-administration - appearance - themes - your theme__ and go to the part for __raw-css__.


------------------

## Use the codes in a signly course or activity

You can also use a textfield or a textblock for putting in css. Therefor you have to note the following things.

- This way takes more ressources. Do not make many big changes by using a textblock or textfield.

- The changes will be active everywhere the textblock or textfield is shown. Within the textblock you can take special settings where it should be shown.

- Use the "unformated text" - editor by selecting in the settings. To select the editor you can also go to yourmoodlesite/user/editor.php

- __Important: You have to put a <style> before the code and a </style> after it because you are writing inline-css in a html-editor.__
