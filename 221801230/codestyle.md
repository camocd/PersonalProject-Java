#代码规范
<br>

* 缩进：四个空格

* 变量命名

  * 普通变量和参数变量：首字母小写驼峰  例如:stuName
  * 常量：常量命名全部大写，单词间用下划线隔开  例如：MAX_NUM
  * 函数名：首字母小写驼峰 例如：getStuName
  * 类名：首字母大写驼峰  例如：WordCount

* 函数最大行：30

* 空行规则

  * 两个函数之间空一格

  * 括号使用：前括号跟在同一行末尾

  * ```
    public void charNumCount(){
        String str = readFile();
        charNumber = str.length();
    }
    ```
    
  * ```
    for(int i = 0; i++; i < 100){
        
    }
    ```  

* 操作符前后均添加空格
  * ```
    a = i - 10;
    ```
   
* 注释规则
  * 代码修改的同时，注释也要进行相应的修改
  * 单行注释使用//   多行注释/**/
