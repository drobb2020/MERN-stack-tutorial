<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/drobb2020/MERN-stack-tutorial">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Workout Companion (MERN Stack)</h3>

  <p align="center">
    This is a MERN stack application demonstrating a basic express API backend and a React frontend.
    <br />
    <a href="https://github.com/drobb2020/MERN-stack-tutorial"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/drobb2020/MERN-stack-tutorial">View Demo</a>
    ·
    <a href="https://github.com/drobb2020/MERN-stack-tutorial/issues">Report Bug</a>
    ·
    <a href="https://github.com/drobb2020/MERN-stack-tutorial/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This is the first part of a two part tutorial from the Net Ninja on YouTube. The first part covers creating the API backend connected to a Mongo database, with a React frontend. 

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Express](https://nextjs.org/)
* [MongoDB](https://www.mongodb.com/cloud/atlas/lp/try4?utm_source=bing&utm_campaign=mdb_bs_americas_canada_search_core_brand_atlas_desktop&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=415204512&adgroup=1212761794897237&msclkid=4d10062d94171b98d32a653bd814cbc6)
* [Node.js](https://nodejs.org/en/)
* [React.js](https://reactjs.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

You must have node.js installed on your machine to get started with this project. Along with node.js, you will also need npm.

### Prerequisites

Install or upgrade node.js:

1. Visit [https://nodejs.org/](https://nodejs.org).
2. It is recommended to download the latest LTS version of node for more users.
3. Follow the installation instructions provided by node.js.

Install or update npm:

* npm

  ```sh
  npm install npm@latest -g
  ```

### Installation

#### Backend Configuration

1. Create a base directory for the entire project. This can be named whatever you like. In my case I named it MERN-stack-tutorial
2. In the directory create an additional folder named backend.
3. cd into the backend folder.
4. run npm init -y to create a package.json file.
5. Install the following packages using npm:

  ```sh
   npm install express dotenv mongoose
   npm install -D nodemon
   ```

6. Add the following line to the scripts section of your package.json:

  ```json
  "dev": "nodemon server.js", 
  ```

7. The backend is now ready for development. Follow the video series on [YouTube](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iJ_KkrkBZWZRHVwnzLIoUE) to complete the project.

#### Frontend Configuration

1. cd out of the backend folder and run the following command:
  ```sh
  npx create-react-app frontend
  ```
2. This will create a frontend folder and populate it with the default React framework.
3. cd into the frontend folder and use the command:
   ```sh
   npm start
   ```

4. This will start the react application.

### Clone this repository
1. If you wish you can clone this repository to get started.

   ```sh
   git clone https://github.com/drobb2020/MERN-stack-tutorial.git
   ```

2. cd into the backend folder and install NPM packages

   ```sh
   npm install
   ```

3. You will need to visit MongoDB Atlas to create and connect your own database.
4. See the file .env_example to configure you Mongo uri and the port the backend will listen on.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

As a tutorial this project was useful in developing my express and react skills. I have done several Net Ninja courses and he is one of the best teachers around for this topic. Please check out his channel on [YouTube](https://www.youtube.com/c/TheNetNinja).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

* [X] Completed the first video series.
* [ ] Continue with the second part of the series [here](https://www.youtube.com/playlist?list=PL4cUxeGkcC9g8OhpOZxNdhXggFz2lOuCT).
* [ ] Go Live with a demonstration website

See the [open issues](https://github.com/drobb2020/MERN-stack-tutorial/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Your Name - [@davidrobb2](https://twitter.com/davidrobb2) - drobb2011@gmail.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/drobb2020/MERN-stack-tutorial)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

As Always this would not be possible without the great teaching skills of The Net Ninja.

Here are some other useful links:

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/drobb2020/MERN-stack-tutorial.svg?style=for-the-badge
[contributors-url]: https://github.com/drobb2020/MERN-stack-tutorial/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/drobb2020/MERN-stack-tutorial.svg?style=for-the-badge
[forks-url]: https://github.com/drobb2020/MERN-stack-tutorial/network/members
[stars-shield]: https://img.shields.io/github/stars/drobb2020/MERN-stack-tutorial.svg?style=for-the-badge
[stars-url]: https://github.com/drobb2020/MERN-stack-tutorial/stargazers
[issues-shield]: https://img.shields.io/github/issues/drobb2020/MERN-stack-tutorial.svg?style=for-the-badge
[issues-url]: https://github.com/drobb2020/MERN-stack-tutorial/issues
[license-shield]: https://img.shields.io/github/license/drobb2020/MERN-stack-tutorial.svg?style=for-the-badge
[license-url]: https://github.com/drobb2020/MERN-stack-tutorial/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
