<script> 
let age 
age = 14

function onClick() {
  age +=1
}
</script>

<button on:click={onClick}>Change the value</button>

{age}
