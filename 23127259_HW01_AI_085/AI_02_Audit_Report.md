# AI-02 - Báo cáo kiểm toán AI

Phụ lục cho HW01 - Việc làm QA/QC, lỗi phần mềm và kiểm thử sản phẩm vật lý.

| Trường thông tin | Giá trị |
| --- | --- |
| MSSV | 23127259 |
| Họ và tên | Nguyễn Tấn Thắng |
| Lớp | 23KTPM4 |
| Ngày lập | 03/06/2026 |


| Artifact | File screenshot output AI đã có |
| --- | --- |
| A1 | `evidence/ai_screenshots/A1_requirement1_jobs_ai_output.png` |
| A2 | `evidence/ai_screenshots/A2_requirement2_defects_ai_output_01.png`, `evidence/ai_screenshots/A2_requirement2_defects_ai_output_02.png` |
| A3 | `evidence/ai_screenshots/A3_mouse_test_cases_ai_output.png` |
| A4 | `evidence/ai_screenshots/A4_mindmap_ai_output.png` |
| A5 | `evidence/ai_screenshots/A5_submission_checklist_ai_output.png` |

## A1 - Requirement 1: Thị trường việc làm QA/QC 2026+

| Mục | Nội dung |
| --- | --- |
| (1) Prompt + tool | Tool: ChatGPT / OpenAI Codex. Timestamp: 15:45 01/06/2026. Full prompt được ghi trong `Appendix_A_Prompt_Log.md`, Prompt 04. Tóm tắt prompt: yêu cầu AI trình bày 10 job theo format thống nhất gồm tiêu đề, nền tảng, công ty, link, ngày đăng, ghi chú screenshot, tóm tắt, kỹ năng, lương và tác động của AI. |
| (2) Output AI | Full output AI được cung cấp bằng screenshot thật tại `evidence/ai_screenshots/A1_requirement1_jobs_ai_output.png`. Screenshot hiển thị prompt gốc và phản hồi AI cho phần 10 job; viền đỏ được thêm để đánh dấu đây là evidence output AI. Trước khi nộp cuối, sinh viên cần kiểm tra ảnh có đủ phần output cần audit; nếu chưa đủ thì chụp bổ sung hoặc dán full output. |
| (3) Kết luận kiểm toán | INCOMPLETE cho đến khi kiểm tra từng screenshot có ngày đăng, tài khoản và thông tin job rõ ràng. |
| (4) Lý do | AI có thể format nội dung job, nhưng không thể tự chứng minh screenshot là thật, có đúng ngày hoặc lấy từ tài khoản sinh viên. Evidence QA phải trace được về screenshot thật. |
| (5) Phần sinh viên chỉnh | Đã thêm các file screenshot thật vào `evidence/job_screenshots`, giữ link nguồn. |

Screenshot output AI:

![A1 Requirement 1 output AI](evidence/ai_screenshots/A1_requirement1_jobs_ai_output.png)

## A2 - Requirement 2: 20 lỗi phần mềm 2022-2026

| Mục | Nội dung |
| --- | --- |
| (1) Prompt + tool | Tool: ChatGPT / OpenAI Codex. Timestamp: 15:55 02/06/2026 và 16:00 02/06/2026. Full prompt được ghi trong `Appendix_A_Prompt_Log.md`, Prompt 06 và Prompt 07. Tóm tắt prompt: yêu cầu AI tạo và định dạng 20 software defects giai đoạn 2022-2026, có link nguồn, mô tả, mức độ nghiêm trọng, hậu quả, giải pháp và ví dụ AI bias/hallucination. |
| (2) Output AI | Full output AI được cung cấp bằng screenshot tại `evidence/ai_screenshots/A2_requirement2_defects_ai_output_01.png` và `evidence/ai_screenshots/A2_requirement2_defects_ai_output_02.png`. Screenshot hiển thị prompt gốc và phản hồi AI cho danh sách/phân tích 20 defect; viền đỏ được thêm để đánh dấu evidence output AI. Trước khi nộp cuối, sinh viên cần kiểm tra ảnh có đủ phần output cần audit; nếu chưa đủ thì chụp bổ sung hoặc dán full output. |
| (3) Kết luận kiểm toán | VALID AFTER SOURCE REVIEW, nhưng từng defect sẽ là INCOMPLETE nếu link hỏng hoặc source không chứng minh được claim trong report. |
| (4) Lý do | Phân tích defect công khai cần nguồn đáng tin cậy. AI có thể hallucinate root cause, phóng đại impact hoặc trộn thông tin giữa các sự cố khác nhau. |
| (5) Phần sinh viên chỉnh | Sinh viên đã kiểm tra và sửa link nguồn S1-S20, thay các link hỏng như S1/S4/S6, và thêm một cảnh báo AI bias/hallucination cho từng defect. |

Screenshot output AI:

![A2 Requirement 2 output AI 01](evidence/ai_screenshots/A2_requirement2_defects_ai_output_01.png)

![A2 Requirement 2 output AI 02](evidence/ai_screenshots/A2_requirement2_defects_ai_output_02.png)

## A3 - Requirement 3: Test case cho chuột máy tính

| Mục | Nội dung |
| --- | --- |
| (1) Prompt + tool | Tool: ChatGPT / OpenAI Codex. Timestamp: 17:30 02/06/2026. Full prompt được ghi trong `Appendix_A_Prompt_Log.md`, Prompt 11. Full prompt: “Generate 15 test cases for testing a computer mouse. Include objective, input, steps, expected result, actual result, and verdict.” |
| (2) Output AI | Full output AI được cung cấp bằng screenshot thật tại `evidence/ai_screenshots/A3_mouse_test_cases_ai_output.png`. Screenshot hiển thị prompt gốc và phản hồi AI cho 15 test cases chuột; viền đỏ được thêm để đánh dấu evidence output AI. Các edge cases sinh viên bổ sung gồm nhiều bề mặt, click liên tục nhanh, rút/cắm lại khi đang dùng, giữ click lâu, pin yếu và khoảng cách kết nối không dây. Trước khi nộp cuối, sinh viên cần kiểm tra ảnh có đủ phần output cần audit; nếu chưa đủ thì chụp bổ sung hoặc dán full output. |
| (3) Kết luận kiểm toán | VALID WITH REVIEW. Screenshot output AI gốc đã được thêm; sinh viên vẫn cần kiểm tra ảnh có đủ phần prompt/output cần audit. Test design đã được chỉnh, actual result đã điền cho TC01-TC05 và video evidence đã được thêm. |
| (4) Lý do | Test case theo ISTQB cần objective, input/precondition, steps, expected result, actual result, verdict và evidence. AI tạo được case chức năng phổ biến, nhưng sinh viên phải tự thực thi test thật và bổ sung edge cases dựa trên hành vi thiết bị vật lý. |
| (5) Phần sinh viên chỉnh | Đã điền actual result cho TC01-TC05, thêm link YouTube Shorts, và bổ sung edge cases như nhiều bề mặt, click liên tục, rút/cắm lại, giữ click lâu, pin yếu và khoảng cách không dây. |

Screenshot output AI:

![A3 output AI test case chuột](evidence/ai_screenshots/A3_mouse_test_cases_ai_output.png)

## A4 - CLO G9.1: Mindmap vai trò QA/QC hoặc ISTQB

| Mục | Nội dung |
| --- | --- |
| (1) Prompt + tool | Tool: ChatGPT / OpenAI Codex. Timestamp: 17:55 02/06/2026 và 19:00 02/06/2026. Full prompt được ghi trong `Appendix_A_Prompt_Log.md`, Prompt 12 và Prompt 13. Tóm tắt prompt: yêu cầu AI tạo mindmap QA/QC role hoặc ISTQB process, sau đó review và chỉ ra ít nhất 3 lỗi/sai sót. |
| (2) Output AI | Full output AI được cung cấp bằng screenshot thật tại `evidence/ai_screenshots/A4_mindmap_ai_output.png`. Screenshot hiển thị prompt gốc và phản hồi AI cho mindmap; viền đỏ được thêm để đánh dấu evidence output AI. Các điểm sinh viên đã sửa gồm QA vs QC, thứ tự ISTQB process và giới hạn vai trò AI. Trước khi nộp cuối, sinh viên cần kiểm tra ảnh có đủ phần output cần audit; nếu chưa đủ thì chụp bổ sung hoặc dán full output. |
| (3) Kết luận kiểm toán | VALID sau khi sinh viên chỉnh sửa. |
| (4) Lý do | Artifact hợp lệ vì sinh viên đã chỉ ra và chỉnh các vấn đề khái niệm: QA/QC không giống nhau hoàn toàn, thứ tự ISTQB process được sửa lại, và AI không được xem là thay thế phán đoán của tester. |
| (5) Phần sinh viên chỉnh | Ghi lại 3 lỗi AI đã chỉnh trong main report và giữ artifact mindmap đã sửa trong `QA_QC_Role_Mindmap.md`. |

Screenshot output AI:

![A4 output AI mindmap](evidence/ai_screenshots/A4_mindmap_ai_output.png)

## A5 - Checklist nộp bài và tổ chức report

| Mục | Nội dung |
| --- | --- |
| (1) Prompt + tool | Tool: ChatGPT / OpenAI Codex. Timestamp: 19:05 02/06/2026 và 19:10 02/06/2026. Full prompt được ghi trong `Appendix_A_Prompt_Log.md`, Prompt 14 và Prompt 15. Tóm tắt prompt: yêu cầu AI tạo checklist nộp bài và viết lại prompt log theo trình tự làm HW01. |
| (2) Output AI | Full output AI được cung cấp bằng screenshot thật tại `evidence/ai_screenshots/A5_submission_checklist_ai_output.png`. Screenshot hiển thị prompt gốc và phản hồi AI cho checklist/prompt log; viền đỏ được thêm để đánh dấu evidence output AI. Các mục vẫn cần kiểm tra bằng evidence thật gồm timestamp, video, screenshot và GitHub Issues. Trước khi nộp cuối, sinh viên cần kiểm tra ảnh có đủ phần output cần audit; nếu chưa đủ thì chụp bổ sung hoặc dán full output. |
| (3) Kết luận kiểm toán | INCOMPLETE cho đến khi sinh viên xác nhận từng checkbox và timestamp là thật. |
| (4) Lý do | Checklist có thể do AI hỗ trợ tạo, nhưng trạng thái compliance cuối cùng phụ thuộc vào file thật, evidence thật và timestamp chính xác. Prompt log không được dùng timestamp bịa như bằng chứng cuối cùng. |
| (5) Phần sinh viên chỉnh | Review từng checklist item, thay placeholder timestamp/link còn thiếu và bảo đảm package cuối cùng chỉ chứa evidence thật. |

Screenshot output AI:

![A5 output AI checklist nộp bài](evidence/ai_screenshots/A5_submission_checklist_ai_output.png)

## Tỉ lệ độ chính xác và kết luận

| Loại kết luận | Tỉ lệ | Giải thích |
| --- | --- | --- |
| Hợp lệ | 2/5 artifacts = 40% | A2 sau khi review nguồn; A4 sau khi sinh viên chỉnh. Screenshot output AI A1-A5 đã được thêm vào package. |
| Chưa hoàn chỉnh | 3/5 artifacts = 60% | A1 cần kiểm tra screenshot job cuối; A3 cần đảm bảo screenshot output AI đủ phần phản hồi gốc; A5 cần xác nhận timestamp/checklist. |
| Không hợp lệ | 0/5 artifacts = 0% | Không artifact nào được cố tình nộp ở trạng thái không hợp lệ; output yếu đã được chỉnh hoặc đánh dấu chưa hoàn chỉnh. |

Kết luận: AI nên được dùng để brainstorming, tạo cấu trúc report, tạo bản nháp và gợi ý test ideas. AI không nên dùng làm evidence cuối cùng, test oracle cuối cùng, công cụ xác minh nguồn, bằng chứng thực thi thiết bị thật hoặc thay thế phán đoán của sinh viên/tester. Trách nhiệm QA/QC cuối cùng vẫn thuộc về sinh viên.

Xác nhận của sinh viên: Em đã review nội dung AI tạo ra, chỉnh các phần thiếu căn cứ hoặc chưa hoàn chỉnh, và sẽ chỉ nộp screenshot thật, video evidence thật và link nguồn đã kiểm tra trong bản nộp cuối.
