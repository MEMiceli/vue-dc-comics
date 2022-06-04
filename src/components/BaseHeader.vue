<template>
  <header>
      <div class="right_header">
        <div class="box_image">
            <img src="../assets/img/dc-logo.png" alt="logo">
        </div>    
      </div>
      <div class="left_header">
        <nav class="nav_header">
            <ul>
                <li><a href="#"></a>Characters</li>
                <li class="active"><a href="#"></a>Comics</li>        
                <li><a href="#"></a>Movies</li>
                <li><a href="#"></a>Tv</li>
                <li><a href="#"></a>Games</li>
                <li><a href="#"></a>Collectibles</li>
                <li><a href="#"></a>Videos</li>
                <li><a href="#"></a>Fans</li>
                <li><a href="#"></a>News</li>
                <li><a href="#"></a>Shop</li>        
            </ul>
        </nav>     
      </div>
  </header>
</template>

<script>
export default {
    name:'BaseHeader',

}
</script>

<style lang="scss" scoped>
    header{
        display:flex;
        justify-content: space-around;
        margin: 1.25rem 0;
        text-align: center;
        // display: flex;
        // align-items: center; soluzione corretta per allinamento testo
        // justify-content: center;
        

    };
    ul{
        display: flex;
        align-items: flex-end;
        list-style-type: none;
        text-transform: uppercase;
        list-style: none;
        column-gap: 2rem;
        // line-height: è sbagliato;
        line-height: 130px;
        .active {
            border-bottom: .2rem solid var(--primary-color);
        }
    
    }
</style>