# SVG Logo Generator
![Github license](https://img.shields.io/badge/license-MIT-blue)
## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Contribute](#contribute)
* [Contributors](#contributors)
* [Testing](#tests)
* [License](#license)
* [Questions](#questions)
## Description
This app is to help professional developers design a logo on the for their projects.
This app allows the developer to choose shape of the logo, the text within logo and its colour. Developers can also choose the size background colour, border colour and thickness.


## Screenshots

<img width="632" alt="main" src="https://user-images.githubusercontent.com/105487471/234520573-3f783e05-3b18-4dca-96af-e80b05e9a3b0.png">

## Installation
Go to the github repository and clone the project into a local directory at your computer.

https://github.com/sanjaybenu/svg-logo-generator

Before you can start using the app, please ensure you have package.json in your folder. 

<img width="263" alt="packagejson" src="https://user-images.githubusercontent.com/105487471/234521112-aa43b681-c2c5-4a7f-aab1-4c5e8a3fdaa8.png">

Now run the following command in terminal to install dependencies you need for the project.

npminstall.png


If you do not find the package.json file, please run the following commands on your terminal.

npminit.png
inquirer.png


After you have run this command, package-lock.json file and node modules folder will be created.

packagelock.png

Now you can run the following command.

<img width="655" alt="Screenshot6" src="https://user-images.githubusercontent.com/105487471/233835428-fe008623-b7a1-4ef0-b06c-775e7a9f84e5.png">

You will be asked a few questions about logo you want to generate.

<img width="729" alt="Screenshot7" src="https://user-images.githubusercontent.com/105487471/233835451-7709df8d-ddc3-4109-807c-2f7edce199c5.png">

Once all questions have been answered the code for the logo will be generated and will be written to the logo.svg file in the output folder, a sub-folder of folder main.

output.png
rendered.png

## Usage
Please refer to section above for the usage.

You can also refer to the following video for a demonstration of the project.

Feel free to modify questions.js and shapes.js to suit your requirement.

You may modify tests to represent changes desired in the code. 

youtube link

## Tests
Jest should already be downloaded. Please check package.json file. If you do not find jest under development dependancies please download jest from npm using the following command.

jestdev.png

Once downloaded successfully, open package.json file and you will find jest listed under the development dependency. 

Go to the script section and ensure jest is written under scripts, against test, if not please add it to the script.

jestinpackagejson.png

Run the test using the following command

runningtest.png

if the test runs successfully the following will be shown in the terminal.

testpassed.png

## Contribute
This is an open-source project and you are welcome to add features to the project. Please feel free to create a pull request. You may also contact me via link in the questions section for any ideas/concerns you would like to share.
## Contributors

I would like acknowledge my tutors Jack Song and Sid Baral of Monash University Coding Camp to teach the concepts that have helped in creating this project.

## License
This project is created under MIT license.

Users of software using an MIT License are permitted to use, copy, modify, merge publish, distribute, sublicense and sell copies of the software


## Questions
If you have any questions or suggestions please [contact](mailto:sanjaybenu@gmail.com?subject=README_file_generator) or visit [github/sanjaybenu](https://github.com/sanjaybenu)