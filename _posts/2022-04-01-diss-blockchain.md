---
layout: post
title: "Blockchain không thần thánh như chúng ta tưởng."
author: quang
categories: [review, chem-gio]
image: assets/images/blockchain-break.jpeg
beforetoc: "Bài viết dựa trên hiểu biết và góc nhìn cá nhân của tác giả, mọi ý kiến đóng góp có thể để lại bên dưới."
featured: true
hidden: true
comments: true
---

Trào lưu Blockchain đang rất rầm rộ, nó là một thuật ngữ mà bạn có thể dùng để tăng 200% độ khủng khiếp của một dự án. Ấy vậy, nói Blockchain là một công nghệ đỉnh cao, là tương lai của nhân loại thì tôi nghĩ không phải, ít nhất là cho tới hiện tại. Điểm yếu của nó không xuất phát từ yếu tố công nghệ mà là vấn đề về vận hành.

#### Vậy Blockchain là gì?

Để trình bày chính xác về cách Blockchain hoạt động như thế nào từ a tới z thì trong một bài viết là không đủ. Nên để minh họa nhanh hãy thử lấy ví dụ về ứng dụng cơ bản của blockchain là tiền số. Một ngày đẹp trời <strong>A</strong> muốn chuyển một số tiền <em>k</em> cho <strong>B</strong>, tuy nhiên việc sử dụng tiền mặt không được thuận tiện cho lắm nên <strong>A</strong> quyết định chuyển tiền cho <strong>B</strong> qua dịch vụ của ngân hàng. Ngân hàng lúc này sẽ đóng vai trò trung gian đảm bảo rằng <strong>A</strong> sử hữu số tiền <em>k</em> và đã chuyển số tiền <em>k</em> qua cho <strong>B</strong> đồng thời <strong>B</strong> cũng đã nhận được số tiền đó, những thông tin này được ngân hàng đảm bảo tính chính xác và có thể truy hồi lại sau này.

Cũng trong tình huống gửi tiền như vậy, <strong>A</strong> và <strong>B</strong> không thông qua ngân hàng nữa mà dùng blockchain (bitcoin chẳng hạn). Blockchain có thể hiểu hí họa là một <em>"hội đồng"</em> gồm những người: <strong>C,D,E...Z</strong>, mỗi người trong nhóm có một cuốn sổ, khi A chuyển số tiền <em>k</em> qua cho <strong>B</strong>, các thành viên trong <em>"hội đồng"</em> rồng rắn ghi chép lịch sử giao dịch này lại. Vì nhiều người có công việc riêng không online suốt được nên chỉ cần 50% số người trong <em>"hội đồng"</em> xác nhận giao dịch này hợp lệ thì coi như việc <strong>A</strong> chuyển tiền cho <strong>B</strong> thành công. Theo các chuyên gia, nếu số lượng người trong hội đồng đủ lớn, việc <em>hách</em> hay <em>pha ke</em> một giao dịch nào là rất khó và hầu như bất khả thì, nhưng mà nhớ phải nhấn mạnh từ <strong>đủ lớn</strong> nhé.

Rất đơn giản phải không, blockchain chuyển việc xác thực từ tập trung(ngân hàng) sang phi tập trung(<em>"hội đồng"</em>). Ấy vậy một câu hỏi đặt ra, khi ngân hàng xác nhận việc chuyển tiền, họ có thu phí, hoặc nếu không thu phí họ có thể kiếm lợi nhuận bằng cách sửa dụng tiền mà người dùng đã gửi vào ngân hàng để đầu tư hoặc cho vay, nói chung trong hoàn cảnh nào thì ngân hàng cũng có lợi ích. Quay lại với <em>"hội đồng"</em> blockchain, nhóm người này phải hoạt động 24/7, quần quật ghi ghi chép chép cho một nùi giao dịch. <em>"Hội đồng"</em> của chúng ta không phải một tổ chức phi lợi nhuận do đó họ không thể nào làm free được. Vậy những ai sẵn sàng tham gia vào <em>"hội đồng"</em>, và làm sao họ để họ có thu nhập?

#### Các anh thợ mỏ cần cù

![miner]({{ site.baseurl }}/assets/images/miner.jpg)

Đúng vậy, câu trả lời là các anh thở mỏ cần cù. Các anh là những thanh niên lực lưỡng cơ bắp cuồn cuộn, công việc chính của các anh phải làm là chép sổ, và nhận tiền công cho việc này. Mà khoan, việc chép sổ này dễ quá cần gì thanh niên lực lưỡng, thế là rất nhiều người già trẻ gái trai hò nhau đi chép sổ kiếm tiền. Công việc chép sổ quá là dễ luôn, ai cũng làm được, mà nhiều người làm quá thì trả tiền cho họ như thế nào đây? Trả nhiều tiền quá thì tốn kém, ít quá thì chả ai làm. Giải pháp là phải làm gì đó để tăng độ khó cho game lên, để chỉ những anh thợ cơ bắp mới làm được, và họ sẽ được trả công đủ tốt để chấp nhận công việc. Vậy là một ý tưởng "thiên tài" được đưa ra: Bắt các thợ mỏ vừa "hít đất" vừa chép sổ.

Hàng triệu máy tính(dân gian hay gọi là trâu cày) trên thế giới tham gia vào mạng lưới đào mỏ hiện nay đang vừa "hít đất" vừa chép sổ. Chép sổ thì rõ rồi, còn "hít đất" nghĩa đen là gì? Với một vài đồng tiền ảo nổi tiếng như Bitcoin, Ethereum thì "hít đất" gần giống với việc "hách" pass wifi. Nghe có vẻ hơi phèn, mà cơ bản thì đúng là thế thật. Hơi ngoài lề xíu thì "hách" pass wifi được thược hiện qua các bước như sau:

- Bằng một vài thủ thuật đặc biệt "hách cơ" sẽ yêu cần router gửi một gói tin có chứa mật khẩu đã được hash trong đó.
- Khi lấy được đoạn mật khẩu đã được hash này, "hách cơ" sẽ mò pass wifi bằng cách hash tất cả các mật khẩu có thể có để đối chiếu với mật khẩu hash gốc.

Còn quá trình đào mỏ sẽ qua các bước như này:

- Các thợ mỏ sẽ được cung cấp một đoạn hash(giống như đoạn mật khẩu được hash ở trên) được tạo ra từ một giá trị cụ thể ban đầu.
- Các thợ mỏ lúc này sẽ tranh nhau đi mò, lấy tất cả các giá trị có thể có, hash nó rồi đối chiếu với đoạn hash được cho, ai mò ra đầu tiên thì được thưởng.

#### Gót chân Achilles

Vậy công việc mà các trâu cày thực hiện hằng ngày, tốn cả tấn điện, làm độn giá GPU lên cao chót vót lại là một quá trình vô nghĩa, tốn kém và không mang lại bất cứ một giá trị gì cho nhân loại. Mục đích chính chỉ để tăng độ khó cho việc xác thực giao dịch(ghi sổ). Biết là vô nghĩa nhưng vẫn phải cắn răng mà làm thôi, vì nếu không vận hành như thế thì lấy ai mà "chép sổ" cho.

Đó là điểm yếu chí mạng của blockchain, vấn đề về vận hành. Hiện nay có lẽ nhiều giả pháp đã được đưa ra, mà làm được tới đâu thì nói thật tôi cũng không biết, có lẽ thêm vài nẵm nữa một ý tưởng "thiên tài" nào đó sẽ lại được đề xuất. Còn hiện tại thì với những Bitcoin hay Ethereum thì vấn đề vẫn còn đó.

#### Ý tưởng thiên tài

<figure>
    <img src="{{ site.baseurl }}/assets/images/word-image-71.jpeg"
         alt="Axie Infinity"
         style="display: block;margin: 0 auto;">
    <figcaption style="text-align:center;"><small>Nhân vật trong game Axie Infinity.</small></figcaption>
</figure>

Ngày 31/03/2022, một sự kiện khiến tôi nảy sinh ý tưởng viết blog xàm xí này đó là vụ Axie Infinity(một game blockchain) bị trộm đột nhập lấy mất 600 triệu kim Mỹ tiền số. Câu hỏi là thế quái nào blockchain an toàn như thế mà vẫn bị "hách". Thì hóa ra trước kia Axie Infinity sử dụng nền tảng blockchain dựa trên ETH, cơ mà ETH nó charge phí cao qua, mà lại còn chậm nữa, game cả trăm triệu người chơi nên quá trình hoạt động vừa lâu vừa tốn kém.

Thế là một ý tưởng thiên tài được đưa ra, Axie Infinity tự chế một nền tảng blockchain riêng, gọi là Ronin. Mấu chốt nằm ở chỗ, nền tảng của họ vận hành trên 9 node được setup sẵn, nghĩa là chỉ có 9 con trâu cày phục vụ cho hệ thống. Việc chỉ có 9 node giúp cho hệ thống chạy nhanh như máy điện, lại không tốn phí, quá hợp lý. Cơ mà cũng vì việc chỉ có 9 node khiến cho họ bị trộm mất 600 triệu kim Mỹ. Như đã nói ở trên, blockchain chỉ an toàn khi số lượng node tham giam trong quá trình xác thực giao dịch phải đủ lớn, và con số 9 tất nhiên không phải là số lớn. Xưa đi học phân tích độ phức tạp thuật toán, O(n) là O(n), mà O(2n) cũng vẫn là O(n), mà O(9n) thì vẫn là O(n) thôi. 9 node lúc này cũng không khác 1 node là bao.

Hậu quả của việc chỉ setup cố định 9 node là anh "hách cơ" vui tính nào đó đã đánh ngất hơn một nửa trong số 9 node này và ẵm đi một đống ETH trị giá 600 củ kim Mỹ. Đó là một dẫn chứng thực tế về điểm yếu trong quá trình vận hành của blockchain.

#### Vậy blockchain là đồ bỏ

Gọi blockchain là thứ vô tích sự, phá hoại môi trường, hấp diêm con heo đẩy bà già xuống biển thì cũng hơi quá khắt khe. Bản chất blockchain là một công nghệ, mà công nghệ thì không có tội, lỗi tại con người cường điệu, phù phiếm và đẩy nó đi xa giá trị thực tế quá mức cần thiết.
