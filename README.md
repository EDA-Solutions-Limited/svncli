# SVNCLI

<!-- PROJECT LOGO -->
<p align="center">
  <a href="https://github.com/EDA-Solutions-Limited/svncli"><strong>Explore the project »</strong></a>
  <br />
  <a href="https://github.com/EDA-Solutions-Limited/svncli/issues">Report Bug</a>
  ·
  <a href="https://github.com/EDA-Solutions-Limited/svncli/issues">Request Feature</a>
</p>

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
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

The SVN commands on Linux can be tedious to use, as you have to type "svn" for every command and type the full url path when referencing to the SVN. There are several Linux SVN GUI clients, however, they are outdated and not included in some of the built-in repos.
<br>
This SVN CLI interfaces with the svn command, to create a constant user input loop, allowing for more intuitive interaction with the SVN via Linux command line.

<!-- GETTING STARTED -->
## Getting Started

### Installation

#### Manual Installation
1. Move contents to the desired location e.g. /opt/svncli/
2. Add the bin folder path to the PATH environment variable
3. Edit the contents in the config folder to include your svn url and repo list

### Usage
1. Run "svncli" in the folder that you would like to interact with
2. Enter your details and choose the repo that you would like to enter
3. Use the svn subcommands without the "svn" commands, adding "svn" will run the command as absolute (as written in the terminal) in case the parsing of the command fails.
4. Run "help" to get a list of the commands, or run "svn help" to get the original svn documentation

### Notes:
Some commands may have reduced functionality just to create a more intuitive experience. Some commands may work even though they are not listed in the available commands. Please feel free to add to this project if you have any ideas to contribute.

<!-- ROADMAP -->
## Roadmap
1. Add a prefix to substitute for SVN's current path
2. Streamline the login process, maybe add password encryption and add auto-login during the same shell session

<!-- CONTRIBUTING -->
## Contributing

Contributions are what makes the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License
MIT

<!-- CONTACT -->
## Contact
support@eda-solutions.com
