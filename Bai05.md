| **Loại**        | **Tên**                           | **Mô tả / Ý nghĩa**                                             |
| --------------- | --------------------------------- | --------------------------------------------------------------- |
| **Thuộc tính**  | bookID                          | Mã định danh duy nhất của sách                                  |
|                 | title                         | Tên sách                                                        |
|                 | author                          | Tên tác giả                                                     |
|                 | price                           | Giá bán của sách                                                |
|                 | quantity                        | Số lượng còn trong kho                                          |
| **Phương thức** | displayInfo()                   | Hiển thị thông tin chi tiết của sách (mã, tên, tác giả, giá...) |
|                 | updateQuantity(int newQuantity) | Cập nhật số lượng sách trong kho                                |
|                 | applyDiscount(double percent)   | Giảm giá sách theo phần trăm (%)                                |
|                 | isAvailable()                  | Kiểm tra xem sách còn hàng hay không                            |


Book 
----------------------
  - bookID : String
  - title : String
  - author : String
  - price : double
  - quantity : int
----------------------------
  + displayInfo() : void
  + updateQuantity(newQuantity : int) : void
  + applyDiscount(percent : double) : void
  + isAvailable() : boolean

