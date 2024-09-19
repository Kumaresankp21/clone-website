--mirror: This option enables mirroring of the website. It’s essentially a shortcut for several other options that ensure the site is downloaded in a way that preserves its structure and makes it suitable for offline viewing.

--convert-links: After downloading, this option converts the links in the HTML files so that they point to the local copies of the files rather than the original online versions. This ensures that you can navigate the site offline without running into broken links.

--adjust-extension: This option adds the appropriate file extensions (like .html) to files based on their content type. This helps in ensuring that files are saved in a way that makes them easily recognizable and usable offline.

--page-requisites: This tells wget to download all the necessary elements (like images, stylesheets, and scripts) required to properly display the pages. This ensures that the downloaded pages look as they would online.

--no-parent: This prevents wget from downloading files from parent directories. It restricts the download to the specified URL and its subdirectories, ensuring you only get the content you want.
