<!--info-header-start--><h1>useLocalStorage <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/> <img src="https://img.shields.io/badge/-%23Composable%20Function-999" alt="#Composable Function"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eyJBcHAudnVlIjoiPHNjcmlwdCBzZXR1cCBsYW5nPSd0cyc+XG5cbmltcG9ydCB7IHJlZiB9IGZyb20gXCJ2dWVcIlxuXG4vKipcbiAqIEltcGxlbWVudCB0aGUgY29tcG9zYWJsZSBmdW5jdGlvblxuICogTWFrZSB0aGUgZnVuY3Rpb24gd29yayBmaW5lXG4qL1xuZnVuY3Rpb24gdXNlTG9jYWxTdG9yYWdlKGtleTogc3RyaW5nLCBpbml0aWFsVmFsdWU6IGFueSkge1xuICBjb25zdCB2YWx1ZSA9IHJlZihpbml0aWFsVmFsdWUpXG5cbiAgcmV0dXJuIHZhbHVlXG59XG5cbmNvbnN0IGNvdW50ZXIgPSB1c2VMb2NhbFN0b3JhZ2UoXCJjb3VudGVyXCIsIDApXG5cbi8vIFdlIGNhbiBnZXQgbG9jYWxTdG9yYWdlIHZpYSB0cmlnZ2VyZWQgdGhlIGdldHRlcjpcbmNvbnNvbGUubG9nKGNvdW50ZXIudmFsdWUpXG5cbi8vIEFuZCBXZSBhbHNvIGNhbiBzZXQgbG9jYWxTdG9yYWdlIHZpYSB0cmlnZ2VyZWQgdGhlIHNldHRlcjpcblxuY291bnRlci52YWx1ZSA9IDFcblxuPC9zY3JpcHQ+XG4ifQ==" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-213547?logo=vue.js&logoColor=42b883" alt="Take the Challenge"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-gray" alt="简体中文"/></a> </p><!--info-header-end-->


We often need to use the `localStorage` API. A composable function will help us use it better. Lets go. 👇: 


```vue
<script setup lang='ts'>

import { ref } from "vue"

/**
 * Implement the composable function
 Make sure the function works correctly
*/
function useLocalStorage(key: string, initialValue: any) {
  const value = ref(initialValue)

  return value
}

const counter = useLocalStorage("counter", 0)

// We can get the localStorage by triggering the getter:
console.log(counter.value)

// And we also can set the localStorage by triggering the setter:

counter.value = 1

</script>

```

<!--info-footer-start--><br><a href="../../README.md" target="_blank"><img src="https://img.shields.io/badge/-Back-grey" alt="Back"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues/new?labels=answer,en&template=0-answer.md&title=18%20-%20useLocalStorage" target="_blank"><img src="https://img.shields.io/badge/-Share%20your%20Solutions-teal" alt="Share your Solutions"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues?q=label%3A18+label%3Aanswer" target="_blank"><img src="https://img.shields.io/badge/-Check%20out%20Solutions-de5a77?logo=awesome-lists&logoColor=white" alt="Check out Solutions"/></a> <!--info-footer-end-->
