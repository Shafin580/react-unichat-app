<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Shafin580/react-unichat-app">
    <img src="images/logo.ico" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Unichat App</h3>

  <p align="center">
    An awesome chat application where users can sign up using their google account and chat with other people who signed up in the application.
    <br />
    <br />
    <br />
    <a href="https://unichatshafindev.netlify.app/">View Demo</a>
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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://unichatshafindev.netlify.app/)

This project is a full-fledged Firebase Chat Application. With social authentication including Google and Facebook using Firebase, online statuses, great design, and functionality, image support, sound notifications, the ability to create multiple rooms, and much more.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [React.js](https://reactjs.org/)
* [Chatengine.io](https://chatengine.io/)
* [Firebase](https://firebase.google.com/)
* [Styled-Components](https://styled-components.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Here are some set of instructions to get the project running on your local device. Download the full project from github to your local device first. You can also run the following command in your CLI:

```sh
   git clone https://github.com/Shafin580/react-unichat-app
   ```

### Prerequisites

All the dependencies are listed in package.json file. All that needs to be done is to open the CLI and cd to the root of the project folder and run the following command.
* npm
  ```sh
  npm install
  ```

### Installation

To run the project, you must first get your own required API keys and set it up.

1. Get ChatEngine API key at [https://chatengine.io/](https://chatengine.io/)
2. Enter your chatengine API key in `.env`
   ```js
    REACT_APP_CHAT_ENGINE_KEY='your chat engine key'
    REACT_APP_CHAT_ENGINE_ID='your chat engine id'
   ```
3. Configure your firebase in `src/firebase.js`
  ```js
    import firebase from "firebase/app";
    import "firebase/auth";

    export const auth = firebase.initializeApp({
        apiKey: "your firebase api key",
        authDomain: "your firebase auth domain",
        projectId: "your firebase project id",
        storageBucket: "your firebase auth domain",
        messagingSenderId: "firebase messenger id",
        appId: "firebase app id"
      }).auth();
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://www.linkedin.com/in/shafin-ahmed-790959213/
[product-screenshot]: images/unichatSS.png
