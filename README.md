<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAILBREAK-MD-V1</title>
    <style>
        body {
            background-color: black;
            color: #00ff00; /* Hacker green text */
            font-family: 'Courier New', Courier, monospace;
        }
        .repo {
            text-align: center;
        }
        a {
            color: #00ff00;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        h1, h2, h3, h4, h5, h6 {
            color: #00ff00;
        }
        pre {
            background-color: black;
            color: #00ff00;
            padding: 15px;
            border: 1px solid #00ff00;
            border-radius: 5px;
            overflow-x: auto;
        }
        .button {
            background-color: #00ff00;
            color: black;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            display: inline-block;
            margin: 10px 0;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        .button:hover {
            background-color: black;
            color: #00ff00;
            border: 1px solid #00ff00;
        }
    </style>
</head>
<body>
    <h1>JAILBREAK-MD-V1</h1>
    <p>Simple Best WhatsApp Bot Created By JAILBREAKALT1</p>
    
    <div class="repo">
        <h2>Deploy Setup ↕️</h2>
        <p><strong>1. Fork This Repository</strong></p>
        <p>Start by forking this repository to your own GitHub account. Click the button below to fork:</p>
        <a href="https://github.com/jailbreakalt1/JAILBREAK-MD-v1/fork">
            <button class="button">Fork Repository</button>
        </a>

        <h3>🔑 Get Session ID (WhatsApp Pair Code Login)</h3>
        <p>To deploy, generate your session ID from the link below:</p>
        <a href="https://malvin-pair-code-xzcb.onrender.com/?">
            <button class="button">Get Pair Code</button>
        </a>

        <p><strong>2. Obtain the Session ID</strong></p>
        <p>After accessing the URL, you should see a session ID displayed. Copy this session ID.</p>

        <h3>Deploy Methods</h3>
        <p><strong>1. Deploy on Heroku ⤵️</strong></p>
        <a href="https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fkingmalvn%2FLITE-MD">
            <button class="button">Deploy on Heroku</button>
        </a>

        <p><strong>2. Deploy on Render ⤵️</strong></p>
        <a href="https://render.com/deploy?repo=https://github.com/kingmalvn/LITE-MD.git">
            <button class="button">Deploy on Render</button>
        </a>

        <p><strong>3. Deploy on GitHub ⤵️</strong></p>
        <p>Copy the workflow codes and then fork the repo. Edit the config, add session ID, then save. Click on the repo action tab, then click "Start New Workflow". Paste the workflow codes and rename `main.yml` to `deploy.yml`, then save the file.</p>

        <h3>Important</h3>
        <p><strong>Attention!</strong> We do not take responsibility if your GitHub account is suspended through this Deploy method. I advise you not to use this workflow deploy method for newer GitHub accounts. GitHub accounts created a year or more ago have not received the risk of suspension so far. This method will only work for 6 hours; you need to update the code to reactivate it.</p>

        <pre>
        name: Node.js CI

        on:
          push:
            branches:
              - main
          pull_request:
            branches:
              - main

        jobs:
          build:
            runs-on: ubuntu-latest

            strategy:
              matrix:
                node-version: [20.x]

            steps:
              - name: Checkout repository
                uses: actions/checkout@v3

              - name: Set up Node.js
                uses: actions/setup-node@v3
                with:
                  node-version: ${{ matrix.node-version }}

              - name: Install dependencies
                run: npm install

              - name: Start application
                run: npm start
        </pre>
        
        <p>Thank you dear, <strong>JAILBREAK-MD Developer</strong></p>
        <p>Developer of JAILBREAK-MD:</p>
        <p>- <a href="https://github.com/techlord01">jailbreakalt1</a></p>
        <p>Creator and Owner of JAILBREAK-MD</p>
        <p>Lite-MD Helper:</p>
        <p>- <a href="https://github.com/kingmalvn">Malvin King</a></p>
        <p>For helping in bot plugin files.</p>
    </div>
</body>
</html><!DOCTYPE html>
