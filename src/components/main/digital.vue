<template>
  <div>
    <div class="container">
      <h1>
        “ They thoroughly analyze our industry and target audience, allowing
        them to develop customized campaigns that effectively reach and engage
        our customers. Their creative ideas and cutting-edge techniques have
        helped us stay ahead of the competition.”
      </h1>
      <div class="flex">
        <div class="info">
            <div class="img"></div>
          <h2>Michael Kaizer <br /><span>CEO of Basecamp Corp</span></h2>
        </div>
        <div class="pagination">
          <button><i class="bi bi-arrow-left-short"></i></button>
          <p>01/05</p>
          <button><i class="bi bi-arrow-right-short"></i></button>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
h1{
    font-weight: 600;
    font-size: 36px;
    line-height: 57px;
    color: #010205;
    margin-bottom: 70px;
}
.flex{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 60px;
    .info{
        display: flex;
        gap: 20px;
        .img{
            width: 60px;
            height: 60px;
            background: #c1bfbf;
            border-radius: 50%;
        }
        h2{
            font-weight: 700;
            font-size: 20px;
            line-height: 30px;
            color: #010205;
            span{
                font-weight: 500;
                font-size: 13px;
                line-height: 18px;
                color: #878C91;
                margin-top: 5px;
            }
        }
    }
    .pagination{
        display: flex;
        align-items: center;
        gap: 20px;
        button{
            background: transparent;
            border: none;
            cursor: pointer;
            width: 80px;
            height: 40px;
            border: 1px solid rgba(87, 84, 84, 0.685);
            border-radius: 35px;
            &:focus{
                background: #000;
                color: #fff;
            }
            i{
                font-size: 28px;
                color: #878C91;
            }
        }
        p{
            font-weight: 500;
            font-size: 14px;
            line-height: 24px;
            color: #626364;
        }
    }
}
</style>
