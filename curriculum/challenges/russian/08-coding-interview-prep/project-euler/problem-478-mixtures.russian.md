---
id: 5900f54c1000cf542c51005e
challengeType: 5
title: 'Problem 478: Mixtures'
videoUrl: ''
localeTitle: 'Задача 478: Смеси'
---

## Description
<section id="description"> Рассмотрим смеси трех веществ: A, B и C. Смесь может быть описана отношением количеств A, B и C в ней, то есть (a: b: c). Например, смесь, описываемая соотношением (2: 3: 5), содержит 20% А, 30% В и 50% С. <p> Для целей этой проблемы мы не можем отделить отдельные компоненты от смеси. Однако мы можем комбинировать различные количества различных смесей с образованием смесей с новыми соотношениями. </p><p> Например, предположим, что у нас есть три смеси с соотношениями (3: 0: 2), (3: 6: 11) и (3: 3: 4). Путем смешивания 10 единиц первого, 20 единиц второго и 30 единиц третьего, мы получаем новую смесь с соотношением (6: 5: 9), так как: (10 · 3/5 + 20 · 3/20 + 30 · 3/10: 10 · 0/5 + 20 · 6/20 + 30 · 3/10: 10 · 2/5 + 20 · 11/20 + 30 · 4/10) = (18: 15: 27) = (6: 5: 9) </p><p> Однако с теми же тремя смесями невозможно сформировать соотношение (3: 2: 1), так как количество B всегда меньше количества C. </p><p> Пусть n - положительное целое число. Предположим, что для каждой тройки целых чисел (a, b, c) с 0 ≤ a, b, c ≤ n и gcd (a, b, c) = 1 мы имеем смесь с отношением (a: b: c). Пусть M (n) - множество всех таких смесей. </p><p> Например, M (2) содержит 19 смесей со следующими соотношениями: {(0: 0: 1), (0: ​​1: 0), (0: ​​1: 1), (0: ​​1: 2), ( 0: 2: 1), (1: 0: 0), (1: 0: 1), (1: 0: 2), (1: 1: 0), (1: 1: 1) 1: 2), (1: 2: 0), (1: 2: 1), (1: 2: 2), (2: 0: 1), (2: 1: 0), (2: 1: 1), (2: 1: 2), (2: 2: 1)}. </p><p> Пусть E (n) - число подмножеств M (n), которое может производить смесь с соотношением (1: 1: 1), т. Е. Смесь с равными частями A, B и C. Мы можем проверить, что E (1 ) = 103, E (2) = 520447, E (10) mod 118 = 82608406 и E (500) mod 118 = 13801403. Найдите E (10 000 000) мод 118. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler478()</code> должен возвращать 59510340.
    testString: 'assert.strictEqual(euler478(), 59510340, "<code>euler478()</code> should return 59510340.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler478() {
  // Good luck!
  return true;
}

euler478();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>