# Oracle

## Mục Tiêu

Oracle nhằm mục đích người chơi luôn nhận được số lượng token xBlade nhận được khi chiến đấu và chi phí khi tạo Hero, vũ khí mới hợp lý tương xứng với giá trị xBlade/USD vào thời điểm đó.

Điều này chỉ ra rằng nếu giá trị đô la trên mỗi xBlade tăng, điều sau sẽ xảy ra:

* xBlade nhận được giảm
* xBlade cần để tạo Hero mới sẽ giảm
* xBlade cần để chế tạo Vũ Khí sẽ giảm
* xBlade cần để nâng cấp Vũ Khí sẽ giảm

Trong trường hợp giá xBlade tính bằng đô la giảm xuống dưới ngưỡng, các khoản thanh toán và yêu cầu xBlade sẽ tăng lên.

Nhà tiên tri đảm bảo rằng nếu người chơi thắng phần lớn các trận chiến hàng ngày, họ sẽ kiếm được nhiều xBlade hơn, đủ để trả chi phí xăng.

Tùy thuộc vào những thay đổi trong giá trị đô la của xBlade, Oracle sẽ tự động điều chỉnh các khoản thanh toán chiến đấu lên hoặc xuống.

## Lý do

Mục đích của việc sử dụng Oracle là giữ lại giá trị của đơn vị tiền tệ trong trò chơi với một chi phí cố định. Dường như có một quy định đối với số lượng mã thông báo xBlade lưu thông trong nền kinh tế. Vì lý do đó, sự gia tăng đáng kể về số lượng người dùng dẫn đến dòng chảy của tất cả xBlade trong hợp đồng.

Nhờ có Oracle, CryptoWar tạo ra mối quan hệ qua lại giữa người dùng đang hoạt động và giá trị tiền tệ của xBlade. Giả sử rằng giá xBlade tăng, nhu cầu về xBlade sẽ tăng lên, do mẫu vật của các tính năng mới của trò chơi hoặc lượng người chơi mới.

Nhà tiên tri trao quyền cho phí giao dịch chiến đấu cũng như phí đúc tiền cho NFT được giữ ở giá trị đồng đô la không đổi, cho phép người chơi mới tham gia vào trò chơi với phí vào cửa phải chăng ngay cả khi giá trị đô la của xBlade tăng.

## Tỷ lệ Oracle xBlade/Dollar&#x20;

Oracle tuân theo giá trị đô la hiện tại của xBlade và thay đổi giá xBlade tương ứng với tỷ lệ không được tiết lộ để giữ mọi thứ công bằng và không thiên vị giữa tất cả người chơi.

Cryptowar đang sử dụng Pancake Price Feed oracle. Để kiểm tra giá xBlade:&#x20;

* Truy cập [PancakeSwap xBlade page](https://pancakeswap.finance/swap?inputCurrency=0x27a339d9b59b21390d7209b78a839868e319301b\&outputCurrency=0xe9e7cea3dedca5984780bafc599bd69add087d56)
* Nhập vào 1 xBlade
* ![](<../../.gitbook/assets/image (2).png>)

![](broken-reference)

Khi số tiền được tính toán khác với giá trị đô la thực tế của xBlade, các khoản ưu đãi cho các khoản thanh toán và chi phí đúc tiền được mong đợi nếu Oracle cao hơn giá trị hiện tại của xBlade và ngược lại, giảm giá trị nếu thấp hơn.
