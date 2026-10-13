# PROJECT HANDOVER — Ôn thi vào 10 chuyên Hóa

## 1. Mục tiêu
- Tài liệu LaTeX ôn tuyển sinh lớp 10 chuyên Hóa, bám YCCD KHTN/Hóa học lớp 8–9; Lâm Đồng là trục chính, đề tỉnh/trường khác để nhận diện mục tiêu và độ phân hóa.
- Lời văn học sinh: tiếng Việt tự nhiên, rõ, đúng mức lớp 9. Backward-design là logic biên soạn, không cần hiện thành thuật ngữ trong bài học.
- Ưu tiên kỹ năng hóa học, dữ kiện thực tế, thí nghiệm và bài toán nhiều bước; tránh liệt kê mẹo/dạng toán rời rạc.

## 2. Repo và trạng thái
- Repo: https://github.com/xkplitrz/tai_lieu_on_chuyen ; branch chính: main.
- HEAD lúc lập handover: ff00f44167b438186c6b0829714f9a32bc3e5216 — “Sửa để in toàn bộ chuyên đề”. Luôn fetch/refetch trước khi sửa.
- Đã có Chuyên đề 1–7; chưa có Chuyên đề 8 trở đi.
- Kế hoạch toàn khóa khoảng 50 buổi; đã chốt gần đây: Chuyên đề 5 = 8 buổi, 6 = 6 buổi, 7 = 4 buổi. Kiểm tra lịch tổng trước khi chốt lại tổng số buổi.

## 3. Cấu trúc repo
- main.tex: bìa, chọn bản học sinh, bật/tắt chuyên đề, gọi các file phần bằng input.
- preamble.tex: packages, font/kiểu trang, toggle, môi trường trình bày, macro bangmol.
- data/:
  - Chuyên đề 1: buoi01–buoi04, baitap_chuyende.
  - Chuyên đề 2: cd02_01–cd02_04, baitap_chuyende2.
  - Chuyên đề 3: cd03_01–cd03_07, cd03_bt_cungco, cd03_bt_tonghop, baitap_chuyende3.
  - Chuyên đề 4: cd04_01, cd04_02, baitap_chuyende4.
  - Chuyên đề 5: cd05_01–cd05_08, baitap_chuyende5.
  - Chuyên đề 6: cd06_01–cd06_06, baitap_chuyende6.
  - Chuyên đề 7: cd07_01–cd07_04, baitap_chuyende7.
  - data/assets/: logo và hình thí nghiệm/đồ thị. Không đổi tên hoặc xóa trước khi tìm hết tham chiếu includegraphics.
  - Các file de_nangluong_*, de_tocdo_*, loigiai_* cũng có trong repo; không xóa chỉ vì chưa thấy được gọi trực tiếp trong main.tex.
- Repo hiện theo dõi .texpadtmp/main.synctex(busy), có vẻ là file tạm. Kiểm tra trước khi dọn; không xóa nếu chưa chắc không được dùng.
- Bìa chưa khớp bản tổng: main.tex đang bật tất cả chuyên đề nhưng TenChuyenDe vẫn ghi “NĂNG LƯỢNG VÀ TỐC ĐỘ PHẢN ỨNG”. Chốt tiêu đề trước khi phát hành.
- YCCD gốc Chuong trinh Hoa hoc 8 va 9.docx chưa nằm trong cây repo được kiểm tra; lấy lại nguồn khi cần đối chiếu chi tiết.

## 4. Tiến độ
- 1. Công cụ định lượng trong hóa học — mol, PTHH, chất hết/dư, hiệu suất/độ tinh khiết, dung dịch.
- 2. Năng lượng và tốc độ phản ứng — nhấn mạnh năng lượng/nhiên liệu; không lặp phần năng lượng ở Chuyên đề 6.
- 3. Acid–base–pH–oxide–muối — phản ứng, chuẩn độ, chuỗi, nhận biết, định lượng.
- 4. Phân bón hóa học — dinh dưỡng N/P/K/NPK, hàm lượng, muối ammonium + base, pH đất, môi trường.
- 5. Kim loại và tài nguyên khoáng sản — tính chất/dãy hoạt động, bài toán kim loại, dữ kiện gián tiếp/hệ ẩn, quặng/luyện kim, gang–thép, đá vôi/silicate.
- 6. Carbon, hydrocarbon và nhiên liệu — CTPT/CTCT, cháy, sản phẩm cháy, xác định hydrocarbon, alkene, LPG; không lặp năng lượng của Chuyên đề 2.
- 7. Ethylic alcohol – Acetic acid – Ester — độ cồn, phản ứng acid, giấm/chuẩn độ, ester hóa và thí nghiệm. Đã thêm mục Bài tập mục tiêu với câu gắn nguồn Lâm Đồng, An Giang, Đắk Lắk, Ninh Bình, Quảng Ninh 2026; các bài phỏng theo phải ghi rõ. Kiểm tra lại nguyên văn và đáp án với ảnh đề gốc trước bản phát hành.
- Dự kiến tiếp: Chuyên đề 8 lipid/chất béo, carbohydrate, protein; Chuyên đề 9 polymer; sau đó audit và bố trí bài tích hợp/ôn tổng kết.

## 5. Backward-design — bắt buộc
1. Audit kho đề tuyển sinh trước khi lập dàn ý hoặc viết LaTeX.
2. Chọn bài tập mục tiêu nguyên văn từ đề thật trước; từ bài đó suy ra kỹ năng cần dạy.
3. Mục tiêu khoảng 5–10 bài nguyên văn/chuyên đề nếu kho có đủ. Nếu tìm được ít hơn, báo đúng số lượng/lý do; không tự chế rồi gắn nguồn giả.
4. Đọc ảnh/scan gốc bằng mắt khi có thể; OCR chỉ hỗ trợ, không thay ảnh. Lời giải chỉ giúp kiểm tra cách hiểu, không thay nguồn đề.
5. Từ bài mục tiêu suy ra kỹ năng → dàn ý → lý thuyết/ví dụ → bài củng cố → bài luyện kỹ năng → bài mục tiêu/tổng hợp.
6. Nếu ghi “Trích nguyên văn”, giữ nguyên câu chữ, số liệu, phương án, đơn vị và lệnh hỏi. Đã sửa/đơn giản hóa thì ghi “Phỏng theo”.
7. Không viết chương mới trước khi người dùng đồng ý với kết quả audit và dàn ý.

## 6. Quy tắc LaTeX
- Dùng LuaLaTeX; compile sau mỗi đợt sửa. Kiểm tra lỗi fatal, Overfull hbox, đường dẫn ảnh, tràn bảng/sơ đồ và đáp số.
- Giữ phong cách preamble.tex; không viết lại header/footer, bìa, watermark, màu, font hay môi trường dùng chung nếu chưa có lý do và kiểm tra hồi quy.
- Công thức/PTHH dùng \ce{...}; đại lượng/đơn vị dùng \SI{...}{...} theo phong cách file hiện có.
- Môi trường chính: vidu, loigiai, ghinho, notechem, tuluyen, loigiaiBT, \dapso{...}, \source{...}, tasks.
- Câu ngắn dùng tasks(2) hoặc số cột phù hợp; câu/ý dài dùng enumerate/itemize. Đừng ép đoạn văn dài vào tasks.
- Lời giải định lượng vẫn theo tư duy chung: số mol → PTHH/sơ đồ → giá trị trung gian/hệ → đại lượng hỏi. Nhưng từ Chuyên đề 4 trở đi, trong lời giải mẫu **không ghi tiêu đề “Bước 1/2/3/4”**; viết thẳng phép tính/lập luận và kết thúc bằng câu “Vậy, …”. Phần lý thuyết có thể dạy quy trình giải, không lặp nhãn bước trong mỗi lời giải.
- Bảng lượng chất dưới PTHH bắt buộc dùng macro \bangmol{n}{<dòng phương trình>}{<dòng lượng chất>} trong preamble.tex; không dùng array để đặt hệ số/số mol dưới PTHH.
  - n là số cột thật, không cố định. Mỗi chất, dấu +, và mũi tên chiếm một cột riêng; dòng lượng chất phải cùng số cột.
  - A + B -> C + D thường 7 cột; phản ứng dài tăng lên 9, 11, 13… cột theo số ô.
  - Không gộp nhiều chất trong một ô, ví dụ tránh \ce{ZnCl2 + H2} thành một ô; điều này làm lượng chất canh lệch.
  - Macro tự giảm cỡ chữ/khoảng cách khi nhiều cột; vẫn phải xem PDF. Nếu tràn, chia dòng/sơ đồ hợp lý, không khai sai số cột.
  - array/aligned vẫn có thể dùng cho hệ phương trình; “không dùng array” chỉ áp dụng cho bảng lượng chất dưới PTHH.
- Không chèn Markdown/HTML vào .tex; chỉ LaTeX.
- BanHocSinh: hiện lời giải ví dụ, ẩn nguồn/đáp số/lời giải bài tự luyện. BanGiaoVien: hiện đủ nguồn, đáp số, lời giải bài tập. Biết rõ đang compile chế độ nào.
- Toggle hiện có ChiChuyenDe{1}…ChiChuyenDe{7}, TatTatCaChuyenDe, BatChuyenDe{n}, TatCaChuyenDe. Khi test riêng, hoàn nguyên lựa chọn trước commit nếu không định đổi mặc định.

## 7. Quy tắc bài tập và lời giải
- Bài tập mục tiêu tuyển sinh là đích cuối của mỗi chuyên đề, không phải phần trang trí. Bài tập tự tạo không được thay thế toàn bộ câu đích.
- Tổ chức tự nhiên theo Củng cố → Bài tập tổng hợp/kỹ năng → Bài tập mục tiêu.
- Tôn trọng YCCD/lớp 9. Đề ngoài tỉnh có thể vượt phạm vi; chỉ lấy phần phù hợp làm lõi hoặc ghi rõ mở rộng.
- Dùng đơn vị lớn (kg, tấn, L, m³…) trong bối cảnh sản xuất/thực tế khi phù hợp; không hạ mọi bài thành số nhỏ.
- Giữ nhất quán phương pháp định lượng; không tự tạo “phương pháp dạng toán” mới nếu chỉ cần dùng kỹ năng đã học.
- Kiểm tra độc lập đáp số, hệ số PTHH, hệ phương trình, hiệu suất/độ tinh khiết và chiều sai số thực nghiệm.

## 8. Python và công cụ
- Cây repo hiện **không có file .py hoặc script Python**; dự án hiện là tài liệu LaTeX. Không tự ý thêm Python/dependency hoặc đổi pipeline nếu chưa có yêu cầu.
- Nếu thật sự cần Python sau này, tách vào thư mục riêng (ví dụ scripts/), ghi rõ cách chạy/dependency, không để file sinh ra/cache trong data/, và trao đổi trước khi đổi kiến trúc.

## 9. Git và an toàn chỉnh sửa
- Commit message luôn bằng tiếng Việt, mô tả đúng thay đổi.
- Fetch và kiểm tra HEAD trước mỗi lần ghi; không dùng SHA/parent cũ.
- Trước thao tác local: git status; git fetch origin; git log --oneline --left-right --graph main...origin/main.
- Nếu branch diverge, không cố git pull --ff-only; xác định commit local/remote rồi mới rebase hoặc giữ thay đổi. Không dùng reset --hard/restore/xóa file khi chưa xác minh thay đổi local có cần giữ.
- Sau sửa: compile chuyên đề bị ảnh hưởng; xem diff; kiểm tra mọi file input/ảnh; commit gọn, không đưa file tạm vào commit.
- Không xóa/đổi tên file cũ, tái cấu trúc thư mục hoặc thay macro chung khi chưa tìm hết tham chiếu và compile hồi quy.

## 10. Ưu tiên tiếp theo
- Chuyên đề 8: audit đề trước, chọn câu nguyên văn làm mục tiêu, chốt dàn ý rồi mới viết.
- Quay lại audit Chuyên đề 1–6 để bổ sung mục tiêu từ đề thật như Chuyên đề 7; phân biệt rõ nguyên văn/phỏng theo.
- Rà soát nguyên văn và đáp án tất cả câu đã gắn nhãn “Trích nguyên văn” trong Chuyên đề 7 bằng ảnh gốc.
- Chốt tiêu đề bìa trước khi biên dịch/phát hành bản tổng.
