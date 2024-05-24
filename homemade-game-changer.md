---
title: Homemade Game Changer
layout: page
type: homemadegamechanger
---

<style>

        body {
            justify-content: center;
            align-items: center;
            background-color: #f0f0f0;
        }
        .download-container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 100%;
        }
        .download-container table {
            width: 100%;
            border-collapse: collapse;
        }
        .download-container th, .download-container td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        .download-container th {
            background-color: #4CAF50;
            color: white !important;
        }
        .download-container tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .download-container tr:hover {
            background-color: #f1f1f1;
        }
        .download-container .download-btn {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .download-container .download-btn:hover {
            background-color: #45a049;
        }
        hr.has-background-black {
            display: none;
        }
        h1.title {
            display: none;
        }
        .highlight {
            background-color: #d4edda !important;
            font-weight: bold;
        }
    </style>
<body>
    <div class="download-container">
        <h1 style="text-align:center;">Homemade Game Changer Downloads</h1>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Download</th>
                </tr>
            </thead>
            <tbody>
                <tr id="guess-that-phrase">
                    <td>Guess That Phrase!</td>
                    <td><a href="https://github.com/ScytedTV-Studios/Homemade-Game-Changer/releases/download/guess-that-phrase/guess-that-phrase.zip" class="download-btn">Download</a></td>
                </tr>
            </tbody>
        </table>
    </div>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const urlParams = new URLSearchParams(window.location.search);
            const query = urlParams.get('query');
            if (query) {
                const targetRow = document.getElementById(query);
                if (targetRow) {
                    targetRow.classList.add('highlight');
                    targetRow.scrollIntoView({ behavior: 'smooth', block: 'center' });
                }
            }
        });
    </script>
</body>