<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starry Night</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background-color: black;
            color: white; /* Set text color to white */
            font-family: 'Arial', sans-serif; /* Set font family */
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background-color: white;
            animation: twinkle 1s infinite, moveStar linear 10s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.4; }
            50% { opacity: 1; }
        }

        @keyframes moveStar {
            from { transform: translate(0, 0); }
            to { transform: translate(100vw, 100vh); }
        }
    </style>
</head>
<body>
    <h1>Free VMware Workstation Pro 17 full license keys</h1>
    <p>MC60H-DWHD5-H80U9-6V85M-8280D 
4A4RR-813DK-M81A9-4U35H-06KND
NZ4RR-FTK5H-H81C1-Q30QH-1V2LA
JU090-6039P-08409-8J0QH-2YR7F
4Y09U-AJK97-089Z0-A3054-83KLA
4C21U-2KK9Q-M8130-4V2QH-CF810 < Worked for me!</p>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const numberOfStars = 50;

            for (let i = 0; i < numberOfStars; i++) {
                createStar();
            }

            function createStar() {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.left = Math.random() * 100 + 'vw';
                star.style.top = Math.random() * 100 + 'vh';
                document.body.appendChild(star);
            }
        });
    </script>
</body>
</html>
