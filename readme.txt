v0.0.9 jQuery baigoCheckall 表单全选插件
(c) 2012 baigo - http://www.baigo.net/jQueryPlugins/baigoCheckall.php
License: http://www.opensource.org/licenses/mit-license.php

1 文件
	1.1 baigoCheckall.js 全选插件
	1.2 readme.txt 使用说明

2 用法
	2.1 引入文件
		2.1.1 引入 jQuery 库 <script src="jquery.min.js" type="text/javascript"></script> 此为 jQuery 库，请自行下载 http://www.jquery.com/download/
		2.1.2 引入 baigoCheckall 插件 <script src="baigoCheckall.js" type="text/javascript"></script>

	2.2 初始化 baigoCheckall，如
		obj_form = $("#form_demo").baigoCheckall();

	2.3 在需要操作的 checkbox 中定义 id 和 class，其中，id 代表选框本身，class 代表父元素的 id，如
		<input type="checkbox" id="first" class="none">
		<input type="checkbox" id="second_1" class="first">
		<input type="checkbox" id="second_2" class="first">
		<input type="checkbox" id="second_3" class="first">
		<input type="checkbox" id="second_4" class="first">

		当用户选中 id 为 first 的选框的时候，class 为 first 的选框将全部被选中，反之则为未选中；当任意一个 class 为 first 的选框未被选中时，id 为 first 的选框也会处于未被选中状态。

