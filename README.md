### Purpose

Store image files (`.jpg`, `.png`) to be accessed via address link (URL). 

Example: "Better Canvas" browser extension (chromium) allows users to set custom dashboard course card images.

#### Errors

1) Beyond symlink (directory):
   * If a directory itself is a symlink git cannot traverse the file path to access files contained in that directory. Each file must be individually a symlink.

