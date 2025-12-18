git - repo create
git clone <link>
git add . / git add index.html
git commit -m "msg"
git push origin main

# Tailwind CSS CLi
<h1>Website</h1>
1. copy - npm install tailwindcss @tailwindcss/cli


<h1>VS Code</h1>
1. open Terminal
2. Past cmd
3. Enter
4. Create index.html and input.css
2.<link rel="stylesheet" href="./output.css"> <!--index.html -->


<h1>package.json</h1>
1. ,
2. "scripts": {
    "start": "npx @tailwindcss/cli -i ./input.css -o ./output.css --watch"
  }


<h1>input.css</h1>
1. copy - @import "tailwindcss";