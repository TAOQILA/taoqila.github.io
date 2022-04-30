<p id="0"></p>

![HeadLogo](https://user-images.githubusercontent.com/64893569/165919450-66388bff-fb68-4777-b44b-8e16d54c06cd.png)
### 目录 | [个人简介](#1) | [动态](#4) | [下载](#3) | [画展](#2) | [音乐会](#6) |

<p id="1"></p>

---
# 个人简介
- 昵称：淘气喵 TAOQILA
- 生日：2006.7.7 (巨蟹座,15岁)
- 来自：中国-黑龙江省-哈尔滨市
- 爱好：画画 编程 编曲 谈恋爱 撸猫
- QQ群：[921289019](https://jq.qq.com/?_wv=1027&k=0yhFgJKO)
- 邮箱：taoqila@qq.com
- 哔哩哔哩：[淘气喵w](https://space.bilibili.com/353586902)
- pixiv：[淘气喵w](https://www.pixiv.net/users/59091519)

###### [↑ 回到顶部](#0)

<p id="4"></p>

---
# 动态
此处只做粗略展示，具体请访问我的其他媒体！
### 04.26 创作了《刚洗完澡澡呐喵w》画作
![动态](https://user-images.githubusercontent.com/64893569/166089475-9c77e6c6-44d7-48a9-b7af-145cdb3e44e4.jpg)
#### [查看详情 →](https://www.pixiv.net/artworks/97892255)
---
### 01.30 创作了《Outlaw》音乐与MV
<iframe src="//player.bilibili.com/player.html?aid=338626553&bvid=BV1RR4y1T77G&cid=498035578&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>  
#### [查看详情 →](https://www.bilibili.com/video/BV1RR4y1T77G)

###### [↑ 回到顶部](#0)

<p id="3"></p>

---
# 下载
下载时遇到问题请尝试联系淘气喵
- [画集包.zip](https://pan.baidu.com/s/13aRkDUnDdJAOCbH-3JgFHA) | 百度网盘 | 提取码:arts | 2022/04/29
- [乐集包.zip](https://pan.baidu.com/s/1zTL3AgmrDDA_Azz1gQK9Pw) | 百度网盘 | 提取码:obey | 2022/04/30
- [作废软件合集.zip](https://pan.baidu.com/s/1onKTx1AxVC1-jyWU02PhlQ) | 百度网盘 | 提取码:2333 | 2022/04/29

###### [↑ 回到顶部](#0)

<p id="2"></p>

---
# 画展
此处只做粗略展示，具体请访问我的[pixiv](#1)或[画集包](#3)！
![Paintsp1](https://user-images.githubusercontent.com/64893569/165918758-81193dc8-e588-4d18-8345-b16ce2a2cb1e.png)
![Paintsp2](https://user-images.githubusercontent.com/64893569/165918783-ecdea6ea-63fc-465b-acef-fa0107c7ded0.png)

###### [↑ 回到顶部](#0)

<p id="6"></p>

---
# 音乐会
此处只做粗略展示，具体请访问我的[乐集包](#3)！
## Circle Painter
1. [Separation - 淘气喵](https://www.bilibili.com/audio/au2578490)
2. [Falling Autumn  - 淘气喵](https://www.bilibili.com/audio/au2619576) [[MV]](https://www.bilibili.com/video/BV1qf4y1M7Wp)
3. [Findoor - 淘气喵](https://www.bilibili.com/audio/au2619358)
4. [Outlaw  - 淘气喵](https://www.bilibili.com/audio/au2797901) [[MV]](https://www.bilibili.com/video/BV1RR4y1T77G)

###### [↑ 回到顶部](#0)  
  
---
##### 如发现问题欢迎向淘气喵反馈
##### 淘气喵©版权所有

<html lang="zh-cn">
	<head>
		<title>鼠标特效</title>
		
	</head>
	<body>
		
		<!-- 鼠标特效 -->
		<script src="js/jquery-2.2.0.min.js"></script>
		<script>
			var a_idx = 0;
			jQuery(document).ready(function($) {
				addTips = function(e) {
					var a = new Array("富强", "民主", "文明", "和谐", "自由", "平等", "公正", "法治", "爱国", "敬业", "诚信", "友善");
					var i = $("<span />").text(a[a_idx]);
					a_idx = (a_idx + 1) % a.length;
					var x = e.pageX,
						y = e.pageY;
					i.css({
						"z-index": 999999999999999999999999999999999999999999999999999999999999999999999,
						"top": y - 20,
						"left": x,
						"position": "absolute",
						"font-weight": "bold",
						"color": "#ff6651"
					});
 
					$("body").append(i);
					i.animate({
						"top": y - 180,
						"opacity": 0
					}, 1500, function() {
						i.remove()
					})
					return false;
				}
				//绑定鼠标左键
				$("body").click(addTips);
				//绑定鼠标左键
				$("body").bind("contextmenu", addTips)
			});
		</script>
		<script>
			function o(w, v, i) {
				return w.getAttribute(v) || i
			}
 
			function j(i) {
				return document.getElementsByTagName(i)
			}
 
			function l() {
				var i = j("script"),
					w = i.length,
					v = i[w - 1];
				return {
					l: w,
					z: o(v, "zIndex", -1),
					o: o(v, "opacity", 0.5),
					c: o(v, "color", "0,0,0"),
					n: o(v, "count", 99)
				}
			}
 
			function k() {
				r = u.width = window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth,
					n = u.height = window.innerHeight || document.documentElement.clientHeight || document.body.clientHeight
			}
 
			function b() {
				e.clearRect(0, 0, r, n);
				var w = [f].concat(t);
				var x, v, A, B, z, y;
				t.forEach(function(i) {
					i.x += i.xa,
						i.y += i.ya,
						i.xa *= i.x > r || i.x < 0 ? -1 : 1,
						i.ya *= i.y > n || i.y < 0 ? -1 : 1,
						e.fillRect(i.x - 0.5, i.y - 0.5, 1, 1);
					for (v = 0; v < w.length; v++) {
						x = w[v];
						if (i !== x && null !== x.x && null !== x.y) {
							B = i.x - x.x, z = i.y - x.y, y = B * B + z * z;
							y < x.max && (x === f && y >= x.max / 2 && (i.x -= 0.03 * B, i.y -= 0.03 * z), A = (x.max -
									y) / x.max, e.beginPath(), e.lineWidth = A / 2, e.strokeStyle = "rgba(" + s.c +
								"," + (A + 0.2) + ")", e.moveTo(i.x, i.y), e.lineTo(x.x, x.y), e.stroke())
						}
					}
					w.splice(w.indexOf(i), 1)
				}), m(b)
			}
			var u = document.createElement("canvas"),
				s = l(),
				c = "c_n" + s.l,
				e = u.getContext("2d"),
				r, n,
				m = window.requestAnimationFrame || window.webkitRequestAnimationFrame || window.mozRequestAnimationFrame ||
				window.oRequestAnimationFrame || window.msRequestAnimationFrame || function(i) {
					window.setTimeout(i, 1000 / 45)
				},
				a = Math.random,
				f = {
					x: null,
					y: null,
					max: 20000
				};
			u.className = "particle_canvas";
			var browserName = navigator.userAgent.toLowerCase();
			if (/msie/i.test(browserName) && !/opera/.test(browserName)) {
				u.className += ' ie10_gte';
			};
			u.id = c;
			u.style.cssText = "position:fixed;top:0;left:0;z-index:" + s.z + ";opacity:" + s.o;
			j("body")[0].appendChild(u);
			k(), window.onresize = k;
			window.onmousemove = function(i) {
					i = i || window.event,
						f.x = i.clientX,
						f.y = i.clientY
				},
				window.onmouseout = function() {
					f.x = null,
						f.y = null
				};
			for (var t = [], p = 0; s.n > p; p++) {
				var h = a() * r,
					g = a() * n,
					q = 2 * a() - 1,
					d = 2 * a() - 1;
				t.push({
					x: h,
					y: g,
					xa: q,
					ya: d,
					max: 6000
				})
			}
			setTimeout(function() {
				b()
			}, 100)
		</script>
		
		
		<!-- 背景效果 -->
		<style>
			.github-corner:hover .octo-arm {
				animation: octocat-wave 560ms ease-in-out
			}
 
			@keyframes octocat-wave {
 
				0%,
				100% {
					transform: rotate(0)
				}
 
				20%,
				60% {
					transform: rotate(-25deg)
				}
 
				40%,
				80% {
					transform: rotate(10deg)
				}
			}
 
			@media (max-width:500px) {
				.github-corner:hover .octo-arm {
					animation: none
				}
 
				.github-corner .octo-arm {
					animation: octocat-wave 560ms ease-in-out
				}
			}
		</style>
 
	</body>
</html>
