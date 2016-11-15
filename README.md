**Trần Thị Ngọc**  
##Báo cáo học hàm  
[Định Nghĩa](#Định_Nghĩa)  
[Cú Pháp](#Cú_pháp)  
[Hàm và con trỏ](#con_trỏ)  

<a name Định_Nghĩa><a\>  
###1.Định Nghĩa  
**Là một đoạn chương trình độc lập thực hiện trọn vẹn một chương trình nhất định, rồi trả về giá trị cho chương trình gọi nó.**  
*Đặc điểm:*  
- Là một đơn vị độc lập của chương trình.  
- không xây dựng hai hay nhiều hàm lồng nhau.  
  
<a name Cú_Pháp><a\>
###2.Cú Pháp:  
` <Kiểu_trả_về>  <tên_hàm> ( [khai báo các tham số hình thức])
  
{  
  
            [Khai báo các biến cục bộ]  
              
            [Các câu lệnh]  
              
            [return[biểu thức];  
              
}  

`  
*Giải thích:*  
-      <Kiểu_trả_về>: giá trị kiểu dữ liệu của dữ liệu sẽ trả về cho hàm  
-      <tên_hàm>: tên của hàm mà bạn muốn định nghĩa, được đặt theo qui tắc đặt tên của C  
-      [khai báo các tham số hình thức]: các tham số hình thức và kiểu của chúng  
-      [Khai báo các biến cục bộ]: khai báo các biến cục bộ, các biến này chỉ có tác dụng trong nội bộ hàm  
-      [return]: là lệnh thực hiện gán giá trị trả về cho hàm  
-      [biểu thức]: là giá trị trả về cho hàm, có thể là biến, hằng, biểu thức nhưng phải có giá trị xác định và có kiểu dữ liệu là kiểu đã khai báo cho hàm.  
   
Ví dụ 1: Hàm tìm giá trị lớn nhất giữa hai giá trị
  
`int tim_max(int a, int b)  
  
{   
  
            if(a>=b)  
              
                        return a;  
                          
            else  
              
                        return b;  
                          
}  
  
`  
<a name con_trỏ><a\>  
###3.Hàm với con trỏ  
*-  Hàm có đối con trỏ (tham chiếu):*
  -  Tham số thực tương ứng phải là địa chỉ của biến kiểu int (float,double,.).  
  -  Khi đó địa chỉ của biến được truyền cho đối con trỏ tương ứng.  
  -  Do đã biết địa chỉ của biến, nên ta có thể gán cho nó một giá trị mới bằng cách sử dụng các câu lệnh thích hợp trong thân hàm.  
*-  Khi nào sử dụng đối con trỏ (tham chiếu):*  
  -  Khi muốn bảo lưu lại kết quả tính toán được của các đối số trong hàm để sử dụng cho chương trình gọi hàm có đối số thì chúng ta phải khai báo đối số của hàm là tham chiếu (con trỏ hay dạng địa chỉ).



 




 
