<template>
    <header>
        <nav class="conteiner">

            <a href="/"><img alt="WDEV" id="logo" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg"></a>
            
            <img alt="Abrir menu" id="menu-buttom" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg">

            <div id="menu-overlay"></div>

            <div id="menu-items">
                
                <a href="/"><img alt="WDEV" id="menu-logo" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg"></a>
                
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/video">Vídeos</a></li>
                    <li><a href="/sobre">Sobre</a></li>
                    <li><a href="/contato">Contato</a></li>
                </ul>

            </div>

        </nav>
    </header>
</template>

<script>
export default{

    name: 'Header'
}
</script>

<style scoped>

    header{
        background-color: var(--color-background-nav);
        height: 60px;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    nav{
        display: flex;
        justify-content: space-between;
    }

    #logo{
        width: 130px;
    }

    #menu-buttom{
        width: 30px;
    
    }

    #menu-overlay{
        position: fixed;
        top:0;
        left:0;
        width: 40%;
        height: 100vh;
        background-color: #000000;
        opacity: 0.8;
    }

    #menu-log{
        width: 110px;
    
    }


</style>