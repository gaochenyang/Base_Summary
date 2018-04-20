# 前端技术栈
http://devdocs.io/

# jQuery API中文文档
http://www.css88.com/jqapi-1.9/

# 不错的前端资源网站
http://jsrun.net

# 前端资源汇集
http://blog.csdn.net/yuexianchang/article/details/51188309

# 最牛前端
http://f2er.club/

# 伯乐在线
https://github.com/jobbole

# 前端开发仓库

http://code.ciaoca.com/

# 后台管理系统框架

http://www.h-ui.net/H-ui.admin.shtml

# js拼接
'<img src="' + "images/demo.png" + '"/>'

# 相同的key,value加和



 var arry_temp =
 
 		[
		
		 {name:'a',value:2},
		 
		 {name:'a',value:2},
		 
		 {name:'a',value:2}
		 
		 ]
		    var temp = {};var data=[];
			for(var i in arry_temp) {
				var lnglat = arry_temp[i].name;
				if(temp[lnglat]) {
					temp[lnglat].value = temp[lnglat].value + arry_temp[i].value;
					temp[lnglat].name = arry_temp[i].name;
				} else {
					temp[lnglat] = {};
					temp[lnglat].value = arry_temp[i].value;
					temp[lnglat].name = arry_temp[i].name;
				}
				
			}
			console.log(temp)
			
# 对象中追加

var store ={};

store[aa] ='123';


# 对象数组去重 取最后一个对象

` for(var i = 0;i<arr.length;i++){
      if(!find(newArr,arr[i])){
        newArr.push(arr[i]);
      }
    }

 //在数组中查找是否有这个对象
   function find(arr,object){
     var b = false;
        for(var i= 0; i<arr.length;i++){
          if( arr[i].skuId == object.skuId){
            arr[i] = object;
            b=true
          }
        }
      return b;
    }

`
