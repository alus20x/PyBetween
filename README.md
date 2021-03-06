# PyBetween
Wrapper for Between - 비트윈을 위한 파이썬 라이브러리

# Legal Disclaimer
오직 교육적 목적으로만 사용할수 있으며, 비트윈은 VCNC의 자산입니다. 악의적 공격에 이용할시 처벌 받을수 있습니다. 사용에 따른 책임은 사용자가 집니다.
Only use for educational purposes, Between is tradmark for VCNC. User takes responsibility for usage.

## Install
```
pip install PyBetween
```
    
## Using

### Import

```python
> from PyBetween import *
```

### Login
```python
> between = Between('YOUR_ID', 'YOUR_PASSWORD')
> between.login()
True
```

### Get Messages
```python
messages = between.get_messages().data
for message in messages:
	print(message.content)
```

### Send Messages
```python
> between.send_message('Hello!')
True
```

### Class Structure
![](https://mermaid.ink/img/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG4gICAgY2xhc3MgVXNlciB7XG4gICAgICAgIHN0ciBhY2Nlc3NfdG9rZW5cbiAgICAgICAgc3RyIHVzZXJfaWRcbiAgICAgICAgc3RyIHJlbGF0aW9uc2hpcF9pZFxuICAgICAgICBzdHIgYWNjb3VudF9pZFxuICAgICAgICBzdHIgc2Vzc2lvbl9pZFxuICAgICAgICBpbnQgZXhwaXJlc19hdFxuICAgIH1cblxuICAgIFRocmVhZHMgLS18PiBUaHJlYWRcbiAgICBUaHJlYWRzOiBsaXN0KFRocmVhZCkgZGF0YVxuICAgIFRocmVhZHM6IGludCBjb3VudFxuXG5cbiAgICBjbGFzcyBUaHJlYWQge1xuICAgICAgICBzdHIgaWRcbiAgICAgICAgaW50IGNyZWF0ZWRfdGltZVxuICAgICAgICBpbnQgbWVzc2FnZV9jb3VudFxuICAgICAgICBpbnQgdW5yZWFkX2NvdW50XG4gICAgICAgIHN0ciBjaGF0cm9vbV9pZFxuICAgICAgICBpbnQgcmV2aXNpb25cbiAgICB9XG4gICAgXG4gICAgTWVzc2FnZXMgLS18PiBNZXNzYWdlXG4gICAgTWVzc2FnZXM6IGxpc3QoTWVzc2FnZSkgZGF0YVxuICAgIE1lc3NhZ2VzOiBpbnQgY291bnRcbiAgICBNZXNzYWdlczogaW50IHJldmlzaW9uXG5cbiAgICBjbGFzcyBNZXNzYWdlIHtcbiAgICAgICAgc3RyIGlkXG4gICAgICAgIHN0ciBmcm9tXyAoVG8gYXZvaWQgcHl0aG9uIGJ1aWx0LWluIGtleXdvcmQpXG4gICAgICAgIGludCBjcmVhdGVkX3RpbWVcbiAgICAgICAgc3RyIGNvbnRlbnRcbiAgICB9IiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)
