# Authenicated Welcome Message

This is a a drupal 7 site that has a custom module that enables a block with welcome text.

# Things to know

* Disabling Module: Overlay
* Enabling new Module: Authenticated Welcome Message
* Module code repo: ```/sites/all/modules/custom/auth_message``

# Configuration

### Disable overlay
* Go to: ```/admin/modules```
* Look for: **Overlay**
	* Uncheck the box and click *Save*


### Enable Module

* Go to: ```/admin/modules```
* Check the box for **Authenticated Welcome Message*
* Click **Save** at the bottom


### Enable Block / Configure

* Go to: ```/admin/structure/block/manage/auth_message/auth_message/configure```
* Edit the following fields:
	* Welcome Message can be anything
* In the **REGION SETTINGS**
	* Change the *Bartik (default theme)* to **Sidebar first**
* Near the bottom under the **Roles** Tab
	* Check the boxe for **authenticated user**
* Save Block
* Create a basic page

# Testing..

### Go to any page
* Go to the basic page that was created above
* While logged in you should see a sidebar with the following information:
```
Hello <username>!
Your last log in was <login date>.
Visit your profile | link”

 ```
 