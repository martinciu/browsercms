## Issue #566: Add Ckeditor inline editing

### Question

* For developers, should we continue to call it text?

### Features

* No need to toggle the editor on/off. Just click the area of the page you want to edit.

### ToDo

* Full Edit - Click to edit in full text editor.
* Order blocks on pages
* Add a 'Preview' button - Open window in new tab, no UI.
* Edit page title
* Handle editing other blocks (i.e. Products)
* Link to files
* Link to images
* View as Mobile? - Does this still work?

#### Other Desired Features

* Edit Page - Show all editable components on a page (title, etc).

### Bugs


A. Removing/re-add block from page and it won't update   (Versioning bug?)

I observed this during testing but was unable to recreate. Might have been a data issue.

Possible Steps:
    1. Add text to homepage
    2. Edit it several times
    3. Remove it
    4. Readd it to the page
    5. Try to edit it

    Observed: 'Old' version of the block would still be shown.

B. 500 error after editing and removing a block
