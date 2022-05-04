# CS331.M21
PP1 : Dựa trên feature map của gương mặt (đã biết trước ) -> nội suy bbox gương mặt ở ảnh gốc
PP2 : Sử dungh pretrainedmodel với regression -> mạng sẽ học cách tính bbox dựa trên dữ liệu huấn luyện học máy
PP3 : phát hiện đối tượng với 2 giai đoạn
    * GD1 : object proposal
    * GD2 : objec localgation
PP4 : phát hiện đối tượng với 1 giai đoạn end to end

Cách để normalize là chia cho w,h
Đóng băng lớp conv (Freagee)
chỉ truyền regression head
Bài tập về nhà
hàm độ lỗi cho bài toàn phân loại (hồi quy là gì) ? Giải thích vì sao?
Tại sao normailize output về đoạn 0->1 mà không sử dụng nguyên bản bbox?
