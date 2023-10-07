
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="intro.css">
    <title>Portfolio</title>
</head>

<body>
    <header class="container">
        <div class="page-header">
            <input type="checkbox" id="click">

            <label for="click" class="mainicon">
                <div class="menu">
                    <i class='bx bx-menu'></i>
                </div>
            </label>
            
            <label class="mode">
                <input type="checkbox" id="darkModeToggle">
                <i class='bx bxs-moon'></i>
            </label>
        </div>
    </header>


    <section class="container">
        <div class="main">
            <div class="detail">
                <h3>Hi, It's Me</h3>
                <h1>I'm <span style="color:#1bb4b4;">Salah</span></h1>
                <p>Driven by a commitment to excellence and a passion for solving real-world problems through code.
                </p>
                <div class="social">
                    <a href="https://youtube.com/@TheKaleidoscope3301?feature=shared"><i class='bx bxl-youtube'></i></a>
                    <a href="https://instagram.com/salah_eddine_berret?igshid=YTQwZjQ0NmI0OA=="><i class='bx bxl-instagram'></i></a>
                    <a href="https://twitter.com/SALAHEDDIN38731"><i class='bx bxl-twitter'></i></a>
                    <a href="https://wa.me/+212705163569"><i class='bx bxl-whatsapp'></i></a>
                </div>
            </div>
            <div class="img-sec">
                <div class="images">
                    <img src="im1.jpg" alt="" class="img-w">
                </div>
            </div>
        </div>
    </section>
    <script>
        const darkModeToggle = document.getElementById('darkModeToggle');
        const body = document.body;
        const isDarkMode = localStorage.getItem('darkMode') === 'enabled';
        if (isDarkMode) {
            body.classList.add('dark-mode');
            darkModeToggle.checked = true;
        }
        darkModeToggle.addEventListener('change', () => {
            if (darkModeToggle.checked) {
                body.classList.add('dark-mode');
                localStorage.setItem('darkMode', 'enabled');
            } else {
                body.classList.remove('dark-mode');
                localStorage.setItem('darkMode', 'disabled');
            }
        });
    </script>
    
</body>

</html>
