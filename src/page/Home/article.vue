<template>
  <div class="container">
    <div class="uc-full-box">
      <div class="row">
        <div class="span4">
          <div class="uc-nav-box">
            <div class="box-hd">
              <h3 class="title">购物指南</h3>
            </div>
            <div class="box-bd">
              <ul class="uc-nav-list">
                <li><a v-on:click="clickSelect(1)" title="购物常见问题">购物常见问题</a></li>
                <li><a v-on:click="clickSelect(2)" title="密码服务">密码服务</a></li>
              </ul>
            </div>
          </div>
          <div class="uc-nav-box">
            <div class="box-hd">
              <h3 class="title">支付方式</h3>
            </div>
            <div class="box-bd">
              <ul class="uc-nav-list">
                <li><a v-on:click="clickSelect(3)" title="支付方式">支付方式</a></li>
                <li><a v-on:click="clickSelect(4)" title="支付常见问题">支付常见问题</a></li>
              </ul>
            </div>
          </div>
          <div class="uc-nav-box">
            <div class="box-hd">
              <h3 class="title">售后服务</h3>
            </div>
            <div class="box-bd">
              <ul class="uc-nav-list">
                <li><a v-on:click="clickSelect(5)" title="退换货流程">退换货流程</a></li>
                <li><a v-on:click="clickSelect(6)" title="退换货政策">退换货政策</a></li>
              </ul>
            </div>
          </div>
          <div class="uc-nav-box">
            <div class="box-hd">
              <h3 class="title">关于我们</h3>
            </div>
            <div class="box-bd">
              <ul class="uc-nav-list">
                <li><a v-on:click="clickSelect(7)" title="联系我们">联系我们</a></li>
                <li><a v-on:click="clickSelect(8)" title="关于我们">关于我们</a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">购物常见问题</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">1.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">哪些城市可以货到付款？订单完成后多长时间送达？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">我们目前尚未开通送货上门货到付款服务。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">2.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">如何订购？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">您可以通过拨打热线电话，联系我们的销售中心进行订购，也可以通过网站自行订购。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">3.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">如何付款？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">我们为您提供多种结算方式，您可以根据自身情况选择方便的方式支付货款：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">网银在线：指直接使用您的银行帐号或卡号进行网上在线付款，您的银行卡需开通网上银行支付的服务才能使用此种支付方式；消费者选择在线支付后，系统会弹出支付窗口，根据提示操作即可支付货款。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">4.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">配送费如何收取？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">订单购物金额满300元可免除配送费</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">5.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">订单生成后我需要多长时间内支付？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">选择网银在线支付、邮局汇款、银行电汇时，如果在以下三个规定时间内未收到您的款项，系统将自动取消订单。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">网上支付： 等待7天</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">邮局汇款： 等待7天</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">银行电汇： 等待7天</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">6.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">送货方式有哪几种？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">目前只支持EMS快递（款到发货）</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">7.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">我已经申请了退换货，你们快递什么时间上门来取货？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">目前，我们尚未开通了上门取货办理退换货的服务。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">8.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">如何获得发票？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">获得发票的方式：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">电话订购时，确认好所需要的产品后，请将您的发票抬头提供给销售人员，发票将随同商品一起送到。
                                        <br> 说明：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(1)我们提供的发票为专用发票，此发票可用作单位报销使用。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(2)一张订单对应一张发票，发票会随每次包裹一同发出。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(3)发票金额不能高于订单金额。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(4)非现金虚拟账户支付的金额和礼品卡支付的金额不开发票</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">例如：订单总金额为300元，使用礼品卡支付100元，选择开具发票后，发票金额为200元，不包含100元礼品卡支付的金额。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(5)补发票说明：请与客服人员联系</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">9.</span>
                  </b>
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">如何办理退款？</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">发生退货后款项我们会为您存入帐户中，以便于下次订购时使用，如您需办理退回，请联系我们的帮助中心，经客服工作人员核实后会为您办理退款，以下为退款方式及时间：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span style="font-size: 9.0pt;color:#333;">(1)银行转账：
                                        需提供您的银行帐户信息（开户行与支行、开户名、帐号）</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">正常退款周期：3~5个工作日</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(2)邮局退款： 需提供您的邮汇信息（收款人姓名、地址、邮编）</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">正常退款周期：7~15个工作日</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(3)网银退款： 货款会按原渠道退回。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">正常退款周期：1~3个工作日</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">温馨提示：如果使用建行卡及兴业银行卡通过网银在线支付，则退货时货款无法原渠道退回。</span>
                </p>
                <h2 style="margin:0cm;margin-bottom:.0001pt"><span
                  style="font-size:12.0pt;line-height:173%;color:red">支付方式<span lang="EN-US">
                                        </span></span></h2>
                <p style="margin:0cm;margin-bottom:.0001pt;line-height:18.75pt"><strong><span
                  style="color:#333333">网上第三方在线支付（包含有网上银行支付功能）</span></strong><span
                  lang="EN-US" style="font-size:9.0pt;color:#333333">
                                    </span></p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">顾客可通过本站验证的第三方支付平台进行在线支付，目前支持的支付平台有：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">①支付宝：您需要注册一个以您的地址为账户名的支付宝账户，然后使用您的银行帐号或卡号对该支付宝帐户进行充值，之后使用支付宝帐号进行支付。支付宝支持的银行请点击https://www.alipay.com查看(银行帐号需到当地柜台申请为网上银行功能才可以充值)</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">②QQ财付通：您需要注册一个以您的地址作为账户名的财付通账户，然后使用您的银行帐号或卡号对该财付通账户进行充值，之后使用财付通账户帐号进行支付。财付通账户支持的银行请点击https://www.tenpay.com查看</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">注：以上两种支付方式都包含有网上银行支付功能。</span>
                </p>
                <h2 style="margin:0cm;margin-bottom:.0001pt"><span
                  style="font-size:12.0pt;line-height:173%;color:red">退、换货政策<span lang="EN-US">
                                        </span></span></h2>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">1．本站为您提供</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">①在收到商品的30天内，产品没有污迹和破损且未经使用过；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②商品的外包装和吊牌卡都是完好的；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②商品的外包装和吊牌卡都是完好的；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">③产品未使用过的或者规范使用的，但出现质量问题的；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">出现以上三种情况我们可以无条件退换货</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">2．本商城所有产品的图片及信息仅供参照，商品将以实物为准。因拍摄灯光及不同显示器色差等问题可能造成商品图片与实物有一定色差，不属质量问题；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">3．本商城保留了您对部分产品订购数量的限制权。在您订购商品时，您对提供给我们所有信息的真实性负责。另外，本商城特价销售的产品，售完即止，这类产品除非存在质量问题，一律不得退换，敬请谅解。另外，涉及到礼品或赠品也一律不能退换，敬请谅解。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">4．正常情况下，您的一张订单只能进行一次退换货操作，所以为了您的权益，请您考虑周全后与我们联系退货事宜。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">5．退换货的邮寄方式采用EMS快递更为安全，以确保本商城能收到您需退换的货物，并尽快为您办理后续事宜。如使用不可查询的邮寄方式退货，发生商品遗失、破损、误送等情况，成都市高新区府城大道西段505号1幢2单元20层7号不承担责任，敬请谅解。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">6．关于退换货涉及的运费规定：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">①发生退货时，由于客户自身原因造成的退货，我们只退回商品的货款金额，原订单如有相应运费（以本商城当时邮寄费用为准）恕不退还；其中退货运费由客户付；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">②如因本商城自身的原因或商品质量问题而造成的退货，我们将退还您商品的货款及相应运费(按快递或包裹单上实际的配送金额计算，如报销凭证丢失，则根据本商城订单运费的最低收取标准报销10元，报销的运费将存入您在本商城的虚拟账户中，您可以进入“我的帐户”进行查询。)</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">③如因本商城本身的原因或商品质量问题的而造成的换货本商城将承担相应运费；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">④由于客户对非组合商品或组合产品的颜色、材质、规格等不满意需要换货的，发生的相应运费需由客户承担。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">7．本商城在收到退换货包裹后进行品质检验，检验通过后即以您选择的方式返还您的退货金额或配送更换后的产品。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">8．您可以选择以下3种方式中的任意一种来收取退款</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span style="font-size: 9.0pt;color:#333;">①．直接划转至您的银行帐号
                                        （需要您提供您的银行户名、卡号及开户行）；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②．采用邮政汇款方式退款 （需要您提供邮政地址、邮编和收件人姓名）；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">③．存入您在本商城的帐户，以便下次订购使用。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">9．关于退换货涉及的运费规定：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">①．请直接联系我们的客服人员；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②．在用户中心直接填写并提交退换货资料；</span>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">密码服务</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <h4 style="margin:0cm;margin-bottom:.0001pt;line-height:18.75pt;background:white"><span
                  style="font-size:9.0pt;mso-bidi-font-size:10.0pt;color:#333333">如果您忘记了账号密码，别担心，您可以通过点击<span><br>
                                            1</span><span
                  style="font-size:9.0pt;mso-bidi-font-size:10.0pt;color:#333333;">、进入到找回密码页面后<span
                  lang="EN-US">,</span>如果您曾设置了密保，那么直接在页面中输入密保问题与答案便可找回。<span
                  lang="EN-US"><br>
                                                2</span>、如果您没有设置密保，您也可以联系客服帮您重设密码。<span lang="EN-US">
                                            </span></span></span></h4>

              </div>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">支付方式</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <b>
                    <span style="font-size: 9.0pt;color:#333;">网上第三方在线支付（包含有网上银行支付功能）</span>
                  </b>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">顾客可通过本站验证的第三方支付平台进行在线支付，目前支持的支付平台有：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">①支付宝：您需要注册一个以您的Email地址为账户名的支付宝账户，然后使用您的银行帐号或卡号对该支付宝帐户进行充值，之后使用支付宝帐号进行支付。支付宝支持的银行请点击https://www.alipay.com查看(银行帐号需到当地柜台申请为网上银行功能才可以充值)</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">②QQ财付通：您需要注册一个以您的QQ号或Email地址作为账户名的财付通账户，然后使用您的银行帐号或卡号对该财付通账户进行充值，之后使用财付通账户帐号进行支付。财付通账户支持的银行请点击https://www.tenpay.com查看</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">注：以上两种支付方式都包含有网上银行支付功能。</span>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">支付常见问题</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">1、网上支付确认</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">如果出现信用卡超额透支、存折余额不足、意外断线等导致支付不成功，请您登录本商城帐户，在订单支付管理中找到该张未支付成功的订单，重新完成支付。://www.alipay.com查看(银行帐号需到当地柜台申请为网上银行功能才可以充值)</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">2、邮局汇款到账时间　://www.tenpay.com查看</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">支付方式/到款时间 需要向我们提供的信息</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span style="font-size: 9.0pt;color:#333;">邮局普通汇款2-5个工作日
                                        订单号、汇款金额、汇款人姓名、汇款时间、汇款地址</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span style="font-size: 9.0pt;color:#333;">邮局电子汇款2-3个工作日
                                        订单号、汇款金额、汇款人姓名、汇款时间、汇款地址</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">从理论上说，电子汇款的数据传输只需24小时，但邮局还需要经过打印、整理、汇兑等过程，所以我们收到汇款单一般需要2-5天左右；如果您的货款汇出7天后我们还没有收到，请将汇款单收据传真给我们进行查询或者您可以到当地邮局凭汇款收据进行查询。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">3、实际汇款金额与应汇款金额不符</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">系统将无法处理您的订单，请您尽快补足货款以便我们尽快为您发货。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">4、邮局汇款单招领</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">自您办理邮局汇款手续之日起2-5天内，我们就会收到您的款项，但有一些特殊情况，可能会影响订单的正常处理：汇款单中未注明订单号（或订单号有误）、有效联系人和联系方式，汇款人姓名、汇款地址与订单中的收货人姓名、收货地址不符。若出现以上情况，请尽快与我们联系。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">5、订单生成后我需要在多长时间内支付货款？</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">邮局汇款：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">自您支付方式为邮局汇款的订单我们会为您保留7天，为确保您所订购的产品库存情况，在订单生成后需要您立即汇款，7天内收到您的汇款后我们会为您安排货。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">正常退款周期：3-5个工作日</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(2)邮局退款： 需提供您的邮汇信息（收款人姓名、地址、邮编）</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">正常退款周期：7-15个工作日</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">(3)网银退款： 货款会按原渠道退回。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">正常退款周期：1-3个工作日</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                                    <span
                                      style="font-size: 9.0pt;color:#333;">温馨提示：如果使用建行卡及兴业银行卡通过网银在线支付，则退货时货款无法原渠道退回。</span>
                </p>
              </div>
            </div>
          </div>
        </div>

        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">退换货流程</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;<img src="../../assets/icon/process.png" width="558" height="171" alt=""></p>
              </div>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">退换货政策</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">1．本站为您提供30天的质量满意保证期</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">①在收到商品的30天内，产品没有污迹和破损且未经使用过；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②商品的外包装和吊牌卡都是完好的；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">③产品未使用过的或者规范使用的，但出现质量问题的；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">2．本商城所有产品的图片及信息仅供参照，商品将以实物为准。因拍摄灯光及不同显示器色差等问题可能造成商品图片与实物有一定色差，不属质量问题；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">3．本商城保留了您对部分产品订购数量的限制权。在您订购商品时，您对提供给我们所有信息的真实性负责。另外，本商城特价销售的产品，售完即止，这类产品除非存在质量问题，一律不得退换，敬请谅解。另外，涉及到礼品或赠品也一律不能退换，敬请谅解。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">4．正常情况下，您的一张订单只能进行一次退换货操作，所以为了您的权益，请您考虑周全后与我们联系退货事宜。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">5．退换货的邮寄方式采用EMS快递更为安全，以确保本商城能收到您需退换的货物，并尽快为您办理后续事宜。如使用不可查询的邮寄方式退货，发生商品遗失、破损、误送等情况，成都市高新区府城大道西段505号1幢2单元20层7号不承担责任，敬请谅解。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">6．关于退换货涉及的运费规定：</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">①发生退货时，由于客户自身原因造成的退货，我们只退回商品的货款金额，原订单如有相应运费（以本商城当时邮寄费用为准）恕不退还；其中退货运费由客户付；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②如因本商城自身的原因或商品质量问题而造成的退货，我们将退还您商品的货款及相应运费(按快递或包裹单上实际的配送金额计算，如报销凭证丢失，则根据本商城订单运费的最低收取标准报销10元，报销的运费将存入您在本商城的虚拟账户中，您可以进入"我的帐户"进行查询。)；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">③如因本商城本身的原因或商品质量问题的而造成的换货，本商城将承担相应运费；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">④由于客户对非组合商品或组合产品的颜色、材质、规格等不满意需要换货的，发生的相应运费需由客户承担。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">7．本商城在收到退换货包裹后进行品质检验，检验通过后即以您选择的方式返还您的退货金额或配送更换后的产品。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">8．您可以选择以下3种方式中的任意一种来收取退款</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">①．直接划转至您的银行帐号 （需要您提供您的银行户名、卡号及开户行）；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②．采用邮政汇款方式退款 （需要您提供邮政地址、邮编和收件人姓名）；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">③．存入您在本商城的帐户，以便下次订购使用。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">退款将在我们确认收到你退还的货物并通过质检后，立即执行。</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">9．如何提交退换货资料？</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">①．请直接联系我们的客服人员；</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">②．在用户中心直接填写并提交退换货资料；</span>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">联系我们</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">公司名：成都市高新区府城大道西段505号1幢2单元20层7号</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">地址：成都市高新区府城大道西段505号</span>
                 
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                   <span style="font-size: 9.0pt;color:#333;">售后电话：028-67561169</span>
                </p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                    <span style="font-size: 9.0pt;color:#333;">E-MAIl：haoyunyouxuan@126.com</span>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="span16 content-right" style="display: none;">
          <div class="xm-line-box uc-box">
            <div class="box-hd">
              <h3 class="title">关于我们</h3>
            </div>
            <div class="bd" style="height:100%;">
              <div class="m_reserver">
                <p>&nbsp;</p>
                <p class="MsoNormal" style="text-align:left;line-height:18.75pt">
                  <span style="font-size: 9.0pt;color:#333;">成都市高新区府城大道西段505号1幢2单元20层7号于2017年1月成立，总部位于成都，注册资本1000万元。是一家拥有来自互联网行业资深人士和优秀的行业技术专家组成的优质团队。公司专注于移动终端应用软件开发，互联网技术服务和平台开发支持，手机销售、是一家高科技企业。同时，在政府关系、产品开发、技术创新、市场开拓和企业管理等方面都具有丰富的经验和资源。是一个为广大用户提供灵活、自助、安全的信息服务平台。自公司成立以来，秉承成就客户、极致服务、实事求是、开放分享的核心价值观，以交易服务改变生活为使命，致力成为世界一流的交易服务平台。</span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'article',
    methods: {
      clickSelect (number) {
        let aBox = document.getElementsByClassName('content-right')
        for (let i = 0; i < aBox.length; i++) {
          if (parseInt(number) === i + 1) {
            aBox[i].style.display = 'block'
          } else {
            aBox[i].style.display = 'none'
          }
        }
      }
    },
    mounted () {
      let number = window.location.hash.split('?id=')[1]
      this.clickSelect(number)
    }
  }
</script>

<style scoped>
  @import "../../assets/style/footer/index.css";
  @import "../../assets/style/footer/list.css";
</style>
