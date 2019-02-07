# jquery-tabbed-webpart
jQuery Tabbed Web Part

See https://gallery.technet.microsoft.com/sharepoint/jQuery-Tabbed-webpart-65ede893

To use:

  1) Save the script to your machine
  
  2) upload the script to a location from where you can reference to your site
  [Site Assets document Library, if  have a fear of somebody will delete better to keep it  under root]
  
  3) Add a content editor webpart to a page where you want to show jquery tabbed webpart
  
  4) Add all the webparts[Which wanted to show in tabs] under content query webpart on the same page
  
  5) Edit the downloaded script [in step 1] with the name of webparts which added on the previous step 4.

    //put all the webpart names which you want to show in "tabs"       
    jtabs(["webpart1","webpart2","Webpart3"]);

  6) Link the script to the content editor webpart [added in step 3]

    Note: Don’t forget to enable the chrome= “title” from the webpart properties, otherwise jquery will not identify the webparts on page and show webparts on all tabs.
