PHPWord Joomla! Library ![](https://img.shields.io/badge/maintained%3F-no!-red.svg?style=flat)
=======================

PHPWord Library for Joomla! 2.5. &amp; 3.x 

If you already know PHPWord, than this is a library package to be used in Joomla!

Version
-------

* The current Joomla! Library is using PHPWord 0.14.0 (master) EXPERIMENTAL

Download
-------

[Download PHPWord Joomla! Library 0.6.3](https://bitbucket.org/vdespa/phpword-joomla-library/downloads/PHPWord-Joomla-Library-0.6.3.zip)

Usage
-----

`jimport('phpword.library.autoload');`

Please note the upercases when using jimport!

`// New Word Document`

`$phpWord = new \PhpOffice\PhpWord\PhpWord();`

`// now you can use PHPWord as usual...  `

Documentation
-------------

* [PHPWord Codeplex page] (http://phpword.codeplex.com/)
* [PHPWord github page] (https://github.com/PHPOffice/PHPWord/)

Bugs? Problems? Feedback?
-------------------------

If you have any problems installing / updating PHPWord Library in Joomla! feel free to [Add a New issue] (https://github.com/vdespa/PHPWord-Joomla/issues)

If you are having problems with PHPExcel itself and you think is a bug or something, check the [PHPWord Issue Tracker] (https://github.com/PHPOffice/PHPWord/issues)

Credits
-------

* Special thanks to the [PHPOffice team] (https://github.com/PHPOffice?tab=members) which put the PHPWord library together.
* Also thanks to Joe for the [inspiration] (http://www.ostraining.com/howtojoomla/how-tos/development/how-to-package-joomla-libraries).


License
-------
PHPWord is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PHPExcel/blob/master/license.md)

Note
----

The library folder was build using the given composer.json file and executing:

    composer update --no-dev --prefer-dist
