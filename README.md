# MusicApplication
<div class="music-player">
</div>

{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #5f7a61;
    font-family: 'roboto', sans-serif;
}

.music-player{
    width: 250px;
    height: 450px;
    border-radius: 20px;
    background: rgba(255, 255, 255, 0.08);
    box-shadow: 0 40px 100px rgba(255, 255, 255, 0.1);
    padding: 40px;
    overflow: hidden;
    color: #d5eebb;
}

<h1 class="music-name">song one</h1>
.music-name{
    font-size: 30px;
    font-weight: 400;
    margin-bottom: 10px;
}


<div class="song-slider">
    <input type="range" value="0" class="seek-bar">
</div>

.song-slider{
    width: 100%;
    position: relative;
}

<div class="song-slider">
    <input type="range" value="0" class="seek-bar">
    <span class="current-time">00:00</span>
    <span class="song-duration">00:00</span>

.current-time,
.song-duration{
    font-size: 14px;
}

.song-duration{
    position: absolute;
    right: 0;
}

<div class="controls">
    <button class="play-btn">
        <span></span>
        <span></span>
    </button>
</div>


.controls{
    width: 60%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: auto;
    margin-top: 20px;
}

.play-btn{
    position: relative;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #d5eebb;
    cursor: pointer;
    border: none;
}


.play-btn.pause span:nth-child(1){
    width: 35%;
    left: 53%;
    transform: translate(-50%, -50%);
    border-radius: 0;
    clip-path: polygon(0 0, 100% 50%, 100% 50%, 0% 100%);
}


.btn{
    width: 40px;
    height: 40px;
    background: #d5eebb;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    border: none;
    cursor: pointer;
}
