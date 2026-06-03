# Appendix A - Prompt Log


## Prompt 01 - Understand HW01 requirements

* Tool: ChatGPT
* Timestamp: [15:30 01/06/2026]
* Prompt:

```text
Tôi vừa upload file HW01. Bạn hãy đọc kỹ file này rồi giải thích chi tiết bằng tiếng Việt cho tôi hiểu bài này yêu cầu làm gì. Hãy trình bày rõ từng requirement, cách nộp bài, các file cần nộp, cách dùng AI, phần AI Audit Report, AI Critique, Mandatory Disclosure và những lỗi có thể khiến bài bị 0 điểm.
```

---

## Prompt 02 - Clarify Requirement 1

* Tool: ChatGPT
* Timestamp: [15:35 01/06/2026]
* Prompt:

```text
Theo file HW01 thì Requirement 1 phải làm ở đâu? Tôi chưa hiểu phần QA/QC Job Market 2026+ là phải test trên hệ thống hay tìm job thật trên các website tuyển dụng. Bạn hãy giải thích giúp tôi và chỉ rõ tôi cần tìm những thông tin gì cho mỗi job.
```

---

## Prompt 03 - Find platforms and keywords for QA/QC jobs

* Tool: ChatGPT
* Timestamp: [15:37 01/06/2026]
* Prompt:

```text
Bạn hãy gợi ý cho tôi các website có thể tìm job QA/QC để làm Requirement 1. Tôi cần tìm 10 job trong vòng 60 ngày, trong đó có ít nhất 3 job liên quan AI, LLM hoặc automation-AI. Hãy gợi ý keyword tìm kiếm và format để tôi trình bày từng job trong report.
```

---

## Prompt 04 - Organize 10 job screenshots

* Tool: ChatGPT
* Timestamp: [15:45 01/06/2026]
* Prompt:

```text
Tôi đã gửi screenshot của 10 job tôi tìm được. Bạn hãy giúp tôi viết lại nội dung 10 job này theo format thống nhất gồm: Job title, Platform, Company, Job link, Posted date, Screenshot note, Job description summary, Required skills, Salary và AI Impact Analysis. Chỉ dùng đúng thông tin có trong screenshot, phần nào không thấy thì ghi Not disclosed hoặc Not shown in screenshot.
```

---

## Prompt 05 - Understand Requirement 2

* Tool: ChatGPT
* Timestamp: [15:50 02/06/2026]
* Prompt:

```text
Bây giờ tôi làm tiếp Requirement 2. Bạn hãy giải thích giúp tôi phần 20 Software Defects 2022-2026 yêu cầu làm gì. Tôi cần hiểu thế nào là software defect, phải tìm nguồn ở đâu, cần có những cột nào, và phần AI bias/hallucination instance phải viết như thế nào cho đúng yêu cầu của đề.
```

---

## Prompt 06 - Build list of 20 software defects

* Tool: ChatGPT
* Timestamp: [15:55 02/06/2026]
* Prompt:

```text
Bạn hãy giúp tôi tìm và trình bày 20 software defects trong giai đoạn 2022-2026 để làm Requirement 2. Trong đó phải có ít nhất 5 defects liên quan AI/LLM như hallucination, prompt injection hoặc bias. Với mỗi defect, hãy trình bày source link, description, severity, consequences, solution và một ví dụ AI có thể bị bias hoặc hallucinate khi giải thích defect đó.
```

---

## Prompt 07 - Refine Requirement 2 into report format

* Tool: ChatGPT
* Timestamp: [16:00 02/06/2026]
* Prompt:

```text
Bạn hãy chỉnh lại Requirement 2 thành dạng có thể đưa vào report. Tôi muốn có bảng overview 20 defects trước, sau đó là phần phân tích chi tiết từng defect. Mỗi defect cần có Year, System/Product, Category, Source, Description, Severity, Consequences, Solution/Mitigation và AI bias/hallucination instance.
```

---

## Prompt 08 - Start Requirement 3

* Tool: ChatGPT
* Timestamp: [16:05 02/06/2026]
* Prompt:

```text
Tôi làm tiếp Requirement 3. Bạn hãy giúp tôi chọn một sản phẩm vật lý dễ test ở nhà để làm bài. Tôi muốn chọn chuột máy tính. Hãy thiết kế cho tôi 15 test cases theo đúng format Objective, Input, Steps, Expected Result, Actual Result và Verdict.
```

---

## Prompt 09 - Add execution videos and defects for physical product

* Tool: ChatGPT
* Timestamp: [17:00 02/06/2026]
* Prompt:

```text
Với 15 test cases cho chuột máy tính, bạn hãy giúp tôi chọn ít nhất 5 test cases phù hợp để quay video demo dưới 60 giây. Đồng thời hãy gợi ý cách ghi nhận defects trong quá trình test và cách log chúng thành GitHub Issues theo yêu cầu HW01.
```

---

## Prompt 10 - Identify edge cases AI missed

* Tool: ChatGPT
* Timestamp: [17:16 02/06/2026]
* Prompt:

```text
Trong Requirement 3, đề yêu cầu ít nhất 3 test cases phải là edge cases mà AI tool không tìm ra. Bạn hãy giúp tôi xác định các edge cases thực tế cho chuột máy tính mà AI thường bỏ sót, giải thích vì sao AI bỏ sót chúng, và viết phần Student-added value cho từng edge case.
```

---

## Prompt 11 - Generate initial computer mouse test cases

* Tool: ChatGPT
* Timestamp: [17:30 02/06/2026]
* Prompt:

```text
Generate 15 test cases for testing a computer mouse. Include objective, input, steps, expected result, actual result, and verdict.
```

---

## Prompt 12 - QA/QC role or ISTQB process mindmap

* Tool: ChatGPT
* Timestamp: [17:55 02/06/2026]
* Prompt:

```text
Bạn hãy tạo cho tôi một mindmap về QA/QC role hoặc ISTQB testing process để làm phần CLO G9.1 của HW01. Mindmap cần có các nhánh như test planning, test analysis, test design, test execution, defect reporting, test closure, QA/QC responsibilities và AI-assisted testing roles. Trình bày bằng Markdown để tôi có thể chuyển thành hình ảnh.
```

---

## Prompt 13 - Find mistakes in AI-generated mindmap

* Tool: ChatGPT
* Timestamp: [19:00 02/06/2026]
* Prompt:

```text
Bạn hãy review lại mindmap QA/QC hoặc ISTQB testing process vừa tạo và chỉ ra ít nhất 3 điểm sai, thiếu hoặc dễ gây hiểu lầm theo kiến thức Software Testing/ISTQB. Với mỗi lỗi, hãy giải thích vì sao sai hoặc chưa đủ và đưa ra phiên bản sửa đúng hơn.
```

---

## Prompt 14 - Prepare HW01 submission checklist

* Tool: ChatGPT
* Timestamp: [19:05 02/06/2026]
* Prompt:

```text
Dựa trên file HW01, bạn hãy tổng hợp giúp tôi toàn bộ những file cần nộp trong file zip. Hãy ghi rõ tên file zip đúng format, các file bên trong, những phần bắt buộc trong main report PDF, các evidence cần có, link YouTube, GitHub Issues, prompt log, AI Audit Report, AI Disclosure Form, AI Privacy Checklist và self-assessment.
```

---

## Prompt 15 - Rewrite prompt log

* Tool: ChatGPT
* Timestamp: [19:10 02/06/2026]
* Prompt:

```text
Bạn hãy viết lại Appendix A - Prompt Log cho tôi theo kiểu tự nhiên, giống như tôi và bạn đang làm việc chung từng bước để hoàn thành HW01. Nội dung prompt cần phù hợp với các phần tôi đã làm: hiểu đề, Requirement 1, Requirement 2, Requirement 3, mindmap, AI critique và checklist nộp bài.
```
