<h2>bugku web</h2>
1. 直接f12flag在源码中
2. 修改源码中maxlength为2或3，增加输入长度即可<br>maxlength 属性规定输入字段的最大长度，以字符个数计。
3. 打开是一段php代码，通过get的方式通过what变量传参，修改url 加上？what=flag
4. 打开是一段php代码，通过post的方式通过what变量传参,查了百度。找到了http://coolaf.com/这个网址可以输入what=flag直接输出
5. 代码get传参num不能为数字或数字字符串但是值==1，在php中==是弱比较，“1”和1是一样的，所以可以payload ?num=1x或?num=1e0.1