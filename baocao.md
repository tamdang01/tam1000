# BÀI BÁO CÁO #

- Đặng Nguyễn Thiện Tâm <!-- markdownlint-capture -->
- Nguyễn Minh Quân <!-- markdownlint-capture -->

1. **Git là gì?**
Git là một hệ thống quản lý phiên bản phân tán (Distributed Version Control System – DVCS). Git cung cấp cho mỗi lập trình viên kho lưu trữ(repository) riêng chứa toàn bộ lịch sử thay đổi.
Vd: Trang bán hang điện tử Tiki sẽ có một kho tổng chứa hang, ngoài kho tổng đó thì sẽ có nhiều kho nhỏ được phân ra ở các nơi khác nhau có thể hiểu là các kho con ở các tỉnh thì git cũng giống như vậy. Nó là nơi lưu trữ source code
Khi làm việc nhóm ta sẽ đổ vào một git chung(nơi lưu trữ chung) và nó sẽ quản lí version cho các member(quản lí được ai đẩy code lên, thời gian hay mọi thay đổi trên code,…) sẽ phản ánh trên git. Sẽ có một leader nhìn và thấy mọi hoạt động trên git.

2. **Tại sao phải dùng Git?**

- Bình thường khi lập trình ta thường lưu trữ source code trong máy tính, như vậy sẽ rất nguy hiểm. Ví dụ khi bị hỏng ổ cứng thì dữ liệu sẽ mất hết thì git sẽ giúp lưu trữ dữ liệu và lưu trữ thời gian thay đổi ngay cả việc bạn thay đổi cái gì đều có thể truy tìm trong lịch sử
- Ví dụ: khi triển khai dự án cần nhiều người thì leader không cần phải chạy tới từng member để kiểm tra code như thế nào. Leader chỉ cần chỉ thị và yêu cầu đẩy code lên git thì sẽ kiểm soát được bạn code được bao nhiêu dòng, ngày hôm nay bạn code được gì, bạn thay đổi được gì,...
- Lưu lại được các phiên bản khác nhau của mã nguồn dự án phần mềm
- Khôi phục lại mã nguồn từ một phiên bản bất kỳ
- Dễ dàng so sánh giữa các phiên bản
- Phát hiện được ai đã sửa phần nào làm phát sinh lỗi Khôi phục lại tập tin bị mất
- Dễ dàng thử nghiệm, mở rộng tính năng của dự án mà không làm ảnh hưởng đến phiên bản chính (master branch)
- Giúp phối hợp thực hiện dự án trong nhóm một cách hiệu quả
