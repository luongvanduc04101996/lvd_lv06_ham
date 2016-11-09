# Hàm
## 1.Khái niệm  
**a. Chương trình:** Một chương trình C bao gồm một hay nhiều hàm. Hàm main() là thành phần bắt buộc của chương trình. Chương trình được bắt đầu thực hiện bằng câu lệnh đầu tiên của hàm main() cho đến khi gặp dấu } cuối cùng của hàm này.

**b. Hàm:** Là một đoạn chương trình độc lập thực hiện trọn vẹn một công việc nhất định, rồi trả về một giá trị tương ứng cho chương trình đã gọi nó.  
* Đặc điểm của Hàm:

 - Là một đơn vị độc lập của chương trình.

 - Không cho phép xây dựng một hàm khác bên trong hàm.  
   
   
## 2.Xây dựng hàm
 **Mẫu chung**:  
   `<Kieu_tra_ve>  <Ten_ham(Danh_sach_tham_so)>`  
* __Kiểu giá trị của hàm__  
Giá trị trả về của hàm phải được xác định dựa vào mục đích của hàm và 
 trong thân hàm ta phải trả về đúng kiểu giá trị đã định ban đầu. Nếu các hàm không trả về giá trị ta phải khai báo kiểu void.  
* __Tên hàm__  
Ðặt theo qui định đối với danh định, nên đặt ngắn gọn và phản ánh phần nào mục đích của hàm.
Tên hàm trong nguyên mẫu và khi khai báo phải giống nhau.  
* __Tham số của hàm__  
 * _Phân loại theo cách sử dụng_:  
**Tham số hình thức**  
**Tham số thực**  
 * _Phân loại theo công dụng_:  
 **Tham số vào**  
 **Tham số ra**  
 **Tham số vừa vào vừa ra**  
  
## 3.Hàm và con trỏ
* Hàm có đối con trỏ (tham chiếu)  
Nếu đối của hàm là con trỏ kiểu int (float,double,. ) thì tham số thực tương ứng phải là địa chỉ của biến kiểu int (float,double,.).
Khi đó địa chỉ của biến được truyền cho đối con trỏ tương ứng.
Do đã biết địa chỉ của biến, nên ta có thể gán cho nó một giá trị mới bằng cách sử dụng các câu lệnh thích hợp trong thân hàm.  
* Khi nào sử dụng đối con trỏ (tham chiếu)  
 Khi muốn bảo lưu lại kết quả tính toán được của các đối số trong hàm để sử dụng cho chương trình gọi hàm có đối số thì chúng 
 ta phải khai báo đối số của hàm là tham chiếu (con trỏ hay dạng địa chỉ). 
