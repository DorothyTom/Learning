# Typescript
![step02](https://user-images.githubusercontent.com/94232298/149668220-650007c7-224d-41a2-ba01-483ed1e834e9.png)
### TypeScript là gì?
- TypeScript là một dự án mã nguồn mở được phát triển bởi Microsoft, nó có thể được coi là một phiên bản nâng cao của Javascript bởi việc bổ sung tùy chọn kiểu tĩnh và lớp hướng đối tượng mà điều này không có ở Javascript. TypeScript có thể sử dụng để phát triển các ứng dụng chạy ở client-side (Angular2) và server-side (NodeJS).

### Tại sao nên sử dụng TypeScript??
- **Dễ phát triển dự án lớn:** Với việc sử dụng các kỹ thuật mới nhất và lập trình hướng đối tượng nên TypeScript giúp chúng ta phát triển các dự án lớn một cách dễ dàng.
- **Nhiều Framework:** Hiện nay các Javascript Framework đã dần khuyến khích nên sử dụng TypeScript để phát triển, ví dụ như AngularJS 2.0 và Ionic 2.0.
- **Hỗ trợ các tính năng của Javascript phiên bản mới nhất:** TypeScript luôn đảm bảo việc sử dụng đầy đủ các kỹ thuật mới nhất của Javascript, ví dụ như version hiện tại là ECMAScript 2015 (ES6).
- **Là mã nguồn mở:** TypeScript là một mã nguồn mở nên bạn hoàn toàn có thể sử dụng mà không mất phí, bên cạnh đó còn được cộng đồng hỗ trợ.
- **TypeScript là Javascript:** Bản chất của TypeScript là biên dịch tạo ra các đoạn mã javascript nên ban có thê chạy bất kì ở đâu miễn ở đó có hỗ trợ biên dịch Javascript. Ngoài ra bạn có thể sử dụng trộn lẫn cú pháp của Javascript vào bên trong TypeScript, điều này giúp các lập trình viên tiếp cận TypeScript dễ dàng hơn.

### Cơ bản về  TypeScript
- Trong TypeScript chia ra làm 7 loại cơ bản, bao gồm: boolean, number, string, array, enum, any, void. Khi khai báo ta sẽ sử dụng cấu trúc như sau: var tên_biến : kiểu_trả_về = giá_trị_biến;
  

Reference: https://viblo.asia/p/tim-hieu-typescript-va-kien-thuc-co-ban-PmeRQpnyGoB

### Chức năng của TypeScript là gì?
#### Static Typing
- Một trong những chức năng không thể lẫn vào đâu được của TypeScript đó là hỗ trợ 'static typing'. Đồng nghĩa với việc bạn có thể khai báo kiểu cho biến, và trình biên dịch sẽ giảm được tỷ lệ gán sai kiểu của các giá trị. Nếu khai báo kiểu bị bỏ qua, chúng sẽ được tự động phát hiện từ code của bạn.
- Toàn bộ khai báo kiểu sẽ bị xóa trong trường hợp TypeScript biên dịch thành Javascript thành công
- Biên dịch tsc sẽ báo lỗi khi chúng ta thao tác không hợp lệ
- Hệ thống cũng sẽ báo lỗi nếu thao tác truyền sai tham số tới một hàm 

###### Các kiểu dữ liệu được sử dụng phổ biến nhất: 
- Any: Một biến với kiểu này có thể có giá trị là một string, number hoặc bất kỳ kiểu nào
- String: Giống chức năng của string trong Javascript, có thể được bao quanh bởi 'dấu nháy đơn' hoặc "dấu nháy kép"
- Number: Tất cả giá trị số trong hàm đều được biểu diễn bởi kiểu number, không có định nghĩa riêng cho số nguyên (interger), số thực (float) cũng như các kiểu khác.
- Boolean: true hoặc false, sử dụng 0 và 1 sẽ gây ra lỗi biên dịch
- Arrays: Có 2 kiểu cú pháp: my_arr: number[]; hoặc my_arr: Array<number>
- Void: sử dụng khi hàm không trả lại bất kỳ giá trị nào

#### Interfaces
- Chức năng chính của Interfaces là sử dụng để kiểm tra, xem một đối tượng có phù hợp với một cấu trúc nhất định hay không, trợ giúp trong giai đoạn giai đoạn phát triển.
- Bằng cách định nghĩa một interface, ta có thể đặt tên trong trường hợp có sự kết hợp đặc biệt của các biến, đảm bảo rằng chúng luôn luôn đi cùng nhau.
- Ngoài ra bạn nên biết rằng, thứ tự của các thuộc tính không quan trọng bằng việc chúng ta phải fill đủ số lượng các thuộc tính và đúng kiểu. Nếu một thuộc tính nào đó bị thiếu, hoặc sai kiểu, hoặc sai tên, trình biên dịch sẽ cảnh báo chúng ta.

#### Classes
- Trong các dự án, ứng dụng lớn, lập trình hướng đối tượng rất hay được các Dev sử dụng nhất là trong các ngôn ngữ như Java hoặc C#.
- TypeScript cung cấp hệ thống class khá tương đồng với các ngôn ngữ này ví dụ như chức năng kế thừa, abstract classes, interface implementations, setter/getters, …
- Từ phiên bản ECMAScript 2015 trở đi, classes được xem là một tính năng có sẵn trong JS và có thể không cần sử dụng TypeScript. Mặc dù 2 phiên bản này có nhiều chức năng tương tự nhau, nhưng chúng vẫn có điểm khác biệt, đó là TypeScript nghiêm ngặt hơn.

#### Modules
- Tính module hóa rất quan trọng khi bạn đang thực hiện những dự án lớn. Nó phân chia code thành nhiều thành phần nhỏ và còn có khả năng tái sử dụng giúp dự án của bạn dễ tổ chức và dễ hiểu hơn so với file có hàng ngàn dòng code.
- TypeScript có chức năng exporting và importing các module, nhưng bản thân nó không thể xử lý thực sự việc liên kết giữa các file. Dùng require.js cho các ứng dụng client và CommonJS cho Node.js để cho phép modules TS dựa trên các thư viện của bên thứ ba.
- Đặt trường hợp có 2 file: 1 file export một hàm, 1 file import, chúng ta sẽ gọi nó là:
###### exporter.ts
> var sayHi = function(): void {
>     console.log("Hello!");
> }
> export = sayHi;

###### importer.ts
> import sayHi = require('./exporter'); 
> sayHi();

- Để có thể hoàn thành thao tác, cần download require.js và thêm nó trong một thẻ script – xem hướng dẫn typescript là gì của requirejs.org. Sau đó biên dịch 2 file .ts. Mộ tham số mở rộng cần được thêm vào để nói với TypeScript chúng ta đang xây dựng các module cho require.js (còn được gọi là AMD):
> tsc --module amd *.ts

### Generics
- Chức năng của Generics là cho phép cùng một hàm có thể chấp nhận các tham số với nhiều kiểu khác nhau. Việc tạo ra các thành phần có thể tái sử dụng với generics tốt hơn sử dụng kiểu any, vì generics bảo tồn kiểu của các biến vào và ra của chúng.
- Lần đầu tiên gọi hàm chúng ta thiết lập kiểu thành string. Điều này không bắt buộc vì trình biên dịch có thể xem tham số được truyền và tự động quyết định kiểu nào phù hợp nhất, giống như lần gọi hàm thứ 2.
- Mặc dù không bắt buộc, luôn luôn cung cấp kiểu được coi là cần thiết vì trình biên dịch có thể đoán sai kiểu trong các kịch bản phức tạp.

### Ưu điểm của TypeScript
##### TypeScript thật sự thuận tiện và hoàn toàn miễn phí
  + Đối với loại ngôn ngữ lập trình tĩnh như TypeScript, tất cả những số liệu, thông số của bạn sẽ dễ dàng được lấy hơn nhờ IDE và trình biên dịch.
  + TypeScript hỗ trợ quá trình tìm kiếm giúp bạn tiết kiệm thời gian kiểm tra lại code, không cần thông qua bất cứ một ai để có thể tìm thông tin dữ liệu, ngoài ra TypeScript làm giảm phần trăm va chạm lỗi trong thời gian vận hành.
  + Ngoài ra, đây cũng là một trong những phần mềm nổi trội được Microsoft hỗ trợ hoàn toàn miễn phí.
##### Thao tác nhanh chóng và đơn giản hơn
  + Ngôn ngữ TypeScript có thao tác khá đơn giản, tiết kiệm thời gian hơn nhưng lại đem đến kết quả tốt đến bất ngờ, nó khắc phục tình trạng xuất hiện lỗi và dễ đọc hơn.
  + Cụ thể là, đối với ngôn ngữ thông thường người dùng thường thao tác theo các bước như:
    - Restart lại hàm, tạo đối số, hoàn thành đoạn mã
    - Sau khi apply hết các đoạn mã, công cụ cần thiết thì cho vận hành
    - Trong quá trình vận hành nếu phát hiện lỗi thì sửa chữa lại.
##### Tái cấu trúc
  + Chắc chắn trong quá trình viết code, các lập trình viên sẽ thường xuyên mắc phải nhiều lỗi nhỏ và cần chỉnh sửa, việc sử dụng TypeScript sẽ giúp bước chỉnh sửa code trở nên dễ dàng hơn nhờ hiệu quả của lệnh Rename Symbol/Find All Occurrences.
  + Đối với các ngôn ngữ khác, khi muốn sửa chi tiết nào đó thì thường phải thay đổi luôn những tập tin khác nếu có liên quan hoặc sử dụng RegEx
  + Trong trường hợp người dùng TypeScript muốn nâng cấp hệ thống của mình (thêm hoặc xóa thuộc tính, đổi tên,…) thì TypeScript sẽ giúp bạn tái cấu trúc lại sao cho phù hợp với nhu cầu tìm kiếm của bạn mà không gây náo loạn trong hệ thống. Trong trường hợp code của bạn không match được bất cứ dữ liệu nào thì sẽ được báo đến bạn ngay để được xử lý ổn thỏa.

##### Giảm tỉ lệ mắc lỗi trong hệ thống
- Nhờ vào việc cảnh báo lỗi ngay khi viết code, nên tỷ lệ mắc lỗi trong hệ thống khi sử dụng TypeScript khá thấp, TypeScript sẽ trả lại giá trị null hoặc gợi ý thay đổi chỉnh sửa. Mỗi lần chỉnh sửa sau khi được TypeScript báo lỗi thì phần trăm hệ thống hoạt động mà không mắc phải lỗi là rất cao, có thể dễ dàng thấy được TypeScript giúp người dùng tiết kiệm không ít thời gian để sửa lỗi.

##### Hạn chế thử nghiệm Boilerplate
- Với quy trình kiểm tra và báo lỗi tự động ngay khi code, khi bạn đã chắc chắn rằng các biến dữ liệu của mình nằm ở đúng chỗ thì bạn không cần phải lo hệ thống không vận hành hoặc không cần phải kiểm tra lại nữa.
- Điều này sẽ giúp bạn tiết kiệm thời gian, không đặt quá nhiều chú ý vào những thao tác đơn giản cho việc kiểm tra mà có thể tận dụng thời gian tối ưu hơn bằng cách kiểm tra chất lượng logic của hệ thống.
- Việc hạn chế được các bước thử nghiệm sẽ giúp tiết kiệm được thời gian hơn, nâng cao hiệu quả công việc của các lập trình viên.

##### Hợp nhất mã đơn giản
- Sau khi hoàn thiện được một đoạn code và cho chúng chạy thử nghiệm, có thể ngay trong môi trường đó mọi thứ đều hoạt động trơn tru, nhưng bạn có chắc được đoạn code đó cũng sẽ hoạt động tốt khi ở trong môi trường điều kiện khác? 
- Một trong những điểm mạnh của TypeScript là bạn có thể hợp nhất mã một cách đơn giản để có thể dễ dàng kiểm tra đánh giá đoạn mã bạn vừa mới cho ra đời kia bằng cách sử dụng Typedef – kiểm tra biên dịch.
- Lại một lần nữa, TypeScript lại giúp người dùng tiết kiệm thời gian và công sức!

##### Hỗ trợ ưu hóa quy trình làm việc
- TypeScript sẽ không khuyến khích người dùng nhảy bước, thực hiện sai thao tác. TypeScript khuyến khích người dùng đưa ra quyết định về kiểu dữ liệu khi sử dụng ngôn ngữ kiểu tĩnh trước khi thực hiện thao tác, các bước tiếp theo. Chính vì những quy luật như thế sẽ giúp cho các lập trình viên tối ưu được quy trình làm việc hiệu quả hơn.

### Nhược điểm của Typescript là gì?
- Bất kỳ ngôn ngữ nào cũng có điểm yếu và hạn chế của nó, và TypeScript cũng vậy, điểm hạn chế của TypeScript là:

##### Bắt buộc dùng biên dịch
- Để có thể vận hành một tệp TypeScript với đuôi .js trên nền tảng Node.js bạn bắt buộc phải dùng trình biên dịch để có thể sử dụng.
##### Bước thiết lập cồng kềnh
- Trước khi có thể sử dụng được TypeScript, bạn cần đảm bảo rằng máy chủ Node.js, trình thử nghiệm và webpack đều có thể hoạt động với TypeScript, nếu không thì bạn sẽ không sử dụng được.
- Bên cạnh đó, mỗi khi bạn apply thêm bất kỳ library nào như Redux, React và Styled-Component thì bạn cũng phải thêm Typedef vào.
##### Chỉ là phần ngôn ngữ mở rộng hỗ trợ
- Sau cùng, chức năng của TypeScript cũng chỉ là để biên dịch về JavaScript, nó không phải là một ngôn ngữ có thể vận hành độc lập và nó cũng đồng thời không thể thay thế được vai trò của JavaScript. Chức năng của TypeScript bị giới hạn bởi chức năng của JavaScript, TypeScript chỉ là được nâng cấp từ điểm yếu của JavaScript.
- Chỉ với mỗi TypeScript, người dùng không thể nào hoàn thiện được các công đoạn của dự án, công dụng của TypeScript chỉ thực sự nổi bật khi được kết hợp nhuần nhuyễn và tối ưu với các ngôn ngữ, nền tảng và tool khác.

##### TypeScript có thực sự là một mã nguồn mở?
- Có nhiều luồng ý kiến cho rằng TypeScript là một mã nguồn mở, và đó cũng là một trong những lý do họ thích sử dụng TypeScript. Nhưng liệu đó có phải sự thật?
- Đúng! TypeScript thực sự là một mã nguồn mở nhưng nó vẫn nằm dưới sự chi phối của Microsoft – công ty phần mềm nổi tiếng về các phiên bản phần mềm độc quyền. 
- Nhiều người dự đoán, TypeScript là một sản phẩm marketing của Microsoft dùng để thu hút người dùng về công năng và sự miễn phí. Tuy nhiên sau cùng, việc Microsoft có kéo dài việc miễn phí này hay không vẫn phụ thuộc rất nhiều vào Microsoft và người dùng hoàn toàn bị động trong chuyện này.

Reference:
https://topdev.vn/blog/typescript-la-gi-uu-va-nhuoc-diem-cua-typescript/

