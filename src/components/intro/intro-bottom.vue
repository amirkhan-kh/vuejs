<template>
    <div class="container">
    <div class="bottom">
        <div class="title">
            <h2>Provide the best service with out of the box ideas</h2>
            <p>we are a passionate team of digital marketing enthusiasts dedicated to helping businesses succeed in the digital world. With years of experience and a deep understanding of the ever-evolving online landscape, we stay at the forefront of industry trends and technologies.</p>
        </div>
        <div class="action">
            <div class="left">
                <div class="top">
                    <h1>920 <span>+</span></h1>
                    <p>Project finish with superbly</p>
                </div>
                <div class="result">
                    <div class="avatar"></div>
                    <div class="avatar"></div>
                    <div class="avatar"></div>
                    <div class="avatar"></div>
                    <div class="avatarr"><h1>+</h1></div>
                </div>
            </div>
            <div class="right">
                <h2>HOW WE WORK</h2>
                <button><img src="../icons/solar_play-bold.svg" alt=""></button>
            </div>
        </div>
    </div>
    </div>
</template>
<style lang="scss" scoped>
.bottom{
    padding: 30px 0px;
    
    .title{
        display: flex;
        width: 100%;
        justify-content: space-between;
        margin-bottom: 70px;
        h2{
            width: 45%;
            font-weight: 700;
            font-size: 40px;
            line-height: 60px;
        }
        p{
            width: 50%;
            font-weight: 500;
            font-size: 17px;
            line-height: 25px;
            color: #878C91;

        }
    }    
    .action{
        display: flex;
        margin-bottom: 70px;
        gap: 24px;
        .left{
            width: 438px;
            height: 382px;
            background-image: url("../icons/image 60.png");
            background-repeat: no-repeat;
            background-color: #010104;
            background-size: cover;
            border-radius: 20px;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 40px;
            .top{
                h1{
                    font-weight: 700;
                    font-size: 80px;
                    line-height: 80px;
                    display: flex;
                    margin-bottom: 30px;
                    span{
                        color: #99CF63;

                    }
                }
                p{
                    font-weight: 500;
                    font-size: 17px;
                    line-height: 25px;
                    color: #878C91;

                }
            }
            .result{
                display: flex;
                align-items: center;
                gap: 15px;
                .avatar{
                    width: 60px;
                    height: 60px;
                    border-radius: 50%;
                    background-color: #C6C6C6;
                }
                .avatarr{
                    width: 60px;
                    height: 60px;
                    border-radius: 50%;
                    display: grid;
                    place-items: center;
                    cursor: pointer;
                    h1{
                        font-size: 48px;
                    }
                }
                
                
                
            }

        }
        .right{
            background-color: #C7C7C7;
            height: 382px;
            width: 100%;
            border-radius: 20px;
            display: grid;
            place-items: center;
            position: relative;
            h2{
                font-weight: 600;
                font-size: 50px;
                color: #fff;
            }
            button{
                position:absolute;
                bottom: -20px;
                right: -10px;
                border-radius: 50%;
                border: 8px solid #fff;
                border-radius: 50%;
                background-color: #99EA48;
                padding: 40px;
            }
        }
    }
}
</style>