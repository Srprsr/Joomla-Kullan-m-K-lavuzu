# Joomla Kullanım Kılavuzu

#Introduction
Joomla is a great Content Management System with a lot of flexibility and with an
easy-to-use user interface that a lot of people get intimidated about when they
realize how many options and configurations are available. This manual is meant to
serve as a guide to Joomla’s basic features and help you install and start your first
Joomla website.

![alt text](http://www.webdoor.com.au/images/joomla.png "Joomla Logo")

We have all been beginner
users at some point, so I
hope this guide helps
answer some of the questions you might have.


##What is a CMS (Content Management System)?
A Content Management System is a series of programming pages connected to a
database that allows one to retrieve information from that database in the form of
content. Sounds complicated? You’ve used one more often that you think.
Have you ever updated your Facebook page or created a blog? Have you ever
bought a book from Amazon.com or bid on something on eBay? Have you ever
read The New York Times Online or checked something out on Wikipedia? All of
these sites work with a type of Content Management System.
The ones we will be focusing on are ones that allow you to manage your own
website from a simple interface, to creating your own pages and menus without the
need for knowing how to program yourself.

##About Joomla
Joomla is a platform based on PHP and MySQL which was created in 2005 by a
team of open source developers. It currently has 200,000 community users and
contributors. Joomla is free to anyone who wants to download it and use it to create
a website. It is also open to anyone who wants to create extensions and templates.
The most current version of Joomla can be downloaded from
http://www.joomla.org/download.html

Why Joomla?
There are three main free CMSs available today, and endless other less popular
ones. The most popular Content Management Systems available are: Joomla,
Drupal and Wordpress.
The differences among them are quite significant, although they are basically
meant to do the same thing – to help you create and manage your website. There
have been many heated arguments between the Joomla and the Drupal users over
which one is best. As someone who has used them both, my take is that they each
have their good and bad points.

###Joomla

**Pros**:

* Joomla is usually easier to get up and running and tends to have a
quicker learning curve.
* Joomla tends to have better looking templates and a friendlier
community, even towards beginner users.

**Cons**:

* Joomla’s code can be messy at times and loading time tends to be
longer because of that.
* Its architecture limits how many levels of sub categories can be created.
* 
###Drupal

**Pros**:

* Drupal has a more flexible infrastructure, allowing you to create multiple
sub-categories and with more advanced user features.
* Fast loading time and reasonably clean code.
* 
**Cons**:

* Longer learning curve and usually a longer install to launch time.
* Although the community is supportive, there is less tolerance to new users
and people asking very basic questions.
Basically, they are both excellent CMSs and which one you choose should depend
on your particular needs and willingness to work through each CMS’s individual
problems.

![alt text](http://i.hizliresim.com/kvyyyW.jpg "Joomla Logo")

Also pay attention to what modules and themes each CMS has as you may require
one that is not on both platforms. It is best to weigh up the pros and cons of each
CMS before you go ahead and create your website.
Wordpress is different in many ways. Wordpress truly is built to serve primarily as a
blogging platform. It also has a large community and flexibility to evolve beyond a
simple blog, but it works best as a delivery medium for always changing material
exactly the way blogs are supposed to be. That being said, you can create nice
websites using Wordpress that are not blogs.

#Installing Joomla

##Basic Requirements

There are two ways to install Joomla. Manually and using an installation software
such as Fantastico or C-panel, which are installed in the host’s server and offer an
user friendly interface for the management of the site and the installation of
software, but the requirements for both are very similar.
Since Joomla is a database driven system, it requires a SQL database to run. That’s
where it will install its tables and store information you add to it. Joomla also does
better on a relatively fast server, so if you have been on the same server for longer
than you can remember, contact your host and check if it’s been upgraded and if
that’s not the case, ask to be moved to a newer server.
Joomla uses a lot of resources and your site will load faster if the server can handle
many processes at once. There is also a chance that the technology on older
servers won’t support Joomla’s newest versions. You can view a list of the most
current requirements at: http://help.joomla.org/content/view/1938/302/
If you are using Fantastico or C-Panel, check the version of the installer. You want
the newest version of Joomla if possible, and at the very least one version behind.
New versions usually carry security upgrades as well as bug fixes, and when dealing
with a dynamic site, those fixes can make a big difference.
To determine Joomla’s latest version, visit the Joomla website.

Installation with C-Panel

So you have checked all the requirements, what now? Well, if you have C-Panel
installed on your server, you have your work cut out for you.
Go to C-Panel, look for Fantastico and look under the Content Management
section. Check the version of Joomla they have available. You want the 1.5 version
at least. If it is a recent version, click “New Installation” (some versions of Fantastico
also give you an option to upgrade your installation if you already have one).

![alt text](http://i.hizliresim.com/r9obmz.png "Joomla Logo")

You will be asked to fill in the following fields:
* What domain you want to use.
* Install directory (leave it empty if you want it to be in the root folder of your
site or create the name of a directory if you want it to be inside a folder within
your site).
* Admin username and password, email and full name.
* Site name
* Install user data (check box). This option will install pages, menus and
directories with Joomla information. If you’d like to see them and change
them around as a way of learning how to use the site, leave this option.
Personally, I find this option cumbersome, since you have to go ahead and
delete all the Joomla pages from your site, so I always uncheck this. Then click
“Install Joomla”.

![alt text](http://i.hizliresim.com/pPpL40.jpg "Joomla Logo")

Just give it a few minutes and C-Panel will create the database and install Joomla
for you. It will then give you a link to your installation and to your administration,
which is where you go to create articles and configure your site.

##Manual Installation
Now what do you do if your server does not provide you with C-Panel? Don’t worry,
there are a few more steps, but it’s still not a long process.
You will need a database, an FTP program and Joomla Installation files.
###Step 1 – The Database
Most hosts nowadays, allow you to create databases using their administration. You
won’t have to know how to deal with the database once it’s created. All you need
is the:
* Database Name
* Database ID
* Database Password
* Database Path (or address)
Once you create the database, you should have access to all that information.
Keep it safe, since Joomla will ask you for it during the installation.

###Step 2 – Downloading Joomla Files
Once you have the database set up, you need the Joomla Installation files. You can
get the most updated files from: http://www.joomla.org/download.html
Download them to your computer as a zip file and extract them to your website
folder. Now, you have two options here. If you want Joomla to be your whole site, or
the main part of your site, you should put it on the root folder, which is the main
folder for your site.
If instead, you already have a site and you only want Joomla to be part of that site,
in a subfolder such as: http://mysite.com/joomla, then you should create that folder
and extract all of the files to that folder instead.

###Step 3 – Uploading Joomla Files
Next, you should upload all of the Joomla files to your host using an FTP program, or
extract the zip file directly to your server through the server’s file manager.
THE COMPLETE BEGINNERS GUIDE TO
JOOMLA
http://simplytatydesigns.com | Taty Sena
MakeUseOf.com

###Step 4 – Running the Installation
Once that is done, go to (if you uploaded Joomla to the root folder):
http://yoursite.com/index.php
Or if you uploaded it to a sub-folder, go to:
http://yoursite.com/JoomlaFolder/index.php
From that point on, follow the install wizard. 

![alt text](http://i.hizliresim.com/PMZgQ7.png "Joomla Logo")

It will ask you for a language, and then it will check whether your server can handle
Joomla without any problems.
On some specific hosts, Joomla's folders might not default to their correct permission 
settings, which would cause it to display an error saying 'Access is not allowed'. In
that case, you might have to access those folders and change the permissions by
hand.
Some hosts provide an interface on their administration that allows you to do that,
otherwise, check the permission instructions on the FTP program you are using. When
changing permissions, you must be very careful, because if you change the wrong
folders, your site may be wide open to hackers.
There are many discussions about which security setting should be used with Joomla.
The basic permission settings are:

![alt text](http://i.hizliresim.com/o7R1pb.png "Joomla Logo")

Use the most secure setting for all non-public files whenever possible and when it
doesn't affect installations and usage of Joomla.

##Step 5 – License
Next, read over Joomla’s license, it is pretty straightforward.

![alt text](http://i.hizliresim.com/2ZVbzE.png "Joomla Logo")

##Step 6 – Database Information
The following page is where you will need your database information.

![alt text](http://i.hizliresim.com/L3WLjV.png "Joomla Logo")

Select:
* The type of database (mysql is the most common)
* Hostname (the address or path to your database)
* Username and password (for the database)
* Database name (you probably chose that when creating the database)
Note: Depending on your host, you might not have been given a choice to select
your options for the database creation. In that case, try hostname “localhost” and
username and password provided by your hosting company.
If you are installing on a localhost using WAMP or XAMPP, the Username is usually
“root” and the password is nothing/blank.
Unless you know what you are doing or have received an error during the
installation, don’t bother looking at the advanced settings.
Continue through the configuration. You will be asked to add basic information such
as email and site name, and be given an option to install “Sample Data”. As I
explained on the C-panel install, this option will install pages, menus and directories
with Joomla information.
If you’d like to see them and change them around as a way of learning how to use
the site, leave this option. I usually don’t like having all those pages installed on my
sites, because I have to delete them later.
If you continue with the prompts, you should now have a “Congratulations” page. 

![alt text](http://i.hizliresim.com/R3lq2Z.png "Joomla Logo")

All you need to do now to start using your Joomla site is to go back to FTP and
delete the “Installation” directory. Having this directory still on the site is a major
security issue.
You are now ready to start adding content to your website through the Joomla
interface.


![alt text](http://i.hizliresim.com/R3lq2Z.png "Joomla Logo")

##Configuration Settings
Once Joomla is installed, it’s time to start adding content and managing your site.
You will need to log into the administration of the site. The default administration can
be found at: http://(your site and folder where Joomla is installed)/administrator. You
will need the username and password you set up during installation to log in and
access the backend of your site.

![alt text](http://i.hizliresim.com/bbdz6b.png "Joomla Logo")

##User Manager
The user manager allows you to create new users by clicking the “new” button and
to edit existing users. You can also use this interface to define what permission group
they belong to, which defines what they can and can’t do on the site. 
For example, “super administrators” have full control of the site; meanwhile,
registered users can access parts of the front end of the site that require a log in, but
not much else.
##Global Configuration
There are three tags under Global Configuration, and your choices here affect the
whole site. They are:
###Site
You can take the site offline (so no one can see it while you work on it). It will say the
site is down for maintenance.

![alt text](http://i.hizliresim.com/kvyNMq.png "Joomla Logo")

You also have an option to change the site name and to choose a default
WYSIWYG editor (Watch You See Is What You Get), which is the interface for you to
create your articles, make fonts, bold, create tables, etc. The default is TinyMCE. You
can install others if you like. Joomla has a large selection of extensions available for
download, but more on that later.
List length determines how long the lists of articles on the backend of your site will be
by default, before Joomla displays a "next page". 
Feed length and feed email determine the length and email for the RSS feed on
your site.
Global Site Meta Description and keywords is the description that Google and other
search engines will pick up as being the general site description and keywords.
##SEO settings
Search Engine friendly URLs will modify the address of your pages from something
that looks like this:
http://yoursite.com/index.php?option=com_mtree&task=listcats&cat_id=1922&Itemi
d=35
to something that looks like this:
http://yoursite.com/about-us/contact
or
http://yoursite.com/index.php/about-us/contact.html
If you choose to add a suffix to the URL (that’s the .html part)
That will only work in some hosts if you use an Apache mod_rewrite, hence that
option. The best way to find out is just to try without it, and if you have problems,
change that option to yes.
You can even have it so there is no index.php in the URL.

![alt text](http://i.hizliresim.com/o7RDpR.png "Joomla Logo")

##System
Under the system settings you will see several options you might want to consider
modifying, which control whether users can register on your site and what kind of
privileges they can have. Some of the most important features are:

![alt text](http://i.hizliresim.com/goJ3DN.png "Joomla Logo")

##User settings:
Allow user registration (yes, no) – Determines whether people are allowed to register
as site users or not. If you select yes, you can determine what level of access the
new users will have when they sign up. The options are:
New user registration type:
* Registered – Can’t edit or publish any articles. The user is simply a registered
user of the site with no privileges.
Author – Can create content and determine where it should go and some
minor settings relating to their individual articles.
* Editor – Has the same ability as the above users, but they can also edit articles
by other users.
* Publisher – Can do all of the above, plus the ability to choose whether an
article will be published or not.
(Detailed information can be found at: http://docs.joomla.org/)

New User account activation (yes, no) - Determines whether the site requires that
they respond to an activation email.
Path to media folder - if you decide to change where the media manager files are
stored you can put the new URL here.
Path to image folder - if you decide to change where your photos are stored you
can put the new URL here.
Minimum User Level for Media Manager (author) – Allows you to decide which kinds
of users can have access to your media manager, which would allow them to
upload pictures, delete them and move them. Author is the default choice, since
they might need access to upload images to articles they create.
Most of the other ones you should only change if you know what they do.
###Server
Most options will already be set for you during installation. The options you must
change are:
Under mail settings:
Mail from - the email you want to use when sending messages from your Joomla site
From name:
The sender name you want the receivers to see on the emails you send using your
Joomla site.

![alt text](http://i.hizliresim.com/PMZLbb.png "Joomla Logo")

##Tools
Most of the tools under this button can be used for general management
maintenance of the site and communication among users. You can send private
messages to users or mass messages to all of them.
When another user is editing a file, a little padlock prevents others from editing it at
the same time, and “checks it out” for the time being. The Global Check In basically
makes everything that was checked out available for editing by checking them in
again.
Some mods cache some of the information for speed’s sake. You can clear that
cache if you need to by using the “Clean Cache Admin” and the “Purge Cache
Admin”.

#How To Publish Content
The Joomla architecture requires that every article belong to a section and a
category (unless you make it unspecified). Because of that, before you start
creating the sections and categories, you need to think of the names that you might
need. Think of a section as being a like a drawer in a filing cabinet, a category is the
folder inside and articles as the documents inside the folder.
Another good rule of thumb is to think of the sections and categories as one thinks of
the menus and pull down menus. Let’s say you want to have a button called “About
my company”, and when someone puts the mouse over that button, a pull down
menu with the options “Staff” and “Locations” appears.
That is a good guideline to creating your sections and categories. Make “about my
company” a section and “Staff” and “Locations” the categories. They you can
create one page for each person in the staff and place it inside the “Staff”
Category and all different locations your business has on their own page with map,
contact and information, and place each of those pages inside the “Locations”
category. That way you can keep your site organized for when you are ready to
create the menus.
##Sections
So to create a section, simply go to the “Content” menu button and select
“Sections”. Once on the page, click the “New” button. You will be taken to a page
with several options. The only one you really need is the Title, and a Description if you
want to link a menu button to that section at some point, otherwise, just the title
would be enough.
##Categories
From the content menu, you can also
get to categories. Since they are subcategories
of sections, they work in a
similar way, and you should also add a
Title, but this time you must also select
a section for the category. All the
other fields are optional and not
necessary for the functioning of the
site. 
##Articles
Now that you have your sections and categories created, we can start adding
some real content to the site. To create an article, go to “Content”, articles and
click “New”.
You will be taken to a page that looks a little like Microsoft Word, but without as
many features. It is what we call a WYSIWYG (What You See Is What You Get)
interface. What that means is that whatever you do on this page will be translated
by the software into HTML which can be read by web browsers as a webpage.
Start by adding the title. The alias is not necessary. You must then select a section
and the category (which is why you had to create them first). You can then add the
text and images in either view, the standard WYSIWYG viewer or directly to the HMTL
(by clicking the little HTML icon). You can also add SEO (Search Engine Optimization)
information by clicking on the Meta Tags option on the right hand side.
One other button worth mentioning is the “Read more” button. You would use this
button if you want people to read a short preview of the article and have to click on
the read more link on the article to read the whole thing. Basically, just select where
you want the preview to end, click on it and then click on the “Read more” button. 

![alt text](http://i.hizliresim.com/y4r7Qa.png "Joomla Logo")

It will add some code to the article to create the “Read more” button. It is
particularly useful if you are using a blog display (more on that later) and don’t want
a list of complete articles to display on the same page.
You will also notice that there are several advanced parameters you can modify
such whether you want to display the name of the author or whether you want to
display the default PDF, print and email icons that usually appear on the upper right
hand side of Joomla articles.
##Media Manager
The media manager is your tool to organizing your images. One important thing to
know about the media manager is where to put your files. By default, it comes with a
few images (such as fruit and food). Those images can be accessed from the
articles interface to be added to the articles, but only the folders and images
placed inside the “Stories” folder can be accessed that way.
You can still link to the other images, but you must find their address by hand and
type it in, so for ease of use, I suggest you place all of the images you will be placing
on the pages of your site in organized folders inside the “Stories” folder.
Another thing to know is that the Media Manager does not re-size images, so if you
are uploading huge images, they will distort your website once you place them on
the website, and even if you change the image size by hand on the code within
Joomla, those images will still take a long time to load and significantly slow your site
down. So re-size and compress them with image software in your computer before
uploading them to the Media Manager.
##Front Page Manager
The Front Page Manager is the manager that let’ you choose the order and
particular features of the articles you have selected to appear on the home page
(Front page) of your site. It can be reached from the “Content” menu. It’s the place
where you can manage the options for the articles you chose to have on the front
page of your site.
One of the most useful features is the possibility of re-ordering them (which is a
feature also available in sections, categories and articles). To do that, go to the front
page manager, and look at the list of articles listed there. You will see a column
called “order”. Change the numbers around to the order in which you would like
them to appear on the page, then click the little save icon on that column, right
next to the “order” title. 
