<a id="readme-top"></a>


<div align="center">
  <a href="https://github.com/Jason897571/Raccoon-E-commerce-Back-End">
    <img src="./public/image/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Raccoon E-commerce Back End</h3>

  <p align="center">
    This is a back end for an Ecommerce website to search, create, update and delete data regarding categories, products and tags <br />With Help of this project, you would easily search, create, update and delete relative data from your database
    <br />
    <a href="https://github.com/Jason897571/Raccoon-E-commerce-Back-End"><strong>Click here for Github Repo  »</strong></a>
    <br />
    <br />
    <a href="https://drive.google.com/file/d/10hdOsKll_u83wpzZ_T_ifShay4kZYw9_/view?usp=sharing">Walk-Through Video</a>
    ·
    <a href="https://github.com/Jason897571/Raccoon-E-commerce-Back-End/issues">Report Bug</a>
    ·
    <a href="https://github.com/Jason897571/Raccoon-E-commerce-Back-End/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Navigation of Contents</summary>
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
    <li><a href="#contact">Contact</a></li>
    <li><a href="#future_additions">Future Additions</a></li>
    <li><a href="#reference">Reference</a></li>
  </ol>
</details>

<a id="#about-the-project"></a>
## About The Project

<p><strong>Start Page</strong></p>


![alt text](./public/image/start.png)

<br />

This is the start page when you download the project.




<a id="#built-with"></a>
## Built with
This generator is made with Javascript.

* ![Alt text](./public/image/javascript.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="getting_started"></a>
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

<a id="prerequisities"></a>
### Prerequisites

You should have your shell ready for downloading this project. We use gitbash as an example in this project

<a id="installation"></a>
### Installation
1. Get a free API Key at [github](https://github.com/Jason897571/Raccoon-E-commerce-Back-End#built-with)
2. Clone the repo
   ```sh
   git clone https://github.com/Jason897571/Raccoon-E-commerce-Back-End.git
   ```
3. Open the project using vs code and open your mysql terminal to import `source db/schemal.sql` and input `node seeds/seed.js` in your bash terminal. Then you will see three tables in your database.

4. In your terminal, input `npm start` to start the server.





<p align="right">(<a href="#readme-top">back to top</a>)</p>


<a id="usage"></a>
## Usage

When you input `npm start` In your terminal to start the server, you could send request to server to search, create, update or delete data.


### Get All Info

You could use insomnia to send <strong>GET</strong> request to `http://localhost:3000/api/products` to get all products information.

try `http://localhost:3000/api/categories` to see categories information

try `http://localhost:3000/api/tags` to see tags information

![alt text](./public/image/get_all_product.png)

### Get Single Info

You could use insomnia to send <strong>GET</strong> request to `http://localhost:3000/api/products/1` to get the product information with id `1`.

try `http://localhost:3000/api/categories/1` to see categories information with id `1`

try `http://localhost:3000/api/tags/1` to see tags information with id `1`

![alt text](./public/image/get_single_info.png)


### Create Info

You could use insomnia to send <strong>POST</strong> request to `http://localhost:3000/api/products/1` to crate the product information with body info show below.

try `http://localhost:3000/api/categories/1` to create categories information

try `http://localhost:3000/api/tags/1` to create tags information

![alt text](./public/image/create.png)

### Update Info

You could use insomnia to send <strong>PUT</strong> request to `http://localhost:3000/api/products/1` to update the product information with body info show below.

try `http://localhost:3000/api/categories/1` to update categories information

try `http://localhost:3000/api/tags/1` to update tags information

![alt text](./public/image/update.png)

### Delete Info

You could use insomnia to send <strong>DELETE</strong> request to `http://localhost:3000/api/products/6` to delete the product information with id `6`.

try `http://localhost:3000/api/categories/6` to delete categories information with id `6`

try `http://localhost:3000/api/tags/6` to delete tags information with id `6`

![alt text](./public/image/delete.png)




For more details, please refer to the [Documentation](https://github.com/Jason897571/Raccoon-E-commerce-Back-End) or [Video](https://drive.google.com/file/d/1M-gGJv8WTPyUfoR1LIr6bXMF6Er_WBt6/view?usp=sharing)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<a id="future_additions"></a>
## Future Additions
* Create front end to reflect back end data



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<a id="contact"></a>
## Contact

Jason Gu - [Email](king.gs1314@outlook.com) - king.gs1314@outlook.com

Project Link: [https://github.com/Jason897571/Raccoon-E-commerce-Back-End](https://github.com/Jason897571/Raccoon-E-commerce-Back-End)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="reference"></a>
## Reference
* Xpert Assistant/ChatGPT
* https://dev.to/envoy_/150-badges-for-github-pnk#games
* https://github.com/othneildrew/Best-README-Template


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Javascript-url]:https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
