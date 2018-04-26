
Collections
- each
- map
- reduce
- reduceRight
- find
- filter
- where
- findWhere
- reject
- every
- some
- contains
- invoke
- pluck
- max
- min
- sortBy
- groupBy
- indexBy
- countBy
- shuffle
- sample
- toArray
- size
- partition
Arrays
- first
- initial
- last
- rest
- compact
- flatten
- without
- union
- intersection
- difference
- uniq
- zip
- unzip
- object
- chunk
- indexOf
- lastIndexOf
- sortedIndex
- findIndex
- findLastIndex
- range
Functions
- bind
- bindAll
- partial
- memoize
- delay
- defer
- throttle
- debounce
- once
- after
- before
- wrap
- negate
- compose
- restArguments
Objects
- keys
- allKeys
- values
- mapObject
- pairs
- invert
- create
- functions
- findKey
- extend
- extendOwn
- pick
- omit
- defaults
- clone
- tap
- has
- property
- propertyOf
- matcher
- isEqual
- isMatch
- isEmpty
- isElement
- isArray
- isObject
- isArguments
- isFunction
- isString
- isNumber
- isFinite
- isBoolean
- isDate
- isRegExp
- isError
- isSymbol
- isMap
- isWeakMap
- isSet
- isWeakSet
- isNaN
- isNull
- isUndefined
Utility
- noConflict
- identity
- constant
- noop
- times
- random
- mixin
- iteratee
- uniqueId
- escape
- unescape
- result
- now
- template
OOP Style
Chaining
- chain
- value


```
// The cornerstone, an `each` implementation, aka `forEach`.
  // Handles raw objects in addition to array-likes. Treats all
  // sparse array-likes as if they were dense.
  // 与 ES5 中 Array.prototype.forEach 使用方法类似
  // 遍历数组或者对象的每个元素
  // 第一个参数为数组（包括类数组）或者对象
  // 第二个参数为迭代方法，对数组或者对象每个元素都执行该方法
  // 该方法又能传入三个参数，分别为 (item, index, array)（(value, key, obj) for object）
  // 与 ES5 中 Array.prototype.forEach 方法传参格式一致
  // 第三个参数（可省略）确定第二个参数 iteratee 函数中的（可能有的）this 指向
  // 即 iteratee 中出现的（如果有）所有 this 都指向 context
  // notice: 不要传入一个带有 key 类型为 number 的对象！
  // notice: _.each 方法不能用 return 跳出循环（同样，Array.prototype.forEach 也不行）
  _.each = _.forEach = function(obj, iteratee, context) {...}
  
  ```
