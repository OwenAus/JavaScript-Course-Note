### **1. Create a new set**

```js
const orderSet = new set([
  "Pasta",
  "Pizza",
  "Pizza",
  "Risotto",
  "Pasta",
  "Pizza",
]);
```

### **2. Size not length**

```js
console.log(orderSet.size); // 3
```

### **3. Check if a certain element is in set**

```js
console.log(orderSet.has("Pizza")); // true
```

### **4. Add new element to a set**

```js
orderSet.add("Garlic Bread");
```

### **5. Delete element**

```js
orderSet.delete("Garlic Risotto");
```

### **6. Loop over sets**

```js
for (const order of orderSet) console.log(order); // Pasta Pizza Garlic Bread
```

## <font color=blue>**7. Remove duplicate values of arrays**</font>

```js
const staff = ["Waiter", "Chef", "Waiter", "Manager", "Chef", "Waiter"];
const staffUnique = new Set(staff) ;
=== const staffUnique = [...new Set(staff)] ;

console.log(staffUnique); // "Waiter", "Chef", "Manager"

console.log(new Set("sfsdsilsdfjk").size);
```
