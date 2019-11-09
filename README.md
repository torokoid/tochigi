# tochigi
<!DOCTYPE html>
<!-- saved from url=(0054)https://naoyu.net/sample/scroll-background-fadein.html -->
<html lang="ja"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Scroll Background Fadein | naoyu.net</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<!-- Global site tag (gtag.js) - Google Analytics -->
<script src="/osd.js"></script>
    <script src="ca-pub-7408088410773034.js"></script>
    <script type="text/javascript" async="" src="analytics.js"></script>
    <script async="" src="js"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-10603270-10');
</script>
<script src="jquery.min.js"></script>
<style>
/* init */
.background {
    top: 0;
    left: 0;
    right: 0;
    height: 100%;
    position: fixed;
    background-position: center center;
    opacity: 0;
-webkit-background-size: cover;
        background-size: cover;
-webkit-transition: all 0.5s ease 0s;
   -moz-transition: all 0.5s ease 0s;
        transition: all 0.5s ease 0s;
}
.show .background { opacity: 1;}
.contents .wrap {
    padding: 40vh 0 60vh;
    position: relative;
    z-index: 2;
}
  p {
color: #fffafa;
font-size: 1.5em;
 }
<!--
 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
/* design*/
#content01_bg {background-image: url(https://torokoid.github.io/shiobara/20191109_015.JPG);}
#content02_bg {background-image: url(https://torokoid.github.io/greenpark/20190928_015.JPG);}
  /*
#content03_bg {background-image: url(https://torokoid.github.io/oizumi2010/20100828_031.JPG);}
#content04_bg {background-image: url(https://torokoid.github.io/izumikai/20101024_020.JPG);}
#content05_bg {background-image: url(https://torokoid.github.io/mascot/20190521_009.JPG);}
#content06_bg {background-image: url(https://torokoid.github.io/ensoku/20190527_001.JPG);}   
#content07_bg {background-image: url(https://torokoid.github.io/1978/20190607_039.JPG);}
  */

#content01 .wrap { background-color: rgba(255,0,0,0.2);}
#content02 .wrap { background-color: rgba(0,255,0,0.2);}
/*
#content03 .wrap { background-color: rgba(0,0,255,0.2);}
#content04 .wrap { background-color: rgba(255,0,0,0.2);}
#content05 .wrap { background-color: rgba(0,255,0,0.2);}
#content06 .wrap { background-color: rgba(0,0,255,0.2);}
#content07 .wrap { background-color: rgba(255,0,0,0.2);}
*/

.text-box {
    padding: 50px 25px;
    max-width: 640px;
    background-color: rgba(0,0,0,0.5);
    color: #fff;
}
#content02 .text-box {
    margin-left: auto;
}
#content04 .text-box {
    margin-left: auto;
}
#content06 .text-box {
    margin-left: auto;
}
.text-box .catch {
    margin: 0 0 10px;
    font-size: 40px;
}
.text-box .copy {
    margin: 0;
    line-height: 2;
}
a{color: #fff;}
    
</style>
<link rel="preload" href="f.txt" as="script">
    <script type="text/javascript" src="f.txt"></script>
    <link rel="preload" href="f(1).txt" as="script">
    <script type="text/javascript" src="f(1).txt"></script>
    <link rel="preload" href="https://pagead2.googlesyndication.com/pagead/js/r20190424/r20190131/show_ads_impl.js" as="script">
    </head>
<body>
<section id="contents">
    <div id="content01" class="contents show">
        <div id="content01_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">shiobara</p>
                <a href="https://torokoid.github.io/shiobara">2019/11/09リンク</a>
            </div>
        </div>
    </div><!-- content01 -->
    <div id="content02" class="contents">
        <div id="content02_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">greenpark</p>
                <a href="https://torokoid.github.io/greenpark">2019/09/28リンク</a>
            </div>
        </div>
    </div><!-- content02 -->
    <!--
    <div id="content03" class="contents">
        <div id="content03_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2010年同期会</p>
                <a href="https://torokoid.github.io/oizumi2010">2010年同期会のHPリンク</a>
             </div>
        </div>
    </div><!-- content03 -->
  <!--
<div id="content04" class="contents">
        <div id="content04_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2010年いずみ会</p>
                <a href="https://torokoid.github.io/izumikai">2010年いずみ会のHPリンク</a>
             </div>
        </div>
    </div><!-- content04 -->
  <!--
<div id="content05" class="contents">
        <div id="content05_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">船津さん、片桐さん提供、<br>  体育祭マスコット</p>
                <a href="https://torokoid.github.io/mascot">体育祭マスコット写真、リンク</a>
            </div>
        </div> 
    </div><!-- content05 -->
  <!--
<div id="content06" class="contents">
        <div id="content06_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">船津さん提供、遠足の写真<br>宮下さん、東さん提供、<br>スキーの写真</p>
                <a href="https://torokoid.github.io/ensoku">遠足の写真、リンク</a>
            </div>
        </div> 
    </div><!-- content06 -->
  <!--
<div id="content07" class="contents">
        <div id="content07_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">１組田中さん、他提供、<br>  大泉高校卒業アルバム</p>
                <a href="https://torokoid.github.io/1978">卒業アルバム、リンク</a>
            </div>
        </div> 
    </div><!-- content07 -->

<!--
                <div class="ad" style="text-align: center;">
                <script async="" src="./Scroll_files/f(2).txt"></script>
                -->
                <!-- naoyunet sampleページ -->
                <!--
                <ins class="adsbygoogle" style="display: block; height: 59px; width: 640px;" data-ad-client="ca-pub-7408088410773034" data-ad-slot="5732846980" data-ad-format="auto" data-full-width-responsive="true" data-adsbygoogle-status="done"><ins id="aswift_1_expand" style="display: inline-table; border: none; height: 59px; margin: 0px; padding: 0px; position: relative; visibility: visible; width: 640px; background-color: transparent;"><ins id="aswift_1_anchor" style="display: block; border: none; height: 59px; margin: 0px; padding: 0px; position: relative; visibility: visible; width: 640px; background-color: transparent; overflow: hidden;"><iframe width="640" height="59" frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" allowfullscreen="true" onload="var i=this.id,s=window.google_iframe_oncopy,H=s&amp;&amp;s.handlers,h=H&amp;&amp;H[i],w=this.contentWindow,d;try{d=w.document}catch(e){}if(h&amp;&amp;d&amp;&amp;(!d.body||!d.body.firstChild)){if(h.call){setTimeout(h,0)}else if(h.match){try{h=s.upd(h,i)}catch(e){}w.location.replace(h)}}" id="aswift_1" name="aswift_1" style="left: 0px; position: absolute; top: 0px; border: 0px; width: 640px; height: 59px;" src="./Scroll_files/saved_resource.html"></iframe></ins></ins></ins>
                -->
                <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
                </div>
<!-- フッタ -->
 <footer>
 <span class="white">Copyright 2019/05/01 Pe-Young(S.Hada)</span>
 </footer>
 <!--           </div>
        </div>
    </div><!-- content03 -->
</section>

<script>
$(function(){
    $('.contents').each(function(i, elem){
        var contentsPOS = $(elem).offset().top;
        $(window).on('load scroll resize', function(){
            var winHeight = $(window).height();
            var scrollTop = $(window).scrollTop();
            var showClass = 'show';
            var timing = 100;
            if (scrollTop >= contentsPOS - winHeight + timing){
              $(elem).addClass(showClass);
            } else {
              $(elem).removeClass(showClass);
            }
        });
    });
});
</script>


<ins class="adsbygoogle adsbygoogle-noablate" data-adsbygoogle-status="done" style="display: none !important;"><ins id="aswift_0_expand" style="display:inline-table;border:none;height:0px;margin:0;padding:0;position:relative;visibility:visible;width:0px;background-color:transparent;"><ins id="aswift_0_anchor" style="display:block;border:none;height:0px;margin:0;padding:0;position:relative;visibility:visible;width:0px;background-color:transparent;"><iframe frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" allowfullscreen="true" onload="var i=this.id,s=window.google_iframe_oncopy,H=s&amp;&amp;s.handlers,h=H&amp;&amp;H[i],w=this.contentWindow,d;try{d=w.document}catch(e){}if(h&amp;&amp;d&amp;&amp;(!d.body||!d.body.firstChild)){if(h.call){setTimeout(h,0)}else if(h.match){try{h=s.upd(h,i)}catch(e){}w.location.replace(h)}}" id="aswift_0" name="aswift_0" style="left:0;position:absolute;top:0;border:0px;width:0px;height:0px;" src="./Scroll_files/saved_resource(1).html"></iframe></ins></ins></ins><iframe id="google_osd_static_frame_1872476073822" name="google_osd_static_frame" style="display: none; width: 0px; height: 0px;" src="./Scroll_files/saved_resource(2).html"></iframe></body><iframe id="google_shimpl" style="display: none;" src="./Scroll_files/saved_resource(3).html"></iframe><iframe id="google_esf" name="google_esf" src="./Scroll_files/zrt_lookup.html" data-ad-client="ca-pub-7408088410773034" style="display: none;"></iframe>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 
