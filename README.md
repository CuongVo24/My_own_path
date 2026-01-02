# 🛡️ Lộ trình Kỹ sư Bảo mật & Kiểm chứng hình thức (Formal Verification) v2.0
> **Mục tiêu:** Kỹ sư Bảo mật Hệ thống / Smart Contract Auditor (Global/Remote)
> **Chiến lược:** "Blue Ocean" - Đi vào ngách khó, ít cạnh tranh, rào cản kỹ thuật cao.
> **Thời gian:** T1/2026 - T6/2028
> **Trạng thái:** 🟢 Giai đoạn 1: Khởi động & Vượt khó

## 📖 Giới thiệu
Hành trình từ sinh viên **HCMUS** trở thành **Kỹ sư Bảo mật (Verification Focused)**.
Lộ trình này không tập trung vào việc tạo ra phần mềm nhanh (Product), mà tập trung vào việc tạo ra phần mềm **không thể sai** (Correctness) bằng cách kết hợp:
1.  **Rust:** Ngôn ngữ an toàn bộ nhớ (Memory Safety).
2.  **Lean 4:** Ngôn ngữ chứng minh toán học (Formal Proof).
3.  **Security Mindset:** Tư duy phản biện và tấn công.

---

## 🗺️ Lộ trình Chi tiết

### 🚩 Giai đoạn 1: Xây nền tảng Logic & "Cú sốc" Rust
**Thời gian:** Năm 2, Học kỳ 2 (T1/2026 - T6/2026)
**Trọng tâm:** Logic mệnh đề, Rust Ownership, Tư duy hệ thống.

| Mảng | Hoạt động & Mục tiêu chính | Trạng thái |
| :--- | :--- | :---: |
| **🏛️ HCMUS** | **Hệ điều hành (OS):** <br> - [ ] Ánh xạ khái niệm Stack/Heap, Race Conditions sang Rust.<br> - [ ] *Câu hỏi:* Tại sao C++ cho phép lỗi này còn Rust thì không? | ⬜ |
| **🏛️ HCMUS** | **Lý thuyết đồ thị:** <br> - [ ] Nắm vững thuật toán (Dijkstra, BFS/DFS).<br> - [ ] *Tư duy:* Các tính chất bất biến (invariants) của đồ thị là gì? | ⬜ |
| **🏠 Tự học** | **Tư duy Logic (Tiền đề cho Lean):** <br> - [ ] Học kỹ **Propositional Logic** (Mệnh đề) & **First-order Logic** (Vị từ).<br> - [ ] *Tài liệu:* Giáo trình Toán rời rạc hoặc Logic for CS. | ⬜ |
| **🏠 Tự học** | **Rust (Hard Mode):** <br> - [ ] Đọc "The Rust Programming Language" (Chương 1-6).<br> - [ ] **Hiểu sâu:** Ownership, Borrowing, Lifetimes (Sống sót qua compiler). | ⬜ |
| **🏠 Tự học** | **Lean 4 (Nhập môn):** <br> - [ ] Hoàn thành **"The Natural Number Game"** (Lean 4 version).<br> - [ ] Mục tiêu: Hiểu cảm giác "Gamification" của việc chứng minh. | ⬜ |
| **🌐 Cộng đồng** | **Chiến thuật "Lurker":** <br> - [ ] Join Discord: **Rust Vietnam**, **Code4rena**.<br> - [ ] *Nhiệm vụ:* Đọc tin nhắn, không chat, xem cách họ tìm bug. | ⬜ |

---

### 🚀 Giai đoạn 2: Tăng tốc & Kết nối (The Bridge)
**Thời gian:** Hè năm 2 (T6/2026 - T8/2026)
**Trọng tâm:** Kết nối Toán (Lean) vào Code (Software).

#### 🦀 Rust System Programming
- [ ] **Re-write Project:** Viết lại một bài tập lớn môn Cấu trúc dữ liệu (VD: Linked List) bằng Rust.
- [ ] *Mục tiêu:* Hiểu tại sao Linked List trong Rust là "địa ngục" (và học cách dùng `Box`, `Rc`, `RefCell`).

#### 📐 Program Verification (Thay vì Pure Math)
- [ ] **Functional Programming:** Học cách tư duy phi trạng thái (Stateless).
- [ ] **Verification Project:** Sử dụng Lean 4 để chứng minh tính đúng đắn của một hàm đơn giản (VD: Hàm tính tổng, Hàm đảo ngược chuỗi).
- [ ] *Tài liệu:* "Software Foundations" (Vol 1 - Logical Foundations).

---

### ⚔️ Giai đoạn 3: Chuyên sâu Bảo mật (Security Core)
**Thời gian:** Năm 3, Học kỳ 1 (T9/2026 - T1/2027)
**Trọng tâm:** Mật mã học, Smart Contracts, Audit.

| Mảng | Hoạt động & Mục tiêu chính | Trạng thái |
| :--- | :--- | :---: |
| **🏛️ HCMUS** | **Mật mã học:** <br> - [ ] Hiểu sâu RSA, Elliptic Curves, Zero Knowledge Proofs (cơ bản). | ⬜ |
| **🏠 Tự học** | **Blockchain Security:** <br> - [ ] Học Solidity & EVM Architecture.<br> - [ ] Phân tích các lỗi kinh điển: Re-entrancy, Overflow, Logic Errors. | ⬜ |
| **🏠 Tự học** | **Rust Verification Tools:** <br> - [ ] Tìm hiểu **Verus** hoặc **Kani** (Công cụ verify code Rust trực tiếp).<br> - [ ] *Lý do:* Đây là thứ các công ty như AWS/Meta đang dùng. | ⬜ |
| **💰 Thực chiến** | **Săn lỗi (Bug Bounty):** <br> - [ ] Thử sức giải các bài CTF cũ của Paradigm hoặc Ethernaut.<br> - [ ] Đọc các báo cáo Audit trên Code4rena (Hiểu cách viết report). | ⬜ |

---

### 💎 Giai đoạn 4: Portfolio & Thực chiến (Proof of Work)
**Thời gian:** Năm 3, Học kỳ 2 (T2/2027 - T6/2027)
**Trọng tâm:** Xây dựng sản phẩm để "bán" bản thân.

#### 🏆 Nhiệm vụ tối thượng: The Verified Project
*(Thay thế cho Mathlib PR - Thực tế hơn)*
- [ ] **Project:** Xây dựng một Library nhỏ bằng Rust (VD: Token standard, Voting system) và **Chứng minh nó an toàn** (bằng Lean hoặc Verus).
- [ ] **Output:** Một Repo Github với badge `Verified`, tài liệu chứng minh rõ ràng. Đây là "vé tuyển thẳng" vào phỏng vấn.

#### 🛠️ Kỹ năng bổ trợ
- [ ] **English:** Đọc/Viết tài liệu kỹ thuật trôi chảy (Bắt buộc cho Remote).
- [ ] **CI/CD:** Thiết lập GitHub Actions để tự động chạy kiểm chứng mỗi khi push code.

---

### 💼 Giai đoạn 5: Gia nhập thị trường (The Entry)
**Thời gian:** Hè năm 3 (T6/2027 - T8/2027)

- **Target:** Intern tại các công ty Blockchain Security (Verichains, audit firms) hoặc Protocol Labs.
- **Vũ khí:** Repo "Verified Project" + Kiến thức Rust sâu + Tư duy Logic đã rèn luyện.

---

### 🗃️ Cấu trúc Repository (Cập nhật)

```text
My_own_path/
│
├── 01_basics_and_logic/       # GIAI ĐOẠN 1 (Nền tảng)
│   ├── logic-notes/           # Ghi chép Propositional/First-order logic
│   ├── rust-book-exercises/   # Bài tập The Rust Book
│   └── lean-natural-number/   # Lời giải Natural Number Game
│
├── 02_systems_and_rust/       # GIAI ĐOẠN 2 (Hệ thống)
│   ├── os-concepts-in-rust/   # Mô phỏng khái niệm OS bằng Rust
│   └── data-structures-rust/  # Linked List, Tree (Safe & Unsafe)
│
├── 03_security_playground/    # GIAI ĐOẠN 3 (Bảo mật)
│   ├── ethernaut-solutions/   # Giải bài tập hack Smart Contract
│   ├── crypto-primitives/     # Cài đặt thuật toán mật mã
│   └── code4rena-reports/     # Phân tích các lỗi tìm được từ C4
│
├── 04_verified_software/      # GIAI ĐOẠN 4 (Sản phẩm để đời)
│   ├── specs/                 # Đặc tả toán học (Specification)
│   ├── src/                   # Source code (Rust/Solidity)
│   └── proofs/                # Mã chứng minh (Lean/Verus)
│
└── 99_resources/
    ├── networking.md          # Danh sách người/cộng đồng nên follow
    └── interview-prep.md      # Các câu hỏi phỏng vấn Rust/Logic
