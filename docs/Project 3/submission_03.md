# TEAM NAME: flour

# WEB APPLICATION NAME: Catch

# Overview:
1. Views:
    * Home Page:
        * Displays all events, will implement sorting later
    * Events Page
        * Displays all events that the logged in user is hosting
    * Map Page
        * Currently displays all events, sorting not implemented
    * Profile Page
        * Displays data based on logged in user
        * Moved pet information to new Pet Page
    * About Page -> Pet Page
        * Now displays all Pets that the logged in user owns
 
# Team Members:

* Bailey Boone, baileyboone
* Erica Zheng, pinebay
* Justin Hui, jhui04
* Parth Nagraj, pdnagraj

# Video Link: https://www.youtube.com/watch?v=1o2OCPbLbUQ

# Design Overview:
Users can now only view the page when logged in. Being logged in displays the events that the user is hosting under the Events tab. Being logged in displays the pets that the user owns under the Pets tab. Being logged in allows the user to edit their profile information.

1. Part 1 Authentication, Authorization, and Session Support (35%)
     * Your application must support authentication and authorization/permissions.
     * Your application must include login/logout functionality.
     * Your application must include at least one user in your database.
     * Your application must include at least one group.
     * Your application must tailor the rendered view in the browser according to a user that is logged in.
        * If the user is not loggeed in they see a form to either login or sign up, Event tab displays all the events that the User is Hosting and Pet tab displays all the Pets that the user is the owner of. compsci326 does not have Events or Pets, login to another account to check this.
        
2. Part 2 User Interaction with Forms (35%)
    * Your application must include a login form.
    * Your application must include at least one form that allows new data to be created in your application. For example, a Facebook-like app can create a new “post” - this new post is new data on your server which contains what was posted and who posted it.
      * Under the Profile Tab, user can create a Pet which will appear under the Pet Tab
    * Your application must include at least one form that allows data in your application to be modified from a logged in user. (i.e., a user modifies their favorite movie in profile data).
       * Under the Profile Tab, user can edit their Profile information

# Problems/Successes:

Problems:
* Getting an image associated with the admin user and pets
* Assigning encrypted passwords with init.py
* Programatically creating a group and assigning permissions
* Editing user image profile

Success: 
* Displaying events and pets based on the logged in user
* Forms that allow user to create pets and events
* Form that allows user to edit their profile

# Team Choice:
Using the Google maps API to embed a realtime map with a marker where the user currently is and markers of nearby events currently going on.


