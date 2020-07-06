# **UPLOAD VÀ DOWNLOAD EXTENSIONS**

**Gist** là nơi lưu trữ các cài đặt, extensions mà bạn có thể làm việc ở bất cứ đâu mà không cần phải lúc nào chuyển chỗ xem ngồi tìm kiếm từng thứ cài đặt lại dẫn đến mất nhiều thời gian.

Vì lý do trên nên **Gist** là lựa chọn cần thiết và ở trong **Visual Studio Code** có extension hỗ trợ việc upload, download các extensions đã cài trong VSC là `Settings Sync` .

### **Giao diện cần tìm**

---

![extension-settings-sync](/assets/img/extension-settings-sync.png)

---

![extension-settings-sync-content](/assets/img/extension-settings-sync-content.png)

---

### **Phím tắt**

1. Upload Key : `Shift + Alt + U`
2. Download Key : `Shift + Alt + D`

(trên macOS : `Shift + Option + U` / `Shift + Option + D`)

Với lần đầu Upload thì nó sẽ hiển thị thêm giao diện login, chọn nút `LOGIN WITH GITHUB`.

---

![extension-settings-sync-login-button](/assets/img/extension-settings-sync-login-button.png)

---

![extension-settings-sync-login](/assets/img/extension-settings-sync-login.png)

Sau khi liên kết với extension.

---

![extension-settings-sync-success](/assets/img/extension-settings-sync-success.png)

> Giờ thì có thể thoải mái Upload extension!

> Để kiểm tra thì truy cập `gist.github.com`

Giao diện trước khi upload.

![gist-before](/assets/img/gist-before.png)

---

Sau khi upload thành công.

![gist-after](/assets/img/gist-after.png)

Và mỗi lần đổi máy để làm việc thì chỉ cần tải `Settings Sync` và download về.

**Nếu bạn muốn đổi tài khoản Gist để upload hay download**

1. Mở **File Explorer** và dẫn đường link
- **Windows** `%APPDATA%\Code\User\syncLocalSettings.json`
- **macOS** `$HOME/Library/Application Support/Code/User/syncLocalSettings.json`
- **Linux** `$HOME/.config/Code/User/syncLocalSettings.json`

![gist-other-user](/assets/img/gist-other-user.png)

Xóa giá trị `token` là xong!

---

![girll](/assets/img/girll.jpg)