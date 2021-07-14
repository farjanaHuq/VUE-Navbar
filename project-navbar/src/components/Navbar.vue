
<template>
    <div class="container-fluid" style="background-color:blue height: 250px width: 100%">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Logo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <!-- Navbar options -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
            <li class="nav-item">
                <a class="nav-link" href="#" style="font-weight:bold; color:black">Codex <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item" id="navbar-options">
                <a class="nav-link" href="#">Trading</a>
            </li>
            <li class="nav-item" id="navbar-options">
                <a class="nav-link" href="#">Lending</a>
            </li>
            <li class="nav-item" id="navbar-options">
                <a class="nav-link" href="#">Stake</a>
            </li>
            <li class="nav-item" id="navbar-options">
                <a class="nav-link" href="#">Portfolio</a>
            </li>
            <li class="nav-item" id="navbar-options">
                <a class="nav-link" href="#">OrderBook</a>
            </li>
            <li class="nav-item" id="navbar-options">
                <a class="nav-link" href="#">Markets</a>
            </li>
            <li class="nav-item dropdown" id="navbar-options">
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
                   <!-- user wallet dropdown menue-->
                  <div class="dropdown-menu" aria-labelledby="navbarDropdown" id="user-walet-box">
                             <div class="row" id="user-wallet-items" style="">
                                      <div class="nav-item" role="button"><i class="fa fa-files-o" aria-hidden="true" style="width:16px; height: 14px"></i>Copy Address</div>        
                            </div>
                           
                             <div class="row" id="user-wallet-items" style="">
                                      <div class="nav-item" role="button"><i class="fa fa-globe" aria-hidden="true" style="width:14px; height: 16px"></i>Open Etherscan</div>        
                            </div>
                             <div class="row" id="user-wallet-items" style="">
                                      <div class="nav-item" role="button"><i class="fa fa-sign-out" aria-hidden="true" style="width:14px; height: 16px"></i>Disconnect</div>        
                            </div>
                  </div>
                </li>
                <li style="color:gray font-weight:light padding-right: 2px"> | </li> 

<!-- This section covers navbar settinngs. The gear icon is clickable and displays a dropdown menue to edit layout. -->
                 <li class="dropdown">
                  <a class="dropdown" role="button" data-toggle="dropdown">
                  <i class="fa fa-cog"></i></a>
                  <div class="dropdown-menu" id="settings-layout">
                      <div id="setting-layout-inside">
                            <div class="row" id="div-divider">
                                   <div class="col-sm-6" style="font-size:13px">Light</div>
                                   <div class="col-sm-6 text-right"><i class="fa fa-toggle-on" aria-hidden="true" style="color:blue; height:24px; width:16px"></i></div>
                            </div>
                            <div class="row">
                                   <div class="col-sm-10" style="font-size:13px; color:#6C757D;border-top:53px; margin-top:16px">Layout Settings</div>
                                     
                                   <div class="col-sm-2 text-right"><i class="fa fa-columns" style="color:#6C757D; margin-top:16px" aria-hidden="true"></i></div>
                            </div>
                            <!-- edit layout button -->
                            <div class="row" id="layout-edit" style="font-size:13px; height:20px; widhth:62px; font-weight:light; margin-left:9px; margin-top 10.67px;">
                                      <div class="nav-item" role="button"><i class="fa fa-pencil-square-o" aria-hidden="true" style="margin-right:8px width:16px; height: 14.22px"></i>Edit Layout</div>        
                            </div>
                            <!-- default layout button -->
                             <div class="row" id="layout-default" style="font-size:13px; height:20px; widhth:62px; font-weight:light; margin-left:9px; margin-top:19.11px;">
                                      <div class="nav-item" role="button"><i class="fa fa-repeat" aria-hidden="true" style="width:16px; height: 16px"></i>Default Layout</div>        
                            </div>
                      </div>
                  </div>
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
.navbar{
     max-width: 1440px;
     max-height:80px;
     margin: 20px;
     color: #000;
     background-color:#FFFFFF;
     font-size: 16px;
}
.navbar-toggler{
  background-color: blue !important;
}
#navbar-options{
  color:black;
  font-size: 16px;
  font-weight:bold;
}
#user-walet-box{
  height: 124px; 
  width: 167px
}
#user-wallet-items{
 font-size:13px; 
 height:20px;  
 margin-left:9px; 
 margin-top:16px;
}
#settings-layout{
  height: 169px; 
  width: 167px
}
#setting-layout-inside{
  height: 135px; 
  width: 137px; 
  margin-top: 16px; 
  margin-left:14px; 
  margin-right:16px; 
  /* border: 1px solid;
  border-top: 12px, solid; */
}
#div-divider{
  height: 36px;
  border-bottom: 1px solid black;
}

</style>


