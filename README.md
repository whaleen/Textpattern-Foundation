txp.foundation
==============

Textpattern &amp; Foundation 4

Using [textpattern-default-theme](https://github.com/textpattern/textpattern-default-theme) as the basis. Have added Foundation 4's JS and CSS and layout classes. More to come...


Requires [cnk_versioning](https://github.com/whaleen/txp.foundation/blob/master/textpattern/plugins/cnk_versioning.txt) plugin.


Live test: [http://wagebyra.com/projects/txp.foundation/](http://wagebyra.com/projects/txp.foundation/)

## Install

1. Drop [/txp.foundation](https://github.com/whaleen/txp.foundation) in the root directory of your Textpattern project.
2. Install Textpattern plugin [cnk_versioning](https://github.com/whaleen/txp.foundation/blob/master/textpattern/plugins/cnk_versioning.txt) and edit the path in it's source to point to [/txp.foundation/textpattern/_templates](https://github.com/whaleen/txp.foundation/textpattern/_templates). Follow cnk_versioning's own instructions via the plugin's help if you are not already familiar with how it works.
3. Sally forth.

## Using Sass

    $ cd txp.foundation 
    $ gem install sass
    $ sass --watch scss:css
