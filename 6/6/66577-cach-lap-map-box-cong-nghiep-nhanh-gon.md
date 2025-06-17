---
title: "Cách lập map box công nghiệp nhanh gọn!"
date: 2025-06-14T05:55:20Z
slug: cach-lap-map-box-cong-nghiep-nhanh-gon
draft: false
---

## Cách lập map box công nghiệp nhanh gọn!

## wander

Cách lập map box công nghiệp nhanh gọn!​
Chú ý: Bài này đăng lên để giải thích về cách lập map cho OriolusMidnight và o0oCHAOSo0o nên mới để ở box này chứ trừ những bạn muốn lên mod hoặc đã lên mod, hoặc những bạn muốn làm map cho box mbm, những bạn khác chắc ko cần cái này 

Công cụ: trình duyệt (IE, FF, Chrome, Opera,... loại nào cũng được), Microsoft Excel và vài tiếng đồng hồ hoặc vài ngày tùy theo lượng page cần làm map và yêu cầu làm map của bạn  1 yêu cầu nữa là nên dọn dẹp box trước khi là map 

I. Tạo danh sách topic aka map box giai đoạn 1:

Đầu tiên, để đỡ lộn xộn, nhất là box nhiều page và bạn không có đủ thời gian copy hết các page ngay thì nên sort topic theo ngày đăng, từ ngày sớm nhất đến ngày trễ nhất như trong hình. Cách này có 1 ưu thế là khi bạn copy, dù có dừng lại nửa chừng thì có ai đăng bài thêm vô, thứ tự topic cũng không thay đổi. Và sau này nếu bạn update lại map, cũng chỉ cần copy tiếp từ page mà bạn đã dừng lại lần trước. Rất tiện!


Click chọn như hình trên và click "Đặt tùy chọn". Nhìn thanh address thấy ra phần order =.... như dưới hình là thành công.


Chú ý: đừng đăng nhập nick nếu bạn là tmod trở lên, vì có thể sẽ lẫn cả những topic đã xóa trong box giống như hình dưới.

Sau đó quét chọn page cần làm map, copy. 


Dán vào Excel. 

Vì kết quả thu được ngoài tên topic còn rất nhiều thứ lộn xộn như trên nên ta sẽ loại nó đi. Cũng chỉ cần 2 bước đơn giản.

Bước 1: Lọc danh sách các topic. 
Nhìn vào danh sách file trên Excel, bạn sẽ thấy dòng "Trả lời:" cách dòng tiêu đề topic đúng 3 dòng, ta sẽ sử dụng điều này để lọc. Đầu tiên, copy ô trả lời (A7) ra 1 ô gần đó (trong hình là D1), nhớ chọn cột khác với 2 cột mà ta sẽ sử dụng để lọc nhé, ko thì bị sai ráng chịu . Sau đó ghi hàm như trong hình (vào B4). Enter.

Nhớ để ý kết quả là 1 với những dòng chứa tên topic và 0 với những dòng còn lại như hình dưới mới đúng nhé.

  
Giờ chỉ cần sort lại là xong. Ta quét chọn toàn bộ khu vực có dữ liệu (ở đây là 2 cột A, , nhấn custom sort.


Chọn như trong hình.

Thành quả đây 


Bước 2: Loại bỏ ava mem đăng bài:
Nhấn Ctrl+G, click vào Special trên hộp thoại hiện ra:

Chọn Objects như trong hình, click OK.

Xong ấn Delete nữa là các ava sẽ bị xóa sạch sẽ.

Vậy là bạn đã có 1 list topic hoàn chỉnh. Nếu làm map box theo kiểu đơn giản thì chỉ cần sort tên topic từ A-Z nữa là xong mà tui bảo đảm bước này ai cũng biết làm 

Chú ý: Số page làm mỗi lần tùy thuộc vào máy bạn nhanh hay chậm, mỗi lần làm xong hãy copy sang 1 sheet khác, rồi tiếp tục copy page mới vào sheet này để tận dụng công thức sẵn có, chỉ phải chỉnh lại chút. 

II. Tạo danh sách topic aka map box giai đoạn 2:

Tuy nhiên, nếu nhu cầu của bạn cao hơn, bạn muốn phân loại các topic trong box lung linh như topic này: http://forum.matngu12chomsao.com/threads/map-box-phan-tich-xu-nu-moi.58509/ của bạn ThuyanhDoan1997 thì ta sẽ cần thêm vài bước xử lý. (Map box của mình lấy cảm hứng từ map của bạn ấy và gợi ý của CrimsonV  )

Chú ý: Vì excel chỉ hiểu được các trường có sẵn nên nếu bạn làm map box cho MBM mà muốn thêm thể loại truyện thì phải tự điền tay vô thôi, vì trên tên topic không hề có thể loại 

Chẳng hạn theo yêu cầu của box Tổng hợp, để chống trùng và tiện cho mem theo dõi các chủ đề mà họ yêu thích thì mình phân loại theo 4 tiêu chí như hình dưới. Uhm, bày vẽ linh tinh thôi, kiểu chòm sao và giải trí sẽ có chòm sao và thần tượng, chòm sao và phim ảnh,... nếu chỉ phân loại theo 1 cột thì hơi khó sắp xếp , chứ thực tế làm đơn giản hơn nhiều  

Ở đây mình dùng kết hợp hàm If, Iserror và search để phân loại cho các topic dựa theo tên. Như hình dưới là mình đang phân loại những topic có từ gia đình, cha, mẹ, anh chị em và cùng thể loại Gia đình (ô G3 mình type chữ Gia đình ở trỏng để tiết kiệm ký tự trong hàm). Bạn nào có cách xếp hay hơn thì nói mình nhé 

 
Sau khi dùng hàm xử lý xong (nên ưu tiên xử lý các topic nào nhiều mà ít có từ khóa trùng với các thể loại khác, ví dụ yêu vẫn có thể trùng với yêu thương gia đình ), bạn nên dò lại 1 lần nữa, vì máy chỉ là máy và khả năng đặt từ khóa của ta có hạn còn từ ngữ Việt thì quả là phong phú vô cùng. 

Dưới đây là thành quả  khi lên map box chỉ cần sort theo thể loại và theo tên là đủ.
 

p/s: Nhận mọi gạch đá, góp ý tại đây! Trình excel của tui còn cùi lắm nên ai có cách hay hơn thì chỉ giúp. Many thanks