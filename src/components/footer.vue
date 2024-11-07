<template>
    <div>
            <div class="container">
            <div class="black">
                <h1>Ready to work with us ?</h1>
                <button>Get Started <i class="bi bi-arrow-right-short"></i></button>
            </div>
            <div class="flex">
                <div class="left">
                    <div class="logo">
                        <img src="./icons/Group 2.png" alt="">
                        <h1>MAC</h1>
                    </div>
                    <p>We offers a comprehensive suite of digital marketing services that cover all aspects of our online presence. From SEO and social media marketing to content creation and PPC advertising, they have the expertise and resources to handle our diverse marketing needs.</p>
                    <div class="messengers">
                        <p><i class="bi bi-facebook"></i></p>
                        <p><i class="bi bi-twitter"></i></p>
                        <p><i class="bi bi-linkedin"></i></p>
                        <p><i class="bi bi-instagram"></i></p>
                    </div>
                </div>
                <div class="right">
                    <ul>
                        <li><strong>Navigation</strong></li>
                        <li>Privacy Policy</li>
                        <li>Copyright</li>
                        <li>Email Address</li>
                        <li>Email Address</li>
                        <li>Email Address</li>
                    </ul>
                    <ul>
                        <li><strong>Licence</strong></li>
                        <li>Privacy Policy</li>
                        <li>Copyright</li>
                        <li>Email Address</li>
                    </ul>
                    <ul>
                        <li><strong>Contact</strong></li>
                        <li><i class="bi bi-telephone-fill"></i>(406) 555-0120</li>
                        <li><i class="bi bi-envelope"></i>Hey@boostim.com</li>
                        <li><i class="bi bi-geo-alt-fill"></i>2972 Westheimer Rd. Santa Ana, Illinois 85486 </li>
                    </ul>

                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
    .black{
    background-color: #000000;
    background-image: url("./icons/image\ 60.png");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: #fff;
    padding: 50px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-bottom: 100px;
    border-radius: 25px;
    h1{
        font-weight: 600;
        font-size: 80px;
        line-height: 100px;

    }
    button{
        width: 200px;
        height: 56px;
        border-radius: 25px;
        border: none;
        background: #fff;
        font-size: 18px;
    }
}

.flex{
    display: flex;
    justify-content: space-between;
    align-items: start;
    margin-bottom: 100px;
    width: 100%;
    .left{
        width: 40%;
        padding-right: 50px;
        .logo{
            display: flex;
            align-items:center;
            gap: 10px;
            margin-bottom: 30px;
            h1{
            font-weight: 700;
            font-size: 40px;
            line-height: 50px;
        }

        }
        p{
            font-size: 14px;
            line-height: 24px;
            font-weight: 400;
            color: #9B9B9C;
            margin-bottom: 30px;

        }
       .messengers{
        display: flex;
        gap: 20px;
        p{
            font-size: 20px;
            line-height: 30px;
            font-weight: 600;
            color: #9B9B9C;
            &:hover{
                cursor: pointer;
            }
            i{
                color: #000000;

            }
        }
       }
    }
    .right{
        padding-left: 50px;
        display: flex;
        gap: 115px;
        ul{
            list-style-type: none;
            padding: 0;
            li{
                font-size: 13px;
                line-height: 26px;
                font-weight: 600;
                color: #9B9B9C;
                margin-bottom: 10px;
                display: flex;
                gap: 10px;
                strong{
                    font-weight: 800;
                    color: #000000;
                    margin-bottom: 30px;
                }
                i{
                    color: #000000;

                }
            }
        }
    }
}
</style>