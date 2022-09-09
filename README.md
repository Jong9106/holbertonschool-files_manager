# 0x15. Files manager

-   By:  Guillaume, CTO at Holberton School
-   Weight:  1
-   Project to be done in teams of  2  people  (your team:  Juan Carlos Hernández Ríos, Andres Sotelo Duran)
-   Project will start  Aug 29, 2022 12:00 AM, must end by  Sep 9, 2022 12:00 AM
-   was  released at  Sep 3, 2022 12:00 PM
-   **Manual QA review must be done**  (request it when you are done with the project)
-   An auto review will be launched at the deadline

This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files:

-   User authentication via a token
-   List all files
-   Upload a new file
-   Change permission of a file
-   View a file
-   Generate thumbnails for images

You will be guided step by step for building it, but you have some freedoms of implementation, split in more files etc… (`utils`  folder will be your friend)

Of course, this kind of service already exists in the real life - it’s a learning purpose to assemble each piece and build a full product.

Enjoy!

## Resources

**Read or watch**:

-   [Node JS getting started](https://intranet.hbtn.io/rltoken/J_U3SM5CYCUEN1brjOYchg "Node JS getting started")
-   [Process API doc](https://intranet.hbtn.io/rltoken/nP0R4BowbhpL4f8EqRp_fg "Process API doc")
-   [Express getting started](https://intranet.hbtn.io/rltoken/0Na8JRLrAhDKV-wHixwV0A "Express getting started")
-   [Mocha documentation](https://intranet.hbtn.io/rltoken/GmYXjUgsy9U1vyaJEBgxKg "Mocha documentation")
-   [Nodemon documentation](https://intranet.hbtn.io/rltoken/b04g3H0SE9X2qQa8p9apEg "Nodemon documentation")
-   [MongoDB](https://intranet.hbtn.io/rltoken/EH7qVDpUEXcKfvWt8cMwnQ "MongoDB")
-   [Bull](https://intranet.hbtn.io/rltoken/w3LMsDeIqzOxQyn9mFq5Yw "Bull")
-   [Image thumbnail](https://intranet.hbtn.io/rltoken/e7qYbmNo0KnILM0SEbBt5g "Image thumbnail")
-   [Mime-Types](https://intranet.hbtn.io/rltoken/cr22bbwXIxvXoSokT6IigA "Mime-Types")
-   [Redis](https://intranet.hbtn.io/rltoken/cC7OJWzv6-4-BeQhEki04g "Redis")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/5yAT8wL9g3JvNT5jhk63-A "explain to anyone"),  **without the help of Google**:

-   how to create an API with Express
-   how to authenticate a user
-   how to store data in MongoDB
-   how to store temporary data in Redis
-   how to setup and use a background worker

## Requirements

-   Allowed editors:  `vi`,  `vim`,  `emacs`,  `Visual Studio Code`
-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using  `node`  (version 12.x.x)
-   All your files should end with a new line
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `js`  extension
-   Your code will be verified against lint using ESLint

## Provided files

### `package.json`

Click to show/hide file contents

### `.eslintrc.js`

Click to show/hide file contents

### `babel.config.js`

Click to show/hide file contents

### and…

Don’t forget to run  `$ npm install`  when you have the  `package.json`