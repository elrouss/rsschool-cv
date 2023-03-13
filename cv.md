# Curriculum Vitae

## Boris Zashliapin
### Frontend-developer

## Contacts
**Location:** St Petersburg, Russia

**Email:** test-zashliapin-b@yandex.ru

**Telegram:** @elrouss

**Github:** https://github.com/elrouss

## About
Add text

## Hard Skills
### Frontend: 
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![SASS](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
### Backend:
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Node JS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
### General:
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white)
![Babel](https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)

## Code example
**Permute a Palindrome:** *Write a function that will check whether ANY permutation of the characters of the input string is a palindrome*

````
function permuteAPalindrome(input) { 
  const obj = {};
  
  for (let char in input) {
    obj[input[char]] ? obj[input[char]] += 1 : obj[input[char]] = 1;
  }
  
  let counter = 0;
  Object.values(obj).forEach(num => {
    if (num % 2 !== 0) counter++;
  })
  
  return counter <= 1;
}
````
*([Codewars](https://www.codewars.com/kata/reviews/58aead37c51d22295a000053/groups/63f00c43b6f14400017e3853), 6kyu)*

## Experience
Add text

## Education
### Courses (Frontend-developer)
#### RS School (Mar, 2023 - present)
#### Yandex Praktikum (Jul, 2022 - present)

### University
#### St Peterburg State University (MA, history of arts, 2016-2018)
#### St Peterburg State University (BA, history of arts, 2012-2016)

## Languages
* Russian (native)
* English (B2)
* German (B1)
* French (A1)