[Mirador](http://projectmirador.org) 2.x code uses [BootBox](http://bootboxjs.com/) to create some dialogs (notably confiramtion for updating or deleting annotations). BootBox is currently (as of 2/9/2018) not supporting Bootstrap 4. 

If you embed Mirador as a component in your HTML page, you are pretty much stuck with Bootstrap 3. The dialogs will fail to show up under Bootstrap 4 or Semantic UI, for example.

You can include either one of the JavaScript files here (after including the Mirador code) to override the DialogBuilder code of Mirador to make it work with Bootstrap 4 or Semantic UI. You can also take a hint from these files and make your own override to suit your purpose.



