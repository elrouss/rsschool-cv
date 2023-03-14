# Curriculum Vitae

## Boris Zashliapin
Frontend Developer

![Фотография автора CV](./images/photo.png)

## Contacts
**Location:** St Petersburg, Russia

**Email:** test-zashliapin-b@yandex.ru

**Telegram:** [@elrouss](https://t.me/elrouss)

**Github:** https://github.com/elrouss

**LinkedIn:** https://www.linkedin.com/in/frontend-elrouss/

## About Me
Having studying art history for 10 years I have become a professional in this sphere, who can attribute pieces of art of different epoques. I am a curator of an exhibition "Alexander Nevsky" (2021) and the author of 8 scientific articles.

One year ago my school interest in programming has become passionate and having tried different areas (backend, testing) I have finally decided to become a frontend developer. Due to my trained eye it is easier to me working with the computer screen, but it does not detract at all from working with `console.log()` and writing a programm with `TypeScript` or `JavaScript`.

I am interested in Web Development because this sphere developes dynamicallyy and provides an endless possibility for professional growth (which has stopped in the museum),
besides there is a huge amount of free high quality resources for self-education and a large community of professional developers. 

I believe, that my ability to quick learning and to gaining new skills will help me in becoming a proficient frontend developer.

## Employment History
**Researcher, State Hermitage Museum**

*Mar 2018 - Present*

Hermitage Museum is one of the world's greatest museum of art with collections unrivalled in their scope and diversity. As a researcher and a curator of silver in the Russian Department, my core activities include:

* Art expertise and attribution
* Writing scientific research articles
* Conceiving and organizing exhibitions

## Skills
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
There are 

## Education
### Courses
- [RS School](https://rs.school/) (Mar, 2023 - present)
  - JavaScript/Front-end (Stage no. 1)
- [Yandex Praktikum](https://practicum.yandex.ru/) (Jul, 2022 - present)
  - Web Developer

### University
- [St Peterburg State University](https://english.spbu.ru/)
  - History of Arts, 2016-2018 (MA)
  - History of Arts, 2012-2016 (BA)

## Languages
* Russian (native)
* English (B2)
* German (B1)
* French (A1)