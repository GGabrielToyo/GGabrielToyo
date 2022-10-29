<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="#style">
</head>
<body>
    <div>
        <center>
            <h1>👋 Hi, I’m Gabriel Alves Toyo Pontes </h1>
        </center>
    </div>
    <div class="row">
        <div class="card green">
            <h2>📕UERJ:<br> computer student</h2>
            <p>Course: computer science</p>
            <p>Period: 4/8</p>
            <button class="image">📕</button>
        </div>
        <div class="card blue">
            <h2>📫E-mail: ggabrieltoyo@gmail.com</h2>
            <p>How to reach me</p>
            <button class="image1">✉</button>
        </div>
        <div class="card red">
            <h2>👨‍💻 Intern at the court of accounts of Rio De Janeiro </h2>
            <p>TCE-RJ</p>
            <button class="image1">💻</button>
        </div>
    </div>
</body>
</html>
<style>
    body {
        font-family: "Poppins", sans-serif;
        background-color: #fafafa;
    }
    .row {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .card {
        border-radius: 5px;
        box-shadow: 7px 7px 13px 0px rgba(50, 50, 50, 0.22);
        padding: 30px;
        margin: 20px;
        width: 400px;
        transition: all 0.3s ease-out;
        height: 180px;
    }
    .card:hover {
        transform: translateY(-15px);
        cursor: pointer;
    }
    .card p {
        color: #a3a5ae;
        font-size: 16px;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    .image {
        float: right;
        max-width: 64px;
        max-height: 64px;
    }
    .image1 {
        float: right;
        max-width: 64px;
        max-height: 64px;
        margin-top: 34px;
    }
    .blue {
        border-left: 3px solid #4895ff;
    }
    .green {
        border-left: 3px solid #3bb54a;
    }
    .red {
        border-left: 3px solid #b3404a;
    }
    h1 {
        font-family: 'Courier New', Courier, monospace;
    }
</style>
