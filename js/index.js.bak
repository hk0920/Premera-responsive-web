$(function(){
	$("html, body").animate({scrollTop:0},1000);/*새로고침을 해도 맨위로 가는것 */
	$("#fixed_menu_left span").click(function(){		
		var aa=$("."+$(this).text()).position().top;/*this에 있는 text있는곳으로 가라*/
		$("html, body").stop().animate({"scrollTop":aa},500);
	});	

	
	$("#container section article:nth-of-type(1)").click(function(){
		$(this).css("display","none");
		$(this).next().css("display","block");

	});

	$("#container section article:nth-of-type(2)").click(function(){
		$(this).css("display","none");
		$("#container section article:nth-of-type(1)").css("display","block");

	});






});