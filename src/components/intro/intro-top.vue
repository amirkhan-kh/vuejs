<template>
    <div class="container">
        <div class="intro">
            <div class="left">
                <h1>Stay ahead of the curve with our forward-thinking </h1>
                <p>An award-winning SEO agency with disciplines in digital marketing, design, and website development. focused on understanding you.</p>
                <div class="btns">
                    <button>Schedule Call <i class="bi bi-arrow-right-short"></i></button>
                    <button>View Case Study</button>
                </div>
                <div class="partners">
                    <p>Trusted by the world's biggest brands</p>
                    <a href=""><img src="../../assets/images/Company logo.svg" alt=""></a>
                    <a href=""><img src="../../assets//images/Company logo (1).svg" alt=""></a>
                    <a href=""><img src="../../assets/images/Company logo.png" alt=""></a>
                </div>
            </div>
            <div class="right">
                <div class="top">
                    <div class="topLeft">
                        <div class="circle">
                            <img src="../icons/trending-up.png" alt="">
                        </div>
                    </div>
                    <div class="topRight">
                        <h1>230+</h1>
                        <p>some big companies that we work with, and trust us very much</p>
                        <input type="range">
                    </div>
                </div>
                <div class="statistic">
                    <div class="in">
                        <div class="lefts">
                            <h3>Drive More Traffic and Sales </h3>
                            <h4>Drive more traffic and product sales </h4>
                        </div>
                        <div class="rights">
                            <div class="cub"></div>
                            <div class="cub"></div>
                            <div class="cub"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.intro{
    display: flex;
    gap: 50px;
    padding: 53px 0px;
    width: 100%;
    .left{
        width: 50%;
        h1{
            font-size: 72px;
            font-weight: 700;
            margin-bottom: 40px;
            line-height: 79px;
        }
        p{
            font-size: 17px;
            line-height: 25px;
            font-weight: normal;
            color: #878C91;
            margin-bottom: 40px;

        }
        .btns{
            display: flex;
            gap: 20px;
            margin-bottom: 90px;
            button{
                width: 200px;
                height: 56px;
                border-radius: 50px;
                border: none;
                background-color: #010205;
                color: #fff;
                font-size: 16px;
                transition: background-color 0.3s ease;
                &:hover{
                    background-color: #222223;
                }
            }
            button:last-child{
                background-color: transparent;
                text-decoration: underline;
                color: #010205;
                font-size: 16px;
                font-weight: 600;
            }
        }
        .partners{
            display: flex;
            gap: 20px;
            justify-content: space-between;
            margin-bottom: 40px;
            p{
                color: #010205;
                font-size: 16px;
                width: 180px;
                font-weight: 600;
                line-height: 24px;
            }
            a{
                img{
                    height: 33px;
                }
            }
        }
    }
    .right{
        width: 50%;
        display: flex;
        flex-direction: column;
        .top{
            width: 100%;
            display: flex;
            gap: 24px;
            margin-bottom: 40px;
            width: 100%;
            .topLeft{
                width: 50%;
                height: 295px;
                background-color: #C8C8C8;
                border-radius:100% 10px 10px 10px ;
                position: relative;
                .circle{
                    position: absolute;
                    width: 60px;
                    height: 60px;
                    border-radius: 50%;
                    background-color: #010205;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    color: #fff;
                    filter: drop-shadow(0px 15px 10px rgba(0, 0, 0, 0.5)); 
                    left: 60%;
                    top:-20px;
                    img{
                        width: 20px;
                    }
                }
            }
            .topRight{
                width: 50%;
                background-color: #F0F0F0;
                border-radius: 15px;
                padding: 30px 25px;
                h1{
                    font-size: 80px;
                    font-weight: 700;
                    line-height: 50px;
                    text-align: center;
                    width: 100% ;
                    margin-bottom: 30px;
                    
                }
                p{
                    font-size: 16px;
                    line-height: 24px;
                    color: #010205;
                    font-weight: 500;
                    margin-bottom: 30px;
                    color: #5C5D5F;
                }
                input[type="range"]{
                    width: 100%;
                    height: 20px;
                    background-color: #5f5d5d;
                    border-radius: 5px;
                    margin-bottom: 30px;
                    accent-color: black;
                }
            }
        }
        .statistic{
            background-image: url("../icons/image 60.png");
            background-repeat: no-repeat;
            width: 100%;
            height: 200px;
            border-radius: 20px;
            background-color: rgb(1,2,5);
            overflow: hidden;
            .in{
                display: flex;
                color: white;
                .lefts{
                    padding: 40px 60px;
                    width: 50%;
                    h3{
                        text-align: center;
                        font-size: 12px;
                        font-weight: 600;
                        line-height: 17px;
                        margin-bottom: 30px;
                    }
                    h4{
                        font-size: 22px;
                        line-height: 41px;
                        font-weight: 600;
                    }
               }
               .rights{
                width: 50%;
                display: flex;
                gap: 20px;
                padding: 0px 40px;
                transform: rotate(180deg);
                .cub{
                    width: 70px;
                    height: 90px;
                    background: #BAE289;
                    bottom: 0;
                    margin-right: 10px;
                }
                .cub:nth-child(1){
                    height: 170px;
                    background: #77B248;

                }
                .cub:nth-child(2){
                    height: 140px;
                    background: #99CF63;

                }
               }
            }
        }
    }
}
</style>