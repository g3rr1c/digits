![](https://github.com/ics-software-engineering/nextjs-application-template/raw/main/doc/landing-page.png)

Digits is a Next.js 14 application that utilizes:

- A standard directory layout using 'src/' as recommended in the [Next.js Project Structure](https://nextjs.org/docs/getting-started/project-structure) guide.
- [Bootstrap 5 React](https://react-bootstrap.github.io/) for user interface.
- [React Hook Form](https://www.react-hook-form.com/) for form development.
- Authorization, authentication, and registration using [NextAuth.js](https://next-auth.js.org/).
- Initialization of users and data from a settings file.
- Alerts regarding success or failure of DB updates using [Sweet Alert](https://sweetalert.js.org/).
- Quality assurance using [ESLint](http://eslint.org) with packages to partially enforce the [Next.js ESLint rules](https://nextjs.org/docs/app/building-your-application/configuring/eslint) and the [AirBnB Javascript Style Guide](https://github.com/airbnb/javascript).

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

<img width="600px" src="/public/digitsLandingPage.png">

### Register
If you do not yet have an account on the system, you can register by clicking on “Login”, then “Sign Up”:

<img width="600px" src="/public/digitsLandingPage.png">

### Sign in
Click on the Login link, then click on the Signin link to bring up the Sign In page which allows you to login:

<img width="600px" src="/public/digitsLandingPage.png">

### User home page
After successfully logging in, the system takes you to your home page. It is just like the landing page, but the NavBar contains links to list contact and add new contacts:

<!--
## Screencasts

For more information about this system, please watch one or more of the following screencasts. Note that the current source code might differ slightly from the code in these screencasts, but the changes should be very minor.

- [Walkthrough of system user interface (6 min)](https://youtu.be/48xu1hrqUi8)
- [Data and accounts structure and initialization (18 min)](https://youtu.be/HZRjwrVBWp4)
- [Navigation, routing, pages, components (34 min)](https://youtu.be/XztTdHpv6Jw)
- [Forms (32 min)](https://youtu.be/8FyWR3gUGCM)
- [Authorization, authentication, and roles (12 min)](https://youtu.be/9HX5vuXTlvA)
-->
