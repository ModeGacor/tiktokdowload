<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>TikTok Downloader - Draxz</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700;900&family=Rajdhani:wght@400;500;600;700&family=Courier+Prime:wght@400;700&display=swap" rel="stylesheet">

<style>
:root {
    --primary-purple: #8A2BE2;
    --secondary-purple: #4c1d95;
    --accent-cyan: #00f3ff;
}

/* Reset dasar */
* { margin:0; padding:0; box-sizing:border-box; font-family:'Rajdhani', sans-serif; outline:none; }
body {
    background-color:#050505;
    min-height:100vh;
    background: radial-gradient(circle at 50% 20%, #1a0b2e 0%, #000 60%);
    background-size:200% 200%;
    animation: bgPulse 10s ease infinite;
    display:flex; justify-content:center; align-items:center;
}
@keyframes bgPulse { 0%{background-position:50% 0%;} 50%{background-position:50% 20%;} 100%{background-position:50% 0%;} }

.app-container {
    width: 100%; max-width: 420px;
    background: rgba(0,0,0,0.95);
    border-radius: 20px; padding: 20px;
    color: #fff; position:relative;
    box-shadow:0 0 40px rgba(138,43,226,0.3);
    overflow:hidden;
}

/* Animasi naik */
.anim-element { opacity:0; animation:fadeInUp 0.6s cubic-bezier(0.2,0.8,0.2,1) forwards; }
@keyframes fadeInUp { from{opacity:0; transform:translateY(20px);} to{opacity:1; transform:translateY(0);} }
.delay-1 { animation-delay:0.1s; }
.delay-2 { animation-delay:0.2s; }
.delay-3 { animation-delay:0.3s; }

/* Card input */
.glass-card {
    background: rgba(30,30,45,0.5);
    border-radius:16px; padding:20px;
    border:1px solid rgba(255,255,255,0.08);
    margin-bottom:20px;
}

/* Input box */
.input-group { position:relative; margin-bottom:15px; }
.input-box {
    width:100%; padding:14px 40px 14px 14px;
    border-radius:10px; border:1px solid rgba(255,255,255,0.1);
    background: rgba(0,0,0,0.4); color:#fff; font-size:0.95rem;
}
.input-box:focus {
    border-color:var(--accent-cyan);
    box-shadow:0 0 10px rgba(0,243,255,0.1);
}
.input-icon { position:absolute; right:15px; top:50%; transform:translateY(-50%); color:#888; pointer-events:none; }

/* Tombol action */
.action-btn {
    width:100%; padding:14px;
    background: linear-gradient(135deg, var(--primary-purple), var(--secondary-purple));
    border:none; border-radius:10px;
    color:white; font-family:'Orbitron'; font-weight:700; font-size:0.95rem;
    cursor:pointer; display:flex; justify-content:center; align-items:center; gap:8px;
    position:relative; overflow:hidden;
    transition:0.3s;
}
.action-btn:active { transform:scale(0.98); }
.action-btn:disabled { opacity:0.7; cursor:not-allowed; }

/* Sparkle effect */
.sparkle {
    position:absolute; width:6px; height:6px; background:var(--accent-cyan);
    border-radius:50%; pointer-events:none;
    animation:sparkleAnim 0.8s forwards;
}
@keyframes sparkleAnim { 0%{opacity:1; transform:translate(0,0) scale(1);} 100%{opacity:0; transform:translate(var(--tx),var(--ty)) scale(0);} }

/* Progress bar */
.progress-wrapper { margin-top:15px; display:none; }
.progress-track { width:100%; height:4px; background: rgba(255,255,255,0.1); border-radius:10px; overflow:hidden; }
.progress-fill { height:100%; width:0%; background: var(--accent-cyan); transition:width 0.3s ease; box-shadow:0 0 8px var(--accent-cyan); }
.progress-text { text-align:center; font-size:0.7rem; color:#aaa; margin-top:6px; font-family:'Courier Prime', monospace; }

/* Result section */
.result-section { display:none; }
.video-wrapper {
    width:100%; border-radius:12px; overflow:hidden; background:#000;
    margin-bottom:15px; border:1px solid #333; position:relative; padding-top:177%; max-height:60vh;
}
.video-player { position:absolute; top:0; left:0; width:100%; height:100%; }
.meta-info { text-align:center; margin-bottom:15px; }
.meta-title { color:#fff; font-weight:600; font-size:0.95rem; margin-bottom:2px; }
.meta-author { color:var(--accent-cyan); font-size:0.85rem; font-family:'Courier Prime', monospace; }
.stats-grid { display:grid; grid-template-columns:1fr 1fr 1fr; background: rgba(0,0,0,0.2); padding:10px; border-radius:10px; margin-bottom:15px; border:1px solid rgba(255,255,255,0.05); }
.stat-item { text-align:center; color:#ccc; font-size:0.8rem; display:flex; flex-direction:column; align-items:center; gap:4px; }
.stat-item i { color:var(--primary-purple); font-size:1rem; }
.dl-grid { display:grid; grid-template-columns:1fr 1fr; gap:10px; }
.dl-btn {
    background: rgba(255,255,255,0.05); border:1px solid rgba(255,255,255,0.1);
    padding:12px; border-radius:10px; color:#fff; text-decoration:none;
    display:flex; flex-direction:column; align-items:center; justify-content:center; transition:0.2s;
}
.dl-btn:active { background: rgba(255,255,255,0.15); transform:scale(0.98); }
.dl-btn i { font-size:1.1rem; margin-bottom:4px; color:var(--accent-cyan); }
.dl-btn span { font-size:0.85rem; font-weight:600; }
.dl-btn small { font-size:0.65rem; color:#888; }

/* Terminal log */
.terminal-log { background:#080808; border:1px solid #222; border-radius:10px; padding:12px; font-family:'Courier Prime'; font-size:0.7rem; height:100px; overflow-y:auto; color:#00ff88; margin-top:20px; }
.log-line { margin-bottom:4px; border-bottom:1px solid rgba(255,255,255,0.03); }
.log-error { color:#ff3355; }
.log-info { color:#777; }

/* Toast */
.toast {
    position:absolute; bottom:20px; left:50%;
    transform: translateX(-50%) translateY(20px);
    background: rgba(20,20,25,0.95);
    border:1px solid var(--accent-cyan);
    padding:10px 20px; border-radius:50px;
    display:flex; align-items:center; gap:10px;
    color:#fff; font-size:0.9rem; font-weight:600;
    opacity:0; visibility:hidden;
    transition: all 0.3s cubic-bezier(0.175,0.885,0.32,1.275);
    z-index:1000; width:max-content; max-width:90%;
}
.toast.show { opacity:1; visibility:visible; transform: translateX(-50%) translateY(0); }
.toast i { color:var(--accent-cyan); }
</style>
</head>
<body>

<div class="app-container">

    <!-- Input Card -->
    <div class="glass-card anim-element delay-1">
        <div class="input-group">
            <input type="text" class="input-box" id="tiktok-url" placeholder="Paste TikTok Link...">
            <i class="fa-solid fa-link input-icon"></i>
        </div>
        <button class="action-btn" id="downloadBtn">
            <i class="fa-solid fa-bolt"></i> GET VIDEO
        </button>
        <div class="progress-wrapper" id="progress-container">
            <div class="progress-track">
                <div class="progress-fill" id="progress-fill"></div>
            </div>
            <div class="progress-text" id="progress-text">Connecting...</div>
        </div>
    </div>

    <!-- Result Section -->
    <div class="glass-card result-section" id="result-section">
        <div class="meta-info">
            <div class="meta-title" id="video-title">Title Loading...</div>
            <div class="meta-author" id="video-author">@username</div>
        </div>

        <div class="video-wrapper">
            <video class="video-player" id="video-preview" controls loop playsinline></video>
        </div>

        <div class="stats-grid">
            <div class="stat-item"><i class="fa-solid fa-heart"></i> <span id="like-count">0</span></div>
            <div class="stat-item"><i class="fa-solid fa-comment"></i> <span id="comment-count">0</span></div>
            <div class="stat-item"><i class="fa-solid fa-share"></i> <span id="share-count">0</span></div>
        </div>

        <div class="dl-grid">
            <a href="#" class="dl-btn" id="dl-video">
                <i class="fa-solid fa-video"></i>
                <span>No Watermark</span>
                <small>MP4 HD</small>
            </a>
            <a href="#" class="dl-btn" id="dl-audio">
                <i class="fa-solid fa-music"></i>
                <span>Audio Only</span>
                <small>MP3 Format</small>
            </a>
        </div>
    </div>

    <!-- Terminal Log -->
    <div class="terminal-log anim-element delay-3" id="log">
        <div class="log-line">> System Initialized...</div>
        <div class="log-line log-info">> Ready for input.</div>
    </div>

    <!-- Toast -->
    <div class="toast" id="toast">
        <i class="fa-solid fa-info-circle"></i>
        <span id="toast-msg">Notification</span>
    </div>
</div>

<script>
// ----------------- Utilities -----------------
const utils = {
    log: (msg, type='') => {
        const log = document.getElementById('log');
        const line = document.createElement('div');
        line.className = `log-line ${type==='error'?'log-error':type==='info'?'log-info':''}`;
        line.innerText = `> ${msg}`;
        log.appendChild(line);
        log.scrollTop = log.scrollHeight;
    },
    toast: (msg) => {
        const t = document.getElementById('toast');
        document.getElementById('toast-msg').innerText = msg;
        t.classList.add('show');
        setTimeout(()=> t.classList.remove('show'), 3000);
    },
    loading: (state) => {
        const btn = document.getElementById('downloadBtn');
        const prog = document.getElementById('progress-container');
        if(state){
            btn.disabled = true;
            btn.innerHTML='<i class="fa-solid fa-spinner fa-spin"></i> PROCESSING...';
            prog.style.display='block';
        } else {
            btn.disabled=false;
            btn.innerHTML='<i class="fa-solid fa-bolt"></i> GET VIDEO';
            prog.style.display='none';
        }
    },
    progress: (pct,text) => {
        document.getElementById('progress-fill').style.width=pct+'%';
        document.getElementById('progress-text').innerText=text;
    }
}

// ----------------- Format number -----------------
function formatNumber(num){
    if(num>=1000000) return (num/1000000).toFixed(1)+'M';
    if(num>=1000) return (num/1000).toFixed(1)+'K';
    return num;
}

// ----------------- Sparkle Effect -----------------
function createSparkles(x,y){
    for(let i=0;i<8;i++){
        const sp=document.createElement('div');
        sp.className='sparkle';
        const tx=(Math.random()-0.5)*80 + 'px';
        const ty=(Math.random()-0.5)*80 + 'px';
        sp.style.setProperty('--tx', tx);
        sp.style.setProperty('--ty', ty);
        sp.style.left = (x - 3) + 'px'; // tengah sparkle
        sp.style.top = (y - 3) + 'px';
        document.body.appendChild(sp);
        sp.addEventListener('animationend',()=>sp.remove());
    }
}

// ----------------- Setup Download Button -----------------
function setupBtn(id,url,name){
    const btn=document.getElementById(id);
    btn.onclick=(e)=>{
        e.preventDefault();
        utils.toast("Download started...");
        const a=document.createElement('a');
        a.href=url; a.download=name; a.target='_blank';
        document.body.appendChild(a); a.click(); document.body.removeChild(a);
    }
}

// ----------------- API -----------------
const API_ENDPOINTS=[
    {
        url:(url)=>`https://www.tikwm.com/api/?url=${encodeURIComponent(url)}`,
        method:"GET",
        parse:(data)=>{
            if(data.data) return {
                success:true,
                video:data.data.play||data.data.wmplay,
                music:data.data.music,
                title:data.data.title,
                author:data.data.author?.nickname||"User",
                stats:{
                    like:data.data.digg_count||0,
                    comment:data.data.comment_count||0,
                    share:data.data.share_count||0
                }
            };
            throw new Error("Invalid response");
        }
    }
];

// ----------------- Fetch TikTok Data -----------------
async function fetchTikTokData(url){
    for(const endpoint of API_ENDPOINTS){
        try{
            utils.log("Connecting to server...","info");
            const res=await fetch(endpoint.url(url));
            const data=await res.json();
            const result=endpoint.parse(data);
            if(result.success) return result;
        }catch(e){ utils.log(`API Error: ${e.message}`,'error'); }
    }
    throw new Error("Server busy. Try again.");
}

// ----------------- Download TikTok -----------------
async function downloadTikTok(){
    const url=document.getElementById('tiktok-url').value.trim();
    if(!url) return utils.toast("Please paste a link first!");
    utils.loading(true);
    document.getElementById('result-section').style.display='none';
    utils.progress(10,"Initializing...");

    try{
        const data=await fetchTikTokData(url);
        utils.progress(80,"Data retrieved...");

        // Update UI
        document.getElementById('video-title').innerText=data.title||"No Title";
        document.getElementById('video-author').innerText="@"+data.author;
        document.getElementById('like-count').innerText=formatNumber(data.stats.like);
        document.getElementById('comment-count').innerText=formatNumber(data.stats.comment);
        document.getElementById('share-count').innerText=formatNumber(data.stats.share);

        const vid=document.getElementById('video-preview'); vid.src=data.video;
        setupBtn('dl-video',data.video,`tiktok_${Date.now()}.mp4`);
        setupBtn('dl-audio',data.music,`audio_${Date.now()}.mp3`);
        document.getElementById('dl-audio').style.display=data.music?'flex':'none';

        utils.progress(100,"Complete!");
        document.getElementById('result-section').style.display='block';
        utils.log("Success!","info");
        utils.toast("Video found!");

    }catch(e){
        utils.toast("Failed to download");
        utils.log(e.message,'error');
    }finally{ utils.loading(false); }
}

// ----------------- Attach Button Listener -----------------
const downloadBtn=document.getElementById('downloadBtn');
downloadBtn.addEventListener('click',(e)=>{
    // Sparkle effect di tengah tombol
    const rect=downloadBtn.getBoundingClientRect();
    createSparkles(rect.left+rect.width/2, rect.top+rect.height/2);

    // Panggil download
    downloadTikTok();
});
</script>
</body>
</html>
