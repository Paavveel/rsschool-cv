# Pavel Tomilin

## Contacts

- **Phone:** +7 916 9179195
- **E-mail:** pa.tomilin@gmail.com
- **Telegram:** [@patomilin](https://t.me/patomilin)
- [GitHub](https://github.com/Paavveel)
- [LinkedIn](https://www.linkedin.com/in/pavel-tomilin/)
- [Codewars](https://www.codewars.com/users/Paavveel)

## **About Me**

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

## **Courses**

## **Languages**
