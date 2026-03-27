# 🚀 StarBlaster - Unity 2D Space Shooter

![StarBlaster Banner](https://via.placeholder.com/800x200?text=StarBlaster+Game+Project)
## 👤 Thông tin tác giả
* **Họ tên:** [Nguyễn Thục Uyên]
* **MSSV:** [2312794]
* **Lớp:** [CTK47C]

---

**StarBlaster** là một dự án game bắn súng không gian 2D cổ điển được phát triển bằng Unity. Người chơi sẽ điều khiển một phi thuyền, chiến đấu chống lại các đợt tấn công của kẻ địch và cố gắng đạt số điểm cao nhất.

---

## 🎮 Tính năng chính (Key Features)

* **Hệ thống di chuyển:** Điều khiển phi thuyền mượt mà bằng bàn phím (WASD/Arrow Keys).
* **Chiến đấu:** Cơ chế bắn đạn liên tục với hiệu ứng âm thanh sống động.
* **Kẻ địch thông minh:** Kẻ địch di chuyển theo các đường dẫn (Pathfinding) và xuất hiện theo từng đợt (Waves) dựa trên `ScriptableObjects`.
* **Hệ thống điểm số:** Tính điểm khi tiêu diệt kẻ địch và lưu giữ **High Score** bằng `PlayerPrefs`.
* **Hiệu ứng hình ảnh:** Sử dụng `Particle System` cho các vụ nổ và `Camera Shake` khi nhận sát thương.
* **UI/UX:** Màn hình Menu, Gameplay và Game Over hoàn chỉnh.

---

## 🛠️ Công nghệ sử dụng (Tech Stack)

* **Engine:** Unity 6 (hoặc Unity 2022.3 LTS)
* **Ngôn ngữ:** C#
* **Input System:** Unity Input System Package (New)
* **Quản lý phiên bản:** Git & GitHub

---

## 📂 Cấu trúc dự án (Project Structure)

* `Assets/Scripts`: Chứa toàn bộ logic C# (Player, Enemy, Health, ScoreKeeper...).
* `Assets/Prefabs`: Các đối tượng được thiết kế sẵn (Bullet, Enemies, VFX).
* `Assets/Scenes`: Các màn chơi (MainMenu, GameScene, GameOver).
* `Assets/ScriptableObjects`: Cấu hình cho các đợt quái (Wave Configs).

---

## ⚙️ Hướng dẫn cài đặt (Installation)

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/TÊN_USER_CỦA_BẠN/StarBlaster.git](https://github.com/TÊN_USER_CỦA_BẠN/StarBlaster.git)
    ```
2.  **Mở dự án:**
    * Mở **Unity Hub**.
    * Chọn **Add** -> trỏ đến thư mục vừa clone.
    * Sử dụng phiên bản Unity tương ứng để mở.
3.  **Chạy Game:**
    * Mở scene `MainMenu` trong thư mục `Assets/Scenes`.
    * Nhấn nút **Play** trong Unity Editor.

---

Trong quá trình thực hiện Lab 03, tôi đã tùy chỉnh các thông số sau:
* **Player Speed:** Tăng từ 10 lên 20 để tăng độ linh hoạt.
* **Enemy Health:** Điều chỉnh máu của các "Tanky Enemy" để cân bằng độ khó.
* **VFX:** Thêm hiệu ứng nổ lớn hơn khi Boss bị tiêu diệt.

---




