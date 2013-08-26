txp.foundation
==============

Textpattern &amp; Foundation 4

Install [cnk_versioning](https://github.com/whaleen/txp.foundation/blob/master/textpattern/plugins/cnk_versioning.txt) plugin.

Edit plugin code:

Change

    $CNK_VER_OUTPUT_PATH = 'admin/'; //e.g. 'textpattern/_templates/versioning/'
    
to

    $CNK_VER_OUTPUT_PATH = 'txp.foundation/textpattern/_templates/'; //e.g. 'textpattern/_templates/versioning/'



### Using SASS

    $ cd txp.foundation 
    $ gem install sass
    $ sass --watch scss:css
