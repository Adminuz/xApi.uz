<script>
import ProjectItim from './Itim.svelte'
import Title from '../Title.svelte'
</script>


<Title name="✌🏻 Проекты ✌🏻" />
<div class="proj">
<ProjectItim name="Свои Люди" derct="Cтатистики сервера CS:GO" img='/static/csgo.jpg' />
<ProjectItim name="Ислам в Твери" derct="Время молитв - (ДУМТвО)." img='/static/islam.png' />
<ProjectItim name="Намоз Вақтлари" derct="Telegram Бот - Узбекистан." img='/static/uzislam.jpg'/>
</div>

<style>




.proj{
  display: flex;
  height:80px;
  flex-direction: row;
}


@media (max-width: 900px) {
    .proj{
        height:200px;
        flex-direction: column;
   }
       
    }

</style>