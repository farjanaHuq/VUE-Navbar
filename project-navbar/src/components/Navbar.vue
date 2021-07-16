
<template>
  <div
    class="container-fluid"
    style="background-color:blue height: 250px width: 100%"
  >
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand Codex-Logo" href="#"><img src="/images/codex-logo.png" alt=""></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

      <!-- Navbar options -->
      <!-- Navbar left items -->
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item" id="navbar-options">
            <a class="nav-link" href="#" style="width: 57px;height: 19px; margin: 2px 16px 2px 0; color:#0d6efd">Trading</a>
          </li>
          <li class="nav-item" id="navbar-options">
            <a class="nav-link" href="#" style="width: 60px;height: 23px;margin: 0 16px;">Lending</a>
          </li>
          <li class="nav-item" id="navbar-options">
            <a class="nav-link" href="#" style="width: 34px;height: 23px; margin: 0 16px;">Earn</a>
          </li>
          <li class="nav-item" id="navbar-options">
            <a class="nav-link" href="#" style="width: 63px; height: 23px;margin: 0 16px;">Portfolio</a>
          </li>
          <li class="nav-item" id="navbar-options">
            <a class="nav-link" href="#" style="width: 86px; height: 23px;margin: 0 16px;">OrderBook</a>
          </li>
          <li class="nav-item" id="navbar-options">
            <a class="nav-link" href="#" style="width: 60px;height: 23px; margin: 0 16px;">Markets</a>
          </li>
          <li class="nav-item dropdown" id="navbar-options" style="width: 39px; height: 23px; margin: 0 8px 0 0;">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
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
        <!-- Navbar right elements -->
        <div class="w3-bar">
          <ul class="navbar-nav mr-auto list-unstyled justify-content-end">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
                >0XF696...6EDE
              </a>
              <!-- User wallet dropdown menue-->
              <div
                class="dropdown-menu"
                aria-labelledby="navbarDropdown"
                id="user-walet-box"
              >
                <div class="row" id="user-wallet-items" style="">
                  <div class="nav-item" role="button">
                    <i
                      class="fa fa-files-o"
                      aria-hidden="true"
                      style="width: 16px; height: 14px"
                    ></i
                    >Copy Address
                  </div>
                </div>

                <div class="row" id="user-wallet-items" style="">
                  <div class="nav-item" role="button">
                    <i
                      class="fa fa-globe"
                      aria-hidden="true"
                      style="width: 14px; height: 16px"
                    ></i
                    >Open Etherscan
                  </div>
                </div>
                <div class="row" id="user-wallet-items" style="">
                  <div class="nav-item" role="button">
                    <i
                      class="fa fa-sign-out"
                      aria-hidden="true"
                      style="width: 14px; height: 16px"
                    ></i
                    >Disconnect
                  </div>
                </div>
              </div>
            </li>
            <li style="color:gray font-weight:light padding-right: 2px">|</li>

            <!-- This section covers navbar settinngs. The gear icon is clickable and displays a dropdown menue to edit layout. -->
            <li class="dropdown">
              <a class="dropdown" role="button" data-toggle="dropdown">
                <i class="fa fa-cog" style="width:15px; height:16px;"></i
              ></a>
              <!-- <div class="dropdown-menu Rectangle">
                <div class="Light">Light</div>
              </div> -->
              <div class="dropdown-menu" id="settings-rectangle">
                          <div id="setting-layout-inside">
                            <div class="row" id="div-divider">
                               <div class="col Light">Light</div>
                                   <div class="col Shape text-right"><i class="fa fa-toggle-on" aria-hidden="true"></i></div> 
                            </div> 
                            
                            <!-- <div class="row" >
                                   <div class="col Light">Light</div>
                                   <div class="col Shape text-right"><i class="fa fa-toggle-on" aria-hidden="true"></i></div> 
                            </div>  -->
                            
                            
                            <div class="row">
                                   <div class="col-sm-10" style="font-size:13px; color:#6C757D;border-top:53px; margin-top:16px">Layout Settings</div>
                                     
                                   <div class="col-sm-2 text-right"><i class="fa fa-columns" style="color:#6C757D; margin-top:16px" aria-hidden="true"></i></div>
                            </div>
                            
                            <div class="row" id="layout-edit" style="font-size:13px; height:20px; widhth:62px; font-weight:light; margin-left:9px; margin-top 10.67px;">
                                      <div class="nav-item" role="button"><i class="fa fa-pencil-square-o" aria-hidden="true" style="margin-right:8px width:16px; height: 14.22px"></i>Edit Layout</div>        
                            </div>
                           
                             <div class="row" id="layout-default" style="font-size:13px; height:20px; widhth:62px; font-weight:light; margin-left:9px; margin-top:19.11px;">
                                      <div class="nav-item" role="button"><i class="fa fa-repeat" aria-hidden="true" style="width:16px; height: 16px"></i>Default Layout</div>        
                            </div>
                       </div>
                  </div>
                  <!-- edit layout button -->
                   <!-- default layout button -->
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
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap");
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
.navbar {
  max-width: 1440px;
  max-height: 80px;
  margin: 24px 0 0;
  padding: 0 24px;
  background-color: #ffffff;
  font-size: 16px;
  font-family: Arial, Helvetica, sans-serif;
}
/* .navbar-toggler {
  background-color: blue !important;
} */
#navbar-options {
  font-family: HelveticaNeue;
  font-size: 16px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.44;
  letter-spacing: normal;
  color: #000;
}
.Codex-Logo {
  width: 124px;
  height: 40px;
  margin: 20px 24px 20px 0;
  object-fit: contain;
}
#user-walet-box {
  height: 124px;
  width: 167px;
}
#user-wallet-items {
  font-size: 13px;
  height: 20px;
  margin-left: 9px;
  margin-top: 16px;
}
.Light {
  width: 29px;
  height: 20px;
  margin: 0 82px 4px 0;
  color:#000;

}
.Shape{
  width: 24px;
  height: 16px;
  color: #0d6efd;
}

#settings-rectangle{
  width: 167px;
  height: 169px;
  border-radius: 4px;
  box-shadow: 0 8px 16px 0 rgba(52, 58, 64, 0.1);
  background-color:#ffffff;
  padding: 16px;
  
  font-size: 13px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.54;
  letter-spacing: normal;
  color:#000;
}
#setting-layout-inside{
  height: 135px; 
  height: 137px; 
}
#div-divider {
  height: 36px;
  border-bottom: 0.2px solid #b8c3cf;
}
#layout-settings{
font-size: 13px;
color: #6c757d;
border-top: 53px;
margin-top: 16px;
/* width: 97px; */
height: 20px;
/* margin: 0 22px 0 0; */
}

#layout-edit{
 height: 20px;
 margin-left:9px; 
 margin-top: 10.67px;
 font-size: 13px;
}
#layout-default {
  height: 20px;
  margin-left: 9px;
  font-size: 13px;
}
.Codex-Logo {
  width: 124px;
  height: 40px;
  margin: 20px 24px 20px 0;
  object-fit: contain;
}
</style>


