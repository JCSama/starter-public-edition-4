A Distro Based on CodeIgniter 3 and PHP Application Starter-4
==========================================================


Features in addition to CodeIgniter 3.0-dev
--------

* Idiorm ORM see: <a href="http://idiorm.readthedocs.org/en/latest/">Documentation for Idiorm Object Relational Mapper</a>
* Ember [coming soon]
* Codeigniter Cross Modular Extensions - XHMVC,
https://bitbucket.org/xperez/codeigniter-cross-modular-extensions-xhmvc,
http://www.4amics.com/x.perez/2013/06/xhmvc-common-modular-extensions/ (only the essential piece of code).
* Support for the old CI 2.x class/file name convention. When you port your older libraries, models, and controllers,
you would not be forced to rename them according to the new strict "ucfirst" naming convention.
* Native PHP session support by default.
* Modular Extensions - HMVC for CodeIgniter, https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc
* Enhanced bootsrapping process, see the content of the folder platform/core/bootstrap/.
* In addition to the normal MVC execution, it is possible to run non-MVC scripts, look at the folder www/non-mvc/ for examples.
* Form Validation Callbacks in HMVC in Codeigniter, http://www.mahbubblog.com/php/form-validation-callbacks-in-hmvc-in-codeigniter/
* Making CodeIgniter’s Profiler AJAX compatible, http://dragffy.com/blog/posts/making-codeigniters-profiler-ajax-compatible
* CodeIgniter Form Validation External Callbacks, https://gist.github.com/1503599, http://ellislab.com/forums/viewthread/205469/
* User Agent Helper Functions for CodeIgniter, https://github.com/ivantcholakov/codeigniter-user-agent-helper
* Template library for CodeIgniter by Phil Sturgeon, http://philsturgeon.co.uk/code/codeigniter-template
* CodeIgniter Asset Library by Phil Sturgeon.
* UTF-8 string support for CodeIgniter based on Kohana's implementation, https://github.com/ivantcholakov/codeigniter-utf8
* PHP fallback function http_build_url(), https://github.com/ivantcholakov/http_build_url
* Core_Model, see https://github.com/ivantcholakov/codeigniter-base-model
* Some basic javascripts + normalize.css.
* Internationalization, initially based on CodeIgniter 2.1 internationalization i18n, https://github.com/EllisLab/CodeIgniter/wiki/CodeIgniter-2.1-internationalization-i18n, but totally reworked.
* cURL library for CodeIgniter, https://github.com/philsturgeon/codeigniter-curl
* A simple Event System for CodeIgniter, https://github.com/ericbarnes/CodeIgniter-Events
* Support for database stored settings (Settings library).
* Textile, A Humane Web Text Generator, http://textile.thresholdstate.com/
* Markdown Extra - A text-to-HTML conversion tool, http://michelf.com/projects/php-markdown/
* Markdownify - A HTML-to-text conversion tool, http://milianw.de/projects/markdownify/
* Mustache, Logic-less templates, https://github.com/bobthecow/mustache.php
* Less.php compiler, https://github.com/oyejorge/less.php
* PHPMailer, http://phpmailer.worxware.com/, https://github.com/Synchro/PHPMailer
* A CodeIgniter compatible email-library powered by PHPMailer, https://github.com/ivantcholakov/codeigniter-phpmailer
* A PHP class for transliteration, https://github.com/ivantcholakov/transliterate
* AES (256, 192, 128) Symmetric Encryption, Compatible with OpenSSL, https://github.com/ivantcholakov/gibberish-aes-php
* HTML Purifier, http://htmlpurifier.org/
* Core_Lang, language translations: Support has been implemented for placeholders %s, %d, etc.
* A way for database classes/drivers modification: Files under platform/core/framework/database/ folder may be copied
into platform/core/common/database/ (the prefered location) or platform/applications/{application_name}/database.
The copied files can be modified/customized. See https://github.com/ivantcholakov/starter-public-edition-4/issues/5
* CodeIgniter Cache Helper, https://github.com/stevenbenner/codeigniter-cache-helper
* auto_link() helper accepts attributes, https://github.com/EllisLab/CodeIgniter/wiki/auto-link
* Menu Library, https://github.com/nihaopaul/Spark-Menu, https://github.com/Barnabas/Spark-Menu (the original spark-source), https://github.com/daylightstudio/FUEL-CMS/blob/master/fuel/modules/fuel/libraries/Menu.php
* Function print_d() (enhanced debug print), https://github.com/vikerlane/print_d
* Registry library for CodeIgniter, https://github.com/ivantcholakov/codeigniter-registry
* Bootstrap 3.1, http://getbootstrap.com/
* Bootstrap Hover Dropdown Plugin, https://github.com/CWSpear/bootstrap-hover-dropdown


License Information
-------------------

For Ivan Tcholakov's original code:  
Author: Ivan Tcholakov ivantcholakov@gmail.com, 2012-2014.  
License: The MIT License (MIT), http://opensource.org/licenses/MIT

CodeIgniter:  
Copyright (c) 2008 - 2014, EllisLab, Inc. (http://ellislab.com/)  
License: Open Software License (OSL 3.0), http://opensource.org/licenses/OSL-3.0

CodeIgniter configuration file:  
Copyright (c) 2008 - 2014, EllisLab, Inc. (http://ellislab.com/)  
License: Academic Free License (AFL 3.0), http://opensource.org/licenses/AFL-3.0

Third parties:  
License information is to be found directly within code and/or within additional files at corresponding folders.
