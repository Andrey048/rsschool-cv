# Andrey Isaev
### Junior Frontend Developer

---

### Contact information:

**E-mail:** andreas.isaew@yandex.ru<br>
**Telegram:** @Andrey_Isaev<br>

---

### Briefly About Myself:

I love programming and learning new technologies. My main strengths are problem solving and fast learning.I want to get the knowledge and skills that will be enough for employment in the company.

---

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript
- Git, GitHub
- Adobe Photoshop, Figma

---

### Code example:

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---

### Courses:

- JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) (in progress)
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

---

### Languages:

- English \- Pre-intermediate
- Russian \- Basic
