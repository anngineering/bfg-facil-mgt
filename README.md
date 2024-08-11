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
  <a href="https://github.com/anngineering/bfg-scam-prevention">
    <img src="images/logo.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">NLPolis Against Scams</h3>

  <p align="center">
    Build For Good project repo for NLP scam prevention system
    <br />
    <a href="https://github.com/anngineering/bfg-scam-prevention"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/anngineering/bfg-scam-prevention">View Demo</a>
    ·
    <a href="https://github.com/anngineering/bfg-scam-prevention/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/anngineering/bfg-scam-prevention/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
    <li><a href="#nlp-models">NLP Models</a></li>
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

_Note: This is a preliminary proposal to enhancing scam prevention in SG. Feel free to propose other methods, suggest changes to the system diagram, or simply bounce ideas with me via Telegram DM. Do also note that certain aspects of the scope may expand/get cut as we go along in this hackathon._     
  
This project proposes a backend service MVP (for now) to enhance the detection, reporting, and indexing of phishing emails, sms, and urls, relying on NLP models and human reporting. The desired features are explained in greater detail in the `roadmap` section below.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

TBD

* Python
* Docker
* FastAPI? gRPC? Kafka?
* Any other ideas?

### Datasets

TBD  

- Phishing Email Datasets
    - https://www.kaggle.com/datasets/subhajournal/phishingemails 
    - https://www.kaggle.com/datasets/shashwatwork/phishing-dataset-for-machine-learning
- Phishing SMS Datsets
    - https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data
    - https://huggingface.co/datasets/ucirvine/sms_spam 
- Phishing URL Datasets
    - https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset
    - https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls  

### NLP Models

TBD  

- BERT (Encoder only)
    - https://huggingface.co/google-bert/bert-base-cased 
    - https://huggingface.co/google-bert/bert-base-uncased 
- Feel free to add more

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
   git clone https://github.com/anngineering/bfg-scam-prevention
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

- Data Processing of ham/spam email, sms, and url datasets
- Set up ElasticSearch DB
    - Need index for train/val dataset of ham/spam emails, sms, and urls
    - Need index for model-generated and human-reported spam emails, sms, and urls
- Train email, sms, and phishing url classification models to adequate metrics
    - Selection of model types and fine-tuning methodologies (including appropropriate metrics)
    - Fine Tuning and hyperparameter tuning
- POC of on-line inference pipeline (command line arguments from local txt file is fine???)
- POC of on-line user-reporting service for human-labeled spam email/sms/url samples

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

<a href="https://github.com/anngineering/bfg-scam-prevention/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Anngineering - [@Anngineer](https://web.telegram.org/) - ann.chiajx@gmail.com

Project Link: [https://github.com/anngineering/bfg-scam-prevention](https://github.com/anngineering/bfg-scam-prevention)

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
