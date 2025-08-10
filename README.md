<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>रक्षाबंधन स्पेशल</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(to right, #f9d423, #ff4e50);
    color: #333;
    margin: 0; padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .container {
    background: white;
    padding: 2rem 3rem;
    border-radius: 15px;
    box-shadow: 0 8px 15px rgba(0,0,0,0.2);
    text-align: center;
    max-width: 400px;
  }
  h1 {
    color: #d62828;
    margin-bottom: 0.5rem;
  }
  p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
  }
  .rakhi {
    width: 150px;
    margin-bottom: 1rem;
  }
  button {
    background: #d62828;
    color: white;
    border: none;
    padding: 0.8rem 1.5rem;
    font-size: 1rem;
    border-radius: 25px;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  button:hover {
    background: #f94144;
  }
</style>
</head>
<body>

<div class="container">
  <h1>रक्षाबंधन की शुभकामनाएं!</h1>
  <img src="murgi 2.jpg" alt="राखी" class="rakhi" />
  <p>भाई-बहन के प्यारे रिश्ते को समर्पित यह त्योहार।</p>
  <button onclick="showMessage()">मेसेज दिखाओ</button>
  <p id="message" style="color:#d62828; font-weight:bold; margin-top: 1rem;"></p>
</div>

<script>
  function showMessage() {
    document.getElementById('message').innerText = "रक्षा बंधन का त्यौहार हमेशा खुशियाँ और प्यार लाए।";
  }
</script>

</body>
</html>
