
<template>
    <div class="container-fluid">
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
            <ul class="navbar-nav mr-auto" style="inline-block">
              <li class="nav-item dropdown list-unstyled">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">0XF696...6EDE
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <div>
                      <a class="dropdown-item" href="#">Action</a>
                    </div>
                    <a class="dropdown-item" href="#">Another action</a>
                    <div class="dropdown-divider"></div>
                    <a class="dropdown-item" href="#">Something else here</a>
                </div>
               </li>
               <li class="list-unstyled" style="color:gray font-weight:light"> | </li>
               <div></div>
               <li class="list-unstyled"> <i class="fa fa-cog" ></i></li>
            </ul>        
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
.container {
  max-width: 100%;
  margin: 0px auto;
  overflow: auto;
  max-height: 100px;
  /* border: 1px solid steelblue; */
  /* padding: 5px; */
  background-color: #000;
}
.navbar{
     max-width: 90%;
     max-height:80px;
     margin: 20px;
     color: #000;
     font-weight: bold;
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


