# Môi trường và Cảnh (Scene) UR5e cho Isaac Sim

Repository này chứa cấu hình môi trường (`env_isaacsim6`) và cảnh 3D (`ur5etunewithtable.usd`) được thiết kế để mô phỏng cánh tay robot cộng tác UR5e tương tác với mặt bàn trong **NVIDIA Isaac Sim**.

## Yêu cầu hệ thống (Prerequisites)

Trước khi tải và chạy project này, hãy đảm bảo bạn đã cài đặt các phần mềm sau:
- [NVIDIA Omniverse Launcher](https://www.nvidia.com/en-us/omniverse/)
- **Isaac Sim** (6.0.1)
- Git và [Git LFS](https://git-lfs.com/) 

## Cài đặt & Thiết lập

**1. Clone Repository (Tải code về máy)**
Mở terminal của bạn lên và clone repo này về máy tính cục bộ:

```bash
# Đảm bảo bạn đã cài đặt Git LFS trước khi clone
git lfs install

# Clone repository
git clone <LINK_REPO_CUA_BAN>
cd <TEN_THU_MUC_REPO>

```

**2. Setup the Environment**
Repository này yêu cầu một số thư viện Python nhất định. Để tự động cài đặt môi trường ảo và các thư viện cần thiết, hãy chạy các lệnh sau trong terminal để khởi tạo:

```bash
# Tạo một môi trường ảo mới (đặt tên là env)
python3 -m venv env_isaacsim6

# Kích hoạt môi trường ảo
source env_isaacsim6/bin/activate

# Cài đặt toàn bộ thư viện cần thiết từ file requirements
pip install -r requirements.txt
```

