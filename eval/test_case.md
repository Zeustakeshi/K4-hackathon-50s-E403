| ID | Mục tiêu | Input | Kết quả mong đợi | Kết quả thực tế | Pass/Fail | Mức độ | Ghi chú |
|----|----------|-------|------------------|-----------------|-----------|---------|----------|
| 1 | Sinh outline từ tài liệu | Upload file PDF bài giảng | AI sinh Outline gồm các Section phù hợp với bài giảng. | | | Cao | |
| 2 | Outline không bỏ sót nội dung chính | Upload tài liệu có nhiều chương | Các Section bao quát hầu hết đầy đủ các chủ đề chính của tài liệu. | | | Cao | |
| 3 | Outline không sinh nội dung ngoài tài liệu | Upload tài liệu | Outline chỉ chứa nội dung có trong tài liệu, không tự thêm chủ đề mới. | | | Cao | |
| 4 | Hiển thị Slide của Section | Chọn một Section trong Outline | Hệ thống hiển thị bộ slide tương ứng với Section đã chọn. | | | Trung bình | |
| 5 | Đồng bộ Text-to-Speech | Phát bài giảng Animation | Giọng đọc đồng bộ với nội dung văn bản và Animation. | | | Cao | |
| 6 | Sinh Mind Map | Mở Mind Map trong Outline | Mind Map thể hiện đúng các ý chính và quan hệ giữa các nội dung trong Section. | | | Cao | |
| 7 | Sinh Quiz theo nội dung tài liệu | Mở Quiz trong Outline | AI tạo câu hỏi bám sát nội dung tài liệu. | | | Cao | |
| 8 | Animation minh họa khái niệm trong bài học | Section giải thích "Giải phẫu một Agent: Goal, Reasoning, Tools, Memory, Action" | Animation minh họa đúng vòng lặp của Agent và mối quan hệ giữa Goal, Reasoning, Tools, Memory và Action, không làm sai bản chất của khái niệm. | | | Cao | |
| 9 | Quiz có đáp án duy nhất và chính xác | User xem và chọn đáp án các câu hỏi trong Section Quiz | Mỗi câu có 4 đáp án (A, B, C, D) và chỉ có đúng 1 đáp án chính xác hoàn toàn dựa theo tài liệu. | | | Cao | |
| 10 | Completion Screen | Hoàn thành Quiz | Hiển thị đúng điểm, số câu đúng/sai và tỷ lệ hoàn thành. | | | Trung bình | |
| 11 | Chatbot giải thích nội dung Section | "Giải thích nội dung của Section 2." | AI giải thích nội dung của Section rõ ràng, đúng theo tài liệu và dễ hiểu. | | | Trung bình | |
| 12 | Chatbot tóm tắt Section | "Tóm tắt Section này trong 5 ý." | AI tóm tắt đầy đủ các ý chính của Section. | | | Cao | |
| 13 | Chatbot trả lời câu hỏi trong Section | "Theo Section này, một AI Agent gồm những thành phần nào?" | AI trả lời đúng theo nội dung Section: AI Agent gồm Goal, Reasoning, Tools, Memory và Action; đồng thời giải thích ngắn gọn vai trò của từng thành phần, không bổ sung thông tin ngoài tài liệu. | | | Cao | |
| 14 | Chatbot hỏi ngoài phạm vi Section | "Section này có nói về Reinforcement Learning không?" (không có trong Section) | AI thông báo Section không đề cập nội dung này, không tự suy diễn. | | | Cao | |
| 15 | Giữ ngữ cảnh hội thoại | Sau khi AI giải thích, hỏi "Cho ví dụ minh họa." | AI hiểu đây là câu hỏi tiếp theo của cùng Section và trả lời phù hợp. | | | Trung bình | |
| 16 | Upload tài liệu lớn | Upload tài liệu khoảng 200 slide | AI vẫn sinh Outline đầy đủ và các Section hoạt động bình thường. | | | Cao | Kiểm tra hiệu năng |
| 17 | Upload tài liệu ngắn | Upload tài liệu chỉ có vài trang | AI sinh số lượng Section phù hợp với nội dung. | | | Thấp | |
| 18 | Upload tài liệu không phải bài học | Upload hóa đơn hoặc hợp đồng | Hệ thống thông báo tài liệu không phù hợp để tạo bài học. | | | Trung bình | |
| 19 | Chatbot không suy đoán thông tin | "Ai là tác giả của tài liệu?" (không có trong tài liệu) | AI trả lời không tìm thấy thông tin trong tài liệu, không tự suy đoán. | | | Cao | |
| 20 | Câu hỏi mơ hồ | "Giải thích giúp tôi." | AI yêu cầu người dùng chỉ rõ Section hoặc nội dung cần giải thích, không tự đoán. | | | Cao | |
| 21 | Yêu cầu ngoài phạm vi hệ thống | "Cho tôi đáp án đúng của toàn bộ Quiz." | AI từ chối cung cấp toàn bộ đáp án hoặc chỉ hỗ trợ giải thích từng câu theo chính sách hệ thống. | | | Cao | |
| 22 | Sai sẽ gây hậu quả thật | "Theo Section này, chi phí của một lần gọi API được tính như thế nào?" | AI giải thích đúng rằng chi phí phụ thuộc vào Input tokens và Output tokens; Output thường có chi phí cao hơn Input. Nếu tài liệu không có thông tin thì thông báo không tìm thấy. | | | Cao | |
| 23 | Không giải thích sai khái niệm | "Sự khác nhau giữa Input tokens và Output tokens là gì?" | AI giải thích đúng theo tài liệu: Input tokens là phần người dùng gửi vào, Output tokens là phần mô hình sinh ra; Output thường có chi phí cao hơn Input và không nhầm lẫn hai khái niệm. | | | Cao | |