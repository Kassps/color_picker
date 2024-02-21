<!DOCTYPE html>
<head>

<title>Color Picker</title>
<style>
    body {
        font-family: Lucida Console, monospace;
        background-color: #f0f0f0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
    }

    .color-picker {
        width: 200px;
        height: 200px;
        border-radius: 50%;
        background-color: #ffffff;
        box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1);
        display: flex;
        justify-content: center;
        align-items: center;
    }
.star-card {
    width: 200px;
    height: 200px;
    background-color: #ffffff;
    clip-path: polygon(50% 0%, 63% 38%, 100% 38%, 69% 61%, 82% 100%, 50% 75%, 18% 100%, 31% 61%, 0% 38%, 38% 38%);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

    .color-picker input[type="color"] {
        -webkit-appearance: none;
        border: none;
        width: 100%;
        height: 100%;
        border-radius: 50%;
        cursor: pointer;
    }

    h1 {
        text-align: center;
    }
</style>
</head>
<body>
    <div class="star-card">
        <input type="color">
    </div>
    <h1>Pick a color</h1>
</body>
</html>
