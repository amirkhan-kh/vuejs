<template>
    <header>
        <div class="container">
           <nav>
            <div class="nav">
                <div class="logo">
                    <img src="./icons/Group 2.png" alt="Logo">
                    <h1>MAC</h1>
                </div>
                <ul>
                    <li><a href="#">Service <i class="bi bi-chevron-down"></i></a></li>
                    <li><a href="#">Agency <i class="bi bi-chevron-down"></i></a></li>
                    <li><a href="#">Case study <i class="bi bi-chevron-down"></i></a></li>
                    <li><a href="#">Resources <i class="bi bi-chevron-down"></i></a></li>
                    <li><a href="#">Contact<i class="bi bi-chevron-down"></i></a></li>
                </ul>
            </div>
            <div class="btn">
                <button>Get started</button>
                <button class="btns"><img src="./icons/bell.svg" alt=""></button>
            </div>
           </nav>

        </div>
    </header>
</template>
<style lang="scss" scoped>
header{
    padding: 19px 0px;
    nav{
        display: flex;
        align-items: center;
        justify-content: space-between;
        .nav{
            display: flex;
            align-items: center;
            gap: 74px;
            .logo{
                display: flex;
                gap: 10px;
                align-items: center;
                h1{
                    font-size: 24px;
                    font-weight: 700;
                    color: #020407;
                }
                img{
                    width: 33px;
                    height: 33px;
                }
            }
            ul{
                display: flex;
                align-items: center;
                gap: 33px;
                li{
                    a{
                        color:#020407;
                        text-decoration: none;
                        font-size: 14px;
                        line-height:17px;
                        font-weight: 600;
                        display: flex;
                        gap: 10px;
                        align-items: center;
                    }
                }
            }
        }
        .btn{
            display: flex;
            gap: 10px;
            .btns{
                width: 28px;
                height: 28px;
                background: #000;
                border-radius: 50%;
                display: flex;
                align-items: center;
                justify-content: center;
                img{
                    width: 18px;
                    height: 18px;
                }
            }
            button{
                color: #000;
                border-radius: 50px;
                padding: 5px 15px;
                border: 1px solid #000;
                background: transparent;
                cursor: pointer;
            }
        }
    }
}
</style>