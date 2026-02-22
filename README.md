<a href=https://github.com/C0m3b4ck/StreamTalker/blob/main/README_PL.md>🇵🇱🇵🇱🇵🇱🇵🇱🇵🇱POLSKA WERSJA🇵🇱🇵🇱🇵🇱🇵🇱🇵🇱🇵🇱</a>
<br>![GitHub All Releases](https://img.shields.io/github/downloads/C0m3b4ck/StreamTalker/total)
<br><b>🇪🇺🇪🇺🇪🇺Made in Europe🇪🇺🇪🇺🇪🇺</b>
# StreamTalker
<b>A GUI app using SadTalker in Python, hosted locally. </b>
<br>User prompts llamacpp, then the reply is returned with a head/bust animation of the selected image (using TTS and SadTalker).
# Instructions
🎥🎥🎥<b>Video can be found here: </a></b>🎥🎥🎥
<h2><b>Required:</b></h2>
<b>
<pre><code>requirements.txt for app.py</code></pre>
<pre><code>requirements.txt for SadTalker</code></pre>
<pre><code>./download_models.sh from SadTalker</code></pre>

<h2>1. Main project - venv</h2>
<pre><code>python -m venv venv</code></pre>
<pre><code>source venv/bin/activate</code></pre>
<pre><code>pip install --upgrade pip</code></pre>
<pre><code>pip install -r requirements.txt</code></pre>

<h2>2. Ollama model</h2>
<pre><code>ollama pull llama3.2:3b</code></pre>

<h2>3. SadTalker repo</h2>
<pre><code>git clone https://github.com/OpenTalker/SadTalker.git</code></pre>
<pre><code>cd SadTalker</code></pre>
<pre><code>pip install -r requirements.txt</code></pre>
<pre><code>./download_models.sh</code></pre>
<pre><code>cd ..</code></pre>

<h2>4. Place your portrait called bust_photo.png in the same directory as app.py</h2>

# 5. Run
<pre><code>python app.py</code></pre>
</b>

# Supported OSes
<b>Supports Linux, Windows requires different commands and a small rewrite of the app. However, it is not worth it, as Windows is slow and limited in terms of local AI.</b>
# Author
Started by C0m3b4ck on February 20th, 2026
