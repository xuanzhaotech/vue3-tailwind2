<template>
<svg :height="height" :width="width" viewBox="0 0 32 32" class="fill-current">
 <path d="M4 6H15V8H4zM18 6H28V8H18zM21 12H28V14H21zM11 12H18V14H11zM4 12H8V14H4zM4 18H28V20H4zM4 24H21V26H4zM24 24H28V26H24z"/></svg>
</template>
<script> 
export default
{ name:"IconData2", 
 props:{ height: { type:  Number, default: 20, }, width: { type:  Number, default: 20, }, } 
}
</script>