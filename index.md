<head>
    <style>
        body{
            background-color: rgb(220,220,220);
        }
        .box div img:hover{
            color: white;
            background-color: darkgray;
        }
        #ki1:hover{
            opacity: 0.3;
        }
        @media screen and (max-width: 450px){
            body{
                text-align: center;
            }
            .box{
                display: grid;
                grid-template-columns: 1fr;
                grid-gap: 5px;
            }
            .box div{
                border: 1px solid black;
                width: 150px;
                justify-self: center;
                align-self: center;              
            }
            .k2{
                height: 150px;
                width: 150px;
                font-size: 8px;
                margin: 2px;
                background-color: rgb(200,200,200);
            }
        }
        @media screen and (min-width: 450px){
            .box{
                display: grid;
                grid-template-columns: 1fr 1fr 1fr;
                grid-auto-rows: 150px;
                grid-gap: 4px;
                max-width: 450px;
                margin: 0 auto;
                grid-template-areas:
                ". k2 k2"
            }
            .box div{
                background-color: rgb(200,200,200);
                font-size: 12px;
                }
            .k1{
                padding: 0px;
            }
            .k2{
                padding: 5px;
                grid-area: k2
            }
        }
        @media screen and (min-width: 1600px){
            .box{
                display: grid;
                grid-template-columns: 1fr 1fr 1fr;
                grid-auto-rows: 150px;
                grid-gap: 8px;
                max-width: 450px;
                margin: 0 auto;
                grid-template-areas:
                "k1 k2 k2"
            }
            .box div{
                background-color: rgb(200,200,200);
                font-size: 14px;
                }
            .k1{
                grid-area: k1;
            }
            .k2 {
                grid-area: k2;
                padding: 8px
            }
        }
    </style>
</head>
<body>
    <div class="box">
        <div class="k1"><img id="ki1" src="Instagram-Grid/kat.jpg" height="150px" width="150px"></div>
        <div class="k2">
            <b>The cat next to me is a vicious predator</b><br>
            <p>Be careful!
        </div>
        <div class="k3"><img id="ki1" src="Instagram-Grid/kat2.jpg" height="150px" width="150px"></div>
        <div class="k4"><img id="ki1" src="Instagram-Grid/kat.jpg" height="150px" width="150px"></div>
        <div class="k5"><img id="ki1" src="Instagram-Grid/kat2.jpg" height="150px" width="150px"></div>
        <div class="k6"><img id="ki1" src="Instagram-Grid/kat.jpg" height="150px" width="150px"></div>
        <div class="k7"><img id="ki1" src="Instagram-Grid/kat2.jpg" height="150px" width="150px"></div>
        <div class="k8"><img id="ki1" src="Instagram-Grid/kat.jpg" height="150px" width="150px"></div>
    </div>
</body>
