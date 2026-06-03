# Phụ lục A - Nhật ký prompt


## Prompt 01 - Hiểu yêu cầu HW01

* Tool: ChatGPT
* Timestamp: [15:30 01/06/2026]
* Prompt:

```text
Em vừa upload file HW01. Bạn hãy đọc kỹ file này rồi giải thích chi tiết bằng tiếng Việt cho em hiểu bài này yêu cầu làm gì. Hãy trình bày rõ từng requirement, cách nộp bài, các file cần nộp, cách dùng AI, phần AI Audit Report, AI Critique, Mandatory Disclosure và những lỗi có thể khiến bài bị 0 điểm.
```

---

## Prompt 02 - Làm rõ Requirement 1

* Tool: ChatGPT
* Timestamp: [15:35 01/06/2026]
* Prompt:

```text
Theo file HW01 thì Requirement 1 phải làm ở đâu? Em chưa hiểu phần QA/QC Job Market 2026+ là phải test trên hệ thống hay tìm job thật trên các website tuyển dụng. Bạn hãy giải thích giúp em và chỉ rõ em cần tìm những thông tin gì cho mỗi job.
```

---

## Prompt 03 - Tìm nền tảng và keyword cho việc làm QA/QC

* Tool: ChatGPT
* Timestamp: [15:37 01/06/2026]
* Prompt:

```text
Bạn hãy gợi ý cho em các website có thể tìm job QA/QC để làm Requirement 1. Em cần tìm 10 job trong vòng 60 ngày, trong đó có ít nhất 3 job liên quan AI, LLM hoặc automation-AI. Hãy gợi ý keyword tìm kiếm và format để em trình bày từng job trong report.
```

---

## Prompt 04 - Tổ chức nội dung 10 screenshot việc làm

* Tool: ChatGPT
* Timestamp: [15:45 01/06/2026]
* Prompt:

```text
Em đã gửi screenshot của 10 job em tìm được. Bạn hãy giúp em viết lại nội dung 10 job này theo format thống nhất gồm: Job title, Platform, Company, Job link, Posted date, Screenshot note, Job description summary, Required skills, Salary và AI Impact Analysis. Chỉ dùng đúng thông tin có trong screenshot, phần nào không thấy thì ghi Not disclosed hoặc Not shown in screenshot.
```

---

## Prompt 05 - Hiểu Requirement 2

* Tool: ChatGPT
* Timestamp: [15:50 02/06/2026]
* Prompt:

```text
Bây giờ em làm tiếp Requirement 2. Bạn hãy giải thích giúp em phần 20 Software Defects 2022-2026 yêu cầu làm gì. Em cần hiểu thế nào là software defect, phải tìm nguồn ở đâu, cần có những cột nào, và phần AI bias/hallucination instance phải viết như thế nào cho đúng yêu cầu của đề.
```

---

## Prompt 06 - Lập danh sách 20 lỗi phần mềm

* Tool: ChatGPT
* Timestamp: [15:55 02/06/2026]
* Prompt:

```text
Bạn hãy giúp em tìm và trình bày 20 software defects trong giai đoạn 2022-2026 để làm Requirement 2. Trong đó phải có ít nhất 5 defects liên quan AI/LLM như hallucination, prompt injection hoặc bias. Với mỗi defect, hãy trình bày source link, description, severity, consequences, solution và một ví dụ AI có thể bị bias hoặc hallucinate khi giải thích defect đó.
```

---

## Prompt 07 - Chỉnh Requirement 2 theo format report

* Tool: ChatGPT
* Timestamp: [16:00 02/06/2026]
* Prompt:

```text
Bạn hãy chỉnh lại Requirement 2 thành dạng có thể đưa vào report. Em muốn có bảng overview 20 defects trước, sau đó là phần phân tích chi tiết từng defect. Mỗi defect cần có Year, System/Product, Category, Source, Description, Severity, Consequences, Solution/Mitigation và AI bias/hallucination instance.
```

---

## Prompt 08 - Bắt đầu Requirement 3

* Tool: ChatGPT
* Timestamp: [16:05 02/06/2026]
* Prompt:

```text
Em làm tiếp Requirement 3. Bạn hãy giúp em chọn một sản phẩm vật lý dễ test ở nhà để làm bài. Em muốn chọn chuột máy tính. Hãy thiết kế cho em 15 test cases theo đúng format Objective, Input, Steps, Expected Result, Actual Result và Verdict.
```

---

## Prompt 09 - Thêm video thực thi và defect cho sản phẩm vật lý

* Tool: ChatGPT
* Timestamp: [17:00 02/06/2026]
* Prompt:

```text
Với 15 test cases cho chuột máy tính, bạn hãy giúp em chọn ít nhất 5 test cases phù hợp để quay video demo dưới 60 giây. Đồng thời hãy gợi ý cách ghi nhận defects trong quá trình test và cách log chúng thành GitHub Issues theo yêu cầu HW01.
```

---

## Prompt 10 - Xác định edge case AI bỏ sót

* Tool: ChatGPT
* Timestamp: [17:16 02/06/2026]
* Prompt:

```text
Trong Requirement 3, đề yêu cầu ít nhất 3 test cases phải là edge cases mà AI tool không tìm ra. Bạn hãy giúp em xác định các edge cases thực tế cho chuột máy tính mà AI thường bỏ sót, giải thích vì sao AI bỏ sót chúng, và viết phần Student-added value cho từng edge case.
```

---

## Prompt 11 - Tạo bản nháp test case cho chuột máy tính

* Tool: ChatGPT
* Timestamp: [17:30 02/06/2026]
* Prompt:

```text
Generate 15 test cases for testing a computer mouse. Include objective, input, steps, expected result, actual result, and verdict.
```

---

## Prompt 12 - Mindmap vai trò QA/QC hoặc quy trình ISTQB

* Tool: ChatGPT
* Timestamp: [17:55 02/06/2026]
* Prompt:

```text
Bạn hãy tạo cho em một mindmap về QA/QC role hoặc ISTQB testing process để làm phần CLO G9.1 của HW01. Mindmap cần có các nhánh như test planning, test analysis, test design, test execution, defect reporting, test closure, QA/QC responsibilities và AI-assisted testing roles. Trình bày bằng Markdown để em có thể chuyển thành hình ảnh.
```

---

## Prompt 13 - Tìm lỗi trong mindmap do AI tạo

* Tool: ChatGPT
* Timestamp: [19:00 02/06/2026]
* Prompt:

```text
Bạn hãy review lại mindmap QA/QC hoặc ISTQB testing process vừa tạo và chỉ ra ít nhất 3 điểm sai, thiếu hoặc dễ gây hiểu lầm theo kiến thức Software Testing/ISTQB. Với mỗi lỗi, hãy giải thích vì sao sai hoặc chưa đủ và đưa ra phiên bản sửa đúng hơn.
```

---

## Prompt 14 - Chuẩn bị checklist nộp HW01

* Tool: ChatGPT
* Timestamp: [19:05 02/06/2026]
* Prompt:

```text
Dựa trên file HW01, bạn hãy tổng hợp giúp em toàn bộ những file cần nộp trong file zip. Hãy ghi rõ tên file zip đúng format, các file bên trong, những phần bắt buộc trong main report PDF, các evidence cần có, link YouTube, GitHub Issues, prompt log, AI Audit Report, AI Disclosure Form, AI Privacy Checklist và self-assessment.
```

---

## Prompt 15 - Viết lại nhật ký prompt

* Tool: ChatGPT
* Timestamp: [19:10 02/06/2026]
* Prompt:

```text
Bạn hãy viết lại Appendix A - Prompt Log cho em theo kiểu tự nhiên, giống như em và bạn đang làm việc chung từng bước để hoàn thành HW01. Nội dung prompt cần phù hợp với các phần em đã làm: hiểu đề, Requirement 1, Requirement 2, Requirement 3, mindmap, AI critique và checklist nộp bài.
```

---

## Prompt 16 - Xóa file nháp prompt log

* Tool: OpenAI Codex
* Timestamp: [22:20 02/06/2026]
* Prompt:

```text
Bản nháp bỏ đi, giữ bản thật và em sẽ trực tiếp chỉnh sửa trên bản thật nhé.
```

---

## Prompt 17 - Đổi main report sang Markdown và chèn screenshot việc làm

* Tool: OpenAI Codex
* Timestamp: [22:25 02/06/2026]
* Prompt:

```text
Bạn đổi Main Report viết bằng Markdown được không mà Markdown đó kèm theo từng ảnh trong mục Requirement 1 được không hay phải dùng LaTeX. Bổ sung 10 ảnh này vô thư mục job_screenshots rồi bổ sung vô file Main report.md nhé.
```

---

## Prompt 18 - Kiểm tra vị trí và độ đầy đủ của Requirement 2

* Tool: OpenAI Codex
* Timestamp: [23:14 02/06/2026]
* Prompt:

```text
Còn Requirement 2 thì sao, bạn đã làm chưa và nó ở đâu vậy?
```

---

## Prompt 19 - Kiểm tra link nguồn Requirement 2

* Tool: OpenAI Codex
* Timestamp: [23:38 02/06/2026]
* Prompt:

```text
Bạn check kỹ lại và mở mấy link bạn để trong Requirement 2 nhé, có link nó bị lỗi 404 hoặc không mở được. Link S4, S6 bị lỗi nhé hãy sửa 2 link này cho em. Nội dung trong phần mỗi defect rồi bảng dưới đúng tương ứng với từng link bạn sửa chưa?
```

---

## Prompt 20 - Chỉnh test case chuột trong Requirement 3

* Tool: OpenAI Codex
* Timestamp: [10:54 03/06/2026]
* Prompt:

```text
Đây là 15 test case cho chuột máy tính. Đây là TC03 - Left click. Expected result là hệ thống phản hồi đúng khi em click trái vào folder này. Em sẽ click trái vào folder. Actual result là folder đã được chọn/mở đúng cách. Verdict: Pass. Bạn hãy trình bày chỉnh sửa Requirement 3 lại nhé.
```

---

## Prompt 21 - Thêm actual result và video evidence cho Requirement 3

* Tool: OpenAI Codex
* Timestamp: [11:00 03/06/2026]
* Prompt:

```text
Cái Requirement 3 cái actual result bạn điền cho em luôn đi, rồi 5 test case đầu có các evidence là các video này theo thứ tự từ 1 đến 5: https://youtube.com/shorts/3CMP3iIHS9o, https://youtube.com/shorts/b6bOtu37ajE, https://youtube.com/shorts/EFAPSEX-c2E, https://youtube.com/shorts/p8jwLAn1duk, https://youtube.com/shorts/z_PfUJBP1SM. Tạo 1 file txt chứa 5 video YouTube cho test case 1 đến 5. Kiểm tra mục Requirement 3 đúng yêu cầu trong ảnh hay chưa. Mục bảng test case summary bỏ cột Có nên quay hay không, đổi thành Đã quay thì tích dấu xanh 5 test case đầu, còn lại tích dấu x.
```

---

## Prompt 22 - Dịch report Markdown sang tiếng Việt và xóa report DOCX

* Tool: OpenAI Codex
* Timestamp: [11:32 03/06/2026]
* Prompt:

```text
Sửa lại report file .md thay từ tiếng Anh sang tiếng Việt nhé, còn file report doc xoá đi nhé. Sao PDF thấy chuyển qua tiếng Việt rồi mà .md vẫn chưa vậy?
```

---

## Prompt 23 - Kiểm tra phần AI Collaboration Protocol

* Tool: OpenAI Codex
* Timestamp: [13:23 03/06/2026]
* Prompt:

```text
Còn phần AI Collaboration Protocol là sao, nó đã có hay chưa?
```

---

## Prompt 24 - Kiểm tra yêu cầu AI Audit Report

* Tool: OpenAI Codex
* Timestamp: [13:27 03/06/2026]
* Prompt:

```text
Bạn kiểm tra xem phần AI Audit Report đã có hay chưa. Làm sao để có ảnh output AI thật với sửa mấy file DOCX trong đó thành file .md nhé.
```

---

## Prompt 25 - Chỉnh AI_02 Audit Report với evidence output AI thật

* Tool: OpenAI Codex
* Timestamp: [14:10 03/06/2026]
* Prompt:

```text
Chỉnh lại file AI_02_Audit_Report.md theo yêu cầu: phần AI output phải có full AI output hoặc screenshot AI output có viền đỏ và annotation, không chỉ summary. Nếu dùng screenshot thì dẫn tới evidence/ai_screenshots. Prompt + tool cũng cần rõ hơn và dẫn tới Appendix_A_Prompt_Log.md.
```

---

## Prompt 26 - Đổi tên ảnh AI screenshot và kiểm tra Audit 02

* Tool: OpenAI Codex
* Timestamp: [14:45 03/06/2026]
* Prompt:

```text
Em mới lưu 5 ảnh trong ai_screenshots, bạn đổi tên ảnh rồi check trình bày trong AI_02_Audit_Report.md nhé.
```

---

## Prompt 27 - Kiểm tra AI Critique và Mandatory Disclosure

* Tool: OpenAI Codex
* Timestamp: [15:51 03/06/2026]
* Prompt:

```text
Yêu cầu AI Critique 200-300 words đã có hay chưa? Phần Mandatory Disclosure đã có chưa?
```

---

## Prompt 28 - Kiểm tra artifact chống gian lận AI

* Tool: OpenAI Codex
* Timestamp: [15:59 03/06/2026]
* Prompt:

```text
Trong thư mục đã làm cho yêu cầu Mandatory Disclosure và Anti-AI-Cheat mechanisms trong ảnh hay chưa?
```

---

## Prompt 29 - Tạo GitHub repo và evidence issue

* Tool: OpenAI Codex
* Timestamp: [16:24 03/06/2026]
* Prompt:

```text
Còn cái link GitHub như đề file HW01 nói thì sao? Bạn làm giúp em nhé, account em là thangak18.
```

---

## Prompt 30 - Đặt GitHub public và kiểm tra rubric

* Tool: OpenAI Codex
* Timestamp: [16:53 03/06/2026]
* Prompt:

```text
Để GitHub chế độ public nhé, rồi xem thư mục này đủ yêu cầu trong 2 ảnh trên chưa: Markdown, Git commit log, bảng tự chấm điểm, AI Audit, AI Critique, 5 videos YouTube links.
```

---

## Prompt 31 - Sắp xếp lại thư mục nộp bài cuối

* Tool: OpenAI Codex
* Timestamp: [17:10 03/06/2026]
* Prompt:

```text
Đây là cấu trúc thư mục nộp bài của em: 23127259_HW01_AI_085.zip với HW01_Main_Report.pdf/md, checklist xlsx, prompt log, mindmap, AI_02, AI_03, AI_05, GitHub repo/issue file, video links txt, device photo, GitHub issues screenshot và evidence/job_screenshots, evidence/ai_screenshots. Bạn sửa lại, file nào thừa thì xoá rồi đổi tên cho đúng, chưa cần zip liền nhé.
```

---

## Prompt 32 - Cập nhật prompt log và cách xưng hô

* Tool: OpenAI Codex
* Timestamp: [17:20 03/06/2026]
* Prompt:

```text
File Appendix_A_Prompt_Log.md bổ sung thêm mấy prompt em có trò chuyện với bạn hôm nay và hôm qua nhé, rồi đổi cách xưng hô trong các file sang "em" nhé.
```
