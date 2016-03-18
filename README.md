# -
百度前端任务
@@ -0,0 +1,138 @@
<!DOCTYPE HTML>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<title>0基础第一次尝试做前端</title>
<style>
span{
color:red;
}
</style>
</head>
<hx>这是网页标题</hx>
<ul>
     <li><a href="1" title="说啥好呢">说啥好呢</a> </li>
    <li><a href="2" title="说啥好呢">说啥好呢</a></li>
    <li><a href="3" title="说点啥好呢">说点啥好呢</a></li>
</ul>
<body>
<h1>文章一级标题</h1>
<h2>文章二级标题</h2>
文章：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;文章作者：
<p>这是一个<span>不知道</span>说啥的段落，这是一个不知道说啥的段这是一个不知道说啥的段落，这是一个不知道说啥的段落这是一个不知道说啥的<em>段落</em>，这是一个不知道说啥的段落落这是一个不知道说啥的段落，空行了</br>这是一个不知道说啥的段落，这里有个<a href="http://0" title="链接">链接</a>，这是一个不知道说啥的段落，这是一个不知道说啥的段落</p>
<img http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg
 <p>换了个新段落了，那谁曾经说过<q>I can code, they can not. That's pretty damn cool!</q> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前面是几个空格，这里有个<strong>粗体字</strong>,又下一行了<br/>
 <img src="http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg" title="海贼王"
<!--海贼王是我最喜欢的漫画-->这里有个注释
</p>
 <hr>

<br>
<br>
<h1>另一篇文章一级标题</h1>
<h2>另一篇文章二级标题</h2>
 文章：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;文章作者：
 <p>这又是一个不知道说啥的段落这又是一个不知道说啥的段落这又是一个不知道说啥的段落这又是一个不知道说啥的段落这又是一个不知道说啥的段落这又是一个不知道说啥的段落这又是一个不知道说啥的段落这又是一个不知道说啥的段落这里可以在新窗口中打开链接（<a href="X" target="_blank">click here!</a></a>）不知道说啥的段落<br/>说点什么好呢</p>
  <img src="http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg" title="海贼王"
  <ul>
  <li>路飞</li>
  <li>佐罗</li>
  <li>山治</li>
  <li>娜美</li>
  <li>乔巴</li>
  <li>布鲁克</li>
  <li>乌索普</li>
  <li>弗兰奇</li>
  <li>罗宾</li>
  <br/>
  <br/>
  <h1>图片</h1>
  <img src="http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg" title="海贼王" >海贼王
  <img src="http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg" title="海贼王" >海贼王
    <img src="http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg" title="海贼王" >海贼王  <img src="http://img1.imgtn.bdimg.com/it/u=3450944733,2741969930&fm=11&gp=0.jpg" title="海贼王" >海贼王<br/>
    <br/>
<h1>最后一篇文章一级标题</h1>
<h2>文章二级标题</h2>
海贼王：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;人气排名：
<ol>
    <li>路飞</li>
    <li>佐罗</li>
    <li>山治</li>
</ol>
<table>
<style type="text/css">
table tr td,th{border:1px solid #000;}
</style>
<table summary=海贼王人物介绍>
<caption>海贼王人物</caption>
  <tr>
    <th>名称 </th>
    <th>能力 </th>
    <th>性格 </th>
  </tr>
  <tr>
    <td>路飞 </td>
    <td>橡胶果实</td>
    <td>爱吃</td>
  </tr>
  <tr>
    <td>佐罗</td>
    <td>剑士 </td>
    <td>路痴</td>
  </tr>
  <tr>
    <td>山治</td>
    <td>恶魔</td>
    <td>好色</td>
  </tr>
</table>

<form>

  <br />
  <h1>这里是侧栏</h1>
  <h2>这里是侧栏标题</h2>
  <label for="email">输入你的邮箱地址</label>
  <input type="email" id="email" placeholder="这里填邮箱地址"><br/>按邮箱格式输入
<br/>
<form  method="post" action="save.php">
    请输入密码:
<input type="passward" name="pass"/>
	<br>
	请重复密码:
<input type="password" name="pass"/>
</form>
<br/>
性别:
   <label for="male">男</label>
  <input type="radio" name="gender" id="male" />

  <label for="female">女</label>
  <input type="radio" name="gender" id="female" /><form action="save.php" method="post" >
    <label>所在地:</label>
    <select multiple="multiple">
      <option value="北京">北京</option>
      <option value="上海">上海</option>
      <option value="广州">广州</option>
      <option value="深圳">深圳</option>
    </select>
  <br/>
  <br/>
</form>
你对什么活动感兴趣：<br/>
<label for="running">慢跑</label>
<input type="checkbox" name="hobbit" id="running"/>
<br/>
<lable for="climbing" >登山</lable>
<input type="checkbox" name="hobbit" id="climbing"/><br/>
<label for="basketball">篮球</label>
<input type="checkbox" name="hobbit" id="basketball"<br/>
<br/>
<form action="save.php" method="post" >
    <label>个人介绍：</label>
    <textarea cols="60" rows="10">在这里输入内容...</textarea>
    <input type="submit" value="确定"  name="submit" />
    <input type="reset" value="重置"  name="reset" />
</form>
</body>
</html>
