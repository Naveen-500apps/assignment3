<template>
  <div>
<label>QUESTION10 </label>
   <button @click="FULLNAME()">click here</button>
  </div>
</template>
<script>
export default {
name: "FullnaME",
data()
{
return{

first_name:"500apps ",
last_name:"infinity",
}
},
methods:{
FULLNAME(){
this.full_name=this.first_name+ "_" +this.last_name

console.log(this.full_name)
}
}
};
</script>
<style scoped>
label {padding:5px}
</style>