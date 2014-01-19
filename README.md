# Contao Open Source CMS 
# => unofficial release 2.11.14.x <=

Release 2.11.13 extended with Hacks from BugBuster

## Hacks

### 2.11.14.01: Correctly detect IE11 in the `Environment::agent()` method

* 2013-11-23 File: system/config/agents.php 

### 2.11.14.02: Corrected doctype in mail_default.html5/xhtml template

* 2013-11-24 File: system/modules/frontend/templates/mail_default.xhtml
* 2013-11-24 File: system/modules/frontend/templates/mail_default.html5

### 2.11.14.03: Remove the wrong "PHP tidy" requirement

* 2013-11-28 File: system/modules/backend/languages/de/tl_settings.php
* 2013-11-28 File: system/modules/backend/languages/en/tl_settings.php
 
### 2.11.14.04: Correctly resize the mediaboxAdvanced in IE11 (see #6504).
* 2014-01-19 File: plugins/mediabox/1.4.6/js/mediabox-uncompressed.js 
* 2014-01-19 File: plugins/mediabox/1.4.6/js/mediabox.js
