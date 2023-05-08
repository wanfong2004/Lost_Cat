# Lost_Cat

## Giới thiệu
### Về tác giả

- Họ và tên: Lương Thế Quyền
- MSSV: 22021156
- Lớp: K67CB

### Về dự án

Đây là một dự án cuối kì của bộ môn Lập trình nâng cao và cũng là dự án game đầu tay của mình. Tuy vẫn còn nhiều sai sót và đồ họa cũng chưa được đẹp nhưng đó đều công sức quý báu mà mình bỏ ra, mong các bạn sẽ có một trải nghiệm thú vị khi chơi game.

Trò chơi được lấy ý tưởng từ tựa game mobile Chú mèo không tên (Nhân vật chính của chúng ta cũng được xây dựng từ chú mèo ở trong game).

Trò chơi được lập trình bằng ngôn ngữ C++ tích hợp cùng thư viện đồ họa SDL.

## Cài đặt trò chơi

- Bước 1: Tải file zip về và giải nén
- Bước 2: Mở project và chạy file Game.exe
- Bước 3: Trải nghiệm trò chơi

## Về trò chơi

### Cốt truyện
Um... Tôi là ai?... Đây là đâu?

NPC: Cậu không nhớ mình là ai sao? Cậu đã xuất hiện từ cánh cổng đó và ngất lịm đi từ lúc đó đến giờ à.

Cổng?... Kí ức của tôi...

NPC: Vậy thì có thể trong quá trình cậu đến đây, kí ức của cậu đã bị đánh rơi và thất lạc ở đâu đó mất rồi. Ở đây, mỗi kí ức sẽ có hình dạng là một quả cầu lấp lánh, bởi vì chúng đều là những tạo vật tinh túy và vô cùng quý giá.

Tôi muốn về nhà...

NPC: Được thôi. Cánh cổng đó sẽ dẫn cậu đến những nơi mà nó biết cậu thật sự đang cần. Nhưng trước hết cậu phải đi tìm được kí ức của cậu đã. Cẩn thận nhé, không phải ở đâu cũng thân thiện với yên bình như ở đây đâu.

Um... Cảm ơn...

NPC: Không có gì. Bảo trọng nhé!

### Di chuyển nhân vật

- A: Di chuyển sang trái
- D: Di chuyển sang phải
- W: Nhảy
- SPACE: Dịch chuyển tức thời (Chỉ khi đứng gần bộ dịch chuyển tức thời)
* Đặc biệt: Khi nhảy lên đám mây sẽ có hiệu ứng nhảy cao hơn

### Luật chơi

Trò chơi bao gồm 3 màn chơi. Ở mỗi màn, nhiệm vụ của ta là đi thu thập các mảnh kí ức (đại diện bằng quả cầu nhỏ phát sáng) và sau đó đi tới cánh cổng không gian (chỉ xuất hiện sau khi đã thu thập được kí ức) để sang màn tiếp theo.

Trò chơi sẽ kết thúc khi ta chạm vào các Mối Đe Dọa và sẽ tự bắt đầu lại màn chơi sau 3 giây

### Mối Đe Dọa

* Gai/ Chông băng/ Dung nham
* Bẫy gai rơi
* Hog - sẽ tự động tăng tốc và lao đến vị trí người chơi
* Bat - bay từ từ về vị trí người chơi (xác định sau mỗi 1 giây)

## Các kĩ thuật để tạo nên trò chơi

Xây dựng và xử lý va chạm với Tile Map.

Xây dựng các class, object. Sử dụng lớp kế thừa, quản lý và liên kết các class.

Xử lý đồ họa, tương tác âm thanh.

Sử dụng kiến thức toán học, lí học để tạo nên các chuyển động của nhân vật, bẫy rơi và quái.

Game hoạt động mượt mà trơn tru.

* Trong tương lai, game còn có thể được cải tiến bằng cách thêm các tính năng, thêm quái vật, thêm bản đồ...

### Tài liệu tham khảo

LazyFoo.net

YouTube.com

Phattrienphanmem123az.com

### Sau cùng, xin chân thành cảm ơn thầy Trần Trường Thủy , Thầy Tạ Việt Cường của trường Đại học Công nghệ - Đại học Quốc gia Hà Nội đã tạo ra dự án và cho mình kiến thức để tạo ra game này, xin cảm ơn những người đã trợ giúp mình trong quá trình lập trình và phát triển trò chơi 

#### Thông tin liên hệ: luongquyenn03022004@gmail.com
