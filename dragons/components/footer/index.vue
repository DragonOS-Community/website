<template>
  <div>
    <div class="footer">
      <div class="footer-container">
        <div class="footerList">
          <div class="footerItem">
            <h4>DragonOS</h4>
            <ul class="footerItemCon">
              <li>Copyright ©2022 longjin & All contributors of DragonOS.
                All rights reserved.</li>
            </ul>
          </div>
        </div>
        <div class="copyright">
          <ul class="helpLink">
            <li>
              关于我们
              <span class="space"></span>
            </li>
            <li>
              联系我们
              <span class="space"></span>
            </li>
            <li>
              友情链接
              <span class="space"></span>
            </li>
          </ul>
          <p>Edit this page on GitHub</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  //给组件起一个名字,开发者工具中显示这个组件的时候，显示的就是这个名字
  name: "Footer",
};
</script>

<style scoped lang="less">
.footer {
  left: 0px;
  top: 2334px;
 width: 1840px;
  height: 262px;
  background: linear-gradient(90deg, rgba(67, 67, 67, 1) 0%, rgba(0, 0, 0, 1) 100%);


  .footer-container {
    width: 1200px;
    margin: 0 auto;
    padding: 0 15px;

    .footerList {
      padding: 20px;
      border-bottom: 1px solid #e4e1e1;
      border-top: 1px solid #e4e1e1;
      overflow: hidden;
      padding-left: 40px;

      .footerItem {
        left: 632px;
        top: 2374px;
        width: 154px;
        height: 41px;
        color: rgba(255, 255, 255, 1);
        letter-spacing: 2px;
        font-size: 28px;
        font-weight: 700;

        h4 {
          font-size: 14px;
        }

        .footerItemCon {
          li {
            left: 408px;
            top: 2449px;
            width: 629px;
            height: 66px;
            color: rgba(255, 255, 255, 1);
            letter-spacing: 1px;
            font-size: 22px;
            font-weight: 400;

          }
        }

        &:last-child img {
          width: 161px;
          height: 66px;
        }
      }
    }

    .copyright {
      padding: 20px;

      .helpLink {
        text-align: center;

        li {
          display: inline;
          color: rgba(255, 255, 255, 1);

          .space {
            border-left: 1px solid rgb(255, 254, 254);
            width: 1px;
            height: 13px;
            background: rgb(255, 253, 253);
            margin: 8px 10px;
          }
        }
      }

      p {
        margin: 10px 0;
        text-align: center;
        color: rgba(255, 255, 255, 1);
      }
    }
  }
}
</style>
