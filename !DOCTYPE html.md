<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <title>Valentine Quiz 💌</title>  
  <style>  
    body {  
      font-family: 'Comic Sans MS', sans-serif;  
      background: linear-gradient(to right, #ff9a9e, #fad0c4);  
      display: flex;  
      justify-content: center;  
      align-items: center;  
      height: 100vh;  
      text-align: center;  
      color: #fff;  
      flex-direction: column;  
    }  
    h1 {  
      font-size: 2.5em;  
      margin-bottom: 20px;  
      text-shadow: 2px 2px #ff6f91;  
    }  
    button {  
      background-color: #ff6f91;  
      border: none;  
      padding: 15px 30px;  
      margin: 10px;  
      font-size: 1.2em;  
      border-radius: 10px;  
      cursor: pointer;  
      transition: all 0.3s ease;  
    }  
    button:hover {  
      transform: scale(1.1);  
      background-color: #ff3c69;  
    }  
  </style>  
</head>  
<body>  
  <h1>Will you be my Valentine? ❤️</h1>  
  <div>  
    <button onclick="yesClicked()">Yes 💖</button>  
    <button onclick="noClicked()">No 😢</button>  
  </div>  
  
  <script>  
    function yesClicked() {  
      alert("Yay! 💕 You made me the happiest person ever!");  
      document.body.innerHTML = "<h1>Yay! 💕 Can't wait to celebrate Valentine’s Day with you!</h1>";  
    }  
  
    function noClicked() {  
      alert("Oops! Are you sure? 😇 Think again!");  
      // redirect to the same page after short delay  
      setTimeout(() => {  
        location.reload();  
      }, 500);  
    }  
  </script>  
</body>  
</html>  
