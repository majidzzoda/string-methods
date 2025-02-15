# string-methods
String и методы String в JavaScript
String в JavaScript
String — это последовательность символов, заключенная в кавычки (' ', " ", `` `).

Основные методы работы со String:
length — возвращает длину String.

let str = "Hello";
console.log(str.length); // 5
toUpperCase() / toLowerCase() — изменяет регистр.


console.log("hello".toUpperCase()); // "HELLO"
console.log("WORLD".toLowerCase()); // "world"
trim() — удаляет пробелы с начала и конца.


console.log("  text  ".trim()); // "text"
charAt(index) — возвращает символ по индексу.

console.log("JavaScript".charAt(4)); // "S"
indexOf(substring) / lastIndexOf(substring) — ищет подстроку в String.


console.log("Hello, world".indexOf("world")); // 7
includes(substring) — проверяет, содержится ли подстрока в String.


console.log("JavaScript".includes("Script")); // true
slice(start, end) — возвращает часть String.

console.log("Hello".slice(1, 4)); // "ell"
replace(old, new) — заменяет часть String.

console.log("Hello world".replace("world", "JS")); // "Hello JS"
split(delimiter) — разбивает String в массив.

console.log("a,b,c".split(",")); // ["a", "b", "c"]
repeat(n) — повторяет String n раз.

console.log("Hi ".repeat(3)); // "Hi Hi Hi "
Эти методы помогают эффективно работать со String, обрабатывать текст и выполнять манипуляции с данными. 🚀