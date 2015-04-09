# Introduction #
Easy!Appointments is a web appointment scheduler that can be installed and run in web servers. Users will be able to reach the application through their web browsers using an active internet connection, just like visiting a normal website. The installation process is very similar to other popular web systems like WordPress and Joomla, so it is very likely that you will be familiar with the next steps. Follow this article strictly in order to complete the installation with no problems. After that, read the "Configuration" section for adjusting the system to fit your needs.
<br><br>
<hr />
<br><br>
<img src='https://dl.dropboxusercontent.com/u/27545985/easyappointments/installation-steps.png' />
<br><br>

<h1>Installation</h1>
There are 5 steps you must do during the installation process. Each step has a hint description aimed to provide more information.<br>
<ol><li><b>Make sure that your server has at least the following applications installed: Apache(v2.4), PHP(v5.3) and MySQL(v5.5.24).</b> Easy!Appointments needs these programs to run and additional <b>rewrite module</b> enabled on Apache. Most (if not all) of the web hosting companies provide these prerequisites on their linux hosting plans. If you want to install Easy!Appointments locally on your computer use one of the premade bundles available on the web (XAMPP, MAMP, WAMP), all of which are free to use.<br>
</li><li><b>Create a new database (or use an existing).</b> The database is necessary for Easy!Appointments to store the system data. Therefore your hosting plan must include at least one MySQL database. You must also get the database administration credentials because they will be needed later on.<br>
</li><li><b>Copy the "easy_appointments" source folder on your server.</b> You can rename this folder into anything you like ("easyappointments", "book" etc). E!A will take 6Mb of your server's storage space. Make sure that you mark the Easy!Appointments folder URL. For example if the system files are placed in the this directory ".../httpdocs/easy_appointments/" then the URL to this folder will be "<a href='http://your-domain-name.com/easy_appointments/'>http://your-domain-name.com/easy_appointments/</a>". This URL will be needed in the following step.<br>
</li><li><b>Edit the "configuration.php" file and set your server properties.</b> Like other web systems Easy!Appointments needs to know how to connect to the database and the base URL of the installation. You can also provide the Google API keys in this file, if you want to use the Google Calendar Sync feature. NOTE that you will need to create an API key before that in the Google Cloud Console (former Google APIs Console).<br>
</li><li><b>Open a web browser and head to the Easy!Appointments installation folder URL.</b> The first time you open this page an installation guide will be shown. Fill in the administrator user and company settings and press the "Install" button. That's it! You can now use Easy!Appointments at your will.<br>
<br><br>
<hr />
<br><br>
<img src='https://dl.dropboxusercontent.com/u/27545985/easyappointments/configuration.png' />
<br><br></li></ol>

<h1>Configuration</h1>
When you finish the installation, Easy!Appointments will only contain an administrator user and some default settings. You will need to apply more info to the system to be able to suit your needs.<br>
<br>
<ol><li>Head to backend section by typing the Easy!Appointments URL followed by the "/backend" word in the end. When logged in, click on the Settings menu item on top of the page. Then click on the "Business Logic" tab to apply the working plan of your company. This will be the default working plan for all new providers. When you are finished click the "Save" button.<br>
</li><li>Next we will need to add some services that our customers can book appointments for. You can group service by using custom categories if you want. Add some records and make sure you fill the required fields.<br>
</li><li>Once you have your services entered you will need to add the service providers of your company. By doing this, customers will be able to select who they want to provide their preferred service. Hit the "Providers" menu item and then the "Providers" tab. Add a new provider and set his working plan and the services he can provide. If you wish to devide the appointments into various employees with not using Easy!Appointments just create a general provider named with your company name. It is also not necessary for the provider to know the log in credentials, but if he does, he will be able to view he's appoitnment plan and sync it with Google Calendar.<br>
</li><li>If you'll have a secretary handling all the appointments for your company, hit the "Secretaries" tab and add a new user. Select the providers that she can manage and save the record. The secretary user will be able to manage the appointments only for the providers she is responsible.<br>
</li><li>That's it! Head to the "Settings" page and hit the "Go To Booking Page" button. Add a new appointment and then go to the "Calendar" page to see it on the plan. The customer data has also been saved and you can see it on the "Customers" page.</li></ol>

Now in order for your customers to find the booking page, add a link on your webpage or your facebook account, that points to the Easy!Appointments installation folder. When a customer clicks on that link he will see the booking page.