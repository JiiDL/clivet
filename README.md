
<a name="readme-top"></a>





<!-- PROJECT LOGO -->
<br />


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
    <li><a href="#rest-api">REST API</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project

A veterinarian clinic application is a software tool that allows veterinarians and other medical professionals to manage and track the healthcare of pets. The application typically includes features for adding and storing information about pets, scheduling and recording visits, and managing user accounts. The application is written in Java and React JS. SpringBoot and Hibernate were used to create the application.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Spring][SpringBoot]][Spring-url]
* [![Hibernate][HibernateSite]][Hibernate-url]
* [![Java][JavaSite]][Java-url]
* [![HTML][HTMLSite]][HTML-url]
* [![CSS][CSSSite]][CSS-url]
* [![React][ReactSite]][React-url]
* [![MySQL][MysqlSite]][Mysql-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->


## Getting Started

### Prerequisites

To run app locally:

* Database setup
  ```
  Set your default db user and db password in application.properties or environment variables.
  ```

* Default server port
    ```
  server.port = 8080
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/minvoo/clivet.git (Backend)
   git clone https://github.com/minvoo/clivet-front.git (Frontend)
   ```

2. Run backend server on port 8080. Navigate to frontend folder and start the server. Install missing dependencies.
```
npm start
npm i [missing-dependency-name]
```

<!-- USAGE EXAMPLES -->
<img src="https://github.com/minvoo/clivet/blob/master/src/main/java/com/teamone/clivet/readme_files/demo-clivet-2.png"> </img>
<br/>
## Usage

Users can:
* Login or register
* Check own profile info
* Check own pets info
* Check all appointments of specific pet

* Administrator can:
* Edit user data
* Add pets
* Add appointments
* Edit pet data
* Delete pets
* Delete appointments
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## REST-API

You can check all API endpoint in controller classes.

## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also
simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>






[contributors-shield]: https://img.shields.io/github/contributors/minvoo/clivet.svg?style=for-the-badge

[contributors-url]: https://github.com/minvoo/clivet/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/minvoo/clivet.svg?style=for-the-badge

[forks-url]: https://github.com/minvoo/clivet/network/members

[stars-shield]: https://img.shields.io/github/stars/minvoo/clivet.svg?style=for-the-badge

[stars-url]: https://github.com/minvoo/clivet/stargazers

[issues-shield]: https://img.shields.io/github/issues/minvoo/clivet.svg?style=for-the-badge

[issues-url]: https://github.com/minvoo/clivet/issues

[license-shield]: https://img.shields.io/github/license/minvoo/clivet.svg?style=for-the-badge

[license-url]: https://github.com/minvoo/clivet/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[linkedin-url]: https://linkedin.com/in/minvoo

[Spring-url]: https://spring.io/projects/spring-boot

[SpringBoot]: https://img.shields.io/badge/SPRINGBOOT-6db33f?style=for-the-badge&logo=spring&logoColor=white

[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white

[Bootstrap-url]: https://getbootstrap.com

[JavaSite]: https://img.shields.io/badge/JAVA-%23ED8B00?style=for-the-badge&logo=java&logoColor=white

[Java-url]: https://www.oracle.com/java/

[HTMLSite]: https://img.shields.io/badge/html-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white

[HTML-url]: https://www.w3schools.com/html/

[HibernateSite]: https://img.shields.io/badge/hibernate-bcae79.svg?style=for-the-badge&logo=hibernate&logoColor=white

[Hibernate-url]: https://hibernate.org/

[CSSSite]: https://img.shields.io/badge/css-2862e9.svg?style=for-the-badge&logo=css3&logoColor=white

[CSS-url]: https://www.w3schools.com/css/default.asp

[ReactSite]: https://img.shields.io/badge/react-6cc2ff.svg?style=for-the-badge&logo=react&logoColor=white

[React-url]: https://reactjs.org

[MysqlSite]: https://img.shields.io/badge/mysql-3e6e93.svg?style=for-the-badge&logo=mysql&logoColor=white

[Mysql-url]: https://www.mysql.com
