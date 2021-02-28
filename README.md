<!-- VARS -->

[star-badge]: https://img.shields.io/github/stars/joaomnabais/node-nps-api?logo=github
[last-commit-badge]: https://img.shields.io/github/last-commit/joaomnabais/node-nps-api
[issues-url]: https://github.com/joaomnabais/node-nps-api/issues/
[node-url]: https://nodejs.org/en
[yarn-url]: https://classic.yarnpkg.com/
[npm-url]:  https://www.npmjs.com/
[insomnia-url]:  https://insomnia.rest/
[postman-url]:  https://www.postman.com/downloads/

<!-- VARS -->

<p align="center">
  Node.js api that consists of calculating the company's NPS
</p>



<div align="center">  

![Git Stars][star-badge]
![Last Commit][last-commit-badge]


</div>


### Content
* [Getting Started](#Getting-Started-)
    * [Cloning](#Cloning)
    * [Requirements](#Requirements)
    * [Running](#Running)
* [Issues](#Issues-)
    * [Report](#Report)

### Getting Started 🚀

#### Cloning

```ps
# Create a directory in your desired location
# Clone the repository inside the directory using git
$ git clone https://github.com/joaomnabais/node-nps-api.git
```

#### Requirements
* [Node.js][node-url]
* [Yarn][yarn-url] or [npm][npm-url]

This project use third party dependencies that need to be installed, use that command to install all needed dependencies

```ps
$ yarn install
```

>The above command will install all third party dependencies used.

This project use SQlite database that need to be created before starting the project, use that command to run all the migrations needed

```ps
$ yarn typeorm migration:run
```

>The above command will execute all the migrations stored in src/database/migrations.

#### Running
If you want to run the integration tests you can use the command

```ps
$ yarn test
```

To start the project run the command

```ps
$ yarn dev
```

You can test all routes using some API client for REST like [Insomnia][insomnia-url] or [Postman][postman-url].

I left an export file from my client API workspace ([Insomnia][insomnia-url]) at the root of the project, which you can import and have access to all requests.

### Issues 🐛

#### Report

In case you are having any problem you can report in [Issues][issues-url] section.
