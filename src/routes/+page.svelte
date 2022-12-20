<script>
    import { blank_object, object_without_properties } from "svelte/internal";

 
let count = 95; 
</script>
<button on:click = {() => count++}>{count} </button>

<h1> <b> Dhingra Portforlio </b> </h1>
<p class = "redtext">  heellooo aimigo </p>


<a href = "/about"> My About Page </a>
<!-- UR COOOOOOOOOOOOL -->
<style> 
h1{
    color : green; 
}
.redtext{
    color : red;
}
:global(body) {
    background-color: black;
    color: white;
    font-family: sans-serif;
}

</style>