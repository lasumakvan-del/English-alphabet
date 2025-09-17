<!DOCTYPE html>
<html lang="gu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gujarati Alphabet Learning</title>
    
    <!-- Open Graph Meta Tags for Social Media Sharing -->
    <meta property="og:title" content="અંગ્રેજી આલ્ફાબેટ ના ગુજરાતી ઉચ્ચારણ">
    <meta property="og:description" content="Learn Gujarati pronunciation of English alphabets - Makvana Sanjaybhai, Shri Pipardi-2 Primary School">
    <meta property="og:image" content="https://your-website.com/gujarati-alphabet-thumbnail.jpg">
    <meta property="og:image:width" content="800">
    <meta property="og:image:height" content="600">
    <meta property="og:url" content="https://lasumakvan-del.github.io/Gujarati-pronunciation-alphabet/">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Gujarati Alphabet Learning">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="અંગ્રેજી આલ્ફાબેટ ના ગુજરાતી ઉચ્ચારણ">
    <meta name="twitter:description" content="Learn Gujarati pronunciation of English alphabets">
    <meta name="twitter:image" content="https://your-website.com/gujarati-alphabet-thumbnail.jpg">
    
    <!-- Additional Meta Tags -->
    <meta name="description" content="Learn Gujarati pronunciation of English alphabets with interactive learning">
    <meta name="keywords" content="Gujarati, English, Alphabet, Learning, Education, Pronunciation">
    
    <style>
        body {
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        
        .image-container {
            text-align: center;
            max-width: 900px;
        }
        
        .clickable-link {
            display: inline-block;
            text-decoration: none;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            cursor: pointer;
            border: none;
            background: none;
            padding: 0;
        }
        
        .clickable-link:hover {
            transform: scale(1.02);
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
        }
        
        .clickable-link:active {
            transform: scale(0.98);
        }
        
        .gujarati-board {
            width: 800px;
            height: 600px;
            background: linear-gradient(135deg, #8B5CF6 0%, #6366F1 100%);
            position: relative;
            border-radius: 15px;
            display: block;
            border: none;
            outline: none;
        }
        
        .book-icon {
            position: absolute;
            top: 30px;
            right: 30px;
            width: 50px;
            height: 40px;
            background: rgba(255,255,255,0.3);
            border-radius: 5px;
        }
        
        .book-pages {
            position: absolute;
            top: 5px;
            left: 5px;
            width: 20px;
            height: 30px;
            background: rgba(255,255,255,0.6);
            border-radius: 3px;
        }
        
        .book-pages::after {
            content: '';
            position: absolute;
            top: 0;
            right: -20px;
            width: 20px;
            height: 30px;
            background: rgba(255,255,255,0.6);
            border-radius: 3px;
        }
        
        .title-banner {
            position: absolute;
            top: 120px;
            left: 50px;
            width: 700px;
            height: 80px;
            background: rgba(255,182,193,0.9);
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .title-text {
            font-size: 36px;
            font-weight: bold;
            color: #8B0A50;
            text-align: center;
            margin: 0;
        }
        
        .alphabet-row {
            position: absolute;
            top: 280px;
            left: 120px;
            display: flex;
            gap: 20px;
        }
        
        .alphabet-box {
            width: 100px;
            height: 120px;
            border-radius: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: #2D3748;
        }
        
        .box-a { background: rgba(255,182,193,0.9); }
        .box-b { background: rgba(147,112,219,0.9); }
        .box-c { background: rgba(255,182,193,0.9); }
        .box-d { background: rgba(173,216,230,0.9); }
        .box-e { background: rgba(255,228,181,0.9); }
        
        .english-letter {
            font-size: 48px;
            margin-bottom: 10px;
        }
        
        .gujarati-letter {
            font-size: 24px;
        }
        
        .author-info {
            position: absolute;
            bottom: 80px;
            left: 0;
            right: 0;
            text-align: center;
            color: white;
        }
        
        .author-name {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .school-name {
            font-size: 24px;
        }
        
        .instructions {
            margin-top: 20px;
            color: #7B2CBF;
            font-size: 18px;
            font-weight: bold;
        }
        
        .sub-instructions {
            margin-top: 5px;
            color: #666;
            font-size: 14px;
        }
        
        .click-indicator {
            position: absolute;
            top: 10px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(255,255,255,0.9);
            color: #7B2CBF;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: bold;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 0.8; }
            50% { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="image-container">
        <a href="https://lasumakvan-del.github.io/Gujarati-pronunciation-alphabet/" 
           target="_blank" 
           class="clickable-link"
           title="Click to learn Gujarati pronunciation of English alphabets">
            
            <div class="gujarati-board">
                <div class="click-indicator">🖱️ Click to Learn</div>
                
                <div class="book-icon">
                    <div class="book-pages"></div>
                </div>
                
                <div class="title-banner">
                    <h1 class="title-text">અંગ્રેજી આલ્ફાબેટ ના ગુજરાતી ઉચ્ચારણ</h1>
                </div>
                
                <div class="alphabet-row">
                    <div class="alphabet-box box-a">
                        <div class="english-letter">A</div>
                        <div class="gujarati-letter">એ</div>
                    </div>
                    <div class="alphabet-box box-b">
                        <div class="english-letter">B</div>
                        <div class="gujarati-letter">બ</div>
                    </div>
                    <div class="alphabet-box box-c">
                        <div class="english-letter">C</div>
                        <div class="gujarati-letter">ક</div>
                    </div>
                    <div class="alphabet-box box-d">
                        <div class="english-letter">D</div>
                        <div class="gujarati-letter">ડ</div>
                    </div>
                    <div class="alphabet-box box-e">
                        <div class="english-letter">E</div>
                        <div class="gujarati-letter">એ</div>
                    </div>
                </div>
                
                <div class="author-info">
                    <div class="author-name">Makvana Sanjaybhai</div>
                    <div class="school-name">Shri Pipardi-2 Primary School</div>
                </div>
            </div>
            
        </a>
        
        <div class="instructions">
            📚 આ image પર click કરો learning website ખોલવા માટે
        </div>
        <div class="sub-instructions">
            Click anywhere on the image above to open the learning website
        </div>
    </div>
</body>
</html>
