<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH TƯỜNG AN KHANG - Tủ Bếp &amp; Nội Thất Đẹp Giá Xưởng Đà Nẵng | tuongankhang.com</title>
  <meta name="description" content="CÔNG TY TNHH TƯỜNG AN KHANG (tuongankhang.com) - Chuyên thiết kế, sản xuất, thi công Tủ Bếp, Nội Thất trọn gói và phân phối Thiết Bị Bếp tại Đà Nẵng. Showroom 1: 176 Nguyễn Hữu Thọ - Showroom 2: 239 Nguyễn Hữu Thọ. Hotline: 0905.052.458 - 0905.116.357.">
  
  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tuongankhang.com/">
  <meta property="og:title" content="CÔNG TY TNHH TƯỜNG AN KHANG - Nội Thất &amp; Tủ Bếp Đà Nẵng">
  <meta property="og:description" content="Thiết kế &amp; Thi công Tủ Bếp - Nội Thất Giá Xưởng. Showroom 1: 176 Nguyễn Hữu Thọ | Showroom 2: 239 Nguyễn Hữu Thọ, Đà Nẵng. ĐT: 0905.052.458 - 0905.116.357">
  <meta property="og:image" content="https://placehold.co/1200x630/8B1E1E/F59E0B?text=LOGO+TUONG+AN+KHANG+-+TUONGANKHANG.COM">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://placehold.co/1200x630/8B1E1E/F59E0B?text=LOGO+TUONG+AN+KHANG+-+TUONGANKHANG.COM">

  <!-- Favicon SVG đồng bộ màu Logo -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='18' fill='%238B1E1E'/%3E%3Cpath d='M20 72 L50 24 L80 72 Z' fill='none' stroke='%23F59E0B' stroke-width='7'/%3E%3Ctext x='50' y='68' font-family='Arial' font-size='26' font-weight='bold' fill='%23FFFFFF' text-anchor='middle'%3ETAK%3C/text%3E%3C/svg%3E">

  <!-- Google Fonts & Font Awesome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    /* ==========================================================================
       CẤU HÌNH CHUẨN FLATSOME UX BUILDER - MÀU THEO LOGO TƯỜNG AN KHANG
       Chủ đạo: Đỏ Đô Hoàng Gia (#8B1E1E) - Vàng Kim (#D97706) - Than Chì (#1E293B)
       ========================================================================== */
    :root {
      --primary-color: #8B1E1E;
      --primary-dark: #6E1414;
      --accent-gold: #D97706;
      --accent-gold-light: #F59E0B;
      --text-dark: #1E293B;
      --bg-light: #F8FAFC;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      color: var(--text-dark);
      background-color: #F4F5F7;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }

    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tối ưu thanh danh mục trên máy tính:
       Tên danh mục viết liền trên 1 hàng, chữ nhỏ gọn, không tự xuống dòng bên trong tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 2px 6px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .desktop-nav-item {
      position: relative;
    }

    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      padding: 8px 9px;
      font-size: 12.5px;
      font-weight: 700;
      color: #FFFFFF;
      text-transform: uppercase;
      white-space: nowrap; /* Tuyệt đối không xuống dòng bên trong tên danh mục */
      letter-spacing: 0.01em;
      border-radius: 4px;
      transition: background-color 0.2s ease, color 0.2s ease;
    }

    .desktop-nav-link:hover,
    .desktop-nav-link.active {
      background-color: rgba(255, 255, 255, 0.14);
      color: #FCD34D;
    }

    /* Dropdown menu chuẩn Flatsome */
    .nav-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #FFFFFF;
      border-top: 3px solid var(--accent-gold);
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.14);
      border-radius: 0 0 6px 6px;
      padding: 6px 0;
      z-index: 100;
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }

    .desktop-nav-item:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .nav-dropdown a {
      display: block;
      padding: 7px 14px;
      font-size: 12.5px;
      font-weight: 500;
      color: #334155;
      white-space: nowrap;
      border-bottom: 1px solid #F1F5F9;
      transition: all 0.15s ease;
    }

    .nav-dropdown a:last-child {
      border-bottom: none;
    }

    .nav-dropdown a:hover {
      background-color: #FEF2F2;
      color: var(--primary-color);
      padding-left: 18px;
    }

    /* Tiêu đề danh mục chuẩn Flatsome */
    .flatsome-section-header {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid var(--primary-color);
      margin-bottom: 14px;
      background: #FFFFFF;
      border-radius: 6px 6px 0 0;
    }

    .flatsome-section-title {
      background: var(--primary-color);
      color: #FFFFFF;
      font-size: 14px;
      font-weight: 700;
      text-transform: uppercase;
      padding: 9px 16px;
      border-radius: 6px 6px 0 0;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      white-space: nowrap;
      margin: 0;
    }

    /* Chữ danh mục nhỏ gọn ở trang chủ, viết liền không gãy chữ */
    .subcat-pills {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 4px;
      padding: 6px 10px;
    }

    .subcat-pill {
      font-size: 11.5px;
      font-weight: 600;
      color: #334155;
      padding: 4px 9px;
      border-radius: 4px;
      background: #F1F5F9;
      white-space: nowrap;
      transition: all 0.2s ease;
      cursor: pointer;
    }

    .subcat-pill:hover,
    .subcat-pill.active {
      background: var(--primary-color);
      color: #FFFFFF;
    }

    /* Thẻ sản phẩm Flatsome:
       - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
       - Chỉ có % giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-product-card {
      background: #FFFFFF;
      border: 1px solid #E2E8F0;
      border-radius: 6px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      height: 100%;
      position: relative;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .flatsome-product-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(139, 30, 30, 0.12);
      border-color: #CBD5E1;
    }

    /* Badge giảm giá chuẩn Flatsome góc trên bên trái */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background: #D90429;
      color: #FFFFFF;
      font-size: 11.5px;
      font-weight: 800;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.22);
      line-height: 1;
    }

    /* Tên sản phẩm đầy đủ, tự xuống dòng gọn gàng, tuyệt đối không bị cắt chữ (...) hay tràn viền */
    .flatsome-product-title {
      font-size: 13px;
      line-height: 1.42;
      font-weight: 600;
      color: #1E293B;
      margin: 0 0 6px 0;
      word-wrap: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      overflow: visible;
      text-overflow: clip;
    }

    @media (min-width: 768px) {
      .flatsome-product-title {
        font-size: 13.5px;
      }
    }

    /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
    .floating-contact-group {
      position: fixed;
      bottom: 16px;
      left: 12px;
      z-index: 90;
      display: flex;
      flex-direction: column;
      gap: 8px;
      max-width: calc(100vw - 24px);
    }

    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(139, 30, 30, 0.55); }
      70% { box-shadow: 0 0 0 10px rgba(139, 30, 30, 0); }
      100% { box-shadow: 0 0 0 0 rgba(139, 30, 30, 0); }
    }

    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- ==========================================================================
       1. TOP BAR: ĐỊA CHỈ 2 SHOWROOM & HOTLINE (GỌN GÀNG, KHÔNG TRÀN VIỀN)
       ========================================================================== -->
  <div class="bg-[#6E1414] text-white text-[11.5px] py-1.5 border-b border-[#8B1E1E]">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-amber-400"></i>
          <strong>Showroom 1:</strong> 176 Nguyễn Hữu Thọ - Đà Nẵng
        </span>
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-amber-400"></i>
          <strong>Showroom 2:</strong> 239 Nguyễn Hữu Thọ - Đà Nẵng
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="inline-flex items-center gap-1 text-amber-300 font-semibold">
          <i class="fa-solid fa-phone-volume"></i>
          0905.052.458 - 0905.116.357
        </span>
        <span class="hidden sm:inline text-white/60">|</span>
        <a href="https://www.facebook.com/noithatbeptuongankhang" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1 hover:text-amber-300 transition">
          <i class="fa-brands fa-facebook"></i> Fanpage Tường An Khang
        </a>
      </div>
    </div>
  </div>

  <!-- ==========================================================================
       2. HEADER CHÍNH: LOGO MỚI GỌN NHỎ LẠI, TÌM KIẾM, GIỎ BÁO GIÁ
          (Không để nút Gọi ngay trên Header để tránh tràn viền)
       ========================================================================== -->
  <header class="bg-white shadow-sm sticky top-0 z-50">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-2.5">
      
      <!-- Nút mở danh mục trên Điện thoại -->
      <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded bg-[#8B1E1E] text-white shrink-0">
        <i class="fa-solid fa-bars text-base"></i>
      </button>

      <!-- LOGO MỚI CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
      <a href="#top" class="flex items-center gap-2 shrink-0 group">
        <svg class="w-10 h-10 sm:w-11 sm:h-11 shrink-0 rounded-lg shadow-sm" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="takGrad" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#991B1B" />
              <stop offset="100%" stop-color="#6E1414" />
            </linearGradient>
            <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="0%">
              <stop offset="0%" stop-color="#F59E0B" />
              <stop offset="100%" stop-color="#FBBF24" />
            </linearGradient>
          </defs>
          <rect width="120" height="120" rx="20" fill="url(#takGrad)" stroke="#F59E0B" stroke-width="3"/>
          <!-- Biểu tượng Mái nhà & Tủ bếp hiện đại -->
          <path d="M22 54 L60 22 L98 54" fill="none" stroke="url(#goldGrad)" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
          <rect x="33" y="54" width="54" height="36" rx="4" fill="none" stroke="#FFFFFF" stroke-width="3.5"/>
          <line x1="60" y1="54" x2="60" y2="90" stroke="#F59E0B" stroke-width="3"/>
          <line x1="33" y1="72" x2="87" y2="72" stroke="#F59E0B" stroke-width="2.5"/>
          <text x="60" y="109" font-family="Inter, sans-serif" font-size="13" font-weight="800" fill="#FCD34D" text-anchor="middle" letter-spacing="1.5">TAK</text>
        </svg>
        <div class="leading-tight">
          <div class="text-[13px] sm:text-[15px] font-extrabold tracking-tight text-[#8B1E1E] uppercase">
            TƯỜNG AN KHANG
          </div>
          <div class="text-[10px] sm:text-[11px] font-semibold text-amber-700">
            tuongankhang.com • Tủ Bếp &amp; Nội Thất
          </div>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm (giống mẫu tubephome3d.com) -->
      <div class="hidden md:flex flex-1 max-w-xl mx-3">
        <div class="flex w-full border-2 border-[#8B1E1E] rounded-md overflow-hidden bg-white">
          <input id="searchInputDesktop" type="text" placeholder="Tìm tủ bếp Inox cánh kính, tủ bếp Acrylic, nội thất, bếp từ..." class="w-full px-3 py-1.5 text-xs focus:outline-none text-slate-700">
          <button id="searchBtnDesktop" type="button" class="bg-[#8B1E1E] hover:bg-[#6E1414] text-white px-4 text-xs font-semibold shrink-0 transition">
            <i class="fa-solid fa-magnifying-glass mr-1"></i> Tìm kiếm
          </button>
        </div>
      </div>

      <!-- Cam kết xưởng & Giỏ báo giá (Không để nút gọi ngay để tránh tràn viền) -->
      <div class="flex items-center gap-2 sm:gap-3 shrink-0">
        <div class="hidden xl:flex items-center gap-2 bg-amber-50 border border-amber-200 px-2.5 py-1 rounded text-[11px] text-slate-700">
          <i class="fa-solid fa-award text-[#8B1E1E] text-sm"></i>
          <div>
            <div class="font-bold text-[#8B1E1E]">GIÁ TẬN XƯỞNG ĐÀ NẴNG</div>
            <div class="text-[10px] text-slate-600">Miễn phí thiết kế 3D 100%</div>
          </div>
        </div>

        <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 bg-slate-100 hover:bg-amber-50 text-[#8B1E1E] border border-slate-200 px-2.5 py-1.5 rounded text-xs font-bold transition">
          <i class="fa-solid fa-file-invoice-dollar"></i>
          <span class="hidden sm:inline">Nhận Báo Giá</span>
          <span id="quoteCountBadge" class="bg-[#8B1E1E] text-white text-[10px] px-1.5 py-0.5 rounded-full">0</span>
        </a>
      </div>
    </div>

    <!-- Thanh tìm kiếm gọn trên Điện thoại -->
    <div class="md:hidden flatsome-container pb-2">
      <div class="flex w-full border border-[#8B1E1E] rounded overflow-hidden bg-white">
        <input id="searchInputMobile" type="text" placeholder="Tìm mẫu tủ bếp, nội thất, thiết bị bếp..." class="w-full px-2.5 py-1.5 text-xs focus:outline-none">
        <button id="searchBtnMobile" type="button" class="bg-[#8B1E1E] text-white px-3 text-xs">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </div>
    </div>

    <!-- ==========================================================================
         3. THANH DANH MỤC TRÊN MÁY TÍNH (LẤY TỪ WEB MẪU TUBEPHOME3D.COM)
            Chữ nhỏ gọn, viết liền trên 1 hàng (white-space: nowrap), không gãy dòng
         ========================================================================== -->
    <nav class="hidden lg:block bg-[#8B1E1E] border-t border-[#6E1414]">
      <div class="flatsome-container">
        <ul class="desktop-nav-list">
          <li class="desktop-nav-item">
            <a href="#top" class="desktop-nav-link active"><i class="fa-solid fa-house text-[11px]"></i> Trang chủ</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-tu-bep" class="desktop-nav-link">Tủ bếp <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="nav-dropdown">
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Inox Cánh Kính')">Tủ Bếp Inox Cánh Kính Cường Lực</a>
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Cánh Acrylic')">Tủ Bếp Cánh Acrylic Bóng Gương</a>
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Gỗ Công Nghiệp')">Tủ Bếp Gỗ Công Nghiệp An Cường</a>
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Gỗ Nhựa Picomat')">Tủ Bếp Gỗ Nhựa Picomat Siêu Chịu Nước</a>
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Nhôm Nội Thất')">Tủ Bếp Nhôm Hợp Kim Nội Thất</a>
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Cánh Laminate')">Tủ Bếp Cánh Phủ Laminate / Melamine</a>
              <a href="#sec-tu-bep" onclick="filterByCategory('Tủ Bếp Gỗ Tự Nhiên')">Tủ Bếp Gỗ Tự Nhiên (Sồi, Xoan Đào, Óc Chó)</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-noi-that" class="desktop-nav-link">Nội thất <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="nav-dropdown">
              <a href="#sec-noi-that">Nội Thất Phòng Khách Hiện Đại</a>
              <a href="#sec-noi-that">Nội Thất Phòng Ngủ Trọn Gói</a>
              <a href="#sec-noi-that">Vách Ngăn Phòng Khách Và Bếp</a>
              <a href="#sec-noi-that">Tủ Quần Áo Cánh Kính Khung Nhôm</a>
              <a href="#sec-noi-that">Kệ Ti Vi Phòng Khách &amp; Tủ Rượu Gỗ</a>
              <a href="#sec-noi-that">Giường Ngủ - Bàn Trang Điểm - Tủ Giày</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-thiet-bi-bep" class="desktop-nav-link">Thiết bị bếp <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="nav-dropdown">
              <a href="#sec-thiet-bi-bep">Bếp Từ Đôi &amp; Bếp Điện Từ Âm</a>
              <a href="#sec-thiet-bi-bep">Máy Hút Mùi Nhà Bếp Cao Cấp</a>
              <a href="#sec-thiet-bi-bep">Phụ Kiện Tủ Bếp Inox 304 Thông Minh</a>
              <a href="#sec-thiet-bi-bep">Chậu Rửa &amp; Vòi Rửa Chén Inox 304</a>
              <a href="#sec-thiet-bi-bep">Máy Rửa Chén - Lò Nướng - Lò Vi Sóng</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-thiet-ke" class="desktop-nav-link">Thiết kế <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="nav-dropdown">
              <a href="#form-bao-gia">Thiết Kế Nội Thất Phòng Bếp 3D</a>
              <a href="#form-bao-gia">Thiết Kế Nội Thất Phòng Khách</a>
              <a href="#form-bao-gia">Thiết Kế Nội Thất Phòng Ngủ</a>
              <a href="#form-bao-gia">Thiết Kế Nội Thất Nhà Phố - Biệt Thự</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-thi-cong" class="desktop-nav-link">Thi công <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="nav-dropdown">
              <a href="#sec-tat-ca-san-pham">Thi Công Nội Thất Chung Cư Đà Nẵng</a>
              <a href="#sec-tat-ca-san-pham">Thi Công Nội Thất Nhà Phố Trọn Gói</a>
              <a href="#sec-tat-ca-san-pham">Thi Công Nội Thất Biệt Thự Cao Cấp</a>
              <a href="#sec-tat-ca-san-pham">Cải Tạo &amp; Sửa Chữa Tủ Bếp Chống Ẩm</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#form-bao-gia" class="desktop-nav-link">Báo giá</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-doi-tac" class="desktop-nav-link">Đối tác</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-tin-tuc" class="desktop-nav-link">Tin tức</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-lien-he-map" class="desktop-nav-link">Liên hệ Showroom</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Thanh cuộn Danh mục nhanh trên Điện thoại (Tối ưu xem trên ĐT đẹp & không tràn viền) -->
    <div class="lg:hidden bg-[#8B1E1E] text-white border-t border-[#6E1414] overflow-x-auto no-scrollbar">
      <div class="flex items-center gap-1 px-2 py-1.5 text-[11.5px] font-bold uppercase whitespace-nowrap">
        <a href="#sec-danh-muc" class="px-2.5 py-1 rounded bg-white/15 text-amber-300">Danh mục</a>
        <a href="#sec-tu-bep" class="px-2.5 py-1 rounded hover:bg-white/10">Tủ bếp</a>
        <a href="#sec-noi-that" class="px-2.5 py-1 rounded hover:bg-white/10">Nội thất</a>
        <a href="#sec-thiet-bi-bep" class="px-2.5 py-1 rounded hover:bg-white/10">Thiết bị bếp</a>
        <a href="#form-bao-gia" class="px-2.5 py-1 rounded hover:bg-white/10">Báo giá</a>
        <a href="#sec-doi-tac" class="px-2.5 py-1 rounded hover:bg-white/10">Đối tác</a>
        <a href="#sec-tin-tuc" class="px-2.5 py-1 rounded hover:bg-white/10">Tin tức</a>
        <a href="#sec-lien-he-map" class="px-2.5 py-1 rounded hover:bg-white/10">Bản đồ &amp; Fanpage</a>
      </div>
    </div>
  </header>

  <!-- ==========================================================================
       DRAWER MENU TRÊN ĐIỆN THOẠI (CHUẨN FLATSOME MOBILE MENU)
       ========================================================================== -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/60 z-50 hidden transition-opacity">
    <div class="w-[82%] max-w-[310px] bg-white h-full overflow-y-auto shadow-2xl flex flex-col">
      <div class="bg-[#8B1E1E] text-white p-3.5 flex items-center justify-between">
        <div class="font-bold text-xs uppercase tracking-wide">
          DANH MỤC TƯỜNG AN KHANG
        </div>
        <button id="closeMobileMenuBtn" type="button" class="w-7 h-7 rounded bg-white/15 flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-3 divide-y divide-slate-100 text-xs font-semibold text-slate-700 flex-1">
        <a href="#top" class="mobile-nav-item block py-2.5 text-[#8B1E1E]"><i class="fa-solid fa-house w-5"></i> Trang chủ</a>
        <a href="#sec-tu-bep" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-kitchen-set w-5 text-[#8B1E1E]"></i> Tủ Bếp Gỗ Công Nghiệp</a>
        <a href="#sec-tu-bep" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-shield-halved w-5 text-[#8B1E1E]"></i> Tủ Bếp Inox Cánh Kính</a>
        <a href="#sec-tu-bep" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-droplet-slash w-5 text-[#8B1E1E]"></i> Tủ Bếp Gỗ Nhựa Picomat</a>
        <a href="#sec-tu-bep" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-wand-magic-sparkles w-5 text-[#8B1E1E]"></i> Tủ Bếp Cánh Acrylic Bóng Gương</a>
        <a href="#sec-tu-bep" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-tree w-5 text-[#8B1E1E]"></i> Tủ Bếp Gỗ Tự Nhiên</a>
        <a href="#sec-noi-that" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-couch w-5 text-[#8B1E1E]"></i> Nội Thất Phòng Khách &amp; Phòng Ngủ</a>
        <a href="#sec-noi-that" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-border-all w-5 text-[#8B1E1E]"></i> Vách Ngăn &amp; Tủ Áo Cánh Kính</a>
        <a href="#sec-thiet-bi-bep" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-fire-burner w-5 text-[#8B1E1E]"></i> Thiết Bị Bếp &amp; Phụ Kiện Inox 304</a>
        <a href="#form-bao-gia" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-calculator w-5 text-[#8B1E1E]"></i> Báo Giá &amp; Thiết Kế 3D</a>
        <a href="#sec-doi-tac" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-handshake w-5 text-[#8B1E1E]"></i> Đối Tác Thương Hiệu</a>
        <a href="#sec-tin-tuc" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-newspaper w-5 text-[#8B1E1E]"></i> Tin Tức &amp; Kinh Nghiệm</a>
        <a href="#sec-lien-he-map" class="mobile-nav-item block py-2.5"><i class="fa-solid fa-map-location-dot w-5 text-[#8B1E1E]"></i> Showroom &amp; Bản Đồ Google Map</a>
      </div>
      <div class="p-3 bg-slate-50 border-t border-slate-200 text-[11px] text-slate-600 space-y-1">
        <div><strong>SR1:</strong> 176 Nguyễn Hữu Thọ - Đà Nẵng</div>
        <div><strong>SR2:</strong> 239 Nguyễn Hữu Thọ - Đà Nẵng</div>
        <div class="text-[#8B1E1E] font-bold">ĐT: 0905.052.458 - 0905.116.357</div>
      </div>
    </div>
  </div>

  <!-- ==========================================================================
       4. HỆ THỐNG 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
          - Thiết kế ảnh Banner Máy Tính và ảnh Banner Điện Thoại KHÁC NHAU
          - Chữ nhỏ gọn nằm trọn bên trong ảnh Banner, tuyệt đối không tràn viền
       ========================================================================== -->
  <section id="top" class="py-3">
    <div class="flatsome-container">
      <div class="relative rounded-lg overflow-hidden shadow-md bg-[#4A0D0D]">

        <!-- ================= BANNER DÀNH RIÊNG CHO MÁY TÍNH (2 SLIDE BẰNG NHAU) ================= -->
        <div class="hidden md:block relative w-full h-[320px] lg:h-[370px] overflow-hidden">
          
          <!-- Desktop Slide 1 -->
          <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-100 flex items-center"
               style="background: linear-gradient(95deg, #4A0D0D 0%, #8B1E1E 52%, rgba(30,41,59,0.88) 100%);">
            <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-14 gap-6">
              <div class="col-span-7 text-white space-y-2.5 pr-4">
                <div class="inline-block bg-amber-400 text-[#6E1414] text-[11px] font-extrabold uppercase px-3 py-1 rounded">
                  CÔNG TY TNHH TƯỜNG AN KHANG • TUONGANKHANG.COM
                </div>
                <h1 class="text-xl lg:text-2xl font-extrabold leading-snug text-white uppercase">
                  CHUYÊN THIẾT KẾ &amp; THI CÔNG TỦ BẾP - NỘI THẤT GIÁ TẬN XƯỞNG ĐÀ NẴNG
                </h1>
                <p class="text-xs lg:text-[13px] text-amber-100 leading-relaxed max-w-xl">
                  Chuyên Tủ Bếp Inox Cánh Kính Cường Lực, Tủ Bếp Acrylic An Cường, Nhựa Picomat Chống Nước 100% &amp; Nội Thất Phòng Khách - Phòng Ngủ Đồng Bộ. Miễn phí thiết kế 3D!
                </p>
                <div class="grid grid-cols-2 gap-2 pt-1 text-[11.5px] text-white/95 max-w-xl">
                  <div class="bg-black/25 border border-white/15 rounded px-2.5 py-1.5">
                    <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>
                    <strong>Showroom 1:</strong> 176 Nguyễn Hữu Thọ - Đà Nẵng
                  </div>
                  <div class="bg-black/25 border border-white/15 rounded px-2.5 py-1.5">
                    <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>
                    <strong>Showroom 2:</strong> 239 Nguyễn Hữu Thọ - Đà Nẵng
                  </div>
                </div>
                <div class="pt-1 flex items-center gap-3">
                  <a href="#form-bao-gia" class="bg-amber-400 hover:bg-amber-300 text-[#6E1414] text-xs font-extrabold px-4 py-2 rounded shadow transition">
                    NHẬN BÁO GIÁ TẬN XƯỞNG
                  </a>
                  <span class="text-xs font-bold text-amber-300">
                    <i class="fa-solid fa-phone-volume mr-1"></i> Hotline: 0905.052.458 - 0905.116.357
                  </span>
                </div>
              </div>
              <div class="col-span-5 h-[250px] lg:h-[290px] flex items-center justify-center">
                <div class="w-full h-full rounded-lg overflow-hidden border-2 border-amber-400/70 shadow-lg bg-slate-900 relative">
                  <img data-drive-id="1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1"
                       src="https://drive.google.com/thumbnail?id=1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1&sz=w1000"
                       alt="Tủ bếp thực tế Tường An Khang"
                       class="w-full h-full object-cover">
                  <div class="absolute bottom-2 right-2 bg-[#8B1E1E]/90 text-white text-[10.5px] font-semibold px-2.5 py-1 rounded">
                    Ảnh Thi Công Thực Tế Tường An Khang
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Desktop Slide 2 (Kích thước bằng hệt Slide 1) -->
          <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex items-center"
               style="background: linear-gradient(95deg, #1E293B 0%, #6E1414 55%, #8B1E1E 100%);">
            <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-14 gap-6">
              <div class="col-span-7 text-white space-y-2.5 pr-4">
                <div class="inline-block bg-amber-400 text-[#6E1414] text-[11px] font-extrabold uppercase px-3 py-1 rounded">
                  ƯU ĐÃI TRỌN GÓI TỦ BẾP &amp; THIẾT BỊ BẾP CHÍNH HÃNG
                </div>
                <h2 class="text-xl lg:text-2xl font-extrabold leading-snug text-white uppercase">
                  GIẢM ĐẾN 25% PHỤ KIỆN INOX 304 &amp; THIẾT BỊ BẾP KHI THI CÔNG TỦ BẾP
                </h2>
                <p class="text-xs lg:text-[13px] text-slate-200 leading-relaxed max-w-xl">
                  Phân phối chính hãng Bếp Từ, Máy Hút Mùi, Chậu Vòi Inox 304, Giá Bát Nâng Hạ. Bảo hành uy tín dài hạn, khảo sát &amp; lắp đặt tận nơi tại Đà Nẵng và Miền Trung.
                </p>
                <div class="grid grid-cols-2 gap-2 pt-1 text-[11.5px] text-white/95 max-w-xl">
                  <div class="bg-white/10 border border-white/15 rounded px-2.5 py-1.5">
                    <i class="fa-solid fa-check-circle text-amber-400 mr-1"></i>
                    Xưởng sản xuất trực tiếp - Không qua trung gian
                  </div>
                  <div class="bg-white/10 border border-white/15 rounded px-2.5 py-1.5">
                    <i class="fa-solid fa-check-circle text-amber-400 mr-1"></i>
                    Đo đạc &amp; Lên bản vẽ 3D hoàn toàn miễn phí
                  </div>
                </div>
                <div class="pt-1 flex items-center gap-3">
                  <a href="#sec-tat-ca-san-pham" class="bg-amber-400 hover:bg-amber-300 text-[#6E1414] text-xs font-extrabold px-4 py-2 rounded shadow transition">
                    XEM 14+ SẢN PHẨM THỰC TẾ
                  </a>
                  <span class="text-xs font-bold text-amber-300">
                    <i class="fa-solid fa-phone-volume mr-1"></i> Tư vấn: 0905.052.458 - 0905.116.357
                  </span>
                </div>
              </div>
              <div class="col-span-5 h-[250px] lg:h-[290px] flex items-center justify-center">
                <div class="w-full h-full rounded-lg overflow-hidden border-2 border-amber-400/70 shadow-lg bg-slate-900 relative">
                  <img data-drive-id="19DCXMXuKGT-1svYY5cGE21_Kr8EEQqZJ"
                       src="https://drive.google.com/thumbnail?id=19DCXMXuKGT-1svYY5cGE21_Kr8EEQqZJ&sz=w1000"
                       alt="Tủ bếp cao cấp Tường An Khang"
                       class="w-full h-full object-cover">
                  <div class="absolute bottom-2 right-2 bg-[#8B1E1E]/90 text-white text-[10.5px] font-semibold px-2.5 py-1 rounded">
                    Showroom 176 &amp; 239 Nguyễn Hữu Thọ
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- ================= BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI =================
             (Khác với banner máy tính, chữ chỉnh nhỏ gọn nằm hết bên trong ảnh, không tràn viền) -->
        <div class="block md:hidden relative w-full h-[270px] overflow-hidden">
          
          <!-- Mobile Slide 1 -->
          <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-100 flex flex-col justify-between p-3.5"
               style="background: linear-gradient(160deg, #5C1010 0%, #8B1E1E 60%, #2A0808 100%);">
            <div class="flex items-center justify-between gap-2">
              <span class="bg-amber-400 text-[#6E1414] text-[9.5px] font-extrabold px-2 py-0.5 rounded uppercase">
                TUONGANKHANG.COM
              </span>
              <span class="text-[10px] text-amber-300 font-bold">
                0905.052.458 - 0905.116.357
              </span>
            </div>
            <div class="grid grid-cols-12 gap-2.5 items-center my-auto">
              <div class="col-span-7 text-white space-y-1">
                <h2 class="text-[13px] font-extrabold leading-tight uppercase text-amber-300">
                  CÔNG TY TNHH TƯỜNG AN KHANG
                </h2>
                <p class="text-[11px] font-bold leading-snug text-white">
                  Tủ Bếp Inox Cánh Kính, Acrylic, Picomat &amp; Nội Thất Giá Xưởng Đà Nẵng
                </p>
                <div class="text-[10px] text-amber-100 leading-tight space-y-0.5 pt-0.5">
                  <div>• SR1: 176 Nguyễn Hữu Thọ - Đà Nẵng</div>
                  <div>• SR2: 239 Nguyễn Hữu Thọ - Đà Nẵng</div>
                </div>
              </div>
              <div class="col-span-5 h-[135px] rounded overflow-hidden border border-amber-400/70 bg-slate-900">
                <img data-drive-id="1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1"
                     src="https://drive.google.com/thumbnail?id=1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1&sz=w800"
                     alt="Tủ bếp Tường An Khang"
                     class="w-full h-full object-cover">
              </div>
            </div>
            <div class="flex items-center justify-between bg-black/25 px-2.5 py-1.5 rounded text-[10px] text-white">
              <span>Miễn phí Thiết kế 3D &amp; Đo đạc</span>
              <a href="#form-bao-gia" class="bg-amber-400 text-[#6E1414] font-extrabold px-2 py-0.5 rounded">Nhận báo giá</a>
            </div>
          </div>

          <!-- Mobile Slide 2 (Kích thước bằng hệt Mobile Slide 1) -->
          <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex flex-col justify-between p-3.5"
               style="background: linear-gradient(160deg, #1E293B 0%, #6E1414 65%, #8B1E1E 100%);">
            <div class="flex items-center justify-between gap-2">
              <span class="bg-amber-400 text-[#6E1414] text-[9.5px] font-extrabold px-2 py-0.5 rounded uppercase">
                KHUYẾN MÃI TẬN XƯỞNG
              </span>
              <span class="text-[10px] text-amber-300 font-bold">
                0905.052.458 - 0905.116.357
              </span>
            </div>
            <div class="grid grid-cols-12 gap-2.5 items-center my-auto">
              <div class="col-span-7 text-white space-y-1">
                <h2 class="text-[13px] font-extrabold leading-tight uppercase text-amber-300">
                  ƯU ĐÃI ĐẾN 25% TRỌN GÓI BẾP
                </h2>
                <p class="text-[11px] font-bold leading-snug text-white">
                  Phân Phối Bếp Từ, Máy Hút Mùi &amp; Phụ Kiện Tủ Bếp Inox 304 Chính Hãng
                </p>
                <div class="text-[10px] text-slate-200 leading-tight space-y-0.5 pt-0.5">
                  <div>• Bảo hành chính hãng dài hạn</div>
                  <div>• Lắp đặt tận nơi toàn Đà Nẵng</div>
                </div>
              </div>
              <div class="col-span-5 h-[135px] rounded overflow-hidden border border-amber-400/70 bg-slate-900">
                <img data-drive-id="19DCXMXuKGT-1svYY5cGE21_Kr8EEQqZJ"
                     src="https://drive.google.com/thumbnail?id=19DCXMXuKGT-1svYY5cGE21_Kr8EEQqZJ&sz=w800"
                     alt="Tủ bếp Acrylic Tường An Khang"
                     class="w-full h-full object-cover">
              </div>
            </div>
            <div class="flex items-center justify-between bg-black/25 px-2.5 py-1.5 rounded text-[10px] text-white">
              <span>Xưởng trực tiếp không qua trung gian</span>
              <a href="#sec-tat-ca-san-pham" class="bg-amber-400 text-[#6E1414] font-extrabold px-2 py-0.5 rounded">Xem sản phẩm</a>
            </div>
          </div>
        </div>

        <!-- Nút điều khiển & Chấm chuyển Slide Banner -->
        <button id="prevBannerBtn" type="button" aria-label="Slide trước" class="
          absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center z-20">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button id="nextBannerBtn" type="button" aria-label="Slide tiếp" class="
          absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center z-20">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button type="button" onclick="setBannerSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
          <button type="button" onclick="setBannerSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- ==========================================================================
       5. DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, TỐI ƯU TRÊN ĐT & MÁY TÍNH)
          Lấy theo hệ thống danh mục web mẫu tubephome3d.com
       ========================================================================== -->
  <section id="sec-danh-muc" class="py-2">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg p-3 shadow-sm border border-slate-200">
        <div class="flex items-center justify-between mb-2.5 pb-1.5 border-b border-slate-100">
          <h2 class="text-xs sm:text-sm font-extrabold uppercase text-[#8B1E1E] flex items-center gap-1.5">
            <i class="fa-solid fa-layer-group"></i> DANH MỤC SẢN PHẨM CHÍNH
          </h2>
          <span class="text-[11px] text-slate-500">Chọn danh mục để lọc nhanh</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2">
          <button type="button" onclick="filterByCategory('ALL')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-border-all text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Tất Cả Sản Phẩm</div>
          </button>

          <button type="button" onclick="filterByCategory('Tủ Bếp Inox Cánh Kính')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-shield-halved text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Tủ Bếp Inox Cánh Kính</div>
          </button>

          <button type="button" onclick="filterByCategory('Tủ Bếp Cánh Acrylic')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-kitchen-set text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Tủ Bếp Cánh Acrylic</div>
          </button>

          <button type="button" onclick="filterByCategory('Tủ Bếp Gỗ Công Nghiệp')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-cubes text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Tủ Bếp Gỗ Công Nghiệp</div>
          </button>

          <button type="button" onclick="filterByCategory('Tủ Bếp Gỗ Nhựa Picomat')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-droplet-slash text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Tủ Bếp Nhựa Picomat</div>
          </button>

          <button type="button" onclick="filterByCategory('Tủ Bếp Gỗ Tự Nhiên')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-tree text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Tủ Bếp Gỗ Tự Nhiên</div>
          </button>

          <button type="button" onclick="filterByCategory('Nội Thất Gia Đình')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-couch text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Nội Thất Phòng Khách &amp; Ngủ</div>
          </button>

          <button type="button" onclick="filterByCategory('Thiết Bị Bếp')" class="cat-box group bg-slate-50 hover:bg-[#8B1E1E] border border-slate-200 rounded p-2 text-center transition">
            <div class="w-8 h-8 mx-auto mb-1 rounded-full bg-red-50 group-hover:bg-white/20 flex items-center justify-center text-[#8B1E1E] group-hover:text-amber-300">
              <i class="fa-solid fa-fire-burner text-xs"></i>
            </div>
            <div class="text-[11px] font-bold text-slate-800 group-hover:text-white leading-tight">Thiết Bị &amp; Phụ Kiện Bếp</div>
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       6. DANH MỤC 1: TỦ BẾP ĐẸP GIÁ XƯỞNG (8 ẢNH SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE)
          - Chia 2 cột trên Điện thoại (grid-cols-2), 4 cột trên Máy tính (lg:grid-cols-4)
          - Có % giảm giá góc trên bên trái chuẩn Flatsome, không để nhãn dán phụ
          - Tên sản phẩm hiển thị trọn vẹn, không tràn viền, không cắt chữ
       ========================================================================== -->
  <section id="sec-tu-bep" class="py-3">
    <div class="flatsome-container">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-kitchen-set"></i> TỦ BẾP CAO CẤP GIÁ XƯỞNG
        </h2>
        <div class="subcat-pills">
          <span onclick="filterByCategory('ALL')" class="subcat-pill active">Tất cả</span>
          <span onclick="filterByCategory('Tủ Bếp Inox Cánh Kính')" class="subcat-pill">Tủ bếp Inox cánh kính</span>
          <span onclick="filterByCategory('Tủ Bếp Cánh Acrylic')" class="subcat-pill">Tủ bếp Cánh Acrylic</span>
          <span onclick="filterByCategory('Tủ Bếp Gỗ Công Nghiệp')" class="subcat-pill">Tủ bếp Gỗ Công Nghiệp</span>
          <span onclick="filterByCategory('Tủ Bếp Gỗ Nhựa Picomat')" class="subcat-pill">Tủ bếp Nhựa Picomat</span>
          <span onclick="filterByCategory('Tủ Bếp Gỗ Tự Nhiên')" class="subcat-pill">Tủ bếp Gỗ Tự Nhiên</span>
        </div>
      </div>

      <!-- Grid 2 cột trên ĐT, 4 cột trên Máy tính -->
      <div id="kitchenProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-3.5">
        <!-- Được render tự động từ mảng 14 ảnh thực tế Google Drive bên dưới -->
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       7. DANH MỤC 2: NỘI THẤT PHÒNG KHÁCH - PHÒNG NGỦ & THIẾT BỊ BẾP
          (6 ẢNH SẢN PHẨM THỰC TẾ TIẾP THEO TRONG 14 FILE GOOGLE DRIVE)
       ========================================================================== -->
  <section id="sec-noi-that" class="py-3">
    <div class="flatsome-container">
      <div id="sec-thiet-bi-bep" class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-couch"></i> NỘI THẤT GIA ĐÌNH &amp; THIẾT BỊ NHÀ BẾP
        </h2>
        <div class="subcat-pills">
          <span onclick="filterByCategory('ALL')" class="subcat-pill active">Xem tất cả</span>
          <span onclick="filterByCategory('Nội Thất Gia Đình')" class="subcat-pill">Nội thất phòng khách</span>
          <span onclick="filterByCategory('Nội Thất Gia Đình')" class="subcat-pill">Nội thất phòng ngủ</span>
          <span onclick="filterByCategory('Nội Thất Gia Đình')" class="subcat-pill">Tủ áo cánh kính</span>
          <span onclick="filterByCategory('Thiết Bị Bếp')" class="subcat-pill">Thiết bị bếp &amp; Phụ kiện</span>
        </div>
      </div>

      <!-- Grid 2 cột trên ĐT, 3-4 cột trên Máy tính -->
      <div id="interiorProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-2.5 sm:gap-3.5">
        <!-- Được render tự động từ mảng 14 ảnh thực tế Google Drive bên dưới -->
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       8. FORM YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ TRANG CHỦ (CHUẨN UX BUILDER FLATSOME)
       ========================================================================== -->
  <section id="form-bao-gia" class="py-4">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
        <div class="grid grid-cols-1 lg:grid-cols-12">
          
          <!-- Cột thông tin quy trình & cam kết -->
          <div class="lg:col-span-5 bg-[#8B1E1E] text-white p-5 sm:p-6 flex flex-col justify-between">
            <div class="space-y-3">
              <div class="text-xs font-extrabold uppercase tracking-wider text-amber-300">
                CÔNG TY TNHH TƯỜNG AN KHANG • ĐÀ NẴNG
              </div>
              <h2 class="text-lg sm:text-xl font-extrabold uppercase leading-snug">
                ĐĂNG KÝ TƯ VẤN THIẾT KẾ 3D &amp; NHẬN BÁO GIÁ TẬN XƯỞNG
              </h2>
              <p class="text-xs text-amber-100 leading-relaxed">
                Quý khách để lại thông tin hoặc kích thước sơ bộ, Kỹ sư Tường An Khang sẽ liên hệ gửi bảng báo giá chi tiết từng hạng mục vật liệu (Inox 304, Acrylic, Picomat, MDF An Cường, Thiết bị bếp) trong vòng 15 phút.
              </p>

              <div class="space-y-2 pt-2 text-xs">
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                  <span>Khảo sát thực tế tận nhà tại Đà Nẵng &amp; Quảng Nam hoàn toàn miễn phí.</span>
                </div>
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                  <span>Miễn phí 100% bản vẽ phối cảnh 3D &amp; bản vẽ kỹ thuật 2D khi thi công.</span>
                </div>
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                  <span>Cam kết đúng 100% chủng loại vật liệu theo hợp đồng, bảo hành đến 5 năm.</span>
                </div>
              </div>
            </div>

            <div class="mt-5 pt-4 border-t border-white/15 text-xs space-y-1">
              <div><i class="fa-solid fa-store text-amber-400 mr-1.5"></i><strong>Showroom 1:</strong> 176 Nguyễn Hữu Thọ - Đà Nẵng</div>
              <div><i class="fa-solid fa-store text-amber-400 mr-1.5"></i><strong>Showroom 2:</strong> 239 Nguyễn Hữu Thọ - Đà Nẵng</div>
              <div class="text-amber-300 font-bold pt-1">
                <i class="fa-solid fa-phone-volume mr-1.5"></i>Hotline/Zalo: 0905.052.458 - 0905.116.357
              </div>
            </div>
          </div>

          <!-- Cột Form nhập yêu cầu -->
          <div class="lg:col-span-7 p-5 sm:p-6 bg-white">
            <h3 class="text-sm sm:text-base font-extrabold text-slate-800 uppercase mb-3 pb-2 border-b border-slate-100">
              <i class="fa-solid fa-pen-to-square text-[#8B1E1E] mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NHANH
            </h3>

            <form id="quoteRequestForm" class="space-y-3">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input id="custName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-[#8B1E1E]">
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="custPhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-[#8B1E1E]">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                  <select id="custCategory" class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-[#8B1E1E] bg-white">
                    <option value="Thi công Tủ Bếp Inox Cánh Kính Cường Lực">Thi công Tủ Bếp Inox Cánh Kính Cường Lực</option>
                    <option value="Thi công Tủ Bếp Cánh Phủ Acrylic Bóng Gương">Thi công Tủ Bếp Cánh Phủ Acrylic Bóng Gương</option>
                    <option value="Thi công Tủ Bếp Nhựa Picomat Chống Nước">Thi công Tủ Bếp Nhựa Picomat Chống Nước</option>
                    <option value="Thi công Tủ Bếp Gỗ Công Nghiệp MDF An Cường">Thi công Tủ Bếp Gỗ Công Nghiệp MDF An Cường</option>
                    <option value="Thi công Tủ Bếp Gỗ Tự Nhiên">Thi công Tủ Bếp Gỗ Tự Nhiên</option>
                    <option value="Nội Thất Phòng Khách - Phòng Ngủ Trọn Gói">Nội Thất Phòng Khách - Phòng Ngủ Trọn Gói</option>
                    <option value="Mua Thiết Bị Bếp & Phụ Kiện Tủ Bếp Inox 304">Mua Thiết Bị Bếp &amp; Phụ Kiện Tủ Bếp Inox 304</option>
                    <option value="Cải Tạo - Sửa Chữa Tủ Bếp Cũ">Cải Tạo - Sửa Chữa Tủ Bếp Cũ</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình</label>
                  <input id="custAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng, Quảng Nam..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-[#8B1E1E]">
                </div>
              </div>

              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Yêu cầu chi tiết (Kích thước bếp dự kiến, kiểu chữ I / L / U, sản phẩm quan tâm...)</label>
                <textarea id="custNote" rows="3" placeholder="Nhập kích thước sơ bộ hoặc mẫu sản phẩm quý khách cần báo giá..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-[#8B1E1E]"></textarea>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                <button type="submit" class="bg-[#8B1E1E] hover:bg-[#6E1414] text-white font-extrabold text-xs uppercase px-5 py-2.5 rounded shadow transition">
                  <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ NGAY
                </button>
                <span class="text-[11px] text-slate-500">
                  Hoặc kết nối Zalo: <strong class="text-[#8B1E1E]">0905.052.458 - 0905.116.357</strong>
                </span>
              </div>
            </form>

            <!-- Hộp thông báo xác nhận gửi Form (không dùng alert) -->
            <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs">
              <div class="font-bold"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Đã tiếp nhận yêu cầu báo giá thành công!</div>
              <div id="quoteSuccessDetail" class="mt-1 text-[11.5px]"></div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (CẨM NANG TỦ BẾP & PHONG THỦY)
          Thiết kế giống web mẫu tubephome3d.com
       ========================================================================== -->
  <section id="sec-tin-tuc" class="py-3">
    <div class="flatsome-container">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-newspaper"></i> CẨM NANG TỦ BẾP &amp; KINH NGHIỆM NỘI THẤT
        </h2>
        <div class="subcat-pills">
          <span class="subcat-pill active">Báo giá tủ bếp Đà Nẵng</span>
          <span class="subcat-pill">Kinh nghiệm chọn vật liệu</span>
          <span class="subcat-pill">Phong thủy nhà bếp</span>
        </div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3">
        <!-- Bài viết 1 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-100">
            <img data-drive-id="1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1"
                 src="https://drive.google.com/thumbnail?id=1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1&sz=w800"
                 alt="Báo giá tủ bếp Inox cánh kính tại Đà Nẵng"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[10.5px] font-bold text-[#8B1E1E] uppercase">Báo Giá Tủ Bếp</span>
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 mt-1 leading-snug">
                Báo Giá Tủ Bếp Inox 304 Cánh Kính Cường Lực Tại Đà Nẵng Mới Nhất
              </h3>
              <p class="text-[11.5px] text-slate-600 mt-1.5 leading-relaxed">
                Phân tích ưu điểm vượt trội của thùng tủ bếp Inox 304 chấn gấp CNC kết hợp cánh kính cường lực khung nhôm chống nước, chống mối mọt tuyệt đối.
              </p>
            </div>
            <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11.5px] font-bold text-[#8B1E1E] mt-2.5 hover:underline">
              Xem chi tiết &amp; Nhận báo giá <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-100">
            <img data-drive-id="1-Q5rxr7B92fJzot5qakKu9Qk1Y-gPpkR"
                 src="https://drive.google.com/thumbnail?id=1-Q5rxr7B92fJzot5qakKu9Qk1Y-gPpkR&sz=w800"
                 alt="Tủ bếp nhựa Picomat cánh phủ Acrylic"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[10.5px] font-bold text-[#8B1E1E] uppercase">Tư Vấn Vật Liệu</span>
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 mt-1 leading-snug">
                So Sánh Tủ Bếp Nhựa Picomat Và Tủ Bếp Gỗ Công Nghiệp MDF Chống Ẩm
              </h3>
              <p class="text-[11.5px] text-slate-600 mt-1.5 leading-relaxed">
                Giải pháp kết hợp thùng tủ dưới bằng nhựa đặc Picomat chịu nước 100% và thùng tủ trên MDF lõi xanh phủ Acrylic bóng gương tiết kiệm chi phí.
              </p>
            </div>
            <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11.5px] font-bold text-[#8B1E1E] mt-2.5 hover:underline">
              Xem chi tiết &amp; Nhận báo giá <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-100">
            <img data-drive-id="1I9w0uONXjS9Wf_Ghz6siVg58_mciWPvq"
                 src="https://drive.google.com/thumbnail?id=1I9w0uONXjS9Wf_Ghz6siVg58_mciWPvq&sz=w800"
                 alt="Xu hướng tủ quần áo cánh kính và nội thất hiện đại"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[10.5px] font-bold text-[#8B1E1E] uppercase">Xu Hướng Nội Thất</span>
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 mt-1 leading-snug">
                Xu Hướng Thi Công Tủ Áo Cánh Kính Đèn LED &amp; Nội Thất Phòng Ngủ Đồng Bộ
              </h3>
              <p class="text-[11.5px] text-slate-600 mt-1.5 leading-relaxed">
                Tổng hợp các công trình nội thất phòng khách, vách tivi và tủ quần áo cánh kính sang trọng do Tường An Khang trực tiếp sản xuất, lắp đặt.
              </p>
            </div>
            <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11.5px] font-bold text-[#8B1E1E] mt-2.5 hover:underline">
              Xem chi tiết &amp; Nhận báo giá <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-100">
            <img data-drive-id="1fnol_d-NfZSrmJIvbSDeGbD5XnXoGaVM"
                 src="https://drive.google.com/thumbnail?id=1fnol_d-NfZSrmJIvbSDeGbD5XnXoGaVM&sz=w800"
                 alt="Kinh nghiệm chọn thiết bị bếp và phụ kiện tủ bếp"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[10.5px] font-bold text-[#8B1E1E] uppercase">Thiết Bị &amp; Phong Thủy</span>
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 mt-1 leading-snug">
                Cách Bố Trí Bếp Từ, Máy Hút Mùi Và Chậu Rửa Hợp Phong Thủy Nhà Bếp
              </h3>
              <p class="text-[11.5px] text-slate-600 mt-1.5 leading-relaxed">
                Nguyên tắc tam giác công năng (Bếp nấu - Chậu rửa - Tủ lạnh) và kích thước lỗ ban chuẩn phong thủy mang lại tài lộc cho gia chủ.
              </p>
            </div>
            <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11.5px] font-bold text-[#8B1E1E] mt-2.5 hover:underline">
              Xem chi tiết &amp; Nhận báo giá <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       10. DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU TRANG CHỦ
       ========================================================================== -->
  <section id="sec-doi-tac" class="py-3">
    <div class="flatsome-container">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-handshake"></i> ĐỐI TÁC VẬT LIỆU &amp; THIẾT BỊ BẾP CHÍNH HÃNG
        </h2>
        <span class="text-xs text-slate-500 px-3 py-1">Cam kết 100% vật tư &amp; phụ kiện chính hãng</span>
      </div>

      <div class="bg-white rounded-lg p-3 border border-slate-200 shadow-sm">
        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">AN CƯỜNG</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Gỗ Công Nghiệp</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">PICOMAT</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Gỗ Nhựa Chống Nước</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">HAFELE</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Phụ Kiện &amp; Thiết Bị</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">BLUM</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Bản Lề &amp; Ray Trượt</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">BOSCH</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Nhà Bếp Đức</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">EUROGOLD</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Phụ Kiện Inox 304</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">MALLOCA</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Bếp Từ &amp; Hút Mùi</div>
          </div>
          <div class="border border-slate-200 rounded p-2.5 text-center bg-slate-50 hover:border-[#8B1E1E] transition">
            <div class="text-xs font-extrabold text-[#8B1E1E]">GARIS / CARINY</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Phụ Kiện Tủ Bếp</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       11. BẢN ĐỒ GOOGLE MAPS (2 SHOWROOM) & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
           - Showroom 1: 176 Nguyễn Hữu Thọ - Đà Nẵng
           - Showroom 2: 239 Nguyễn Hữu Thọ - Đà Nẵng
           - Fanpage: https://www.facebook.com/noithatbeptuongankhang
       ========================================================================== -->
  <section id="sec-lien-he-map" class="py-3">
    <div class="flatsome-container">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-map-location-dot"></i> HỆ THỐNG SHOWROOM GOOGLE MAPS &amp; FANPAGE TƯỜNG AN KHANG
        </h2>
        <span class="text-xs font-semibold text-[#8B1E1E] px-3 py-1">
          Hotline: 0905.052.458 - 0905.116.357
        </span>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-3.5">
        
        <!-- Cột Bản đồ Google Maps 2 Showroom ngoài trang chủ -->
        <div class="lg:col-span-7 bg-white rounded-lg border border-slate-200 p-3 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
              <div class="text-xs font-extrabold text-[#8B1E1E] uppercase">
                <i class="fa-solid fa-location-dot mr-1"></i> BẢN ĐỒ VỊ TRÍ 2 SHOWROOM TẠI ĐÀ NẴNG
              </div>
              <div class="flex flex-wrap gap-1.5">
                <button type="button" onclick="switchMapShowroom(1)" id="btnMapSR1" class="text-[11px] font-bold px-2.5 py-1 rounded bg-[#8B1E1E] text-white transition">
                  Showroom 1: 176 Nguyễn Hữu Thọ
                </button>
                <button type="button" onclick="switchMapShowroom(2)" id="btnMapSR2" class="text-[11px] font-bold px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-slate-200 transition">
                  Showroom 2: 239 Nguyễn Hữu Thọ
                </button>
              </div>
            </div>

            <!-- Google Map Embed trực tiếp ngoài trang chủ -->
            <div class="w-full h-[250px] sm:h-[280px] rounded overflow-hidden border border-slate-200 relative bg-slate-100">
              <iframe
                id="googleMapIframe"
                title="Bản đồ Google Maps Công Ty TNHH Tường An Khang"
                src="https://maps.google.com/maps?q=176%20Nguy%E1%BB%85n%20H%E1%BB%AFu%20Th%E1%BB%8D%2C%20H%E1%BA%A3i%20Ch%C3%A2u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 mt-2.5 text-xs">
            <div class="p-2.5 rounded bg-red-50/70 border border-red-100">
              <div class="font-extrabold text-[#8B1E1E]">SHOWROOM 1: 176 NGUYỄN HỮU THỌ</div>
              <div class="text-[11px] text-slate-600 mt-0.5">176 Nguyễn Hữu Thọ, Quận Hải Châu, TP. Đà Nẵng</div>
              <a href="https://www.google.com/maps/search/?api=1&query=176+Nguyen+Huu+Tho+Da+Nang" target="_blank" rel="noopener noreferrer" class="inline-block mt-1 text-[11px] font-bold text-[#8B1E1E] hover:underline">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở chỉ đường Google Maps
              </a>
            </div>
            <div class="p-2.5 rounded bg-amber-50/70 border border-amber-200">
              <div class="font-extrabold text-[#8B1E1E]">SHOWROOM 2: 239 NGUYỄN HỮU THỌ</div>
              <div class="text-[11px] text-slate-600 mt-0.5">239 Nguyễn Hữu Thọ, Quận Hải Châu, TP. Đà Nẵng</div>
              <a href="https://www.google.com/maps/search/?api=1&query=239+Nguyen+Huu+Tho+Da+Nang" target="_blank" rel="noopener noreferrer" class="inline-block mt-1 text-[11px] font-bold text-[#8B1E1E] hover:underline">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở chỉ đường Google Maps
              </a>
            </div>
          </div>
        </div>

        <!-- Cột Fanpage Facebook chính thức ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-lg border border-slate-200 p-3 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between mb-2.5">
              <div class="text-xs font-extrabold text-[#1877F2] uppercase flex items-center gap-1.5">
                <i class="fa-brands fa-facebook text-base"></i> FANPAGE NỘI THẤT BẾP TƯỜNG AN KHANG
              </div>
              <a href="https://www.facebook.com/noithatbeptuongankhang" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-[#1877F2] hover:underline">
                Theo dõi trang <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
              </a>
            </div>

            <!-- Khung Fanpage trực quan + Iframe Facebook Page Plugin -->
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
              <div class="p-3 bg-gradient-to-r from-[#8B1E1E] to-[#4A0D0D] text-white flex items-center justify-between gap-2">
                <div class="flex items-center gap-2.5">
                  <div class="w-11 h-11 rounded-full bg-white text-[#8B1E1E] font-extrabold flex items-center justify-center border-2 border-amber-400 shrink-0 text-xs">
                    TAK
                  </div>
                  <div>
                    <a href="https://www.facebook.com/noithatbeptuongankhang" target="_blank" rel="noopener noreferrer" class="font-extrabold text-xs sm:text-sm text-white hover:underline block">
                      Nội Thất Bếp Tường An Khang
                    </a>
                    <div class="text-[11px] text-amber-200">@noithatbeptuongankhang • Tủ Bếp &amp; Nội Thất Đà Nẵng</div>
                  </div>
                </div>
                <a href="https://www.facebook.com/noithatbeptuongankhang" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white text-[11px] font-bold px-2.5 py-1.5 rounded shrink-0">
                  <i class="fa-brands fa-facebook-f mr-1"></i> Thích trang
                </a>
              </div>

              <!-- Facebook Page Plugin nhúng trực tiếp + Hình ảnh thực tế trên Fanpage -->
              <div class="p-2.5 space-y-2">
                <div class="w-full overflow-hidden rounded border border-slate-200 bg-white">
                  <iframe
                    title="Fanpage Nội Thất Bếp Tường An Khang"
                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fnoithatbeptuongankhang&tabs=timeline&width=500&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                    width="100%"
                    height="210"
                    style="border:none;overflow:hidden"
                    scrolling="no"
                    frameborder="0"
                    allowfullscreen="true"
                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                  </iframe>
                </div>

                <div class="bg-white p-2.5 rounded border border-slate-200 text-[11.5px] text-slate-700 space-y-1">
                  <div class="font-bold text-slate-800">
                    <i class="fa-solid fa-circle-check text-[#1877F2] mr-1"></i> Cập nhật công trình tủ bếp &amp; nội thất thực tế mỗi ngày
                  </div>
                  <div>• Showroom 1: 176 Nguyễn Hữu Thọ - Đà Nẵng</div>
                  <div>• Showroom 2: 239 Nguyễn Hữu Thọ - Đà Nẵng</div>
                  <div>• Hotline/Zalo: <strong class="text-[#8B1E1E]">0905.052.458 - 0905.116.357</strong></div>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-2.5 flex flex-wrap gap-2">
            <a href="https://www.facebook.com/noithatbeptuongankhang" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold py-2 px-3 rounded transition">
              <i class="fa-brands fa-facebook-messenger mr-1"></i> Nhắn Tin Fanpage
            </a>
            <a href="https://zalo.me/0905052458" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-sky-600 hover:bg-sky-700 text-white text-xs font-bold py-2 px-3 rounded transition">
              <i class="fa-solid fa-comment-dots mr-1"></i> Chat Zalo Báo Giá
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ==========================================================================
       12. FOOTER CHUẨN FLATSOME (CÔNG TY TNHH TƯỜNG AN KHANG - TUONGANKHANG.COM)
       ========================================================================== -->
  <footer id="gioi-thieu" class="bg-[#1E293B] text-slate-200 pt-8 pb-20 md:pb-8 mt-4 border-t-4 border-[#8B1E1E]">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-slate-700">
        
        <!-- Thông tin pháp nhân Công ty -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded bg-[#8B1E1E] border border-amber-400 flex items-center justify-center font-extrabold text-amber-300 text-xs">
              TAK
            </div>
            <div>
              <h3 class="text-sm font-extrabold text-white uppercase">CÔNG TY TNHH TƯỜNG AN KHANG</h3>
              <div class="text-[11px] text-amber-400 font-semibold">Website chính thức: tuongankhang.com</div>
            </div>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed">
            Đơn vị uy tín hàng đầu tại Đà Nẵng &amp; Miền Trung chuyên tư vấn, thiết kế 3D, sản xuất và thi công trọn gói Tủ Bếp Inox Cánh Kính, Tủ Bếp Acrylic, Tủ Bếp Nhựa Picomat, Gỗ Công Nghiệp An Cường, Nội Thất Gia Đình và phân phối Thiết Bị Nhà Bếp chính hãng.
          </p>
          <ul class="text-xs space-y-1.5 text-slate-200 pt-1">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Showroom 1:</strong> 176 Nguyễn Hữu Thọ - Đà Nẵng</li>
            <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Showroom 2:</strong> 239 Nguyễn Hữu Thọ - Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i><strong>Điện thoại / Zalo:</strong> 0905.052.458 - 0905.116.357</li>
            <li><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> tuongankhang.com</li>
            <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i><strong>Fanpage:</strong> fb.com/noithatbeptuongankhang</li>
          </ul>
        </div>

        <!-- Danh mục Tủ bếp & Nội thất -->
        <div class="lg:col-span-4 space-y-2">
          <h4 class="text-xs font-extrabold uppercase text-amber-400 tracking-wider pb-1 border-b border-slate-700">
            DANH MỤC SẢN PHẨM CHỦ LỰC
          </h4>
          <div class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
            <a href="#sec-tu-bep" class="hover:text-amber-300">• Tủ Bếp Inox Cánh Kính</a>
            <a href="#sec-tu-bep" class="hover:text-amber-300">• Tủ Bếp Cánh Acrylic</a>
            <a href="#sec-tu-bep" class="hover:text-amber-300">• Tủ Bếp Gỗ Công Nghiệp</a>
            <a href="#sec-tu-bep" class="hover:text-amber-300">• Tủ Bếp Nhựa Picomat</a>
            <a href="#sec-tu-bep" class="hover:text-amber-300">• Tủ Bếp Cánh Laminate</a>
            <a href="#sec-tu-bep" class="hover:text-amber-300">• Tủ Bếp Gỗ Tự Nhiên</a>
            <a href="#sec-noi-that" class="hover:text-amber-300">• Nội Thất Phòng Khách</a>
            <a href="#sec-noi-that" class="hover:text-amber-300">• Nội Thất Phòng Ngủ</a>
            <a href="#sec-noi-that" class="hover:text-amber-300">• Tủ Áo Cánh Kính LED</a>
            <a href="#sec-thiet-bi-bep" class="hover:text-amber-300">• Thiết Bị &amp; Phụ Kiện Bếp</a>
          </div>
        </div>

        <!-- Chính sách khách hàng -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="text-xs font-extrabold uppercase text-amber-400 tracking-wider pb-1 border-b border-slate-700">
            CHÍNH SÁCH &amp; CAM KẾT
          </h4>
          <ul class="text-xs space-y-1.5 text-slate-300">
            <li>• Miễn phí khảo sát &amp; Thiết kế 3D</li>
            <li>• Báo giá gốc trực tiếp tại xưởng</li>
            <li>• Chính sách bảo hành lên đến 5 năm</li>
            <li>• Bảo trì trọn đời sản phẩm</li>
            <li>• Giao hàng &amp; Lắp đặt tận nơi</li>
          </ul>
        </div>
      </div>

      <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>© Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH TƯỜNG AN KHANG (tuongankhang.com)</strong>. Giao diện chuẩn Flatsome UX Builder.</div>
        <div>Showroom 1: 176 Nguyễn Hữu Thọ - Đà Nẵng | Showroom 2: 239 Nguyễn Hữu Thọ - Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ==========================================================================
       13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
           Tương thích hoàn hảo trên cả Máy tính và Điện thoại, không tràn viền
       ========================================================================== -->
  <div class="floating-contact-group">
    <!-- Nút Zalo nổi bật -->
    <a href="https://zalo.me/0905052458" target="_blank" rel="noopener noreferrer"
       class="inline-flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg text-xs font-extrabold transition">
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-black text-[10px] shrink-0">Zalo</span>
      <span class="pr-1">Chat Zalo: 0905.052.458</span>
    </a>

    <!-- Nút Facebook Fanpage nổi bật -->
    <a href="https://www.facebook.com/noithatbeptuongankhang" target="_blank" rel="noopener noreferrer"
       class="inline-flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg text-xs font-extrabold transition">
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="pr-1">Fanpage Tường An Khang</span>
    </a>

    <!-- Nút Hotline 1 & 2 nổi bật -->
    <a href="tel:0905052458"
       class="pulse-btn inline-flex items-center gap-2 bg-[#8B1E1E] hover:bg-[#6E1414] text-white px-3 py-2 rounded-full shadow-lg text-xs font-extrabold border border-amber-400 transition">
      <span class="w-6 h-6 rounded-full bg-amber-400 text-[#6E1414] flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="pr-1">0905.052.458 - 0905.116.357</span>
    </a>
  </div>

  <!-- ==========================================================================
       14. MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT BÁO GIÁ NHANH (KHÔNG DÙNG ALERT)
       ========================================================================== -->
  <div id="productDetailModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="bg-[#8B1E1E] text-white px-4 py-2.5 flex items-center justify-between">
        <div id="modalProductCategory" class="text-xs font-bold uppercase text-amber-300">CHI TIẾT SẢN PHẨM</div>
        <button type="button" onclick="closeProductModal()" class="w-7 h-7 rounded bg-white/15 flex items-center justify-center hover:bg-white/25">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 grid grid-cols-1 sm:grid-cols-12 gap-4 items-center">
        <div class="sm:col-span-6 h-56 sm:h-64 rounded overflow-hidden border border-slate-200 bg-slate-100 relative">
          <img id="modalProductImg" src="" alt="Ảnh sản phẩm thực tế" class="w-full h-full object-cover">
          <span id="modalProductDiscount" class="flatsome-sale-badge">-20%</span>
        </div>
        <div class="sm:col-span-6 space-y-2.5">
          <h3 id="modalProductTitle" class="text-sm sm:text-base font-extrabold text-slate-800 leading-snug"></h3>
          <div class="flex items-baseline gap-2">
            <span id="modalProductPrice" class="text-base font-extrabold text-[#D90429]"></span>
            <span id="modalProductOldPrice" class="text-xs text-slate-400 line-through"></span>
          </div>
          <p id="modalProductDesc" class="text-xs text-slate-600 leading-relaxed"></p>
          <div class="bg-slate-50 p-2.5 rounded border border-slate-200 text-[11px] text-slate-700 space-y-1">
            <div><i class="fa-solid fa-check text-emerald-600 mr-1"></i> Sản xuất &amp; phân phối: <strong>CÔNG TY TNHH TƯỜNG AN KHANG</strong></div>
            <div><i class="fa-solid fa-location-dot text-[#8B1E1E] mr-1"></i> SR1: 176 Nguyễn Hữu Thọ | SR2: 239 Nguyễn Hữu Thọ, Đà Nẵng</div>
            <div><i class="fa-solid fa-phone text-[#8B1E1E] mr-1"></i> Tư vấn: <strong>0905.052.458 - 0905.116.357</strong></div>
          </div>
          <div class="flex flex-wrap gap-2 pt-1">
            <button type="button" onclick="selectProductForQuote()" class="flex-1 bg-[#8B1E1E] hover:bg-[#6E1414] text-white text-xs font-bold py-2 px-3 rounded">
              <i class="fa-solid fa-calculator mr-1"></i> Nhận Báo Giá Mẫu Này
            </button>
            <a id="modalDriveLink" href="#" target="_blank" rel="noopener noreferrer" class="bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold py-2 px-3 rounded">
              <i class="fa-solid fa-expand mr-1"></i> Xem ảnh gốc
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ==========================================================================
       JAVASCRIPT: DỮ LIỆU 14 ẢNH THỰC TẾ GOOGLE DRIVE, BỘ LỌC, SLIDER & BẢN ĐỒ
       ========================================================================== -->
  <script>
    /* Danh sách đầy đủ 14 ảnh sản phẩm thực tế từ 14 link Google Drive của khách hàng,
       phân vào đúng danh mục và tên sản phẩm chuẩn theo mẫu tubephome3d.com */
    const PRODUCTS_DATA = [
      {
        id: 1,
        driveId: "1yKwbie1L8wCYLkB-TpkW8HEAQe7C5tE1",
        name: "Tủ Bếp Inox 304 Cánh Kính Cường Lực Khung Nhôm Cao Cấp (TAK-01)",
        category: "Tủ Bếp Inox Cánh Kính",
        section: "kitchen",
        price: "5.200.000₫/md",
        oldPrice: "6.500.000₫/md",
        discount: "-20%",
        desc: "Thùng tủ Inox 304 chấn gấp CNC chống nước, chống mối mọt vĩnh viễn kết hợp cánh kính cường lực tràn viền sang trọng."
      },
      {
        id: 2,
        driveId: "19DCXMXuKGT-1svYY5cGE21_Kr8EEQqZJ",
        name: "Tủ Bếp Gỗ Công Nghiệp MDF Lõi Xanh Cánh Phủ Acrylic Bóng Gương (TAK-02)",
        category: "Tủ Bếp Cánh Acrylic",
        section: "kitchen",
        price: "3.800.000₫/md",
        oldPrice: "4.600.000₫/md",
        discount: "-17%",
        desc: "Cốt gỗ MDF lõi xanh chống ẩm cao cấp kết hợp bề mặt cánh phủ Acrylic bóng gương không đường line hiện đại."
      },
      {
        id: 3,
        driveId: "1-Q5rxr7B92fJzot5qakKu9Qk1Y-gPpkR",
        name: "Tủ Bếp Gỗ Nhựa Picomat Chống Nước 100% Cánh Phủ Acrylic (TAK-03)",
        category: "Tủ Bếp Gỗ Nhựa Picomat",
        section: "kitchen",
        price: "4.500.000₫/md",
        oldPrice: "5.500.000₫/md",
        discount: "-18%",
        desc: "Thùng tủ 100% nhựa đặc Picomat siêu chịu nước, chống ẩm mốc tuyệt đối, cánh phủ Acrylic bóng gương dễ vệ sinh."
      },
      {
        id: 4,
        driveId: "1k0YVEHyJNw5QMCxmPcTpqqGPj__X7ZJz",
        name: "Tủ Bếp Gỗ Công Nghiệp An Cường Cánh Phủ Laminate Chống Trầy (TAK-04)",
        category: "Tủ Bếp Gỗ Công Nghiệp",
        section: "kitchen",
        price: "3.600.000₫/md",
        oldPrice: "4.300.000₫/md",
        discount: "-16%",
        desc: "Bề mặt Laminate vân gỗ chống trầy xước, chịu nhiệt cao, thiết kế thông minh tối ưu công năng nhà bếp."
      },
      {
        id: 5,
        driveId: "1XsJWYvOfx6KJ8mIYWF5jyYQWz2KNmD_N",
        name: "Mẫu Tủ Bếp Chữ L Cánh Acrylic Kèm Hệ Tủ Kho & Quầy Bar (TAK-05)",
        category: "Tủ Bếp Cánh Acrylic",
        section: "kitchen",
        price: "3.900.000₫/md",
        oldPrice: "4.800.000₫/md",
        discount: "-19%",
        desc: "Thiết kế tủ bếp kịch trần chữ L hiện đại, tích hợp đèn LED cảm ứng, khay gia vị và giá bát nâng hạ Inox 304."
      },
      {
        id: 6,
        driveId: "1deC9rdMn24t2DN6qenn5FfSSokK1PQiA",
        name: "Tủ Bếp Gỗ Công Nghiệp MDF Chống Ẩm Cánh Phủ Melamine (TAK-06)",
        category: "Tủ Bếp Gỗ Công Nghiệp",
        section: "kitchen",
        price: "3.200.000₫/md",
        oldPrice: "3.900.000₫/md",
        discount: "-18%",
        desc: "Giải pháp tủ bếp bền đẹp giá tận xưởng cho nhà phố và căn hộ chung cư tại Đà Nẵng."
      },
      {
        id: 7,
        driveId: "16PzlS4a1JPH0ucQENr87MZXl-3zr8E75",
        name: "Tủ Bếp Hợp Kim Nhôm Cánh Kính Cao Cấp Chống Nước Tuyệt Đối (TAK-07)",
        category: "Tủ Bếp Inox Cánh Kính",
        section: "kitchen",
        price: "4.900.000₫/md",
        oldPrice: "6.000.000₫/md",
        discount: "-18%",
        desc: "Khung thùng hợp kim nhôm tấm kết hợp cánh kính cường lực siêu bền, không cong vênh, tuổi thọ trên 20 năm."
      },
      {
        id: 8,
        driveId: "1jm0f32K1E0qAY8iDNuiUeomAPwtvoYY9",
        name: "Tủ Bếp Gỗ Tự Nhiên Sồi Nga Sơn Inchem Cao Cấp Giá Xưởng (TAK-08)",
        category: "Tủ Bếp Gỗ Tự Nhiên",
        section: "kitchen",
        price: "4.500.000₫/md",
        oldPrice: "5.400.000₫/md",
        discount: "-17%",
        desc: "Gỗ tự nhiên tẩm sấy kỹ lưỡng chống cong vênh, phun sơn PU Inchem 5 lớp giữ nguyên vân gỗ ấm cúng."
      },
      {
        id: 9,
        driveId: "1hKdk4vgZqHD9y2Ap0ZAuc6G7VAmYRjwJ",
        name: "Combo Nội Thất Phòng Khách Kệ Tivi Và Vách Ốp Trang Trí Hiện Đại (TAK-09)",
        category: "Nội Thất Gia Đình",
        section: "interior",
        price: "14.500.000₫",
        oldPrice: "18.000.000₫",
        discount: "-19%",
        desc: "Thi công trọn gói kệ tivi treo tường, vách ốp PVC vân đá và lam sóng gỗ công nghiệp sang trọng."
      },
      {
        id: 10,
        driveId: "1I9w0uONXjS9Wf_Ghz6siVg58_mciWPvq",
        name: "Tủ Quần Áo Cánh Kính Khung Nhôm Tích Hợp Đèn LED Cảm Ứng (TAK-10)",
        category: "Nội Thất Gia Đình",
        section: "interior",
        price: "2.650.000₫/m²",
        oldPrice: "3.200.000₫/m²",
        discount: "-17%",
        desc: "Tủ áo cánh kính cường lực màu trà/xám khói kết hợp hệ thống đèn LED thanh nhôm sang trọng cho phòng ngủ."
      },
      {
        id: 11,
        driveId: "1_-5mfeImsDIJOq9DwGLyjMuAZC4n2qlg",
        name: "Trọn Bộ Nội Thất Phòng Ngủ Giường Tủ Áo Và Bàn Trang Điểm Đồng Bộ (TAK-11)",
        category: "Nội Thất Gia Đình",
        section: "interior",
        price: "19.800.000₫",
        oldPrice: "24.500.000₫",
        discount: "-19%",
        desc: "Combo giường ngủ bọc nệm, tủ quần áo kịch trần, tab đầu giường và bàn phấn thiết kế may đo theo diện tích."
      },
      {
        id: 12,
        driveId: "1oWAorcMTQHvlez2VSLqHoeK4pVpaAh7M",
        name: "Hệ Vách Ngăn Phòng Khách Và Bếp Kết Hợp Tủ Rượu Trang Trí (TAK-12)",
        category: "Nội Thất Gia Đình",
        section: "interior",
        price: "12.500.000₫",
        oldPrice: "15.500.000₫",
        discount: "-19%",
        desc: "Tủ rượu kết hợp vách ngăn CNC phân chia không gian phòng khách và phòng bếp tinh tế, chuẩn phong thủy."
      },
      {
        id: 13,
        driveId: "1fnol_d-NfZSrmJIvbSDeGbD5XnXoGaVM",
        name: "Combo Thiết Bị Bếp Từ Đôi Inverter Và Máy Hút Mùi Kính Vát Cao Cấp (TAK-13)",
        category: "Thiết Bị Bếp",
        section: "interior",
        price: "8.900.000₫",
        oldPrice: "11.800.000₫",
        discount: "-25%",
        desc: "Trọn bộ bếp từ đôi mặt kính Schott Ceran/Kanger tiết kiệm điện và máy hút mùi cảm ứng vẫy tay siêu êm."
      },
      {
        id: 14,
        driveId: "1bPP6DipyH-XXVuHfqPoZuyiWPHBs27Sh",
        name: "Trọn Bộ Phụ Kiện Tủ Bếp Thông Minh Inox 304 Giá Bát Nâng Hạ & Kệ Xoong Nồi (TAK-14)",
        category: "Thiết Bị Bếp",
        section: "interior",
        price: "5.600.000₫",
        oldPrice: "7.200.000₫",
        discount: "-22%",
        desc: "Bộ phụ kiện tủ bếp Inox 304 chính hãng: giá bát nâng hạ, giá xoong nồi, kệ dao thớt gia vị ray giảm chấn."
      }
    ];

    let selectedProduct = null;
    let quoteCounter = 0;

    /* Chuỗi fallback tự động cho ảnh Google Drive để đảm bảo hiển thị 100% */
    function handleDriveImgError(imgEl, driveId) {
      const step = parseInt(imgEl.getAttribute("data-fallback-step") || "0", 10);
      if (step === 0) {
        imgEl.setAttribute("data-fallback-step", "1");
        imgEl.src = "https://lh3.googleusercontent.com/d/" + driveId + "=w1000";
      } else if (step === 1) {
        imgEl.setAttribute("data-fallback-step", "2");
        imgEl.src = "https://drive.google.com/uc?export=view&id=" + driveId;
      } else if (step === 2) {
        imgEl.setAttribute("data-fallback-step", "3");
        imgEl.src = "https://placehold.co/600x450/8B1E1E/FFFFFF?text=TUONG+AN+KHANG+SP+" + driveId.substring(0, 5);
      }
    }

    /* Tạo HTML thẻ sản phẩm chuẩn Flatsome:
       - Có % giảm giá ở góc trên bên trái
       - Không để các nhãn dán phụ khác
       - Tên sản phẩm hiển thị đầy đủ không cắt chữ, chia 2 cột trên điện thoại */
    function createProductCardHTML(item) {
      const thumbUrl = "https://drive.google.com/thumbnail?id=" + item.driveId + "&sz=w1000";
      return `
        <div class="flatsome-product-card group">
          <div class="relative w-full h-36 sm:h-48 bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${item.id})">
            <span class="flatsome-sale-badge">${item.discount}</span>
            <img src="${thumbUrl}"
                 alt="${item.name}"
                 onerror="handleDriveImgError(this, '${item.driveId}')"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10px] font-semibold text-slate-400 uppercase mb-0.5">${item.category}</div>
              <h3 class="flatsome-product-title cursor-pointer hover:text-[#8B1E1E]" onclick="openProductModal(${item.id})">
                ${item.name}
              </h3>
            </div>
            <div class="pt-1.5 border-t border-slate-100 mt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-xs sm:text-sm font-extrabold text-[#D90429]">${item.price}</span>
                <span class="text-[10.5px] sm:text-xs text-slate-400 line-through">${item.oldPrice}</span>
              </div>
              <div class="mt-2 flex items-center gap-1.5">
                <button type="button" onclick="openProductModal(${item.id})" class="w-full bg-[#8B1E1E] hover:bg-[#6E1414] text-white text-[11px] font-bold py-1.5 px-2 rounded transition">
                  Báo Giá Chi Tiết
                </button>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    function renderProducts(filterCategory = "ALL", searchKeyword = "") {
      const kitchenGrid = document.getElementById("kitchenProductGrid");
      const interiorGrid = document.getElementById("interiorProductGrid");
      const keyword = searchKeyword.trim().toLowerCase();

      const filtered = PRODUCTS_DATA.filter(item => {
        const matchCat = filterCategory === "ALL" || item.category.toLowerCase().includes(filterCategory.toLowerCase());
        const matchSearch = !keyword || item.name.toLowerCase().includes(keyword) || item.category.toLowerCase().includes(keyword);
        return matchCat && matchSearch;
      });

      const kitchenItems = filtered.filter(i => i.section === "kitchen");
      const interiorItems = filtered.filter(i => i.section === "interior");

      if (filterCategory !== "ALL" || keyword !== "") {
        kitchenGrid.innerHTML = filtered.map(createProductCardHTML).join("");
        interiorGrid.innerHTML = PRODUCTS_DATA.filter(i => i.section === "interior").map(createProductCardHTML).join("");
      } else {
        kitchenGrid.innerHTML = kitchenItems.map(createProductCardHTML).join("");
        interiorGrid.innerHTML = interiorItems.map(createProductCardHTML).join("");
      }
    }

    function filterByCategory(categoryName) {
      renderProducts(categoryName, "");
      const targetEl = document.getElementById("sec-tu-bep");
      if (targetEl && categoryName !== "ALL") {
        targetEl.scrollIntoView({ behavior: "smooth", block: "start" });
      }
    }

    /* Modal chi tiết sản phẩm */
    function openProductModal(productId) {
      const product = PRODUCTS_DATA.find(p => p.id === productId);
      if (!product) return;
      selectedProduct = product;

      document.getElementById("modalProductCategory").textContent = product.category;
      document.getElementById("modalProductTitle").textContent = product.name;
      document.getElementById("modalProductPrice").textContent = product.price;
      document.getElementById("modalProductOldPrice").textContent = product.oldPrice;
      document.getElementById("modalProductDiscount").textContent = product.discount;
      document.getElementById("modalProductDesc").textContent = product.desc;

      const imgEl = document.getElementById("modalProductImg");
      imgEl.setAttribute("data-fallback-step", "0");
      imgEl.onerror = function() { handleDriveImgError(imgEl, product.driveId); };
      imgEl.src = "https://drive.google.com/thumbnail?id=" + product.driveId + "&sz=w1000";

      document.getElementById("modalDriveLink").href = "https://drive.google.com/file/d/" + product.driveId + "/view?usp=sharing";

      const modal = document.getElementById("productDetailModal");
      modal.classList.remove("hidden");
      modal.classList.add("flex");
    }

    function closeProductModal() {
      const modal = document.getElementById("productDetailModal");
      modal.classList.add("hidden");
      modal.classList.remove("flex");
    }

    function selectProductForQuote() {
      if (selectedProduct) {
        quoteCounter++;
        document.getElementById("quoteCountBadge").textContent = String(quoteCounter);
        const noteEl = document.getElementById("custNote");
        noteEl.value = "Tôi quan tâm và muốn nhận báo giá mẫu: " + selectedProduct.name + " (Giá niêm yết: " + selectedProduct.price + ").";
      }
      closeProductModal();
      document.getElementById("form-bao-gia").scrollIntoView({ behavior: "smooth" });
      document.getElementById("custName").focus();
    }

    /* Chuyển đổi bản đồ Google Maps giữa Showroom 1 (176 Nguyễn Hữu Thọ) & Showroom 2 (239 Nguyễn Hữu Thọ) */
    function switchMapShowroom(srNumber) {
      const iframe = document.getElementById("googleMapIframe");
      const btn1 = document.getElementById("btnMapSR1");
      const btn2 = document.getElementById("btnMapSR2");

      if (srNumber === 1) {
        iframe.src = "https://maps.google.com/maps?q=176%20Nguy%E1%BB%85n%20H%E1%BB%AFu%20Th%E1%BB%8D%2C%20H%E1%BA%A3i%20Ch%C3%A2u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed";
        btn1.className = "text-[11px] font-bold px-2.5 py-1 rounded bg-[#8B1E1E] text-white transition";
        btn2.className = "text-[11px] font-bold px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-slate-200 transition";
      } else {
        iframe.src = "https://maps.google.com/maps?q=239%20Nguy%E1%BB%85n%20H%E1%BB%AFu%20Th%E1%BB%8D%2C%20H%E1%BA%A3i%20Ch%C3%A2u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed";
        btn2.className = "text-[11px] font-bold px-2.5 py-1 rounded bg-[#8B1E1E] text-white transition";
        btn1.className = "text-[11px] font-bold px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-slate-200 transition";
      }
    }

    /* Hệ thống 2 Banner tự trượt đồng bộ trên cả Máy tính và Điện thoại */
    let currentBannerIndex = 0;
    let bannerInterval = null;

    function updateBannerSlides() {
      const desktopSlides = document.querySelectorAll(".banner-slide-desktop");
      const mobileSlides = document.querySelectorAll(".banner-slide-mobile");
      const dots = document.querySelectorAll(".banner-dot");

      desktopSlides.forEach((slide, idx) => {
        if (idx === currentBannerIndex) {
          slide.classList.remove("opacity-0", "pointer-events-none");
          slide.classList.add("opacity-100");
        } else {
          slide.classList.remove("opacity-100");
          slide.classList.add("opacity-0", "pointer-events-none");
        }
      });

      mobileSlides.forEach((slide, idx) => {
        if (idx === currentBannerIndex) {
          slide.classList.remove("opacity-0", "pointer-events-none");
          slide.classList.add("opacity-100");
        } else {
          slide.classList.remove("opacity-100");
          slide.classList.add("opacity-0", "pointer-events-none");
        }
      });

      dots.forEach((dot, idx) => {
        dot.className = idx === currentBannerIndex
          ? "banner-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition"
          : "banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition";
      });
    }

    function setBannerSlide(index) {
      currentBannerIndex = index;
      updateBannerSlides();
      resetBannerTimer();
    }

    function nextBannerSlide() {
      currentBannerIndex = (currentBannerIndex + 1) % 2;
      updateBannerSlides();
    }

    function prevBannerSlide() {
      currentBannerIndex = (currentBannerIndex - 1 + 2) % 2;
      updateBannerSlides();
    }

    function resetBannerTimer() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(nextBannerSlide, 5500);
    }

    window.addEventListener("DOMContentLoaded", function() {
      renderProducts("ALL", "");
      resetBannerTimer();

      /* Gắn fallback cho các ảnh Drive trên Banner & Tin tức */
      document.querySelectorAll("img[data-drive-id]").forEach(img => {
        const driveId = img.getAttribute("data-drive-id");
        img.onerror = function() { handleDriveImgError(img, driveId); };
      });

      document.getElementById("nextBannerBtn").addEventListener("click", function() {
        nextBannerSlide();
        resetBannerTimer();
      });

      document.getElementById("prevBannerBtn").addEventListener("click", function() {
        prevBannerSlide();
        resetBannerTimer();
      });

      /* Tìm kiếm trên máy tính & điện thoại */
      document.getElementById("searchBtnDesktop").addEventListener("click", function() {
        const val = document.getElementById("searchInputDesktop").value;
        renderProducts("ALL", val);
      });
      document.getElementById("searchInputDesktop").addEventListener("keyup", function(e) {
        if (e.key === "Enter") renderProducts("ALL", e.target.value);
      });

      document.getElementById("searchBtnMobile").addEventListener("click", function() {
        const val = document.getElementById("searchInputMobile").value;
        renderProducts("ALL", val);
      });

      /* Menu Điện thoại */
      const mobileOverlay = document.getElementById("mobileMenuOverlay");
      document.getElementById("mobileMenuBtn").addEventListener("click", function() {
        mobileOverlay.classList.remove("hidden");
      });
      document.getElementById("closeMobileMenuBtn").addEventListener("click", function() {
        mobileOverlay.classList.add("hidden");
      });
      mobileOverlay.addEventListener("click", function(e) {
        if (e.target === mobileOverlay) mobileOverlay.classList.add("hidden");
      });
      document.querySelectorAll(".mobile-nav-item").forEach(link => {
        link.addEventListener("click", function() {
          mobileOverlay.classList.add("hidden");
        });
      });

      /* Xử lý Form Yêu cầu báo giá trang chủ */
      document.getElementById("quoteRequestForm").addEventListener("submit", function(e) {
        e.preventDefault();
        const name = document.getElementById("custName").value.trim();
        const phone = document.getElementById("custPhone").value.trim();
        const category = document.getElementById("custCategory").value;
        const address = document.getElementById("custAddress").value.trim() || "Đà Nẵng";

        quoteCounter++;
        document.getElementById("quoteCountBadge").textContent = String(quoteCounter);

        const box = document.getElementById("quoteSuccessBox");
        const detail = document.getElementById("quoteSuccessDetail");
        detail.textContent = `Cảm ơn ${name} (SĐT: ${phone} - Khu vực: ${address}). Bộ phận kỹ thuật CÔNG TY TNHH TƯỜNG AN KHANG sẽ liên hệ tư vấn hạng mục "${category}" qua Hotline/Zalo 0905.052.458 - 0905.116.357 ngay!`;
        box.classList.remove("hidden");
        this.reset();
      });
    });
  </script>
</body>
</html>
