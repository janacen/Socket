
字体乱码解决方案：

在最初接收源头更改格式

根据后端的字符集统一就可以，将下方 Default 改为指定字符集即可

System.Text.Encoding.Default.GetBytes

改为

System.Text.Encoding.UTF8.GetBytes
