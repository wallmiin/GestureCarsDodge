# 🕹️ Gesture Car Dodge

Game né xe điều khiển bằng tay qua webcam.

## Cài Đặt
1. Tải dự án:
git clone https://github.com/wallmin/GestureCarDodge.git
cd GestureCarDodge

2. Tạo môi trường ảo:
python -m venv venv
.\venv\Scripts\activate  # Windows

3. Cài thư viện:
pip install -r requirements.txt

File `requirements.txt`:
mediapipe==0.10.11
numpy>=1.21
pygame~=2.0.1
pynput~=1.7.3
opencv-contrib-python

## Chạy Game
1. Đảm bảo có webcam.
2. Mở 2 terminal:
- Terminal 1:
python main.py

- Terminal 2:
python camera.py

## Cách Chơi
- Dùng tay điều khiển xe (màu vàng) né xe địch.
- Nghiêng tay trái: Xe sang trái.
- Nghiêng tay phải: Xe sang phải.
- Né xe địch để tăng điểm (hiển thị góc trên).

---

© 2024 wallmin
