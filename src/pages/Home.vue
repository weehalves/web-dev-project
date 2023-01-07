<template>
    <main> 
        <div class="text-top">Vídeos novos toda <b>quinta</b> ás <b>20h</b></div>
        <a href="https://youtube.com.br/wwdev" target=" Blank">
            <img alt="Inscrever-se" id="subscribe" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg">
        </a>
        <div class="text-bottom">youtube.com/wwdev</div>

    </main>
</template>

<script>
   export default{
    name: 'Home'
   }
</script>

<style scoped>
  main{
    background-color: var(--color-background-home);
    justify-content: center;
    align-items: center;
  }

  .text-top{
    color: var(--color-text-light);
    font-size: 22px;
    margin-top: 20px;
  }

  #subscribe{
    width: 340px;
  }

  .text-bottom{
    color: var(--color-text-light);
    font-size: 18px;
    margin-top: 20px;
  }
</style>