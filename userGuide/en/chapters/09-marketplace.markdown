# Liferay Marketplace

Liferay Marketplace is an exciting new hub for sharing, browsing and downloading Liferay-compatible applications. As enterprises look for ways to build and enhance their existing platforms, developers and software vendors are searching for new avenues to reach this market. Marketplace leverages the entire Liferay ecosystem to release and share apps in a user-friendly, one-stop site.

This chapter covers the following topics:

- Users, Companies, and Apps
- Accessing Liferay Marketplace
- Finding, Downloading, and Installing Apps
- Managing Apps
- Plugins and Plugin Management
- Portlets, Themes, Layout Templates, Hooks, and Web Plugins
- Installing Plugins from Repositories
- Installing Plugins Manually
- Plugin Troubleshooting and Configuration Issues
- The Software Catalog

In a nutshell, the Liferay Marketplace is a repository for applications built on the Liferay Platform. You can find and download applications directly from the Marketplace on the web, or use an existing Liferay installation to access and install applications onto the running Liferay web site. Once installed, you can manage the applications through Liferay's control panel. 

## Marketplace Concepts: Users, Companies, and Apps

Anyone can browse the apps available on Liferay Marketplace at [http://liferay.com/marketplace](http://liferay.com/marketplace) but a `liferay.com` user account is required for purchasing and downloading apps, whether from the Marketplace website or from an existing Liferay installation. Many official Liferay apps, as well as some third party apps, are available free of charge. Other apps require you to pay a fee in order to access them. When you purchase an app, you can do so on your own behalf or on behalf of a company. Apps purchased on your own behalf are associated with your personal `liferay.com` user account. Apps purchased on behalf of a company are associated with that company's account and can be accessed by any users that belong to that company. Once you've purchased an app, you're free to download and install any available version of the app whenever you like. We'll explain how to set up a company account, manage company apps, and join companies after we discuss how to access Liferay Marketplace.

## Accessing the Liferay Marketplace

There are two ways to access the Marketplace.

1. Via the website--Using your favorite browser, you can navigate to the marketplace at [http://liferay.com/marketplace](http://liferay.com/marketplace).

2. Via Liferay--If you have a site up and running based on Liferay, you can use the Marketplace section of the control panel to access Marketplace content.

### The Basics

No matter which method you choose, you will see the same content and apps.
 
If you are new to the Marketplace, the easiest way to access it is by using your browser to navigate to [http://liferay.com/marketplace](http://liferay.com/marketplace). You will be presented with the Marketplace home page.

![Figure 9.1: Marketplace Home Page](../../images/marketplace-homepage.png) 
 
In the center of the page, you will see a number of icons. Each icon represents an individual app and they are grouped into a couple of different areas:

* New To Marketplace: The latest apps that have been added to the marketplace
* Featured Products: Liferay features a different set of apps each month
* Most Viewed: The top 10 most viewed apps

If you click on the title of an app, you can access details about the app, including a description, the author's name, screenshots, price, latest version, number of users, number of weekly installs, a link to the developer's `liferay.com` profile page, a link to the developer's own website, a link to report abuse, and a Purchase button. You'll also be able to view version history, read reviews left by other users, or write your own review. 

![Figure 9.x: Marketplace App Details](../../images/marketplace-app-details.png) 

If you click on the Purchase button, you'll be prompted to choose a purchase type. You can purchase an app for your personal account or for your company. If your company has already been registered, select it in the drop-down list. If you'd like to purchase an app for your company, but it hasn't been registered yet, you can click the *Register Your Company* link to register your company with Liferay Marketplace. Please see the *Creating a Company* section below for details.
 
The left side of each page in the [http://liferay.com/marketplace](http://liferay.com/marketplace) site contains a Marketplace navigation menu. This menu contains links to various categories of apps and themes that are available from Marketplace. Clicking on the individual categories will allow you to browse apps in that category. To view all apps or themes at once, click the *Apps* or *Themes* link and then the *See All* link in the Apps or Themes portlet.

![Figure 9.2: Browsing Apps in Marketplace](../../images/marketplace-browsing-apps.png)

Below the navigation menu is the search bar. This allows you to search for apps with specific titles. Type in search terms and click *Search* to perform the search.
 
### Logging In

You do not need a `liferay.com` account in order to browse the Marketplace. Once you decide you wish to purchase and download an app (or if you are a developer and wish to create and upload new apps), you will need to establish a `liferay.com` account, and agree to the Marketplace Terms of Use. To get a new `liferay.com` login, visit the register page and sign up! Once you are signed in, you will be able to fully utilize the Marketplace to find and use Marketplace apps.
 
### Marketplace Profile

On your existing `liferay.com` Home page, you'll notice a new link entitled *App Manager*. The App Manager allows you to access information about the apps you've purchased and apps you've uploaded to Marketplace. It also provides a mechanism for uploading new apps to Marketplace. Once you submit your app, it will be reviewed before appearing on the `liferay.com` Marketplace.

---

![tip](../../images/01-tip.png) Note: Your `liferay.com` Home page is a private page. It's distinct from your public `liferay.com` Profile page.

---

### Managing Apps

The App Manager shows you relevant information related to your usage of Marketplace. You'll find three tabs to help you manage your Marketplace apps: *Purchased*, *Apps*, and *Add an App*.

The Purchased tab lists the apps that you have purchased. From this screen, you can find information about the authors of the apps you have purchased. You can also download or re-download the app (for example, if you lost your copy or have re-installed Liferay and wish to re-deploy the app). This option is also useful for downloading apps and deploying them to offline instances of Liferay that do not have direct access to `liferay.com`.

![Figure 9.4: Purchased Apps](../../images/marketplace-purchased-apps.png)

If possible, it's best to log into your portal instance and install purchased applications through the My Marketplace link in the control panel. This will provide your portal instance with automatic update notices should they become available. If you download applications this way, they can be hot-deployed.
 
The Apps tab lists apps that you have authored and uploaded, showing you details such as the number of downloads, the current price, and other relevant information. From here you can manage the apps that you have created (please see the Marketplace chapter of the Developer Guide for details on this topic).
 
![Figure 9.5: Upload an App](../../images/marketplace-upload-app.png)
 
Clicking on *Add an App* allows you to upload a new app and make it available in the marketplace. Please see the Marketplace Developer Guide for more detail on authoring your own app.

### Creating a Company

To create and register a company with Liferay Marketplace, click the *Create a Company* link in the left-hand navigation menu. Your first step is check to if your company already exists on Liferay Marketplace. Enter your company name into the search box and check if it's already been registered. If someone else from your company has already created a company account on Liferay Marketplace, you can click the *Request to Join this Company* button. This will send an email notification to your company's Marketplace admin (the one who created your company's Marketplace account). Your company's Marketplace admin will then be able to add you to the company. If the company name you'd like to use is available, click the *Register Your Company* button to move on to the next step. 

![Figure 9.5: Creating a Company](../../images/marketplace-creating-new-company.png)

Your second step is to fill out your company's information. The public information you must provide includes a company logo, the company name, a company description, a company email address, and a homepage URL. The private information you must provide includes a company address, your company's country, region, city, postal code, and phone number. Additonal private information required for validation includes a company email address and a legal tax document. Once your company's Marketplace registration has been approved, you be your company's Marketplace admin! This means that you'll be responsible for handling Marketplace users' requests to join your company. Don't worry, you don't have to be stuck with this responsibility. Once you've added other users to your company, you can promote some of them to be company Marketplace admins too.

## Finding Apps

There are several ways to search for and find apps you are interested in.

1. Browsing Categories. Click on a category (for example, *Communication* or *Productivity*) to see a list of interesting apps in that category. Upon clicking a category, you are presented with a list of featured apps for that category, as well as a canonical listing of all apps. Also, on the right, are lists of the Most Viewed apps within that category.

![Figure 9.6: Browsing Categories](../../images/marketplace-browsing-categories.png)
 
2. Searching. To search for an app, type in search criteria in the search box under the navigation menu on the left, and click *Search*. Apps matching the specified search criteria are displayed.

![Figure 9.7: Marketplace Search Box](../../images/marketplace-search-box.png)

### Versions

Apps are often updated to include new features or fix bugs. Each time an app is updated, its version number is changed. The version number is specified by the app developer, and often follows established norms, such as 1.0 &rarr; 1.1 &rarr; 2.0, or 1.0.1 &rarr; 1.0.2 &rarr; 1.2.0 and so on. Generally, the higher the numbers, the younger the version.
 
When viewing an app's details, the click on the *Version History* tab to see a list of versions of the app. In some cases, not all historical versions of apps are available, depending on the app. Usually you will want to download and install the latest available app for the version of Liferay you are using (See Compatibility below).
 
### Compatibility

Some apps are written to work across a wide range of Liferay Platform releases. Others are dependent on a specific Liferay Platform release (or a handful of such releases). When viewing individual apps, each version of the app that is available also describes the range of Liferay Platform versions the app is compatible with. Make sure to choose a version of the app that is compatible with your Liferay Platform release.

![Figure 9.7: Marketplace App Version History](../../images/marketplace-app-version-history.png)

To check if an app is compatible with your version of Liferay, click on the App and then click on the *Version History* tab. The Version History tab displays not only the list of versions of the app but also the app's supported framework versions and the dates of each version of the app. The supported framework version of the app tells you whether or not the app is compatible with your version of Liferay.

## Downloading and Installing Apps
 
Once you've found an app you wish to download and use, click on the name of the app to display its detailed information screen.

![Figure 9.8: Detailed App Information](../../images/marketplace-app-information.png)

On this screen, there are a number of items to assist in learning more about the app. You can find the primary information about the app on the left side of the screen. In the center display, you see a set of screenshots along with a description of the app. On the left, below the icon for the app, is some basic information about the app.

* Author: The creator of the app
* Rating: The average rating of the app on a scale from zero to five stars. The number of ratings is also shown.
* Latest Version: The latest released version of this app
* Supported By: Who to contact if you need support for this app
* Users: The total number of users of the app
* Weekly Installs: The average number of installations per week
* Developer Profile: A link to the app developer's `liferay.com` profile page
* Developer Website: A link to the developer's own website
* Purchase: The button to click on to purchase the app. You must purchase an app before you can download it.

In the lower section, you will find Reviews and Version History tabs for this app. Check here to find out what other people are saying about this app. In addition, on a separate tab, you will find the history of versions for this app, where you can download other versions (for example, if you are using an older version of the Liferay Platform, you may need to download a specific version of this app that is compatible with the version of the Liferay Platform you are using).
 
![Figure 9.9: Detailed App Information](../../images/marketplace-app-version-history-and-reviews.png)

### Downloading and Installing

You've chosen an app, read the reviews, and want to download and use the app! There are two ways to install the app. Ultimately, both methods result in the same outcome: the app you've chosen is installed onto your local running Liferay instance.
 
### Installing through the Control Panel

The easiest way to install an app is to do so from your Liferay control panel. This requires that you have already installed Liferay on your local machine, and that you can log in as an administrator. Once you are logged in as an administrator, click the *Go to* menu on the Dockbar and choose *Control Panel*.

![Figure 9.10: Marketplace from the Control Panel](../../images/marketplace-control-panel-entries.png)
 
Click on either the *Store* or the *Purchased* link in the Marketplace category at the upper-left. Before you can access Marketplace via the control panel, you need to associate your `liferay.com` login credentials with your local administrator account. Enter your `liferay.com` email address and password so that your Liferay installation can connect to the `liferay.com` Marketplace.

![Figure 9.11: Marketplace Login Screen](../../images/marketplace-login.png)
 
**VERY IMPORTANT**: The local admin user you associate with your `liferay.com` account will be THE ONLY USER who will be able to access and install apps from the Marketplace. Be sure you are logged into your local Liferay installation using the account you wish to designate the Marketplace Administrator. Once this linkage is established, there is no way to undo this, short of re-installing Liferay.
 
Once you've successfully linked the accounts, you will be presented with the same Marketplace screens as you would have if you were directly accessing the Marketplace. You will be able to browse, search, and install directly from the Marketplace. Click on the *Store* link under the Marketplace heading in the control panel to browse the apps available from the `liferay.com` Marketplace. Browse to the app you wish to install, click the *Purchase* button, and then the *Buy* button on the next screen. The app will be downloaded and deployed to your local Liferay installation.
 
All apps that you've bought are listed on the *Purchased* page of the Marketplace control panel. Clicking on the *Purchased* link will show you a list of those apps which you have downloaded in the past, including apps you may have purchased/downloaded while using other Liferay installations.

![Figure 9.12: Purchased Apps](../../images/marketplace-purchased-apps-control-panel.png)
 
The apps which you downloaded and installed on the currently running instance of Liferay are listed as Installed. Apps which you have previously downloaded or purchased on other Liferay instances that are incompatible with the current one are listed as Not Compatible. You need to re-download/re-install the appropriate version of these apps if you wish to use them on your running instance of Liferay.
 
### Downloading through liferay.com

The second way to install an app is to download it first, then in a separate step, deploy it to your running Liferay instance. This is especially useful in situations where you do not wish to deploy the app directly to your production environment, or in cases where the target Liferay instance that is to receive the app is behind a corporate firewall or otherwise does not have direct access to the Marketplace.
 
In this case, using your browser, you will find the app on `liferay.com/marketplace`. Once found, click on the *Purchase* button when viewing the individual app. This will cause the app to be placed in your *Purchased* list on your personal Home page. Navigate to your Home page, click on *App Manager* and visit the *Purchased* tab. Each app is listed. Find the app that you just purchased and click *Downloads*. You'll find a list of app versions and Liferay versions. Choose the version of the app that you want, making sure the that Liferay version corresponds to the version of the Liferay installation into which you'd like to install the app. Click *Download App* and the app is downloaded to your local machine in the same way that any other file would be downloaded. This file can then be hot-deployed to Liferay by copying it to Liferay's hot deploy directory.

## Creating and Uploading Apps
 
Creating apps for the Liferay Marketplace is very easy and intuitive. To find out more information about creating your own Liferay apps, visit the Liferay Marketplace Developer Guide and get started creating apps today!

## Plugin Management

One of the primary ways of extending the functionality of Liferay Portal is by the use of plugins. *Plugin* is an umbrella term for installable portlet, theme, layout template, hook, Ext, and web module Java EE `.war` files. Though Liferay comes bundled with a number of functional portlets, themes, layout templates, hooks, and web modules, plugins provide a means of extending Liferay to be able to do almost anything.

### Portlets

Portlets are small web applications that run in a portion of a web page. The heart of any portal implementation is its portlets, because all of the functionality of a portal resides in its portlets. Liferay's core is a portlet container. The container's job is to manage the portal's pages and to aggregate the set of portlets that are to appear on any particular page. This means that the core doesn't contain application code. Instead, all of the features and functionality of your portal application must reside in its portlets.

---

![tip](../../images/tip.png) **Tip:** Liferay 4.4.2 and below support the Portlet 1.0 standard: JSR-168. Liferay 5.0 and above support the Portlet 2.0 standard: JSR-286. You cannot run Portlet 2.0 portlets in Liferay 4.4.2, but because the Portlet 2.0 standard is backwards-compatible, portlets written to the 1.0 standard will run in Liferay 5.x and above.

---

Portlet applications, like servlet applications, have become a Java standard which various portal server vendors have implemented. The JSR-168 standard defines the portlet 1.0 specification, and the JSR-286 standard defines the portlet 2.0 specification. A Java standard portlet should be deployable on any portlet container which supports the standard. Portlets are placed on the page in a certain order by the end user and are served up dynamically by the portal server. This means that certain “givens” that apply to servlet-based projects, such as control over URLs or access to the `HttpServletRequest` object, don’t apply in portlet projects, because the portal server generates these objects dynamically. 

Portal applications come generally in two flavors: 1) portlets can be written to provide small amounts of functionality and then aggregated by the portal server into a larger application, or 2) whole applications can be written to reside in only one or a few portlet windows. The choice is up to those designing the application. The developer only has to worry about what happens inside of the portlet itself; the portal server handles building out the page as it is presented to the user.

Most developers nowadays like to use certain frameworks to develop their applications, because those frameworks provide both functionality and structure to a project. For example, Struts enforces the Model-View-Controller design pattern and provides lots of functionality, such as custom tags and form validation, that make it easier for a developer to implement certain standard features. With Liferay, developers are free to use all of the leading frameworks in the Java EE space, including Struts, Spring MVC, and Java Server Faces. This allows developers familiar with those frameworks to more easily implement portlets, and also facilitates the quick porting of an application using those frameworks over to a portlet implementation.

Additionally, Liferay allows for the consuming of PHP and Ruby applications as “portlets,” so you do not need to be a Java developer in order to take advantage of Liferay's built-in features (such as user management, sites, organizations, page building and content management). You can also use scripting languages such as Groovy if you wish. You can use the Plugins SDK to deploy your PHP or Ruby application as a portlet, and it will run seamlessly inside of Liferay. We have plenty of examples of this; to see them, check out the Plugins SDK from Liferay's public code repository.

Does your organization make use of any Enterprise Planning (ERP) software that exposes its data via web services? You could write a portlet plugin for Liferay that can consume that data and display it as part of a dashboard page for your users. Do you subscribe to a stock service? You could pull stock quotes from that service and display them on your page, instead of using Liferay's built-in Stocks portlet. Do you have a need to combine the functionality of two or more servlet-based applications on one page? You could make them into portlet plugins and have Liferay display them in whatever layout you want. Do you have existing Struts, Spring MVC, or JSF applications that you want to integrate with your portal? It is a straightforward task to migrate these applications into Liferay, and then they can take advantage of the layout, security, and administration infrastructure that Liferay provides.

### Themes

![Figure 9.14: Envision Theme from Liferay's Theme Repository](../../images/marketplace-envision-theme.png)

Themes are hot deployable plugins which can completely transform the look and feel of the portal. Most organizations have their own look and feel standards which go across all of the web sites and web applications in the infrastructure. Liferay makes it possible for a site designer to create a theme plugin which can be installed, allowing for the complete transformation of the portal to whatever look and feel is needed. There are lots of available theme plugins on Liferay's web site, and more are being added every day. This makes it easier for those who wish to develop themes for Liferay, as you can now choose a theme which most closely resembles what you want to do and then customize it. This is much easier than starting a theme from scratch. You can learn more about theme development in [*Liferay in Action*](http://manning.com/sezov).

![Figure 9.15: Murali Theme from Liferay's Theme Repository](../../images/marketplace-murali-theme.png)

### Layout Templates

Layout Templates are ways of choosing how your portlets will be arranged on a page. They make up the body of your page, the large area into which you can drag and drop portlets. Liferay Portal comes with several built-in layout templates, but if you have a complex page layout (especially for your home page), you may wish to create a custom layout template of your own. This is covered in [*Liferay in Action*](http://manning.com/sezov).

### Hook Plugins

Hook plugins were introduced with Liferay 5.2. As the name implies, they allow “hooking” into Liferay's core functionality. This means that they enable developers to override or replace functionality that is in the core of the system. You can hook into the eventing system, model listeners, and portal properties. You can also override Liferay's core JSPs with your own. Hooks are very powerful and have been designed to replace most of the reasons for using the extension environment with something that is easier to use and hot deployable.

### Web Plugins

Web plugins are regular Java EE web modules that are designed to work with Liferay. Liferay supports integration with various Enterprise Service Bus (ESB) implementations, as well as Single Sign-On implementations, workflow engines, and so on. These are implemented as web modules that are used by Liferay portlets to provide functionality.

### Installing Plugins from Repositories

Liferay Portal has a section of the control panel called Plugins Installation, which you can finder beneath the Server heading. This section not only allows you to see what plugins are installed in your portal, but also it enables you to run the search indexer on those portlets that support it and install new portlets.

Use the dockbar's *Go to* menu to select *Control Panel*. Under the Server heading, select *Plugins Installation*. You should now see the page which allows you to configure and install portlets.

The default view of the Plugins Installation page shows which plugins are already installed on the system and whether whether or not they are active. The Portlet Plugins tab allows you reindex certain portlets to improve their searchability. The Theme and Layout Template Plugins tabs display which portal roles can access them.

![Figure 9.16: Plugins Installation Portlet Tab Default View](../../images/marketplace-plugins-installation-portlet-tab.png)

![Figure 9.17: Plugins Installation Theme Tab Default View](../../images/marketplace-plugins-installation-theme-tab.png)

If you would like to see what plugins are available, you can do so by clicking the *Install More [Plugin Type]* button, where [Plugin Type] changes based on which tab you are viewing. Please note that the machine upon which Liferay is running must have access to the Internet in order to be able to read the Official and Community repositories. If the machine does not have Internet access, you will need to download the plugins from the site and install them manually. We will discuss how to do this later in this chapter.

It's easy to navigate from the initial page of the Plugin Installer to different pages since the plugins are listed alphabetically. You can also change the number of items per page and navigate to a specific page if you know where a particular plugin appears in the list. This is a standard feature of Liferay, and you will see it in most of Liferay's portlets.

![Figure 9.18: Installing Plugins](../../images/marketplace-plugins-installer.png)

After you click the *Install More [Plugin Type]* button, a new view appears. This view has multiple tabs, and by default, displays the *Portlet Plugins* tab. Note that the list displayed is a list of all of the plugins that are available across all of the repositories to which the server is subscribed. Above this is a search mechanism which allows you to search for plugins by their name, by whether or not they are installed, by tag, or by which repository they belong to. To install a plugin, choose the plugin by clicking on its name. For example, if you want to use online web forms on your web site, you might want to install the Web Form portlet. This portlet provides a handy interface which allows you to create forms for users to fill out. You can specify an address to which the results will be emailed.

Find the Web Form Portlet in the list by searching for it or browsing to it. Once you have found it, click on its name. Another page will be displayed which describes the portlet plugin in more detail. Below the description is an *Install* button. Click this button to install your plugin.

![Figure 9.19: Installing the Web Form Portlet](../../images/marketplace-installing-web-form-portlet.png)

Once you click *Install*, your chosen plugin will automatically download and be installed on your instance of Liferay. If you have the Liferay console open, you can view the deployment as it happens. When it is finished, you should be able to go back to the Add Application window and add your new plugin to a page in your portal.

The same procedure is used for installing new Liferay themes, layout templates, hooks, and web modules. Instead of the *Portlet Plugins* tab, you would use the appropriate tab for the type of plugin you wish to install to view the list of plugins of that type. For themes, convenient thumbnails (plus a larger version when you click on the details of a particular theme) are shown in the list.

After clicking on the *Install* button for a theme, the theme becomes available on the *Look and Feel* tab of any page.

### Installing Plugins Manually

Installing plugins manually is almost as easy as installing plugins via the Plugin Installer. There are several scenarios in which you would need to install plugins manually rather than from Liferay's repositories:

-   Your server is firewalled without access to the Internet. This makes it impossible for your instance of Liferay to connect to the plugin repositories.

-   You are installing portlets which you have either purchased from a vendor, downloaded separately, or developed yourself.

-   For security reasons, you do not want to allow portal administrators to install plugins from the Internet before they are evaluated.

You can still use the control panel to install plugins that are not available from the online repositories. This is by far the easiest way to install plugins.

If your server is firewalled, you will not see any plugins displayed in the Portlet Plugins or Theme Plugins tabs. Instead, you will need to click the *Upload File* tab. This gives you a simple interface for uploading a `.war` file containing a plugin to your Liferay Portal.

![Figure 9.20: Installing a Plugin Manually](../../images/marketplace-plugin-installer-upload-file.png)

Click the *Browse* button and navigate your file system to find the portlet or theme `.war` you have downloaded. The other field on the page is optional: you can specify your own context for deployment. If you leave this field blank, the default context defined in the plugin (or the `.war` file name itself) will be used.

That's all the information the Plugin Installer needs in order to deploy your portlet, theme, layout template, hook, or web module. Click the *Install* button, and your plugin will be uploaded to the server and deployed. If it is a portlet, you should see it in the *Add Content* window. If it is a theme, it will be available on the *Look and Feel* tab in the page definition.

If you do not wish to use the Update Manager or Plugin Installer to deploy plugins, you can also deploy them at the operating system level. The first time Liferay starts, it creates a *hot deploy* folder which is, by default, created inside the Liferay Home folder. This folder generally resides one directory up from where your application server is installed, though it may be elsewhere depending on which application server you are running. To find out where the Liferay Home folder is for your application server, please see the section on your server in chapter 1. The first time Liferay is launched, it will create a folder structure in Liferay Home to house various configuration and administrative data. One of the folders it creates is called *deploy*. If you copy a portlet or theme plugin into this folder, Liferay will deploy it and make it available for use just as though you'd installed it via the Plugin Installer in the control panel. In fact, this is what the Plugin Installer is doing behind the scenes.

You can change the defaults for this directory structure so that it is stored anywhere you like by modifying the appropriate properties in your `portal-ext.properties` file. Please see the above section on the `portal-ext.properties` file for more information.

To have Liferay hot deploy a portlet or theme plugin, copy the plugin into your hot deploy folder, which by default is in `[Liferay Home]/deploy`. If you are watching the Liferay console, you should see messages like the following:

	16:11:47,616 INFO [PortletAutoDeployListener:71] Copying portlets for
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/deploy/weather-portlet-6.0.4.1.war
	
	Expanding:
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/deploy/weather-portlet-6.0.4.1.war
	into
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/temp/20100729161147694
	
	Copying 1 file to
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/temp/20100729161147694/WEB-INF
	
	Copying 1 file to
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/temp/20100729161147694/WEB-INF/classes
	
	Copying 1 file to
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/temp/20100729161147694/WEB-INF/classes
	
	Copying 1 file to
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/temp/20100729161147694/META-INF
	
	Copying 37 files to
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/webapps/weather-portlet
	
	Copying 1 file to
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/webapps/weather-portlet
	
	Deleting directory
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/tomcat-6.0.26/temp/20100729161147694
	
	16:11:48,072 INFO [PortletAutoDeployListener:81] Portlets for
	/Users/stephenkostas/java/liferay/bundles/liferay-portal-6.0.4/deploy/weather-portlet-6.0.4.1.war
	copied successfully. Deployment will start in a few seconds.
	
	Jul 29, 2010 4:11:50 PM org.apache.catalina.startup.HostConfig
	deployDirectory
	
	INFO: Deploying web application directory weather-portlet
	
	16:11:50,585 INFO [PortletHotDeployListener:222] Registering portlets
	for weather-portlet
	
	16:11:50,784 INFO [PortletHotDeployListener:371] 1 portlet for
	weather-portlet is available for use

The *available for use* message means that your plugin was installed correctly and is available for use in the portal.

### Plugin Troubleshooting

Sometimes plugins fail to install. There can be different reasons for installation failure based on several factors, including

-   Liferay configuration

-   The container upon which Liferay is running

-   Changing the configuration options in multiple places

-   How Liferay is being launched

You can often tell whether or not you have a plugin deployment problem by looking at the Liferay server console. If the hot deploy listener recognizes the plugin, you'll see a *plugin copied successfully* message. If this message is not followed up by an *available for use* message then you have an issue with your plugin deployment configuration, probably due to one of the factors listed above.

Let's take a look at each of these factors.

#### Liferay Configuration Issues

---

![tip](../../images/tip.png) **Tip:** This applies to Liferay versions prior to version 4.3.5. Liferay versions above 4.3.5 are able to auto detect the type of server it is running on, which makes things a lot easier. If you are running a newer version of Liferay, you can skip this section. If you are upgrading from one of these versions, continue reading.

---

Liferay by default comes as a bundle or as a `.war` file. Though every effort has been made to make the `.war` file as generic as possible, sometimes the default settings are inappropriate for the container upon which Liferay is running. Most of these problems were resolved in Liferay 4.3.5 with the addition of code that allows Liferay to determine which application server it is running on and adjust the way it deploys plugins as a result. If you have upgraded from one of these older versions, you may still have settings in your `portal.ext.properties` file that are no longer needed. One of these settings is the manual override of the default value of `auto.deploy.dest.dir`.

In versions of Liferay prior to 4.3.5, there is a property called `auto.deploy.dest.dir` that defines the folder where plugins are deployed after the hot deploy utilities have finished preparing them. This folder maps to a folder that the container defines as an auto-deploy or a hot deploy folder. By default in older versions of Liferay, this property is set to `../webapps`. This default value works for Tomcat containers (if Tomcat has been launched from its `bin` folder), but will not work for other containers that define their hot deploy folders in a different place. In newer versions of Liferay, this value is automatically set to the default for the application server upon which Liferay is running.

For example, Glassfish defines the hot deploy folder as a folder called `autodeploy` inside of the domain folder in which your server is running. By default, this is in `<Glassfish Home>/domains/domain1/autodeploy`. JBoss defines the hot deploy folder as a root folder inside of the particular server configuration you are using. By default, this is in `<JBoss Home>/server/default/deploy`. WebLogic defines this folder inside of the domain directory. By default, this is in `<Bea Home>/user_projects/domains/<domain name>/autodeploy`.

The best thing to do when upgrading to newer versions of Liferay Portal is to remove this property altogether. It is not needed, as the autodetection of the container handles the hot deploy location. If, for whatever reason, you need to customize the location of the hot deploy folder, follow the instructions below.

You will first need to determine where the hot deploy folder is for the container you are running. Consult your product documentation for this. Once you have this value, there are two places in which you can set it: in the `portal-ext.properties` file and in the Plugin Installer portlet.

To change this setting in the `portal-ext.properties` file, browse to where Liferay was deployed in your application server. Inside of this folder should be a `WEB-INF/classes` folder. Here you will find the `portal-ext.properties` file. Open this file in a text editor and look for the property `auto.deploy.dest.dir`. If it does not appear in the file, you can add it. The safest way to set this property, as we will see later, is to define the property using an absolute path from the root of your file system to your application server's hot deploy folder. For example, if you are using Glassfish, and you have the server installed in `/java/glassfish`, your `auto.deploy.dest.dir` property would look like the following:

	auto.deploy.dest.dir=/java/glassfish/domains/domain1/autodeploy

Remember, if you are on a Windows system, use forward slashes instead of back slashes, like so:

	auto.deploy.dest.dir=C:/java/glassfish/domains/domain1/autodeploy

Save the file and then restart your container. Now plugins should install correctly.

Instead of changing the hot deploy destination directory in your `portal-ext.properties` file, you can do it via the Plugin Installer. To change change the setting this way, navigate to the Plugins Installation page of the control panel, click the *Install More [Plugins]* button. This will bring you to the Plugin Installer page. Next, click on the *Configuration* tab of the Plugin Installer page. There are a number of settings that you can change on this tab, including the default folders for hot deploy, where Liferay should look for plugin repositories, and so on.

![Figure 9.21: Changing the Hot Deploy Destination Directory](../../images/marketplace-plugin-installer-configuration.png)

The setting to change is the field labeled *Destination Directory*. Change this to the full path to your container's auto deploy folder from the root of your file system. When you are finished, click the *Save* button at the bottom of the form. The setting will now take effect without your having to restart your container. Note that the setting in the control panel overrides the setting in the properties file.

If you are having hot deploy trouble in Liferay versions 4.3.5 and greater, it is possible that the administrator of your application server has changed the default folder for auto deploy in your application server. In this case, you would want to set `auto.deploy.dest.dir` to the customized folder location as you would with older versions of Liferay. In Liferay 4.3.5 and greater, this setting still exists, but is blank. Add the property to your `portal-ext.properties` file and set its value to the fully qualified path to the auto deploy folder configured in your application server.

#### Deploy Issues for Specific Containers

Some containers, such as WebSphere®, don't have a hot deploy feature. Unfortunately, these containers do not work with Liferay's hot deploy system. But this does not mean that you cannot install plugins on these containers. You can deploy plugins manually using the application server's deployment tools. Liferay is able to pick up the portlet plugins once they get deployed to the container manually, especially if you add it to the same Enterprise Application project that was created for Liferay.

When Liferay hot deploys portlet and theme `.war` files, it sometimes makes modifications to those files right before deployment. In order to successfully deploy plugins using an application server vendor's tools, you will want to run your plugins through this process before you attempt to deploy them.

Navigate back to the *Configuration* tab of the Plugin Installer. Enter the location that you would like plugin `.war` files to be copied to after they are processed by Liferay's plugin installer process into the *Destination Directory* field. You will use this as a staging directory for your plugins before you install them manually with your server's deployment tools. When you are finished, click *Save*.

Now you can deploy plugins using the Plugin Installer portlet or by dropping `.war` files into your auto deploy directory. Liferay will pick up the files, modify them, and then copy the result into the destination directory you have configured. You may then deploy them from here to your application server.

##### Example: WebSphere® Application Server

1.  If you don't have one already, create a `portal-ext.properties` file in the Liferay Home folder of your Liferay installation. Add the following directive to it:

	auto.deploy.dest.dir=${liferay.home}/websphere-deploy

2.  Create a folder called `websphere-deploy` inside your `$LIFERAY_HOME` folder. This is the folder where the Lucene index, Jackrabbit config, and deploy folders are.

3.  Make sure the `web.xml` file inside the plugin you want to install has the following context parameter in it:

	<context-param\>
	
	<param-name\>com.ibm.websphere.portletcontainer.PortletDeploymentEnabled</param-name\>
	
	<param-value\>false</param-value\>
	
	</context-param\>

Liferay versions 5.2.2 and higher will automatically inject this into the `web.xml` file on WebSphere containers.

4.  The WebSphere deploy occurs in two steps. You will first use Liferay's tools to “pre-deploy” the file, and then use WebSphere's tools to do the actual deployment. This is because Liferay makes deployment-time modifications to the plugins right before they are actually deployed to the application server. For other application servers, this can usually be done in one step, because Liferay can make the modifications and then copy the resulting `.war` file into an autodeploy folder to have it actually deployed. Because WebSphere does not have an autodeploy feature, we need to separate these two steps.

5.  Deploy your .war file using Liferay's Plugin Installer or by copying it into `$LIFERAY_HOME/deploy`. Liferay will make its modifications and because we changed the `auto.deploy.dest.dir` in the first step, it will copy the resulting `.war` file into `$LIFERAY_HOME/websphere-deploy`. You will see a *copied successfully* message in the log.

6.  Use WebSphere's tools to deploy the `.war` file. Make the context root for the `.war` file equal to the file name (i.e., `/my-first-portlet`). Once the `.war` file is deployed, save it to the master configuration.

7.  Go back to the *Applications &rarr; Enterprise Applications* screen in the WebSphere Admin Console. You will see that your portlet is deployed, but not yet started. Start it.

8.  Liferay will immediately recognize that the portlet has been deployed and register it. The portlet will be automatically started and registered upon subsequent restarts of WebSphere.

Experienced WebSphere system administrators can further automate this by writing a script which watches the `websphere-deploy` directory and uses `wsadmin` commands to then deploy plugins automatically.

#### Changing the Configuration Options in Multiple Places

Sometimes, especially during development when several people have administrative access to the server at the same time, the auto deploy folder location may inadvertently be customized in both the `portal-ext.properties` file and in the control panel. If this happens, the value in the control panel takes precedence over the value in the properties file. If you go into the control panel and change the value to the correct setting, plugin deployment will start working again.

### Creating Your Own Plugin Repository

As your enterprise builds its own library of portlets for internal use, you can create your own plugin repository to make it easy to install and upgrade portlets. This will allow different departments who may be running different instances of Liferay to share portlets and install them as needed. If you are a software development house, you may wish to create a plugin repository for your own products. Liferay makes it easy for you to create your own plugin repository and make it available to others.

You can create your plugin repository in two ways:

1.  Use the Software Catalog in the control panel to create the repository by using its graphical interface and an HTTP server.

2.  Create an XML file using the Liferay Plugin Repository DTD (`http://www.liferay.com/dtd/liferay-plugin-repository_6_0_0.dtd`) and an HTTP server.

Both methods have their benefits. The first method allows users to upload their plugins to an HTTP server to which they have access. They can then register their plugins with the repository by adding a link to it via the control panel's graphical user interface. Liferay will then generate the XML necessary to connect the repository to a control panel running on another instance of Liferay. This XML file can then be placed on an HTTP server, and the URL to it can be added to the Plugin Installer, making the portlets in this repository available to the server running Liferay.

The second method does not require an instance of Liferay to be running. You can upload plugins to an HTTP server of your choice, and then create an XML file called `liferay-plugin-repository.xml` manually. If you make this file available on an HTTP server (it can be the same one which is storing the plugins or a different one), you can connect the repository to a Plugin Installer in the control panel running on an instance of Liferay.

We will first look at creating a plugin repository using the Software Catalog in the control panel.

#### The Software Catalog

You will want to use the Software Catalog if you will have multiple users submitting portlets into the repository, and if you don't want to worry about creating the `liferay-plugin-repository.xml` file yourself.

![Figure 9.22: The Software Catalog with Nothing Installed](../../images/marketplace-software-catalog.png)

Each site in your portal can have an instance of the Software Catalog. The control panel presents you with the software catalog for whichever site you are working on. This means that different sites can have different software repositories, so you can host several software repositories on the same instance of Liferay if you wish—they just have to be in different sites. Choose the site that will host the plugin repository and go to the control panel. You will see at the top of the screen a message that says “Content for [Site],” where [Site] is the site you were on when you selected the control panel from the dockbar. If you want to administer the software catalog for a different site, you can select it from the selection box.

![Figure 9.23: Populated Software Catalog from liferay.com](../../images/marketplace-populated-software-catalog.png)

The Software Catalog has several tabs. The first tab is labeled Products. The default view of the portlet, when populated with software, displays what plugins are available for install or download. This can be seen in the version on Liferay's home page.

We will use an example site in order to better illustrate how to use the Software Catalog portlet. Assume you, as the portal administrator, have created a site called *Old Computers*. This site will be for users to collaborate on setting up and using old computers with obsolete hardware and operating systems. Users who participate in the site will eventually get upgraded to a more privileged status and get their own blog page. To implement this, you have created a My Summary portlet which displays the user's name, picture, and description from his or her user profile. Because this portlet is generic enough that it could be useful to anyone using Liferay, you have decided to make it available in your own software catalog.

The first step in adding a plugin to your software repository is to add a license for your product. A license communicates to users the terms upon which you are allowing them to download and use your software. Click the *Licenses* tab and then click the *Add License* button that appears. You will then see a form which allows you to enter the title of your license, a URL pointing to the actual license document, and check boxes denoting whether the license is open source, active, or recommended.

When you have finished filling out the form, click the *Save* button. Your license will be saved. Once you have at least one license in the system, you can begin adding software products to your software catalog. Click the *Products* tab, and then click the *Add Product* button.

Your next step will be to create the product record in the software catalog. This will register the product in the software catalog and allow you to start adding versions of your software for users to download and/or install directly from their instances of Liferay. You will first need to put the `.war` file containing your software on a web server that is accessible without authentication to the users who will be installing your software. In the example above, the *Old Computers* site is on the Internet, so you would place the file on a web server that is accessible to anyone on the Internet. If you are creating a software catalog for an internal Intranet, you would place the file on a web server that is available to anyone inside of your organization's firewall.

To create the product record in the Software Catalog portlet, click the *Products* tab, and then click the *Add Product* button. Fill out the form with information about your product.

![Figure 9.24: Adding a Product to the Software Catalog](../../images/marketplace-adding-product-to-software-catalog.png)

**Name:** The name of your software product.

**Type:** Select whether this is a portlet, theme, layout template, hook, or web plugin.

**Licenses:** Select the license(s) under which you are releasing this software.

**Author:** Enter the name of the author of the software.

**Page URL:** If the software has a home page, enter its url here.

**Tags:** Enter any tags you would like added to this software.

**Short Description:** Enter a short description. This will be displayed in the summary table of your software catalog.

**Long Description:** Enter a longer description. This will be displayed on the details page for this software product.

**Permissions:** Click the *Configure* link to set permissions for this software product.

**Group ID:** Enter a group ID. A group ID is a name space which usually identifies the company or organization that made the software. For our example, we will use *old-computers*.

**Artifact ID:** Enter an Artifact ID. The artifact ID is a unique name within the name space for your product. For our example, we will use *my-summary-portlet*.

**Screenshot:** Click the *Add Screenshot* button to add a screen shot of your product for users to view.

When you have finished filling out the form, click the *Save* button. You will be brought back to the product summary page, and you will see that your product has been added to the repository.

Notice that in the version column, *N/A* is being displayed. This is because there are not yet any released *versions* of your product. To make your product downloadable, you need to create a version of your product and point it to the file you uploaded to your HTTP server earlier.

Before you do that, however, you need to add a *Framework Version* to your software catalog. A Framework version denotes what version of Liferay your plugin is designed for and works on. You cannot add a version of your product without linking it to a version of the framework for which it is designed.

Why is this so important? Because as Liferay gains more and more features, you may wish to take advantage of those features in future versions of your product, while still keeping older versions of your product available for those who are using older versions of Liferay. This is perfectly illustrated in the example My Summary portlet we are using. Liferay had a My Summary portlet of its own, which does exactly what we have described here. This portlet was added to the suite of portlets which Liferay provides in the Social Networking plugin. This plugin makes use of the many social networking features which have been added to Liferay. So rather than just displaying a summary of your information, the Social Networking portlet adds features such as status updates, a “wall” for each user in his or her profile that other users can “write” on, the ability to become “friends” with other users—thereby granting them access to their profiles—and more.

None of this would work in older versions of Liferay, because the core engine that enables developers to create features like this is not there. So in this case, you would want to keep the older My Summary portlet available for users who have not yet upgraded, and make the newer social portlets available to those using latest version of Liferay. This is what *Framework Versions* does for you. If you connect to Liferay's software repositories with an old version of Liferay Portal, you will see the My Summary portlet. If you connect to Liferay's software repositories with new version of Liferay, you will see the social portlets.

So click the *Framework Versions* tab and then click the *Add Framework Version* button.

Give the framework a name, a URL, and leave the *Active* check box checked. For our example, we have entered 6.0.3 for the name, because our portlet should work on that version and higher, and [http://www.liferay.com](http://www.liferay.com) for the URL. Click *Save*.

![Figure 9.25: Adding a Product Version to the Software Catalog](../../images/marketplace-adding-product-version-software-catalog.png)

Now go back to the *Products* tab and click on your product. You will notice that a message is displayed stating that the product does not have any released versions. Click the *Add Product Version* button.

**Version Name:** Enter the version of your product.

**Change Log:** Enter some comments regarding what changed between this version and any previous versions.

**Supported Framework Versions:** Select the framework version for which your software product is intended. Enter a `+` at the end of the version number if you want to specify a version plus any future versions.

**Download Page URL:** If your product has a descriptive web page, enter its URL here.

**Direct Download URL (Recommended):** Enter a direct download link to your software product here. The Plugin Installer portlet will follow this link in order to download your software product.

**Include Artifact in Repository:** To enable others to use the Plugin Installer portlet to connect to your repository and download your plugin, select *yes* here.

When you are finished filling out the form, click the *Save* button. Your product version will be saved, and your product will now be available in the software repository.

##### Generating The Software Catalog

The Software Catalog works by generating an XML document which the Plugin Installer reads. Using the data from this XML document, the Plugin Installer knows where it can download the plugins from, what version of Liferay the plugins are designed for, and all other data about the plugins that have been entered into the Software Catalog portlet.

In order to get your Software Catalog to generate this XML data, you will need to access a particular URL. If you have created a friendly URL for your site (for example, the default site, which is called *guest*, has a friendly URL of `/guest` already configured for it), you can use the friendly URL. If not, you will first need to know the Group ID of the site in which your Software Catalog portlet resides. You can do this by accessing the Manage Pages interface and looking at the URLs for any of the pages. The URL will look something like this: `http://localhost:8080/web/10148/1`.

Obviously, it is much easier if you are using Friendly URLs, which we highly recommend.

Next, go to your browser and go to the following URL:

[http://<server name\>:<port number\>/software\_catalog?<Friendly URL name or Group ID\>](http://<server name\>:<port number\>/software\_catalog?<Friendly URL name or Group ID\>)

For example, if you are on the same machine as your Liferay instance, and that instance is running on port 8080, and your group ID from the database is 10148, you would use the following URL:

[http://localhost:8080/software\_catalog?10148](http://localhost:8080/software\_catalog?10148)

If you have also created a friendly URL called *old-computers* for this site, you would use the following URL:

[http://localhost:8080/software\_catalog?old-computers](http://localhost:8080/software\_catalog?old-computers)

If you have configured everything properly, an XML document should be returned:

	<?xml version="1.0" encoding="UTF-8"?\>
	
	<plugin-repository\>
	
	<settings/\>
	
	<plugin-package\>
	
	<name\>My Summary</name\>
	
	<module-id\>old-computers/my-summary-portlet/1.0/war</module-id\>
	
	<modified-date\>Thu, 23 Apr 2009 20:40:16 +0000</modified-date\>
	
	<types\>
	
	<type\>portlet</type\>
	
	</types\>
	
	<tags\>
	
	<tag\>social</tag\>
	
	<tag\>profile</tag\>
	
	</tags\>
	
	<short-description\>My Summary</short-description\>
	
	<long-description\>My Summary</long-description\>
	
	<change-log\>Initial Version</change-log\>
	
	<download-url\>[http://www.liferay.com/portlets/my-summary-portlet-6.0.4.war](http://www.liferay.com/portlets/my-summary-portlet-5.2.2.war)
	
	</download-url\>
	
	<author\>Rich Sezov</author\>
	
	<screenshots/\>
	
	<licenses\>
	
	<license osi-approved="true"\>MIT License</license\>
	
	</licenses\>
	
	<liferay-versions/\>
	
	</plugin-package\>
	
	</plugin-repository\>

You can now give the URL to your software repository out on your web site, and other administrators of Liferay can enter it into the Plugins Installation module of their Liferay control panels to connect to your repository.

If you want to serve your repository off of a static web server, you can save this document to a file called `liferay-plugin-package.xml` and put this file on your HTTP server. You can then give out the URL to the directory which holds this file on your web site, and anyone with an instance of Liferay will be able to point their Plugin Installer portlets to it.

##### Benefits of the Software Catalog

As you can see, the Software Catalog makes it easy for you to create a repository of your software. Users of Liferay can configure their Plugin Installers to attach to your repository, and the proper versions of your software will be automatically made available to them by a single click. This is by far the easiest way for you to keep track of your software, and for your users to obtain your software.

Another benefit of the Software Catalog is that by using it, you make available to your users a standard interface for manually downloading your software. For those who prefer to manually download plugins, your Software Catalog gives them an interface to go in, find your software either by browsing or by searching, preview screen shots, and download your software—and you don't have to build any of those pages yourself. Simply configure your software in the portlet, and all of that is done for you.

How can you do this? The Software Catalog is also available as a portlet. You can add it to any page on your web site through the *Add Application* menu. You can find the portlet in the *Tools* category.

#### Manually Creating A Software Catalog

If you do not wish to use the control panel to create your software catalog, you can create it manually by manually typing out the XML file that the Software Catalog section of the control panel would normally generate. Note that if you do this, you will not be able to use the Software Catalog portlet as a graphical user interface to your software that end users can use to download your software manually: you will have to build this yourself. Keep in mind that many instances of Liferay Portal sit behind a firewall without access to the Internet. Because of this, if you are making your software available to Internet users, some of them will have to download it manually anyway, because their installations are firewalled. In this case, the Software Catalog portlet is the easiest way to provide a user interface for downloading your software.

If you still wish to use a text editor to create your software catalog, you can. To manually create a software catalog, obtain the DTD for the XML file from Liferay's source code. You will find this DTD in the *definitions* folder in the Liferay source. It is a file called `liferay-plugin-package_6_0_0.dtd`. Use this DTD with a validating XML editor (a good, free choice is jEdit with all the XML plugins) to create your software catalog manually.

#### Connecting to a Software Catalog

If there is a software catalog of plugins that you would like to point your instance of Liferay to, all you need is the URL to the catalog. Once you have the URL, go to the Plugin Installer in your control panel and click the *Configuration* tab. You will see that there are two fields in which you can enter URLs to plugin repositories: *Trusted Plugin Repositories* and *Untrusted Plugin Repositories*. Currently, the only difference between the two is to provide a visual cue for administrators as to which repositories are trusted and untrusted.

Enter the URL to the repository to which you wish to connect in one of the fields and click *Save*. The portlet will connect to the repository, and items from this repository will be shown in the list.

## Summary

In this chapter we introduced Liferay Marketplace, the portal's system for managing Liferay applications. We looked at how to browse, download, and install apps. You do this through Liferay Portal's control panel or through [liferay.com](liferay.com). Next, we covered at the Plugin Installer, which was the portal's mechanism for managing plugins in versions prior to Liferay 6.1. We also looked at different kinds of plugins, including portlets, themes, layout templates, hooks, and web plugins. We looked at how to install plugins either manually or from a repository and discussed some solutions to potential configuration issues. Finally, we showed how to create your own plugin repository using Liferay's Software Catalog. We hope this information helps you set up your portal with all the software you need to be productive.
