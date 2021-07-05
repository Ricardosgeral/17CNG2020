#  Web Site for 17CNG

This repository contains code and data for the 17CNG 2020 web site.

#### Generating site using jekyll

The website uses jekyll engine to generate the website using the templates. To get started with jekyll:

    gem install jekyll bundler
    bundle install
    bundle exec jekyll build

To generate the website and serve it from a local webserver, e.g., for debugging
 
    bundle exec jekyll serve

The site is served locally in http://localhost:4000/ (127.0.0.1:4000 may not work properly!)

## Overview

The repository is organized as follows:

* `_DOCS/`      are various files used to prepare other files, but not directly published themselves.

* `_config.yml` is a configuration file for the website, defining title, menu, and several basic parameters
* `_data/`      contains datasets in YaML or JSON format defining conference dates, news, and supporters
* `_includes/`  are supplementary scripts to generate website's content, including templates for menu, news, google analytics, and sponsors
* `_layouts/`   are layout files

* `css/`        CSS code. Only edit style.css, the rest is 3rd party.
* `css/images/` jquerymobile CSS images
* `images/`     Our images (logos, etc.)
- The program item styles (talk,paper,demo,session,etc.) are defined in `_sass/customization.scss` (for instance, .prog-social).
- The program item styles (talk,paper,demo,session,etc.) are defined in `_sass/customization.scss` (for instance, .prog-social).
- Some basic coloring scheme is defined in `_sass/variables.scss`.

- To change the sources of the picture slideshow on the main site, edit index.md. In particular, add your pictures here:
```
<div id="sliderFrame">
  <div id="slider">
    <img src="images/header_1.png" alt="" style="width:500px"/>
    <img src="images/header_2.png" alt="" style="width:500px"/>
  </div>
</div>
```

- Supporters and their priorities that will be shown on the footer (and on the supporters.html as well), 
please edit `_data/supporters.json` (prio, picture name, link, 0, width, height, tag). Note that width and height are important since they are used to show the pictures in a good aspect ratio. You can easily get this info in linux as follows:
```
$ file vmware.jpg

vmware.jpg: JPEG image data, JFIF standard 1.01, resolution (DPI), density 72x72, segment length 16, Exif Standard: [TIFF image data, big-endian, direntries=7, orientation=upper-left, xresolution=98, yresolution=106, resolutionunit=2, software=GIMP 2.8.10, datetime=2016:07:11 16:32:06], progressive, precision 8, 420x100, frames 3
```

## License

Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License (see [LICENSE.md](LICENSE.md) for details).

## Credits

This site is based on the [SIGCOMM 2018 site](https://github.com/cslev/sigcomm_2018).

You are welcome to reuse and adapt the code under the same Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License and the same sharing conditions as above.
