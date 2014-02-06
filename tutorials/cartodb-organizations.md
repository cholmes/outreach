### Summary

This tutorial will walk you through the basics of CartoDB's new Multi-User functionality. As this feature is
very new this may get out of date and/or change soon.

### Getting Started

Currently a select group of CartoDB's paying users are in contact with the core team to test and give feedback on
the new Enterprise functionality. If you are interested in joining that group then get in touch, with an email
to support [at] cartodb.com. We are starting with existing customers, but soon will trial to new users as well.

A CartoDB team member will enable the functionality on your existing account. If your account is set up with 
personal name then you can request to use an alternate organization name. Users created in your
account will login to username.org-name.cartodb.com, and org-name can be your existing account name or a new one.

Once you are notified that the new functionality has been enabled you should login to your account and you should see a new option under your user name dropdown.

![organization users](https://f.cloud.github.com/assets/407017/2070714/369fd400-8d1f-11e3-9b47-89dcb74bece2.png)

Click on the **Organization users** option and you'll be taken to your organization dashboard.

![organization dashboard](https://f.cloud.github.com/assets/407017/2070679/d64c84cc-8d1e-11e3-8c45-5caac4a35003.png)

### User Management

You should see your user listed. If you click on this user you get the user details page.

![user details](https://f.cloud.github.com/assets/407017/2070747/b6fbffa2-8d1f-11e3-8dca-af320594e676.png)

This gives an overview of the user. You can see how many tables and visualizations they've made, how many map views
and geocodes they've used, and how recently they accessed. This user is a special user, as it is the administrator. 
Often right after upgrade the administrator will have a disproportionate amount of space, so you may want to lower the
quota of the administrator user.

### Adding a New User

To add a new user just hit the 'add new user' button from the main organization dashboard page. This will take you
to the **Create new user** page.

![create user](https://f.cloud.github.com/assets/407017/2070852/ff4c98b0-8d20-11e3-8e43-4f0c4a7a301a.png)

The username will be what the new user will login as, under your organization name, so in the above case it would
be http://cholmes.widget-org.cartodb.com You can change the space allocated to them. Right now the email address
is not hooked up to the signin process, but will be soon.

In the future we will not ask the admin for the password, but will just send an email to the user so they can
create their own password though. Currently though the administrator should create a temporary password (like
'changeme') and then tell the user to login with that and then go to their account settings and change it). 
Alternatively you could just ask your user for a password or have them enter it on your admin screen.

### Organization user sign in

Right now organization users need to sign in at their specific account. You can see what URL they should sign in
at on their user detail page:

![detail page](https://f.cloud.github.com/assets/407017/2070986/c783449a-8d22-11e3-9708-ae092a8ddeef.png)

Give that url to your user, and tell them to login there.

Currently there is a problem with the CartoDB security certificates, so they likely will get a warning screen in
their browser:

![warning](https://f.cloud.github.com/assets/407017/2071025/2883a488-8d23-11e3-97d1-1aaa2f9bf1b8.png)

(this will look different in firefox or safari, but will be the same general message)

**This will be fixed as soon as we can**

But for now, just go past the error, give the exception to the browser - we'll get it fixed up soon. Note also that currently
organization users have to login at that location, we don't yet allow them to login to the main CartoDB signin. So
if your users are having trouble logging in make sure they are going to their proper entry point.

### Quota Visualization

The main organization page shows you how much space user is allocated. You can adjust it by clicking on the user 
and then changing their details.

![org overview](https://f.cloud.github.com/assets/407017/2070966/7527acf4-8d22-11e3-9b79-bb5223df6f7b.png)

### Next steps

We know we have some improvements to make, and we have a number of ideas of where we want to go next. But please
let us know what you see as the most critical next steps to make this truly useful for your organization.






