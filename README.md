# Full-Stack-Application-Systémes-Distribués-Docker
Projet-JEE-CLOUD
# application-based-architecture-micro-service
Activité Pratique du Contrôle " Ayoub Chawki "
application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.
<br /> ![3](https://user-images.githubusercontent.com/97169668/207480973-10c8afea-fad4-4d98-8ff8-94a720fc4582.PNG)
<div align="center">
<a name="readme-top"></a>


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->

  <h3 align="center"> application-based-architecture-micro-service</h3>

  <p align="center">
application-based-architecture-micro-service!
    <br />
    <a href="https://github.com/ayoubchawkiPRO/application-based-architecture-micro-service/tree/master"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="(https://github.com/ayoubchawkiPRO/application-based-architecture-micro-service)">View Demo</a>
    ·
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

# I. Backend :
  * [1. about-the-project](#about-the-project)
  * [2 Inventory service - get all products](#2-inventory-service---get-all-products)
  * [3 Inventory service - get product by ID](#3-inventory-service---get-product-by-id)
  * [4 Customer Service - get All Customers](#4-customer-service---get-all-customers)
  * [5 Customer Service - get Customer by ID](#5-customer-service---get-customer-by-id)
  * [6 Bill Service - get bills](#6-bill-service---get-bills)
  * [7 Gateway](#7Gateway)
  * [8 Eureka Service](#8-eureka-service)
# II. Frontend Angular Client :
  * [Login screen](#login-screen)
  ## Products
  * [1 Show all products](#1-show-all-products)
  * [2 Edit products](#2-edit-products)
  * [3 Delete products](#3-delete-products)
  * [4 Search for a product](#4-search-for-a-product)
  * [5 New Product](#5-new-product)
  ## Customers
  * [1 Show all customer](#1-show-all-customer)
  ## Bills
  * [Show Bills](#show-bills)
# III Secured Angular Client with keycloak
  * [1 Setup](#1-setup)
  * [2 Postman](#2-postman)
  * [3 Client Auth Credentials](#3-client-auth-credentials)
# IV. KAFKA :
  * [1 Supplier](#1-supplier)
  * [2 Consumer](#2-Consumer)
  * [3 Kafka streams ](#3-Kafka-streams )


# V. DOCKER :
  * * [4 gitHub](#5-gitHub)



<!-- ABOUT THE PROJECT -->
## About The Project
![3](https://user-images.githubusercontent.com/97169668/207427247-d51edb9f-035b-466b-856d-dccb99cb292b.PNG)
  USE CASE :
  ![mcd](https://user-images.githubusercontent.com/97169668/207427919-3d1c1a88-e508-4182-a9b9-36aca8e47805.PNG)
  
* You should implement DRY principles to the rest of your life :smile:

Use the `README.md` to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![Angular][Angular.io]][Angular-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
![1](https://user-images.githubusercontent.com/97169668/207427133-57c0b81a-0b9e-425c-a25b-a62e53082919.PNG)
![2](https://user-images.githubusercontent.com/97169668/207427160-33383348-ce0a-40b3-9901-c133edf5ac2e.PNG)

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```
## 1 Customer Service - get All Customers
![Capture5](https://user-images.githubusercontent.com/97169668/207427595-f0c89585-3b6e-49b9-b35d-740b6fcd8622.PNG)
![Capture13](https://user-images.githubusercontent.com/97169668/207427646-c86bfc79-8135-4ac3-930f-9244cab9d71c.PNG)
![Capture2](https://user-images.githubusercontent.com/97169668/207427574-ef9fbcd5-3077-49cf-96c4-c4c005821e4f.PNG)
![Capture18](https://user-images.githubusercontent.com/97169668/207427674-9a68d992-23cc-470f-b585-3053fc69e738.PNG)

![Capture3](https://user-images.githubusercontent.com/97169668/207427580-20b5a8a5-b710-4f77-95c0-b4ec13fca826.PNG)
![Capture4](https://user-images.githubusercontent.com/97169668/207427591-4f8167a5-4d5f-422b-8d20-b69eb807ea14.PNG)
## 2 Customer Service - get Customer by ID
![Capture19](https://user-images.githubusercontent.com/97169668/207427682-6e834b23-3eba-4b3d-918c-ce16836bf73a.PNG)
## 3 Inventory service - get all products
![Capture6](https://user-images.githubusercontent.com/97169668/207427607-904fe10a-6edc-4b70-9758-ea9e654e0e0a.PNG)
![Capture10](https://user-images.githubusercontent.com/97169668/207427635-05c2fee3-94cd-4782-897a-29fc1acf1bcb.PNG)
![Capture7](https://user-images.githubusercontent.com/97169668/207427617-414002f9-5b06-4890-9549-72e45a625e47.PNG)
![Capture8](https://user-images.githubusercontent.com/97169668/207427622-46cf135e-a0f8-425e-8c3f-ca76076ba5d6.PNG)
## 4 Inventory service - get product by ID 
![Capture17](https://user-images.githubusercontent.com/97169668/207427669-3bbd8202-237e-476d-86cc-72531738830e.PNG)


## 5 Eureka Service 
```http
GET /localhost:8761/
```
![Capture21](https://user-images.githubusercontent.com/97169668/207427788-20e752a3-7a51-46da-a248-029ccfc2f794.png)


## 6 Gateway
![Capture15](https://user-images.githubusercontent.com/97169668/207427654-428a86da-2d76-4551-b08d-1fb88aa099dd.PNG)
![Capture16](https://user-images.githubusercontent.com/97169668/207427659-7bf0ea58-ba21-410e-a637-14d5f79a7a43.PNG)

![Capture20](https://user-images.githubusercontent.com/97169668/207427691-4ecdcaff-9689-44fd-9d0d-061f6c0cb22e.PNG)
![Capture21](https://user-images.githubusercontent.com/97169668/207427700-ac0e9596-3257-4ccc-a349-9b1927d01027.jpeg)
## Bills
## Show Bills  
![Capture21](https://user-images.githubusercontent.com/97169668/207427709-dd15b317-38b4-4a91-932a-0516360a582f.png)

# II. Frontend Angular Client :
![Captjijure](https://user-images.githubusercontent.com/97169668/207427818-29b7fac0-b763-4f90-906e-91c4fb30dc5f.PNG)
![Capture12](https://user-images.githubusercontent.com/97169668/207427642-d3ef4722-6bc5-4195-88e2-3633f2a1091b.PNG)
Login screen
![Capture24](https://user-images.githubusercontent.com/97169668/207427845-f5c435bf-bc62-476e-b135-4f753206d564.PNG)
## Products
## 1 Show all products 
![Capture57](https://user-images.githubusercontent.com/97169668/207427885-1badbf70-d91d-467d-aaca-41a3f776474a.PNG)
## 2 New Product
![CaptureFD](https://user-images.githubusercontent.com/97169668/207427901-ed54b0d2-e156-4d95-ac4d-12501abc11a6.PNG)
## 3 Edit products 
![Capture76](https://user-images.githubusercontent.com/97169668/207427897-7dad4eac-8d3e-4838-b31c-79bedc536263.PNG)
## 4 Delete products 
![image](https://user-images.githubusercontent.com/97169668/207487960-4adacb1b-7c0a-4cf7-9456-c9e2df6061a8.png)

## 5 Search for a product
![image](https://user-images.githubusercontent.com/97169668/207487888-c2e84b58-6717-4eee-8956-dbac4da98052.png)

## Bills
## Show Bills  
![27](https://user-images.githubusercontent.com/97169668/207427931-c9e694bf-0fd4-47bc-9bc2-866276ce35c6.png)

# III Secured Angular Client with keycloak 
Sécuriser les micro-services et le frontend angular en déployant les adaptateurs Keycloak
## 1 Setup
![Capture28](https://user-images.githubusercontent.com/97169668/207484726-9ee9ebda-054c-408f-9d86-2746e41555e0.PNG)
![Capture29](https://user-images.githubusercontent.com/97169668/207484799-4bd8da7c-f4da-4f67-b9b5-fd1447315d45.PNG)
![Capture30](https://user-images.githubusercontent.com/97169668/207484841-f888fc73-62e9-4ad3-8ddf-8350d204917d.PNG)
![image](https://user-images.githubusercontent.com/97169668/207484910-8c28722f-8ee7-430f-ac96-72f0aac3530e.png)
![image](https://user-images.githubusercontent.com/97169668/207485040-ed53cd3c-ca93-4d37-b6c1-0f2d9a4a5029.png)
![image](https://user-images.githubusercontent.com/97169668/207485203-084b830c-e24a-477a-8f72-e3884da777c1.png)
![image](https://user-images.githubusercontent.com/97169668/207485254-aa72f484-4dfc-481d-a972-2d6f1b4f0c17.png)


## 2 Postman
![image](https://user-images.githubusercontent.com/97169668/207485368-8b06a0dc-b20a-4d69-8cc6-e5fc44a4818e.png)
![image](https://user-images.githubusercontent.com/97169668/207485486-56a7e099-ad40-43ad-bc73-c008b5828548.png)


## 3 Client Auth Credentials
![image](https://user-images.githubusercontent.com/97169668/207485486-56a7e099-ad40-43ad-bc73-c008b5828548.png)

# IV KAFKA STREAM
![image](https://user-images.githubusercontent.com/97169668/219981114-f2815688-ec19-4eab-a7db-3fc4764faba0.png)
![Capturea](https://user-images.githubusercontent.com/97169668/219981355-6f776a7d-ed6c-4c2c-9657-0d74ff47af63.PNG)
![image](https://user-images.githubusercontent.com/97169668/219981771-3a513d6c-2b4a-4fb8-8c17-6c4ded88a170.png)
![image](https://user-images.githubusercontent.com/97169668/219982313-29f1133d-c14c-4bf4-848a-f8647c2f19ad.png)
![image](https://user-images.githubusercontent.com/97169668/219982285-8254ac0b-31c0-46a9-8901-2f226922c755.png)

# V DOCKER
Déployer l'ensemble des services de l'application en utilisant des conteneur Docker : 
Créer les images Docker pour chaque service 
Créer un Dockerfile pour chaque service : Un Dockerfile est un fichier de configuration qui définit les instructions pour créer une image Docker. Il contient des instructions pour copier les fichiers nécessaires, installer les dépendances et configurer le service.
( docker build ) pour construire l'image Docker
![image](https://user-images.githubusercontent.com/97169668/219982523-c5f26ffe-1e45-4910-a029-e005591fbe59.png)
![image](https://user-images.githubusercontent.com/97169668/219982607-d4b5047b-a7ef-44be-9c61-e0b31672ed88.png)
![image](https://user-images.githubusercontent.com/97169668/219982858-cc756972-162c-406d-a0ee-3533431bac2c.png)
et le fichier Docker-compose.yml qui permet de déployer toute l'application
![image](https://user-images.githubusercontent.com/97169668/219982657-2981f7ee-ff8a-4a67-8911-d7df50063099.png)

## 4 gitHub GIT
![Capturefdfd](https://user-images.githubusercontent.com/97169668/207427939-fb8293ca-672d-49a3-a415-43f809b95d6e.PNG)
![image](https://user-images.githubusercontent.com/97169668/219982903-fe225e4f-78e6-4ecc-8344-d095aaff89f8.png)

![Capturefvf](https://user-images.githubusercontent.com/97169668/207427944-128880eb-dc02-4da5-9191-241aed38435c.PNG)
### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/ayoubchawkiPRO/application-based-architecture-micro-service) for a full list of proposed features (and known issues).

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



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
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
