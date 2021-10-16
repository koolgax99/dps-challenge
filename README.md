# DPS Challenge 

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-npm.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-bootstrap.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/fo-real.svg)](https://forthebadge.com)

---

---

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#how-to-use">How To Use</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

DPS Challenge is a web application that allows user to do CRUD operations on contacts. The contact include Firstname, Lastname, Email and Address.

### Built With

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com)
- [MongoDB](https://www.mongodb.com/cloud)
- [React.js](https://reactjs.org/)

<!-- GETTING STARTED -->

# Getting Started

## Video Demonstration:

[![forthebadge](https://img.shields.io/badge/click-link-lightgrey)](https://forthebadge.com)

[[DPS Challenge App Demo]]()

---

### Deployment:

[![forthebadge](https://img.shields.io/badge/click-link-lightgrey)](https://forthebadge.com)

Deployed using [Heroku](https://dps-challenge-nihar.herokuapp.com/)

---

### Dependencies:

- Node-
  Go to [official Node.js website](https://nodejs.org/) and download the installer.
- MongoDB url-
  Visit [MongoDB](https://www.mongodb.com/)
- Browser Version-Latest

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

    $ git clone https://github.com/koolgax99/dps-challenge.git
    $ cd dps-challenge
    $ npm install
    $ cd client
    $ npm install

<!-- USAGE EXAMPLES -->

## Running

    npm run dev

---

    After getting the API Keys and endpoints please specify the following in a .env file in the root directory.
    MONGODB_URI = "" // Mongo cluster URI

## How To Use

The landing page consists of 2 main parts- 'Contacts' and 'Add Contacts':
On the Contacts page the user can choose whichever contact they want to view

  <p align='center'><img src=screenshots\1.PNG>
<p align="center">

On the add page the user can fill the contact form with firstname, lastname, email and address. And then click on the Submit button is order to add a new contact to the DB.

  <p align='center'><img src=screenshots\3.PNG>
<p align="center">
  
Once you click on any contact in the page, you can see all the details about that contact. And also you have an option to edit that contact.
  
  <p align='center'><img src=screenshots\2.PNG>
<p align="center">
  
In the Edit contact page you can view the particular contact and then edit the fields of that contact. If you edit any option you have to click on the "Update" button to save those changes. By clicking on the "delete" button you can delete that particular contact.
  <p align='center'><img src=screenshots\4.PNG>
<p align="center">
  ***
  
<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.
