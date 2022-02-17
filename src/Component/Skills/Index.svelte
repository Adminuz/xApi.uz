 <script>
  import Title from '../Title.svelte' 
  import Itim from './Itms.svelte'
 
  const data = [
  {name:'⚙ Backend',list:['Node','PHP','Sql/NoSql']},
  {name:'💻 Frontend',list:['React','Svelte','Vue']},
  {name:'📱 Mobile App',list:['Flutter','A/Cordova','React Native']}
]


 </script>

 <Title name ="✍🏻 Основной стек"/>
<div class="continer">
 <div class="skills">
    {#each data as {name,list}}
    <Itim name={name} data={list}/>
    {/each}
</div>

</div>


<style>
.continer{
margin-top: 1em;
text-align: center; 
}


.skills{
    display: inline-flex;
    width: 90%;
    flex-direction: row;
    align-items: flex-start;
   

}


</style>