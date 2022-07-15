<template>
  <div class="rank">
    <div class="tab">
      <div class="tab-tit clearfix">
        
        <a href="javascript:;">
         
          <p class="text">参与开发</p>
        </a>
      </div>
    </div>
    <div class="content">
      <ul>
        <li>
          <div class="tab-info">
              <div class="info-title">
                <a href="#"
                  >123</a
                >
              </div>
              <p class="info-price">PR</p>
            </div>
          <div class="img-item">
            
            <div class="tab-info">
              <div class="info-title">
                <a href="#"
                  >66</a
                >
              </div>
              <p class="info-price">Starts</p>
            </div>
          </div>
          <div class="img-item">
            
            <div class="tab-info">
              <div class="info-title">
                <a href="#"
                  >11</a
                >
              </div>
              <p class="info-price">Forks</p>
            </div>
          </div>
          <div class="img-item">
            
            <div class="tab-info">
              <div class="info-title">
                <a href="#"
                  >23</a
                >
              </div>
              <p class="info-price">贡献者</p>
            </div>
          </div>
          <div class="img-item">
           
            <div class="tab-info">
              <div class="info-title">
                <a href="#"
                  >1</a
                >
              </div>
              <p class="info-price">Releases</p>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
};
</script>

<style scoped lang="less">
.rank {
  width:1840px;
  margin: 0 auto;
  background: linear-gradient(90deg, rgba(22, 217, 227, 1) 0%, rgba(48, 199, 236, 1) 47%, rgba(70, 174, 247, 1) 100%);

  .tab {
    margin: 0 auto;
    overflow: hidden;
    width: 312px;

    .tab-tit {
      text-align: center;

      a {
        display: block;
        padding: 0 18px;
        float: left;
        text-decoration: none;
        font-size: 16px;
        color: #999;

        p {
          margin: 5px 0;
        }

        .img {
          i {
            width: 35px;
            height: 35px;
            display: block;
            background: url(./images/bg0.png);
            margin-left: 10px;
          }
        }

        .text {
          line-height: 28px;
        }
      }

      .on {
        color: #e60012;

        .img {
          i {
            background-position: -35px 0;
          }
        }
      }
    }
  }

  .content {
    overflow: hidden;
    padding: 10px;

    ul {
      li {
        overflow: hidden;
        list-style: none;
        line-height: 18px;

        .img-item {
          border: 1px solid #e1251b;
          width: 269px;
          float: left;
          overflow: hidden;
          margin: 0 12px 10px;
          background: #fff;

          .tab-pic {
            width: 230px;
            height: 210px;
            overflow: hidden;
            text-align: center;
            margin: 5px auto 18px;

            a {
              img {
                width: 200px;
                height: 200px;
              }
            }
          }

          .tab-info {
            

            .info-title {
              height: 50px;
              line-height: 28px;
              overflow: hidden;
              margin: 0 auto;
              padding-left: 10px;

              a {
                color: #333;
                text-decoration: none;
              }
            }

            .info-price {
              font-size: 20px;
              color: #e1251b;
              height: 35px;
              padding-left: 10px;
              display: block;
              line-height: 24px;
              margin: 10px auto 0;
            }
          }
        }
      }
    }
  }
}
</style>
