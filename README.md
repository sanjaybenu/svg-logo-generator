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

<img width="636" alt="npminstall" src="https://user-images.githubusercontent.com/105487471/234521485-2e850d15-4f3f-4b76-a280-3e304c6cc38e.png">


If you do not find the package.json file, please run the following commands on your terminal.

<img width="583" alt="npminit" src="https://user-images.githubusercontent.com/105487471/234521809-cb5ed9ae-d800-4285-9a6b-8467817ee79d.png">

<img width="591" alt="inquirer" src="https://user-images.githubusercontent.com/105487471/234521854-65ec694b-3acd-4a9a-b13b-04d7b5b0ef64.png">


After you have run this command, package-lock.json file and node modules folder will be created.

<img width="190" alt="packagelock" src="https://user-images.githubusercontent.com/105487471/234522159-e72b7e1c-110b-4184-aaee-dc3895399741.png">

Now you can run the following command.

<img width="595" alt="runcommand" src="https://user-images.githubusercontent.com/105487471/234522893-541b0c27-b3ee-424b-bec7-8d683f8c295e.png">

You will be asked a few questions about logo you want to generate.

<img width="913" alt="questions" src="https://user-images.githubusercontent.com/105487471/234523173-aea2054e-aca2-44f7-99a1-63e2bc797b73.png">

Once all questions have been answered the code for the logo will be generated and will be written to the logo.svg file in the output folder, a sub-folder of folder main.

<img width="360" alt="output" src="https://user-images.githubusercontent.com/105487471/234523834-8c5c910e-0641-485f-9988-b8dafe5cf6d1.png">

<img width="575" alt="svgfile" src="https://user-images.githubusercontent.com/105487471/234523903-96e9e012-1995-42c6-8be4-12f2f062a54b.png">

<img width="428" alt="rendered" src="https://user-images.githubusercontent.com/105487471/234523948-0a614408-4d8b-449f-882a-4c4507f3b4a2.png">


## Usage
Please refer to section above for the usage.

You can also refer to the following video for a demonstration of the project.

Feel free to modify questions.js and shapes.js to suit your requirement.

You may modify tests to represent changes desired in the code. 

https://youtu.be/m9oC3wo6JW4

## Tests
Jest should already be downloaded. Please check package.json file. If you do not find jest under development dependancies please download jest from npm using the following command.

<img width="526" alt="jestdev" src="https://user-images.githubusercontent.com/105487471/234524727-8198ec0c-87a4-4160-8cea-9ba4a9fb33f9.png">

Once downloaded successfully, open package.json file and you will find jest listed under the development dependency. 

Go to the script section and ensure jest is written under scripts, against test, if not please add it to the script.

<img width="313" alt="jestinpackagejson" src="https://user-images.githubusercontent.com/105487471/234524373-92037b3c-840e-4019-bd7c-b8548f7eabd0.png">

Run the test using the following command

<img width="583" alt="running test" src="https://user-images.githubusercontent.com/105487471/234525100-ebb8a3de-0e25-4a22-bbef-f060a03f1aab.png">

if the test runs successfully the following will be shown in the terminal.

<img width="564" alt="testpassed" src="https://user-images.githubusercontent.com/105487471/234525363-8a30f6b8-2ddc-48fb-ba32-f7e7753013ef.png">

## Contribute
This is an open-source project and you are welcome to add features to the project. Please feel free to create a pull request. You may also contact me via link in the questions section for any ideas/concerns you would like to share.
## Contributors

I would like acknowledge my tutors Jack Song and Sid Baral of Monash University Coding Camp to teach the concepts that have helped in creating this project.

## License
This project is created under MIT license.

Users of software using an MIT License are permitted to use, copy, modify, merge publish, distribute, sublicense and sell copies of the software


## Questions
If you have any questions or suggestions please [contact](mailto:sanjaybenu@gmail.com?subject=README_file_generator) or visit [github/sanjaybenu](https://github.com/sanjaybenu)
