# Môi trường và Cảnh (Scene) UR5e cho Isaac Sim

Repository này chứa cấu hình môi trường (`env_isaacsim6`) và cảnh 3D (`ur5etunewithtable.usd`) được thiết kế để mô phỏng cánh tay robot cộng tác UR5e tương tác với mặt bàn trong **NVIDIA Isaac Sim**.

## Yêu cầu hệ thống (Prerequisites)

Trước khi tải và chạy project này, hãy đảm bảo bạn đã cài đặt các phần mềm sau:
- [NVIDIA Omniverse Launcher](https://www.nvidia.com/en-us/omniverse/)
- **Isaac Sim** (Phiên bản khuyến nghị: 2022.2.1 / 2023.1.1 hoặc mới hơn)
- Git và [Git LFS](https://git-lfs.com/) (Quan trọng để tải chuẩn xác các file file `.usd` có dung lượng lớn)

## Cài đặt & Thiết lập

**1. Clone Repository (Tải code về máy)**
Mở terminal của bạn lên và clone repo này về máy tính cục bộ:

```bash
# Đảm bảo bạn đã cài đặt Git LFS trước khi clone
git lfs install

# Clone repository
git clone <LINK_REPO_CUA_BAN>
cd <TEN_THU_MUC_REPO>

# Để kích hoạt môi trường (chỉnh sửa lại đường dẫn nếu là conda hoặc venv tiêu chuẩn)
source env_isaacsim6/bin/activate
# hoặc dùng nếu là conda:
conda activate ./env_isaacsim6

