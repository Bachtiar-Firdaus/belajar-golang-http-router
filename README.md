# Belajar HttpRouter di Golang

## Daftar Materi
- Pendahuluan
- Pengenalan HttpRouter
- Router
- Params
- Router Patterns
- Serve File
- Panic Handler
- Not Found Handler
- Method Not Allowed Handler
- Middleware

---

## Ringkasan Materi

### Pendahuluan
HttpRouter adalah library router ringan dan cepat untuk Golang, dipakai buat mapping request HTTP ke handler.

### Pengenalan HttpRouter
HttpRouter mendukung routing berbasis pola URL dengan performa tinggi. Cocok buat aplikasi web dan API.

### Router
Router adalah inti dari HttpRouter, tempat mendefinisikan route dan handler untuk setiap endpoint.

### Params
HttpRouter mendukung parameter dinamis di URL, misalnya `/user/:id`, yang bisa diambil di handler.

### Router Patterns
Router mendukung berbagai pola seperti wildcard (`*`) dan parameter (`:param`) untuk fleksibilitas routing.

### Serve File
HttpRouter bisa dipakai buat serve static file dengan mudah, misalnya file HTML, CSS, atau gambar.

### Panic Handler
Panic handler digunakan untuk menangani error tak terduga (panic) agar aplikasi tetap stabil.

### Not Found Handler
Handler khusus untuk menangani request ke route yang tidak ditemukan (404).

### Method Not Allowed Handler
Handler khusus untuk menangani request dengan method yang tidak diizinkan (405).

### Middleware
Middleware memungkinkan eksekusi logika tambahan sebelum atau sesudah handler, misalnya logging atau autentikasi.

---

## Catatan
- HttpRouter terkenal karena **kecepatan dan efisiensi** dibanding router lain.  
- Cocok dipakai di aplikasi **REST API** maupun web server.  
- Middleware bisa digabung dengan router untuk bikin arsitektur aplikasi lebih modular.
