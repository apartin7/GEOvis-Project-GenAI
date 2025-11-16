# GEOvis-Project-GenAI

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <title>Addison Partin — AS3 Video Submission</title>
    <link rel="stylesheet" href="styles.css" />
    <script src="script.js"></script>

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: "Helvetica Neue", Arial, sans-serif;
            background: linear-gradient(135deg, #f5f0ff, #e8f7ff);
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            color: #333;
        }

        .container {
            max-width: 900px;
            width: 90%;
            margin-top: 50px;
            text-align: center;
        }

        h1.title {
            font-size: 2.8rem;
            font-weight: 700;
            color: #3a2b80;
            margin-bottom: 15px;
        }

        .subtitle {
            font-size: 1.1rem;
            color: #555;
            margin-bottom: 35px;
            font-style: italic;
        }

        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        }

        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
            border-radius: 20px;
        }

        .footer {
            margin-top: 40px;
            font-size: 0.9rem;
            color: #666;
        }

        /* visually hidden for screen readers */
        .visually-hidden {
          position: absolute !important;
          height: 1px; width: 1px;
          overflow: hidden;
          clip: rect(1px, 1px, 1px, 1px);
          white-space: nowrap;
          border: 0;
          padding: 0;
          margin: -1px;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1 id="videoTitle" class="title">✨ Noemi Rives & Addison Partin — Using AI to Enhance Your GeoVisualization Project ✨</h1>
        <div class="subtitle">Seeing Where GenAI Shines (and Where It Doesn’t) in GeoViz</div>

        <!-- offscreen description for assistive tech -->
        <p id="videoCaption" class="visually-hidden">
            Google Meet recording: Addison Partin — Assignment 3 submission, Fall 2025.
        </p>

        <div class="video-wrapper" aria-labelledby="videoTitle" aria-describedby="videoCaption">
            <iframe 
                title="Google Meet recording — Addison Partin AS3"
                src="https://drive.google.com/file/d/1eBZl-YOWd-2CU2QPB4QqC1KZd0eMBgJm/preview"
                allow="autoplay; encrypted-media; fullscreen"
                allowfullscreen>
            </iframe>
        </div>

        <div class="footer">
            Assignment 3 · GES 4070 · Fall 2025
        </div>
    </div>
</body>
</html>

