<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=0.6,maximum-scale=2.0, minimum-scale=0.5">
    <!-- <meta name=”viewport” content=" width=device-width, initial-scale=1.0, minimum-scale=0.5, maximum-scale=2.0, user-scalable=yes"/> -->
    <title>cp</title>
    <link rel="stylesheet" href="index.css">
</head>

<body>

    <h1>CP name generator</h1>


    <div class="name">
        <input type="text" value="" id="name1" maxlength="8" >
        <input type="text" value="" id="name2"  maxlength="8" >
        <button class="sure_btn">确定</button>
    </div>
    <!-- 风格选项 -->
    <div class="style">
        词语 <input type="radio" name="style" value="ciyu" checked="checked" onclick="styleOptin(this.value)">
        成语 <input type="radio" name="style" value="chengyu" onclick="styleOptin(this.value)">
    </div>
    <div class="show">
        <div id="cp_name">
            <span class="cp_name"></span>
        </div>
        <button class="change_btn" disabled="disabled">换一换</button>
    </div>
    <div class="intro">
        <p class="intro1"></p>
        <p class="intro2"></p>
        <p class="intro3"></p>
        <p class="intro4"></p>
    </div>
    <div class="author">
        <span>作者：<a href="https://weibo.com/jingminniu" target="_blank">@电电电是你</a></span> 
        <span class="warehouse" ><a href="https://github.com/wwjmn/cpname.git" target="_blank">仓库地址</a></span> 
    </div>
    <script src="dict/Convert_Pinyin.js"></script>
    <script src="dict/chengyuDicFinal.js"></script>
    <script src="dict/chengyuDic.js"></script>
    <script src="dict/ciyuDicFinal2.js"></script>
    <script src="dict/ciyuDic.js"></script>
    <script src="js/index.js"></script>
</body>

</html>
