<a name="readme-top"></a>


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- [![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://icons8.com/icon/3VheoNbKrTPk/autonomous-car">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">CA ATV Report Analysis</h3>

  <p align="center">
    Repository of code/work for accident-analysis subgroup in AIEA Lab (ATV), UCSC
    <br />
    <br />
    <!-- <a href="https://github.com/rohan527/accident-analysis"><strong>Explore the repo »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a> -->
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<!-- <details>
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
</details> -->


<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

In this project, we are analysing autonomous vehicle (ATV) accident reports generated by the Department of Motor Vehicles, California (DMV) from the year 2016 to 2022. These reports have details about the accidents which includes (but not limited to) date, time, place, car manufacturer, location of damage on ATV, weather, and road conditions.   

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

Major amount of the work is done using Python. Here is am list of libraries that are used until now: 

* beautifulsoup
* matplotlib
* pandas
* seaborn
* pypdf
* ocrmypdf


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

The installation guide for most of the libaries can be found on their websites. Make sure to download all the libraries required in each step so that the code runs correctly. 

<!-- ROADMAP -->
## Roadmap

- [x] Collect DMV reports
- [x] Create dataset by reading the files in PDF/scanned format
- [o] Analyse the data
    - [ ] Possible Tangent: Hazard indicator based on data
    - [ ] Possible Tangent: Visualing the accidents using openai 
    - [ ] Expanding to different states
- [ ] Research Paper 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/name_branch`)
3. Commit your Changes (`git commit -m 'Added some feature_name'`)
4. Push to the Branch (`git push origin feature/yourname_branch`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Feel free to contact any of the students mentioned below in the acknowledgements. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

The project is being done under professor Leilani Gilpin as a part of the Artificial Intelligence Explainability Accountability (AIEA) Lab at University of California, Santa Cruz. 

Following are the students who have contributed to the project:

* Rohan Ghosalkar (Graduate | CSE | rghosalk@ucsc.edu)
* Tommy Chen (Undergraduate | CSE | tchen175@ucsc.edu)
* Tong Jia (Undergraduate | CSE | tojia@ucsc.edu)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rohan527/accident-analysis.svg?style=for-the-badge
[contributors-url]: https://github.com/rohan527/accident-analysis/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rohan527/accident-analysis.svg?style=for-the-badge
[forks-url]: https://github.com/rohan527/accident-analysis/network/members
[stars-shield]: https://img.shields.io/github/stars/rohan527/accident-analysis.svg?style=for-the-badge
[stars-url]: https://github.com/rohan527/accident-analysis/stargazers
[issues-shield]: https://img.shields.io/github/issues/rohan527/accident-analysis.svg?style=for-the-badge
[issues-url]: https://github.com/rohan527/accident-analysis/issues
[license-shield]: https://img.shields.io/github/license/rohan527/accident-analysis.svg?style=for-the-badge
[license-url]: https://github.com/rohan527/accident-analysis/blob/master/LICENSE.txt
<!-- [linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew -->
[product-screenshot]: images/screenshot.png
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