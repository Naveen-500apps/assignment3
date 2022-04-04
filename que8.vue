<template>
<div>
<p @click="func()">
p tag : KEVIN TECH
</p>
<textarea id="id">
</textarea>
</div>
</template>
<script>
export default {
name: "QuE8",
data() {
return {
textdata: "",
};
},
methods: {
func() {
this.textdata = " " + document.getElementById("id").value;
document.write(this.textdata);
},
},
};
</script>