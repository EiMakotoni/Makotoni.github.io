<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Báo Cáo Động Đất Kon Tum - Phân tích & Dự báo 2024</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { 
            font-family: 'Plus Jakarta Sans', sans-serif; 
            background-color: #ffffff; 
            color: #1a202c;
            scroll-behavior: smooth;
        }
        .header-gradient {
            background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
        }
        .section-card {
            border-bottom: 1px solid #edf2f7;
            padding-top: 4rem;
            padding-bottom: 4rem;
        }
        .image-frame {
            border-radius: 16px;
            overflow: hidden;
            border: 1px solid #e2e8f0;
            background-color: #f8fafc;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }
        .chart-container {
            position: relative;
            height: 400px;
            width: 100%;
            background: #f8fafc;
            padding: 1.5rem;
            border-radius: 12px;
        }
        .nav-link {
            transition: all 0.2s;
            position: relative;
        }
        .nav-link:hover { color: #3182ce; }
        .nav-link::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background-color: #3182ce;
            transition: width 0.3s;
        }
        .nav-link:hover::after { width: 100%; }
        
        @keyframes slideInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .reveal { animation: slideInUp 0.8s ease-out forwards; }
    </style>
</head>
<body class="antialiased">

    <!-- Sticky Navigation -->
    <nav class="fixed top-0 w-full z-50 bg-white/90 backdrop-blur-md border-b border-gray-100 px-6 py-4">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xs shadow-lg shadow-blue-200">KT</div>
                <div class="flex flex-col">
                    <span class="font-extrabold text-sm tracking-tight leading-none">Báo Cáo Động Đất Kon Tum</span>
                    <span class="text-[9px] text-gray-400 uppercase font-bold mt-1">Phân tích nguyên nhân & Dự báo</span>
                </div>
            </div>
            <div class="hidden md:flex gap-8 text-[10px] font-bold text-gray-500 uppercase tracking-widest">
                <a href="#nguyen-nhan" class="nav-link">Nguyên nhân</a>
                <a href="#du-lieu" class="nav-link">Dữ liệu</a>
                <a href="#du-bao" class="nav-link">Dự báo</a>
                <a href="#phu-luc" class="nav-link text-blue-600">Phụ lục</a>
            </div>
            <div class="flex items-center gap-3">
                <span class="px-3 py-1 bg-green-100 text-green-700 text-[10px] font-bold rounded-full border border-green-200 uppercase">Status 2024</span>
            </div>
        </div>
    </nav>

    <!-- Main Header -->
    <header class="header-gradient pt-40 pb-24 text-white text-center px-6">
        <div class="max-w-4xl mx-auto reveal">
            <h1 class="text-4xl md:text-5xl font-extrabold mb-6 leading-tight">Báo Cáo Động Đất Kon Tum</h1>
            <p class="text-lg text-blue-200 font-medium max-w-2xl mx-auto opacity-90 leading-relaxed mb-8">
                Phân tích nguyên nhân địa chất, tác động từ hoạt động thủy điện và dự báo rủi ro thiên tai cập nhật năm 2024.
            </p>
            <div class="flex justify-center gap-4">
                <span class="px-4 py-2 bg-white/10 rounded-lg backdrop-blur-sm border border-white/10 text-[10px] font-bold uppercase tracking-widest">Viện Vật lý Địa cầu Data</span>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-6">
        
        <!-- SECTION 1: NGUYÊN NHÂN ĐỊA CHẤT -->
        <section id="nguyen-nhan" class="section-card">
            <div class="grid lg:grid-cols-2 gap-16 items-start">
                <div class="reveal">
                    <span class="text-blue-600 font-black text-xs uppercase tracking-[0.3em] mb-4 block">Giai đoạn 1: Địa tầng & Nguyên nhân</span>
                    <h2 class="text-3xl font-extrabold mb-6 leading-tight text-gray-900">Đặc điểm địa chấn khu vực</h2>
                    <p class="text-gray-600 leading-relaxed mb-6 text-justify">
                        Khu vực huyện Kon Plông nằm trên hệ thống đứt gãy nhánh có cấu trúc phức tạp. Kể từ tháng 4/2021, khu vực này bắt đầu ghi nhận chuỗi động đất kích thích dồn dập. Sự dịch chuyển địa tầng kết hợp với các đới đứt gãy nhạy cảm đã làm bùng nổ hàng trăm trận chấn động mỗi năm.
                    </p>
                    <div class="bg-gray-50 border-l-4 border-blue-500 p-6 rounded-r-2xl mb-8">
                        <p class="text-gray-700 italic font-medium leading-relaxed text-sm">
                            "Động đất tại Kon Tum mang đặc điểm của động đất kích thích, xảy ra do quá trình tích nước hồ chứa thủy điện tác động lên hệ thống đứt gãy hoạt động bên dưới."
                        </p>
                        <div class="mt-4 flex items-center gap-3">
                            <div class="font-bold text-xs">TS. Nguyễn Xuân Anh</div>
                            <div class="text-[9px] uppercase font-bold text-gray-400">Viện trưởng Viện Vật lý địa cầu</div>
                        </div>
                    </div>
                </div>
                <div class="reveal">
                    <div class="image-frame">
                        <img src="https://xdcs.cdnchinhphu.vn/thumb_w/640/446259493575335936/2024/7/29/78a5348934579109c846-17222370434451343098690-1722241057201-17222410575761677253168.jpg" alt="Chân dung chuyên gia Nguyễn Xuân Anh" class="w-full h-full object-cover">
                        <p class="p-3 bg-white text-[9px] text-center font-bold text-gray-400 uppercase tracking-widest">TS. Nguyễn Xuân Anh trao đổi với phóng viên (VGP)</p>
                    </div>
                </div>
            </div>

            <!-- Chuỗi sự kiện tiêu biểu -->
            <div class="mt-20">
                <h3 class="text-xs font-extrabold mb-10 text-center uppercase tracking-widest text-gray-400">Dữ liệu các trận động đất tiêu biểu 23/08/2022</h3>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="image-frame reveal">
                        <img src="https://congdankhuyenhoc.qltns.mediacdn.vn/449484899827462144/2022/8/24/dong-dat-o-kon-tum-238-tran-1-1661301637768590991821.png" class="w-full h-48 object-cover">
                        <div class="p-4 bg-white text-center border-t border-gray-100">
                            <p class="font-extrabold text-red-600 text-xs uppercase">Trận số 1 - Độ lớn 4.7</p>
                            <p class="text-[9px] font-bold text-gray-400 mt-1">23/08/2022 | 14:08:04</p>
                        </div>
                    </div>
                    <div class="image-frame reveal">
                        <img src="https://congdankhuyenhoc.qltns.mediacdn.vn/thumb_w/840/449484899827462144/2022/8/24/dong-dat-238-tran-4-16613170354221478328454.png" class="w-full h-48 object-cover">
                        <div class="p-4 bg-white text-center border-t border-gray-100">
                            <p class="font-extrabold text-blue-600 text-xs uppercase">Trận số 4 - Độ lớn 2.5</p>
                        </div>
                    </div>
                    <div class="image-frame reveal">
                        <img src="https://congdankhuyenhoc.qltns.mediacdn.vn/449484899827462144/2022/8/24/dong-dat-238-tran-9-16613168305181431588435.png" class="w-full h-48 object-cover">
                        <div class="p-4 bg-white text-center border-t border-gray-100">
                            <p class="font-extrabold text-blue-600 text-xs uppercase">Trận số 9 - Độ lớn 2.7</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: DỮ LIỆU & THỦY ĐIỆN -->
        <section id="du-lieu" class="section-card">
            <div class="reveal mb-12">
                <span class="text-blue-600 font-black text-xs uppercase tracking-[0.3em] mb-4 block">Giai đoạn 2: Dữ liệu & Tương quan</span>
                <h2 class="text-3xl font-extrabold mb-6 leading-tight text-gray-900">Thống kê dữ liệu chính xác qua các năm</h2>
                <p class="text-gray-600 leading-relaxed mb-10 max-w-4xl text-justify">
                    Theo Viện Vật lý Địa cầu, từ năm 1903 đến 2020 chỉ ghi nhận khoảng 30 trận động đất. Tuy nhiên, kể từ năm 2021, tần suất tăng vọt đáng báo động. Trận động đất lớn nhất từng ghi nhận tại khu vực xảy ra vào ngày 28/7/2024 với độ lớn 5.0 độ Richter.
                </p>
            </div>

            <!-- Biểu đồ thống kê chính xác -->
            <div class="bg-white p-8 rounded-3xl border border-gray-100 shadow-xl shadow-gray-200/50 reveal mb-16">
                <div class="flex flex-col md:flex-row items-center justify-between mb-8 px-4 gap-4">
                    <h4 class="font-bold text-gray-800 uppercase tracking-widest text-[10px]">Thống kê số trận động đất kích thích (Kon Tum)</h4>
                    <div class="flex gap-4">
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 bg-blue-600 rounded"></span>
                            <span class="text-[10px] font-bold text-gray-500 uppercase">Số trận (>2.5)</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-0.5 border-t-2 border-dashed border-amber-500"></span>
                            <span class="text-[10px] font-bold text-gray-500 uppercase">Mực nước hồ (%)</span>
                        </div>
                    </div>
                </div>
                <div class="chart-container">
                    <canvas id="seismicChart"></canvas>
                </div>
                <p class="mt-6 text-center text-[9px] text-gray-400 font-bold uppercase tracking-widest">* Nguồn dữ liệu: Viện Vật lý Địa cầu - Viện Hàn lâm KH&CN Việt Nam</p>
            </div>
        </section>

        <!-- SECTION 3: DỰ BÁO & ẢNH HƯỞNG -->
        <section id="du-bao" class="section-card">
            <div class="grid lg:grid-cols-2 gap-16 items-start">
                <div class="reveal">
                    <span class="text-blue-600 font-black text-xs uppercase tracking-[0.3em] mb-4 block">Giai đoạn 3: Dự báo & Ảnh hưởng</span>
                    <h2 class="text-3xl font-extrabold mb-6 leading-tight text-gray-900">Dự báo rủi ro & Tác động cộng đồng</h2>
                    <p class="text-gray-600 leading-relaxed mb-8 text-justify">
                        Dự báo trong thời gian tới, động đất tại Kon Tum vẫn sẽ tiếp diễn nhưng ít có khả năng vượt quá 5.5 độ Richter. Tuy nhiên, sự rung lắc liên tục đã gây ra thiệt hại về tài sản, nứt tường các trụ sở y tế, giáo dục và nhà dân tại huyện Kon Plông.
                    </p>
                    <div class="image-frame">
                        <img src="https://cdn2.tuoitre.vn/thumb_w/1200/471584752817336320/2024/7/31/do-hoa-1722387777162777128778.jpg" class="w-full">
                        <div class="p-3 bg-white text-[9px] text-center font-bold text-gray-400 uppercase tracking-widest">Đồ họa vùng ảnh hưởng động đất 2024 (Tuổi Trẻ)</div>
                    </div>
                </div>
                <div class="reveal">
                    <h3 class="font-extrabold text-[10px] uppercase tracking-widest text-gray-400 mb-8">Thư viện hiện trường & Tác động</h3>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="image-frame h-48 group cursor-pointer overflow-hidden">
                            <img src="https://suckhoedoisong.qltns.mediacdn.vn/thumb_w/640/324455921873985536/2025/4/12/dong-dat-thuc-giac-o-viet-nam-1744443191032406229303.jpg" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110">
                        </div>
                        <div class="image-frame h-48 group cursor-pointer overflow-hidden">
                            <img src="https://media.vov.vn/sites/default/files/styles/large/public/2025-04/fd.jpg" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110">
                        </div>
                        <div class="image-frame h-48 group cursor-pointer overflow-hidden">
                            <img src="https://photo.znews.vn/w1920/Uploaded/gtnzna/2022_12_11/dong_dat_thumb_1_.jpg" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110">
                        </div>
                        <div class="image-frame h-48 group cursor-pointer overflow-hidden">
                            <img src="https://scontent.fhan14-5.fna.fbcdn.net/v/t39.30808-6/490657543_659651133476301_4843622312229266825_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=127cfc&_nc_ohc=Dgp0NDHACs8Q7kNvwE2_fu0&_nc_oc=AdlIb9CNtXcdtPH4M5wT5IUunDpTzSCmNKrnz__onJ0XZL7EtbCSIDO3Pe25hcwBinYnSCo8YfTJz1qbeSkpiDAx&_nc_zt=23&_nc_ht=scontent.fhan14-5.fna&_nc_gid=jI_EWMopWMmrnq4PFnmtFQ&oh=00_Afl6HhHvFC9cQpZU_zAdHhZvdO5FRg1xiKJqn-RkaEs7cQ&oe=695408E3" 
                                 class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" 
                                 onerror="this.src='https://via.placeholder.com/400x300?text=News+Update';">
                        </div>
                    </div>
                    <p class="mt-6 text-[9px] text-center text-gray-400 font-bold uppercase tracking-tighter">Tổng hợp hình ảnh từ các báo VOV, Znews, Sức khỏe đời sống</p>
                </div>
            </div>
        </section>

        <!-- SECTION: PHỤ LỤC MINH HỌA -->
        <section id="phu-luc" class="section-card border-none pb-40">
            <div class="text-center mb-16 reveal">
                <span class="text-blue-600 font-black text-xs uppercase tracking-[0.3em] mb-4 block">Phụ lục minh họa</span>
                <h2 class="text-3xl font-extrabold text-gray-900">Hoạt động Thủy điện & Bản đồ địa chấn</h2>
            </div>
            
            <div class="grid md:grid-cols-2 gap-10">
                <div class="image-frame reveal">
                    <img src="https://media-cdn-v2.laodong.vn/Storage/NewsPortal/2023/6/17/1205833/Thuy-Dien-2.jpg" class="w-full h-80 object-cover" alt="Thủy điện Thượng Kon Tum">
                    <div class="p-6 bg-white border-t border-gray-100">
                        <p class="text-sm font-bold text-gray-800 mb-2">Công trình hồ chứa thủy điện khu vực Kon Plông</p>
                        <p class="text-xs text-gray-500 leading-relaxed italic">Hoạt động tích nước gây áp suất lên hệ thống đới đứt gãy bên dưới lòng hồ.</p>
                    </div>
                </div>
                <div class="image-frame reveal">
                    <img src="https://daphuongtien.moj.gov.vn/noidung/tintuc/PublishingImages/1152022kontum.png" class="w-full h-80 object-cover" alt="Bản đồ định vị tâm chấn">
                    <div class="p-6 bg-white border-t border-gray-100">
                        <p class="text-sm font-bold text-gray-800 mb-2">Bản đồ phân bố mạng lưới trạm quan trắc</p>
                        <p class="text-xs text-gray-500 leading-relaxed italic">Dữ liệu định vị cho thấy chấn tâm tập trung dày đặc quanh hành lang tích nước thủy điện.</p>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-20 px-6">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-10">
            <div>
                <div class="flex items-center gap-2 mb-4">
                    <div class="w-6 h-6 bg-blue-600 rounded flex items-center justify-center text-[10px] font-bold">KT</div>
                    <span class="font-extrabold text-lg tracking-tight">KonTum Seismic Report 2024</span>
                </div>
                <p class="text-gray-500 text-[10px] max-w-sm uppercase font-bold tracking-widest opacity-60">Dữ liệu khoa học phục vụ nghiên cứu & ứng phó thiên tai</p>
            </div>
            <div class="flex gap-8 text-[9px] font-bold uppercase tracking-widest text-gray-400">
                <a href="#" class="hover:text-blue-500 transition-colors">Viện Vật lý Địa cầu</a>
                <a href="#" class="hover:text-blue-500 transition-colors">Trung tâm Báo tin Động đất</a>
                <a href="#" class="hover:text-blue-500 transition-colors">Tài liệu tham khảo</a>
            </div>
        </div>
    </footer>

    <script>
        window.onload = function() {
            const ctx = document.getElementById('seismicChart').getContext('2d');
            
            new Chart(ctx, {
                type: 'line',
                data: {
                    labels: ['2020', '2021', '2022', '2023', '2024'],
                    datasets: [{
                        label: 'Số trận động đất (> 2.5)',
                        data: [0, 169, 254, 316, 436],
                        borderColor: '#2563eb',
                        backgroundColor: (context) => {
                            const chart = context.chart;
                            const {ctx, chartArea} = chart;
                            if (!chartArea) return null;
                            const gradient = ctx.createLinearGradient(0, chartArea.bottom, 0, chartArea.top);
                            gradient.addColorStop(0, 'rgba(37, 99, 235, 0)');
                            gradient.addColorStop(1, 'rgba(37, 99, 235, 0.2)');
                            return gradient;
                        },
                        borderWidth: 4,
                        pointRadius: 6,
                        pointBackgroundColor: '#2563eb',
                        pointBorderColor: '#ffffff',
                        pointBorderWidth: 2,
                        tension: 0.4,
                        fill: true,
                        yAxisID: 'y',
                    }, {
                        label: 'Mực nước hồ (%)',
                        data: [40, 78, 92, 85, 96],
                        borderColor: '#f59e0b',
                        borderDash: [8, 4],
                        borderWidth: 2,
                        pointRadius: 0,
                        tension: 0.2,
                        fill: false,
                        yAxisID: 'y1',
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    interaction: { mode: 'index', intersect: false },
                    scales: {
                        x: {
                            grid: { display: false },
                            ticks: { font: { weight: 'bold', size: 10 } }
                        },
                        y: {
                            type: 'linear',
                            display: true,
                            position: 'left',
                            title: { display: true, text: 'SỐ TRẬN GHI NHẬN', font: { weight: '800', size: 10 } },
                            grid: { color: '#f1f5f9' },
                            min: 0
                        },
                        y1: {
                            type: 'linear',
                            display: true,
                            position: 'right',
                            grid: { drawOnChartArea: false },
                            title: { display: true, text: 'MỰC NƯỚC (%)', font: { weight: '800', size: 10 } },
                            min: 0,
                            max: 100
                        }
                    },
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            backgroundColor: '#1e293b',
                            padding: 12,
                            titleFont: { size: 14, weight: 'bold' },
                            bodyFont: { size: 13 },
                            cornerRadius: 8
                        }
                    }
                }
            });

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) entry.target.classList.add('reveal');
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
        };
    </script>
</body>
</html>
