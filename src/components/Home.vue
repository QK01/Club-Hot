<template>

    <body>      
        <!-- R1 Page************************************************ --> 
        <div id="R1"  style="background-image: linear-gradient(to right, #FFEFBA , #FFFFFF);">
            <div style="margin-top:10px;" id="header" class="container">  
                    <p style="text-align:center; font-size:25px"><b>به نام خدا</b></p>  
            </div>
                <div id="main" class="row">

                    <div id="content" class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                        <img src="../assets/logo.png" alt="avatar">

                        <div style="border: 1px solid blue; border-radius: 10px; margin-bottom: 30px; background-color: white">
                            <p style="text-align:right; font-size:25px; margin-right: 10px; color:red;"><b>کلاب هات</b></p>
                            <p style="text-align:center; font-size:20px; margin-top: -8%; color:red;">یک دنیا فرصت و امتیاز</p>
                        </div>                   
                        <input style="margin-bottom: 20px; border-radius: 5px;" type="tel" placeholder="09..."><br>
                        <button style="margin-bottom: 10px; width:200px; height:50px" class="btn btn-warning" @click="R101()">دریافت کد</button>                        
                    </div>
                </div>
            <div id="footer" class="row">
            </div>
        </div>   

        <!-- R101 Page********************************************** -->
        <div id="R101"  style="background-image: linear-gradient(to right, #FFEFBA , #FFFFFF);">
            <div style="margin-top:10px;" id="header" class="container">  
                    <p style="text-align:center; font-size:25px"><b>به نام خدا</b></p>  
            </div>
                <div id="main" class="row">

                    <div id="content" class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                        <img src="../assets/logo.png" alt="avatar">

                        <div style="border: 1px solid blue; border-radius: 10px; margin-bottom: 30px; background-color: white">
                            <p style="text-align:right; font-size:25px; margin-right: 10px; color:red;"><b>کلاب هات</b></p>
                            <p style="text-align:center; font-size:20px; margin-top: -8%; color:red;">یک دنیا فرصت و امتیاز</p>
                        </div>                   
                        <input style="margin-bottom: 20px; border-radius: 5px;" type="tel" placeholder="09..."><br>
                        <input style="margin-bottom: 20px; border-radius: 5px; text-align:center; height:50px" type="password" placeholder="___ ___ ___ ___ ___ ____"><br>
                        <button style="margin-bottom: 10px; width:200px; height:50px" class="btn btn-success" @click="R102()">ادامه</button>                        
                    </div>
                </div>
            <div id="footer" class="row">
            </div>
        </div>
        <!-- R102 Page********************************************** -->
        <div id="R102"  style="background-image: linear-gradient(to right, #FFEFBA , #FFFFFF);">
            <div style="margin-top:10px;" id="header" class="container">  
                    <p style="text-align:center; font-size:25px"><b>به نام خدا</b></p>  
            </div>
                <div id="main" class="row">

                    <div id="content" class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                        <img src="../assets/logo.png" alt="avatar">

                        <div style="border: 1px solid blue; border-radius: 10px; margin-bottom: 30px; background-color: white">
                            <p style="text-align:right; font-size:25px; margin-right: 10px; color:red;"><b>کلاب هات</b></p>
                            <p style="text-align:center; font-size:20px; margin-top: -8%; color:red;">یک دنیا فرصت و امتیاز</p>
                        </div>                   
                        <input style="margin-bottom: 20px; border-radius: 5px;" type="tel" placeholder="09121000000"><br>
                        <input style="margin-bottom: 20px; border-radius: 5px; height:40px" type="text" placeholder="نام"><br>
                        <input style="margin-bottom: 20px; border-radius: 5px; height:40px" type="text" placeholder="نام خانوادگی"><br>
                        <button class="btn btn-info" style="border-radius: 15px; margin-left:10px"><input type="radio" name="gender" value="male" margin-left:10px> مرد</button>
                        <button class="btn btn-info" style="border-radius: 15px; margin-left:10px"><input type="radio" name="gender" value="male" margin-left:10px> زن</button>
                        <button class="btn btn-info" style="border-radius: 15px; margin-left:10px"><input type="radio" name="gender" value="male" margin-left:10px> غیره</button><br><br>
                        
                        <button style="margin-bottom: 10px; width:200px; height:50px" class="btn btn-primary" @click="R103()">ثبت نام</button>                        
                    </div>
                </div>
            <div id="footer" class="row">
            </div>
        </div>
        <!-- L1 Page********************************************** -->
        <div id="L1"  style="background-image: linear-gradient(to right, #FFEFBA , #FFFFFF);">
            <div style="margin-top:10px;" id="header" class="container">  
                    <p style="text-align:center; font-size:25px"><b>به نام خدا</b></p>  
            </div>
                <div id="main" class="row">

                    <div id="content" class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                        <img src="../assets/logo.png" alt="avatar">

                        <div style="border: 1px solid blue; border-radius: 10px; margin-bottom: 30px; background-color: white">
                            <p style="text-align:right; font-size:25px; margin-right: 10px; color:red;"><b>کلاب هات</b></p>
                            <p style="text-align:center; font-size:20px; margin-top: -8%; color:red;">یک دنیا فرصت و امتیاز</p>
                        </div>                   
                        <input style="margin-bottom: 20px; border-radius: 5px;" type="tel" placeholder="09121000000"><br>
                        <input style="margin-bottom: 20px; border-radius: 5px; text-align:center; height:50px" type="password" placeholder="رمز عبور"><br>
                        <button style="margin-bottom: 10px; width:200px; height:50px" class="btn btn-success" @click="L1()">ورود</button>                        

                    </div>
                </div>
            <div id="footer" class="row">
            </div>
        </div>

        <!--H1 Page*********************************************** -->
        <div id="H1"  style="background-image: linear-gradient(to right, #2193b0 , #6dd5ed);">
            
        </div>

                 
    </body>

   
</template>

<script>

export default ({
    setup() {
        
    },
    methods:{
        R101() {
            document.getElementById("R1").style.display = "none";
            document.getElementById("R101").style.display = "block";
        },
        R102() {
            document.getElementById("R1").style.display = "none";
            document.getElementById("R101").style.display = "none";
            document.getElementById("R102").style.display = "block";
        },
        R103() {
            document.getElementById("R1").style.display = "none";
            document.getElementById("R101").style.display = "none";
            document.getElementById("R102").style.display = "none";
            document.getElementById("L1").style.display = "block";

        },
        L1() {
            document.getElementById("R1").style.display = "none";
            document.getElementById("R101").style.display = "none";
            document.getElementById("R102").style.display = "none";
            document.getElementById("L1").style.display = "none";
            document.getElementById("H1").style.display = "block";
        },

        
    }
})
</script>









<style scoped>   
   #header{
        
        text-align: center;  
        background-image: linear-gradient(to right, #a1f5ea , #74db8b);
        height: 5%;
        width: 70%;
        border-radius: 30px;
       
   } 
   #main{
        width: 80%;
        height: 80%;
        margin-left: 10%;
        margin-top: 1%;

   }
   #content{
        background-image: linear-gradient(to right, #FFEFBA , #FFFFFF);
        text-align: center;
        height: 80%;
        border-radius: 10px;
        border: 2px solid blue;
      
   }
   #sidebar{
        background-color: cyan;
   }
   #footer{
        height: 100px;
        background-image: linear-gradient(to right, #FFEFBA , #FFFFFF);
        margin-top: 1%;
   }
    #R101 {
        display: none;
   }#R102 {
        display: none;
   }#L1 {
       display: none;
   }#H1 {
       display: none;
   }
  
</style>