<script>

</script>


<appBar>
  <div class="logo"> </div>
  <div class="main">
      <div class="continer">
             <div class="main_left">
              <hello>Ас-саляму алейкум, я</hello><br>
             <name>Джуманазаров, Умидбек</name> <br>
             <dev>Full-stack Разработчик</dev>
            </div>
        </div>
       
        <div class="continer">
       <div class="main_right">
           <avatar/>
     </div> 
    
   </div>

</div> 
</appBar>


<style>

appBar{
  display: flex;
  align-items:center;
  flex-direction: column;
  justify-content: flex-start;


}
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
    width: 100%;
   height: 60vh;   
  display: flex;
  align-items:center;
  justify-content: space-around;


  }

  @media (max-width: 600px) {
    .main {
        flex-direction: column-reverse;
       
    }
   .main_left{
    margin-top: 2vh
   }
   .main_right{
      margin-top: 5vh;
   }
   
}

  .main_right{
 position: absolute; 
 left: 50%;
 top: 50%;
 color:red;
 transform: translate(-50%, -50%);
text-align: center;
  }
   .main_left {
position: absolute; 
 left: 50%;
 top: 50%;
 color:red;
 transform: translate(-50%, -50%);
 text-align: center;

        
    }


 avatar{
 background-image: url('/static/avatar.jpg');
 background-position-y: -35px;
 background-size: cover;
 background-repeat: no-repeat;
 border-radius:10em;
 width: 35vh;
 height: 35vh;
 position: absolute; 
 left: 50%;
 top: 50%;
 color:red;
 transform: translate(-50%, -50%)
 }



.continer{
 background-color: rgba(0, 0, 0, 0.111);
 position: relative;
  width:100%;
  height:60vh;
  align-self: center;

}




   .logo{
        text-align: z;
        z-index: 1;
        background-image: url('/static/logo.png');
        background-repeat: no-repeat;
        width: 100%;
        height: 71px;
        

    }
    
    
    </style>