<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>浙江大学通行码</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <style type="text/css">
        body {
	background-color: #fff;
	padding: 0;
	margin: 0;
	font-family:"Microsoft YaHei";
    }
     input:-moz-placeholder, textarea:-moz-placeholder {
     color: #fff;
    }
     input:-ms-input-placeholder, textarea:-ms-input-placeholder {
     color: #fff;
    }
     input::-webkit-input-placeholder, textarea::-webkit-input-placeholder {
     color: #fff;
    }
    ol, ul, li {
        padding-left: 0em;
        list-style: none
    }
    h2, h3, h4, ul, li, p {
        padding: 0;
        margin: 0;
    }
    input {
        outline: none;
    }
    html {
        padding: 0;
        margin: 0;
    }
    html, body {
        height: 100%
    }
    .blue-bg{
        background:url(/84204c2d90ac439b8f670d065ea41e89/blue-bg.png) no-repeat left top;
        background-size:100% auto;
    }
    .top-header{
        line-height:44px;
        height:44px;
        font-size:1.3rem;
        color:#fff;
        text-align:center;
        width:100%;
    }
    .banner{
        width:100%;
        text-align:center;
        margin:40px 0;
    }
    .banner img{
        width:88%;
        height:auto;

    }
    .content-box{
        width:90%;
        height:480px;
        border-radius:10px;
        box-shadow:0 0 8px rgba(0, 0, 0, 0.4);
        background:#fff;
        margin:0 auto;
        position:relative;
    }
    .top-title{
        width:90%;
        margin:0 auto;
        line-height:48px;
    }
    .top-title h3{
        font-size:1.3rem;
        color:#333;
        width:70%;
        float:left;
        font-weight:normal;
    }
    .link-btn{
        width:30%;
        float:right;
        text-align:right;
        color:#028aff;
        text-decoration:none;
        font-size:1.1rem;
    }
    .time{
        width:90%;
        margin:0 auto;
        text-align:center;
        line-height:24px;
        font-size:0.9rem;
        color:#999;
    }
    .time2{
        /*width:90%;*/
        margin:5px;
        text-align:center;
        line-height:24px;
        font-size:1.3rem;
        color:black;
        /*font-weight: bold;*/
    }
    .qr{
        /*width:70%;*/
        /*margin:15px auto;*/
        text-align: center;
        margin:0 auto;
    }
    .qr img{
        width:100%;
        height:auto;
    }
    .tip{
        width:100%;
        text-align:center;
        line-height:24px;
        font-size:1rem;
        color:#666;
    }
    .bottom-tip{
        width:80%;
        margin:30px auto;
    }
    .bottom-tip h3{
        float:left;
        font-size:1rem;
        color:#999;
        font-weight:normal;
        width:70%;
    }
    .orange{
        color:#f75908;
    }
    .hz{
        margin-top: 10px;
        margin-bottom: 10px;
        width:100%;
        text-align:center;
        line-height:24px;
        font-size:1rem;
        color:#666;
    }
    .bgr-blue{
        background: #028aff;
        font-size: 18px;
        border-radius: 20%;
        padding: 3px;
        color: white;
    }
    .bgr-oranige{
        background: #EB6E18;
        font-size: 18px;
        border-radius: 20%;
        padding: 3px;
        color: white;
    }
    </style>
</head>

<script src="/84204c2d90ac439b8f670d065ea41e89/jquery-1.7.2.min.js"></script>
<script type="text/javascript" src="/84204c2d90ac439b8f670d065ea41e89/jquery.qrcode.min.js"></script>


<script>setTimeout("location=location; ", (24*3600*1000)*3); </script>
<script>
    jQuery(function(){

        var colour = '';
        var flag = '';
        if(null == colour || "" == colour){
            colour = "CCCCCC";
        }


        var mzt='';

        var account='3160100224';
        jQuery('#output').qrcode({
            render	: "table",
            width: 180,
            height: 180,
            text	: 'jT6tmuodGqINMrflvMDAWP8k7rEe1qNDAbampP1sd4Yc9ft6m6cRYt7QkhzF9fpt/+2ZADAe/RA=',
            render: "canvas", //也可以替换为table
            foreground: "#1E90FF",
            background: "#FFF",

        });
    })

    if(true){
        //获取系统时间
        function showTime() {
            nowtime = new Date();
            year = nowtime.getFullYear();//年
            month = nowtime.getMonth() + 1;//月
            day = nowtime.getDate();//日
            hour = nowtime.getHours();//时
            minutes = nowtime.getMinutes(); //分
            seconds = nowtime.getSeconds(); //秒
            //文字增加空格
            document.getElementById("div_timer").style = "white-space:pre;";
            //显示时间
            document.getElementById("div_timer").innerText = p(month) + "月" + p(day) + "日 " + p(hour) + ":" + p(minutes) + ":" + p(seconds);
        }
        setInterval("showTime()", 1000);
        //月日时分秒小于10补0
        function p(s) {
            return s < 10 ? '0' + s : s;
        }
    }

</script>



<body class="blue-bg">
<div class="banner"><img src="/84204c2d90ac439b8f670d065ea41e89/text.png"></div>




<div class="content-box">
    <div class="top-title">
        <h3>的通行码</h3>
        

            <span  class="bgr-blue">本科生</span>
            

        


    </div>
    
        <strong><div class="time2" id="div_timer"></div></strong>
    
    <div class="qr">
        
            <div id="output" style="margin-top: 10px;margin-bottom: 10px"></div>
        
        
        
        

        
    </div>
    
        
            <div class="time">有效期：2020-05-09 - 2020-05-15</div>
        
    

    <div id="hzjkm"><div class="hz" style="color: #55b957">健康码为 绿码</div></div>


    <div id="dateTime"><div class="time">同步时间：2020-05-13 09:58:11</div></div>

    
        <p class="tip" style="margin-top: 10px;">凭蓝码可在浙江大学校园内通行<br>请主动出示，配合检查</p>
    
    
    <div style="text-align:center; margin-top: 10px">
        <a target="_blank" href="http://one.zju.edu.cn/taskcenter/wechat/index" >办事大厅</a>&nbsp;&nbsp;&nbsp;
        <a target="_blank" href="/pass_code/zx/getList" >申请记录</a>&nbsp;&nbsp;&nbsp;





    </div>
</div>
<div class="bottom-tip">
    <h3>安 保 处 ：0571-88206110</h3>
    <a href="http://xwfw.zju.edu.cn/mobile/redir.php?catalog_id=371039" target="_blank" class="link-btn">常见问题</a>
    <h3>技术支持：0571-87951669</h3>
</div>
</body>
</html>
