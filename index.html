<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>KametiPay Pro</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Noto+Nastaliq+Urdu:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-color: #0b0f19;
            --accent-primary: #8b5cf6;
            --accent-secondary: #ec4899;
            --text-main: #ffffff;
            --text-sub: #e2e8f0;
            --border-color: rgba(255, 255, 255, 0.25);
        }

        body.theme-light {
            --bg-color: #f3f4f6;
            --accent-primary: #3b82f6;
            --accent-secondary: #1d4ed8;
            --text-main: #0f172a;
            --text-sub: #334155;
            --border-color: rgba(0, 0, 0, 0.15);
        }

        body.theme-gold {
            --bg-color: #14100b;
            --accent-primary: #eab308;
            --accent-secondary: #ca8a04;
            --text-main: #fef08a;
            --text-sub: #e2e8f0;
            --border-color: rgba(234, 179, 8, 0.3);
        }

        body.theme-cyber {
            --bg-color: #030712;
            --accent-primary: #06b6d4;
            --accent-secondary: #f43f5e;
            --text-main: #f1f5f9;
            --text-sub: #cbd5e1;
            --border-color: rgba(6, 182, 212, 0.3);
        }

        body.theme-emerald {
            --bg-color: #022c22;
            --accent-primary: #10b981;
            --accent-secondary: #34d399;
            --text-main: #ecfdf5;
            --text-sub: #a7f3d0;
            --border-color: rgba(16, 185, 129, 0.3);
        }

        body.theme-sunset {
            --bg-color: #2e1065;
            --accent-primary: #f43f5e;
            --accent-secondary: #fb923c;
            --text-main: #fff1f2;
            --text-sub: #fecdd3;
            --border-color: rgba(244, 63, 94, 0.3);
        }

        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Plus Jakarta Sans', sans-serif; }

        body.lang-rtl {
            direction: rtl;
            font-family: 'Noto Nastaliq Urdu', 'Plus Jakarta Sans', sans-serif;
        }

        html, body {
            width: 100%; min-height: 100vh;
            background-color: var(--bg-color); color: var(--text-main);
            overflow-x: hidden; overflow-y: auto;
            background-size: cover; background-position: center; background-attachment: fixed;
        }

        body { padding: 12px; display: flex; justify-content: center; align-items: flex-start; }

        /* Modern Smooth Splash Animation */
        #splash-screen {
            position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
            background: radial-gradient(circle, #1e1b4b 0%, #0b0f19 100%);
            display: flex; flex-direction: column;
            justify-content: center; align-items: center; z-index: 9999;
            transition: opacity 0.6s ease, visibility 0.6s;
        }

        .splash-icon-box {
            width: 90px; height: 90px; border-radius: 50%;
            background: linear-gradient(135deg, #8b5cf6, #ec4899);
            display: flex; align-items: center; justify-content: center;
            font-size: 38px; color: #ffffff;
            box-shadow: 0 0 30px rgba(139, 92, 246, 0.7);
            animation: pulseSplash 1.5s infinite alternate;
        }

        @keyframes pulseSplash {
            0% { transform: scale(0.9); box-shadow: 0 0 15px rgba(139, 92, 246, 0.4); }
            100% { transform: scale(1.1); box-shadow: 0 0 35px rgba(236, 72, 153, 0.8); }
        }

        .splash-title {
            font-size: 28px; font-weight: 800; margin-top: 18px;
            background: linear-gradient(135deg, #a78bfa, #f472b6);
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
            letter-spacing: 0.5px;
        }

        .drawer-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0,0,0,0.5); z-index: 1000; display: none;
            backdrop-filter: blur(2px);
        }

        .drawer-menu {
            position: fixed; top: 0; left: -290px; width: 290px; height: 100%;
            background: rgba(15, 23, 42, 0.92); border-right: 1px solid var(--border-color);
            z-index: 1001; padding: 20px; transition: left 0.3s ease;
            display: flex; flex-direction: column; gap: 12px; overflow-y: auto;
            backdrop-filter: blur(16px); -webkit-backdrop-filter: blur(16px);
        }

        body.lang-rtl .drawer-menu {
            left: auto; right: -290px; border-right: none; border-left: 1px solid var(--border-color);
            transition: right 0.3s ease;
        }

        .drawer-menu.active { left: 0; }
        body.lang-rtl .drawer-menu.active { right: 0; left: auto; }
        .drawer-overlay.active { display: block; }

        .profile-upload-section {
            display: flex; flex-direction: column; align-items: center; gap: 8px;
            padding: 12px; border-radius: 12px;
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid var(--border-color); margin-bottom: 6px;
        }

        .profile-img-preview {
            width: 65px; height: 65px; border-radius: 50%;
            border: 2px solid var(--accent-secondary); background: #111827;
            object-fit: cover; display: flex; align-items: center; justify-content: center;
            overflow: hidden;
        }

        .profile-img-preview img { width: 100%; height: 100%; object-fit: cover; }

        .btn-upload-pic {
            background: rgba(255, 255, 255, 0.15); border: 1px solid var(--border-color);
            color: var(--text-main); padding: 6px 12px; border-radius: 6px;
            font-size: 11px; font-weight: 600; cursor: pointer;
            display: flex; align-items: center; gap: 6px;
        }

        .lang-select-box {
            width: 100%; padding: 8px; border-radius: 8px;
            background: rgba(255,255,255,0.15); border: 1px solid var(--accent-primary);
            color: var(--text-main); font-weight: 700; outline: none; cursor: pointer;
        }
        .lang-select-box option { background: #0b0f19; color: #ffffff; }

        .google-box {
            display: flex; flex-direction: column; align-items: center; gap: 8px;
            padding: 10px; background: rgba(255,255,255,0.08);
            border: 1px solid var(--border-color); border-radius: 10px; margin-bottom: 6px;
        }

        .btn-google-login {
            width: 100%; padding: 10px; border-radius: 8px;
            background: #ffffff; color: #111827; border: none;
            font-weight: 700; font-size: 12px; cursor: pointer;
            display: flex; align-items: center; justify-content: center; gap: 8px;
        }

        .btn-google-logout {
            background: rgba(239, 68, 68, 0.25); border: 1px solid rgba(239, 68, 68, 0.6);
            color: #f87171; padding: 4px 8px; border-radius: 6px; font-size: 10px;
            cursor: pointer; margin-top: 4px; font-weight: 600;
        }

        .theme-btn {
            width: 100%; padding: 10px; border-radius: 8px;
            background: rgba(255,255,255,0.1); border: 1px solid var(--border-color);
            color: var(--text-main); text-align: left; cursor: pointer; font-weight: 600;
            font-size: 12px; display: flex; align-items: center; gap: 8px;
        }

        body.lang-rtl .theme-btn { text-align: right; }

        .btn-action-data {
            width: 100%; padding: 10px; border-radius: 8px;
            background: rgba(16, 185, 129, 0.25); border: 1px solid #10b981;
            color: #34d399; font-weight: 700; cursor: pointer; font-size: 12px;
            display: flex; align-items: center; justify-content: center; gap: 8px;
        }

        .container {
            width: 100%; max-width: 480px; display: flex; flex-direction: column; gap: 14px;
            padding-bottom: 30px; z-index: 10;
        }

        .header { display: flex; justify-content: space-between; align-items: center; }

        .menu-bar-btn {
            width: 38px; height: 38px; border-radius: 10px;
            background: rgba(15, 23, 42, 0.6); border: 1px solid rgba(255, 255, 255, 0.3);
            backdrop-filter: blur(4px);
            display: flex; align-items: center; justify-content: center;
            color: var(--text-main); cursor: pointer; font-size: 18px;
        }

        .brand-title {
            font-size: 22px; font-weight: 800;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
            filter: drop-shadow(0 2px 6px rgba(0,0,0,0.8));
        }

        .card {
            background: rgba(11, 15, 25, 0.75) !important;
            border: 1px solid rgba(255, 255, 255, 0.3) !important;
            border-radius: 16px; padding: 16px;
            backdrop-filter: none !important;
            -webkit-backdrop-filter: none !important;
            box-shadow: 0 8px 24px 0 rgba(0, 0, 0, 0.4);
        }

        .leader-badge-box {
            display: flex; align-items: center; justify-content: space-between;
            background: rgba(139, 92, 246, 0.15); border: 1px solid var(--accent-primary);
            padding: 8px 12px; border-radius: 10px; margin-bottom: 12px; font-size: 13px;
        }

        .grid-stats { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
        .stat-box {
            background: rgba(0, 0, 0, 0.3); border: 1px solid rgba(255, 255, 255, 0.2);
            padding: 12px; border-radius: 12px; text-align: center;
        }
        .stat-box h5 { font-size: 11px; color: var(--text-sub); text-transform: uppercase; letter-spacing: 0.5px; }
        .stat-box p { font-size: 17px; font-weight: 800; margin-top: 4px; text-shadow: 0 2px 4px rgba(0,0,0,0.9); }

        .wheel-outer-ring {
            position: relative; width: 275px; height: 275px; margin: 15px auto;
            border-radius: 50%;
            background: rgba(0, 0, 0, 0.4);
            border: 6px solid rgba(255, 255, 255, 0.3);
            box-shadow: 0 10px 30px rgba(0,0,0,0.6);
            display: flex; justify-content: center; align-items: center;
        }

        .wheel-pointer {
            position: absolute; top: -14px; left: 50%; transform: translateX(-50%);
            z-index: 25; width: 0; height: 0;
            border-left: 14px solid transparent;
            border-right: 14px solid transparent;
            border-top: 26px solid #ff3b30;
            filter: drop-shadow(0 4px 6px rgba(0,0,0,0.8));
        }

        #wheelCanvas {
            width: 250px; height: 250px; border-radius: 50%;
            box-shadow: inset 0 0 12px rgba(0,0,0,0.5);
            transition: transform 5s cubic-bezier(0.15, 0.85, 0.15, 1);
        }

        .wheel-center-cap {
            position: absolute; width: 42px; height: 42px; border-radius: 50%;
            background: radial-gradient(circle, #ffd700 0%, #b8860b 100%);
            border: 3px solid #ffffff;
            box-shadow: 0 4px 10px rgba(0,0,0,0.6);
            z-index: 15; pointer-events: none;
            display: flex; align-items: center; justify-content: center;
            color: #000; font-size: 14px;
        }

        .btn-draw {
            width: 100%; padding: 14px; background: linear-gradient(135deg, #8b5cf6, #ec4899);
            border: none; border-radius: 12px; color: white; font-size: 15px; font-weight: 800; cursor: pointer;
            box-shadow: 0 4px 18px rgba(139, 92, 246, 0.5); margin-top: 8px;
        }
        .btn-draw:active { transform: scale(0.98); }
        .btn-draw:disabled { opacity: 0.6; cursor: not-allowed; }

        .form-group { margin-bottom: 8px; }
        .form-label { font-size: 11px; color: var(--text-sub); display: block; margin-bottom: 2px; font-weight: 600; }
        .form-control {
            width: 100%; padding: 10px; background: rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.3); border-radius: 8px;
            color: var(--text-main); outline: none; font-size: 13px;
        }
        .form-control::placeholder { color: rgba(255, 255, 255, 0.6); }

        .btn-submit {
            width: 100%; padding: 11px;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            border: none; border-radius: 8px; color: white; font-weight: 700; cursor: pointer;
            box-shadow: 0 4px 12px rgba(0,0,0,0.4);
        }

        .member-img-preview {
            width: 40px; height: 40px; border-radius: 50%;
            border: 1.5px solid var(--accent-primary);
            object-fit: cover; background: rgba(255,255,255,0.1);
        }

        .member-info-group { display: flex; align-items: center; gap: 10px; }

        .member-card {
            background: rgba(0, 0, 0, 0.3); border: 1px solid rgba(255, 255, 255, 0.25);
            border-radius: 12px; padding: 10px; margin-bottom: 10px;
        }

        .member-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px; }
        .attendance-row { display: grid; grid-template-columns: repeat(5, 1fr); gap: 6px; }

        .day-box {
            height: 32px; border-radius: 6px; font-size: 10px; font-weight: 700;
            display: flex; align-items: center; justify-content: center;
            border: 1px solid rgba(255, 255, 255, 0.25); background: rgba(0, 0, 0, 0.3);
            color: var(--text-main); cursor: pointer;
        }

        .day-box.p-state { background: rgba(34, 197, 94, 0.6); border-color: #22c55e; color: #4ade80; }
        .day-box.a-state { background: rgba(239, 68, 68, 0.6); border-color: #ef4444; color: #f87171; }

        .won-badge {
            background: rgba(234, 179, 8, 0.4); color: #fde047; border: 1px solid #eab308;
            padding: 2px 6px; border-radius: 4px; font-size: 9px; font-weight: 800;
        }

        .btn-toggle-win {
            background: rgba(255, 255, 255, 0.15); border: 1px solid rgba(255, 255, 255, 0.3);
            color: var(--text-sub); border-radius: 6px; padding: 4px 8px; font-size: 10px; cursor: pointer; font-weight: 600;
        }

        .btn-toggle-win.is-winner { background: rgba(234, 179, 8, 0.4); color: #fde047; border-color: #eab308; }

        .btn-delete-member {
            background: rgba(239, 68, 68, 0.3); border: 1px solid rgba(239, 68, 68, 0.6);
            color: #f87171; width: 28px; height: 28px; border-radius: 6px;
            display: flex; align-items: center; justify-content: center;
            cursor: pointer; font-size: 12px;
        }

        .winner-list-item {
            display: flex; justify-content: space-between; align-items: center; padding: 8px 10px;
            background: rgba(234, 179, 8, 0.25); border: 1px solid rgba(234, 179, 8, 0.6);
            border-radius: 8px; margin-top: 6px; font-size: 12px; font-weight: 600;
        }

        .btn-remove-winner {
            background: rgba(239, 68, 68, 0.4); border: 1px solid rgba(239, 68, 68, 0.6);
            color: #f87171; width: 24px; height: 24px; border-radius: 50%;
            display: flex; align-items: center; justify-content: center; cursor: pointer;
            font-size: 11px;
        }

        .modal-overlay {
            position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
            background: rgba(0, 0, 0, 0.8); backdrop-filter: blur(4px);
            z-index: 10000; display: none; justify-content: center; align-items: center;
            padding: 20px;
        }

        .modal-overlay.active { display: flex; }

        .modal-card {
            background: rgba(15, 23, 42, 0.95); border: 1px solid var(--border-color);
            border-radius: 16px; padding: 20px; width: 100%; max-width: 320px;
            text-align: center; box-shadow: 0 10px 30px rgba(0,0,0,0.8);
        }

        .modal-icon {
            width: 50px; height: 50px; border-radius: 50%;
            background: rgba(139, 92, 246, 0.2); border: 1px solid rgba(139, 92, 246, 0.5);
            color: var(--accent-primary); display: flex; align-items: center; justify-content: center;
            font-size: 22px; margin: 0 auto 12px auto;
        }

        .modal-icon.danger {
            background: rgba(239, 68, 68, 0.2); border-color: rgba(239, 68, 68, 0.5);
            color: #ef4444;
        }

        .modal-title { font-size: 16px; font-weight: 700; margin-bottom: 6px; }
        .modal-text { font-size: 13px; color: var(--text-sub); margin-bottom: 14px; line-height: 1.4; }

        .modal-actions { display: flex; gap: 10px; justify-content: center; }

        .btn-modal-ok {
            flex: 1; padding: 10px; border-radius: 8px;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            border: none; color: white; font-weight: 700; font-size: 13px; cursor: pointer;
        }

        .btn-modal-cancel {
            flex: 1; padding: 10px; border-radius: 8px;
            background: rgba(255, 255, 255, 0.15); border: 1px solid var(--border-color);
            color: var(--text-main); font-weight: 600; font-size: 12px; cursor: pointer;
        }

        .btn-modal-delete {
            flex: 1; padding: 10px; border-radius: 8px;
            background: #ef4444; border: none;
            color: white; font-weight: 700; font-size: 12px; cursor: pointer;
        }

        .footer-credits {
            text-align: center; padding: 15px 0; font-size: 12px; font-weight: 700;
            color: var(--accent-secondary); letter-spacing: 0.5px;
            text-shadow: 0 2px 6px rgba(0,0,0,0.9);
        }
    </style>
</head>
<body class="theme-dark">

    <div id="splash-screen">
        <div class="splash-icon-box">
            <i class="fa-solid fa-wallet"></i>
        </div>
        <div class="splash-title">KametiPay Pro</div>
        <div style="color: #cbd5e1; font-size: 11px; margin-top: 4px;" data-key="sub_title">Smart Financial & Kameti Manager</div>
    </div>

    <div class="modal-overlay" id="customAlertModal">
        <div class="modal-card">
            <div class="modal-icon" id="alertIcon"><i class="fa-solid fa-circle-check"></i></div>
            <div class="modal-title" id="alertTitle">Notification</div>
            <div class="modal-text" id="alertMessage">Message...</div>
            <div class="modal-actions">
                <button class="btn-modal-ok" onclick="closeCustomAlert()">OK</button>
            </div>
        </div>
    </div>

    <div class="modal-overlay" id="googleLoginModal">
        <div class="modal-card">
            <div class="modal-icon"><i class="fa-brands fa-google"></i></div>
            <div class="modal-title" data-key="g_login_title">Google Sign-In</div>
            <div class="modal-text" data-key="g_login_text">Enter your Name and Email:</div>
            <div class="form-group" style="text-align: left; margin-bottom: 10px;">
                <input type="text" id="gInputName" class="form-control" placeholder="Name..." data-key-ph="ph_name">
            </div>
            <div class="form-group" style="text-align: left; margin-bottom: 16px;">
                <input type="email" id="gInputEmail" class="form-control" placeholder="Email..." data-key-ph="ph_email">
            </div>
            <div class="modal-actions">
                <button class="btn-modal-cancel" onclick="closeGoogleLoginModal()" data-key="cancel">Cancel</button>
                <button class="btn-modal-ok" onclick="submitGoogleLoginModal()">OK</button>
            </div>
        </div>
    </div>

    <div class="modal-overlay" id="deleteModal">
        <div class="modal-card"
