# Andrew Kostukevich
### Frontend Developer

***
## Contacts
* **Email**: dexs.kostukevi4@yandex.by
* **Phone**: +375 29 546-84-67
* **Telegram**: [@solumzy](https://t.me/solumzy)
* **Github**: [solum-the-creator](https://github.com/solum-the-creator)

***

## Profile
My main goal is to become a good frontend developer. I like to find solutions to interesting and complex problems. I like to learn and learn new things in all areas of life.
### Personal Skills
* Fast learner
* Honest
* Curios
* Responsible
* Punctual


***

## Skills
* JavaScript (Vanilla, OOP, ES6, DOM etc.)
* HTML
* CSS/SCSS
* PHP (Frameworks Laravel and Yii)
* Git
* Figma, Photoshop, Illustrator
* C# (basic knowledge)
* Editors (VSCode, SublimeText, WebStorm, Visual Studio)

***

## Code Example
Given a string **s**, find the length of the longest substring without repeating characters.
```
const lengthOfLongestSubstring = function(s) {
    let curString = "";
    let res = 0;
    for(let i=0;i<s.length;i++){
        let curIndex = curString.indexOf(s[i]);
        if(curIndex !== -1 ){
            curString = curString.slice(curIndex+1);
        }
        curString+=s[i];
        res=res<curString.length?curString.length:res;
    }
    return res;
};
```

***

## Work experience
Work on a graduation project at the university, which is a website for the national park, with the ability to make hotel reservations, buy tickets, and view and create itineraries around the park. The project was created using the Laravel framework. JavaScript, CSS and HTML were also used. The database used was MySql. [A link](https://github.com/solum-the-creator/Travel-Website-laravel) to the project's github.
In addition to this project, many other projects were completed during the course of the training.
***
## Education
* Belarusian State Technological University
  + Information technology department
* [The Odin Project](https://www.theodinproject.com) self-study course
* [FreeCodeCamp](https://www.freecodecamp.org/)


***

## Languages
* **Russian** - Native
* **Belarusian** - Upper-intermediate
* **English** - Pre-intermediate


***
