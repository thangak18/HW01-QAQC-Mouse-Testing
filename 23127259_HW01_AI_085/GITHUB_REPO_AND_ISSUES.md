# Link GitHub repo và GitHub Issues cho HW01

## Trạng thái hiện tại

- GitHub repo link thật: `https://github.com/thangak18/HW01-QAQC-Mouse-Testing`
- GitHub issue trạng thái defect log: `https://github.com/thangak18/HW01-QAQC-Mouse-Testing/issues/1`
- Screenshot trang Issues có GitHub username: `github_issues_screenshot.png`
- Repo đang để chế độ public để giảng viên/TA có thể truy cập khi chấm bài.

## Yêu cầu từ đề HW01

Đề yêu cầu nộp Moodle kèm GitHub repo link cho artifacts. Mantis không còn dùng cho HW01; thay vào đó, defect tìm được khi test thiết bị vật lý phải được log thành Issues trong GitHub repository của sinh viên. Cần có screenshot trang Issues hiển thị GitHub username.

## Cách làm nhanh

1. Repo đã được chuẩn bị với tên `HW01-QAQC-Mouse-Testing`.
2. Upload/push toàn bộ thư mục `23127259_HW01_AI_085` lên repo.
3. Issue trạng thái defect log đã được tạo tại `issues/1`.
4. Vào tab `Issues` của repo và tạo issue riêng cho các defect thật tìm được khi test.
5. Chụp screenshot trang Issues có thấy GitHub username, lưu thành `github_issues_screenshot.png`.
6. Cập nhật link từng issue vào bảng `3.5 Liên kết defect tiềm năng với GitHub Issue` trong `HW01_Main_Report.md`.

## Mẫu GitHub Issue nếu phát hiện defect

### D01 - Con trỏ bị trễ hoặc nhảy bất thường

Tiêu đề:

```text
D01 - Con trỏ bị trễ hoặc nhảy bất thường khi di chuyển bình thường
```

Nội dung:

```text
Test case liên quan: TC02 - Di chuyển con trỏ chuột
Mức độ nghiêm trọng: Medium

Mô tả:
Khi di chuyển chuột vật lý trên bề mặt bàn thông thường, con trỏ bị trễ, nhảy bất thường hoặc không đi theo chuyển động của chuột một cách mượt mà.

Kết quả mong đợi:
Con trỏ phải di chuyển mượt và cùng hướng với chuyển động của chuột vật lý.

Kết quả thực tế:
[Điền kết quả quan sát thật nếu defect xảy ra]

Bằng chứng:
[Dán link video/screenshot nếu có]

Môi trường:
- Thiết bị: chuột máy tính
- Bề mặt: [lót chuột / bàn / giấy / bề mặt khác]
- Máy tính/Hệ điều hành: [điền nếu cần]
```

### D02 - Bánh xe cuộn bị nhảy dòng hoặc cuộn sai hướng

Tiêu đề:

```text
D02 - Bánh xe cuộn bị nhảy dòng hoặc cuộn sai hướng
```

Nội dung:

```text
Test case liên quan: TC05 - Cuộn chuột lên/xuống
Mức độ nghiêm trọng: Medium

Mô tả:
Bánh xe cuộn hoạt động không ổn định, có thể bỏ qua dòng, cuộn quá xa hoặc cuộn sai hướng.

Kết quả mong đợi:
Trang hoặc danh sách phải cuộn mượt theo đúng hướng xoay của bánh xe.

Kết quả thực tế:
[Điền kết quả quan sát thật nếu defect xảy ra]

Bằng chứng:
[Dán link video/screenshot nếu có]
```

### D03 - Drag and drop bị nhả item trước khi thả nút

Tiêu đề:

```text
D03 - Drag and drop thất bại vì item bị nhả ngoài ý muốn
```

Nội dung:

```text
Test case liên quan: TC07 - Drag and drop file/icon
Mức độ nghiêm trọng: High

Mô tả:
Trong lúc drag and drop, file/icon đang được chọn bị nhả ra trước khi người dùng chủ động thả nút chuột.

Kết quả mong đợi:
Item phải tiếp tục được giữ khi người dùng giữ nút trái chuột và chỉ được thả khi người dùng nhả nút.

Kết quả thực tế:
[Điền kết quả quan sát thật nếu defect xảy ra]

Bằng chứng:
[Dán link video/screenshot nếu có]
```

### D04 - Con trỏ không ổn định trên bề mặt thông dụng

Tiêu đề:

```text
D04 - Con trỏ không ổn định trên bề mặt thông dụng
```

Nội dung:

```text
Test case liên quan: TC09 - Kiểm tra trên nhiều bề mặt
Mức độ nghiêm trọng: Low/Medium

Mô tả:
Con trỏ trở nên không ổn định hoặc thiếu chính xác khi chuột được dùng trên bề mặt thông dụng như giấy, gỗ, vải hoặc bề mặt bóng.

Kết quả mong đợi:
Chuột phải vẫn dùng được trên các bề mặt thường gặp hằng ngày, hoặc giới hạn sử dụng phải được ghi rõ.

Kết quả thực tế:
[Điền kết quả quan sát thật nếu defect xảy ra]

Bằng chứng:
[Dán link video/screenshot nếu có]
```

### D05 - Chuột không được nhận lại sau khi rút/cắm lại

Tiêu đề:

```text
D05 - Chuột không được nhận lại sau khi rút/cắm lại USB hoặc receiver
```

Nội dung:

```text
Test case liên quan: TC11 - Rút/cắm lại chuột khi đang sử dụng
Mức độ nghiêm trọng: High

Mô tả:
Sau khi rút và cắm lại chuột hoặc receiver trong lúc hệ thống đang chạy, chuột không được nhận lại.

Kết quả mong đợi:
Hệ thống phải nhận lại chuột và con trỏ phải dùng được mà không cần khởi động lại máy.

Kết quả thực tế:
[Điền kết quả quan sát thật nếu defect xảy ra]

Bằng chứng:
[Dán link video/screenshot nếu có]
```

## Nếu không tìm thấy defect thật

Nếu quá trình test không phát hiện defect thật, không nên tạo issue giả. Trong report có thể ghi rõ: "Không phát hiện defect thật trong các video TC01-TC05 đã thực thi; D01-D05 là mẫu issue cho defect tiềm năng." Tuy nhiên đề có ghi nên cố gắng tìm ít nhất 5 defects từ thiết bị, nên nếu có thể, hãy test thêm TC07, TC09, TC10, TC11, TC12 để tìm defect thực tế và log issue thật.
