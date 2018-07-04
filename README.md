# Hello-World
我的第一个git

#点击空白区域隐藏div
1、$("body").not("#drugResult").click(function() {
		$("#drugResult").css("display", "none");
	})

2、$(document).mouseup(function(e){
	  var _con = $("#hospitaldistpicker .jobdiv");   // 设置目标区域
	  if(!_con.is(e.target) && _con.has(e.target).length === 0){ // Mark 1
		  $("#hospitaldistpicker .jobdiv").css("display","none");
	  }
	});

隐藏滚动条：
/* #searchdrug .drugdiv .input-group #drugResult::-webkit-scrollbar {
	display: none;
} */
