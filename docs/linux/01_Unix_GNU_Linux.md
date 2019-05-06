# Unix, GNU ,Linux : Nguồn gốc và sự khác biệt
> ## **UNIX**
<p align="center"><img src=https://i.imgur.com/dcuNhVm.png width=50%></p>
<center><i>Logo Unix</i></center>

- **Unix** là một hệ điều hành vốn ra đời đã từ rất lâu, tại phòng thí nghiệm **Bell Labs** của **AT&T**. Dự án được dẫn dắt bởi **Ken Thompson** và **Dennis Ritchie** , 2 nhà khoa học máy tính nổi tiếng.
- Công việc phát triển **Unix** chính thức được bắt đầu vào mùa hè năm 1969, và phiên bản đầu tiên của Unix được ra đời vào tháng 3 năm 1971, tiếp đó là phiên bản thứ 2 ra đời năm 1972. ( nếu bạn gõ lệnh date trên một máy Linux, hay trên MacOS ... bạn sẽ nhận được một con số gọi là Unix Timestamp. Con số này là số giây tính từ thời điểm 00:00:00 ngày 1 tháng 1 năm 1970. Còn tại sao lại là thời điểm ngày 1 tháng 1 năm 1970 thì chắc giờ bạn cũng có câu trả lời rồi nhỉ. Đó chính là thời thời điểm mà Unix đang nằm trong quá trình phát triển )
- Ken Thompson và Dennis Ritchie chính là 2 người đã tạo ra B, ngôn ngữ lập trình vốn được support ở Unix những phiên bản đầu. Sau đó, vào năm 1972, Ritchie đã viết lại ngôn ngữ B, cải thiện nó tốt hơn, để trở thành ngôn ngữ lập C, ngôn ngữ lập trình còn rất phổ biến cho đến tận ngày nay. Hầu hết các components của Unix sau này đều được viết bằng C.
- Những năm sau của thập niên 70, AT&T chia sẻ Unix cho những tổ chức giáo dục, hay tổ chức thương mại bên ngoài, từ đó dẫn đến sự ra đời của nhiều phiên bản Unix khác nhau. Nổi bật nhất trong số đó là phiên bản giáo dục được xây dựng bởi Computer Systems Research Group thuộc đại học California, Berkeley. Phiên bản này được biết đến rộng rãi với cái tên Berkeley Software Distribution, hay BSD.
- Ban đầu, BSD được xây dựng dựa trên codebase cũng như design của Unix, tuy nhiên càng về sau, các phiên bản của Unix và BSD càng có những điểm đặc trưng, khác biêt, dẫn đến việc xảy ra những "cuộc chiến" để trở thành "tiêu chuẩn" giữa phiên bản Unix BSD và phiên bản Unix của AT&T mang tên mã System V. Kết quả là phần thắng thuộc về System V. Các phiên bản BSD sau đó đã xích gần lại System V hơn với việc học tập và đưa vào những tiêu chuẩn chung đã được công nhận.
- Nhánh BSD đi đến hồi kết của quá trình phát triển lịch sử của nó, với sự ra đời và của các open source project như: FreeBSD, NetBSD và OpenBSD. Phiên bản cuối cùng của BSD được giới thiệu năm 1995. Trong khi đó, phiên bản cuối cùng của Unix được phát triển bởi Bell Laps, phiên bản Unix 10, được ra mắt vào năm 1989.
- Mặc dù phiên bản chính thức của Unix, BSD đã dừng phát triển từ lâu, thế nhưng những di sản mà chúng để lại là rất lớn cho đến ngày hôm nay. Rất nhiều hệ điều hành, từ close source cho đến open source đựa dựa trên 2 nhánh này.
- Phiên bản thương mại, close source nổi tiếng, thành công nhất, có lẽ chính là MacOS đình đám của Apple. MacOS cũng như các hệ điều hành khác của Apple hiện nay là iOS, watchOS, và tvOS đều được dựa trên nền tảng của BSD. Và MacOS cũng là một trong số ít các hệ điều hành được coi là Unix-like, khi có được chứng nhận Single UNIX Specification. 
> ## **GNU**
<center><img src=https://i.imgur.com/ZV3cMd1.png width=50%></center>

<center><i>Logo GNU</i></center>

- Tháng 9 năm 1983, Richard Stallman thông báo về sự ra đời của dự án GNU (GNU là viết tắt của từ GNU's not Unix)
- Mục tiêu của dự án GNU là tạo ra được một hệ điều hành miễn phí, giống Unix, nơi mà mọi người có quyền tự do copy, phát triển, chỉnh sửa và phân phối phần mềm, và việc tái phân phối là không bị giới hạn. (Nên nhớ, Unix và các phiên bản rẽ nhánh từ Unix ban đầu đều là close source và bị ràng buộc bản quyền)
- Năm 1985, Richard thành lập tổ chức Free Software Foundation, hay FSF, một tổ chức phi lợi nhuận muốn thúc đẩy sự tự do trong trong phát triển phần mềm.
- Project GNU đã tạo ra được rất nhiều sản phẩm quan trọng như GNU Compiler Collection (gcc), GNU Debugger, GNU Emacs text editor (Emacs), GNU build automator (make) ... Ngoài ra còn phải kể đến giấy phép nổi tiếng được sử dụng rộng rãi nhất hiện nay: GNU General Public License (GPL)
- GNU Project đã đạt được nhiều thành tựu lớn, tạo ra được nhiều công cụ tương tự như những gì có trên Unix. Tuy nhiên, GNU vẫn thiếu một thành phần quan trọng, mảnh ghép cuối cùng để nó trở thành một hệ điều hành hoàn chỉnh. Đó chính là Kernel, phần thực hiện công việc điều khiển, giao tiếp với các thiết bị phần cứng (CPU, RAM, Devices ...).
> ## **Linux**
<center><img src=https://i.imgur.com/1WYvIRm.png width=35%></center>
<center><i>Logo Linux</i></center>

- Ngày 25 tháng 8 năm 1991, một cậu sinh viên ở Phần Lan mang tên Linus Torvalds giới thiệu một sản phẩm cá nhân, sau này trở thành Linux Kernel.
- Project của Linus nhanh chóng nhận được sự chú ý cùng với đó là những đóng góp của nhiều cá nhân, tổ chức.
- Sự kết hợp giữa nhân Linux, với các phần mềm của GNU đã tạo ra một hệ điều hành hoàn chỉnh, hệ điều hành hoàn toàn miễn phí đầu tiên. Nó được mang tên GNU/Linux.
- Bản thân Linux chỉ là một Kernel, nó không phải là một hệ điều hành hoàn chỉnh. Hệ điều hành mà các bạn có thể vẫn đang sử dụng thực tế trên máy tính của mình có tên là GNU/Linux, nhưng có lẽ vì cái tên nó dài dòng nên người ta đã gọi ngắn gọn nó là Linux chăng. Việc lược bỏ đi GNU trong tên gọi hệ điều hành được cho là không công bằng, và đánh giá thấp vai trò của GNU. Tuy nhiên, biết sao được, nhiều người vẫn dùng cái tên Linux để thay cho tên gọi hệ điều hành GNU/Linux. Và khi nhắc đến Hệ Điều Hành Linux, ta cần hiểu đó là Hệ Điều Hành GNU/Linux. Trong series này tôi cũng sẽ sử dụng cách gọi đó, hệ điều hành Linux.
- Hệ điều hành Linux hoàn toàn không sử dụng chung, hay kế thừa bất kỳ phần code nào của Unix, hay BSD. Nó được xây dựng mới hoàn toàn bởi Linus và GNU Project để có thể trở thành ... một phiên bản clone của Unix. Chính vì thế Linux và các hệ điều hành con cháu của Unix hiện nay (như MacOS chẳng hạn) có rất nhiều điểm giống nhau.
> ## **Unix-like**
- MacOS là một trong số ít các hệ điều hành được chứng nhận của Single UNIX Specification (SUS), và được coi là một hệ điều hành Unix-like.
- Hiện thương hiệu UNIX thuộc bản quyền của tổ chức The Open Group (chú ý là các chữ cái trong tên thương hiệu UNIX đều được viết hoa, trong khi để chỉ hệ điều thành thì ta có thể viết Unix hoặc UNIX).
- Khái niệm "Unix-like" vốn được dùng để chỉ những hệ điều hành có được chứng nhận SUS, và có thể sử dụng thương hiệu UNIX.
- Linux không phải 1 hệ điều hành "Unix-like" . Đã từng có dự án giúp Linux đạt được SUS, nhưng cuối cùng không đi đến đâu cả, và hiện tại các Distro Linux cũng không được phép sử dụng trademark UNIX.
- Có thể chia ra làm 3 loại Unix-like:
    - Genetic UNIX: Chỉ những hệ điều hành có liên quan trực tiếp đến codebase của phiên bản Unix của Bell Labs.
    - Trademark UNIX: Những hệ điều hành thoả mãn yêu cầu SUS và có thể sử dụng thương hiệu UNIX.
    - Functional UNIX: Những hệ điều hành "hoạt động giống Unix", và Linux có thể được xếp vào loại này.