# csce378-gradetracker

Since this is just a prototype we should be able to fake everything without the need for a web server. That idea is that you just open the file directly in your web browser, and use relative links from there.

I've included some basic libraries we will be needing, including [Bootstrap](http://getbootstrap.com/) for the base layout and syling, [Datatables](https://datatables.net/) for tables, and [jQuery](https://jquery.com/). Data will be stored in the browser using [PouchDB](https://pouchdb.com/).

We can persist data for users through browser data, and use URL parameters where needed. Javascript isn't great, but it should work for a simple prototype. 

## Opening the application

Clone this repository, you can use a program like [SmartGit](http://www.syntevo.com/smartgit/) (which is free for non-commercial use), or use the command line git [client](https://git-scm.com/). Then in the cloned folder, drag the index.html file to your web browser.

You should then see the home page of the application. Links from there are all relative to that index.html file. 

## Editing the application

Just edit the files in a text editor. You will need to commit and push your changes once you make them, using your git client. 

I already have some basic pages laid out, and some example database rows in the init.html file, we'll use this to initialize the application with a test class or two before doing any presenting (just drag it into your web browser). 

Keep in mind that the URLs are all relative, and each file is completely independent. If you change a label on one page, you might have to change it on others. 

You can get data out of the database, and put data back in, using PouchDB in Javascript. Information on the page can be updated using jQuery with the objects from the database. 
