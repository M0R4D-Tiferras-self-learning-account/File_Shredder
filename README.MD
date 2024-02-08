<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>File Shredder</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        p {
            margin-bottom: 20px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            font-family: Consolas, monospace;
            font-size: 14px;
        }
        .warning {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>File Shredder</h1>
        <p><strong>Introduction:</strong> This is a small file shredder tool designed to securely delete files from a specified directory using the <code>shred</code> and <code>rm</code> commands in Linux. It is intended to provide a simple and effective way to permanently delete sensitive files beyond recovery.</p>
        <h2>Features:</h2>
        <ul>
            <li>Securely delete files from a specified directory.</li>
            <li>Utilizes the <code>shred</code> command to overwrite file contents before deletion, making recovery virtually impossible.</li>
            <li>Removes all traces of the deleted files from the system.</li>
        </ul>
       
        <div class="warning">
            <p><strong>Warning:</strong> Use with caution: This tool permanently deletes files and cannot be undone. Ensure that you specify the correct target directory before executing the command.</p>
</body>
</html>
