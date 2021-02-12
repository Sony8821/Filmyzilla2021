<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateVersion='1.0.0' expr:class='data:blog.languageDirection' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta content='width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1' name='viewport'/>
    <title><data:view.title.escaped/></title>
    <b:include data='blog' name='all-head-content'/>
 <b:if cond='data:view.isHomepage'>
 <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
    </b:if>
    <!-- Google Fonts -->
    <link href='//fonts.googleapis.com/css?family=PT+Sans:400,400i,700,700i' media='all' rel='stylesheet' type='text/css'/>
    <link href='https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css' rel='stylesheet'/>
 
<!-- Template Style CSS -->
<b:skin version='1.0.0'><![CDATA[/* 
-----------------------------------------------
Blogger Template Style
Name:        Downloadhub
Version:     Free Version
Author:      SoraTemplates
Author Url:  https://www.soratemplates.com/
----------------------------------------------- */

/*
<!-- Variable definitions -->
<Variable name="keycolor" description="Main Color" type="color" hideEditor="true" default="#008000" value="#008000"/>
<Variable name="followByEmail" description="Follow By Email Text" type="string" hideEditor="true" default="Get all latest content delivered straight to your inbox." value="Get all latest content delivered straight to your inbox."/>
<Variable name="body.font" description="Body Font" type="font" hideEditor="true" default="PT Sans, sans-serif" value="PT Sans, sans-serif"/>
<Variable name="title.font" description="Title Font" type="font" hideEditor="true" default="PT Sans, sans-serif" value="PT Sans, sans-serif"/>


<Group description="Theme Body" selector="body">
  <Variable name="body.background.color" description="Body Background Color" type="color" default="#f8f8f8"  value="#f8f8f8"/>
  <Variable name="body.background" description="Background" type="background" color="#f8f8f8" default="$(color) url() repeat scroll top left" value="$(color) url() repeat scroll top left"/>
  <Variable name="body.text.color" description="Text Color" type="color" default="#888888"  value="#888888"/>
</Group>

<Group description="Theme Colors" selector="body">
  <Variable name="header.bg.color" description="Header Beackground" type="color" default="#008000" value="#008000"/>
  <Variable name="main.color" description="Theme Color" type="color" default="#008000" value="#008000"/>
  <Variable name="main.dark.color" description="Dark Color" type="color" default="#111111" value="#111111"/>
  <Variable name="menu.color" description="Menu Color" type="color" default="#ffffff" value="#ffffff"/>
  <Variable name="menu.hover.color" description="Menu Hover Color" type="color" default="#999999" value="#999999"/>
<Variable name="post.title.color" description="Post Title Color" type="color" default="#ffffff" value="#ffffff"/>
  <Variable name="title.color" description="Title Color" type="color" default="#111111" value="#111111"/>
  <Variable name="title.color.lite" description="Title Color Lite" type="color" default="#ffffff" value="#ffffff"/>
  <Variable name="meta.color" description="Meta Color" type="color" default="#aaaaaa" value="#aaaaaa"/>
</Group>
 
*/

 a,abbr,acronym,address,applet,b,big,blockquote,body,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,form,h1,h2,h3,h4,h5,h6,html,i,iframe,img,ins,kbd,label,legend,li,object,p,pre,q,s,samp,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,tr,tt,u,ul,var{padding:0;border:0;outline:0;vertical-align:baseline;background:0 0;text-decoration:none }form,textarea,input,button{-webkit-appearance:none;-moz-appearance:none;appearance:none;border-radius:0 }dl,ul{list-style-position:inside;font-weight:400;list-style:none }ul li{list-style:none }caption,th{text-align:center }img{border:none;position:relative }a,a:visited{text-decoration:none }.clearfix{clear:both }.section,.widget,.widget ul{margin:0;padding:0 }a{color:$(title.color) }a:hover{color:$(main.color) }a img{border:0 }abbr{text-decoration:none }.CSS_LIGHTBOX{z-index:999999!important }.separator a{clear:none!important;float:none!important;margin-left:0!important;margin-right:0!important }#navbar-iframe,.widget-item-control,a.quickedit,.home-link,.feed-links{display:none!important }.center{display:table;margin:0 auto;position:relative }.widget > h2,.widget > h3{display:none }body{background:$(body.background);background-color:$(body.background.color);font-family:$(body.font);font-size:14px;font-weight:400;color:$(body.text.color);word-wrap:break-word;margin:0;padding:0 }#outer-wrapper{margin:0 auto;background-color:#fff;box-shadow:0 0 5px rgba(0,0,0,.1) }.index #outer-wrapper {background-color:#eee;}.row{width:1000px }#content-wrapper{margin:40px auto;}#content-wrapper > .container{margin:0 -20px }#main-wrapper{float:left;overflow:hidden;width:66.66666667%;box-sizing:border-box;padding:0 20px }#sidebar-wrapper{float:right;overflow:hidden;width:33.33333333%;box-sizing:border-box;padding:0 20px }.index #main-wrapper{width:100% }.index #sidebar-wrapper{display:none }.post-image-wrap{position:relative;display:block }.post-image-link,.about-author .avatar-container,.comments .avatar-image-container{background-color:#f9f9f9;color:transparent!important }.post-thumb{display:block;position:relative;width:100%;height:100%;object-fit:cover;z-index:1;transition:opacity .17s ease }.post-image-link:hover .post-thumb{opacity:.8 }.social a:before{display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400 }.social .facebook a:before{content:"\f230" }.social .facebook-f a:before{content:"\f09a" }.social .twitter a:before{content:"\f099" }.social .gplus a:before{content:"\f0d5" }.social .rss a:before{content:"\f09e" }.social .youtube a:before{content:"\f16a" }.social .skype a:before{content:"\f17e" }.social .stumbleupon a:before{content:"\f1a4" }.social .tumblr a:before{content:"\f173" }.social .vk a:before{content:"\f189" }.social .stack-overflow a:before{content:"\f16c" }.social .github a:before{content:"\f09b" }.social .linkedin a:before{content:"\f0e1" }.social .dribbble a:before{content:"\f17d" }.social .soundcloud a:before{content:"\f1be" }.social .behance a:before{content:"\f1b4" }.social .digg a:before{content:"\f1a6" }.social .instagram a:before{content:"\f16d" }.social .pinterest a:before{content:"\f0d2" }.social .pinterest-p a:before{content:"\f231" }.social .twitch a:before{content:"\f1e8" }.social .delicious a:before{content:"\f1a5" }.social .codepen a:before{content:"\f1cb" }.social .reddit a:before{content:"\f1a1" }.social .whatsapp a:before{content:"\f232" }.social .snapchat a:before{content:"\f2ac" }.social .email a:before{content:"\f0e0" }.social .external-link a:before{content:"\f14c" }.social-color .facebook a,.social-color .facebook-f a{background-color:#3b5999 }.social-color .twitter a{background-color:#00acee }.social-color .gplus a{background-color:#db4a39 }.social-color .youtube a{background-color:#db4a39 }.social-color .instagram a{background:linear-gradient(15deg,#ffb13d,#dd277b,#4d5ed4) }.social-color .pinterest a,.social-color .pinterest-p a{background-color:#ca2127 }.social-color .dribbble a{background-color:#ea4c89 }.social-color .linkedin a{background-color:#0077b5 }.social-color .tumblr a{background-color:#365069 }.social-color .twitch a{background-color:#6441a5 }.social-color .rss a{background-color:#ffc200 }.social-color .skype a{background-color:#00aff0 }.social-color .stumbleupon a{background-color:#eb4823 }.social-color .vk a{background-color:#4a76a8 }.social-color .stack-overflow a{background-color:#f48024 }.social-color .github a{background-color:#24292e }.social-color .soundcloud a{background:linear-gradient(#ff7400,#ff3400) }.social-color .behance a{background-color:#191919 }.social-color .digg a{background-color:#1b1a19 }.social-color .delicious a{background-color:#0076e8 }.social-color .codepen a{background-color:#000 }.social-color .reddit a{background-color:#ff4500 }.social-color .whatsapp a{background-color:#3fbb50 }.social-color .snapchat a{background-color:#ffe700 }.social-color .email a{background-color:#888 }.social-color .external-link a{background-color:$(main.color) }.social-text .facebook a:after,.social-text .facebook-f a:after{content:"Facebook" }.social-text .twitter a:after{content:"Twitter" }.social-text .gplus a:after{content:"Google +" }.social-text .rss a:after{content:"Rss" }.social-text .youtube a:after{content:"YouTube" }.social-text .skype a:after{content:"Skype" }.social-text .stumbleupon a:after{content:"StumbleUpon" }.social-text .tumblr a:after{content:"Tumblr" }.social-text .vk a:after{content:"VKontakte" }.social-text .stack-overflow a:after{content:"Stack Overflow" }.social-text .github a:after{content:"Github" }.social-text .linkedin a:after{content:"LinkedIn" }.social-text .dribbble a:after{content:"Dribbble" }.social-text .soundcloud a:after{content:"SoundCloud" }.social-text .behance a:after{content:"Behance" }.social-text .digg a:after{content:"Digg" }.social-text .instagram a:after{content:"Instagram" }.social-text .pinterest a:after,.social-text .pinterest-p a:after{content:"Pinterest" }.social-text .twitch a:after{content:"Twitch" }.social-text .delicious a:after{content:"Delicious" }.social-text .codepen a:after{content:"CodePen" }.social-text .flipboard a:after{content:"Flipboard" }.social-text .reddit a:after{content:"Reddit" }.social-text .whatsapp a:after{content:"Whatsapp" }.social-text .snapchat a:after{content:"Snapchat" }.social-text .email a:after{content:"Email" }.social-text .external-link a:after{content:"WebSite" }#header-wrap{position:relative;width:100%;height:70px;background-color:$(header.bg.color);z-index:1010;box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16), 0 2px 10px 0 rgba(0,0,0,0.12);}#header-wrap .container{position:relative;margin:0 auto }.header-logo{float:left;margin:0 20px 0 0 }.main-logo{position:relative;float:left;width:auto;max-width:250px;max-height:40px;margin:0;padding:15px 0 }.main-logo .header-image-wrapper{display:block }.main-logo img{max-width:100%;max-height:40px;margin:0 }.main-logo h1{color:#fff;font-size:20px;line-height:1.4em;margin:0 }.main-logo p{font-size:12px;margin:5px 0 0 }.header-menu{float:left }#main-menu .widget,#main-menu .widget > .widget-title{display:none }#main-menu .show-menu{display:block }#main-menu{position:relative;height:70px;z-index:15 }#main-menu ul > li{float:left;position:relative;margin:0;padding:0;transition:background .17s ease }#main-menu ul > li > a{position:relative;color:$(menu.color);font-size:15px;font-weight:400;line-height:70px;display:inline-block;text-decoration:none;margin:0;padding:0 15px;transition:color .17s ease }#main-menu ul#main-menu-nav > li:hover > a{color:$(menu.hover.color) }#main-menu ul > li > ul{position:absolute;float:left;left:0;top:70px;width:180px;background-color:$(main.dark.color);z-index:99999;margin-top:0;padding:0;border:0;box-shadow:0 2px 2px rgba(0,0,0,0.2);visibility:hidden;opacity:0 }#main-menu ul > li > ul > li:hover{background-color:rgba(255,255,255,0.03) }#main-menu ul > li > ul > li > ul{position:absolute;float:left;top:0;left:100%;margin-left:0;border:0 }#main-menu ul > li > ul > li{display:block;float:none;position:relative;transition:background .17s ease }#main-menu ul > li > ul > li a{display:block;height:34px;font-size:13px;color:$(menu.color);font-weight:400;line-height:34px;box-sizing:border-box;margin:0;padding:0 15px;transition:color .17s ease }#main-menu ul > li > ul > li:last-child a{border-bottom:0 }#main-menu ul > li.has-sub > a:after{content:'\f0d7';float:right;font-family:FontAwesome;font-size:12px;font-weight:400;margin:-1px 0 0 6px }#main-menu ul > li > ul > li.has-sub > a:after{content:'\f0da';float:right;margin:0 }#main-menu ul > li:hover > ul,#main-menu ul > li > ul > li:hover > ul{visibility:visible;opacity:1 }#main-menu ul ul{transition:all .17s ease }.show-search,.hide-search{position:absolute;top:15px;right:0;display:block;width:40px;height:40px;line-height:40px;z-index:20;color:$(menu.color);font-size:14px;font-weight:400;text-align:right;cursor:pointer;transition:color .17s ease }.show-search:hover,.hide-search:hover{color:$(menu.hover.color) }.show-search:before{content:"\f002";font-family:FontAwesome }.hide-search:before{content:"\f00d";font-family:FontAwesome }#nav-search{display:none;position:absolute;left:0;top:0;width:100%;height:70px;z-index:99;background-color:$(main.color);box-sizing:border-box;padding:0 }#nav-search .search-form{width:100%;height:70px;background-color:rgba(0,0,0,0);line-height:70px;overflow:hidden;padding:0 }#nav-search .search-input{width:100%;height:70px;font-family:inherit;color:$(menu.color);margin:0;padding:0 50px 0 0;background-color:rgba(0,0,0,0);font-size:13px;font-weight:400;box-sizing:border-box;border:0 }#nav-search .search-input:focus{color:$(menu.color);outline:none }.mobile-menu-toggle{display:none;position:absolute;top:15px;left:0;width:40px;height:40px;line-height:40px;z-index:20;color:$(menu.color);font-size:17px;font-weight:400;text-align:left;cursor:pointer;transition:color .17s ease }.mobile-menu-toggle:hover{color:$(menu.hover.color) }.mobile-menu-toggle:before{content:"\f0c9";font-family:FontAwesome }.nav-active .mobile-menu-toggle:before{content:"\f00d";font-family:FontAwesome }.overlay{display:none;position:fixed;top:0;left:0;right:0;bottom:0;z-index:990;background:rgba(255,255,255,0.8) }.mobile-menu-wrap{display:none;position:absolute;top:70px;left:0;width:100%;background-color:$(main.dark.color);box-sizing:border-box;visibility:hidden;z-index:1000;opacity:0;transition:all .17s ease }.nav-active .mobile-menu-wrap{visibility:visible;opacity:1 }.mobile-menu{position:relative;overflow:hidden;padding:20px;border-top:1px solid rgba(255,255,255,0.03) }.mobile-menu > ul{margin:0 }.mobile-menu .m-sub{display:none;padding:0 }.mobile-menu ul li{position:relative;display:block;overflow:hidden;float:left;width:100%;font-size:12px;line-height:38px }.mobile-menu > ul > li{font-weight:700 }.mobile-menu > ul li ul{overflow:hidden }.mobile-menu ul li a{color:$(menu.color);padding:0;display:block;transition:all .17s ease }.mobile-menu > ul > li > a{text-transform:uppercase }.mobile-menu ul li.has-sub .submenu-toggle{position:absolute;top:0;right:0;color:$(menu.color);cursor:pointer }.mobile-menu ul li.has-sub .submenu-toggle:after{content:'\f0da';font-family:FontAwesome;font-weight:400;float:right;width:34px;font-size:16px;text-align:center;transition:all .17s ease }.mobile-menu ul li.has-sub.show > .submenu-toggle:after{transform:rotate(90deg) }.mobile-menu > ul > li > ul > li > a{color:$(menu.color);opacity:.7;padding:0 0 0 15px }.mobile-menu > ul > li > ul > li > ul > li > a{color:$(menu.color);opacity:.7;padding:0 0 0 30px }#hot-wrapper{margin:0 auto }#hot-section .widget,#hot-section .widget > .widget-title{display:none }#hot-section .show-hot{display:block!important }#hot-section .show-hot .widget-content{position:relative;height:320px;margin:40px 0 0 }.hot-loader{position:relative;height:100%;overflow:hidden;display:block }.hot-loader:after{content:'';position:absolute;top:50%;left:50%;width:26px;height:26px;margin:-16px 0 0 -16px;border:3px solid #eaeaea;border-left-color:$(main.color);border-right-color:$(main.color);border-radius:100%;animation:spinner .8s infinite linear;transform-origin:center }@-webkit-keyframes spinner {0%{-webkit-transform:rotate(0deg);transform:rotate(0deg) }to{-webkit-transform:rotate(1turn);transform:rotate(1turn) }}@keyframes spinner {0%{-webkit-transform:rotate(0deg);transform:rotate(0deg) }to{-webkit-transform:rotate(1turn);transform:rotate(1turn) }}ul.hot-posts{display: flex;flex-wrap: wrap;margin: 0 -15px;height:320px;}.hot-posts .hot-item{position: relative;width: 25%;flex-direction: column;vertical-align: top;box-sizing: border-box;padding: 0 15px;height: 320px;display: block;word-wrap: break-word;}.hot-item-inner{position:relative;float:left;width:100%;height:100%;overflow:hidden;border: 2px solid #fff;box-shadow: 0 1px 1px rgba(204,197,185,0.5);border-radius: 4px;}.hot-posts .post-image-link{width:100%;height:100%;position:relative;overflow:hidden;display:block;z-index: 1;border-radius: 4px;}.hot-posts .post-image-link:before {position: absolute;top: 0;left: 0;width: 100%;opacity: 0;height: 100%;background-color: rgba(15,15,15,0.7);z-index: 4;content: '';transition: all .17s ease;}.hot-posts .post-image-link:after {content: '\f019';position: absolute;top: calc(50% - 14px);left: calc(50% - 19px);width: 38px;height: 38px;background: linear-gradient(45deg,rgba(255,101,165,1) 0,rgba(255,101,165,1) 13%,rgba(255,107,154,1) 35%,rgba(255,134,106,1) 100%);font-family: FontAwesome;font-size: 14px;color: #ffffff;font-weight: 400;text-align: center;line-height: 38px;z-index: 5;box-sizing: border-box;border: 1px solid #fff;padding: 0;border-radius: 50%;opacity: 0;transition: all .17s ease;}.hot-posts .hot-item-inner:hover .post-image-link:before{opacity:1;transition: all .17s ease;}.hot-posts .hot-item-inner:hover .post-image-link:after{opacity:1;transition: all .17s ease;-ms-transform: translate(-0,-50%);-webkit-transform: translate(-0,-50%);transform: translate(-0,-50%);}.hot-posts .post-info{position: absolute;bottom: 0;left: 0;width: 100%;background-image: linear-gradient(rgba(0,0,0,0),#000);overflow: hidden;z-index: 5;box-sizing: border-box;padding: 20px;text-align: center;border-bottom-right-radius: 4px;border-bottom-left-radius: 4px;transition: all .17s ease;}.hot-posts .post-title{font-family: PT Sans, sans-serif;font-size: 16px;font-weight: 700;line-height: 1.4em;padding: 0;margin: 0;text-transform: capitalize;}.hot-posts .post-title a{color:$(post.title.color);display: block;transition: color .17s ease;}.hot-posts .post-meta{font-size:11px;color:#f0f0f0 }.show-hot .no-posts{position:absolute;top:calc(50% - 50px);left:0;width:100%;text-align:center;}#home-ad-top1 .widget > .widget-title,#home-ad-top .widget > .widget-title{display:none }#home-ad-top .widget, #home-ad-top .widget{position:relative;padding:0 20px }#home-ad-top .widget-content{position:relative;width:728px;max-width:100%;max-height:90px;line-height:1;margin:40px auto 0 }#ad-wrapper {margin:0 auto;}#home-ad-top1 .widget-content {position:relative;max-width:100%;max-height:90px;line-height:1;margin:40px auto 0 }.tags-wrapper .widget > .widget-title{display:none }.tags-wrapper {margin:0 auto;}.tags-wrapper .widget-content {position: relative;margin: 40px auto 0;}.tags-wrapper .menu-cat {text-align:center;}.tags-wrapper .menu-cat li {position: relative;display: inline-block;margin: 0 5px 5px 0;}.tags-wrapper .menu-cat li a {display: block;height: 35px;background-color: $(main.color);color: $(title.color.lite);font-size: 15px;line-height: 35px;font-weight: 700;padding: 0 15px;border-radius: 26px;transition: all .17s ease;}.tags-wrapper .menu-cat li a:hover {background-color: $(main.dark.color);}.post-meta{color:$(meta.color);font-size:12px;font-weight:400;font-style:italic;padding:0 1px }.post-meta .post-author,.post-meta .post-date{display:inline-block }.post-meta em{color:$(title.color) }.post-meta a{color:$(meta.color);transition:color .17s ease }.post-meta a:hover{color:$(main.color) }.custom-widget li{overflow:hidden;padding:20px 0 0 }.custom-widget .post-image-link{position:relative;width:87px;height:67px;float:left;overflow:hidden;display:block;vertical-align:middle;margin:0 12px 0 0 }.custom-widget .post-title{overflow:hidden;font-family:$(title.font);font-size:14px;font-weight:700;line-height:1.5em;margin:0 0 5px }.custom-widget .post-title a{display:block;color:$(title.color);transition:color .17s ease }.custom-widget .post-title a:hover{color:$(main.color) }.custom-widget .post-meta{font-size:11px }.custom-widget .post-date:before{font-size:10px }.main .widget{position:relative }.queryMessage{overflow:hidden;background-color:#f2f2f2;color:$(title.color);font-size:13px;font-weight:400;padding:8px 10px;margin:0 0 25px }.queryMessage .query-info{margin:0 5px }.queryMessage .search-query,.queryMessage .search-label{font-weight:700;text-transform:uppercase }.queryMessage .search-query:before,.queryMessage .search-label:before{content:"\201c" }.queryMessage .search-query:after,.queryMessage .search-label:after{content:"\201d" }.queryMessage a.show-more{float:right;color:$(main.color) }.queryMessage a.show-more:hover{text-decoration:underline }.queryEmpty{font-size:13px;font-weight:400;padding:10px 0;margin:0 0 25px;text-align:center }.blog-post{display:block;overflow:hidden;word-wrap:break-word }.widget > h3.home-title{display:block;position:relative;font-size:15px;background: $(main.color);color:$(title.color.lite);font-weight:700;line-height:15px;text-transform:uppercase;padding: 15px 20px;box-sizing: border-box;border-radius: 4px;margin:0 0 20px;box-shadow: 0 1px 1px rgba(204,197,185,0.5);}.home-title:before{content:'';position:absolute;z-index:1 }.home-title span{position:relative;z-index:5 }.index-post-wrap{display:flex;flex-wrap:wrap;margin:0 -15px;}.index-post{width:25%;flex-direction:column;vertical-align:top;box-sizing:border-box;padding:0 15px;margin:0 0 30px;overflow:visible;}.index-post .post-image-wrap{float:left;width:100%;height: 320px;margin:0;border: 2px solid #fff;box-shadow: 0 1px 1px rgba(204,197,185,0.5);border-radius: 4px;}.index-post .post-image-wrap .post-image-link{width:100%;height:100%;position:relative;display:block;z-index:1;overflow:hidden;border-radius: 4px;}.index-post .post-image-wrap .post-image-link .post-thumb{border-radius: 4px;}.post-tag{position:relative;display:inline-block;color:$(main.color);font-size:11px;font-weight:700;line-height:11px;text-transform:uppercase }.index-post .post-content {position: relative;}.index-post .post-image-wrap .post-image-link:before {position: absolute;top: 0;left: 0;width: 100%;opacity: 0;height: 100%;background-color: rgba(15,15,15,0.7);z-index: 4;content:'';transition: all .17s ease;}.index-post .post-image-wrap .post-image-link:after {content: '\f019';position: absolute;top: calc(50% - 14px);left: calc(50% - 19px);width: 38px;height: 38px;background: linear-gradient(45deg,rgba(255,101,165,1) 0,rgba(255,101,165,1) 13%,rgba(255,107,154,1) 35%,rgba(255,134,106,1) 100%);font-family: FontAwesome;font-size: 14px;color: $(post.title.color);font-weight: 400;text-align: center;line-height: 38px;z-index: 5;box-sizing: border-box;border: 1px solid #fff;padding: 0;border-radius: 50%;opacity:0;transition: all .17s ease;}.index-post .post-info{position: absolute;bottom: 0;left: 0;width: 100%;background-image: linear-gradient(rgba(0,0,0,0),#000);overflow: hidden;z-index: 5;box-sizing: border-box;padding: 20px;text-align:center;border-bottom-right-radius: 4px;border-bottom-left-radius: 4px;transition: all .17s ease;}.index-post .post-image-wrap:hover .post-image-link:before{opacity:1;transition: all .17s ease;}.index-post .post-image-wrap:hover .post-image-link:after{opacity:1;transition: all .17s ease;-ms-transform: translate(-0,-50%);-webkit-transform: translate(-0,-50%);transform: translate(-0,-50%);}.index-post .post-image-wrap:hover .post-info{transition: all .17s ease;}.index-post .post-info > h2{font-family: PT Sans, sans-serif;font-size: 16px;font-weight: 700;line-height: 1.4em;padding: 0;margin: 0;text-transform: capitalize;}.index-post .post-info > h2 > a{display:block;color:$(post.title.color);transition:color .17s ease }.index-post .post-info > h2 > a:hover{color: #f2f2f2;}.widget iframe,.widget img{max-width:100% }.post-snippet{position:relative;display:block;overflow:hidden;font-size:13px;color:#888;line-height:1.5em;font-weight:400;margin:10px 0 0 }a.read-more{position:relative;display:inline-block;background-color:$(main.dark.color);height:28px;color:#fff;font-size:11px;font-weight:700;line-height:28px;text-transform:uppercase;padding:0 15px;margin:15px 0 0;border-radius:28px;transition:background .17s }a.read-more:hover{background-color:$(main.color) }.item-post h1.post-title{font-family:$(title.font);font-size:25px;color:$(title.color);line-height:1.5em;font-weight:700;position:relative;display:block;margin:10px 0 15px }.item-post .post-header .post-meta{font-size:13px }.item-post .post-body{display:block;overflow:hidden;font-size:14px;line-height:1.6em;padding:25px 0 0 }.static_page .item-post .post-body{padding:20px 0 }.item-post .post-outer{padding:0 }.item-post .post-body img{max-width:100% }.post-footer{position:relative;float:left;width:100%;margin:25px 0 0 }.inline-ad{position:relative;display:block;max-height:60px;margin:0 0 30px }.inline-ad > ins{display:block!important;margin:0 auto!important }.item .inline-ad{float:left;width:100%;margin:30px 0 0 }.item-post-wrap > .inline-ad{margin:0 0 30px }.post-labels{overflow:hidden;height:auto;position:relative;margin:0 0 25px }.post-labels span,.post-labels a{float:left;color:$(main.color);font-size:12px;font-weight:400 }.post-labels span{color:$(title.color) }.post-labels a{margin:0 0 0 5px;transition:all .17s ease }.post-labels .Label:after{content:',' }.post-labels .Label:last-child:after{display:none }.post-labels a:hover{text-decoration:underline }.post-share{position:relative;overflow:hidden;line-height:0;margin:0 0 30px }ul.share-links{position:relative }.share-links li{float:left;box-sizing:border-box;margin:0 5px 0 0 }.share-links li.whatsapp-mobile{display:none }.is-mobile li.whatsapp-desktop{display:none }.is-mobile li.whatsapp-mobile{display:inline-block }.share-links li a,.share-links li span{float:left;display:inline-block;height:28px;line-height:28px;color:#fff;font-size:12px;font-weight:400;padding:0 10px;border-radius:28px;transition:all .17s ease }.share-links li span{background-color:$(main.dark.color);color:#fff }.share-links li a:after{display:none;margin:0 0 0 5px }.share-links .facebook-f a:after,.share-links .twitter a:after,.share-links .pinterest-p a:after{display:inline-block }.share-links li a:hover{opacity:.8 }.about-author{position:relative;display:block;overflow:hidden;padding:20px;margin:0 0 25px;border:1px solid #ebebeb }.about-author .avatar-container{position:relative;float:left;width:100px;height:100px;background-color:#f2f2f2;overflow:hidden;margin:0 15px 0 0;border-radius:100% }.about-author .author-avatar{float:left;width:100%;height:100% }.author-name{overflow:hidden;display:inline-block;font-family:$(title.font);font-size:16px;font-weight:700;margin:3px 0 }.author-name span{color:$(title.color) }.author-name a{color:$(main.color) }.author-name a:hover{text-decoration:underline }.author-description{display:block;overflow:hidden;font-size:13px;line-height:1.6em }.author-description a{color:$(title.color);transition:color .17s ease }.author-description a:hover{color:$(main.color) }#related-wrap{overflow:hidden;margin:0 0 25px }#related-wrap .related-tag{display:none }.related-title h3{font-family:$(title.font);color:$(title.color);font-size:16px;font-weight:700;margin:0 auto 17px }.related-ready{float:left;width:100% }.related-ready .loader{height:178px }ul.related-posts{position:relative;overflow:hidden;margin:0 -10px;padding:0 }.related-posts .related-item{width:33.33333333%;position:relative;overflow:hidden;float:left;display:block;box-sizing:border-box;margin:0;padding:0 10px }.related-posts .post-image-wrap{position:relative;overflow:hidden }.related-posts .post-image-link{width:100%;height:140px;position:relative;overflow:hidden;display:block }.related-posts .related-item .post-meta{padding:0;border:0 }.related-posts .post-title{font-family:$(title.font);font-size:14px;font-weight:700;line-height:1.5em;display:block;margin:7px 0 3px }.related-posts .post-title a{color:$(title.color);transition:color .17s ease }.related-posts .related-item:hover .post-title a{color:$(main.color) }ul.post-nav{position:relative;overflow:hidden;display:block;padding:0;margin:0 0 25px;border-top:1px solid #ebebeb;border-bottom:1px solid #ebebeb }.post-nav li{display:inline-block;width:50% }.post-nav .post-prev{float:left;text-align:left;box-sizing:border-box;padding:0 10px }.post-nav .post-next{float:right;text-align:right;box-sizing:border-box;padding:0 10px }.post-nav li a{color:$(title.color);line-height:1.4em;display:block;overflow:hidden;padding:15px 0;transition:color .17s ease }.post-nav li:hover a{color:$(main.color) }.post-nav li span{display:block;font-size:12px;color:$(meta.color);font-weight:700;text-transform:uppercase;padding:0 0 2px }.post-nav .post-prev span:before{content:"\f053";float:left;font-family:FontAwesome;font-size:8px;font-weight:400;text-transform:none;margin:1px 2px 0 0 }.post-nav .post-next span:after{content:"\f054";float:right;font-family:FontAwesome;font-size:8px;font-weight:400;text-transform:none;margin:1px 0 0 2px }.post-nav p{font-size:13px;font-weight:400;line-height:1.4em;margin:0 }.post-nav .post-nav-active p{color:$(meta.color) }#blog-pager{display:block;overflow:hidden;clear:both;text-align:center;margin:20px 0 0 }.blog-pager a,.blog-pager span{display:inline-block;width:32px;height:32px;background-color:#f2f2f2;color:$(title.color);font-size:13px;font-weight:700;line-height:32px;text-align:center;box-sizing:border-box;padding:0;margin:0 2px;border-radius:100%;transition:all .17s ease }.blog-pager span.page-dots{width:20px;background-color:#fff;font-size:16px;line-height:30px;border:0 }.blog-pager .page-of{display:none;width:auto;float:right;border-color:rgba(0,0,0,0);margin:0 }.blog-pager .page-active{background-color:$(main.dark.color);color:#fff }.blog-pager a:hover{background-color:$(main.color);color:#fff }.blog-pager .page-prev:before,.blog-pager .page-next:before{font-family:FontAwesome;font-size:15px;font-weight:400 }.blog-pager .page-prev:before{content:'\f100' }.blog-pager .page-next:before{content:'\f101' }.archive #blog-pager,.blog-pager .blog-pager-newer-link,.blog-pager .blog-pager-older-link{display:none }.blog-post-comments{display:none }#comments{margin:0 }#gpluscomments{float:left!important;width:100%!important;margin:0 0 25px!important }#gpluscomments iframe{float:left!important;width:100% }.comments{display:block;clear:both;margin:0 }.comments > h3{float:left;width:100%;font-family:$(title.font);font-size:16px;color:$(title.color);font-weight:700;margin:0 0 20px }.comments > h3.no-comments{margin:0 0 15px }.comments .comments-content{float:left;width:100%;margin:0 }#comments h4#comment-post-message{display:none }.comments .comment-block{padding:0 0 0 55px }.comments .comment-content{font-size:13px;line-height:1.6em;margin:10px 0 }.comment-thread .comment{position:relative;padding:15px 0 0;margin:15px 0 0;list-style:none;border-top:1px solid #ebebeb }.comment-thread ol{padding:0 0 0 15px;margin:0 0 15px }.comment-thread ol > li:first-child{padding:0;margin:0;border:0 }.comment-thread .avatar-image-container{position:absolute;top:15px;left:0;width:40px;height:40px;border-radius:100%;overflow:hidden }.comment-thread ol > li:first-child > .avatar-image-container{top:0 }.avatar-image-container img{width:100%;height:100% }.comments .comment-header .user{font-family:$(title.font);font-size:14px;color:$(title.color);display:inline-block;font-style:normal;font-weight:700;margin:0 }.comments .comment-header .user a{color:$(title.color) }.comments .comment-header .icon.user{display:none }.comments .comment-header .icon.blog-author{display:inline-block;font-size:12px;color:$(main.color);font-weight:400;vertical-align:top;margin:0 0 0 5px }.comments .comment-header .icon.blog-author:before{content:'\f058';font-family:FontAwesome }.comments .comment-header .datetime{display:inline-block;margin:0 0 0 5px }.comment-header .datetime a{font-size:12px;color:$(meta.color);font-style:italic }.comment-header .datetime a:before{content:'.';font-size:15px;line-height:15px;vertical-align:top;margin:0 5px 0 2px }.comments .comment-actions{display:block;margin:0 0 15px }.comments .comment-actions a{color:$(meta.color);font-size:11px;margin:0 15px 0 0;transition:color .17s ease }.comments .comment-actions a:hover{color:$(main.color) }.loadmore.loaded a{display:inline-block;border-bottom:1px solid rgba(0,0,0,0.1);text-decoration:none;margin-top:15px }.comments .continue{display:none!important }.comments .comment-replies{padding:0 0 0 55px }.thread-expanded .thread-count a,.loadmore{display:none }.comments .footer,.comments .comment-footer{font-size:13px }.comment-form{margin:0 -7.5px }.comment-form > p{font-size:13px;padding:10px 0 5px }.comment-form > p > a{color:$(title.color) }.comment-form > p > a:hover{text-decoration:underline }iframe.blogger-iframe-colorize,iframe.blogger-comment-from-post{height:253px!important }.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{color:$(title.color);margin:0 0 15px }.post-body h1,.post-body h2{font-size:24px }.post-body h3{font-size:21px }.post-body h4{font-size:18px }.post-body h5{font-size:16px }.post-body h6{font-size:13px }blockquote{font-size:15px;line-height:1.5em;font-style:italic;color:$(title.color);text-align:center;padding:10px 50px;margin:0 }blockquote:before,blockquote:after{display:inline-block;font-family:FontAwesome;color:$(title.color);font-weight:400;font-style:normal;line-height:1 }blockquote:before{content:'\f10d';margin:0 10px 0 0 }blockquote:after{content:'\f10e';margin:0 0 0 10px }.widget .post-body ul,.widget .post-body ol{line-height:1.5;font-weight:400 }.widget .post-body li{margin:5px 0;padding:0;line-height:1.5 }.post-body ul{padding:0 0 0 20px }.post-body ul li:before{content:"\f105";font-family:FontAwesome;font-size:13px;font-weight:900;margin:0 5px 0 0 }.post-body u{text-decoration:underline }.post-body a{transition:color .17s ease }.post-body strike{text-decoration:line-through }.contact-form{overflow:hidden }.contact-form .widget-title{display:none }.contact-form .contact-form-name{width:calc(50% - 5px) }.contact-form .contact-form-email{width:calc(50% - 5px);float:right }.sidebar .widget{position:relative;overflow:hidden;background-color:#fff;box-sizing:border-box;padding:0;margin:0 0 35px }.sidebar .widget > .widget-title{position:relative;float:left;width:100%;height:32px;background-color:$(main.dark.color);display:block;margin:0 0 25px }.sidebar .widget > .widget-title > h3{display:block;height:32px;font-size:13px;color:#fff;font-weight:700;line-height:32px;text-transform:uppercase;padding:0 15px;margin:0 }#sidebar-right .widget:last-child{margin:0 }.sidebar .widget-content{float:left;width:100%;margin:0 }ul.social-counter{display:flex;flex-wrap:wrap;margin:0 -5px }.social-counter li{float:left;width:calc(50% - 10px);display:flex;flex-direction:column;margin:10px 5px 0 }.social-counter li:nth-child(1),.social-counter li:nth-child(2){margin:0 5px }.social-counter li a{display:block;height:100%;height:32px;font-size:13px;color:#fff;text-align:center;line-height:32px;padding:0 10px;border-radius:32px;transition:opacity .17s ease }.social-counter li a:after{margin:0 0 0 5px }.social-counter li a:hover{opacity:.9 }.list-label li{position:relative;display:block;padding:8px 0;border-top:1px dashed #ebebeb }.list-label li:first-child{padding:0 0 8px;border-top:0 }.list-label li:last-child{padding-bottom:0;border-bottom:0 }.list-label li a{display:block;color:$(title.color);font-size:13px;font-weight:400;text-transform:capitalize;transition:color .17s }.list-label li a:before{content:"\f105";float:left;color:$(title.color);font-family:FontAwesome;margin:2px 3px 0 0 }.list-label li a:hover{color:$(main.color) }.list-label .label-count{color:$(title.color);font-size:11px;font-weight:400;position:relative;float:right;background-color:rgba(0,0,0,0.08);width:18px;height:18px;text-align:center;line-height:18px;border-radius:100%;transition:all .17s ease }.list-label li a:hover .label-count{background-color:$(main.color);color:#fff }.cloud-label li{position:relative;float:left;margin:0 5px 5px 0 }.cloud-label li a{display:block;height:26px;background-color:#f2f2f2;color:$(title.color);font-size:11px;line-height:26px;font-weight:400;padding:0 10px;border-radius:26px;transition:all .17s ease }.cloud-label li a:hover{color:#fff;background-color:$(main.color) }.cloud-label .label-count{display:none }.sidebar .FollowByEmail > .widget-title{margin:0 0 15px }.FollowByEmail .widget-content{position:relative;overflow:hidden;font-weight:400 }.FollowByEmail .before-text{display:block;overflow:hidden;font-family:$(title.font);font-size:14px;color:$(title.color);line-height:1.5em;padding:0 30px 0 0;margin:0 0 10px }.FollowByEmail .follow-by-email-inner{position:relative }.FollowByEmail .follow-by-email-inner .follow-by-email-address{width:100%;height:32px;font-family:inherit;font-size:11px;color:#888;text-align:center;font-style:italic;padding:0 10px;margin:0;box-sizing:border-box;border:1px solid #eaeaea;border-radius:32px;transition:ease .17s }.FollowByEmail .follow-by-email-inner .follow-by-email-address:focus{border-color:rgba(0,0,0,0.1) }.FollowByEmail .follow-by-email-inner .follow-by-email-submit{width:100%;height:32px;background-color:$(main.color);font-family:inherit;font-size:12px;color:#fff;font-weight:700;text-transform:uppercase;cursor:pointer;margin:10px 0 0;border:0;border-radius:32px;transition:background .17s ease }.FollowByEmail .follow-by-email-inner .follow-by-email-submit:hover{background-color:$(main.dark.color) }#ArchiveList ul.flat li{color:$(title.color);font-size:13px;font-weight:400;padding:8px 0;border-bottom:1px dashed #eaeaea }#ArchiveList ul.flat li:first-child{padding-top:0 }#ArchiveList ul.flat li:last-child{padding-bottom:0;border-bottom:0 }#ArchiveList .flat li > a{display:block;color:$(title.color);transition:color .17s }#ArchiveList .flat li > a:hover{text-decoration:underline }#ArchiveList .flat li > a:before{content:"\f105";float:left;color:$(title.color);font-family:FontAwesome;margin:2px 3px 0 0 }#ArchiveList .flat li > a > span{color:$(title.color);font-size:11px;font-weight:400;position:relative;float:right;background-color:rgba(0,0,0,0.08);width:18px;height:18px;text-align:center;line-height:18px;border-radius:18px;transition:all .17s ease }#ArchiveList .flat li > a:hover > span{background-color:$(main.color);color:#fff }.PopularPosts .widget-content .post{overflow:hidden;padding:20px 0 0 }.sidebar .PopularPosts .widget-content .post:first-child,.sidebar .custom-widget li:first-child{padding:0 }.PopularPosts .post-image-link{position:relative;width:87px;height:67px;float:left;overflow:hidden;display:block;vertical-align:middle;margin:0 12px 0 0 }.PopularPosts .post-info{overflow:hidden }.PopularPosts .post-title{font-family:$(title.font);font-size:14px;font-weight:700;line-height:1.5em;margin:0 0 5px }.PopularPosts .post-title a{display:block;color:$(title.color);transition:color .17s ease }.PopularPosts .post-title a:hover{color:$(main.color) }.PopularPosts .post-meta{font-size:11px }.PopularPosts .post-date:before{font-size:10px }.FeaturedPost .post-content{text-align:center }.FeaturedPost .post-image-link{display:block;position:relative;width:100%;height:200px;margin:0 0 15px }.FeaturedPost .post-title{font-family:$(title.font);font-size:19px;overflow:hidden;font-weight:700;line-height:1.5em;padding:0 10px;margin:7px 0 10px }.FeaturedPost .post-title a{color:$(title.color);display:block }.FeaturedPost .post-title a:hover{text-decoration:underline }.Text{font-size:13px }.contact-form-widget form{font-weight:400 }.contact-form-name{float:left;width:100%;height:30px;font-family:inherit;font-size:13px;line-height:30px;box-sizing:border-box;padding:5px 10px;margin:0 0 10px;border:1px solid #ebebeb }.contact-form-email{float:left;width:100%;height:30px;font-family:inherit;font-size:13px;line-height:30px;box-sizing:border-box;padding:5px 10px;margin:0 0 10px;border:1px solid #ebebeb }.contact-form-email-message{float:left;width:100%;font-family:inherit;font-size:13px;box-sizing:border-box;padding:5px 10px;margin:0 0 10px;border:1px solid #ebebeb }.contact-form-button-submit{float:left;width:100%;height:30px;background-color:$(main.color);font-size:13px;color:#fff;line-height:30px;cursor:pointer;box-sizing:border-box;padding:0 10px;margin:0;border:0;transition:background .17s ease }.contact-form-button-submit:hover{background-color:$(main.dark.color) }.contact-form-error-message-with-border{float:left;width:100%;background-color:#fbe5e5;font-size:11px;text-align:center;line-height:11px;padding:3px 0;margin:10px 0;box-sizing:border-box;border:1px solid #fc6262 }.contact-form-success-message-with-border{float:left;width:100%;background-color:#eaf6ff;font-size:11px;text-align:center;line-height:11px;padding:3px 0;margin:10px 0;box-sizing:border-box;border:1px solid #5ab6f9 }.contact-form-cross{margin:0 0 0 3px }.contact-form-error-message,.contact-form-success-message{margin:0 }.BlogSearch .search-input{float:left;width:calc(75% - 10px);height:30px;background-color:#fff;font-weight:400;font-size:12px;line-height:30px;box-sizing:border-box;padding:0 10px;border:1px solid #ebebeb;border-radius:30px }.BlogSearch .search-action{float:right;width:25%;height:30px;font-family:inherit;font-size:12px;text-transform:uppercase;line-height:30px;cursor:pointer;box-sizing:border-box;background-color:$(main.color);color:#fff;padding:0 5px;border:0;border-radius:30px;transition:background .17s ease }.BlogSearch .search-action:hover{background-color:$(main.dark.color) }.Profile .profile-img{float:left;width:80px;height:80px;margin:0 15px 0 0;transition:all .17s ease }.Profile .profile-datablock{margin:0 }.Profile .profile-data .g-profile{display:block;font-family:$(title.font);font-size:14px;color:$(title.color);margin:0 0 5px;transition:color .17s ease }.Profile .profile-data .g-profile:hover{text-decoration:underline }.Profile .profile-info > .profile-link{color:$(title.color);font-size:11px;margin:5px 0 0;transition:color .17s ease }.Profile .profile-info > .profile-link:hover{text-decoration:underline }.Profile .profile-datablock .profile-textblock{display:none }.common-widget .LinkList ul li,.common-widget .PageList ul li{width:calc(50% - 5px);padding:7px 0 0 }.common-widget .LinkList ul li:nth-child(odd),.common-widget .PageList ul li:nth-child(odd){float:left }.common-widget .LinkList ul li:nth-child(even),.common-widget .PageList ul li:nth-child(even){float:right }.common-widget .LinkList ul li a,.common-widget .PageList ul li a{display:block;color:$(title.color);font-size:13px;font-weight:400;transition:color .17s ease }.common-widget .LinkList ul li a:hover,.common-widget .PageList ul li a:hover{text-decoration:underline }.common-widget .LinkList ul li:first-child,.common-widget .LinkList ul li:nth-child(2),.common-widget .PageList ul li:first-child,.common-widget .PageList ul li:nth-child(2){padding:0 }#home-ad-footer .widget > .widget-title{display:none }#home-ad-footer .widget{position:relative;padding:0 20px }#home-ad-footer .widget-content{position:relative;width:728px;max-width:100%;max-height:90px;line-height:1;margin:0 auto 40px }#footer-wrapper{background-color:$(main.dark.color) }#sub-footer-wrapper{background-color:rgba(0,0,0,0.35);color:$(title.color.lite);display:block;padding:0;width:100%;overflow:hidden }#sub-footer-wrapper .container{overflow:hidden;margin:0 auto;padding:10px 0 }#menu-footer{float:right;position:relative;display:block }#menu-footer .widget > .widget-title{display:none }#menu-footer ul li{float:left;display:inline-block;height:34px;padding:0;margin:0 }#menu-footer ul li a{font-size:13px;font-weight:400;display:block;color:$(title.color.lite);line-height:34px;padding:0 5px;margin:0 0 0 10px;transition:color .17s ease }#menu-footer ul li:last-child a{padding:0 0 0 5px }#menu-footer ul li a:hover{color:$(main.color) }#sub-footer-wrapper .copyright-area{font-size:13px;float:left;height:34px;line-height:34px;font-weight:400 }#sub-footer-wrapper .copyright-area a{color:$(title.color.lite);transition:color .17s }#sub-footer-wrapper .copyright-area a:hover{color:$(main.color) }.hidden-widgets{display:none;visibility:hidden }.back-top{display:none;z-index:1010;width:36px;height:36px;position:fixed;bottom:25px;right:25px;background-color:$(main.color);cursor:pointer;overflow:hidden;font-size:15px;color:#fff;text-align:center;line-height:36px;border-radius:100% }.back-top:after{content:'\f102';position:relative;font-family:FontAwesome;font-weight:400 }.error404 #main-wrapper{width:100%!important;margin:0!important }.error404 #sidebar-wrapper{display:none }.errorWrap{color:$(title.color);text-align:center;padding:60px 0 100px }.errorWrap h3{font-size:160px;line-height:1;margin:0 0 30px }.errorWrap h4{font-size:25px;margin:0 0 20px }.errorWrap p{margin:0 0 10px }.errorWrap a{display:block;color:$(main.color);padding:10px 0 0 }.errorWrap a i{font-size:14px }.errorWrap a:hover{text-decoration:underline }@media (max-width: 1100px) {#outer-wrapper{max-width:100%!important }.row,#content-wrapper{width:100% }#header-wrap,.footer-widgets-wrap,#sub-footer-wrapper{box-sizing:border-box;padding:0 20px }#hot-wrapper{box-sizing:border-box;padding:0 20px;}#content-wrapper{position:relative;box-sizing:border-box;padding:0 20px;margin:35px 0 0 }#main-wrapper{margin:0 0 35px }}@media (max-width: 980px) {.header-logo,.main-logo{width:100%;max-width:100%;text-align:center;margin:0 }.header-menu{display:none }.mobile-menu-wrap,.mobile-menu-toggle{display:block }.show-search,.hide-search{font-size:17px;text-align:right }#nav-search{left:-2px;width:calc(100% + 4px) }#content-wrapper > .container{margin:0 }#main-wrapper{width:100%;padding:0!important }#sidebar-wrapper{width:100%;padding:0 }#sidebar-right .widget:last-child{margin:0 0 35px }}@media (max-width: 880px) {#hot-section .show-hot .widget-content, ul.hot-posts {height: auto;}.hot-posts .hot-item {width: 50%;margin: 20px 0 0 0;padding: 0 10px;}.hot-posts .hot-item.item-0, .hot-posts .hot-item.item-1 {margin: 0;}.index-post {width: 50%;}.footer-widgets-wrap{display:block }#footer-wrapper .footer{width:100%;margin-right:0 }#footer-sec2,#footer-sec3{margin-top:25px }}@media (max-width: 680px) {#menu-footer,#sub-footer-wrapper .copyright-area{width:100%;height:auto;line-height:inherit;text-align:center }#menu-footer{margin:10px 0 0 }#sub-footer-wrapper .copyright-area{margin:10px 0 }#menu-footer ul li{float:none;height:auto }#menu-footer ul li a{line-height:inherit;margin:0 3px 5px }.comment-form{margin:0 }}@media (max-width: 540px) {.hot-posts .hot-item, .hot-posts .hot-item.item-0, .hot-posts .hot-item.item-1 {width: 100%;margin: 20px 0 0 0;}.index-post{width:100% }.share-links li a:after{display:none!important }#related-wrap,ul.related-posts{margin:0 }.related-posts .related-item{width:100%;padding:0;margin:0 0 25px }.related-posts .post-image-link{height:180px }.related-posts .post-title{font-size:17px }.inline-ad,.inline-ad > ins{height:auto;min-height:1px;max-height:250px }}@media (max-width: 440px) {.queryMessage{text-align:center }.queryMessage a.show-more{width:100%;margin:10px 0 0 }.item-post h1.post-title{font-size:23px }blockquote{padding:10px 30px }.about-author{text-align:center }.about-author .avatar-container{float:none;display:table;margin:0 auto 10px }#comments ol{padding:0 }}@media (max-width: 360px) {.errorWrap h3{font-size:130px }.share-links li a, .share-links li span{width:28px;text-align:center;box-sizing:border-box;padding:0 }.about-author .avatar-container{width:60px;height:60px }iframe.blogger-iframe-colorize,iframe.blogger-comment-from-post{height:263px!important }}.input-group {position: relative;}.panel.panel-primary{background:#eee;text-align:center;display:table;overflow:hidden;width:100%;max-width:970px;padding:0;border-radius:5px;margin:25px auto;border: 1px solid #e1e1e1;}.panel-body{position:relative;margin:0 25px;box-sizing: border-box;}.panel-heading h2{color:#000;margin:0 auto 25px auto;font-weight:500;padding:15px;font-size:20px;border-bottom:1px solid rgba(0,0,0,0.05) }.panel-body input{background: #fff;width: 100%;padding: 15px;border-radius: 5px;border: 1px solid transparent;box-shadow: 0 1px 1px rgba(204,197,185,0.5);font-size: 16px;color: #000;outline: none;text-indent: 60px;transition: all .3s;box-sizing: border-box;}.panel-body input:focus{background:#fff;color:#000;border-color:#e74c3c;outline:none;box-shadow:0 0 5px rgba(0,0,0,0.1) }.panel-body .input-group-btn{position:absolute;top:0;right:0 }.panel-body button{border-radius: 0 5px 5px 0;background: $(main.color);color: #fff;border: 0;padding: 16px 52px;height: 50px;font-weight: 700;font-size: 14px;text-transform: uppercase;outline: none;cursor:pointer;transition: all .3s;}.panel-body button:hover,.panel-body button:focus{background:#d24637;outline:none }#generatelink{margin:20px auto 0 auto }#generatelink button{background:#01a3a4;border-radius:5px;font-size:14px;padding:14px 32px }#generatelink button:hover,#generatelink button:focus{background:#028889;border-radius:5px;font-size:14px }#generatelink button .fa.fa-floppy-o,#generatelink button .fa.fa-check{margin:0 5px 0 0 }.panel-body:before{content:' \f0c1' ;background:rgba(0,0,0,0.05);font-family:fontawesome;position:absolute;left:0;top:0;color:#888;padding:12px 20px;border-radius:5px 0 0 5px;border-right:1px solid transparent;transition:all .6s }.panel-body:active:before,.panel-body:focus-within:before{content:' \f061' ;background:#e74c3c;color:#fff }#generatelink input{background:#ffeaa7;text-indent:0 }#generatelink input:hover,#generatelink input:focus{background:#ffeaa7;border-color:transparent;box-shadow:none }#generateloading{margin:20px auto 0 auto;font-size:20px;color:#f39c12;font-weight:normal }.hidden {display: none;}#timer{margin:20px auto;width:80px;text-align:center }.pietimer{position:relative;font-size:200px;width:1em;height:1em }.pietimer > .percent{position:absolute;top:28px;left:12px;width:3.33em;font-size:18px;text-align:center;display:none }.pietimer > .slice{position:absolute;width:1em;height:1em;clip:rect(0px,1em,1em,0.5em) }.pietimer > .slice.gt50{clip:rect(auto,auto,auto,auto) }.pietimer > .slice > .pie{border:0.06em solid #c0c0c0;position:absolute;width:70px;height:70px;clip:rect(0em,0.5em,1em,0em);border-radius:0.5em }.pietimer > .slice > .pie.fill{-moz-transform:rotate(180deg)!important;-webkit-transform:rotate(180deg)!important;-o-transform:rotate(180deg)!important;transform:rotate(180deg)!important }.pietimer.fill > .percent{display:none }.pietimer.fill > .slice > .pie{border:transparent;background-color:#c0c0c0;width:1em;height:1em }.text-center{text-align:center }.text-center button{margin:20px auto;border-radius:5px;text-align:center;padding:12px 22px;background:$(main.color);color:#fff;cursor: pointer;font-weight: 700;font-size: 14px;text-transform: uppercase;box-shadow:0 5px 10px rgba(0,0,0,0.19),0 3px 3px rgba(0,0,0,0.13);transition:all 0.3s cubic-bezier(.25,.8,.25,1);border: none;}.panel-body .text-center button{margin:0 auto;}.text-center button:hover,.text-center button:active,.text-center button:focus{box-shadow:0 1px 3px rgba(0,0,0,0.12),0 1px 2px rgba(0,0,0,0.24) }.text-center button span{margin:0 5px 0 0 }.panel-body{margin:0 auto;padding:25px }.panel-body:before{display:none }.panel-heading h2{background:#fff;color:#222;margin:0 auto;font-weight:500;padding:21px;font-size:24px;text-align:center }@media (max-width: 540px) {.panel-body .input-group-btn {display: block;position: relative;overflow: hidden;margin: 20px auto 0 auto;}.panel-body button {border-radius: 5px;width: 100%;}}
]]></b:skin>
<style>
/*-------Typography and ShortCodes-------*/
 .firstcharacter{float:left;color:#27ae60;font-size:75px;line-height:60px;padding-top:4px;padding-right:8px;padding-left:3px }.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{margin-bottom:15px;color:#2c3e50 }blockquote{font-style:italic;color:#888;border-left:5px solid #27ae60;margin-left:0;padding:10px 15px }blockquote:before{content:&#39;\f10d&#39;;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;margin-right:10px;color:#888 }blockquote:after{content:&#39;\f10e&#39;;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;margin-left:10px;color:#888 }.button{background-color:#2c3e50;float:left;padding:5px 12px;margin:5px;color:#fff;text-align:center;border:0;cursor:pointer;border-radius:3px;display:block;text-decoration:none;font-weight:400;transition:all .3s ease-out !important;-webkit-transition:all .3s ease-out !important }a.button{color:#fff }.button:hover{background-color:#27ae60;color:#fff }.button.small{font-size:12px;padding:5px 12px }.button.medium{font-size:16px;padding:6px 15px }.button.large{font-size:18px;padding:8px 18px }.small-button{width:100%;overflow:hidden;clear:both }.medium-button{width:100%;overflow:hidden;clear:both }.large-button{width:100%;overflow:hidden;clear:both }.demo:before{content:&quot;\f06e&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale }.download:before{content:&quot;\f019&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale }.buy:before{content:&quot;\f09d&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale }.visit:before{content:&quot;\f14c&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale }.widget .post-body ul,.widget .post-body ol{line-height:1.5;font-weight:400 }.widget .post-body li{margin:5px 0;padding:0;line-height:1.5 }.post-body ul li:before{content:&quot;\f105&quot;;margin-right:5px;font-family:fontawesome }pre{font-family:Monaco, &quot;Andale Mono&quot;, &quot;Courier New&quot;, Courier, monospace;background-color:#2c3e50;background-image:-webkit-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-moz-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-ms-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-o-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);-webkit-background-size:100% 50px;-moz-background-size:100% 50px;background-size:100% 50px;line-height:25px;color:#f1f1f1;position:relative;padding:0 7px;margin:15px 0 10px;overflow:hidden;word-wrap:normal;white-space:pre;position:relative }pre:before{content:&#39;Code&#39;;display:block;background:#F7F7F7;margin-left:-7px;margin-right:-7px;color:#2c3e50;padding-left:7px;font-weight:400;font-size:14px }pre code,pre .line-number{display:block }pre .line-number a{color:#27ae60;opacity:0.6 }pre .line-number span{display:block;float:left;clear:both;width:20px;text-align:center;margin-left:-7px;margin-right:7px }pre .line-number span:nth-child(odd){background-color:rgba(0, 0, 0, 0.11) }pre .line-number span:nth-child(even){background-color:rgba(255, 255, 255, 0.05) }pre .cl{display:block;clear:both }#contact{background-color:#fff;margin:30px 0 !important }#contact .contact-form-widget{max-width:100% !important }#contact .contact-form-name,#contact .contact-form-email,#contact .contact-form-email-message{background-color:#FFF;border:1px solid #eee;border-radius:3px;padding:10px;margin-bottom:10px !important;max-width:100% !important }#contact .contact-form-name{width:47.7%;height:50px }#contact .contact-form-email{width:49.7%;height:50px }#contact .contact-form-email-message{height:150px }#contact .contact-form-button-submit{max-width:100%;width:100%;z-index:0;margin:4px 0 0;padding:10px !important;text-align:center;cursor:pointer;background:#27ae60;border:0;height:auto;-webkit-border-radius:2px;-moz-border-radius:2px;-ms-border-radius:2px;-o-border-radius:2px;border-radius:2px;text-transform:uppercase;-webkit-transition:all .2s ease-out;-moz-transition:all .2s ease-out;-o-transition:all .2s ease-out;-ms-transition:all .2s ease-out;transition:all .2s ease-out;color:#FFF }#contact .contact-form-button-submit:hover{background:#2c3e50 }#contact .contact-form-email:focus,#contact .contact-form-name:focus,#contact .contact-form-email-message:focus{box-shadow:none !important }.alert-message{position:relative;display:block;background-color:#FAFAFA;padding:20px;margin:20px 0;-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px;color:#2f3239;border:1px solid }.alert-message p{margin:0 !important;padding:0;line-height:22px;font-size:13px;color:#2f3239 }.alert-message span{font-size:14px !important }.alert-message i{font-size:16px;line-height:20px }.alert-message.success{background-color:#f1f9f7;border-color:#e0f1e9;color:#1d9d74 }.alert-message.success a,.alert-message.success span{color:#1d9d74 }.alert-message.alert{background-color:#DAEFFF;border-color:#8ED2FF;color:#378FFF }.alert-message.alert a,.alert-message.alert span{color:#378FFF }.alert-message.warning{background-color:#fcf8e3;border-color:#faebcc;color:#8a6d3b }.alert-message.warning a,.alert-message.warning span{color:#8a6d3b }.alert-message.error{background-color:#FFD7D2;border-color:#FF9494;color:#F55D5D }.alert-message.error a,.alert-message.error span{color:#F55D5D }.fa-check-circle:before{content:&quot;\f058&quot;}.fa-info-circle:before{content:&quot;\f05a&quot;}.fa-exclamation-triangle:before{content:&quot;\f071&quot;}.fa-exclamation-circle:before{content:&quot;\f06a&quot;}.post-table table{border-collapse:collapse;width:100% }.post-table th{background-color:#eee;font-weight:bold }.post-table th,.post-table td{border:0.125em solid #333;line-height:1.5;padding:0.75em;text-align:left }@media (max-width: 30em){.post-table thead tr{position:absolute;top:-9999em;left:-9999em }.post-table tr{border:0.125em solid #333;border-bottom:0 }.post-table tr + tr{margin-top:1.5em }.post-table tr,.post-table td{display:block }.post-table td{border:none;border-bottom:0.125em solid #333;padding-left:50% }.post-table td:before{content:attr(data-label);display:inline-block;font-weight:bold;line-height:1.5;margin-left:-100%;width:100% }}@media (max-width: 20em){.post-table td{padding-left:0.75em }.post-table td:before{display:block;margin-bottom:0.75em;margin-left:0 }}.FollowByEmail {clear: both;}.widget .post-body ol {padding: 0 0 0 15px;}.post-body ul li {list-style: none;}

</style>
<b:if cond='data:view.isLayoutMode'>
<b:template-skin>
<![CDATA[
/*------Layout (No Edit)----------*/
 body#layout #outer-wrapper,body#layout .row{width:auto;padding:0 }body#layout{width:800px;position:relative;padding:95px 5px 0;margin:0 }body#layout div.section{margin:0 5px 10px!important;padding:16px 16px 18px!important }body#layout .section h4{font-size:14px;margin:0 }body#layout .layout-widget-description{display:none }body#layout .theme-options,body#layout #main-menu .widget{display:block!important }body#layout div.sora-panel{background-color:#d7d7d7!important;overflow:hidden!important;border-color:#bcbcbc }body#layout .sora-panel .widget{float:left;width:49%;margin-right:2% }body#layout .sora-panel #LinkList71{margin-right:0 }body#layout #header-wrap{height:auto }body#layout #header-wrap .container{display:flex }body#layout .header-logo,body#layout .header-menu{width:500%;float:left;max-width:none;max-height:none;margin:0 }body#layout .main-logo{float:none;max-width:none;max-height:none }body#layout .mobile-menu{display:none }body#layout #main-menu{height:auto }body#layout #hot-wrapper .widget{display:block }body#layout #content-wrapper{width:auto;margin:0 }#content-wrapper > .container{margin:0 }body#layout #main-wrapper{width:67%;padding:0 }body#layout #sidebar-wrapper{display:block;width:33%;padding:0 }body#layout .sidebar .widget,body#layout .sidebar .widget-content{float:none;width:auto;overflow:visible }#home-ad-top .widget-content,#home-ad-footer .widget-content{width:auto;max-height:auto;margin:0 }body#layout .footer-widgets-wrap{display:flex;margin:0 }body#layout .footer-widgets-wrap div.footer{width:100% }body#layout #menu-footer{float:none }
/*------Layout (end)----------*/

]]></b:template-skin>
</b:if>

<!-- Global Variables -->
<script type='text/javascript'>
//<![CDATA[
// Global variables. "Available for Edit"
var monthFormat = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"],
    noThumbnail = "https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/s1600/nth.png",
    postPerPage = 7,
    fixedSidebar = true,
    commentsSystem = "blogger",
    disqusShortname = "soratemplates";
//]]>
</script>

<b:defaultmarkups>
  <b:defaultmarkup type='Common'>
    <b:includable id='widget-title'>
      <b:if cond='data:defaultTitle or data:title'>
        <div class='widget-title'>
          <h3 class='title'>
            <data:title/>
          </h3>
        </div>
      </b:if>
    </b:includable>    
  </b:defaultmarkup>
  <b:defaultmarkup type='Header'>
    <b:includable id='main' var='this'>
      <div class='header-widget'>
        <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
        <b:include cond='data:imagePlacement not in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='title'/>
        <b:include cond='data:imagePlacement != &quot;REPLACE&quot;' name='description'/>
      </div>
    </b:includable>
    <b:includable id='description'>
      <p>
        <data:this.description/>
      </p>
    </b:includable>
    <b:includable id='image'>
      <a class='header-brand' expr:href='data:blog.homepageUrl'>
        <img expr:alt='data:blog.title.escaped' expr:data-height='data:height' expr:data-width='data:width' expr:src='data:image'/>
      </a>
    </b:includable>
    <b:includable id='title'>
      <h1>
        <b:tag cond='data:view.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
          <data:title/>
        </b:tag>
      </h1>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='PopularPosts'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='content' var='post'>
      <div class='post'>
        <div class='post-content'>
          <a class='post-image-link' expr:href='data:post.url'>
            <b:if cond='data:post.featuredImage'>
              <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 180'/>
              <b:else/>
              <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w180/nth.png'/>
            </b:if>
          </a>
          <div class='post-info'>
            <h2 class='post-title'>
              <a expr:href='data:post.url'><data:post.title/></a>
            </h2>
            <div class='post-meta'>
              <span class='post-date published' expr:datetime='data:post.date.iso8601'><data:post.date/></span>
            </div>
          </div>
        </div>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FeaturedPost'>
    <b:includable id='main' var='this'>
      <b:if cond='data:widget.sectionId == &quot;main&quot;'>
        <b:if cond='data:view.isHomepage'>
          <b:include name='widget-title'/>
          <div class='widget-content'>
            <b:loop values='data:posts' var='post'>
              <b:include data='post' name='content'/>
            </b:loop>
          </div>
        </b:if>
        <b:else/>
        <b:include name='widget-title'/>
        <div class='widget-content'>
          <b:loop values='data:posts' var='post'>
            <b:include data='post' name='content'/>
          </b:loop>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='content' var='post'>
      <div class='post'>
        <div class='post-content'>
          <div class='post-image-wrap'>
            <a class='post-image-link' expr:href='data:post.url'>
              <b:if cond='data:post.featuredImage'>
                <b:if cond='data:widget.sectionId == &quot;main&quot;'>
                  <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 780'/>
                  <b:else/>
                  <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 480'/>
                </b:if>
                <b:else/>
                <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w780/nth.png'/>
              </b:if>
            </a>
          </div>
          <span class='post-tag'><data:post.labels.first.name/></span>
          <h2 class='post-title'>
            <a expr:href='data:post.url'><data:post.title/></a>
          </h2>
          <div class='post-meta'>
            <span class='post-author'><em><data:widgets.Blog.first.allBylineItems.author.label/></em> <a expr:href='data:post.author.profileUrl' expr:title='data:post.author.name' target='_blank'><data:post.author.name/></a></span> <span class='post-date published' expr:datetime='data:post.date.iso8601'><em><data:widgets.Blog.first.allBylineItems.timestamp.label/></em> <data:post.date/></span>
          </div>
          <b:if cond='data:widget.sectionId == &quot;main&quot;'>
            <p class='post-snippet'><b:eval expr='data:post.snippets.long snippet { length: 280 }'/></p>
            <b:else/>
            <p class='post-snippet'><b:eval expr='data:post.snippets.long snippet { length: 92 }'/></p>
          </b:if>
          <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
            <a class='read-more' expr:href='data:post.url'><data:blog.jumpLinkMessage/></a>
          </b:if>
        </div>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Label'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='list'/>
      </div>
    </b:includable>
    <b:includable id='list'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <a class='label-name' expr:href='data:label.url'>
              <data:label.name/>
              <b:if cond='data:this.showFreqNumbers'>
                <span class='label-count'><data:label.count/></span>
              </b:if>
            </a>
          </li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Image'>
    <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:tag cond='data:link' expr:href='data:link' name='a'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
      </b:tag>
      <br/>
      <b:if cond='data:caption'>
        <span class='caption'><data:caption/></span>
      </b:if>
    </div>
  </b:includable>
    </b:defaultmarkup>
  <b:defaultmarkup type='FollowByEmail'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <span class='before-text'><data:skin.vars.followByEmail/></span>
        <div class='follow-by-email-inner'>
          <form action='https://feedburner.google.com/fb/a/mailverify' expr:onsubmit='&quot;window.open(\&quot;https://feedburner.google.com/fb/a/mailverify?uri=&quot; + data:feedPath + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' target='popupwindow'>
            <input autocomplete='off' class='follow-by-email-address' expr:placeholder='data:messages.emailAddress' name='email' type='email'/>
            <input class='follow-by-email-submit' expr:value='data:messages.subscribe' type='submit'/>
            <input expr:value='data:feedPath' name='uri' type='hidden'/>
            <input name='loc' type='hidden' value='en_US'/>
          </form>
        </div>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogSearch'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content' role='search'>
        <form class='search-form' expr:action='data:blog.searchUrl'>
          <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <b:include name='urlParamsAsFormInput'/>
          <input autocomplete='off' class='search-input' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
          <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>  
        </form>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogArchive'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <div id='ArchiveList'>
          <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
            <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;, &quot;HIERARCHY&quot;}' name='flat'/>
          </div>
        </div>
      </div>
    </b:includable>
    <b:includable id='flat'>
      <ul class='flat'>
        <b:loop values='data:data' var='i'>
          <li class='archivedate'>
            <a expr:href='data:i.url'>
              <data:i.name/><span class='post-count'><data:i.post-count/></span>
            </a>
          </li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
</b:defaultmarkups>

    <!-- Google Analytics -->
    <b:include data='blog' name='google-analytics'/>

</head>

<body expr:class='data:blog.pageType'>
  <b:class cond='data:view.isHomepage' name='home'/>
  <b:class cond='data:view.isPage' name='item'/>
  <b:class cond='data:view.isArchive' name='index'/>
  <b:class cond='data:view.isError' name='error404'/>

<!-- Theme Options -->
  <div class='theme-options' style='display:none'>
    <b:section class='sora-panel' id='sora-panel' maxwidgets='1' name='Theme Options' showaddelement='no'>
      <b:widget id='LinkList70' locked='true' title='Css Options (Boxed and Snippet)' type='LinkList' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='sorting'>NONE</b:widget-setting>
          <b:widget-setting name='text-0'>boxedVersion</b:widget-setting>
          <b:widget-setting name='link-0'>false</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          &lt;style type=&#39;text/css&#39;&gt;
          <b:loop values='data:links' var='link'>
            <b:if cond='data:link.name == &quot;boxedVersion&quot;'>
              <b:if cond='data:link.target == &quot;true&quot;'>
                #outer-wrapper{max-width:1080px} 
              </b:if>
            </b:if>
          </b:loop>
          &lt;/style&gt;
        </b:includable>
      </b:widget>
      <b:widget id='LinkList71' locked='true' title='Default Variables' type='LinkList' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='link-3'>9</b:widget-setting>
          <b:widget-setting name='sorting'>NONE</b:widget-setting>
          <b:widget-setting name='link-4'>5</b:widget-setting>
          <b:widget-setting name='text-1'>commentsSystem</b:widget-setting>
          <b:widget-setting name='link-1'>blogger</b:widget-setting>
          <b:widget-setting name='text-0'>disqusShortname</b:widget-setting>
          <b:widget-setting name='link-2'>true</b:widget-setting>
          <b:widget-setting name='text-3'>postPerPage</b:widget-setting>
          <b:widget-setting name='link-0'>soratemplates</b:widget-setting>
          <b:widget-setting name='text-2'>fixedSidebar</b:widget-setting>
          <b:widget-setting name='text-4'>postPerPage</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          &lt;script type=&#39;text/javascript&#39;&gt;
          //&lt;![CDATA[
          <b:loop values='data:links' var='link'>
            <b:if cond='data:link.name == &quot;postPerPage&quot;'>
              var postPerPage = <data:link.target/>;
            </b:if>
            <b:if cond='data:link.name == &quot;fixedSidebar&quot;'>
              var fixedSidebar = <data:link.target/>;
            </b:if>
            <b:if cond='data:link.name == &quot;commentsSystem&quot;'>
              var commentsSystem = &quot;<data:link.target/>&quot;;
            </b:if>
            <b:if cond='data:link.name == &quot;disqusShortname&quot;'>
              var disqusShortname = &quot;<data:link.target/>&quot;;
            </b:if>
          </b:loop>
          //]]&gt;
          &lt;/script&gt;
        </b:includable>
      </b:widget>
    </b:section>
  </div>

<!-- Outer Wrapper -->
<div id='outer-wrapper'>

  <!-- Header Wrapper -->
  <div id='header-wrap'>
    <div class='mobile-menu-wrap'>
      <div class='mobile-menu'/>
    </div>
    <div class='container row'>
      <div class='header-logo'>    
        <b:section class='main-logo' id='main-logo' maxwidgets='1' name='Header Logo' showaddelement='yes'>
              <b:widget id='Header1' locked='true' title='Download Hub (Header)' type='Header' version='2' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='displayUrl'>http://2.bp.blogspot.com/-xzomfvIy6xA/XoGluSBtUrI/AAAAAAAAIEs/tG3lZY71WCErCksFvaoCpUy7q6LOadIHgCK4BGAYYCw/s1600/Downloadhub.png</b:widget-setting>
                  <b:widget-setting name='displayHeight'>40</b:widget-setting>
                  <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                  <b:widget-setting name='useImage'>true</b:widget-setting>
                  <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                  <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
                  <b:widget-setting name='displayWidth'>249</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main' var='this'>
              <div class='header-widget'>
                <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
                <b:include cond='data:imagePlacement not in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='title'/>
                <b:include cond='data:imagePlacement != &quot;REPLACE&quot;' name='description'/>
              </div>
            </b:includable>
                <b:includable id='behindImageStyle'>
              <b:if cond='data:sourceUrl'>
                <b:include cond='data:this.image' data='{                    image: data:this.image,                    selector: &quot;.header-widget&quot;                  }' name='responsiveImageStyle'/>
                <style type='text/css'>
                  .header-widget {
                    background-position: <data:blog.locale.languageAlignment/>;
                    background-repeat: no-repeat;
                  }
                </style>
              </b:if>
            </b:includable>
                <b:includable id='description'>
              <p>
                <data:this.description/>
              </p>
            </b:includable>
                <b:includable id='image'>
              <a class='header-brand' expr:href='data:blog.homepageUrl'>
                <img expr:alt='data:blog.title.escaped' expr:data-height='data:height' expr:data-width='data:width' expr:src='data:image'/>
              </a>
            </b:includable>
                <b:includable id='title'>
              <h1>
                <b:tag cond='data:view.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
                  <data:title/>
                </b:tag>
              </h1>
            </b:includable>
              </b:widget>
            </b:section>
      </div>
      <div class='header-menu'>
        <b:section class='main-menu' id='main-menu' maxwidgets='1' name='Main Menu' showaddelement='yes'>
          <b:widget id='LinkList74' locked='true' title='Link List' type='LinkList' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='text-10'>_Web Documentation</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>#</b:widget-setting>
              <b:widget-setting name='link-2'>#</b:widget-setting>
              <b:widget-setting name='link-12'>https://www.soratemplates.com/2020/04/download-hub-blogger-templates.html</b:widget-setting>
              <b:widget-setting name='link-0'>#</b:widget-setting>
              <b:widget-setting name='link-11'>https://youtu.be/2H6_eMZpxAo</b:widget-setting>
              <b:widget-setting name='link-10'>https://www.sorabloggingtips.com/2020/04/how-to-setup-download-hub-blogger.html</b:widget-setting>
              <b:widget-setting name='text-9'>Documentation</b:widget-setting>
              <b:widget-setting name='link-9'>#</b:widget-setting>
              <b:widget-setting name='text-8'>Learn Blogging</b:widget-setting>
              <b:widget-setting name='link-7'>https://download-hub-soratemplates.blogspot.com/soratemplates</b:widget-setting>
              <b:widget-setting name='link-8'>https://www.youtube.com/channel/UCCDjoOPSNiuLJX06HirPjOA?sub_confirmation=1</b:widget-setting>
              <b:widget-setting name='link-5'>https://download-hub-soratemplates.blogspot.com/p/post-format-and-page-markup.html</b:widget-setting>
              <b:widget-setting name='link-6'>https://www.sorabloggingtips.com/2017/01/how-to-add-sitemap-widget-in-blogspot-blogs.html</b:widget-setting>
              <b:widget-setting name='link-3'>#</b:widget-setting>
              <b:widget-setting name='link-4'>#</b:widget-setting>
              <b:widget-setting name='text-1'>_Multi DropDown</b:widget-setting>
              <b:widget-setting name='text-0'>Features</b:widget-setting>
              <b:widget-setting name='text-3'>__DropDown 2</b:widget-setting>
              <b:widget-setting name='text-2'>__DropDown 1</b:widget-setting>
              <b:widget-setting name='text-5'>_ShortCodes</b:widget-setting>
              <b:widget-setting name='text-4'>__DropDown 3</b:widget-setting>
              <b:widget-setting name='text-7'>_Error Page</b:widget-setting>
              <b:widget-setting name='text-6'>_SiteMap</b:widget-setting>
              <b:widget-setting name='text-11'>_Video Documentation</b:widget-setting>
              <b:widget-setting name='text-12'>Download This Template</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <ul id='main-menu-nav' role='menubar'>
                <b:loop values='data:links' var='link'>
                  <li><a expr:href='data:link.target' role='menuitem'><data:link.name/></a></li>
                </b:loop>
              </ul>
            </b:includable>
          </b:widget>
        </b:section>
      </div>
      <div id='nav-search'>
        <form class='search-form' expr:action='data:blog.searchUrl' role='search'>
          <input autocomplete='off' class='search-input' expr:placeholder='data:messages.searchThisBlog' name='q' type='search' value=''/>
          <span class='hide-search'/>
        </form>
      </div>
      <span class='show-search'/>
      <span class='mobile-menu-toggle'/> 
    </div>
  </div>

  <div class='clearfix'/>

  <b:if cond='data:view.isHomepage'>
<div class='row' id='ad-wrapper'>
 <b:section id='home-ad-top1' maxwidgets='1' name='Home Ads Top' showaddelement='yes'>
   <b:widget id='HTML21' locked='false' title='Ad Code' type='HTML' visible='true'>
     <b:widget-settings>
       <b:widget-setting name='content'>&lt;a class=&quot;sora-ads-here&quot; href=&quot;javascript:;&quot;&gt;Responsive Advertisement&lt;/a&gt;
&lt;style&gt;
.sora-ads-here {
    display: block;
    background-color: #ffffff;
    text-align: center;
    font-size: 13px;
    color: #aaaaaa;
    font-weight: 400;
    font-style: italic;
    line-height: 90px;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,.05);
}
&lt;/style&gt;</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
   </b:widget>
 </b:section>
    </div>
  <div class='clearfix'/>
   <div class='row' id='hot-wrapper'>
      <b:section id='hot-section' maxwidgets='1' name='Hot Posts' showaddelement='yes'>
        <b:widget id='HTML22' locked='false' title='' type='HTML' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'>random/hot-posts</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
        </b:widget>
      </b:section>
    </div>
    <div class='clearfix'/>
  </b:if>


  <b:if cond='data:view.isHomepage'>
    <b:section id='home-ad-top' maxwidgets='1' name='Home Ads Top' showaddelement='yes'>
      <b:widget id='HTML2' locked='false' title='Ad Code' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'>&lt;a class=&quot;sora-ads-here&quot; href=&quot;javascript:;&quot;&gt;Responsive Advertisement&lt;/a&gt;
&lt;style&gt;
.sora-ads-here {
    display: block;
    background-color: #ffffff;
    text-align: center;
    font-size: 13px;
    color: #aaaaaa;
    font-weight: 400;
    font-style: italic;
    line-height: 90px;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,.05);
}
&lt;/style&gt;</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
      </b:widget>
    </b:section>
  </b:if>

<b:if cond='data:view.isHomepage'>
  <div class='clearfix'/>
<div class='tags-wrapper row'>
   <b:section class='menu-cat' id='menu-cat' maxwidgets='1' name='Categories Menu' showaddelement='yes'>
     <b:widget id='LinkList86' locked='true' title='Tags Menu Widget' type='LinkList' version='2' visible='true'>
       <b:widget-settings>
         <b:widget-setting name='text-22'>Trailers</b:widget-setting>
         <b:widget-setting name='text-23'>Uncategorized</b:widget-setting>
         <b:widget-setting name='text-24'>WEB Series</b:widget-setting>
         <b:widget-setting name='text-9'>Hindi TV Shows</b:widget-setting>
         <b:widget-setting name='text-8'>Hindi Dubbed</b:widget-setting>
         <b:widget-setting name='text-20'>Tamil Movies</b:widget-setting>
         <b:widget-setting name='text-21'>Telugu Movies</b:widget-setting>
         <b:widget-setting name='text-1'>300Mb Movies</b:widget-setting>
         <b:widget-setting name='text-0'>1080p Movies</b:widget-setting>
         <b:widget-setting name='text-3'>Bollywood Movies</b:widget-setting>
         <b:widget-setting name='text-2'>720p HEVC Movies</b:widget-setting>
         <b:widget-setting name='text-5'>Bollywood Video Songs</b:widget-setting>
         <b:widget-setting name='text-4'>Bollywood Mp3 Songs</b:widget-setting>
         <b:widget-setting name='text-7'>English TV Shows</b:widget-setting>
         <b:widget-setting name='text-6'>Dual Audio</b:widget-setting>
         <b:widget-setting name='text-19'>Single Video Songs</b:widget-setting>
         <b:widget-setting name='text-15'>Pakistani Movies</b:widget-setting>
         <b:widget-setting name='text-16'>Pc Games</b:widget-setting>
         <b:widget-setting name='text-17'>Pre Release</b:widget-setting>
         <b:widget-setting name='text-18'>Punjabi Movies</b:widget-setting>
         <b:widget-setting name='text-11'>Malayalam Movies</b:widget-setting>
         <b:widget-setting name='text-12'>Marathi Movies</b:widget-setting>
         <b:widget-setting name='text-13'>Mobile Movies</b:widget-setting>
         <b:widget-setting name='text-14'>Multi Audio</b:widget-setting>
         <b:widget-setting name='text-10'>Hollywood Movies</b:widget-setting>
         <b:widget-setting name='link-17'>#</b:widget-setting>
         <b:widget-setting name='link-16'>#</b:widget-setting>
         <b:widget-setting name='link-19'>#</b:widget-setting>
         <b:widget-setting name='sorting'>NONE</b:widget-setting>
         <b:widget-setting name='link-18'>#</b:widget-setting>
         <b:widget-setting name='link-1'>#</b:widget-setting>
         <b:widget-setting name='link-13'>#</b:widget-setting>
         <b:widget-setting name='link-2'>#</b:widget-setting>
         <b:widget-setting name='link-12'>#</b:widget-setting>
         <b:widget-setting name='link-15'>#</b:widget-setting>
         <b:widget-setting name='link-0'>#</b:widget-setting>
         <b:widget-setting name='link-14'>#</b:widget-setting>
         <b:widget-setting name='link-11'>#</b:widget-setting>
         <b:widget-setting name='link-10'>#</b:widget-setting>
         <b:widget-setting name='link-9'>#</b:widget-setting>
         <b:widget-setting name='link-7'>#</b:widget-setting>
         <b:widget-setting name='link-8'>#</b:widget-setting>
         <b:widget-setting name='link-5'>#</b:widget-setting>
         <b:widget-setting name='link-6'>#</b:widget-setting>
         <b:widget-setting name='link-3'>#</b:widget-setting>
         <b:widget-setting name='link-4'>#</b:widget-setting>
         <b:widget-setting name='link-24'>#</b:widget-setting>
         <b:widget-setting name='link-23'>#</b:widget-setting>
         <b:widget-setting name='link-20'>#</b:widget-setting>
         <b:widget-setting name='link-22'>#</b:widget-setting>
         <b:widget-setting name='link-21'>#</b:widget-setting>
       </b:widget-settings>
       <b:includable id='main'>
            <b:include name='widget-title'/>
            <b:include name='content'/>
          </b:includable>
       <b:includable id='content'>
            <div class='widget-content'>
              <ul>
                <b:loop values='data:links' var='link'>
                  <li><a expr:href='data:link.target'><data:link.name/></a></li>
                </b:loop>
              </ul>
            </div>
          </b:includable>
     </b:widget>
   </b:section>
  <div class='clearfix'/>
  </div>
</b:if>
    <!-- Content Wrapper -->
    <div class='row' id='content-wrapper'>
      <div class='container'>

      <!-- Main Wrapper -->
      <div id='main-wrapper'>
        <b:section class='main' id='main' maxwidgets='1' name='Main Posts' showaddelement='yes'>
          <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='commentLabel'>Comments</b:widget-setting>
              <b:widget-setting name='showShareButtons'>true</b:widget-setting>
              <b:widget-setting name='authorLabel'>by</b:widget-setting>
              <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              <b:widget-setting name='timestampLabel'/>
              <b:widget-setting name='reactionsLabel'>Reactions</b:widget-setting>
              <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
              <b:widget-setting name='showLocation'>false</b:widget-setting>
              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
              <b:widget-setting name='postsPerAd'>1</b:widget-setting>
              <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
              <b:widget-setting name='backlinksLabel'>Related Posts</b:widget-setting>
              <b:widget-setting name='showDateHeader'>false</b:widget-setting>
              <b:widget-setting name='style.textcolor'>#888888</b:widget-setting>
              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
              <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showAuthor'>true</b:widget-setting>
              <b:widget-setting name='style.linkcolor'>#f8f8f8</b:widget-setting>
              <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
              <b:widget-setting name='showLabels'>true</b:widget-setting>
              <b:widget-setting name='postLabelsLabel'>Tags:</b:widget-setting>
              <b:widget-setting name='showBacklinks'>true</b:widget-setting>
              <b:widget-setting name='showInlineAds'>false</b:widget-setting>
              <b:widget-setting name='showReactions'>true</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
              <b:include name='searchMessage'/>
 <b:if cond='data:view.isHomepage'>
                  <h3 class='home-title'><span><data:messages.recentPosts/></span></h3>
                </b:if>
              <div class='blog-posts hfeed'>
                <b:class cond='data:view.isMultipleItems' name='index-post-wrap'/>
                <b:class cond='data:view.isSingleItem' name='item-post-wrap'/>
                 <b:loop index='i' values='data:posts' var='post'>
                  <b:include data='post' name='postCommentsAndAd'/>
                </b:loop>
              </div>
              <b:include cond='data:view.isMultipleItems' name='postPagination'/>
              <b:include name='feedLinks'/>
            </b:includable>
            <b:includable id='aboutPostAuthor'>
              <div class='about-author'>
                <div class='avatar-container'>
                  <b:if cond='data:post.author.authorPhoto.image'>
                    <img class='author-avatar' expr:alt='data:post.author.name' expr:src='data:post.author.authorPhoto.image resizeImage 130'/>                
                    <b:else/>
                    <img class='author-avatar' expr:alt='data:post.author.name' src='https://4.bp.blogspot.com/-uCjYgVFIh70/VuOLn-mL7PI/AAAAAAAADUs/Kcu9wJbv790hIo83rI_s7lLW3zkLY01EA/s100/avatar.png'/>
                  </b:if>
                </div>
                <h3 class='author-name'>
                  <span><data:messages.postedBy/></span><a expr:alt='data:post.author.name' expr:href='data:post.author.profileUrl' target='_blank'> <data:post.author.name/></a>
                </h3>
                <span class='author-description'><data:post.author.aboutMe/></span>
              </div>
            </b:includable>
            <b:includable id='addComments'>
              <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
                <b:message name='messages.postAComment'/>
              </a>
            </b:includable>
            <b:includable id='backLinks' var='post'>
              <b:comment>Disabled</b:comment>         
            </b:includable>
            <b:includable id='commentAuthorAvatar'>
              <div class='avatar-image-container'>
                <img class='author-avatar' expr:src='data:comment.authorAvatarSrc' height='45' width='45'/>
              </div>
            </b:includable>
            <b:includable id='commentDeleteIcon' var='comment'>
              <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                <b:if cond='data:showCmtPopup'>
                  <div class='goog-toggle-button'>
                    <div class='goog-inline-block comment-action-icon'/>
                  </div>
                  <b:else/>
                  <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
                    <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
                  </a>
                </b:if>
              </span>
            </b:includable>
            <b:includable id='commentForm' var='post'>
              <div class='comment-form'>
                <a name='comment-form'/>
                <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
                  <p><data:this.messages.blogComment/></p>
                </b:if>
                <b:include data='post' name='commentFormIframeSrc'/>
                <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                <data:post.cmtfpIframe/>
                <script type='text/javascript'>
                  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                </script>
              </div>
            </b:includable>
            <b:includable id='commentFormIframeSrc' var='post'>
              <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
            </b:includable>
            <b:includable id='commentItem' var='comment'>
              <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
                <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

                <div class='comment-block'>
                  <div class='comment-author'>
                    <b:if cond='data:comment.authorUrl'>
                      <b:message name='messages.authorSaidWithLink'>
                        <b:param expr:value='data:comment.author' name='authorName'/>
                        <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
                      </b:message>
                      <b:else/>
                      <b:message name='messages.authorSaid'>
                        <b:param expr:value='data:comment.author' name='authorName'/>
                      </b:message>
                    </b:if>
                  </div>
                  <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
                    <data:comment.body/>
                  </div>
                  <div class='comment-footer'>
                    <span class='comment-timestamp'>
                      <a expr:href='data:comment.url' title='comment permalink'>
                        <data:comment.timestamp/>
                      </a>
                      <b:include data='comment' name='commentDeleteIcon'/>
                    </span>
                  </div>
                </div>
              </div>
            </b:includable>
            <b:includable id='commentList' var='comments'>
              <div id='comments-block'>
                <b:loop values='data:comments' var='comment'>
                  <b:include data='comment' name='commentItem'/>
                </b:loop>
              </div>
            </b:includable>
            <b:includable id='commentPicker' var='post'>
              <b:if cond='data:post.commentSource == 1'>
                <b:include data='post' name='iframeComments'/>
                <b:elseif cond='data:post.showThreadedComments'/>
                <b:include data='post' name='threadedComments'/>
                <b:else/>
                <b:include data='post' name='comments'/>
              </b:if>
            </b:includable>
            <b:includable id='comments' var='post'>
              <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
                <a name='comments'/>
                <b:if cond='data:post.allowComments'>

                  <b:include name='commentsTitle'/>

                  <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                    <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
                  </div>

                  <b:if cond='data:post.commentPagingRequired'>
                    <div class='paging-control-container'>
                      <b:if cond='data:post.hasOlderLinks'>
                        <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                          <data:messages.oldest/>
                        </a>
                        <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                          <data:messages.older/>
                        </a>
                      </b:if>

                      <span class='comment-range-text'>
                        <data:post.commentRangeText/>
                      </span>

                      <b:if cond='data:post.hasNewerLinks'>
                        <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                          <data:messages.newer/>
                        </a>
                        <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                          <data:messages.newest/>
                        </a>
                      </b:if>
                    </div>
                  </b:if>

                  <div class='footer'>
                    <b:if cond='data:post.embedCommentForm'>
                      <b:if cond='data:post.allowNewComments'>
                        <b:include data='post' name='commentForm'/>
                        <b:else/>
                        <data:post.noNewCommentsText/>
                      </b:if>
                      <b:else/>
                      <b:if cond='data:post.allowComments'>
                        <b:include data='post' name='addComments'/>
                      </b:if>
                    </b:if>
                  </div>
                </b:if>
                <b:if cond='data:showCmtPopup'>
                  <div id='comment-popup'>
                    <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                    </iframe>
                  </div>
                </b:if>
              </section>
            </b:includable>
            <b:includable id='commentsTitle'>
              <!-- Post Commments Title -->
              <h3 class='title'><data:post.numberOfComments/> <data:messages.comments/></h3>
              <b:class cond='data:post.numberOfComments == &quot;0&quot;' name='no-comments'/>
            </b:includable>
            <b:includable id='feedLinks'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
            <b:includable id='feedLinksBody' var='links'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
            <b:includable id='footerBylines' var='post'>
              <!-- Post Footer Extras -->
              <b:include data='post' name='postLabels'/>
              <b:include data='post' name='postShareButtons'/>
            </b:includable>
            <b:includable id='headerByline' var='post'>
              <!-- Post Header Meta -->
                <div class='post-meta'>
                  <b:include data='post' name='postAuthor'/>
                  <b:include data='post' name='postTimestamp'/>
                </div>
            </b:includable>
            <b:includable id='homePageLink'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
            <b:includable id='iframeComments' var='post'>
              <b:if cond='data:post.allowIframeComments'>
                <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>
                <b:if cond='!data:post.embedCommentForm'>
                  <b:include data='post' name='commentsLink'/>
                </b:if>
              </b:if>
            </b:includable>
            <b:includable id='indexPost' var='post'>
              <!-- Index Post Content -->
              <div class='post-content'>
                <div class='post-image-wrap'>
                <a class='post-image-link' expr:href='data:post.url'>
                  <b:if cond='data:post.featuredImage'> 
                    <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 480'/>
                    <b:else/>
                    <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w480/nth.png'/>
                  </b:if>
                </a>
   <div class='post-info'>
                  <b:include data='post' name='postHeader'/>
                </div>

              </div>
             
              </div>
            </b:includable>
            <b:includable id='inlineAd' var='post'>
              <b:if cond='!data:view.isPreview'>
                <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
                  <!-- Ad -->
                  <div class='inline-ad'>
                    <b:if cond='data:this.adCode != &quot;&quot;'>
                      <data:this.adCode/>
                      <b:else/>
                      <b:include cond='data:this.adClientId or data:blog.adsenseClientId' name='defaultAdUnit'/>
                    </b:if>
                  </div>
                </b:if>
                <b:else/>
                <div class='inline-ad'>
                  <div class='inline-ad-placeholder'>
                    <span><b:message name='messages.adsGoHere'/></span>
                  </div>
                </div>
              </b:if>
            </b:includable>
            <b:includable id='itemPost' var='post'>
              <!-- Item Post Content -->
              <b:include data='post' name='postMeta'/>
              <div class='post-header'>
                <b:include data='post' name='postHeader'/>
              </div>
              <!-- Show ad inside post content (top), if post page. -->
              <b:include cond='data:view.isPost and data:post.includeAd' data='post' name='inlineAd'/>
              <b:include data='post' name='postBody'/>
              <!-- Show ad inside post content (bottom), if post page. -->
              <b:include cond='data:view.isPost and data:post.includeAd' data='post' name='inlineAd'/>
              <b:include cond='data:view.isPost' data='post' name='postFooter'/>
            </b:includable>
            <b:includable id='nextPageLink'>
              <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:messages.olderPosts'>
                <data:messages.olderPosts/>
              </a>
            </b:includable>
            <b:includable id='post' var='post'>
              <!-- Post Index -->
              <b:include cond='data:view.isMultipleItems' data='post' name='indexPost'/>
              <!-- Post Item -->
              <b:include cond='data:view.isSingleItem' data='post' name='itemPost'/>
            </b:includable>
            <b:includable id='postAuthor' var='post'>
              <!-- Post Author -->
              <b:if cond='data:allBylineItems.author'>
                <span class='post-author'><em><data:allBylineItems.author.label/></em> <a expr:href='data:post.author.profileUrl' expr:title='data:post.author.name' target='_blank'><data:post.author.name/></a></span>
              </b:if>
            </b:includable>
            <b:includable id='postBody' var='post'> 
              <!-- Post Body Entry Content-->
              <div class='post-body post-content'>
                <data:post.body/>
              </div>
            </b:includable>
            <b:includable id='postBodySnippet' var='post'>
              <b:include data='post' name='postBody'/>
            </b:includable>
            <b:includable id='postBreadcrumbs' var='post'>
              <!-- Post Breadcrumbs -->
              <script type='application/ld+json'>
              {
                &quot;@context&quot;: &quot;http://schema.org&quot;,
                &quot;@type&quot;: &quot;BreadcrumbList&quot;,
                &quot;itemListElement&quot;: [{
                  &quot;@type&quot;: &quot;ListItem&quot;,
                  &quot;position&quot;: 1,
                  &quot;item&quot;: {
                    &quot;name&quot;: &quot;<data:messages.home/>&quot;,
                    &quot;@id&quot;: &quot;<data:blog.homepageUrl.jsonEscaped/>&quot;
                  }
                },{
                  &quot;@type&quot;: &quot;ListItem&quot;,
                  &quot;position&quot;: 2,
                  &quot;item&quot;: {
                    &quot;name&quot;: &quot;<b:if cond='data:post.labels'><data:post.labels.first.name/></b:if>&quot;,
                    &quot;@id&quot;: &quot;<data:post.labels.last.url.jsonEscaped/>&quot;
                  }
                },{
                  &quot;@type&quot;: &quot;ListItem&quot;,
                  &quot;position&quot;: 3,
                  &quot;item&quot;: {
                    &quot;name&quot;: &quot;<data:post.title/>&quot;,
                    &quot;@id&quot;: &quot;<data:post.url.jsonEscaped/>&quot;
                  }
                }]
              }
            </script>
            </b:includable>
            <b:includable id='postCategory' var='post'>
              <!-- Post Label/Category -->
              <b:if cond='data:post.labels'>
                <span class='post-tag'>
                  <data:post.labels.first.name/>
                </span>
              </b:if>
            </b:includable>
            <b:includable id='postCommentsAndAd' var='post'>
              <!-- Post, Comments and Ads -->
              <!-- Post Content Index and Item -->
              <div class='blog-post hentry'>
                <b:class cond='data:view.isMultipleItems' name='index-post'/>
                <b:class cond='data:view.isSingleItem' name='item-post'/>
                <b:include data='post' name='post'/>
              </div>
              <!-- Comments -->
              <b:if cond='data:view.isSingleItem'>
                <div class='blog-post-comments'>
                  <b:include data='post' name='threadedCommentsDisqus'/>
                  <b:include data='post' name='commentPicker'/>
                </div>
              </b:if>
            </b:includable>
            <b:includable id='postCommentsLink'>
              <b:if cond='data:view.isMultipleItems'>
                <span class='byline post-comment-link container'>
                  <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
                  <b:include cond='data:post.commentSource == 1' name='commentsLinkIframe'/>
                </span>
              </b:if>
            </b:includable>
            <b:includable id='postFeaturedImage' var='post'>
              <!-- Post Featured Image on Index -->
              <div class='post-image-wrap'>
                <a class='post-image-link' expr:href='data:post.url'>
                  <b:if cond='data:post.featuredImage'> 
                    <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 480'/>
                    <b:else/>
                    <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w480/nth.png'/>
                  </b:if>
                </a>
              </div>
            </b:includable>
            <b:includable id='postFooter' var='post'>
              <!-- Post Footer Itens -->
              <div class='post-footer'>
                <!-- Post Labels, Reactions, Share, Navigation, About Author an Related Posts -->
                <b:include data='post' name='footerBylines'/>
                <b:include cond='data:post.author.aboutMe' data='post' name='aboutPostAuthor'/>
                <b:include cond='data:allBylineItems.backlinks' data='post' name='postRelated'/>
                <b:include cond='data:allBylineItems.icons' data='post' name='postNavigation'/>
              </div>
            </b:includable>
            <b:includable id='postFooterAuthorProfile' var='post'>
  <b:if cond='data:post.author.aboutMe and data:view.isPost'>
    <div class='author-profile'>
      <b:if cond='data:post.author.authorPhoto.url'>
        <img class='author-image' expr:src='data:post.author.authorPhoto.url' width='50px'/>
        <div class='author-about'>
          <b:include data='post' name='aboutPostAuthor'/>
        </div>
      <b:else/>
        <b:include data='post' name='aboutPostAuthor'/>
      </b:if>
    </div>
  </b:if>
</b:includable>
            <b:includable id='postHeader' var='post'>
              <b:include cond='data:view.isPost' data='post' name='postBreadcrumbs'/>
              <b:include cond='data:view.isPost' data='post' name='postCategory'/>
              <b:include data='post' name='postTitle'/>
              <b:include cond='data:view.isPost' data='post' name='headerByline'/>
            </b:includable>
            <b:includable id='postJumpLink' var='post'>
              <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
                <a class='read-more' expr:href='data:post.url'><data:blog.jumpLinkMessage/></a>
              </b:if>
            </b:includable>
            <b:includable id='postLabels' var='post'>
              <b:if cond='data:allBylineItems.labels'>
                <b:if cond='data:post.labels'>
                  <div class='post-labels'>
                    <span class='labels-label'><data:allBylineItems.labels.label/></span>
                      <b:loop values='data:post.labels' var='label'>
                        <span class='Label'><a class='label-link' expr:href='data:label.url' rel='tag'><data:label.name/></a></span>
                      </b:loop>
                  </div>
                </b:if>
              </b:if>
            </b:includable>
            <b:includable id='postMeta' var='post'>
              <b:include data='post' name='postMetadataJSON'/>
            </b:includable>
            <b:includable id='postNavigation' var='post'>
              <!-- Post Navigation Item -->
              <ul class='post-nav'>
                <li class='post-next'> 
                  <b:if cond='data:newerPageUrl'> 
                    <a class='next-post-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' rel='next'>
                      <div class='post-nav-inner'><span><data:messages.newer/></span><p/></div>
                    </a> 
                    <b:else/> 
                    <a rel='next'><div class='post-nav-inner post-nav-active'><span><data:messages.newest/></span><p><data:post.title/></p></div></a> 
                  </b:if> 
                </li>
                <li class='post-prev'> 
                  <b:if cond='data:olderPageUrl'> 
                    <a class='prev-post-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' rel='previous'>
                      <div class='post-nav-inner'><span><data:messages.older/></span><p/></div>
                    </a> 
                    <b:else/>
                    <a rel='previous'><div class='post-nav-inner post-nav-active'><span><data:messages.oldest/></span><p><data:post.title/></p></div></a> 
                  </b:if> 
                </li>
              </ul>
            </b:includable>
            <b:includable id='postPagination'>
              <div class='blog-pager' id='blog-pager'>
                <b:include cond='data:newerPageUrl' name='previousPageLink'/>
                <b:include cond='data:olderPageUrl' name='nextPageLink'/>
                <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
              </div>
            </b:includable>
            <b:includable id='postRelated' var='post'>
              <!-- Related Posts -->
                <div id='related-wrap'>
                  <div class='related-title'>
                    <h3><data:messages.youMayLikeThesePosts/></h3>
                  </div>
                  <div class='related-ready'>
                    <b:if cond='data:post.labels'>
                      <div class='related-tag' expr:data-label='data:post.labels.first.name'/>
                      <b:else/>
                      <div class='related-tag' data-label='random'/>
                    </b:if>
                  </div> 
                </div>  
            </b:includable>
            <b:includable id='postShareButtons' var='post'>
              <!-- Post ShareButtons -->
              <b:if cond='data:allBylineItems.share'>
                <div class='post-share'>
                  <ul class='share-links social social-color social-text'> 
                    <b:class cond='data:blog.isMobileRequest' name='is-mobile'/>
                    <li class='share-it'><span><i class='fa fa-share'/></span></li>
                    <li class='facebook-f'><a class='facebook' expr:href='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=650, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'/></li>
                    <li class='twitter'><a class='twitter' expr:href='&quot;https://twitter.com/share?url=&quot; + data:post.url + &quot;&amp;text=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=450, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'/></li>
                    <li class='pinterest-p'><a class='pinterest' expr:href='&quot;https://www.pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.featuredImage + &quot;&amp;description=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=735, height=750, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'/></li> 
                                       <li class='linkedin'><a class='linkedin' expr:href='&quot;https://www.linkedin.com/shareArticle?url=&quot; + data:post.url' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=650, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'/></li>
                    <li class='whatsapp whatsapp-desktop'><a class='whatsapp' expr:href='&quot;https://web.whatsapp.com/send?text=&quot; + data:post.title + &quot; | &quot; + data:post.url' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=900, height=550, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'/></li>
                    <li class='whatsapp whatsapp-mobile'><a class='whatsapp' expr:href='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title + &quot; | &quot; + data:post.url' rel='nofollow' target='_blank'/></li>                    
                    <li class='email'><a class='email' expr:href='&quot;mailto:?subject=&quot; + data:post.title + &quot;&amp;body=&quot; + data:post.url' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=500, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'/></li>
                  </ul>
                </div>
              </b:if>
            </b:includable>
            <b:includable id='postShortMeta'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
            <b:includable id='postSummary' var='post'>
              <!-- Post Summary -->
              <p class='post-snippet'><b:eval expr='data:post.snippets.short snippet { length: 92 }'/></p>
            </b:includable>
            <b:includable id='postTimestamp' var='post'>
              <!-- Post Timestamp -->
              <b:if cond='data:allBylineItems.timestamp'>
                <span class='post-date published' expr:datetime='data:post.date.iso8601'><em><data:allBylineItems.timestamp.label/></em> <data:post.date/></span>
              </b:if>
            </b:includable>
            <b:includable id='postTitle' var='post'>
              <!-- Post Title Index and Item -->
              <b:if cond='data:view.isMultipleItems'>
                <h2 class='post-title'>
                  <a expr:href='data:post.url'><data:post.title/></a>
                </h2>
              </b:if>
              <b:if cond='data:view.isSingleItem'>
                <h1 class='post-title'>
                  <data:post.title/>
                </h1>
              </b:if>
            </b:includable>
            <b:includable id='previousPageLink'>
              <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:messages.newerPosts'>
                <data:messages.newerPosts/>
              </a>
            </b:includable>
            <b:includable id='searchMessage'>
              <!-- Search Message -->
              <b:if cond='data:view.search.query'>
                <div class='queryMessage'>
                  <b:if cond='data:posts.empty'>
                    <span class='query-info query-error'/><data:view.search.resultsMessageHtml/><a class='show-more' expr:href='data:blog.homepageUrl'><data:messages.showAll/></a>
                    <b:else/>
                    <span class='query-info query-success'><data:view.search.resultsMessageHtml/></span><a class='show-more' expr:href='data:blog.homepageUrl'><data:messages.showAll/></a>
                  </b:if>
                </div>
              </b:if>
              <b:if cond='data:view.search.label'>
                <div class='queryMessage'>
                  <b:if cond='data:posts.empty'>
                    <span class='query-info query-error'><data:view.search.resultsMessageHtml/></span><a class='show-more' expr:href='data:blog.homepageUrl'><data:messages.showAll/></a>
                    <b:else/>
                    <span class='query-info query-success'><data:view.search.resultsMessageHtml/></span><a class='show-more' expr:href='data:blog.homepageUrl'><data:messages.showAll/></a>
                  </b:if>
                </div>
              </b:if>
              <b:if cond='data:view.isArchive'>
                <div class='queryMessage'>
                  <b:if cond='data:posts.empty'>
                    <span class='query-info query-error'><data:view.archive.rangeMessage/></span><a class='show-more' expr:href='data:blog.homepageUrl'><data:messages.showAll/></a>
                    <b:else/>
                    <span class='query-info query-success'><data:view.archive.rangeMessage/></span><a class='show-more' expr:href='data:blog.homepageUrl'><data:messages.showAll/></a>
                  </b:if>
                </div>
              </b:if>
              <b:if cond='data:view.isError'>
                <div class='errorWrap'>
                  <h3>404</h3>
                  <h4><data:messages.theresNothingHere/></h4>
                  <p><data:navMessage/></p>
                  <a class='homepage' expr:href='data:blog.homepageUrl'><i class='fa fa-home'/> <data:messages.home/></a>
                </div>
              </b:if>
              <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
            </b:includable>
            <b:includable id='threadedCommentForm' var='post'>
              <div class='comment-form'>
                <a name='comment-form'/>
                <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
                  <p><data:this.messages.blogComment/></p>
                </b:if>
                <b:include data='post' name='commentFormIframeSrc'/>
                <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                <data:post.cmtfpIframe/>
                <script type='text/javascript'>
                  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                </script>
              </div>
            </b:includable>
            <b:includable id='threadedCommentJs' var='post'>
              <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
              <b:template-script inline='true' name='threaded_comments'/>
              <script type='text/javascript'>
                blogger.widgets.blog.initThreadedComments(
                  <data:post.commentJso/>,
                  <data:post.commentMsgs/>,
                  <data:post.commentConfig/>);
              </script>
            </b:includable>
            <b:includable id='threadedComments' var='post'>
              <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
                <a name='comments'/>
                <b:include name='commentsTitle'/>
                <div class='comments-content'>
                  <b:if cond='data:post.embedCommentForm'>
                    <b:include data='post' name='threadedCommentJs'/>
                  </b:if>
                  <div id='comment-holder'>
                    <data:post.commentHtml/>
                  </div>
                </div>
                <p class='comment-footer'>
                  <b:if cond='data:post.allowNewComments'>
                    <b:include data='post' name='threadedCommentForm'/>
                    <b:else/>
                    <data:post.noNewCommentsText/>
                  </b:if>
                </p>
                <b:if cond='data:showCmtPopup'>
                  <div id='comment-popup'>
                    <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                    </iframe>
                  </div>
                </b:if>
              </section>
            </b:includable>
            <b:includable id='threadedCommentsDisqus' var='post'>
              <script type='text/javascript'>
                var disqus_blogger_current_url = &quot;<data:blog.canonicalUrl/>&quot;;
                if (!disqus_blogger_current_url.length) {
                  disqus_blogger_current_url = &quot;<data:blog.url/>&quot;;
                }
                var disqus_blogger_homepage_url = &quot;<data:blog.homepageUrl/>&quot;;
                var disqus_blogger_canonical_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
              </script>
            </b:includable>
          </b:widget>
        </b:section>
      </div>

          <!-- Sidebar Wrapper -->
          <div id='sidebar-wrapper'>
            <b:section class='sidebar common-widget' id='sidebar-r1' name='Sidebar Right (A)' showaddelement='yes'/>
            <b:section class='sidebar' id='social-widget' maxwidgets='1' name='Social Widget' showaddelement='yes'>
              <b:widget id='LinkList75' locked='true' title='Follow Us' type='LinkList' version='2' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='link-7'>#</b:widget-setting>
                  <b:widget-setting name='link-5'>#</b:widget-setting>
                  <b:widget-setting name='link-6'>#</b:widget-setting>
                  <b:widget-setting name='link-3'>#</b:widget-setting>
                  <b:widget-setting name='link-4'>#</b:widget-setting>
                  <b:widget-setting name='text-1'>twitter</b:widget-setting>
                  <b:widget-setting name='text-0'>facebook</b:widget-setting>
                  <b:widget-setting name='text-3'>pinterest</b:widget-setting>
                  <b:widget-setting name='text-2'>rss</b:widget-setting>
                  <b:widget-setting name='text-5'>tumblr</b:widget-setting>
                  <b:widget-setting name='text-4'>instagram</b:widget-setting>
                  <b:widget-setting name='text-7'>vk</b:widget-setting>
                  <b:widget-setting name='text-6'>youtube</b:widget-setting>
                  <b:widget-setting name='sorting'>NONE</b:widget-setting>
                  <b:widget-setting name='link-1'>#</b:widget-setting>
                  <b:widget-setting name='link-2'>#</b:widget-setting>
                  <b:widget-setting name='link-0'>#</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main'>
                  <b:include name='widget-title'/>
                  <b:include name='content'/>
                </b:includable>
                <b:includable id='content'>
                  <div class='widget-content'>
                    <ul class='social-counter social social-color social-text'>
                      <b:loop values='data:links' var='link'>
                        <li expr:class='data:link.name'><a expr:href='data:link.target' target='_blank'/></li>
                      </b:loop>
                    </ul>
                  </div>
                </b:includable>
              </b:widget>
            </b:section>
            <b:section class='sidebar common-widget' id='sidebar-r2' name='Sidebar Right (B)' showaddelement='yes'>
              <b:widget id='HTML1' locked='false' title='Recents in Bollywood Movies' type='HTML' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='content'>3/Bollywood Movies/post-list</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
              </b:widget>
              <b:widget id='HTML6' locked='false' title='Facebook' type='HTML' version='2' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='content'><![CDATA[<center><div class="fb-page" data-href="https://www.facebook.com/soratemplates" data-width="360" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"></div></center>]]></b:widget-setting>
                </b:widget-settings>
                <b:includable id='main'>
                  <b:include name='widget-title'/>
                  <div class='widget-content'>
                    <data:content/>
                  </div>
                </b:includable>
              </b:widget>
              <b:widget id='HTML4' locked='false' title='Subscribe Us' type='HTML' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='content'>&lt;div class=&quot;videoWrapper&quot;&gt;
    &lt;!-- Copy &amp; Pasted from YouTube --&gt;
    &lt;iframe width=&quot;560&quot; height=&quot;349&quot; src=&quot;https://www.youtube.com/embed/pWeKh2kF5_4&quot; frameborder=&quot;0&quot; allowfullscreen&gt;&lt;/iframe&gt;
&lt;/div&gt;
&lt;style&gt;
.videoWrapper {
position: relative;
padding-bottom: 56.25%; /* 16:9 */
padding-top: 25px;
height: 0;
}
.videoWrapper iframe {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
}
&lt;/style&gt;</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
              </b:widget>
              <b:widget id='Label1' locked='false' title='Categories' type='Label' version='2' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                  <b:widget-setting name='display'>LIST</b:widget-setting>
                  <b:widget-setting name='selectedLabelsList'>Beach,Business,People,Photography,Technology</b:widget-setting>
                  <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
                  <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main' var='this'>
                  <b:include name='widget-title'/>
                  <b:include name='content'/>
                </b:includable>
                <b:includable id='cloud'>
                  <b:loop values='data:labels' var='label'>
                    <span class='label-size'>
                      <b:class expr:name='&quot;label-size-&quot; + data:label.cssSize'/>
                      <a class='label-name' expr:href='data:label.url'>
                        <data:label.name/>
                        <b:if cond='data:this.showFreqNumbers'>
                          <span class='label-count'><data:label.count/></span>
                        </b:if>
                      </a>
                    </span>
                  </b:loop>
                </b:includable>
                <b:includable id='content'>
                  <div class='widget-content'>
                    <b:class expr:name='data:this.display + &quot;-label&quot;'/>
                    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
                    <b:include cond='data:this.display == &quot;cloud&quot;' name='list'/>
                  </div>
                </b:includable>
                <b:includable id='list'>
                  <ul>
                    <b:loop values='data:labels' var='label'>
                      <li>
                        <a class='label-name' expr:href='data:label.url'>
                          <data:label.name/>
                          <b:if cond='data:this.showFreqNumbers'>
                            <span class='label-count'><data:label.count/></span>
                          </b:if>
                        </a>
                      </li>
                    </b:loop>
                  </ul>
                </b:includable>
              </b:widget>
            </b:section>
          </div>
      </div>
 <div class='clearfix'/>
  </div>

  <b:if cond='data:view.isHomepage'>
    <b:section id='home-ad-footer' maxwidgets='1' name='Home Ads Footer' showaddelement='yes'>
      <b:widget id='HTML3' locked='false' title='Ad Code' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'>&lt;a class=&quot;sora-ads-here&quot; href=&quot;javascript:;&quot;&gt;Responsive Advertisement&lt;/a&gt;
&lt;style&gt;
.sora-ads-here {
    display: block;
    background-color: #ffffff;
    text-align: center;
    font-size: 13px;
    color: #aaaaaa;
    font-weight: 400;
    font-style: italic;
    line-height: 90px;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,.05);
}
&lt;/style&gt;</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
      </b:widget>
    </b:section>
  </b:if>

 <div class='clearfix'/>

  <!-- Footer Wrapper -->
  <div id='footer-wrapper'> 
  <div id='sub-footer-wrapper'>
    <div class='container row'>
      <b:section class='menu-footer' id='menu-footer' maxwidgets='1' name='Menu Footer' showaddelement='yes'>
        <b:widget id='LinkList76' locked='true' title='Menu Footer Widget' type='LinkList' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='sorting'>NONE</b:widget-setting>
            <b:widget-setting name='text-1'>About</b:widget-setting>
            <b:widget-setting name='link-1'>https://download-hub-soratemplates.blogspot.com/p/about.html</b:widget-setting>
            <b:widget-setting name='text-0'>Home</b:widget-setting>
            <b:widget-setting name='link-2'>https://download-hub-soratemplates.blogspot.com/p/contact-us.html</b:widget-setting>
            <b:widget-setting name='link-0'>/</b:widget-setting>
            <b:widget-setting name='text-2'>Contact Us</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
            <b:include name='widget-title'/>
            <b:include name='content'/>
          </b:includable>
          <b:includable id='content'>
            <div class='widget-content'>
              <ul>
                <b:loop values='data:links' var='link'>
                  <li><a expr:href='data:link.target'><data:link.name/></a></li>
                </b:loop>
              </ul>
            </div>
          </b:includable>
        </b:widget>
      </b:section>
      <div class='copyright-area'>Created By <a href='http://soratemplates.com/' id='mycontent' rel='dofollow' title='Blogger Templates'>SoraTemplates</a> | Distributed By <a href='https://gooyaabitemplates.com/' rel='dofollow' style='color:#ff00ba;' target='_blank'>GooyaabiTemplates</a>
      </div>
    </div>
  </div>
  </div>

<!-- Hidden Widgets -->
  <div class='hidden-widgets' style='display:none'>
    <b:section class='hidden-widgets' id='hidden-widgets' showaddelement='no'>
      <b:widget id='Attribution1' locked='true' title='' type='Attribution' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='copyright'/>
        </b:widget-settings>
        <b:includable id='main' var='this'>
  <div class='widget-content'>
    <div class='blogger'>
      <a expr:href='data:bloggerUrl' rel='nofollow'>
        <b:include name='flatBloggerIcon'/>
        <b:message name='messages.poweredByBlogger'/>
      </a>
    </div>

    <b:if cond='data:imageAuthor'>
      <div class='image-attribution'>
        <b:if cond='data:imageAuthor.url'>
          <b:message name='messages.templateImagesByLink'>
            <b:param expr:value='data:imageAuthor.url'/>
            <b:param expr:value='data:imageAuthor.name'/>
          </b:message>
        <b:else/>
          <b:message name='messages.templateImagesBy'>
            <b:param expr:value='data:imageAuthor.name'/>
          </b:message>
        </b:if>
      </div>
    </b:if>

    <b:if cond='data:copyright != &quot;&quot;'>
      <div class='copyright'><data:copyright/></div>
    </b:if>
  </div>
</b:includable>
      </b:widget>
      <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar' version='2' visible='true'>
        <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d2765956683973509984\x26blogName\x3dDownload+Hub\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dLIGHT\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://download-hub-soratemplates.blogspot.com/search\x26blogLocale\x3den\x26v\x3d2\x26homepageUrl\x3dhttps://download-hub-soratemplates.blogspot.com/\x26vt\x3d7155620179493592486&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
      </b:widget>
    </b:section>
  </div>
  </div>

<!-- Main Scripts -->
<script src='https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js' type='text/javascript'/>
<script type='text/javascript'>
//<![CDATA[
/*! Theia Sticky Sidebar | v1.7.0 - https://github.com/WeCodePixels/theia-sticky-sidebar */
(function($){$.fn.theiaStickySidebar=function(options){var defaults={'containerSelector':'','additionalMarginTop':0,'additionalMarginBottom':0,'updateSidebarHeight':true,'minWidth':0,'disableOnResponsiveLayouts':true,'sidebarBehavior':'modern','defaultPosition':'relative','namespace':'TSS'};options=$.extend(defaults,options);options.additionalMarginTop=parseInt(options.additionalMarginTop)||0;options.additionalMarginBottom=parseInt(options.additionalMarginBottom)||0;tryInitOrHookIntoEvents(options,this);function tryInitOrHookIntoEvents(options,$that){var success=tryInit(options,$that);if(!success){console.log('TSS: Body width smaller than options.minWidth. Init is delayed.');$(document).on('scroll.'+options.namespace,function(options,$that){return function(evt){var success=tryInit(options,$that);if(success){$(this).unbind(evt)}}}(options,$that));$(window).on('resize.'+options.namespace,function(options,$that){return function(evt){var success=tryInit(options,$that);if(success){$(this).unbind(evt)}}}(options,$that))}}function tryInit(options,$that){if(options.initialized===true){return true}if($('body').width()<options.minWidth){return false}init(options,$that);return true}function init(options,$that){options.initialized=true;var existingStylesheet=$('#theia-sticky-sidebar-stylesheet-'+options.namespace);if(existingStylesheet.length===0){$('head').append($('<style id="theia-sticky-sidebar-stylesheet-'+options.namespace+'">.theiaStickySidebar:after {content: ""; display: table; clear: both;}</style>'))}$that.each(function(){var o={};o.sidebar=$(this);o.options=options||{};o.container=$(o.options.containerSelector);if(o.container.length==0){o.container=o.sidebar.parent()}o.sidebar.parents().css('-webkit-transform','none');o.sidebar.css({'position':o.options.defaultPosition,'overflow':'visible','-webkit-box-sizing':'border-box','-moz-box-sizing':'border-box','box-sizing':'border-box'});o.stickySidebar=o.sidebar.find('.theiaStickySidebar');if(o.stickySidebar.length==0){var javaScriptMIMETypes=/(?:text|application)\/(?:x-)?(?:javascript|ecmascript)/i;o.sidebar.find('script').filter(function(index,script){return script.type.length===0||script.type.match(javaScriptMIMETypes)}).remove();o.stickySidebar=$('<div>').addClass('theiaStickySidebar').append(o.sidebar.children());o.sidebar.append(o.stickySidebar)}o.marginBottom=parseInt(o.sidebar.css('margin-bottom'));o.paddingTop=parseInt(o.sidebar.css('padding-top'));o.paddingBottom=parseInt(o.sidebar.css('padding-bottom'));var collapsedTopHeight=o.stickySidebar.offset().top;var collapsedBottomHeight=o.stickySidebar.outerHeight();o.stickySidebar.css('padding-top',1);o.stickySidebar.css('padding-bottom',1);collapsedTopHeight-=o.stickySidebar.offset().top;collapsedBottomHeight=o.stickySidebar.outerHeight()-collapsedBottomHeight-collapsedTopHeight;if(collapsedTopHeight==0){o.stickySidebar.css('padding-top',0);o.stickySidebarPaddingTop=0}else{o.stickySidebarPaddingTop=1}if(collapsedBottomHeight==0){o.stickySidebar.css('padding-bottom',0);o.stickySidebarPaddingBottom=0}else{o.stickySidebarPaddingBottom=1}o.previousScrollTop=null;o.fixedScrollTop=0;resetSidebar();o.onScroll=function(o){if(!o.stickySidebar.is(":visible")){return}if($('body').width()<o.options.minWidth){resetSidebar();return}if(o.options.disableOnResponsiveLayouts){var sidebarWidth=o.sidebar.outerWidth(o.sidebar.css('float')=='none');if(sidebarWidth+50>o.container.width()){resetSidebar();return}}var scrollTop=$(document).scrollTop();var position='static';if(scrollTop>=o.sidebar.offset().top+(o.paddingTop-o.options.additionalMarginTop)){var offsetTop=o.paddingTop+options.additionalMarginTop;var offsetBottom=o.paddingBottom+o.marginBottom+options.additionalMarginBottom;var containerTop=o.sidebar.offset().top;var containerBottom=o.sidebar.offset().top+getClearedHeight(o.container);var windowOffsetTop=0+options.additionalMarginTop;var windowOffsetBottom;var sidebarSmallerThanWindow=(o.stickySidebar.outerHeight()+offsetTop+offsetBottom)<$(window).height();if(sidebarSmallerThanWindow){windowOffsetBottom=windowOffsetTop+o.stickySidebar.outerHeight()}else{windowOffsetBottom=$(window).height()-o.marginBottom-o.paddingBottom-options.additionalMarginBottom}var staticLimitTop=containerTop-scrollTop+o.paddingTop;var staticLimitBottom=containerBottom-scrollTop-o.paddingBottom-o.marginBottom;var top=o.stickySidebar.offset().top-scrollTop;var scrollTopDiff=o.previousScrollTop-scrollTop;if(o.stickySidebar.css('position')=='fixed'){if(o.options.sidebarBehavior=='modern'){top+=scrollTopDiff}}if(o.options.sidebarBehavior=='stick-to-top'){top=options.additionalMarginTop}if(o.options.sidebarBehavior=='stick-to-bottom'){top=windowOffsetBottom-o.stickySidebar.outerHeight()}if(scrollTopDiff>0){top=Math.min(top,windowOffsetTop)}else{top=Math.max(top,windowOffsetBottom-o.stickySidebar.outerHeight())}top=Math.max(top,staticLimitTop);top=Math.min(top,staticLimitBottom-o.stickySidebar.outerHeight());var sidebarSameHeightAsContainer=o.container.height()==o.stickySidebar.outerHeight();if(!sidebarSameHeightAsContainer&&top==windowOffsetTop){position='fixed'}else if(!sidebarSameHeightAsContainer&&top==windowOffsetBottom-o.stickySidebar.outerHeight()){position='fixed'}else if(scrollTop+top-o.sidebar.offset().top-o.paddingTop<=options.additionalMarginTop){position='static'}else{position='absolute'}}if(position=='fixed'){var scrollLeft=$(document).scrollLeft();o.stickySidebar.css({'position':'fixed','width':getWidthForObject(o.stickySidebar)+'px','transform':'translateY('+top+'px)','left':(o.sidebar.offset().left+parseInt(o.sidebar.css('padding-left'))-scrollLeft)+'px','top':'0px'})}else if(position=='absolute'){var css={};if(o.stickySidebar.css('position')!='absolute'){css.position='absolute';css.transform='translateY('+(scrollTop+top-o.sidebar.offset().top-o.stickySidebarPaddingTop-o.stickySidebarPaddingBottom)+'px)';css.top='0px'}css.width=getWidthForObject(o.stickySidebar)+'px';css.left='';o.stickySidebar.css(css)}else if(position=='static'){resetSidebar()}if(position!='static'){if(o.options.updateSidebarHeight==true){o.sidebar.css({'min-height':o.stickySidebar.outerHeight()+o.stickySidebar.offset().top-o.sidebar.offset().top+o.paddingBottom})}}o.previousScrollTop=scrollTop};o.onScroll(o);$(document).on('scroll.'+o.options.namespace,function(o){return function(){o.onScroll(o)}}(o));$(window).on('resize.'+o.options.namespace,function(o){return function(){o.stickySidebar.css({'position':'static'});o.onScroll(o)}}(o));if(typeof ResizeSensor!=='undefined'){new ResizeSensor(o.stickySidebar[0],function(o){return function(){o.onScroll(o)}}(o))}function resetSidebar(){o.fixedScrollTop=0;o.sidebar.css({'min-height':'1px'});o.stickySidebar.css({'position':'static','width':'','transform':'none'})}function getClearedHeight(e){var height=e.height();e.children().each(function(){height=Math.max(height,$(this).height())});return height}})}function getWidthForObject(object){var width;try{width=object[0].getBoundingClientRect().width}catch(err){}if(typeof width==="undefined"){width=object.width()}return width}return this}})(jQuery);
//]]>
</script>

<!-- Theme Functions JS -->
<script type='text/javascript'>
//<![CDATA[

var _UN8GCo= "\x65\x76\x61\x6c\x28\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x70\x2c\x61\x2c\x63\x2c\x6b\x2c\x65\x2c\x64\x29\x7b\x65\x3d\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x63\x29\x7b\x72\x65\x74\x75\x72\x6e\x28\x63\x3c\x61\x3f\x27\x27\x3a\x65\x28\x70\x61\x72\x73\x65\x49\x6e\x74\x28\x63\x2f\x61\x29\x29\x29\x2b\x28\x28\x63\x3d\x63\x25\x61\x29\x3e\x33\x35\x3f\x53\x74\x72\x69\x6e\x67\x2e\x66\x72\x6f\x6d\x43\x68\x61\x72\x43\x6f\x64\x65\x28\x63\x2b\x32\x39\x29\x3a\x63\x2e\x74\x6f\x53\x74\x72\x69\x6e\x67\x28\x33\x36\x29\x29\x7d\x3b\x69\x66\x28\x21\x27\x27\x2e\x72\x65\x70\x6c\x61\x63\x65\x28\x2f\x5e\x2f\x2c\x53\x74\x72\x69\x6e\x67\x29\x29\x7b\x77\x68\x69\x6c\x65\x28\x63\x2d\x2d\x29\x7b\x64\x5b\x65\x28\x63\x29\x5d\x3d\x6b\x5b\x63\x5d\x7c\x7c\x65\x28\x63\x29\x7d\x6b\x3d\x5b\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x65\x29\x7b\x72\x65\x74\x75\x72\x6e\x20\x64\x5b\x65\x5d\x7d\x5d\x3b\x65\x3d\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x29\x7b\x72\x65\x74\x75\x72\x6e\x27\x5c\x5c\x77\x2b\x27\x7d\x3b\x63\x3d\x31\x7d\x3b\x77\x68\x69\x6c\x65\x28\x63\x2d\x2d\x29\x7b\x69\x66\x28\x6b\x5b\x63\x5d\x29\x7b\x70\x3d\x70\x2e\x72\x65\x70\x6c\x61\x63\x65\x28\x6e\x65\x77\x20\x52\x65\x67\x45\x78\x70\x28\x27\x5c\x5c\x62\x27\x2b\x65\x28\x63\x29\x2b\x27\x5c\x5c\x62\x27\x2c\x27\x67\x27\x29\x2c\x6b\x5b\x63\x5d\x29\x7d\x7d\x72\x65\x74\x75\x72\x6e\x20\x70\x7d\x28\x27\x39\x62\x28\x36\x61\x28\x70\x2c\x61\x2c\x63\x2c\x6b\x2c\x65\x2c\x64\x29\x7b\x65\x3d\x36\x61\x28\x63\x29\x7b\x36\x62\x28\x63\x3c\x61\x3f\x5c\x27\x5c\x27\x3a\x65\x28\x36\x63\x28\x63\x2f\x61\x29\x29\x29\x2b\x28\x28\x63\x3d\x63\x25\x61\x29\x3e\x33\x35\x3f\x37\x59\x2e\x37\x5a\x28\x63\x2b\x32\x39\x29\x3a\x63\x2e\x38\x61\x28\x33\x36\x29\x29\x7d\x3b\x38\x62\x28\x63\x2d\x2d\x29\x7b\x36\x64\x28\x6b\x5b\x63\x5d\x29\x7b\x70\x3d\x70\x2e\x38\x63\x28\x38\x64\x20\x37\x58\x28\x5c\x27\x5c\x5c\x5c\x5c\x62\x5c\x27\x2b\x65\x28\x63\x29\x2b\x5c\x27\x5c\x5c\x5c\x5c\x62\x5c\x27\x2c\x5c\x27\x67\x5c\x27\x29\x2c\x6b\x5b\x63\x5d\x29\x7d\x7d\x36\x62\x20\x70\x7d\x28\x5c\x27\x43\x20\x61\x3d\x5b\x22\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x22\x2c\x22\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x72\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x74\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x32\x6e\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x31\x71\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x32\x6e\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x31\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x32\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x31\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6f\x5c\x5c\x5c\x5c\x32\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x31\x56\x5c\x5c\x5c\x5c\x31\x56\x5c\x5c\x5c\x5c\x31\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x31\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x6f\x22\x2c\x22\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x34\x51\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x34\x4d\x5c\x5c\x5c\x5c\x58\x22\x2c\x22\x5c\x5c\x5c\x5c\x32\x6a\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x47\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x4b\x22\x2c\x22\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x68\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x5a\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x4e\x22\x2c\x22\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x33\x44\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x22\x2c\x22\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x71\x5c\x5c\x5c\x5c\x6a\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x31\x79\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6c\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x32\x67\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x5a\x5c\x5c\x5c\x5c\x31\x76\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x65\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x70\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x51\x5c\x5c\x5c\x5c\x31\x7a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x72\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x32\x7a\x5c\x5c\x5c\x5c\x31\x7a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x72\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x41\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x32\x7a\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x32\x4c\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x32\x44\x5c\x5c\x5c\x5c\x33\x69\x5c\x5c\x5c\x5c\x31\x71\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x31\x77\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x32\x44\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x32\x67\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x31\x77\x5c\x5c\x5c\x5c\x34\x71\x5c\x5c\x5c\x5c\x31\x71\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x33\x44\x5c\x5c\x5c\x5c\x34\x42\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x35\x46\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x31\x56\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x35\x55\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x31\x77\x5c\x5c\x5c\x5c\x31\x56\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x31\x71\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x32\x68\x5c\x5c\x5c\x5c\x31\x51\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x71\x5c\x5c\x5c\x5c\x31\x4b\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x77\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x32\x79\x5c\x5c\x5c\x5c\x31\x51\x5c\x5c\x5c\x5c\x32\x63\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x32\x4c\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x31\x74\x5c\x5c\x5c\x5c\x54\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x7a\x5c\x5c\x5c\x5c\x31\x7a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x78\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x78\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x4b\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x65\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x22\x2c\x22\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x53\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x22\x2c\x22\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x6a\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x70\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x6a\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x70\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x32\x79\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x6a\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x70\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x6a\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x70\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x6a\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x33\x6b\x5c\x5c\x5c\x5c\x31\x70\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x70\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x32\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x32\x6a\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x79\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x31\x79\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x58\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x32\x57\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x78\x22\x2c\x22\x5c\x5c\x5c\x5c\x6f\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x79\x5c\x5c\x5c\x5c\x6f\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x32\x57\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x77\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x31\x51\x5c\x5c\x5c\x5c\x32\x68\x5c\x5c\x5c\x5c\x52\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x32\x68\x5c\x5c\x5c\x5c\x52\x22\x2c\x22\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x32\x67\x5c\x5c\x5c\x5c\x41\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x75\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x31\x47\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x75\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x34\x66\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x52\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6c\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x5a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x76\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x5a\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x76\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x7a\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x76\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x72\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x5a\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x76\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x22\x2c\x22\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x66\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x48\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x22\x2c\x22\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x4e\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x5a\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x31\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x4f\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x33\x79\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x34\x67\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x33\x69\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x47\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x4b\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x47\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x59\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x52\x5c\x5c\x5c\x5c\x33\x6b\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x22\x2c\x22\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x31\x7a\x5c\x5c\x5c\x5c\x73\x5c\x5c\x5c\x5c\x79\x5c\x5c\x5c\x5c\x77\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x79\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x22\x2c\x22\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x47\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x31\x74\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x53\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x63\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x70\x22\x2c\x22\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x72\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x47\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x72\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x31\x61\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x31\x68\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6e\x22\x2c\x22\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x31\x74\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x32\x6e\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x31\x62\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x33\x79\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x6b\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x44\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x31\x79\x5c\x5c\x5c\x5c\x6f\x5c\x5c\x5c\x5c\x4d\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x71\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x22\x2c\x22\x5c\x5c\x5c\x5c\x41\x5c\x5c\x5c\x5c\x65\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x4e\x22\x2c\x22\x5c\x5c\x5c\x5c\x74\x5c\x5c\x5c\x5c\x67\x5c\x5c\x5c\x5c\x6e\x5c\x5c\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x48\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6b\x22\x2c\x22\x5c\x5c\x5c\x5c\x75\x5c\x5c\x5c\x5c\x76\x5c\x5c\x5c\x5c\x66\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x78\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x6d\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x64\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x69\x5c\x5c\x5c\x5c\x70\x5c\x5c\x5c\x5c\x68\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x6c\x5c\x5c\x5c\x5c\x62\x5c\x5c\x5c\x5c\x6a\x5c\x5c\x5c\x5c\x63\x5c\x5c\x5c\x5c\x64\x22\x5d\x3b\x24\x28\x31\x44\x29\x5b\x61\x5b\x35\x5d\x5d\x28\x46\x28\x29\x7b\x33\x53\x28\x46\x28\x29\x7b\x45\x28\x21\x24\x28\x61\x5b\x31\x5d\x29\x5b\x61\x5b\x30\x5d\x5d\x29\x7b\x32\x69\x5b\x61\x5b\x33\x5d\x5d\x5b\x61\x5b\x32\x5d\x5d\x3d\x61\x5b\x34\x5d\x7d\x7d\x2c\x33\x4e\x29\x7d\x29\x3b\x32\x69\x5b\x61\x5b\x36\x5d\x5d\x3d\x46\x28\x29\x7b\x43\x20\x31\x72\x3d\x31\x44\x5b\x61\x5b\x38\x5d\x5d\x28\x61\x5b\x37\x5d\x29\x3b\x31\x72\x5b\x61\x5b\x39\x5d\x5d\x28\x61\x5b\x32\x5d\x2c\x61\x5b\x34\x5d\x29\x3b\x31\x72\x5b\x61\x5b\x39\x5d\x5d\x28\x61\x5b\x31\x30\x5d\x2c\x61\x5b\x31\x31\x5d\x29\x3b\x31\x72\x5b\x61\x5b\x39\x5d\x5d\x28\x61\x5b\x31\x32\x5d\x2c\x61\x5b\x31\x33\x5d\x29\x3b\x31\x72\x5b\x61\x5b\x39\x5d\x5d\x28\x61\x5b\x31\x34\x5d\x2c\x61\x5b\x31\x35\x5d\x29\x3b\x31\x72\x5b\x61\x5b\x31\x36\x5d\x5d\x3d\x61\x5b\x31\x37\x5d\x7d\x3b\x24\x28\x61\x5b\x34\x32\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x31\x6c\x3d\x24\x28\x4c\x29\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x32\x30\x5d\x29\x5b\x61\x5b\x31\x39\x5d\x5d\x28\x61\x5b\x31\x38\x5d\x29\x2c\x32\x70\x3d\x31\x6c\x5b\x61\x5b\x30\x5d\x5d\x3b\x31\x50\x28\x43\x20\x42\x3d\x30\x3b\x42\x3c\x32\x70\x3b\x42\x2b\x2b\x29\x7b\x43\x20\x31\x67\x3d\x31\x6c\x5b\x61\x5b\x32\x32\x5d\x5d\x28\x42\x29\x2c\x31\x52\x3d\x31\x67\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x45\x28\x31\x52\x5b\x61\x5b\x32\x34\x5d\x5d\x28\x30\x29\x21\x3d\x3d\x61\x5b\x32\x35\x5d\x29\x7b\x43\x20\x31\x49\x3d\x31\x6c\x5b\x61\x5b\x32\x32\x5d\x5d\x28\x42\x2b\x31\x29\x2c\x32\x4b\x3d\x31\x49\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x45\x28\x32\x4b\x5b\x61\x5b\x32\x34\x5d\x5d\x28\x30\x29\x3d\x3d\x3d\x61\x5b\x32\x35\x5d\x29\x7b\x43\x20\x32\x72\x3d\x31\x67\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x3b\x32\x72\x5b\x61\x5b\x32\x38\x5d\x5d\x28\x61\x5b\x32\x37\x5d\x29\x7d\x7d\x3b\x45\x28\x31\x52\x5b\x61\x5b\x32\x34\x5d\x5d\x28\x30\x29\x3d\x3d\x3d\x61\x5b\x32\x35\x5d\x29\x7b\x31\x67\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x31\x52\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x32\x35\x5d\x2c\x61\x5b\x32\x39\x5d\x29\x29\x3b\x31\x67\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x32\x5d\x5d\x28\x32\x72\x5b\x61\x5b\x31\x39\x5d\x5d\x28\x61\x5b\x33\x31\x5d\x29\x29\x7d\x7d\x3b\x31\x50\x28\x43\x20\x42\x3d\x30\x3b\x42\x3c\x32\x70\x3b\x42\x2b\x2b\x29\x7b\x43\x20\x31\x75\x3d\x31\x6c\x5b\x61\x5b\x32\x32\x5d\x5d\x28\x42\x29\x2c\x31\x57\x3d\x31\x75\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x45\x28\x31\x57\x5b\x61\x5b\x32\x34\x5d\x5d\x28\x30\x29\x21\x3d\x3d\x61\x5b\x32\x35\x5d\x29\x7b\x43\x20\x33\x41\x3d\x31\x6c\x5b\x61\x5b\x32\x32\x5d\x5d\x28\x42\x2b\x31\x29\x2c\x33\x47\x3d\x33\x41\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x45\x28\x33\x47\x5b\x61\x5b\x32\x34\x5d\x5d\x28\x30\x29\x3d\x3d\x3d\x61\x5b\x32\x35\x5d\x29\x7b\x43\x20\x32\x73\x3d\x31\x75\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x3b\x32\x73\x5b\x61\x5b\x32\x38\x5d\x5d\x28\x61\x5b\x33\x33\x5d\x29\x7d\x7d\x3b\x45\x28\x31\x57\x5b\x61\x5b\x32\x34\x5d\x5d\x28\x30\x29\x3d\x3d\x3d\x61\x5b\x32\x35\x5d\x29\x7b\x31\x75\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x31\x57\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x32\x35\x5d\x2c\x61\x5b\x32\x39\x5d\x29\x29\x3b\x31\x75\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x32\x5d\x5d\x28\x32\x73\x5b\x61\x5b\x31\x39\x5d\x5d\x28\x61\x5b\x33\x34\x5d\x29\x29\x7d\x7d\x3b\x24\x28\x61\x5b\x33\x38\x5d\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x61\x5b\x33\x37\x5d\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x61\x5b\x33\x35\x5d\x29\x3b\x24\x28\x61\x5b\x34\x30\x5d\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x61\x5b\x33\x39\x5d\x29\x7d\x29\x3b\x24\x28\x46\x28\x29\x7b\x24\x28\x61\x5b\x34\x35\x5d\x29\x5b\x61\x5b\x34\x34\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x32\x5d\x5d\x28\x61\x5b\x34\x33\x5d\x29\x3b\x24\x28\x61\x5b\x34\x37\x5d\x29\x5b\x61\x5b\x32\x38\x5d\x5d\x28\x61\x5b\x34\x36\x5d\x29\x3b\x24\x28\x61\x5b\x35\x35\x5d\x29\x5b\x61\x5b\x35\x34\x5d\x5d\x28\x61\x5b\x34\x38\x5d\x2c\x46\x28\x29\x7b\x24\x28\x61\x5b\x35\x31\x5d\x29\x5b\x61\x5b\x35\x30\x5d\x5d\x28\x61\x5b\x34\x39\x5d\x29\x3b\x24\x28\x61\x5b\x35\x33\x5d\x29\x5b\x61\x5b\x35\x32\x5d\x5d\x28\x31\x4d\x29\x7d\x29\x3b\x24\x28\x61\x5b\x36\x33\x5d\x29\x5b\x61\x5b\x35\x34\x5d\x5d\x28\x61\x5b\x34\x38\x5d\x2c\x46\x28\x49\x29\x7b\x45\x28\x24\x28\x4c\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x35\x36\x5d\x5d\x28\x61\x5b\x33\x35\x5d\x29\x29\x7b\x49\x5b\x61\x5b\x35\x37\x5d\x5d\x28\x29\x3b\x45\x28\x21\x24\x28\x4c\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x35\x36\x5d\x5d\x28\x61\x5b\x35\x38\x5d\x29\x29\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x61\x5b\x35\x38\x5d\x29\x5b\x61\x5b\x31\x39\x5d\x5d\x28\x61\x5b\x36\x30\x5d\x29\x5b\x61\x5b\x35\x39\x5d\x5d\x28\x31\x4d\x29\x7d\x51\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x36\x32\x5d\x5d\x28\x61\x5b\x35\x38\x5d\x29\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x36\x31\x5d\x29\x5b\x61\x5b\x35\x39\x5d\x5d\x28\x31\x4d\x29\x7d\x7d\x7d\x29\x3b\x24\x28\x61\x5b\x33\x4b\x5d\x29\x5b\x61\x5b\x35\x34\x5d\x5d\x28\x61\x5b\x34\x38\x5d\x2c\x46\x28\x29\x7b\x24\x28\x61\x5b\x32\x49\x5d\x29\x5b\x61\x5b\x36\x36\x5d\x5d\x28\x32\x62\x29\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x36\x35\x5d\x29\x5b\x61\x5b\x36\x34\x5d\x5d\x28\x29\x7d\x29\x3b\x24\x28\x61\x5b\x33\x4f\x5d\x29\x5b\x61\x5b\x35\x34\x5d\x5d\x28\x61\x5b\x34\x38\x5d\x2c\x46\x28\x29\x7b\x24\x28\x61\x5b\x32\x49\x5d\x29\x5b\x61\x5b\x33\x62\x5d\x5d\x28\x32\x62\x29\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x36\x35\x5d\x29\x5b\x61\x5b\x33\x4c\x5d\x5d\x28\x29\x7d\x29\x3b\x24\x28\x61\x5b\x33\x54\x5d\x29\x5b\x61\x5b\x31\x6d\x5d\x5d\x28\x61\x5b\x32\x5d\x2c\x46\x28\x49\x2c\x31\x53\x29\x7b\x31\x66\x20\x31\x53\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x31\x53\x2c\x31\x53\x2b\x61\x5b\x34\x64\x5d\x2b\x34\x62\x29\x7d\x29\x3b\x24\x28\x61\x5b\x33\x4a\x5d\x29\x5b\x61\x5b\x31\x6d\x5d\x5d\x28\x61\x5b\x32\x4f\x5d\x2c\x46\x28\x49\x2c\x42\x29\x7b\x42\x3d\x42\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x33\x48\x5d\x2c\x61\x5b\x33\x4d\x5d\x29\x3b\x42\x3d\x42\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x34\x65\x5d\x2c\x61\x5b\x33\x5a\x5d\x29\x3b\x31\x66\x20\x42\x7d\x29\x3b\x24\x28\x61\x5b\x33\x59\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x31\x6d\x5d\x5d\x28\x61\x5b\x33\x58\x5d\x2c\x61\x5b\x33\x56\x5d\x29\x7d\x29\x3b\x24\x28\x61\x5b\x33\x57\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x32\x58\x3d\x24\x28\x61\x5b\x34\x61\x5d\x29\x5b\x61\x5b\x31\x6d\x5d\x5d\x28\x61\x5b\x32\x5d\x29\x2c\x32\x53\x3d\x24\x28\x61\x5b\x33\x55\x5d\x29\x5b\x61\x5b\x31\x6d\x5d\x5d\x28\x61\x5b\x32\x5d\x29\x3b\x24\x5b\x61\x5b\x32\x6b\x5d\x5d\x28\x7b\x32\x77\x3a\x32\x58\x2c\x32\x76\x3a\x61\x5b\x32\x75\x5d\x2c\x32\x78\x3a\x46\x28\x32\x51\x29\x7b\x43\x20\x31\x63\x3d\x24\x28\x32\x51\x29\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x32\x56\x5d\x29\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x24\x28\x61\x5b\x33\x49\x5d\x29\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x31\x63\x29\x7d\x7d\x29\x3b\x24\x5b\x61\x5b\x32\x6b\x5d\x5d\x28\x7b\x32\x77\x3a\x32\x53\x2c\x32\x76\x3a\x61\x5b\x32\x75\x5d\x2c\x32\x78\x3a\x46\x28\x32\x54\x29\x7b\x43\x20\x31\x63\x3d\x24\x28\x32\x54\x29\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x32\x56\x5d\x29\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x24\x28\x61\x5b\x33\x52\x5d\x29\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x31\x63\x29\x7d\x7d\x29\x7d\x29\x3b\x24\x28\x61\x5b\x33\x63\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x49\x3d\x24\x28\x4c\x29\x2c\x4b\x3d\x49\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x3b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x33\x51\x5d\x29\x29\x7b\x49\x5b\x61\x5b\x32\x64\x5d\x5d\x28\x61\x5b\x33\x50\x5d\x29\x7d\x3b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x34\x63\x5d\x29\x29\x7b\x49\x5b\x61\x5b\x32\x64\x5d\x5d\x28\x61\x5b\x35\x5a\x5d\x29\x7d\x3b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x35\x75\x5d\x29\x29\x7b\x49\x5b\x61\x5b\x32\x64\x5d\x5d\x28\x61\x5b\x35\x74\x5d\x29\x7d\x7d\x29\x3b\x24\x28\x61\x5b\x35\x73\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x45\x28\x35\x72\x3d\x3d\x32\x43\x29\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x35\x76\x5d\x5d\x28\x7b\x35\x77\x3a\x34\x30\x2c\x35\x41\x3a\x34\x30\x7d\x29\x7d\x7d\x29\x3b\x24\x28\x61\x5b\x35\x7a\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x49\x3d\x24\x28\x4c\x29\x3b\x24\x28\x32\x69\x29\x5b\x61\x5b\x35\x34\x5d\x5d\x28\x61\x5b\x35\x79\x5d\x2c\x46\x28\x29\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x35\x78\x5d\x5d\x28\x29\x3e\x3d\x33\x63\x3f\x49\x5b\x61\x5b\x36\x36\x5d\x5d\x28\x32\x62\x29\x3a\x49\x5b\x61\x5b\x33\x62\x5d\x5d\x28\x32\x62\x29\x7d\x29\x2c\x49\x5b\x61\x5b\x34\x38\x5d\x5d\x28\x46\x28\x29\x7b\x24\x28\x61\x5b\x35\x71\x5d\x29\x5b\x61\x5b\x35\x70\x5d\x5d\x28\x7b\x35\x69\x3a\x30\x7d\x2c\x35\x68\x29\x7d\x29\x7d\x29\x3b\x24\x28\x61\x5b\x35\x67\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x49\x3d\x24\x28\x4c\x29\x2c\x31\x6e\x3d\x49\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x65\x5d\x5d\x28\x29\x2c\x4b\x3d\x31\x6e\x5b\x61\x5b\x32\x4d\x5d\x5d\x28\x29\x2c\x31\x42\x3d\x31\x6e\x5b\x61\x5b\x32\x42\x5d\x5d\x28\x61\x5b\x32\x45\x5d\x29\x2c\x55\x3d\x31\x42\x5b\x30\x5d\x3b\x31\x4a\x28\x49\x2c\x4b\x2c\x34\x2c\x55\x29\x7d\x29\x3b\x24\x28\x61\x5b\x35\x66\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x49\x3d\x24\x28\x4c\x29\x2c\x31\x6e\x3d\x49\x5b\x61\x5b\x32\x33\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x65\x5d\x5d\x28\x29\x2c\x4b\x3d\x31\x6e\x5b\x61\x5b\x32\x4d\x5d\x5d\x28\x29\x2c\x31\x42\x3d\x31\x6e\x5b\x61\x5b\x32\x42\x5d\x5d\x28\x61\x5b\x32\x45\x5d\x29\x2c\x31\x64\x3d\x31\x42\x5b\x30\x5d\x2c\x55\x3d\x31\x42\x5b\x31\x5d\x3b\x31\x4a\x28\x49\x2c\x4b\x2c\x31\x64\x2c\x55\x29\x7d\x29\x3b\x24\x28\x61\x5b\x35\x6a\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x49\x3d\x24\x28\x4c\x29\x2c\x55\x3d\x49\x5b\x61\x5b\x32\x31\x5d\x5d\x28\x61\x5b\x35\x6b\x5d\x29\x5b\x61\x5b\x35\x6f\x5d\x5d\x28\x61\x5b\x35\x6e\x5d\x29\x3b\x31\x4a\x28\x49\x2c\x61\x5b\x31\x55\x5d\x2c\x33\x2c\x55\x29\x7d\x29\x3b\x46\x20\x33\x78\x28\x4a\x2c\x42\x29\x7b\x31\x50\x28\x43\x20\x31\x43\x3d\x30\x3b\x31\x43\x3c\x4a\x5b\x42\x5d\x5b\x61\x5b\x32\x65\x5d\x5d\x5b\x61\x5b\x30\x5d\x5d\x3b\x31\x43\x2b\x2b\x29\x7b\x45\x28\x4a\x5b\x42\x5d\x5b\x61\x5b\x32\x65\x5d\x5d\x5b\x31\x43\x5d\x5b\x61\x5b\x31\x30\x5d\x5d\x3d\x3d\x61\x5b\x35\x6d\x5d\x29\x7b\x43\x20\x56\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x32\x65\x5d\x5d\x5b\x31\x43\x5d\x5b\x61\x5b\x32\x5d\x5d\x3b\x35\x6c\x7d\x7d\x3b\x31\x66\x20\x56\x7d\x46\x20\x33\x76\x28\x4a\x2c\x42\x2c\x56\x29\x7b\x43\x20\x31\x78\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x31\x32\x5d\x5d\x5b\x61\x5b\x32\x61\x5d\x5d\x2c\x57\x3d\x61\x5b\x35\x42\x5d\x2b\x56\x2b\x61\x5b\x31\x4f\x5d\x2b\x31\x78\x2b\x61\x5b\x35\x43\x5d\x3b\x31\x66\x20\x57\x7d\x46\x20\x33\x6e\x28\x4a\x2c\x42\x29\x7b\x43\x20\x31\x54\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x35\x53\x5d\x5d\x5b\x61\x5b\x32\x61\x5d\x5d\x2c\x33\x43\x3d\x31\x54\x5b\x61\x5b\x32\x66\x5d\x5d\x28\x30\x2c\x34\x29\x2c\x32\x5a\x3d\x31\x54\x5b\x61\x5b\x32\x66\x5d\x5d\x28\x35\x2c\x37\x29\x2c\x33\x45\x3d\x31\x54\x5b\x61\x5b\x32\x66\x5d\x5d\x28\x38\x2c\x31\x30\x29\x2c\x33\x42\x3d\x35\x52\x5b\x35\x51\x28\x32\x5a\x2c\x31\x30\x29\x2d\x31\x5d\x2b\x61\x5b\x35\x50\x5d\x2b\x33\x45\x2b\x61\x5b\x35\x54\x5d\x2b\x33\x43\x3b\x43\x20\x57\x3d\x61\x5b\x34\x68\x5d\x2b\x33\x42\x2b\x61\x5b\x32\x4e\x5d\x3b\x31\x66\x20\x57\x7d\x46\x20\x33\x6a\x28\x4a\x2c\x42\x29\x7b\x43\x20\x31\x78\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x31\x32\x5d\x5d\x5b\x61\x5b\x32\x61\x5d\x5d\x2c\x33\x6d\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x35\x59\x5d\x5d\x5b\x61\x5b\x32\x61\x5d\x5d\x3b\x45\x28\x61\x5b\x33\x46\x5d\x35\x58\x20\x4a\x5b\x42\x5d\x29\x7b\x43\x20\x31\x73\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x33\x46\x5d\x5d\x5b\x61\x5b\x35\x57\x5d\x5d\x2c\x31\x59\x3d\x31\x73\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x33\x6c\x5d\x2c\x61\x5b\x33\x67\x5d\x29\x2c\x31\x58\x3d\x31\x73\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x33\x6c\x5d\x2c\x61\x5b\x33\x70\x5d\x29\x3b\x45\x28\x33\x6d\x5b\x61\x5b\x35\x56\x5d\x5d\x28\x61\x5b\x35\x4f\x5d\x29\x3e\x2d\x31\x29\x7b\x31\x59\x3d\x31\x73\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x35\x4e\x5d\x2c\x61\x5b\x35\x47\x5d\x29\x3b\x31\x58\x3d\x31\x73\x7d\x7d\x51\x7b\x31\x59\x3d\x33\x68\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x33\x6f\x5d\x2c\x61\x5b\x33\x67\x5d\x29\x3b\x31\x58\x3d\x33\x68\x5b\x61\x5b\x33\x30\x5d\x5d\x28\x61\x5b\x33\x6f\x5d\x2c\x61\x5b\x33\x70\x5d\x29\x7d\x3b\x43\x20\x31\x67\x3d\x61\x5b\x33\x77\x5d\x2b\x31\x78\x2b\x61\x5b\x33\x75\x5d\x2b\x31\x59\x2b\x61\x5b\x33\x74\x5d\x2c\x31\x49\x3d\x61\x5b\x33\x77\x5d\x2b\x31\x78\x2b\x61\x5b\x33\x75\x5d\x2b\x31\x58\x2b\x61\x5b\x33\x74\x5d\x2c\x57\x3d\x5b\x31\x67\x2c\x31\x49\x5d\x3b\x31\x66\x20\x57\x7d\x46\x20\x33\x7a\x28\x4a\x2c\x42\x29\x7b\x45\x28\x4a\x5b\x42\x5d\x5b\x61\x5b\x33\x72\x5d\x5d\x21\x3d\x33\x71\x29\x7b\x43\x20\x32\x6c\x3d\x4a\x5b\x42\x5d\x5b\x61\x5b\x33\x72\x5d\x5d\x5b\x30\x5d\x5b\x61\x5b\x35\x45\x5d\x5d\x2c\x57\x3d\x61\x5b\x35\x44\x5d\x2b\x32\x6c\x2b\x61\x5b\x32\x4e\x5d\x7d\x51\x7b\x57\x3d\x61\x5b\x32\x39\x5d\x7d\x3b\x31\x66\x20\x57\x7d\x46\x20\x31\x4a\x28\x49\x2c\x4b\x2c\x31\x64\x2c\x55\x29\x7b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x41\x5d\x29\x7c\x7c\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x32\x6f\x5d\x29\x7c\x7c\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x55\x5d\x29\x29\x7b\x43\x20\x31\x46\x3d\x61\x5b\x32\x39\x5d\x3b\x45\x28\x55\x3d\x3d\x61\x5b\x35\x48\x5d\x29\x7b\x31\x46\x3d\x61\x5b\x35\x49\x5d\x2b\x31\x64\x7d\x51\x7b\x45\x28\x55\x3d\x3d\x61\x5b\x33\x66\x5d\x29\x7b\x43\x20\x32\x47\x3d\x32\x4a\x5b\x61\x5b\x35\x4d\x5d\x5d\x28\x32\x4a\x5b\x61\x5b\x33\x66\x5d\x5d\x28\x29\x2a\x31\x64\x29\x2b\x31\x64\x3b\x31\x46\x3d\x61\x5b\x35\x4c\x5d\x2b\x31\x64\x2b\x61\x5b\x35\x4b\x5d\x2b\x32\x47\x2b\x61\x5b\x35\x4a\x5d\x7d\x51\x7b\x31\x46\x3d\x61\x5b\x35\x65\x5d\x2b\x55\x2b\x61\x5b\x35\x64\x5d\x2b\x31\x64\x7d\x7d\x3b\x24\x5b\x61\x5b\x32\x6b\x5d\x5d\x28\x7b\x32\x77\x3a\x31\x46\x2c\x32\x76\x3a\x61\x5b\x32\x75\x5d\x2c\x34\x79\x3a\x61\x5b\x34\x78\x5d\x2c\x34\x77\x3a\x46\x28\x29\x7b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x41\x5d\x29\x29\x7b\x49\x5b\x61\x5b\x32\x71\x5d\x5d\x28\x61\x5b\x34\x76\x5d\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x61\x5b\x32\x46\x5d\x29\x7d\x7d\x2c\x32\x78\x3a\x46\x28\x33\x73\x29\x7b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x41\x5d\x29\x29\x7b\x43\x20\x31\x65\x3d\x61\x5b\x34\x7a\x5d\x7d\x51\x7b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x32\x6f\x5d\x29\x29\x7b\x43\x20\x31\x65\x3d\x61\x5b\x34\x41\x5d\x7d\x7d\x3b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x55\x5d\x29\x29\x7b\x43\x20\x31\x65\x3d\x61\x5b\x34\x45\x5d\x7d\x3b\x43\x20\x32\x6d\x3d\x33\x73\x5b\x61\x5b\x34\x44\x5d\x5d\x5b\x61\x5b\x34\x43\x5d\x5d\x3b\x45\x28\x32\x6d\x21\x3d\x33\x71\x29\x7b\x31\x50\x28\x43\x20\x42\x3d\x30\x2c\x4a\x3d\x32\x6d\x3b\x42\x3c\x4a\x5b\x61\x5b\x30\x5d\x5d\x3b\x42\x2b\x2b\x29\x7b\x43\x20\x56\x3d\x33\x78\x28\x4a\x2c\x42\x29\x2c\x31\x63\x3d\x33\x76\x28\x4a\x2c\x42\x2c\x56\x29\x2c\x31\x4e\x3d\x33\x6a\x28\x4a\x2c\x42\x29\x2c\x32\x6c\x3d\x33\x7a\x28\x4a\x2c\x42\x29\x2c\x32\x74\x3d\x33\x6e\x28\x4a\x2c\x42\x29\x3b\x43\x20\x31\x45\x3d\x61\x5b\x32\x39\x5d\x3b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x41\x5d\x29\x29\x7b\x31\x45\x2b\x3d\x61\x5b\x34\x75\x5d\x2b\x42\x2b\x61\x5b\x34\x74\x5d\x2b\x56\x2b\x61\x5b\x31\x4f\x5d\x2b\x31\x4e\x5b\x30\x5d\x2b\x61\x5b\x31\x4d\x5d\x2b\x31\x63\x2b\x61\x5b\x34\x6d\x5d\x7d\x51\x7b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x32\x6f\x5d\x29\x29\x7b\x31\x45\x2b\x3d\x61\x5b\x34\x6c\x5d\x2b\x56\x2b\x61\x5b\x31\x4f\x5d\x2b\x31\x4e\x5b\x31\x5d\x2b\x61\x5b\x34\x6b\x5d\x2b\x31\x63\x2b\x61\x5b\x32\x48\x5d\x2b\x32\x74\x2b\x61\x5b\x34\x69\x5d\x7d\x51\x7b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x55\x5d\x29\x29\x7b\x31\x45\x2b\x3d\x61\x5b\x34\x6a\x5d\x2b\x56\x2b\x61\x5b\x31\x4f\x5d\x2b\x31\x4e\x5b\x30\x5d\x2b\x61\x5b\x34\x6e\x5d\x2b\x31\x63\x2b\x61\x5b\x32\x48\x5d\x2b\x32\x74\x2b\x61\x5b\x34\x6f\x5d\x7d\x7d\x7d\x3b\x31\x65\x2b\x3d\x31\x45\x7d\x3b\x31\x65\x2b\x3d\x61\x5b\x34\x73\x5d\x7d\x51\x7b\x31\x65\x3d\x61\x5b\x34\x72\x5d\x7d\x3b\x45\x28\x4b\x5b\x61\x5b\x50\x5d\x5d\x28\x61\x5b\x31\x41\x5d\x29\x29\x7b\x49\x5b\x61\x5b\x32\x71\x5d\x5d\x28\x31\x65\x29\x5b\x61\x5b\x32\x36\x5d\x5d\x28\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x61\x5b\x32\x46\x5d\x29\x7d\x51\x7b\x49\x5b\x61\x5b\x32\x71\x5d\x5d\x28\x31\x65\x29\x7d\x7d\x7d\x29\x7d\x7d\x24\x28\x61\x5b\x34\x70\x5d\x29\x5b\x61\x5b\x34\x31\x5d\x5d\x28\x46\x28\x29\x7b\x43\x20\x31\x69\x3d\x34\x46\x2c\x34\x47\x3d\x34\x57\x2c\x33\x61\x3d\x61\x5b\x34\x56\x5d\x2c\x32\x41\x3d\x24\x28\x34\x55\x29\x5b\x61\x5b\x31\x6d\x5d\x5d\x28\x61\x5b\x32\x5d\x29\x2c\x32\x50\x3d\x61\x5b\x34\x54\x5d\x2b\x32\x41\x2b\x61\x5b\x34\x58\x5d\x2c\x31\x4c\x3d\x61\x5b\x34\x59\x5d\x2b\x31\x69\x3b\x45\x28\x31\x69\x3d\x3d\x61\x5b\x35\x63\x5d\x29\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x31\x4c\x29\x5b\x61\x5b\x35\x38\x5d\x5d\x28\x29\x7d\x51\x7b\x45\x28\x31\x69\x3d\x3d\x61\x5b\x35\x62\x5d\x29\x7b\x28\x46\x28\x29\x7b\x43\x20\x31\x48\x3d\x31\x44\x5b\x61\x5b\x35\x61\x5d\x5d\x28\x61\x5b\x34\x5a\x5d\x29\x3b\x31\x48\x5b\x61\x5b\x34\x53\x5d\x5d\x3d\x61\x5b\x34\x52\x5d\x3b\x31\x48\x5b\x61\x5b\x34\x4b\x5d\x5d\x3d\x32\x43\x3b\x31\x48\x5b\x61\x5b\x32\x4f\x5d\x5d\x3d\x61\x5b\x34\x4a\x5d\x2b\x34\x49\x2b\x61\x5b\x34\x48\x5d\x3b\x28\x31\x44\x5b\x61\x5b\x32\x59\x5d\x5d\x28\x61\x5b\x34\x4c\x5d\x29\x5b\x30\x5d\x7c\x7c\x31\x44\x5b\x61\x5b\x32\x59\x5d\x5d\x28\x61\x5b\x35\x31\x5d\x29\x5b\x30\x5d\x29\x5b\x61\x5b\x34\x50\x5d\x5d\x28\x31\x48\x29\x7d\x29\x28\x29\x3b\x24\x28\x61\x5b\x33\x64\x5d\x29\x5b\x61\x5b\x32\x52\x5d\x5d\x28\x29\x3b\x24\x28\x4c\x29\x5b\x61\x5b\x32\x38\x5d\x5d\x28\x33\x61\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x31\x4c\x29\x5b\x61\x5b\x35\x38\x5d\x5d\x28\x29\x7d\x51\x7b\x45\x28\x31\x69\x3d\x3d\x61\x5b\x34\x4f\x5d\x29\x7b\x24\x28\x61\x5b\x33\x64\x5d\x29\x5b\x61\x5b\x32\x52\x5d\x5d\x28\x29\x3b\x24\x28\x4c\x29\x5b\x61\x5b\x32\x38\x5d\x5d\x28\x32\x50\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x31\x4c\x29\x5b\x61\x5b\x35\x38\x5d\x5d\x28\x29\x7d\x51\x7b\x45\x28\x31\x69\x3d\x3d\x61\x5b\x32\x55\x5d\x29\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x32\x55\x5d\x5d\x28\x29\x7d\x51\x7b\x24\x28\x4c\x29\x5b\x61\x5b\x33\x36\x5d\x5d\x28\x61\x5b\x34\x4e\x5d\x29\x5b\x61\x5b\x35\x38\x5d\x5d\x28\x29\x7d\x7d\x7d\x7d\x7d\x29\x7d\x29\x5c\x27\x2c\x36\x32\x2c\x38\x65\x2c\x5c\x27\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x38\x67\x7c\x38\x68\x7c\x38\x69\x7c\x38\x6a\x7c\x38\x6b\x7c\x38\x6c\x7c\x38\x6d\x7c\x38\x66\x7c\x37\x56\x7c\x37\x4d\x7c\x37\x55\x7c\x37\x46\x7c\x37\x47\x7c\x37\x48\x7c\x37\x49\x7c\x37\x4a\x7c\x37\x4b\x7c\x37\x45\x7c\x37\x4c\x7c\x37\x4e\x7c\x37\x4f\x7c\x37\x50\x7c\x37\x51\x7c\x37\x52\x7c\x37\x53\x7c\x37\x54\x7c\x38\x6e\x7c\x37\x57\x7c\x38\x6f\x7c\x38\x49\x7c\x36\x64\x7c\x36\x61\x7c\x38\x4b\x7c\x38\x4c\x7c\x38\x4d\x7c\x38\x4e\x7c\x38\x4f\x7c\x38\x50\x7c\x38\x51\x7c\x38\x4a\x7c\x38\x52\x7c\x39\x33\x7c\x38\x54\x7c\x38\x55\x7c\x38\x56\x7c\x38\x57\x7c\x38\x58\x7c\x38\x59\x7c\x38\x5a\x7c\x38\x53\x7c\x38\x48\x7c\x38\x79\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x38\x47\x7c\x38\x72\x7c\x38\x73\x7c\x38\x74\x7c\x38\x75\x7c\x36\x62\x7c\x38\x76\x7c\x38\x77\x7c\x38\x71\x7c\x38\x78\x7c\x38\x7a\x7c\x38\x41\x7c\x37\x33\x7c\x38\x42\x7c\x38\x43\x7c\x38\x44\x7c\x38\x45\x7c\x37\x43\x7c\x38\x70\x7c\x37\x44\x7c\x36\x50\x7c\x37\x42\x7c\x36\x79\x7c\x36\x7a\x7c\x36\x41\x7c\x36\x42\x7c\x36\x43\x7c\x36\x44\x7c\x36\x78\x7c\x36\x45\x7c\x36\x47\x7c\x36\x48\x7c\x36\x49\x7c\x36\x4a\x7c\x36\x4b\x7c\x36\x4c\x7c\x36\x4d\x7c\x36\x46\x7c\x36\x4e\x7c\x36\x77\x7c\x36\x6f\x7c\x36\x66\x7c\x36\x67\x7c\x36\x68\x7c\x36\x69\x7c\x36\x6a\x7c\x36\x65\x7c\x36\x75\x7c\x36\x6e\x7c\x36\x70\x7c\x36\x71\x7c\x36\x72\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x36\x73\x7c\x36\x74\x7c\x36\x6d\x7c\x39\x35\x7c\x36\x6c\x7c\x36\x6b\x7c\x36\x4f\x7c\x37\x6a\x7c\x37\x6c\x7c\x37\x6d\x7c\x38\x39\x7c\x37\x6e\x7c\x37\x6f\x7c\x37\x70\x7c\x37\x71\x7c\x37\x72\x7c\x37\x6b\x7c\x37\x73\x7c\x37\x75\x7c\x37\x76\x7c\x38\x36\x7c\x37\x77\x7c\x37\x78\x7c\x37\x79\x7c\x37\x7a\x7c\x37\x41\x7c\x37\x74\x7c\x37\x69\x7c\x36\x5a\x7c\x37\x68\x7c\x36\x52\x7c\x36\x53\x7c\x36\x54\x7c\x36\x55\x7c\x36\x37\x7c\x36\x56\x7c\x36\x57\x7c\x36\x58\x7c\x36\x51\x7c\x36\x59\x7c\x37\x35\x7c\x37\x61\x7c\x37\x62\x7c\x37\x63\x7c\x37\x64\x7c\x37\x65\x7c\x37\x66\x7c\x38\x37\x7c\x37\x67\x7c\x39\x61\x7c\x38\x46\x7c\x39\x63\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x61\x34\x7c\x37\x30\x7c\x61\x50\x7c\x62\x34\x7c\x61\x52\x7c\x61\x53\x7c\x61\x54\x7c\x61\x4d\x7c\x61\x57\x7c\x61\x58\x7c\x61\x59\x7c\x61\x5a\x7c\x62\x30\x7c\x62\x32\x7c\x61\x56\x7c\x61\x4b\x7c\x61\x42\x7c\x61\x4a\x7c\x61\x74\x7c\x61\x75\x7c\x61\x76\x7c\x61\x77\x7c\x61\x78\x7c\x61\x79\x7c\x61\x7a\x7c\x61\x73\x7c\x61\x43\x7c\x61\x44\x7c\x61\x45\x7c\x61\x46\x7c\x61\x47\x7c\x61\x48\x7c\x61\x49\x7c\x37\x36\x7c\x38\x38\x7c\x38\x30\x7c\x36\x38\x7c\x36\x39\x7c\x37\x37\x7c\x62\x68\x7c\x37\x31\x7c\x39\x34\x7c\x39\x32\x7c\x39\x30\x7c\x62\x36\x7c\x37\x34\x7c\x38\x35\x7c\x38\x32\x7c\x39\x31\x7c\x38\x31\x7c\x38\x33\x7c\x37\x39\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x38\x34\x7c\x62\x65\x7c\x39\x36\x7c\x37\x32\x7c\x37\x38\x7c\x62\x62\x7c\x62\x61\x7c\x62\x35\x7c\x62\x38\x7c\x62\x37\x7c\x62\x67\x7c\x62\x66\x7c\x62\x39\x7c\x62\x63\x7c\x62\x64\x7c\x62\x69\x7c\x61\x51\x7c\x61\x72\x7c\x39\x4f\x7c\x61\x70\x7c\x39\x78\x7c\x39\x79\x7c\x39\x7a\x7c\x39\x41\x7c\x39\x42\x7c\x39\x43\x7c\x39\x77\x7c\x39\x44\x7c\x39\x46\x7c\x39\x47\x7c\x39\x48\x7c\x39\x49\x7c\x39\x4a\x7c\x39\x4b\x7c\x39\x4c\x7c\x39\x45\x7c\x39\x75\x7c\x39\x6c\x7c\x39\x74\x7c\x39\x65\x7c\x39\x66\x7c\x39\x67\x7c\x39\x68\x7c\x39\x69\x7c\x39\x6a\x7c\x39\x64\x7c\x39\x6b\x7c\x39\x6d\x7c\x39\x6e\x7c\x39\x6f\x7c\x39\x70\x7c\x39\x71\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x39\x72\x7c\x39\x73\x7c\x61\x71\x7c\x39\x4d\x7c\x39\x76\x7c\x39\x4e\x7c\x61\x37\x7c\x61\x39\x7c\x61\x61\x7c\x61\x62\x7c\x61\x63\x7c\x61\x64\x7c\x61\x65\x7c\x61\x66\x7c\x61\x38\x7c\x61\x67\x7c\x61\x69\x7c\x61\x6a\x7c\x61\x6b\x7c\x39\x39\x7c\x39\x38\x7c\x61\x6c\x7c\x61\x6d\x7c\x61\x6e\x7c\x61\x6f\x7c\x61\x68\x7c\x61\x36\x7c\x39\x58\x7c\x61\x35\x7c\x39\x51\x7c\x39\x52\x7c\x39\x53\x7c\x39\x54\x7c\x39\x55\x7c\x39\x56\x7c\x39\x50\x7c\x39\x57\x7c\x39\x59\x7c\x39\x5a\x7c\x61\x30\x7c\x61\x31\x7c\x61\x32\x7c\x36\x63\x7c\x61\x33\x7c\x61\x4c\x7c\x62\x33\x7c\x61\x41\x7c\x62\x31\x7c\x61\x55\x7c\x61\x4f\x7c\x61\x4e\x7c\x39\x37\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x5c\x27\x2e\x36\x76\x28\x5c\x27\x7c\x5c\x27\x29\x29\x29\x27\x2c\x36\x32\x2c\x37\x30\x31\x2c\x27\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x66\x75\x6e\x63\x74\x69\x6f\x6e\x7c\x72\x65\x74\x75\x72\x6e\x7c\x70\x61\x72\x73\x65\x49\x6e\x74\x7c\x69\x66\x7c\x31\x31\x37\x7c\x66\x6f\x72\x7c\x78\x33\x33\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x36\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x30\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x33\x7c\x31\x32\x36\x7c\x31\x31\x39\x7c\x78\x37\x41\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x62\x7c\x31\x32\x33\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x63\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x62\x7c\x78\x33\x46\x7c\x31\x32\x31\x7c\x32\x35\x30\x7c\x78\x33\x39\x7c\x73\x70\x6c\x69\x74\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x35\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x64\x7c\x78\x33\x37\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x30\x7c\x78\x32\x43\x7c\x78\x33\x35\x7c\x31\x34\x38\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x38\x7c\x64\x6f\x63\x75\x6d\x65\x6e\x74\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x64\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x37\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x30\x7c\x78\x37\x31\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x65\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x37\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x66\x7c\x78\x35\x46\x7c\x31\x37\x30\x7c\x78\x34\x46\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x61\x7c\x31\x30\x39\x7c\x31\x31\x30\x7c\x31\x36\x30\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x31\x7c\x31\x37\x34\x7c\x4d\x61\x74\x68\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x38\x7c\x78\x35\x39\x7c\x31\x33\x30\x7c\x74\x72\x75\x65\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x63\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x33\x7c\x31\x39\x37\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x32\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x35\x7c\x32\x30\x30\x7c\x78\x32\x34\x7c\x78\x35\x36\x7c\x31\x31\x31\x7c\x78\x33\x38\x7c\x31\x36\x32\x7c\x77\x69\x6e\x64\x6f\x77\x7c\x78\x35\x33\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x65\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x34\x7c\x78\x34\x32\x7c\x31\x34\x39\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x39\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x62\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x65\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x36\x7c\x74\x79\x70\x65\x7c\x75\x72\x6c\x7c\x73\x75\x63\x63\x65\x73\x73\x7c\x78\x35\x37\x7c\x78\x33\x34\x7c\x78\x32\x36\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x7c\x78\x34\x35\x7c\x78\x32\x46\x7c\x78\x36\x44\x7c\x78\x37\x30\x7c\x78\x36\x34\x7c\x78\x32\x30\x7c\x78\x36\x33\x7c\x78\x37\x35\x7c\x78\x32\x32\x7c\x78\x36\x45\x7c\x78\x36\x38\x7c\x78\x32\x45\x7c\x78\x36\x32\x7c\x78\x33\x43\x7c\x78\x36\x37\x7c\x78\x33\x45\x7c\x78\x33\x44\x7c\x78\x37\x32\x7c\x78\x32\x44\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x34\x7c\x52\x65\x67\x45\x78\x70\x7c\x53\x74\x72\x69\x6e\x67\x7c\x66\x72\x6f\x6d\x43\x68\x61\x72\x43\x6f\x64\x65\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x74\x6f\x53\x74\x72\x69\x6e\x67\x7c\x77\x68\x69\x6c\x65\x7c\x72\x65\x70\x6c\x61\x63\x65\x7c\x6e\x65\x77\x7c\x33\x37\x39\x7c\x78\x36\x46\x7c\x5f\x30\x78\x35\x64\x65\x39\x7c\x78\x36\x35\x7c\x78\x37\x34\x7c\x78\x37\x33\x7c\x78\x36\x31\x7c\x78\x36\x43\x7c\x78\x36\x39\x7c\x78\x36\x36\x7c\x76\x61\x72\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x61\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x38\x7c\x78\x35\x34\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x34\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x61\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x33\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x35\x7c\x78\x34\x33\x7c\x78\x37\x42\x7c\x78\x33\x32\x7c\x78\x32\x31\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x37\x7c\x78\x33\x42\x7c\x78\x37\x44\x7c\x78\x34\x39\x7c\x31\x39\x36\x7c\x78\x36\x41\x7c\x78\x33\x31\x7c\x78\x37\x36\x7c\x78\x36\x42\x7c\x78\x37\x37\x7c\x78\x37\x39\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x66\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x63\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x36\x7c\x74\x68\x69\x73\x7c\x78\x32\x33\x7c\x78\x33\x41\x7c\x78\x34\x43\x7c\x65\x6c\x73\x65\x7c\x78\x33\x30\x7c\x78\x37\x38\x7c\x78\x34\x31\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x39\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x65\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x31\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x31\x7c\x65\x76\x61\x6c\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x35\x7c\x31\x38\x32\x7c\x32\x30\x31\x7c\x31\x39\x39\x7c\x31\x39\x34\x7c\x78\x34\x38\x7c\x31\x39\x30\x7c\x31\x38\x39\x7c\x6c\x6f\x63\x61\x74\x69\x6f\x6e\x7c\x31\x39\x35\x7c\x31\x38\x31\x7c\x64\x69\x73\x71\x75\x73\x5f\x62\x6c\x6f\x67\x67\x65\x72\x5f\x63\x75\x72\x72\x65\x6e\x74\x5f\x75\x72\x6c\x7c\x31\x38\x33\x7c\x31\x38\x34\x7c\x31\x38\x37\x7c\x31\x38\x38\x7c\x31\x38\x36\x7c\x78\x34\x44\x7c\x31\x39\x31\x7c\x31\x35\x37\x7c\x31\x36\x34\x7c\x31\x36\x38\x7c\x31\x36\x31\x7c\x62\x65\x66\x6f\x72\x65\x53\x65\x6e\x64\x7c\x31\x35\x39\x7c\x64\x61\x74\x61\x54\x79\x70\x65\x7c\x31\x36\x33\x7c\x78\x35\x35\x7c\x31\x39\x32\x7c\x31\x36\x36\x7c\x31\x36\x37\x7c\x31\x36\x35\x7c\x63\x6f\x6d\x6d\x65\x6e\x74\x73\x53\x79\x73\x74\x65\x6d\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x39\x7c\x31\x39\x33\x7c\x64\x69\x73\x71\x75\x73\x53\x68\x6f\x72\x74\x6e\x61\x6d\x65\x7c\x31\x35\x38\x7c\x31\x31\x33\x7c\x31\x37\x39\x7c\x31\x35\x36\x7c\x31\x34\x37\x7c\x31\x34\x36\x7c\x78\x34\x42\x7c\x31\x34\x30\x7c\x31\x35\x30\x7c\x31\x35\x31\x7c\x31\x35\x35\x7c\x31\x32\x32\x7c\x31\x35\x34\x7c\x31\x35\x33\x7c\x31\x33\x39\x7c\x31\x33\x37\x7c\x31\x32\x37\x7c\x6d\x6f\x6e\x74\x68\x46\x6f\x72\x6d\x61\x74\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x61\x7c\x31\x32\x34\x7c\x61\x64\x64\x69\x74\x69\x6f\x6e\x61\x6c\x4d\x61\x72\x67\x69\x6e\x42\x6f\x74\x74\x6f\x6d\x7c\x31\x31\x32\x7c\x31\x31\x35\x7c\x35\x30\x30\x7c\x73\x63\x72\x6f\x6c\x6c\x54\x6f\x70\x7c\x31\x31\x38\x7c\x31\x31\x36\x7c\x62\x72\x65\x61\x6b\x7c\x31\x32\x30\x7c\x31\x31\x34\x7c\x31\x30\x35\x7c\x31\x30\x37\x7c\x31\x30\x36\x7c\x66\x69\x78\x65\x64\x53\x69\x64\x65\x62\x61\x72\x7c\x31\x30\x32\x7c\x31\x30\x31\x7c\x61\x64\x64\x69\x74\x69\x6f\x6e\x61\x6c\x4d\x61\x72\x67\x69\x6e\x54\x6f\x70\x7c\x31\x30\x34\x7c\x31\x30\x33\x7c\x31\x36\x39\x7c\x31\x38\x35\x7c\x31\x38\x30\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x64\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x33\x32\x7c\x31\x34\x34\x7c\x31\x34\x33\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x66\x7c\x31\x34\x32\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x31\x62\x7c\x78\x34\x45\x7c\x78\x34\x41\x7c\x75\x6e\x64\x65\x66\x69\x6e\x65\x64\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x63\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x37\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x34\x7c\x78\x34\x34\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x36\x7c\x31\x33\x32\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x64\x7c\x31\x34\x35\x7c\x31\x33\x36\x7c\x31\x32\x35\x7c\x6e\x6f\x54\x68\x75\x6d\x62\x6e\x61\x69\x6c\x7c\x31\x33\x31\x7c\x69\x6e\x7c\x31\x30\x30\x7c\x78\x35\x30\x7c\x31\x30\x38\x7c\x31\x35\x32\x7c\x31\x33\x35\x7c\x31\x33\x33\x7c\x31\x34\x31\x7c\x78\x34\x36\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x38\x7c\x78\x32\x35\x7c\x31\x33\x34\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x39\x7c\x31\x33\x38\x7c\x5f\x30\x78\x39\x66\x32\x63\x78\x32\x32\x7c\x31\x32\x38\x7c\x31\x39\x38\x7c\x31\x32\x39\x7c\x73\x65\x74\x49\x6e\x74\x65\x72\x76\x61\x6c\x7c\x31\x37\x36\x7c\x31\x37\x35\x7c\x31\x37\x31\x7c\x78\x35\x32\x7c\x78\x33\x36\x7c\x31\x37\x37\x7c\x31\x37\x38\x7c\x70\x6f\x73\x74\x50\x65\x72\x50\x61\x67\x65\x7c\x31\x37\x32\x7c\x31\x37\x33\x7c\x33\x30\x30\x30\x7c\x32\x30\x32\x27\x2e\x73\x70\x6c\x69\x74\x28\x27\x7c\x27\x29\x2c\x30\x2c\x7b\x7d\x29\x29\x0a";eval(_UN8GCo);
//]]>
</script>
<!-- Pagination Scripts -->
<b:if cond='data:view.isMultipleItems'>
<script type='text/javascript'>
//<![CDATA[
var postResults=postPerPage;
var numOfPages=2;
var pageOf=["Page", "of"];
eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--){d[e(c)]=k[c]||e(c)}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('5 K;5 m;5 l;5 w;5 s=1p.9;5 y="/";1d();G 1b(a){5 b=\'\';J=M(W/2);4(J==W-J){W=J*2+1}D=l-J;4(D<1)D=1;j=M(a/n)+1;4(j-1==a/n)j=j-1;E=D+W-1;4(E>j)E=j;b+=\'<C 6="3-1u">\'+17[0]+\' \'+l+\' \'+17[1]+\' \'+j+\'</C>\';5 c=M(l)-1;4(l>1){4(l==2){4(m==\'3\'){b+=\'<a 6="3-7 3-U" 9="\'+y+\'"></a>\'}h{b+=\'<a 6="3-7 3-U" 9="/v/u/\'+w+\'?&i-o=\'+n+\'"></a>\'}}h{4(m==\'3\'){b+=\'<a 6="3-7 3-U" 9="#" z="L(\'+c+\');B x"></a>\'}h{b+=\'<a 6="3-7 3-U" 9="#" z="I(\'+c+\');B x"></a>\'}}}4(D>1){4(m=="3"){b+=\'<a 6="3-7" 9="\'+y+\'">1</a>\'}h{b+=\'<a 6="3-7" 9="/v/u/\'+w+\'?&i-o=\'+n+\'">1</a>\'}}4(D>2){b+=\'<C 6="3-7 3-16">...</C>\'}1a(5 d=D;d<=E;d++){4(l==d){b+=\'<C 6="3-7 3-1v">\'+d+\'</C>\'}h 4(d==1){4(m==\'3\'){b+=\'<a 6="3-7" 9="\'+y+\'">1</a>\'}h{b+=\'<a 6="3-7" 9="/v/u/\'+w+\'?&i-o=\'+n+\'">1</a>\'}}h{4(m==\'3\'){b+=\'<a 6="3-7" 9="#" z="L(\'+d+\');B x">\'+d+\'</a>\'}h{b+=\'<a 6="3-7" 9="#" z="I(\'+d+\');B x">\'+d+\'</a>\'}}}4(E<j-1){b+=\'<C 6="3-7 3-16">...</C>\'}4(E<j){4(m=="3"){b+=\'<a 6="3-7" 9="#" z="L(\'+j+\');B x">\'+j+\'</a>\'}h{b+=\'<a 6="3-7" 9="#" z="I(\'+j+\');B x">\'+j+\'</a>\'}}5 e=M(l)+1;4(l<j){4(m==\'3\'){b+=\'<a 6="3-7 3-15" 9="#" z="L(\'+e+\');B x"></a>\'}h{b+=\'<a 6="3-7 3-15" 9="#" z="I(\'+e+\');B x"></a>\'}}b+=\'\';5 f=A.1s(\'1t\');5 g=A.1r(\'1A-1D\');1a(5 p=0;p<f.O;p++){f[p].1c=b}4(f&&f.O>0){b=\'\'}4(g){g.1c=b}}G 12(a){5 b=a.1f;5 c=M(b.1E$1B.$t,10);1b(c)}G 1d(){5 a=s;4(a.k(\'/v/u/\')!=-1){4(a.k(\'?T-i\')!=-1){w=a.H(a.k(\'/v/u/\')+14,a.k(\'?T-i\'))}h{w=a.H(a.k(\'/v/u/\')+14,a.k(\'?&i\'))}}4(a.k(\'?q=\')==-1&&a.k(\'.1C\')==-1){4(a.k(\'/v/u/\')==-1){m=\'3\';4(s.k(\'#F=\')!=-1){l=s.H(s.k(\'#F=\')+8,s.O)}h{l=1}A.18(\'<r Q=\\\'\'+y+\'P/R/N?i-o=1&X=Y-S-r&V=12\\\'><\\/r>\')}h{m=\'u\';4(a.k(\'&i-o=\')==-1){n=1F}4(s.k(\'#F=\')!=-1){l=s.H(s.k(\'#F=\')+8,s.O)}h{l=1}A.18(\'<r Q="\'+y+\'P/R/N/-/\'+w+\'?X=Y-S-r&V=12&i-o=1" ><\\/r>\')}}}G L(a){Z=(a-1)*n;K=a;5 b=A.1h(\'1q\')[0];5 c=A.1o(\'r\');c.1e=\'1m/1n\';c.1i(\'Q\',y+\'P/R/N?1j-1k=\'+Z+\'&i-o=1&X=Y-S-r&V=13\');b.1l(c)}G I(a){Z=(a-1)*n;K=a;5 b=A.1h(\'1q\')[0];5 c=A.1o(\'r\');c.1e=\'1m/1n\';c.1i(\'Q\',y+\'P/R/N/-/\'+w+\'?1j-1k=\'+Z+\'&i-o=1&X=Y-S-r&V=13\');b.1l(c)}G 13(a){11=a.1f.1x[0];5 b=11.1g.$t.H(0,19)+11.1g.$t.H(1z,1w);5 c=1y(b);4(m==\'3\'){5 d=\'/v?T-i=\'+c+\'&i-o=\'+n+\'#F=\'+K}h{5 d=\'/v/u/\'+w+\'?T-i=\'+c+\'&i-o=\'+n+\'#F=\'+K}1p.9=d}',62,104,'|||page|if|var|class|num||href||||||||else|max|lastPageNo|indexOf|currentPageNo|currentPage|postResults|results|||script|locationUrl||label|search|postLabel|false|home_page|onclick|document|return|span|pageStart|pageEnd|PageNo|function|substring|getLabelPage|pageNumber|noPage|getPage|parseInt|summary|length|feeds|src|posts|in|updated|prev|callback|numOfPages|alt|json|jsonstart||post|dataFeed|findPostDate||next|dots|pageOf|write||for|startPagination|innerHTML|pageCurrentBlogger|type|feed|published|getElementsByTagName|setAttribute|start|index|appendChild|text|javascript|createElement|location|head|getElementById|getElementsByName|pageArea|of|active|29|entry|encodeURIComponent|23|blog|totalResults|html|pager|openSearch|20'.split('|'),0,{}))
//]]>
</script>
</b:if>

<!-- Facebook SDK -->
<script type='text/javascript'>
//<![CDATA[
(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = 'https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v3.0';
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));
//]]>
</script> 

<b:if cond='data:view.isPage'>
<script type='text/javascript'>
//<![CDATA[
//timer.js
!function(i){var e={init:function(e){var t={timer:null,timerSeconds:10,callback:function(){},timerCurrent:0,showPercentage:!1,fill:!1,color:"#CCC"};return t=i.extend(t,e),this.each(function(){var e=i(this);e.data("pietimer")||(e.addClass("pietimer"),e.css({fontSize:e.width()}),e.data("pietimer",t),t.showPercentage&&e.find(".percent").show(),t.fill&&e.addClass("fill"),e.pietimer("start"))})},stopWatch:function(){var e=i(this).data("pietimer");if(e){var t=(e.timerFinish-(new Date).getTime())/1e3;if(t<=0)clearInterval(e.timer),i(this).pietimer("drawTimer",100),e.callback();else{var r=100-t/e.timerSeconds*100;i(this).pietimer("drawTimer",r)}}},drawTimer:function(e){$this=i(this);var t=$this.data("pietimer");if(t){$this.html('<div class="percent"></div><div class="slice'+(e>50?' gt50"':'"')+'><div class="pie"></div>'+(e>50?'<div class="pie fill"></div>':"")+"</div>");var r=3.6*e;$this.find(".slice .pie").css({"-moz-transform":"rotate("+r+"deg)","-webkit-transform":"rotate("+r+"deg)","-o-transform":"rotate("+r+"deg)",transform:"rotate("+r+"deg)"}),$this.find(".percent").html(Math.round(e)+"%"),t.showPercentage&&$this.find(".percent").show(),$this.hasClass("fill")?$this.find(".slice .pie").css({backgroundColor:t.color}):$this.find(".slice .pie").css({borderColor:t.color})}},start:function(){var e=i(this).data("pietimer");e&&(e.timerFinish=(new Date).getTime()+1e3*e.timerSeconds,i(this).pietimer("drawTimer",0),e.timer=setInterval("$this.pietimer('stopWatch')",50))},reset:function(){var e=i(this).data("pietimer");e&&(clearInterval(e.timer),i(this).pietimer("drawTimer",0))}};i.fn.pietimer=function(t){return e[t]?e[t].apply(this,Array.prototype.slice.call(arguments,1)):"object"!=typeof t&&t?void i.error("Method "+t+" does not exist on jQuery.pietimer"):e.init.apply(this,arguments)}}(jQuery);

// SafeLink.js
!function(t,e){"object"==typeof exports&&"object"==typeof module?module.exports=e():"function"==typeof define&&define.amd?define([],e):"object"==typeof exports?exports.ClipboardJS=e():t.ClipboardJS=e()}(this,function(){return function(n){var o={};function r(t){if(o[t])return o[t].exports;var e=o[t]={i:t,l:!1,exports:{}};return n[t].call(e.exports,e,e.exports,r),e.l=!0,e.exports}return r.m=n,r.c=o,r.d=function(t,e,n){r.o(t,e)||Object.defineProperty(t,e,{enumerable:!0,get:n})},r.r=function(t){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(t,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(t,"__esModule",{value:!0})},r.t=function(e,t){if(1&t&&(e=r(e)),8&t)return e;if(4&t&&"object"==typeof e&&e&&e.__esModule)return e;var n=Object.create(null);if(r.r(n),Object.defineProperty(n,"default",{enumerable:!0,value:e}),2&t&&"string"!=typeof e)for(var o in e)r.d(n,o,function(t){return e[t]}.bind(null,o));return n},r.n=function(t){var e=t&&t.__esModule?function(){return t.default}:function(){return t};return r.d(e,"a",e),e},r.o=function(t,e){return Object.prototype.hasOwnProperty.call(t,e)},r.p="",r(r.s=0)}([function(t,e,n){"use strict";var r="function"==typeof Symbol&&"symbol"==typeof Symbol.iterator?function(t){return typeof t}:function(t){return t&&"function"==typeof Symbol&&t.constructor===Symbol&&t!==Symbol.prototype?"symbol":typeof t},i=function(){function o(t,e){for(var n=0;n<e.length;n++){var o=e[n];o.enumerable=o.enumerable||!1,o.configurable=!0,"value"in o&&(o.writable=!0),Object.defineProperty(t,o.key,o)}}return function(t,e,n){return e&&o(t.prototype,e),n&&o(t,n),t}}(),a=o(n(1)),c=o(n(3)),u=o(n(4));function o(t){return t&&t.__esModule?t:{default:t}}var l=function(t){function o(t,e){!function(t,e){if(!(t instanceof e))throw new TypeError("Cannot call a class as a function")}(this,o);var n=function(t,e){if(!t)throw new ReferenceError("this hasn't been initialised - super() hasn't been called");return!e||"object"!=typeof e&&"function"!=typeof e?t:e}(this,(o.__proto__||Object.getPrototypeOf(o)).call(this));return n.resolveOptions(e),n.listenClick(t),n}return function(t,e){if("function"!=typeof e&&null!==e)throw new TypeError("Super expression must either be null or a function, not "+typeof e);t.prototype=Object.create(e&&e.prototype,{constructor:{value:t,enumerable:!1,writable:!0,configurable:!0}}),e&&(Object.setPrototypeOf?Object.setPrototypeOf(t,e):t.__proto__=e)}(o,c.default),i(o,[{key:"resolveOptions",value:function(){var t=0<arguments.length&&void 0!==arguments[0]?arguments[0]:{};this.action="function"==typeof t.action?t.action:this.defaultAction,this.target="function"==typeof t.target?t.target:this.defaultTarget,this.text="function"==typeof t.text?t.text:this.defaultText,this.container="object"===r(t.container)?t.container:document.body}},{key:"listenClick",value:function(t){var e=this;this.listener=(0,u.default)(t,"click",function(t){return e.onClick(t)})}},{key:"onClick",value:function(t){var e=t.delegateTarget||t.currentTarget;this.clipboardAction&&(this.clipboardAction=null),this.clipboardAction=new a.default({action:this.action(e),target:this.target(e),text:this.text(e),container:this.container,trigger:e,emitter:this})}},{key:"defaultAction",value:function(t){return s("action",t)}},{key:"defaultTarget",value:function(t){var e=s("target",t);if(e)return document.querySelector(e)}},{key:"defaultText",value:function(t){return s("text",t)}},{key:"destroy",value:function(){this.listener.destroy(),this.clipboardAction&&(this.clipboardAction.destroy(),this.clipboardAction=null)}}],[{key:"isSupported",value:function(){var t=0<arguments.length&&void 0!==arguments[0]?arguments[0]:["copy","cut"],e="string"==typeof t?[t]:t,n=!!document.queryCommandSupported;return e.forEach(function(t){n=n&&!!document.queryCommandSupported(t)}),n}}]),o}();function s(t,e){var n="data-clipboard-"+t;if(e.hasAttribute(n))return e.getAttribute(n)}t.exports=l},function(t,e,n){"use strict";var o,r="function"==typeof Symbol&&"symbol"==typeof Symbol.iterator?function(t){return typeof t}:function(t){return t&&"function"==typeof Symbol&&t.constructor===Symbol&&t!==Symbol.prototype?"symbol":typeof t},i=function(){function o(t,e){for(var n=0;n<e.length;n++){var o=e[n];o.enumerable=o.enumerable||!1,o.configurable=!0,"value"in o&&(o.writable=!0),Object.defineProperty(t,o.key,o)}}return function(t,e,n){return e&&o(t.prototype,e),n&&o(t,n),t}}(),a=n(2),c=(o=a)&&o.__esModule?o:{default:o};var u=function(){function e(t){!function(t,e){if(!(t instanceof e))throw new TypeError("Cannot call a class as a function")}(this,e),this.resolveOptions(t),this.initSelection()}return i(e,[{key:"resolveOptions",value:function(){var t=0<arguments.length&&void 0!==arguments[0]?arguments[0]:{};this.action=t.action,this.container=t.container,this.emitter=t.emitter,this.target=t.target,this.text=t.text,this.trigger=t.trigger,this.selectedText=""}},{key:"initSelection",value:function(){this.text?this.selectFake():this.target&&this.selectTarget()}},{key:"selectFake",value:function(){var t=this,e="rtl"==document.documentElement.getAttribute("dir");this.removeFake(),this.fakeHandlerCallback=function(){return t.removeFake()},this.fakeHandler=this.container.addEventListener("click",this.fakeHandlerCallback)||!0,this.fakeElem=document.createElement("textarea"),this.fakeElem.style.fontSize="12pt",this.fakeElem.style.border="0",this.fakeElem.style.padding="0",this.fakeElem.style.margin="0",this.fakeElem.style.position="absolute",this.fakeElem.style[e?"right":"left"]="-9999px";var n=window.pageYOffset||document.documentElement.scrollTop;this.fakeElem.style.top=n+"px",this.fakeElem.setAttribute("readonly",""),this.fakeElem.value=this.text,this.container.appendChild(this.fakeElem),this.selectedText=(0,c.default)(this.fakeElem),this.copyText()}},{key:"removeFake",value:function(){this.fakeHandler&&(this.container.removeEventListener("click",this.fakeHandlerCallback),this.fakeHandler=null,this.fakeHandlerCallback=null),this.fakeElem&&(this.container.removeChild(this.fakeElem),this.fakeElem=null)}},{key:"selectTarget",value:function(){this.selectedText=(0,c.default)(this.target),this.copyText()}},{key:"copyText",value:function(){var e=void 0;try{e=document.execCommand(this.action)}catch(t){e=!1}this.handleResult(e)}},{key:"handleResult",value:function(t){this.emitter.emit(t?"success":"error",{action:this.action,text:this.selectedText,trigger:this.trigger,clearSelection:this.clearSelection.bind(this)})}},{key:"clearSelection",value:function(){this.trigger&&this.trigger.focus(),window.getSelection().removeAllRanges()}},{key:"destroy",value:function(){this.removeFake()}},{key:"action",set:function(){var t=0<arguments.length&&void 0!==arguments[0]?arguments[0]:"copy";if(this._action=t,"copy"!==this._action&&"cut"!==this._action)throw new Error('Invalid "action" value, use either "copy" or "cut"')},get:function(){return this._action}},{key:"target",set:function(t){if(void 0!==t){if(!t||"object"!==(void 0===t?"undefined":r(t))||1!==t.nodeType)throw new Error('Invalid "target" value, use a valid Element');if("copy"===this.action&&t.hasAttribute("disabled"))throw new Error('Invalid "target" attribute. Please use "readonly" instead of "disabled" attribute');if("cut"===this.action&&(t.hasAttribute("readonly")||t.hasAttribute("disabled")))throw new Error('Invalid "target" attribute. You can\'t cut text from elements with "readonly" or "disabled" attributes');this._target=t}},get:function(){return this._target}}]),e}();t.exports=u},function(t,e){t.exports=function(t){var e;if("SELECT"===t.nodeName)t.focus(),e=t.value;else if("INPUT"===t.nodeName||"TEXTAREA"===t.nodeName){var n=t.hasAttribute("readonly");n||t.setAttribute("readonly",""),t.select(),t.setSelectionRange(0,t.value.length),n||t.removeAttribute("readonly"),e=t.value}else{t.hasAttribute("contenteditable")&&t.focus();var o=window.getSelection(),r=document.createRange();r.selectNodeContents(t),o.removeAllRanges(),o.addRange(r),e=o.toString()}return e}},function(t,e){function n(){}n.prototype={on:function(t,e,n){var o=this.e||(this.e={});return(o[t]||(o[t]=[])).push({fn:e,ctx:n}),this},once:function(t,e,n){var o=this;function r(){o.off(t,r),e.apply(n,arguments)}return r._=e,this.on(t,r,n)},emit:function(t){for(var e=[].slice.call(arguments,1),n=((this.e||(this.e={}))[t]||[]).slice(),o=0,r=n.length;o<r;o++)n[o].fn.apply(n[o].ctx,e);return this},off:function(t,e){var n=this.e||(this.e={}),o=n[t],r=[];if(o&&e)for(var i=0,a=o.length;i<a;i++)o[i].fn!==e&&o[i].fn._!==e&&r.push(o[i]);return r.length?n[t]=r:delete n[t],this}},t.exports=n},function(t,e,n){var d=n(5),h=n(6);t.exports=function(t,e,n){if(!t&&!e&&!n)throw new Error("Missing required arguments");if(!d.string(e))throw new TypeError("Second argument must be a String");if(!d.fn(n))throw new TypeError("Third argument must be a Function");if(d.node(t))return s=e,f=n,(l=t).addEventListener(s,f),{destroy:function(){l.removeEventListener(s,f)}};if(d.nodeList(t))return a=t,c=e,u=n,Array.prototype.forEach.call(a,function(t){t.addEventListener(c,u)}),{destroy:function(){Array.prototype.forEach.call(a,function(t){t.removeEventListener(c,u)})}};if(d.string(t))return o=t,r=e,i=n,h(document.body,o,r,i);throw new TypeError("First argument must be a String, HTMLElement, HTMLCollection, or NodeList");var o,r,i,a,c,u,l,s,f}},function(t,n){n.node=function(t){return void 0!==t&&t instanceof HTMLElement&&1===t.nodeType},n.nodeList=function(t){var e=Object.prototype.toString.call(t);return void 0!==t&&("[object NodeList]"===e||"[object HTMLCollection]"===e)&&"length"in t&&(0===t.length||n.node(t[0]))},n.string=function(t){return"string"==typeof t||t instanceof String},n.fn=function(t){return"[object Function]"===Object.prototype.toString.call(t)}},function(t,e,n){var a=n(7);function i(t,e,n,o,r){var i=function(e,n,t,o){return function(t){t.delegateTarget=a(t.target,n),t.delegateTarget&&o.call(e,t)}}.apply(this,arguments);return t.addEventListener(n,i,r),{destroy:function(){t.removeEventListener(n,i,r)}}}t.exports=function(t,e,n,o,r){return"function"==typeof t.addEventListener?i.apply(null,arguments):"function"==typeof n?i.bind(null,document).apply(null,arguments):("string"==typeof t&&(t=document.querySelectorAll(t)),Array.prototype.map.call(t,function(t){return i(t,e,n,o,r)}))}},function(t,e){if("undefined"!=typeof Element&&!Element.prototype.matches){var n=Element.prototype;n.matches=n.matchesSelector||n.mozMatchesSelector||n.msMatchesSelector||n.oMatchesSelector||n.webkitMatchesSelector}t.exports=function(t,e){for(;t&&9!==t.nodeType;){if("function"==typeof t.matches&&t.matches(e))return t;t=t.parentNode}}}])});

// Expires Header
jQuery.cookie=function(e,n,o){if(arguments.length>1&&"[object Object]"!==String(n)){if(o=jQuery.extend({},o),(null===n||void 0===n)&&(o.expires=-1),"number"==typeof o.expires){var t=o.expires,r=o.expires=new Date;r.setDate(r.getDate()+t)}
return n=String(n),document.cookie=[encodeURIComponent(e),"=",o.raw?n:encodeURIComponent(n),o.expires?"; expires="+o.expires.toUTCString():"",o.path?"; path="+o.path:"",o.domain?"; domain="+o.domain:"",o.secure?"; secure":""].join("")}
o=n||{};var i,c=o.raw?function(e){return e}:decodeURIComponent;return(i=new RegExp("(?:^|; )"+encodeURIComponent(e)+"=([^;]*)").exec(document.cookie))?c(i[1]):null};

eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('$(G).J(2(){$("#1g").k("F",2(){4 e=$("#P").u(),r=$("#1h"),a=$("#1i"),n=$("#1j");v(""==e)H $("#P").1f(),!1;$("#x").9("<6 h=\'5 5-1e-o\'></6> 1a 1b"),a.f("8"),r.y("8"),$.1c({1d:"/1k/1l/1s?1t=1u-1r-1q",19:"1n",1o:"1p",L:2(t){4 o="",l=t.O.1v,s=B 17;v(W 0!==l){Q(4 i=0;i<l.z;i++){Q(4 d=0;d<l[i].q.z;d++)v("X"==l[i].q[d].Z){o=l[i].q[d].C;Y}s[i]=o;4 c=18.16()*s.z;c=11(c)}S=m.15+"//"+E.m.14+"/p/q-12.9"+"#?o="+M.13(j(e),j("I")),a.y("8"),r.f("8"),n.u(S)}1m n.u("1E 22!")},1w:2(){n.u("20 1X O!")}})}),B 1Z(".x").k("L",2(e){$("#x").9("<6 h=\'5 5-V\'></6> N 1Y K 1W")})});$(G).J(2(){$.D=2(o){4 n=B 1U("[?&]"+o+"=([^&#]*)").1V(E.m.C);H A==n?A:21(n[1])||0};4 b=$("#b"),7=$("#7"),g=$("#g");2 U(){4 o=3;7.f("8");4 n=1S(2(){4 e=o-=1;7.9(\'<6 h="5 5-1D 5-1T"></6> 1F 1G...\'),e<0&&(1C(n),7.T("R",!1),7.9(\'<6 h="5 5-V"></6> 1x K N\'))},1y)}A!=$.D("o")&&g.1A({1H:10,1I:"#1P",1Q:!1,1R:!0,1O:2(){b.T("R",!1),b.f("8"),g.y("8")}});4 w=!1;b.F(2(){0==w&&(U(),w=!0),$("9, 23").1M({1L:1K(7.1J().1N-10)},1z)}),7.k("F",2(){4 o=M.1B(j($.D("o")),j("I"));E.m.C=o}).k(!1,2(){})});',62,128,'||function||var|fa|span|gotolink|hidden|html||getlink||||removeClass|timer|class||convertstr|on||location||||link||||val|if|request|copytoclipboard|addClass|length|null|new|href|urlParam|window|click|document|return|root|ready|to|success|aesCrypto|Link|feed|generateurl|for|disabled|resultgenerate|prop|gotolinkcountdown|check|void|alternate|break|rel||parseInt|target|encrypt|hostname|protocol|random|Array|Math|type|Copy|URL|ajax|url|floppy|focus|btngenerate|generatelink|generateloading|resulturl|feeds|posts|else|get|dataType|jsonp|script|in|summary|alt|json|entry|error|Go|1e3|500|pietimer|decrypt|clearInterval|cog|No|Please|Wait|timerSeconds|color|offset|eval|scrollTop|animate|top|callback|03a9f4|fill|showPercentage|setInterval|spin|RegExp|exec|Clipboard|loading|Copied|ClipboardJS|Error|decodeURI|result|body'.split('|')))


function convertstr(str) {return str.replace(/^\s+/, '').replace(/\s+$/, ''); } 
var CryptoJS=CryptoJS||function(t,e){var r={},n=r.lib={},i=n.Base=function(){function t(){}return{extend:function(e){t.prototype=this;var r=new t;return e&&r.mixIn(e),r.hasOwnProperty("init")||(r.init=function(){r.$super.init.apply(this,arguments)}),r.init.prototype=r,r.$super=this,r},create:function(){var t=this.extend();return t.init.apply(t,arguments),t},init:function(){},mixIn:function(t){for(var e in t)t.hasOwnProperty(e)&&(this[e]=t[e]);t.hasOwnProperty("toString")&&(this.toString=t.toString)},clone:function(){return this.init.prototype.extend(this)}}}(),o=n.WordArray=i.extend({init:function(t,r){t=this.words=t||[],this.sigBytes=r!=e?r:4*t.length},toString:function(t){return(t||a).stringify(this)},concat:function(t){var e=this.words,r=t.words,n=this.sigBytes,i=t.sigBytes;if(this.clamp(),n%4)for(var o=0;i>o;o++){var s=r[o>>>2]>>>24-o%4*8&255;e[n+o>>>2]|=s<<24-(n+o)%4*8}else if(r.length>65535)for(var o=0;i>o;o+=4)e[n+o>>>2]=r[o>>>2];else e.push.apply(e,r);return this.sigBytes+=i,this},clamp:function(){var e=this.words,r=this.sigBytes;e[r>>>2]&=4294967295<<32-r%4*8,e.length=t.ceil(r/4)},clone:function(){var t=i.clone.call(this);return t.words=this.words.slice(0),t},random:function(e){for(var r=[],n=0;e>n;n+=4)r.push(4294967296*t.random()|0);return new o.init(r,e)}}),s=r.enc={},a=s.Hex={stringify:function(t){for(var e=t.words,r=t.sigBytes,n=[],i=0;r>i;i++){var o=e[i>>>2]>>>24-i%4*8&255;n.push((o>>>4).toString(16)),n.push((15&o).toString(16))}return n.join("")},parse:function(t){for(var e=t.length,r=[],n=0;e>n;n+=2)r[n>>>3]|=parseInt(t.substr(n,2),16)<<24-n%8*4;return new o.init(r,e/2)}},c=s.Latin1={stringify:function(t){for(var e=t.words,r=t.sigBytes,n=[],i=0;r>i;i++){var o=e[i>>>2]>>>24-i%4*8&255;n.push(String.fromCharCode(o))}return n.join("")},parse:function(t){for(var e=t.length,r=[],n=0;e>n;n++)r[n>>>2]|=(255&t.charCodeAt(n))<<24-n%4*8;return new o.init(r,e)}},f=s.Utf8={stringify:function(t){try{return decodeURIComponent(escape(c.stringify(t)))}catch(e){throw new Error("Malformed UTF-8 data")}},parse:function(t){return c.parse(unescape(encodeURIComponent(t)))}},u=n.BufferedBlockAlgorithm=i.extend({reset:function(){this._data=new o.init,this._nDataBytes=0},_append:function(t){"string"==typeof t&&(t=f.parse(t)),this._data.concat(t),this._nDataBytes+=t.sigBytes},_process:function(e){var r=this._data,n=r.words,i=r.sigBytes,s=this.blockSize,a=4*s,c=i/a;c=e?t.ceil(c):t.max((0|c)-this._minBufferSize,0);var f=c*s,u=t.min(4*f,i);if(f){for(var h=0;f>h;h+=s)this._doProcessBlock(n,h);var p=n.splice(0,f);r.sigBytes-=u}return new o.init(p,u)},clone:function(){var t=i.clone.call(this);return t._data=this._data.clone(),t},_minBufferSize:0}),h=(n.Hasher=u.extend({cfg:i.extend(),init:function(t){this.cfg=this.cfg.extend(t),this.reset()},reset:function(){u.reset.call(this),this._doReset()},update:function(t){return this._append(t),this._process(),this},finalize:function(t){t&&this._append(t);var e=this._doFinalize();return e},blockSize:16,_createHelper:function(t){return function(e,r){return new t.init(r).finalize(e)}},_createHmacHelper:function(t){return function(e,r){return new h.HMAC.init(t,r).finalize(e)}}}),r.algo={});return r}(Math);!function(){{var t=CryptoJS,e=t.lib,r=e.WordArray,n=t.enc;n.Base64={stringify:function(t){var e=t.words,r=t.sigBytes,n=this._map;t.clamp();for(var i=[],o=0;r>o;o+=3)for(var s=e[o>>>2]>>>24-o%4*8&255,a=e[o+1>>>2]>>>24-(o+1)%4*8&255,c=e[o+2>>>2]>>>24-(o+2)%4*8&255,f=s<<16|a<<8|c,u=0;4>u&&r>o+.75*u;u++)i.push(n.charAt(f>>>6*(3-u)&63));var h=n.charAt(64);if(h)for(;i.length%4;)i.push(h);return i.join("")},parse:function(t){var e=t.length,n=this._map,i=n.charAt(64);if(i){var o=t.indexOf(i);-1!=o&&(e=o)}for(var s=[],a=0,c=0;e>c;c++)if(c%4){var f=n.indexOf(t.charAt(c-1))<<c%4*2,u=n.indexOf(t.charAt(c))>>>6-c%4*2;s[a>>>2]|=(f|u)<<24-a%4*8,a++}return r.create(s,a)},_map:"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/="}}}(),function(t){function e(t,e,r,n,i,o,s){var a=t+(e&r|~e&n)+i+s;return(a<<o|a>>>32-o)+e}function r(t,e,r,n,i,o,s){var a=t+(e&n|r&~n)+i+s;return(a<<o|a>>>32-o)+e}function n(t,e,r,n,i,o,s){var a=t+(e^r^n)+i+s;return(a<<o|a>>>32-o)+e}function i(t,e,r,n,i,o,s){var a=t+(r^(e|~n))+i+s;return(a<<o|a>>>32-o)+e}var o=CryptoJS,s=o.lib,a=s.WordArray,c=s.Hasher,f=o.algo,u=[];!function(){for(var e=0;64>e;e++)u[e]=4294967296*t.abs(t.sin(e+1))|0}();var h=f.MD5=c.extend({_doReset:function(){this._hash=new a.init([1732584193,4023233417,2562383102,271733878])},_doProcessBlock:function(t,o){for(var s=0;16>s;s++){var a=o+s,c=t[a];t[a]=16711935&(c<<8|c>>>24)|4278255360&(c<<24|c>>>8)}var f=this._hash.words,h=t[o+0],p=t[o+1],l=t[o+2],d=t[o+3],v=t[o+4],y=t[o+5],g=t[o+6],_=t[o+7],m=t[o+8],S=t[o+9],B=t[o+10],x=t[o+11],k=t[o+12],C=t[o+13],z=t[o+14],w=t[o+15],E=f[0],D=f[1],M=f[2],b=f[3];E=e(E,D,M,b,h,7,u[0]),b=e(b,E,D,M,p,12,u[1]),M=e(M,b,E,D,l,17,u[2]),D=e(D,M,b,E,d,22,u[3]),E=e(E,D,M,b,v,7,u[4]),b=e(b,E,D,M,y,12,u[5]),M=e(M,b,E,D,g,17,u[6]),D=e(D,M,b,E,_,22,u[7]),E=e(E,D,M,b,m,7,u[8]),b=e(b,E,D,M,S,12,u[9]),M=e(M,b,E,D,B,17,u[10]),D=e(D,M,b,E,x,22,u[11]),E=e(E,D,M,b,k,7,u[12]),b=e(b,E,D,M,C,12,u[13]),M=e(M,b,E,D,z,17,u[14]),D=e(D,M,b,E,w,22,u[15]),E=r(E,D,M,b,p,5,u[16]),b=r(b,E,D,M,g,9,u[17]),M=r(M,b,E,D,x,14,u[18]),D=r(D,M,b,E,h,20,u[19]),E=r(E,D,M,b,y,5,u[20]),b=r(b,E,D,M,B,9,u[21]),M=r(M,b,E,D,w,14,u[22]),D=r(D,M,b,E,v,20,u[23]),E=r(E,D,M,b,S,5,u[24]),b=r(b,E,D,M,z,9,u[25]),M=r(M,b,E,D,d,14,u[26]),D=r(D,M,b,E,m,20,u[27]),E=r(E,D,M,b,C,5,u[28]),b=r(b,E,D,M,l,9,u[29]),M=r(M,b,E,D,_,14,u[30]),D=r(D,M,b,E,k,20,u[31]),E=n(E,D,M,b,y,4,u[32]),b=n(b,E,D,M,m,11,u[33]),M=n(M,b,E,D,x,16,u[34]),D=n(D,M,b,E,z,23,u[35]),E=n(E,D,M,b,p,4,u[36]),b=n(b,E,D,M,v,11,u[37]),M=n(M,b,E,D,_,16,u[38]),D=n(D,M,b,E,B,23,u[39]),E=n(E,D,M,b,C,4,u[40]),b=n(b,E,D,M,h,11,u[41]),M=n(M,b,E,D,d,16,u[42]),D=n(D,M,b,E,g,23,u[43]),E=n(E,D,M,b,S,4,u[44]),b=n(b,E,D,M,k,11,u[45]),M=n(M,b,E,D,w,16,u[46]),D=n(D,M,b,E,l,23,u[47]),E=i(E,D,M,b,h,6,u[48]),b=i(b,E,D,M,_,10,u[49]),M=i(M,b,E,D,z,15,u[50]),D=i(D,M,b,E,y,21,u[51]),E=i(E,D,M,b,k,6,u[52]),b=i(b,E,D,M,d,10,u[53]),M=i(M,b,E,D,B,15,u[54]),D=i(D,M,b,E,p,21,u[55]),E=i(E,D,M,b,m,6,u[56]),b=i(b,E,D,M,w,10,u[57]),M=i(M,b,E,D,g,15,u[58]),D=i(D,M,b,E,C,21,u[59]),E=i(E,D,M,b,v,6,u[60]),b=i(b,E,D,M,x,10,u[61]),M=i(M,b,E,D,l,15,u[62]),D=i(D,M,b,E,S,21,u[63]),f[0]=f[0]+E|0,f[1]=f[1]+D|0,f[2]=f[2]+M|0,f[3]=f[3]+b|0},_doFinalize:function(){var e=this._data,r=e.words,n=8*this._nDataBytes,i=8*e.sigBytes;r[i>>>5]|=128<<24-i%32;var o=t.floor(n/4294967296),s=n;r[(i+64>>>9<<4)+15]=16711935&(o<<8|o>>>24)|4278255360&(o<<24|o>>>8),r[(i+64>>>9<<4)+14]=16711935&(s<<8|s>>>24)|4278255360&(s<<24|s>>>8),e.sigBytes=4*(r.length+1),this._process();for(var a=this._hash,c=a.words,f=0;4>f;f++){var u=c[f];c[f]=16711935&(u<<8|u>>>24)|4278255360&(u<<24|u>>>8)}return a},clone:function(){var t=c.clone.call(this);return t._hash=this._hash.clone(),t}});o.MD5=c._createHelper(h),o.HmacMD5=c._createHmacHelper(h)}(Math),function(){var t=CryptoJS,e=t.lib,r=e.Base,n=e.WordArray,i=t.algo,o=i.MD5,s=i.EvpKDF=r.extend({cfg:r.extend({keySize:4,hasher:o,iterations:1}),init:function(t){this.cfg=this.cfg.extend(t)},compute:function(t,e){for(var r=this.cfg,i=r.hasher.create(),o=n.create(),s=o.words,a=r.keySize,c=r.iterations;s.length<a;){f&&i.update(f);var f=i.update(t).finalize(e);i.reset();for(var u=1;c>u;u++)f=i.finalize(f),i.reset();o.concat(f)}return o.sigBytes=4*a,o}});t.EvpKDF=function(t,e,r){return s.create(r).compute(t,e)}}(),CryptoJS.lib.Cipher||function(t){var e=CryptoJS,r=e.lib,n=r.Base,i=r.WordArray,o=r.BufferedBlockAlgorithm,s=e.enc,a=(s.Utf8,s.Base64),c=e.algo,f=c.EvpKDF,u=r.Cipher=o.extend({cfg:n.extend(),createEncryptor:function(t,e){return this.create(this._ENC_XFORM_MODE,t,e)},createDecryptor:function(t,e){return this.create(this._DEC_XFORM_MODE,t,e)},init:function(t,e,r){this.cfg=this.cfg.extend(r),this._xformMode=t,this._key=e,this.reset()},reset:function(){o.reset.call(this),this._doReset()},process:function(t){return this._append(t),this._process()},finalize:function(t){t&&this._append(t);var e=this._doFinalize();return e},keySize:4,ivSize:4,_ENC_XFORM_MODE:1,_DEC_XFORM_MODE:2,_createHelper:function(){function t(t){return"string"==typeof t?x:m}return function(e){return{encrypt:function(r,n,i){return t(n).encrypt(e,r,n,i)},decrypt:function(r,n,i){return t(n).decrypt(e,r,n,i)}}}}()}),h=(r.StreamCipher=u.extend({_doFinalize:function(){var t=this._process(!0);return t},blockSize:1}),e.mode={}),p=r.BlockCipherMode=n.extend({createEncryptor:function(t,e){return this.Encryptor.create(t,e)},createDecryptor:function(t,e){return this.Decryptor.create(t,e)},init:function(t,e){this._cipher=t,this._iv=e}}),l=h.CBC=function(){function e(e,r,n){var i=this._iv;if(i){var o=i;this._iv=t}else var o=this._prevBlock;for(var s=0;n>s;s++)e[r+s]^=o[s]}var r=p.extend();return r.Encryptor=r.extend({processBlock:function(t,r){var n=this._cipher,i=n.blockSize;e.call(this,t,r,i),n.encryptBlock(t,r),this._prevBlock=t.slice(r,r+i)}}),r.Decryptor=r.extend({processBlock:function(t,r){var n=this._cipher,i=n.blockSize,o=t.slice(r,r+i);n.decryptBlock(t,r),e.call(this,t,r,i),this._prevBlock=o}}),r}(),d=e.pad={},v=d.Pkcs7={pad:function(t,e){for(var r=4*e,n=r-t.sigBytes%r,o=n<<24|n<<16|n<<8|n,s=[],a=0;n>a;a+=4)s.push(o);var c=i.create(s,n);t.concat(c)},unpad:function(t){var e=255&t.words[t.sigBytes-1>>>2];t.sigBytes-=e}},y=(r.BlockCipher=u.extend({cfg:u.cfg.extend({mode:l,padding:v}),reset:function(){u.reset.call(this);var t=this.cfg,e=t.iv,r=t.mode;if(this._xformMode==this._ENC_XFORM_MODE)var n=r.createEncryptor;else{var n=r.createDecryptor;this._minBufferSize=1}this._mode=n.call(r,this,e&&e.words)},_doProcessBlock:function(t,e){this._mode.processBlock(t,e)},_doFinalize:function(){var t=this.cfg.padding;if(this._xformMode==this._ENC_XFORM_MODE){t.pad(this._data,this.blockSize);var e=this._process(!0)}else{var e=this._process(!0);t.unpad(e)}return e},blockSize:4}),r.CipherParams=n.extend({init:function(t){this.mixIn(t)},toString:function(t){return(t||this.formatter).stringify(this)}})),g=e.format={},_=g.OpenSSL={stringify:function(t){var e=t.ciphertext,r=t.salt;if(r)var n=i.create([1398893684,1701076831]).concat(r).concat(e);else var n=e;return n.toString(a)},parse:function(t){var e=a.parse(t),r=e.words;if(1398893684==r[0]&&1701076831==r[1]){var n=i.create(r.slice(2,4));r.splice(0,4),e.sigBytes-=16}return y.create({ciphertext:e,salt:n})}},m=r.SerializableCipher=n.extend({cfg:n.extend({format:_}),encrypt:function(t,e,r,n){n=this.cfg.extend(n);var i=t.createEncryptor(r,n),o=i.finalize(e),s=i.cfg;return y.create({ciphertext:o,key:r,iv:s.iv,algorithm:t,mode:s.mode,padding:s.padding,blockSize:t.blockSize,formatter:n.format})},decrypt:function(t,e,r,n){n=this.cfg.extend(n),e=this._parse(e,n.format);var i=t.createDecryptor(r,n).finalize(e.ciphertext);return i},_parse:function(t,e){return"string"==typeof t?e.parse(t,this):t}}),S=e.kdf={},B=S.OpenSSL={execute:function(t,e,r,n){n||(n=i.random(8));var o=f.create({keySize:e+r}).compute(t,n),s=i.create(o.words.slice(e),4*r);return o.sigBytes=4*e,y.create({key:o,iv:s,salt:n})}},x=r.PasswordBasedCipher=m.extend({cfg:m.cfg.extend({kdf:B}),encrypt:function(t,e,r,n){n=this.cfg.extend(n);var i=n.kdf.execute(r,t.keySize,t.ivSize);n.iv=i.iv;var o=m.encrypt.call(this,t,e,i.key,n);return o.mixIn(i),o},decrypt:function(t,e,r,n){n=this.cfg.extend(n),e=this._parse(e,n.format);var i=n.kdf.execute(r,t.keySize,t.ivSize,e.salt);n.iv=i.iv;var o=m.decrypt.call(this,t,e,i.key,n);return o}})}(),function(){var t=CryptoJS,e=t.lib,r=e.BlockCipher,n=t.algo,i=[],o=[],s=[],a=[],c=[],f=[],u=[],h=[],p=[],l=[];!function(){for(var t=[],e=0;256>e;e++)t[e]=128>e?e<<1:e<<1^283;for(var r=0,n=0,e=0;256>e;e++){var d=n^n<<1^n<<2^n<<3^n<<4;d=d>>>8^255&d^99,i[r]=d,o[d]=r;var v=t[r],y=t[v],g=t[y],_=257*t[d]^16843008*d;s[r]=_<<24|_>>>8,a[r]=_<<16|_>>>16,c[r]=_<<8|_>>>24,f[r]=_;var _=16843009*g^65537*y^257*v^16843008*r;u[d]=_<<24|_>>>8,h[d]=_<<16|_>>>16,p[d]=_<<8|_>>>24,l[d]=_,r?(r=v^t[t[t[g^v]]],n^=t[t[n]]):r=n=1}}();var d=[0,1,2,4,8,16,32,64,128,27,54],v=n.AES=r.extend({_doReset:function(){for(var t=this._key,e=t.words,r=t.sigBytes/4,n=this._nRounds=r+6,o=4*(n+1),s=this._keySchedule=[],a=0;o>a;a++)if(r>a)s[a]=e[a];else{var c=s[a-1];a%r?r>6&&a%r==4&&(c=i[c>>>24]<<24|i[c>>>16&255]<<16|i[c>>>8&255]<<8|i[255&c]):(c=c<<8|c>>>24,c=i[c>>>24]<<24|i[c>>>16&255]<<16|i[c>>>8&255]<<8|i[255&c],c^=d[a/r|0]<<24),s[a]=s[a-r]^c}for(var f=this._invKeySchedule=[],v=0;o>v;v++){var a=o-v;if(v%4)var c=s[a];else var c=s[a-4];f[v]=4>v||4>=a?c:u[i[c>>>24]]^h[i[c>>>16&255]]^p[i[c>>>8&255]]^l[i[255&c]]}},encryptBlock:function(t,e){this._doCryptBlock(t,e,this._keySchedule,s,a,c,f,i)},decryptBlock:function(t,e){var r=t[e+1];t[e+1]=t[e+3],t[e+3]=r,this._doCryptBlock(t,e,this._invKeySchedule,u,h,p,l,o);var r=t[e+1];t[e+1]=t[e+3],t[e+3]=r},_doCryptBlock:function(t,e,r,n,i,o,s,a){for(var c=this._nRounds,f=t[e]^r[0],u=t[e+1]^r[1],h=t[e+2]^r[2],p=t[e+3]^r[3],l=4,d=1;c>d;d++){var v=n[f>>>24]^i[u>>>16&255]^o[h>>>8&255]^s[255&p]^r[l++],y=n[u>>>24]^i[h>>>16&255]^o[p>>>8&255]^s[255&f]^r[l++],g=n[h>>>24]^i[p>>>16&255]^o[f>>>8&255]^s[255&u]^r[l++],_=n[p>>>24]^i[f>>>16&255]^o[u>>>8&255]^s[255&h]^r[l++];f=v,u=y,h=g,p=_}var v=(a[f>>>24]<<24|a[u>>>16&255]<<16|a[h>>>8&255]<<8|a[255&p])^r[l++],y=(a[u>>>24]<<24|a[h>>>16&255]<<16|a[p>>>8&255]<<8|a[255&f])^r[l++],g=(a[h>>>24]<<24|a[p>>>16&255]<<16|a[f>>>8&255]<<8|a[255&u])^r[l++],_=(a[p>>>24]<<24|a[f>>>16&255]<<16|a[u>>>8&255]<<8|a[255&h])^r[l++];t[e]=v,t[e+1]=y,t[e+2]=g,t[e+3]=_},keySize:8});t.AES=r._createHelper(v)}();var aesCrypto={};!function(t){"use strict";t.formatter={prefix:"",stringify:function(t){var r=this.prefix;return r+=t.salt.toString(),r+=t.ciphertext.toString()},parse:function(t){var r=CryptoJS.lib.CipherParams.create({}),e=this.prefix.length;return 0!==t.indexOf(this.prefix)?r:(r.ciphertext=CryptoJS.enc.Hex.parse(t.substring(16+e)),r.salt=CryptoJS.enc.Hex.parse(t.substring(e,16+e)),r)}},t.encrypt=function(r,e){try{return CryptoJS.AES.encrypt(r,e,{format:t.formatter}).toString()}catch(n){return""}},t.decrypt=function(r,e){try{var n=CryptoJS.AES.decrypt(r,e,{format:t.formatter});return n.toString(CryptoJS.enc.Utf8)}catch(i){return""}}}(aesCrypto);
//]]>
</script>
  </b:if>
<!-- Overlay and Back To Top --> 
  <div class='overlay'/>
  <div class='back-top' title='Back to Top'/>
</body>
</html>
