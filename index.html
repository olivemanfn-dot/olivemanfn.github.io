<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Strawberry Elephant Login Demo</title>
<style>
  body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    background: linear-gradient(135deg, #f8d0e6, #ffe6f0);
    margin: 0;
    padding: 20px;
    color: #333;
  }

  h1 {
    text-align: center;
    color: #a0522d;
    font-size: 2em;
    margin-bottom: 20px;
  }

  .container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    max-width: 1000px;
    margin: 0 auto;
  }

  .section {
    background: #ffffffcc;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
  }

  .section h2 {
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 1.5em;
    color: #d14b6f;
    border-bottom: 2px solid #d14b6f;
    padding-bottom: 8px;
  }

  label {
    display: block;
    margin-top: 12px;
    font-weight: 600;
  }

  input[type="text"],
  input[type="password"],
  input[type="email"] {
    width: 100%;
    padding: 10px 14px;
    margin-top: 6px;
    border-radius: 8px;
    border: 1px solid #ccc;
    font-size: 1em;
    transition: border-color 0.2s;
  }

  input[type="text"]:focus,
  input[type="password"]:focus,
  input[type="email"]:focus {
    border-color: #a0522d;
    outline: none;
  }

  button {
    margin-top: 20px;
    padding: 12px 25px;
    font-size: 1em;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: background 0.3s;
  }

  #saveBtn {
    background-color: #d14b6f;
    color: #fff;
  }

  #saveBtn:hover {
    background-color: #b13a55;
  }

  #clearBtn {
    background-color: #a0522d;
    margin-left: 10px;
  }

  #clearBtn:hover {
    background-color: #804020;
  }

  /* Admin panel styling */
  .admin-panel {
    background: #fff0f5cc;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
  }

  .admin-panel h2 {
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 1.5em;
    color: #a0522d;
    border-bottom: 2px solid #a0522d;
    padding-bottom: 8px;
  }

  #displayData {
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    max-height: 300px;
    overflow-y: auto;
    font-family: 'Courier New', monospace;
    font-size: 0.95em;
  }

  /* Responsive adjustments */
  @media(max-width: 768px){
    .container {
      padding: 10px;
    }
  }
</style>
</head>
<body>

<h1>Strawberry Elephant Login Demo</h1>

<div class="container">

  <!-- User Input Form -->
  <div class="section" id="input-section">
    <h2>User Input</h2>
    <label for="username">Username:</label>
    <input type="text" id="username" placeholder="Enter username" />

    <label for="password">Password:</label>
    <input type="password" id="password" placeholder="Enter password" />

    <label for="email">Email:</label>
    <input type="email" id="email" placeholder="Enter email" />

    <button id="saveBtn">Save Data</button>
    <button id="clearBtn">Clear Data</button>
  </div>

  <!-- Admin Panel -->
  <div class="section admin-panel" id="admin-section">
    <h2>Admin Panel - Stored Data</h2>
    <div id="displayData">No data saved yet.</div>
  </div>

</div>

<script>
  // Select DOM elements
  const usernameInput = document.getElementById('username');
  const passwordInput = document.getElementById('password');
  const emailInput = document.getElementById('email');
  const saveBtn = document.getElementById('saveBtn');
  const clearBtn = document.getElementById('clearBtn');
  const displayDiv = document.getElementById('displayData');

  // Load data from localStorage on page load
  function loadData() {
    const data = JSON.parse(localStorage.getItem('demoData'));
    if (data) {
      usernameInput.value = data.username || '';
      passwordInput.value = data.password || '';
      emailInput.value = data.email || '';
      updateDisplay(data);
    } else {
      displayDiv.innerHTML = 'No data saved yet.';
    }
  }

  // Save data to localStorage and update display
  function saveData() {
    const data = {
      username: usernameInput.value,
      password: passwordInput.value,
      email: emailInput.value
    };
    localStorage.setItem('demoData', JSON.stringify(data));
    updateDisplay(data);
  }

  // Clear stored data
  function clearData() {
    localStorage.removeItem('demoData');
    usernameInput.value = '';
    passwordInput.value = '';
    emailInput.value = '';
    displayDiv.innerHTML = 'No data saved yet.';
  }

  // Update admin display in real-time
  function updateDisplay(data) {
    if (data && Object.keys(data).length > 0) {
      displayDiv.innerHTML = `<pre>${JSON.stringify(data, null, 2)}</pre>`;
    } else {
      displayDiv.innerHTML = 'No data saved yet.';
    }
  }

  // Event listeners for immediate update
  usernameInput.addEventListener('input', saveData);
  passwordInput.addEventListener('input', saveData);
  emailInput.addEventListener('input', saveData);
  saveBtn.addEventListener('click', saveData);
  clearBtn.addEventListener('click', clearData);

  // Load data when page loads
  window.onload = loadData;
</script>

</body>
</html>
