This repository holds the code that renders the Library of Juggling, a website dedicated to cataloging juggling patterns. I created the site back in 2012, and it has become an essential resource for jugglers looking to expand their repertoire. Although the library is no longer updated, I continue to host it at <https://libraryofjuggling.com/>.

To prepare this repository, I rebuilt the Library of Juggling using Jekyll so that changes could be more easily propagated across the site. The `_include/default.html` layout file is used by all pages, and contains the side navigation bar which is rendered from `_data/tricks.yml` using Liquid. The juggling GIFs used throughout the site are not tracked here, but can be downloaded in a zip file from this [GCP bucket](https://storage.googleapis.com/icpublicstuff/projects/libraryofjuggling/juggling_gifs.zip). The `JMLarchive` directory includes the JML files that were used by JugglingLab to create most of the GIFs, and is not directly part of the website.