# 🛡️ Lộ trình Kỹ sư An toàn thông tin & Kiểm chứng hình thức (Formal Verification)
> **Mục tiêu:** Kỹ sư Bảo mật / Kỹ sư Kiểm chứng hình thức (Thị trường Global)
> **Thời gian:** T1/2026 - T6/2028
> **Trạng thái:** 🟢 Đang thực hiện

## 📖 Giới thiệu
Repository này ghi lại hành trình của tôi từ một sinh viên Công nghệ thông tin tại **HCMUS** đến khi trở thành một **Kỹ sư Bảo mật** chuyên về **Kiểm chứng hình thức (Formal Verification)**. Lộ trình này kết hợp nền tảng học thuật tại trường với các công nghệ mũi nhọn như Lean 4, Rust và Bảo mật Blockchain.

---

## 🗺️ Lộ trình & Tiến độ

### 🚩 Giai đoạn 1: Xây nền tảng & Chuyển đổi tư duy
**Thời gian:** Năm 2, Học kỳ 2 (T2/2026 - T6/2026)
**Trọng tâm:** Cú pháp Lean, Hệ thống Linux, Lý thuyết tập hợp.

| Mảng | Hoạt động & Mục tiêu chính | Trạng thái |

| **🏛️ HCMUS** | **Hệ điều hành (OS):** <br> - [ ] Hiểu rõ Heap/Stack, Phân quyền, Race Conditions.<br> - [ ] *Tư duy:* Làm sao để chứng minh hệ thống không bị Deadlock? | ⬜ |
| **🏛️ HCMUS** | **Mạng máy tính:** <br> - [ ] Nắm vững mô hình OSI, TCP/IP, Wireshark.<br> - [ ] *Tư duy:* Khái niệm về Kiểm chứng giao thức (Protocol Verification). | ⬜ |
| **🏛️ HCMUS** | **Cơ sở dữ liệu:** <br> - [ ] Đại số quan hệ (Liên hệ với Lý thuyết tập hợp trong Lean). | ⬜ |
| **🏠 Tự học** | **Lean 4:** <br> - [ ] Hoàn thành "The Natural Number Game" (bản Lean 4).<br> - [ ] Đọc "Theorem Proving in Lean 4" (Các chương Logic & Proof). | ⬜ |
| **🏠 Tự học** | **InfoSec:** <br> - [ ] Thành thạo Linux Command Line (Ubuntu/Kali).<br> - [ ] PicoCTF: Các kỹ năng cơ bản & giải CTF nhập môn. | ⬜ |

---

### 🚀 Giai đoạn 2: Tăng tốc & Mật mã học
**Thời gian:** Hè năm 2 (T6/2026 - T8/2026)
**Trọng tâm:** Rust Ownership, Mathlib, Cơ bản về Mật mã.

#### 🦀 Rust (Bước đệm về An toàn bộ nhớ)
- [ ] **Học Rust:** Tập trung vào Ownership & Borrowing (Tư duy Memory Safety).
- [ ] **Dự án:** Viết tool CLI mã hóa/giải mã file đơn giản bằng Rust.

#### 📐 Lean & Toán học
- [ ] **Khám phá Mathlib:** Tìm hiểu cấu trúc thư viện toán học của Lean.
- [ ] **Thực hành:** Chứng minh các định lý đơn giản (Cauchy-Schwarz, Số nguyên tố).

---

### ⚔️ Giai đoạn 3: Chuyên sâu & Hội tụ
**Thời gian:** Năm 3, Học kỳ 1 (T9/2026 - T1/2027)
**Trọng tâm:** Mật mã học, Lý thuyết đồ thị, Formal Verification.

| Mảng | Hoạt động & Mục tiêu chính | Trạng thái |
| :--- | :--- | :---: |
| **🏛️ HCMUS** | **Nhập môn ATTT:** <br> - [ ] Nắm vững bộ ba CIA (Confidentiality, Integrity, Availability). | ⬜ |
| **🏛️ HCMUS** | **Mật mã học (Môn Vàng):** <br> - [ ] Ánh xạ RSA/Elliptic Curves với các Cấu trúc đại số trong Mathlib. | ⬜ |
| **🏛️ HCMUS** | **Lý thuyết đồ thị:** <br> - [ ] Cài đặt các định lý đồ thị bằng Lean (thay vì Python). | ⬜ |
| **🏠 Tự học** | **Formal Verification:** <br> - [ ] Đọc cuốn "Software Foundations" (phiên bản Lean/Coq). | ⬜ |
| **🏠 Tự học** | **Cộng đồng:** <br> - [ ] Tham gia & đặt câu hỏi trên Lean Zulip Chat. | ⬜ |

---

### 💎 Giai đoạn 4: Thực chiến & Đóng góp (Contributor)
**Thời gian:** Năm 3, Học kỳ 2 (T2/2027 - T6/2027)
**Trọng tâm:** **Đóng góp Mathlib**, Smart Contracts, Trình biên dịch.

#### 🏆 Nhiệm vụ tối thượng: The Mathlib PR
- [ ] **Mục tiêu:** Có ít nhất 1 Pull Request (PR) được merge vào thư viện `mathlib4` (Điểm nhấn quan trọng nhất cho CV).

#### 🛠️ Kỹ năng kỹ thuật
- [ ] **Smart Contract Security:** Học Solidity, đọc báo cáo audit (Verichains, Trail of Bits).
- [ ] **Mô hình hóa EVM:** Tìm hiểu cách mô hình hóa Ethereum Virtual Machine trong Lean.
- [ ] **Trình biên dịch (HCMUS):** Hiểu về AST & Parsing (Cách Lean dịch code).
- [ ] **Phát triển ứng dụng (HCMUS):** Hiểu cấu trúc phần mềm để nhận diện các điểm dễ sinh lỗi (bug).

---

### 💼 Giai đoạn 5: Thực tập & Nghiên cứu
**Thời gian:** Hè năm 3 (T6/2027 - T8/2027)
**Mục tiêu:** Kinh nghiệm làm việc chuyên nghiệp.

- **Phương án A (Ưu tiên):** Remote Research Intern (Ethereum Foundation, Tezos, Global Labs).
  - *Vũ khí:* Cái PR đã được merge vào Mathlib.
- **Phương án B:** Các công ty bảo mật hàng đầu Việt Nam (VNG, VNPT, Viettel CS).
  - *Vị trí:* Code Auditing / Security Research.

---

### 🎓 Giai đoạn 6: Khóa luận & Ra trường
**Thời gian:** Năm 4 (T9/2027 - T6/2028)
**Mục tiêu:** Tốt nghiệp & Nhận Offer Global.

#### 📜 Khóa luận tốt nghiệp (Vũ khí cuối cùng)
- [ ] **Đề tài:** Kiểm chứng tính đúng đắn của Giao thức X / Công cụ phân tích Smart Contract.
- [ ] **GVHD:** Tìm thầy cô bên Khoa học máy tính/CNPM nếu cần hướng dẫn nghiên cứu sâu.

#### 🌍 Tìm việc (Job Hunt)
- [ ] Ứng tuyển vị trí **Security Engineer / Formal Verification Engineer** trên toàn cầu.

---

## 🗃️ Tài nguyên & Ghi chú
* **Cấu trúc Repo:**
My_own_path/
│
├── .github/                   # (Nâng cao) Cấu hình GitHub Actions để tự động kiểm tra code
│   └── workflows/             # Chứa script CI/CD (ví dụ: tự động build code Rust/Lean)
│
├── .gitignore                 # File quan trọng: Loại bỏ file rác, file build, key bí mật
├── README.md                  # File lộ trình tổng quan (đã soạn ở trên)
├── LICENSE                    # MIT License (cho thấy sự chuyên nghiệp về bản quyền)
│
├── 00_university_hcmus/       # Mọi thứ liên quan đến trường lớp
│   ├── year2_sem2/
│   │   ├── os-operating-systems/
│   │   │   ├── 
│   │   │   └── 
│   │   ├── networks/
│   │   │   ├── 
│   │   │   └── 
│   │   └── 
│   ├── year3_sem1/
│   │   ├── 
│   │   └── 
│   └── ... (các kỳ sau)
│
├── 01_formal_verification/    # TRÁI TIM CỦA REPO (Lean 4)
│   ├── learn-lean4/
│   │   ├── natural-number-game/# Lời giải các màn chơi
│   │   └── tpil4-exercises/    # Bài tập từ sách Theorem Proving in Lean 4
│   ├── mathlib-experiments/    # Nơi cậu "nghịch" Mathlib
│   │   ├── algebra-structures/ # Thử định nghĩa nhóm, vành
│   │   └── my-theorems/        # Các định lý nhỏ cậu tự chứng minh
│   └── projects/               # Các dự án Lean lớn hơn
│       └── graph-verification/ # Dự án: Chứng minh định lý đồ thị bằng Lean
│
├── 02_security_lab/           # Kỹ năng thực chiến InfoSec & Rust
│   ├── ctf-training/
│   │   ├── picoctf/           # Writeups (lời giải) cho các bài đã giải
│   │   └── tools/             # Các script python nhỏ để giải CTF
│   ├── rust-security/
│   │   ├── learning-rust/     # Bài tập cú pháp, Ownership
│   │   └── secure-cli-tool/   # Dự án: Tool mã hóa file (Giai đoạn 2)
│   └── smart-contract/        # (Giai đoạn 4)
│       ├── solidity-basics/
│       └── audits/            # Phân tích các lỗi trong contract mẫu
│
├── 03_research_thesis/        # Dành cho nghiên cứu chuyên sâu & Khóa luận
│   ├── papers-review/         # Ghi chú tóm tắt các paper đã đọc
│   ├── mathlib-pr/            # Nháp code cho Pull Request vào Mathlib
│   └── graduation-thesis/     # Tài liệu khóa luận (Năm 4)
│
└── 99_knowledge_base/         # "Bộ não thứ hai" - Ghi chú tổng hợp
    ├── daily-log.md           # Nhật ký học tập mỗi ngày (Hôm nay học được gì?)
    ├── vocabulary/            # Từ vựng chuyên ngành (Anh-Việt)
    └── cheat-sheets/          # Các lệnh Linux, Lean syntax hay quên

* **Châm ngôn:** *"Đừng chỉ sửa lỗi, hãy chứng minh chúng không tồn tại."*
