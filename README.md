# Interview Prep AI - Hướng Dẫn Cài Đặt

Dự án này bao gồm hai phần: **Backend** (API) và **Frontend** (Giao diện người dùng).

## Hướng Dẫn Cài Đặt Chung

Trong thư mục gốc của từng phần (`backend` và `frontend`):

1.  **Cài đặt dependencies:**
    ```bash
    npm install
    ```

2.  **Chạy ở chế độ development:**
    ```bash
    npm run dev
    ```

3.  **Hoặc chạy production (chỉ áp dụng cho Backend):**
    ```bash
    npm start
    ```

---

## Thiết Lập Backend

### Biến Môi Trường (`.env`)

Tạo file **`.env`** trong thư mục **backend** và thêm các biến sau:

```env
MONGODB_URI=
JWT_SECRET=
GEMINI_API_KEY=
PORT=
```

### Xác Thực (Authorization)
Một số API yêu cầu xác thực bằng header sau:
```bash
Authorization: Bearer <YOUR_JWT_TOKEN>
```
## Thiết Lập Frontend

### Biến Môi Trường (`.env`)

Tạo file **`.env`** trong thư mục **backend** và thêm các biến sau:

```env
BACKEND_URL=http://localhost:5173/
```
