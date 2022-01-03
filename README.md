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
###So sánh giữa bộ nhớ stack vs bộ nhớ heap:
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
