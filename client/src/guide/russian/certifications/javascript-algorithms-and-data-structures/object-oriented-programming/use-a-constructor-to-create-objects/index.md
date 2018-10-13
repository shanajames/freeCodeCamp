---
title: Use a Constructor to Create Objects
localeTitle: Использование конструктора для создания объектов
---
## Использование конструктора для создания объектов

### Метод:

В последнем вызове мы увидели, как создать конструкторную функцию. Теперь мы можем просто вызвать эту функцию для создания нового объекта со свойствами, уже определенными в конструкторе. Просто инициализируйте новую переменную `hound` вызывающую конструктор `Dog()` .

### Решение:

```javascript
function Dog() { 
  this.name = "Rupert"; 
  this.color = "brown"; 
  this.numLegs = 4; 
 } 
 // Add your code below this line 
 let hound = new Dog(); 

```