## So sánh về computed và subcribe trong knockout
Tính chất| computed | subcribe
---|---|--- 
Tính đồng bộ| Không có tính đồng bộ | Có tính đồng bộ, khai báo trước sẽ chạy trướctrước
Kiểu trả về| Là hàm có trả về giống như getter, setter| Là hàm void, không có kiểu trả về giống như 1 callback function
Số lần thực hiện| Tùy thuộc vào số obseverble trong hàm thay đổi mà hàm sẽ thực hiện từng đó lần, bbạn không biết được obseverble nào đã thay đổi và kích hoạt computed| Chỉ thực hiện 1 lần khi các obseverble thay đổi 
- computed dùng khi muốn lằng nghe sự thay đổi của nhiều obseverble
- subcribe dùng khi chỉ muốn lắng nghe sự thay đổi 1 obseverble