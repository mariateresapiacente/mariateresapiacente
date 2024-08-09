<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mariateresa's Introduction</title>
    <style>
        body {
            background-color: #282c34;
            color: #08CE90;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
            flex-direction: column;
        }

        .typing {
            font-size: 2rem;
            white-space: nowrap;
            overflow: hidden;
            border-right: .15em solid #08CE90;
            width: 0;
            animation: typing 3.5s steps(30, end) forwards, blink-caret .75s step-end infinite;
        }

        .typing2 {
            font-size: 2rem;
            white-space: nowrap;
            overflow: hidden;
            border-right: .15em solid #08CE90;
            width: 0;
            margin-top: 10px;
            animation: typing2 3.5s steps(30, end) forwards, blink-caret .75s step-end infinite;
            animation-delay: 3.7s; /* Avvio immediato dopo la prima animazione */
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes typing2 {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #08CE90; }
        }
    </style>
</head>
<body>
    <div class="typing">Hello, I'm Mariateresa.</div>
    <div class="typing2">I'm a Developer student.</div>
</body>
</html>
