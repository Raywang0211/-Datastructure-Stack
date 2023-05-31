## 簡介：

是一種抽象資料型態(ADT)，遵守了先進後出的概念(FILO)

## 特性:

- 只能從堆疊最頂端存取資料
- 只能從堆疊最頂端新增或刪除資料
- 符合先進後出原則(FILO)
- 不允許隨機存取

## 構造:

只要某一種類別提供了以下的方法也可以稱為一種類別

1. creat: 可以建立一個空的堆疊
2. push(append): 在資料頂端新增資料
3. Pop: 在資料頂端刪除資料
4. Peek: 回傳資料最頂端的資料，沒有刪除

可以用陣列array或是串列linked-list 實作他

## 儲存方式:

使用python list實作簡單的stack

```python
stack = []
stack.append(1)
stack.append(3)
stack.append(5)
stack.append(7)
print(stack)
stack.pop()
print(stack)
```