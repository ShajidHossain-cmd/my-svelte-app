<script>
	export let data;
    
</script>
<!--{console.log(data.props.guides)}-->
<div class="guides">
   <ul>
       {#each data.guides as guide}
        <li><a href={`/guides/${guide.id}`}>{guide.title}</a></li>
       {/each}
    </ul> 
</div> 
<style>
    .guides{
        margin-top: 20px;
        
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    a {
        display: inline-block;
        margin-top: 10px;
        padding: 10px;
        border: 1px dotted rgb(255,255,255,0.2);
    }
</style>