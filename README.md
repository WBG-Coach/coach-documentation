<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://avatars.githubusercontent.com/u/105060288?s=400&u=f87d168238dae0200943f1711c51d7be151b5919&v=4" alt="Project logo"></a>
</p>

<h3 align="center">Coach Digital</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)](https://github.com/WBG-Coach) 
   [![License](https://img.shields.io/badge/license-TBD-blue.svg)](/LICENSE)

</div>

---

<p align="center"> An online teacher coaching tool, developed by the World Bank Group.
    <br> 
</p>

## Table of Contents

**Detailed guides for users:**

- [Guide for coaches](./Coaches.md)
- [Guide for teachers](./Teachers.md)
- [Guide for mangers](./Managers.md)

---

**For system administrators:**

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## About <a name = "about"></a>
The World Bank Group’s (WBG) Global Education Practice developed *Coach*, which aims to accelerate student learning by improving in-service teacher professional development. *Coach* encompasses support to countries through one-to-one coaching, group training sessions and workshops, and other approaches, either through in-person, remote or hybrid modalities—with the goal of increasing the quality of teacher-student interactions, key to improving student learning outcomes. For *Coach* to benefit a global community of teachers and to served teacher at a scale (at a lower cost while maximizing its impact) requires a strategic integration of digital technologies. This ***Coach Digital*** product provides a flexible approach for implementing the *Coach* method across various country contexts.

## Getting Started <a name = "getting_started"></a>
Coach Digital is comprised of three components: backend, frontend, and administrative backend. These instructions are designed for system administrators and will get you a copy of the project up and running on your local machine for development and testing purposes or for deployment. See [deployment](#deployment) for extra considerations on how to deploy the project on a live system.

### Prerequisites
 Coach Digital is built to run on PHP 7.4, Composer, MariaDB (MySQL), and Nginx. On Debian 11, these packages may be installed with the command:

```
sudo apt update && sudo apt install composer nginx php-fpm mariadb-server 
```

### Installing
Installation instructions go here

```
list commands needed 
```

And repeat

```
until finished
```

If running uwf or another firewall, ensure ports 80/tcp and 443/tcp are open. Enabling SSL encryption is required. This can be done after nginx is initially configured by installing [Let's Encrypt](https://letsencrypt.org) and running certbot, following SSL certificate installation instructions:

```
sudo apt install certbot

certbot
```


End with an example of getting some data out of the system or using it for a little demo.

## Maintaining the system <a name = "maintenance"></a>
Explain how to run any automated tasks or regular maintenance for this system.

### Break down into end to end tasks
Explain what these tasks are and why ... `show command/code examples`

## Usage <a name="usage"></a>
Add notes about how to use the system.

## Deployment <a name = "deployment"></a>
Add additional notes about how to deploy this on a live system.

## Built Using <a name = "built_using"></a>
- [Laravel](https://laravel.com) - PHP framework for the backend

## Authors <a name = "authors"></a>
- [@educationfutures](https://github.com/educationfutures) - Product concept, design, & QA
- [@msoledade](https://github.com/msoledade) - Sprint manager, development integrator
- [@jmoreirafilho](https://github.com/jmoreirafilho) - Backend developer
- [@janderson-souza](https://github.com/janderson-souza) - Frontend developer
- TBD - UI/UX design


## Acknowledgements <a name = "acknowledgement"></a>
Thank you to everybody who provided inspiration and helped provide feedback for this product, espcially:
- World Bank Group Coach team
- Ministry of Education, Mozambique