thml
<!DOCTYPE html>  
<html lang="km">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>ហាងពេជ្រ Free Fire</title>  
    <style>  
        body {  
            background-color: #0f0f0f;  
            color: #ffffff;  
            font-family: sans-serif;  
            display: flex;  
            justify-content: center;  
            align-items: center;  
            height: 100vh;  
            margin: 0;  
        }  
        .card {  
            background: #1a1a1a;  
            padding: 25px;  
            border-radius: 12px;  
            width: 90%;  
            max-width: 380px;  
            box-shadow: 0 4px 15px rgba(255, 152, 0, 0.4);  
            text-align: center;  
            border: 1px solid #333;  
        }  
        h2 { color: #ff9800; margin-bottom: 5px; }  
        p { color: #aaa; font-size: 13px; margin-bottom: 20px; }  
        input {  
            width: 100%;  
            padding: 12px;  
            margin-bottom: 15px;  
            background: #2b2b2b;  
            border: 1px solid #444;  
            color: #fff;  
            border-radius: 6px;  
            box-sizing: border-box;  
            font-size: 15px;  
        }  
        input:focus { border-color: #ff9800; outline: none; }  
        .btn {  
            width: 100%;  
            background: linear-gradient(45deg, #ff9800, #ff5722);  
            color: #fff;  
            padding: 12px;  
            border: none;  
            border-radius: 6px;  
            font-weight: bold;  
            font-size: 16px;  
            cursor: pointer;  
        }  
        .btn:active { opacity: 0.8; }  
    </style>  
</head>  
<body>  
  
    <div class="card">  
        <h2>🔥 Free Fire Store 🔥</h2>  
        <p>ប្រព័ន្ធបំពេញព័ត៌មានកម្សាន្ត</p>  
        <input type="text" id="playerId" placeholder="បញ្ចូលលេខ ID របស់អ្នក">  
        <button class="btn" onclick="checkData()">បញ្ជាក់ទិន្នន័យ</button>  
    </div>  
  
    <script>  
        function checkData() {  
            let id = document.getElementById('playerId').value;  
            if(id.trim() !== "") {  
                alert("បានទទួលលេខ ID: " + id + " រួចរាល់!");  
            } else {  
                alert("សូមបញ្ចូលលេខ ID ជាមុនសិន!");  
            }  
        }  
    </script>  
  
</body>  
</html>  
