<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH XÂY DỰNG CÔNG KING - Thiết Kế & Thi Công Xây Dựng Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TRÁCH NHIỆM HỮU HẠN XÂY DỰNG CÔNG KING (congking.com) chuyên Thiết kế Kiến trúc - Nội thất, Thi công phần thô, Thi công hoàn thiện Nhà phố, Biệt thự, Khách sạn, Căn hộ tại Đà Nẵng. Địa chỉ: 94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0934.771.372">

    <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link congking.com -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://congking.com/">
    <meta property="og:title" content="CÔNG TY TRÁCH NHIỆM HỮU HẠN XÂY DỰNG CÔNG KING | congking.com">
    <meta property="og:description" content="Chuyên Thiết kế & Thi công Xây dựng Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng trọn gói uy tín tại Đà Nẵng. Đ/c: 94 Lê Quang Định, Hòa Xuân, Đà Nẵng - SĐT: 0934.771.372">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1200">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Xây Dựng Công King">

    <!-- Favicon đồng bộ màu Logo -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='16' fill='%230F2942'/%3E%3Cpath d='M20 72 L50 24 L80 72 Z' fill='none' stroke='%23D49B27' stroke-width='7'/%3E%3Cpath d='M32 45 L50 28 L68 45' fill='none' stroke='%23F4C44E' stroke-width='5'/%3E%3Crect x='43' y='50' width='14' height='22' fill='%23D49B27'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        kingNavy: '#0F2942',
                        kingNavyDark: '#091A2B',
                        kingBlue: '#163B5E',
                        kingGold: '#D49B27',
                        kingGoldLight: '#EAB33E',
                        kingGoldBg: '#FDF8EC'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch sang phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn 95% chiều ngang màn hình máy tính, căn giữa chuẩn xác */
        .flatsome-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ tự ngắt chữ trong tên danh mục */
        .nav-menu-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px 6px;
        }
        .nav-item-link {
            white-space: nowrap !important;
            font-size: 12.5px;
            font-weight: 700;
            letter-spacing: 0.01em;
            padding: 7px 9px;
            border-radius: 6px;
            color: #0F2942;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            line-height: 1.2;
        }
        @media (min-width: 1280px) {
            .nav-item-link {
                font-size: 13px;
                padding: 8px 11px;
            }
        }
        .nav-item-link:hover, .nav-item-link.active {
            background-color: #0F2942;
            color: #EAB33E;
        }

        /* Dropdown menu chuẩn Flatsome */
        .has-dropdown {
            position: relative;
        }
        .dropdown-sub {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            border-top: 3px solid #D49B27;
            box-shadow: 0 10px 25px rgba(15, 41, 66, 0.15);
            border-radius: 0 0 8px 8px;
            padding: 6px 0;
            z-index: 100;
        }
        .has-dropdown:hover .dropdown-sub {
            display: block;
        }
        .dropdown-sub a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 600;
            color: #1e293b;
            white-space: nowrap;
            transition: all 0.15s ease;
        }
        .dropdown-sub a:hover {
            background-color: #FDF8EC;
            color: #D49B27;
            padding-left: 18px;
        }

        /* Danh mục lọc ở trang chủ: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng tên danh mục */
        .cat-filter-wrap {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            gap: 6px;
        }
        .cat-tab-btn {
            white-space: nowrap !important;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background: #ffffff;
            color: #0F2942;
            cursor: pointer;
            transition: all 0.2s ease;
            line-height: 1.25;
        }
        .cat-tab-btn:hover,
        .cat-tab-btn.active {
            background: #0F2942;
            color: #EAB33E;
            border-color: #0F2942;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            text-align: center;
        }
        .section-title-normal::before,
        .section-title-normal::after {
            content: "";
            flex: 1;
            max-width: 120px;
            height: 2px;
            background: linear-gradient(90deg, transparent, #D49B27, transparent);
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối, chữ cách xa viền và không bao giờ mất chữ */
        .hero-slider-viewport {
            position: relative;
            width: 100%;
            height: 330px;
            overflow: hidden;
            border-radius: 12px;
            background-color: #0F2942;
        }
        @media (min-width: 640px) {
            .hero-slider-viewport {
                height: 390px;
            }
        }
        @media (min-width: 1024px) {
            .hero-slider-viewport {
                height: 460px;
            }
        }
        .hero-slide-item {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }
        .hero-slide-item.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Tên sản phẩm / công trình: hiển thị đầy đủ, không cắt chữ, không tràn ra ngoài */
        .product-card-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 700;
            color: #0F2942;
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
        }
        @media (min-width: 768px) {
            .product-card-title {
                font-size: 14.5px;
            }
        }

        /* Hiệu ứng mượt cho ảnh sản phẩm Flatsome Box */
        .flatsome-box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .flatsome-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 24px -6px rgba(15, 41, 66, 0.14);
            border-color: #D49B27;
        }
        .flatsome-box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background: #0F2942;
        }
        .flatsome-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }
        .flatsome-box:hover .flatsome-box-image img {
            transform: scale(1.05);
        }

        /* Cụm nút liên hệ nổi bên phải tương thích điện thoại & máy tính */
        .floating-contact-bar {
            position: fixed;
            right: 12px;
            bottom: 18px;
            z-index: 90;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(212, 155, 39, 0.65); }
            70% { box-shadow: 0 0 0 12px rgba(212, 155, 39, 0); }
            100% { box-shadow: 0 0 0 0 rgba(212, 155, 39, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ================= TOP BAR ================= -->
    <div class="bg-kingNavy text-white text-xs py-2 border-b border-kingGold/30">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-3 sm:gap-5">
                <span class="inline-flex items-center gap-1.5 font-medium text-kingGoldLight">
                    <i class="fa-solid fa-building"></i>
                    <span>CÔNG TY TNHH XÂY DỰNG CÔNG KING</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-kingGold"></i>
                    <span>94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-4 ml-auto">
                <a href="tel:0934771372" class="inline-flex items-center gap-1.5 text-kingGoldLight font-semibold hover:underline">
                    <i class="fa-solid fa-phone-volume"></i>
                    <span>0934.771.372</span>
                </a>
                <span class="hidden sm:inline text-slate-400">|</span>
                <a href="https://congking.com" class="hidden sm:inline-flex items-center gap-1 text-slate-200 hover:text-kingGoldLight">
                    <i class="fa-solid fa-globe text-kingGold"></i>
                    <span>congking.com</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ================= HEADER (LOGO GỌN NHỎ & DANH MỤC 1 HÀNG, KHÔNG ĐỂ NÚT GỌI NGAY) ================= -->
    <header id="header" class="bg-white sticky top-0 z-50 shadow-sm border-b border-slate-200">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- Logo Công Ty Chuyên Nghiệp - Chỉnh Gọn Nhỏ Lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" title="Công Ty TNHH Xây Dựng Công King">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-kingNavy flex items-center justify-center border border-kingGold shadow-sm shrink-0">
                    <svg class="w-7 h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Vương miện King & Mái kiến trúc -->
                        <path d="M12 24L22 32L32 16L42 32L52 24L48 44H16L12 24Z" stroke="#EAB33E" stroke-width="3.2" stroke-linejoin="round" fill="#D49B27" fill-opacity="0.2"/>
                        <!-- Tòa nhà xây dựng trung tâm -->
                        <path d="M22 44V28L32 21L42 28V44" stroke="#FFFFFF" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <rect x="29" y="31" width="6" height="13" fill="#EAB33E"/>
                        <line x1="10" y1="49" x2="54" y2="49" stroke="#EAB33E" stroke-width="3" stroke-linecap="round"/>
                    </svg>
                </div>
                <div class="leading-tight">
                    <div class="text-sm sm:text-base font-extrabold tracking-tight text-kingNavy group-hover:text-kingGold transition-colors">
                        CÔNG KING
                    </div>
                    <div class="text-[10px] sm:text-[11px] font-semibold text-kingGold uppercase tracking-wider">
                        Xây Dựng & Nội Thất
                    </div>
                </div>
            </a>

            <!-- Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng tên danh mục -->
            <nav class="hidden lg:block flex-1">
                <ul class="nav-menu-list">
                    <li><a href="#trang-chu" class="nav-item-link active">TRANG CHỦ</a></li>
                    <li><a href="#gioi-thieu" class="nav-item-link">GIỚI THIỆU</a></li>
                    <li class="has-dropdown">
                        <a href="#cong-trinh-thuc-te" class="nav-item-link">
                            <span>CÔNG TRÌNH THỰC TẾ</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="dropdown-sub">
                            <a href="#cong-trinh-thuc-te" onclick="filterRealProjects('khach-san')">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterRealProjects('biet-thu')">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterRealProjects('nha-pho')">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterRealProjects('van-phong')">Văn phòng</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#linh-vuc-hoat-dong" class="nav-item-link">
                            <span>LĨNH VỰC HOẠT ĐỘNG</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="dropdown-sub">
                            <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                            <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                            <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#mau-thiet-ke-bao-gia" class="nav-item-link">
                            <span>MẪU THIẾT KẾ</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="dropdown-sub">
                            <a href="#mau-thiet-ke-bao-gia" onclick="filterCatalog('mau-nha-pho')">Mẫu thiết kế nhà phố</a>
                            <a href="#mau-thiet-ke-bao-gia" onclick="filterCatalog('mau-noi-that')">Mẫu thiết kế nội thất</a>
                        </div>
                    </li>
                    <li><a href="#du-an-da-nang" class="nav-item-link">DỰ ÁN ĐÀ NẴNG</a></li>
                    <li class="has-dropdown">
                        <a href="#mau-thiet-ke-bao-gia" class="nav-item-link">
                            <span>BÁO GIÁ</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="dropdown-sub">
                            <a href="#mau-thiet-ke-bao-gia" onclick="filterCatalog('bao-gia-thiet-ke')">Báo giá thiết kế kiến trúc</a>
                            <a href="#mau-thiet-ke-bao-gia" onclick="filterCatalog('bao-gia-phan-tho')">Báo giá thi công phần thô</a>
                            <a href="#mau-thiet-ke-bao-gia" onclick="filterCatalog('bao-gia-hoan-thien')">Báo giá thi công hoàn thiện</a>
                            <a href="#mau-thiet-ke-bao-gia" onclick="filterCatalog('bao-gia-tron-goi')">Báo giá thi công trọn gói</a>
                        </div>
                    </li>
                    <li><a href="#tin-tuc" class="nav-item-link">TIN TỨC</a></li>
                    <li><a href="#doi-tac" class="nav-item-link">ĐỐI TÁC</a></li>
                    <li><a href="#lien-he-ban-do" class="nav-item-link">LIÊN HỆ</a></li>
                </ul>
            </nav>

            <!-- Nút mở Menu trên Điện thoại (Không có nút Gọi ngay trên Header để tránh tràn viền) -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-kingNavy text-kingGoldLight text-xs font-bold">
                <i id="mobileMenuIcon" class="fa-solid fa-bars text-sm"></i>
                <span>DANH MỤC</span>
            </button>
        </div>

        <!-- Menu Danh Mục Trên Điện Thoại -->
        <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 grid grid-cols-2 sm:grid-cols-3 gap-2">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-kingNavy text-kingGoldLight text-xs font-bold whitespace-nowrap">TRANG CHỦ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">GIỚI THIỆU</a>
                <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">CÔNG TRÌNH THỰC TẾ</a>
                <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">LĨNH VỰC HOẠT ĐỘNG</a>
                <a href="#mau-thiet-ke-bao-gia" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">MẪU THIẾT KẾ</a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">DỰ ÁN ĐÀ NẴNG</a>
                <a href="#mau-thiet-ke-bao-gia" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">BÁO GIÁ XÂY DỰNG</a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">YÊU CẦU TƯ VẤN</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">TIN TỨC</a>
                <a href="#lien-he-ban-do" onclick="toggleMobileMenu()" class="px-3 py-2 rounded-md bg-slate-100 text-kingNavy text-xs font-bold whitespace-nowrap">LIÊN HỆ & BẢN ĐỒ</a>
            </div>
        </div>
    </header>

    <!-- ================= 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
    <!-- Hình ảnh và chữ nằm gọn bên trong banner, cách xa viền, không bị thiếu chữ trên điện thoại & máy tính -->
    <section id="trang-chu" class="py-3 sm:py-4">
        <div class="flatsome-container">
            <div class="hero-slider-viewport shadow-md border border-kingGold/30">

                <!-- SLIDE 1 -->
                <div class="hero-slide-item active" data-slide="0">
                    <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600';"
                         alt="Công Ty TNHH Xây Dựng Công King - Thiết Kế Thi Công Trọn Gói"
                         class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-r from-kingNavyDark/90 via-kingNavy/80 to-kingNavy/55"></div>

                    <!-- Vùng nội dung chữ cách xa viền banner (px-8 sm:px-14 md:px-20 py-7 sm:py-12) -->
                    <div class="absolute inset-0 flex items-center justify-between px-7 sm:px-14 md:px-20 py-6 sm:py-10">
                        <div class="w-full lg:w-7/12 text-white space-y-2 sm:space-y-3.5">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-kingGold/25 border border-kingGold text-kingGoldLight text-[11px] sm:text-xs font-bold">
                                <span>CÔNG TY TNHH XÂY DỰNG CÔNG KING</span>
                            </div>
                            <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                THIẾT KẾ & THI CÔNG XÂY DỰNG <span class="text-kingGoldLight">TRỌN GÓI UY TÍN TẠI ĐÀ NẴNG</span>
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl">
                                Chuyên Thiết kế Kiến trúc – Nội thất, Thi công Phần thô & Hoàn thiện Khách sạn, Biệt thự, Căn hộ, Nhà phố, Văn phòng. Cam kết An Toàn – Chất Lượng – Đúng Tiến Độ.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-2.5 sm:gap-3 text-xs sm:text-sm">
                                <a href="#form-bao-gia" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-kingGold hover:bg-kingGoldLight text-kingNavyDark font-extrabold transition shadow">
                                    NHẬN BÁO GIÁ NGAY
                                </a>
                                <a href="#cong-trinh-thuc-te" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-bold border border-white/30 transition">
                                    XEM CÔNG TRÌNH THỰC TẾ
                                </a>
                            </div>
                        </div>

                        <!-- Khung ảnh thực tế nằm gọn bên trong banner trên màn hình lớn -->
                        <div class="hidden lg:flex w-4/12 justify-end">
                            <div class="w-72 h-56 rounded-xl overflow-hidden border-2 border-kingGold shadow-xl bg-kingNavy">
                                <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1000"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1000';"
                                     alt="Dự án thực tế Công King tại Đà Nẵng"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau 100%) -->
                <div class="hero-slide-item" data-slide="1">
                    <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1600';"
                         alt="Kiến Tạo Không Gian Sống Đẳng Cấp - Xây Dựng Công King"
                         class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-r from-kingNavyDark/90 via-kingNavy/80 to-kingNavy/55"></div>

                    <!-- Vùng nội dung chữ cách xa viền banner (px-8 sm:px-14 md:px-20 py-7 sm:py-12) -->
                    <div class="absolute inset-0 flex items-center justify-between px-7 sm:px-14 md:px-20 py-6 sm:py-10">
                        <div class="w-full lg:w-7/12 text-white space-y-2 sm:space-y-3.5">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-kingGold/25 border border-kingGold text-kingGoldLight text-[11px] sm:text-xs font-bold">
                                <span>NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH</span>
                            </div>
                            <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                GIẢI PHÁP KIẾN TRÚC HIỆN ĐẠI <span class="text-kingGoldLight">& BẢO HÀNH DÀI HẠN</span>
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl">
                                Địa chỉ: 94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng. Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm giám sát chặt chẽ, tối ưu chi phí đầu tư cho Chủ nhà.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-2.5 sm:gap-3 text-xs sm:text-sm">
                                <a href="tel:0934771372" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-kingGold hover:bg-kingGoldLight text-kingNavyDark font-extrabold transition shadow">
                                    HOTLINE: 0934.771.372
                                </a>
                                <a href="#du-an-da-nang" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-bold border border-white/30 transition">
                                    DỰ ÁN TẠI ĐÀ NẴNG
                                </a>
                            </div>
                        </div>

                        <!-- Khung ảnh thực tế nằm gọn bên trong banner trên màn hình lớn -->
                        <div class="hidden lg:flex w-4/12 justify-end">
                            <div class="w-72 h-56 rounded-xl overflow-hidden border-2 border-kingGold shadow-xl bg-kingNavy">
                                <img src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w1000"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000';"
                                     alt="Thi công thực tế Công King"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Banner gọn bên trong -->
                <button onclick="changeHeroSlide(-1)" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-kingNavy/70 hover:bg-kingGold text-white hover:text-kingNavy flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeHeroSlide(1)" aria-label="Banner kế tiếp" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-kingNavy/70 hover:bg-kingGold text-white hover:text-kingNavy flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToHeroSlide(0)" class="hero-dot w-6 h-2 rounded-full bg-kingGold transition-all" aria-label="Slide 1"></button>
                    <button onclick="goToHeroSlide(1)" class="hero-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU (THEO MẪU TINTRUONGTHINH.COM) ================= -->
    <section id="linh-vuc-hoat-dong" class="py-7 sm:py-10 bg-white border-y border-slate-200/80">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>LĨNH VỰC HOẠT ĐỘNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Giải pháp Thiết kế – Thi công – Nội thất đồng bộ tiêu chuẩn kỹ thuật tại Công Ty TNHH Xây Dựng Công King
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800';"
                             alt="Thiết kế Kiến trúc – Nội thất">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title uppercase">Thiết kế Kiến trúc – Nội thất</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Thiết kế phối cảnh 3D, hồ sơ kỹ thuật thi công Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tối ưu công năng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-kingGold hover:text-kingNavy">
                            <span>Nhận tư vấn thiết kế</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800';"
                             alt="Thi công phần thô">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title uppercase">Thi công phần thô</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Thi công nền móng, kết cấu bê tông cốt thép, xây tô tường đúng quy chuẩn kỹ thuật, vật tư chính hãng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-kingGold hover:text-kingNavy">
                            <span>Xem đơn giá phần thô</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800';"
                             alt="Thi công hoàn thiện trọn gói">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title uppercase">Thi công hoàn thiện</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Xây nhà trọn gói chìa khóa trao tay, ốp lát, sơn bả, lắp đặt hệ thống điện nước, cửa nhôm kính đồng bộ.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-kingGold hover:text-kingNavy">
                            <span>Báo giá trọn gói</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800';"
                             alt="Thi công nội thất">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title uppercase">Thi công nội thất</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Sản xuất và lắp đặt nội thất phòng khách, bếp, phòng ngủ, căn hộ cho thuê, khách sạn sang trọng, bền đẹp.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-kingGold hover:text-kingNavy">
                            <span>Tư vấn nội thất</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= GIỚI THIỆU & 6 THẾ MẠNH CỦA CÔNG KING (GIỐNG MẪU TINTRUONGTHINH.COM) ================= -->
    <section id="gioi-thieu" class="py-8 sm:py-11 bg-slate-50">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 sm:p-7 rounded-xl border border-slate-200 shadow-sm">
                <div class="lg:col-span-7 space-y-3">
                    <div class="text-xs font-extrabold uppercase tracking-wider text-kingGold">
                        VỀ CHÚNG TÔI • CONGKING.COM
                    </div>
                    <h2 class="text-lg sm:text-2xl font-extrabold text-kingNavy leading-snug">
                        CÔNG TY TRÁCH NHIỆM HỮU HẠN XÂY DỰNG CÔNG KING
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                        <strong>CÔNG TY TNHH XÂY DỰNG CÔNG KING</strong> chuyên <strong>Thiết kế – Xây dựng – Nội thất</strong> các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Thành phố Đà Nẵng và khu vực miền Trung. Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn mang đến trải nghiệm chuyên nghiệp và sự an tâm tuyệt đối dành cho Quý Khách hàng.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                        Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu để mỗi công trình luôn đạt chuẩn <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-2 text-xs text-kingNavy font-semibold">
                        <div class="flex items-center gap-2 bg-kingGoldBg px-3 py-2 rounded-lg border border-kingGold/30">
                            <i class="fa-solid fa-location-dot text-kingGold"></i>
                            <span>94 Lê Quang Định, Hòa Xuân, Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2 bg-kingGoldBg px-3 py-2 rounded-lg border border-kingGold/30">
                            <i class="fa-solid fa-phone text-kingGold"></i>
                            <span>Hotline tư vấn 24/7: 0934.771.372</span>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <div class="rounded-lg overflow-hidden aspect-[4/3] border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800';"
                             alt="Thi công thực tế Công King 1" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-lg overflow-hidden aspect-[4/3] border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800';"
                             alt="Thi công thực tế Công King 2" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh chuẩn mẫu tintruongthinh.com -->
            <div class="mt-7">
                <div class="section-title-container">
                    <h3 class="section-title-normal text-base sm:text-xl font-extrabold text-kingNavy uppercase">
                        <span>THẾ MẠNH CỦA CHÚNG TÔI</span>
                    </h3>
                </div>
                <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-9 h-9 rounded-lg bg-kingNavy text-kingGoldLight flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-user-tie text-sm"></i>
                        </div>
                        <h4 class="product-card-title">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Đội ngũ kiến trúc sư sáng tạo cùng kỹ sư giàu kinh nghiệm và đội thợ lành nghề trực tiếp thi công tại Đà Nẵng.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-9 h-9 rounded-lg bg-kingNavy text-kingGoldLight flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-compass-drafting text-sm"></i>
                        </div>
                        <h4 class="product-card-title">Cập nhật xu hướng mới nhất hiện đại</h4>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Không ngừng cải tiến, mang đến cho ngôi nhà của bạn xu thế kiến trúc mới, vật liệu và biện pháp thi công hiện đại.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-9 h-9 rounded-lg bg-kingNavy text-kingGoldLight flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-clipboard-check text-sm"></i>
                        </div>
                        <h4 class="product-card-title">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Hoàn thành đúng tiến độ cam kết, thường xuyên báo cáo hình ảnh từng hạng mục thi công để Chủ đầu tư theo dõi.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-9 h-9 rounded-lg bg-kingNavy text-kingGoldLight flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-shield-halved text-sm"></i>
                        </div>
                        <h4 class="product-card-title">Bảo hành công trình lâu dài</h4>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Chế độ hậu mãi tận tâm, bảo hành kết cấu và chống thấm dài hạn để Quý khách hàng hoàn toàn yên tâm sử dụng.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-9 h-9 rounded-lg bg-kingNavy text-kingGoldLight flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-Scale-balanced text-sm"></i>
                        </div>
                        <h4 class="product-card-title">Giá cả hợp lý phải chăng</h4>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Dự toán minh bạch, rõ ràng từng chủng loại vật tư, cân đối chi phí hợp lý nhất đi đôi với chất lượng bền vững.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-9 h-9 rounded-lg bg-kingNavy text-kingGoldLight flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-headset text-sm"></i>
                        </div>
                        <h4 class="product-card-title">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Khảo sát thực tế tại Đà Nẵng, tư vấn phương án thiết kế, xin phép xây dựng và dự toán ngân sách miễn phí 24/7.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= CÔNG TRÌNH THỰC TẾ & HÌNH ẢNH THI CÔNG XÂY DỰNG (9 FILE GOOGLE DRIVE NHÓM 1) ================= -->
    <!-- Không để các nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên sản phẩm không bị tràn hay thiếu chữ -->
    <section id="cong-trinh-thuc-te" class="py-8 sm:py-11 bg-white">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>CÔNG TRÌNH THỰC TẾ & THI CÔNG XÂY DỰNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Hình ảnh thực tế thi công xây dựng phần thô, hoàn thiện Nhà phố, Biệt thự, Khách sạn – Căn hộ của Công King
                </p>
            </div>

            <!-- Danh mục lọc chữ nhỏ gọn, viết liền 1 hàng từng mục, không xuống dòng tên danh mục -->
            <div class="cat-filter-wrap mb-6" id="realProjectTabs">
                <button onclick="filterRealProjects('all')" data-filter="all" class="cat-tab-btn active">Tất cả</button>
                <button onclick="filterRealProjects('khach-san')" data-filter="khach-san" class="cat-tab-btn">Khách sạn – Căn hộ – Phòng trọ</button>
                <button onclick="filterRealProjects('biet-thu')" data-filter="biet-thu" class="cat-tab-btn">Biệt thự</button>
                <button onclick="filterRealProjects('nha-pho')" data-filter="nha-pho" class="cat-tab-btn">Nhà phố</button>
                <button onclick="filterRealProjects('van-phong')" data-filter="van-phong" class="cat-tab-btn">Văn phòng</button>
            </div>

            <!-- Grid: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) -->
            <div id="realProjectsGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">

                <!-- Ảnh thực tế 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                <div class="flatsome-box real-project-card" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000';"
                             alt="Thi công phần thô và hoàn thiện Nhà phố Anh Bình – Hòa Xuân">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công phần thô & hoàn thiện Nhà phố Anh Bình – Hòa Xuân</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Nhà phố</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                <div class="flatsome-box real-project-card" data-category="khach-san">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000';"
                             alt="Thi công kết cấu Khách sạn Bắc Nam & Căn hộ cho thuê">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công kết cấu Khách sạn Bắc Nam & Căn hộ cho thuê</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                <div class="flatsome-box real-project-card" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000';"
                             alt="Thi công xây dựng Nhà phố Chị Ly – Nguyễn Chánh">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công xây dựng Nhà phố Chị Ly – Nguyễn Chánh</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Nhà phố</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                <div class="flatsome-box real-project-card" data-category="khach-san">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000';"
                             alt="Thi công Căn hộ Hồ Biểu Chánh – Khu căn hộ cao cấp">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công Căn hộ Hồ Biểu Chánh – Khu căn hộ cao cấp</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                <div class="flatsome-box real-project-card" data-category="biet-thu">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000';"
                             alt="Thi công Biệt thự 2 mặt tiền hiện đại tại Đà Nẵng">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công Biệt thự 2 mặt tiền hiện đại tại Đà Nẵng</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Biệt thự</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                <div class="flatsome-box real-project-card" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1000';"
                             alt="Thi công trọn gói Nhà phố Anh Quang – Tiểu La">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công trọn gói Nhà phố Anh Quang – Tiểu La</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Nhà phố</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                <div class="flatsome-box real-project-card" data-category="khach-san">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w1000';"
                             alt="Thi công Căn hộ Anh Thư & Tổ hợp căn hộ cho thuê">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công Căn hộ Anh Thư & Tổ hợp căn hộ cho thuê</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                <div class="flatsome-box real-project-card" data-category="biet-thu">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w1000';"
                             alt="Thi công Biệt thự nghỉ dưỡng & Khách sạn Nesta">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thi công Biệt thự nghỉ dưỡng & Khách sạn Nesta</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Biệt thự</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh thực tế 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                <div class="flatsome-box real-project-card" data-category="van-phong">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w1000"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w1000';"
                             alt="Thiết kế & Thi công Tòa nhà Văn phòng Thành Vinh Holding">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thiết kế & Thi công Tòa nhà Văn phòng Thành Vinh Holding</h3>
                            <p class="text-xs text-slate-500 mt-1">Danh mục: Văn phòng</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy inline-flex items-center gap-1">
                            <span>Xem chi tiết & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 FILE GOOGLE DRIVE NHÓM 2) ================= -->
    <!-- Chia 2 cột trên giao diện điện thoại, 5 cột trên máy tính, không nhãn dán, không mất chữ -->
    <section id="du-an-da-nang" class="py-8 sm:py-11 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Tổng hợp các dự án Thiết kế & Thi công thực tế tại Hòa Xuân, Nam Việt Á, Cẩm Lệ, Hải Châu, Sơn Trà – TP Đà Nẵng
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính (lg:grid-cols-5) -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">

                <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800';"
                             alt="Dự án Nhà phố Khu đô thị sinh thái Hòa Xuân – Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Nhà phố Khu đô thị sinh thái Hòa Xuân – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Phường Hòa Xuân, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800';"
                             alt="Dự án Nhà phố Anh Tuấn – Khu đô thị Nam Việt Á, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Nhà phố Anh Tuấn – Khu đô thị Nam Việt Á, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Khu Nam Việt Á, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800';"
                             alt="Dự án Kyo Apartment – Căn hộ cao cấp View sông Hàn Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Kyo Apartment – Căn hộ cao cấp View sông Hàn Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Quận Sơn Trà, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800';"
                             alt="Dự án Nhà phố Anh Phong – Khu đô thị Phước Lý, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Nhà phố Anh Phong – Khu đô thị Phước Lý, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Khu Phước Lý, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800';"
                             alt="Dự án Nhà phố Anh Hùng – Khu dân cư Bình Kỳ, Hòa Quý, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Nhà phố Anh Hùng – Khu dân cư Bình Kỳ, Hòa Quý, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Ngũ Hành Sơn, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800';"
                             alt="Dự án Nhà phố Anh Lộc – Khu dân cư Bầu Cầu, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Nhà phố Anh Lộc – Khu dân cư Bầu Cầu, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Hòa Xuân – Cẩm Lệ, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800';"
                             alt="Dự án Biệt thự phố Lê Quang Định – Phường Hòa Xuân, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Biệt thự phố Lê Quang Định – Phường Hòa Xuân, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Phường Hòa Xuân, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800';"
                             alt="Dự án Tổ hợp Căn hộ & Văn phòng Husble tại Hải Châu, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Tổ hợp Căn hộ & Văn phòng Husble tại Hải Châu, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Quận Hải Châu, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800';"
                             alt="Dự án Nhà phố hiện đại 3 tầng Nguyễn Chánh – Liên Chiểu, Đà Nẵng">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Nhà phố hiện đại 3 tầng Nguyễn Chánh – Liên Chiểu, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Quận Liên Chiểu, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800';"
                             alt="Dự án Homestay & Biệt thự nghỉ dưỡng Cánh Đồng Sưa Retreat">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-card-title">Dự án Homestay & Biệt thự nghỉ dưỡng Cánh Đồng Sưa Retreat</h3>
                        <p class="text-[11px] text-slate-500 mt-1.5">Khu vực Đà Nẵng – Quảng Nam</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC MẪU THIẾT KẾ & BÁO GIÁ (LẤY TỪ WEB MẪU TINTRUONGTHINH.COM) ================= -->
    <section id="mau-thiet-ke-bao-gia" class="py-8 sm:py-11 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>MẪU THIẾT KẾ & BẢNG BÁO GIÁ XÂY DỰNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Danh mục sản phẩm thiết kế và gói báo giá xây dựng chuẩn theo hệ thống Công Ty TNHH Xây Dựng Công King
                </p>
            </div>

            <!-- Thanh lọc danh mục viết liền trên 1 hàng chữ nhỏ gọn -->
            <div class="cat-filter-wrap mb-6" id="catalogTabs">
                <button onclick="filterCatalog('all')" data-cat="all" class="cat-tab-btn active">Tất cả</button>
                <button onclick="filterCatalog('mau-nha-pho')" data-cat="mau-nha-pho" class="cat-tab-btn">Mẫu thiết kế nhà phố</button>
                <button onclick="filterCatalog('mau-noi-that')" data-cat="mau-noi-that" class="cat-tab-btn">Mẫu thiết kế nội thất</button>
                <button onclick="filterCatalog('bao-gia-thiet-ke')" data-cat="bao-gia-thiet-ke" class="cat-tab-btn">Báo giá thiết kế kiến trúc</button>
                <button onclick="filterCatalog('bao-gia-phan-tho')" data-cat="bao-gia-phan-tho" class="cat-tab-btn">Báo giá thi công phần thô</button>
                <button onclick="filterCatalog('bao-gia-hoan-thien')" data-cat="bao-gia-hoan-thien" class="cat-tab-btn">Báo giá thi công hoàn thiện</button>
                <button onclick="filterCatalog('bao-gia-tron-goi')" data-cat="bao-gia-tron-goi" class="cat-tab-btn">Báo giá thi công trọn gói</button>
            </div>

            <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <div id="catalogGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">

                <div class="flatsome-box catalog-item" data-cat="mau-nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800';"
                             alt="Mẫu thiết kế nhà phố hiện đại 3 tầng mặt tiền 5m">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Mẫu thiết kế nhà phố hiện đại 3 tầng mặt tiền 5m</h3>
                            <p class="text-xs text-slate-600 mt-1">Danh mục: Mẫu thiết kế nhà phố</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Nhận hồ sơ mẫu →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="mau-nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800';"
                             alt="Mẫu thiết kế nhà phố kết hợp kinh doanh & căn hộ tại Đà Nẵng">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Mẫu thiết kế nhà phố kết hợp kinh doanh & căn hộ tại Đà Nẵng</h3>
                            <p class="text-xs text-slate-600 mt-1">Danh mục: Mẫu thiết kế nhà phố</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Nhận hồ sơ mẫu →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="mau-noi-that">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800';"
                             alt="Mẫu thiết kế nội thất phòng khách & bếp gỗ hiện đại">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Mẫu thiết kế nội thất phòng khách & bếp gỗ hiện đại</h3>
                            <p class="text-xs text-slate-600 mt-1">Danh mục: Mẫu thiết kế nội thất</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Nhận hồ sơ mẫu →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="mau-noi-that">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800';"
                             alt="Mẫu thiết kế nội thất Căn hộ cho thuê & Khách sạn">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Mẫu thiết kế nội thất Căn hộ cho thuê & Khách sạn</h3>
                            <p class="text-xs text-slate-600 mt-1">Danh mục: Mẫu thiết kế nội thất</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Nhận hồ sơ mẫu →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="bao-gia-thiet-ke">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800';"
                             alt="Báo giá thiết kế kiến trúc & nội thất trọn gói">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Báo giá thiết kế kiến trúc & hồ sơ kỹ thuật thi công</h3>
                            <p class="text-xs font-bold text-kingGold mt-1">Từ 120.000đ – 180.000đ/m²</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingNavy hover:text-kingGold">Yêu cầu báo giá chi tiết →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="bao-gia-phan-tho">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800';"
                             alt="Báo giá thi công phần thô và nhân công hoàn thiện">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Báo giá thi công phần thô & nhân công hoàn thiện</h3>
                            <p class="text-xs font-bold text-kingGold mt-1">Từ 3.600.000đ – 3.950.000đ/m²</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingNavy hover:text-kingGold">Yêu cầu báo giá chi tiết →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="bao-gia-hoan-thien">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800';"
                             alt="Báo giá thi công hoàn thiện công trình">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Báo giá thi công hoàn thiện vật tư chuẩn chính hãng</h3>
                            <p class="text-xs font-bold text-kingGold mt-1">Từ 2.400.000đ – 3.200.000đ/m²</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingNavy hover:text-kingGold">Yêu cầu báo giá chi tiết →</a>
                    </div>
                </div>

                <div class="flatsome-box catalog-item" data-cat="bao-gia-tron-goi">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800';"
                             alt="Báo giá thi công trọn gói chìa khóa trao tay">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Báo giá thi công trọn gói – Chìa khóa trao tay tại Đà Nẵng</h3>
                            <p class="text-xs font-bold text-kingGold mt-1">Từ 5.800.000đ – 7.200.000đ/m²</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingNavy hover:text-kingGold">Yêu cầu báo giá chi tiết →</a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (GIỐNG WEB MẪU TINTRUONGTHINH.COM) ================= -->
    <section id="form-bao-gia" class="py-8 sm:py-12 bg-kingNavy text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-5 space-y-3">
                    <div class="text-xs font-bold uppercase tracking-wider text-kingGoldLight">
                        ĐĂNG KÝ TƯ VẤN & DỰ TOÁN CHI PHÍ
                    </div>
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug">
                        MIỄN PHÍ TƯ VẤN & BÁO GIÁ XÂY DỰNG TRỌN GÓI
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                        Quý khách vui lòng để lại thông tin nhu cầu xây dựng. Đội ngũ Kỹ sư & Kiến trúc sư <strong>CÔNG TY TNHH XÂY DỰNG CÔNG KING</strong> sẽ liên hệ tư vấn phương án mặt bằng và gửi bảng báo giá chi tiết ngay trong ngày.
                    </p>
                    <div class="space-y-2 pt-2 text-xs sm:text-sm">
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-check-circle text-kingGoldLight"></i>
                            <span>Khảo sát hiện trạng và tư vấn thiết kế miễn phí 100%</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-check-circle text-kingGoldLight"></i>
                            <span>Hỗ trợ thủ tục xin giấy phép xây dựng tại Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-check-circle text-kingGoldLight"></i>
                            <span>Cam kết không phát sinh chi phí ngoài hợp đồng</span>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form id="quoteRequestForm" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 p-4 sm:p-6 rounded-xl shadow-lg border-2 border-kingGold">
                        <h3 class="text-base sm:text-lg font-extrabold text-kingNavy mb-4 uppercase text-center">
                            FORM YÊU CẦU TƯ VẤN & BÁO GIÁ
                        </h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-kingNavy mb-1">Họ và tên *</label>
                                <input type="text" id="qName" required placeholder="Nhập họ và tên của bạn" class="w-full px-3 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-kingGold">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-kingNavy mb-1">Số điện thoại *</label>
                                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0934.771.372" class="w-full px-3 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-kingGold">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-kingNavy mb-1">Loại công trình</label>
                                <select id="qType" class="w-full px-3 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-kingGold bg-white">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-kingNavy mb-1">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-kingGold bg-white">
                                    <option value="1 - 2 tỷ">1 - 2 tỷ</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                    <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div class="sm:col-span-2">
                                <label class="block text-xs font-bold text-kingNavy mb-1">Địa điểm xây dựng & Yêu cầu chi tiết</label>
                                <textarea id="qNote" rows="2" placeholder="Nhập diện tích đất, số tầng dự kiến, khu vực xây dựng tại Đà Nẵng..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-kingGold"></textarea>
                            </div>
                        </div>
                        <button type="submit" class="mt-4 w-full py-3 rounded-lg bg-kingGold hover:bg-kingGoldLight text-kingNavyDark font-extrabold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                            GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC XÂY DỰNG) ================= -->
    <section id="tin-tuc" class="py-8 sm:py-11 bg-white">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>TIN TỨC & KINH NGHIỆM XÂY DỰNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Cập nhật kiến thức thi công phần thô, bảo dưỡng bê tông và xu hướng kiến trúc nội thất mới nhất
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800';"
                             alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Hướng dẫn bảo dưỡng bê tông móng đúng cách đạt chuẩn kỹ thuật</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Trong quá trình xây dựng công trình, bê tông móng đóng vai trò quyết định đến độ bền vững của toàn bộ ngôi nhà...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Đọc tiếp →</a>
                    </div>
                </article>

                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800';"
                             alt="Thiết kế nội thất là gì? Khái niệm và Tầm quan trọng">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Thiết kế nội thất là gì? Khái niệm và tầm quan trọng với tổ ấm</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Thiết kế nội thất không chỉ là việc bố trí đồ đạc mà còn là nghệ thuật tổ chức không gian sống tiện nghi, hài hòa...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Đọc tiếp →</a>
                    </div>
                </article>

                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800';"
                             alt="03 Nỗi lo lớn nhất khi xây nhà mà 100% Chủ đầu tư đều gặp phải">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">03 Nỗi lo lớn nhất khi xây nhà mà 100% Chủ đầu tư đều gặp phải</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Kiểm soát chi phí phát sinh, lựa chọn nhà thầu uy tín tại Đà Nẵng và giám sát chất lượng vật tư phần thô...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Đọc tiếp →</a>
                    </div>
                </article>

                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800';"
                             alt="Tâm lý học không gian: Nội thất tác động đến hành vi như thế nào">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-card-title">Tâm lý học không gian: Nội thất tác động đến hành vi như thế nào?</h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Ánh sáng tự nhiên, thông gió và tỷ lệ kiến trúc giúp nâng cao năng lượng tích cực cho mọi thành viên...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-2.5 text-xs font-bold text-kingGold hover:text-kingNavy">Đọc tiếp →</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC ĐỐI TÁC ================= -->
    <section id="doi-tac" class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Công Ty TNHH Xây Dựng Công King cam kết sử dụng vật tư chính hãng từ các thương hiệu hàng đầu
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <div class="text-sm font-extrabold text-kingNavy">THÉP HÒA PHÁT</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng kết cấu</div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <div class="text-sm font-extrabold text-kingNavy">SƠN DULUX & JOTUN</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Sơn ngoại & nội thất</div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <div class="text-sm font-extrabold text-kingNavy">GẠCH VIGLACERA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát cao cấp</div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <div class="text-sm font-extrabold text-kingNavy">THIẾT BỊ TOTO / INAX</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh chính hãng</div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <div class="text-sm font-extrabold text-kingNavy">NHÔM XINGFA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính cao cấp</div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <div class="text-sm font-extrabold text-kingNavy">GỖ AN CƯỜNG</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất chuẩn</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ ================= -->
    <section id="lien-he-ban-do" class="py-8 sm:py-11 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-normal text-base sm:text-xl md:text-2xl font-extrabold text-kingNavy uppercase">
                    <span>FANPAGE & BẢN ĐỒ TRỤ SỞ CÔNG TY CÔNG KING</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Địa chỉ: 94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng • Điện thoại: 0934.771.372
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                <!-- Fanpage ngoài trang chủ -->
                <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-200 pb-3 mb-3">
                            <span class="text-xs sm:text-sm font-extrabold text-kingNavy uppercase flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-base"></i>
                                <span>FANPAGE FACEBOOK CHÍNH THỨC</span>
                            </span>
                            <span class="text-[11px] font-semibold text-emerald-700 bg-emerald-50 px-2 py-0.5 rounded">Đang hoạt động</span>
                        </div>

                        <!-- Khung giao diện Fanpage trực quan trên trang chủ -->
                        <div class="rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm">
                            <div class="relative h-36 bg-kingNavy">
                                <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1000"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000';"
                                     alt="Fanpage Công Ty TNHH Xây Dựng Công King"
                                     class="w-full h-full object-cover opacity-65">
                                <div class="absolute inset-0 bg-gradient-to-t from-kingNavyDark/90 via-kingNavy/40 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-kingNavy border-2 border-kingGold flex items-center justify-center shrink-0">
                                        <span class="text-kingGoldLight font-extrabold text-sm">CK</span>
                                    </div>
                                    <div class="text-white">
                                        <div class="text-xs sm:text-sm font-extrabold leading-tight">CÔNG TY TNHH XÂY DỰNG CÔNG KING</div>
                                        <div class="text-[11px] text-slate-200">Thiết kế & Thi công Xây dựng trọn gói Đà Nẵng</div>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3.5 space-y-2.5 text-xs text-slate-700">
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-location-dot text-kingGold w-4 text-center"></i>
                                    <span>94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-phone text-kingGold w-4 text-center"></i>
                                    <span>Hotline/Zalo: <strong class="text-kingNavy">0934.771.372</strong></span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-globe text-kingGold w-4 text-center"></i>
                                    <span>Website: <strong class="text-kingNavy">congking.com</strong></span>
                                </div>
                                <div class="pt-2 flex flex-wrap gap-2">
                                    <a href="https://www.facebook.com" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs transition">
                                        <i class="fa-brands fa-facebook-f mr-1"></i> Theo dõi Fanpage
                                    </a>
                                    <a href="https://zalo.me/0934771372" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded-lg bg-kingGold hover:bg-kingGoldLight text-kingNavyDark font-bold text-xs transition">
                                        <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn tin Zalo
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 text-[11px] text-slate-500">
                        Cập nhật hình ảnh thi công thực tế hằng ngày tại các công trình Đà Nẵng.
                    </div>
                </div>

                <!-- Bản đồ Google Map ngoài trang chủ -->
                <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-200 pb-3 mb-3">
                        <span class="text-xs sm:text-sm font-extrabold text-kingNavy uppercase flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-kingGold text-base"></i>
                            <span>BẢN ĐỒ GOOGLE MAPS: 94 LÊ QUANG ĐỊNH, HÒA XUÂN, ĐÀ NẴNG</span>
                        </span>
                        <a href="https://www.google.com/maps/search/?api=1&query=94+L%C3%AA+Quang+%C4%90%E1%BB%8Bnh,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="text-xs font-bold text-kingGold hover:underline">
                            Mở Google Maps lớn →
                        </a>
                    </div>

                    <div class="w-full h-72 sm:h-80 rounded-xl overflow-hidden border border-slate-300 bg-slate-200">
                        <iframe
                            title="Bản đồ Công Ty TNHH Xây Dựng Công King - 94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng"
                            src="https://www.google.com/maps?q=94+L%C3%AA+Quang+%C4%90%E1%BB%8Bnh,+Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER (CHÂN TRANG CHUẨN MẪU TINTRUONGTHINH.COM) ================= -->
    <footer class="bg-kingNavyDark text-slate-200 pt-10 pb-6 border-t-4 border-kingGold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-slate-700/80">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <div class="w-10 h-10 rounded-lg bg-kingNavy flex items-center justify-center border border-kingGold shrink-0">
                            <span class="text-kingGoldLight font-extrabold text-sm">CK</span>
                        </div>
                        <div>
                            <div class="text-sm sm:text-base font-extrabold text-white">
                                CÔNG TY TRÁCH NHIỆM HỮU HẠN XÂY DỰNG CÔNG KING
                            </div>
                            <div class="text-xs text-kingGoldLight font-semibold">Website: congking.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-kingGold mt-1"></i>
                            <span><strong>Địa chỉ:</strong> 94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-kingGold"></i>
                            <span><strong>Hotline:</strong> <a href="tel:0934771372" class="text-kingGoldLight font-bold hover:underline">0934.771.372</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-kingGold"></i>
                            <span><strong>Website:</strong> <a href="https://congking.com" class="hover:text-kingGoldLight">https://congking.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-id-card text-kingGold"></i>
                            <span><strong>Mã số thuế:</strong> 0402039462</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h3 class="text-sm font-extrabold text-kingGoldLight uppercase tracking-wider">
                        Lĩnh vực hoạt động
                    </h3>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-kingGoldLight">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-kingGoldLight">• Thi công phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-kingGoldLight">• Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-kingGoldLight">• Thi công nội thất</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-kingGoldLight">• Các dự án xây dựng tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Công trình & Báo giá -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h3 class="text-sm font-extrabold text-kingGoldLight uppercase tracking-wider">
                        Danh mục sản phẩm & Báo giá
                    </h3>
                    <div class="grid grid-cols-2 gap-2 text-xs sm:text-sm text-slate-300">
                        <a href="#cong-trinh-thuc-te" class="hover:text-kingGoldLight">• Khách sạn – Căn hộ</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-kingGoldLight">• Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-kingGoldLight">• Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-kingGoldLight">• Văn phòng</a>
                        <a href="#mau-thiet-ke-bao-gia" class="hover:text-kingGoldLight">• Báo giá thiết kế</a>
                        <a href="#mau-thiet-ke-bao-gia" class="hover:text-kingGoldLight">• Báo giá phần thô</a>
                        <a href="#mau-thiet-ke-bao-gia" class="hover:text-kingGoldLight">• Báo giá hoàn thiện</a>
                        <a href="#mau-thiet-ke-bao-gia" class="hover:text-kingGoldLight">• Báo giá trọn gói</a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright © 2026 <strong>CÔNG TY TRÁCH NHIỆM HỮU HẠN XÂY DỰNG CÔNG KING (congking.com)</strong>. All rights reserved.</div>
                <div>Địa chỉ: 94 Lê Quang Định, Phường Hòa Xuân, TP Đà Nẵng | SĐT: 0934.771.372</div>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH ĐIỆN THOẠI & MÁY TÍNH ================= -->
    <div class="floating-contact-bar" aria-label="Liên hệ nhanh Công King">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0934771372" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2.5 rounded-full shadow-lg transition transform hover:scale-105"
           title="Chat Zalo: 0934.771.372">
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 font-extrabold text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage -->
        <a href="#lien-he-ban-do"
           class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2.5 rounded-full shadow-lg transition transform hover:scale-105"
           title="Fanpage Facebook Công King">
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0934771372"
           class="pulse-btn flex items-center gap-2 bg-kingGold hover:bg-kingGoldLight text-kingNavyDark px-3.5 py-2.5 rounded-full shadow-xl transition transform hover:scale-105 border border-white"
           title="Gọi ngay 0934.771.372">
            <span class="w-7 h-7 rounded-full bg-kingNavy text-kingGoldLight flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1 whitespace-nowrap">0934.771.372</span>
        </a>
    </div>

    <!-- ================= HỘP THOẠI THÔNG BÁO GỬI FORM THÀNH CÔNG (THAY THẾ ALERT) ================= -->
    <div id="customModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-kingNavyDark/75 p-4">
        <div class="bg-white rounded-xl max-w-md w-full p-6 text-center shadow-2xl border-2 border-kingGold">
            <div class="w-12 h-12 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center mx-auto mb-3">
                <i class="fa-solid fa-check text-xl"></i>
            </div>
            <h4 class="text-base sm:text-lg font-extrabold text-kingNavy">ĐÃ GỬI YÊU CẦU BÁO GIÁ THÀNH CÔNG!</h4>
            <p id="modalMessageText" class="text-xs sm:text-sm text-slate-600 mt-2 leading-relaxed"></p>
            <button onclick="closeCustomModal()" class="mt-4 px-6 py-2.5 rounded-lg bg-kingNavy text-kingGoldLight text-xs font-bold uppercase hover:bg-kingBlue transition">
                Đóng thông báo
            </button>
        </div>
    </div>

    <!-- ================= JAVASCRIPT ĐIỀU KHIỂN SLIDER, LỌC DANH MỤC & FORM ================= -->
    <script>
        // 1. Đóng/mở menu trên điện thoại
        function toggleMobileMenu() {
            const panel = document.getElementById('mobileMenuPanel');
            const icon = document.getElementById('mobileMenuIcon');
            if (panel.classList.contains('hidden')) {
                panel.classList.remove('hidden');
                icon.classList.remove('fa-bars');
                icon.classList.add('fa-xmark');
            } else {
                panel.classList.add('hidden');
                icon.classList.remove('fa-xmark');
                icon.classList.add('fa-bars');
            }
        }

        // 2. Tự động trượt 2 Banner chuyên nghiệp kích thước bằng nhau
        let currentHeroSlide = 0;
        const heroSlides = document.querySelectorAll('.hero-slide-item');
        const heroDots = document.querySelectorAll('.hero-dot');
        let heroSlideInterval = null;

        function renderHeroSlide(index) {
            if (!heroSlides.length) return;
            currentHeroSlide = (index + heroSlides.length) % heroSlides.length;
            heroSlides.forEach((slide, idx) => {
                if (idx === currentHeroSlide) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            heroDots.forEach((dot, idx) => {
                if (idx === currentHeroSlide) {
                    dot.className = 'hero-dot w-6 h-2 rounded-full bg-kingGold transition-all';
                } else {
                    dot.className = 'hero-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function changeHeroSlide(step) {
            renderHeroSlide(currentHeroSlide + step);
            restartHeroAutoSlide();
        }

        function goToHeroSlide(index) {
            renderHeroSlide(index);
            restartHeroAutoSlide();
        }

        function restartHeroAutoSlide() {
            if (heroSlideInterval) clearInterval(heroSlideInterval);
            heroSlideInterval = setInterval(() => {
                renderHeroSlide(currentHeroSlide + 1);
            }, 5000);
        }

        // 3. Lọc Công trình thực tế (9 ảnh Google Drive nhóm 1)
        function filterRealProjects(category) {
            const cards = document.querySelectorAll('.real-project-card');
            const buttons = document.querySelectorAll('#realProjectTabs .cat-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-filter') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            cards.forEach(card => {
                const itemCat = card.getAttribute('data-category');
                if (category === 'all' || itemCat === category) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
        }

        // 4. Lọc Danh mục Mẫu thiết kế & Báo giá
        function filterCatalog(catKey) {
            const items = document.querySelectorAll('.catalog-item');
            const buttons = document.querySelectorAll('#catalogTabs .cat-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === catKey) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            items.forEach(item => {
                const key = item.getAttribute('data-cat');
                if (catKey === 'all' || key === catKey) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 5. Xử lý gửi Form Yêu cầu tư vấn & Báo giá
        function handleQuoteSubmit(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const type = document.getElementById('qType').value;
            const budget = document.getElementById('qBudget').value;

            const msg = `Cảm ơn Quý khách ${name} (${phone}). Yêu cầu báo giá hạng mục "${type}" với mức đầu tư "${budget}" đã được gửi đến CÔNG TY TNHH XÂY DỰNG CÔNG KING. Kỹ sư của chúng tôi sẽ liên hệ lại qua số 0934.771.372 trong thời gian sớm nhất!`;
            document.getElementById('modalMessageText').textContent = msg;
            const modal = document.getElementById('customModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.getElementById('quoteRequestForm').reset();
        }

        function closeCustomModal() {
            const modal = document.getElementById('customModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        window.onload = function () {
            restartHeroAutoSlide();
        };
    </script>
</body>
</html>
