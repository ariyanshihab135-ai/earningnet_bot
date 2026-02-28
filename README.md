<!DOCTYPE html>
<html lang="en">
<head>
<script src="https://pl28816050.effectivegatecpm.com/b2/f3/60/b2f360cc2aa9446470e249201048a4df.js"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taka Income BD</title>
    
<script src='//libtl.com/sdk.js' data-zone='10665732' data-sdk='show_10665732'></script>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #121212; color: #ffffff; }
        .dark-bg { background-color: #121212; }
        .card-bg { background-color: #1e1e1e; }
        .border-accent { border-color: #10b981; }
        .text-accent { color: #10b981; }
        .btn, .btn-accent, .btn-outline-accent { transition: all 0.2s ease-in-out; transform: scale(1); }
        .btn:active, .btn-accent:active, .btn-outline-accent:active { transform: scale(0.95); }
        .btn-accent { background-color: #10b981; color: #121212; font-weight: bold; }
        .btn-accent:hover { background-color: #059669; }
        .btn-outline-accent { border: 1px solid #10b981; color: #10b981; }
        .btn-outline-accent:hover { background-color: #10b981; color: #121212; }
        .input-field { background-color: #2c2c2c; border: 1px solid #444; }
        .main-page { display: none; }
        .main-page.active { display: flex; animation: fadeIn 0.5s ease-in-out; }
        .sub-page { display: none; }
        .sub-page.active { display: block; animation: fadeIn 0.3s ease-in-out; }
        .bottom-nav a.active { color: #10b981; }
        .notification-dot {
            position: absolute; top: -2px; right: -2px; width: 10px; height: 10px;
            background-color: #ef4444; border-radius: 50%; border: 2px solid #121212; display: none;
        }
        .modal-scroll::-webkit-scrollbar { width: 4px; }
        .modal-scroll::-webkit-scrollbar-thumb { background-color: #ccc; border-radius: 4px; }
        
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes popUp { from { transform: scale(0.9); opacity: 0; } to { transform: scale(1); opacity: 1; } }
        .popup-anim { animation: popUp 0.3s ease-out; }
    </style>
</head>
<body class="max-w-md mx-auto">

    <div id="loader" class="hidden fixed inset-0 dark-bg bg-opacity-75 flex items-center justify-center z-50">
        <div class="animate-spin rounded-full h-16 w-16 border-t-2 border-b-2 border-accent"></div>
    </div>

    <div id="welcome-modal" class="fixed inset-0 bg-black bg-opacity-80 flex items-center justify-center z-[60] hidden p-4">
        <div class="bg-white text-gray-900 rounded-2xl w-full max-w-sm p-6 relative popup-anim shadow-2xl">
            <button onclick="closeWelcomeModal()" class="absolute top-4 right-4 text-gray-500 hover:text-gray-800">
                <i data-lucide="x" class="w-6 h-6"></i>
            </button>
            <div class="text-center mb-4">
                <h2 class="text-2xl font-bold text-black flex items-center justify-center gap-2">স্বাগতম! 🔥</h2>
            </div>
            <div class="space-y-4 text-sm font-medium leading-relaxed text-center">
                <p>আসসালামু আলাইকুম, সততার সাথে পেমেন্ট করছি। নিয়ম মেনে কাজ করলে ১০০% পেমেন্ট পাবেন ইনশাআল্লাহ 🔥</p>
                <div class="space-y-2 text-left bg-gray-50 p-3 rounded-lg border border-gray-200">
                    <p class="flex items-center gap-2"><span class="text-yellow-500">⚡</span> ওয়েবসাইট ভিজিট: ১০০ কয়েন</p>
                    <p class="flex items-center gap-2"><span class="text-green-600">💸</span> প্রতি রেফারে: ২০০ কয়েন</p>
                    <p class="flex items-center gap-2"><span class="text-yellow-600">💰</span> প্রতি বিজ্ঞাপনে: ৫০ কয়েন</p>
                </div>
                <div class="border-t border-gray-200 pt-3">
                    <p class="flex items-center justify-center gap-1 font-bold text-gray-800"><span class="text-red-600 text-lg">📌</span> ১০০% পেমেন্ট গ্যারান্টি</p>
                </div>
            </div>
            <button onclick="closeWelcomeModal()" class="w-full mt-6 bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 rounded-xl transition-colors text-lg">বুঝেছি</button>
        </div>
    </div>

    <div id="auth-section" class="min-h-screen p-6 flex-col justify-center main-page">
        <h1 class="text-4xl font-bold text-center mb-2 text-accent">Taka Income BD</h1>
        <p class="text-center text-gray-400 mb-8">Login or Signup to continue</p>
        <div id="auth-container">
            <div id="login-view">
                <input id="login-email" type="email" placeholder="Email" class="w-full p-3 rounded-lg input-field mb-4">
                <input id="login-password" type="password" placeholder="Password" class="w-full p-3 rounded-lg input-field mb-4">
                <button id="login-btn" class="w-full p-3 rounded-lg btn-accent mb-4">Login</button>
                <p class="text-center text-gray-400">Don't have an account? <a href="#" id="show-signup" class="font-semibold text-accent">Sign Up</a></p>
            </div>
            <div id="signup-view" class="hidden">
                 <input id="signup-name" type="text" placeholder="Full Name" class="w-full p-3 rounded-lg input-field mb-4">
                <input id="signup-email" type="email" placeholder="Email" class="w-full p-3 rounded-lg input-field mb-4">
                <input id="signup-password" type="password" placeholder="Password" class="w-full p-3 rounded-lg input-field mb-4">
                <button id="signup-btn" class="w-full p-3 rounded-lg btn-accent mb-4">Sign Up</button>
                <p class="text-center text-gray-400">Already have an account? <a href="#" id="show-login" class="font-semibold text-accent">Login</a></p>
            </div>
        </div>
    </div>

    <div id="app-container" class="min-h-screen flex-col main-page">
        <header class="flex items-center justify-between p-4 sticky top-0 bg-opacity-80 backdrop-blur-md z-10 dark-bg">
            <h1 class="text-xl font-bold text-accent">Taka Income BD</h1>
            <div class="flex items-center space-x-4">
                <div id="notification-bell" class="relative cursor-pointer">
                    <i data-lucide="bell" class="w-6 h-6"></i>
                    <div id="notification-dot" class="notification-dot"></div>
                </div>
                <i data-lucide="user" class="w-6 h-6 cursor-pointer" onclick="navigateTo('profile-page')"></i>
            </div>
        </header>

        <main class="flex-grow">
            <div id="home-page" class="p-4 space-y-6 sub-page">
                <div class="card-bg p-4 rounded-lg flex items-center justify-between">
                    <div>
                        <p class="text-gray-400 text-sm">Your Balance</p>
                        <p class="text-3xl font-bold"><span id="coin-balance">0</span> Coins</p>
                    </div>
                    <button id="home-withdraw-btn" class="bg-white text-black font-semibold px-6 py-2 rounded-lg">Withdraw</button>
                </div>
                
                <section>
                    <div class="flex justify-between items-center">
                        <div>
                            <h2 class="text-lg font-semibold">Daily Tasks</h2>
                            <p class="text-sm text-gray-400 mb-4">Complete tasks to earn money.</p>
                        </div>
                        <p class="text-sm text-gray-400">Done: <span id="ads-left-count">0</span>/<span id="max-tasks">...</span></p>
                    </div>
                    
                    <div class="space-y-3">
                        <h3 class="text-xs font-bold text-gray-500 uppercase mt-2">Website Visits (30s Timer)</h3>
                        
                        <div class="card-bg p-3 rounded-lg flex items-center justify-between">
                            <div class="flex items-center space-x-3"><span class="text-3xl">🌐</span><div><h3 class="font-semibold">Website Visit 1</h3><p class="text-xs text-gray-400">Reward: 50 Coins</p></div></div>
                            <button id="task-btn-1" class="bg-green-600 text-white font-bold px-6 py-2 rounded-lg text-sm btn" onclick="startWebTask(1)">Visit</button>
                        </div>

                        <div class="card-bg p-3 rounded-lg flex items-center justify-between">
                            <div class="flex items-center space-x-3"><span class="text-3xl">🌐</span><div><h3 class="font-semibold">Website Visit 2</h3><p class="text-xs text-gray-400">Reward: 50 Coins</p></div></div>
                            <button id="task-btn-2" class="bg-green-600 text-white font-bold px-6 py-2 rounded-lg text-sm btn" onclick="startWebTask(2)">Visit</button>
                        </div>

                        <div class="card-bg p-3 rounded-lg flex items-center justify-between">
                            <div class="flex items-center space-x-3"><span class="text-3xl">🌐</span><div><h3 class="font-semibold">Website Visit 3</h3><p class="text-xs text-gray-400">Reward: 50 Coins</p></div></div>
                            <button id="task-btn-3" class="bg-green-600 text-white font-bold px-6 py-2 rounded-lg text-sm btn" onclick="startWebTask(3)">Visit</button>
                        </div>

                        <h3 class="text-xs font-bold text-gray-500 uppercase mt-4">Ad Rewards</h3>
                        <div class="bg-orange-500 p-3 rounded-lg flex items-center justify-between text-black">
                            <div class="flex items-center space-x-3"><span class="text-3xl">🤩</span><div><h3 class="font-bold">Watch Short Ad</h3></div></div>
                            <button class="bg-white text-orange-500 font-bold px-6 py-2 rounded-lg text-sm btn" onclick="claimReward('interstitial')">Claim</button>
                        </div>
                        <div class="card-bg p-3 rounded-lg flex items-center justify-between">
                            <div class="flex items-center space-x-3"><span class="text-3xl">😎</span><div><h3 class="font-semibold">Click for Reward</h3></div></div>
                            <button class="bg-white text-black font-bold px-6 py-2 rounded-lg text-sm btn" onclick="claimReward('popup')">Claim</button>
                        </div>
                    </div>
                </section>
            </div>

            <div id="wallet-page" class="p-4 space-y-6 sub-page">
                <h2 class="text-xl font-bold text-center">My Wallet</h2>
                <div class="card-bg p-4 rounded-lg">
                    <h3 class="font-semibold mb-3">Withdraw Earnings</h3>
                    <p class="text-sm text-gray-400 mb-1">Current Balance: <span class="font-bold text-accent"><span id="wallet-coin-balance">0</span> Coins</span></p>
                    <p class="text-sm text-gray-400 mb-2">Minimum Withdrawal: <span id="min-withdrawal-info">...</span> Coins</p>
                    <p class="text-sm text-gray-400 mb-4 font-semibold" id="coin-value-info">...</p>
                    <input id="withdraw-amount" type="number" placeholder="Enter coin amount" class="w-full p-3 rounded-lg input-field mb-3">
                    <select id="withdraw-method" class="w-full p-3 rounded-lg input-field mb-3"></select>
                    <div id="payment-details-container"></div>
                    <button id="withdraw-btn" class="w-full p-3 rounded-lg btn-accent mt-3">Request Withdrawal</button>
                </div>
                <div>
                    <h3 class="text-lg font-semibold mb-3">Withdrawal History</h3>
                    <div id="withdrawal-history-list" class="space-y-3"></div>
                </div>
            </div>

            <div id="refer-page" class="p-4 space-y-6 sub-page">
                 <h2 class="text-xl font-bold text-center">Refer & Earn</h2>
                 <div class="card-bg p-6 rounded-lg text-center">
                     <p class="text-gray-400 mb-2">Your Referral Code</p>
                     <div class="bg-gray-800 p-3 rounded-lg flex items-center justify-center mb-4">
                         <span id="referral-code" class="text-2xl font-bold tracking-widest">LOADING...</span>
                         <button id="copy-code-btn" class="ml-4"><i data-lucide="copy" class="w-6 h-6 text-gray-400"></i></button>
                     </div>
                 </div>
                 <button id="share-btn" class="w-full p-3 rounded-lg btn-accent">Share Your Code</button>
                 <div class="card-bg p-4 rounded-lg mt-6">
                    <h3 class="font-semibold mb-3 text-center">Have a Referral Code?</h3>
                    <input id="enter-referral-code" type="text" placeholder="Enter code here" class="w-full p-3 rounded-lg input-field mb-3">
                    <button id="apply-referral-btn" class="w-full p-3 rounded-lg btn-outline-accent">Apply Code</button>
                 </div>
            </div>

            <div id="profile-page" class="p-4 space-y-6 sub-page">
                <h2 class="text-xl font-bold text-center mb-4">Profile</h2>
                <div class="flex flex-col items-center">
                    <img src="https://placehold.co/100x100/1e1e1e/10b981?text=U" class="rounded-full mb-2 shadow-lg border-2 border-accent">
                    <h2 id="profile-name" class="text-xl font-bold">User Name</h2>
                    <p id="profile-email" class="text-gray-400 text-sm">user@email.com</p>
                </div>

                <div class="space-y-3 pt-2">
                    <p class="text-xs text-gray-500 uppercase font-bold ml-1">Community & Support</p>
                    
                    <a id="link-telegram-btn" href="#" target="_blank" class="card-bg p-4 rounded-xl flex items-center justify-between hover:bg-[#252525] transition-colors border border-transparent hover:border-gray-700">
                        <div class="flex items-center gap-3">
                            <div class="p-2 bg-blue-500/10 rounded-lg text-blue-400"><i data-lucide="send" class="w-5 h-5"></i></div>
                            <span class="font-medium">Join Our Official Telegram</span>
                        </div>
                        <i data-lucide="chevron-right" class="w-5 h-5 text-gray-600"></i>
                    </a>

                    <a id="link-facebook-btn" href="#" target="_blank" class="card-bg p-4 rounded-xl flex items-center justify-between hover:bg-[#252525] transition-colors border border-transparent hover:border-gray-700">
                        <div class="flex items-center gap-3">
                            <div class="p-2 bg-blue-700/10 rounded-lg text-blue-600"><i data-lucide="facebook" class="w-5 h-5"></i></div>
                            <span class="font-medium">Join Our Official Facebook</span>
                        </div>
                        <i data-lucide="chevron-right" class="w-5 h-5 text-gray-600"></i>
                    </a>

                    <a id="link-admin-btn" href="#" target="_blank" class="card-bg p-4 rounded-xl flex items-center justify-between hover:bg-[#252525] transition-colors border border-transparent hover:border-gray-700">
                        <div class="flex items-center gap-3">
                            <div class="p-2 bg-green-500/10 rounded-lg text-green-400"><i data-lucide="message-circle" class="w-5 h-5"></i></div>
                            <span class="font-medium">Contact Admin</span>
                        </div>
                        <i data-lucide="chevron-right" class="w-5 h-5 text-gray-600"></i>
                    </a>
                </div>

                <button id="logout-btn" class="w-full mt-4 p-3 rounded-lg bg-red-600/20 text-red-500 border border-red-600/50 font-bold hover:bg-red-600 hover:text-white transition-all">Logout</button>
            </div>
            
            <div id="notifications-page" class="p-4 space-y-4 sub-page">
                <h2 class="text-xl font-bold text-center">Notifications</h2>
                <div id="notifications-list" class="space-y-3"></div>
            </div>
        </main>

        <nav class="bottom-nav sticky bottom-0 grid grid-cols-4 items-center text-center py-2 card-bg">
            <a href="#" class="nav-link" data-page="home-page"><i data-lucide="home" class="mx-auto w-6 h-6"></i><span class="text-xs">Home</span></a>
            <a href="#" class="nav-link" data-page="wallet-page"><i data-lucide="wallet" class="mx-auto w-6 h-6"></i><span class="text-xs">Wallet</span></a>
            <a href="#" class="nav-link" data-page="refer-page"><i data-lucide="users" class="mx-auto w-6 h-6"></i><span class="text-xs">Refer & Earn</span></a>
            <a href="#" class="nav-link" data-page="profile-page"><i data-lucide="user" class="mx-auto w-6 h-6"></i><span class="text-xs">Profile</span></a>
        </nav>
    </div>
    
    <div id="custom-alert" class="hidden fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 p-4">
        <div class="bg-gray-800 rounded-lg p-6 w-full max-w-sm text-center">
            <p id="alert-message" class="mb-4"></p>
            <button id="alert-ok-btn" class="btn-accent px-6 py-2 rounded-lg">OK</button>
        </div>
    </div>

    <script type="module">
       const firebaseConfig = {
  apiKey: "AIzaSyAcgt7GalsZkXd7cFgW_4XnRGA-wmG-xMM",
  authDomain: "earning-app-39ec4.firebaseapp.com",
  databaseURL: "https://earning-app-39ec4-default-rtdb.firebaseio.com",
  projectId: "earning-app-39ec4",
  storageBucket: "earning-app-39ec4.firebasestorage.app",
  messagingSenderId: "409925626146",
  appId: "1:409925626146:web:69d4eb3e6b57e98eea5d7b",
  measurementId: "G-HDQNQP65Z3"
};
        
        import { initializeApp } from "https://www.gstatic.com/firebasejs/9.23.0/firebase-app.js";
        import { getAuth, onAuthStateChanged, createUserWithEmailAndPassword, signInWithEmailAndPassword, signOut } from "https://www.gstatic.com/firebasejs/9.23.0/firebase-auth.js";
        import { getFirestore, doc, setDoc, getDoc, updateDoc, collection, addDoc, serverTimestamp, query, where, getDocs, orderBy, limit } from "https://www.gstatic.com/firebasejs/9.23.0/firebase-firestore.js";

        const app = initializeApp(firebaseConfig);
        const auth = getAuth(app);
        const db = getFirestore(app);

        let currentUser = null;
        let userData = null;
        let appConfig = {};

        const loader = document.getElementById('loader');
        const coinBalanceEl = document.getElementById('coin-balance');
        const walletCoinBalanceEl = document.getElementById('wallet-coin-balance');
        const profileNameEl = document.getElementById('profile-name');
        const profileEmailEl = document.getElementById('profile-email');
        const referralCodeEl = document.getElementById('referral-code');
        const minWithdrawalInfoEl = document.getElementById('min-withdrawal-info');
        const coinValueInfoEl = document.getElementById('coin-value-info');
        const withdrawMethodSelect = document.getElementById('withdraw-method');
        const notificationDot = document.getElementById('notification-dot');
        const adsLeftCountEl = document.getElementById('ads-left-count');
        const paymentDetailsContainer = document.getElementById('payment-details-container');

        window.onload = () => {
            lucide.createIcons();
            setupEventListeners();
            showMainPage('auth-section');
            loader.style.display = 'none';
            onAuthStateChanged(auth, handleAuthStateChange);
            openWelcomeModal();
        };

        function openWelcomeModal() { document.getElementById('welcome-modal').classList.rem
