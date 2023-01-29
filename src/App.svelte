<script>
  let color;
  addEventListener('input',()=>{
    document.getElementById("colorarea").style.backgroundColor=`#${color}`


  })


</script>


<main>

<div class="heading">
  <h2>Color Picker</h2>
<h5>Get useful information like conversion, blindness simulation, combinations and more.</h5>

</div>
<input type="text"  bind:value={color} >
<div class="card" id="colorarea">

</div>
</main>

<style>
main{
  text-align: center;

}

h5{
  color: grey;
}

input{
  width:100%;
  border-radius: 5px;
  margin: 50px 0px;
  padding: 10px;
}

.card{
  width:90%;
  margin: 0 auto;
  height: 200px;
  
}






</style>
