# Marketplace

Khi tham gia vào trò chơi, người chơi sở hữu tài sản của riêng mình, chẳng hạn như nhân vật và vũ khí được tích trữ trong trò chơi và được đúc trong ERC-721 NFTs. Những tài sản này có thể được giao dịch tự do với những người chơi khác. Tất cả các giao dịch trong trò chơi đều được thực hiện trên một thị trường độc quyền thuộc sở hữu của CryptoWar, trong đó người chơi được cấp quyền tham gia và mua NFT của họ để loại bỏ các gian lận lớn trong khi thực hiện các giao dịch thông qua việc sử dụng các hợp đồng NFT.

## Chấp thuận sử dụng xBlade

Sau khi mua NFT trên thị trường, hệ thống sẽ tự động gửi thông báo về biểu mẫu chấp thuận giao dịch cho người chơi, như minh họa trong ảnh sau:

Đó là do CryptoWar không được cấp quyền chi tiêu xBlade trực tiếp từ ví MetaMask của người chơi. Do đó, người chơi có nghĩa vụ phải xin phép bất cứ khi nào họ cần thực hiện một giao dịch thị trường, giao dịch này có vẻ hoàn toàn khác với xác nhận mua hàng thực tế. Sau khi hoàn tất phê duyệt giao dịch, người chơi sẽ nhận được thông báo chính thức về quá trình mua bán trên thị trường.

![](<../.gitbook/assets/11 (1).jpg>)

{% hint style="info" %}
Nên có kế hoạch mua hàng chiến lược cho từng mặt hàng trên thị trường; nếu không người chơi sẽ nhận được lỗi tính phí gas trong trường hợp họ thử đồ do người khác mua.
{% endhint %}

## Thuế

Để niêm yết một NFT, một khoản phí gas nhất định sẽ được yêu cầu để thực hiện các giao dịch trong trò chơi nhằm mục đích chuyển NFT sang hợp đồng thị trường.

Thuế tính khi mua NFT trên thị trường ở mức 10% do người mua trả. Đối với mỗi giao dịch mua trên thị trường, thuế được bao gồm trong giá niêm yết của NFT và thuế 10% được chuyển đến hợp đồng để thanh toán cho xBlade thông qua chiến đấu.

## Khóa Giao Dịch

Các nhân vật được liệt kê và mua qua thị trường hoặc giao dịch thông qua hợp đồng thông minh sẽ bị khóa trong vòng 24 giờ trước khi mặt hàng được phép niêm yết hoặc giao dịch trở lại.

{% hint style="info" %}
0,285 lỗi phí gas sẽ được tính khi nỗ lực liên tục để liệt kê hoặc giao dịch một mặt hàng bị khóa. Vui lòng không thực hiện bất kỳ giao dịch nào trong thời gian này.
{% endhint %}

## Browse NFTs

![](https://github.com/ElasticBTC-XBT/CryptoWar-Wiki/tree/534c0aa13bb170622866cfb21d20deb8b8953046/.gitbook/assets/browse-nfts.png)

Tab Browse NFTs cho phép người chơi bỏ qua các nhân vật và vũ khí hiện có. Nhấp vào “Nút bộ lọc” trong trường hợp người chơi muốn liệt kê các tùy chọn có sẵn cho cả nhân vật và vũ khí. Do không có phân trang, chỉ 60 kết quả đầu tiên sẽ được hiển thị trong kết quả nghiên cứu. Người chơi được yêu cầu lấy ID nội dung và dán nó vào Tìm kiếm NFT như được minh họa trong hình sau trong trường hợp họ tìm cách mua trực tiếp NFT được niêm yết của ai đó trên thị trường.

## Search NFTs

![](https://github.com/ElasticBTC-XBT/CryptoWar-Wiki/tree/534c0aa13bb170622866cfb21d20deb8b8953046/.gitbook/assets/search-nfts.png)

If Nếu người chơi có thể truy cập vào ID tài sản của NFT đã mua hoặc vào ví của người bán, họ có thể bỏ qua chúng ngay trong tab Tìm kiếm NFT.

Sau đó, chỉ cần dán ID nội dung vào hộp văn bản và chọn "ID nhân vật tìm kiếm" hoặc "ID vũ khí tìm kiếm" để phát hiện NFT mong muốn của người chơi.

Trong trường hợp người chơi có địa chỉ ví của người bán, họ có thể chèn địa chỉ đó vào hộp văn bản và chọn “Nhân vật của người bán” hoặc “Vũ khí của người bán” để xem tất cả các nhân vật và vũ khí hiện có của họ. Hơn nữa, người chơi có thể sử dụng tab này để theo dõi các nhân vật và vũ khí hiện tại của họ, cùng với giá đã bao gồm thuế của chúng.

Người chơi có quyền hủy niêm yết mặt hàng hoặc điều chỉnh giá niêm yết của nó khi chọn một NFT được liệt kê. Tuy nhiên, điều đáng chú ý là người chơi nên đặt giá mới vào hộp văn bản sau quá trình điều chỉnh giá, sau đó sẽ bị đánh thuế ở mức 10% trước khi mặt hàng được niêm yết lại trên thị trường.

{% hint style="info" %}
Điều quan trọng cần lưu ý là việc hủy niêm yết một mặt hàng dẫn đến khóa giao dịch 24 giờ. Vì lý do đó, người chơi được khuyến cáo không tham gia vào bất kỳ giao dịch nào hoặc liệt kê lại vật phẩm.
{% endhint %}

## List NFTs

![](https://github.com/ElasticBTC-XBT/CryptoWar-Wiki/tree/534c0aa13bb170622866cfb21d20deb8b8953046/.gitbook/assets/list-nfts.png)

Người chơi có thể liệt kê NFT của riêng họ trên thị trường bằng cách sử dụng tab Danh sách NFT. Giá họ đang cố gắng kiếm được từ việc bán NFT của họ sẽ được cộng thêm 10% thuế để trở thành giá niêm yết. Sau khi danh sách của họ, NFT được liệt kê của họ sẽ được chuyển đến thị trường và các vị trí của họ trong ví của người chơi sẽ được giải phóng để đúc NFT mới. Việc hủy niêm yết sẽ trả lại NFT cho các vị trí của họ trong ví của người chơi trừ khi chúng đã đầy (trong trường hợp đó, việc hủy niêm yết sẽ không khả dụng). Xin lưu ý rằng việc niêm yết sẽ phải chịu một khoản phí gas tương tự như giao dịch. CryptoWar cũng sẽ yêu cầu người chơi cho phép sử dụng CBC hoặc CBW của họ.
