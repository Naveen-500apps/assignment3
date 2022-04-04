<template>
    <div>
        <label> QUESTION 1 </label>
        <h1>spread operator</h1>
        <button @click="clickhere()">click here</button>
    </div>
</template>
<script>
export default{
    name:"OPErator",
    data(){
        return{
         array:[1,2,3,7,8,6,9,10],
         array2:[4,5]

        }
    },
methods:
    {
     clickhere(){
const array=[1,2,3,7,8,...this.array2,6,9,10]
console.log(array);
        }
    }   
}
</script>
<style scoped>
label {text-align: center;}
</style>




