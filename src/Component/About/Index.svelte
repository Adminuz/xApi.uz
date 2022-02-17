<script>
import Title from '../Title.svelte';
let list = [
  'PHP', 'JavaScript','TypeScript','Node', 'Dart',
  'MySql', 'Mongodb', 'Redis', 'Express', 'Socket', 'Flutter',
  'HTML', 'CSS', 'SASS', 'React', 'Vue', 'Svelte',
  'AdobeXd', 'Figma', 'GIMP', 'Git', 'GNU/Linux', 'Webpack', 'Npm'

];
</script>


<Title name ="✅ Профессиональные навыки"/>


<div class="grid">
  {#each list as name}
  <div>{name}</div>
  {/each}
</div>

<style>




.grid {
  padding: 15px;
  padding-left: 20px;
  display: grid;
  
  grid-template-columns: repeat(auto-fill, minmax(60px, 100px));
  grid-gap: 1rem;
  
}
.grid > div {

  background: #EDE7F6;
  text-align: center;
  padding: 10px;
  border-radius: 5px;
}


</style>