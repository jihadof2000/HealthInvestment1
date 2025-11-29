<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة عوائد الاستثمار الصحي</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #0b3a5a;
            --primary-light: #145f8c;
            --primary-dark: #082a42;
            --secondary: #1a936f;
            --secondary-light: #2bbd91;
            --accent: #ff6b6b;
            --text-dark: #2d3748;
            --text-light: #718096;
            --bg-light: #f8fafc;
            --bg-white: #ffffff;
            --border: #e2e8f0;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            --radius: 12px;
            --radius-sm: 8px;
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
            color: var(--text-dark);
            line-height: 1.6;
        }

        .layout {
            display: flex;
            min-height: 100vh;
        }

        /* الشريط الجانبي */
        .sidebar {
            width: 280px;
            background: linear-gradient(180deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 0;
            position: fixed;
            right: 0;
            top: 0;
            bottom: 0;
            display: flex;
            flex-direction: column;
            z-index: 100;
            box-shadow: var(--shadow-lg);
        }

        .sidebar-header {
            padding: 24px 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            background: rgba(0, 0, 0, 0.1);
        }

        .logo-container {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .logo-badge {
            width: 50px;
            height: 50px;
            border-radius: 12px;
            background: rgba(255, 255, 255, 0.15);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .logo-badge i {
            font-size: 20px;
            color: white;
        }

        .app-info h2 {
            font-size: 18px;
            margin-bottom: 4px;
            font-weight: 600;
        }

        .app-info small {
            opacity: 0.8;
            font-size: 12px;
        }

        .nav-links {
            padding: 20px 0;
            flex: 1;
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .nav-item {
            display: flex;
            align-items: center;
            padding: 12px 20px;
            color: rgba(255, 255, 255, 0.8);
            transition: var(--transition);
            border-right: 3px solid transparent;
            cursor: pointer;
        }

        .nav-item:hover, .nav-item.active {
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border-right-color: var(--secondary);
        }

        .nav-item i {
            margin-left: 12px;
            font-size: 18px;
            width: 24px;
            text-align: center;
        }

        .sidebar-footer {
            padding: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        #langToggle {
            width: 100%;
            padding: 10px;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: var(--radius-sm);
            cursor: pointer;
            font-size: 14px;
            transition: var(--transition);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }

        #langToggle:hover {
            background: rgba(255, 255, 255, 0.2);
        }

        /* المحتوى الرئيسي */
        .content {
            margin-right: 280px;
            padding: 0;
            flex: 1;
            display: flex;
            flex-direction: column;
        }

        /* الشريط العلوي */
        .topbar {
            background: var(--bg-white);
            padding: 16px 32px;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 99;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .topbar-info h1 {
            font-size: 24px;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 4px;
        }

        .topbar-info p {
            font-size: 14px;
            color: var(--text-light);
        }

        .user-menu {
            display: flex;
            align-items: center;
            gap: 16px;
        }

        .user-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
        }

        /* شريط التبويبات الأفقي */
        .horizontal-tabs {
            background: var(--primary);
            padding: 0;
            box-shadow: var(--shadow);
            position: sticky;
            top: 82px;
            z-index: 98;
        }

        .horizontal-nav {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            gap: 0;
            padding: 0;
        }

        .horizontal-tab {
            display: flex;
            align-items: center;
            padding: 16px 24px;
            color: rgba(255, 255, 255, 0.8);
            transition: var(--transition);
            border-bottom: 3px solid transparent;
            cursor: pointer;
            white-space: nowrap;
        }

        .horizontal-tab:hover, .horizontal-tab.active {
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border-bottom-color: var(--secondary);
        }

        .horizontal-tab i {
            margin-left: 12px;
            font-size: 18px;
            width: 24px;
            text-align: center;
        }

        /* البطاقات */
        .card {
            background: var(--bg-white);
            padding: 24px;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            margin-bottom: 24px;
            border: 1px solid var(--border);
        }

        .card-header {
            margin-bottom: 20px;
            padding-bottom: 16px;
            border-bottom: 1px solid var(--border);
        }

        .card-header h2 {
            font-size: 20px;
            font-weight: 600;
            color: var(--primary);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .card-header p {
            color: var(--text-light);
            margin-top: 8px;
            font-size: 14px;
        }

        /* أقسام الصفحة */
        .section-container {
            padding: 32px;
        }

        .hero-section {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            color: white;
            padding: 60px 32px;
            border-radius: 0 0 var(--radius) var(--radius);
            margin-bottom: 32px;
        }

        .hero-projects-card {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            color: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow-lg);
            margin-bottom: 32px;
            overflow: hidden;
        }

        .hero-projects-card .hero-content {
            padding: 60px 32px 40px 32px;
        }

        .hero-projects-divider {
            height: 1px;
            background: rgba(255, 255, 255, 0.2);
            margin: 0 32px;
        }

        .hero-content {
            max-width: 800px;
        }

        .hero-title {
            font-size: 36px;
            font-weight: 700;
            margin-bottom: 16px;
        }

        .hero-subtitle {
            font-size: 18px;
            opacity: 0.9;
            margin-bottom: 32px;
            max-width: 600px;
        }

        .hero-actions {
            display: flex;
            gap: 16px;
        }

        .btn {
            padding: 12px 24px;
            border-radius: var(--radius-sm);
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            display: inline-flex;
            align-items: center;
            gap: 8px;
            border: none;
        }

        .btn-primary {
            background: var(--secondary);
            color: white;
        }

        .btn-primary:hover {
            background: var(--secondary-light);
        }

        .btn-outline {
            background: transparent;
            color: white;
            border: 2px solid rgba(255, 255, 255, 0.3);
        }

        .btn-outline:hover {
            background: rgba(255, 255, 255, 0.1);
            border-color: white;
        }

        .btn-secondary {
            background: var(--primary-light);
            color: white;
        }

        .btn-secondary:hover {
            background: var(--primary);
        }

        /* بطاقات الاستثمار */
        .invest-cards {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 24px;
            margin-top: 20px;
        }

        .invest-card {
            background: var(--bg-white);
            border-radius: var(--radius);
            padding: 24px;
            cursor: pointer;
            box-shadow: var(--shadow);
            border: 1px solid var(--border);
            transition: var(--transition);
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .invest-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-lg);
            border-color: var(--primary-light);
        }

        .invest-card-icon {
            width: 60px;
            height: 60px;
            border-radius: 12px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 16px;
            color: white;
            font-size: 24px;
        }

        .invest-card-title {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 8px;
            color: var(--primary);
        }

        .invest-card-sub {
            font-size: 14px;
            color: var(--text-light);
            flex: 1;
        }

        /* نماذج الإدخال */
        .form-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .form-group {
            margin-bottom: 16px;
        }

        .form-label {
            display: block;
            font-size: 14px;
            font-weight: 600;
            margin-bottom: 8px;
            color: var(--primary);
        }

        .form-input {
            width: 100%;
            padding: 12px 16px;
            border-radius: var(--radius-sm);
            border: 1px solid var(--border);
            font-size: 14px;
            transition: var(--transition);
        }

        .form-input:focus {
            outline: none;
            border-color: var(--primary-light);
            box-shadow: 0 0 0 3px rgba(11, 58, 90, 0.1);
        }

        .form-actions {
            margin-top: 24px;
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
        }

        /* شاشة تسجيل الدخول */
        #loginScreen {
            position: fixed;
            inset: 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 1000;
        }

        .login-container {
            background: var(--bg-white);
            padding: 40px;
            border-radius: var(--radius);
            width: 100%;
            max-width: 420px;
            box-shadow: var(--shadow-lg);
            text-align: center;
        }

        .login-logo {
            margin-bottom: 24px;
        }

        .login-logo i {
            font-size: 48px;
            color: var(--primary);
            margin-bottom: 16px;
        }

        .login-title {
            font-size: 24px;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 8px;
        }

        .login-subtitle {
            color: var(--text-light);
            margin-bottom: 32px;
        }

        .login-form {
            text-align: right;
        }

        .login-input-group {
            margin-bottom: 20px;
        }

        .login-input {
            width: 100%;
            padding: 14px 16px;
            border-radius: var(--radius-sm);
            border: 1px solid var(--border);
            font-size: 16px;
            transition: var(--transition);
        }

        .login-input:focus {
            outline: none;
            border-color: var(--primary-light);
            box-shadow: 0 0 0 3px rgba(11, 58, 90, 0.1);
        }

        .login-btn {
            width: 100%;
            padding: 14px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: var(--radius-sm);
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
        }

        .login-btn:hover {
            background: var(--primary-light);
        }

        /* نتائج الحساب */
        .kpi-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            gap: 20px;
            margin-bottom: 24px;
        }

        .kpi-card {
            background: var(--bg-white);
            border-radius: var(--radius);
            padding: 20px;
            box-shadow: var(--shadow);
            border-left: 4px solid var(--primary);
        }

        .kpi-label {
            font-size: 14px;
            color: var(--text-light);
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .kpi-value {
            font-size: 28px;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 4px;
        }

        .kpi-sub {
            font-size: 12px;
            color: var(--text-light);
        }

        /* التقارير */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 24px;
            margin-top: 20px;
        }

        .project-card {
            background: var(--bg-white);
            border-radius: var(--radius);
            padding: 24px;
            box-shadow: var(--shadow);
            border-left: 4px solid var(--secondary);
            transition: var(--transition);
            height: 100%;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-lg);
        }

        .project-details {
            margin-top: 16px;
        }

        .project-detail-item {
            margin-bottom: 12px;
            display: flex;
        }

        .project-detail-label {
            font-weight: 600;
            min-width: 120px;
            color: var(--primary);
            font-size: 14px;
        }

        .project-detail-value {
            flex: 1;
            color: var(--text-light);
            font-size: 14px;
        }

        .project-roi {
            background: rgba(26, 147, 111, 0.1);
            padding: 12px;
            border-radius: var(--radius-sm);
            margin-top: 16px;
            text-align: center;
            font-weight: 700;
            color: var(--secondary);
            border: 1px solid rgba(26, 147, 111, 0.2);
        }

        .history-item {
            padding: 15px;
            border: 1px solid var(--border);
            border-radius: var(--radius);
            margin-bottom: 10px;
            cursor: pointer;
            transition: var(--transition);
        }

        .history-item:hover {
            background-color: var(--bg-light);
            border-color: var(--primary-light);
        }

        /* تبويب المشاريع */
        .projects-tab {
            background: var(--bg-white);
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            margin-bottom: 24px;
            overflow: hidden;
        }

        .hero-projects-card .projects-tab {
            background: transparent;
            box-shadow: none;
            margin-bottom: 0;
        }

        .projects-tab-header {
            background: transparent;
            color: white;
            padding: 20px 32px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            cursor: pointer;
            transition: var(--transition);
        }

        .projects-tab-header:hover {
            background: rgba(255, 255, 255, 0.1);
        }

        .hero-projects-card .projects-tab-header {
            background: transparent;
        }

        .projects-tab-header h2 {
            font-size: 20px;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .projects-tab-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
            background: var(--bg-white);
        }

        .projects-tab-content.active {
            max-height: 1000px;
        }

        .hero-projects-card .projects-tab-content {
            background: var(--bg-white);
        }

        .projects-tab-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .project-tab-card {
            background: var(--bg-light);
            border-radius: var(--radius-sm);
            padding: 16px;
            border: 1px solid var(--border);
            transition: var(--transition);
            cursor: pointer;
        }

        .project-tab-card:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow);
            border-color: var(--primary-light);
        }

        .project-tab-card h3 {
            font-size: 16px;
            font-weight: 600;
            color: var(--primary);
            margin-bottom: 8px;
        }

        .project-tab-card p {
            font-size: 13px;
            color: var(--text-light);
            margin-bottom: 12px;
        }

        .project-tab-roi {
            font-size: 14px;
            font-weight: 700;
            color: var(--secondary);
            text-align: center;
            padding: 8px;
            background: rgba(26, 147, 111, 0.1);
            border-radius: var(--radius-sm);
        }

        /* فريق العمل */
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .team-member {
            background: var(--bg-white);
            border-radius: var(--radius);
            padding: 20px;
            box-shadow: var(--shadow);
            border-left: 4px solid var(--secondary);
            transition: var(--transition);
        }

        .team-member:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-lg);
        }

        .team-member h3 {
            font-size: 18px;
            font-weight: 600;
            color: var(--primary);
            margin-bottom: 8px;
        }

        .team-member p {
            font-size: 14px;
            color: var(--text-light);
        }

        /* التكيف مع الشاشات الصغيرة */
        @media (max-width: 768px) {
            .sidebar {
                transform: translateX(100%);
                width: 280px;
            }
            
            .sidebar.active {
                transform: translateX(0);
            }
            
            .content {
                margin-right: 0;
            }
            
            .hero-title {
                font-size: 28px;
            }
            
            .hero-actions {
                flex-direction: column;
            }
            
            .invest-cards {
                grid-template-columns: 1fr;
            }
            
            .form-grid {
                grid-template-columns: 1fr;
            }
            
            .projects-tab-grid {
                grid-template-columns: 1fr;
            }
            
            .team-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<!-- شاشة تسجيل الدخول -->
<div id="loginScreen">
    <div class="login-container">
        <div class="login-logo">
            <i class="fas fa-heartbeat"></i>
            <h1 class="login-title">تسجيل الدخول</h1>
            <p class="login-subtitle">منصة عوائد الاستثمار الصحي</p>
        </div>
        <form class="login-form" id="loginForm">
            <div class="login-input-group">
                <input type="text" id="loginUser" class="login-input" placeholder="اسم المستخدم">
            </div>
            <div class="login-input-group">
                <input type="password" id="loginPass" class="login-input" placeholder="كلمة المرور">
            </div>
            <button type="submit" class="login-btn">
                <i class="fas fa-sign-in-alt"></i> دخول
            </button>
        </form>
    </div>
</div>

<!-- الهيكل الرئيسي -->
<div class="layout" style="display:none;" id="mainLayout">
    <aside class="sidebar">
        <div class="sidebar-header">
            <div class="logo-container">
                <div class="logo-badge">
                    <i class="fas fa-heartbeat"></i>
                </div>
                <div class="app-info">
                    <h2 id="appTitle">منصة عوائد الاستثمار الصحي</h2>
                    <small id="appSub">تحليل استثمارات المستشفيات والأدوية والأجهزة الطبية</small>
                </div>
            </div>
        </div>

        <div class="nav-links">
            <div class="nav-item active" onclick="showSection('home')">
                <i class="fas fa-home"></i>
                <span>الصفحة الرئيسية</span>
            </div>
            <div class="nav-item" onclick="showSection('dashboard')">
                <i class="fas fa-chart-bar"></i>
                <span>لوحة التحكم</span>
            </div>
            <div class="nav-item" onclick="showSection('reports')">
                <i class="fas fa-chart-line"></i>
                <span>التقارير والتحليل</span>
            </div>
            <div class="nav-item" onclick="showSection('about')">
                <i class="fas fa-info-circle"></i>
                <span>حول المنصة</span>
            </div>
            <div class="nav-item" onclick="showSection('team')">
                <i class="fas fa-users"></i>
                <span>من نحن</span>
            </div>
        </div>

        <div class="sidebar-footer">
            <button id="langToggle" onclick="switchLang()">
                <i class="fas fa-language"></i> EN / عربي
            </button>
        </div>
    </aside>

    <main class="content">
        <div class="topbar">
            <div class="topbar-info">
                <h1 id="topTitle">منصة عوائد الاستثمار الصحي</h1>
                <p id="topMeta">نظام موحّد لحساب وتحليل عوائد الاستثمار الصحي</p>
            </div>
            <div class="user-menu">
                <div class="user-avatar">
                    <i class="fas fa-user"></i>
                </div>
            </div>
        </div>

        <!-- شريط التبويبات الأفقي -->
        <div class="horizontal-tabs">
            <div class="horizontal-nav">
                <div class="horizontal-tab active" onclick="showSection('home')">
                    <i class="fas fa-home"></i>
                    <span>الصفحة الرئيسية</span>
                </div>
                <div class="horizontal-tab" onclick="showSection('selection')">
                    <i class="fas fa-calculator"></i>
                    <span>حساب ROI</span>
                </div>
                <div class="horizontal-tab" onclick="showSection('projects')">
                    <i class="fas fa-project-diagram"></i>
                    <span id="horizontalProjectsTabTitle">مشاريع تعزيز الاستثمار الصحي</span>
                </div>
                <div class="horizontal-tab" onclick="showSection('reports')">
                    <i class="fas fa-chart-line"></i>
                    <span>التقارير والتحليل</span>
                </div>
            </div>
        </div>

        <div class="section-container">
            <!-- الصفحة الرئيسية -->
            <section id="homeSection">
                <div class="hero-section">
                    <div class="hero-content">
                        <h1 class="hero-title" id="homeHeroTitle">مرحبًا بك في منصة عوائد الاستثمار الصحي</h1>
                        <p class="hero-subtitle" id="homeHeroSub">
                            احسب عوائد الاستثمار في المستشفيات، الأدوية، الأجهزة الطبية، والمؤشرات غير المالية، مع لوحة تحكم تفاعلية ثنائية اللغة.
                        </p>
                        <div class="hero-actions">
                            <button class="btn btn-primary" onclick="showSection('selection')">
                                <i class="fas fa-play-circle"></i> ابدأ الآن
                            </button>
                            <button class="btn btn-outline" onclick="showSection('dashboard')">
                                <i class="fas fa-tachometer-alt"></i> عرض لوحة التحكم
                            </button>
                        </div>
                    </div>
                </div>
                
                <div id="projectDetailsSection" class="project-details-section" style="display:none;"></div>
            </section>

            <!-- اختيار نوع الاستثمار -->
            <section id="selectionSection" class="card" style="display:none;">
                <div class="card-header">
                    <h2><i class="fas fa-hand-pointer"></i> <span id="selectTitle">اختر نوع الاستثمار</span></h2>
                    <p id="selectSub">اختر نوع الاستثمار الصحي الذي ترغب في تحليله، ثم انتقل لنموذج إدخال البيانات.</p>
                </div>
                <div class="invest-cards">
                    <div class="invest-card" onclick="selectInvestment('hospital')">
                        <div class="invest-card-icon">
                            <i class="fas fa-hospital"></i>
                        </div>
                        <div class="invest-card-title" id="cardHospitalTitle">مستشفى / عيادات</div>
                        <div class="invest-card-sub" id="cardHospitalSub">تحليل الإيرادات والتكاليف وصافي الربح للمؤسسات العلاجية.</div>
                    </div>
                    <div class="invest-card" onclick="selectInvestment('pharma')">
                        <div class="invest-card-icon">
                            <i class="fas fa-pills"></i>
                        </div>
                        <div class="invest-card-title" id="cardPharmaTitle">أدوية / Pharmaceuticals</div>
                        <div class="invest-card-sub" id="cardPharmaSub">استثمارات تطوير الأدوية والتجارب السريرية والتصنيع.</div>
                    </div>
                    <div class="invest-card" onclick="selectInvestment('devices')">
                        <div class="invest-card-icon">
                            <i class="fas fa-x-ray"></i>
                        </div>
                        <div class="invest-card-title" id="cardDevicesTitle">أجهزة طبية / Medical Devices</div>
                        <div class="invest-card-sub" id="cardDevicesSub">تحليل جدوى شراء وتشغيل وصيانة الأجهزة الطبية.</div>
                    </div>
                    <div class="invest-card" onclick="selectInvestment('nonfinancial')">
                        <div class="invest-card-icon">
                            <i class="fas fa-chart-pie"></i>
                        </div>
                        <div class="invest-card-title" id="cardNFTitle">عوائد غير مالية / Non-Financial</div>
                        <div class="invest-card-sub" id="cardNFSub">جودة الخدمات، رضا المرضى، السلامة، وتحسن الصحة المجتمعية.</div>
                    </div>
                </div>
            </section>

            <!-- إدخال البيانات -->
            <section id="inputSection" class="card" style="display:none;">
                <div class="card-header">
                    <h2><i class="fas fa-edit"></i> <span id="inputTitle">نموذج إدخال البيانات</span></h2>
                    <p id="inputSub">أدخل بيانات الاستثمار الصحي وفق النوع المختار، ثم اضغط حساب.</p>
                </div>
                <div class="form-grid" id="dynamicForm"></div>
                <div class="form-actions">
                    <button class="btn btn-primary" onclick="calculateROI()">
                        <i class="fas fa-calculator"></i> حساب ROI
                    </button>
                    <button class="btn btn-outline" onclick="fillDummyData()">
                        <i class="fas fa-database"></i> بيانات تجريبية
                    </button>
                    <button class="btn btn-secondary" onclick="showSection('selection')">
                        <i class="fas fa-arrow-right"></i> رجوع لاختيار النوع
                    </button>
                </div>
            </section>

            <!-- لوحة التحكم والنتائج -->
            <section id="dashboardSection" style="display:none;">
                <div class="card">
                    <div class="card-header">
                        <h2><i class="fas fa-chart-bar"></i> <span id="resultTitle">نتائج الحساب ومؤشرات الأداء</span></h2>
                        <p id="resultSub">تعرض هذه الصفحة نتائج الحساب (الإيرادات، التكاليف، صافي الربح، ROI، التصنيف)، مع رسومات بيانية.</p>
                    </div>
                    <div class="kpi-grid" id="kpiFinancialRow">
                        <div class="kpi-card">
                            <div class="kpi-label"><i class="fas fa-money-bill-wave"></i> <span id="labelRevenue">إجمالي الإيرادات</span></div>
                            <div class="kpi-value" id="kpiRevenue">—</div>
                            <div class="kpi-sub" id="subRevenue">حسب البيانات المدخلة</div>
                        </div>
                        <div class="kpi-card">
                            <div class="kpi-label"><i class="fas fa-receipt"></i> <span id="labelCost">إجمالي التكاليف</span></div>
                            <div class="kpi-value" id="kpiCost">—</div>
                            <div class="kpi-sub" id="subCost">حسب البيانات المدخلة</div>
                        </div>
                        <div class="kpi-card">
                            <div class="kpi-label"><i class="fas fa-chart-line"></i> <span id="labelProfit">صافي الربح</span></div>
                            <div class="kpi-value" id="kpiProfit">—</div>
                            <div class="kpi-sub" id="subProfit">إيرادات - تكاليف</div>
                        </div>
                        <div class="kpi-card">
                            <div class="kpi-label"><i class="fas fa-percentage"></i> <span id="labelROI">العائد على الاستثمار ROI</span></div>
                            <div class="kpi-value" id="kpiROI">—%</div>
                            <div class="kpi-sub" id="subROI">نسبة العائد إلى التكاليف</div>
                        </div>
                    </div>
                    <div class="form-actions">
                        <button class="btn btn-primary" onclick="showSection('reports')">
                            <i class="fas fa-chart-line"></i> عرض التقارير
                        </button>
                        <button class="btn btn-secondary" onclick="showSection('selection')">
                            <i class="fas fa-calculator"></i> حساب جديد
                        </button>
                    </div>
                </div>
            </section>

            <!-- التقارير والتحليل -->
            <section id="reportsSection" class="card" style="display:none;">
                <div class="card-header">
                    <h2><i class="fas fa-chart-line"></i> <span id="reportsTitle">التقارير والتحليل المتقدم</span></h2>
                    <p id="reportsSub">تحليل متقدم للاستثمارات الصحية ومقارنة الأداء وتقديم توصيات استثمارية.</p>
                </div>
                <div id="reportsContent">
                    <div class="projects-grid">
                        <div class="project-card">
                            <h3><i class="fas fa-chart-bar"></i> تحليل الأداء المالي</h3>
                            <p>تحليل شامل للأداء المالي للاستثمارات الصحية مع مؤشرات الأداء الرئيسية.</p>
                            <div class="form-actions">
                                <button class="btn btn-primary" onclick="generateReport('financial')">عرض التقرير</button>
                            </div>
                        </div>
                        
                        <div class="project-card">
                            <h3><i class="fas fa-balance-scale"></i> مقارنة الاستثمارات</h3>
                            <p>مقارنة أداء أنواع الاستثمارات المختلفة لتحديد الأكثر ربحية.</p>
                            <div class="form-actions">
                                <button class="btn btn-primary" onclick="generateReport('comparison')">عرض التقرير</button>
                            </div>
                        </div>
                        
                        <div class="project-card">
                            <h3><i class="fas fa-exclamation-triangle"></i> تحليل المخاطر</h3>
                            <p>تقييم المخاطر المحتملة للاستثمارات الصحية وتقديم توصيات للتخفيف.</p>
                            <div class="form-actions">
                                <button class="btn btn-primary" onclick="generateReport('risk')">عرض التقرير</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="form-actions">
                
                    <button class="btn btn-outline" onclick="showSection('home')">
                        <i class="fas fa-home"></i> الصفحة الرئيسية
                    </button>
                </div>
            </section>

            <!-- مشاريع تعزيز الاستثمار الصحي -->
            <section id="projectsSection" class="card" style="display:none;">
                <div class="card-header">
                    <h2><i class="fas fa-project-diagram"></i> <span id="projectsSectionTitle">مشاريع تعزيز الاستثمار الصحي</span></h2>
                    <p id="projectsSectionSub">استكشف المشاريع المختلفة لتعزيز الاستثمار الصحي وعوائدها على الاستثمار.</p>
                </div>
                <div class="projects-tab-grid" id="projectsSectionGrid">
                    <!-- سيتم تعبئة المشاريع هنا ديناميكياً -->
                </div>
                <div id="projectDetailsSectionStandalone" class="project-details-section" style="display:none; margin-top: 24px;"></div>
                <div class="form-actions">
                    <button class="btn btn-secondary" onclick="showSection('home')">
                        <i class="fas fa-arrow-right"></i> العودة للرئيسية
                    </button>
                </div>
            </section>

            <!-- حول المنصة -->
            <section id="aboutSection" class="card" style="display:none;">
                <div class="card-header">
                    <h2><i class="fas fa-info-circle"></i> <span id="aboutTitle">حول المنصة</span></h2>
                </div>
                <p id="aboutText">
                    تم تصميم هذه المنصة كنموذج أولي لحساب وتحليل عوائد الاستثمار الصحي في مجالات متعددة،
                    مع دعم ثنائي اللغة وإمكانية التوسع مستقبلاً لنظام مستخدمين وصلاحيات وقاعدة بيانات.
                </p>
                <div class="form-actions">
                    <button class="btn btn-secondary" onclick="showSection('home')">
                        <i class="fas fa-arrow-right"></i> العودة للرئيسية
                    </button>
                </div>
            </section>

            <!-- من نحن -->
            <section id="teamSection" class="card" style="display:none;">
                <div class="card-header">
                    <h2><i class="fas fa-users"></i> <span id="teamTitle">من نحن</span></h2>
                </div>
                <p>فريق العمل المتميز الذي ساهم في تطوير هذه المنصة:</p>
                <div class="team-grid">
                    <div class="team-member">
                        <h3>الممرضة بدرية عامر السلماني</h3>
                        <p>مركز إسماعيه الصحي</p>
                    </div>
                    <div class="team-member">
                        <h3>الممرضة رياء ناصر السلماني</h3>
                        <p>مركز إسماعيه الصحي</p>
                    </div>
                    <div class="team-member">
                        <h3>مساعد صيدلي جهاد إسماعيل</h3>
                        <p>مركز إسماعيه الصحي</p>
                    </div>
                    <div class="team-member">
                        <h3>محمد عبد الله الرحبي</h3>
                        <p>دائرة تقنية المعلومات</p>
                    </div>
                    <div class="team-member">
                        <h3>زايد سلطان المحروقي</h3>
                        <p>مستشفى سناو</p>
                    </div>
                    <div class="team-member">
                        <h3>الصيدلانية زينب الحارثي</h3>
                        <p>مستشفى إبراء المرجعي</p>
                    </div>
                    <div class="team-member">
                        <h3>ايمان سعيد المسكري</h3>
                        <p>مستشفى إبراء المرجعي</p>
                    </div>
                    <div class="team-member">
                        <h3>عمر الحارثي</h3>
                        <p>قسم التطوير و التوجيه المهني</p>
                    </div>
                </div>
                <div class="form-actions">
                    <button class="btn btn-secondary" onclick="showSection('home')">
                        <i class="fas fa-arrow-right"></i> العودة للرئيسية
                    </button>
                </div>
            </section>
        </div>
    </main>
</div>

<script>
// البيانات الأساسية
const text = {
    ar: {
        appTitle: "منصة عوائد الاستثمار الصحي",
        appSub: "تحليل استثمارات المستشفيات والأدوية والأجهزة الطبية",
        topTitle: "منصة عوائد الاستثمار الصحي",
        topMeta: "نظام موحّد لحساب وتحليل عوائد الاستثمار الصحي",
        homeHeroTitle: "مرحبًا بك في منصة عوائد الاستثمار الصحي",
        homeHeroSub: "احسب عوائد الاستثمار في المستشفيات، الأدوية، الأجهزة الطبية، والمؤشرات غير المالية، مع لوحة تحكم تفاعلية ثنائية اللغة.",
        selectTitle: "اختر نوع الاستثمار",
        selectSub: "اختر نوع الاستثمار الصحي الذي ترغب في تحليله، ثم انتقل لنموذج إدخال البيانات.",
        cardHospitalTitle: "مستشفى / عيادات",
        cardHospitalSub: "تحليل الإيرادات والتكاليف وصافي الربح للمؤسسات العلاجية.",
        cardPharmaTitle: "أدوية / Pharmaceuticals",
        cardPharmaSub: "استثمارات تطوير الأدوية والتجارب السريرية والتصنيع.",
        cardDevicesTitle: "أجهزة طبية / Medical Devices",
        cardDevicesSub: "تحليل جدوى شراء وتشغيل وصيانة الأجهزة الطبية.",
        cardNFTitle: "عوائد غير مالية / Non-Financial",
        cardNFSub: "جودة الخدمات، رضا المرضى، السلامة، وتحسن الصحة المجتمعية.",
        inputTitle: "نموذج إدخال البيانات",
        inputSub: "أدخل بيانات الاستثمار الصحي وفق النوع المختار، ثم اضغط حساب.",
        resultTitle: "نتائج الحساب ومؤشرات الأداء",
        resultSub: "تعرض هذه الصفحة نتائج الحساب (الإيرادات، التكاليف، صافي الربح، ROI، التصنيف)، مع رسومات بيانية.",
        reportsTitle: "التقارير والتحليل المتقدم",
        reportsSub: "تحليل متقدم للاستثمارات الصحية ومقارنة الأداء وتقديم توصيات استثمارية.",
        aboutTitle: "حول المنصة",
        aboutText: "تم تصميم هذه المنصة كنموذج أولي لحساب وتحليل عوائد الاستثمار الصحي في مجالات متعددة، مع دعم ثنائي اللغة وإمكانية التوسع مستقبلاً لنظام مستخدمين وصلاحيات وقاعدة بيانات.",
        teamTitle: "من نحن",
        projectsTabTitle: "مشاريع تعزيز الاستثمار الصحي",
        projectsSectionTitle: "مشاريع تعزيز الاستثمار الصحي",
        projectsSectionSub: "استكشف المشاريع المختلفة لتعزيز الاستثمار الصحي وعوائدها على الاستثمار.",
        labelRevenue: "إجمالي الإيرادات",
        labelCost: "إجمالي التكاليف",
        labelProfit: "صافي الربح",
        labelROI: "العائد على الاستثمار ROI"
    },
    en: {
        appTitle: "Health Investment ROI Platform",
        appSub: "Analyze investments in hospitals, pharma, and medical devices",
        topTitle: "Health Investment ROI Platform",
        topMeta: "Unified system to calculate and analyze health investment ROI",
        homeHeroTitle: "Welcome to the Health Investment ROI Platform",
        homeHeroSub: "Calculate ROI for hospitals, pharmaceuticals, medical devices, and non-financial benefits with a bilingual interactive dashboard.",
        selectTitle: "Select Investment Type",
        selectSub: "Choose the health investment type you want to analyze, then proceed to the input form.",
        cardHospitalTitle: "Hospital / Clinics",
        cardHospitalSub: "Analyze revenue, cost, and net profit for care providers.",
        cardPharmaTitle: "Pharmaceuticals",
        cardPharmaSub: "Investments in drug R&D, clinical trials, and manufacturing.",
        cardDevicesTitle: "Medical Devices",
        cardDevicesSub: "Evaluate feasibility of purchasing, operating, and maintaining medical devices.",
        cardNFTitle: "Non-Financial Benefits",
        cardNFSub: "Quality of service, patient satisfaction, safety, and community health.",
        inputTitle: "Input Form",
        inputSub: "Enter investment data according to the selected type, then click Calculate.",
        resultTitle: "Results & KPIs",
        resultSub: "This page shows revenue, costs, net profit, ROI and classification, along with charts.",
        reportsTitle: "Advanced Reports & Analysis",
        reportsSub: "Advanced analysis of health investments, performance comparison, and investment recommendations.",
        aboutTitle: "About the Platform",
        aboutText: "This platform is a prototype for calculating and analyzing health investment ROI in multiple domains, with bilingual support and potential future expansion to user management and databases.",
        teamTitle: "About Us",
        projectsTabTitle: "Health Investment Enhancement Projects",
        projectsSectionTitle: "Health Investment Enhancement Projects",
        projectsSectionSub: "Explore different projects to enhance health investment and their return on investment.",
        labelRevenue: "Total Revenue",
        labelCost: "Total Cost",
        labelProfit: "Net Profit",
        labelROI: "ROI"
    }
};

// بيانات المشاريع
const projectsData = {
    ar: [
        {
            id: 1,
            title: "مشروع التوعية ضد السمنة",
            description: "برنامج التوعية للوقاية من السمنة يهدف إلى تقليل معدلات السمنة بين فئة الشباب والبالغين من خلال التوعية بالتغذية الصحية والنشاط البدني.",
            target: "طلاب المدارس والجامعات - موظفو القطاع العام",
            activities: "حملات إعلامية وتثقيفية - ورش عمل مع مختصين بالتغذية - برامج رياضية مجانية أو مدعومة - توزيع منشورات توعوية",
            expectedReturn: "تقليل معدلات السمنة بنسبة 15-20% خلال 5 سنوات - انخفاض تكاليف علاج الأمراض المرتبطة بالسمنة - رفع إنتاجية الأفراد وتقليل أيام التغيب المرضي",
            indicators: "قياس مؤشر كتلة الجسم قبل وبعد البرنامج - نسبة الحضور والمشاركة - التغير في السلوك الغذائي والرياضي",
            recommendations: "التوسع في البرنامج ليشمل مناطق أخرى - إدماج البرنامج ضمن الرعاية الأولية - تطوير مواد توعية رقمية تفاعلية - تقييم سنوي لقياس الأثر الصحي والمالي",
            roi: "233%"
        },
        {
            id: 2,
            title: "مشروع التوعية ضد التدخين",
            description: "برنامج التوعية للحد من التدخين يهدف إلى تقليل نسبة المدخنين ورفع الوعي بأضرار التدخين.",
            target: "المراهقون - طلاب المدارس - الموظفون",
            activities: "محاضرات توعوية في المدارس والجامعات - حملات في وسائل الإعلام ومواقع التواصل - توفير الدعم للإقلاع عن التدخين (مثل العيادات المجانية)",
            expectedReturn: "خفض نسبة المدخنين الجدد - تقليل تكاليف الرعاية الصحية الناتجة عن أمراض التدخين - زيادة الوعي الصحي المجتمعي - خفض زيارات الطوارئ بنسبة 30% - تقليل دخول المستشفيات بنسبة 20%",
            indicators: "انخفاض نسبة المدخنين خلال فترة البرنامج - عدد المشاركين في برامج الإقلاع - عدد الحصص التوعوية المنفذة",
            recommendations: "التوسع في البرنامج ليشمل مناطق أخرى - إدماج البرنامج ضمن الرعاية الأولية - تطوير مواد توعية رقمية تفاعلية - تقييم سنوي لقياس الأثر الصحي والمالي",
            roi: "367%"
        },
        {
            id: 3,
            title: "مشروع التوعية لمرضى السكري",
            description: "برنامج توعوي شامل لمرضى السكري يهدف إلى تحسين إدارة المرض وتقليل المضاعفات.",
            target: "مرضى السكري - أفراد عائلاتهم - مقدمي الرعاية الصحية",
            activities: "جلسات توعوية حول إدارة السكري - توزيع أجهزة قياس السكر - تدريبات على حقن الأنسولين - استشارات غذائية",
            expectedReturn: "تحسين التحكم في مستويات السكر - تقليل مضاعفات السكري - خفض تكاليف الرعاية الصحية - تحسين جودة الحياة",
            indicators: "مستويات السكر التراكمي - عدد زيارات الطوارئ - معدل دخول المستشفى",
            recommendations: "التوسع في البرنامج ليشمل جميع المناطق - توفير تطبيق إلكتروني للمتابعة - تدريب مقدمي الرعاية الصحية",
            roi: "289%"
        },
        {
            id: 4,
            title: "مشروع التوعية للحوامل من فقر الدم",
            description: "برنامج توعوي للوقاية من فقر الدم لدى الحوامل وتحسين صحة الأم والجنين.",
            target: "الحوامل - النساء في سن الإنجاب - مقدمي الرعاية الصحية",
            activities: "جلسات توعوية حول التغذية - توزيع مكملات الحديد - فحوصات دورية للدم - استشارات غذائية",
            expectedReturn: "تقليل حالات فقر الدم لدى الحوامل - تحسين صحة الأم والجنين - تقليل مضاعفات الحمل والولادة",
            indicators: "مستويات الهيموجلوبين - معدل الولادات المبكرة - وزن المواليد",
            recommendations: "التوسع في البرنامج ليشمل جميع المراكز الصحية - توفير مكملات غذائية مجانية - تدريب القابلات",
            roi: "312%"
        },
        {
            id: 5,
            title: "مشروع التوعية للمباعدة بين الولادات",
            description: "برنامج توعوي لتعزيز المباعدة بين الولادات وتحسين صحة الأم والطفل.",
            target: "الأزواج - النساء في سن الإنجاب - مقدمي الرعاية الصحية",
            activities: "جلسات توعوية حول تنظيم الأسرة - توزيع وسائل منع الحمل - استشارات أسرية - ندوات تثقيفية",
            expectedReturn: "تحسين صحة الأم والطفل - تقليل وفيات الأمهات - تحسين الوضع الاقتصادي للأسر",
            indicators: "معدل استخدام وسائل منع الحمل - الفترة بين الولادات - صحة الأمهات والأطفال",
            recommendations: "التوسع في البرنامج ليشمل جميع المناطق - توفير وسائل منع الحمل مجاناً - تدريب مقدمي الخدمات",
            roi: "275%"
        },
        {
            id: 6,
            title: "مشروع التوعية لمرضى الضغط",
            description: "برنامج توعوي لمرضى الضغط يهدف إلى تحسين إدارة المرض وتقليل المضاعفات.",
            target: "مرضى الضغط - كبار السن - مقدمي الرعاية الصحية",
            activities: "جلسات توعوية حول إدارة الضغط - توزيع أجهزة قياس الضغط - استشارات غذائية - أنشطة رياضية",
            expectedReturn: "تحسين التحكم في ضغط الدم - تقليل مضاعفات الضغط - خفض تكاليف الرعاية الصحية",
            indicators: "مستويات ضغط الدم - عدد زيارات الطوارئ - معدل دخول المستشفى",
            recommendations: "التوسع في البرنامج ليشمل جميع المناطق - توفير أجهزة قياس الضغط - تدريب مقدمي الرعاية الصحية",
            roi: "298%"
        },
        {
            id: 7,
            title: "مشروع برنامج التوعية لمرض الكلى",
            description: "برنامج توعوي شامل لمرضى الكلى يهدف إلى تحسين إدارة المرض وتقليل المضاعفات.",
            target: "مرضى الكلى - الأشخاص المعرضين للإصابة - مقدمي الرعاية الصحية",
            activities: "جلسات توعوية حول أمراض الكلى - فحوصات دورية - استشارات غذائية - تدريبات على الغسيل الكلوي",
            expectedReturn: "تحسين إدارة مرض الكلى - تقليل الحاجة للغسيل الكلوي - خفض تكاليف العلاج",
            indicators: "وظائف الكلى - عدد جلسات الغسيل الكلوي - معدل دخول المستشفى",
            recommendations: "التوسع في البرنامج ليشمل جميع المناطق - توفير فحوصات مجانية - تدريب مقدمي الرعاية الصحية",
            roi: "324%"
        },
        {
            id: 8,
            title: "مشروع التوعية لإصابات حوادث السيارات",
            description: "برنامج توعوي للوقاية من إصابات حوادث السيارات وتحسين السلامة المرورية.",
            target: "السائقون - الركاب - طلاب المدارس - المجتمع عامة",
            activities: "حملات توعوية حول السلامة المرورية - توزيع مقاعد الأطفال - تدريبات على الإسعافات الأولية - محاضرات في المدارس",
            expectedReturn: "تقليل إصابات حوادث السيارات - خفض الوفيات والإعاقات - تقليل تكاليف الرعاية الصحية",
            indicators: "عدد الحوادث - عدد الإصابات والوفيات - استخدام حزام الأمان ومقاعد الأطفال",
            recommendations: "التوسع في البرنامج ليشمل جميع المناطق - تعزيز القوانين المرورية - تدريب فرق الطوارئ",
            roi: "356%"
        }
    ],
    en: [
        {
            id: 1,
            title: "Obesity Awareness Project",
            description: "Obesity prevention awareness program aimed at reducing obesity rates among youth and adults through awareness of healthy nutrition and physical activity.",
            target: "School and university students - Public sector employees",
            activities: "Media and educational campaigns - Workshops with nutrition specialists - Free or subsidized sports programs - Distribution of awareness brochures",
            expectedReturn: "Reduce obesity rates by 15-20% within 5 years - Decrease costs of treating obesity-related diseases - Increase individual productivity and reduce sick leave days",
            indicators: "Measuring BMI before and after the program - Attendance and participation rate - Change in dietary and sports behavior",
            recommendations: "Expand the program to include other areas - Integrate the program into primary care - Develop interactive digital awareness materials - Annual evaluation to measure health and financial impact",
            roi: "233%"
        },
        {
            id: 2,
            title: "Smoking Awareness Project",
            description: "Awareness program to reduce smoking rates and raise awareness of the harms of smoking.",
            target: "Teenagers - School students - Employees",
            activities: "Awareness lectures in schools and universities - Campaigns in media and social media - Providing support for quitting smoking (such as free clinics)",
            expectedReturn: "Reduce the rate of new smokers - Reduce healthcare costs resulting from smoking-related diseases - Increase community health awareness - Reduce emergency visits by 30% - Reduce hospital admissions by 20%",
            indicators: "Decrease in smoking rates during the program period - Number of participants in smoking cessation programs - Number of awareness sessions implemented",
            recommendations: "Expand the program to include other areas - Integrate the program into primary care - Develop interactive digital awareness materials - Annual evaluation to measure health and financial impact",
            roi: "367%"
        },
        {
            id: 3,
            title: "Diabetes Awareness Project",
            description: "Comprehensive awareness program for diabetic patients aimed at improving disease management and reducing complications.",
            target: "Diabetic patients - Their family members - Healthcare providers",
            activities: "Awareness sessions on diabetes management - Distribution of blood sugar monitoring devices - Insulin injection training - Nutritional consultations",
            expectedReturn: "Improved blood sugar control - Reduced diabetes complications - Lower healthcare costs - Improved quality of life",
            indicators: "HbA1c levels - Number of emergency visits - Hospital admission rate",
            recommendations: "Expand the program to cover all areas - Provide an electronic application for follow-up - Train healthcare providers",
            roi: "289%"
        },
        {
            id: 4,
            title: "Anemia Awareness Project for Pregnant Women",
            description: "Awareness program to prevent anemia in pregnant women and improve maternal and fetal health.",
            target: "Pregnant women - Women of childbearing age - Healthcare providers",
            activities: "Awareness sessions on nutrition - Distribution of iron supplements - Regular blood tests - Nutritional consultations",
            expectedReturn: "Reduce anemia cases in pregnant women - Improve maternal and fetal health - Reduce pregnancy and childbirth complications",
            indicators: "Hemoglobin levels - Preterm birth rate - Birth weight",
            recommendations: "Expand the program to include all health centers - Provide free nutritional supplements - Train midwives",
            roi: "312%"
        },
        {
            id: 5,
            title: "Birth Spacing Awareness Project",
            description: "Awareness program to promote birth spacing and improve maternal and child health.",
            target: "Couples - Women of childbearing age - Healthcare providers",
            activities: "Awareness sessions on family planning - Distribution of contraceptives - Family counseling - Educational seminars",
            expectedReturn: "Improved maternal and child health - Reduced maternal mortality - Improved economic situation for families",
            indicators: "Contraceptive use rate - Interval between births - Health of mothers and children",
            recommendations: "Expand the program to cover all areas - Provide free contraceptives - Train service providers",
            roi: "275%"
        },
        {
            id: 6,
            title: "Hypertension Awareness Project",
            description: "Awareness program for hypertension patients aimed at improving disease management and reducing complications.",
            target: "Hypertension patients - Elderly - Healthcare providers",
            activities: "Awareness sessions on blood pressure management - Distribution of blood pressure monitors - Nutritional consultations - Sports activities",
            expectedReturn: "Improved blood pressure control - Reduced hypertension complications - Lower healthcare costs",
            indicators: "Blood pressure levels - Number of emergency visits - Hospital admission rate",
            recommendations: "Expand the program to cover all areas - Provide blood pressure monitors - Train healthcare providers",
            roi: "298%"
        },
        {
            id: 7,
            title: "Kidney Disease Awareness Program",
            description: "Comprehensive awareness program for kidney patients aimed at improving disease management and reducing complications.",
            target: "Kidney patients - People at risk - Healthcare providers",
            activities: "Awareness sessions on kidney diseases - Regular checkups - Nutritional consultations - Dialysis training",
            expectedReturn: "Improved kidney disease management - Reduced need for dialysis - Lower treatment costs",
            indicators: "Kidney function - Number of dialysis sessions - Hospital admission rate",
            recommendations: "Expand the program to cover all areas - Provide free checkups - Train healthcare providers",
            roi: "324%"
        },
        {
            id: 8,
            title: "Car Accident Injuries Awareness Project",
            description: "Awareness program to prevent car accident injuries and improve road safety.",
            target: "Drivers - Passengers - School students - General public",
            activities: "Awareness campaigns on road safety - Distribution of child seats - First aid training - School lectures",
            expectedReturn: "Reduce car accident injuries - Reduce deaths and disabilities - Lower healthcare costs",
            indicators: "Number of accidents - Number of injuries and deaths - Use of seat belts and child seats",
            recommendations: "Expand the program to cover all areas - Strengthen traffic laws - Train emergency teams",
            roi: "356%"
        }
    ]
};

// نماذج إدخال البيانات الكاملة لكل نوع استثمار
const investmentForms = {
    hospital: {
        ar: [
            { id: "hospital_name", label: "اسم المستشفى/العيادة", type: "text", placeholder: "أدخل اسم المؤسسة" },
            { id: "patient_visits", label: "عدد زيارات المرضى سنوياً", type: "number", placeholder: "عدد الزيارات" },
            { id: "avg_revenue_per_visit", label: "متوسط الإيراد لكل زيارة", type: "number", placeholder: "بالعملة المحلية" },
            { id: "staff_costs", label: "تكاليف الموظفين", type: "number", placeholder: "تكاليف الرواتب والمزايا" },
            { id: "equipment_costs", label: "تكاليف المعدات", type: "number", placeholder: "تكاليف شراء وصيانة المعدات" },
            { id: "facility_costs", label: "تكاليف المرافق", type: "number", placeholder: "تكاليف التشغيل والصيانة" },
            { id: "medication_costs", label: "تكاليف الأدوية", type: "number", placeholder: "تكاليف شراء الأدوية" },
            { id: "other_costs", label: "تكاليف أخرى", type: "number", placeholder: "أي تكاليف إضافية" }
        ],
        en: [
            { id: "hospital_name", label: "Hospital/Clinic Name", type: "text", placeholder: "Enter institution name" },
            { id: "patient_visits", label: "Annual Patient Visits", type: "number", placeholder: "Number of visits" },
            { id: "avg_revenue_per_visit", label: "Average Revenue Per Visit", type: "number", placeholder: "In local currency" },
            { id: "staff_costs", label: "Staff Costs", type: "number", placeholder: "Salaries and benefits" },
            { id: "equipment_costs", label: "Equipment Costs", type: "number", placeholder: "Purchase and maintenance" },
            { id: "facility_costs", label: "Facility Costs", type: "number", placeholder: "Operations and maintenance" },
            { id: "medication_costs", label: "Medication Costs", type: "number", placeholder: "Medication purchases" },
            { id: "other_costs", label: "Other Costs", type: "number", placeholder: "Any additional costs" }
        ]
    },
    pharma: {
        ar: [
            { id: "drug_name", label: "اسم الدواء", type: "text", placeholder: "أدخل اسم الدواء" },
            { id: "rd_costs", label: "تكاليف البحث والتطوير", type: "number", placeholder: "تكاليف البحث والتجارب" },
            { id: "production_costs", label: "تكاليف الإنتاج", type: "number", placeholder: "تكاليف التصنيع" },
            { id: "marketing_costs", label: "تكاليف التسويق", type: "number", placeholder: "تكاليف الإعلان والتسويق" },
            { id: "distribution_costs", label: "تكاليف التوزيع", type: "number", placeholder: "تكاليف الشحن والتوزيع" },
            { id: "units_sold", label: "الوحدات المباعة", type: "number", placeholder: "عدد الوحدات المباعة سنوياً" },
            { id: "price_per_unit", label: "سعر الوحدة", type: "number", placeholder: "سعر بيع الوحدة" },
            { id: "regulatory_costs", label: "تكاليف تنظيمية", type: "number", placeholder: "تكاليف التراخيص والامتثال" }
        ],
        en: [
            { id: "drug_name", label: "Drug Name", type: "text", placeholder: "Enter drug name" },
            { id: "rd_costs", label: "R&D Costs", type: "number", placeholder: "Research and trial costs" },
            { id: "production_costs", label: "Production Costs", type: "number", placeholder: "Manufacturing costs" },
            { id: "marketing_costs", label: "Marketing Costs", type: "number", placeholder: "Advertising and marketing" },
            { id: "distribution_costs", label: "Distribution Costs", type: "number", placeholder: "Shipping and distribution" },
            { id: "units_sold", label: "Units Sold", type: "number", placeholder: "Annual units sold" },
            { id: "price_per_unit", label: "Price Per Unit", type: "number", placeholder: "Selling price per unit" },
            { id: "regulatory_costs", label: "Regulatory Costs", type: "number", placeholder: "Licensing and compliance" }
        ]
    },
    devices: {
        ar: [
            { id: "device_name", label: "اسم الجهاز الطبي", type: "text", placeholder: "أدخل اسم الجهاز" },
            { id: "purchase_cost", label: "تكلفة الشراء", type: "number", placeholder: "تكلفة شراء الجهاز" },
            { id: "maintenance_cost", label: "تكاليف الصيانة السنوية", type: "number", placeholder: "تكاليف الصيانة والتشغيل" },
            { id: "training_cost", label: "تكاليف التدريب", type: "number", placeholder: "تكاليف تدريب الموظفين" },
            { id: "procedures_per_year", label: "عدد الإجراءات سنوياً", type: "number", placeholder: "عدد مرات استخدام الجهاز" },
            { id: "revenue_per_procedure", label: "الإيراد لكل إجراء", type: "number", placeholder: "الإيراد من كل استخدام للجهاز" },
            { id: "device_lifespan", label: "العمر الافتراضي للجهاز (سنوات)", type: "number", placeholder: "عدد سنوات استخدام الجهاز" },
            { id: "other_device_costs", label: "تكاليف أخرى", type: "number", placeholder: "أي تكاليف إضافية" }
        ],
        en: [
            { id: "device_name", label: "Medical Device Name", type: "text", placeholder: "Enter device name" },
            { id: "purchase_cost", label: "Purchase Cost", type: "number", placeholder: "Device purchase cost" },
            { id: "maintenance_cost", label: "Annual Maintenance Cost", type: "number", placeholder: "Maintenance and operation" },
            { id: "training_cost", label: "Training Costs", type: "number", placeholder: "Staff training costs" },
            { id: "procedures_per_year", label: "Procedures Per Year", type: "number", placeholder: "Number of device uses" },
            { id: "revenue_per_procedure", label: "Revenue Per Procedure", type: "number", placeholder: "Revenue per device use" },
            { id: "device_lifespan", label: "Device Lifespan (Years)", type: "number", placeholder: "Years of device usage" },
            { id: "other_device_costs", label: "Other Costs", type: "number", placeholder: "Any additional costs" }
        ]
    },
    nonfinancial: {
        ar: [
            { id: "project_name", label: "اسم المشروع", type: "text", placeholder: "أدخل اسم المشروع" },
            { id: "patient_satisfaction", label: "رضا المرضى (%)", type: "number", placeholder: "نسبة رضا المرضى" },
            { id: "error_rate", label: "معدل الأخطاء (%)", type: "number", placeholder: "نسبة الأخطاء الطبية" },
            { id: "infection_rate", label: "معدل العدوى (%)", type: "number", placeholder: "نسبة العدوى المكتسبة" },
            { id: "health_index", label: "مؤشر الصحة المجتمعية", type: "number", placeholder: "مؤشر تحسن الصحة المجتمعية" },
            { id: "project_costs", label: "تكاليف المشروع", type: "number", placeholder: "إجمالي تكاليف المشروع" },
            { id: "time_saved", label: "الوقت المحفوظ (ساعات)", type: "number", placeholder: "الوقت المحفوظ في الإجراءات" },
            { id: "lives_saved", label: "عدد الأرواح المحفوظة", type: "number", placeholder: "تقدير عدد الأرواح المحفوظة" }
        ],
        en: [
            { id: "project_name", label: "Project Name", type: "text", placeholder: "Enter project name" },
            { id: "patient_satisfaction", label: "Patient Satisfaction (%)", type: "number", placeholder: "Patient satisfaction rate" },
            { id: "error_rate", label: "Error Rate (%)", type: "number", placeholder: "Medical error rate" },
            { id: "infection_rate", label: "Infection Rate (%)", type: "number", placeholder: "Hospital-acquired infection rate" },
            { id: "health_index", label: "Community Health Index", type: "number", placeholder: "Community health improvement index" },
            { id: "project_costs", label: "Project Costs", type: "number", placeholder: "Total project costs" },
            { id: "time_saved", label: "Time Saved (Hours)", type: "number", placeholder: "Time saved in procedures" },
            { id: "lives_saved", label: "Lives Saved", type: "number", placeholder: "Estimated lives saved" }
        ]
    }
};

// المتغيرات العامة
let currentLang = 'ar';
let currentInvestment = null;
let investmentHistory = [];

try {
    if (typeof localStorage !== 'undefined') {
        const storedHistory = localStorage.getItem('healthROIHistory');
        if (storedHistory) {
            investmentHistory = JSON.parse(storedHistory);
        }
    }
} catch (e) {
    console.warn('LocalStorage access denied or not supported', e);
}

// وظيفة تسجيل الدخول
function doLogin() {
    const usernameInput = document.getElementById('loginUser');
    const passwordInput = document.getElementById('loginPass');
    
    if (!usernameInput || !passwordInput) return;

    const username = usernameInput.value.trim().toLowerCase();
    const password = passwordInput.value.trim().toLowerCase();
    
    if (username === 'moh' && password === 'moh') {
        document.getElementById('loginScreen').style.display = 'none';
        document.getElementById('mainLayout').style.display = 'flex';
        setLangTexts();
        loadProjectsTab();
        showSection('home');
    } else {
        alert(currentLang === 'ar' ? 'اسم المستخدم أو كلمة المرور غير صحيحة' : 'Invalid username or password');
    }
}

// وظيفة تعيين النصوص
function setLangTexts() {
    const t = text[currentLang];
    document.getElementById('appTitle').textContent = t.appTitle;
    document.getElementById('appSub').textContent = t.appSub;
    document.getElementById('topTitle').textContent = t.topTitle;
    document.getElementById('topMeta').textContent = t.topMeta;
    document.getElementById('homeHeroTitle').textContent = t.homeHeroTitle;
    document.getElementById('homeHeroSub').textContent = t.homeHeroSub;
    document.getElementById('selectTitle').textContent = t.selectTitle;
    document.getElementById('selectSub').textContent = t.selectSub;
    document.getElementById('cardHospitalTitle').textContent = t.cardHospitalTitle;
    document.getElementById('cardHospitalSub').textContent = t.cardHospitalSub;
    document.getElementById('cardPharmaTitle').textContent = t.cardPharmaTitle;
    document.getElementById('cardPharmaSub').textContent = t.cardPharmaSub;
    document.getElementById('cardDevicesTitle').textContent = t.cardDevicesTitle;
    document.getElementById('cardDevicesSub').textContent = t.cardDevicesSub;
    document.getElementById('cardNFTitle').textContent = t.cardNFTitle;
    document.getElementById('cardNFSub').textContent = t.cardNFSub;
    document.getElementById('inputTitle').textContent = t.inputTitle;
    document.getElementById('inputSub').textContent = t.inputSub;
    document.getElementById('resultTitle').textContent = t.resultTitle;
    document.getElementById('resultSub').textContent = t.resultSub;
    document.getElementById('reportsTitle').textContent = t.reportsTitle;
    document.getElementById('reportsSub').textContent = t.reportsSub;
    document.getElementById('aboutTitle').textContent = t.aboutTitle;
    document.getElementById('aboutText').textContent = t.aboutText;
    document.getElementById('teamTitle').textContent = t.teamTitle;
    document.getElementById('projectsTabTitle').textContent = t.projectsTabTitle;
    const horizontalProjectsTab = document.getElementById('horizontalProjectsTabTitle');
    if (horizontalProjectsTab) horizontalProjectsTab.textContent = t.projectsTabTitle;
    const projectsSectionTitle = document.getElementById('projectsSectionTitle');
    if (projectsSectionTitle) projectsSectionTitle.textContent = t.projectsSectionTitle;
    const projectsSectionSub = document.getElementById('projectsSectionSub');
    if (projectsSectionSub) projectsSectionSub.textContent = t.projectsSectionSub;
    document.getElementById('labelRevenue').textContent = t.labelRevenue;
    document.getElementById('labelCost').textContent = t.labelCost;
    document.getElementById('labelProfit').textContent = t.labelProfit;
    document.getElementById('labelROI').textContent = t.labelROI;
}

// وظيفة تبديل اللغة
function switchLang() {
    currentLang = currentLang === 'ar' ? 'en' : 'ar';
    document.body.dir = currentLang === 'ar' ? 'rtl' : 'ltr';
    setLangTexts();
    loadProjectsTab();
    
    // Reload projects section if it's currently visible
    const projectsSection = document.getElementById('projectsSection');
    if (projectsSection && projectsSection.style.display !== 'none') {
        loadProjectsSection();
    }
    
    if (currentInvestment) {
        loadInvestmentForm(currentInvestment);
    }
}

// وظيفة عرض القسم
function showSection(sectionId) {
    // إخفاء جميع الأقسام
    const sections = ['home', 'selection', 'input', 'dashboard', 'reports', 'projects', 'about', 'team'];
    sections.forEach(section => {
        const sectionEl = document.getElementById(section + 'Section');
        if (sectionEl) sectionEl.style.display = 'none';
    });
    
    // إظهار القسم المحدد
    const targetSection = document.getElementById(sectionId + 'Section');
    if (targetSection) {
        targetSection.style.display = 'block';
        
        // تحميل المشاريع إذا كان القسم هو projects
        if (sectionId === 'projects') {
            loadProjectsSection();
        }
    }
    
    // تحديث القوائم النشطة
    document.querySelectorAll('.nav-item').forEach(item => item.classList.remove('active'));
    document.querySelectorAll('.horizontal-tab').forEach(item => item.classList.remove('active'));
    
    // تحديث الشريط الجانبي
    const navMap = {
        'home': 'الصفحة الرئيسية',
        'dashboard': 'لوحة التحكم',
        'reports': 'التقارير والتحليل',
        'about': 'حول المنصة',
        'team': 'من نحن'
    };
    
    const activeNavText = navMap[sectionId];
    if (activeNavText) {
        const activeNavItem = Array.from(document.querySelectorAll('.nav-item')).find(item => 
            item.textContent.includes(activeNavText)
        );
        if (activeNavItem) activeNavItem.classList.add('active');
    }
    
    // تحديث الشريط الأفقي
    if (sectionId === 'projects') {
        const projectsTab = document.querySelector('.horizontal-tab[onclick*="projects"]');
        if (projectsTab) projectsTab.classList.add('active');
    } else {
        const tabMap = {
            'home': 'الصفحة الرئيسية',
            'selection': 'حساب ROI',
            'reports': 'التقارير والتحليل'
        };
        
        const activeTabText = tabMap[sectionId];
        if (activeTabText) {
            const activeTab = Array.from(document.querySelectorAll('.horizontal-tab')).find(item => {
                const span = item.querySelector('span');
                return span && (span.textContent.includes(activeTabText) || activeTabText.includes(span.textContent));
            });
            if (activeTab) activeTab.classList.add('active');
        }
    }
}

// وظائف المشاريع
function toggleProjectsTab() {
    const tabContent = document.getElementById('projectsTabContent');
    const tabIcon = document.getElementById('projectsTabIcon');
    
    if (tabContent.classList.contains('active')) {
        tabContent.classList.remove('active');
        tabIcon.classList.remove('fa-chevron-up');
        tabIcon.classList.add('fa-chevron-down');
    } else {
        tabContent.classList.add('active');
        tabIcon.classList.remove('fa-chevron-down');
        tabIcon.classList.add('fa-chevron-up');
    }
}

function loadProjectsTab() {
    const projectsGrid = document.getElementById('projectsTabGrid');
    const projects = projectsData[currentLang];
    
    projectsGrid.innerHTML = '';
    
    projects.forEach(project => {
        const projectCard = document.createElement('div');
        projectCard.className = 'project-tab-card';
        projectCard.onclick = () => showProjectDetails(project.id);
        
        projectCard.innerHTML = `
            <h3>${project.title}</h3>
            <p>${project.description.substring(0, 100)}...</p>
            <div class="project-tab-roi">ROI: ${project.roi}</div>
        `;
        
        projectsGrid.appendChild(projectCard);
    });
}

function loadProjectsSection() {
    const projectsGrid = document.getElementById('projectsSectionGrid');
    if (!projectsGrid) return;
    
    const projects = projectsData[currentLang];
    
    projectsGrid.innerHTML = '';
    
    projects.forEach(project => {
        const projectCard = document.createElement('div');
        projectCard.className = 'project-tab-card';
        projectCard.onclick = () => showProjectDetailsStandalone(project.id);
        
        projectCard.innerHTML = `
            <h3>${project.title}</h3>
            <p>${project.description.substring(0, 100)}...</p>
            <div class="project-tab-roi">ROI: ${project.roi}</div>
        `;
        
        projectsGrid.appendChild(projectCard);
    });
}

function showProjectDetails(projectId) {
    const project = projectsData[currentLang].find(p => p.id === projectId);
    if (!project) return;
    
    const projectDetailsSection = document.getElementById('projectDetailsSection');
    projectDetailsSection.innerHTML = `
        <div class="card">
            <div class="card-header">
                <h2><i class="fas fa-project-diagram"></i> ${project.title}</h2>
            </div>
            <p>${project.description}</p>
            <div class="project-details">
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'الفئة المستهدفة:' : 'Target Group:'}</div>
                    <div class="project-detail-value">${project.target || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'الأنشطة:' : 'Activities:'}</div>
                    <div class="project-detail-value">${project.activities || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'العائد المتوقع:' : 'Expected Return:'}</div>
                    <div class="project-detail-value">${project.expectedReturn || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'المؤشرات:' : 'Indicators:'}</div>
                    <div class="project-detail-value">${project.indicators || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'التوصيات:' : 'Recommendations:'}</div>
                    <div class="project-detail-value">${project.recommendations || ''}</div>
                </div>
            </div>
            <div class="project-roi">
                ${currentLang === 'ar' ? 'العائد على الاستثمار:' : 'Return on Investment:'} ${project.roi}
            </div>
        </div>
    `;
    
    projectDetailsSection.style.display = 'block';
    
    setTimeout(() => {
        projectDetailsSection.scrollIntoView({ behavior: 'smooth' });
    }, 100);
}

function showProjectDetailsStandalone(projectId) {
    const project = projectsData[currentLang].find(p => p.id === projectId);
    if (!project) return;
    
    const projectDetailsSection = document.getElementById('projectDetailsSectionStandalone');
    if (!projectDetailsSection) return;
    
    projectDetailsSection.innerHTML = `
        <div class="card">
            <div class="card-header">
                <h2><i class="fas fa-project-diagram"></i> ${project.title}</h2>
            </div>
            <p>${project.description}</p>
            <div class="project-details">
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'الفئة المستهدفة:' : 'Target Group:'}</div>
                    <div class="project-detail-value">${project.target || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'الأنشطة:' : 'Activities:'}</div>
                    <div class="project-detail-value">${project.activities || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'العائد المتوقع:' : 'Expected Return:'}</div>
                    <div class="project-detail-value">${project.expectedReturn || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'المؤشرات:' : 'Indicators:'}</div>
                    <div class="project-detail-value">${project.indicators || ''}</div>
                </div>
                <div class="project-detail-item">
                    <div class="project-detail-label">${currentLang === 'ar' ? 'التوصيات:' : 'Recommendations:'}</div>
                    <div class="project-detail-value">${project.recommendations || ''}</div>
                </div>
            </div>
            <div class="project-roi">
                ${currentLang === 'ar' ? 'العائد على الاستثمار:' : 'Return on Investment:'} ${project.roi}
            </div>
        </div>
    `;
    
    projectDetailsSection.style.display = 'block';
    
    setTimeout(() => {
        projectDetailsSection.scrollIntoView({ behavior: 'smooth' });
    }, 100);
}

// وظائف الاستثمار
function selectInvestment(type) {
    currentInvestment = type;
    loadInvestmentForm(type);
    showSection('input');
}

function loadInvestmentForm(type) {
    const formContainer = document.getElementById('dynamicForm');
    const formFields = investmentForms[type][currentLang];
    
    formContainer.innerHTML = '';
    
    formFields.forEach(field => {
        const formGroup = document.createElement('div');
        formGroup.className = 'form-group';
        formGroup.innerHTML = `
            <label class="form-label" for="${field.id}">${field.label}</label>
            <input type="${field.type}" id="${field.id}" class="form-input" placeholder="${field.placeholder}">
        `;
        formContainer.appendChild(formGroup);
    });
}

function fillDummyData() {
    const formFields = investmentForms[currentInvestment][currentLang];
    
    formFields.forEach(field => {
        const input = document.getElementById(field.id);
        if (input) {
            if (field.type === 'number') {
                if (field.id.includes('cost') || field.id.includes('revenue') || field.id.includes('price')) {
                    input.value = Math.floor(Math.random() * 1000000) + 10000;
                } else if (field.id.includes('rate') || field.id.includes('satisfaction')) {
                    input.value = Math.floor(Math.random() * 30) + 70;
                } else if (field.id.includes('visits') || field.id.includes('units') || field.id.includes('procedures')) {
                    input.value = Math.floor(Math.random() * 10000) + 1000;
                } else if (field.id.includes('lifespan')) {
                    input.value = Math.floor(Math.random() * 10) + 5;
                } else if (field.id.includes('time_saved')) {
                    input.value = Math.floor(Math.random() * 1000) + 100;
                } else if (field.id.includes('lives_saved')) {
                    input.value = Math.floor(Math.random() * 100) + 10;
                } else {
                    input.value = Math.floor(Math.random() * 100) + 1;
                }
            } else if (field.type === 'text') {
                if (currentLang === 'ar') {
                    input.value = `بيانات تجريبية ${field.label}`;
                } else {
                    input.value = `Sample data for ${field.label}`;
                }
            }
        }
    });
    
    alert(currentLang === 'ar' ? 'تم تعبئة البيانات التجريبية' : 'Sample data has been filled');
}

function calculateROI() {
    if (!currentInvestment) return;
    
    const formFields = investmentForms[currentInvestment][currentLang];
    const inputData = {};
    
    formFields.forEach(field => {
        const input = document.getElementById(field.id);
        inputData[field.id] = parseFloat(input.value) || 0;
    });
    
    let results = {};
    switch(currentInvestment) {
        case 'hospital':
            results = calculateHospitalROI(inputData);
            break;
        case 'pharma':
            results = calculatePharmaROI(inputData);
            break;
        case 'devices':
            results = calculateDevicesROI(inputData);
            break;
        case 'nonfinancial':
            results = calculateNonFinancialROI(inputData);
            break;
    }
    
    // حفظ في السجل
    const calculation = {
        id: Date.now(),
        type: currentInvestment,
        data: inputData,
        results: results,
        timestamp: new Date().toISOString()
    };
    
    investmentHistory.unshift(calculation);
    
    try {
        localStorage.setItem('healthROIHistory', JSON.stringify(investmentHistory));
    } catch (e) {
        console.warn('Could not save to localStorage', e);
    }
    
    displayResults(results);
    showSection('dashboard');
}

function calculateHospitalROI(data) {
    const totalRevenue = data.patient_visits * data.avg_revenue_per_visit;
    const totalCost = data.staff_costs + data.equipment_costs + data.facility_costs + 
                     data.medication_costs + data.other_costs;
    const netProfit = totalRevenue - totalCost;
    const roi = totalCost > 0 ? (netProfit / totalCost) * 100 : 0;
    
    return { totalRevenue, totalCost, netProfit, roi };
}

function calculatePharmaROI(data) {
    const totalRevenue = data.units_sold * data.price_per_unit;
    const totalCost = data.rd_costs + data.production_costs + data.marketing_costs + 
                     data.distribution_costs + data.regulatory_costs;
    const netProfit = totalRevenue - totalCost;
    const roi = totalCost > 0 ? (netProfit / totalCost) * 100 : 0;
    
    return { totalRevenue, totalCost, netProfit, roi };
}

function calculateDevicesROI(data) {
    const annualRevenue = data.procedures_per_year * data.revenue_per_procedure;
    const annualCost = data.purchase_cost / data.device_lifespan + data.maintenance_cost + 
                      data.training_cost + data.other_device_costs;
    const netProfit = annualRevenue - annualCost;
    const roi = annualCost > 0 ? (netProfit / annualCost) * 100 : 0;
    
    return { totalRevenue: annualRevenue, totalCost: annualCost, netProfit, roi };
}

function calculateNonFinancialROI(data) {
    const healthBenefits = (data.patient_satisfaction + (100 - data.error_rate) + 
                          (100 - data.infection_rate) + data.health_index) / 4;
    const roi = data.project_costs > 0 ? (healthBenefits * 1000 / data.project_costs) : 0;
    
    return { 
        totalRevenue: 0,
        totalCost: data.project_costs,
        netProfit: -data.project_costs,
        roi,
        nonFinancial: {
            patientSatisfaction: data.patient_satisfaction,
            errorRate: data.error_rate,
            infectionRate: data.infection_rate,
            healthIndex: data.health_index,
            timeSaved: data.time_saved,
            livesSaved: data.lives_saved
        }
    };
}

function displayResults(results) {
    document.getElementById('kpiRevenue').textContent = formatNumber(results.totalRevenue);
    document.getElementById('kpiCost').textContent = formatNumber(results.totalCost);
    document.getElementById('kpiProfit').textContent = formatNumber(results.netProfit);
    document.getElementById('kpiROI').textContent = results.roi.toFixed(2) + '%';
}

function formatNumber(num) {
    // Use Latin numerals (0-9) for both Arabic and English
    return new Intl.NumberFormat(currentLang === 'ar' ? 'ar-SA' : 'en-US', {
        numberingSystem: 'latn'
    }).format(Math.round(num));
}

// وظائف التقارير
function generateReport(type) {
    const reportsContent = document.getElementById('reportsContent');
    
    if (investmentHistory.length === 0) {
        reportsContent.innerHTML = `<p>${currentLang === 'ar' ? 'لا توجد حسابات سابقة' : 'No previous calculations'}</p>`;
        return;
    }
    
    let reportHTML = '';
    
    if (type === 'financial') {
        reportHTML = generateFinancialReport();
    } else if (type === 'comparison') {
        reportHTML = generateComparisonReport();
    } else if (type === 'risk') {
        reportHTML = generateRiskReport();
    }
    
    reportsContent.innerHTML = reportHTML;
}

function generateFinancialReport() {
    const latestCalc = investmentHistory[0];
    return `
        <div class="card">
            <h3>${currentLang === 'ar' ? 'تقرير الأداء المالي' : 'Financial Performance Report'}</h3>
            <p><strong>${currentLang === 'ar' ? 'العائد على الاستثمار:' : 'ROI:'}</strong> ${latestCalc.results.roi.toFixed(2)}%</p>
            <p><strong>${currentLang === 'ar' ? 'صافي الربح:' : 'Net Profit:'}</strong> ${formatNumber(latestCalc.results.netProfit)}</p>
            <p><strong>${currentLang === 'ar' ? 'نسبة الربحية:' : 'Profit Margin:'}</strong> ${(latestCalc.results.totalRevenue > 0 ? (latestCalc.results.netProfit / latestCalc.results.totalRevenue) * 100 : 0).toFixed(2)}%</p>
        </div>
    `;
}

function generateComparisonReport() {
    if (investmentHistory.length < 2) {
        return `<p>${currentLang === 'ar' ? 'تحتاج إلى حسابين على الأقل للمقارنة' : 'You need at least two calculations for comparison'}</p>`;
    }
    
    let comparisons = '';
    investmentHistory.slice(0, 3).forEach((calc, index) => {
        comparisons += `
            <div class="history-item">
                <strong>${currentLang === 'ar' ? 'حساب ' : 'Calculation '}${index + 1}</strong>
                <p>ROI: ${calc.results.roi.toFixed(2)}%</p>
                <p>${currentLang === 'ar' ? 'صافي الربح: ' : 'Net Profit: '}${formatNumber(calc.results.netProfit)}</p>
            </div>
        `;
    });
    
    return `
        <div class="card">
            <h3>${currentLang === 'ar' ? 'مقارنة الاستثمارات' : 'Investment Comparison'}</h3>
            ${comparisons}
        </div>
    `;
}

function generateRiskReport() {
    const latestCalc = investmentHistory[0];
    const riskLevel = latestCalc.results.roi > 20 ? 'low' : latestCalc.results.roi > 10 ? 'medium' : 'high';
    const riskText = {
        ar: { low: 'منخفض', medium: 'متوسط', high: 'مرتفع' },
        en: { low: 'Low', medium: 'Medium', high: 'High' }
    };
    
    return `
        <div class="card">
            <h3>${currentLang === 'ar' ? 'تحليل المخاطر' : 'Risk Analysis'}</h3>
            <p><strong>${currentLang === 'ar' ? 'مستوى المخاطرة:' : 'Risk Level:'}</strong> ${riskText[currentLang][riskLevel]}</p>
            <p><strong>${currentLang === 'ar' ? 'التوصيات:' : 'Recommendations:'}</strong></p>
            <ul>
                <li>${currentLang === 'ar' ? 'مراقبة الأداء بانتظام' : 'Monitor performance regularly'}</li>
                <li>${currentLang === 'ar' ? 'تنويع الاستثمارات' : 'Diversify investments'}</li>
                <li>${currentLang === 'ar' ? 'وضع خطة طوارئ' : 'Develop contingency plan'}</li>
            </ul>
        </div>
    `;
}

// التهيئة الأولية
document.addEventListener('DOMContentLoaded', function() {
    const loginForm = document.getElementById('loginForm');
    if (loginForm) {
        loginForm.addEventListener('submit', function(e) {
            e.preventDefault();
            doLogin();
        });
    }
});
</script>
</body>
</html>