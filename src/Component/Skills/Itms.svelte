<script>
export let name, data;


</script>
<div>
<div class="title">{name}</div>
{#each data as e}
<p>{e}</p>
{/each}
</div>

<style>
p{
    text-align: center;
}

.title{
font-size: 14px;
}


div{
width: 100%;
}
</style>

