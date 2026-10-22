<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#1a0507">
<title>محمد &amp; أسراء</title>
<link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Aref+Ruqaa:wght@400;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#1a0507;--bg2:#2a0b0f;--gold:#d8b46a;--gold2:#f2dca0;--text:#efe6d6;--mut:#b9ab94;color-scheme:dark;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:env(safe-area-inset-top,0px);height:100%}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;min-height:100%;background:var(--bg);color:var(--text);font-family:'Amiri',serif;overflow-x:hidden}
body.locked{overflow:hidden;height:100%}
.script{font-family:'Aref Ruqaa','Amiri',serif}
/* petals / sparkles */
#fx{position:fixed;inset:0;pointer-events:none;z-index:1}
/* cover */
#cover{position:fixed;inset:0;z-index:50;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;
background:radial-gradient(ellipse at 50% 35%,#2b2016 0%,#14100d 70%);transition:transform 1.4s cubic-bezier(.7,0,.2,1),opacity 1.2s;padding:24px}
#cover.open{transform:translateY(-100%);opacity:.2;pointer-events:none}
.frame{position:absolute;inset:max(14px,env(safe-area-inset-top,0px)) 14px max(14px,env(safe-area-inset-bottom,0px));border:1px solid rgba(216,180,106,.45);border-radius:6px}
.frame::after{content:"";position:absolute;inset:6px;border:1px solid rgba(216,180,106,.2)}
.kicker{letter-spacing:.25em;color:var(--gold);font-size:1.05rem;margin-bottom:18px;animation:fade 1.6s .2s both}
.names{font-size:clamp(3rem,15vw,5.2rem);line-height:1.15;margin:0;background:linear-gradient(120deg,#b8913f,#f6e3a8 40%,#b8913f 70%,#f6e3a8);-webkit-background-clip:text;background-clip:text;color:transparent;background-size:200% 100%;animation:shine 6s linear infinite,fade 1.6s .5s both}
.names small{display:block;font-size:.45em;color:var(--gold);-webkit-text-fill-color:var(--gold);margin:2px 0}
.seal{margin-top:40px;width:104px;height:104px;border-radius:50%;border:0;cursor:pointer;position:relative;color:#3b2606;font-size:2.1rem;font-family:'Aref Ruqaa',serif;
background:radial-gradient(circle at 35% 30%,#f6e3a8,#c79a45 55%,#8d6a26);box-shadow:0 0 0 6px rgba(216,180,106,.15),0 10px 30px rgba(0,0,0,.6),inset 0 -6px 12px rgba(0,0,0,.25);animation:pulse 2.4s ease-in-out infinite,fade 1.6s .9s both}
.seal::before{content:"";position:absolute;inset:9px;border-radius:50%;border:1px dashed rgba(59,38,6,.5)}
.hint{margin-top:22px;color:var(--mut);font-size:1.1rem;animation:fade 1.6s 1.3s both}
@keyframes fade{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}
@keyframes shine{to{background-position:-200% 0}}
@keyframes pulse{50%{transform:scale(1.07);box-shadow:0 0 0 14px rgba(216,180,106,.08),0 10px 30px rgba(0,0,0,.6),inset 0 -6px 12px rgba(0,0,0,.25)}}
/* main */
main{position:relative;z-index:2;max-width:560px;margin:0 auto;padding:0 20px 90px}
section{padding:54px 0;text-align:center}
