Write a JavaScript function that checks how similar are two strings, which are passed in to this function as arguments.  

See example below ...

```
    This is a string
    There was string
      ^^^^^^^          <-- 7 differences
```

In the above example, the function should return 7.

// function calculateLevDistance (src, target) {
//     if (!tgt.length) return src.length;
//     if (!src.length) return tgt.length;

//     return Math.min(
//         calculateLevDistance( src.slice(1), tgt ) + 1, calculateLevDistance( tgt.slice(1), src ) + 1,
//         calculateLevDistance( src.slice(1), tgt.slice(1) ) + ( src[0] == tgt[0] ? 0 : 1 )
//     );
// }