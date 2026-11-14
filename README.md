# THE FOOTBALL ARCHIVE

THE FOOTBALL ARCHIVE is a digital football book and encyclopedia documenting modern football and selected historical eras. It is intended to grow into a collection of chapters, editorial articles, player profiles, club histories, and match stories.

## Technology

This project uses **HTML5 and CSS3 only**. JavaScript, frameworks, and component libraries are not part of the project.

## Structure

- `index.html` is the project homepage.
- `pages/` contains the top-level archive pages.
- `chapters/` organizes content by era.
- `players/`, `clubs/`, `matches/`, and `stories/` are reserved for archive entries.
- `css/` contains the reset, design-token entry point, typography, and stylesheet entry points.
- `assets/` contains image, font, and icon directories.

The HTML pages link to the shared CSS files. Pages inside `pages/` use paths relative to their nested location. The design-token file and layout/component styles are intentionally unpopulated until the visual direction is supplied.
