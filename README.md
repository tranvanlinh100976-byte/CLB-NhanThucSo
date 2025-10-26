<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CLB NHẬN THỨC SỐ - NƠI KHƠI DẬY TƯ DUY  VÀ LÀM CHỦ CÔNG NGHỆ!</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <div class="brand">
        <div class="logo">🌟</div>
        <div>
          <h1 class="club-name">CLB NHẬN THỨC SỐ</h1>
          <p class="tagline">NƠI KHƠI DẬY TƯ DUY  VÀ LÀM CHỦ CÔNG NGHỆ!</p>
        </div>
      </div>

      <nav class="main-nav" id="mainNav">
        <a href="#home">Trang chủ</a>
        <a href="#about">Giới thiệu</a>
        <a href="#events">Sự kiện</a>
        <a href="#members">Thành viên</a>
        <a href="#contact">Liên hệ</a>
        <button id="menuToggle" aria-label="Mở menu">☰</button>
      </nav>
    </div>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="container hero-inner">
        <h2>Chào mừng đến với <span class="accent">CLB NHẬN THỨC SỐ</span></h2>
        <p>Chúng tôi là một cộng đồng năng động — học hỏi, sáng tạo và tổ chức sự kiện thú vị.</p>
        <div class="hero-actions">
          <a href="#events" class="btn">Xem sự kiện</a>
          <a href="#contact" class="btn ghost">Tham gia ngay</a>
        </div>
      </div>
    </section>

    <section id="about" class="container section">
      <h3>CLB Nhận Thức Số được thành lập với mục tiêu:</h3>
      <p> “Trang bị cho học sinh tư duy phản biện, kỹ năng nhận biết thông tin sai lệch, làm chủ công nghệ và lan tỏa giá trị tích cực trên không gian mạng.” </p>
      <p> Nơi đây, chúng ta cùng nhau:</p>
 <p>Thảo luận về AI, truyền thông đen, tin giả và an toàn số</p>
<p>Tạo ra video, podcast, chiến dịch tuyên truyền sáng tạo</p>
<p>Tổ chức hoạt động truyền thông, tọa đàm, mini game, talkshow học đường</p>
 <p>Kết nối những người trẻ dám nghĩ, dám nói, dám hành động để thay đổi nhận thức cộng đồng!</p>
      <div class="cards">
        <div class="card">
          <h4>Mission</h4>
          <p>Nâng cao kỹ năng, kết nối thành viên.</p>
        </div>
        <div class="card">
          <h4>Sứ mệnh</h4>
          <p>Chia sẻ kiến thức và thực hành.</p>
        </div>
        <div class="card">
          <h4>Hoạt động</h4>
          <p>Workshop, dự án, cuộc thi.</p>
        </div>
      </div>
    </section>

    <section id="events" class="container section">
      <h3>Sự kiện sắp tới</h3>
      <div class="events-grid" id="eventsList">
        <!-- Sự kiện mẫu; JS có thể thêm/sửa -->
        <article class="event">
          <h4>Workshop HTML & CSS</h4>
          <time datetime="2025-11-10">10 Nov 2025</time>
          <p>Học cách tạo trang web cơ bản và thiết kế responsive.</p>
          <a href="#" class="btn small">Đăng ký</a>
        </article>

        <article class="event">
          <h4>Hackathon nội bộ</h4>
          <time datetime="2025-12-05">05 Dec 2025</time>
          <p>Thi xây sản phẩm trong 24 giờ — đội nhóm, giải thưởng.</p>
          <a href="#" class="btn small">Xem chi tiết</a>
        </article>
      </div>
    </section>

    <section id="member-list" class="container section">
        <h3>Thành viên tiêu biểu</h3>
<div class="member-list">
  <!-- Chủ CLB -->
  <div class="member">
    <a href="https://www.facebook.com/share/1MoQ7mm52y/?mibextid=wwXIfr" target="_blank">
      <img src="https://via.placeholder.com/120" alt="NGuyễn Thanh Hoa - BOSS CLB">
    </a>
    <h5><a href="https://www.facebook.com/share/1MoQ7mm52y/?mibextid=wwXIfr"  target="_blank">Nguyễn Thanh Hoa</a></h5>
    <p>Vai trò: BOSS CLB</p>
  </div>

  <!-- Chủ nhiệm CLB(thành viên) -->
  <div class="member">
     <img src="dphu.jpg">
        <h5><a href="https://www.facebook.com/share/1BdNBETnty/?mibextid=wwXIfr" target="_blank"> Lê Đại Phú</a></h5>
    <p>Vai trò: Chủ Nhiệm CLB</p>
  </div>

    <section id="gallery" class="container section">
      <h3>Gallery</h3>
      <div class="gallery-grid">
        <img src="https://via.placeholder.com/300x200" alt="Ảnh 1">
        <img src="https://via.placeholder.com/300x200" alt="Ảnh 2">
        <img src="https://via.placeholder.com/300x200" alt="Ảnh 3">
        <img src="https://via.placeholder.com/300x200" alt="Ảnh 4">
      </div>
    </section>

    <section id="contact" class="container section contact-section">
      <h3>Liên hệ & Đăng ký</h3>
      <form id="contactForm" class="contact-form" novalidate>
        <label>
          Tên
          <input type="text" name="name" id="name" required minlength="2" placeholder="Họ và tên">
        </label>
        <label>
          Email
          <input type="email" name="email" id="email" required placeholder="email@vd.com">
        </label>
        <label>
          Tin nhắn
          <textarea name="message" id="message" rows="4" required placeholder="Bạn muốn tham gia vì..."></textarea>
        </label>
        <div class="form-row">
          <button type="submit" class="btn">Gửi</button>
          <button type="reset" class="btn ghost">Xóa</button>
        </div>
        <div id="formMsg" class="form-msg" aria-live="polite"></div>
      </form>

      <div class="contact-info">
        <p><strong>Địa chỉ:</strong> Trường THPT Lương Thế Vinh , Số 16 Hùng Vương, Phường Ba Đồn, Thị xã Ba Đồn, Tỉnh Quảng Trị/p>
        <p><strong>Điện thoại:</strong> 0918726442</p>
        <p><strong>Email:</strong> clb@example.com</p>
        <p><strong>Facebook:</strong> fb.com/tenclb</p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> </p>
    </div> CLB NHẬN THỨC SỐ - NƠI KHƠI DẬY TƯ DUY  VÀ LÀM CHỦ CÔNG NGHỆ!
  <script src="script.js"></script>
