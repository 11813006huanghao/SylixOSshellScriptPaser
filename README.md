# SylixOSshellScriptPaser
original SlixOS shell can execute script file but can not parse branch statement such as if/else if/else/while/for, this code provode  functions to parse those branch statements

为了解析分支语句并合理跳转，需要解析出分支语句中的变量的值和比较符，判断比较条件是否满足，不满足则跳转。
难点在于，分支语句可以互相多重嵌套，因此需要使用栈这个数据结构来保存变量
