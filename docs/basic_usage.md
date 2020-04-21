# Basic Usage

### Page Choooser
1. Open the Wagtail Admin on the destination site.
2. In the menu, select `Import`.
3. Select a source site.
4. Using the page chooser, select a parent page on the source site.
   This page, and all of its descendants, will be imported.
5. If this page was not previously imported, you will be prompted to select a page on the destination site: the imported
   page tree will be created as a child of this page. If the page has already been imported on the destination site, the
   existing page/s will be updated and you will not need to select a destination parent page.
6. Click the import button, which tells you how many pages will be imported.

### Model Choosers
1. Open the Wagtail Admin on the destination site.
2. In the menu, select `Import`.
3. Select a source site.
4. Using the snippet chooser, select an entire model or select an individual snippet to import.
5. If the object was not previously imported a new object will be created in your destination website.
6. Click the import button

The pages - and, depending on your [configuration](settings.md), their associated objects, such as images and documents - will now be available on the destination site.
