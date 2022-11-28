### 1. Thực hành về git
- Tạo một repo trên git với tên là  ```play-ts```
- Khởi tạo 1 project angular ( hoặc node ts với TTS node )
- push code lên với nhánh develop
- Thực hiện bảo mật nhánh develop
- tạo ssh-key và clone lại project bằng ssh link
- Thực hành các lệnh: ```rebase```, ```commit --amend``` và ```commit --amend --no-edit```
- Với mỗi bài tập bên dưới, yêu cầu checkout ra các nhánh riêng biệt và tạo PR mỗi khi xong
- Yêu cầu commit rõ ràng
### 2. Thống kê phần tử
1. tạo ô input nhập mảng các số ( vd: 1,2,4,6,6,2,6 )
2. In ra các số tương ứng với số lần nó xuất hiện trong mảng, sắp xếp từ số xuất hiện nhiều nhất đến nhỏ nhất
Vd: 1,2,4,6,6,2,6 . In ra 6:3, 2:2, 1:1, 4: 1 
### 3. camelCase
1. Tạo ô input nhập vào chuỗi bất kỳ
2. In lại chuỗi đó theo dạng camelCase
Vd: ```Foo Bar``` => ```fooBar```, ```--foo-bar--``` => ```fooBar```, ```__FOO_BAR__``` => ```fooBar```
		
### 4. Template string
Viết chương trình để chuyền dữ liệu vào 1 template
1. Tạo 2 ô input, 1 để viết template, 1 để chuyền dữ liệu
2. In ra kết quả từ template đó
Ví dụ : Input 1 nhập vào hello ```<%= user %>!```, Input 2 nhập vào là ```{ 'user': 'fred' }```, Kết quả in ra là : ```hello fred!```
### 5. Ends With
Kiểm tra xem chuỗi có kết thúc bằng chuỗi mục tiêu đã cho hay không.
Viết một hàm checkend nhận vào 2 hoặc 3 params in ra true hoặc false tùy điều kiện
VD: ```checkend('abc', 'c')``` in ra true
    ```checkend('abc', 'b')``` in ra false
    ```checkend('abc', 'b', 2)``` in ra true
### 6. Viết chương trình in ra tất cả giờ trong 1 ngày cách nhau 10 phút ( vd: 01:00, 01:10, 01:20 ), đổ dữ liệu vào 1 thẻ select;

### 7. Bài toán máy tính
YÊU CẦU CALCULATOR APP
- Tính toán biểu thức do người dùng nhập vào : biểu thức phải chứa các kí tự cho phép như : 0...9, +, -, * , / , ( , ).
- Biểu thức dưới dạng chuỗi(biểu thức toán hạng cho các số nguyên) :
vd : 3*2/4+5.
- Nếu có lỗi xuất hiện do người dùng nhập sai sẽ hiển thị ra lỗi :
1. Nhập vào biểu thức các số không phải số nguyên : vd. 3.012*2.2
2. Nhập các kí tự không được cho phép : &, # , ! , …
3.Nhập thiếu/thừa toán tử : vd. 3**3 , 3 +* 4 , 4*(4-3)(3+1), ...
- Với bất kì trường hợp nào ta phải cung cấp kết quả chính xác tuân theo các quy tắc toán học:
1. Trong ngoặc trước ngoài ngoặc sau , ở đây ta dùng ngoặc tròn ().
2. Nhân chia trước cộng trừ sau.
3. Nếu cùng loại toán tử thì thực hiện tính toán từ trái qua phải.
4. Nếu có lỗi tính toán thì hiển thị thông báo cho người dùng biết
5. Ví dụ : lỗi chia cho 0.
- Các hàm tính toán :
1. Cộng add(int a,int b)
2. Trừ sub(int a,int b)
3. Nhân mul(int a, int b)
4. Chia divide(double a, double b)
- Test :
1. Test định dạng : định dạng như trên đã đề cập phải đúng dạng chuỗi và là biểu thức toán hạng cho các số nguyên
2. UnitTest: trong quá trình tính toán cần đánh giá kết quả đầu ra so với đầu vào có đúng với mong đợi :
Ví dụ. Khi ta sử dụng hàm chia divide(3,2) kết quả mong đợi là 1.5 và so với thực tế có chính xác không ? nếu sai thì phải xem xét lại hàm divide()...

### 8. Viết chương trình tìm tất cả các số chia hết cho 7 nhưng không phải bội số của 5, nằm trong đoạn 10 và 200 (tính cả 10 và 200). Các số thu được sẽ được in thành chuỗi trên một dòng, cách nhau bằng dấu phẩy
### 9. Viết chương trình giải phương trình bậc 2: ax2 + bx + c = 0.

 


