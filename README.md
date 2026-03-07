 ### What is the difference between var, let, and const?

Ans: var → old JavaScript variable, function scoped, re-declare করা যায়।

let → block scoped, value change করা যায় কিন্তু same scope এ আবার declare করা যায় না।

const → block scoped, declare করার পরে value change করা যায় না।


### What is the spread operator (...)?

Ans: ... use হয় array বা object এর elements spread / copy করার জন্য।
const arr1 = [1,2];
const arr2 = [...arr1,3,4];


### What is the difference between map(), filter(), and forEach()?

Ans: map() → array এর প্রতিটা element নিয়ে new array return করে।

filter() → condition অনুযায়ী selected elements দিয়ে new array return করে।

forEach() → শুধু loop করে, কিছু return করে না।


