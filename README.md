# Very-Social-Api
A full-stack social networking platform using MongoDB.

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Built With](#built-with)
* [Walkthrough Videos](#walkthrough-videos)
* [Author](#author)
* [Questions](#questions)
* [Repository](#repository)
* [License](#license)


## Description

Very-Social-API is a an API for a social network web application where users can share their thoughts, react to friends' thoughts and create a friend list.  

You can interact with Very-Social-Api very easily using Insomnia and Compass. 

There are 3 models, Users, Friends, and Thoughts. Users have a list of Friends array and a list of Thoughts Array.  Thoughts can have reactions which are subdocuments.

In the User model, you can GET, GET <single>, PUT, POST, and DELETE.
In the Thoughts model, you can also GET, GET <single>, PUT, POST and DELETE.
In the Friends model, you can POST and DELETE.
With the Reactions, you can POST and DELETE.

Videos are below which demonstrate the functionality.



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Installation

### Download the code from the repository and run
> npm i

## Usage

Run 
>npm start

Use MongoDB Compass and Insomnia to run queries to the routes and see the results.


## Built With

* Mongoose
* MongoDB
* Express
* node.js

## Walkthrough Videos
https://watch.screencastify.com/v/3L7FO6R6chYww4cGhnJF
https://watch.screencastify.com/v/EplmTmGetcj5y3jGlqaX
https://watch.screencastify.com/v/sLI8MTvXG1aQc7scmycL
https://watch.screencastify.com/v/tdKs7va66HxcER1iXLuj

## Author

[Linda Waterhouse](https://github.com/llwaterhouse)


## Questions

If you have any questions or would like to contribute, please contact me via my Github link above.


## Repository
Click here to see the github repository https://github.com/llwaterhouse/Very-Social-Api

## License

MIT License 

Copyright (c) [2021] [MVC-Tech-Blog]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

