<template>
    <div class="container">
        <h2 style="float: left">Lokasi</h2><br><br><br>
        <div class="row">
            <div class="column">
                <div class="card">
                <img alt="Vue logo" src="../assets/yogya.jpeg" width="100%"><br>  
                    <h4><b>Yogyakarta</b></h4>
                    <p></p>
                </div>
            </div>
            <div class="column">
                <div class="card">
                <img alt="Vue logo" src="../assets/jkt.jpg" width="100%"><br>  
                    <h4><b>Jakarta</b></h4>
                    <p></p>
                </div>
            </div>
            <div class="column">
                <div class="card">
                <img alt="Vue logo" src="../assets/bdg.jpg" width="100%"><br> 
                    <h4><b>Bandung</b></h4>
                    <p></p>
                </div>
            </div>
        </div>
        <br><br>
        <div class="row">
        <div class="column">
                <div class="card">
                <img alt="Vue logo" src="../assets/smg.jpg" width="100%"><br> 
                    <h4><b>Semarang</b></h4>
                    <p></p>
                </div>
            </div>
        </div>
        
    </div>

</template>

<script>
export default {
    name: 'Lokasi'
  }
</script>

<style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 100%;
  height: 100%;
  
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 2px 16px;
  margin-bottom: 40px;
  
  
}

.column {
    width: 370px;
  padding: 0 20px;
  
  /* float: center; */
}



</style>