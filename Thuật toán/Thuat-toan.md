### Thuật toán là gì?
- Thuật toán là một khái niệm cơ sở của Toán học và Tin học. Hiểu một cách đơn giản, thuật toán là một tập các hướng dẫn nhằm thực hiện một công việc nào đó. Ðối với việc giải quyết một vấn đề - bài toán thì thuật toán có thể hiểu là một tập hữu hạn các hướng dẫn rõ ràng để người giải toán có thể theo đó mà giải quyết được vấn đề. Như vậy, thuật toán là một phương pháp thể hiện lời giải của vấn đề - bài toán.
- Trong toán học và khoa học máy tính, một thuật toán, còn gọi là giải thuật, là một tập hợp hữu hạn các hướng dẫn được xác định rõ ràng, có thể thực hiện được bằng máy tính, thường để giải quyết một lớp vấn đề hoặc để thực hiện một phép tính.
- Các thuật toán luôn rõ ràng và được sử dụng chỉ rõ việc thực hiện các phép tính, xử lý dữ liệu, suy luận tự động và các tác vụ khác.

### Tại sao lại là "Thuật toán"
- Từ thuật toán (Algorithm) xuất phát từ tên một nhà toán học người Trung Á là Abu Abd - Allah ibn Musa al’Khwarizmi, thường gọi là al’Khwarizmi. Ông là tác giả một cuốn sách về số học, trong đó ông đã dùng phương pháp mô tả rất rõ ràng, mạch lạc cách giải những bài toán. Sau này, phương pháp mô tả cách giải toán của ông đã được xem là một chuẩn mực và được nhiều nhà toán học khác tuân theo. Từ algorithm ra đời dựa theo cách phiên âm tên của ông.

### Các đặc trưng của thuật toán
##### Tính xác định
- Việc nghiên cứu về thuật toán có vai trò rất quan trọng trong khoa học máy tính vì máy tính chỉ giải quyết được vấn đề khi đã có hướng dẫn giải rõ ràng và đúng. Nếu hướng dẫn giải sai hoặc không rõ ràng thì máy tính không thể giải đúng được bài toán. Trong khoa học máy tính, thuật toán được định nghĩa là một dãy hữu hạn các bước không mập mờ và có thể thực thi được, quá trình hành động theo các bước này phải dừng và cho được kết quả như mong muốn.
- Số bước hữu hạn của thuật toán và tính chất dừng của nó được gọi chung là tính hữu hạn. Số bước hữu hạn của thuật toán là một tính chất khá hiển nhiên. Ta có thể tìm ở đâu một lời giải vấn đề - bài toán có vô số bước giải ? Tính "không mập mờ" và "có thể thực thi được" gọi chung là tính xác định.
- Tính "thực thi được" cũng là một tính chất khá hiển nhiên. Rõ ràng nếu trong "thuật toán" tồn tại một bước không thể thực thi được thì làm sao ta có được kết quả đúng như ý muốn? Tuy nhiên, cần phải hiểu là "thực thi được" xét trong điều kiện hiện tại của bài toán. Chẳng hạn, khi nói "lấy căn bậc hai của một số âm" là không thể thực thi được nếu miền xác định của bài toán là số thực, nhưng trong miền số phức thì thao tác "lấy căn bậc hai của một số âm" là hoàn toàn thực thi được. Tương tự, nếu ta chỉ đường cho một người đi xe máy đến một bưu điện nhưng con đường ta chỉ là đường cụt, đường cấm hoặc đường ngược chiều thì người đi không thể đi đến bưu điện được.

##### Tính hữu hạn
- Tính "dừng" hay hữu hạn là tính chất dễ bị vi phạm nhất, thường là do sai sót khi trình bày thuật toán. Dĩ nhiên, mọi thuật toán đều nhằm thực hiện một công việc nào đó nên sau một thời gian thi hành hữu hạn thì thuật toán phải cho chúng ta kết quả mong muốn. Khi không thỏa tính chất này, ta nói rằng "thuật toán" bị lặp vô tận hoặc bị quẩn. Ðể tính tổng các số nguyên dương lẻ trong khoảng từ 1 đến n ta có thuật toán sau :
```bash
B1. Hỏi giá trị của n.
B2. S = 0
B3. i = 1
B4. Nếu i = n+1 thì sang bước B8, ngược lại sang bước B5
B5. Cộng thêm i vào S
B6. Cộng thêm 2 vào i
B7. Quay lại bước B4.
B8. Tổng cần tìm chính là S.
```
- Ta chú ý đến bước B4. Ở đây ta muốn kết thúc thuật toán khi giá trị của i vượt quá n. Thay vì viết là "nếu i lớn hơn n" thì ta thay bằng điều kiện "nếu i bằng n+1" vì theo toán học "i = n+1" thì suy ra "i lớn hơn n". Nhưng điều kiện "i=n+1" không phải lúc nào cũng đạt được. Vì ban đầu i = 1 là số lẻ, sau mỗi bước, i được tăng thêm 2 nên i luôn là số lẻ. Nếu n là số chẵn thì n+1 là một số lẻ nên sau một số bước nhất định, i sẽ bằng n+1. Tuy nhiên, nếu n là một số lẻ thì n+1 là một số chẵn, do i là số lẻ nên dù có qua bao nhiêu bước đi chăng nữa, i vẫn khác n+1. Trong trường hợp đó, thuật toán trên sẽ bị quẩn.

##### Tính đúng
- Tính "đúng" là một tính chất khá hiển nhiên nhưng là tính chất khó đạt tới nhất. Thực vậy, khi giải quyết một vấn đề-bài toán, ta luôn luôn mong muốn lời giải của mình sẽ cho kết quả đúng nhưng không phải lúc nào cũng đạt được. Mọi học sinh khi làm bài kiểm tra đều muốn bài làm của mình có đáp số đúng nhưng trên thực tế, trong lớp học chỉ có một số học sinh nhất định là có khả năng đưa ra lời giải đúng!

##### Tính hiệu quả
- Tính hiệu quả của thuật toán được đánh giá dựa trên một số tiêu chuẩn như khối lượng tính toán, không gian và thời gian khi thuật toán được thi hành. Tính hiệu quả của thuật toán là một yếu tố quyết định để đánh giá, chọn lựa cách giải quyết vấn đề-bài toán trên thực tế. Có rất nhiều phương pháp để đánh giá tính hiệu quả của thuật toán. Trong mục 3 của chương , ta sẽ tìm hiểu một tiêu chuẩn được dùng rộng rãi là độ phức tạp của thuật toán.

##### Tính tổng quát
- Thuật toán có tính tổng quát là thuật toán phải áp dụng được cho mọi trường hợp của bài toán chứ không phải chỉ áp dụng được cho một số trường hợp riêng lẻ nào đó. Chẳng hạn giải phương trình bậc hai sau đây bằng Delta đảm bảo được tính chất này vì nó luôn giải được với mọi giá trị số thực a,b,c bất kỳ. Tuy nhiên, không phải thuật toán nào cũng đảm bảo được tính tổng quát. Trong thực tế, có lúc người ta chỉ xây dựng thuật toán cho một dạng đặc trưng của bài toán mà thôi.

Reference: https://laptrinh.vn/books/thuat-toan/page/thuat-toan-la-gi

### Tầm quan trọng của việc học thuật toán
- Với một lập trình viên, hay một nhà khoa học máy tính, học các thuật toán vừa nêu là rất quan trọng để có thể áp dụng xử lý các bài toán trong thực tiễn.
- Nếu ta viết một phần mềm, ta sẽ phải đánh giá được phần mềm đó sẽ hoạt động nhanh chậm ra sao. Những đánh giá như vậy sẽ kém chính xác hơn nhiều nếu ta không có hiểu biết về thời gian chạy hay độ phức tạp.
- Thêm nữa, hiểu biết kỹ càng về thuật toán của những gì ta đang làm sẽ giúp ta dự đoán những trường hợp đặc biệt khiến phần mềm chạy chậm đi hay xảy ra lỗi.
- Tất nhiên, ta sẽ thường xuyên gặp những bài toán chưa được nghiên cứu trước đó. Lúc này ta phải tự nghĩ ra thuật mới, hoặc áp dụng thuật cũ một cách sáng tạo hơn.

