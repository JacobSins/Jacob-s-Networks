<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jacob's Networks</title>
    <style>
        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #1a1a2e;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        .login-container, .settings-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #161625;
        }

        .login-box, .settings-box {
            background-color: #252546;
            padding: 30px;
            border-radius: 8px;
            width: 300px;
        }

        .login-box h2, .settings-box h2 {
            text-align: center;
            margin-bottom: 10px;
        }

        .login-box h3, .settings-box h3 {
            text-align: center;
            color: #f0ad4e;
            margin-bottom: 20px;
        }

        .login-box input, .settings-box input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #3a3a5e;
            border-radius: 5px;
            background-color: #161625;
            color: #fff;
        }

        .login-box button, .settings-box button {
            width: 100%;
            padding: 10px;
            background-color: #3a3a5e;
            border: none;
            border-radius: 5px;
            color: #fff;
            cursor: pointer;
        }

        .login-box button:hover, .settings-box button:hover {
            background-color: #4a4a6e;
        }

        .sidebar {
            width: 250px;
            background-color: #161625;
            height: 100vh;
            position: fixed;
            padding: 20px;
            z-index: 10;
        }

        .sidebar h2 {
            margin-bottom: 30px;
        }

        .sidebar a {
            display: block;
            padding: 10px;
            color: #fff;
            text-decoration: none;
            margin-bottom: 15px;
            border-radius: 5px;
            background-color: #252546;
        }

        .sidebar a:hover {
            background-color: #3a3a5e;
        }

        .main-content {
            margin-left: 270px;
            padding: 20px;
            position: relative;
        }

        .header {
            font-size: 1.8rem;
            margin-bottom: 20px;
        }

        .card-container {
            display: flex;
            gap: 20px;
        }

        .card {
            flex: 1;
            background-color: #252546;
            padding: 20px;
            border-radius: 8px;
        }

        .card h3 {
            margin: 0 0 10px 0;
            font-size: 1.2rem;
        }

        .recent-transactions {
            margin-top: 20px;
            background-color: #252546;
            padding: 20px;
            border-radius: 8px;
            max-height: 300px;
            overflow-y: auto;
        }

        .recent-transactions h3 {
            margin-bottom: 10px;
        }

        .transaction {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .transaction span {
            font-size: 0.9rem;
        }

        .actions {
            margin-top: 20px;
            background-color: #252546;
            padding: 20px;
            border-radius: 8px;
        }

        .actions h3 {
            margin-bottom: 10px;
        }

        .actions button {
            background-color: #3a3a5e;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        .actions button:hover {
            background-color: #4a4a6e;
        }

        /* Custom scrollbar styling */
        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-track {
            background-color: #161625;
            border-radius: 10px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #3a3a5e;
            border-radius: 10px;
            border: 2px solid #161625;
        }

        ::-webkit-scrollbar-thumb:hover {
            background-color: #4a4a6e;
        }

        /* Password settings container (hidden by default) */
        .password-settings-container {
            background-color: #252546;
            padding: 20px;
            border-radius: 8px;
            position: absolute;
            top: 0;
            right: -100%;
            width: 100%;
            height: 100%;
            transition: right 0.3s ease-in-out;
            z-index: 5;
        }

        .password-settings-container h3 {
            margin-bottom: 20px;
            text-align: center;
        }

        .password-settings-container input {
            margin-bottom: 10px;
        }

        .password-settings-container button {
            width: 100%;
        }

        .password-settings-open {
            right: 0;
        }

        /* Hide sections by default */
        .dashboard-content, .password-settings-content {
            display: none;
        }

        /* Custom button styling for subject selection */
        .subject-button {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            background-color: #3a3a5e;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }

        .subject-button:hover {
            background-color: #4a4a6e;
        }
    </style>
</head>
<body>
    <!-- Login Page -->
    <div id="login-page" class="login-container">
        <div class="login-box">
            <h3>WELCOME TO JACOB'S NETWORKS</h3>
            <h2>Login</h2>
            <input type="text" id="username" placeholder="Username">
            <input type="password" id="password" placeholder="Password">
            <button onclick="login()">Login</button>
            <p id="login-error" style="color: red; text-align: center; display: none;">Invalid username or password</p>
        </div>
    </div>

    <!-- Dashboard Page -->
    <div id="dashboard-page" style="display: none;">
        <div class="sidebar">
            <h2>JACOB'S NETWORKS</h2>
            <a href="#" onclick="showBankOverview()">Bank Overview</a>
            <a href="#" onclick="showPasswordSettings()">School</a>
            <a href="#" onclick="transferFunds()">Transfer Funds</a>
            <a href="#" style="color: red;" onclick="logout()">Logout</a>
        </div>

        <div class="main-content">
            <!-- Bank Overview Section -->
            <div id="bank-overview" class="dashboard-content">
                <div class="header">Banking Dashboard</div>
                <div class="card-container">
                    <div class="card">
                        <h3>Account Balance</h3>
                        <p id="balance">$0.00</p>
                    </div>

                    <div class="card">
                        <h3>Recent Transactions</h3>
                        <p>Last Transaction: <span id="last-transaction">$0.00</span></p>
                    </div>

                    <div class="card">
                        <h3>Active Loans</h3>
                        <p id="active-loans">No active loans</p>
                    </div>
                </div>

                <div class="recent-transactions">
                    <h3>Recent Activity</h3>
                    <div id="transactions"></div>
                </div>

                <div class="actions">
                    <h3>Actions</h3>
                    <button onclick="deposit()">Deposit</button>
                    <button onclick="withdraw()">Withdraw</button>
                    <button onclick="transferFunds()">Transfer Funds</button>
                    <button onclick="clearRecentActivity()">Clear Recent Activity</button>
                </div>
            </div>

            <!-- Subject Selection Section -->
            <div id="password-settings" class="password-settings-content">
                <h3>Choose a Subject</h3>
                <button class="subject-button" onclick="selectSubject('Science')">Science</button>
                <button class="subject-button" onclick="selectSubject('English')">English</button>
                <button class="subject-button" onclick="selectSubject('Math')">Math</button>
                <button class="subject-button" onclick="selectSubject('Filipino')">Filipino</button>
                <button class="subject-button" onclick="selectSubject('AP')">AP</button>
                <button class="subject-button" onclick="selectSubject('Esp')">Esp</button>
                <button class="subject-button" onclick="selectSubject('TVE')">TVE</button>
                <button class="subject-button" onclick="selectSubject('Entrep')">Entrep</button>
                <button class="subject-button" onclick="selectSubject('MAPEH')">MAPEH</button>
                <p id="subject-message" style="color: green; text-align: center;"></p>
            </div>
        </div>
    </div>

    <script>
        // Dummy login credentials for demonstration
        const validUsername = 'Jacob';
        const validPassword = '0611';

        // Retrieve saved data from localStorage
        let balance = parseFloat(localStorage.getItem('balance')) || 0;
        let transactions = JSON.parse(localStorage.getItem('transactions')) || [];
        let currentUsername = validUsername;
        let savedPassword = localStorage.getItem('password') || null;

        // Update the dashboard
        function updateDashboard() {
            document.getElementById('balance').textContent = `$${balance.toFixed(2)}`;
            const lastTransaction = transactions[0];
            document.getElementById('last-transaction').textContent = lastTransaction ? `$${lastTransaction.amount.toFixed(2)}` : '$0.00';

            const transactionsContainer = document.getElementById('transactions');
            transactionsContainer.innerHTML = '';
            transactions.forEach((transaction) => {
                const div = document.createElement('div');
                div.className = 'transaction';
                div.innerHTML = `<span>${transaction.type}</span><span>$${transaction.amount.toFixed(2)}</span><span>${transaction.timestamp}</span>`;
                transactionsContainer.appendChild(div);
            });

            localStorage.setItem('balance', balance);
            localStorage.setItem('transactions', JSON.stringify(transactions));
        }

        // Toggle between Bank Overview and Password Settings
        function showBankOverview() {
            document.getElementById('bank-overview').style.display = 'block';
            document.getElementById('password-settings').style.display = 'none';
        }

        function showPasswordSettings() {
            document.getElementById('bank-overview').style.display = 'none';
            document.getElementById('password-settings').style.display = 'block';
        }

        // Subject Selection
        function selectSubject(subject) {
            document.getElementById('subject-message').textContent = `You selected ${subject}.`;
        }

        // Handle Login
        function login() {
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;

            if (username === validUsername && password === validPassword) {
                document.getElementById('login-page').style.display = 'none';
                document.getElementById('dashboard-page').style.display = 'block';
                updateDashboard();
            } else {
                document.getElementById('login-error').style.display = 'block';
            }
        }

        // Handle Logout
        function logout() {
            document.getElementById('login-page').style.display = 'block';
            document.getElementById('dashboard-page').style.display = 'none';
        }

        // Functions for handling banking operations
        function deposit() {
            const amount = parseFloat(prompt('Enter amount to deposit:'));
            if (amount > 0) {
                balance += amount;
                transactions.unshift({ type: 'Deposit', amount, timestamp: new Date().toLocaleString() });
                updateDashboard();
            }
        }

        function withdraw() {
            const amount = parseFloat(prompt('Enter amount to withdraw:'));
            if (amount > 0 && amount <= balance) {
                balance -= amount;
                transactions.unshift({ type: 'Withdraw', amount, timestamp: new Date().toLocaleString() });
                updateDashboard();
            } else {
                alert('Insufficient balance or invalid amount');
            }
        }

        function transferFunds() {
            const amount = parseFloat(prompt('Enter amount to transfer:'));
            if (amount > 0 && amount <= balance) {
                balance -= amount;
                transactions.unshift({ type: 'Transfer', amount, timestamp: new Date().toLocaleString() });
                updateDashboard();
            } else {
                alert('Insufficient balance or invalid amount');
            }
        }

        function clearRecentActivity() {
            transactions = [];
            updateDashboard();
        }
    </script>
</body>
</html>
