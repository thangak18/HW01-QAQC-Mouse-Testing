# GitHub repo link và GitHub Issues cho HW01

## Trạng thái hiện tại

- GitHub repo link thật: `https://github.com/thangak18/HW01-QAQC-Mouse-Testing`
- Screenshot trang Issues có GitHub username: cần lưu vào `evidence/github_issues/`
- Ghi chú: `gh` trên máy hiện chưa đăng nhập hợp lệ, nên cần tạo repo/issues trực tiếp trên GitHub bằng tài khoản của sinh viên hoặc đăng nhập lại GitHub CLI.

## Yêu cầu từ đề HW01

Đề yêu cầu nộp Moodle kèm GitHub repo link cho artifacts. Mantis không còn dùng cho HW01; thay vào đó, defect tìm được khi test thiết bị vật lý phải được log thành Issues trong GitHub repository của sinh viên. Cần có screenshot trang Issues hiển thị GitHub username.

## Cách làm nhanh

1. Repo đã được chuẩn bị với tên `HW01-QAQC-Mouse-Testing`.
2. Upload/push toàn bộ thư mục `HW01_SUBMISSION_PACKAGE` lên repo.
3. Vào tab `Issues` của repo và tạo issue cho các defect thật tìm được khi test.
4. Chụp screenshot trang Issues có thấy GitHub username, lưu vào `evidence/github_issues/`.
5. Cập nhật link từng issue vào bảng `3.5 Liên kết defect tiềm năng với GitHub Issue` trong `HW01_Main_Report.md`.

## Issue templates nếu phát hiện defect

### D01 - Pointer lag or abnormal jump

Title:

```text
D01 - Pointer lag or abnormal jump during normal movement
```

Body:

```text
Related test case: TC02 - Di chuyển con trỏ chuột
Severity: Medium

Description:
When moving the physical mouse under normal desk-surface conditions, the pointer appears delayed, jumps unexpectedly, or does not follow the mouse movement smoothly.

Expected result:
The pointer should move smoothly in the same direction as the physical mouse movement.

Actual result:
[Điền kết quả quan sát thật nếu defect xảy ra]

Evidence:
[Dán link video/screenshot nếu có]

Environment:
- Device: computer mouse
- Surface: [mouse pad / desk / paper / other]
- Computer/OS: [điền nếu cần]
```

### D02 - Scroll wheel skips lines or scrolls in wrong direction

Title:

```text
D02 - Scroll wheel skips lines or scrolls in wrong direction
```

Body:

```text
Related test case: TC05 - Cuộn chuột lên/xuống
Severity: Medium

Description:
The scroll wheel does not scroll consistently. It may skip lines, scroll too far, or scroll in the wrong direction.

Expected result:
The page/list should scroll smoothly according to the wheel direction.

Actual result:
[Điền kết quả quan sát thật nếu defect xảy ra]

Evidence:
[Dán link video/screenshot nếu có]
```

### D03 - Drag and drop releases item before button is released

Title:

```text
D03 - Drag and drop fails because item is released unexpectedly
```

Body:

```text
Related test case: TC07 - Drag and drop file/icon
Severity: High

Description:
During drag and drop, the selected file/icon is released before the mouse button is intentionally released.

Expected result:
The item should stay selected while the left button is held and should drop only when the user releases the button.

Actual result:
[Điền kết quả quan sát thật nếu defect xảy ra]

Evidence:
[Dán link video/screenshot nếu có]
```

### D04 - Pointer unstable on common surfaces

Title:

```text
D04 - Pointer becomes unstable on common surface
```

Body:

```text
Related test case: TC09 - Kiểm tra trên nhiều bề mặt
Severity: Low/Medium

Description:
The pointer becomes unstable or inaccurate when the mouse is used on a common surface such as paper, wood, fabric, or a glossy surface.

Expected result:
The mouse should remain usable on normal everyday surfaces, or the limitation should be clearly documented.

Actual result:
[Điền kết quả quan sát thật nếu defect xảy ra]

Evidence:
[Dán link video/screenshot nếu có]
```

### D05 - Mouse is not recognized after unplug/replug

Title:

```text
D05 - Mouse is not recognized after USB unplug/replug
```

Body:

```text
Related test case: TC11 - Rút/cắm lại chuột khi đang sử dụng
Severity: High

Description:
After unplugging and reconnecting the mouse or receiver while the system is running, the mouse is not recognized again.

Expected result:
The system should detect the mouse again and the pointer should become usable without requiring a restart.

Actual result:
[Điền kết quả quan sát thật nếu defect xảy ra]

Evidence:
[Dán link video/screenshot nếu có]
```

## Nếu không tìm thấy defect thật

Nếu quá trình test không phát hiện defect thật, không nên tạo issue giả. Trong report có thể ghi rõ: "No actual defect was found during the executed TC01-TC05 videos; D01-D05 are issue templates for potential defects." Tuy nhiên đề có ghi nên cố gắng tìm ít nhất 5 defects từ thiết bị, nên nếu có thể, hãy test thêm TC07, TC09, TC10, TC11, TC12 để tìm defect thực tế và log issue thật.
