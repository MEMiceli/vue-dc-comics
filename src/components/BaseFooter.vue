<template>
    <footer>
        <div class="footertop">
            <div class="container">
               <ul>
                <li><div class="boximage"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div>digital comics</li>
                <li><div class="boximage"><img src="../assets/img/buy-comics-merchandise.png" alt=""></div>dc merchandise</li>
                <li><div class="boximage"><img src="../assets/img/buy-comics-subscriptions.png" alt=""></div>subscription</li>
                <li><div class="boximage"><img src="../assets/img/buy-comics-shop-locator.png" alt=""></div>comic shop locator</li>
                <li><div class="boximage"><img src="../assets/img/buy-dc-power-visa.svg" alt=""></div>dc power visa</li>
            </ul> 
            </div>
            
        </div>
        <div class="footermiddle">
            <div class="container">
                <div class="footermiddlehalf">
                    <div class="column">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>uno</li>
                            <li>due</li>
                            <li>tre</li>
                            <li>quattro</li>
                            <li>cinque</li>
                            <li>sei</li>
                            <li>sette</li>
                        </ul>
                        <h3>SHOP</h3>
                        <ul>
                            <li>uno</li>
                            <li>due</li>
                        </ul>
                    </div>
                    <div class="column">
                        <h3>DC</h3>
                        <ul>
                            <li>uno</li>
                            <li>due</li>
                            <li>tre</li>
                            <li>quattro</li>
                            <li>cinque</li>
                            <li>sei</li>
                            <li>sette</li>
                        </ul>
                    </div>
                    <div class="column">
                        <h3>DC</h3>
                        <ul>
                            <li>uno</li>
                            <li>due</li>
                            <li>tre</li>
                            <li>quattro</li>
                            <li>cinque</li>
                            <li>sei</li>
                            <li>sette</li>
                        </ul>
                    </div>
                </div>
                 <div class="footermiddlehalf">
                    <div class="bigboximage"><img src="../assets/img/dc-logo-bg.png" alt=""></div>
                </div>
            </div> 
        </div>
        <div class="footerbottom">
            <div class="footerbottomleft">
                <button>Sign Up Now</button>
            </div>
            <div class="footerbottomright">
                <ul>
                    <li><a href="#"></a>Follow Us</li>
                    <li><a href="#"></a><img src="../assets/img/footer-facebook.png" alt="facebook"></li>
                    <li><a href="#"></a><img src="../assets/img/footer-twitter.png" alt="twitter"></li>
                    <li><a href="#"></a><img src="../assets/img/footer-youtube.png" alt="youtube"></li>
                    <li><a href="#"></a><img src="../assets/img/footer-pinterest.png" alt="pinterest"></li>
                    <li><a href="#"></a><img src="../assets/img/footer-periscope.png" alt="periscope"></li>
                </ul>
            </div>
        </div>
    </footer>
  
</template>

<script>
export default {
    name:'BaseFooter',

}
</script>

<style lang="scss" scoped>
    .footertop{
        background-color: var(--primary-color);
        .boximage{
            width: 4rem;
            img{
                width: 100%;
            }
        }
    }
    ul{
        display: flex;
        justify-content: space-between;
        // list-style-type: none;
        text-transform: uppercase;
        list-style: none;
        // column-gap: 2rem;
        li{
            display: flex;
            padding: 2rem;
            align-items: center;
            justify-content: center;
            gap: .625rem;
        }
    }
    footer{
        color: white;
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        
    }
    .container{
        display: flex;
        .footermiddlehalf{
            // margin:auto;
            display: flex;
            ul{
                display: flex;
                flex-direction: column;
                li{
                    padding: .125rem;
                    font-size: smaller;
                    color:silver;
                    text-transform: capitalize;
                }
            }
        }
       
    }
    .footerbottom{
        background-color: gray;
        display: flex;
        justify-content:space-between;

    }
</style>