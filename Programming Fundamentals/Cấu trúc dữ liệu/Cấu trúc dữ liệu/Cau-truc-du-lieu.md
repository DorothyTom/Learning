### Cấu trúc dữ liệu
- Trong khoa học máy tính, cấu trúc dữ liệu là một cách lưu dữ liệu trong máy tính sao cho nó có thể được sử dụng một cách hiệu quả.
- Trong thiết kế nhiều loại chương trình, việc chọn cấu trúc dữ liệu là vấn đề quan trọng. Kinh nghiệm trong việc xây dựng các hệ thống lớn cho thấy khó khăn của việc triển khai chương trình, chất lượng và hiệu năng của kết quả cuối cùng phụ thuộc rất nhiều vào việc chọn cấu trúc dữ liệu tốt nhất.
- Mỗi loại cấu trúc dữ liệu phù hợp với một vài loại ứng dụng khác nhau, một số cấu trúc dữ liệu dành cho những công việc đặc biệt. Ví dụ, các B-tree đặc biệt phù hợp trong việc thiết kế cơ sở dữ liệu. Sau khi cấu trúc dữ liệu được chọn, người ta thường dễ nhận thấy thuật toán cần sử dụng. Đôi khi trình tự công việc diễn ra theo thứ tự ngược lại: cấu trúc dữ liệu được chọn do những bài toán quan trọng nhất định có thuật toán chạy tốt nhất với một số cấu trúc dữ liệu cụ thể. Trong cả hai trường hợp, việc lựa chọn cấu trúc dữ liệu là rất quan trọng.

### Kết luận
- Thông thường, một cấu trúc dữ liệu được chọn cẩn thận sẽ cho phép thực hiện thuật toán hiệu quả hơn. Việc chọn cấu trúc dữ liệu thường bắt đầu từ chọn một cấu trúc dữ liệu trừu tượng. Một cấu trúc dữ liệu được thiết kế tốt cho phép thực hiện nhiều phép toán, sử dụng càng ít tài nguyên, thời gian xử lý và không gian bộ nhớ càng tốt. Các cấu trúc dữ liệu được triển khai bằng cách sử dụng các kiểu dữ liệu, các tham chiếu và các phép toán trên đó được cung cấp bởi một ngôn ngữ lập trình.
- Tri thức đó đã dẫn đến sự nổi lên của nhiều ngôn ngữ lập trình và phương pháp thiết kế được hình thức hóa, mà trong đó, nhân tố tổ chức quan trọng là các cấu trúc dữ liệu chứ không phải các thuật toán. Đa số ngôn ngữ có một tính năng thuộc dạng hệ thống module cho phép các cấu trúc dữ liệu được tái sử dụng an toàn trong các ứng dụng khác nhau, bằng cách dùng các giao diện có điều khiển để che các chi tiết cài đặt đã được kiểm thử. Đặc biệt, các ngôn ngữ lập trình hướng đối tượng như C++ và Java sử dụng lớp (class) cho mục đích này.
- Vì cấu trúc dữ liệu có tính chất quyết định đối với các chương trình chuyên nghiệp nên có rất nhiều hỗ trợ về cấu trúc dữ liệu trong các thư viện chuẩn của các ngôn ngữ lập trình hiện đại, ví dụ thư viện mẫu chuẩn của C++, Java API, và Microsoft .NET Framework.
- Các cấu trúc xây dựng căn bản của hầu hết các cấu trúc dữ liệu là mảng (array), bản ghi (record), tổ hợp phân biệt(?) (discriminated union), và tham chiếu (reference). Ví dụ, tham chiếu khả rỗng (có thể có giá trị null) là một kết hợp của tham chiếu và cấu trúc discriminated union, và cấu trúc dữ liệu liên kết đơn giản nhất, danh sách liên kết, được xây dựng từ các bản ghi và các tham chiếu khả rỗng.

### Các cấu trúc dữ liệu thường dùng
- Mảng (cấu trúc dữ liệu) (array list)
  + Mảng (Array) là một trong các cấu trúc dữ liệu quan trọng nhất. Mảng có thể lưu giữ một số phần tử cố định và các phần tử này nền có cùng kiểu. Hầu hết các cấu trúc dữ liệu đều sử dụng mảng để triển khai giải thuật. Dưới đây là các khái niệm quan trọng liên quan tới Mảng.
    - Phần tử: Mỗi mục được lưu giữ trong một mảng được gọi là một phần tử.
    - Chỉ mục (index): Mỗi vị trí của một phần tử trong một mảng có một chỉ mục số được sử dụng để nhận diện phần tử.
  + Mảng gồm các bản ghi có kiểu giống nhau, có kích thước cố định, mỗi phần tử được xác định bởi chỉ số
  ##### Ưu điểm của mảng
  + Truy cập phần tử với thời gian hằng số
  + Sử dụng bộ nhớ hiệu quả
  + Tính cục bộ về bộ nhớ
  ##### Nhược điểm của mảng
  + Không thể thay đổi kích thước của mảng khi chương trình đang thực hiện.

- Ngăn xếp (stack)
  + Một ngăn xếp là một cấu trúc dữ liệu trừu tượng (Abstract Data Type – viết tắt là ADT), hầu như được sử dụng trong hầu hết mọi ngôn ngữ lập trình. Đặc điểm của ngăn xếp là LIFO (last in first out) - có nghĩa là vào sau ra trước. Đặt tên là ngăn xếp bởi vì nó hoạt động như một ngăn xếp trong đời sống thực, ví dụ như một cỗ bài hay một chồng đĩa, …

- Hàng đợi (queue)
  + Hàng đợi (Queue) là một cấu trúc dữ liệu trừu tượng. Đặc điểm của hàng đợi là FIFO (first in first out) - có nghĩa là vào trước ra trước. Đặt tên là hàng đợi bởi vì nó là một cái gì đó tương tự như hàng đợi trong đời sống hàng ngày (xếp hàng).
  + Khác với ngăn xếp, hàng đợi là mở ở cả hai đầu. Một đầu luôn luôn được sử dụng để chèn dữ liệu vào (hay còn gọi là sắp vào hàng) và đầu kia được sử dụng để xóa dữ liệu (rời hàng). Cấu trúc dữ liệu hàng đợi tuân theo phương pháp First-In-First-Out, tức là dữ liệu được nhập vào đầu tiên sẽ được truy cập đầu tiên.
  
- Bảng năm (hash table)
  + Cấu trúc dữ liệu Hash Table là một cấu trúc dữ liệu lưu giữ dữ liệu theo cách thức liên hợp. Trong Hash Table, dữ liệu được lưu giữ trong định dạng mảng, trong đó các giá trị dữ liệu có giá trị chỉ mục riêng. Việc truy cập dữ liệu trở nên nhanh hơn nếu chúng ta biết chỉ mục của dữ liệu cần tìm.
  + Do đó, với loại cấu trúc dữ liệu Hash Table này thì các hoạt động chèn và hoạt động tìm kiếm sẽ diễn ra rất nhanh, bất chấp kích cỡ của dữ liệu là bao nhiêu. Hash Table sử dụng mảng như là một kho lưu giữ trung gian và sử dụng kỹ thuật Hash để tạo chỉ mục tại nơi phần tử được chèn vào.

- Danh sách liên kết (linked list)
  + Một danh sách liên kết (Linked List) là một dãy các cấu trúc dữ liệu bao gồm một nhóm các nút (node) được kết nối với nhau thông qua các liên kết (link) tạo thành một chuỗi. Mỗi nút gồm dữ liệu ở nút đó và tham chiếu đến nút kế tiếp trong chuỗi.
  + Danh sách liên kết là cấu trúc dữ liệu được sử dụng phổ biến thứ hai sau mảng.
  + Dưới đây là các khái niệm cơ bản liên quan tới Danh sách liên kết:
    - Link (liên kết): mỗi link của một Danh sách liên kết có thể lưu giữ một dữ liệu được gọi là một phần tử.
    - Next: Mỗi liên kết của một Danh sách liên kết chứa một link tới next link được gọi là Next.
    - First: một Danh sách liên kết bao gồm các link kết nối tới first link được gọi là First.

- Cây (cấu trúc dữ liệu) (tree)
  + Cấu trúc dữ liệu cây biểu diễn các nút (node) được kết nối bởi các cạnh. Chúng ta sẽ tìm hiểu về Cây nhị phân (Binary Tree) và Cây tìm kiếm nhị phân (Binary Search Tree) trong phần này.
  + Cây nhị phân là một cấu trúc dữ liệu đặc biệt được sử dụng cho mục đích lưu trữ dữ liệu. Một cây nhị phân có một điều kiện đặc biệt là mỗi nút có thể có tối đa hai nút con. Một cây nhị phân tận dụng lợi thế của hai kiểu cấu trúc dữ liệu: một mảng đã sắp thứ tự và một danh sách liên kết (Linked List), do đó việc tìm kiếm sẽ nhanh như trong mảng đã sắp thứ tự và các thao tác chèn và xóa cũng sẽ nhanh bằng trong Linked List.

- Đồ thị (cấu trúc dữ liệu) (graph)
  + Một đồ thị (Graph) là một dạng biểu diễn hình ảnh của một tập các đối tượng, trong đó các cặp đối tượng được kết nối bởi các link. Các đối tượng được nối liền nhau được biểu diễn bởi các điểm được gọi là các đỉnh (vertices), và các link mà kết nối các đỉnh với nhau được gọi là các cạnh (edges).
  + Các hình toán học có thể được biểu diễn trong cấu trúc dữ liệu. Chúng ta có thể biểu diễn một hình bởi sử dụng một mảng các đỉnh và một mảng hai chiều của các cạnh. Trước khi tiếp tục, chúng ta tìm hiểu một vài khái niệm quan trọng sau:
    - Đỉnh (Vertex): Mỗi nút của hình được biểu diễn như là một đỉnh.
    - Cạnh (Edge): Cạnh biểu diễn một đường nối hai đỉnh.
    - Kề nhau: Hai đỉnh là kề nhau nếu chúng được kết nối với nhau thông qua một cạnh.
    - Đường: Đường biểu diễn một dãy các cạnh giữa hai đỉnh.
