# Daryna Belichenko

## Junior Frontend Developer

## Contact information:

- email address: de.em.aa.frontend@gmail.com
- github: https://github.com/Dmasbs
- Telephone number: +3(096)851-30-88
- discord: Daryna Belichenko (@Dmasbs)

## About Myself:

Hello, I want to become a full stack developer.I always liked to solve equations and problems of different complexity. I am a person who is constantly developing and I like learning something new, which is native to my personality.

This year, I’ve become interested in the IT field and I’ve realised that it will be my future profession, because progress does not stand still and this field is developing rapidly. I have already tried myself in this profession on a mini course, and I can say with confidence that I want to complete the course. :)

## Skills:

- HTML5(CSS3)
  - Sass
  - Flex
  - adaptive
- JavaScript(basic)
  ***

## Soft Skills:

- Agile
- Teamwork

## Code example:

> For this kata you will have to forget how to add two numbers. In simple terms, our method does not like the principle of carrying over numbers and just writes down every number it calculates.
> You may assume both integers are positive integers.

```
function add(num1, num2) {
  const arr1 = num1.toString().split('').reverse();
  const arr2 = num2.toString().split('').reverse();
  const result = [];

  const length = arr1.length > arr2.length ? arr1.length : arr2.length;
  for (let i = 0; i < length; i++) {
    const a = arr1[i] ? arr1[i] : 0;
    const b = arr2[i] ? arr2[i] : 0;
    result.push(parseInt(a) + parseInt(b));
  }
  return parseInt(result.reverse().join(''));
}
```

---
