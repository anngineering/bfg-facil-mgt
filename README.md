<!--
*** Credits to https://github.com/othneildrew/Best-README-Template/blob/main/BLANK_README.md for template>
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
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
<!-- [![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url] -->
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/anngineering/bfg-facil-mgt">
    <img src="images/logo.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">NLPolis Against Scams</h3>

  <p align="center">
    Build For Good project repo for Automated Facilities Allocation Service
    <br />
    <a href="https://github.com/anngineering/bfg-facil-mgt"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/anngineering/bfg-facil-mgt">View Demo</a>
    ·
    <a href="https://github.com/anngineering/bfg-facil-mgt/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/anngineering/bfg-facil-mgt/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
    <li><a href="#datasets">Datasets</a></li>
    <li><a href="#algos">Resource Allocation Algorithms</a></li>
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

![Product Name Screen Shot][product-screenshot]

<!-- Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description` -->
    
  
Recreational sports offer a multitude of benefits that significantly contribute to physical and mental well-being. Engaging in these activities helps individuals stay active, enhancing cardiovascular health, muscle strength, and overall fitness. Beyond the physical benefits, team sports foster a strong sense of belonging and community, creating inclusive environments where race, ethnicity, and socio-economic background become secondary to shared goals and teamwork. Moreover, recreational sports teams often serve as the first "line of defense" in spotting and nurturing new talent, potentially building the next Olympian for Team Singapore.  

However, securing facilities for these teams presents significant challenges. Currently, the process involves direct communication with SportsSG, often requiring a 2-3 month advance notice to check facility availability for individual dates. This manual system is prone to delays and inefficiencies, as decisions are at the discretion of sports officers who may be unavailable due to vacations or other reasons. Consequently, teams may face disruptions if their requests are not processed in time.  

To address these issues, I propose a solution inspired by Team USA Gymnastics' use of a computer program to select their bronze medal-winning team. By applying a similar algorithmic approach, we can optimize facility allocations based on parameters such as resource availability, demand, national versus recreational status, team size, and preferences. The envisioned end-state product is a web app that displays available facilities, allows teams to apply for facilities and indicate their preferences, runs a recommendation algorithm to suggest optimal allocations, and notifies teams of their assigned locations and dates. This system aims to streamline the booking process, ensuring fair and efficient access to facilities for all sports teams.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

TBD

* Python
* Docker
* MongoDB/MySQL

### Datasets

TBD  


### Resource Allocation Algorithms

TBD  

- 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

<!-- This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps. -->
TBD

### Prerequisites

<!-- This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ``` -->
TBD

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/anngineering/bfg-facil-mgt
   ```
2. Enter build folder
   ```sh
   cd build
   ```
3. Build Docker Container
   ```sh
   docker compose up -d
   ```
4. execute code within container at src/ folder
   ```sh
   docker exec -it bash
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

<!-- Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_ -->
TBD

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- Establish parameters for resource allocation algorithm
- Test and select resource allocation algorithms
- Set up Facilities DB, User DB, Booking DB
- Create Facility Recommendation Service, Application service, Notification service
- Front End

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

TBD after KOM

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/anngineering/bfg-facil-mgt/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Anngineering - [@Anngineer](https://web.telegram.org/) - ann.chiajx@gmail.com

Project Link: [https://github.com/anngineering/bfg-facil-mgt](https://github.com/anngineering/bfg-facil-mgt)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: [https://github.com/anngineering]
<!-- [forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues -->
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/anngineering
[product-screenshot]: images/screenshot.jpg
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
