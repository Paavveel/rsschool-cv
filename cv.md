# Pavel Tomilin

## Contacts

- **Phone:** +7 916 9179195
- **E-mail:** pa.tomilin@gmail.com
- **Telegram:** [@patomilin](https://t.me/patomilin)
- [GitHub](https://github.com/Paavveel)
- [LinkedIn](https://www.linkedin.com/in/pavel-tomilin/)
- [Codewars](https://www.codewars.com/users/Paavveel)

## **About Me**

I started my career as a system administrator, worked for 7 years. Then I decided to study frontend development. I am interested in web development because this profession provides endless opportunities for professional growth.
I took various courses, read documentations, watched lectures and training materials, coded some pet projects. After I got into a small team that develops an educational website, I continued to study and apply the knowledge gained in practice. I try to be on the wave of my stack, open to learning new technologies, I like to write high-quality, testable code. I want to implement my skills in a difficult, high load project, to be part of a team that develops business and makes a product useful to people.

## **Skills**

- JavaScript (ES6+)
- TypeScript (Basic)
- React JS, Redux
- HTML5, CSS3
- Git, GitHub
- Figma

## **Code Example**

**Valid Braces KATA from CODEWARS:**
_Write a function that takes a string of braces, and determines if the order of the braces is valid. It should return true if the string is valid, and false if it's invalid._

```javascript
function validBraces(braces) {
  const map = {
    '(': ')',
    '{': '}',
    '[': ']',
  };
  const openBraces = Object.keys(map);
  const openBracketsStack = [];

  for (const b of braces) {
    if (openBraces.includes(b)) {
      openBracketsStack.push(b);
      continue;
    }

    if (map[openBracketsStack.pop()] !== b) {
      return false;
    }
  }

  return openBracketsStack.length === 0;
}
```

## **Experience**

Some of my pet projects: [GitHub](https://github.com/Paavveel/hacker-news)

## **Courses**

- **HTML Academy**

  - [Profession Front-end Developer](https://assets.htmlacademy.ru/certificates/profession/15/1295561.pdf)
  - [JavaScript. Professional Development of Web Interfaces](https://assets.htmlacademy.ru/certificates/intensive/173/1295561.pdf)
  - [HTML & CSS. Adeptive Website Coding and Automation](https://assets.htmlacademy.ru/certificates/intensive/161/1295561.pdf)
  - [HTML & CSS. Professional Website Coding](https://assets.htmlacademy.ru/certificates/intensive/159/1295561.pdf)

- **Udemy**

  - [JavaScript, React JS](https://www.udemy.com/course/javascript_full/)
  - [React JS](https://www.udemy.com/course/react-from-scratch/)
  - [Docker](https://www.udemy.com/course/docker-ru/)

- **RS School - JavaScript/Front-end 2023Q1** (in progress)

## **Languages**

- **Russian** - Native
- **English** - B1 (B2 in progress)
