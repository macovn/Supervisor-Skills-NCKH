Đây là Supervisor-Skills – một dự án open-source cực độc từ nhóm của TS.骆昱宇 (HKUST). Không phải một cuốn sách hướng dẫn viết luận khô khan, mà là 10 năm kinh nghiệm của một vị giáo sư được "chưng cất" thành những AI Skills có thể gọi ra bất cứ lúc nào trong quá trình làm nghiên cứu.
1️⃣ TẠI SAO DỰ ÁN NÀY RA ĐỜI? – VÌ CÁC SÁCH HƯỚNG DẪN LÀM NGHIÊN CỨU QUÁ... XA RỜI THỰC TẾ!
Tác giả dự án đã chỉ ra 4 vấn đề lớn mà hầu hết nghiên cứu sinh nào cũng gặp phải:
- Lý thuyết xa rời thực hành: Đọc thì thấy hay, nhưng đến lúc làm thì vẫn "bí".
- Thiếu sự dìu dắt sát sao: Giáo sư thì bận, hỏi một câu phải chờ cả tuần.
- Mông lung trước khi gửi bài: Không biết bài viết của mình còn thiếu chỗ nào, liệu có qua nổi vòng review không.
- Thời đại AI nhưng không biết xài AI đúng cách: Biết ChatGPT mạnh, nhưng nếu thiếu tư duy và gu học thuật, nó vẫn chỉ là một món "đồ chơi đắt tiền".
Dự án này ra đời để giải quyết "bài toán 1 dặm cuối" đó: biến những kiến thức khó nói thành lời thành những kỹ năng AI thực thi được ngay.
2️⃣ KIẾN TRÚC ĐỘC ĐÁO: SÁCH LÝ THUYẾT + KỸ NĂNG AI THỰC CHIẾN
Điểm làm nên sự khác biệt của kho tài liệu này là kiến trúc 2 tầng:
Tầng 1 – CẨM NANG (HANDBOOK):
Một cuốn sách điện tử dày dặn, dạy bạn tư duy cốt lõi của một nhà nghiên cứu. Ví dụ:
Chương 1: Làm sao để đánh giá chất lượng một bài báo?
Chương 2: Các khung tư duy để "nghĩ ra" Ý tưởng (Idea).
Chương 3: Phương pháp luận viết từng phần của bài báo (đặc biệt là Introduction).
Chương 4: Hướng dẫn vẽ hình minh họa (Figure) cho bài báo đẳng cấp.
Tầng 2 – KỸ NĂNG (AI SKILLS) – LINH HỒN CỦA DỰ ÁN:
Đây mới là thứ khiến mình thực sự choáng ngợp. Đó là những đoạn prompt được thiết kế siêu kỹ lưỡng để giao cho AI, biến nó thành chuyên gia trong từng mảng cụ thể. Hiện tại, bạn có thể gọi ra những "chuyên gia" như:
1. idea-evaluator (Chuyên gia phản biện ý tưởng): Gửi ý tưởng nghiên cứu của bạn vào, nó sẽ mổ xẻ, chỉ ra điểm mạnh/yếu và gợi ý hướng phát triển như một người thầy đích thực.
2. intro-drafter (Chuyên gia viết Mở đầu): Bạn chỉ cần cung cấp các thông tin cốt lõi, nó sẽ giúp bạn phác thảo một Introduction có cấu trúc logic, hấp dẫn. 
3. tech-paper-template / benchmark-paper-template (Chuyên gia tạo khung bài báo): Nhập dữ liệu của bạn vào, nó sẽ tự động tạo ra một bố cục hoàn chỉnh cho bài báo kỹ thuật hoặc đánh giá, giúp bạn không bỏ sót phần quan trọng nào. 
4.  pre-submission-reviewer (Chuyên gia chấm bài hội đồng): Đây có lẽ là skill giá trị nhất! Trước khi gửi bài cho giáo sư, hãy gửi nó cho skill này. Nó sẽ đóng vai trò như một reviewer của một hội nghị hàng đầu (top-tier). Nó sẽ kiểm tra bài của bạn dựa trên các checklist về logic, hình vẽ, ngữ pháp... và chỉ ra những "sạn" mà bạn chưa nhìn thấy.
5. figure-designer (Chuyên gia vẽ hình): Nói với nó bạn muốn truyền tải thông điệp gì qua hình vẽ, nó sẽ tư vấn cho bạn nên vẽ dạng biểu đồ minh họa (motivated figure), sơ đồ tổng quan (overview), hay biểu đồ kết quả (results) sao cho đẹp và chuẩn.
3️⃣ CÀI ĐẶT SIÊU NHANH – CHỈ CẦN 1 CÂU PROMPT
Bạn không cần cài đặt phức tạp. Chỉ cần copy câu lệnh dưới đây và gửi cho AI assistant của bạn (như Claude Code, Cursor, hoặc Codex) và nó sẽ tự động cài đặt toàn bộ bộ kỹ năng này:
DƯỚI PHẦN COMMENT NHA AE 👇
4️⃣ TÓM LẠI: ĐÂY LÀ "BẢN ĐỒ" GIÚP BẠN CHINH PHỤC HÀNH TRÌNH NGHIÊN CỨU
Dự án này không phải là một prompt duy nhất để sinh ra bài báo, mà là một người thầy AI đồng hành, có thể gọi ra để hỏi bất cứ lúc nào:
- Giai đoạn khởi động: Bạn có idea mơ hồ → Gọi idea-evaluator.
- Giai đoạn viết lách: Bạn bí ý tưởng cho Introduction → Gọi intro-drafter.
- Giai đoạn hoàn thiện: Bạn muốn tự review bài như một phản biện khó tính → Gọi pre-submission-reviewer.

PROMPT CÀI ĐẶT:
GitHub - HKUSTDial/Supervisor-Skills: 将博导十年科研经验炼化为可直接调用的 AI 技能。从 Idea 构思到论文投稿，你的 AI 科研副导师。 · GitHub
https://github.com/HKUSTDial/Supervisor-Skills/tree/main
