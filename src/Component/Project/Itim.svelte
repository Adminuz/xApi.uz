<script>
export let name, img,derct;
</script>
  
  <div class="continer">
     <div class="row">
     <avatar style="background-image: url({img})"/>
     <div class="column">
     <small>{name}</small>
     <derct>{derct}</derct>
     </div> 
   </div>

  </div>

<style>

.column{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}


derct{

font-size: 10px;

}


small{
  font-size: 12px;


}

 avatar{
 width: 50px;
 margin-right: 1em;
 height: 50px;
 background-size: cover;
 border-radius: 50%;
 }

.continer{
    text-align: center;
    width: 99%;
    margin-top: 1em;
    padding: 0.5%;
    height: 50px;
    
}

  .row{
    display: inline-flex;
    width: 250px; 
   }


  @media (max-width: 900px) {
    .row{
  flex-direction: row;
  justify-content: flex-start;
  
  }

  .continer{
  text-align: center;
    }

       
    }



</style>