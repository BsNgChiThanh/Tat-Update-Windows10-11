# TẮT UPDATE WINDOWS 10 VÀ WINDOWS 11 #

## Bước 1: ##

- Nhấn tổ hợp phím tắt **Windows + R** để mở nhanh hộp thoại **RUN**
- Nhập vào ô tìm kiếm cụm từ **regedit** nhấn OK để mở cửa sổ regedit

![1](https://user-images.githubusercontent.com/82578024/204069784-2145dd00-f49a-4349-9b5c-4f3c24ca9fb0.jpg)

## Bước 2: ##

- Lần lượt mở các thư mục nằm bên tay trái cửa sổ Regedit Editor theo thứ tự sau: 
- **HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows**

## Bước 3: ##

- Nhấn phải chuột vào thư mục Windows chọn **New  Key**

![image](https://user-images.githubusercontent.com/82578024/204069929-e902352b-ce4a-4ec2-8ed9-d489c5b38fa0.png)

## Bước 4: ##

- Đặt tên cho Key mới tạo tên **WindowsUpdate**

##Bước 5: ##

- Tiếp tục nhấn phải chuột vào thư mục **WindowsUpdate** mới tạo chọn **New -> Key**

![image](https://user-images.githubusercontent.com/82578024/204070096-d8ed9692-260a-4a5e-b542-76d9a576c303.png)

## Bước 6: ##

- Đặt tên cho Key mới tên **AutoUpdate**

## Bước 7: ##

- Nhấn phải chuột vào vị trí trống trong thư mục **AutoUpdate** chọn **New -> DWORD (32-bit) Value**

![image](https://user-images.githubusercontent.com/82578024/204070171-737c52ae-23c8-4ce2-a4ae-68a268516def.png)

## Bước 8: ##

- Đặt tên cho khóa mới là **Tatcapnhapwwin10** 
- Bấm đúp vào Key mới tạo và thay đổi giá trị của nó từ 0 thành 1.
- Trường hợp muốn mở lại thì chọn 0
- Ghi chú:
    - 0: ON
    - 1: OFF

![image](https://user-images.githubusercontent.com/82578024/204070252-81c1b5b8-0bd7-4cba-9223-83eba5534a69.png)

## RESTART MÁY TÍNH LẠI LÀ OK ##
