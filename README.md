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
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/AlmerKastaraZain/Wave-Survival-Game">  
    <img src="https://github.com/user-attachments/assets/90f6972b-df53-4f65-b56c-5095ce0b9ced" width="80px" height="80px" />
  </a>

  <h3 align="center">Hotel Booking Online</h3>

  <p align="center">
    An Hotel Booking Website
    <br />
    <br />
    <br />
    <a href="https://github.com/AlmerKastaraZain/HotelWebsiteTefa/issues/new?labels=bug&template=bug-report---.md"></a>
    <a href="https://github.com/AlmerKastaraZain/HotelWebsiteTefa/issues/new?labels=enhancement&template=feature-request---.md"></a>
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
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![image](https://github.com/user-attachments/assets/3048eb4b-f531-4012-b0c8-dbbe48882492)
![image](https://github.com/user-attachments/assets/3b34da8c-1e20-43d8-985a-7e12cf24d839)

Operasi Merah Putih adalah sebuah game bergenre sejarah aksi yang membawa pemain ke masa penting dalam sejarah Indonesia, yakni perlawanan terhadap pemberontakan Partai Komunis Indonesia (PKI). Game ini dirancang untuk memberikan pengalaman mendalam tentang semangat perjuangan mempertahankan kedaulatan negara, dengan narasi yang berlandaskan fakta sejarah namun dikemas dalam gameplay yang menarik dan penuh aksi.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
[![LinkedIn][linkedin-shield]][linkedin-url]



<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Prerequisites
# Hardware Requirement
Operating System: Windows/Linux/MacOS <br />
Processor: Dual Core 2.5 GHz or higher <br />
RAM: 2GB or more <br />

# Software Requirement
[PHP versi 8.2](https://www.php.net/)
[Composer versi 2.7.8 or above](https://getcomposer.org/)
[MySQL](https://www.mysql.com/)
[Stripe CLI](https://docs.stripe.com/stripe-cli)
[Node js v20.17.0](https://nodejs.org/en)

# API Key needed (To Fill out the ENV)
Google Maps API Key
Stripe API Key
Membership Prod and Price Id (Create it using Stripe)
  
### Installation
1. Install the files from the Development Branch
2. Extract Zip
3. Create .env using .env.example and fill out API key, along with other config...
4. Run ```php artisan key:generate``` in terminal
5. Run ```npm install```, to install the necessary node dependencies. Make sure to install NPM.
6. Run ```composer install```, to install the necessary composer dependencies. Make sure to install Composer.

### Running The Website
1. Run ```php artisan serve```
2. Run ```npm run dev```
3. Run ```stripe listen --forward-to localhost:8000/stripe/webhook --skip-verify```, Make sure to install Stripe CLI, and Set your Stripe Key.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

See the [open issues](https://github.com/AlmerKastaraZain/HotelWebsiteTefa/issues) for a full list of proposed features (and known issues).

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

<!-- CONTACT -->
## Contact

Almer Kastara Zain - almerkastaraaasli@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Developer Note

The current status of this website is incomplete. Due to time constraint, I am to realize this website fully, currently there is a lot of bugs, unfinished features, and legacy code.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* Ahmad Varian Sholeh | Animasi

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AlmerKastaraZain/HotelWebsiteTefa.svg?style=for-the-badge
[contributors-url]: https://github.com/AlmerKastaraZain/HotelWebsiteTefa/contributors
[forks-shield]: https://img.shields.io/github/forks/AlmerKastaraZain/HotelWebsiteTefa.svg?style=for-the-badge
[forks-url]: https://github.com/AlmerKastaraZain/HotelWebsiteTefa/network/members
[stars-shield]: https://img.shields.io/github/stars/AlmerKastaraZain/HotelWebsiteTefa.svg?style=for-the-badge
[stars-url]: https://github.com/AlmerKastaraZain/HotelWebsiteTefa/stargazers
[issues-shield]: https://img.shields.io/github/issues/AlmerKastaraZain/HotelWebsiteTefa.svg?style=for-the-badge
[issues-url]: https://github.com/AlmerKastaraZain/HotelWebsiteTefa/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/almer-kastara-zain-5b5704333/
[product-screenshot]: images/screenshot.png
