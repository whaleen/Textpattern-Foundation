txp.foundation
==============

Textpattern &amp; Foundation 4

Requires [cnk_versioning](https://github.com/whaleen/Textpattern-Foundation/blob/master/textpattern/plugins/cnk_versioning.txt) plugin.

## Install

1. Drop [/txp.foundation](https://github.com/whaleen/Textpattern-Foundation) in the root directory of your Textpattern project.
2. Install Textpattern plugin [cnk_versioning](https://github.com/whaleen/Textpattern-Foundation/blob/master/textpattern/plugins/cnk_versioning.txt) and edit the path in it's source to point to [/txp.foundation/textpattern/_templates](https://github.com/whaleen/Textpattern-Foundation/textpattern/_templates). Follow cnk_versioning's own instructions via the plugin's help if you are not already familiar with how it works.
3. Sally forth.

## Using Sass

    $ cd Textpattern-Foudnation
    $ gem install sass
    $ sass --watch scss:css
