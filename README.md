<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mockseas TV Gallery</title>
    <style>
        /* BBC-inspired Dark Theme */
        body { 
            background: #0a0a0a; 
            color: #efefef; 
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; 
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        h1 { 
            font-size: 2.5rem; 
            letter-spacing: -1px; 
            margin-bottom: 30px; 
            border-bottom: 3px solid #e11b22; /* BBC Red underline */
            padding-bottom: 10px;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            width: 90%;
            max-width: 1000px;
        }

        .nav-box {
            background: #1a1a1a;
            border: 1px solid #333;
            color: white;
            text-decoration: none;
            padding: 40px 20px;
            border-radius: 12px;
            text-align: center;
            transition: all 0.3s ease;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        /* Hover Effects */
        .nav-box:hover {
            background: #252525;
            border-color: #e11b22;
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.5);
        }

        .icon { font-size: 2.5rem; }
        .label { font-size: 1.2rem; font-weight: bold; text-transform: uppercase; }
        .desc { font-size: 0.9rem; color: #aaa; }

        /* BBC Two Purple Hover for the Menu */
        .menu-box:hover { border-color: #4b2c7b !important; }
        
        /* BBC National Blue Hover */
        .nat-box:hover { border-color: #0066cc !important; }
    </style>
</head>
<body>

    <h1>Mockseas Broadcast Gallery</h1>

    <div class="container">
        
        <a href="BBC%20Clock/" class="nav-box">
            <span class="icon">🕒</span>
            <span class="label">BBC One Clock</span>
            <span class="desc">The 1997-2002 "Balloon" Era Clock</span>
        </a>

        <a href="BBCMenu/" class="nav-box menu-box">
            <span class="icon">📺</span>
            <span class="label">BBC Two Menu</span>
            <span class="desc">Interactive Schedule Tool</span>
        </a>

        <a href="BBCNationalService/" class="nav-box nat-box">
            <span class="icon">📻</span>
            <span class="label">National Service</span>
            <span class="desc">Radio & Audio Broadcast Interface</span>
        </a>

        <a href="BBCSlides/" class="nav-box">
            <span class="icon">🖼️</span>
            <span class="label">BBC Slides</span>
            <span class="desc">Information & Continuity Slides</span>
        </a>

    </div>

    <p style="margin-top: 50px; color: #555; font-size: 0.8rem;">Select a service to begin transmission.</p>

</body>
</html>
