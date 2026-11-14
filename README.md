<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Nội Thất Phương Anh Đà Nẵng - Thiết Kế & Thi Công Nội Thất Trọn GóI | noithatphuonganh.com</title>
    <meta name="description" content="Nội Thất Phương Anh (noithatphuonganh.com) chuyên thiết kế, sản xuất và thi công tủ bếp gỗ, tủ thờ, cửa gỗ, cầu thang, sàn gỗ, nhựa giả đá, phòng khách, phòng ngủ uy tín tại Lưu Quang Vũ - Hoà Quý - Đà Nẵng. Hotline: 0905.80.1976.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Nội Thất Phương Anh - noithatphuonganh.com">
    <meta property="og:url" content="https://noithatphuonganh.com/">
    <meta property="og:title" content="Nội Thất Phương Anh Đà Nẵng - Xưởng Thiết Kế & Thi Công Nội Thất Giá Xưởng">
    <meta property="og:description" content="Chuyên thi công tủ bếp, tủ thờ, cửa gỗ, cầu thang, giường tủ, nhựa giả đá tại Lưu Quang Vũ - Hoà Quý - Đà Nẵng. Hotline: 0905.80.1976">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/12emKoKiVivjuzhQPkG1oInB00n3fpMZX">
    <meta property="og:image:alt" content="Logo Nội Thất Phương Anh Đà Nẵng">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nội Thất Phương Anh Đà Nẵng | noithatphuonganh.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/12emKoKiVivjuzhQPkG1oInB00n3fpMZX">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/12emKoKiVivjuzhQPkG1oInB00n3fpMZX">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#fdfaf6',
                            100: '#f7efe4',
                            200: '#eedbc2',
                            500: '#a66829',
                            600: '#8b521c',
                            700: '#6e3f14',
                            800: '#4e2c0e',
                            900: '#2d1908',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Khắc phục triệt để tràn viền ngang hoặc lệch phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8f6f3;
            color: #262626;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
        .ux-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .ux-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng của mỗi tên danh mục, không bị gãy dòng */
        .cat-nav-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            transition: all 0.2s ease;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Đơn giản, dễ làm lại trên Flatsome) */
        .ux-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #8b521c;
            margin-bottom: 16px;
            background: #ffffff;
            border-radius: 6px 6px 0 0;
        }
        .ux-section-title h2 {
            background-color: #8b521c;
            color: #ffffff;
            font-size: 14px;
            font-weight: 700;
            text-transform: uppercase;
            padding: 9px 16px;
            margin: 0;
            border-radius: 6px 6px 0 0;
            letter-spacing: 0.3px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        @media (min-width: 768px) {
            .ux-section-title h2 {
                font-size: 15px;
                padding: 10px 20px;
            }
        }

        /* Thẻ sản phẩm Flatsome đơn giản, tên sản phẩm hiển thị đầy đủ không bị cắt chữ */
        .ux-product-card {
            background: #ffffff;
            border: 1px solid #e7e2da;
            border-radius: 8px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            height: 100%;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }
        .ux-product-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(78, 44, 14, 0.1);
            border-color: #a66829;
        }
        .ux-product-title {
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            line-height: 1.4;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(139, 82, 28, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(139, 82, 28, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(139, 82, 28, 0); }
        }
        .float-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- =======================================================================
         TOP BAR: ĐỊA CHỈ & THÔNG TIN WEBSITE (ĐƠN GIẢN CHUẨN FLATSOME)
    ======================================================================== -->
    <div class="bg-brand-900 text-brand-100 text-xs py-2 border-b border-brand-800">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span><i class="fa-solid fa-globe text-amber-400 mr-1.5"></i><strong>noithatphuonganh.com</strong> - Xưởng Thiết Kế & Thi Công Nội Thất Trọn Gói Đà Nẵng</span>
                <span class="hidden sm:inline text-brand-200">|</span>
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i>Địa chỉ: Lưu Quang Vũ - Hoà Quý - Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-4">
                <span><i class="fa-solid fa-clock text-amber-400 mr-1"></i>7:30 - 18:00 (T2 - CN)</span>
                <a href="https://www.facebook.com/profile.php?id=100078411751009" target="_blank" rel="noopener" class="hover:text-amber-300 font-medium">
                    <i class="fa-brands fa-facebook mr-1"></i>Fanpage Nội Thất Phương Anh
                </a>
            </div>
        </div>
    </div>

    <!-- =======================================================================
         HEADER CHÍNH: LOGO GỌN NHỎ + TÌM KIẾM + MENU (KHÔNG ĐỂ NÚT GỌI NGAY)
    ======================================================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-stone-200">
        <div class="ux-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                <img 
                    src="https://lh3.googleusercontent.com/d/12emKoKiVivjuzhQPkG1oInB00n3fpMZX" 
                    onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=12emKoKiVivjuzhQPkG1oInB00n3fpMZX&sz=w400';"
                    alt="Logo Nội Thất Phương Anh" 
                    class="h-9 sm:h-11 w-auto object-contain rounded border border-stone-200 p-0.5 bg-white"
                >
                <div class="leading-tight">
                    <span class="block text-sm sm:text-base font-extrabold text-brand-700 tracking-tight uppercase">NỘI THẤT PHƯƠNG ANH</span>
                    <span class="block text-[11px] text-stone-500 font-medium">noithatphuonganh.com</span>
                </div>
            </a>

            <!-- Ô tìm kiếm sản phẩm ở giữa (Máy tính) -->
            <div class="hidden md:flex flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input 
                        type="text" 
                        id="searchInput"
                        oninput="filterProductsBySearch(this.value)"
                        placeholder="Tìm tủ bếp, tủ thờ, cầu thang gỗ, cửa gỗ, sàn gỗ..." 
                        class="w-full pl-3.5 pr-10 py-1.5 text-xs bg-stone-50 border border-stone-300 rounded-md focus:outline-none focus:border-brand-600"
                    >
                    <button type="button" aria-label="Tìm kiếm" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-brand-600">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>

            <!-- Menu Điều Hướng Chính (Không có nút Gọi Ngay trên Header để tránh tràn viền) -->
            <nav class="hidden lg:flex items-center gap-5 text-xs font-bold uppercase text-stone-700 shrink-0">
                <a href="#trang-chu" class="text-brand-600 hover:text-brand-700 transition">Trang Chủ</a>
                <a href="#gioi-thieu" class="hover:text-brand-600 transition">Giới Thiệu</a>
                <a href="#san-pham-bep" class="hover:text-brand-600 transition">Sản Phẩm</a>
                <a href="#du-an-da-nang" class="hover:text-brand-600 transition">Dự Án Đà Nẵng</a>
                <a href="#bao-gia-form" class="hover:text-brand-600 transition">Báo Giá</a>
                <a href="#tin-tuc" class="hover:text-brand-600 transition">Bài Viết</a>
                <a href="#lien-he-map" class="hover:text-brand-600 transition">Liên Hệ</a>
            </nav>

            <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
            <button 
                type="button" 
                onclick="toggleMobileMenu()" 
                class="lg:hidden inline-flex items-center gap-1.5 px-3 py-1.5 rounded bg-brand-600 text-white text-xs font-semibold shrink-0"
            >
                <i class="fa-solid fa-bars"></i>
                <span>Danh Mục</span>
            </button>
        </div>

        <!-- ===================================================================
             THANH DANH MỤC SẢN PHẨM (LẤY TỪ WEB MẪU DUCANVU.COM)
             Tối ưu trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng (hoặc xuống hàng 2 nguyên cụm), tuyệt đối không đứt chữ của tên danh mục
        ==================================================================== -->
        <div class="bg-brand-700 text-white border-t border-brand-800">
            <div class="ux-container py-1.5">
                <!-- Danh mục hiển thị trên Máy tính -->
                <ul class="hidden md:flex flex-wrap items-center justify-center xl:justify-between gap-x-1.5 gap-y-1">
                    <li>
                        <a href="#san-pham-bep" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-kitchen-set text-amber-300 mr-1"></i>Thi Công Tủ Bếp Gỗ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-phong-ngu" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-place-of-worship text-amber-300 mr-1"></i>Thi Công Tủ Thờ Gỗ Tự Nhiên
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-cau-thang" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-door-open text-amber-300 mr-1"></i>Thi Công Cửa Gỗ Tự Nhiên
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-phong-khach" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-layer-group text-amber-300 mr-1"></i>Thi Công Nhựa Giả Đá
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-phong-ngu" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-border-all text-amber-300 mr-1"></i>Thi Công Sàn Gỗ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-phong-khach" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-boxes-stacked text-amber-300 mr-1"></i>Thi Công Tủ Gầm Cầu Thang
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-cau-thang" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-stairs text-amber-300 mr-1"></i>Thi Công Cầu Thang Gỗ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-phong-ngu" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-bed text-amber-300 mr-1"></i>Thi Công Đóng Giường Gỗ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-phong-ngu" class="cat-nav-item px-2 py-1 rounded text-[11px] xl:text-[11.5px] font-semibold hover:bg-brand-600">
                            <i class="fa-solid fa-box-archive text-amber-300 mr-1"></i>Thi Công Tủ Gỗ
                        </a>
                    </li>
                </ul>

                <!-- Thanh tìm kiếm nhanh trên Điện thoại -->
                <div class="md:hidden py-1">
                    <div class="relative w-full">
                        <input 
                            type="text" 
                            oninput="filterProductsBySearch(this.value)"
                            placeholder="Tìm kiếm sản phẩm nội thất..." 
                            class="w-full pl-3 pr-8 py-1.5 text-xs text-stone-800 bg-white rounded focus:outline-none"
                        >
                        <i class="fa-solid fa-magnifying-glass text-stone-400 text-xs absolute right-2.5 top-1/2 -translate-y-1/2"></i>
                    </div>
                </div>
            </div>
        </div>

        <!-- Menu Mở Rộng Trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-b border-stone-200 shadow-lg">
            <div class="ux-container py-3 space-y-3">
                <div class="flex flex-wrap gap-2 pb-2 border-b border-stone-100 text-xs font-bold uppercase text-stone-700">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-2.5 py-1 bg-brand-50 text-brand-700 rounded">Trang Chủ</a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-2.5 py-1 bg-stone-100 rounded">Giới Thiệu</a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-2.5 py-1 bg-stone-100 rounded">Dự Án Đà Nẵng</a>
                    <a href="#bao-gia-form" onclick="toggleMobileMenu()" class="px-2.5 py-1 bg-stone-100 rounded">Báo Giá</a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="px-2.5 py-1 bg-stone-100 rounded">Bài Viết</a>
                    <a href="#lien-he-map" onclick="toggleMobileMenu()" class="px-2.5 py-1 bg-stone-100 rounded">Bản Đồ</a>
                </div>
                <p class="text-[11px] font-bold uppercase text-brand-700">Danh Mục Sản Phẩm Thi Công:</p>
                <div class="grid grid-cols-2 gap-1.5 text-xs">
                    <a href="#san-pham-bep" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">1. Thi Công Tủ Bếp Gỗ</a>
                    <a href="#san-pham-phong-ngu" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">2. Tủ Thờ Gỗ Tự Nhiên</a>
                    <a href="#san-pham-cau-thang" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">3. Cửa Gỗ Tự Nhiên</a>
                    <a href="#san-pham-phong-khach" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">4. Nhựa Giả Đá Ốp Vách</a>
                    <a href="#san-pham-phong-ngu" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">5. Thi Công Sàn Gỗ</a>
                    <a href="#san-pham-phong-khach" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">6. Tủ Gầm Cầu Thang</a>
                    <a href="#san-pham-cau-thang" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">7. Cầu Thang Gỗ</a>
                    <a href="#san-pham-phong-ngu" onclick="toggleMobileMenu()" class="p-2 rounded bg-stone-50 border border-stone-200 font-medium text-stone-700">8. Đóng Giường & Tủ Gỗ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- =======================================================================
         SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Hình ảnh và chữ nằm gọn 100% trong banner
         - Chữ cách xa viền ảnh banner (padding lớn)
         - Không bị thiếu chữ trên cả điện thoại và máy tính
    ======================================================================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="ux-container">
            <div class="relative w-full h-[290px] sm:h-[350px] md:h-[420px] rounded-xl overflow-hidden shadow-md bg-brand-900">
                
                <!-- SLIDE BANNER 1 -->
                <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1cdntskkIe6lKP095A8uhscqiDa1P3QK5" 
                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1cdntskkIe6lKP095A8uhscqiDa1P3QK5&sz=w1200';"
                        alt="Banner 1 Nội Thất Phương Anh Đà Nẵng" 
                        class="w-full h-full object-cover object-center"
                    >
                    <!-- Lớp phủ tối giúp chữ nổi bật tuyệt đối -->
                    <div class="absolute inset-0 bg-gradient-to-r from-black/80 via-black/60 to-black/35"></div>
                    
                    <!-- Nội dung chữ cách xa viền banner trên cả mobile và PC -->
                    <div class="absolute inset-0 flex items-center justify-center sm:justify-start px-8 py-6 sm:px-16 sm:py-10 md:px-24 md:py-12">
                        <div class="max-w-xl text-white space-y-2 sm:space-y-3 text-center sm:text-left">
                            <p class="text-amber-300 text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-wider">
                                XƯỞNG NỘI THẤT PHƯƠNG ANH - NOITHATPHUONGANH.COM
                            </p>
                            <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                Thiết Kế & Thi Công Nội Thất Gỗ Trọn Gói Tại Đà Nẵng
                            </h1>
                            <p class="text-xs sm:text-sm text-stone-200 leading-relaxed">
                                Chuyên đóng tủ bếp gỗ, tủ quần áo, giường ngủ, kệ tivi, tủ gầm cầu thang, ốp vách nhựa giả đá trực tiếp tại xưởng Lưu Quang Vũ - Hoà Quý - Đà Nẵng.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap items-center justify-center sm:justify-start gap-2.5">
                                <a href="#bao-gia-form" class="px-4 py-2 rounded-md bg-brand-500 hover:bg-brand-600 text-white font-bold text-xs sm:text-sm transition shadow">
                                    Nhận Báo Giá Tại Xưởng
                                </a>
                                <a href="tel:0905801976" class="px-4 py-2 rounded-md bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition">
                                    Hotline: 0905.80.1976
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE BANNER 2 (KÍCH THƯỚC BẰNG HỆT BANNER 1) -->
                <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 pointer-events-none">
                    <img 
                        src="https://lh3.googleusercontent.com/d/13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj" 
                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj&sz=w1200';"
                        alt="Banner 2 Thi Công Tủ Bếp Phòng Khách Nội Thất Phương Anh" 
                        class="w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-black/80 via-black/60 to-black/35"></div>
                    
                    <!-- Nội dung chữ cách xa viền banner trên cả mobile và PC -->
                    <div class="absolute inset-0 flex items-center justify-center sm:justify-start px-8 py-6 sm:px-16 sm:py-10 md:px-24 md:py-12">
                        <div class="max-w-xl text-white space-y-2 sm:space-y-3 text-center sm:text-left">
                            <p class="text-amber-300 text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-wider">
                                UY TÍN - CHẤT LƯỢNG - BẢO HÀNH DÀI HẠN 3 NĂM
                            </p>
                            <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                Chuyên Tủ Bếp, Tủ Thờ, Cửa Gỗ & Cầu Thang Đẹp Đà Nẵng
                            </h2>
                            <p class="text-xs sm:text-sm text-stone-200 leading-relaxed">
                                Khảo sát tận nơi miễn phí, lên bản vẽ 3D tối ưu công năng, cam kết vật liệu gỗ tự nhiên và gỗ MDF chống ẩm chuẩn chất lượng.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap items-center justify-center sm:justify-start gap-2.5">
                                <a href="#du-an-da-nang" class="px-4 py-2 rounded-md bg-brand-500 hover:bg-brand-600 text-white font-bold text-xs sm:text-sm transition shadow">
                                    Xem Công Trình Thực Tế
                                </a>
                                <a href="#lien-he-map" class="px-4 py-2 rounded-md bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition">
                                    Xem Địa Chỉ Xưởng
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút chuyển trái/phải nằm gọn bên trong mép banner -->
                <button 
                    type="button" 
                    onclick="changeBanner(-1)" 
                    aria-label="Banner trước"
                    class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/45 hover:bg-brand-600 text-white flex items-center justify-center transition"
                >
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button 
                    type="button" 
                    onclick="changeBanner(1)" 
                    aria-label="Banner tiếp theo"
                    class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/45 hover:bg-brand-600 text-white flex items-center justify-center transition"
                >
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBanner(0)" id="bannerDot0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="goToBanner(1)" id="bannerDot1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 2: 4 Ô CAM KẾT GIÁ TRỊ (GIỐNG WEB MẪU DUCANVU.COM)
    ======================================================================== -->
    <section id="gioi-thieu" class="py-3">
        <div class="ux-container">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3">
                <div class="bg-white p-3.5 rounded-lg border border-stone-200 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-medal"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800 uppercase">Uy Tín Hàng Đầu</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5 leading-relaxed">Nội Thất Phương Anh luôn đặt chữ Tâm và lợi ích khách hàng lên trên hết.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-stone-200 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-gem"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800 uppercase">Sản Phẩm Cao Cấp</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5 leading-relaxed">Vật liệu gỗ tự nhiên, MDF lõi xanh chống ẩm có nguồn gốc xuất xứ rõ ràng.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-stone-200 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800 uppercase">Chất Lượng Bền Bỉ</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5 leading-relaxed">Thi công sắc nét từng chi tiết, an toàn và bảo hành uy tín 3 năm.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-stone-200 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800 uppercase">Hỗ Trợ Nhanh 24/7</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5 leading-relaxed">Khảo sát đo đạc và báo giá tận nơi tại Đà Nẵng qua 0905.80.1976.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 3: DANH MỤC SẢN PHẨM THI CÔNG (TỐI ƯU HIỂN THỊ TRÊN PC & MOBILE)
         - Trên máy tính: 9 danh mục nằm gọn đẹp, tên danh mục viết liền trên 1 hàng chữ nhỏ gọn
         - Trên điện thoại: Chia lưới gọn đẹp dễ bấm
    ======================================================================== -->
    <section class="py-3">
        <div class="ux-container">
            <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-stone-200">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-stone-100">
                    <h2 class="text-xs sm:text-sm font-bold uppercase text-brand-700 flex items-center gap-2">
                        <i class="fa-solid fa-table-cells-large"></i> Danh Mục Sản Phẩm Chủ Lực
                    </h2>
                    <span class="text-[11px] text-stone-500">Xưởng sản xuất trực tiếp Lưu Quang Vũ - Hoà Quý</span>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-9 gap-2">
                    <a href="#san-pham-bep" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-kitchen-set text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Thi Công Tủ Bếp Gỗ</span>
                    </a>
                    <a href="#san-pham-phong-ngu" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-place-of-worship text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Tủ Thờ Gỗ Tự Nhiên</span>
                    </a>
                    <a href="#san-pham-cau-thang" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-door-open text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Cửa Gỗ Tự Nhiên</span>
                    </a>
                    <a href="#san-pham-phong-khach" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-layer-group text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Thi Công Nhựa Giả Đá</span>
                    </a>
                    <a href="#san-pham-phong-ngu" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-border-all text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Thi Công Sàn Gỗ</span>
                    </a>
                    <a href="#san-pham-phong-khach" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-boxes-stacked text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Tủ Gầm Cầu Thang</span>
                    </a>
                    <a href="#san-pham-cau-thang" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-stairs text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Thi Công Cầu Thang Gỗ</span>
                    </a>
                    <a href="#san-pham-phong-ngu" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group">
                        <i class="fa-solid fa-bed text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Đóng Giường Gỗ</span>
                    </a>
                    <a href="#san-pham-phong-ngu" class="flex flex-col items-center justify-center p-2.5 rounded-md bg-brand-50/70 hover:bg-brand-600 hover:text-white text-stone-800 border border-brand-100 transition text-center group col-span-2 sm:col-span-1">
                        <i class="fa-solid fa-box-archive text-brand-600 group-hover:text-amber-300 text-base mb-1"></i>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Thi Công Tủ Gỗ</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 4: THI CÔNG NỘI THẤT PHÒNG BẾP (GIỐNG WEB MẪU DUCANVU.COM)
         - Điện thoại: Chia 2 cột (grid-cols-2)
         - Máy tính: Chia 4 cột (lg:grid-cols-4)
         - Không để nhãn dán ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không tràn ra ngoài hoặc thiếu chữ
    ======================================================================== -->
    <section id="san-pham-bep" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-kitchen-set"></i> Thi Công Nội Thất Phòng Bếp</h2>
                <a href="#bao-gia-form" class="text-xs font-semibold text-brand-700 hover:underline pr-3">Nhận báo giá trọn gói <i class="fa-solid fa-angle-right ml-1"></i></a>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Sản phẩm 1 (Ảnh Drive thực tế 1) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1cdntskkIe6lKP095A8uhscqiDa1P3QK5" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1cdntskkIe6lKP095A8uhscqiDa1P3QK5&sz=w800';"
                            alt="Báo giá thi công tủ bếp tại Đà Nẵng năm 2026 - Xưởng sản xuất" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công tủ bếp tại Đà Nẵng năm 2026 – Xưởng sản xuất Phương Anh
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Thi công tủ bếp gỗ công nghiệp MDF lõi xanh chống ẩm phủ Acrylic, Melamine kịch trần hiện đại.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công tủ bếp trọn gói tại Đà Nẵng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2 (Ảnh Drive thực tế 2) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1INdFx94JziGPMPTNPyPu0OJACBTaWeok" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1INdFx94JziGPMPTNPyPu0OJACBTaWeok&sz=w800';"
                            alt="Báo giá đóng tủ bếp bằng gỗ tự nhiên tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá đóng tủ bếp bằng gỗ tự nhiên và MDF chống ẩm tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Thiết kế tủ bếp chữ L, chữ I tối ưu công năng, tích hợp hệ đèn LED và mặt đá bếp sang trọng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Đóng tủ bếp gỗ tự nhiên & MDF chống ẩm')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3 (Ảnh Drive thực tế 3) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1uRvRMmyt67bsWZxms0fnYKt4huKWRF41" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1uRvRMmyt67bsWZxms0fnYKt4huKWRF41&sz=w800';"
                            alt="Thi công tủ bếp kịch trần kèm hệ tủ kho và quầy bar" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Thi công tủ bếp kịch trần kết hợp quầy bar và tủ rượu phòng bếp
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Giải pháp không gian bếp thông minh cho nhà phố và căn hộ tại Đà Nẵng, chống mối mọt tuyệt đối.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Tủ bếp kịch trần kết hợp quầy bar')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4 (Ảnh Drive thực tế 4) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj&sz=w800';"
                            alt="Báo giá phụ kiện tủ bếp tại Đà Nẵng giá rẻ năm 2026" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá phụ kiện tủ bếp inox 304 tại Đà Nẵng năm 2026 – 0905.80.1976
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Lắp đặt trọn bộ giá bát nâng hạ, kệ xoong nồi, kệ gia vị, thùng gạo thông minh chính hãng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Phụ kiện tủ bếp inox 304 chính hãng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 5: THI CÔNG NỘI THẤT PHÒNG KHÁCH (GIỐNG WEB MẪU DUCANVU.COM)
    ======================================================================== -->
    <section id="san-pham-phong-khach" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-couch"></i> Thi Công Nội Thất Phòng Khách</h2>
                <a href="#bao-gia-form" class="text-xs font-semibold text-brand-700 hover:underline pr-3">Nhận báo giá trọn gói <i class="fa-solid fa-angle-right ml-1"></i></a>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Sản phẩm 5 (Ảnh Drive thực tế 5) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1i_1pSkyGPvGr839M-ZvMIS5UTXiWeK_k" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1i_1pSkyGPvGr839M-ZvMIS5UTXiWeK_k&sz=w800';"
                            alt="Báo giá đóng kệ tivi tại Đà Nẵng năm 2026" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá đóng kệ tivi phòng khách tại Đà Nẵng năm 2026 – 0905.80.1976
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Thiết kế kệ tivi treo tường, kệ tivi kết hợp tủ rượu trang trí bằng gỗ công nghiệp và gỗ tự nhiên.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Đóng kệ tivi phòng khách tại Đà Nẵng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 6 (Ảnh Drive thực tế 6) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1LkHBJkFp2tT8P5DL9W4eNuXaYmgIKvRl" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1LkHBJkFp2tT8P5DL9W4eNuXaYmgIKvRl&sz=w800';"
                            alt="Thi công ốp vách tivi bằng tấm nhựa giả đá tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Thi công ốp vách tivi bằng tấm nhựa giả đá và lam sóng tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Chuyên ốp vách tivi nhựa PVC vân đá kết hợp lam sóng giả gỗ sang trọng, chống ẩm mốc bền đẹp.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công ốp vách tivi nhựa giả đá & lam sóng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 7 (Ảnh Drive thực tế 7) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1A4lhN4nyV2kEG-J8F__6vo2tkt24j9Yd" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1A4lhN4nyV2kEG-J8F__6vo2tkt24j9Yd&sz=w800';"
                            alt="Báo giá thi công đóng tủ gầm cầu thang tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công đóng tủ gầm cầu thang tối ưu diện tích tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Đóng tủ kệ tivi, tủ rượu và tủ chứa đồ dưới gầm cầu thang đo đóng chuẩn xác theo từng góc nhà.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Đóng tủ gầm cầu thang tại Đà Nẵng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 8 (Ảnh Drive thực tế 8) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1toGuIGLEJyuwRhchcgk3myiWHFhZkn9u" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1toGuIGLEJyuwRhchcgk3myiWHFhZkn9u&sz=w800';"
                            alt="Thi công tủ rượu và vách ngăn trang trí phòng khách" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Thi công tủ rượu cánh kính và vách ngăn phòng khách hiện đại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Tủ rượu khung nhôm cánh kính cường lực tích hợp đèn LED cảm biến tôn vinh không gian phòng khách.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công tủ rượu cánh kính & vách ngăn')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 6: THI CÔNG NỘI THẤT PHÒNG NGỦ, TỦ THỜ & SÀN GỖ
    ======================================================================== -->
    <section id="san-pham-phong-ngu" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-bed"></i> Thi Công Phòng Ngủ, Tủ Thờ & Sàn Gỗ</h2>
                <a href="#bao-gia-form" class="text-xs font-semibold text-brand-700 hover:underline pr-3">Nhận báo giá trọn gói <i class="fa-solid fa-angle-right ml-1"></i></a>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Sản phẩm 9 (Ảnh Drive thực tế 9) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx&sz=w800';"
                            alt="Báo giá thi công đóng tủ gỗ quần áo tại Đà Nẵng năm 2026" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công đóng tủ gỗ quần áo kịch trần tại Đà Nẵng năm 2026
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Chuyên đóng tủ quần áo cửa lùa, tủ áo góc trang trí bằng gỗ công nghiệp MDF và gỗ tự nhiên.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Đóng tủ quần áo gỗ tại Đà Nẵng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 10 (Ảnh Drive thực tế 10) -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/18fK1d4q550p2MHABgl3XvT0rXFWau6OS" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=18fK1d4q550p2MHABgl3XvT0rXFWau6OS&sz=w800';"
                            alt="Thi công đóng giường gỗ và combo phòng ngủ tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá đóng giường ngủ gỗ và bàn trang điểm đồng bộ tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Giường ngủ có hộc kéo thông minh, kết cấu thang giường chắc chắn, bọc nệm đầu giường êm ái.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Đóng giường ngủ gỗ & combo phòng ngủ')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 11 -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1INdFx94JziGPMPTNPyPu0OJACBTaWeok" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1INdFx94JziGPMPTNPyPu0OJACBTaWeok&sz=w800';"
                            alt="Thi công tủ thờ gỗ tự nhiên chuẩn thước Lỗ Ban tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Thi công tủ thờ gỗ tự nhiên và vách ngăn phòng thờ tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Chạm khắc tinh xảo từ gỗ sồi, gỗ gõ đỏ, gỗ mít chuẩn kích thước phong thủy Lỗ Ban.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công tủ thờ gỗ tự nhiên & phòng thờ')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 12 -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1uRvRMmyt67bsWZxms0fnYKt4huKWRF41" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1uRvRMmyt67bsWZxms0fnYKt4huKWRF41&sz=w800';"
                            alt="Báo giá thi công sàn gỗ công nghiệp tại Đà Nẵng năm 2026" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công sàn gỗ công nghiệp và sàn nhựa giả gỗ tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Thi công sàn gỗ cốt xanh chịu nước, chống trầy xước AC4/AC5 ấm áp và sang trọng cho phòng ngủ.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công sàn gỗ công nghiệp tại Đà Nẵng')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 7: THI CÔNG CẦU THANG & CỬA GỖ (GIỐNG WEB MẪU DUCANVU.COM)
    ======================================================================== -->
    <section id="san-pham-cau-thang" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-stairs"></i> Thi Công Cầu Thang Gỗ & Cửa Gỗ Tự Nhiên</h2>
                <a href="#bao-gia-form" class="text-xs font-semibold text-brand-700 hover:underline pr-3">Nhận báo giá trọn gói <i class="fa-solid fa-angle-right ml-1"></i></a>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Sản phẩm 13 -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1A4lhN4nyV2kEG-J8F__6vo2tkt24j9Yd" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1A4lhN4nyV2kEG-J8F__6vo2tkt24j9Yd&sz=w800';"
                            alt="Báo giá thi công cầu thang gỗ tại Đà Nẵng năm 2026" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công cầu thang gỗ tự nhiên tại Đà Nẵng năm 2026
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Chuyên đóng tay vịn, trụ đề ba và mặt bậc cầu thang gỗ lim Nam Phi, gỗ gõ đỏ, gỗ sồi Nga bền đẹp.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công cầu thang gỗ tự nhiên')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 14 -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1toGuIGLEJyuwRhchcgk3myiWHFhZkn9u" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1toGuIGLEJyuwRhchcgk3myiWHFhZkn9u&sz=w800';"
                            alt="Báo giá thi công lan can cầu thang kính tay vịn gỗ tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công lan can cầu thang kính cường lực tay vịn gỗ tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Kết hợp kính cường lực 10ly - 12ly an toàn với tay vịn gỗ tự nhiên giúp ngôi nhà thông thoáng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công lan can cầu thang kính tay vịn gỗ')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 15 -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1LkHBJkFp2tT8P5DL9W4eNuXaYmgIKvRl" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1LkHBJkFp2tT8P5DL9W4eNuXaYmgIKvRl&sz=w800';"
                            alt="Báo giá thi công đóng cửa gỗ tại Đà Nẵng năm 2026" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Báo giá thi công đóng cửa gỗ tự nhiên phòng ngủ và cửa chính tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Sản xuất cửa gỗ 1 cánh, 2 cánh, 4 cánh đã qua tẩm sấy chống cong vênh, co ngót tại xưởng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công đóng cửa gỗ tự nhiên')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 16 -->
                <div class="ux-product-card product-item">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1i_1pSkyGPvGr839M-ZvMIS5UTXiWeK_k" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1i_1pSkyGPvGr839M-ZvMIS5UTXiWeK_k&sz=w800';"
                            alt="Thi công hệ lam gỗ cầu thang kết hợp tủ trang trí tại Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                                Thi công hệ lam gỗ chắn cầu thang kết hợp kệ trang trí phòng khách
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                                Giải pháp thay thế lan can truyền thống giúp phân chia phòng khách và cầu thang tinh tế, hiện đại.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-brand-600">Liên Hệ</span>
                            <button type="button" onclick="selectProductForQuote('Thi công hệ lam gỗ cầu thang')" class="px-2.5 py-1 rounded bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-semibold transition">
                                Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 8: DANH MỤC CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
         (Chia 2 cột trên điện thoại, 4 cột trên máy tính, không dán nhãn)
    ======================================================================== -->
    <section id="du-an-da-nang" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-building-circle-check"></i> Dự Án Thi Công Thực Tế Tại Đà Nẵng</h2>
                <span class="text-xs text-stone-500 pr-3 hidden sm:inline">Hình ảnh bàn giao thực tế bởi Nội Thất Phương Anh</span>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Dự án 1 -->
                <div class="ux-product-card">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1cdntskkIe6lKP095A8uhscqiDa1P3QK5" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1cdntskkIe6lKP095A8uhscqiDa1P3QK5&sz=w800';"
                            alt="Dự án nội thất nhà phố đường Lưu Quang Vũ - Phường Hoà Quý" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800">
                            Thi công trọn gói nội thất nhà phố đường Lưu Quang Vũ, Phường Hoà Quý, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Tủ bếp MDF lõi xanh phủ Acrylic, kệ tivi, tủ gầm cầu thang và 3 phòng ngủ đồng bộ.
                        </p>
                    </div>
                </div>

                <!-- Dự án 2 -->
                <div class="ux-product-card">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj&sz=w800';"
                            alt="Dự án biệt thự Khu đô thị Hòa Xuân Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800">
                            Hoàn thiện nội thất phòng bếp và phòng khách tại Khu đô thị Hòa Xuân, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Tủ bếp kịch trần, quầy bar mặt đá, vách tivi lam sóng nhựa giả đá và tủ rượu cánh kính.
                        </p>
                    </div>
                </div>

                <!-- Dự án 3 -->
                <div class="ux-product-card">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx&sz=w800';"
                            alt="Dự án nội thất Khu đô thị FPT City Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800">
                            Thi công nội thất căn hộ và nhà liền kề tại Khu đô thị FPT City Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Hệ tủ quần áo kịch trần, giường ngủ thông minh, bàn làm việc và sàn gỗ chống ẩm.
                        </p>
                    </div>
                </div>

                <!-- Dự án 4 -->
                <div class="ux-product-card">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/18fK1d4q550p2MHABgl3XvT0rXFWau6OS" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=18fK1d4q550p2MHABgl3XvT0rXFWau6OS&sz=w800';"
                            alt="Dự án nội thất nhà phố Quận Sơn Trà Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800">
                            Bàn giao combo nội thất phòng ngủ và cầu thang gỗ nhà phố Sơn Trà, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Cầu thang gỗ tự nhiên, cửa gỗ phòng ngủ, tủ thờ gia tiên và nội thất phòng Master.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 9: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
    ======================================================================== -->
    <section id="bao-gia-form" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl border border-stone-200 p-4 sm:p-6 shadow-sm">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    
                    <!-- Cột thông tin cam kết báo giá -->
                    <div class="lg:col-span-5 space-y-3">
                        <span class="inline-block text-xs font-bold uppercase text-brand-600 tracking-wider">
                            BÁO GIÁ TRỰC TIẾP TẠI XƯỞNG ĐÀ NẴNG
                        </span>
                        <h2 class="text-lg sm:text-2xl font-extrabold text-stone-800 leading-snug">
                            Đăng Ký Yêu Cầu Tư Vấn & Nhận Báo Giá Nội Thất
                        </h2>
                        <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                            Quý khách để lại thông tin hoặc hạng mục cần làm, kỹ thuật viên của <strong>Nội Thất Phương Anh</strong> sẽ liên hệ tư vấn, khảo sát đo đạc thực tế và gửi bảng báo giá chi tiết miễn phí.
                        </p>
                        <div class="space-y-2 pt-1 text-xs sm:text-sm text-stone-700">
                            <div class="flex items-center gap-2.5">
                                <i class="fa-solid fa-circle-check text-brand-600"></i>
                                <span>Giá gốc trực tiếp tại xưởng sản xuất Lưu Quang Vũ - Hoà Quý</span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <i class="fa-solid fa-circle-check text-brand-600"></i>
                                <span>Miễn phí 100% khảo sát tận nhà và thiết kế bản vẽ 3D</span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <i class="fa-solid fa-circle-check text-brand-600"></i>
                                <span>Bảo hành 3 năm, bảo trì nhanh chóng tại Đà Nẵng</span>
                            </div>
                        </div>
                        <div class="pt-2 flex flex-wrap items-center gap-3">
                            <a href="tel:0905801976" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-brand-50 text-brand-700 font-bold text-xs sm:text-sm border border-brand-200">
                                <i class="fa-solid fa-phone-volume"></i> Hotline/Zalo: 0905.80.1976
                            </a>
                        </div>
                    </div>

                    <!-- Cột Form nhập thông tin -->
                    <div class="lg:col-span-7 bg-stone-50 p-4 sm:p-5 rounded-lg border border-stone-200">
                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Họ và tên quý khách *</label>
                                    <input 
                                        type="text" 
                                        id="customerName" 
                                        required 
                                        placeholder="Nhập họ và tên..." 
                                        class="w-full px-3 py-2 text-xs sm:text-sm bg-white border border-stone-300 rounded-md focus:outline-none focus:border-brand-600"
                                    >
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input 
                                        type="tel" 
                                        id="customerPhone" 
                                        required 
                                        placeholder="Ví dụ: 0905xxxxxx" 
                                        class="w-full px-3 py-2 text-xs sm:text-sm bg-white border border-stone-300 rounded-md focus:outline-none focus:border-brand-600"
                                    >
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Hạng mục cần báo giá</label>
                                    <select 
                                        id="customerCategory" 
                                        class="w-full px-3 py-2 text-xs sm:text-sm bg-white border border-stone-300 rounded-md focus:outline-none focus:border-brand-600"
                                    >
                                        <option value="Thi công tủ bếp gỗ trọn gói">Thi công tủ bếp gỗ trọn gói</option>
                                        <option value="Thi công nội thất phòng khách (Kệ tivi, Vách ốp)">Thi công nội thất phòng khách (Kệ tivi, Vách ốp)</option>
                                        <option value="Thi công nội thất phòng ngủ (Giường, Tủ áo)">Thi công nội thất phòng ngủ (Giường, Tủ áo)</option>
                                        <option value="Thi công tủ thờ gỗ tự nhiên">Thi công tủ thờ gỗ tự nhiên</option>
                                        <option value="Thi công cửa gỗ tự nhiên">Thi công cửa gỗ tự nhiên</option>
                                        <option value="Thi công nhựa giả đá / Lam sóng">Thi công nhựa giả đá / Lam sóng</option>
                                        <option value="Thi công sàn gỗ công nghiệp">Thi công sàn gỗ công nghiệp</option>
                                        <option value="Thi công tủ gầm cầu thang">Thi công tủ gầm cầu thang</option>
                                        <option value="Thi công cầu thang gỗ / Lan can kính">Thi công cầu thang gỗ / Lan can kính</option>
                                        <option value="Thi công nội thất nhà phố / căn hộ trọn gói">Thi công nội thất nhà phố / căn hộ trọn gói</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Địa chỉ công trình tại Đà Nẵng</label>
                                    <input 
                                        type="text" 
                                        id="customerAddress" 
                                        placeholder="Ví dụ: Hoà Quý, Ngũ Hành Sơn, Đà Nẵng" 
                                        class="w-full px-3 py-2 text-xs sm:text-sm bg-white border border-stone-300 rounded-md focus:outline-none focus:border-brand-600"
                                    >
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Yêu cầu chi tiết (Kích thước, chất liệu mong muốn...)</label>
                                <textarea 
                                    id="customerNote" 
                                    rows="2" 
                                    placeholder="Nhập yêu cầu cụ thể của quý khách..." 
                                    class="w-full px-3 py-2 text-xs sm:text-sm bg-white border border-stone-300 rounded-md focus:outline-none focus:border-brand-600"
                                ></textarea>
                            </div>

                            <button 
                                type="submit" 
                                class="w-full py-2.5 px-4 rounded-md bg-brand-600 hover:bg-brand-700 text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition shadow"
                            >
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Nhận Báo Giá Ngay
                            </button>

                            <!-- Thông báo gửi thành công -->
                            <div id="quoteSuccessBox" class="hidden p-3 rounded-md bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs leading-relaxed"></div>
                        </form>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 10: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM)
    ======================================================================== -->
    <section id="tin-tuc" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-newspaper"></i> Bài Viết & Kinh Nghiệm Nội Thất</h2>
                <span class="text-xs text-stone-500 pr-3 hidden sm:inline">Cập nhật báo giá & xu hướng nội thất Đà Nẵng 2026</span>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Bài viết 1 -->
                <article class="ux-product-card">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1cdntskkIe6lKP095A8uhscqiDa1P3QK5" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1cdntskkIe6lKP095A8uhscqiDa1P3QK5&sz=w800';"
                            alt="Kinh nghiệm chọn vật liệu làm tủ bếp bền đẹp tại Đà Nẵng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                            Kinh nghiệm chọn gỗ MDF lõi xanh chống ẩm và gỗ tự nhiên khi đóng tủ bếp tại Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                            So sánh chi tiết độ bền, khả năng chống ẩm và chi phí thi công các dòng tủ bếp phổ biến hiện nay.
                        </p>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="ux-product-card">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1LkHBJkFp2tT8P5DL9W4eNuXaYmgIKvRl" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1LkHBJkFp2tT8P5DL9W4eNuXaYmgIKvRl&sz=w800';"
                            alt="Xu hướng ốp vách tivi nhựa giả đá kết hợp lam sóng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                            Xu hướng thi công ốp vách tivi bằng tấm nhựa giả đá kết hợp lam sóng gỗ phòng khách
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                            Giải pháp làm mới không gian phòng khách sang trọng, thi công nhanh trong ngày và chi phí tiết kiệm.
                        </p>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="ux-product-card">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1A4lhN4nyV2kEG-J8F__6vo2tkt24j9Yd" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1A4lhN4nyV2kEG-J8F__6vo2tkt24j9Yd&sz=w800';"
                            alt="Cách tận dụng gầm cầu thang làm tủ kệ tivi đẹp" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                            Mẹo tận dụng gầm cầu thang nhà ống làm tủ rượu và kệ tivi gọn đẹp, tối ưu diện tích
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                            Biến góc chết dưới chân cầu thang thành điểm nhấn lưu trữ thẩm mỹ cao cho nhà phố hiện đại.
                        </p>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="ux-product-card">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx&sz=w800';"
                            alt="Bảng báo giá thi công nội thất trọn gói tại Đà Nẵng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="ux-product-title text-xs sm:text-sm font-bold text-stone-800 hover:text-brand-600">
                            Bảng báo giá thiết kế và thi công nội thất phòng ngủ, phòng bếp tại xưởng Đà Nẵng 2026
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5 leading-relaxed">
                            Chi tiết đơn giá đóng tủ quần áo kịch trần, giường ngủ, bàn trang điểm và tủ bếp tại Nội Thất Phương Anh.
                        </p>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 11: DANH MỤC ĐỐI TÁC & VẬT LIỆU CHÍNH HÃNG
    ======================================================================== -->
    <section class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-handshake"></i> Đối Tác & Thương Hiệu Vật Liệu</h2>
                <span class="text-xs text-stone-500 pr-3 hidden sm:inline">Cam kết phụ kiện & vật liệu chính hãng 100%</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">AN CƯỜNG</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Gỗ Công Nghiệp</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">HAFELE</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Phụ Kiện Nội Thất</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">BLUM</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Bản Lề & Ray Trượt</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">EUROGOLD</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Phụ Kiện Tủ Bếp</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">CARINY</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Phụ Kiện Bếp Inox</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">MALLOCA</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Thiết Bị Nhà Bếp</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">VICOSTONE</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Đá Mặt Bếp Cao Cấp</span>
                </div>
                <div class="bg-white border border-stone-200 rounded-lg p-3 text-center flex flex-col items-center justify-center">
                    <span class="text-xs font-extrabold text-brand-700 tracking-wide">INCHEM</span>
                    <span class="text-[10px] text-stone-500 mt-0.5">Sơn Gỗ Cao Cấp</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =======================================================================
         SECTION 12: ĐƯA ẢNH GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
    ======================================================================== -->
    <section id="lien-he-map" class="py-3 pb-6">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2><i class="fa-solid fa-map-location-dot"></i> Bản Đồ Đường Đi & Fanpage Nội Thất Phương Anh</h2>
                <span class="text-xs text-stone-500 pr-3 hidden sm:inline">Lưu Quang Vũ - Hoà Quý - Đà Nẵng</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                
                <!-- BẢN ĐỒ GOOGLE MAP TRANG CHỦ (7 CỘT) -->
                <div class="lg:col-span-7 bg-white rounded-lg border border-stone-200 p-3.5 flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800">
                                <i class="fa-solid fa-location-dot text-red-600 mr-1"></i> Địa chỉ: Đường Lưu Quang Vũ - Phường Hoà Quý - Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-stone-500">Liên hệ chỉ đường hoặc ghé xưởng trực tiếp: <strong>0905.80.1976</strong></p>
                        </div>
                        <a 
                            href="https://www.google.com/maps/search/?api=1&query=Lưu+Quang+Vũ,+Hòa+Quý,+Ngũ+Hành+Sơn,+Đà+Nẵng" 
                            target="_blank" 
                            rel="noopener"
                            class="px-3 py-1.5 rounded bg-brand-600 hover:bg-brand-700 text-white text-xs font-semibold transition"
                        >
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Maps
                        </a>
                    </div>

                    <div class="w-full h-[250px] sm:h-[290px] rounded-lg overflow-hidden border border-stone-200 relative bg-stone-100">
                        <iframe 
                            title="Bản đồ Nội Thất Phương Anh - Lưu Quang Vũ, Hoà Quý, Đà Nẵng"
                            src="https://maps.google.com/maps?q=L%C6%B0u%20Quang%20V%C5%A9,%20H%C3%B2a%20Qu%C3%BD,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                </div>

                <!-- FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ (5 CỘT) -->
                <div class="lg:col-span-5 bg-white rounded-lg border border-stone-200 p-3.5 flex flex-col justify-between">
                    <div class="mb-2.5">
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800">
                            <i class="fa-brands fa-facebook text-[#1877F2] mr-1"></i> Kết Nối Fanpage Facebook Chính Thức
                        </h3>
                        <p class="text-[11px] text-stone-500">Cập nhật hình ảnh công trình thi công thực tế mới nhất mỗi ngày</p>
                    </div>

                    <!-- Khung hiển thị trực quan Fanpage Nội Thất Phương Anh -->
                    <div class="rounded-lg overflow-hidden border border-stone-200 bg-stone-50 flex-1 flex flex-col justify-between">
                        <div class="relative h-36 sm:h-40 w-full overflow-hidden">
                            <img 
                                src="https://lh3.googleusercontent.com/d/13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj" 
                                onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=13t7Gec0GRRJJWHG-7CUNTr8Hy0k3rymj&sz=w800';"
                                alt="Ảnh bìa Fanpage Nội Thất Phương Anh" 
                                class="w-full h-full object-cover"
                            >
                            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/35 to-transparent"></div>
                            <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/12emKoKiVivjuzhQPkG1oInB00n3fpMZX" 
                                    onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=12emKoKiVivjuzhQPkG1oInB00n3fpMZX&sz=w300';"
                                    alt="Avatar Fanpage Nội Thất Phương Anh" 
                                    class="w-12 h-12 rounded-full border-2 border-white bg-white object-contain p-0.5 shrink-0"
                                >
                                <div class="text-white min-w-0">
                                    <a href="https://www.facebook.com/profile.php?id=100078411751009" target="_blank" rel="noopener" class="font-bold text-sm hover:underline block truncate">
                                        Nội Thất Phương Anh - Đà Nẵng
                                    </a>
                                    <span class="text-[11px] text-stone-200 block">Thiết kế & Thi công nội thất trọn gói</span>
                                </div>
                            </div>
                        </div>

                        <div class="p-3 space-y-2.5">
                            <p class="text-xs text-stone-600 leading-relaxed">
                                <i class="fa-solid fa-check text-brand-600 mr-1"></i> Chuyên tủ bếp, giường tủ, kệ tivi, tủ gầm cầu thang, cửa gỗ, cầu thang gỗ tại Lưu Quang Vũ - Hoà Quý - Đà Nẵng.
                            </p>
                            <div class="grid grid-cols-3 gap-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1cdntskkIe6lKP095A8uhscqiDa1P3QK5" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1cdntskkIe6lKP095A8uhscqiDa1P3QK5&sz=w400';" alt="Ảnh thực tế 1" class="h-14 w-full object-cover rounded">
                                <img src="https://lh3.googleusercontent.com/d/1i_1pSkyGPvGr839M-ZvMIS5UTXiWeK_k" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1i_1pSkyGPvGr839M-ZvMIS5UTXiWeK_k&sz=w400';" alt="Ảnh thực tế 2" class="h-14 w-full object-cover rounded">
                                <img src="https://lh3.googleusercontent.com/d/1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1qEJSBFnT7XbPu52eE7vbfJ1-lzWkLEKx&sz=w400';" alt="Ảnh thực tế 3" class="h-14 w-full object-cover rounded">
                            </div>
                            <div class="pt-1 flex items-center gap-2">
                                <a 
                                    href="https://www.facebook.com/profile.php?id=100078411751009" 
                                    target="_blank" 
                                    rel="noopener"
                                    class="flex-1 py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-semibold text-xs text-center transition"
                                >
                                    <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Fanpage
                                </a>
                                <a 
                                    href="https://www.facebook.com/profile.php?id=100078411751009" 
                                    target="_blank" 
                                    rel="noopener"
                                    class="flex-1 py-2 px-3 rounded bg-stone-200 hover:bg-stone-300 text-stone-800 font-semibold text-xs text-center transition"
                                >
                                    <i class="fa-brands fa-facebook-messenger text-[#1877F2] mr-1"></i> Nhắn Tin Ngay
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =======================================================================
         FOOTER (CHÂN TRANG GIỐNG BỐ CỤC MẪU DUCANVU.COM)
    ======================================================================== -->
    <footer class="bg-brand-900 text-stone-200 pt-8 pb-6 border-t-4 border-brand-500">
        <div class="ux-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-brand-800">
                
                <!-- Cột 1: Thông tin Nội Thất Phương Anh -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/12emKoKiVivjuzhQPkG1oInB00n3fpMZX" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=12emKoKiVivjuzhQPkG1oInB00n3fpMZX&sz=w300';"
                            alt="Logo Nội Thất Phương Anh" 
                            class="h-10 w-auto object-contain bg-white rounded p-0.5"
                        >
                        <div>
                            <h3 class="text-sm font-extrabold text-white uppercase">NỘI THẤT PHƯƠNG ANH</h3>
                            <p class="text-[11px] text-amber-300">Sự Lựa Chọn Hoàn Hảo Của Bạn</p>
                        </div>
                    </div>
                    <p class="text-xs text-stone-300 leading-relaxed">
                        Xưởng chuyên tư vấn, thiết kế và thi công nội thất phòng bếp, phòng khách, phòng ngủ, tủ thờ, cầu thang gỗ, cửa gỗ, sàn gỗ uy tín tại Đà Nẵng.
                    </p>
                    <ul class="text-xs space-y-1.5 text-stone-200 pt-1">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i><strong>Địa chỉ:</strong> Lưu Quang Vũ - Hoà Quý - Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i><strong>Hotline/Zalo:</strong> <a href="tel:0905801976" class="text-amber-300 font-bold">0905.80.1976</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-1.5"></i><strong>Website:</strong> noithatphuonganh.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Về Chúng Tôi (Giống mẫu ducanvu.com) -->
                <div>
                    <h4 class="text-xs sm:text-sm font-bold uppercase text-amber-300 mb-3 pb-1.5 border-b border-brand-800">
                        Về Chúng Tôi
                    </h4>
                    <ul class="space-y-2 text-xs text-stone-300">
                        <li><a href="#gioi-thieu" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Giới thiệu xưởng Nội Thất Phương Anh</a></li>
                        <li><a href="#san-pham-bep" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Dịch vụ thiết kế & thi công trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Dự án thực tế tại Đà Nẵng</a></li>
                        <li><a href="#lien-he-map" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Sơ đồ chỉ đường đến xưởng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Tư vấn kích thước Phong Thủy</a></li>
                        <li><a href="#bao-gia-form" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Điều khoản & Chính sách bảo mật</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ Trợ Tư Vấn -->
                <div>
                    <h4 class="text-xs sm:text-sm font-bold uppercase text-amber-300 mb-3 pb-1.5 border-b border-brand-800">
                        Hỗ Trợ Tư Vấn
                    </h4>
                    <ul class="space-y-2 text-xs text-stone-300">
                        <li><a href="#bao-gia-form" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Tư vấn chất liệu gỗ miễn phí</a></li>
                        <li><a href="#bao-gia-form" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thiết kế bản vẽ 2D & 3D</a></li>
                        <li><a href="#bao-gia-form" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Báo giá thi công gốc tại xưởng</a></li>
                        <li><a href="#bao-gia-form" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Hỗ trợ bảo hành tận nhà</a></li>
                    </ul>

                    <h4 class="text-xs sm:text-sm font-bold uppercase text-amber-300 mt-4 mb-2">
                        Chính Sách Bảo Hành
                    </h4>
                    <p class="text-xs text-stone-300">
                        <i class="fa-solid fa-shield-heart text-amber-400 mr-1"></i> Thời gian bảo hành <strong>3 năm</strong>, bảo trì trọn đời sản phẩm.
                    </p>
                </div>

                <!-- Cột 4: Kết Nối Nhanh -->
                <div>
                    <h4 class="text-xs sm:text-sm font-bold uppercase text-amber-300 mb-3 pb-1.5 border-b border-brand-800">
                        Kết Nối Với Phương Anh
                    </h4>
                    <p class="text-xs text-stone-300 leading-relaxed mb-3">
                        Quý khách cần tư vấn đóng tủ bếp, nội thất phòng khách, phòng ngủ tại Đà Nẵng vui lòng liên hệ trực tiếp:
                    </p>
                    <div class="space-y-2">
                        <a href="tel:0905801976" class="flex items-center justify-center gap-2 w-full py-2 px-3 rounded bg-amber-500 hover:bg-amber-600 text-stone-950 font-extrabold text-xs transition">
                            <i class="fa-solid fa-phone-volume"></i> Gọi Ngay: 0905.80.1976
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=100078411751009" target="_blank" rel="noopener" class="flex items-center justify-center gap-2 w-full py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition">
                            <i class="fa-brands fa-facebook"></i> Fanpage Nội Thất Phương Anh
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-stone-400 gap-2 text-center sm:text-left">
                <p>Copyright 2026 © <strong>noithatphuonganh.com</strong> - Nội Thất Phương Anh Đà Nẵng.</p>
                <p>Địa chỉ: Lưu Quang Vũ - Hoà Quý - Đà Nẵng | Hotline: 0905.80.1976</p>
            </div>
        </div>
    </footer>

    <!-- =======================================================================
         CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
    ======================================================================== -->
    <div class="fixed bottom-4 right-3 sm:right-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a 
            href="https://www.facebook.com/profile.php?id=100078411751009" 
            target="_blank" 
            rel="noopener"
            aria-label="Chat Facebook Nội Thất Phương Anh"
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-sm shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a 
            href="https://zalo.me/0905801976" 
            target="_blank" 
            rel="noopener"
            aria-label="Chat Zalo 0905.80.1976"
            class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[10px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a 
            href="tel:0905801976" 
            aria-label="Gọi Hotline 0905.80.1976"
            class="float-btn-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white pl-3 pr-4 py-2 rounded-full shadow-xl transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <div class="leading-tight text-left">
                <span class="block text-[10px] text-red-100 font-medium">Hotline 24/7</span>
                <span class="block text-xs font-extrabold whitespace-nowrap">0905.80.1976</span>
            </div>
        </a>
    </div>

    <!-- =======================================================================
         JAVASCRIPT XỬ LÝ SLIDER 2 BANNER TỰ TRƯỢT, MENU MOBILE & FORM BÁO GIÁ
    ======================================================================== -->
    <script>
        // 1. Điều khiển 2 Banner tự trượt chuyên nghiệp
        let currentBannerIndex = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function renderBanner(index) {
            for (let i = 0; i < totalBanners; i++) {
                const slide = document.getElementById('bannerSlide' + i);
                const dot = document.getElementById('bannerDot' + i);
                if (!slide || !dot) continue;

                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
                    slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0', 'pointer-events-none');
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeBanner(step) {
            currentBannerIndex = (currentBannerIndex + step + totalBanners) % totalBanners;
            renderBanner(currentBannerIndex);
            restartBannerAutoSlide();
        }

        function goToBanner(index) {
            currentBannerIndex = index;
            renderBanner(currentBannerIndex);
            restartBannerAutoSlide();
        }

        function restartBannerAutoSlide() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(function () {
                currentBannerIndex = (currentBannerIndex + 1) % totalBanners;
                renderBanner(currentBannerIndex);
            }, 5000);
        }

        // 2. Đóng/Mở Menu Danh Mục trên Điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        // 3. Chọn sản phẩm cần báo giá và cuộn mượt xuống Form Báo Giá
        function selectProductForQuote(productName) {
            const noteField = document.getElementById('customerNote');
            const formSection = document.getElementById('bao-gia-form');
            if (noteField) {
                noteField.value = 'Tôi cần tư vấn và báo giá hạng mục: ' + productName;
            }
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 4. Xử lý gửi Form Yêu Cầu Báo Giá (Không dùng alert)
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('customerName').value.trim();
            const phone = document.getElementById('customerPhone').value.trim();
            const category = document.getElementById('customerCategory').value;
            const address = document.getElementById('customerAddress').value.trim() || 'Đà Nẵng';
            const successBox = document.getElementById('quoteSuccessBox');

            if (successBox) {
                successBox.classList.remove('hidden');
                successBox.innerHTML = '<strong><i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá!</strong> Cảm ơn <strong>' + name + '</strong> (' + phone + '). Bộ phận kỹ thuật <strong>Nội Thất Phương Anh</strong> sẽ liên hệ tư vấn hạng mục <em>"' + category + '"</em> tại khu vực <em>' + address + '</em> trong thời gian sớm nhất, hoặc quý khách có thể kết nối nhanh qua Hotline/Zalo: <strong>0905.80.1976</strong>.';
            }
            document.getElementById('quoteRequestForm').reset();
        }

        // 5. Tìm kiếm nhanh sản phẩm ngay trên trang chủ
        function filterProductsBySearch(keyword) {
            const q = (keyword || '').toLowerCase().trim();
            const cards = document.querySelectorAll('.product-item');
            cards.forEach(function (card) {
                const text = card.innerText.toLowerCase();
                if (!q || text.includes(q)) {
                    card.style.display = '';
                } else {
                    card.style.display = 'none';
                }
            });
        }

        window.onload = function () {
            restartBannerAutoSlide();
        };
    </script>
</body>
</html>
