<template>
  <div>
    <div class="container">
      <div class="card">
        <h1>
          Real-world examples of how we have helped companies achieve their
          marketing objectives.
        </h1>
        <div class="btns">
          <button>All Work [20]</button>
          <button>UI/UX Design[10]</button>
          <button>Digital Marketing [5]</button>
          <button>Branding [5]</button>
        </div>
        <div class="miniCard">
          <button class="kart">
            <h2>Ai Corporation. 2023</h2>
            <div class="circle">See Details</div>
            <h2>Ai Wave - Ai Chatbot Mobile App</h2>
          </button>
          <button class="kart">
            <h2>Ai Corporation. 2023</h2>
            <div class="circle">See Details</div>
            <h2>Ai Wave - Ai Chatbot Mobile App</h2>
          </button>
          <button class="kart">
            <h2>Ai Corporation. 2023</h2>
            <div class="circle">See Details</div>
            <h2>Ai Wave - Ai Chatbot Mobile App</h2>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.card{
    background-image: url("../icons/image 60.png");
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    background-color: #020609;
    height: 826px;
    border-radius: 30px;
    padding: 80px 50px;
    overflow: hidden;
    margin-bottom: 120px;
    h1{
        text-align: center;
        color: #fff;
        font-weight: 600;
        font-size: 44px;
        line-height: 60px;
        margin-bottom: 50px;
    }
    .btns{
        display: flex;
        padding: 0px 120px;
        justify-content: space-between;
        margin-top: 30px;
        width: 100%;
        button{
            width: 200px;
            height: 45px;
            background: transparent;
            border: 1px solid #ffffff81;
            border-radius: 50px;
            color: #ffffffdb;
            font-size: 16px;
            margin-bottom: 70px;
            &:focus{
                background:#99CF63;
            }
        }

    }
    .miniCard{
        display: flex;
        align-items: center;
        gap: 50px;
        transform: translateX(100px);
        .kart{
            width: 370px;
            height: 370px;
            background: #C3C3C3;
            border: 6px solid #6b6868;
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            justify-content: space-between;
            padding: 10px;
            border-radius: 30px;
            transition: 0.2s;
            &:focus> .circle{
                    display: flex;
                }
            &:focus{
                border-radius: 50%;
            }
            &:focus> h2{
                color:transparent;
            }
            h2{
                color: #fff;
                font-size: 15px;
            }
            .circle{
                width: 80px;
                height: 80px;
                background: #99EA48;
                display: none;
                border-radius: 50%;
                justify-content: center;
                align-items: center;
                color: #000000;
                font-size: 12px;
                margin-bottom: 20px;
                &:focus{
                    display: flex;
                }
            }
        }
    }
}
</style>
