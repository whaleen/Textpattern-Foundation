Foundation 6 for Textpattern CMS
==============

Older: [<a href="]https://github.com/whaleen/Textpattern-Foundation/tree/Foundation-4](Textpattern &amp; Foundation 4)

### Here now is 6

Textpattern is the CMS of legend. Foundation is a CSS/JS Framework.

Requires the [cnk_versioning](https://github.com/whaleen/Textpattern-Foundation/blob/master/textpattern/plugins/cnk_versioning.txt) Textpattern plugin.

## Install

1. Drop [/Textpattern-Foundation](https://github.com/whaleen/Textpattern-Foundation) in the root directory of your Textpattern project.
2. Install Textpattern plugin [cnk_versioning](https://github.com/whaleen/Textpattern-Foundation/blob/master/textpattern/plugins/cnk_versioning.txt) and edit the path in it's source to point to [/Textpattern-Foundation/textpattern/_templates](https://github.com/whaleen/Textpattern-Foundation/textpattern/_templates). Follow cnk_versioning's own instructions via the plugin's help if you are not already familiar with how it works.
3. Sally forth.

## Using Sass

```
$ cd Textpattern-Foundation
$ gem install sass
$ sass --watch scss:css
```
