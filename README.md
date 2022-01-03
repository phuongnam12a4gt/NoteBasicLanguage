#Basic Language
## Variable:
### Java:
'Để khai báo biến trong java thì ta thực hiện như sau:<Kiểu dữ liệu> tên biến.'
- Biến local:
-  +là biến được nằm trong các phương thức ,các constructor,trong các khối block.
-  +biến đó sẽ bị phá hủy khi kết thúc các phương thức.
-  +không sử dụng access modifier,được lưu trên vùng nhớ stack.cần khởi tạo giá trị mặc định.
- Biến instance:
-  +Biến được lưu trử trong bộ nhớ heap.
-  +Biến này được khai báo bên trong lớp.
-  +Được phép sử dụng access modifier.
- Biến static:
-  +Biến được lưu trử trong bộ nhớ stack riêng.
-  +Biến static được tạo ra khi chương trình chạy và bị phá hủy khi chương trình hủy đi.
-  +Sẽ chỉ có duy nhất 1 bản sao của biến static được tạo ra.
### Kotlin:
- 'var :dữ liệu có thể thay đổi.'
- 'val:dữ liệu biến ko thể thay đổi.
### So sánh giữa bộ nhớ stack vs bộ nhớ heap:
- Stack:Kích thước là cố định.lưu trử các biến cục bộ.đều 
được lưu trử trong ram.Dữ liệu tự động lưu trử trong stack
sẽ tự động hủy khi hoàn thành xong nhiệm vụ.Vấn đề lỗi xãy ra khi tạo nhiều đối tượng biến cục bộ ,củng như đệ quy hàm thì sẽ gây ra vấn đề tràn bộ nhớ.
- Heap:Kích thước là tự động,được lưu trử trong Ram.được 
dùng cho những bộ nhớ động.kích thước ko cố định ,đáp 
ứng những nhu cầu lưu trử của chương trình.dữ liệu sẽ được quản lý bởi lập trình viên.Nó ko bị hủy đi ,mà người dùng cần phải thực hiện hủy.Trong một số ngôn ngữ lập 
trình như java đã có trình biên dịch tự động hủy.Vì vậy cần phải vào các trình biên dịch.
## AccessModifier:
### Java:
Có 4 loại:
- private:chỉ được truy cập trong cùng 1 lớp.
- public:được truy cập ở mọi nơi.
- default:truy cập trong cùng package.
- protected:được truy cập trong cùng package vs ngoài package thì lớp con của nó phải kế thừa bởi lớp cha.
### Kotlin:
Có 4 loại:
- private:chỉ được truy cập trong cùng 1 lớp.
- public:được truy cập ở mọi nơi.
- internal:chỉ được truy cập trong cùng 1 module.
- protected:được truy cập trong cùng package vs ngoài package thì lớp con của nó phải kế thừa bởi lớp cha.
## Khởi tạo đối tượng:
### Java:
Dùng từ khóa new.
### Kotlin:
- Object Expressions
-  +:Biểu thức object  được thực thi và khởi tạo ngay lập tức.Khi chúng ta sử dụng.
-  +Chúng ta dùng từ khóa object để tạo 1 đối tượng ẩn danh.
-  +Chúng ta có thể cho đối tượng ẩn danh kế thừa.
-  +Chúng ta sử dụng đối tượng ẩn danh như loại trả về.
-  +Có thể truy cập 1 biến từ đối tượng ẩn danh.
- Object declare:
-  +Khai báo object được khởi  tạo lưởi biếng và được truy cập ngay lần đầu tiên khởi tạo.
-  +companion object:có thể được gọi bằng cách gọi tên lớp với thành phần định danh.
## Constructor:
### Java:
- tên trùng với tên lớp.
### Kotlin:
-primary constructor:1 chỉ có 1 primary constructor
-secondary constructor:Có nhiều secondary constructor.
## This:
- được dùng để tham chiếu tới đối tượng hiện tại.
- được dùng để gọi constructor của lớp hiện tại.
- được dùng để gọi phương thức của lớp hiện tại.
- được dùng truyền như 1 tham số trong phương thức.
- được dùng truyền như 1 tham số trong phương thức constructor.
- được dùng để trả về đối tượng của lớp hiện tại.
## final:(java)
- không thể thay đổi biến final:
- ko thể ghi đè phương thức final:
- ko thể thể kế thừa lớp final.
- biến stack final rỗng là khi khởi tạo để rỗng.chỉ được khởi tạo trong khối static rỗng.
