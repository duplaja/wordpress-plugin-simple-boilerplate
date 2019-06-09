<p align="center">
  <a href="https://github.com/duplaja/wordpress-plugin-simple-boilerplate/LICENSE">
    <img src="https://img.shields.io/cran/l/devtools.svg?style=plastic">
  </a>


</p>

#WordPress Plugin Boilerplate#

* Contributors: Webby Scots (Modified by Dan Dulaney)
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Use this to make your WordPress plugins.

## Installation and Usage

1. Clone the repo
2. Code :-)

It has its own autoloader. All you need to do is create an includes folder and add the class files using add class-mypluginname-classname.php. And then in the init function do:

~~~
if ($this_condition) {
    $this->classname = new MyPluginName_ClassName();
} 
~~~

The part after new is what is searched for, as lowercase and with underscores as dashes in the includes folder, but the class- part is prefixed for you.

## Find and Replace Parameters

plugin_name
plugin_uri
plugin_desc
plugin_slug
author_name
author_uri
author_email
text_domain
current_year
Class_Name
SHORT (Short name for calling the class instance via function)
