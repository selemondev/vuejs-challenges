<!--info-header-start--><h1>useToggle <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/> <img src="https://img.shields.io/badge/-%23Composable%20Function-999" alt="#Composable Function"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eyJBcHAudnVlIjoiPHNjcmlwdCBzZXR1cCBsYW5nPSd0cyc+XG5cbi8qKlxuICogSW1wbGVtZW50IGEgY29tcG9zYWJsZSBmdW5jdGlvbiB0aGF0IHRvZ2dsZSBzdGF0ZVxuICogTWFrZSB0aGUgZnVuY3Rpb24gd29yayBmaW5lXG4qL1xuZnVuY3Rpb24gdXNlVG9nZ2xlKCkge1xuXG59XG5cbmNvbnN0IFtzdGF0ZSwgdG9nZ2xlXSA9IHVzZVRvZ2dsZShmYWxzZSlcblxuPC9zY3JpcHQ+XG5cbjx0ZW1wbGF0ZT5cbiAgPHA+U3RhdGU6IHt7IHN0YXRlID8gJ09OJyA6ICdPRkYnIH19PC9wPlxuICA8cCBAY2xpY2s9XCJ0b2dnbGVcIj5cbiAgICBUb2dnbGUgc3RhdGVcbiAgPC9wPlxuPC90ZW1wbGF0ZT5cbiJ9" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-213547?logo=vue.js&logoColor=42b883" alt="Take the Challenge"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-gray" alt="简体中文"/></a> </p><!--info-header-end-->


For this challenge, we'll start by creating a composable function. Lets start with `useToggle` 👇: 


```vue
<script setup lang='ts'>

/**
 * Implement a composable function that toggles the state
 * Make the function work correctly
*/
function useToggle() {

}

const [state, toggle] = useToggle(false)

</script>

<template>
  <p>State: {{ state ? 'ON' : 'OFF' }}</p>
  <p @click="toggle">
    Toggle state
  </p>
</template>

```

<!--info-footer-start--><br><a href="../../README.md" target="_blank"><img src="https://img.shields.io/badge/-Back-grey" alt="Back"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues/new?labels=answer,en&template=0-answer.md&title=15%20-%20useToggle" target="_blank"><img src="https://img.shields.io/badge/-Share%20your%20Solutions-teal" alt="Share your Solutions"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues?q=label%3A15+label%3Aanswer" target="_blank"><img src="https://img.shields.io/badge/-Check%20out%20Solutions-de5a77?logo=awesome-lists&logoColor=white" alt="Check out Solutions"/></a> <!--info-footer-end-->
