
<template>
    <div class="container-fluid" style="background-color:blue height: 250px width: 100%">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Logo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Codex <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Trading</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Lending</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Stake</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Portfolio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">OrderBook</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Markets</a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                More
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>
                </div>
            </li>
            </ul>
            <div class="w3-bar">     
              <ul class="navbar-nav mr-auto list-unstyled justify-content-end">
                <li class="nav-item dropdown ">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">0XF696...6EDE
                  </a>
                  <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <div>
                        <a class="dropdown-item" href="#">Your Wallets</a>
                      </div>
                          <div class="dropdown-divider"></div>
                      <a class="dropdown-item" href="#">Wallet 1</a>
                  
                      <a class="dropdown-item" href="#">Wallet 2 </a>
                  </div>
                </li>
                <li style="color:gray font-weight:light padding-right: 2px"> | </li>
                
                <li class="nav-item"><a class="nav-link" href="#"> <i class="fa fa-cog" ></i></a>
                   
                </li>
              </ul> 
            </div>       
        </div>
        </nav>
    </div>

</template>

<script>
export default {
  name: "Navbar",
};
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap');
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Poppins', sans-serif;
  color: #000;
  font-weight: bold;
}
.navbar{
     max-width: 90%;
     max-height:80px;
     margin: 20px;
     color: #000;
     background-color: fff;
     font-weight: bold;
     padding: 10px;
     box-shadow: 0.5px 5px ;
}
.navbar-toggler{
  background-color: blue !important;
}
.btn {
  display: inline-block;
  background: #000;
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}
.btn:focus {
  outline: none;
}
.btn:active {
  transform: scale(0.98);
}
.btn-block {
  display: block;
  width: 100%;
}
</style>


