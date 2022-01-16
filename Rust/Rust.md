# RUST


### RUST là gì? 
- Rust là ngôn ngữ lập trình được tạo ra vào năm 2006 bởi Graydon Hoare như một dự án phụ khi đang là developer tại Mozilla.  Rust pha trộn hiệu suất của các ngôn ngữ như C++ với cú pháp thân thiện hơn, tập trung vào code an toàn và được thiết kế tốt giúp đơn giản hóa việc phát triển. Các phần của trình duyệt Firefox của Mozilla được viết bằng Rust và các nhà phát triển tại Microsoft được cho là sử dụng nó để mã hóa lại các phần của hệ điều hành Windows.

### Tại sao lại học Rust?
- Rust giải quyết các vấn đề mà C/C++ đã phải vật lộn trong một thời gian dài, chẳng hạn như lỗi bộ nhớ và xây dựng các chương trình đồng thời.
- Mặc dù Rust không phải là Haskell hay Lisp, nhưng nó có hỗ trợ tuyệt vời cho tất cả các loại hoạt động thú vị như lập trình hàm và macro mà bạn có thể thử trải nghiệm.
Ngoài ra, Rust có một cộng đồng rộng lớn tích cực chia sẻ và rất nhiều tài liệu học tập.
##### Nói một cách đơn giản, Rust là ngôn ngữ lập trình cấp thấp (low level), định kiểu tĩnh (statically typed), là ngôn ngữ lập trình đa dụng (multi-paradigm), tập trung vào sự an toàn và hiệu suất.

### Rust có những tính năng nào?
- Performance (Hiệu suất)
  + Rust cực kỳ nhanh và tiết kiệm bộ nhớ: không có thời gian chạy hoặc bộ thu gom rác, nó có thể cung cấp năng lượng cho các dịch vụ quan trọng về hiệu suất, chạy trên các thiết bị nhúng và dễ dàng tích hợp với các ngôn ngữ khác.
- Reliability (Độ tin cậy)
  + Hệ thống kiểu phong phú và mô hình sở hữu của Rust đảm bảo an toàn bộ nhớ và an toàn luồng - cho phép bạn loại bỏ nhiều lớp lỗi tại thời điểm biên dịch.
- Productivity (Năng suất)
  + Rust có tài liệu tuyệt vời, trình biên dịch thân thiện với các thông báo lỗi hữu ích và công cụ hàng đầu - công cụ xây dựng và quản lý gói tích hợp, hỗ trợ đa trình chỉnh sửa thông minh với tính năng tự động hoàn thành và kiểm tra loại, trình định dạng tự động, v.v.

### Học Rust như thế nào?
- Trước hết là đọc tài liệu
- Sau đó bắt tay vào thực hành code. 

### Ưu điểm và nhược điểm của Rust
#### Ưu điểm: 
- Nếu như với các ngôn ngữ lập trình khác việc điều khiển bộ nhớ khi xử lý lệnh là vô cùng phức tạp và tiềm ẩn nhiều rủi ro thì với Rust, mọi chuyện lại dễ dàng hơn rất nhiều.
- Rust có những chức năng, cũng như công cụ chuyên biệt để quản lý bộ nhớ khi cấp phát. Nhất là trong lập trình hệ thống để có thể giảm thiểu tối đa việc gặp lỗi bộ nhớ khi thực thi lệnh.
- Rust là một ngôn ngữ đa nền tảng, nó có thể chạy được trên mọi hệ điều hành phổ biến hiện nay và tất nhiên là nó cũng có thể làm ra những ứng dụng chạy trên các hệ điều hành đó. Đặc biệt, với khả năng về tốc độ cũng như khả năng quản lý bộ nhớ tốt nên rất phù hợp cho các ứng dụng nhúng.
- Ngoài ra, khác với các ngôn ngữ như C, Rust được xem là tối ưu và hỗ trợ cho những ứng dụng song song. Nói cách khác là nó hỗ trợ cho những CPU đa nhân nhiều hơn, các ứng dụng hiện nay phần lớn đều sử dụng từ 2 tới 3 nhân là chính.
#### Nhược điểm:
- Rust được phát triển bởi cộng đồng mã nguồn mở nên nó luôn được cập nhật thường xuyên, nhưng đôi khi chính điều này lại làm cản trở việc sử dụng chúng. Bạn phải thường xuyên theo dõi những thay đổi, cập nhật để có thể theo kịp những thay đổi khác nhau.
- Tuy là mạnh mẽ nhưng Rust được xem là một ngôn ngữ lập trình khá là khó tiếp cận, bởi chúng được sinh ra để tương tác sâu vào hệ thống nhưng vẫn nằm trong tầm kiểm soát, cách thức câu lệnh khá là phức tạp với người mới.
- Về bản chất thì Rust được sinh ra để lập trình trên những hệ thống phức tạp và cần có tốc độ cao.

### Những đặc điểm nổi trội của ngôn ngữ lập trình Rust
- Quản lý bộ nhớ
- Quản lý đồng thời (concurrency) dễ dàng
- Zero-cost abstractions

### Một số tính năng nổi trội của ngôn ngữ lập trình Rust
- Borrow checker
- Ownership
- Lifetime

### Các framework của Rust
- actix-web
- rocket
- tide
- warp

Reference: https://itguru.vn/blog/rust-la-gi-va-tai-sao-ngon-ngu-lap-trinh-nay-duoc-yeu-thich-den-vay/#Nhung_dac_diem_noi_troi_cua_ngon_ngu_lap_trinh_Rust

### Ứng dụng của Rust
- Làm web, làm ứng dụng PC
- Được sử dụng trong các thiết bị thông tin xử lý với tốc độ cao như hệ thống điều khiển trên xe, các hệ thống tín hiệu,..
- Nhưng hiện nay, Rust vẫn đang được sử dụng nhiều nhất chính là trong các hệ thống lớn, những hệ thống yêu cầu độ phức tạp cao, cũng như là phải xử lý nhiều nguồn dữ liệu song song liên tục cùng lúc.
- Tương lai Rust có thể sẽ được phát triển lên các hệ thống chạy trên chip (vi xử lý) ARM nhờ những ưu điểm về quản lý bộ nhớ và tốc độ thực thi. Đây đều là những thứ mà những thiết bị di động rất cần bởi những hạn chế về kích thước phần cứng. Thậm chí đang có một số cải tiến và thử nghiệm nó trong việc phát triển AI, thứ vốn cần tốc độ càng cao càng tốt.
- Ngoài ra Rust còn được sử dụng để viết:
  + Trình biên dịch
  + Ứng dụng thời gian thực (real-time)
  + Các hệ thống lớn và phức tạp
  + Hệ thống nhúng (embedded system) 
  + Các hệ thống cần có hiệu suất cao và độ trễ thấp. Ví dụ như trong các thiết bị lái xe, trong game, hay các thiết bị phát sóng..
  + Ứng dụng phân tán và song song
  + Web Framework….
  
Reference: https://blogchiasekienthuc.com/goc-nhin/ngon-ngu-lap-trinh-rust.html

  
