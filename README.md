# back_end_via_mysql
Back end for an e-commerce site by modifying starter code using Express.js API with Sequelize to interact with MySQL.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
---
## Author
  
Shawn Fox
  
  
| [GitHub](https://github.com/sfoxgit) | [Email](sfoxgit@gmail.com) |
  
---
## Project Links:
  
- Deployed site: [Heroku](https://evening-beach-41114.herokuapp.com/)
  
- GitHub: [sfoxgit](https://github.com/SFoxGit/back_end_via_mysql)
  
---
## Table of Contents
  
- [Description](##Description)
  
- [Installation](##Installation)
  
- [Usage](##Usage)
    
- [Questions](##Questions)
  
- [License](##License)
  
- [Contributions](##Contributing)
  
- [Credits](##Credits)
  
---
## Description

This is a backend database interaction using mysql and sequelizer that will allow you to update your products, categories, and tags for items being sold online. Products can have many tags, and tags can have many products as well. This uses a through to connect products and tags so we can display all the information with get requests that are set up for you with simple commands. In the usage you will see how I set them up in postman. 
  
---
## Installation

Run the schema, (copy and paste into mysql workbench or using mysql vsc extension)

![Running Schema](./assets/images/runSchema.gif)

npm seed

![Running Seed](./assets/images/runSeed.gif)
  
---
## Usage

npm start

Get Categories

![Get Categories](./assets/images/getCategories.gif)

Put Push Delete Categories

![Put Push Delete Categories](./assets/images/ppdCategories.gif)

Get Products

![Get Products](./assets/images/getProducts.gif)

Post Products

![Post Products](./assets/images/postProducts.gif)

Put Products

![Put Products](./assets/images/putProducts.gif)

Delete Products

![Delete Products](./assets/images/delProducts.gif)

Get Tags

![Get Tags](./assets/images/getTags.gif)

Post Tags

![Post Tags](./assets/images/postTags.gif)

Put Tags

![Put Tags](./assets/images/putTags.gif)

Delete Tags

![Delete Tags](./assets/images/delTag.gif)

  
---
## Questions
  
If you have any questions or concerns please contact me at sfoxgit@gmail.com or any of my contact information above. [Back to Author](##Author) 
  
--- 
 
## License 
 
https://opensource.org/licenses/MIT
  
---
## Contributing
  
If you'd like to contribute, please contact me.
  
---
## Credits
  
 Trilogy Education Services, LLC for the starter code.
  

