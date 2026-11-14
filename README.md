<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS - Nguyên Liệu Thực Phẩm & Dụng Cụ Pha Chế</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS (khangphatfoods.com) - Chuyên cung cấp sỉ & lẻ nguyên liệu thực phẩm, nguyên liệu làm bánh, nguyên liệu & dụng cụ pha chế tại 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng. Hotline: 0898.311.667 - 0369.456.667.">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://khangphatfoods.com/">
    <meta property="og:site_name" content="khangphatfoods.com">
    <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS - Sỉ & Lẻ Nguyên Liệu Thực Phẩm, Dụng Cụ Pha Chế">
    <meta property="og:description" content="Chuyên cung cấp sỉ & lẻ nguyên liệu thực phẩm, nguyên liệu làm bánh, dụng cụ pha chế uy tín giá tốt. Đ/c: 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w1200">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Thương Mại Khang Phát Foods">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS - khangphatfoods.com">
    <meta name="twitter:description" content="Chuyên cung cấp sỉ & lẻ nguyên liệu thực phẩm, dụng cụ pha chế. Hotline: 0898.311.667 - 0369.456.667">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w256">
    <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w512">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            red: '#c81e1e',      /* Đỏ chủ đạo theo tông logo Khang Phát Foods & thực phẩm */
                            darkRed: '#9b1515',  /* Đỏ đậm thanh menu Flatsome */
                            orange: '#ea580c',   /* Cam điểm nhấn thực phẩm */
                            gold: '#f59e0b',     /* Vàng cam năng lượng */
                            green: '#15803d',    /* Xanh lá thực phẩm an toàn */
                            lightBg: '#fdf8f6'   /* Nền kem nhạt ấm áp */
                        }
                    }
                }
            }
        }
    </script>

    <!-- Trình xử lý tải ảnh Google Drive tự động chuyển đổi dự phòng mượt mà -->
    <script>
        function handleDriveImageError(img) {
            const fileId = img.getAttribute('data-drive-id');
            const step = parseInt(img.getAttribute('data-retry-step') || '0', 10);
            if (fileId && step === 0) {
                img.setAttribute('data-retry-step', '1');
                img.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
            } else if (fileId && step === 1) {
                img.setAttribute('data-retry-step', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                img.onerror = null;
                const fallbackTitle = encodeURIComponent(img.getAttribute('data-fallback-text') || 'Khang Phat Foods');
                img.src = 'https://placehold.co/600x600/fff5f5/c81e1e?text=' + fallbackTitle;
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8f9fa;
            color: #222;
            scroll-behavior: smooth;
        }

        /* Khung Container chuẩn 95% kích thước màn hình máy tính, trên điện thoại gọn gàng */
        .flatsome-container {
            width: 96%;
            max-width: 96%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95vw;
                margin-left: auto;
                margin-right: auto;
            }
        }

        /* Tên danh mục luôn viết liền trên 1 hàng, không bao giờ tự ngắt xuống dòng bên trong tên */
        .cat-nowrap {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .flatsome-section-header {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #c81e1e;
            margin-bottom: 1rem;
            background: #ffffff;
            border-radius: 8px 8px 0 0;
        }
        .flatsome-section-title {
            background: linear-gradient(135deg, #c81e1e 0%, #ea580c 100%);
            color: #ffffff;
            padding: 9px 18px;
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 0.3px;
            border-radius: 8px 18px 0 0;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            white-space: nowrap;
        }
        @media (min-width: 768px) {
            .flatsome-section-title {
                font-size: 15px;
                padding: 10px 22px;
            }
        }

        /* Thẻ sản phẩm Flatsome Box-Product */
        .flatsome-product-box {
            background: #ffffff;
            border: 1px solid #ececec;
            border-radius: 8px;
            transition: all 0.25s ease;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            height: 100%;
            position: relative;
            overflow: hidden;
        }
        .flatsome-product-box:hover {
            border-color: #c81e1e;
            box-shadow: 0 8px 20px rgba(200, 30, 30, 0.12);
            transform: translateY(-2px);
        }

        /* Vòng tròn giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-badge-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background: #c81e1e;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            min-width: 38px;
            height: 38px;
            padding: 0 6px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.22);
            line-height: 1;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt mất chữ, không tràn ra ngoài */
        .flatsome-product-title {
            font-size: 13px;
            line-height: 1.42;
            font-weight: 600;
            color: #1f2937;
            word-break: break-word;
            overflow-wrap: anywhere;
            white-space: normal;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .flatsome-product-title {
                font-size: 13.5px;
            }
        }
        .flatsome-product-box:hover .flatsome-product-title {
            color: #c81e1e;
        }

        /* Hiệu ứng rung nhẹ cho nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 30, 30, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 30, 30, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 30, 30, 0); }
        }
        .contact-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-[#f7f7f8] text-gray-800 antialiased">

    <!-- ===================================================================== -->
    <!-- TOP BAR FLATSOME (Đơn giản, không có thanh công cụ UX Builder)        -->
    <!-- ===================================================================== -->
    <div class="bg-[#9b1515] text-white text-[11.5px] md:text-xs py-1.5 border-b border-red-800">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <span class="inline-flex items-center gap-1 font-medium">
                    <i class="fa-solid fa-store text-amber-300"></i>
                    <span>CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS - Chuyên sỉ & lẻ nguyên liệu thực phẩm, dụng cụ pha chế</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 whitespace-nowrap text-red-100">
                <span><i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng</span>
                <span>|</span>
                <span><i class="fa-solid fa-globe text-amber-300 mr-1"></i>khangphatfoods.com</span>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- HEADER CHÍNH FLATSOME (Logo gọn nhỏ, không để nút gọi ngay tránh tràn)-->
    <!-- ===================================================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-gray-200">
        <div class="flatsome-container py-2.5 md:py-3">
            <div class="flex items-center justify-between gap-2 sm:gap-4">
                
                <!-- Nút mở Menu Danh mục trên Điện thoại -->
                <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-lg bg-red-50 text-[#c81e1e] border border-red-200 shrink-0">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo thu gọn nhỏ lại + Tên Công Ty -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 min-w-0">
                    <div class="w-10 h-10 md:w-12 md:h-12 rounded-lg border border-red-100 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-sm">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w400" 
                            data-drive-id="1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy"
                            data-fallback-text="LOGO+KHANG+PHAT"
                            onerror="handleDriveImageError(this)"
                            alt="Logo Khang Phát Foods" 
                            class="w-full h-full object-contain"
                        >
                    </div>
                    <div class="min-w-0">
                        <div class="text-[#c81e1e] font-extrabold text-xs sm:text-sm md:text-base leading-tight tracking-tight truncate">
                            KHANG PHÁT FOODS
                        </div>
                        <div class="text-[10px] sm:text-[11px] text-gray-500 font-medium leading-tight truncate max-w-[175px] sm:max-w-[260px] md:max-w-none">
                            Nguyên liệu thực phẩm & Dụng cụ pha chế
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm chuẩn Flatsome (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-2">
                    <form onsubmit="handleSearch(event)" class="w-full flex items-center border-2 border-[#c81e1e] rounded-full overflow-hidden bg-white">
                        <input 
                            id="desktopSearchInput"
                            type="text" 
                            placeholder="Tìm nguyên liệu pha chế, nguyên liệu làm bánh, dụng cụ..." 
                            class="w-full px-4 py-1.5 text-xs lg:text-sm text-gray-700 focus:outline-none"
                        >
                        <button type="submit" class="bg-[#c81e1e] hover:bg-[#9b1515] text-white px-4 py-2 text-xs lg:text-sm font-semibold transition shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </form>
                </div>

                <!-- Khu vực bên phải Header: Chỉ để Giỏ hàng & Tra cứu báo giá nhỏ gọn, KHÔNG để nút Gọi ngay để tránh tràn viền -->
                <div class="flex items-center gap-2 shrink-0">
                    <a href="#form-bao-gia" class="hidden xl:inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-amber-50 text-amber-800 border border-amber-200 text-xs font-semibold hover:bg-amber-100 transition whitespace-nowrap">
                        <i class="fa-solid fa-file-invoice-dollar text-[#ea580c]"></i>
                        <span>Báo giá sỉ</span>
                    </a>
                    <button type="button" onclick="openCartModal()" class="inline-flex items-center gap-1.5 px-2.5 sm:px-3 py-1.5 rounded-full bg-red-50 hover:bg-red-100 text-[#c81e1e] border border-red-200 text-xs font-bold transition shrink-0">
                        <i class="fa-solid fa-basket-shopping text-sm"></i>
                        <span class="hidden sm:inline">Giỏ hàng</span>
                        <span id="cartCountBadge" class="bg-[#c81e1e] text-white text-[10px] px-1.5 py-0.5 rounded-full">0</span>
                    </button>
                </div>
            </div>

            <!-- Thanh tìm kiếm gọn trên Điện thoại -->
            <div class="mt-2 md:hidden">
                <form onsubmit="handleSearchMobile(event)" class="w-full flex items-center border border-[#c81e1e] rounded-full overflow-hidden bg-gray-50">
                    <input 
                        id="mobileSearchInput"
                        type="text" 
                        placeholder="Tìm nguyên liệu làm bánh, đồ pha chế..." 
                        class="w-full px-3 py-1.5 text-xs bg-transparent focus:outline-none"
                    >
                    <button type="submit" class="bg-[#c81e1e] text-white px-3.5 py-1.5 text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>
        </div>

        <!-- ================================================================= -->
        <!-- THANH MENU DANH MỤC TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền 1 hàng,  -->
        <!-- tuyệt đối không xuống dòng bên trong tên danh mục)                -->
        <!-- ================================================================= -->
        <nav class="hidden lg:block bg-[#c81e1e] text-white border-t border-red-700">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center xl:justify-between gap-x-1 gap-y-1 py-1.5 text-[11px] xl:text-[12px] font-semibold">
                    <li>
                        <a href="#trang-chu" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition bg-[#9b1515]">
                            <i class="fa-solid fa-house mr-1 text-amber-300"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-nguyen-lieu-lam-banh" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            NGUYÊN LIỆU LÀM BÁNH
                        </a>
                    </li>
                    <li>
                        <a href="#sec-do-pha-che" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            ĐỒ PHA CHẾ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-dung-cu-pha-che" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            DỤNG CỤ PHA CHẾ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-dung-cu-lam-banh" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            DỤNG CỤ LÀM BÁNH
                        </a>
                    </li>
                    <li>
                        <a href="#sec-khuon-khay" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            KHUÔN, KHAY LÀM BÁNH
                        </a>
                    </li>
                    <li>
                        <a href="#sec-tui-hop-bao-bi" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            TÚI, HỘP, BAO BÌ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-trang-tri-banh-kem" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            TRANG TRÍ BÁNH KEM
                        </a>
                    </li>
                    <li>
                        <a href="#sec-do-trung-thu" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            ĐỒ TRUNG THU
                        </a>
                    </li>
                    <li>
                        <a href="#sec-vo-banh" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            VỎ BÁNH LÀM SẴN
                        </a>
                    </li>
                    <li>
                        <a href="#sec-bai-viet" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            TIN TỨC
                        </a>
                    </li>
                    <li>
                        <a href="#sec-lien-he" class="cat-nowrap px-2 py-1 rounded hover:bg-[#9b1515] transition">
                            LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ===================================================================== -->
    <!-- DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI (Rõ nét, dễ bấm)                 -->
    <!-- ===================================================================== -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/50 z-50 hidden"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[280px] max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="bg-[#c81e1e] text-white p-3.5 flex items-center justify-between">
            <div class="font-bold text-xs tracking-wide uppercase flex items-center gap-2">
                <i class="fa-solid fa-list-ul text-amber-300"></i>
                <span>DANH MỤC SẢN PHẨM</span>
            </div>
            <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded-full bg-white/15 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="p-3 overflow-y-auto flex-1 divide-y divide-gray-100 text-xs font-semibold text-gray-700">
            <a href="#sec-nguyen-lieu-lam-banh" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-wheat-awn text-[#c81e1e] w-5"></i>NGUYÊN LIỆU LÀM BÁNH</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-do-pha-che" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-mug-hot text-[#c81e1e] w-5"></i>ĐỒ PHA CHẾ</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-dung-cu-pha-che" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-martini-glass-citrus text-[#c81e1e] w-5"></i>DỤNG CỤ PHA CHẾ</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-dung-cu-lam-banh" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-kitchen-set text-[#c81e1e] w-5"></i>DỤNG CỤ LÀM BÁNH</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-khuon-khay" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-border-all text-[#c81e1e] w-5"></i>KHUÔN, KHAY LÀM BÁNH</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-tui-hop-bao-bi" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-box-open text-[#c81e1e] w-5"></i>TÚI, HỘP, BAO BÌ</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-trang-tri-banh-kem" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-cake-candles text-[#c81e1e] w-5"></i>TRANG TRÍ BÁNH KEM</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-do-trung-thu" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-moon text-[#c81e1e] w-5"></i>ĐỒ TRUNG THU</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-vo-banh" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-cookie-bite text-[#c81e1e] w-5"></i>VỎ BÁNH LÀM SẴN</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-file-signature text-[#c81e1e] w-5"></i>YÊU CẦU BÁO GIÁ SỈ & LẺ</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
            <a href="#sec-lien-he" onclick="toggleMobileMenu()" class="flex items-center justify-between py-2.5 hover:text-[#c81e1e]">
                <span><i class="fa-solid fa-map-location-dot text-[#c81e1e] w-5"></i>BẢN ĐỒ & LIÊN HỆ</span>
                <i class="fa-solid fa-angle-right text-gray-400"></i>
            </a>
        </div>
        <div class="p-3 bg-red-50 border-t border-red-100 text-[11px] text-gray-700">
            <div class="font-bold text-[#c81e1e]">HOTLINE KHANG PHÁT FOODS:</div>
            <div class="font-bold text-gray-900 mt-0.5">0898.311.667 - 0369.456.667</div>
            <div class="text-gray-500 mt-0.5">614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng</div>
        </div>
    </aside>

    <!-- ===================================================================== -->
    <!-- MAIN CONTENT (Chiều ngang 95% trên máy tính, không tràn viền)         -->
    <!-- ===================================================================== -->
    <main id="trang-chu" class="flatsome-container py-4 space-y-6">

        <!-- ================================================================= -->
        <!-- SLIDER 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU   -->
        <!-- Chữ & hình nằm trọn bên trong, cách xa viền, không bị thiếu chữ    -->
        <!-- ================================================================= -->
        <section aria-label="Banner chính" class="relative w-full rounded-xl overflow-hidden shadow-md border border-gray-200 bg-white">
            <!-- Khung cố định chiều cao bằng nhau tuyệt đối cho cả 2 Slide -->
            <div class="relative w-full h-[270px] sm:h-[320px] md:h-[370px] lg:h-[410px] overflow-hidden">

                <!-- SLIDE 1: TỔNG KHO NGUYÊN LIỆU THỰC PHẨM & LÀM BÁNH KHANG PHÁT FOODS -->
                <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-[#7f1d1d] via-[#991b1b] to-[#c2410c]">
                    <!-- Khoảng đệm rộng (px-7 sm:px-12 md:px-16 lg:px-20) giúp chữ cách xa viền banner tuyệt đối -->
                    <div class="w-full h-full px-7 py-5 sm:px-12 sm:py-7 md:px-16 lg:px-20 flex flex-col md:flex-row items-center justify-between gap-3 md:gap-8">
                        <!-- Khối chữ bên trong Banner 1 -->
                        <div class="w-full md:w-[58%] text-white flex flex-col justify-center text-center md:text-left">
                            <div class="inline-flex items-center self-center md:self-start gap-1.5 bg-amber-400/20 border border-amber-300/50 text-amber-200 text-[10px] sm:text-xs font-bold px-2.5 py-1 rounded-full mb-1.5 sm:mb-2.5">
                                <span>TỔNG KHO PHÂN PHỐI SỈ & LẺ UY TÍN ĐÀ NẴNG</span>
                            </div>
                            <h1 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug tracking-tight text-white drop-shadow">
                                CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS
                            </h1>
                            <p class="text-[11px] sm:text-xs md:text-sm text-amber-100 font-medium mt-1.5 sm:mt-2 leading-relaxed">
                                Chuyên cung cấp sỉ & lẻ nguyên liệu thực phẩm, nguyên liệu làm bánh, dụng cụ pha chế chính hãng. Giá sỉ tận gốc cho quán Cafe, Trà sữa, Tiệm bánh & Nhà hàng.
                            </p>
                            <div class="mt-2.5 sm:mt-4 flex flex-wrap items-center justify-center md:justify-start gap-2 text-[10.5px] sm:text-xs">
                                <span class="bg-white text-[#991b1b] font-bold px-3 py-1.5 rounded-full shadow">
                                    <i class="fa-solid fa-phone-volume mr-1"></i>0898.311.667 - 0369.456.667
                                </span>
                                <span class="bg-black/25 border border-white/30 text-white px-3 py-1.5 rounded-full">
                                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng
                                </span>
                            </div>
                        </div>
                        <!-- Khối hình ảnh thực tế nằm gọn bên trong Banner 1 -->
                        <div class="hidden sm:flex w-full md:w-[40%] h-[110px] sm:h-[170px] md:h-[270px] lg:h-[310px] items-center justify-center gap-2.5">
                            <div class="w-1/2 h-full rounded-xl overflow-hidden border-2 border-amber-300/70 shadow-lg bg-white p-1">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1UzxPagzh40VJs0LN5vB-EYDgV_hFMywm&sz=w800"
                                    data-drive-id="1UzxPagzh40VJs0LN5vB-EYDgV_hFMywm"
                                    data-fallback-text="Khang+Phat+Foods"
                                    onerror="handleDriveImageError(this)"
                                    alt="Ảnh Công Ty Khang Phát Foods" 
                                    class="w-full h-full object-cover rounded-lg"
                                >
                            </div>
                            <div class="w-1/2 h-full flex flex-col gap-2">
                                <div class="w-full h-1/2 rounded-xl overflow-hidden border-2 border-white/60 shadow bg-white p-1">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2&sz=w600"
                                        data-drive-id="1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2"
                                        data-fallback-text="Nguyen+Lieu+Thuc+Pham"
                                        onerror="handleDriveImageError(this)"
                                        alt="Nguyên liệu thực phẩm Khang Phát" 
                                        class="w-full h-full object-cover rounded-lg"
                                    >
                                </div>
                                <div class="w-full h-1/2 rounded-xl overflow-hidden border-2 border-white/60 shadow bg-white p-1">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=15FSRIU72HOYJPybdIZItH_N_KkU7MXTT&sz=w600"
                                        data-drive-id="15FSRIU72HOYJPybdIZItH_N_KkU7MXTT"
                                        data-fallback-text="Dung+Cu+Pha+Che"
                                        onerror="handleDriveImageError(this)"
                                        alt="Dụng cụ pha chế Khang Phát" 
                                        class="w-full h-full object-cover rounded-lg"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2: NGUYÊN LIỆU & DỤNG CỤ PHA CHẾ - LÀM BÁNH ĐẦY ĐỦ CHÍNH HÃNG -->
                <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-[#0f5132] via-[#15803d] to-[#b45309]">
                    <!-- Khoảng đệm rộng (px-7 sm:px-12 md:px-16 lg:px-20) giúp chữ cách xa viền banner tuyệt đối -->
                    <div class="w-full h-full px-7 py-5 sm:px-12 sm:py-7 md:px-16 lg:px-20 flex flex-col md:flex-row items-center justify-between gap-3 md:gap-8">
                        <!-- Khối chữ bên trong Banner 2 -->
                        <div class="w-full md:w-[58%] text-white flex flex-col justify-center text-center md:text-left">
                            <div class="inline-flex items-center self-center md:self-start gap-1.5 bg-white/15 border border-white/30 text-amber-200 text-[10px] sm:text-xs font-bold px-2.5 py-1 rounded-full mb-1.5 sm:mb-2.5">
                                <span>ĐỐI TÁC TIN CẬY CỦA QUÁN CAFE, TRÀ SỮA & TIỆM BÁNH</span>
                            </div>
                            <h2 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug tracking-tight text-white drop-shadow">
                                NGUYÊN LIỆU PHA CHẾ, LÀM BÁNH & BAO BÌ TRỌN GÓI
                            </h2>
                            <p class="text-[11px] sm:text-xs md:text-sm text-emerald-50 font-medium mt-1.5 sm:mt-2 leading-relaxed">
                                Đầy đủ Bơ, Phô mai, Kem tươi, Trà, Siro, Mứt trái cây, Trân châu, Bột sữa, Bình lắc Shaker, Khuôn khay & Ly hộp bao bì. Giao hàng nhanh tận nơi mỗi ngày!
                            </p>
                            <div class="mt-2.5 sm:mt-4 flex flex-wrap items-center justify-center md:justify-start gap-2 text-[10.5px] sm:text-xs">
                                <span class="bg-amber-400 text-gray-900 font-bold px-3 py-1.5 rounded-full shadow">
                                    <i class="fa-solid fa-truck-fast mr-1"></i>Giao nhanh Đà Nẵng - Quảng Nam
                                </span>
                                <span class="bg-black/25 border border-white/30 text-white px-3 py-1.5 rounded-full">
                                    <i class="fa-solid fa-globe text-amber-300 mr-1"></i>Website: khangphatfoods.com
                                </span>
                            </div>
                        </div>
                        <!-- Khối hình ảnh thực tế nằm gọn bên trong Banner 2 -->
                        <div class="hidden sm:flex w-full md:w-[40%] h-[110px] sm:h-[170px] md:h-[270px] lg:h-[310px] items-center justify-center gap-2.5">
                            <div class="w-1/2 h-full rounded-xl overflow-hidden border-2 border-amber-300/70 shadow-lg bg-white p-1">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1xqu7JF4vzn58QQ0wI_XmWBXH6UTeAlrv&sz=w800"
                                    data-drive-id="1xqu7JF4vzn58QQ0wI_XmWBXH6UTeAlrv"
                                    data-fallback-text="Do+Pha+Che"
                                    onerror="handleDriveImageError(this)"
                                    alt="Nguyên liệu pha chế Khang Phát" 
                                    class="w-full h-full object-cover rounded-lg"
                                >
                            </div>
                            <div class="w-1/2 h-full flex flex-col gap-2">
                                <div class="w-full h-1/2 rounded-xl overflow-hidden border-2 border-white/60 shadow bg-white p-1">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1P2RVYcWUsU8Qc5A-Kpv9F_4wpUYQ7_Zg&sz=w600"
                                        data-drive-id="1P2RVYcWUsU8Qc5A-Kpv9F_4wpUYQ7_Zg"
                                        data-fallback-text="Banh+Kem+Bo+Sua"
                                        onerror="handleDriveImageError(this)"
                                        alt="Nguyên liệu làm bánh Khang Phát" 
                                        class="w-full h-full object-cover rounded-lg"
                                    >
                                </div>
                                <div class="w-full h-1/2 rounded-xl overflow-hidden border-2 border-white/60 shadow bg-white p-1">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=15MEBT33BUV0yXW0JCm62FtTLO24U07V_&sz=w600"
                                        data-drive-id="15MEBT33BUV0yXW0JCm62FtTLO24U07V_"
                                        data-fallback-text="Siro+Mut+Tra"
                                        onerror="handleDriveImageError(this)"
                                        alt="Thực phẩm & Gia vị Khang Phát" 
                                        class="w-full h-full object-cover rounded-lg"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng qua lại giữa 2 Banner -->
                <button type="button" onclick="prevBanner()" aria-label="Banner trước" class="absolute left-1.5 sm:left-2.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="nextBanner()" aria-label="Banner tiếp theo" class="absolute right-1.5 sm:right-2.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chuyển Slide -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBanner(0)" id="bannerDot0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="goToBanner(1)" id="bannerDot1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- DANH MỤC SẢN PHẨM TRANG CHỦ (Giống mẫu dolambanhsana.com,         -->
        <!-- chữ danh mục nhỏ gọn, viết liền trên 1 hàng không bị xuống dòng)  -->
        <!-- ================================================================= -->
        <section aria-label="Danh mục sản phẩm" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flex items-center justify-between mb-3 pb-2 border-b border-gray-100">
                <h2 class="text-xs sm:text-sm font-extrabold uppercase text-[#c81e1e] flex items-center gap-2">
                    <i class="fa-solid fa-layer-group"></i>
                    <span>DANH MỤC SẢN PHẨM</span>
                </h2>
                <span class="text-[11px] text-gray-500 hidden sm:inline">Chọn nhanh danh mục nguyên liệu & dụng cụ</span>
            </div>

            <!-- Lưới danh mục tối ưu cho cả Máy tính (9 cột trên 1 hàng hoặc 5+4) và Điện thoại (2-3 cột chữ gọn) -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 lg:grid-cols-9 gap-2">
                <a href="#sec-nguyen-lieu-lam-banh" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-cheese text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">NGUYÊN LIỆU LÀM BÁNH</span>
                </a>

                <a href="#sec-do-pha-che" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-mug-hot text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">ĐỒ PHA CHẾ</span>
                </a>

                <a href="#sec-dung-cu-pha-che" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-martini-glass-citrus text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">DỤNG CỤ PHA CHẾ</span>
                </a>

                <a href="#sec-dung-cu-lam-banh" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-kitchen-set text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">DỤNG CỤ LÀM BÁNH</span>
                </a>

                <a href="#sec-khuon-khay" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-border-all text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">KHUÔN, KHAY BÁNH</span>
                </a>

                <a href="#sec-tui-hop-bao-bi" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-box-open text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">TÚI, HỘP, BAO BÌ</span>
                </a>

                <a href="#sec-trang-tri-banh-kem" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-cake-candles text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">TRANG TRÍ BÁNH KEM</span>
                </a>

                <a href="#sec-do-trung-thu" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-moon text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">ĐỒ TRUNG THU</span>
                </a>

                <a href="#sec-vo-banh" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-red-50/60 hover:bg-[#c81e1e] border border-red-100 transition text-center col-span-2 sm:col-span-1">
                    <div class="w-9 h-9 rounded-full bg-white text-[#c81e1e] flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-cookie text-sm"></i>
                    </div>
                    <span class="cat-nowrap text-[11px] font-bold text-gray-800 group-hover:text-white">VỎ BÁNH LÀM SẴN</span>
                </a>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- KHỐI 1: ĐỒ PHA CHẾ & NGUYÊN LIỆU THỰC PHẨM THỰC TẾ TẠI KHO        -->
        <!-- (Tích hợp bộ 12 ảnh sản phẩm thực tế từ Google Drive của khách)   -->
        <!-- Điện thoại chia 2 cột, tên đầy đủ không mất chữ, giảm giá góc trái-->
        <!-- ================================================================= -->
        <section id="sec-do-pha-che" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flatsome-section-header">
                <h2 class="flatsome-section-title">
                    <i class="fa-solid fa-mug-hot"></i>
                    <span>ĐỒ PHA CHẾ & NGUYÊN LIỆU THỰC PHẨM</span>
                </h2>
                <div class="flex flex-wrap items-center gap-1.5 px-2 py-1.5 text-[11px] font-semibold text-gray-600">
                    <span class="cat-nowrap px-2 py-0.5 rounded bg-red-50 text-[#c81e1e]">Bột kem, bột sữa</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Trà & Cà phê</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Siro / Syrup</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Mứt & Sinh tố</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Trân châu / Topping</span>
                </div>
            </div>

            <!-- Grid 2 cột trên Điện thoại (grid-cols-2), 4 cột trên Máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

                <!-- Ảnh thực tế 1: 1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-15%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2&sz=w700"
                                data-drive-id="1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2"
                                data-fallback-text="Kem+Pha+Che+Topping"
                                onerror="handleDriveImageError(this)"
                                alt="Kem Béo Pha Chế & Topping Cream Thực Phẩm Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Đồ pha chế</div>
                        <h3 class="flatsome-product-title">
                            Kem Béo Pha Chế & Topping Cream Chuyên Dụng Cho Quán (Hộp Chính Hãng)
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">88.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">75.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Kem Béo Pha Chế & Topping Cream Chuyên Dụng', 75000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 2: 15FSRIU72HOYJPybdIZItH_N_KkU7MXTT -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-18%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=15FSRIU72HOYJPybdIZItH_N_KkU7MXTT&sz=w700"
                                data-drive-id="15FSRIU72HOYJPybdIZItH_N_KkU7MXTT"
                                data-fallback-text="Bot+Kem+Beo+Pha+Che"
                                onerror="handleDriveImageError(this)"
                                alt="Bột Kem Béo Thực Vật Pha Trà Sữa Đậm Vị Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Bột kem, bột sữa</div>
                        <h3 class="flatsome-product-title">
                            Bột Kem Béo Thực Vật Pha Trà Sữa Đậm Đà Thơm Béo (Gói 1Kg - Bao Sỉ)
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">79.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">65.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Bột Kem Béo Thực Vật Pha Trà Sữa (1Kg)', 65000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 3: 1xqu7JF4vzn58QQ0wI_XmWBXH6UTeAlrv -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-14%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1xqu7JF4vzn58QQ0wI_XmWBXH6UTeAlrv&sz=w700"
                                data-drive-id="1xqu7JF4vzn58QQ0wI_XmWBXH6UTeAlrv"
                                data-fallback-text="Mut+Sinh+To+Trai+Cay"
                                onerror="handleDriveImageError(this)"
                                alt="Mứt Trái Cây & Sinh Tố Pha Chế Đồ Uống Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Sinh tố & Mứt</div>
                        <h3 class="flatsome-product-title">
                            Mứt Trái Cây Tươi & Sinh Tố Pha Chế Trà Trái Cây Nhiệt Đới Đủ Vị
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">99.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">85.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Mứt Trái Cây Tươi & Sinh Tố Pha Chế', 85000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 4: 1P2RVYcWUsU8Qc5A-Kpv9F_4wpUYQ7_Zg -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-16%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1P2RVYcWUsU8Qc5A-Kpv9F_4wpUYQ7_Zg&sz=w700"
                                data-drive-id="1P2RVYcWUsU8Qc5A-Kpv9F_4wpUYQ7_Zg"
                                data-fallback-text="Siro+Syrup+Pha+Che"
                                onerror="handleDriveImageError(this)"
                                alt="Siro Hương Trái Cây Pha Chế Soda & Trà Hoa Quả Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Siro / Syrup</div>
                        <h3 class="flatsome-product-title">
                            Siro Hương Trái Cây Cao Cấp Pha Chế Trà Đào, Trà Vải & Soda Ý
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">130.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">109.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Siro Hương Trái Cây Cao Cấp Pha Chế', 109000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 5: 15MEBT33BUV0yXW0JCm62FtTLO24U07V_ -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-15%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=15MEBT33BUV0yXW0JCm62FtTLO24U07V_&sz=w700"
                                data-drive-id="15MEBT33BUV0yXW0JCm62FtTLO24U07V_"
                                data-fallback-text="Hong+Tra+Luc+Tra+Olong"
                                onerror="handleDriveImageError(this)"
                                alt="Hồng Trà, Lục Trà Nhài & Trà Ô Long Pha Chế Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Trà pha chế</div>
                        <h3 class="flatsome-product-title">
                            Hồng Trà Đặc Biệt, Lục Trà Lài & Trà Ô Long Thượng Hạng Chuyên Quán
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">115.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">98.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Hồng Trà, Lục Trà Lài & Trà Ô Long Pha Chế', 98000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 6: 1j2bbnhWNJACPb6-Xuph3MeQlgYo6LTtM -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-20%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1j2bbnhWNJACPb6-Xuph3MeQlgYo6LTtM&sz=w700"
                                data-drive-id="1j2bbnhWNJACPb6-Xuph3MeQlgYo6LTtM"
                                data-fallback-text="Tran+Chau+Topping+Thach"
                                onerror="handleDriveImageError(this)"
                                alt="Trân Châu Hoàng Kim, Trân Châu Đen & Thạch Topping Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Trân châu / Topping</div>
                        <h3 class="flatsome-product-title">
                            Trân Châu Đen, Trân Châu Hoàng Kim & Thạch Trái Cây Topping Trà Sữa
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">65.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">52.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Trân Châu Hoàng Kim & Thạch Topping Trà Sữa', 52000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 7: 1bd9BNY47SxWAldgcWGfzEjYwaPGH74O9 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-12%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1bd9BNY47SxWAldgcWGfzEjYwaPGH74O9&sz=w700"
                                data-drive-id="1bd9BNY47SxWAldgcWGfzEjYwaPGH74O9"
                                data-fallback-text="Bot+Cacao+Matcha+Pudding"
                                onerror="handleDriveImageError(this)"
                                alt="Bột Matcha Trà Xanh, Bột Cacao Nguyên Chất & Bột Pudding" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Bột Cacao, Matcha, Pudding</div>
                        <h3 class="flatsome-product-title">
                            Bột Matcha Trà Xanh, Bột Cacao Đậm Vị & Bột Làm Bánh Flan Pudding
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">145.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">128.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Bột Matcha Trà Xanh & Bột Cacao Pha Chế', 128000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 8: 1UiECYFLCKAU1H9asK5umH-GxXW0I6Cb7 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-15%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1UiECYFLCKAU1H9asK5umH-GxXW0I6Cb7&sz=w700"
                                data-drive-id="1UiECYFLCKAU1H9asK5umH-GxXW0I6Cb7"
                                data-fallback-text="Trai+Cay+Dong+Hop+Dao+Vai"
                                onerror="handleDriveImageError(this)"
                                alt="Đào Ngâm, Vải Ngâm & Trái Cây Đóng Hộp Pha Chế Khang Phát" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Trái cây đóng hộp</div>
                        <h3 class="flatsome-product-title">
                            Đào Ngâm Giòn, Vải Ngâm Đóng Lon & Trái Cây Nhiệt Đới Pha Chế
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">68.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">58.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Đào Ngâm & Vải Ngâm Đóng Hộp Pha Chế', 58000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

            </div>
        </section>

        <!-- ================================================================= -->
        <!-- KHỐI 2: NGUYÊN LIỆU LÀM BÁNH & DỤNG CỤ PHA CHẾ (Tích hợp tiếp     -->
        <!-- các ảnh sản phẩm thực tế 9, 10, 11, 12 từ Google Drive + mẫu SANA)-->
        <!-- ================================================================= -->
        <section id="sec-nguyen-lieu-lam-banh" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flatsome-section-header">
                <h2 class="flatsome-section-title">
                    <i class="fa-solid fa-bread-slice"></i>
                    <span>NGUYÊN LIỆU LÀM BÁNH & DỤNG CỤ PHA CHẾ</span>
                </h2>
                <div class="flex flex-wrap items-center gap-1.5 px-2 py-1.5 text-[11px] font-semibold text-gray-600">
                    <span class="cat-nowrap px-2 py-0.5 rounded bg-red-50 text-[#c81e1e]">Bơ, Kem, Phô mai</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Bột làm bánh</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Socola & Phụ gia</span>
                    <span class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Bình lắc Shaker & Dụng cụ</span>
                </div>
            </div>

            <!-- Grid 2 cột trên Điện thoại, 4 cột trên Máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

                <!-- Ảnh thực tế 9: 1WMuElizcZTvnAmy1ZXu_bxcMaSm3WtS8 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-15%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1WMuElizcZTvnAmy1ZXu_bxcMaSm3WtS8&sz=w700"
                                data-drive-id="1WMuElizcZTvnAmy1ZXu_bxcMaSm3WtS8"
                                data-fallback-text="Bo+Lat+Pho+Mai+Whipping"
                                onerror="handleDriveImageError(this)"
                                alt="Bơ Lạt, Phô Mai Mozzarella & Kem Whipping Cream Làm Bánh" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Bơ, Kem, Phô mai</div>
                        <h3 class="flatsome-product-title">
                            Bơ Lạt Làm Bánh, Phô Mai Kéo Sợi & Kem Tươi Whipping Cream Nhập Khẩu
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">185.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">158.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Bơ Lạt, Phô Mai & Kem Whipping Cream', 158000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 10: 1Y5PFq4hdHyGs7ZGvHtpq06YqQ5QfDmKa -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-17%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1Y5PFq4hdHyGs7ZGvHtpq06YqQ5QfDmKa&sz=w700"
                                data-drive-id="1Y5PFq4hdHyGs7ZGvHtpq06YqQ5QfDmKa"
                                data-fallback-text="Bot+Lam+Banh+Socola"
                                onerror="handleDriveImageError(this)"
                                alt="Bột Làm Bánh Cơ Bản, Bột Trộn Sẵn & Socola Nguyên Chất" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Bột làm bánh & Socola</div>
                        <h3 class="flatsome-product-title">
                            Bột Làm Bánh Mì, Bánh Kem, Bột Trộn Sẵn & Socola Nút Nguyên Chất
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">92.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">76.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Bột Làm Bánh & Socola Nút Nguyên Chất', 76000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 11: 1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN -->
                <article id="sec-dung-cu-pha-che" class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-20%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN&sz=w700"
                                data-drive-id="1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN"
                                data-fallback-text="Binh+Lac+Shaker+Dung+Cu"
                                onerror="handleDriveImageError(this)"
                                alt="Bộ Bình Lắc Shaker, Bình Xịt Kem, Ca Đong & Dụng Cụ Pha Chế" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Dụng cụ pha chế</div>
                        <h3 class="flatsome-product-title">
                            Bộ Bình Lắc Shaker Inox, Bình Xịt Kem Tươi, Ly Đong Jigger & Muỗng Khuấy
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">110.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">88.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Bộ Bình Lắc Shaker & Dụng Cụ Đong Pha Chế', 88000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- Ảnh thực tế 12: 1CBuS2I7KWUp0-6FSdfJ7j_9NjsVK8R24 -->
                <article id="sec-dung-cu-lam-banh" class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-16%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1CBuS2I7KWUp0-6FSdfJ7j_9NjsVK8R24&sz=w700"
                                data-drive-id="1CBuS2I7KWUp0-6FSdfJ7j_9NjsVK8R24"
                                data-fallback-text="Khuon+Khay+Tui+Hop+Bao+Bi"
                                onerror="handleDriveImageError(this)"
                                alt="Khuôn Khay Nướng Bánh, Ly Nhựa, Hộp Đựng Bánh & Bao Bì Thực Phẩm" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Dụng cụ, Khuôn & Bao bì</div>
                        <h3 class="flatsome-product-title">
                            Khuôn Khay Làm Bánh Chống Dính, Phới Silicon & Ly Hộp Bao Bì Đựng Bánh
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">65.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">55.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Khuôn Khay Làm Bánh & Ly Hộp Bao Bì', 55000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

            </div>
        </section>

        <!-- ================================================================= -->
        <!-- KHỐI 3: KHUÔN KHAY, TÚI HỘP BAO BÌ, TRANG TRÍ BÁNH & ĐỒ TRUNG THU -->
        <!-- (Các danh mục chuẩn theo mẫu dolambanhsana.com)                   -->
        <!-- ================================================================= -->
        <section id="sec-khuon-khay" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flatsome-section-header">
                <h2 class="flatsome-section-title">
                    <i class="fa-solid fa-box-open"></i>
                    <span>KHUÔN KHAY, BAO BÌ, TRANG TRÍ BÁNH & VỎ BÁNH</span>
                </h2>
                <div class="flex flex-wrap items-center gap-1.5 px-2 py-1.5 text-[11px] font-semibold text-gray-600">
                    <span id="sec-tui-hop-bao-bi" class="cat-nowrap px-2 py-0.5 rounded bg-red-50 text-[#c81e1e]">Túi, Hộp, Bao bì</span>
                    <span id="sec-trang-tri-banh-kem" class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Trang trí bánh kem</span>
                    <span id="sec-do-trung-thu" class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Đồ Trung Thu</span>
                    <span id="sec-vo-banh" class="cat-nowrap px-2 py-0.5 rounded hover:bg-gray-100">Vỏ bánh làm sẵn</span>
                </div>
            </div>

            <!-- Grid 2 cột trên Điện thoại, 4 cột trên Máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- SP 1 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-15%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2&sz=w600"
                                data-drive-id="1FaygO3vL8DaqYo8VAYJkyy5gxfoQ2Mj2"
                                data-fallback-text="Kem+Cooking+Anchor"
                                onerror="handleDriveImageError(this)"
                                alt="Kem Nấu Cooking Cream & Kem Trang Trí Bánh Creamy Whip" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Nguyên liệu làm bánh</div>
                        <h3 class="flatsome-product-title">
                            Kem Trang Trí Bánh Creamy Whip Ngà 1Kg & Kem Nấu Cooking Cream
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">85.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">72.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Kem Trang Trí Bánh Creamy Whip Ngà 1Kg', 72000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- SP 2 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-19%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1CBuS2I7KWUp0-6FSdfJ7j_9NjsVK8R24&sz=w600"
                                data-drive-id="1CBuS2I7KWUp0-6FSdfJ7j_9NjsVK8R24"
                                data-fallback-text="Ly+Nhua+Hop+Banh"
                                onerror="handleDriveImageError(this)"
                                alt="Hộp Nhựa, Hộp Giấy Kraft, Hộp Mica & Ly Nhựa Đựng Bánh Lạnh" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Túi, hộp, bao bì</div>
                        <h3 class="flatsome-product-title">
                            Hộp Bánh Kem, Hộp Giấy Kraft, Cuộn Mica Quấn Bánh & Ly Nhựa Pha Chế
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">42.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">34.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Combo Hộp Đựng Bánh & Ly Nhựa Pha Chế', 34000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- SP 3 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-14%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1Y5PFq4hdHyGs7ZGvHtpq06YqQ5QfDmKa&sz=w600"
                                data-drive-id="1Y5PFq4hdHyGs7ZGvHtpq06YqQ5QfDmKa"
                                data-fallback-text="De+Banh+Tart+Thuyen"
                                onerror="handleDriveImageError(this)"
                                alt="Vỏ Bánh Tart Trứng, Đế Bánh Thuyền, Đế Pizza & Nhân Bánh Trung Thu" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Vỏ bánh & Đồ Trung Thu</div>
                        <h3 class="flatsome-product-title">
                            Đế Bánh Thuyền Hạnh Nhân, Vỏ Bánh Tart Làm Sẵn & Nguyên Liệu Trung Thu
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">52.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">45.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Đế Bánh Thuyền & Vỏ Bánh Tart Làm Sẵn', 45000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>

                <!-- SP 4 -->
                <article class="flatsome-product-box p-2.5 sm:p-3">
                    <span class="flatsome-badge-sale">-18%</span>
                    <div>
                        <div class="aspect-square w-full rounded-lg overflow-hidden bg-gray-50 mb-2.5 border border-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN&sz=w600"
                                data-drive-id="1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN"
                                data-fallback-text="Phu+Kien+Trang+Tri+Banh"
                                onerror="handleDriveImageError(this)"
                                alt="Set Cắm Giấy Trang Trí Bánh Kem, Đui Bắt Kem & Bàn Xoay Làm Bánh" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="text-[10.5px] text-gray-400 font-medium mb-0.5">Trang trí bánh kem</div>
                        <h3 class="flatsome-product-title">
                            Set Cắm Trang Trí Bánh Kem Sinh Nhật, Bộ Đui Bắt Kem Hoa Tulip & Dao Chà Láng
                        </h3>
                    </div>
                    <div class="pt-2 border-t border-gray-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-1.5">
                            <del class="text-[11px] text-gray-400">55.000₫</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-[#c81e1e] no-underline">45.000₫</ins>
                        </div>
                        <button type="button" onclick="addToCart('Set Trang Trí Bánh Kem & Bộ Đui Bắt Kem', 45000)" class="mt-2 w-full py-1.5 px-2 rounded bg-red-50 hover:bg-[#c81e1e] text-[#c81e1e] hover:text-white text-[11px] sm:text-xs font-bold transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i>Thêm vào giỏ
                        </button>
                    </div>
                </article>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- GIỚI THIỆU CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS + ẢNH CÔNG TY -->
        <!-- ================================================================= -->
        <section class="bg-white rounded-xl p-4 sm:p-5 shadow-sm border border-gray-200">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-red-100 shadow-sm bg-gray-50 aspect-[16/10]">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1UzxPagzh40VJs0LN5vB-EYDgV_hFMywm&sz=w1000"
                            data-drive-id="1UzxPagzh40VJs0LN5vB-EYDgV_hFMywm"
                            data-fallback-text="CONG+TY+KHANG+PHAT+FOODS"
                            onerror="handleDriveImageError(this)"
                            alt="Hình ảnh thực tế Công Ty TNHH Thương Mại Khang Phát Foods" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                </div>
                <div class="lg:col-span-7 space-y-2.5">
                    <div class="text-xs font-bold uppercase text-[#ea580c] tracking-wider">VỀ CHÚNG TÔI - KHANGPHATFOODS.COM</div>
                    <h2 class="text-base sm:text-xl font-extrabold text-[#c81e1e]">
                        CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-700 leading-relaxed">
                        <strong>CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS</strong> tự hào là đơn vị chuyên cung cấp sỉ & lẻ nguyên liệu thực phẩm, nguyên liệu làm bánh, nguyên liệu pha chế và dụng cụ pha chế uy tín tại Đà Nẵng & khu vực miền Trung. Chúng tôi cung ứng trọn gói nguồn hàng chính hãng, rõ nguồn gốc xuất xứ với mức chiết khấu tốt nhất cho các quán Cafe, Trà sữa, Tiệm bánh, Nhà hàng và đại lý.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 pt-1 text-xs">
                        <div class="flex items-center gap-2 bg-red-50/70 p-2 rounded-lg border border-red-100">
                            <i class="fa-solid fa-circle-check text-[#c81e1e]"></i>
                            <span><strong>Hàng chính hãng 100%:</strong> Đảm bảo VSATTP</span>
                        </div>
                        <div class="flex items-center gap-2 bg-red-50/70 p-2 rounded-lg border border-red-100">
                            <i class="fa-solid fa-tags text-[#c81e1e]"></i>
                            <span><strong>Giá sỉ cạnh tranh:</strong> Hỗ trợ chủ quán tối đa</span>
                        </div>
                        <div class="flex items-center gap-2 bg-red-50/70 p-2 rounded-lg border border-red-100">
                            <i class="fa-solid fa-truck-fast text-[#c81e1e]"></i>
                            <span><strong>Giao hàng nhanh:</strong> Điện Bàn - Đà Nẵng - Quảng Nam</span>
                        </div>
                        <div class="flex items-center gap-2 bg-red-50/70 p-2 rounded-lg border border-red-100">
                            <i class="fa-solid fa-headset text-[#c81e1e]"></i>
                            <span><strong>Tư vấn tận tâm:</strong> 0898.311.667 - 0369.456.667</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- FORM YÊU CẦU VÀ BÁO GIÁ SỈ & LẺ TRANG CHỦ                         -->
        <!-- ================================================================= -->
        <section id="form-bao-gia" class="bg-gradient-to-br from-[#9b1515] via-[#c81e1e] to-[#c2410c] rounded-xl p-4 sm:p-6 shadow-md text-white">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                <div class="lg:col-span-5 space-y-2.5">
                    <span class="inline-block bg-amber-400 text-gray-900 text-[11px] font-extrabold px-3 py-1 rounded-full uppercase">
                        Dành cho Quán Cafe, Trà Sữa, Tiệm Bánh & Đại Lý
                    </span>
                    <h2 class="text-base sm:text-xl font-extrabold leading-snug">
                        ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BẢNG BÁO GIÁ SỈ - LẺ
                    </h2>
                    <p class="text-xs sm:text-sm text-red-100 leading-relaxed">
                        Quý khách cần báo giá sỉ nguyên liệu thực phẩm, nguyên liệu làm bánh hoặc trọn bộ dụng cụ mở quán pha chế? Hãy để lại thông tin, bộ phận kinh doanh Khang Phát Foods sẽ gửi bảng giá ưu đãi ngay!
                    </p>
                    <div class="pt-1 space-y-1.5 text-xs text-amber-200 font-semibold">
                        <div><i class="fa-solid fa-phone mr-2"></i>Hotline trực tiếp: 0898.311.667 - 0369.456.667</div>
                        <div><i class="fa-solid fa-location-dot mr-2"></i>Đ/c: 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng</div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form onsubmit="submitQuoteForm(event)" class="bg-white text-gray-800 rounded-xl p-4 sm:p-5 shadow-lg space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Họ và tên khách hàng / Tên quán *</label>
                                <input type="text" id="quoteName" required placeholder="VD: Anh Minh - Cafe Minh Khang" class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-[#c81e1e]">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
                                <input type="tel" id="quotePhone" required placeholder="VD: 0905xxxxxx" class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-[#c81e1e]">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Danh mục cần báo giá</label>
                                <select id="quoteCategory" class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-[#c81e1e] bg-white">
                                    <option value="Nguyên liệu pha chế tổng hợp">Nguyên liệu pha chế tổng hợp (Trà, Siro, Bột sữa...)</option>
                                    <option value="Nguyên liệu làm bánh">Nguyên liệu làm bánh (Bơ, Phô mai, Kem, Bột...)</option>
                                    <option value="Dụng cụ pha chế & làm bánh">Dụng cụ pha chế & Dụng cụ làm bánh</option>
                                    <option value="Túi, hộp, ly nhựa, bao bì">Túi, hộp, ly nhựa, bao bì thực phẩm</option>
                                    <option value="Báo giá sỉ toàn bộ danh mục">Báo giá sỉ toàn bộ sản phẩm mở quán mới</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Hình thức mua hàng</label>
                                <select id="quoteType" class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-[#c81e1e] bg-white">
                                    <option value="Mua sỉ cho quán / đại lý">Mua sỉ định kỳ cho Quán / Tiệm bánh / Đại lý</option>
                                    <option value="Combo mở quán mới">Tư vấn trọn gói mở quán mới</option>
                                    <option value="Mua lẻ gia đình">Mua lẻ sử dụng gia đình</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-gray-700 mb-1">Nội dung yêu cầu chi tiết (Tên mặt hàng, số lượng dự kiến...)</label>
                            <textarea id="quoteNote" rows="2" placeholder="Nhập các mặt hàng bạn đang quan tâm hoặc cần gửi bảng giá qua Zalo..." class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-[#c81e1e]"></textarea>
                        </div>

                        <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-[#c81e1e] hover:bg-[#9b1515] text-white font-extrabold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                        </button>

                        <div id="quoteSuccessMsg" class="hidden p-2.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-semibold text-center"></div>
                    </form>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM PHA CHẾ)   -->
        <!-- ================================================================= -->
        <section id="sec-bai-viet" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flatsome-section-header">
                <h2 class="flatsome-section-title">
                    <i class="fa-solid fa-newspaper"></i>
                    <span>DANH MỤC BÀI VIẾT - CẨM NANG PHA CHẾ & LÀM BÁNH</span>
                </h2>
                <span class="text-[11px] text-gray-500 px-2 hidden sm:inline">Chia sẻ công thức & kinh nghiệm kinh doanh đồ uống, tiệm bánh</span>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <!-- Bài viết 1 -->
                <article class="rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between bg-white">
                    <div>
                        <div class="aspect-[16/9] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=15MEBT33BUV0yXW0JCm62FtTLO24U07V_&sz=w700"
                                data-drive-id="15MEBT33BUV0yXW0JCm62FtTLO24U07V_"
                                data-fallback-text="Cong+Thuc+Tra+Sua"
                                onerror="handleDriveImageError(this)"
                                alt="Bí quyết ủ Hồng Trà và Lục Trà Lài chuẩn vị cho quán" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] text-[#c81e1e] font-bold uppercase mb-1">Công thức pha chế</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-800 leading-snug mb-1.5">
                                Bí Quyết Ủ Hồng Trà & Lục Trà Lài Đậm Vị, Không Bị Chát Dành Cho Quán Trà Sữa
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Hướng dẫn chi tiết nhiệt độ nước, thời gian ủ trà và tỷ lệ kết hợp bột kem béo tại Khang Phát Foods giúp ly trà sữa thơm béo chuẩn vị thương hiệu lớn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] font-semibold text-[#c81e1e] flex items-center justify-between border-t border-gray-50">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Chuyên mục: Đồ pha chế</span>
                        <a href="#form-bao-gia" class="hover:underline">Nhận công thức <i class="fa-solid fa-arrow-right ml-0.5"></i></a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between bg-white">
                    <div>
                        <div class="aspect-[16/9] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1WMuElizcZTvnAmy1ZXu_bxcMaSm3WtS8&sz=w700"
                                data-drive-id="1WMuElizcZTvnAmy1ZXu_bxcMaSm3WtS8"
                                data-fallback-text="Nguyen+Lieu+Lam+Banh"
                                onerror="handleDriveImageError(this)"
                                alt="Cách phân biệt Whipping Cream và Topping Cream khi làm bánh kem" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] text-[#c81e1e] font-bold uppercase mb-1">Kinh nghiệm làm bánh</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-800 leading-snug mb-1.5">
                                Cách Chọn Bơ Lạt, Phô Mai & Kết Hợp Whipping - Topping Cream Đứng Form Bền Đẹp
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Mẹo pha trộn kem trang trí bánh kem không bị chảy trong thời tiết mùa hè miền Trung, tiết kiệm chi phí cốt bánh mà vẫn giữ trọn độ mềm mịn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] font-semibold text-[#c81e1e] flex items-center justify-between border-t border-gray-50">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Chuyên mục: Làm bánh</span>
                        <a href="#form-bao-gia" class="hover:underline">Tư vấn nguyên liệu <i class="fa-solid fa-arrow-right ml-0.5"></i></a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between bg-white">
                    <div>
                        <div class="aspect-[16/9] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN&sz=w700"
                                data-drive-id="1paUng8h3EzhrFbAIBQfljxZG_HPUhcUN"
                                data-fallback-text="Danh+Sach+Dung+Cu+Mo+Quan"
                                onerror="handleDriveImageError(this)"
                                alt="Trọn bộ dụng cụ pha chế cần thiết cho người mới mở quán cafe trà sữa" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] text-[#c81e1e] font-bold uppercase mb-1">Set-up mở quán</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-800 leading-snug mb-1.5">
                                Danh Sách Trọn Bộ Dụng Cụ Pha Chế Cần Thiết Khi Mở Quán Cafe & Trà Sữa Mới
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Tổng hợp các dụng cụ quầy bar thiết yếu: Bình lắc Shaker, Jigger đong định lượng, bình xịt kem, rây lọc trà, ca đánh sữa giúp tối ưu vốn đầu tư ban đầu.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] font-semibold text-[#c81e1e] flex items-center justify-between border-t border-gray-50">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Chuyên mục: Mở quán</span>
                        <a href="#form-bao-gia" class="hover:underline">Nhận báo giá sỉ <i class="fa-solid fa-arrow-right ml-0.5"></i></a>
                    </div>
                </article>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI                      -->
        <!-- ================================================================= -->
        <section aria-label="Danh mục các đối tác" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flatsome-section-header">
                <h2 class="flatsome-section-title">
                    <i class="fa-solid fa-handshake"></i>
                    <span>DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI</span>
                </h2>
                <span class="text-[11px] text-gray-500 px-2 hidden sm:inline">Hợp tác cùng các thương hiệu nguyên liệu thực phẩm & pha chế hàng đầu</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2.5">
                <div class="p-3 rounded-lg border border-gray-200 bg-gray-50/70 hover:border-[#c81e1e] transition flex flex-col items-center justify-center text-center">
                    <span class="text-xs sm:text-sm font-extrabold text-[#c81e1e] tracking-wide">ANCHOR</span>
                    <span class="text-[10.5px] text-gray-500 mt-0.5">Bơ, Sữa & Whipping</span>
                </div>
                <div class="p-3 rounded-lg border border-gray-200 bg-gray-50/70 hover:border-[#c81e1e] transition flex flex-col items-center justify-center text-center">
                    <span class="text-xs sm:text-sm font-extrabold text-[#c81e1e] tracking-wide">RICH'S</span>
                    <span class="text-[10.5px] text-gray-500 mt-0.5">Kem Béo & Topping</span>
                </div>
                <div class="p-3 rounded-lg border border-gray-200 bg-gray-50/70 hover:border-[#c81e1e] transition flex flex-col items-center justify-center text-center">
                    <span class="text-xs sm:text-sm font-extrabold text-[#c81e1e] tracking-wide">PURATOS</span>
                    <span class="text-[10.5px] text-gray-500 mt-0.5">Socola & Phụ Gia Bánh</span>
                </div>
                <div class="p-3 rounded-lg border border-gray-200 bg-gray-50/70 hover:border-[#c81e1e] transition flex flex-col items-center justify-center text-center">
                    <span class="text-xs sm:text-sm font-extrabold text-[#c81e1e] tracking-wide">TORANI / MONIN</span>
                    <span class="text-[10.5px] text-gray-500 mt-0.5">Siro & Sốt Pha Chế</span>
                </div>
                <div class="p-3 rounded-lg border border-gray-200 bg-gray-50/70 hover:border-[#c81e1e] transition flex flex-col items-center justify-center text-center">
                    <span class="text-xs sm:text-sm font-extrabold text-[#c81e1e] tracking-wide">PRESIDENT / TATUA</span>
                    <span class="text-[10.5px] text-gray-500 mt-0.5">Phô Mai & Kem Tươi</span>
                </div>
                <div class="p-3 rounded-lg border border-gray-200 bg-gray-50/70 hover:border-[#c81e1e] transition flex flex-col items-center justify-center text-center">
                    <span class="text-xs sm:text-sm font-extrabold text-[#c81e1e] tracking-wide">TÀI KÝ / UNIFRESH</span>
                    <span class="text-[10.5px] text-gray-500 mt-0.5">Bột Bánh & Mứt Trái Cây</span>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- ĐƯA FANPAGE FACEBOOK VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ      -->
        <!-- ================================================================= -->
        <section id="sec-lien-he" class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-gray-200">
            <div class="flatsome-section-header">
                <h2 class="flatsome-section-title">
                    <i class="fa-solid fa-map-location-dot"></i>
                    <span>KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG KHANG PHÁT FOODS</span>
                </h2>
                <span class="text-[11px] text-gray-500 px-2 hidden sm:inline">614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                <!-- CỘT 1: FANPAGE FACEBOOK TRANG CHỦ -->
                <div class="lg:col-span-5 flex flex-col justify-between rounded-xl border border-gray-200 bg-gray-50 p-3.5">
                    <div>
                        <div class="flex items-center justify-between mb-2.5">
                            <span class="text-xs font-extrabold uppercase text-[#1877F2] flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook text-base"></i>
                                <span>FANPAGE FACEBOOK CHÍNH THỨC</span>
                            </span>
                            <a href="https://www.facebook.com/vy.trieu.7946281" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-[#c81e1e] hover:underline">
                                Mở Facebook <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
                            </a>
                        </div>

                        <!-- Khung hiển thị trực quan Fanpage + Nhúng Facebook -->
                        <div class="rounded-lg overflow-hidden border border-gray-200 bg-white shadow-sm">
                            <div class="relative h-32 bg-gradient-to-r from-[#9b1515] to-[#ea580c] p-3 flex items-end">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1UzxPagzh40VJs0LN5vB-EYDgV_hFMywm&sz=w800"
                                    data-drive-id="1UzxPagzh40VJs0LN5vB-EYDgV_hFMywm"
                                    data-fallback-text="Fanpage+Khang+Phat+Foods"
                                    onerror="handleDriveImageError(this)"
                                    alt="Ảnh bìa Fanpage Khang Phát Foods" 
                                    class="absolute inset-0 w-full h-full object-cover opacity-45"
                                >
                                <div class="relative z-10 flex items-center gap-3">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w300"
                                        data-drive-id="1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy"
                                        data-fallback-text="KP"
                                        onerror="handleDriveImageError(this)"
                                        alt="Avatar Fanpage Khang Phát Foods" 
                                        class="w-14 h-14 rounded-lg border-2 border-white bg-white object-contain p-0.5 shadow"
                                    >
                                    <div class="text-white">
                                        <div class="font-extrabold text-xs sm:text-sm drop-shadow">Khang Phát Foods - Nguyên Liệu Pha Chế</div>
                                        <div class="text-[11px] text-amber-200 font-medium">facebook.com/vy.trieu.7946281</div>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2 text-xs text-gray-700">
                                <p class="leading-relaxed">
                                    Cập nhật hàng mới về kho mỗi ngày: Nguyên liệu thực phẩm, nguyên liệu làm bánh, trà, siro, bột kem béo, trân châu, dụng cụ pha chế giá sỉ & lẻ tốt nhất!
                                </p>
                                <div class="flex flex-wrap gap-2 pt-1">
                                    <a href="https://www.facebook.com/vy.trieu.7946281" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition">
                                        <i class="fa-brands fa-facebook-f mr-1"></i>Theo dõi Fanpage
                                    </a>
                                    <a href="https://www.facebook.com/vy.trieu.7946281" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2 px-3 rounded-lg bg-blue-50 hover:bg-blue-100 text-[#1877F2] border border-blue-200 font-bold text-xs transition">
                                        <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn tin Facebook
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-2.5 border-t border-gray-200 text-xs space-y-1 text-gray-600">
                        <div><strong class="text-gray-800">Website:</strong> khangphatfoods.com</div>
                        <div><strong class="text-gray-800">Hotline / Zalo:</strong> 0898.311.667 - 0369.456.667</div>
                    </div>
                </div>

                <!-- CỘT 2: BẢN ĐỒ GOOGLE MAP TRANG CHỦ -->
                <div class="lg:col-span-7 flex flex-col justify-between rounded-xl border border-gray-200 bg-gray-50 p-3.5">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                        <span class="text-xs font-extrabold uppercase text-[#c81e1e] flex items-center gap-1.5">
                            <i class="fa-solid fa-location-dot text-base"></i>
                            <span>BẢN ĐỒ GOOGLE MAPS: 614 TRẦN HƯNG ĐẠO, ĐIỆN BÀN ĐÔNG, TP.ĐÀ NẴNG</span>
                        </span>
                        <a href="https://share.google/qDPat1bSD7HB6iy71" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 px-2.5 py-1 rounded-full bg-[#c81e1e] hover:bg-[#9b1515] text-white text-[11px] font-bold transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span>Mở Google Map Chỉ Đường</span>
                        </a>
                    </div>

                    <!-- Nhúng trực tiếp Google Maps tại 614 Trần Hưng Đạo, Điện Bàn Đông, Đà Nẵng -->
                    <div class="w-full h-[250px] sm:h-[280px] rounded-lg overflow-hidden border border-gray-300 bg-white shadow-inner">
                        <iframe 
                            title="Bản đồ Công Ty TNHH Thương Mại Khang Phát Foods - 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng"
                            src="https://maps.google.com/maps?q=614%20Tr%E1%BA%A7n%20H%C6%B0ng%20%C4%90%E1%BA%A1o,%20%C4%90i%E1%BB%87n%20B%C3%A0n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>

                    <div class="mt-2.5 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-700">
                        <div>
                            <i class="fa-solid fa-Store text-[#c81e1e] mr-1"></i>
                            <strong>Địa chỉ kho & cửa hàng:</strong> 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng
                        </div>
                        <a href="https://share.google/qDPat1bSD7HB6iy71" target="_blank" rel="noopener noreferrer" class="text-[#c81e1e] font-bold hover:underline">
                            Xem vị trí trên Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-0.5"></i>
                        </a>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ===================================================================== -->
    <!-- FOOTER CHUẨN FLATSOME                                                 -->
    <!-- ===================================================================== -->
    <footer class="bg-[#1f2937] text-gray-200 mt-8 border-t-4 border-[#c81e1e]">
        <div class="flatsome-container py-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6">
                
                <!-- Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-3">
                        <div class="w-11 h-11 rounded-lg bg-white p-0.5 flex items-center justify-center shrink-0">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy&sz=w300"
                                data-drive-id="1Pu_H0BCHSiBcA22ZHS-CX7j2iZwSHvvy"
                                data-fallback-text="LOGO"
                                onerror="handleDriveImageError(this)"
                                alt="Logo Khang Phát Foods" 
                                class="w-full h-full object-contain"
                            >
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white leading-snug">
                                CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS
                            </h3>
                            <p class="text-xs text-amber-400 font-semibold">
                                Chuyên cung cấp sỉ & lẻ nguyên liệu thực phẩm, dụng cụ pha chế.
                            </p>
                        </div>
                    </div>
                    <ul class="space-y-1.5 text-xs text-gray-300 pt-1">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Địa chỉ:</strong> 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i><strong>Điện thoại / Hotline:</strong> 0898.311.667 - 0369.456.667</li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> khangphatfoods.com</li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/vy.trieu.7946281" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/vy.trieu.7946281</a></li>
                        <li><i class="fa-solid fa-map-pin text-amber-400 w-5"></i><strong>Google Map:</strong> <a href="https://share.google/qDPat1bSD7HB6iy71" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">Xem bản đồ chỉ đường</a></li>
                    </ul>
                </div>

                <!-- Danh mục sản phẩm -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-400 tracking-wide">
                        DANH MỤC SẢN PHẨM CHÍNH
                    </h4>
                    <div class="grid grid-cols-2 gap-1.5 text-xs text-gray-300">
                        <a href="#sec-nguyen-lieu-lam-banh" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Nguyên liệu làm bánh</a>
                        <a href="#sec-do-pha-che" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Đồ pha chế</a>
                        <a href="#sec-dung-cu-pha-che" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Dụng cụ pha chế</a>
                        <a href="#sec-dung-cu-lam-banh" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Dụng cụ làm bánh</a>
                        <a href="#sec-khuon-khay" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Khuôn, khay làm bánh</a>
                        <a href="#sec-tui-hop-bao-bi" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Túi, hộp, bao bì</a>
                        <a href="#sec-trang-tri-banh-kem" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Trang trí bánh kem</a>
                        <a href="#sec-do-trung-thu" class="hover:text-white"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Đồ Trung Thu & Vỏ bánh</a>
                    </div>
                </div>

                <!-- Hỗ trợ khách hàng -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-400 tracking-wide">
                        CHÍNH SÁCH SỈ & LẺ
                    </h4>
                    <ul class="space-y-1.5 text-xs text-gray-300">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Chiết khấu cao cho quán & đại lý</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Giao hàng tận nơi nhanh chóng</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Hàng hóa date mới, chính hãng</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Hỗ trợ công thức pha chế & làm bánh</li>
                    </ul>
                </div>

            </div>
        </div>
        <div class="bg-[#111827] py-3 text-center text-[11px] text-gray-400 border-t border-gray-800">
            <div class="flatsome-container">
                © Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI KHANG PHÁT FOODS</strong> (khangphatfoods.com) - Đ/c: 614 Trần Hưng Đạo, Điện Bàn Đông, Tp.Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)                     -->
    <!-- Tương thích hoàn hảo trên máy tính và điện thoại, không gây tràn viền -->
    <!-- ===================================================================== -->
    <div class="fixed bottom-3 right-3 z-40 flex flex-col items-end gap-2">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0898311667" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0898.311.667" class="group flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo Sỉ & Lẻ</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/vy.trieu.7946281" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage Facebook</span>
        </a>

        <!-- Nút Hotline 1 -->
        <a href="tel:0898311667" aria-label="Gọi 0898.311.667" class="contact-pulse flex items-center gap-2 bg-[#c81e1e] hover:bg-[#9b1515] text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-amber-400 text-gray-900 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0898.311.667</span>
        </a>

        <!-- Nút Hotline 2 -->
        <a href="tel:0369456667" aria-label="Gọi 0369.456.667" class="flex items-center gap-2 bg-[#ea580c] hover:bg-orange-700 text-white px-3 py-1.5 rounded-full shadow-lg transition">
            <span class="w-5 h-5 rounded-full bg-white text-[#ea580c] flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-[10px]"></i>
            </span>
            <span class="text-[11.5px] font-bold pr-1">0369.456.667</span>
        </a>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL GIỎ HÀNG & ĐẶT HÀNG NHANH (Không dùng alert)                    -->
    <!-- ===================================================================== -->
    <div id="cartModal" class="fixed inset-0 bg-black/50 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-md w-full p-4 shadow-2xl border border-gray-200">
            <div class="flex items-center justify-between pb-2.5 border-b border-gray-200">
                <h3 class="text-sm font-extrabold text-[#c81e1e] uppercase flex items-center gap-2">
                    <i class="fa-solid fa-basket-shopping"></i>
                    <span>GIỎ HÀNG BÁO GIÁ CỦA BẠN</span>
                </h3>
                <button type="button" onclick="closeCartModal()" class="w-7 h-7 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center text-gray-600">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="cartItemsList" class="py-3 max-h-60 overflow-y-auto divide-y divide-gray-100 text-xs text-gray-700">
                Chưa có sản phẩm trong giỏ hàng.
            </div>
            <div class="pt-3 border-t border-gray-200 flex items-center justify-between text-xs font-bold">
                <span>Tổng cộng tạm tính:</span>
                <span id="cartTotalValue" class="text-sm text-[#c81e1e]">0₫</span>
            </div>
            <div class="mt-3 flex gap-2">
                <button type="button" onclick="closeCartModal()" class="w-1/2 py-2 rounded-lg border border-gray-300 text-xs font-semibold text-gray-700 hover:bg-gray-50">
                    Xem thêm hàng
                </button>
                <a href="#form-bao-gia" onclick="closeCartModal()" class="w-1/2 py-2 rounded-lg bg-[#c81e1e] hover:bg-[#9b1515] text-white text-xs font-bold text-center">
                    Gửi đơn báo giá
                </a>
            </div>
        </div>
    </div>

    <!-- Thông báo Toast gọn nhẹ góc trên -->
    <div id="toastNotice" class="fixed top-16 right-4 z-50 hidden bg-gray-900 text-white text-xs font-semibold px-4 py-2.5 rounded-lg shadow-xl border-l-4 border-amber-400"></div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT ĐIỀU KHIỂN SLIDER 2 BANNER, MENU MOBILE, GIỎ HÀNG & FORM   -->
    <!-- ===================================================================== -->
    <script>
        /* 1. Tự động trượt 2 Banner kích thước bằng nhau */
        let currentBannerIndex = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function renderBannerSlide(index) {
            currentBannerIndex = (index + totalBanners) % totalBanners;
            for (let i = 0; i < totalBanners; i++) {
                const slide = document.getElementById('bannerSlide' + i);
                const dot = document.getElementById('bannerDot' + i);
                if (slide && dot) {
                    if (i === currentBannerIndex) {
                        slide.classList.remove('opacity-0', 'z-0');
                        slide.classList.add('opacity-100', 'z-10');
                        dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    } else {
                        slide.classList.remove('opacity-100', 'z-10');
                        slide.classList.add('opacity-0', 'z-0');
                        dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                    }
                }
            }
        }

        function nextBanner() {
            renderBannerSlide(currentBannerIndex + 1);
            resetBannerTimer();
        }

        function prevBanner() {
            renderBannerSlide(currentBannerIndex - 1);
            resetBannerTimer();
        }

        function goToBanner(idx) {
            renderBannerSlide(idx);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                renderBannerSlide(currentBannerIndex + 1);
            }, 4800);
        }

        /* 2. Đóng / mở Menu Danh mục trên Điện thoại */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const overlay = document.getElementById('mobileMenuOverlay');
            const isHidden = drawer.classList.contains('-translate-x-full');
            if (isHidden) {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            }
        }

        /* 3. Quản lý Giỏ hàng & Thông báo Toast */
        const cart = [];

        function showToast(message) {
            const toast = document.getElementById('toastNotice');
            toast.textContent = message;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 2600);
        }

        function addToCart(productName, price) {
            const existing = cart.find(item => item.name === productName);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ name: productName, price: price, qty: 1 });
            }
            updateCartUI();
            showToast('Đã thêm "' + productName + '" vào giỏ báo giá!');
        }

        function updateCartUI() {
            const badge = document.getElementById('cartCountBadge');
            const list = document.getElementById('cartItemsList');
            const totalEl = document.getElementById('cartTotalValue');

            const totalQty = cart.reduce((sum, i) => sum + i.qty, 0);
            const totalPrice = cart.reduce((sum, i) => sum + i.price * i.qty, 0);
            badge.textContent = totalQty;
            totalEl.textContent = totalPrice.toLocaleString('vi-VN') + '₫';

            if (cart.length === 0) {
                list.innerHTML = '<div class="py-4 text-center text-gray-400">Chưa có sản phẩm trong giỏ hàng.</div>';
                return;
            }

            list.innerHTML = cart.map((item, idx) => `
                <div class="py-2 flex items-center justify-between gap-2">
                    <div class="font-semibold text-gray-800">${item.name} <span class="text-[#c81e1e]">x${item.qty}</span></div>
                    <div class="flex items-center gap-2 shrink-0">
                        <span class="font-bold text-[#c81e1e]">${(item.price * item.qty).toLocaleString('vi-VN')}₫</span>
                        <button type="button" onclick="removeCartItem(${idx})" class="text-gray-400 hover:text-red-600">
                            <i class="fa-solid fa-trash-can"></i>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        function removeCartItem(index) {
            cart.splice(index, 1);
            updateCartUI();
        }

        function openCartModal() {
            const modal = document.getElementById('cartModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeCartModal() {
            const modal = document.getElementById('cartModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* 4. Tìm kiếm nhanh sản phẩm trên trang */
        function filterProductsByQuery(query) {
            const keyword = query.trim().toLowerCase();
            const cards = document.querySelectorAll('.flatsome-product-box');
            let matchCount = 0;
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!keyword || text.includes(keyword)) {
                    card.style.display = 'flex';
                    matchCount++;
                } else {
                    card.style.display = 'none';
                }
            });
            if (keyword) {
                showToast('Tìm thấy ' + matchCount + ' sản phẩm phù hợp với "' + query + '"');
                document.getElementById('sec-do-pha-che').scrollIntoView({ behavior: 'smooth' });
            }
        }

        function handleSearch(e) {
            e.preventDefault();
            const val = document.getElementById('desktopSearchInput').value;
            filterProductsByQuery(val);
        }

        function handleSearchMobile(e) {
            e.preventDefault();
            const val = document.getElementById('mobileSearchInput').value;
            filterProductsByQuery(val);
        }

        /* 5. Xử lý gửi Form Yêu cầu & Báo giá trang chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value.trim();
            const phone = document.getElementById('quotePhone').value.trim();
            const category = document.getElementById('quoteCategory').value;
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.innerHTML = '<i class="fa-solid fa-circle-check mr-1"></i>Cảm ơn <strong>' + name + '</strong> (' + phone + ')! Yêu cầu báo giá mục <strong>' + category + '</strong> đã được ghi nhận. Khang Phát Foods (0898.311.667 - 0369.456.667) sẽ liên hệ báo giá ngay!';
            msgBox.classList.remove('hidden');
            e.target.reset();
        }

        window.onload = function () {
            resetBannerTimer();
        };
    </script>
</body>
</html>
