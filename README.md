# 2D-Game-TheLastAirbender

Project game 2D viết bằng Java. Có thể mở và chạy bằng Eclipse.

## Yêu cầu

- JDK 8 trở lên
- Eclipse IDE

## Cách mở project trong Eclipse

1. Mở Eclipse
2. Chọn **File -> Import**
3. Chọn **Existing Projects into Workspace**
4. Nhấn **Next**
5. Chọn thư mục project `2D-Game-TheLastAirbender`
6. Nhấn **Finish**

## Cách chạy project trong Eclipse

1. Trong Eclipse, mở file:

   `src/com/neet/Main/Game.java`

2. Tìm hàm:

   `public static void main(String[] args)`

3. Chuột phải vào file **Game.java**
4. Chọn:

   **Run As -> Java Application**

## Main class

Main class của project là:

`com.neet.Main.Game`

File chứa hàm `main`:

`src/com/neet/Main/Game.java`

## Nếu project không chạy

Kiểm tra các mục sau:

- Project đã được import đúng vào Eclipse
- Eclipse đã gắn **JRE System Library**
- Máy đã cài JDK
- Không có file source bị thiếu

## Cách kiểm tra JRE trong Eclipse

1. Chuột phải project
2. Chọn **Properties**
3. Chọn **Java Build Path**
4. Kiểm tra có **JRE System Library**
5. Nếu chưa có, thêm JRE vào project

## Ghi chú

Khi chạy, chương trình sẽ tạo cửa sổ game từ class `Game` và hiển thị `GamePanel`.
