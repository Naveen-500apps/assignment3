<template>
<div>
<button @click="ErrorHandling()">catch</button>
</div>
</template>
<script>
export default{
name:"QuE5",
methods:{
ErrorHandling() {
try{
this.test =this. val * 45;
console.log("test",this.val);
}
catch{console.log("Error found")}
}
}
}
</script>