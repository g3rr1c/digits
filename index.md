<img width="800px" src="/public/digitsLandingPage.png">

Digits is an application that allows users to:

- Register an account.
- Create and manage a set of contacts.
- Add a set of timestamped notes regarding their interactions with each contact.

## Installation

First, make sure you have [Node.js and npm installed](https://nodejs.org/en/download).

Second, download a copy of Digits. Note that Digits is a private repo and so you will need to request permission from the author to gain access to the repo.

Third, cd into the app directory install the required libraries with:

```

$ npm install

```
Once the libraries are installed, you can start up the application by invoking:

```

$ npm run start

```

If all goes well, the template application will appear at http://localhost:3000. You can login using the credentials in settings.development.json, or else register a new account.

Lastly, you can run ESLint over the code in the imports/ directory with:

```
$ npm run lint

> nextjs-application-template-1@0.1.0 lint
> next lint

✔ No ESLint warnings or errors
$
```

## Walkthrough

The following sections describe the major features of this template.


### Landing Page
When you first bring up the application, you will see the landing page that provides a brief introduction to the capabilities of Digits:

<img width="800px" src="/public/digitsLandingPage.png">

### Register
If you do not yet have an account on the system, you can register by clicking on “Login”, then “Sign Up”:

<img width="800px" src="/public/signup.png">

### Sign in
Click on the Login link, then click on the Signin link to bring up the Sign In page which allows you to login:

<img width="800px" src="/public/Signin.png">

### User home page
After successfully logging in, the system takes you to your home page. It is just like the landing page, but the NavBar contains links to list contact and add new contacts:

<img width="800px" src="/public/loggedInHome.png">

### List Contacts
Clicking on the List Contacts link brings up a page that lists all of the contacts associated with the logged in user:

<img width="800px" src="/public/listContacts.png">

This page also allows the user to add timestamped “notes” detailing interactions they’ve had with the Contact. For example:

<img width="800px" src="/public/notes.png">

### Edit Contacts
From the List Contacts page, the user can click the “Edit” link associated with any Contact to bring up a page that allows that Contact information to be edited:

<img width="800px" src="/public/editContact.png">

### Admin mode
It is possible to designate one or more users as “Admins” through the settings file. When a user has the Admin role, they get access to a special NavBar link that retrieves a page listing all Contacts associated with all users:

<img width="800px" src="/public/admin.png">


<!--
## Screencasts

For more information about this system, please watch one or more of the following screencasts. Note that the current source code might differ slightly from the code in these screencasts, but the changes should be very minor.

- [Walkthrough of system user interface (6 min)](https://youtu.be/48xu1hrqUi8)
- [Data and accounts structure and initialization (18 min)](https://youtu.be/HZRjwrVBWp4)
- [Navigation, routing, pages, components (34 min)](https://youtu.be/XztTdHpv6Jw)
- [Forms (32 min)](https://youtu.be/8FyWR3gUGCM)
- [Authorization, authentication, and roles (12 min)](https://youtu.be/9HX5vuXTlvA)
-->
