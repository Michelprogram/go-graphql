<div id="top"></div>



<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="img/logo.png" alt="Logo" width="80" height="80">

<h3 align="center">What is graphql ?</h3>

  <p align="center">Learn about the basics of Graphql.</p>
</div>

 <br />  

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">🧭 About The Project</a>
      <ul>
        <li><a href="#built-with">🏗️ Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">📋 Getting Started</a>
      <ul>
        <li><a href="#prerequisites">🗺️ Prerequisites</a></li>
        <li><a href="#installation">⚙️ Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">💾 Usage</a></li>
    <li><a href="#contributing">🔗 Contributing</a></li>
    <li><a href="#license">📰 License</a></li>
    <li><a href="#contact">📫 Contact</a></li>
    <li><a href="#acknowledgments">⛱️ Acknowledgments</a></li>
  </ol>
</details>

<br>



<!-- ABOUT THE PROJECT -->
## 🧭 About The Project

### 🏗️ Built With

List of technologies / frameworks used during the project.

* [Go](https://golang.org/)
* [Docker](https://www.docker.com/)
* [Mysql](https://www.mysql.com/)

<p align="right"><a href="#top">⬆️</a></p>




<!-- GETTING STARTED -->
## 📋 Getting Started

The concept of this project is to learn about graphql before doing a bigger project and understand the basics of Query and Mutation.

Based on this tutorial: https://www.howtographql.com/graphql-go/0-introduction/

### 🗺️ Prerequisites

You need go and docker installed on your machine.

Run a mysql instance with the following command :

```sh
docker run -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=dbpass -e MYSQL_DATABASE=hackernews -d mysql:latest
```

Then create the database using this commands:
    
```sh
docker exec -it mysql bash
```

It will open the bash terminal inside mysql instance.

In the next step we will open mysql repl as the root user:
```sh
mysql -u root -p
```

It will ask you for root password, enter dbpass and enter.

Now we are inside mysql repl. To create the database, run this command:
````sh
CREATE DATABASE hackernews;
````

<p align="right"><a href="#top">⬆️</a></p>


<!-- USAGE EXAMPLES -->
## 💾 Usage

Run the app with the following command :

```sh
go run server.go
```

<p align="right"><a href="#top">⬆️</a></p>


<!-- CONTRIBUTING -->
## 🔗 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right"><a href="#top">⬆️</a></p>




<!-- LICENSE -->
## 📰 License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right"><a href="#top">⬆️</a></p>




<!-- CONTACT -->
## 📫 Contact

Reach me at : gauron.dorian.pro@gmail.com.

Project Link: [https://github.com/Michelprogram/magic-scanner.git](https://github.com/Michelprogram/magic-scanner.git)

<p align="right"><a href="#top">⬆️</a></p>




<!-- ACKNOWLEDGMENTS -->
## ⛱️ Acknowledgments

This space is a list to resources i found helpful and would like to give credit to.

* Scryfall https://scryfall.com/docs/api/cards/search
* Shadcn https://ui.shadcn.com/docs/installation

<p align="right"><a href="#top">⬆️</a></p>

<a href="https://github.com/othneildrew/Best-README-Template">Template inspired by othneildrew</a>
