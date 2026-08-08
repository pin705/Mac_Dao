# Chính Sách Quyền Riêng Tư — Mặc Đạo

**Cập nhật lần cuối: 07/08/2026**

Tài liệu này áp dụng cho ứng dụng **Mặc Đạo** (`com.pin705.macdao`) trên Google Play.

> **Đang đăng tại** `https://github.com/pin705/Mac_Dao/blob/main/privacy-policy.md`. Repo đó
> **phải giữ public vĩnh viễn** — chuyển private là link chết, và app có link chính sách hỏng bị
> gỡ chứ không được nhắc.
>
> **KHI COPY SANG ĐÓ, PHẢI COPY CẢ BỐN DÒNG TIÊU ĐỀ Ở TRÊN.** Bản đăng lần đầu bị cắt mất phần
> đầu và bắt đầu thẳng từ "## 1." — nên tài liệu không còn chỗ nào **tự xưng nó là chính sách
> quyền riêng tư của app nào**. Người duyệt mở link ra và phải tự suy luận; đó là một trong những
> lý do bị trả về hay gặp nhất, và nó không nằm ở nội dung mà ở phần bị bỏ rơi lúc copy.
>
> Nội dung dưới đây mô tả đúng những gì code đang làm tại thời điểm ghi, đọc ra từ
> `net/providers/nakama_provider.gd`. **Sửa backend thì phải sửa lại file này VÀ khai lại form
> Data Safety** — khai sai form là một trong số ít lý do Play gỡ app thẳng, không nhắc trước.

---

## 1. Chúng tôi thu thập gì

Mặc Đạo không có màn đăng ký, không hỏi tên thật, email, số điện thoại hay bất kỳ giấy tờ nào.

Khi trò chơi kết nối tới máy chủ, những dữ liệu sau được gửi đi:

| Dữ liệu | Là gì | Vì sao cần |
|---|---|---|
| **Mã định danh thiết bị** | Chuỗi Android ID do hệ điều hành cấp (`OS.get_unique_id()`) | Là **toàn bộ danh tính tài khoản** của bạn. Không có nó thì không có cách nào nhận ra tiến trình chơi thuộc về ai |
| **Tiến trình chơi** | Cảnh giới, tu vi, trang bị, vật phẩm, nhiệm vụ | Đồng bộ để không mất khi đổi máy, và để chống sửa dữ liệu |
| **Tên nhân vật** | Tên bạn tự đặt trong game | Hiển thị trên bảng xếp hạng và trong Tiên Đấu |
| **Lực chiến, điểm xếp hạng** | Hai con số | Ghép đối thủ và xếp bảng |

**Không thu thập**: tên thật, email, số điện thoại, địa chỉ, vị trí, danh bạ, ảnh, tệp trên máy,
thông tin thanh toán, lịch sử duyệt web, dữ liệu sức khoẻ.

Trò chơi **không xin bất kỳ quyền hệ thống nào** ngoài quyền truy cập mạng
(`android.permission.INTERNET`) — điều này kiểm chứng được bằng cách xem danh sách quyền của app
trong phần Cài đặt của điện thoại.

## 2. Không quảng cáo, không theo dõi

Mặc Đạo **không nhúng SDK quảng cáo, không có bộ đếm phân tích của bên thứ ba, và không bán hay
chia sẻ dữ liệu cho bất kỳ ai**. Không có mã theo dõi hành vi phục vụ quảng cáo.

Dữ liệu chỉ đi tới máy chủ của chính trò chơi.

## 3. Chơi ngoại tuyến

Mặc Đạo chơi được **hoàn toàn không cần mạng**. Ở chế độ đó, dữ liệu nằm nguyên trên máy bạn và
không có gì được gửi đi. Đổi lại, mất máy là mất tiến trình vì không có bản sao nào ở nơi khác.

## 4. Lưu ở đâu, bao lâu

Dữ liệu đồng bộ được lưu trên máy chủ trò chơi và truyền qua kết nối mã hoá HTTPS. Chúng tôi giữ
dữ liệu chừng nào tài khoản còn tồn tại.

## 5. Xoá dữ liệu

Bạn có quyền xoá toàn bộ dữ liệu gắn với thiết bị của mình, và làm được **ngay trong trò chơi**:

> **Thiết Lập → Dữ Liệu → Xoá toàn bộ dữ liệu**

Thao tác này xoá vĩnh viễn tiến trình tu luyện, trang bị, hòm thư, ví và thứ hạng — **cả trên
máy chủ lẫn trên máy** — và không thể khôi phục. Thiết lập âm thanh, cỡ giao diện và tuỳ chọn
giảm chuyển động được giữ lại, vì chúng không gắn với tài khoản và không mô tả bạn.

Hai cách khác:

- **Gỡ cài đặt** xoá dữ liệu lưu trên máy, nhưng **không** xoá dữ liệu trên máy chủ.
- Không mở được trò chơi thì gửi yêu cầu tới địa chỉ ở mục 8. Chúng tôi xử lý trong vòng 30 ngày
  và xoá hẳn, không giữ bản lưu trữ. Vì tài khoản gắn với mã thiết bị chứ không phải email, hãy
  nói rõ bạn đang dùng thiết bị nào và tên nhân vật là gì, để chúng tôi tìm đúng bản ghi.

## 6. Trẻ em

Mặc Đạo không nhắm tới trẻ em dưới 13 tuổi và không cố ý thu thập dữ liệu của trẻ em. Nếu bạn là
phụ huynh và tin rằng con mình đã cung cấp dữ liệu, hãy liên hệ để chúng tôi xoá.

## 7. Thay đổi chính sách

Khi chính sách thay đổi, ngày ở đầu tài liệu sẽ được cập nhật. Thay đổi làm mở rộng phạm vi dữ
liệu thu thập sẽ được thông báo trong trò chơi trước khi có hiệu lực.

## 8. Liên hệ

Mọi câu hỏi về chính sách này, hoặc yêu cầu xoá dữ liệu, gửi tới:

**Email: immortalforgesupport@gmail.com**

Địa chỉ này phải trùng với email liên hệ khai trong Google Play Console.
