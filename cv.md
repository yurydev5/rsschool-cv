# Resume for RS School

![logo](picture.png)

# Yury D

Discord: `@ensj1`

## Motivation

I want to start develop new websites, close some gaps in html, css, front-end frameworks with help of this school. I like to use front-end frameworks: React, Vue. Currently I work as a python/js automation engineer.

## Experience

| Technology |                                                     List                                                     |
| ---------- | :----------------------------------------------------------------------------------------------------------: |
| Languages  |                                   Python, JS, TS, Java, Groovy, HTML, CSS                                    |
| Frameworks | React(continue learning), Vue(learning), Cypress, Playwright, pytest,robot-framework, rest-assured, Selenium |
| SCV        |                                                GitHub, GitLab                                                |
| Cloud      |                                           Azure, AWS, Google Cloud                                           |
| Pipelines  |                                      Jenkins, github actions, gitlab CI                                      |

## Code examples from Codewars:

### Example 1

```javascript
function likes(names) {
  if (names.length > 3) {
    return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`;
  } else if (names.length == 3) {
    return `${names[0]}, ${names[1]} and ${names[3]} like this`;
  } else if (names.length == 2) {
    return `${names[0]} and ${names[1]} like this`;
  } else if (names.length == 1) {
    return `${names[0]} likes this`;
  } else {
    return "no one likes this";
  }
}

describe("example tests", function () {
  it("should return correct text", function () {
    assert.strictEqual(likes([]), "no one likes this");
    assert.strictEqual(likes(["Peter"]), "Peter likes this");
    assert.strictEqual(likes(["Jacob", "Alex"]), "Jacob and Alex like this");
    assert.strictEqual(
      likes(["Max", "John", "Mark"]),
      "Max, John and Mark like this"
    );
    assert.strictEqual(
      likes(["Alex", "Jacob", "Mark", "Max"]),
      "Alex, Jacob and 2 others like this"
    );
  });
});
```

### Example 2

```javascript
function descendingOrder(n) {
  if (n.toString().length == 1) {
    return n;
  }
  const arr = Array.from(n.toString()).sort((a, b) => b - a);
  return Number.parseInt(arr.join(""));
}

describe("Basic tests", () => {
  it("Testing for fixed tests", () => {
    assert.strictEqual(descendingOrder(0), 0);
    assert.strictEqual(descendingOrder(1), 1);
    assert.strictEqual(descendingOrder(111), 111);
    assert.strictEqual(descendingOrder(15), 51);
    assert.strictEqual(descendingOrder(1021), 2110);
    assert.strictEqual(descendingOrder(123456789), 987654321);
  });
});
```

## Current Job Position

_Lead Quality Engineer_

## Passed Courses

Completed courses related to front-end: [JS for Testers](https://learn.epam.com/myLearning/path?rootId=12842128), [NodeJS Essential](https://www.linkedin.com/learning/node-js-essential-training-14888164?u=2113185), [CSS Essential](https://www.linkedin.com/learning/css-essential-training-22688362?u=2113185), [Learning React.js](https://www.linkedin.com/learning/learning-react-js-5?u=2113185), [JavaScript Essential](https://www.linkedin.com/learning/javascript-essential-training?u=2113185), AI courses 😁

## English level

**B2**
