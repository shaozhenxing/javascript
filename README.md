# js如何设置css样式呢？
function setStyle(){
		var oDiv = document.getElementById('div1'); 
		oDiv.style.width = '400px';
		oDiv.style.marginLeft = '10px'; 
	}  
<h6>备注:css怎么写,js就怎么写,除了class,写成className,css有横杆的,js中去掉横杆首字母变成大写</h6>
# js如何获取css样式呢？
  
# 属性的两种访问方式
  oText.value;
  oDiv[name]
# 几种常见的循环方法
  第一种 while
  var a = 1;//1.条件初始化
  while(a<5){//2.条件判断
    alert(a); //3.执行语句
    a++；     //4.自增
  }<br/>
  第二种 for
  for(var a = 1;a<5;a++){
    alert(a);
  }
# js的数据类型都有哪些呢？如何检测数据类型呢？
  typeof xxx 检测数据类型
  string,number,boolean,object,function,undefined
# 关于i的问题
   for循环里面用i加事件等操作，会导致只有最后一个生效	
   第一种解决方法 给自定义属性
   	for(var i = 0;i < aInput.length;i++){ 
	    aInput[i].title = i;              
	    aInput[i].onclick = function () { 
	        alert('点击的i='+this.title);    
	    };                                
	}<br/>                                     
  第二种解决方法 闭包
# 如何检测这个值是不是数字呢？
  isNaN()  true不是数字，false是数字
  
  	
