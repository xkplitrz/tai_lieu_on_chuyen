# Nhật kí dự án — Ôn thi vào 10 chuyên Hóa

- Repo: `xkplitrz/tai_lieu_on_chuyen` — nhánh chính `main`.
- Mục đích file: ghi lại các quyết định và thay đổi lâu dài theo phiên; dùng cùng `PROJECT_HANDOVER.md` khi chuyển cho AI Agent khác.
- Mốc repo trước khi thêm nhật kí này: `7d102d0` — `Thêm tài liệu bàn giao dự án cho AI Agent` (13/10/2026, giờ Việt Nam buổi tối).
- Cách đọc: lịch sử commit xác minh được ghi theo mốc commit; quy tắc chốt trong trao đổi nhưng chưa có commit riêng được ghi như quyết định dự án, không nhất thiết gắn với một ngày chính xác.

## 1. Thiết lập ban đầu — 03/10/2026

- Khởi tạo tài liệu bằng LaTeX (`book`, A4, 12 pt); cấu trúc nội dung tách file trong `data/`, lắp ghép qua `main.tex` và `preamble.tex`.
- Viết Chuyên đề 1 — **Công cụ định lượng trong hóa học**:
  - `data/buoi01.tex`–`buoi04.tex`, `data/baitap_chuyende.tex`.
  - Trục kĩ năng: đổi đơn vị; mol và PTHH; chất hết/dư; hiệu suất/độ tinh khiết; dung dịch, nồng độ, khối lượng riêng, độ tan.
- Thêm logo trung tâm, định dạng ví dụ/lời giải/bài tự luyện, watermark và thiết lập để không đưa PDF/file rác vào Git.
- Chỉnh đáp số, đơn vị hecta, bài vận dụng cao; sửa lỗi cú pháp LaTeX trong bài pyrite.

## 2. Cấu hình bản học sinh/giáo viên — 04/10/2026

- Thêm cơ chế bật/tắt độc lập các thành phần đáp án, lời giải và nguồn.
- Bản học sinh ẩn đáp số/lời giải bài tập và nguồn; bản giáo viên hiện đầy đủ.
- Tiếp tục chỉnh phần dẫn nhập và thiết lập trình bày; giữ watermark.

## 3. Chuyên đề 2 — Năng lượng và tốc độ phản ứng — 12/10/2026

- Chốt trọng tâm là **năng lượng/nhiên liệu**, còn tốc độ phản ứng và chất xúc tác được giữ ở mức cốt lõi.
- Viết và chỉnh `cd02_01`–`cd02_04`, `baitap_chuyende2`.
- Bổ sung: sơ đồ giải bài toán năng lượng; hiệu suất và đun nóng; nhiên liệu hỗn hợp; so sánh trên cùng cơ sở; quy trình sản xuất; bài tốc độ phản ứng.
- Sắp xếp lại hệ bài tập theo mức độ/kĩ năng, rút gọn lời dẫn; đưa các bài từ đề có nguồn như Lâm Đồng 2026 (LPG, E10), Vĩnh Long 2026, Hà Nội/KHTN Hà Nội 2026, Điện Biên 2026, Đắk Lắk 2026.
- Quyết định phạm vi: Chuyên đề 6 sau này không lặp lại trọng tâm tính năng lượng đã xử lí ở đây.

## 4. Chuyên đề 3 — Acid, base, pH, oxide, muối — 12/10/2026

- Xây dựng các phần acid/base/pH, trung hòa, chuẩn độ, oxide, muối và phản ứng dung dịch, chuỗi phản ứng/nhận biết, định lượng.
- Các file chính: `cd03_01`–`cd03_07`, `cd03_bt_cungco`, `cd03_bt_tonghop`, `baitap_chuyende3`.
- Mở rộng phản ứng carbonate/bicarbonate, hiện tượng, chuỗi phản ứng; giữ phần thực hành chuẩn độ và mô phỏng.
- Viết lại lời giải định lượng theo phương pháp chung 4 phần: tính số mol → PTHH/sơ đồ → giá trị trung gian → đại lượng hỏi/kết luận.
- Chỉnh tên đề mục cho tự nhiên, gọn câu hỏi để tiết kiệm giấy; thêm toggle compile từng chuyên đề.
- Chốt nguyên tắc: không tạo các “dạng toán” độc lập nếu thực chất dùng chung một quy trình định lượng.

## 5. Chuyên đề 4 — Phân bón hóa học — 12/10/2026

- Tổ chức thành: dinh dưỡng/phân đạm–lân–kali–NPK; hàm lượng dinh dưỡng/đọc nhãn; phản ứng muối ammonium với base; pH đất; môi trường và sử dụng phân hợp lí.
- Các file: `cd04_01.tex`, `cd04_02.tex`, `baitap_chuyende4.tex`.
- Trọng tâm định lượng: phần trăm N, lượng phân theo nhu cầu dinh dưỡng/diện tích/hiệu suất; PTHH giải phóng `NH3`; độ tinh khiết và bài hệ hai ẩn.
- Thêm bài về ảnh hưởng của `NH4NO3`, `NH4Cl`, `(NH4)2SO4` tới pH đất, lấy Lâm Đồng 2026 làm trục. Nguồn đề phải ghi rõ là trích nguyên văn hay phỏng theo.

## 6. Chuyên đề 5 — Kim loại và tài nguyên khoáng sản — 12/10/2026

- Trước khi chốt dàn ý đã audit đề; đổi khung từ 7 lên **8 buổi** để không ép phần bài toán kim loại/luyện kim.
- Các phần: tính chất/dãy hoạt động; PTHH và chuỗi phản ứng; định lượng kim loại/dung dịch; dữ kiện gián tiếp và biện luận; tách kim loại; quặng/luyện kim nhiều công đoạn; gang–thép/hợp kim; đá vôi/silicate/tài nguyên.
- Các file: `cd05_01.tex`–`cd05_08.tex`, `baitap_chuyende5.tex`.
- Kĩ năng phân hóa phải có: hệ hai ẩn; chất hết/dư; thay đổi khối lượng chất rắn; dữ kiện gián tiếp qua chuỗi phản ứng; độ tinh khiết/hiệu suất quặng; hai nguồn nguyên liệu.
- Không bắt buộc bảo toàn electron ở lõi chương trình lớp 9; ưu tiên PTHH, số mol, lập hệ và biện luận hóa học.
- Đã có sự cố đồng bộ: remote `main` đã có Chuyên đề 5 nhưng local còn ở commit Chuyên đề 4; nguyên nhân do chưa fetch và có sửa local `main.tex`. Bài học: luôn `git fetch` trước khi so trạng thái; không reset/restore khi chưa xem diff.

## 7. Chuyên đề 6 — Carbon, hydrocarbon và nhiên liệu — 13/10/2026

- Audit trước khi viết; giữ 6 buổi: carbon/chu trình carbon/nhiên liệu hóa thạch; hợp chất hữu cơ và hydrocarbon; cháy; xác định công thức/hỗn hợp; ethylene/bromine/trùng hợp; dầu mỏ/khí thiên nhiên/LPG.
- Các file: `cd06_01.tex`–`cd06_06.tex`, `baitap_chuyende6.tex`.
- Không lặp lại bài năng lượng của Chuyên đề 2; ở đây khai thác CTPT/CTCT, PTHH cháy, `CO2`/`H2O`, tìm công thức và hệ hai ẩn, ethylene và nhiên liệu.
- Ban đầu một số bài bối cảnh Lâm Đồng LPG/E10 là bài phỏng theo; sau Chuyên đề 7, quy tắc toàn dự án được nâng lên: phải có “Bài tập mục tiêu” từ đề nguyên văn ở mỗi chương nếu kho đủ bài.

## 8. Chuẩn hóa lời giải và bảng lượng chất — 13/10/2026

- Theo yêu cầu, rà source Chuyên đề 4–6: bỏ các nhãn `Bước 1`, `Bước 2`, `Bước 3`, `Bước 4` trong lời giải mẫu; bỏ câu dẫn rỗng; giữ phép tính và lập luận trực tiếp, kết thúc bằng câu “Vậy, …”.
- Lưu ý: quy trình bốn phần vẫn được dùng để thiết kế/dạy cách giải, nhưng không lặp tiêu đề bước trong từng lời giải sau Chuyên đề 3.
- Bắt gặp bảng số mol đặt bằng `array` lệch cột. Tạo macro `\bangmol{n}{dòng phương trình}{dòng lượng chất}` trong `preamble.tex`.
- `n` là số cột động; mỗi chất, dấu `+` và mũi tên là các cột riêng. Không gộp `\ce{ZnCl2 + H2}` thành một ô; nếu có phản ứng dài thì tăng số cột và kiểm tra PDF. Macro dùng `tabular` bên trong.
- Quy tắc chính xác: dùng `\bangmol` cho bảng hệ số/số mol dưới PTHH; `array`/`aligned` vẫn phù hợp cho hệ phương trình toán học. Không biến “không dùng array” thành cấm mọi môi trường array trong tài liệu.
- Các commit: `4acf41d` (rút gọn lời giải Chuyên đề 4–5), `16849b7` (Chuyên đề 6), `1cf32f8` (macro/bảng lượng chất).

## 9. Chuyên đề 7 — Ethylic alcohol, acetic acid, ester — 13/10/2026

- Audit đề trước; bố trí 4 buổi: ethanol/độ cồn; acetic acid/giấm; định lượng giấm/chuẩn độ; ester hóa/thí nghiệm/hiệu suất.
- Các file: `cd07_01.tex`–`cd07_04.tex`, `baitap_chuyende7.tex`.
- Nhận xét sau bản đầu: bài tập quá đơn giản, chưa coi đề tuyển sinh là đích. Kiểm tra lại và xác định trước khi bổ sung, phần bài tập chưa có câu nào đánh dấu “trích nguyên văn”; các bài ban đầu chỉ ghi “phỏng theo”.
- Bổ sung mục **Bài tập mục tiêu** với các câu được ghi là trích nguyên văn từ Lâm Đồng 2026, An Giang 2026, Đắk Lắk 2026, Ninh Bình 2026 và Quảng Ninh 2026; thêm ảnh đồ thị lên men và sơ đồ chuẩn độ ở `data/assets/nb2026_lenmen_graph.jpg`, `data/assets/qn2026_vinegar_titration.jpg`.
- Có các commit: `da02801` (bản đầu Chuyên đề 7), `9c3af09` (thêm các bài mục tiêu), `0785c65` (bổ sung bài chuẩn độ Quảng Ninh).
- Việc còn lại quan trọng: rà từng câu gắn “trích nguyên văn”, đối chiếu ảnh gốc chữ/số liệu/phương án/đáp án; nếu có biên tập câu chữ phải đổi nhãn thành “phỏng theo”. Kiểm chứng lại đáp số/diễn giải độc lập trước khi phát hành.

## 10. Chế độ biên dịch toàn bộ — 13/10/2026

- Bổ sung toggle theo số chuyên đề 1–7: `\TatCaChuyenDe`, `\TatTatCaChuyenDe`, `\BatChuyenDe{n}`, `\ChiChuyenDe{n}`.
- Hiện `main.tex` được đổi để in toàn bộ chuyên đề; trong `preamble.tex`, `\TatCaChuyenDe` bật tất cả toggle mặc định.
- `main.tex` hiện vẫn để `\TenChuyenDe` là “NĂNG LƯỢNG VÀ TỐC ĐỘ PHẢN ỨNG” mặc dù in toàn bộ sách. Phải sửa tiêu đề bìa trước bản phát hành toàn bộ.
- Repo đã có `PROJECT_HANDOVER.md` cho AI Agent. Commit `7d102d0`.

## 11. Quy tắc vận hành đã chốt

- Backward-design bắt buộc: **audit kho đề → chọn câu mục tiêu nguyên văn → xác định kỹ năng → chốt dàn ý → viết nội dung và bài củng cố**. Không viết chương mới trước khi audit.
- Mỗi chuyên đề cố gắng có 5–10 bài nguyên văn từ đề tuyển sinh nếu dữ liệu cho phép. Thiếu thì báo thực tế; tuyệt đối không giả nguồn. Phân biệt nhãn “Trích nguyên văn” và “Phỏng theo”.
- Lâm Đồng là trục chính; đề hơn 30 tỉnh/trường dùng thêm để nhận diện độ phân hóa, không kéo toàn bộ kiến thức vượt YCCD vào lõi.
- Lời văn dành cho học sinh, tiếng Việt tự nhiên; không để lộ thuật ngữ nội bộ “backward-design” trong phần học sinh.
- Nhóm câu ngắn dùng `tasks(2)` khi phù hợp; mục dài/đa ý dùng `enumerate`/`itemize`. Đề mục cần rõ, tự nhiên, không lặp ý.
- Với mọi định lượng: dùng tư duy nhất quán của Chuyên đề 1 và 3, không chế phương pháp riêng cho mỗi “dạng”.
- Commit message bằng tiếng Việt. Refetch remote trước mọi lần ghi. Nếu branch diverge, xem `git status`, `git fetch`, `git log --left-right --graph main...origin/main` rồi quyết định rebase/giữ commit; không dùng `reset --hard` khi chưa xác minh.
- Compile chuyên đề bị ảnh hưởng bằng LuaLaTeX; xem lỗi fatal, warning, `Overfull \hbox`, bảng/công thức/ảnh và đáp số. Chỉ nói đã compile khi thật sự chạy compile.
- Repo hiện là dự án LaTeX; chưa thấy script `.py` trong cây repo được kiểm tra. Không tự thêm Python/dependency hoặc đổi cấu trúc nếu chưa có yêu cầu.

## 12. Việc nên làm tiếp

1. Chuyên đề 8: audit đề trước; nội dung dự kiến lipid/chất béo, carbohydrate, protein theo YCCD.
2. Audit lại Chuyên đề 1–6 để bổ sung phần **Bài tập mục tiêu nguyên văn**; Chuyên đề 7 là mẫu về cấu trúc nhưng cần xác minh nguồn kỹ.
3. Kiểm chứng nguyên văn/đáp án các bài mới của Chuyên đề 7 từ ảnh đề gốc.
4. Sửa tiêu đề bìa cho bản in toàn tài liệu; kiểm tra `.texpadtmp/main.synctex(busy)` đang được track để quyết định cách xử lí an toàn.
5. Compile bản toàn bộ, xem TOC, số trang, ảnh, phần ẩn/hiện theo `\BanHocSinh`/`\BanGiaoVien`, rồi mới phát hành.
