# Team Profile Generator

## Description
As a developer an created an application that easy generates a html file for a project. The html will be generated from the node command line interface for a team manager that wants to put together a software engineering team. The application will prompt the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user. 
This application will also pass all unit tests when the user runs `npm run test`.

## Screenshot 
<img src ="screenshot.png" width="500">

## Link to deployed app
https://github.com/eradicador/Team-Profile-Generator

## Link to app video walkthrough
https://drive.google.com/file/d/11OeFgU1hjMHxc3Gl5RUqD3w60WDyXIYD/view

## app.js
lines 1 to 10 constants to require values for the functions

lines 10 to 58 manager questions

lines 60 to 66 function to create a manager

lines 68 to 79 function call to create a new employee

lines 81 to 192 created switch statements for engineer and intern questions
line 194 this function writes text to team.html file

lines 200 to 205 function to write team.html file

lines 207 to 209 function to initialize program

line 211 function call to initialize program

## css
line 2 added teal background color to jumbotron

line 6 added white color text to h1 

line 10 added blue background color to card header 

line 14 added white color text to car title 

## Badge
![GitHub license](https://img.shields.io/badge/license-MIT-brightgreen)

## License

MIT License

Copyright (c) [2020] [Michael Amaya]

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

## Contributing
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)