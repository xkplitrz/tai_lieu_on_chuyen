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


## 13. Chuyển giao cho Claude và cấu hình Cursor — 13–15/10/2026

- Tạo PROJECT_HANDOVER.md làm bản hướng dẫn vào dự án: mục tiêu, cây thư mục, tiến độ, backward-design, LaTeX, macro \\bangmol, quy tắc Git và các việc còn tồn.
- Tạo PROJECT_LOG.md để lưu lịch sử quyết định theo phiên; chuẩn hóa Markdown để dễ đọc, ưu tiên các gạch đầu dòng.
- Thêm .cursorrules.txt và .cursorignore.txt để cung cấp chỉ dẫn cho Cursor. Đọc lại hai file này khi thay đổi workflow/agent.
- Thêm MEMORY.md làm ghi chú ngắn cho agent; tránh để nội dung mâu thuẫn với PROJECT_HANDOVER.md và nhật kí này.
- Bổ sung ảnh đề tuyển sinh vào de_vao_chuyen/ (nhiều tỉnh/trường, chủ yếu ảnh trang đề). Đây là nguồn gốc để audit; không chỉ dựa vào OCR hoặc đáp án.
- Xóa file tạm .texpadtmp/main.synctex(busy) khỏi Git trong commit chuyển giao; không tái thêm file build/tạm vào repo.
- Commit xác nhận: 6aaf68e (thêm PROJECT_LOG.md); fe56980 (chỉnh định dạng nhật kí); 7d102d0 (thêm tài liệu bàn giao); 0faa59b (chuẩn bị bản in có giáo án và chuyển giao cho Claude, bổ sung quy tắc Cursor, ghi nhớ agent và ảnh đề).

## 14. Trạng thái tại lần cập nhật nhật kí — 18/10/2026

- Nhánh làm việc chính vẫn là main; commit gần nhất đã xác minh trước lần cập nhật này là 0faa59b — “Thay đổi để in lại bản có giáo án và chuyển giao cho Claude” (15/10/2026 UTC).
- PROJECT_HANDOVER.md và PROJECT_LOG.md đều nằm ở gốc repo. Dùng cả hai khi mở dự án trong Cursor: handover để biết cách làm; log để biết vì sao các quyết định được chốt.
- Trạng thái Chuyên đề 7: đã thêm nhóm bài mục tiêu được gắn nguồn Lâm Đồng, An Giang, Đắk Lắk, Ninh Bình và Quảng Ninh 2026. Cần xác minh từng câu và đáp án từ ảnh gốc trước khi coi là bản phát hành; ghi “phỏng theo” nếu câu chữ không còn nguyên văn.
- Việc tiếp theo theo thứ tự:
  1. Audit kho đề cho Chuyên đề 8 trước khi chốt dàn ý; dự kiến chất béo/lipid, carbohydrate, protein.
  2. Bổ sung bài mục tiêu nguyên văn cho Chuyên đề 1–6 dựa trên audit thật, không gắn nguồn giả.
  3. Kiểm tra lại nguồn/đáp án Chuyên đề 7.
  4. Chốt tiêu đề bìa cho bản in toàn tài liệu và compile toàn bộ bằng LuaLaTeX.
- Lưu ý lịch sử: main.tex đã được sửa để in toàn bộ chuyên đề, nhưng handover trước đó ghi nhận tiêu đề bìa có thể vẫn mang tên Chuyên đề 2. Kiểm tra trực tiếp source hiện tại trước khi sửa; không dựa hoàn toàn vào ghi chú cũ.
- Chỉ cập nhật mốc ngày khi có thay đổi/phiên làm việc đáng kể. Phân biệt sự kiện xác minh từ commit với quyết định được chốt trong trao đổi nhưng chưa có commit.


## 15. Chuyên đề 8 — Lipid, carbohydrate và protein — 09/11/2026

- Audit YCCD và các trang đề gốc trước khi viết; chốt 6 buổi: lipid/chất béo; xà phòng hóa; glucose/saccharose; tinh bột/cellulose; protein; luyện tập tích hợp.
- Bổ sung 5 bài mục tiêu từ trang đề tuyển sinh đã xác minh:
  - Thái Nguyên 2026, Câu 1: dầu/mỡ thực phẩm so với dầu bôi trơn; sự cố tràn dầu và nguyên tắc ly tâm.
  - Cần Thơ 2026, Câu 6: sản xuất xà phòng từ mỡ động vật, có thành phần triglyceride và hiệu suất.
  - Phú Thọ 2026, Câu 5.2: chỉ số acid/ester hóa và sản xuất xà phòng; đề cung cấp định nghĩa hai chỉ số.
  - Lâm Đồng 2026, Câu 16: rơm rạ/cellulose → glucose → ethylic alcohol.
  - Ninh Bình 2026, Câu 5.2: đồ thị lên men glucose, xác định khoảng tốc độ lớn nhất, tốc độ trung bình và hiệu suất.
- Các file nội dung: cd08_01–cd08_05 và baitap_chuyende8. Toggle thứ 8: \ChiChuyenDe{8}.
- Chuyển hai bài carbohydrate (Lâm Đồng Câu 16 và Ninh Bình Câu 5.2) ra khỏi mục tiêu Chuyên đề 7 để tránh lặp; Chuyên đề 7 vẫn còn 7 bài mục tiêu khác.
- Không tìm thấy bài protein trực tiếp trong các trang đề chính thức đã xác minh; một số câu protein/peptide nằm ở phần tài liệu phụ trợ ngoài số trang đề chính thức nên không gắn nguồn nguyên văn.
- Kiểm tra lại bài Cần Thơ: khối lượng mỡ cần dùng xấp xỉ 370,83 kg (80% triglyceride, hiệu suất 90%); sửa số cột bảng phản ứng glucose–Ag2O thành 7 cột.
- Chưa xác nhận compile toàn chương trong môi trường local; cần compile Chuyên đề 8 và hồi quy Chuyên đề 7 trước khi phát hành.

## 16. Chuyên đề 8 — cập nhật dàn ý và WU8.1 — 09/11/2026

- Dàn ý mới được người dùng duyệt, giữ đúng 6 buổi 32–37:
  1. Buổi 32: Chất béo và phản ứng xà phòng hóa.
  2. Buổi 33: Glucose và saccharose.
  3. Buổi 34: Tinh bột và cellulose.
  4. Buổi 35: Bài toán carbohydrate và ứng dụng.
  5. Buổi 36: Protein.
  6. Buổi 37: Tổng hợp lipid – carbohydrate – protein.
- Dàn ý này thay thế cách chia buổi ở mục 15; các bài mục tiêu đã có cần được phân bổ lại theo sáu buổi mới, không tự động giữ nguyên thứ tự cũ.
- WU8.1: rà soát và cập nhật hai file hiện có để cùng tạo thành một buổi học logic:
  - \`data/cd08_01.tex\`: lipid, chất béo, cấu tạo, trạng thái tự nhiên, tính chất vật lí, vai trò và cách sử dụng.
  - \`data/cd08_02.tex\`: chuyển thành các subsection tiếp nối của Buổi 32; bổ sung xà phòng hóa, quy trình sản xuất, bài toán lượng nguyên liệu/sản phẩm/hiệu suất; giữ chỉ số acid và chỉ số ester hóa ở phần mở rộng.
- Đối chiếu Câu 6 Cần Thơ trên bản scan trang 5; sửa sự không thống nhất ở kết luận đáp số thành khoảng 370,83 kg. Ghi nguồn theo năm học 2026–2027.
- YCCD KHTN 8–9 về chất béo được dùng làm giới hạn nội dung: khái niệm/cấu tạo khái quát, trạng thái tự nhiên, tính chất vật lí, phản ứng xà phòng hóa, vai trò và sử dụng phù hợp.
- Giữ mapping Lâm Đồng 3.1, 3.2 theo dàn ý đã duyệt; trước khi đưa câu vào phần bài tập mục tiêu phải đối chiếu nguyên văn với ảnh đề trong \`de_vao_chuyen/LamDong_2026/\`.
- \`main.tex\` hiện vẫn input \`cd08_01\`–\`cd08_05\`; chưa thêm các file cho Buổi 35 và Buổi 37 khi nội dung chưa được biên soạn. Sau khi hai buổi này có file ổn định, cập nhật thứ tự input để phản ánh đủ sáu buổi.
- Đã cập nhật trên \`main\`: \`cd08_01\` (125c5ce), \`cd08_02\` (3e6a87f), \`baitap_chuyende8\` đáp số (f7eadab) và nhãn nguồn Cần Thơ (75a2bb7).
- Chưa chạy biên dịch LuaLaTeX trong phiên này; cần compile Chuyên đề 8 sau khi hoàn tất các file còn thiếu và kiểm tra hồi quy.

## 17. WU8.2 — Buổi 33: Glucose và saccharose — 10/11/2026

- Hoàn thiện \`data/cd08_03.tex\`: thành phần/công thức khái quát của carbohydrate; nguồn gốc, tính chất vật lí và vai trò của glucose/saccharose; phản ứng tráng bạc của glucose; lên men glucose; thủy phân saccharose; cách nhận biết glucose và saccharose.
- Nhấn mạnh tỉ lệ phản ứng tráng bạc: 1 mol glucose tạo 2 mol Ag; tỉ lệ này được dùng trong bài toán tráng gương.
- Đã đối chiếu ảnh gốc trang 3 Cần Thơ 2026–2027: Câu 4.2c nói về nước ép nho chín tác dụng với \`AgNO3/NH3\`, đun nóng, tạo bạc bám lên thành ống nghiệm. Đã đưa vào bài tập mục tiêu với nhãn trích nguyên văn.
- Cùng trang Cần Thơ, Câu 4.2d là phép thử iodine trên chuối xanh, thuộc tinh bột; chuyển mục tiêu này sang Buổi 34, không đưa vào Buổi 33.
- Bổ sung bài toán tráng $x$ gương từ 650 g glucose, diện tích 0,35 m²/gương, độ dày bạc 0,1 µm, hiệu suất 75%, khối lượng riêng Ag 10,49 g/cm³. Bản chữ trích từ tài liệu tập hợp đề; chưa đối chiếu trực tiếp scan gốc trong repo nên giữ nhãn “Phỏng theo Câu 5.1b, Lâm Đồng 2026–2027”. Đáp số độc lập: 585 g Ag tạo thành; 0,36715 g Ag/gương; tối đa 1593 gương.
- Giới hạn kiến thức theo YCCD KHTN 8–9: thành phần/công thức chung ở mức khái quát; công thức phân tử, trạng thái tự nhiên, tính chất vật lí; glucose tráng bạc và lên men; saccharose thủy phân trong acid/enzyme; vai trò và ứng dụng. Không mở rộng sâu sang cấu trúc dạng vòng hoặc cơ chế hữu cơ.
- Đã cập nhật \`data/cd08_03.tex\` và \`data/baitap_chuyende8.tex\`; chưa thêm/bớt input trong \`main.tex\`.
- Chưa compile toàn bộ Chuyên đề 8 trong phiên này. Đã chạy một kiểm tra LuaLaTeX tối giản cho các đơn vị SI và cú pháp phương trình mhchem đang dùng; kiểm tra này thành công. Cần compile cả chuyên đề sau khi hoàn tất các buổi còn lại.
- Commit WU8.2: \`cf91aad\` (lý thuyết Buổi 33), \`176c647\` (bài tập mục tiêu), \`dad7831\` (sửa ký hiệu công thức thể tích lớp bạc), \`667e420\` (nhật kí), \`d0559d4\` (bàn giao).

## 18. WU8.3 — Buổi 34: Tinh bột và cellulose — 10/11/2026

- Hoàn thiện \`data/cd08_04.tex\`: nguồn gốc và trạng thái tự nhiên; tính chất vật lí; so sánh tinh bột/cellulose; phản ứng iodine của hồ tinh bột; thủy phân tinh bột và cellulose; sự tạo thành, vai trò trong cây xanh và ứng dụng.
- Đã đối chiếu YCCD KHTN 8–9 ở phần carbohydrate: trạng thái tự nhiên/tính chất vật lí; thủy phân; phản ứng màu của hồ tinh bột với iodine; quan sát thí nghiệm; vai trò/ứng dụng và sự tạo thành trong cây xanh.
- Đã đối chiếu ảnh scan trang 3 Cần Thơ 2026–2027: Câu 4.2d mô tả nhỏ dung dịch cồn iodine lên lát cắt chuối xanh, bề mặt chuyển xanh tím. Bổ sung câu này vào bài tập mục tiêu, nhãn “Trích nguyên văn”.
- Thêm hai bài tự biên soạn: vận dụng phép thử iodine trên mẫu thực phẩm; viết phương trình thủy phân hoàn toàn tinh bột/cellulose và so sánh mức độ dễ thủy phân.
- Lâm Đồng 5.1a: chưa đối chiếu được ảnh scan gốc trong phiên này; các trang scan nằm trong repo GitHub ở dạng JPEG mà công cụ đọc file hiện tại không giải mã được. Không tự dựng lại nội dung câu và không gắn nhãn trích nguyên văn. Giữ mapping này trong danh sách cần xác minh trước phát hành.
- Lưu ý phạm vi: không suy ra tinh bột và cellulose có cấu trúc/tính chất giống nhau chỉ vì cùng công thức dạng \`(C6H10O5)n\`; không dạy chi tiết cơ chế phản ứng màu iodine vượt yêu cầu.
- Đã cập nhật \`data/cd08_04.tex\`, \`data/baitap_chuyende8.tex\`, nhật kí và handover; chưa đổi \`main.tex\` vì file này đã input \`cd08_04\`.
- Chưa compile toàn bộ Chuyên đề 8 trong phiên này; sau khi hoàn tất Buổi 35–37 cần compile riêng Chuyên đề 8 và kiểm tra hồi quy Chuyên đề 7.
- Kiểm tra LuaLaTeX tối giản cho phần lý thuyết Buổi 34 (bảng \`tabularx\`, \`booktabs\`, công thức \`mhchem\`) và ba bài tập mới đều thành công. Đây không phải compile toàn bộ Chuyên đề 8; cần compile hồi quy sau khi đủ sáu buổi.

## 19. WU8.4 — Buổi 35: Bài toán carbohydrate và ứng dụng — 10/11/2026

- Thêm file \`data/cd08_baitoan.tex\` cho Buổi 35, đặt sau \`cd08_04\` và trước \`cd08_05\` (Protein) trong \`main.tex\`.
- Nội dung phương pháp: sơ đồ nhiều công đoạn; xử lí hàm lượng/purity; tỉ lệ khối lượng 162 g mắt xích tinh bột → 180 g glucose; 180 g glucose → 92 g ethanol; 180 g glucose → 216 g Ag; nhân hiệu suất khi đi xuôi, chia ngược hiệu suất khi tìm nguyên liệu; hiệu suất chung là tích các hiệu suất nối tiếp.
- Có ví dụ đầy đủ gạo → glucose → G-5 và bài tính ngược sắn → tinh bột → glucose → ethanol.
- Bổ sung trong \`baitap_chuyende8.tex\`: Lâm Đồng 5.1a (phỏng theo, G-5; 48.000 chai); hai bài tự biên soạn nhiều công đoạn/giải ngược; lời giải Câu 5.2 Ninh Bình năm học 2026–2027 (đồ thị cho glucose giảm 40 g/L từ 0 đến 60 h, ethanol cực đại 17,8 g/L; khoảng nhanh nhất 36–48 h; tốc độ trung bình 0,67 g/(L.h); hiệu suất 87,07%). Đã đối chiếu các giá trị đọc đồ thị với tài liệu hướng dẫn giải được tìm thấy.
- Rà soát phép tính: 1,8 t gạo × 75% tinh bột → 1.350 kg tinh bột; thủy phân lí thuyết 1.500 kg glucose; thực tế 1.200 kg; mỗi chai 500 mL chứa 25 g; tổng 48.000 chai. Bài toán ngược 46 kg ethanol cho ra 120 kg glucose, 135 kg tinh bột và 187,5 kg sắn.
- Sửa lỗi cấu trúc phát hiện từ WU8.2 trong \`baitap_chuyende8.tex\`: bài tráng gương thiếu phần source/answer/solution trước; câu Cần Thơ 4.2d bị lồng trong environment bài tráng gương. Hai bài đã được tách thành các \`tuluyen\` riêng; bài tráng gương được khôi phục trọn vẹn.
- Giữ nguồn Lâm Đồng 5.1a ở nhãn “Phỏng theo” theo cách ghi trong tài liệu bài tập cũ; chưa đổi sang nguyên văn.
- Đã cập nhật \`main.tex\`, \`data/baitap_chuyende8.tex\`, thêm \`data/cd08_baitoan.tex\`. Bài G-5 trùng trong \`data/baitap_chuyende.tex\` của Chuyên đề 1 đã được gỡ khỏi vị trí cũ để chỉ còn một bản ở Buổi 35.
- Đã audit thứ tự mở/đóng tất cả environment trong \`cd08_baitoan.tex\` và \`baitap_chuyende8.tex\`: cân bằng. LuaLaTeX tối giản cho mhchem, đơn vị SI (gồm \`\ton\`, \`\hou\`), số mũ khoa học và tabularx/booktabs thành công. Đây không phải compile toàn bộ Chuyên đề 8; chưa compile hồi quy Chuyên đề 7.
