# SƠ ĐỒ MẠNG LƯỚI TRI THỨC TƯƠNG TÁC VIS.JS
## Chủ đề: Công nghệ Enzyme và Protein Trị liệu Tích hợp

Sơ đồ mạng lưới này được thiết kế theo cấu trúc phân cấp đa tầng kết hợp liên kết chéo hai chiều giúp kiểm soát toàn bộ bài học và các bẫy thi thường gặp.

```json
{
  "nodes": [
    {
      "id": 1,
      "label": "CÔNG NGHỆ ENZYME & PROTEIN",
      "level": 1,
      "group": "target",
      "tooltip": "💡 Anchor bài học: Xúc tác sinh học và tối ưu trị liệu",
      "detail": "<h3>Đại Cương Công Nghệ Enzyme - Protein</h3><p>Ứng dụng enzyme hoặc các chất xúc tác sinh học nhằm tạo ra các sản phẩm hoặc dịch vụ có giá trị cao trong công nghiệp và y dược đặc hiệu.</p>"
    },
    {
      "id": 2,
      "label": "BẢN CHẤT XÚC TÁC",
      "level": 2,
      "group": "structure",
      "tooltip": "💡 Bản chất hóa học kinh điển và hiện đại",
      "detail": "<h3>Bản Chất Xúc Tác Sinh Học</h3><ul><li><b>Protein:</b> Bản chất kinh điển của hầu hết enzyme trong tự nhiên do tính đa dạng cao.</li><li><b>Protein chứa amino acid không điển hình (noncanonical amino acid):</b> Mở rộng tính năng và nâng cao hiệu năng xúc tác.</li><li><b>Ribozyme (RNA):</b> Xúc tác phạm vi rất hẹp, chỉ cắt chính cơ chất RNA (như pre-RNA thành RNA trưởng thành).</li><li><b>Nhiệt động học:</b> Chỉ xúc tác phản ứng tự phát có biến thiên năng lượng tự do delta G dưới hoặc bằng 0. Muốn xúc tác phản ứng có delta G trên 0 phải ghép đôi với phản ứng thuận lợi khác.</li></ul>"
    },
    {
      "id": 3,
      "label": "CHỈ TIÊU THEO NGÀNH",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 So sánh dược phẩm, phân tích và công nghiệp",
      "detail": "<h3>Chỉ Tiêu Nhu Cầu Theo Ngành</h3><ul><li><b>Dược phẩm:</b> Quy mô sử dụng nhỏ (mg-g), yêu cầu độ tinh khiết tối đa (dạng tinh thể), bắt buộc thu từ nguồn người hoặc nguồn tái tổ hợp để tránh thải ghép, chi phí cao nhất.</li><li><b>Phân tích:</b> Quy mô nhỏ (mg-g), tinh khiết rất cao, dùng cho phản ứng in vitro nên không lo hệ miễn dịch tấn công, thu hoạch từ bất kỳ nguồn nào, chi phí trung bình.</li><li><b>Công nghiệp:</b> Quy mô lớn (hàng tấn), tinh khiết thô, chủ yếu từ enzyme ngoại bào của vi sinh vật dễ thu hoạch, chi phí sản xuất thấp.</li></ul>"
    },
    {
      "id": 4,
      "label": "ĐẶC TÍNH CHỌN LỌC CAO",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Chọn lọc vị trí và chọn lọc không gian",
      "detail": "<h3>Tính Chọn Lọc Vượt Trội</h3><ul><li><b>Chọn lọc theo vị trí nhóm hóa học (Regioselectivity):</b> Ví dụ C. antarctica lipase acyl hóa chính xác nhóm 5'-hydroxy của Purine (Nelarabine) với hiệu suất sản phẩm sạch trên 99,5%.</li><li><b>Chọn lọc không gian (Stereoselectivity):</b> Chỉ xúc tác trên một dạng đồng phân quang học duy nhất (Ví dụ S-naproxen chống viêm mạnh gấp 160 lần R-naproxen).</li></ul>"
    },
    {
      "id": 5,
      "label": "ĐỘ BỀN VÀ CHỊU TẢI",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Khả năng chịu nồng độ cơ chất cao và tái sử dụng",
      "detail": "<h3>Khả Năng Chịu Tải & Độ Bền</h3><ul><li><b>Savinase (sản xuất Abacavir):</b> Ví dụ điển hình chịu tải cơ chất cực cao lên đến 100 g/L (10% khối lượng) mà vẫn hoạt động bền bỉ ở nhiệt độ cao và môi trường kiềm cực mạnh từ pH 8 đến 12.</li><li><b>Penicillin G amidase (PGA):</b> Cố định đồng hóa trị lên chất mang giúp tái sử dụng bền bỉ tới 1.000 mẻ phản ứng chuyển hóa Penicillin G thành khung kháng sinh bán tổng hợp 6-APA.</li></ul>"
    },
    {
      "id": 6,
      "label": "PHẢN ỨNG TRONG DUNG MÔI",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Chuyển đổi chiều thủy phân và chiều tổng hợp",
      "detail": "<h3>Xúc Tác Trong Môi Trường Khan Nước</h3><ul><li><b>Hệ có nước:</b> Lipase xúc tác ưu tiên theo chiều thủy phân chất béo tạo glycerin và acid béo.</li><li><b>Hệ dung môi hữu cơ (aceton):</b> Đảo chiều xúc tác sang chiều tổng hợp. Tuy nhiên nước sinh ra từ phản ứng phụ lập tức tạo cân bằng động thủy phân.</li><li><b>Hệ khan nước có hạt rây phân tử:</b> Hạt rây hấp thụ triệt để lượng nước sinh ra, đẩy cân bằng dịch chuyển hoàn toàn theo chiều tổng hợp với hiệu suất cao. Các enzyme hoạt động tốt trong dung môi hữu cơ thường là Lipase, Esterase, Protease.</li></ul>"
    },
    {
      "id": 7,
      "label": "ENZYME CỐ ĐỊNH",
      "level": 2,
      "group": "target",
      "tooltip": "💡 Định vị không gian bảo toàn hoạt tính xúc tác",
      "detail": "<h3>Công Nghệ Enzyme Cố Định</h3><p><b>Định nghĩa:</b> Định vị enzyme trong không gian xác định nhưng trung tâm hoạt động vẫn được bảo toàn nguyên vẹn để xúc tác (phân biệt với đông tụ lòng trắng trứng gây biến tính mất hoạt tính).</p><ul><li><b>Ưu điểm:</b> Dễ thu hồi tái sử dụng nhiều lần (giảm chi phí), độ bền cơ lý hóa cao hơn, bảo quản ở nhiệt độ phòng dễ dàng, thiết kế hệ thống cột phản ứng liên tục tự động hóa, sản phẩm tinh khiết không lẫn enzyme.</li><li><b>Nhược điểm:</b> Giảm một phần hoạt tính ban đầu do tương tác hóa học và hiện tượng cản trở không gian steric làm hạn chế cơ chất tiếp xúc.</li></ul>"
    },
    {
      "id": 8,
      "label": "TIÊU CHUẨN CHẤT MANG",
      "level": 3,
      "group": "structure",
      "tooltip": "💡 Yêu cầu lý tính và hóa tính của chất mang",
      "detail": "<h3>Tiêu Chuẩn Lựa Chọn Chất Mang (Matrix)</h3><ul><li><b>Yêu cầu:</b> Giá thành rẻ, độ bền cơ lý cao (chịu lực khuấy bồn phản ứng không vỡ), bền hóa học (không tan trong đệm phản ứng), diện tích bề mặt lớn và khả năng trương nở tốt (cellulose vi khuẩn trương nở lớn giúp tăng tiếp xúc).</li><li><b>Bẫy hóa tính:</b> Canxi alginat tạo gel rất tốt nhưng bị rã cấu trúc hoàn toàn nếu đưa vào môi trường đệm phosphat.</li></ul>"
    },
    {
      "id": 9,
      "label": "CHẤT MANG TỰ NHIÊN",
      "level": 4,
      "group": "structure",
      "tooltip": "💡 Polymer hữu cơ tự nhiên dễ phân hủy sinh học",
      "detail": "<h3>Chất Mang Hữu Cơ Tự Nhiên</h3><ul><li><b>Đại diện:</b> Polysaccharide (Cellulose, Agarose, Dextran, Sephadex) và Protein (Gelatin, Keratin, Albumin chứa nhiều nhóm -NH2 dễ tạo màng và hạt).</li><li><b>Ưu điểm:</b> Độ tương thích sinh học cao với enzyme.</li><li><b>Nhược điểm:</b> Kém bền vững môi trường, dễ bị vi sinh vật phân hủy (bảo quản ẩm cao bắt buộc phải giữ ở nhiệt độ lạnh).</li></ul>"
    },
    {
      "id": 10,
      "label": "CHẤT MANG TỔNG HỢP",
      "level": 4,
      "group": "structure",
      "tooltip": "💡 Polymer hữu cơ tổng hợp cơ lý cực bền",
      "detail": "<h3>Chất Mang Hữu Cơ Tổng Hợp</h3><ul><li><b>Đại diện:</b> Polyacrylamid, Polyvinylacetat (PVA), Polystyren, Polypropylen.</li><li><b>Đặc điểm nổi bật:</b> Bền vững cơ lý cao, trương nở tốt, không bị vi sinh vật phân hủy, có thể chủ động điều chỉnh chính xác kích thước lỗ gel bằng tỷ lệ monomer và chất liên kết chéo.</li><li><b>Nhược điểm:</b> Giá thành cao, tương thích sinh học kém hơn polymer tự nhiên và không tự phân hủy sinh học.</li></ul>"
    },
    {
      "id": 11,
      "label": "CỐ ĐỊNH THUẬN NGHỊCH",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Hấp phụ, liên kết ion, ái lực, disulfit",
      "detail": "<h3>Phương Pháp Cố Định Thuận Nghịch</h3><p>Có thể tách rời để thu hồi và tái sử dụng chất mang.</p><ul><li><b>Hấp phụ vật lý:</b> Lực van der Waals, liên kết hydro, kị nước. Lực liên kết yếu, dễ rò rỉ khi rửa nhưng bảo toàn nguyên vẹn hoạt tính enzyme.</li><li><b>Liên kết ion:</b> Hút tĩnh điện ở pH xác định. <i>Bẫy trắc nghiệm:</i> Không áp dụng được nếu phản ứng sinh ra acid/bazo làm thay đổi pH môi trường (làm biến đổi điện tích gây tuột enzyme).</li><li><b>Liên kết ái lực:</b> Rất bền vững, cực kỳ đặc hiệu, không rò rỉ nhưng chi phí rất cao.</li><li><b>Liên kết disulfit:</b> Dễ bị phá vỡ khi đổi điều kiện oxy hóa-khử, dễ làm thay đổi cấu hình không gian gây mất hoạt tính do can thiệp cầu disulfit.</li></ul>"
    },
    {
      "id": 12,
      "label": "CỐ ĐỊNH KHÔNG THUẬN NGHỊCH",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Đồng hóa trị, bắt giữ, tạo vi hạt bao",
      "detail": "<h3>Cố Định Không Thuận Nghịch</h3><ul><li><b>Liên kết đồng hóa trị:</b> Gắn cộng hóa trị (sử dụng Glutaraldehyd làm cầu nối). Dù làm giảm hoạt tính nhiều nhất do biến đổi cấu hình, nhưng lực liên kết cực mạnh, rò rỉ bằng 0, số lần tái sử dụng cao nhất. <b>Đây là phương pháp ứng dụng thực tế nhiều nhất.</b></li><li><b>Bắt giữ (Entrapment):</b> Trộn vào mạng lưới polymer 3D. Tế bào ở sâu bị cản trở không gian steric mạnh làm hoạt tính không đồng đều, dễ rò rỉ nếu chất mang trương nở lớn.</li><li><b>Tạo vi hạt bao (Encapsulation):</b> Bọc trong màng bán thấm. Enzyme tự do di chuyển bên trong nên giữ nguyên 100% hoạt tính. <i>Bẫy trắc nghiệm:</i> Không thể áp dụng cho cơ chất đại phân tử (như tinh bột, protein lớn) vì cơ chất không chui qua được lỗ màng bao.</li></ul>"
    },
    {
      "id": 13,
      "label": "HIỆU ỨNG VI MÔI TRƯỜNG",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Hiệu ứng phân phối và hiệu ứng ngăn chặn",
      "detail": "<h3>Hiệu Ứng Vi Môi Trường</h3><ul><li><b>Hiệu ứng phân phối (Partitioning):</b> Polymer chất mang lôi kéo cơ chất lại gần enzyme (làm TĂNG hoạt tính) hoặc đẩy cơ chất ra xa enzyme (làm GIẢM hoạt tính).</li><li><b>Hiệu ứng ngăn chặn steric (Obstruction):</b> Mạng lưới polymer cản trở sự khuếch tán tự do của cơ chất đi vào và sản phẩm đi ra (làm GIẢM hoạt tính).</li></ul>"
    },
    {
      "id": 14,
      "label": "THUỐC PROTEIN TRỊ LIỆU",
      "level": 2,
      "group": "target",
      "tooltip": "💡 Thách thức dược học và lợi thế đặc hiệu",
      "detail": "<h3>Đặc Tính Thuốc Protein & Enzyme Trị Liệu</h3><ul><li><b>Thách thức cốt lõi:</b> Tính ổn định kém (bị pH dạ dày phân hủy, bị protease tiêu hóa), thấm tế bào cực thấp (do kích thước lớn, thân nước không xuyên màng phospholipid), kiểm định vô cùng phức tạp (định tính SDS-PAGE, Peptide Mapping; định lượng hoạt tính sinh học, tỷ lệ monomer/dimer).</li><li><b>Đích tác động:</b> Chủ yếu là ngoại bào (bên ngoài tế bào).</li><li><b>Lợi thế:</b> Xúc tác đặc hiệu tuyệt đối, hầu như không có tác dụng phụ ngoài mong muốn, không gây quái thai hay đột biến gen như hóa dược nhỏ.</li></ul>"
    },
    {
      "id": 15,
      "label": "KỸ THUẬT PEG HÓA",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Tăng thời gian bán thải và độ ổn định",
      "detail": "<h3>Gắn Polyethylene Glycol (PEG hóa)</h3><p>Polymer siêu thân nước gắn cộng hóa trị mang lại 3 ưu điểm:</p><ul><li><b>Tăng thời gian bán thải T1/2:</b> Tăng kích thước phân tử giúp tránh bị lọc qua cầu thận.</li><li><b>Tăng tính tan:</b> Thỏa mãn yêu cầu nồng độ cao khi tiêm bắp hoặc tiêm dưới da.</li><li><b>Tăng độ bền & giảm tính miễn dịch:</b> Che lấp các epitope nhận diện của protease và kháng thể.</li><li><b>Bẫy thi cực kỳ quan trọng:</b> PEG hóa KHÔNG LÀM TĂNG KHẢ NĂNG XUYÊN MÀNG TẾ BÀO (thực tế làm giảm tính xuyên màng do tăng kích thước và tính thân nước). Trả lời sai bị 0 ĐIỂM!</li></ul>"
    },
    {
      "id": 16,
      "label": "CẢI TIẾN CHUỖI & ĐỊNH HƯỚNG",
      "level": 3,
      "group": "mechanism",
      "tooltip": "💡 Insulin Lispro và các kỹ thuật định hướng đích",
      "detail": "<h3>Cải Tiến Cấu Trúc & Định Hướng Đích</h3><ul><li><b>Cải tiến chuỗi:</b> Ví dụ Insulin Lispro đảo ngược vị trí Lys-29 sau Pro-28 chuỗi B thành Pro-29 sau Lys-28. Enzyme Trypsin không thể cắt liên kết sau Prolin giúp Insulin Lispro cực kỳ bền vững trước Trypsin mà không đổi hoạt tính.</li><li><b>Định hướng đích (Targeting):</b> Biến đổi nhóm đường (gắn beta-galactosidase để tế bào gan nhận diện đặc hiệu) hoặc dung hợp di truyền với peptide hay kháng thể đơn dòng.</li></ul>"
    },
    {
      "id": 17,
      "label": "THẤM TẾ BÀO (STAPLED & CPP)",
      "level": 3,
      "group": "structure",
      "tooltip": "💡 Peptide ghim và peptide xâm nhập tế bào",
      "detail": "<h3>Kỹ Thuật Xuyên Màng Tế Bào</h3><ul><li><b>Peptide ghim (Stapled peptide):</b> Khóa cấu trúc thẳng của peptide ngắn thành dạng xoắn/vòng giúp chống exoprotease cắt từ hai đầu N và C, đồng thời hỗ trợ xuyên màng tế bào cực tốt.</li><li><b>Peptide xâm nhập tế bào (CPP):</b> Đoạn peptide ngắn 20-40 amino acid từ virus (như R8) có khả năng tự xuyên màng tế bào và kéo theo protein đích cồng kềnh (như GFP) chui vào nội bào.</li></ul>"
    },
    {
      "id": 18,
      "label": "HỆ THỐNG SẢN XUẤT",
      "level": 3,
      "group": "structure",
      "tooltip": "💡 So sánh tế bào động vật, nấm men và vi khuẩn",
      "detail": "<h3>Hệ Thống Biểu Hiện Tái Tổ Hợp</h3><ul><li><b>Tế bào người - động vật:</b> Chất lượng protein và biến đổi hậu dịch mã hoàn hảo nhất nhưng năng suất giới hạn, nguy cơ lây nhiễm virus từ nguồn cho động vật.</li><li><b>Nấm men (Pichia pastoris):</b> Năng suất tốt, thực hiện được glycosyl hóa, có khả năng tiết protein ra ngoài môi trường giúp tinh chế rất dễ dàng.</li><li><b>Vi khuẩn (E. coli):</b> Nhân đôi cực nhanh, năng suất cực cao nhưng KHÔNG thực hiện được biến đổi hậu dịch mã, hay tạo thể vùi (protein gập sai không tan) khó xử lý.</li></ul>"
    },
    {
      "id": 19,
      "label": "LIỆU PHÁP ERT THAY THẾ",
      "level": 3,
      "group": "application",
      "tooltip": "💡 Adagen, Myozyme, Ceredase, Sacrosidase, PAL",
      "detail": "<h3>Liệu Pháp Enzyme Thay Thế (ERT)</h3><ul><li><b>Adagen (tiêm):</b> Chế phẩm ADA bò PEG hóa trị SCID. Kỹ thuật PEG hóa giúp tăng thời gian bán thải từ 1 ngày lên 6 ngày và tăng hiệu quả điều trị gấp 4 lần.</li><li><b>Ceredase (tiêm):</b> Điều trị bệnh Gaucher (tồn trữ thể ly giải).</li><li><b>Myozyme (tiêm):</b> Alpha-glucosidase tái tổ hợp điều trị bệnh cơ Pompe.</li><li><b>Sacrosidase (uống):</b> Điều trị thiếu hụt sucrase-isomaltase.</li><li><b>PAL (uống):</b> Phenylalanine ammonia lyase điều trị Phenylketon niệu (PKU).</li><li><b>PEP (uống):</b> Bổ sung amylase, lipase, protease hỗ trợ tiêu hóa cho bệnh nhân suy tụy.</li></ul>"
    },
    {
      "id": 20,
      "label": "XÚC TÁC LÂM SÀNG",
      "level": 3,
      "group": "application",
      "tooltip": "💡 Vibrolysin, Lysozyme, Chitinase, Asparaginase",
      "detail": "<h3>Liệu Pháp Dựa Vào Hoạt Tính Xúc Tác</h3><ul><li><b>Vibrolysin:</b> Loại bỏ chọn lọc protein biến tính ở mô bỏng mà không làm hại mô lành.</li><li><b>Lysozyme:</b> Thủy phân peptidoglycan diệt vi khuẩn Gram dương.</li><li><b>Chitinase:</b> Thủy phân chitin diệt nấm tại vị trí nảy chồi.</li><li><b>Arginine deiminase PEG hóa:</b> Phân hủy arginine trị melanoma và ung thư gan.</li><li><b>Asparaginase PEG hóa:</b> Điều trị ung thư bạch cầu cấp ALL cực tốt ở trẻ em. <i>Cơ chế:</i> Tế bào ung thư ALL không thể tự tổng hợp asparagine mà phụ thuộc vào máu. Tiêm enzyme làm cạn kiệt asparagine máu giúp 'chết đói' chọn lọc tế bào ung thư mà không hại tế bào lành.</li></ul>"
    },
    {
      "id": 21,
      "label": "ADEPT & GIẢI ĐỘC",
      "level": 3,
      "group": "application",
      "tooltip": "💡 Kháng thể đơn dòng mang enzyme và urate oxidase",
      "detail": "<h3>Liệu Pháp ADEPT & Giải Độc Hóa Trị</h3><ul><li><b>ADEPT:</b> Kháng thể đơn dòng mang enzyme bám đặc hiệu tế bào ung thư. Sau đó đưa tiền chất (prodrug) hoàn toàn không độc vào. Enzyme tại khối u cắt prodrug giải phóng hoạt chất độc diệt ung thư tại chỗ, không hại mô lành.</li><li><b>Urate oxidase (Giải độc):</b> Phân hủy acid uric kém tan (tích tụ sau hóa trị gây gout, suy thận) thành allantoin cực kỳ dễ tan để đào thải nhanh qua nước tiểu.</li></ul>"
    },
    {
      "id": 22,
      "label": "BẪY THI & TRÁNH BẪY",
      "level": 2,
      "group": "resistance",
      "tooltip": "💡 Cảnh báo lỗi sai lý thuyết cực kỳ phổ biến",
      "detail": "<h3>Các Bẫy Trắc Nghiệm Cốt Lõi</h3><ul><li><b>Bẫy 1:</b> Đáp án chuẩn cho câu hỏi bản chất xúc tác sinh học là 'Protein'. Ghi lan man RNA hay amino acid không điển hình trong tự luận ngắn sẽ bị 0 ĐIỂM!</li><li><b>Bẫy 2:</b> PEG hóa tăng tính tan và thời gian bán thải, nhưng KHÔNG làm tăng xuyên màng tế bào.</li><li><b>Bẫy 3:</b> Cố định liên kết ion sẽ thất bại hoàn toàn nếu phản ứng làm thay đổi pH vi môi trường.</li><li><b>Bẫy 4:</b> Cố định vi hạt bao không dùng được cho cơ chất có kích thước đại phân tử.</li><li><b>Bẫy 5:</b> Chất mang Canxi Alginat bị phân rã hoàn toàn nếu đưa vào môi trường đệm phosphat.</li></ul>"
    }
  ],
  "edges": [
    {
      "id": "e1",
      "from": 1,
      "to": 2,
      "label": "Bản chất học",
      "isMain": true
    },
    {
      "id": "e2",
      "from": 1,
      "to": 7,
      "label": "Cải tiến cố định",
      "isMain": true
    },
    {
      "id": "e3",
      "from": 1,
      "to": 14,
      "label": "Tối ưu hóa trị liệu",
      "isMain": true
    },
    {
      "id": "e4",
      "from": 1,
      "to": 19,
      "label": "Ứng dụng ERT",
      "isMain": true
    },
    {
      "id": "e5",
      "from": 1,
      "to": 22,
      "label": "Quản lý bẫy thi",
      "isMain": true
    },
    {
      "id": "e6",
      "from": 2,
      "to": 3,
      "label": "Yêu cầu sử dụng",
      "isMain": true
    },
    {
      "id": "e7",
      "from": 2,
      "to": 4,
      "label": "Đặc tính nổi bật",
      "isMain": true
    },
    {
      "id": "e8",
      "from": 2,
      "to": 6,
      "label": "Hoạt động dung môi",
      "isMain": true
    },
    {
      "id": "e9",
      "from": 7,
      "to": 8,
      "label": "Lựa chọn giá mang",
      "isMain": true
    },
    {
      "id": "e10",
      "from": 8,
      "to": 9,
      "label": "Phân loại",
      "isMain": true
    },
    {
      "id": "e11",
      "from": 8,
      "to": 10,
      "label": "Phân loại",
      "isMain": true
    },
    {
      "id": "e12",
      "from": 7,
      "to": 11,
      "label": "Cách thức",
      "isMain": true
    },
    {
      "id": "e13",
      "from": 7,
      "to": 12,
      "label": "Cách thức",
      "isMain": true
    },
    {
      "id": "e14",
      "from": 7,
      "to": 13,
      "label": "Ảnh hưởng vật lý",
      "isMain": true
    },
    {
      "id": "e15",
      "from": 14,
      "to": 15,
      "label": "Giải pháp bảo vệ",
      "isMain": true
    },
    {
      "id": "e16",
      "from": 14,
      "to": 16,
      "label": "Biến đổi chuỗi",
      "isMain": true
    },
    {
      "id": "e17",
      "from": 14,
      "to": 17,
      "label": "Kỹ thuật xuyên màng",
      "isMain": true
    },
    {
      "id": "e18",
      "from": 14,
      "to": 18,
      "label": "Hệ thống sản xuất",
      "isMain": true
    },
    {
      "id": "e19_sub",
      "from": 19,
      "to": 20,
      "label": "Ứng dụng khác",
      "isMain": true
    },
    {
      "id": "e20_sub",
      "from": 19,
      "to": 21,
      "label": "Ứng dụng khác",
      "isMain": true
    },
    {
      "id": "e_cross_1",
      "from": 6,
      "to": 12,
      "label": "Tổng hợp môi trường khan cần cố định đồng hóa trị",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_2",
      "from": 11,
      "to": 22,
      "label": "Liên kết ion thất bại do thay đổi pH",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_3",
      "from": 12,
      "to": 22,
      "label": "Vi hạt bao thất bại với đại phân tử",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_4",
      "from": 15,
      "to": 22,
      "label": "PEG hóa không làm tăng xuyên màng",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_5",
      "from": 8,
      "to": 22,
      "label": "Canxi Alginat rã trong đệm phosphat",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_6",
      "from": 19,
      "to": 15,
      "label": "PEG hóa nâng thời gian bán thải Adagen gấp 6 lần",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_7",
      "from": 20,
      "to": 15,
      "label": "Asparaginase PEG hóa cải thiện tính tan và độ bền",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    },
    {
      "id": "e_cross_8",
      "from": 13,
      "to": 12,
      "label": "Mạng lưới polymer 3D bắt giữ gây cản trở steric",
      "isMain": false,
      "arrows": "",
      "isImportant": true
    }
  ]
}
```
