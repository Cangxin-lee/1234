<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <title>人物标记图</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
    }
    .image-container {
      position: relative;
      display: inline-block;
    }
    .marker {
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: red;
      border-radius: 50%;
      border: 2px solid white;
      cursor: pointer;
    }
    .tooltip {
      position: absolute;
      background-color: rgba(0, 0, 0, 0.75);
      color: white;
      padding: 8px;
      border-radius: 6px;
      white-space: nowrap;
      display: none;
      font-size: 14px;
    }
    .marker:hover + .tooltip {
      display: block;
    }
  </style>
</head>
<body>
  <h1>两岸领导人会晤<h1>
  <h2>点击红点查看人物信息</h2>
  <div class="image-container">
    <!-- 沉浸式新闻 -->
    <img src="123.jpg" alt="人物合影" width="1000" />
    <!-- 标记点1：马英九 -->
    <a href="ma.html" class="marker" style="top:25px; left: 550px;"></a>
    <div class="tooltip" style="top: -15px; left: 500px;">马英九</div>
    <!-- 标记点2：习近平 -->
    <a href="xi.html" class="marker" style="top: 24px; left: 1000px;"></a>
    <div class="tooltip" style="top: -15px; left: 950px;">习近平</div>
</p> 两岸领导人会面，指海峡两岸会面双方均以时任最高领导人的身份出席的会面，截至当下仅有一次，即2015年11月7日下午习近平、马英九在新加坡的历史性会面，简称“习马会”。</p>

</p>2015年11月7日15时，习近平同台湾地区领导人马英九在新加坡香格里拉饭店进行“世纪之握”的动作，就推进两岸关系和平发展交换意见，这是1949年以来两岸领导人的首次会面。会面使用两岸领导人的身份和名义，互称“先生”。</p>   <div class="description-area">   <p>本合影拍摄于 <strong>2015年11月</strong> 两岸领导人会晤期间</p>
  </div>
</body>
</html>
