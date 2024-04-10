# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(?) => O(1)
Space complexity: O(?) => O(1)
Justification: We are making changes to the array itself so adding elements makes the time complexity constant. Since we are adding element to the original array, Space complexity remains constant

[push on MDN][push]


## `arr.pop()`

Time complexity: O(?) => O(1)
Space complexity: O(?) => O(1)
Justification: For Space complexity, since we are removing a single element it remains constant. For Time complexity, We are not iterating through anything and only making references so it constants.

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(?) => O(1)
Space complexity: O(?) => O(1)
Justification: For Space complexity: We are removing a single element so this is constant. For Time complexity: We don't need the length it becuase we reference index 0, remove it and return it. So it constant.

[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(1)
Justification: Space complexity: Adding an element to the front is constant since we are minipulating the array itself. Time complexity: since we have to move all elements to the right the time it takes would be linear.

[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(n)
Justification: Time complexity: based on the 2nd argument, everything that comes after will need to be moved back. Doing this process will would be on the length of 'n' and will be iterating so linear growth. Space complexity: When iterating through the moving elements, it will take up space so O(n)

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(n)
Justification: Space complexity: Since we are copying a piece or full array, the space it takes would be based on the size of 'n' or arr. Time complexity: We are iterating through 'n' and pushing the elements to the new array. That cause it to be linear.

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(1)
Justification: Time complexity: The time it takes to find the target is linear or based on the size of 'n'. Space complexity: This will be constant because 'i' value takes up the same amount of memory.

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(n)
Justification: Space complexity: when iterating though 'n', the index 'i' would take up space but its constant. Since we are creating a new data structure, it would make this linear. Time complexity: is linear becuase we are simply iterating through 'n'.

[map on MDN][map]

## `arr.filter()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(n)
Justification: Time complexity: this would be based on the size of 'this'. Depending on the 'callback' lets assume its constant. Space complexity: since we are creating another array, that takes up more space. Worst case scenario its the same size of 'n' so O(n).

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(1)
Justification: Time complexity: all arithmetic is constant, what linear is iterating through the array. Space complexity: The index, and result of calling the callback makes this constant

[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(1)
Justification: Time complexity: completetly depedent on the size of 'n'. Space complexity: The temp value needed to switch the value in 'n' and 'i' are all constants.

[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(?) => O(n)
Space complexity: O(?) => O(n)
Justification: Space complexity: The space needed is based the amount of arguments however we need to put them into an array so its linear. Time complexity: We need to copy the element into the array so its linear

[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
