# My HomeWork for Learn Python the Hard Way
* ex.23 字符串、字节串和字符编码 
```
def print_line(line, encoding, errors):
    next_lang = line.strip()
    raw_bytes = next_lang.encode(encoding, errors = errors)
    cooked_string = raw_bytes.decode(encoding, errors=errors)
    print(raw_bytes, "<====>", cooked_string)
```
* ex.35 分支和函数
* ex.39 字典 
* ex.40 模块、类和对象 
* ex.41 面对对象术语 
