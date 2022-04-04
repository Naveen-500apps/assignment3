<template>
<div>
<form id="demo">
<p>{{msg}}</p>
<p>{{msg.length}}</p>

    <label> QUESTION2 </label>


<input type="text" name="message" v-model="msg">
</form>
</div>
</template>
<script>
export default{

name:"QuestioN2",

data(){

return{

msg:" "

}
},
}
</script>

<style scoped>

label{text-align:left;} 

</style>
