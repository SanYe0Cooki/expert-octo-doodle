# API 文档

## 模块：`expert_octo_doodle.core`

### 函数：`greet()`

生成一条问候消息。

**签名：**
```python
def greet(name: str = "World") -> str
```

**参数：**
- `name` (str, optional): 要问候的名字。默认值为 "World"。

**返回值：**
- (str): 格式化的问候字符串

**异常：**
- `ValueError`: 如果 name 不是字符串或为空

**示例：**
```python
>>> from expert_octo_doodle import greet
>>> greet("Alice")
'Hello, Alice! Welcome to expert-octo-doodle.'

>>> greet()
'Hello, World! Welcome to expert-octo-doodle.'
```