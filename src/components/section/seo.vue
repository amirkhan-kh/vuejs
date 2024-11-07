<template>
    <div>
        <div class="container">
            <div class="top">
                <h2>Digital Marketing & SEO ServicesThat Grow Traffic & Increase Revenue</h2>
                <div class="right">
                <p>We are the top digital marketing agency for  branding corp. We offer a full range of services to help clients improve their search engine rankings and drive more traffic to their websites.</p>
                <button>See more</button>
                </div>
            </div>
            <div class="cards">
                <div class="card">
                    <div class="top">
                        <div class="role"></div>
                        <p>5 min read</p>
                    </div>
                    <h4>How a Digital Marketing Agency Can Boost Your Business</h4>
                    <div class="bio">
                        <p>We are the top digital marketing agency for  branding corp. We offer a full rang  engine ....</p>
                        <button><i class="bi bi-arrow-right-short"></i></button>
                    </div>
                </div>
                <div class="card">
                    <div class="top">
                        <div class="role"></div>
                        <p>5 min read</p>
                    </div>
                    <h4>The Latest Trends and Strategies with a Digital Marketing Agency</h4>
                    <div class="bio">
                        <p>We are the top digital marketing agency for  branding corp. We offer a full rang  engine ....</p>
                        <button><i class="bi bi-arrow-right-short"></i></button>
                    </div>
                </div>
                <div class="card">
                    <div class="top">
                        <div class="role"></div>
                        <p>5 min read</p>
                    </div>
                    <h4>Maximizing ROI with the Expertise of a Digital Marketing Agency</h4>
                    <div class="bio">
                        <p>We are the top digital marketing agency for  branding corp. We offer a full rang  engine ....</p>
                        <button><i class="bi bi-arrow-right-short"></i></button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.top{
    display: flex;
    align-items: start;
    gap: 39px;
    width: 100%;
    margin-bottom: 70px;
    h2{
        font-size: 46px;
        font-weight: 600;
        line-height: 59px;
        width: 50%;
    }
    .right{
        width: 50%;
        p{
            font-weight: 500;
            font-size: 15px;
            color: #878C91;
            line-height: 28px;
            margin-bottom: 54px;
        }
        button{
            background-color: transparent;
            border: 1px solid silver;
            padding: 7px 20px;
            font-size: 14px;
            color: #000000;
            border-radius: 20px;
            transition: background-color 0.3s ease;
            &:hover{
                background-color: #79797a;
                color: #fff;
            }
        }
    }
}
.cards{
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
    gap: 24px;
    margin-top: 70px;
    padding-bottom: 120px;
    .card{
        background-color: #F9F9F9;
        border-radius: 10px;
        padding: 32px;
        display: flex;
        flex-direction: column;
        box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.1);
        .top{
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 20px;
            .role:nth-child(1){
                border-radius: 50%;
                width: 14px;
                height: 14px;
                background: blue;
                &:nth-child(2){
                border-radius: 50%;
                width: 14px;
                height: 14px;
                background: rgb(0, 255, 64);
            }
            }
            p{
                font-size: 13px;
                color: #878C91;
                line-height: 22px;
                font-weight: 500;
            } 
        }
        h4{
                font-size: 26px;
                font-weight: 600;
                line-height: 35px;
                margin-bottom: 30px;
        }
        .bio{
            display: flex;
            align-items: center;
            gap: 30px;
            p{
                font-size: 14px;
                color: #878C91;
                line-height: 22px;
                font-weight: 500;
            }
            button{
                background-color: transparent;
                border: 1px solid silver;
                padding: 7px 20px;
                font-size: 14px;
                color: #000000;
                border-radius: 20px;
                transition: background-color 0.3s ease;
                &:hover{
                    background-color: #79797a;
                    color: #fff;
                }
            }
        }
    }
}
</style>