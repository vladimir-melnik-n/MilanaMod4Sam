<script>
  import myphoto1 from "$lib/images/Myphoto1.jpg";
  import myphoto2 from "$lib/images/Myphoto2.jpg";
  import myphoto3 from "$lib/images/Myphoto3.jpg";
  import myphoto4 from "$lib/images/Myphoto4.jpg";
  import myphoto5 from "$lib/images/Myphoto5.jpg";
  import myphoto6 from "$lib/images/Myphoto6.jpg";
</script>

<div class="container">
  <img alt="Моё фото 1" src={myphoto1} width="400" />
  <br />
  <img alt="Моё фото 2" src={myphoto2} width="400" />
  <br />
  <img alt="Моё фото 3" src={myphoto3} width="400" />
  <br />
  <img alt="Моё фото 4" src={myphoto4} width="400" />
  <br />
  <img alt="Моё фото 5" src={myphoto5} width="400" />
  <br />
  <img alt="Моё фото 6" src={myphoto6} width="400" />
</div>

<style>
  .container {
    margin: 50px auto;
    max-width: 800px;
    padding: 0 20px;
  }
</style>
