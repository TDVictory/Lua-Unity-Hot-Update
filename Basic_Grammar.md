# Lua 基本语法
## 注释
### 单行注释
两个减号"--"是对语句的单行注释，等效于C#中的双斜杠"//"。
```
--
```
### 多行注释
教程上说通过“--[[”和“--]]”可以进行多行注释。——测试后发现实际上是“--[[...]]”的方式进行多行注释。
```
--[[
a = 1
b = 2
c = 3
]]
```
### 标示符
Lua标示符用于定义一个变量，
