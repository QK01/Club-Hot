<template>
    <body >   
        <!-- R1 Page************************************************ --> 
        <div id="R1"  style="background-image: linear-gradient(to right, #FFEFBA , #FFEFBA); border:2px solid blue; border-radius:10%; margin-top:3%; margin-right:6%;" class="container">

                <div id="content" class="row">
                        <div class="col-md-12 offset-md-5 col-sm-8 offset-sm-2 col-10 offset-2">
                            <img src="../assets/logo.png" alt="avatar" >
                        </div>    
                </div>


                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-6 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-8 offset-6 h1">
                        <p style="color:red; "><b>کلاب هات</b></p>
                    </div>
                </div>
                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-7 offset-3 lead">                           
                        <p><b>یک دنیا فرصت و امتیاز</b></p>
                    </div>
                </div>

                <div class="row">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-8 offset-2">
                        <input id="phone" style="margin-bottom: 20px; border-radius: 5px;" type="tel" placeholder="09..."><br>
                    </div>
                </div> 

                
                <div class="row">
                    <button type="button" class="btn btn-warning btn-lg btn-block" style="margin-bottom:10%;" @click="R101()">دریافت کد</button>   
                </div>

            <div id="footer" class="row">
            </div>
        </div>   

        <!-- R101 Page********************************************** -->

            <div id="R101"  style="background-image: linear-gradient(to right, #FFEFBA , #FFEFBA); border:2px solid blue; border-radius:10%; margin-top:3%; margin-right:6%;" class="container">
                <div id="content" class="row">
                        <div class="col-md-12 offset-md-5 col-sm-8 offset-sm-2 col-10 offset-2">
                            <img src="../assets/logo.png" alt="avatar" >
                        </div>    
                </div>

                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-6 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-8 offset-6 h1">
                        <p style="color:red; "><b>کلاب هات</b></p>
                    </div>
                </div>

                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-7 offset-3 lead">                           
                        <p><b>یک دنیا فرصت و امتیاز</b></p>
                    </div>
                </div>

                <div class="row">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-2 col-sm-8 offset-sm-2 col-8 offset-2">
                        <input disabled id="phone2" style="margin-bottom: 20px; border-radius: 5px;" type="tel"><br>
                        <input style="margin-bottom: 20px; border-radius: 5px; text-align:center" type="password" placeholder="____ ____ ____ ____ ____"><br>
                    </div>
                </div>

                <div class="row">
                    <div class="alert alert-info alert-heading" style="text-align:center;" id="alert">
                        رمز شما به شماره موبایل <input disabled type="lable" id="lable-phone" style="text-align:center;"><br> ارسال شد
                    </div>
                    <button type="button" id="alert-btn" class="btn btn-success btn-lg btn-block" style="margin-bottom:10%; display:none;" @click="R102()">ادامه</button>     
                </div>

            <div id="footer" class="row">
            </div>
        </div> 

        <!-- R102 Page********************************************** -->
        <div id="R102"  style="background-image: linear-gradient(to right, #FFEFBA , #FFEFBA); border:2px solid blue; border-radius:10%; margin-top:3%; margin-right:6%;" class="container">
                <div id="content" class="row">
                        <div class="col-md-12 offset-md-5 col-sm-8 offset-sm-2 col-10 offset-2">
                            <img src="../assets/logo.png" alt="avatar" >
                        </div>    
                </div>

                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-6 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-8 offset-6 h1">
                        <p style="color:red; "><b>کلاب هات</b></p>
                    </div>
                </div>

                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-7 offset-3 lead">                           
                        <p><b>یک دنیا فرصت و امتیاز</b></p>
                    </div>
                </div>

                <div class="row">
                        <input disabled id="phone3" style="margin-bottom: 5%; border-radius: 5px;" type="tel"><br>
                        <input style="margin-bottom: 5%; border-radius: 5px; " class="" type="text" placeholder="نام"><br>
                        <input style="margin-bottom: 20%; border-radius: 5px; " class="" type="text" placeholder="نام خانوادگی"><br>
                </div>

                    <div class="row">

                        <button class="btn btn-info btn-lg btn-block mb-1" style="border-radius: 15px; "><input type="radio" name="gender"> مرد</button>
                        <button class="btn btn-info btn-lg btn-block mb-1" style="border-radius: 15px; "><input type="radio" name="gender"> زن</button>
                        <button class="btn btn-info btn-lg btn-block mb-1" style="border-radius: 15px; "><input type="radio" name="gender"> غیره</button><br><br>                       
                        <button style="margin-bottom: 10%; width:100%; height:50px" class="btn btn-primary" @click="R103()">ثبت نام</button>                        
                    </div>
                    
            <div id="footer" class="row">
            </div>
        </div>

        <!-- L1 Page********************************************** -->
        <div id="L1"  style="background-image: linear-gradient(to right, #FFEFBA , #FFEFBA); border:2px solid blue; border-radius:10%; margin-top:3%; margin-right:6%;" class="container">
                <div id="content" class="row">
                        <div class="col-md-12 offset-md-5 col-sm-8 offset-sm-2 col-10 offset-2">
                            <img src="../assets/logo.png" alt="avatar" >
                        </div>    
                </div>

                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-6 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-8 offset-6 h1">
                        <p style="color:red; "><b>کلاب هات</b></p>
                    </div>
                </div>

                <div class="row" style="">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-6 col-sm-8 offset-sm-2 col-7 offset-3 lead">                           
                        <p><b>یک دنیا فرصت و امتیاز</b></p>
                    </div>
                </div>

                <div class="row">
                    <div class="col-lg-8 offset-lg-5 col-md-8 offset-md-2 col-sm-8 offset-sm-2 col-8 offset-2">
                        <input disabled id="phone4" style="margin-bottom: 20px; border-radius: 5px;" type="tel"><br>
                        <input style="margin-bottom: 20px; border-radius: 5px; text-align:center" type="password" placeholder="رمز عبور"><br>
                    </div>
                </div>

                <div class="row">
                    <button type="button" class="btn btn-info btn-lg btn-block" style="margin-bottom:10%;" @click="L1()">ورود</button>     
                </div>

            <div id="footer" class="row">
            </div>
        </div> 

        <!--H1 Page*********************************************** -->
        <div id="H1"  >
            <p style="text-align: center; margin-top:30%">Please wait, page under construction !!!</p>
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

            var phone = document.getElementById('phone').value
            document.getElementById('phone2').value = phone

            const alertdiv = document.querySelector('#alert')
            const alertbtn = document.querySelector('#alert-btn')
            const phone2 = document.getElementById('phone2').value
            document.getElementById('lable-phone').value = phone2

            
            setTimeout(() => {
                alertdiv.remove()
                alertbtn.style.display = 'block';
                }, 5000);
        },

        R102() {
            document.getElementById("R1").style.display = "none";
            document.getElementById("R101").style.display = "none";
            document.getElementById("R102").style.display = "block";
            var phone = document.getElementById('phone').value
            document.getElementById('phone3').value = phone
        },

        R103() {
            document.getElementById("R1").style.display = "none";
            document.getElementById("R101").style.display = "none";
            document.getElementById("R102").style.display = "none";
            document.getElementById("L1").style.display = "block";
            var phone = document.getElementById('phone').value
            document.getElementById('phone4').value = phone

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