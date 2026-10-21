<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#180d2c">
<title>For Prachi 💗 A Birthday Surprise</title>
<style>
:root{--bg:#160d29;--pink:#ff7aab;--gold:#ffd98e;--cream:#fff4ed;--orange:#ff916e}
*{box-sizing:border-box}
html,body{margin:0;min-height:100%;font-family:system-ui,-apple-system,"Segoe UI",sans-serif}
body{background:radial-gradient(ellipse at 50% 25%,#4b204d 0,#211331 48%,#10091d 100%);color:#fff;min-height:100svh;overflow:hidden}
button{font:inherit;cursor:pointer}
button:focus-visible{outline:2px solid #ffe4a8;outline-offset:4px}
#stars{position:fixed;inset:0;pointer-events:none;overflow:hidden}
.star{position:absolute;background:#fff2d2;border-radius:50%;width:2px;height:2px;opacity:.7;animation:twinkle var(--d) ease-in-out infinite alternate}
@keyframes twinkle{to{opacity:.12;transform:scale(.4)}}
.topline{position:fixed;top:12px;left:0;right:0;text-align:center;font-size:9px;letter-spacing:.26em;color:#f4cbdc;z-index:4;pointer-events:none}
.stage{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;padding:30px 17px 22px;opacity:0;transform:translateY(12px) scale(.985);pointer-events:none;transition:opacity .55s,transform .55s}
.stage.active{opacity:1;transform:none;pointer-events:auto}
.screen{width:min(100%,410px);max-height:calc(100svh - 52px);overflow:auto;text-align:center;padding:25px 22px 22px;border:1px solid #d9b67b78;border-radius:25px;background:linear-gradient(155deg,#2a1838ed,#180f28f5);box-shadow:0 22px 70px #0005;position:relative}
.screen:before{content:"";position:absolute;inset:7px;border:1px solid #fff1;border-radius:19px;pointer-events:none}
.eyebrow{font-size:10px;letter-spacing:.24em;color:#f6d6e2;text-transform:uppercase;margin:2px 0 13px}
h1{font-size:clamp(31px,8.5vw,44px);font-weight:650;line-height:1.12;margin:10px 0;color:#fff5f8}
.script{font-family:"Brush Script MT","Segoe Script",cursive;font-weight:500;color:var(--gold);font-size:clamp(36px,10vw,52px);line-height:1.05;margin:8px 0}
.sub{color:#eaceda;font-size:13px;line-height:1.7;margin:10px auto 18px;max-width:310px}
.btn{display:block;width:100%;border:0;border-radius:99px;padding:14px 16px;background:linear-gradient(100deg,#ff8b78,#ffb84f);color:#fff;font-size:14px;font-weight:750;box-shadow:0 7px 24px #ff8b6335;margin-top:12px;transition:transform .2s}
.btn:active{transform:scale(.97)}
.ghost{background:#ffffff0d;border:1px solid #ffffff35;color:#ffe9f1;box-shadow:none}
.gift{font-size:67px;filter:drop-shadow(0 0 20px #ffae6e70);animation:bob 2s ease-in-out infinite}
@keyframes bob{50%{transform:translateY(-7px) rotate(2deg)}}
.pink-screen{background:linear-gradient(155deg,#ff6e9f,#ed337d 70%,#a82d70);border:1px solid #ffc0d7;box-shadow:0 20px 60px #f52d7950}
.pink-screen:before{border-color:#ffffff38}
.pink-screen h1{font-size:clamp(36px,10vw,51px)}
.line{width:74px;height:2px;background:#ffd58c;margin:18px auto}
.flower-heart{font-size:clamp(105px,32vw,150px);line-height:1.1;letter-spacing:-.16em;filter:drop-shadow(0 0 22px #ff8fa7aa);animation:heartBeat 1.7s infinite;display:block;margin:5px auto 12px}
@keyframes heartBeat{0%,100%{transform:scale(1)}12%{transform:scale(1.07)}24%{transform:scale(1)}38%{transform:scale(1.04)}}
.cake-wrap{height:175px;display:flex;align-items:center;justify-content:center;margin:0 auto 8px}
.cake{width:185px;height:155px;position:relative;filter:drop-shadow(0 10px 10px #0004);animation:cakeUp .8s cubic-bezier(.2,.9,.2,1.2) both}
@keyframes cakeUp{from{transform:translateY(35px) scale(.7);opacity:0}to{transform:none;opacity:1}}
.plate{position:absolute;bottom:5px;left:0;width:185px;height:17px;border-radius:50%;background:linear-gradient(#fff0f3,#e9a8c2);box-shadow:0 4px #a45b88}
.cakebase{position:absolute;left:15px;bottom:21px;width:155px;height:48px;border-radius:9px 9px 12px 12px;background:repeating-linear-gradient(90deg,#ff8caf 0 17px,#ffb6ca 17px 34px);border-top:9px solid #fff0db}
.caketop{position:absolute;left:21px;bottom:63px;width:143px;height:38px;border-radius:12px 12px 6px 6px;background:linear-gradient(#fff1e1 0 10px,#f8a4bf 10px);border-top:6px solid #fffaf0}
.caketop:after{content:"";position:absolute;top:3px;left:12px;width:18px;height:17px;border-radius:0 0 12px 12px;background:#fff0e1;box-shadow:30px 0 #fff0e1,60px 0 #fff0e1,90px 0 #fff0e1}
.candle{position:absolute;left:86px;bottom:98px;width:13px;height:32px;border-radius:4px;background:repeating-linear-gradient(135deg,#fff 0 5px,#ff6da6 5px 10px);z-index:2}
.flame{position:absolute;left:85px;bottom:126px;width:15px;height:22px;border-radius:80% 10% 70% 60%;background:radial-gradient(ellipse at 60% 65%,#fff9b5 0 20%,#ffbf50 44%,#ff6b69 78%);filter:drop-shadow(0 0 10px #ffbd53);animation:flicker .4s infinite alternate;z-index:3}
@keyframes flicker{to{transform:rotate(-9deg) scale(.9,1.08)}}
.balloons{display:flex;align-items:center;justify-content:center;gap:10px;height:105px;margin:0 auto 12px}
.balloon{width:48px;height:61px;border-radius:50% 50% 45% 45%;position:relative;border:1px solid #ffffff55;box-shadow:inset -8px -7px 12px #0002,inset 6px 5px 10px #ffffff55;animation:float 2.1s ease-in-out infinite alternate;transition:transform .35s,opacity .35s}
.balloon:before{content:"";position:absolute;left:21px;bottom:-8px;border-left:5px solid transparent;border-right:5px solid transparent;border-top:9px solid currentColor}
.balloon:after{content:"";position:absolute;left:24px;top:67px;width:1px;height:35px;background:#ffffff75}
.balloon:nth-child(1){background:#ff8baf;color:#ff8baf}
.balloon:nth-child(2){background:#a78bfa;color:#a78bfa;animation-delay:.25s}
.balloon:nth-child(3){background:#53d8c8;color:#53d8c8;animation-delay:.5s}
.balloon:nth-child(4){background:#ffbd61;color:#ffbd61;animation-delay:.75s}
@keyframes float{to{transform:translateY(-9px) rotate(4deg)}}
.balloon.popped{transform:scale(1.7) rotate(25deg);opacity:0;pointer-events:none}
.memory-card{background:#fff4e9;color:#4a2840;border-radius:8px;padding:10px 10px 17px;width:76%;margin:8px auto 18px;box-shadow:0 9px 22px #0004;transform:rotate(-3deg);animation:photoIn .7s both}
@keyframes photoIn{from{opacity:0;transform:translateX(30px) rotate(5deg)}to{opacity:1;transform:rotate(-3deg)}}
.photo-placeholder{height:175px;background:linear-gradient(140deg,#eec3c9,#f7dfd0 50%,#bda5bd);display:grid;place-items:center;font-size:45px;overflow:hidden;position:relative}
.photo-placeholder img{width:100%;height:100%;object-fit:cover;display:none}
.memory-card p{font-family:"Brush Script MT","Segoe Script",cursive;font-size:22px;margin:10px 0 0}
.photo-tools{display:flex;gap:8px;margin:0 auto 12px}
.photo-tools label{flex:1}
.photo-tools .btn{margin:0;font-size:12px;padding:10px 7px}
.envelope{font-size:100px;display:block;animation:envelopeBob 2s infinite}
@keyframes envelopeBob{50%{transform:translateY(-7px)}}
.letter{background:#fff4df;color:#56374a;border-radius:8px;text-align:left;padding:18px 17px;font-family:Georgia,serif;font-size:14px;line-height:1.75;white-space:pre-line;box-shadow:0 9px 24px #0004}
.letter strong{color:#9d4a69}
.final-flowers{font-size:47px;animation:bob 2s infinite}
.spark{position:fixed;top:-20px;z-index:8;pointer-events:none;animation:fall var(--dur) linear forwards;color:var(--col);font-size:var(--size)}
@keyframes fall{to{transform:translate(var(--drift),110svh) rotate(620deg);opacity:.1}}
.ring{width:100px;height:100px;border:2px solid #ff9ab9;border-radius:50%;display:grid;place-items:center;margin:14px auto;box-shadow:0 0 25px #ff74aa55;animation:ringPulse 1.8s infinite}
.ring span{font-size:42px;animation:heartBeat 1.5s infinite}
@keyframes ringPulse{50%{box-shadow:0 0 38px #ff74aaaa;transform:scale(1.04)}}
#modal{position:fixed;inset:0;background:#080511e8;z-index:20;display:none;place-items:center;padding:18px}
#modal.open{display:grid}
.editor{width:min(100%,410px);max-height:90svh;overflow:auto;background:#fff5f8;color:#432039;border-radius:22px;padding:22px;text-align:left}
.editor h2{margin:0 0 10px}
.editor label{display:block;font-size:12px;font-weight:700;margin:12px 0 5px}
.editor input,.editor textarea{width:100%;border:1px solid #e4c5d4;border-radius:10px;padding:11px;font:inherit;font-size:14px;background:#fff;color:#3b2035}
.editor textarea{min-height:100px;resize:vertical}
.actions{display:flex;gap:8px}
.actions button{flex:1}
.progress{position:fixed;bottom:8px;left:50%;transform:translateX(-50%);display:flex;gap:5px;z-index:5}
.dot{width:5px;height:5px;border-radius:9px;background:#ffffff40;transition:all .3s}
.dot.on{width:18px;background:#ffd98e}
.edit{position:fixed;bottom:23px;right:12px;z-index:10;border:1px solid #ffffff50;border-radius:30px;background:#25152eee;color:white;padding:9px 12px;font-size:11px}
@media(max-height:700px){.screen{padding:18px 17px;max-height:calc(100svh - 42px)}.cake-wrap{height:145px}.cake{transform:scale(.9)}.photo-placeholder{height:125px}.memory-card{margin-bottom:10px}.sub{margin:7px auto 12px}}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}}
</style>
</head>
<body>
<div id="stars"></div>
<div class="topline">A LITTLE BIRTHDAY MAGIC · JUST FOR YOU</div>
<div class="progress" id="progress"></div>

<section class="stage active" data-stage="0">
  <div class="screen">
    <div class="eyebrow">a surprise made with love</div>
    <div class="gift">🎁</div>
    <div class="script">For Prachi</div>
    <p class="sub">Someone has a little surprise waiting for you…</p>
    <button class="btn" data-next>Unwrap it ✨</button>
    <p class="sub" style="font-size:10px;margin-bottom:0">♡ made by Manglam ♡</p>
  </div>
</section>

<section class="stage" data-stage="1">
  <div class="screen pink-screen">
    <div class="eyebrow">today is your day</div>
    <h1>HAPPY<br>BIRTHDAY</h1>
    <div class="line"></div>
    <div class="script" style="color:#fff1b8">Prachi!</div>
    <p class="sub" style="color:#fff4f8">May your day be as lovely and special as you are. 💗</p>
    <button class="btn" style="background:linear-gradient(100deg,#fff0cc,#ffb3ca);color:#8c2c5a" data-next>There’s more… 💖</button>
  </div>
</section>

<section class="stage" data-stage="2">
  <div class="screen">
    <div class="eyebrow">a heart full of happy wishes</div>
    <span class="flower-heart">💐</span>
    <div class="script">For you, Prachi</div>
    <p class="sub">Sending you a bouquet of smiles, hugs, and little reasons to be happy.</p>
    <button class="btn" data-next>Keep going ✨</button>
  </div>
</section>

<section class="stage" data-stage="3">
  <div class="screen">
    <div class="eyebrow">first things first 🎂</div>
    <div class="cake-wrap">
      <div class="cake">
        <div class="plate"></div><div class="cakebase"></div>
        <div class="caketop"></div><div class="candle"></div>
        <div class="flame" id="flame"></div>
      </div>
    </div>
    <h1 style="font-size:29px">Make a wish!</h1>
    <p class="sub">Close your eyes, make a little wish, and tap the button. ✨</p>
    <button class="btn" id="wish">Make a wish & blow 🕯️</button>
    <button class="btn ghost" data-next>Next surprise →</button>
  </div>
</section>

<section class="stage" data-stage="4">
  <div class="screen">
    <div class="eyebrow">pop the balloons 🎈</div>
    <h1 style="font-size:28px">Pop them all!</h1>
    <p class="sub">Tap every balloon to reveal your birthday wishes.</p>
    <div class="balloons" id="balloons">
      <button class="balloon" aria-label="Pop pink balloon"></button>
      <button class="balloon" aria-label="Pop purple balloon"></button>
      <button class="balloon" aria-label="Pop teal balloon"></button>
      <button class="balloon" aria-label="Pop golden balloon"></button>
    </div>
    <div id="balloonMsg" class="sub">Your laugh is my favourite sound 💗</div>
    <button class="btn" data-next>Walk down memory lane →</button>
  </div>
</section>

<section class="stage" data-stage="5">
  <div class="screen">
    <div class="eyebrow">a walk down memory lane</div>
    <div class="memory-card">
      <div class="photo-placeholder" id="photoBox">
        <span id="photoEmoji">📸</span>
        <img id="photoImg" alt="Your memory photo">
      </div>
      <p id="photoCaption">Our favourite memory ♡</p>
    </div>
    <div class="photo-tools">
      <label class="btn ghost" for="photoUpload">Add a photo +</label>
      <input id="photoUpload" type="file" accept="image/*" hidden>
    </div>
    <p class="sub">Add a photo to make this little memory card yours. You can also leave the cute placeholder as it is.</p>
    <button class="btn" data-next>One last thing… 💌</button>
  </div>
</section>

<section class="stage" data-stage="6">
  <div class="screen">
    <div class="eyebrow">one last thing, Prachi…</div>
    <span class="envelope">💌</span>
    <div class="script">A little letter</div>
    <p class="sub">I wrote something just for you. Tap to open your letter.</p>
    <button class="btn" id="openLetter">Open my letter 💌</button>
    <div id="letter" class="letter" style="display:none;margin-top:15px"><strong>Dear Prachi,</strong><br><br>Happy Birthday! 🎂💖<br><br>I hope this new year of your life brings you countless reasons to smile, beautiful memories, and dreams that come true. Keep being your wonderful self, and never forget how special you are.<br><br>Wishing you happiness today and always. ✨<br><br><strong>With lots of good wishes,<br>Manglam ♡</strong></div>
    <button class="btn ghost" data-next>See your final surprise →</button>
  </div>
</section>

<section class="stage" data-stage="7">
  <div class="screen">
    <div class="eyebrow">made with love, just for you</div>
    <div class="final-flowers">🌸 ✨ 🌸</div>
    <h1>HAPPY<br>BIRTHDAY</h1>
    <div class="script">Prachi!</div>
    <div class="ring"><span>💗</span></div>
    <p class="sub">May all the good things find their way to you. Keep smiling, keep shining, and have the sweetest birthday ever!</p>
    <div class="line"></div>
    <p class="sub" style="color:#ffda91">With love & warm wishes — Manglam</p>
    <button class="btn" id="again">Replay the surprise ↻</button>
  </div>
</section>

<div id="modal">
  <div class="editor">
    <h2>Personalize your surprise 💗</h2>
    <label for="name">Recipient name</label>
    <input id="name" value="Prachi" maxlength="35">
    <label for="sender">Your name</label>
    <input id="sender" value="Manglam" maxlength="40">
    <label for="customNote">Birthday letter</label>
    <textarea id="customNote">Happy Birthday! 🎂💖

I hope this new year of your life brings you countless reasons to smile, beautiful memories, and dreams that come true. Keep being your wonderful self, and never forget how special you are.

Wishing you happiness today and always. ✨</textarea>
    <div class="actions">
      <button class="btn ghost" id="cancel">Cancel</button>
      <button class="btn" id="save">Save ✨</button>
    </div>
  </div>
</div>

<script>
const $ = id => document.getElementById(id);
const stages = [...document.querySelectorAll('.stage')];
let current = 0, popped = 0;

for (let i = 0; i < 90; i++) {
  let s = document.createElement('i');
  s.className = 'star';
  s.style.left = Math.random() * 100 + '%';
  s.style.top = Math.random() * 100 + '%';
  s.style.setProperty('--d', (1.4 + Math.random() * 3) + 's');
  $('stars').appendChild(s);
}

stages.forEach((_, i) => {
  let d = document.createElement('i');
  d.className = 'dot' + (i === 0 ? ' on' : '');
  $('progress').appendChild(d);
});

function show(n) {
  current = (n + stages.length) % stages.length;
  stages.forEach((s, i) => s.classList.toggle('active', i === current));
  [...$('progress').children].forEach((d, i) => d.classList.toggle('on', i === current));
  if (current === 1 || current === 7) confetti(current === 7 ? 85 : 45);
  if (current === 3) {
    $('flame').style.display = 'block';
    $('wish').textContent = 'Make a wish & blow 🕯️';
  }
}

function confetti(count = 55) {
  for (let i = 0; i < count; i++) {
    let e = document.createElement('span');
    e.className = 'spark';
    e.textContent = ['✦', '♥', '✧', '💗', '✨'][i % 5];
    e.style.left = Math.random() * 100 + '%';
    e.style.setProperty('--dur', (2.5 + Math.random() * 3) + 's');
    e.style.setProperty('--drift', (Math.random() * 180 - 90) + 'px');
    e.style.setProperty('--size', (10 + Math.random() * 15) + 'px');
    e.style.setProperty('--col', ['#ffd98e', '#ff8db8', '#fff0f5', '#c6a6ff'][i % 4]);
    document.body.appendChild(e);
    setTimeout(() => e.remove(), 6000);
  }
}

document.querySelectorAll('[data-next]').forEach(b =>
  b.addEventListener('click', () => show(current + 1))
);

$('wish').addEventListener('click', () => {
  $('flame').style.display = 'none';
  $('wish').textContent = 'Wish sent to the universe ✨';
  confetti(80);
});

$('balloons').querySelectorAll('.balloon').forEach((b, i) =>
  b.addEventListener('click', () => {
    if (!b.classList.contains('popped')) {
      b.classList.add('popped');
      popped++;
      confetti(12);
      $('balloonMsg').textContent = [
        'You deserve all the happiness 💗',
        'Keep shining, always ✨',
        'May your dreams come true 🌸',
        'Happy Birthday, Prachi! 🎂'
      ][i];
      if (popped === 4) {
        $('balloonMsg').textContent = 'You popped them all! Happy Birthday, Prachi! 🎉';
      }
    }
  })
);

$('openLetter').addEventListener('click', () => {
  $('letter').style.display = 'block';
  $('openLetter').textContent = 'A letter just for you 💖';
  confetti(25);
});

$('again').addEventListener('click', () => {
  popped = 0;
  $('balloons').querySelectorAll('.balloon').forEach(b => b.classList.remove('popped'));
  $('letter').style.display = 'none';
  $('openLetter').textContent = 'Open my letter 💌';
  show(0);
});

$('photoUpload').addEventListener('change', e => {
  const f = e.target.files && e.target.files[0];
  if (!f) return;
  const r = new FileReader();
  r.onload = () => {
    $('photoImg').src = r.result;
    $('photoImg').style.display = 'block';
    $('photoEmoji').style.display = 'none';
  };
  r.readAsDataURL(f);
});

$('modal').addEventListener('click', e => {
  if (e.target === $('modal')) $('modal').classList.remove('open');
});
$('cancel').addEventListener('click', () => $('modal').classList.remove('open'));

$('save').addEventListener('click', () => {
  const name = $('name').value.trim() || 'Prachi';
  const sender = $('sender').value.trim() || 'Manglam';

  document.querySelectorAll('.script').forEach(el => {
    if (el.textContent.includes('Prachi') || el.textContent === 'For Prachi') {
      el.textContent = el.textContent.includes('For') ? 'For ' + name : name + '!';
    }
  });

  const letter = $('letter');
  letter.innerHTML = '<strong>Dear ' + escapeHtml(name) + ',</strong><br><br>' +
    escapeHtml($('customNote').value).replace(/\n/g, '<br>') +
    '<br><br><strong>With lots of good wishes,<br>' + escapeHtml(sender) + ' ♡</strong>';

  document.querySelectorAll('.sub').forEach(el => {
    if (el.textContent.includes('With love & warm wishes')) {
      el.textContent = 'With love & warm wishes — ' + sender;
    }
  });

  $('modal').classList.remove('open');
});

function escapeHtml(s) {
  return s.replace(/[&<>"']/g, c => ({
    '&': '&amp;', '<': '&lt;', '>': '&gt;',
    '"': '&quot;', "'": '&#39;'
  }[c]));
}

const edit = document.createElement('button');
edit.className = 'edit';
edit.textContent = '✎ Personalize';
edit.addEventListener('click', () => $('modal').classList.add('open'));
document.body.appendChild(edit);
</script>
</body>
</html>
