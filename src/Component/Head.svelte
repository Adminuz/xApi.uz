<script>

</script>

<div class="logo"> </div>

  
  <div class="main">
      <div class="continer">
             <hello>🇺🇿 Ас-саляму алейкум, я</hello><br>
             <name>Джуманазаров, Умидбек</name> <br>
             <dev>Full-stack Разработчик с 2012 года <br/> (считаю от публикации первого сайта).</dev>
      </div>
       
        <div class="continer">
        <div class="ava"></div> 
        </div>

</div> 

<style>


  hello{
       color: black;
		font-size: 15px;
		font-weight: 100;
  }

  name{
      color: rgb(199, 65, 65);
		font-size: 25px;
		font-weight: 100;
  }

  dev{
       color: black;
		font-size: 15px;
		font-weight: 100;
  }


  .main{
  
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-bottom: 30px;
}



 .continer{
  
  text-align: center;

}





 .ava{
  
 background-image: url('/static/avatar.jpg');
 background-position-y: -35px;
 background-size: cover;
 background-repeat: no-repeat;
 border-radius:10em;
 width: 200px;
 height: 200px;
 


 }







   .logo{
        z-index: 1;
        background-image: url('/static/logo.png');
        background-repeat: no-repeat;
        width: 100%;
        height: 71px;
        

    }
    
    


    @media (max-width: 600px) {
    .main {
        flex-direction: column-reverse;
        justify-content:center;
        align-items: center;
       
       
       
    }
   /* .main_left{
    margin-top: 2vh
   }
   .main_right{
      margin-top: 5vh;
   } */

   /* .continer{
     height: 150px;
   } */
   
}

    </style>