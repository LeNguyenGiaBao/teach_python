# 221219_variable_operator

## Comment: Ghi chú

Bắt đầu bằng dấu "#", các kí tự sau dấu "#" sẽ không dc thực thi khi code chạy

Sử dụng để:

- ghi chú, lâu ngày quay lại đọc sẽ hiểu
- không muốn chạy dòng đó

VD:

```python
# đây là dòng comment
a = 1 # khởi tạo biến a bằng 1
```

---

## Print: in ký tự ra màn hình

Sử dụng để in kí tự ra màn hình

VD:

```python
print("Hello World") # in ra màn hình dòng chữ: Hello World

a = 1
print("a=", 1) # in ra dòng chữ: a= 1
```

---

## Variable: Biến

Khởi tạo

`<tên biến> = <giá trị của biến>`

VD:

```
tuoi = 17
ten = "How Kteam"
PI = 3.14

print(tuoi)
print(ten)
print(PI)
```

Note:

- Tên biến không dc bắt đầu bằng số, vd `1a=1` không hợp lệ nhưng `a1=1` sẽ hợp lệ

---

## Type: Kiểu Dữ Liệu

Sử dụng hàm `type(<bien>)` để kiểm tra kiểu

VD:

```python
tuoi = 17
ten = "How Kteam"
PI = 3.14

print(type(tuoi))
print(type(ten))
print(type(PI))

# Result:
# <class 'int'>
# <class 'str'>
# <class 'float'>
```

Có nhiều kiểu dữ liệu, như trên ví dụ là 'int', 'str' và 'float

Các kiểu dữ liệu
| Kí hiệu | Type | Kiểu | Ví dụ |
| - | - | - | - |
| int | Integer | Số Nguyên | 3 |
| str | String | Chuỗi kí tự | "Hello World"
| float | Float | Số thực | 3.14 |

---

## Numeric operator: Toán tử số học & Comparasion operator: Toán tử so sánh

### Toán tử số học

| Toán tử | Kí hiệu | Ví dụ       | Note                              |
| ------- | ------- | ----------- | --------------------------------- |
| +       | add     | 1 + 2 = 3   | 1 + 2.0 = 3.0 # float             |
| -       | minus   | 1 - 2 = -1  | giống add: 1 - 2.0 = -1.0 # float |
| \_      | multi   | 1 \_ 2 = 2  |                                   |
| /       | divide  | 2 / 2 = 1.0 | kết quả luôn là số thực           |
| //      |         |             |                                   |
| %       |         |             |                                   |
| \*\*    |         |             |                                   |

### Toán tử so sánh

Kết quả của toán tử so sánh là True/ False, kiểu logic
| Kí hiệu | Type | Kiểu | Ví dụ |
| - | - | - | - |
| int | Integer | Số Nguyên | 3 |
| str | String | Chuỗi kí tự | "Hello World"
| float | Float | Số thực | 3.14 |
| bool | Boolean | Logic | True/ False (viết hoa chữ đầu) |

| Toán tử           | Kí hiệu | Ví dụ         | Note |
| ----------------- | ------- | ------------- | ---- |
| lớn               | >       | 2 > 1 # True  |      |
| nhỏ               | <       | 2 < 1 # False |      |
| lớn hơn hoặc bằng | >=      | 2 >= 1        |      |
| nhỏ hơn hoặc bằng | <=      | 2 > 1         |      |
