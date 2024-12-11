## Code
```
const files = [1,2].concat([3,2,4,1]) // 1,2,3,2,4,1 
const withoutDuplicate = files.filter(
    (item, index) => files.indexOf(item) === index
  );

```
