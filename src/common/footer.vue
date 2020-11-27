<template>
  <div class="footer site-footer">
    <div class="container">
      <div class="footer-service">
        <ul class="list-service clearfix">
          <li><a target="_blank"> <i class="iconfont"></i> <strong>保修服务</strong> <span>承诺全国网点保修</span> </a></li>
          <li><a target="_blank"> <i class="iconfont"></i> <strong>发货时间</strong> <span>48小时内准时发货</span> </a></li>
          <li><a target="_blank"> <i class="iconfont"></i> <strong>质量保证</strong> <span>15天质量问题包换</span> </a></li>
          <li><a target="_blank"> <i class="iconfont"></i> <strong>满额送礼</strong> <span>购物满额就送礼包</span> </a></li>
          <li><a target="_blank"> <i class="iconfont"></i> <strong>品牌认证</strong> <span>国家商品认证有保障</span> </a></li>
        </ul>
      </div>
      <div class="footer-links clearfix">
        <dl class="col-links col-links-first">
          <dt>购物指南</dt>
          <dd><router-link to="/article?id=1">购物常见问题</router-link></dd>
          <dd><router-link to="/article?id=2">密码服务</router-link></dd>
        </dl>
        <dl class="col-links ">
          <dt>支付方式</dt>
          <dd><router-link to="/article?id=3">支付方式</router-link></dd>
          <dd><router-link to="/article?id=4">支付常见问题</router-link></dd>
        </dl>
        <dl class="col-links ">
          <dt>售后服务</dt>
          <dd><router-link to="/article?id=5">退换货流程</router-link></dd>
          <dd><router-link to="/article?id=6">退换货政策</router-link></dd>
        </dl>
        <dl class="col-links ">
          <dt>关于我们</dt>
          <dd><router-link to="/article?id=7">联系我们</router-link></dd>
          <dd><router-link to="/article?id=8">关于我们</router-link></dd>
        </dl>
        <div class="col-contact">
          <p class="phone"></p>
          <p>周一至周日 8:00-18:00<br>（仅收市话费）</p>
          <p>联系电话：18180584739</p>        
        </div>
      </div>
    </div>
    <div class="container">
      <div class="cop">
        <h4>© 2005-2020 成都市高新区府城大道西段505号1幢2单元20层7号 版权所有，并保留所有权利。</h4>
      </div>
      <div class="cop">
        <h4>地址：成都市高新区吉泰五路118号3栋10层2号 公安备案号:
          <a href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=51019002002934" target="_blank">51019002002934</a>
        </h4>
      </div>
      <div class="cop">
        <a href="http://beian.miit.gov.cn" target="_blank">
          <span >蜀ICP备18014871号</span>
        </a>
      </div>
    </div>
  </div>
</template>
<script>

</script>
<style lang="scss" rel="stylesheet/scss" scoped>
  @import "../assets/style/footer/index.css";
  .footer {
    padding: 12px 0 10px;
    border-top: 1px solid #e6e6e6;
    background: #fafafa;
    margin-top: 60px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .container {
    width: 1220px;
    text-align: center;
  }

  .cop {
    clear: both;
    padding: 6px 0 0;
    //height: 15px;
    align-content: center;
  }

  input:focus {
    outline: 0
  }

  i {
    display: inline-block;
    vertical-align: middle;
    background-repeat: no-repeat;
  }

  body, div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, code, form, fieldset, legend, input, textarea, p, blockquote, th, td, hr, button, article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
    margin: 0;
    padding: 0;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0)
  }

  article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
    display: block;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0)
  }

  audio, canvas, video {
    display: inline-block;
    *display: inline;
    *zoom: 1
  }

  table {
    border-collapse: collapse;
    border-spacing: 0
  }

  th {
    text-align: inherit
  }

  fieldset, img {
    border: 0
  }

  iframe {
    display: block
  }

  abbr, acronym {
    border: 0;
    font-variant: normal
  }

  del {
    text-decoration: line-through
  }

  address, caption, cite, code, dfn, th, var, i, b {
    font-style: normal;
    font-weight: 500
  }

  em {
    font-style: normal;
  }

  ol, ul {
    list-style: none
  }

  .site-footer {
    margin-top: 50px;
    color: #333;
    background: #fafafa;
  }
</style>
