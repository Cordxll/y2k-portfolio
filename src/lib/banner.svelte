<script>
    let colors = [
    '#323232', '#393939', '#404040', '#474747', '#4E4E4E', '#555555', '#5C5C5C', '#636363', 
    '#6A6A6A', '#717171', '#787878', '#7F7F7F', '#868686', '#8D8D8D', '#949494', '#9B9B9B', 
    '#A2A2A2', '#A9A9A9', '#B0B0B0', '#B7B7B7', '#BEBEBE', '#C5C5C5', '#CCCCCC', '#D3D3D3', 
    '#DADADA', '#E1E1E1', '#E8E8E8', '#EFEFEF', '#F6F6F6', '#FFFFFF'
  ];
</script>
<main>
    <div class='body'>
        <div class='name' style="color: #ffffff; background-color:#323232">Cordell Browne's</div>
        <div class='name' >Portfolio</div> 
        {#each colors as color}
            <div class='colors', style="background-color: {color}"></div>
        {/each}
    </div>
</main>
<style>
    main{
        width: 100%;
    }
    .body{
        display: flex;
        border-style: solid;
        border-color: black;
    }
    .name{
        padding: 0.5%;
        text-align: center;
        font-family: "VT323", monospace;
    }
    .colors{
        padding: 1%;
        padding-right:1.5%;
    }
    
</style>