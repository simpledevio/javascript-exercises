# conditional statements

Try the following statements in the console:
```
if (1 > 0) {
  console.log('The condition is true');
}
```
Output: "The condition is true"

---

```
if (1 < 0) {
  console.log('The condition is true');
}
```
Output: undefined

---
```
if (1 > 0) {
  console.log('The condition is true');
} else {
  console.log('The condition is false');
}
```
Output: "The condition is true"

---

```
if (1 < 0) {
  console.log('The condition is true');
} else {
  console.log('The condition is false');
}
```
Output: "The condition is false"

---

```
if (1 > 0) {
  console.log('The 1st condition is true');
} else if(2 > 1) {
  console.log('The 1st condition is false and the 2nd is true');
} else {
  console.log('Both conditions are false');
}
```
Output: "The 1st condition is true"

---

```
if (1 < 0) {
  console.log('The 1st condition is true');
} else if(2 > 1) {
  console.log('The 1st condition is false and the 2nd is true');
} else {
  console.log('Both conditions are false');
}
```
Output: "The 1st condition is false and the 2nd is true"

---

```
if (1 < 0) {
  console.log('The 1st condition is true');
} else if(2 < 1) {
  console.log('The 1st condition is false and the 2nd is true');
} else {
  console.log('Both conditions are false');
}
```
Output: "Both conditions are false"

---
