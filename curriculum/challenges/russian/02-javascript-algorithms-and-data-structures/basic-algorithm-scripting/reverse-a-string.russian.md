---
id: a202eed8fc186c8434cb6d61
title: Reverse a String
challengeType: 5
forumTopicId: 16043
localeTitle: Обратить строку
---

## Description
<section id='description'>
Переверните предоставленную строку. Возможно, вам придется перевернуть строку в массив, прежде чем вы сможете ее отменить. Ваш результат должен быть строкой. Не забудьте использовать <a href="https://forum.freecodecamp.org/t/how-to-get-help-when-you-are-stuck-coding/19514" target="_blank">Read-Search-Ask,</a> если вы застряли. Напишите свой собственный код.
</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>reverseString("hello")</code> should return a string.
    testString: assert(typeof reverseString("hello") === "string");
  - text: <code>reverseString("hello")</code> should become <code>"olleh"</code>.
    testString: assert(reverseString("hello") === "olleh");
  - text: <code>reverseString("Howdy")</code> should become <code>"ydwoH"</code>.
    testString: assert(reverseString("Howdy") === "ydwoH");
  - text: <code>reverseString("Greetings from Earth")</code> should return <code>"htraE morf sgniteerG"</code>.
    testString: assert(reverseString("Greetings from Earth") === "htraE morf sgniteerG");

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function reverseString(str) {
  return str;
}

reverseString("hello");

```

</div>

</section>

## Solution
<section id='solution'>

```js
function reverseString(str) {
  return str.split('').reverse().join('');
}

reverseString("hello");
```

</section>
