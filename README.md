
        <style>
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                font-family: sans-serif;
            }

            html,body {
                display: grid;
                height: 100%;
                width: 100%;
                place-items: center;
                background: linear-gradient(315deg,#ffffff 0%,#d7e1ec 74%);
            }

            .text1 .text2 {
                display: inline-block;
                height: 60px;
                width: 60px;
                float: left;
                margin: 0 5px;
                overflow: hidden;
                background: #ffff;
                border-radius: 50px;
                cursor: pointer;
                box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.5);
                transition: all 0.3s ease-out;
            }

            .text1 .text2:hover {
                width: 200px;
            }

            .text1 .text2 .text3 {
                display: inline-block;
                height: 60px;
                width: 60px;
                text-align: center;
                border-radius: 50px;
                box-sizing: border-box;
                line-height: 60px;
                transition: all 0.3 ease-out;
            }

            .text1 .text2:nth-child(1):hover .text3{
                background: #f60002;
            }

            .text1 .text2:nth-child(2):hover .text3{
                background: #fb3c7c;
            }

                        .text1 .text2:nth-child(3):hover .text3{
                background: #1c9cea;
            }            

            .text1 .text2:nth-child(4):hover .text3{
                background: #058f2e;
            }


            .text1 .text2 .text3 a {
                color: #000;
                font-size: 25px;
                line-height: 60px;
                transition: all 0.3s ease-out;
            }

            .text1 .text2:hover .text3 a {
                color: white;
            }
            
            .text1 .text2 span {
                font-size: 23px;
                font-weight: 500;
                line-height: 60px;
                margin-left: 10px;
            }

            .text1 .text2:nth-child(1) span{
               color: #f60002;
            }

            .text1 .text2:nth-child(2) span{
                color: #fb3c7c;
            }

            .text1 .text2:nth-child(3) span{
                color: #1c9cea;
            }            

            .text1 .text2:nth-child(4) span{
                color: #058f2e;
            }

        </style>
        <script src="https://use.fontawesome.com/releases/v5.15.3/js/all.js" data-auto-replace-svg></script>
    </head>
    <body>
        <div class="text1">
                <div class="text2">
                    <div class="text3"> 
                        <a href="#"><i class="fab fa-youtube"></i></a>
                </div>
                <span>YouTube</span>
                </div>
                    
                    

                <div class="text2">
                    <div class="text3"> 
                        <a href="#"><i class="fab fa-instagram"></i></a>
                </div>
                <span>Instagram</span>
                </div>



                <div class="text2">
                    <div class="text3"> 
                        <a href="#"><i class="fab fa-twitter"></i></a>
                </div>
                <span>Twitter</span>
                </div>




                <div class="text2">
                    <div class="text3"> 
                        <a href="#"><i class="fab fa-whatsapp"></i></a>
                </div>
                <span>Whatsapp</span>
                </div>
            </div>
        </div>
    </body>
</html>
