# travelwmehsu.github.io
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evo Tour - 마감 임박 특가 투어 (B안: 1일 기준 가격)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&display=swap');
        body { font-family: 'Noto Sans KR', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-plane-departure text-2xl text-cyan-500"></i>
                <span class="text-xl font-bold text-blue-900">Evo <span class="text-cyan-500">Tour</span></span>
            </div>
            <div class="flex items-center space-x-6 text-sm text-gray-600">
                <a href="#" class="hover:text-orange-500"><i class="fa-regular fa-heart text-lg mr-1"></i> 관심 상품 (<span id="wishlist-count">0</span>)</a>
                <a href="#" class="hover:text-orange-500"><i class="fa-regular fa-user text-lg mr-1"></i> 로그인</a>
            </div>
        </div>
    </header>
    <!-- Main Content -->
    <main class="max-w-6xl mx-auto px-4 py-8">
        <div class="text-center mb-8">
            <h1 class="text-2xl font-bold text-gray-900 mb-2">
                마감 임박 <span class="text-orange-500">특가 투어</span>
            </h1>
            <p class="text-sm text-gray-500">하루 커피 몇 잔 가격으로 떠나는 부담 없는 힐링 여행!</p>
        </div>
        <!-- Tour Grid (Variant B: Per-Day Price Display) -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">         
            <!-- Tour 1 -->
            <div class="bg-white rounded-lg shadow border border-emerald-200 hover:shadow-md transition">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?w=500" alt="Cambodia" class="w-full h-44 object-cover rounded-t-lg">
                <div class="p-4">
                    <h3 class="font-bold text-sm mb-2 text-gray-800 line-clamp-2">캄보디아 앙코르와트 4박 5일 패키지</h3>
                    <p class="text-xs text-gray-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i> 출발일: 매주 일요일</p>
                    <p class="text-xs text-gray-500 mb-3"><i class="fa-regular fa-clock mr-1"></i> 여행 기간: 4박 5일</p>
                    <div class="flex items-center justify-between border-t pt-3">
                        <div>
                            <span class="text-[10px] text-emerald-600 font-semibold bg-emerald-50 px-1.5 py-0.5 rounded">1일 기준</span>
                            <div class="text-lg font-bold text-emerald-600">하루 ₩79,580~</div>
                            <span class="text-[11px] text-gray-400">(총액 ₩397,900)</span>
                        </div>
                        <button onclick="recordBooking('B', '캄보디아')" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-3 py-2 rounded">
                            예약하기
                        </button>
                    </div>
                </div>
            </div>
            <!-- Tour 2 -->
            <div class="bg-white rounded-lg shadow border border-emerald-200 hover:shadow-md transition">
                <img src="https://images.unsplash.com/photo-1528127269322-539801943592?w=500" alt="Ha Long Bay" class="w-full h-44 object-cover rounded-t-lg">
                <div class="p-4">
                    <h3 class="font-bold text-sm mb-2 text-gray-800 line-clamp-2">하노이 & 하롱베이 힐링 4일 투어</h3>
                    <p class="text-xs text-gray-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i> 출발일: 매주 월요일</p>
                    <p class="text-xs text-gray-500 mb-3"><i class="fa-regular fa-clock mr-1"></i> 여행 기간: 3박 4일</p>
                    <div class="flex items-center justify-between border-t pt-3">
                        <div>
                            <span class="text-[10px] text-emerald-600 font-semibold bg-emerald-50 px-1.5 py-0.5 rounded">1일 기준</span>
                            <div class="text-lg font-bold text-emerald-600">하루 ₩160,000~</div>
                            <span class="text-[11px] text-gray-400">(총액 ₩640,000)</span>
                        </div>
                        <button onclick="recordBooking('B', '하노이')" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-3 py-2 rounded">
                            예약하기
                        </button>
                    </div>
                </div>
            </div>
            <!-- Tour 3 -->
            <div class="bg-white rounded-lg shadow border border-emerald-200 hover:shadow-md transition">
                <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=500" alt="Phan Thiet" class="w-full h-44 object-cover rounded-t-lg">
                <div class="p-4">
                    <h3 class="font-bold text-sm mb-2 text-gray-800 line-clamp-2">판티엣 & 무이네 사구 3일 투어</h3>
                    <p class="text-xs text-gray-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i> 출발일: 매주 토요일</p>
                    <p class="text-xs text-gray-500 mb-3"><i class="fa-regular fa-clock mr-1"></i> 여행 기간: 2박 3일</p>
                    <div class="flex items-center justify-between border-t pt-3">
                        <div>
                            <span class="text-[10px] text-emerald-600 font-semibold bg-emerald-50 px-1.5 py-0.5 rounded">1일 기준</span>
                            <div class="text-lg font-bold text-emerald-600">하루 ₩66,660~</div>
                            <span class="text-[11px] text-gray-400">(총액 ₩200,000)</span>
                        </div>
                        <button onclick="recordBooking('B', '판티엣')" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-3 py-2 rounded">
                            예약하기
                        </button>
                    </div>
                </div>
            </div>
            <!-- Tour 4 -->
            <div class="bg-white rounded-lg shadow border border-emerald-200 hover:shadow-md transition">
                <img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?w=500" alt="Nha Trang" class="w-full h-44 object-cover rounded-t-lg">
                <div class="p-4">
                    <h3 class="font-bold text-sm mb-2 text-gray-800 line-clamp-2">나트랑 빈펄 리조트 & 호핑 3일</h3>
                    <p class="text-xs text-gray-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i> 출발일: 매주 월요일</p>
                    <p class="text-xs text-gray-500 mb-3"><i class="fa-regular fa-clock mr-1"></i> 여행 기간: 2박 3일</p>
                    <div class="flex items-center justify-between border-t pt-3">
                        <div>
                            <span class="text-[10px] text-emerald-600 font-semibold bg-emerald-50 px-1.5 py-0.5 rounded">1일 기준</span>
                            <div class="text-lg font-bold text-emerald-600">하루 ₩216,660~</div>
                            <span class="text-[11px] text-gray-400">(총액 ₩650,000)</span>
                        </div>
                        <button onclick="recordBooking('B', '나트랑')" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-3 py-2 rounded">
                            예약하기
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </main>
    <script>
        function recordBooking(variant, tourName) {
            alert(`[실험 B] '${tourName}' 상품 예약 클릭이 기록되었습니다.`);
            let clicks = localStorage.getItem('clicks_variant_B') || 0;
            localStorage.setItem('clicks_variant_B', parseInt(clicks) + 1);
        }
    </script>
</body>
</html>
