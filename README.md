# Dice Roller - Ứng dụng Đổ Xúc Xắc

Một ứng dụng Android đơn giản được xây dựng bằng Jetpack Compose để mô phỏng việc đổ xúc xắc. Dự án này là điểm khởi đầu tuyệt vời để học các kiến thức cơ bản về Jetpack Compose, quản lý trạng thái (state management) và sử dụng tài nguyên (resources) trong Android.

## Tính năng
- **Giao diện tương tác:** Nhấn nút "Roll" để đổ xúc xắc.
- **Nội dung động:** Hình ảnh xúc xắc thay đổi dựa trên số ngẫu nhiên được tạo ra (từ 1 đến 6).
- **Giao diện hiện đại:** Được xây dựng hoàn toàn bằng Jetpack Compose và Material Design 3.

## Công nghệ sử dụng
- **Ngôn ngữ:** [Kotlin](https://kotlinlang.org/)
- **UI Framework:** [Jetpack Compose](https://developer.android.com/jetpack/compose)
- **Hệ thống thiết kế:** Material Design 3
- **SDK tối thiểu (Min SDK):** 24
- **SDK mục tiêu (Target SDK):** 36

## Hướng dẫn bắt đầu
1. Sao chép (Clone) kho lưu trữ này.
2. Mở dự án trong Android Studio (khuyến nghị phiên bản Ladybug hoặc mới hơn).
3. Kết nối thiết bị Android hoặc khởi động máy ảo.
4. Chạy module `app`.

## Cấu trúc dự án
- `MainActivity.kt`: Chứa điểm đầu vào chính và logic giao diện Compose.
- `ui/theme/`: Chứa các định nghĩa về chủ đề (theme), màu sắc và kiểu chữ cho ứng dụng.
- `res/drawable/`: Chứa các hình ảnh mặt xúc xắc được sử dụng trong ứng dụng.
- `res/values/strings.xml`: Chứa các tài nguyên chuỗi ký tự để dễ dàng bản địa hóa.

## Xem trước (Preview)
Bạn có thể xem trước composable `DiceRollerApp` trực tiếp trong Android Studio bằng cách sử dụng chú thích `@Preview` trong tệp `MainActivity.kt`.

---
Được phát triển như một phần của khóa học Android Basics with Compose.
