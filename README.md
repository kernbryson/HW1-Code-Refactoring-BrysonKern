# Code Refactoring - Bryson Kern

## Description

This project challenged the developer to refactor the existing code in order to meet semantic standards. While also making the website semantic; the developer also needed to clean up reduntant code and add any necessary notes reguarding what the code does and how they fixed the code.

- The motivation behind this activity was to enhance the existing website to meet accessibilty standards as well as cleaning up the code.
- I completed this activity to make the website more user friendly.
- Users that have vision disabilities are now able to have a better grasp about the content on the website.
- During this activity I learned through trial and error on how to conjoin exisiting css to consolidate code. I also learned the proper semantic tags to use in html.

## Table of Contents (Optional)

- [semantics](#Semantics)
- [Code Consolidation](#CodeConsolidation)
- [Credits](#credits)
- [License](#license)

## Semantics

In order to make the website semantic many elements needed to be replaced. I first started by removing all the div tags and replacing them with semantic tags like nav, article, section, and footer. I then began to make sure all elements were in order to assure that the contents would make sense to a user with a visual disablility. While solidifying the code I also found that many header tags were out of order. This inturn would read the text to the user in an incorrect manor. In order to fix this I simply rearranged the header tags to fit the style of the website along with deleting the unnecessary ones.

## CodeConsolidation

Through out this website many lines of code had reduntant classes. Many items that had the same css were split into different classes.
In order to fix this, I combined all of the classes into one while also changing the class name to something that encompassed all of the elements it affected. Additionaly, all of the img tags did not have alt attributes which are crutial for audio readers to communicate what the image is.

[old css classes](assets/images/oldcss.png)
[new css classes](assets/images/newcss.png)

## Credits

W3schhools-https://www.w3schools.com/
Web Dev Simplified-https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw

## License

Copyright (c) [2022] [BrysonKern]

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
