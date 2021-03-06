
Changes by Pollin14
===================

* I changed the icon's url to work with bower out of box. The original url points to the *ckeditor* directory however
the image are in *ckeditor-youtube-plugin/youtube*. Then, after you run the `bower install`, you need copy the plugin
to *ckeditor* directory. It is not acceptable.

* I added a translation to spanish (Español).

Add to bower
============

Add the repository to the bower's dependencies.

````
"dependencies": {
    "ckeditor-youtube-plugin": "https://github.com/pollin14/ckeditor-youtube-plugin.git"
}
````


Youtube Plugin for CKEditor 4
=============================

Copyright © 2013 Jonnas Fonini <contato@fonini.net>.

This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the LICENSE file for more details.

This plugin allow you to insert Youtube videos using embed code or just the video URL.

## Installation

Follow these steps:

 1. Download the latest version of the plugin from Github.
 2. Extract the downloaded file into the CKEditor's **plugins** folder.
 3. Enable the plugin by changing or adding the extraPlugins line in your configuration (config.js):

    ````
    config.extraPlugins = 'youtube';
    ````
    
## Configuration
The default options can be overriden on config.js.

Video width:

```
config.youtube_width = '640';
```

Video height:

```
config.youtube_height = '480';
```

Show related videos:

```
config.youtube_related = true;
```

Use old embed code:

```
config.youtube_older = false;
```

Enable privacy-enhanced mode:

```
config.youtube_privacy = false;
```

Start video automatically:

```
config.youtube_autoplay = false;
```

## How to use
If everything is ok, a Youtube icon should appear on the CKEditor toolbar. Click it,
paste your embed code or video URL and the video will be inserted.

## Translators
Thanks to those who helped translate the plugin

 * Eyed Farra (ar)
 * Sven Jansen (de)
 * Dimitris Kotsakis (el)
 * BiomanRouge (fr)
 * Moshe Simantov (he)
 * Karmacsi Gábor (hu)
 * Francesco Zanoni (it)
 * Yayoshi Nobuhide (ja)
 * Patrick van Lier (nl)
 * Michał Zalewski (pl)
 * Alexander Ustimenko (ru)
 * Çağdaş Yiğit (tr)
 * Vu Thao (vi)
 * trowa (zh)


[![Licensed under the WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-2.png "Licensed under the WTFPL")](http://www.wtfpl.net)
