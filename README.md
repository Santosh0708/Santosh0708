- 👋 Hi, I’m @Santosh0708
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Santosh0708/Santosh0708 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        form{
            margin: 200px 200px ;
            border: 1px solid black;
            padding: 100px;
        }
    </style>
</head>
<body>
    <form>
        <label> Enter a number</label>
        <input type="text" id="first "> <br> <br>

        <label> Enter password</label>
        <input type="text" id="second">
         <br> <br>
        <button onclick="Login()">Login Here</button>
        <p id="display"></p>
    </form>

    <script>
        function Login(){
         var a = document.getElementById("first").value;
         var b = documnet.getElementById("second").value;

        Text= a+b;
        documnet.getElementById("display").innerHTML.Text;

        };

    </script>
</body>
</html>
