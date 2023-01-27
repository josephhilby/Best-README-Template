<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Stargazers][stars-shield]][stars-url]
-->



<!-- PROJECT LOGO -->
<br />
<div align="center">

  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Issues][issues-shield]][issues-url]

  <a href="https://github.com/<your_repo>">
    <img src="images/banner-example.png" alt="Logo" width="100%">
  </a>

  <h3 align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/<your_repo>/issues">Report Bug</a>
    ·
    <a href="https://github.com/<your_repo>/issues">Request Feature</a>
  </h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#api-endpoints">API Endpoints</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgments">Acknowledgments</li>
    <li><a href="#license">License</a></li></a>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<div align="center">

  [![Product Name Screen Shot][product-screenshot]](https://example.com)
  
</div>

This should be a **short** explination as to: why the project exists, what the project will do, why that is good.

Here's a ul:
* Something about the project
* Another thing about the project
* :smile:

Closing sentence about why the project is so cool!

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Usage

This is an example of how to list things you need to use the web application.
* chrome

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



### Installation

This is an example of how to list things you need to use the software localy.
* ruby '2.7.4'
* rails '5.2.8'

_Below is an example of how you can instruct your audience on installing and setting up your app locally. This template doesn't rely on any external dependencies or services._


1. Get a free API Key at [https://example.com](https://example.com)
2. Fork and clone the repo to your local machine
3. Install gems
   ```sh
   $ bundle install
   $ rails db:{drop,create,migrate,seed}
   $ bundle exec figaro install
   ```
4. Enter your API in `config/application.yml`
   ```yml
   api-key-name: <YOUR API KEY HERE>
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- API Endpoints -->
## API Endpoints

### GET[^1]
<details> 
  <summary> <code>localhost:5001/api/v1/endpoint</code> </summary>

### GET /api/v1/endpoint?q=thing

> Get a list of all things (if no params are passed) OR by selected thing, through params.

**Parameters**

> |          Name | Required |  Type   |  Description     |
> | -------------:|:--------:|:-------:| ---------------- |
> |     `q`       |    no    | string  | The thing you want to filter results by.   |


**Response**

> ```
> {
>     "data": [
>         {
>             "id": null,
>             "type": "thing",
>             "attributes": {
>                 "title": "thing",
>                 "url": "https://www.thing.com/2013/11/thinguri.html",
>                 "image": "https://thing-images.s3.amazonaws.com..."
>             }
>         },
>         {...},
>         {...},
>         {...},
>         {etc},
>     ]
> }
> ```
</details>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Complete MVP
- [x] Add Cool-new-feature
- [ ] Next big thing
    - [ ] part one
    - [ ] part two

See the [open issues](https://github.com/<your_repo>/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- BUILT WITH -->
## Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

<br />
<div align="center">
<img src="images/tech-stack-demo.png" alt="Tech-Stack" width="70%">
</div >

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

### Front End Team
<table>
  <tr>
    <td><img src="https://avatars.githubusercontent.com/u/######?s=120&v=4"></td>
  </tr>
  <tr>
    <td>Name</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/<username>">GitHub</a><br>
      <a href="https://www.linkedin.com/in/<username>/">LinkedIn</a>
    </td>
  </tr>
</table>

### Back End Team
<table>
  <tr>
    <td><img src="https://avatars.githubusercontent.com/u/108031077?s=120&v=4"></td>
  </tr>
  <tr>
    <td>Joseph Hilby</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/josephhilby">GitHub</a><br>
      <a href="https://www.linkedin.com/in/josephmhilby/">LinkedIn</a>
    </td>
  </tr>
</table>

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



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)
* [GitHub Banner](https://rmariuzzo.github.io/github-banner/)
* [Tech Stack](https://www.figma.com/templates/tech-stack-diagram/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

[^1]: Note: Here is a footnote

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/<your_repo>.svg?style=for-the-badge
[contributors-url]: https://github.com/<your_repo>/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/<your_repo>.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/<your_repo>/network/members
[stars-shield]: https://img.shields.io/github/stars/<your_repo>.svg?style=for-the-badge
[stars-url]: https://github.com/<your_repo>/stargazers
[issues-shield]: https://img.shields.io/github/issues/<your_repo>.svg?style=for-the-badge
[issues-url]: https://github.com/<your_repo>/issues
[license-shield]: https://img.shields.io/github/license/<your_repo>.svg?style=for-the-badge
[license-url]: https://github.com/<your_repo>/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/<your_linkedin>
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
