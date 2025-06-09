<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>김온핑 (Kimonping) 팬 페이지</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        /* Noto Sans KR 폰트 적용 */
        body {
            font-family: 'Noto Sans KR', sans-serif;
        }
        /* 스크롤 부드럽게 */
        html {
            scroll-behavior: smooth;
        }
        /* 커스텀 그라데이션 */
        .gradient-bg {
            background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%);
        }
        .card-bg {
            background-color: rgba(255, 255, 255, 0.6);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- 헤더 -->
    <header class="gradient-bg shadow-lg">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-3xl font-bold text-white tracking-wider">김온핑 KIMONPING</h1>
            <nav class="hidden md:flex space-x-8 text-white">
                <a href="#about" class="hover:text-gray-200 transition duration-300">소개</a>
                <a href="#broadcast" class="hover:text-gray-200 transition duration-300">방송 안내</a>
                <a href="#links" class="hover:text-gray-200 transition duration-300">링크</a>
            </nav>
        </div>
    </header>

    <!-- 메인 컨텐츠 -->
    <main class="container mx-auto p-4 md:p-8">

        <!-- 프로필 섹션 -->
        <section id="profile" class="text-center my-12">
            <img src="https://placehold.co/150x150/fbc2eb/a6c1ee?text=ONPING" 
                 alt="김온핑 프로필 이미지"
                 class="w-40 h-40 rounded-full mx-auto shadow-xl border-4 border-white transform hover:scale-110 transition-transform duration-300">
            <h2 class="text-4xl font-extrabold mt-6 mb-2">안녕하세요! 김온핑입니다.</h2>
            <p class="text-lg text-gray-600">여러분의 즐거움을 책임지는 스트리머!</p>
        </section>

        <!-- 소개 섹션 -->
        <section id="about" class="my-16 p-8 card-bg rounded-2xl shadow-lg">
            <h3 class="text-3xl font-bold text-center mb-6 border-b-2 border-pink-300 pb-3">ABOUT ME ABOUT ME 핑</h3>
            <p class="text-center text-lg leading-relaxed">
                <!-- 김온핑님에 대한 소개를 자유롭게 수정해주세요 -->
                다양한 게임과 소통 방송을 진행하고 있는 스트리머 김온핑입니다. 😊<br>
                시청자 여러분과 함께 웃고 떠들며 즐거운 시간을 만드는 것이 저의 가장 큰 기쁨이에요.<br>
                오늘도 핑과 함께 신나는 하루 보내실 준비되셨나요?
            </p>
        </section>

        <!-- 방송 안내 섹션 -->
        <section id="broadcast" class="my-16">
            <h3 class="text-3xl font-bold text-center mb-8">BROADCAST INFO</h3>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="p-8 card-bg rounded-2xl shadow-lg hover:shadow-xl transition-shadow duration-300">
                    <div class="flex items-center mb-4">
                        <i class="fa-solid fa-clock text-3xl text-pink-400 mr-4"></i>
                        <h4 class="text-2xl font-bold">방송 시간</h4>
                    </div>
                    <!-- 방송 시간을 수정해주세요 -->
                    <p>평일 저녁 8시 ~ 12시</p>
                    <p>주말은 랜덤! (공지를 확인해주세요)</p>
                </div>
                <div class="p-8 card-bg rounded-2xl shadow-lg hover:shadow-xl transition-shadow duration-300">
                    <div class="flex items-center mb-4">
                        <i class="fa-solid fa-gamepad text-3xl text-blue-400 mr-4"></i>
                        <h4 class="text-2xl font-bold">주요 컨텐츠</h4>
                    </div>
                    <!-- 주요 컨텐츠를 수정해주세요 -->
                    <p>종합 게임 (스팀 게임, 온라인 게임 등)</p>
                    <p>시청자와 함께하는 소통 방송 (Just Chatting)</p>
                </div>
            </div>
        </section>

        <!-- 링크 섹션 -->
        <section id="links" class="my-16 text-center">
            <h3 class="text-3xl font-bold mb-8">LINKS</h3>
            <div class="flex justify-center items-center space-x-6">
                <!-- 각 아이콘에 김온핑님의 실제 링크를 적용했습니다 -->
                <a href="https://chzzk.naver.com/eacbd2575fbd759ae6d28b6a3aee75b8" target="_blank" class="text-5xl text-green-500 hover:text-green-600 transform hover:-translate-y-1 transition-all duration-300">
                    <i class="fa-solid fa-z"></i>
                    <p class="text-sm mt-2">치지직</p>
                </a>
                <a href="https://www.youtube.com/watch?v=xRCZL5l29_w" target="_blank" class="text-5xl text-red-500 hover:text-red-600 transform hover:-translate-y-1 transition-all duration-300">
                    <i class="fab fa-youtube"></i>
                    <p class="text-sm mt-2">유튜브</p>
                </a>
                <a href="https://www.instagram.com/too.thve_/" target="_blank" class="text-5xl text-purple-500 hover:text-purple-600 transform hover:-translate-y-1 transition-all duration-300">
                    <i class="fab fa-instagram"></i>
                    <p class="text-sm mt-2">인스타그램</p>
                </a>
                <a href="https://fancim.me/celeb/profile.aspx?cu_id=seey4194" target="_blank" class="text-5xl text-pink-500 hover:text-pink-600 transform hover:-translate-y-1 transition-all duration-300">
                    <i class="fa-solid fa-heart"></i>
                    <p class="text-sm mt-2">팬심</p>
                </a>
            </div>
        </section>

    </main>

    <!-- 푸터 -->
    <footer class="gradient-bg text-white text-center p-6 mt-12">
        <p>&copy; 2024 Kimonping Fan Page. All rights reserved.</p>
    </footer>

</body>
</html>
