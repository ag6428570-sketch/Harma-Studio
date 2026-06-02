<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Roblox 战争大亨 · 派系历史与任务站</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        darkBg: '#090d16',
                        darkCard: '#131926',
                        accentBlue: '#3b82f6',
                        accentPurple: '#a855f7',
                        accentPink: '#ec4899',
                    }
                }
            }
        }
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* ========== 主界面样式（保持不变） ========== */
        .gradient-text {
            background: linear-gradient(135deg, #ffffff 30%, #a5b4fc 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        html {
            scroll-behavior: smooth;
        }
        body {
            background: radial-gradient(circle at 20% 30%, rgba(10, 20, 30, 0.95), #020617);
            min-height: 100vh;
            font-family: 'Segoe UI', system-ui, sans-serif;
            margin: 0;
            position: relative;
        }
        /* 主界面玻璃卡片样式 */
        .glass-card {
            background: rgba(18, 25, 45, 0.65);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(59, 130, 246, 0.25);
            border-radius: 24px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
            transition: all 0.2s ease;
        }
        .glass-card:hover {
            border-color: rgba(59, 130, 246, 0.6);
            background: rgba(18, 25, 45, 0.75);
        }
        nav.glass-nav {
            background: rgba(8, 12, 22, 0.7);
            backdrop-filter: blur(12px);
            border-bottom: 1px solid rgba(59, 130, 246, 0.3);
        }
        .social-link-card {
            background: rgba(18, 25, 45, 0.6);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.2s;
            border-radius: 12px;
            padding: 16px;
            display: flex;
            align-items: center;
            color: white;
            text-decoration: none;
            margin-bottom: 12px;
        }
        .social-link-card:hover {
            background: rgba(30, 41, 59, 0.8);
            border-color: #3b82f6;
        }
        .history-scroll::-webkit-scrollbar,
        .achievement-scroll::-webkit-scrollbar {
            width: 4px;
        }
        .history-scroll::-webkit-scrollbar-track,
        .achievement-scroll::-webkit-scrollbar-track {
            background: #1e293b;
            border-radius: 10px;
        }
        .history-scroll::-webkit-scrollbar-thumb,
        .achievement-scroll::-webkit-scrollbar-thumb {
            background: #3b82f6;
            border-radius: 10px;
        }
        .era-badge {
            background: rgba(59, 130, 246, 0.2);
            backdrop-filter: blur(4px);
            border: 1px solid rgba(59, 130, 246, 0.4);
        }
        .achievement-modal-content {
            transition: transform 0.2s ease-out, opacity 0.2s ease;
            transform: scale(0.95);
            opacity: 0;
        }
        .achievement-modal-content.show {
            transform: scale(1);
            opacity: 1;
        }
        .achievement-item {
            background: rgba(15, 20, 32, 0.7);
            backdrop-filter: blur(4px);
            border-radius: 12px;
            padding: 8px 12px;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 12px;
            transition: all 0.2s;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .achievement-item:hover {
            background: rgba(26, 34, 52, 0.85);
            border-color: #3b82f6;
        }
        .achievement-item i {
            font-size: 20px;
            width: 32px;
            text-align: center;
            color: #facc15;
        }
        .achievement-info {
            flex: 1;
        }
        .achievement-name {
            font-weight: bold;
            font-size: 14px;
            color: #fbbf24;
        }
        .achievement-desc {
            font-size: 11px;
            color: #fde047;
        }
        .achievement-date {
            font-size: 10px;
            color: #5b6e8c;
        }
        .easter-egg-bg {
            background: rgba(0, 0, 0, 0.75);
            backdrop-filter: blur(12px);
        }
        .clover-orange-bg {
            background: linear-gradient(135deg, #f97316cc, #ea580ccc);
            backdrop-filter: blur(4px);
        }
        .geoffrey-avatar {
            transition: all 0.3s ease;
            filter: drop-shadow(0 0 8px rgba(59, 130, 246, 0.5));
        }
        .avatar-glow {
            animation: gentleGlow 3s infinite alternate;
        }
        @keyframes gentleGlow {
            0% { box-shadow: 0 0 5px rgba(59, 130, 246, 0.3); border-color: rgba(59, 130, 246, 0.5);}
            100% { box-shadow: 0 0 20px rgba(59, 130, 246, 0.8); border-color: #3b82f6;}
        }
        .float-slow {
            animation: float 4s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-6px); }
            100% { transform: translateY(0px); }
        }
        .code-typing {
            border-right: 2px solid #3b82f6;
            white-space: nowrap;
            overflow: hidden;
            animation: blink-caret 0.75s step-end infinite;
        }
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #3b82f6; }
        }
        .keyboard-glow {
            animation: keyFlash 0.8s infinite ease-in-out;
        }
        @keyframes keyFlash {
            0%,100% { text-shadow: 0 0 2px #3b82f6; opacity: 0.7; }
            50% { text-shadow: 0 0 12px #a855f7,0 0 5px #3b82f6; opacity: 1; }
        }
        .typing-dot {
            display: inline-block;
            width: 8px;
            height: 8px;
            background-color: #3b82f6;
            border-radius: 50%;
            animation: pulse 1.2s infinite;
        }
        @keyframes pulse {
            0%,100% { opacity: 0.3; transform: scale(0.8); }
            50% { opacity: 1; transform: scale(1.2); }
        }
        .heptagram-2d {
            display: inline-block;
            animation: spinFlat 12s infinite linear;
        }
        @keyframes spinFlat {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .achievement-toast {
            position: fixed;
            top: 80px;
            right: 20px;
            z-index: 1100;
            background: rgba(30, 41, 59, 0.9);
            backdrop-filter: blur(12px);
            border-left: 5px solid #fbbf24;
            border-radius: 12px;
            padding: 12px 20px;
            box-shadow: 0 10px 25px -5px rgba(0,0,0,0.5);
            display: flex;
            align-items: center;
            gap: 12px;
            transform: translateX(400px);
            transition: transform 0.3s ease;
            border: 1px solid #fbbf24;
        }
        .achievement-toast.show {
            transform: translateX(0);
        }
        .task-card {
            background: rgba(18, 25, 45, 0.7);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(59, 130, 246, 0.2);
            border-radius: 16px;
            transition: all 0.2s;
        }
        .task-card:hover {
            border-color: #3b82f6;
            background: rgba(18, 25, 45, 0.85);
            transform: translateY(-2px);
        }
        /* ========== 登录模态框深色风格（右侧无文字，使用用户名） ========== */
        .auth-modal-new {
            max-width: 500px;
            width: 90%;
            background: rgba(0, 0, 0, 0.85);
            backdrop-filter: blur(20px);
            border-radius: 32px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
            overflow: hidden;
            font-family: 'Inter', system-ui, sans-serif;
            border: 1px solid rgba(255, 255, 255, 0.15);
        }
        .auth-left {
            padding: 2.5rem;
        }
        .auth-tab-new {
            display: inline-block;
            font-size: 1.1rem;
            font-weight: 500;
            padding-bottom: 0.5rem;
            margin-right: 1.5rem;
            cursor: pointer;
            color: #9ca3af;
            border-bottom: 2px solid transparent;
            transition: all 0.2s;
        }
        .auth-tab-new.active {
            color: #3b82f6;
            border-bottom-color: #3b82f6;
        }
        .auth-input-new {
            width: 100%;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid #374151;
            border-radius: 14px;
            padding: 12px 16px;
            color: white;
            font-size: 0.95rem;
            transition: all 0.2s;
        }
        .auth-input-new:focus {
            outline: none;
            border-color: #3b82f6;
            box-shadow: 0 0 0 2px rgba(59,130,246,0.2);
        }
        .auth-btn-new {
            width: 100%;
            background: #3b82f6;
            border: none;
            border-radius: 40px;
            padding: 12px;
            font-weight: 600;
            color: white;
            font-size: 1rem;
            transition: all 0.2s;
            cursor: pointer;
        }
        .auth-btn-new:hover {
            background: #2563eb;
            transform: scale(1.02);
        }
        .checkbox-new {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.85rem;
            color: #9ca3af;
        }
        .checkbox-new input {
            width: 16px;
            height: 16px;
            accent-color: #3b82f6;
        }
        /* 动态背景层（白色像素雨） */
        .dynamic-bg-layer {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            pointer-events: none;
        }
        .dynamic-bg-layer canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0.4;
        }
        .grid-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
            background-size: 40px 40px;
            animation: gridMove 20s linear infinite;
        }
        @keyframes gridMove {
            0% { transform: translate(0, 0); }
            100% { transform: translate(40px, 40px); }
        }
        .pixel-noise {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: repeating-linear-gradient(0deg, rgba(255,255,255,0.02) 1px, transparent 2px);
            pointer-events: none;
        }
        .dynamic-hidden {
            display: none !important;
        }
    </style>
</head>
<body>
    <!-- 动态像素背景（白色） -->
    <div id="dynamicBg" class="dynamic-bg-layer">
        <canvas id="pixel-canvas"></canvas>
        <div class="grid-overlay"></div>
        <div class="pixel-noise"></div>
    </div>

    <!-- 深色登录/注册模态框（使用用户名） -->
    <div id="auth-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/60 backdrop-blur-sm">
        <div class="auth-modal-new">
            <div class="auth-left">
                <div class="mb-6">
                    <span id="login-tab-new" class="auth-tab-new active">登录</span>
                    <span id="register-tab-new" class="auth-tab-new">注册</span>
                </div>
                <!-- 登录表单 -->
                <div id="login-form-new" class="space-y-4">
                    <div>
                        <input type="text" id="login-username" class="auth-input-new" placeholder="用户名">
                    </div>
                    <div>
                        <input type="password" id="login-password" class="auth-input-new" placeholder="密码">
                    </div>
                    <div class="flex justify-between items-center">
                        <label class="checkbox-new">
                            <input type="checkbox" id="remember-me"> <span>记住我</span>
                        </label>
                    </div>
                    <button id="login-btn-new" class="auth-btn-new">登录</button>
                </div>
                <!-- 注册表单 -->
                <div id="register-form-new" class="space-y-4 hidden">
                    <div>
                        <input type="text" id="reg-username" class="auth-input-new" placeholder="用户名">
                    </div>
                    <div>
                        <input type="password" id="reg-password" class="auth-input-new" placeholder="密码">
                    </div>
                    <div>
                        <input type="password" id="reg-confirm" class="auth-input-new" placeholder="确认密码">
                    </div>
                    <button id="register-btn-new" class="auth-btn-new">注册</button>
                </div>
            </div>
        </div>
    </div>

    <!-- ========== 主页面内容（完全恢复原样） ========== -->
    <div id="main-app" style="display: none;">
        <nav class="sticky top-0 z-40 glass-nav px-4 py-3">
            <div class="max-w-6xl mx-auto flex items-center justify-between">
                <div onclick="window.scrollTo({top: 0, behavior: 'smooth'})" class="flex items-center space-x-2 cursor-pointer transition active:opacity-70">
                    <span class="text-blue-500 text-xl font-bold">⚔</span>
                    <span class="font-extrabold tracking-wider text-white">Roblox 战争大亨</span>
                </div>
                <div class="flex items-center gap-3">
                    <button onclick="openTrackerModal()" class="relative px-3 py-1.5 text-xs font-semibold bg-blue-600/20 text-blue-400 border border-blue-500/30 rounded-lg hover:bg-blue-600/30 transition">
                        <i class="fa-solid fa-bookmark mr-1"></i> 我的追踪
                        <span id="tracker-badge" class="absolute -top-1.5 -right-1.5 bg-red-500 text-white text-[10px] w-4 h-4 rounded-full flex items-center justify-center hidden">0</span>
                    </button>
                    <button onclick="openAchievementModal()" class="px-3 py-1.5 text-xs font-semibold bg-amber-600/20 text-amber-400 border border-amber-500/30 rounded-lg hover:bg-amber-600/30 transition">
                        <i class="fa-solid fa-trophy mr-1"></i> 成就
                    </button>
                    <button id="logout-btn" class="px-3 py-1.5 text-xs font-semibold bg-red-600/20 text-red-400 border border-red-500/30 rounded-lg hover:bg-red-600/30 transition">
                        <i class="fa-solid fa-sign-out-alt mr-1"></i> 登出
                    </button>
                </div>
            </div>
        </nav>

        <header class="relative pt-10 pb-6 px-4 text-center">
            <div class="max-w-3xl mx-auto space-y-3">
                <h1 class="text-3xl md:text-5xl font-black tracking-tight text-white">⚔ <span class="gradient-text">Roblox 战争大亨</span></h1>
                <p class="text-xs md:text-sm text-gray-400 max-w-lg mx-auto">现代化任务网站 | 坦克 | 飞机 | 直升机 | 船舰</p>
            </div>
            <div class="max-w-md mx-auto mt-6 px-2">
                <div class="flex items-center gap-2">
                    <input type="text" id="search-input" oninput="searchTasks()" placeholder="输入「任务/载具名称」进行精确搜索..." class="w-full bg-darkCard border border-gray-700 rounded-xl py-3 px-4 text-sm text-white placeholder-gray-500 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition">
                    <button onclick="showEasterEggPage(); unlockAchievement('easter_egg')" class="bg-gradient-to-r from-amber-500/20 to-orange-500/20 hover:from-amber-500/40 hover:to-orange-500/40 border border-amber-500/50 rounded-xl py-3 px-4 transition-all duration-300"><i class="fa-solid fa-dragon text-amber-400 text-xl"></i></button>
                </div>
                <div id="search-results-info" class="text-xs text-blue-400 mt-2 text-left hidden"></div>
            </div>
        </header>

        <main class="max-w-6xl mx-auto px-4 mt-2 space-y-10">
            <!-- 任务分类快速跳转 -->
            <section id="category-selector" class="space-y-4">
                <h2 class="text-base font-bold text-gray-400">选择任务分类</h2>
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-4">
                    <div onclick="scrollToSection('tank-section'); unlockAchievement('tank_category')" class="rounded-2xl bg-gradient-to-br from-blue-600 to-indigo-700 p-4 cursor-pointer transform hover:-translate-y-1 transition duration-300 shadow-lg"><div class="space-y-1 text-white"><h3 class="text-lg font-black">坦克任务</h3><p class="text-blue-100 text-xs opacity-90">16 个项目</p></div></div>
                    <div onclick="scrollToSection('helicopter-section'); unlockAchievement('helicopter_category')" class="rounded-2xl bg-gradient-to-br from-purple-600 to-violet-700 p-4 cursor-pointer transform hover:-translate-y-1 transition duration-300 shadow-lg"><div class="space-y-1 text-white"><h3 class="text-lg font-black">直升机任务</h3><p class="text-purple-100 text-xs opacity-90">10 个项目</p></div></div>
                    <div onclick="scrollToSection('airplane-section'); unlockAchievement('airplane_category')" class="rounded-2xl bg-gradient-to-br from-pink-600 to-rose-700 p-4 cursor-pointer transform hover:-translate-y-1 transition duration-300 shadow-lg"><div class="space-y-1 text-white"><h3 class="text-lg font-black">飞机任务</h3><p class="text-pink-100 text-xs opacity-90">17 个项目</p></div></div>
                    <div onclick="scrollToSection('hovercraft-section'); unlockAchievement('hovercraft_category')" class="rounded-2xl bg-gradient-to-br from-cyan-600 to-teal-700 p-4 cursor-pointer transform hover:-translate-y-1 transition duration-300 shadow-lg"><div class="space-y-1 text-white"><h3 class="text-lg font-black">悬空载具</h3><p class="text-cyan-100 text-xs opacity-90">6 个项目</p></div></div>
                    <div onclick="scrollToSection('ship-section'); unlockAchievement('ship_category')" class="rounded-2xl bg-gradient-to-br from-emerald-600 to-teal-850 p-4 cursor-pointer transform hover:-translate-y-1 transition duration-300 shadow-lg"><div class="space-y-1 text-white"><h3 class="text-lg font-black">船舰与潜艇</h3><p class="text-emerald-100 text-xs opacity-90">7 个项目</p></div></div>
                </div>
                <div class="mt-4"><a href="https://wttd.trade/" target="_blank" class="group relative overflow-hidden rounded-2xl bg-gradient-to-br from-slate-700 to-slate-900 p-4 cursor-pointer transform hover:-translate-y-1 transition duration-300 shadow-lg block max-w-xs text-center"><div class="text-white"><h3 class="text-lg font-black">⚔ 交易市场 (wttd.trade)</h3></div></a></div>
            </section>

            <!-- 官方社群区块 -->
            <section id="social-section" class="max-w-xl space-y-4">
                <h2 class="text-lg font-bold text-gray-300">官方社群</h2>
                <div class="space-y-3">
                    <a href="https://roblox.com/join/y54bw" target="_blank" class="social-link-card"><i class="fa-solid fa-gamepad mr-4 text-blue-500 text-xl"></i> War Tycoon (Roblox)</a>
                    <a href="https://discord.gg/nFeyYDySug" target="_blank" class="social-link-card"><i class="fa-brands fa-discord mr-4 text-indigo-400 text-xl"></i> Discord</a>
                    <a href="https://tiktok.com/@wartycoon" target="_blank" class="social-link-card"><i class="fa-brands fa-tiktok mr-4 text-pink-500 text-xl"></i> Tik Tok</a>
                    <a href="https://x.com/WarTycoonRBLX" target="_blank" class="social-link-card"><i class="fa-brands fa-x-twitter mr-4 text-white text-xl"></i> X (Twitter)</a>
                    <a href="https://www.youtube.com/@WarTycoonRBLX" target="_blank" class="social-link-card"><i class="fa-brands fa-youtube mr-4 text-red-500 text-xl"></i> YouTube</a>
                </div>
            </section>

            <!-- 派系历史完整版 -->
            <hr id="faction-hr" class="border-gray-800 my-6" />
            <section id="faction-section" class="glass-card p-5 md:p-6 space-y-5">
                <div class="flex flex-wrap items-center justify-between gap-2 border-b border-gray-700 pb-3"><h2 class="text-xl md:text-2xl font-black text-white flex items-center gap-2"><i class="fa-solid fa-landmark text-blue-400"></i> 派系 · 大兴王朝历史<span class="text-xs bg-blue-500/20 text-blue-300 px-2 py-0.5 rounded-full">2023-至今</span></h2></div>
                <div class="flex flex-wrap gap-3 text-sm"><span class="era-badge px-3 py-1 rounded-full text-blue-300 text-xs font-mono">🏛️ 【古代史】2023.01.29-2024.7.14</span><span class="era-badge px-3 py-1 rounded-full text-purple-300 text-xs font-mono">📜 【近代史】2025.06.27-2026.1.20</span><span class="era-badge px-3 py-1 rounded-full text-pink-300 text-xs font-mono">⚡ 【现代史】2026.02.11-至今</span><span class="bg-gradient-to-r from-amber-500/20 to-rose-500/20 border border-amber-500/40 px-3 py-1 rounded-full text-amber-300 text-xs font-bold">✿ BNS鼎盛时期 2025.08.21-2026.01.05 ✿</span></div>
                <div class="history-scroll max-h-[480px] overflow-y-auto pr-2 rounded-lg"><div class="space-y-2 text-sm leading-relaxed text-gray-300 font-medium"><div class="space-y-1.5"><p class="text-cyan-400 font-bold mt-1">❀ 2023年 (云墨十三元年):</p><div class="pl-3 border-l-2 border-blue-500/40 space-y-1"><p>01.29夜晚 - 墨墨创建了[Bomb]Nuclear Strike派系(简称BNS)</p><p>02.05 - 墨墨因敏感词系统被封，于是退游去玩MC</p><p class="text-gray-500">【2023.02.06至2024.03.30 不详】</p></div><p class="text-cyan-400 font-bold mt-3">❀ 2024年 (云墨十四元年):</p><div class="pl-3 border-l-2 border-purple-500/40 space-y-1"><p>03.31 - 墨墨因无聊下回了Roblox，并注册了一个新号继续游玩战争大亨</p><p>04.03夜晚 - 墨墨重建[Bomb]Nuclear Strike派系(简称BNS)</p><p>04.04上午 - BNS迎来第一位成员“456”，并进行了第一次团建</p><p>04.06 - 一位对BNS影响重大的人士加入了我们</p><p>04.15 - BNS打赢了对外抗战(征战全服)</p><p>04.19 - 墨墨决定每周举行一次演习，为提升派系实力</p><p>04.27 - BNS来了一位实力强悍的俄罗斯玩家</p><p>05.01 - 欢庆劳动节，墨墨带领BNS成员当志愿者给萌新送零件/油桶</p><p>06.22 - 墨墨貌似遇到了深厚的友情(暂时退游)</p><p>07.04 - 墨墨第一次交到好朋友(暂时退游)</p><p>07.09 - 墨墨与那个人绝交</p><p>07.10 - 墨墨退游常驻Ro市人生</p><p>07.14 - 第二届盟大会议决定，BNS开始闭关锁国</p><p class="text-gray-500">【2024.07.15至2025.06.26 不详】</p></div><p class="text-cyan-400 font-bold mt-3">❀ 2025年 (云墨十五元年):</p><div class="pl-3 border-l-2 border-pink-500/40 space-y-1"><p>06.27 - 墨墨被表白</p><p class="text-gray-500">【2025.06.28至07.17 不详】</p><p>07.18凌晨 - 墨墨和对象分手</p><p>07.19 - 墨墨回归Roblox</p><p>07.22 - 墨墨回归战争大亨</p><p>07.29 - 沫梦加入BNS</p><p>08.21 - 墨墨创建了BNS交流群(具有深远意义)</p><p>08.22 - 墨墨创建了BNS频道</p><p>08.23 - BNS决定带成员无条件保护萌新并扶持他们发育——帮助刷任务&amp;送油桶/零件</p><p>08.25 - 沫梦开学</p><p>08.26 - UU加入了BNS</p><p>09.01 - BNS成员陷入开学狂潮</p><p>09.13 - 诺晨加入了BNS</p><p>09.18 - Дормер加入了BNS</p><p>10.02 - szhk加入了BNS</p><p>10.05 - UU被通缉，墨墨率领17位成员将UU打至退游</p><p>10.06 - 墨墨创建了BNS网站</p><p>10.07 - BNS网站烂尾废弃</p><p>10.11 - 濠创建了BNS派系HTML格式网页</p><p>10.12 - 墨墨正式接替濠更新网页</p><p>10.15 - 墨墨创建蓝狐俱乐部™️，专门负责拍摄</p><p>10.17 - BNS被联合部队嘲讽</p><p>10.28 - BNS通缉“[联合部队]联合军校”派系</p><p>11.13 - BNS大部分成员转MC</p><p>11.21 - 墨墨转MC</p><p>12.03 - BNS派系群网页下架</p><p>12.14 - BNS派系网页替代BNS派系群网页</p><p>12.21 - 墨墨决定肝重生，BNS大部分成员陷入肝重生狂潮</p><p>12.29 - BNS团建(影响深刻)</p><p>12.31 - 跨年夜BNS组织了赛车比赛庆祝</p></div><p class="text-cyan-400 font-bold mt-3">❀ 2026年 (云墨十六元年):</p><div class="pl-3 border-l-2 border-emerald-500/40 space-y-1"><p>01.03 - 小米加入了BNS</p><p>01.05 - 濠暂退战争大亨</p><p>01.08 - BNS第二次大型军事演习</p><p>01.09 - 墨墨无聊算了一下重生要多少钱(精确到个位数)</p><p>01.13 - BNS确定了单兵榜</p><p>01.18 - 墨墨被SMDG二军营长看上，将派系暂时转给了濠，加入了SMDG二军</p><p>01.19 - BNS派系群正式改为Momo粉丝群三群，BNS群(几乎荒废)</p><p>01.20 - 墨墨结束了1000多天的统治</p><p class="text-gray-400">【2026.01.20至2026.02.10 衰落】</p><p>02.11 - BNS被SMDG二军TVO墨墨收入，墨墨创建了BNS新群，墨墨恢复统治</p><p class="text-gray-400">【2026.02.12至2026.04.07 渐渐强大】</p><p>04.08 - BNS改为TVO第三自治营</p><p>04.15 - BNS改为TVO第二自治营</p><p>04.18 - 墨墨改BNS为墨墨の窝</p><p>04.19 - 貅猫加入了BNS；同日BNS取消自治，改为TVO第二综合营</p><p>04.20 - 72X加入了BNS</p><p>04.22 - ty加入了BNS</p><p>04.25 - 肝帝和麻蛋加入了BNS</p><p>04.26 - emm,商家和WuYaoCai加入了BNS</p><p>04.27 - 蓝狐工作室™️正式改为Harma工作室™️</p><p>05.01 - KZZ和乔然加入了BNS</p><p>05.02 - sea加入了BNS</p><p>05.03 - 墨墨组织TVO拍摄宣传片但拍摄不佳(几乎不能用)</p><p>05.04 - 跳进染加入了BNS</p><p>05.05 - BNS团建吃火锅；墨墨淡游转营长给貅猫，副营长为肝帝</p><p>05.09 - 外星人侮辱墨墨，被拉入黑名单</p><p>05.10 - 72X叛变退出</p><p>05.16 - 秋月加入了BNS；同日BNS举行了第二届赛车比赛(未成功举行)；墨墨玩真心话大冒险导致红温</p><p class="text-yellow-300 text-xs mt-2">✨ 敬请期待 ✨</p></div></div></div></div>
                <div class="text-right text-[11px] text-gray-500 border-t border-gray-700 pt-3 mt-1"><i class="fa-regular fa-clock"></i> 派系纪实 · 源于BNS / 大兴王朝编年史</div>
            </section>

            <!-- 关于我们完整版 -->
            <hr id="about-hr" class="border-gray-800 my-6" />
            <section id="aboutus-section" class="glass-card p-5 md:p-6">
                <div class="flex items-center gap-2 border-b border-indigo-500/30 pb-3 mb-4"><i class="fa-regular fa-star-of-life text-indigo-400 text-xl"></i><h2 class="text-xl md:text-2xl font-black text-white tracking-tight">关于我们 · 重生之翼</h2></div>
                <div class="space-y-4 text-gray-300">
                    <p class="bg-black/20 rounded-xl p-4 border-l-4 border-blue-500 text-sm leading-relaxed">✿ <span class="font-bold text-blue-300">2026.05.26</span> 管理员濠制作了派系网页2.0 (重制版)，墨墨决定重新更新派系网页。<br>因1.0的经验，2.0的功能将更加全面，同时档案大小也是指数增加，我们将推翻旧的UI设计，制定一个全新的UI以及动画设计等，理想情况会加入注册登录功能。<br>后续我们团队会想办法将其弄成软件或网站，敬请期待 ✨<br>如果你也想为这个做贡献，就加入我们 Harma工作室™️ 吧！</p>
                    <div class="flex flex-wrap gap-3 text-sm font-mono"><span class="bg-pink-500/10 text-pink-300 px-3 py-1 rounded-full text-xs">💖 “If you love Harma, I love you!”</span><span class="bg-amber-500/10 text-amber-300 px-3 py-1 rounded-full text-xs">🍑 “If you love Momo, I love you!”</span></div>
                    <div class="pt-2 space-y-1 text-sm border-t border-gray-700/70 mt-3"><p class="flex items-center gap-2"><i class="fa-regular fa-copyright text-gray-400"></i> <strong>Harma工作室™️</strong> ‖ 版权归 Harma™️ 所有</p><p class="text-gray-400 text-xs">Harma工作室™️ [前蓝狐(Blue Fox工作室™️)]</p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mt-3 bg-black/20 p-3 rounded-xl"><div class="flex items-center gap-2 text-sm"><i class="fa-regular fa-envelope text-blue-400"></i> <span class="break-all">ag6428570@gmail.com</span> <span class="text-blue-300 text-xs">—— GeoffreyLei (技术人员)</span></div><div class="flex items-center gap-2 text-sm"><i class="fa-regular fa-envelope text-pink-400"></i> <span class="break-all">1710278186@qq.com</span> <span class="text-pink-300 text-xs">—— 𝑴𝒐𝒎𝒐 (CEO)</span></div></div></div>
                    <p class="text-xs text-gray-500 text-right italic">「千年王朝之梦，战火淬炼新生」</p>
                </div>
            </section>

            <!-- 任务列表渲染区 -->
            <hr id="section-divider" class="border-gray-800 my-6" />
            <div id="tasks-container" class="space-y-12"></div>
        </main>
    </div>

    <!-- 成就模态框 -->
    <div id="achievement-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/80 backdrop-blur-sm opacity-0 pointer-events-none transition-all duration-200">
        <div class="bg-darkCard border border-gray-700 w-full max-w-md rounded-2xl shadow-2xl overflow-hidden transform transition-all duration-200 achievement-modal-content backdrop-blur-xl">
            <div class="p-5">
                <div class="flex justify-between items-center mb-3"><h3 class="text-lg font-bold text-white flex items-center gap-2"><i class="fa-solid fa-trophy text-yellow-500"></i> 我的成就</h3><button onclick="closeAchievementModal()" class="text-gray-400 hover:text-white text-xl">×</button></div>
                <div id="achievement-list" class="achievement-scroll space-y-2 max-h-96 overflow-y-auto pr-1"></div>
                <div class="mt-3 text-right text-[10px] text-gray-500">成就将自动保存</div>
            </div>
        </div>
    </div>

    <!-- 彩蛋页面（完整保留） -->
    <div id="easteregg-page" class="fixed inset-0 z-50 bg-darkBg easter-egg-bg hidden overflow-y-auto">
        <div class="min-h-screen flex flex-col items-center justify-center p-6 relative">
            <div class="max-w-5xl w-full space-y-10">
                <div class="glass-card p-6 shadow-2xl">
                    <div class="bg-gradient-to-r from-slate-800 to-gray-900 px-4 py-2 border-b border-indigo-500/30 flex items-center justify-between rounded-t-2xl">
                        <div class="flex items-center gap-3"><button onclick="hideEasterEggPage()" class="flex items-center gap-1 text-gray-300 hover:text-white transition text-xs bg-gray-700/50 hover:bg-gray-600/50 rounded-md px-2 py-1"><i class="fa-solid fa-arrow-left text-[10px]"></i><span>返回主页</span></button><div class="flex items-center gap-2"><i class="fa-solid fa-terminal text-cyan-400 text-sm"></i><span class="font-mono text-cyan-300 text-xs font-bold">~/developer_den</span></div></div>
                        <div class="text-[10px] text-gray-400"><span>© 彩蛋模式·致敬创作者</span></div>
                    </div>
                    <div class="p-6">
                        <div class="flex flex-col md:flex-row gap-6">
                            <div class="md:w-1/3 flex flex-col items-center justify-center text-center space-y-3">
                                <div class="relative geoffrey-avatar float-slow"><div class="w-40 h-40 rounded-full bg-gradient-to-br from-cyan-500 to-blue-600 flex items-center justify-center avatar-glow"><i class="fa-solid fa-user-ninja text-6xl text-white"></i></div><div class="absolute -bottom-1 -right-1 bg-blue-500/60 rounded-full p-1.5"><i class="fa-solid fa-microchip text-white text-sm"></i></div></div>
                                <div><p class="font-mono text-cyan-300 text-sm">✨ 首席架构师 ✨</p><p class="text-2xl font-bold text-white">GeoffreyLei</p><p class="text-blue-300 text-sm">「键盘为剑，代码为盾」</p></div>
                            </div>
                            <div class="md:w-2/3 space-y-4">
                                <div class="bg-black/40 rounded-xl p-4 border border-gray-700"><div class="flex items-center gap-2 mb-3"><div class="w-3 h-3 rounded-full bg-red-500"></div><div class="w-3 h-3 rounded-full bg-yellow-500"></div><div class="w-3 h-3 rounded-full bg-green-500"></div><span class="text-xs text-gray-400 ml-2">~/war-tycoon/secret_script.js</span></div><div class="font-mono text-sm space-y-1"><p class="text-cyan-400"><span class="text-pink-400">const</span> <span class="text-yellow-300">coder</span> = {</p><p class="text-gray-300 pl-4">name: <span class="text-green-300">"GeoffreyLei"</span>,</p><p class="text-gray-300 pl-4">passion: <span class="text-green-300">"Open Source & Game Dev"</span>,</p><p class="text-gray-300 pl-4">working: <span class="text-green-300">true</span>,</p><p class="text-gray-300 pl-4">skill: [<span class="text-blue-300">"HTML"</span>, <span class="text-blue-300">"CSS"</span>, <span class="text-blue-300">"JS"</span>, <span class="text-blue-300">"Tailwind"</span>]</p><p class="text-cyan-400">};</p><p class="text-gray-400 mt-2"><span class="text-purple-400">function</span> <span class="text-yellow-300">buildEasterEgg</span>() {</p><p class="text-gray-400 pl-4"><span class="text-green-300">console</span>.<span class="text-yellow-300">log</span>(<span class="text-orange-300">"🔒 秘密基地已解锁 🔒"</span>);</p><p class="text-gray-400 pl-4"><span class="text-blue-300">return</span> <span class="text-green-300">"在电脑桌前编写下一段传奇"</span>;</p><p class="text-purple-400">}</p><div class="code-typing inline-block text-blue-400 text-xs mt-2">正在部署新功能...</div></div></div>
                                <div class="bg-gradient-to-r from-indigo-950/40 to-purple-950/40 rounded-xl p-4 border border-indigo-400/30"><div class="flex items-center gap-2 border-b border-indigo-400/20 pb-2 mb-3"><i class="fa-solid fa-video text-pink-400"></i><span class="text-xs font-bold text-indigo-300">LIVE · 动态编码室</span><span class="typing-dot"></span></div><div class="space-y-2 text-xs font-mono"><p class="text-green-400"><span class="text-gray-300">$&gt;</span> 编译战争模块...</p><p class="text-cyan-300 animate-pulse">[INFO] 正在加载派系引擎</p><p class="text-yellow-300"><span class="text-gray-500">&gt;&gt;</span> 敲击键盘: <span class="inline-block keyboard-glow">████████░░ 78%</span></p><div class="flex gap-1 mt-1"><div class="h-1 w-6 bg-blue-500 rounded-sm animate-pulse"></div><div class="h-1 w-8 bg-purple-500 rounded-sm animate-pulse delay-75"></div><div class="h-1 w-4 bg-pink-500 rounded-sm animate-pulse delay-150"></div></div><p class="text-gray-400 flex items-center gap-1">🔒 <span>coding in progress</span> <span class="w-1.5 h-1.5 bg-green-400 rounded-full animate-pulse"></span></p><p class="text-gray-500 text-[10px] italic">AI生成</p></div><div class="text-center text-[10px] text-gray-400 mt-3 border-t border-indigo-500/20 pt-2">🔍 实时动态 · 键盘与灵感共振</div></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- CloverMo 区域 -->
                <div class="glass-card p-6 flex flex-col items-center border border-pink-500/30">
                    <div class="relative mb-4"><div class="w-48 h-48 rounded-full clover-orange-bg flex items-center justify-center shadow-xl" style="box-shadow: 0 0 20px rgba(251,146,60,0.6);"><div class="heptagram-2d"><svg width="180" height="180" viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg"><g stroke="#666666" stroke-width="12" fill="none" stroke-linecap="round" stroke-linejoin="round"><polyline points="200,40 337.5,107.5 326.4,262.5 142.5,357.5 57.5,197.5 142.5,42.5 326.4,137.5 57.5,262.5 142.5,107.5 337.5,262.5 57.5,137.5 326.4,42.5 142.5,262.5 200,40"/></g></svg></div></div></div>
                    <div class="text-center space-y-2"><p class="font-mono text-pink-300 text-sm">👑 首席执行官 👑</p><p class="text-2xl font-bold text-white">CloverMo</p><p class="text-amber-300 text-sm">Harma工作室™️ CEO</p><div class="mt-3 px-4 py-2 bg-amber-500/20 rounded-full inline-block border border-amber-500/30"><p class="text-amber-300 text-xs italic">「执码领团，破界拓新」</p></div></div>
                </div>
                <div class="text-center text-[10px] text-gray-500 pt-2"><i class="fa-solid fa-dragon"></i> 彩蛋·致敬每一位创作者 | Harma工作室</div>
            </div>
        </div>
    </div>

    <!-- 任务详情与追踪模态框 -->
    <div id="detail-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/80 backdrop-blur-sm opacity-0 pointer-events-none transition-all duration-200"><div class="bg-darkCard border border-gray-700 w-full max-w-sm rounded-2xl shadow-2xl overflow-hidden transform scale-95 transition-all duration-200"><div id="modal-header-accent" class="h-2 w-full bg-blue-500"></div><div class="p-6 space-y-4"><div class="flex justify-between items-start"><div><span id="modal-category" class="text-xs font-semibold px-2 py-0.5 rounded bg-gray-800 text-gray-400">分类</span><h3 id="modal-title" class="text-xl font-bold text-white mt-1">名称</h3></div><button onclick="closeModal()" class="text-gray-400 hover:text-white text-xl">×</button></div><div class="bg-gray-900/80 border border-gray-800 rounded-xl p-4"><p class="text-xs text-gray-500 uppercase tracking-wider mb-1 font-bold">解锁获取条件</p><p id="modal-requirement" class="text-sm text-gray-100 font-semibold leading-relaxed">要求详情</p></div><div class="flex space-x-2 pt-2"><button id="modal-track-btn" onclick="toggleTrackCurrent()" class="flex-1 bg-blue-600 hover:bg-blue-500 text-white font-bold py-2 px-4 rounded-xl text-sm transition">加入追踪</button><button onclick="copyCurrentRequirement()" class="bg-gray-800 hover:bg-gray-700 text-gray-200 font-bold py-2 px-4 rounded-xl text-sm transition">复制</button></div><p id="modal-toast" class="text-xs text-center text-green-400 font-medium opacity-0 transition-opacity duration-200"></p></div></div></div>
    <div id="tracker-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/80 backdrop-blur-sm opacity-0 pointer-events-none transition-all duration-200"><div class="bg-darkCard border border-gray-700 w-full max-w-md rounded-2xl shadow-2xl overflow-hidden transform scale-95 transition-all duration-200"><div class="p-6 space-y-4"><div class="flex justify-between items-center"><h3 class="text-lg font-bold text-white">我的资料追踪清单</h3><button onclick="closeTrackerModal()" class="text-gray-400 hover:text-white text-xl">×</button></div><div id="tracker-list-content" class="space-y-2 max-h-60 overflow-y-auto pr-1"></div><div class="border-t border-gray-800 pt-4 flex justify-between items-center"><span class="text-xs text-gray-500">提示：资料已储存于浏览器缓存中。</span><button onclick="clearAllTracked()" class="text-xs text-red-400 hover:text-red-300">全部清除</button></div></div></div></div>

    <script>
        // ==================== 像素风格动态背景（白色方块雨） ====================
        const canvas = document.getElementById('pixel-canvas');
        let ctx, width, height, columns, drops, pixelSize = 10;
        
        function initPixelCanvas() {
            if (!canvas) return;
            ctx = canvas.getContext('2d');
            width = window.innerWidth;
            height = window.innerHeight;
            canvas.width = width;
            canvas.height = height;
            columns = Math.floor(width / pixelSize);
            drops = new Array(columns).fill(1);
        }
        
        function drawPixelRain() {
            if (!ctx) return;
            ctx.fillStyle = "rgba(0, 0, 0, 0.1)";
            ctx.fillRect(0, 0, width, height);
            ctx.fillStyle = "#ffffff";
            for (let i = 0; i < drops.length; i++) {
                ctx.fillRect(i * pixelSize, drops[i] * pixelSize, pixelSize - 1, pixelSize - 1);
                if (drops[i] * pixelSize > height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                drops[i]++;
            }
            requestAnimationFrame(drawPixelRain);
        }
        
        function resizePixelCanvas() {
            if (!canvas) return;
            width = window.innerWidth;
            height = window.innerHeight;
            canvas.width = width;
            canvas.height = height;
            columns = Math.floor(width / pixelSize);
            drops = new Array(columns).fill(1);
        }
        
        window.addEventListener('resize', resizePixelCanvas);
        
        // ==================== 登录注册逻辑（使用用户名） ====================
        let users = JSON.parse(localStorage.getItem('war_tycoon_users')) || [];
        let isLoggedIn = localStorage.getItem('war_tycoon_logged_in') === 'true';
        
        function saveUsers() { localStorage.setItem('war_tycoon_users', JSON.stringify(users)); }
        
        function setDynamicBg(visible) {
            const bgLayer = document.getElementById('dynamicBg');
            if (bgLayer) {
                if (visible) {
                    bgLayer.classList.remove('dynamic-hidden');
                    if (!ctx) initPixelCanvas();
                    if (ctx) drawPixelRain();
                } else {
                    bgLayer.classList.add('dynamic-hidden');
                }
            }
        }
        
        function checkAuth() {
            if (!isLoggedIn) {
                document.getElementById('auth-modal').style.display = 'flex';
                document.getElementById('main-app').style.display = 'none';
                setDynamicBg(true);
                const savedUsername = localStorage.getItem('remembered_username');
                const savedPwd = localStorage.getItem('remembered_password');
                if (savedUsername) {
                    document.getElementById('login-username').value = savedUsername;
                    document.getElementById('remember-me').checked = true;
                }
                if (savedPwd) document.getElementById('login-password').value = savedPwd;
            } else {
                document.getElementById('auth-modal').style.display = 'none';
                document.getElementById('main-app').style.display = 'block';
                setDynamicBg(false);
                initAchievements();
                renderTaskSections();
                updateTrackerBadge();
            }
        }
        
        // 登录按钮
        document.getElementById('login-btn-new').addEventListener('click', () => {
            const username = document.getElementById('login-username').value.trim();
            const pwd = document.getElementById('login-password').value.trim();
            const remember = document.getElementById('remember-me').checked;
            if (!username) { alert('请输入用户名'); return; }
            if (!pwd) { alert('请输入密码'); return; }
            const user = users.find(u => u.username === username);
            if (!user) { alert('用户名不存在，请先注册'); return; }
            if (user.password !== pwd) { alert('密码错误'); return; }
            localStorage.setItem('war_tycoon_logged_in', 'true');
            localStorage.setItem('war_tycoon_user', username);
            localStorage.setItem('war_tycoon_name', user.name || username);
            if (remember) {
                localStorage.setItem('remembered_username', username);
                localStorage.setItem('remembered_password', pwd);
            } else {
                localStorage.removeItem('remembered_username');
                localStorage.removeItem('remembered_password');
            }
            alert(`欢迎回来，${username}！`);
            isLoggedIn = true;
            checkAuth();
        });
        
        // 注册按钮
        document.getElementById('register-btn-new').addEventListener('click', () => {
            const username = document.getElementById('reg-username').value.trim();
            const pwd = document.getElementById('reg-password').value.trim();
            const confirm = document.getElementById('reg-confirm').value.trim();
            if (!username) { alert('请输入用户名'); return; }
            if (!pwd) { alert('密码不能为空'); return; }
            if (pwd !== confirm) { alert('两次输入的密码不一致'); return; }
            if (users.find(u => u.username === username)) { alert('用户名已存在，请直接登录'); return; }
            users.push({ username, name: username, password: pwd });
            saveUsers();
            alert(`注册成功！请使用用户名“${username}”登录。`);
            // 清空注册表单
            document.getElementById('reg-username').value = '';
            document.getElementById('reg-password').value = '';
            document.getElementById('reg-confirm').value = '';
            // 切换到登录选项卡
            document.getElementById('login-tab-new').click();
            document.getElementById('login-username').value = username;
            document.getElementById('login-password').value = '';
        });
        
        // 选项卡切换
        const loginTab = document.getElementById('login-tab-new');
        const registerTab = document.getElementById('register-tab-new');
        const loginFormDiv = document.getElementById('login-form-new');
        const registerFormDiv = document.getElementById('register-form-new');
        
        loginTab.addEventListener('click', () => {
            loginTab.classList.add('active');
            registerTab.classList.remove('active');
            loginFormDiv.classList.remove('hidden');
            registerFormDiv.classList.add('hidden');
        });
        registerTab.addEventListener('click', () => {
            registerTab.classList.add('active');
            loginTab.classList.remove('active');
            registerFormDiv.classList.remove('hidden');
            loginFormDiv.classList.add('hidden');
        });
        
        // 登出按钮
        document.getElementById('logout-btn').addEventListener('click', () => {
            localStorage.removeItem('war_tycoon_logged_in');
            localStorage.removeItem('war_tycoon_user');
            localStorage.removeItem('war_tycoon_name');
            isLoggedIn = false;
            checkAuth();
        });
        
        // ==================== 成就系统 ====================
        const achievementsDB = {
            "first_visit": { name: "初来乍到", desc: "首次打开网站", icon: "fa-door-open" },
            "tank_category": { name: "装甲先锋", desc: "点击坦克任务分类", icon: "fa-tank" },
            "helicopter_category": { name: "旋翼骑士", desc: "点击直升机任务分类", icon: "fa-helicopter" },
            "airplane_category": { name: "空中之鹰", desc: "点击飞机任务分类", icon: "fa-plane" },
            "hovercraft_category": { name: "气垫狂徒", desc: "点击悬空载具分类", icon: "fa-water" },
            "ship_category": { name: "深海幽灵", desc: "点击船舰与潜艇分类", icon: "fa-ship" },
            "trade_market": { name: "交易大师", desc: "点击交易市场链接", icon: "fa-chart-line" },
            "social_community": { name: "社群之友", desc: "点击任意官方社群链接", icon: "fa-users" },
            "easter_egg": { name: "秘境探索者", desc: "点击彩蛋按钮", icon: "fa-dragon" }
        };
        let userAchievements = JSON.parse(localStorage.getItem('war_tycoon_achievements')) || [];
        function saveAchievements() { localStorage.setItem('war_tycoon_achievements', JSON.stringify(userAchievements)); if (document.getElementById('achievement-modal') && !document.getElementById('achievement-modal').classList.contains('opacity-0')) renderAchievementList(); }
        function showAchievementToast(achievementId) { const ach = achievementsDB[achievementId]; if (!ach) return; const existingToast = document.querySelector('.achievement-toast'); if (existingToast) existingToast.remove(); const toast = document.createElement('div'); toast.className = 'achievement-toast'; toast.innerHTML = `<i class="fa-solid ${ach.icon}"></i><div class="text"><div class="title">🏆 成就解锁！</div><div>${ach.name} - ${ach.desc}</div></div>`; document.body.appendChild(toast); setTimeout(() => toast.classList.add('show'), 10); setTimeout(() => { toast.classList.remove('show'); setTimeout(() => toast.remove(), 300); }, 4000); }
        function unlockAchievement(achievementId) { if (!isLoggedIn) return; if (!achievementsDB[achievementId]) return; if (!userAchievements.find(a => a.id === achievementId)) { userAchievements.push({ id: achievementId, unlockedAt: new Date().toLocaleString() }); saveAchievements(); showAchievementToast(achievementId); } }
        function renderAchievementList() { const container = document.getElementById('achievement-list'); if (!container) return; if (userAchievements.length === 0) { container.innerHTML = '<div class="text-center text-xs text-gray-500 py-4">暂无成就，快去探索吧！</div>'; return; } const sorted = [...userAchievements].reverse(); container.innerHTML = sorted.map(ach => { const meta = achievementsDB[ach.id]; if (!meta) return ''; return `<div class="achievement-item"><i class="fa-solid ${meta.icon}"></i><div class="achievement-info"><div class="achievement-name">${meta.name}</div><div class="achievement-desc">${meta.desc}</div></div><div class="achievement-date">${ach.unlockedAt}</div></div>`; }).join(''); }
        function openAchievementModal() { const modal = document.getElementById('achievement-modal'); const content = modal.querySelector('.achievement-modal-content'); renderAchievementList(); modal.classList.remove('opacity-0', 'pointer-events-none'); content.classList.add('show'); }
        function closeAchievementModal() { const modal = document.getElementById('achievement-modal'); const content = modal.querySelector('.achievement-modal-content'); content.classList.remove('show'); setTimeout(() => { modal.classList.add('opacity-0', 'pointer-events-none'); }, 150); }
        function initAchievements() { if (!userAchievements.find(a => a.id === 'first_visit')) unlockAchievement('first_visit'); else renderAchievementList(); }
        
        // ==================== 任务数据 ====================
        const taskData = {
            "tank": { title: "坦克任务", tasks: [{ name: "M3布拉德利", requirement: "花费 40 个坦克零件" },{ name: "威斯尔1MK20", requirement: "使用 15 次空投呼召" },{ name: "威斯尔1拖车Ⅱ型", requirement: "使用 1MK20 摧毁 20 辆地面载具" },{ name: "T72", requirement: "使用坦克击杀 30 人" },{ name: "ADATS", requirement: "摧毁 60 架飞行器" },{ name: "维塞尔1防空", requirement: "使用 1MK20 摧毁 20 辆地面载具" },{ name: "M1艾布拉姆斯", requirement: "使用坦克摧毁 30 辆坦克 & 偷取 10 个零件箱" },{ name: "K9雷霆SPG", requirement: "摧毁 60 辆地面载具 & 300 米外击杀 40 人" },{ name: "豹子2A7", requirement: "摧毁 35 辆坦克 & 驾驶 600 秒坦克" },{ name: "失败任务", requirement: "占领捕捉点 1800 秒 & 使用坦克 200 米外击杀 20 人" },{ name: "T90", requirement: "使用坦克摧毁 45 辆坦克 & 花费 100 个坦克零件" },{ name: "PL_01", requirement: "使用坦克摧毁 40 辆地面载具 & 驾驶 1500 秒坦克" },{ name: "MAUS", requirement: "坦克受到 10 万伤害 & 找到 4 个隐藏车辆部件" },{ name: "T14", requirement: "收集 10 桶石油 & 使用坦克 200 米外击杀 40 人 & 使用坦克击杀 75 人" },{ name: "挑战者Ⅱ黑色夜晚", requirement: "坦克受到 12 万伤害 & 收集 10 架坠毁的无人机 & 使用 50 次主动保护系统" },{ name: "KF_51豹子", requirement: "花费 200 个坦克零件 & 占领捕捉点 3000 秒 & 使用坦克击杀 100 人" }] },
            "helicopter": { title: "直升机任务", tasks: [{ name: "UH60_黑鹰", requirement: "救起 10 个玩家" },{ name: "欧洲直升机老虎", requirement: "摧毁 40 辆车辆" },{ name: "无敌", requirement: "使用直升机摧毁 45 架直升机 & 驾驶直升机通过圆环获取 45 积分" },{ name: "AH_64阿帕奇", requirement: "使用直升机击杀 25 人 & 占领捕捉点 1500 秒" },{ name: "KA_52鳄鱼", requirement: "摧毁 30 架直升机 & 使用直升机 200 米外击杀 20 人" },{ name: "直10", requirement: "花费 100 个船舰零件 & 使用直升机对任何载具造成 5 万伤害" },{ name: "超级种马", requirement: "使用直升机摧毁 20 辆船舰 & 收集 5 桶石油" },{ name: "AH_1Z毒蛇", requirement: "使用直升机摧毁 50 辆地面载具 & 占领捕捉点 1200 秒" },{ name: "咆哮者X", requirement: "使用直升机摧毁 20 架飞机 & 使用直升机摧毁 20 辆车库车辆 & 驾驶直升机通过圆环获取 200 积分" },{ name: "A129芒果", requirement: "花费 200 个直升机零件 & 使用直升机摧毁 40 架飞机 & 使用直升机击杀 12 人" }] },
            "airplane": { title: "飞机任务", tasks: [{ name: "B_29", requirement: "占领捕捉点 1800 秒" },{ name: "F_14", requirement: "使用飞机摧毁 30 架直升机" },{ name: "Ju57斯图卡", requirement: "使用飞机摧毁 15 辆坦克" },{ name: "F_4", requirement: "使用飞机击杀 30 人" },{ name: "米格_29", requirement: "使用飞机摧毁 25 架飞机" },{ name: "A_10", requirement: "使用飞机摧毁 50 辆地面载具 & 飞机受到 4 万伤害" },{ name: "JAS_39", requirement: "占领捕捉点 1800 秒 & 使用飞机击杀 50 人" },{ name: "F_15E", requirement: "使用飞机摧毁 60 辆地面载具 & 使用飞机 200 米外击杀 40 人" },{ name: "F_18", requirement: "使用飞机摧毁 40 辆船舰 & 花费 100 个飞机零件" },{ name: "苏57", requirement: "花费 100 个飞机零件 & 使用飞机摧毁 30 架飞机" },{ name: "欧洲战斗机台风", requirement: "使用飞机摧毁车辆 & 偷取 5 个零件箱" },{ name: "阵风", requirement: "使用飞机摧毁 20 辆船舰 & 使用飞机摧毁 60 架飞行器" },{ name: "F_16", requirement: "摧毁 30 架飞机 & 花费 60 个飞机零件" },{ name: "F_22", requirement: "驾驶飞机通过圆环收集 400 积分 & 占领捕捉点 1800 秒 & 使用飞机击杀 100 人" },{ name: "夜鹰", requirement: "使用飞机炸弹击杀 25 人 & 占领捕捉点 1800 秒 & 偷取 10 个零件箱" },{ name: "黑暗之星", requirement: "花费 10 个升级点数 & 偷取 10 个零件箱 & 收集 10 架坠毁的无人机" },{ name: "歼36", requirement: "收集 10 架坠毁的无人机 & 使用飞机摧毁 20 辆船舰 & 花费 100 个飞机零件" }] },
            "hovercraft": { title: "悬空载具", tasks: [{ name: "PACV_78突击", requirement: "使用气垫船摧毁 40 辆地面载具" },{ name: "PACV_77风镰", requirement: "使用气垫船摧毁 30 架飞行器" },{ name: "QBZ_95", requirement: "使用自动武器 50 米外击杀 30 人" },{ name: "C4", requirement: "使用手榴弹击杀 15 人 & 摧毁 10 辆地面车辆" },{ name: "QBJ_LMG", requirement: "偷取 10 个零件箱 & 使用自动武器击杀 20 人" },{ name: "AVH猎人", requirement: "使用气垫船摧毁 60 辆地面载具 & 使用气垫船撞倒 300 物品 & 驾驶气垫船 1800 秒" }] },
            "ship": { title: "船舰与潜艇", tasks: [{ name: "PG02", requirement: "使用船舰击杀 25 人" },{ name: "法尔米尔", requirement: "收集 10 桶海洋沉船石油" },{ name: "KSG_12", requirement: "使用夹弹枪击杀 20 人 & 收集 4 桶石油" },{ name: "道格拉斯号", requirement: "使用船舰摧毁 40 辆载具 & 占领捕捉点 1800 秒" },{ name: "PP_19Bizon", requirement: "使用自动武器击杀 25 人 & 偷取 2 个零件箱" },{ name: "Pr.206", requirement: "使用船舰摧毁 20 辆敌方船舰" },{ name: "USS独立号", requirement: "使用船舰摧毁 125 辆载具或者船舰 & 占领捕捉点 1500 秒 & 收集 10 桶石油" }] }
        };
        let trackedTasks = JSON.parse(localStorage.getItem('wtt_tracked')) || [];
        let activeModalTask = null;
        
        function renderTaskSections(filterText = "") {
            const container = document.getElementById('tasks-container');
            const categorySelector = document.getElementById('category-selector');
            const sectionDivider = document.getElementById('section-divider');
            container.innerHTML = '';
            const filter = filterText.trim().toLowerCase();
            if (filter === "") {
                categorySelector.classList.remove('hidden');
                if(sectionDivider) sectionDivider.classList.remove('hidden');
                Object.keys(taskData).forEach(key => {
                    const category = taskData[key];
                    const section = document.createElement('section');
                    section.id = `${key}-section`;
                    section.className = "space-y-4 scroll-mt-20";
                    section.innerHTML = `<div class="border-b border-gray-800 pb-2"><h2 class="text-xl font-bold text-white flex items-center gap-2"><span class="w-1 h-5 bg-blue-500 rounded-full"></span>${category.title}</h2></div><div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">${category.tasks.map((task, index) => { const isTracked = trackedTasks.some(t => t.name === task.name); return `<div onclick="openTaskDetail('${key}', ${index})" class="task-card p-4 cursor-pointer flex flex-col justify-between h-36"><div class="flex justify-between items-start"><span class="text-xs text-blue-400 font-medium bg-blue-500/20 px-1.5 py-0.5 rounded">载具/装备</span></div><h4 class="text-sm font-bold text-white truncate my-2">${task.name}</h4><div class="flex justify-between items-center text-xs text-gray-500 pt-2 border-t border-gray-800/60"><span>点击查看 →</span>${isTracked ? '<span class="text-[10px] text-green-400 bg-green-500/20 px-1.5 py-0.5 rounded">追踪中</span>' : ''}</div></div>`; }).join('')}</div>`;
                    container.appendChild(section);
                });
            } else {
                categorySelector.classList.add('hidden');
                if(sectionDivider) sectionDivider.classList.add('hidden');
                let totalMatches = 0;
                Object.keys(taskData).forEach(key => {
                    const category = taskData[key];
                    const filteredTasks = category.tasks.map((t, idx) => ({...t, originalIndex: idx})).filter(t => t.name.toLowerCase().includes(filter));
                    if(filteredTasks.length > 0){
                        totalMatches += filteredTasks.length;
                        const section = document.createElement('section');
                        section.className = "space-y-4";
                        section.innerHTML = `<div class="border-b border-gray-800 pb-2"><h2 class="text-lg font-bold text-white">${category.title}</h2></div><div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">${filteredTasks.map(task => { const isTracked = trackedTasks.some(t => t.name === task.name); return `<div onclick="openTaskDetail('${key}', ${task.originalIndex})" class="task-card p-4 cursor-pointer flex flex-col justify-between h-36"><div class="flex justify-between items-start"><span class="text-xs text-blue-400 font-medium bg-blue-500/20 px-1.5 py-0.5 rounded">载具/装备</span></div><h4 class="text-sm font-bold text-white truncate my-2">${task.name}</h4><div class="flex justify-between items-center text-xs text-gray-500 pt-2 border-t border-gray-800/60"><span>点击查看 →</span>${isTracked ? '<span class="text-[10px] text-green-400 bg-green-500/20 px-1.5 py-0.5 rounded">追踪中</span>' : ''}</div></div>`; }).join('')}</div>`;
                        container.appendChild(section);
                    }
                });
                const infoText = document.getElementById('search-results-info');
                if(infoText) { infoText.classList.remove('hidden'); infoText.innerText = `找到 ${totalMatches} 个名称相符项目`; }
            }
        }
        
        function openTaskDetail(categoryKey, index) { const category = taskData[categoryKey]; const task = category.tasks[index]; activeModalTask = { ...task, categoryTitle: category.title }; document.getElementById('modal-category').innerText = category.title; document.getElementById('modal-title').innerText = task.name; document.getElementById('modal-requirement').innerText = task.requirement; const isTracked = trackedTasks.some(t => t.name === task.name); updateModalTrackButtonState(isTracked); document.getElementById('modal-toast').classList.add('opacity-0'); const modal = document.getElementById('detail-modal'); modal.classList.remove('opacity-0', 'pointer-events-none'); modal.querySelector('div').classList.remove('scale-95'); }
        function closeModal() { const modal = document.getElementById('detail-modal'); modal.classList.add('opacity-0', 'pointer-events-none'); modal.querySelector('div').classList.add('scale-95'); activeModalTask = null; }
        function copyCurrentRequirement() { if (!activeModalTask) return; const text = `【${activeModalTask.name}】解锁条件：${activeModalTask.requirement}`; const dummy = document.createElement("textarea"); document.body.appendChild(dummy); dummy.value = text; dummy.select(); document.execCommand("copy"); document.body.removeChild(dummy); showToast("已成功复制！"); }
        function showToast(msg) { const toast = document.getElementById('modal-toast'); toast.innerText = msg; toast.classList.remove('opacity-0'); setTimeout(() => toast.classList.add('opacity-0'), 2000); }
        function toggleTrackCurrent() { if (!activeModalTask) return; toggleTrackDirectly(activeModalTask.name, activeModalTask.categoryTitle, activeModalTask.requirement); const isTracked = trackedTasks.some(t => t.name === activeModalTask.name); updateModalTrackButtonState(isTracked); showToast(isTracked ? "已追踪" : "取消追踪"); }
        function updateModalTrackButtonState(isTracked) { const btn = document.getElementById('modal-track-btn'); if (isTracked) { btn.className = "flex-1 bg-red-600/20 text-red-400 border border-red-500/20 font-bold py-2 px-4 rounded-xl text-sm transition"; btn.innerText = "取消追踪"; } else { btn.className = "flex-1 bg-blue-600 text-white font-bold py-2 px-4 rounded-xl text-sm transition"; btn.innerText = "加入追踪"; } }
        function toggleTrackDirectly(name, category, requirement) { const index = trackedTasks.findIndex(t => t.name === name); if (index > -1) trackedTasks.splice(index,1); else trackedTasks.push({ name, category, requirement }); localStorage.setItem('wtt_tracked', JSON.stringify(trackedTasks)); updateTrackerBadge(); const input = document.getElementById('search-input'); renderTaskSections(input.value); }
        function openTrackerModal() { const modal = document.getElementById('tracker-modal'); renderTrackerList(); modal.classList.remove('opacity-0', 'pointer-events-none'); modal.querySelector('div').classList.remove('scale-95'); }
        function closeTrackerModal() { const modal = document.getElementById('tracker-modal'); modal.classList.add('opacity-0', 'pointer-events-none'); modal.querySelector('div').classList.add('scale-95'); }
        function renderTrackerList() { const content = document.getElementById('tracker-list-content'); if (trackedTasks.length === 0) { content.innerHTML = `<p class="text-center py-6 text-xs text-gray-500">暂无追踪项目</p>`; return; } content.innerHTML = trackedTasks.map(t => `<div class="p-2.5 bg-gray-900 border border-gray-800 rounded-lg flex items-center justify-between text-xs"><div><span class="text-[10px] text-blue-400 font-bold">[${t.category}]</span><span class="text-white font-bold">${t.name}</span><p class="text-gray-400 mt-1">${t.requirement}</p></div><button onclick="toggleTrackDirectly('${t.name}'); renderTrackerList();" class="text-red-400 px-2 font-bold">×</button></div>`).join(''); }
        function clearAllTracked() { trackedTasks = []; localStorage.setItem('wtt_tracked', JSON.stringify([])); updateTrackerBadge(); renderTrackerList(); const input = document.getElementById('search-input'); renderTaskSections(input.value); }
        function updateTrackerBadge() { const badge = document.getElementById('tracker-badge'); if (trackedTasks.length > 0) { badge.innerText = trackedTasks.length; badge.classList.remove('hidden'); } else { badge.classList.add('hidden'); } }
        function searchTasks() { const input = document.getElementById('search-input'); const infoText = document.getElementById('search-results-info'); const social = document.getElementById('social-section'); const divider = document.getElementById('section-divider'); const factionHr = document.getElementById('faction-hr'); const factionSec = document.getElementById('faction-section'); const aboutHr = document.getElementById('about-hr'); const aboutSec = document.getElementById('aboutus-section'); const val = input.value.trim(); const isFiltering = val !== ""; const extra = [factionHr, factionSec, aboutHr, aboutSec]; if (isFiltering) { if(social) social.style.display = 'none'; if(divider) divider.style.display = 'none'; extra.forEach(el => { if(el) el.style.display = 'none'; }); infoText.classList.remove('hidden'); } else { if(social) social.style.display = 'block'; if(divider) divider.style.display = 'block'; extra.forEach(el => { if(el) el.style.display = 'block'; }); infoText.classList.add('hidden'); } renderTaskSections(input.value); }
        function scrollToSection(id) { document.getElementById(id)?.scrollIntoView({ behavior: 'smooth' }); }
        function showEasterEggPage() { document.getElementById('main-app').style.display = 'none'; document.getElementById('easteregg-page').classList.remove('hidden'); setDynamicBg(false); }
        function hideEasterEggPage() { document.getElementById('main-app').style.display = 'block'; document.getElementById('easteregg-page').classList.add('hidden'); setDynamicBg(false); }
        
        initPixelCanvas();
        drawPixelRain();
        checkAuth();
    </script>
</body>
</html>
