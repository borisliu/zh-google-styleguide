语法
==============

## 标识符

标识符只使用ASCII字符、数字、下划线`_`（用于常量和结构化测试方法名称）和`'\('`标识。因此有效的标识符应该符合正则表达式`` `[\)\w]+` ``。

|  风格   | 类型  |
|  ----  | ----  |
| UpperCamelCase  | 类(class) / 接口(interface) / 类型(type) / 枚举(enum) / 装饰器(decorator) / 类型参数(type parameters) |
| lowerCamelCase  | 变量(variable) / 参数(parameter) / 函数(function) / 方法(method) / 属性(property) / 模块别名(module alias) |
| CONSTANT_CASE  | 全局常量，包括枚举值 |
| #ident  | 私有标识 |