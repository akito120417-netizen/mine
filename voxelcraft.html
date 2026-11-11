<!DOCTYPE html>
<html lang="ja"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, viewport-fit=cover">
<title>Voxel Craft</title><link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
<style>
:root{--bg:#cfe8f7;--ink:#14202b;--panel:rgba(255,255,255,.82);--acc:#2b8a3e;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);color-scheme:light}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0b1118;--ink:#f1efe6;--panel:rgba(14,20,28,.8);--acc:#8ce99a;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0b1118;--ink:#f1efe6;--panel:rgba(14,20,28,.8);--acc:#8ce99a;color-scheme:dark}
html,body{height:100%;margin:0;overflow:hidden;background:var(--bg);color:var(--ink);font:14px/1.6 system-ui,-apple-system,"Hiragino Sans","Noto Sans JP",sans-serif}
canvas{position:fixed;inset:0;width:100%;height:100%;display:block;touch-action:none}
#hud{position:fixed;left:10px;top:calc(10px + env(safe-area-inset-top,0px));padding:3px 10px;border-radius:8px;background:var(--panel);font-size:12px;white-space:pre}
#cross{position:fixed;left:50%;top:50%;width:18px;height:18px;margin:-9px 0 0 -9px;pointer-events:none}
#cross:before,#cross:after{content:"";position:absolute;background:#fff;mix-blend-mode:difference}
#cross:before{left:8px;top:0;width:2px;height:18px}
#cross:after{top:8px;left:0;height:2px;width:18px}
#bar{position:fixed;left:50%;bottom:calc(14px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);display:flex;gap:0;padding:3px;background:#8b8b8b;border:3px solid #000;box-shadow:inset 2px 2px #c6c6c6,inset -2px -2px #555}
.s{width:min(42px,9.4vw);height:min(42px,9.4vw);border:3px solid #373737;position:relative;box-sizing:border-box}
.s.on{border-color:#fff;outline:2px solid #000;z-index:1}
.s i{position:absolute;left:2px;top:-1px;font:700 10px/14px system-ui;font-style:normal;color:#fff;text-shadow:0 0 3px #000}
[hidden]{display:none!important}
html,body,canvas,.sc,button{-webkit-user-select:none;user-select:none;-webkit-touch-callout:none;-webkit-tap-highlight-color:transparent}canvas{touch-action:none}#cmd{-webkit-user-select:text;user-select:text}
#cp{position:fixed;left:8px;right:8px;bottom:calc(172px + env(safe-area-inset-bottom,0px));display:none;flex-wrap:wrap;gap:6px;z-index:30}
#xp{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(62px + env(safe-area-inset-bottom,0px));width:min(360px,80vw);height:6px;background:rgba(0,0,0,.45);border:1px solid #000;display:none;z-index:6}#xp i{display:block;height:100%;width:0;background:#7ddc3a}#xp b{position:absolute;left:50%;top:-17px;transform:translateX(-50%);color:#7dff3a;font:700 13px system-ui;text-shadow:1px 1px #000}body.ng #xp{display:none!important}
#ms{position:fixed;left:8px;top:calc(8px + env(safe-area-inset-top,0px));color:#fff;font:13px system-ui;text-shadow:1px 1px #000;z-index:8;pointer-events:none;white-space:pre;background:rgba(0,0,0,.0)}#fl{position:fixed;inset:0;background:#fff;opacity:0;pointer-events:none;z-index:9;transition:opacity .12s}
#cmd{position:fixed;left:8px;right:8px;bottom:calc(130px + env(safe-area-inset-bottom,0px));display:none;z-index:30;font:14px system-ui;padding:6px 8px;background:rgba(0,0,0,.7);color:#fff;border:1px solid #888;outline:none}
#bb,#bp{display:none!important}#nm{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(108px + env(safe-area-inset-bottom,0px));color:#fff;font:700 14px system-ui;text-shadow:1px 1px #000;opacity:0;transition:opacity .4s;z-index:6;white-space:nowrap;pointer-events:none}body.ng #nm{display:none}
#tt{position:fixed;pointer-events:none;background:rgba(16,0,16,.92);border:2px solid #28007f;color:#fff;font:12px system-ui;padding:3px 6px;z-index:20;display:none}
#uwo{position:fixed;inset:0;pointer-events:none;opacity:0;transition:opacity .3s;z-index:3;background:radial-gradient(ellipse at 50% 30%,rgba(120,200,230,.16),rgba(8,60,100,.42))}body.ng #uwo{display:none}
#ip2{background:#c6c6c6;border:3px solid #000;box-shadow:inset 3px 3px #fff,inset -3px -3px #555;padding:12px;color:#404040;text-shadow:none;width:min(440px,94vw);max-height:80vh;overflow-y:auto;margin-bottom:20px}#ip2 h3{margin:0 0 8px}.rw{display:flex;align-items:center;gap:8px;padding:4px 0;border-bottom:1px solid #999;font-size:13px}.ri{width:32px;height:32px;flex:none;background:center/cover;image-rendering:pixelated}.rw .mb{width:auto;margin-left:auto;padding:0 12px;flex:none}
body.ng #st,body.ng #pg{display:none!important}#st{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(78px + env(safe-area-inset-bottom,0px));font:700 14px system-ui;letter-spacing:1px;text-shadow:1px 1px #000;white-space:nowrap;z-index:6}#pg{position:fixed;left:50%;top:calc(50% + 24px);width:60px;height:5px;transform:translateX(-50%);display:none;background:#0006;z-index:6}
.s b{position:absolute;right:2px;bottom:0;font-size:12px;color:#fff;text-shadow:1px 1px #000}.it{position:relative}.it::after{content:attr(data-n);position:absolute;right:2px;bottom:0;font-size:11px;color:#fff;text-shadow:1px 1px #000}
#bs{left:calc(150px + env(safe-area-inset-left,0px));right:auto;top:auto;bottom:calc(46px + env(safe-area-inset-bottom,0px));width:60px!important;height:60px!important}
body.fl{position:fixed;left:0;top:0;width:100vh;height:100vw;transform-origin:0 0;transform:translateX(100vw) rotate(90deg)}body.fl.fr{transform:translateY(100vh) rotate(-90deg)}
body.fl .mb{height:34px;line-height:30px;font-size:14px}body.fl .logo{margin-bottom:12px;font-size:clamp(22px,6vw,42px)}body.fl .sc h2,body.fl .sc h3{margin:0 0 4px}body.fl #ig{max-height:46vw;grid-template-columns:repeat(12,44px)}body.fl #ip{margin-bottom:54px;padding:8px}body.fl #ol{width:min(640px,90vh)}
#rot{position:fixed;inset:0;z-index:99;display:none;align-items:center;justify-content:center;background:#111;color:#fff;font:700 18px system-ui,sans-serif;text-align:center}
@media(max-height:480px){.mb{height:34px;line-height:30px;font-size:14px}.logo{margin-bottom:12px;font-size:clamp(22px,6vw,42px)}.sc h2,.sc h3{margin:0 0 4px}#ig{max-height:38vh}#ip{margin-bottom:54px;padding:8px}}body.ng #bar,body.ng #cross,body.ng #hud,body.ng #tc{display:none!important}
.sc{position:fixed;inset:0;display:none;flex-direction:column;align-items:center;justify-content:safe center;overflow-y:auto;gap:6px;font-weight:700;color:#fff;text-shadow:2px 2px #3f3f3f;z-index:5;user-select:none}
.sc h2,.sc h3,.sc p{margin:0 0 8px}.sc small{font-weight:400;font-size:12px}
.dk{background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),var(--dirt) 0 0/64px;image-rendering:pixelated}
#ti{background:radial-gradient(transparent 35%,rgba(0,0,0,.6))}#pa{background:rgba(0,0,0,.55)}#ld{z-index:9}
.mb{position:relative;display:block;width:min(400px,86vw);height:40px;box-sizing:border-box;padding:0;border:2px solid #000;background:#7d7d7d;box-shadow:inset -3px -4px #565656,inset 3px 3px #c6c6c6;color:#e8e8e8;font:700 15px/36px system-ui,"Hiragino Sans","Noto Sans JP",sans-serif;text-shadow:2px 2px #3f3f3f;text-align:center;cursor:pointer}
.mb:hover:not(:disabled){background:#6f7cab;color:#ffffa0;border-color:#fff}.mb:disabled{background:#6a6a6a;color:#a0a0a0;cursor:default}
.row{display:flex;gap:8px;width:min(400px,86vw)}.row .mb{width:50%}
.logo{position:relative;text-align:center;margin-bottom:30px;font:400 clamp(30px,8vw,60px)/1.2 'Press Start 2P',monospace;letter-spacing:.06em;color:#c5c5c5;text-shadow:-2px 0 #000,2px 0 #000,0 -2px #000,0 2px #000,3px 3px #555,4px 4px #555,5px 5px #333,6px 6px #333}
#sp{position:absolute;right:-60px;bottom:-12px;color:#ff0;font:700 16px system-ui,sans-serif;letter-spacing:0;text-shadow:2px 2px #3f3f00;white-space:nowrap;transform:rotate(-20deg);animation:pu .5s infinite alternate}@keyframes pu{to{scale:1.12}}
.f1{position:fixed;left:8px;bottom:6px}.f2{position:fixed;right:8px;bottom:6px}
#wl{width:min(400px,86vw);box-sizing:border-box;border:2px solid #fff;background:rgba(0,0,0,.5);padding:6px 10px;margin-bottom:10px}
#lw{width:min(300px,70vw);height:8px;background:#444;border:1px solid #000}#lb{height:100%;width:0;background:#7ddc5a}
#ol{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:6px 10px;width:min(640px,94vw);margin-bottom:12px}#ol .mb{width:100%}
.sl i{position:absolute;left:0;top:0;bottom:0;background:#3f4d8f;opacity:.75}.sl span{position:relative}.sl input{position:absolute;inset:0;width:100%;height:100%;margin:0;opacity:0;cursor:pointer}
#ct{margin:0 0 10px;font:400 12px/1.5 system-ui,"Noto Sans JP",sans-serif;text-align:left;background:rgba(0,0,0,.5);padding:6px 10px;max-width:94vw;white-space:pre-wrap}
#bi,#bz,#bs,#bc,#bv{z-index:7;top:calc(10px + env(safe-area-inset-top,0px));width:44px!important;height:44px!important}#bz{right:14px}#bi{right:66px}#bc{right:118px}#bv{right:170px}
#bar{z-index:6}.s{background-size:cover;image-rendering:pixelated}
#ip{background:#c6c6c6;border:3px solid #000;box-shadow:inset 3px 3px #fff,inset -3px -3px #555;padding:12px;color:#404040;text-shadow:none;max-width:94vw;margin-bottom:70px}#ip h3{margin:0 0 8px}
#ig{max-height:56vh;overflow-y:auto;display:grid;grid-template-columns:repeat(9,min(44px,9vw));gap:2px}.it{aspect-ratio:1;background:#8b8b8b center/cover;image-rendering:pixelated;border:2px solid;border-color:#373737 #fff #fff #373737;cursor:pointer}.it:hover{outline:3px solid #fff;z-index:1}#in{margin-top:6px;min-height:16px;font-size:13px}
#tc{display:none}.touch #tc{display:block}
#tc *{position:fixed;touch-action:none;user-select:none;-webkit-user-select:none}
#js{left:calc(18px + env(safe-area-inset-left,0px));bottom:calc(84px + env(safe-area-inset-bottom,0px));width:120px;height:120px;border-radius:50%;background:var(--panel)}
#kn{left:50%;top:50%;width:48px;height:48px;margin:-24px;border-radius:50%;background:var(--ink);opacity:.45;position:absolute!important}
#tc button{width:56px;height:56px;border-radius:50%;border:0;background:var(--panel);color:var(--ink);font-size:24px}
#bb{right:24px;bottom:100px}#bp{right:92px;bottom:100px}#bj{right:24px;bottom:166px}#bf{right:92px;bottom:166px}
</style></head><body>
<canvas id="c"></canvas><div id="cross"></div><div id="hud"></div><div id="bar"></div>
<div id="tc"><div id="js"><b id="kn"></b></div><button id="bj">⤒</button><button id="bb">⛏</button><button id="bp">▣</button><button id="bf">⇩</button><button id="bc">💬</button><button id="bv">👁</button><button id="bs">⚡</button><button id="bi">▦</button><button id="bz">Ⅱ</button></div>
<div id="uwo"></div><div id="nm"></div><div id="tt"></div><div id="ms"></div><div id="xp"><i></i><b>0</b></div><div id="fl"></div><div id="cp"></div><input id="cmd" autocomplete="off" placeholder="/time set day  /weather rain  /gamemode s  /give 11 64  /tp x y z"><div id="st"></div><div id="pg"></div>
<div id="rot">📱 画面を横向きにしてください</div><div id="ti" class="sc"><div class="logo">VOXEL<br>CRAFT<span id="sp"></span></div>
<button class="mb" id="b1">シングルプレイ</button><button class="mb" disabled>マルチプレイ</button>
<div class="row"><button class="mb" id="b2">設定...</button><button class="mb" id="b3">ゲームを終了</button></div>
<small class="f1">Voxel Craft 1.0</small><small class="f2">非公式ファンメイド作品</small></div>
<div id="ws" class="sc dk"><h2>ワールドを選択</h2><div id="wl"><b>新しいワールド</b><br><small id="wi"></small></div>
<button class="mb" id="wp">選択したワールドでプレイ</button><button class="mb" id="wn">新しいワールドを作成</button>
<div class="row"><button class="mb" id="wd">削除</button><button class="mb" id="wc">キャンセル</button></div></div>
<div id="ld" class="sc dk"><h3>ワールドを読み込み中</h3><div id="lw"><div id="lb"></div></div><p id="lt">地形を生成中 0%</p></div>
<div id="op" class="sc dk"><h2>設定</h2><div id="ol"></div><pre id="ct" hidden>WASD 移動 ／ マウス 視点
左クリック 壊す ／ 右クリック 置く
1〜9・ホイール ブロック選択
Space ジャンプ（2回押しで飛行）／ Shift / W2回押し ダッシュ・下降
E ブロック一覧 ／ F3 デバッグ表示 ／ N 新しい世界 ／ Esc 一時停止
スマホ: 左スティック移動 ／ 右画面ドラッグで視点 ／ Ⅱ 一時停止</pre><button class="mb" id="od">完了</button></div>
<div id="iv" class="sc"><div id="ip"><h3>ブロック</h3><div id="ig"></div><small id="in">&nbsp;</small><button class="mb" id="icr" style="margin-top:8px;width:100%">クラフト（2×2）</button><button class="mb" id="ic" style="margin-top:8px;width:100%">閉じる（Eキー）</button></div></div>
<div id="dt" class="sc" style="background:rgba(120,0,0,.55)"><h2>死にました！</h2><button class="mb" id="rs1">リスポーン</button></div>
<div id="cr" class="sc"><div id="ip2"><h3 id="crt"></h3><div id="crl"></div><button class="mb" id="crc" style="margin-top:8px;width:100%">閉じる</button></div></div>
<div id="pa" class="sc"><h2>ゲームメニュー</h2><button class="mb" id="p1">ゲームに戻る</button><button class="mb" id="p2">設定...</button><button class="mb" id="p4">ディメンション移動</button><button class="mb" id="p3">セーブしてタイトルへ</button></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>window.THREE||document.write('<script src="https://cdn.jsdelivr.net/npm/three@0.128.0/build/three.min.js"><\/script>')</script>
<script>if(!window.THREE)addEventListener('DOMContentLoaded',()=>{document.body.style.cssText='background:#111;color:#fff;font:16px sans-serif;padding:24px';document.body.textContent='3Dライブラリを読み込めませんでした。インターネット接続、広告ブロック、学校・会社のネットワーク制限を確認してください。'})</script>
<script>
const TOUCH=matchMedia('(pointer:coarse)').matches||'ontouchstart' in window,CS=16,H=248,SEA=126,D0=104,OF=40,REACH=6;let RD=TOUCH?5:9,SNv=1;
let seed=(Math.random()*1e9)|0,ed={},T=.08,saved=0,DIM=0;
const P={x:8.5,y:50,z:8.5};let yaw=0,pitch=0,vx=0,vy=0,vz=0,ground=0,fly=0;
try{const s=JSON.parse(localStorage.getItem('vc1')||'null');if(s&&s.v==3){seed=s.s;ed=s.e;T=s.t;Object.assign(P,s.p);yaw=s.y;pitch=s.q;DIM=s.d|0;saved=1}}catch(e){}
const hs=(x,y,z)=>{let h=Math.imul(x,374761393)^Math.imul(y,668265263)^Math.imul(z,1274126177)^seed;h=Math.imul(h^(h>>>13),1274126177);return((h^(h>>>16))>>>0)/4294967296};
function vn(x,z){const xi=Math.floor(x),zi=Math.floor(z),xf=x-xi,zf=z-zi,u=xf*xf*(3-2*xf),v=zf*zf*(3-2*zf),a=hs(xi,0,zi),b=hs(xi+1,0,zi),c=hs(xi,0,zi+1),d=hs(xi+1,0,zi+1);return a+(b-a)*u+(c-a)*v+(a-b-c+d)*u*v}
const fbm=(x,z)=>vn(x/64,z/64)*.55+vn(x/32,z/32)*.28+vn(x/16,z/16)*.12+vn(x/8,z/8)*.05;
const tw=(x0,z0)=>vn((x0+vn(x0/70+500,z0/70+500)*36-18)/600+50,(z0+vn(x0/70+900,z0/70-300)*36-18)/600+50),cnyc=(x,z)=>{const xw=x+(vn(x/45+6500,z/45)-.5)*26,zw=z+(vn(x/45+6700,z/45+9)-.5)*26;return[Math.abs(vn(xw/320+4000,zw/320+100)-.5)+(vn(x/11+1,z/11)-.5)*.004,.03*(.5+vn(x/70+9000,z/70)*1.1)]},mw=(x0,z0)=>{const x=x0+vn(x0/70+500,z0/70+500)*36-18,z=z0+vn(x0/70+900,z0/70-300)*36-18;return[vn(x/600+50,z/600+50),vn(x/600+300,z/600-200)]},th0=(x,z)=>Math.min(H-12,Math.floor(14+D0+Math.pow(fbm(x,z),2.2)*76+Math.max(0,vn(x/260+700,z/260)-.52)*140*(1-Math.abs(2*vn(x/70,z/70)-1)))),fbs=(x,z)=>(vn(x/64,z/64)*.55+vn(x/32,z/32)*.28)/.83,th=(x,z)=>{let h=th0(x,z);{const w=Math.max(0,1-Math.abs(h-SEA)/8);if(w>0){const hm=Math.floor(14+D0+Math.pow(fbs(x,z),2.2)*76);h=Math.floor(h*(1-w)+hm*w)}}const k=Math.max(0,Math.min(1,(vn(x/450+2000,z/450+900)-.5)*5));if(k)h=Math.floor(h*(1-k)+(SEA+4+vn(x/70,z/70)*4)*k);
let mzw=0;{const mq=mw(x,z),sm=v=>{v=Math.max(0,Math.min(1,v));return v*v*(3-2*v)};mzw=sm((mq[0]-.62)/.07)*sm((.46-mq[1])/.07);if(mzw>0){const n=vn(x/120+8300,z/120+8300)*.6+vn(x/52+8400,z/52)*.28+vn(x/22+8500,z/22)*.12,L=Math.floor(Math.max(0,Math.min(.999,(n-.32)/.36))*7),hm=SEA+3+L*8+Math.floor(vn(x/8+8600,z/8)*2);h=Math.floor(h*(1-mzw)+hm*mzw)}}
const q=cnyc(x,z),c=q[0],th2=q[1],xw=x+(vn(x/45+6500,z/45)-.5)*26,zw=z+(vn(x/45+6700,z/45+9)-.5)*26;
if(c<th2&&vn(x/600+8000,z/600)>.4){const d=Math.min(1,(th2-c)/(th2*.4))*Math.min(1,Math.max(0,(h-SEA)/2)),bd=SEA-4-Math.floor(vn(x/50+1,z/50)*10);h=Math.floor(h*(1-d)+bd*d)}
if(h>SEA&&vn(x/260+7000,z/260)>.5){const t0=tw(xw,zw),rv=Math.abs(t0-.6);if(rv<.07){const gr=(Math.abs(tw(xw+4,zw)-t0)+Math.abs(tw(xw,zw+4)-t0))/4+1e-4,ds=rv/gr,sl=vn(x/300+7300,z/300+40)>.5,wr=(sl?1.2+vn(x/40+7100,z/40)*1.6:2.2+vn(x/40+7100,z/40)*3)*(.75+.5*vn(x/7+7700,z/7)),wb=wr+7+vn(x/55+7400,z/55+3)*14;if(ds<wb){const gate=Math.max(0,Math.min(1,(SEA+16-h)/6))*(1-mzw);if(gate>0){if(ds<wr){const bed=SEA-1-(sl?0:1+Math.floor(vn(x/9+7500,z/9)*1.99));h=Math.floor(h*(1-gate)+bed*gate+.5)}else{let u=(ds-wr)/(wb-wr);u=Math.max(0,Math.min(1,u+(vn(x/12+7600,z/12+7)-.5)*.6));u=u*u*(3-2*u);const tg=SEA+1;if(h>tg){const nh=tg+(h-tg)*u;h=Math.floor(h*(1-gate)+nh*gate)}}}}}}if(h>SEA+1){const wq=Math.min(1,(h-SEA-1)/4)*(1-mzw*.92);h+=Math.round(((vn(x/17+3100,z/17+300)-.5)*4+(vn(x/41+3300,z/41+500)-.5)*7+(vn(x/90+3500,z/90+700)-.5)*8)*wq)}return h};
const OP=b=>b&&b!=6&&b!=7&&b!=9&&(b<29||b>=56)&&!((b>65&&b<71)||b==203)&&!(b>163&&b<167)&&!(b>=177&&b<=192),NS=b=>b==32||b==33||b==34||b==35||b==36||(b>51&&b<56)||(b>163&&b<167),SOL=b=>b&&b!=7&&!NS(b);
const ch=new Map(),meshes=new Map(),ck=(x,z)=>(x+32768)*65536+(z+32768)+DIM*4294967296;
const bm0=(x0,z0)=>{const x=x0+vn(x0/70+500,z0/70+500)*36-18,z=z0+vn(x0/70+900,z0/70-300)*36-18,t=vn(x/600+50,z/600+50),m=vn(x/600+300,z/600-200);if(vn(x/450+2000,z/450+900)>.58&&t>.32&&t<.62)return 1;if(t>.6){if(t>.66&&m<.42)return 9;return m<.32?2:m<.57?6:5}if(t<.28)return 7;return m>.68?8:m>.56?4:1},BN=['','平原','砂漠','雪原','森','ジャングル','サバンナ','タイガ','湿地','メサ','シラカバの森','ダークフォレスト','花の平原','キノコ島','氷樹の平原','サクラの林','タケの林'],DN=['オーバーワールド','ネザー','ジ・エンド','シフト'];
const bm=(x,z)=>{const b=bm0(x,z),v=vn(x/160+1500,z/160+200),mz=vn(x/260+700,z/260),hot=b==2||b==9||b==5||b==6;if(mz>.5&&!hot){const hh=th(x,z);if(hh>=SEA+34)return v>.7?14:3;if(hh>=SEA+18)return 7}if(b==4)return v>.66?10:v<.3?11:4;if(b==1){if(vn(x/400+3000,z/400+100)>.8)return 13;return v>.7?12:v<.16?15:1}if(b==5&&v>.6)return 16;return b};
/*VIL-BEGIN*/
const VR=176,VLC=new Map();
const vrn=(a,b,k)=>{let s=(hs(a,77+k,b)*4294967296)>>>0;return()=>{s=(s+1831565813)>>>0;let t=s;t=Math.imul(t^t>>>15,t|1);t^=t+Math.imul(t^t>>>7,t|61);return((t^t>>>14)>>>0)/4294967296}};
const vsty=bi=>bi==2?{top:4,f:1,w:[[12,80,0],[12,110,0],[110,80,0]],fd:12,fl:12,ro:[4,12,14,12]}
:bi==9?{top:102,f:1,w:[[27,110,0],[110,27,0],[12,110,0]],fd:110,fl:110,ro:[102,110,100,27]}
:(bi==3||bi==7||bi==14)?{top:13,w:[[61,57,40],[61,57,44],[19,57,44],[8,57,40]],fd:11,fl:61,ro:[14,11,100,14]}
:bi==6?{top:1,w:[[64,59,40],[64,5,40],[62,59,40]],fd:11,fl:64,ro:[100,14,100,11]}
:bi==5?{top:1,w:[[63,58,40],[8,58,40]],fd:11,fl:63,ro:[100,14,11,100]}
:bi==11?{top:1,w:[[65,60,40],[65,60,44],[61,60,40]],fd:11,fl:65,ro:[14,11,100,14]}
:bi==15?{top:1,w:[[205,204,40],[8,204,40],[62,204,40]],fd:11,fl:205,ro:[14,11,100,14]}
:bi==8?{top:1,w:[[61,57,40],[65,60,40]],fd:11,fl:61,ro:[100,14,11,100]}
:{top:1,w:[[8,5,40],[8,5,40],[62,56,40],[19,5,44],[10,5,44],[8,5,40]],fd:11,fl:8,ro:[100,14,11,100,14]};
const vmed=a=>{a.sort((x,y)=>x-y);return a[a.length>>1]};
function vlay(a,b){const key=seed+':'+a+':'+b;if(VLC.has(key))return VLC.get(key);let v=null;const R=vrn(a,b,0);
if(R()>.25){const ham=R()<.28;for(let tr=0;tr<8&&!v;tr++){const cx=a*VR+((.3+R()*.4)*VR|0),cz=b*VR+((.3+R()*.4)*VR|0);v=vbuild(cx,cz,R,ham)}}
VLC.set(key,v);return v}
function vbuild(cx,cz,R,ham){const bi=bm(cx,cz);if(bi==13||bi==16)return null;const g0=th(cx,cz);if(g0<=SEA+2)return null;
let wet=0,lo=1e9,hi=-1;for(let i=-22;i<=22;i+=8)for(let j=-22;j<=22;j+=8){const q=th(cx+i,cz+j);if(q<=SEA+1)wet++;if(q<lo)lo=q;if(q>hi)hi=q}
if(wet>3||hi-lo>(ham?12:18))return null;
const st=vsty(bi),bl=[],rd=[],pr=[],rc=[],stub=[];
const terr=(x0,z0,x1,z1,md)=>{const hs2=[];for(let x=x0;x<=x1;x+=2)for(let z=z0;z<=z1;z+=2){hs2.push(th(x,z))}for(const[x,z]of[[x0,z1],[x1,z0],[x1,z1]])hs2.push(th(x,z));let l=1e9,h=-1;for(const q of hs2){if(q<l)l=q;if(q>h)h=q}if(l<=SEA+1||h-l>md)return 0;return vmed(hs2)};
const free=(x0,z0,x1,z1)=>!rc.some(r=>x0<=r[2]&&x1>=r[0]&&z0<=r[3]&&z1>=r[1]);
const DIM_={house:[7,7,1],inn:[11,9,2],smith:[9,7,1],church:[9,14,1],market:[7,4,1],farm:[9,11,1],mill:[13,8,1]},HH={house:16,inn:17,smith:13,church:22,market:6,farm:5,mill:15,plaza:8};
const add=(t,x0,z0,W,D,r,md,extra)=>{const ww=r&1?D:W,dd=r&1?W:D,x1=x0+ww-1,z1=z0+dd-1;if(!free(x0-1,z0-1,x1+1,z1+1))return null;const gh=terr(x0-1,z0-1,x1+1,z1+1,md);if(!gh)return null;
const m=st.w[R()*st.w.length|0],b=Object.assign({t,x:x0,z:z0,W,D,r,gh,m,st,F:1,x1,z1,hh:HH[t]||10,tw:R()},extra||{});bl.push(b);rc.push([x0-1,z0-1,x1+1,z1+1]);return b};
if(ham){const b=add('house',cx-4,cz-4,7,7,0,5,{F:1});if(!b)return null;stub.push([cx-1,cz+4]);rd.push([cx-1,cz+3,cx-1,cz+4]);
if(R()<.7)add('farm',cx+6,cz-6,9,11,0,5);if(R()<.4)add('market',cx-12,cz-2,7,4,1,5);pr.push([cx-6,cz+4,'lamp'],[cx+3,cz+5,'lamp']);
return vfin(bl,rd,pr,stub,cx,cz,st)}
const pg=terr(cx-7,cz-7,cx+7,cz+7,6);if(!pg)return null;
bl.push({t:'plaza',x:cx-6,z:cz-6,W:13,D:13,r:0,gh:pg,m:st.w[0],st,F:1,x1:cx+6,z1:cz+6,hh:8,tw:R()});rc.push([cx-7,cz-7,cx+7,cz+7]);
const arms=[];for(const[dx,dz]of[[1,0],[-1,0],[0,1],[0,-1]]){let L=0,pv=pg;for(let s=8;s<=38;s++){const x=cx+dx*s,z=cz+dz*s,q=th(x,z);if(q<=SEA+1||Math.abs(q-pv)>3||bm(x,z)==13)break;pv=q;L=s}if(L>=20)arms.push({dx,dz,L})}
if(arms.length<2)return null;
const used={church:0,smith:0,market:0,inn:0,mill:0};
arms.forEach(A=>{const{dx,dz,L}=A;rd.push(dx?[dx>0?cx+7:cx-L,cz-1,dx>0?cx+L:cx-7,cz+1]:[cx-1,dz>0?cz+7:cz-L,cx+1,dz>0?cz+L:cz-7]);rc.push(dx?[dx>0?cx+7:cx-L,cz-1,dx>0?cx+L:cx-7,cz+1]:[cx-1,dz>0?cz+7:cz-L,cx+1,dz>0?cz+L:cz-7])});
arms.forEach(A=>{const{dx,dz,L}=A;for(const sd of[-1,1]){let s=8+(R()*3|0);while(s<L-4){
let t='house';const q=R();if(!used.church&&s<30&&q<.4)t='church';else if(!used.smith&&s<34&&q<.3)t='smith';else if(used.market<2&&s<26&&q<.28)t='market';else if(used.inn<2&&q<.2)t='inn';else if(s>L-16&&q<.6)t='farm';
let[W,D,F]=DIM_[t];if(t=='house'){W=R()<.5?7:9;D=R()<.5?7:9;F=W==9&&D==9&&R()<.4?2:1}
let x0,z0,r;if(dx){x0=dx>0?cx+s:cx-s-W+1;if(sd<0){z0=cz-3-D+1;r=0}else{z0=cz+3;r=2}}else{z0=dz>0?cz+s:cz-s-W+1;if(sd<0){x0=cx-3-D+1;r=3}else{x0=cx+3;r=1}}
const b=add(t,x0,z0,W,D,r,t=='farm'?4:6,{F});
if(b){if(t in used)used[t]++;const dxw=dx?x0+(W>>1):(sd<0?x0+D:x0-1),dzw=dx?(sd<0?z0+D:z0-1):z0+(W>>1);stub.push([dxw,dzw]);rd.push([dxw,dzw,dxw,dzw]);s+=W+1+(R()*3|0)}else s+=3}}});
// windmill at the tip of a random arm
{const A=arms[R()*arms.length|0],{dx,dz,L}=A;let x0,z0,r;if(dx>0){x0=cx+L+2;z0=cz-6;r=1}else if(dx<0){x0=cx-L-2-7;z0=cz-6;r=3}else if(dz>0){z0=cz+L+2;x0=cx-6;r=2}else{z0=cz-L-2-7;x0=cx-6;r=0}
const b=add('mill',x0,z0,13,8,r,5);if(b){const[ex,ez]=dx>0?[x0-1,cz]:dx<0?[x0+7+1,cz]:dz>0?[cx,z0-1]:[cx,z0+8];if(dx>0)rd.push([cx+L+1,cz-1,x0-1,cz+1]);else if(dx<0)rd.push([x0+8,cz-1,cx-L-1,cz+1]);else if(dz>0)rd.push([cx-1,cz+L+1,cx+1,z0-1]);else rd.push([cx-1,z0+8,cx+1,cz-L-1])}}
// lamps along the roads
arms.forEach(A=>{const{dx,dz,L}=A;let k=0;for(let s=11;s<L-2;s+=9,k++){const sd=k&1?1:-1,x=dx?cx+dx*s:cx+sd*2,z=dx?cz+sd*2:cz+dz*s;if(!stub.some(p=>Math.abs(p[0]-x)<2&&Math.abs(p[1]-z)<2))pr.push([x,z,'lamp'])}});
for(const[x,z]of[[-5,-5],[5,-5],[-5,5],[5,5]])pr.push([cx+x,cz+z,'lamp']);
return vfin(bl,rd,pr,stub,cx,cz,st)}
function vfin(bl,rd,pr,stub,cx,cz,st){let x0=1e9,z0=1e9,x1=-1e9,z1=-1e9;const ex=(a,b,c,d)=>{x0=Math.min(x0,a);z0=Math.min(z0,b);x1=Math.max(x1,c);z1=Math.max(z1,d)};
bl.forEach(b=>ex(b.x-2,b.z-2,b.x1+2,b.z1+2));rd.forEach(r=>ex(r[0],r[1],r[2],r[3]));return{bl,rd,pr,st,cx,cz,bb:[x0,z0,x1,z1]}}
const vgh=(v,x,z)=>{for(const b of v.bl)if(x>=b.x-1&&x<=b.x1+1&&z>=b.z-1&&z<=b.z1+1)return b.gh;return th(x,z)};
const vroof=(P,i0,j0,i1,j1,y0,ax,rf,fm)=>{const lo=ax?i0:j0,hi=ax?i1:j1,A0=ax?j0:i0,A1=ax?j1:i1,dL=ax?1:2,dH=ax?3:0;
for(let l=0;;l++){const a=lo-1+l,b=hi+1-l;if(a>b)break;const y=y0+l;
for(let t=A0-1;t<=A1+1;t++){if(a<b){if(ax){P.d(a,y,t,rf,dL);P.d(b,y,t,rf,dH)}else{P.d(t,y,a,rf,dL);P.d(t,y,b,rf,dH)}}else{if(ax)P.p(a,y,t,fm);else P.p(t,y,a,fm)}}
for(let u=a+1;u<b;u++){if(ax){P.p(u,y,A0,fm);P.p(u,y,A1,fm)}else{P.p(A0,y,u,fm);P.p(A1,y,u,fm)}}}};
const vpyr=(P,ci,cj,y0,n,rf,cap)=>{for(let l=0;l<n;l++){const h=n-1-l,y=y0+l;if(h==0){P.p(ci,y,cj,cap);continue}for(let i=-h;i<=h;i++)for(let j=-h;j<=h;j++){if(Math.abs(i)!=h&&Math.abs(j)!=h)continue;P.d(ci+i,y,cj+j,rf,j==-h?2:j==h?0:i==-h?1:3)}}};
const VB={
house(P,b){const{W,D,F,m,st}=b,[wl,lg,rf]=m,hg=4*F,di=W>>1,flat=!rf,jm=D>>1;
P.box(0,0,0,W-1,0,D-1,st.fl);
for(let i=0;i<W;i++)for(let j=0;j<D;j++){if(i&&j&&i<W-1&&j<D-1)continue;const cn=(i==0||i==W-1)&&(j==0||j==D-1);for(let y=1;y<=hg;y++)P.p(i,y,j,cn||y%4==0?lg:wl)}
for(let s=0;s<F;s++)for(let k=0;k<2;k++){const y=2+4*s+k;for(const i of[di-2,di+2]){P.p(i,y,0,9);P.p(i,y,D-1,9)}if(s)P.p(di,y,D-1,9);P.p(di,y,0,9);P.p(0,y,jm,9);P.p(W-1,y,jm,9)}
P.d(di,1,D-1,48,2);P.d(di,2,D-1,48,2);
if(flat){P.box(0,hg+1,0,W-1,hg+1,D-1,st.fd);for(let i=0;i<W;i++)for(let j=0;j<D;j++)if(!i||!j||i==W-1||j==D-1)P.p(i,hg+2,j,30)}else vroof(P,0,0,W-1,D-1,hg+1,0,rf,wl);
P.p(1,1,1,31);P.p(W-2,1,D-2,31);P.p(1,1,D-2,92);P.p(1,2,D-2,92);P.p(2,1,D-2,92);P.p(W-2,1,1,95);
if(!flat)for(let y=2;y<=hg+4;y++)P.p(W-2,y,1,11);
P.p(di,1,jm,29);P.p(di,2,jm,33);P.d(di-1,1,jm,40,3);P.d(di+1,1,jm,40,1);P.p(2,1,1,94);P.p(W-3,1,D-2,33);
if(F==2){const a=D-2;for(let i=1;i<W-1;i++)for(let j=1;j<D-1;j++){if(i==1&&j>=a-3)continue;P.p(i,4,j,st.fl)}
P.d(1,1,a,40,0);P.d(1,2,a-1,40,0);P.d(1,3,a-2,40,0);P.d(1,4,a-3,40,0);
P.p(W-2,5,1,31);P.p(W-3,5,1,31);P.p(2,5,1,92);P.p(2,6,1,92);P.p(3,5,1,92);P.p(di,5,jm,29);P.p(di,6,jm,33);P.d(di-1,5,jm,40,3);P.d(di+1,5,jm,40,1);P.p(W-2,5,D-2,33)}
P.p(di-2,1,-1,34);P.p(di+2,1,-1,35);P.p(di-2,1,D,35);P.p(di+2,1,D,34)},
smith(P,b){const{W,D,m,st}=b,rf=44;P.box(0,0,0,W-1,0,D-1,11);
for(let i=0;i<W;i++)for(let y=1;y<=4;y++)P.p(i,y,0,11);
for(let j=1;j<=3;j++)for(let y=1;y<=3;y++){P.p(0,y,j,11);P.p(W-1,y,j,11)}
for(const i of[0,W-1])for(let y=1;y<=4;y++){P.p(i,y,D-1,m[1]);P.p(i,y,4,m[1])}
vroof(P,0,0,W-1,D-1,5,0,rf,11);
P.p(2,1,1,95);P.p(4,1,1,95);P.p(6,1,1,95);for(let y=2;y<=9;y++){P.p(2,y,1,11);P.p(6,y,1,11)}
P.p(7,1,3,86);P.p(7,2,3,33);P.p(1,0,4,7);P.p(1,0,5,7);P.p(4,0,3,107);P.p(7,1,5,106);P.p(7,2,5,106);P.p(1,1,D-2,33);P.p(W-2,1,D-2,33);P.p(4,1,5,33)},
market(P,b){const{W,D,tw}=b;P.box(0,0,0,W-1,0,D-1,8);
for(const[i,j]of[[0,0],[W-1,0],[0,D-1],[W-1,D-1]])for(let y=1;y<=3;y++)P.p(i,y,j,5);
for(let i=-1;i<=W;i++)for(let j=-1;j<=D;j++)P.p(i,4,j,((i+(tw>.5?1:0))&1)?20:112);
const G=[96,97,106,34,35,96];for(let i=1;i<W-1;i++){P.p(i,1,1,29);P.p(i,2,1,G[((i+tw*9)|0)%G.length]);}
P.p(1,1,D-1,106);P.p(W-2,1,D-1,106);P.p(1,2,D-1,96);P.p(W-2,1,0,97);P.p(0,3,D-1,33)},
farm(P,b){const{W,D,tw}=b;
for(let i=0;i<W;i++)for(let j=0;j<D;j++){const e=i==0||j==0||i==W-1||j==D-1;if(e){if(!(j==D-1&&i==W>>1))P.p(i,1,j,29);continue}P.p(i,0,j,2);if(i==4){P.p(i,0,j,7);continue}
const k=Math.abs(i-4);P.p(i,1,j,k==3?(j&1?96:97):k==2?((j+i)%3?36:35):((i+j)&1?35:34))}
P.p(4,0,5,2);P.p(4,1,5,5);P.p(4,2,5,106);P.p(4,3,5,96);
for(const[i,j]of[[0,0],[W-1,0],[0,D-1],[W-1,D-1]]){P.p(i,1,j,5);P.p(i,2,j,5);P.p(i,3,j,33)}},
mill(P,b){const{m,st}=b,ci=6,cj=4,wl=m[0];for(let i=3;i<=9;i++)for(let j=1;j<=7;j++){const d=Math.hypot(i-ci,j-cj);if(d>3.45)continue;P.p(i,0,j,st.fl);if(d<=2.45)continue;for(let y=1;y<=9;y++)P.p(i,y,j,y<=3?11:y==9?m[1]:wl)}
P.d(ci,1,7,48,2);P.d(ci,2,7,48,2);for(const i of[3,9])for(let y=4;y<=5;y++)P.p(i,y,cj,9);P.p(ci,5,7,9);
vpyr(P,ci,cj,10,4,40,wl);P.p(ci,14,cj,33);
for(let t=1;t<=6;t++){P.p(ci+t,7,0,5);P.p(ci-t,7,0,5);P.p(ci,7+t,0,5);P.p(ci,7-t,0,5);if(t>1){P.p(ci+t,8,0,8);P.p(ci-1,7+t,0,8);P.p(ci-t,6,0,8);P.p(ci+1,7-t,0,8)}}P.p(ci,7,0,60);
P.p(ci,1,cj,94);P.p(ci-1,1,cj+1,106);P.p(ci+1,1,cj-1,33)},
church(P,b){const C=11,S=19;P.box(0,0,0,8,0,13,76);for(let j=2;j<=9;j++)P.p(4,0,j,20);
for(let i=0;i<=8;i++)for(let j=0;j<=10;j++){const edge=i==0||i==8||j==0||j==10;if(!edge)continue;for(let y=1;y<=7;y++){let v=S;if((i==0||i==8)&&j%3==0)v=C;else if((i==0||i==8)&&y>=3&&y<=6&&j>0&&j<10)v=177+[4,11,14,3][(j/3|0)%4];else if(j==0&&y>=3&&y<=6&&i>=3&&i<=5)v=191;P.p(i,y,j,v)}}
for(let i=3;i<=5;i++)for(let y=1;y<=3;y++)P.p(i,y,10,0);
vroof(P,0,0,8,10,8,1,44,S);
for(let i=2;i<=6;i++)for(let j=10;j<=14;j++){const e=i==2||i==6||j==10||j==14;for(let y=1;y<=16;y++){if(!e){continue}let v=y%8==0?C:S;if(y>=13&&y<=15&&((i==4&&(j==10||j==14))||(j==12&&(i==2||i==6))))v=0;P.p(i,y,j,v)}}
for(let i=3;i<=5;i++)for(let j=11;j<=13;j++)P.p(i,0,j,76);
P.d(4,1,14,48,2);P.d(4,2,14,48,2);for(let i=3;i<=5;i++)for(let y=1;y<=3;y++)P.p(i,y,10,0);
vpyr(P,4,12,17,4,44,C);P.p(4,21,12,25);P.p(4,14,12,25);P.p(4,1,12,33);
P.p(4,1,1,80);P.p(4,2,1,25);P.p(3,1,1,33);P.p(5,1,1,33);for(const j of[3,5,7])for(const i of[2,3,5,6])P.p(i,1,j,29);P.p(1,1,9,33);P.p(7,1,9,33)},
plaza(P,b){const{st}=b;for(let i=0;i<13;i++)for(let j=0;j<13;j++){const d=Math.max(Math.abs(i-6),Math.abs(j-6));P.p(i,0,j,d>=6?st.ro[0]:d==5?11:((i+j)&1?19:st.fd))}
for(let i=5;i<=7;i++)for(let j=5;j<=7;j++)if(i!=6||j!=6)P.p(i,1,j,11);
P.p(6,0,6,7);P.p(6,-1,6,7);P.p(6,-2,6,11);
for(const[i,j]of[[5,5],[7,5],[5,7],[7,7]]){P.p(i,2,j,5);P.p(i,3,j,5)}
for(let i=4;i<=8;i++)for(let j=4;j<=8;j++)P.p(i,4,j,29);P.p(6,5,6,33);
P.d(3,1,6,40,3);P.d(9,1,6,40,1);P.d(6,1,3,40,0);P.d(6,1,9,40,2)}};
function vdraw(v,c,X0,Z0){const X1=X0+15,Z1=Z0+15;
for(const b of v.bl){const px0=b.x-1,pz0=b.z-1,px1=b.x1+1,pz1=b.z1+1;if(px0>X1||px1<X0||pz0>Z1||pz1<Z0)continue;
const gh=b.gh,st=b.st;
for(let x=Math.max(px0,X0);x<=Math.min(px1,X1);x++)for(let z=Math.max(pz0,Z0);z<=Math.min(pz1,Z1);z++){const h=th(x,z),inf=x>=b.x&&x<=b.x1&&z>=b.z&&z<=b.z1,i=x-X0,j=z-Z0;
if(h<gh)for(let y=h+1;y<gh;y++)c[i+16*(j+16*y)]=inf?st.fd:2;
c[i+16*(j+16*gh)]=inf&&b.t!='farm'&&b.t!='mill'?st.fd:st.top;const top=Math.min(H-1,Math.max(gh+b.hh,h));for(let y=gh+1;y<=top;y++)c[i+16*(j+16*y)]=0}
const r=b.r,W=b.W,D=b.D,P={p(i,y,j,v2){let wx,wz;if(r==0){wx=i;wz=j}else if(r==1){wx=D-1-j;wz=i}else if(r==2){wx=W-1-i;wz=D-1-j}else{wx=j;wz=W-1-i}const X=b.x+wx-X0,Z=b.z+wz-Z0;if(X<0||X>15||Z<0||Z>15)return;const Y=gh+y;if(Y<0||Y>=H)return;c[X+16*(Z+16*Y)]=v2},
d(i,y,j,base,dd){P.p(i,y,j,base+((dd+r)&3))},box(i0,y0,j0,i1,y1,j1,v2){for(let y=y0;y<=y1;y++)for(let i=i0;i<=i1;i++)for(let j=j0;j<=j1;j++)P.p(i,y,j,v2)}};
const f=VB[b.t]||(b.t=='inn'?VB.house:0);if(f)f(P,b)}
for(const r of v.rd){const x0=Math.max(r[0],X0),x1=Math.min(r[2],X1),z0=Math.max(r[1],Z0),z1=Math.min(r[3],Z1);for(let x=x0;x<=x1;x++)for(let z=z0;z<=z1;z++){const y=vgh(v,x,z);if(y<=SEA||y+4>=H)continue;const i=x-X0,j=z-Z0,ro=v.st.ro;c[i+16*(j+16*y)]=ro[(hs(x,5,z)*ro.length)|0];for(let k=1;k<=3;k++)c[i+16*(j+16*(y+k))]=0}}
for(const[x,z,k]of v.pr){if(x<X0||x>X1||z<Z0||z>Z1)continue;const y=vgh(v,x,z);if(y<=SEA)continue;const i=x-X0,j=z-Z0;for(let t=1;t<=3;t++)c[i+16*(j+16*(y+t))]=5;c[i+16*(j+16*(y+4))]=33}}
function vApply(cx,cz,c){const X0=cx*CS,Z0=cz*CS,X1=X0+15,Z1=Z0+15;
for(let a=Math.floor((X0-80)/VR);a<=Math.floor((X1+80)/VR);a++)for(let b=Math.floor((Z0-80)/VR);b<=Math.floor((Z1+80)/VR);b++){const v=vlay(a,b);if(!v||v.bb[0]>X1||v.bb[2]<X0||v.bb[1]>Z1||v.bb[3]<Z0)continue;vdraw(v,c,X0,Z0)}}
const vNear=(x,z)=>{for(let a=Math.floor((x-90)/VR);a<=Math.floor((x+90)/VR);a++)for(let b=Math.floor((z-90)/VR);b<=Math.floor((z+90)/VR);b++){const v=vlay(a,b);if(v&&x>=v.bb[0]-14&&x<=v.bb[2]+14&&z>=v.bb[1]-14&&z<=v.bb[3]+14)return true}return false};
/*VIL-END*/
function structs(cx,cz,c){const X0=cx*CS,Z0=cz*CS;
for(let a=Math.floor((X0-48)/64);a<=Math.floor((X0+16)/64);a++)for(let b=Math.floor((Z0-48)/64);b<=Math.floor((Z0+16)/64);b++){
if(hs(a,3,b)>.5)continue;
const sx=a*64+4+(hs(a,4,b)*14|0),sz=b*64+4+(hs(a,5,b)*14|0),bi=bm(sx+7,sz+7),k=hs(a,6,b),
kind=bi==2?(k<.5?'p':'v'):bi==9?'p':bi==5?'j':bi==3||bi==14?(k<.6?'i':'t'):bi==7?(k<.5?'v':'t'):bi==8?(k<.5?'h':'t'):k<.45?'v':k<.65?'h':k<.8?'t':'r';
if(bi==13||kind=='v'||kind=='h'||vNear(sx+7,sz+7))continue;
(kind=='v'?[['h',0,0],['h',20,0],['h',0,20],['t',20,20],['w',15,15]]:[[kind,0,0]]).forEach(([ty,ox,oz])=>{
const wx=sx+ox,wz=sz+oz,n=ty=='w'?5:15,gh=Math.max(th(wx+(n>>1),wz+(n>>1)),SEA+1),
put=(i,y,j,v)=>{const x=wx+i-X0,z=wz+j-Z0;if(x>=0&&x<16&&z>=0&&z<16&&y>=0&&y<H)c[x+16*(z+16*y)]=v},
wm=bi==2?12:bi==7||bi==3?61:8,rm=bi==2?12:bi==7||bi==3?61:10;
let lo=999,hi=-1;const sp2=Math.max(2,n>>2);for(let i=0;i<=n;i+=sp2)for(let j=0;j<=n;j+=sp2){const q=th(wx+Math.min(i,n-1),wz+Math.min(j,n-1));lo=Math.min(lo,q);hi=Math.max(hi,q)}
if(hi-lo>5||lo<=SEA)return;
for(let i=0;i<n;i++)for(let j=0;j<n;j++){for(let y=gh-6;y<=gh;y++)put(i,y,j,y<gh?(bi==2?4:2):(bi==2||bi==9?4:bi==3?13:1));for(let y=gh+1;y<gh+17;y++)put(i,y,j,0)}
if(ty=='p'||ty=='j'){const m=ty=='j'?75:12;for(let l=0;l<8;l++){const r=7-l;for(let i=-r;i<=r;i++)for(let j=-r;j<=r;j++){const e=Math.abs(i)==r||Math.abs(j)==r;put(7+i,gh+1+l,7+j,e||l>3||Math.abs(i)>2||Math.abs(j)>2?m:0)}}
for(let i=3;i<=7;i++){put(7+i,gh+1,7,0);put(7+i,gh+2,7,0)}put(7,gh+1,7,25);put(8,gh+1,7,26);put(6,gh+1,6,33)}
else if(ty=='h'){for(let i=4;i<=10;i++)for(let j=4;j<=10;j++){const w=i==4||i==10||j==4||j==10,cn=(i==4||i==10)&&(j==4||j==10);put(i,gh,j,11);
for(let y=1;y<=4;y++)put(i,gh+y,j,!w?0:cn?5:(y==2||y==3)&&((j==4&&i==7)||((i==4||i==10)&&j==7))?9:wm);put(i,gh+5,j,wm)}
for(let i=3;i<=11;i++)for(let j=3;j<=11;j++)put(i,gh+6,j,rm);
put(7,gh+1,10,50);put(7,gh+2,10,50);put(7,gh+4,7,21);put(5,gh+1,9,33);put(9,gh+1,9,33);put(6,gh+1,6,20);put(8,gh+1,6,20)}
else if(ty=='t'){const R=[[6,6],[7,6],[8,6],[8,7],[8,8],[7,8],[6,8],[6,7]];
for(let i=5;i<=9;i++)for(let j=5;j<=9;j++){const w=i==5||i==9||j==5||j==9;
for(let y=1;y<=14;y++)put(i,gh+y,j,y==13?((i==8&&(j==7||j==8))?0:19):w?(y==14?((i+j)&1?19:0):19):0)}
for(let y=1;y<=12;y++)put(R[(y-1)%8][0],gh+y,R[(y-1)%8][1],11);
put(7,gh+1,9,50);put(7,gh+2,9,50);put(6,gh+1,5,33);put(5,gh+3,7,9);put(9,gh+8,7,9);put(7,gh+14,7,25)}
else if(ty=='w'){for(let i=0;i<5;i++)for(let j=0;j<5;j++){const e=i==0||i==4||j==0||j==4;put(i,gh,j,e?11:7);put(i,gh+1,j,e?11:0);if(i%4==0&&j%4==0)for(let y=2;y<=4;y++)put(i,gh+y,j,5);put(i,gh+5,j,8)}}
else if(ty=='i'){for(let i=-4;i<=4;i++)for(let j=-4;j<=4;j++)for(let y=0;y<=4;y++){const d=Math.hypot(i,y,j);if(d<=4.4)put(7+i,gh+1+y,7+j,d>3.4?112:0)}
put(7,gh+1,11,0);put(7,gh+2,11,0);put(7,gh+1,7,20);put(6,gh+1,7,20);put(8,gh+3,7,21)}
else{for(let i=0;i<4;i++)for(let j=0;j<5;j++){const e=i==0||i==3||j==0||j==4;put(5+i,gh+1+j,7,e?((j>0&&j<4&&hs(wx+i,j,wz)<.15)?0:24):164)}for(let i=3;i<=10;i++)for(let j=5;j<=9;j++)if(hs(wx+i,j,wz)<.3)put(i,gh,j,77)}
})}
vApply(cx,cz,c)}
const MV3=[];for(let k=0;k<10;k++)MV3.push(new Float32Array(40));
const mv3=(k,X,Z,S)=>{const ca=MV3[k].fill(-1),g=i=>{let v=ca[i];if(v<0){v=vn(X+i*17.1,Z+i*9.7);ca[i]=v}return v};return y=>{const t=y/S,yi=Math.floor(t),f=t-yi,u=f*f*(3-2*f),a=g(yi);return a+(g(yi+1)-a)*u}};
function genO(cx,cz){
const c=new Uint8Array(CS*CS*H),hh=[],BI=[];
for(let z=0;z<CS;z++)for(let x=0;x<CS;x++){
const wx=cx*CS+x,wz=cz*CS+z,h=th(wx,wz),bi=bm(wx,wz),be=h<=SEA+1,mt=h>44+D0&&bi!=9,cn=(()=>{const q=cnyc(wx,wz);return q[0]<q[1]*1.15})()&&vn(wx/600+8000,wz/600)>.4&&h>SEA+3,i=x+16*z,sv=vn((wx+vn(wx/13+3,wz/13)*16)/46+4000,(wz+vn(wx/17+9,wz/17+5)*16)/46+10);hh[i]=h;BI[i]=bi;
const nb=vn(wx/19+8100,wz/19+80),sy=be&&(bi==2||(h>=SEA?nb>.62:nb>.42)),gv=be&&!sy&&h<SEA&&nb<.26,sa=sy||bi==2,tl=Math.floor(vn(wx/70+8700,wz/70)*5+vn(wx/23+8800,wz/23)*2),STR=[148,148,159,159,148,155,147,147,151,148,148,161,161,147,159,148,155,155,148,151,147,147,161,148];
const cap=vn(wx/37+60,wz/37)>.5?h:h-2,F1=mv3(0,wx/30,wz/30,22),F2=mv3(1,wx/30+500,wz/30+900,22),F3=mv3(2,wx/50+90,wz/50,30),F4=mv3(3,wx/34+700,wz/34+200,18),F5=mv3(4,wx/24+1700,wz/24+300,12),F6=mv3(5,wx/24+2300,wz/24+1100,12),F7=mv3(6,wx/37+3700,wz/37+700,9),F8=mv3(7,wx/37+4300,wz/37+1500,9),O1=mv3(8,wx/11+500,wz/11+800,8),O2=mv3(9,wx/20+300,wz/20+300,9);
for(let y=0;y<=h;y++){
let b=y==0?28:y==h?(cn?3:sy?4:gv?14:be&&h<SEA?2:mt?(h>54+D0?13:3):[0,1,4,13,1,1,1,1,h<SEA?101:1,102,1,1,1,98,13,1,1][bi]):(bi==9&&!mt&&!be&&y>SEA-30)?STR[(y+tl+48)%24]:y>h-4?(cn?3:sa?(y>h-2?4:12):gv?(y>h-2?14:2):mt?3:2):(y<62+OF?74:3);
if((b==3||b==74)&&y>1&&y<106+OF){const r=hs(wx,y,wz);b=r<.012?15:r<.017&&y<96+OF?16:r<.0185&&y<74+OF?17:r<.0195&&y<52+OF?18:r>.985?14:3}
if(h>SEA+2&&y>78+OF&&b!=28){const dp=h-y;if((sv>.8&&dp<32&&O1(y)>.5+dp*.012+(1-Math.min(1,(sv-.8)*10))*.25)||(sv>.76&&y<94+OF&&O2(y)>.45))b=0}
if(y>2&&y<cap&&b!=28){if((Math.abs(F1(y)-.5)<.045&&Math.abs(F2(y)-.5)<.045)||((y<106+OF||h>110+OF)&&F3(y)>.82)||(y>6&&y<70+OF&&F4(y)>.78))b=0;else if(y<h-3&&((Math.abs(F5(y)-.5)<.038&&Math.abs(F6(y)-.5)<.038)||(Math.abs(F7(y)-.5)<.034&&Math.abs(F8(y)-.5)<.034)))b=0}
c[x+16*(z+16*y)]=b}
for(let y=h+1;y<=SEA;y++)c[x+16*(z+16*y)]=bi==3&&y==SEA?23:7;
{const cb=vn(wx/90+1000,wz/90+500);if(cb>.62||cb<.28){const mo=cb>.62;for(let y=3;y<h-1;y++){const q=x+16*(z+16*y);if(c[q])continue;const r=hs(wx,y,wz),fl=c[q-256],ce=c[q+256];
if(fl&&fl!=7&&fl!=28){c[q-256]=mo?201:202;if(mo?r<.2:r<.05)c[q]=mo?36:202}
if(ce&&ce!=7&&ce!=28){c[q+256]=mo?201:202;if(mo?r>.96:r>.94)c[q]=mo?21:202}}}}
}
for(let z=2;z<14;z++)for(let x=2;x<14;x++){
const h=hh[x+16*z],bi=BI[x+16*z],wx=cx*CS+x,wz=cz*CS+z,tb=c[x+16*(z+16*h)],r=hs(wx,9,wz);
if(tb==1&&h>SEA&&!c[x+16*(z+16*(h+1))]){const p=hs(wx,11,wz),fp=vn(wx/9+9400,wz/9+5),fs=vn(wx/41+9500,wz/41+3),gp=vn(wx/11+9100,wz/11+40)*.65+vn(wx/4+9200,wz/4)*.35,gm=vn(wx/60+9300,wz/60+9),fl=bi==12?(fp>.38?.5:0):(fp>.64?.22:0),pg=(bi==12?.4:.3)*Math.max(0,Math.min(1,(gp-.3)*2.6))*(.55+.9*gm),q=x+16*(z+16*(h+1));if(p<fl)c[q]=hs(wx,12,wz)<(fs>.5?.8:.2)?34:35;else if(hs(wx,13,wz)<pg)c[q]=36}
if(bi==2&&tb==4&&h>SEA+1&&r>.992){for(let d=1;d<=1+((r*1e3|0)%3);d++)c[x+16*(z+16*(h+d))]=22;continue}
if(bi==16&&tb==1&&r>.9&&x>1&&x<14&&z>1&&z<14){const hb3=5+(hs(wx,6,wz)*8|0);for(let dy=1;dy<=hb3;dy++)c[x+16*(z+16*(h+dy))]=32;continue}
if(bi==14&&tb==13&&r>.99&&x>3&&x<12&&z>3&&z<12){const hh2=8+(hs(wx,7,wz)*8|0);for(let dy=1;dy<=hh2;dy++){const rr=Math.max(0,2-(dy>>2));for(let i=-rr;i<=rr;i++)for(let k=-rr;k<=rr;k++)if(Math.abs(i)+Math.abs(k)<=rr+1)c[x+i+16*(z+k+16*(h+dy))]=108}continue}
if(!(tb==1||tb==13||tb==99||tb==100)||r<[0,.997,1,.99,.94,.9,.985,.95,.975,1,.93,.86,.998,1,1,.9,1][bi]||h+16>=H)continue;
const R0=hs(wx,8,wz),ty=bi==7||bi==3?'s':bi==6?'a':bi==5?'j':bi==10?'b':bi==11?'d':bi==15?'c':(bi==4&&R0>.7)?'b':'o';
if((ty=='j'||ty=='a'||ty=='d'||ty=='c')&&(x<3||x>12||z<3||z>12))continue;
const LG={s:57,a:59,j:58,b:56,o:5,d:60,c:204}[ty],LF={s:66,a:69,j:68,b:67,o:6,d:70,c:203}[ty],t=ty=='c'?5+(R0*3|0):ty=='d'?6+(R0*3|0):ty=='j'?7+(R0*5|0):ty=='s'?6+(R0*4|0):ty=='a'?4+(R0*2|0):4+(R0*3|0);
const lv=(i,dy,k)=>{const q=x+i+16*(z+k+16*(h+dy));if(!c[q])c[q]=LF};
for(let dy=1;dy<=t;dy++)c[x+16*(z+16*(h+dy))]=LG;
if(ty=='s'){for(let dy=2;dy<=t+1;dy++){const r=dy>t?0:dy==t?1:((t-dy)%2?2:1);for(let i=-r;i<=r;i++)for(let k=-r;k<=r;k++)if(Math.abs(i)+Math.abs(k)<=r+1)lv(i,dy,k)}}
else{const e=ty=='j'||ty=='a'||ty=='d'||ty=='c'?1:0;for(let dy=t-2;dy<=t+1;dy++){const r=(dy>=t?1:2)+e;for(let i=-r;i<=r;i++)for(let k=-r;k<=r;k++){if(Math.abs(i)==r&&Math.abs(k)==r&&hs(wx+i,dy,wz+k)>.5)continue;lv(i,dy,k)}}}
}
structs(cx,cz,c);
const e=ed[ck(cx,cz)];if(e)for(const i in e)c[i]=e[i];
return c}
const gen=(cx,cz)=>DIM==1?genN(cx,cz):DIM==2?genE(cx,cz):DIM==3?genS(cx,cz):genO(cx,cz);
const vn3=(x,y,z)=>{const yi=Math.floor(y),f=y-yi,u=f*f*(3-2*f),a=vn(x+yi*17.1,z+yi*9.7),b=vn(x+(yi+1)*17.1,z+(yi+1)*9.7);return a+(b-a)*u};
const fin=(cx,cz,c)=>{const e=ed[ck(cx,cz)];if(e)for(const i in e)c[i]=e[i];return c};
function nfort(cx,cz,c){const X0=cx*CS,Z0=cz*CS;for(let a=Math.floor((X0-48)/64);a<=Math.floor((X0+16)/64);a++)for(let b=Math.floor((Z0-48)/64);b<=Math.floor((Z0+16)/64);b++){if(hs(a,13,b)>.4)continue;
const sx=a*64+(hs(a,14,b)*16|0),sz=b*64+(hs(a,15,b)*30|0),y0=26+(hs(a,16,b)*14|0),put=(i,y,j,v)=>{const x=sx+i-X0,z=sz+j-Z0;if(x>=0&&x<16&&z>=0&&z<16&&y>=1&&y<H-2)c[x+16*(z+16*y)]=v};
for(let i=0;i<48;i++)for(let j=0;j<5;j++){const w=j%4==0;for(let y=0;y<6;y++)put(i,y0+y,j,y==0||y==5||(w&&!(y==3&&i%6==2))?78:0);if(w&&i%12==0)for(let y=1;y<14;y++)put(i,y0-y,j,78);if(j==2&&i%8==4)put(i,y0+5,j,21)}}}
function genN(cx,cz){const c=new Uint8Array(CS*CS*H);
for(let z=0;z<CS;z++)for(let x=0;x<CS;x++){const wx=cx*CS+x,wz=cz*CS+z;
for(let y=0;y<H;y++){let b=0;
if(y==0||y==70)b=28;else if(y>70)b=0;
else{const n=vn3(wx/22,y/12,wz/22)*.75+vn3(wx/8,y/5,wz/8)*.25;
if(n+Math.abs(y-38)/70>.66){const r=hs(wx,y,wz);b=y>=60&&r>.985?21:y<=22&&r>.92?107:r>.8&&vn(wx/7,wz/7)>.6?79:77}
else if(y<=20)b=7}
c[x+16*(z+16*y)]=b}}
nfort(cx,cz,c);return fin(cx,cz,c)}
function genE(cx,cz){const c=new Uint8Array(CS*CS*H);
for(let z=0;z<CS;z++)for(let x=0;x<CS;x++){const wx=cx*CS+x,wz=cz*CS+z,r=Math.hypot(wx,wz),R=34+vn(wx/9,wz/9)*8,o=vn(wx/35+9,wz/35);
let top=0,t2=0;if(r<R){top=40;t2=2+(R-r)*.55}else if(o>.76&&r>70){top=38;t2=3+(o-.76)*60}
if(top)for(let y=Math.max(1,Math.floor(top-t2));y<=top;y++)c[x+16*(z+16*y)]=81}
for(let k=0;k<8;k++){const px=Math.round(Math.cos(k*.7854)*26),pz=Math.round(Math.sin(k*.7854)*26),hh=48+(k*5%5)*3;
for(let i=-2;i<=2;i++)for(let j=-2;j<=2;j++){if(i*i+j*j>6)continue;const x=px+i-cx*CS,z=pz+j-cz*CS;if(x<0||x>15||z<0||z>15)continue;for(let y=40;y<=hh;y++)c[x+16*(z+16*y)]=24;c[x+16*(z+16*(hh+1))]=21}}
return fin(cx,cz,c)}
function genS(cx,cz){const c=new Uint8Array(CS*CS*H);
for(let z=0;z<CS;z++)for(let x=0;x<CS;x++){const wx=cx*CS+x,wz=cz*CS+z;
for(let L=0;L<3;L++){const a=vn(wx/30+L*41,wz/30+L*17)-.56;if(a<=0)continue;const base=22+L*18,top=base+Math.floor(a*16),bot=base-Math.floor(a*60)-2,col=131+Math.floor(vn(wx/60+L*5,wz/60)*16)%16;
for(let y=Math.max(1,bot);y<=top&&y<H-1;y++)c[x+16*(z+16*y)]=y==top?col:y>top-3?2:y>base-6?3:hs(wx,y,wz)>.97?21:71}}
return fin(cx,cz,c)}
function chunk(cx,cz){const k=ck(cx,cz);let c=ch.get(k);if(!c){c=gen(cx,cz);ch.set(k,c)}return c}
const getB=(x,y,z)=>y<0?3:y>=H?0:chunk(x>>4,z>>4)[(x&15)+16*((z&15)+16*y)];
const FD=[[1,0,0,0,1,0,0,0,1],[-1,0,0,0,0,1,0,1,0],[0,1,0,0,0,1,1,0,0],[0,-1,0,1,0,0,0,0,1],[0,0,1,1,0,0,0,1,0],[0,0,-1,0,1,0,1,0,0]];
const SH=[.9,.82,1,.6,.94,.76];
const cv=document.getElementById('c'),R=new THREE.WebGLRenderer({canvas:cv,antialias:false,powerPreference:'high-performance'});
R.setPixelRatio(Math.min(devicePixelRatio,1.25));R.shadowMap.enabled=true;R.shadowMap.type=THREE.PCFShadowMap;R.shadowMap.autoUpdate=false;
const scene=new THREE.Scene(),cam=new THREE.PerspectiveCamera(75,1,.1,700);cam.rotation.order='YXZ';
scene.fog=new THREE.Fog(0x8fcdf0,CS*RD*.5,CS*RD-8);
const A=document.createElement('canvas');A.width=128;A.height=256;
{const g=A.getContext('2d');let s=11;const rnd=()=>((s=Math.imul(s,1664525)+1013904223>>>0)/4294967296);
const S=(h,v=.28)=>{const k=1+(rnd()-.5)*v;return'rgb('+[h>>16,h>>8&255,h&255].map(q=>Math.min(255,q*k|0))+')'};
const T=(t,f)=>{for(let y=0;y<16;y++)for(let x=0;x<16;x++){const q=f(x,y);if(q){g.fillStyle=q;g.fillRect((t&7)*16+x,(t>>3)*16+y,1,1)}else g.clearRect((t&7)*16+x,(t>>3)*16+y,1,1)}};
const rg=Array.from({length:16},()=>2+rnd()*2|0),DI=()=>rnd()<.12?S(0x6b4a2b,.2):S(0x866043,.3),STN=()=>rnd()<.18?S(0x6e6e6e,.2):S(0x828282,.25);
const OR=[[3,3],[4,3],[3,4],[10,5],[11,5],[10,6],[6,11],[7,11],[7,12],[12,11],[8,2]];
const ore=(t,h)=>T(t,(x,y)=>OR.some(p=>p[0]==x&&p[1]==y)?S(h,.2):STN());
T(0,()=>S(rnd()<.25?0x2c4e2a:0x3b6a32,.26));T(1,(x,y)=>y<rg[x]?S(0x4d7239,.26):DI());T(2,DI);T(3,STN);T(4,()=>S(0xdbcf9a,.12));
const bt=Array.from({length:16},()=>rnd());T(5,(x,y)=>{const v=bt[x]*.6+rnd()*.4+(y%7==3&&rnd()<.35?.25:0);return v<.33?S(0x3e2f19,.1):v<.62?S(0x5e4a2c,.1):v<.85?S(0x76603a,.1):S(0x8a7348,.1)});
T(6,(x,y)=>{const d=Math.max(Math.abs(x-7.5),Math.abs(y-7.5));return d>6.5?S(0x5e4a2c,.12):d<1.5?S(0x8a6a3a,.1):(d|0)%2?S(0xa57f4c,.1):S(0xb48d58,.1)});
T(7,()=>rnd()<.27?null:rnd()<.3?S(0x2a5324,.3):S(0x3f7230,.45));T(8,(x,y)=>{const w=Math.sin(x*.8+Math.sin(y*.6)*2.2)*.5+.5;return w>.8?S(0x6aa0ec,.06):S(0x2b5fc8,.08)});
T(9,(x,y)=>y%4==3?S(0x7d5f35,.12):(x+(y>>2)*5)%16==0?S(0x8a6a3c,.12):rnd()<.22?S(0x9c7a46,.1):S(0xb8945a,.1));
T(10,(x,y)=>x==0||y==0||x==15||y==15?'rgba(205,230,242,.96)':x==1||y==1||x==14||y==14?'rgba(200,226,240,.3)':(x+y==8||x+y==9)&&x>=2&&x<=7?'rgba(255,255,255,.75)':x+y==13&&x>=6&&x<=10?'rgba(255,255,255,.42)':'rgba(205,232,244,.1)');
T(11,(x,y)=>y%4==3||(x+(y>>2&1)*4)%8==0?S(0xc9bfae,.1):S(0xa0503a,.3));
T(12,(x,y)=>(x+(y/4|0)%2*3)%6==0||y%5==0?S(0x5a5a5a,.2):S(0x858585,.35));
T(13,(x,y)=>y<2||y>13?S(0xd0c088,.1):y==5||y==10?S(0xc2b078,.1):S(0xe0d3a2,.08));T(14,()=>S(0xdcd0a0,.1));
T(15,()=>S(0xf4faff,.06));T(16,(x,y)=>y<rg[x]+1?S(0xf4faff,.06):DI());
T(17,()=>{const r=rnd();return r<.3?S(0x6f6a68,.3):r<.6?S(0x8f8a86,.3):S(0xa39e98,.3)});
ore(18,0x1f1f1f);ore(19,0xd8af93);ore(20,0xfcee4b);ore(21,0x5decf5);
T(22,(x,y)=>y%8==7||(x+(y>>3&1)*8)%16==0?S(0x5f5f5f,.1):S(0x7f7f7f,.2));
T(23,()=>S(0xb02e26,.3));T(24,()=>rnd()<.35?S(0xffe070,.3):S(0xc8914a,.4));
T(25,(x,y)=>x%5==0?S(0x2d5a1a,.2):(x==3||x==10)&&y%4==1?S(0xe8f0d0,.1):S(0x4e8a2a,.25));
T(26,(x,y)=>x<2||y<2||x>13||y>13?S(0x2d5a1a,.2):S(0x4e8a2a,.25));T(27,()=>S(0x9ccaff,0));
T(28,()=>rnd()<.2?S(0x2b1d45,.3):S(0x120c1f,.4));
T(29,(x,y)=>x==0||y==0?S(0xfff3a0,.05):x>13||y>13?S(0xd9a520,.1):S(0xf8d93a,.15));
T(30,(x,y)=>x==0||y==0?S(0xb8fbff,.05):x>13||y>13?S(0x2fb0b8,.1):S(0x5ed9e0,.15));
T(31,(x,y)=>S([0x985a42,0xb5694a,0xd09a7c,0xa8614a][y>>2],.1));T(32,()=>rnd()<.4?S(0x2e2e2e,.5):S(0x575757,.5));
T(33,(x,y)=>{const dx=Math.abs(x-7.5)/7.5,v=Math.max(0,1-dx*.9-y/24+(rnd()-.5)*.18);return v>.7?S(0xfff4b0,.06):v>.45?S(0xffc83c,.08):v>.2?S(0xff8c1a,.1):S(0xe0501a,.1)});T(95,(x,y)=>y<3?S(0x2d2218,.2):x==0||x==15?S(0x5a4322,.15):x%3==1?S(0x93713a,.12):S(0x7a5a2b,.15));
T(34,(x,y)=>x==7&&y>=7?S(0x3a8a2a,.2):Math.hypot(x-7,y-4.5)<2.6?(x==7&&y==4?S(0x222222):S(0xd0202a,.2)):null);
T(35,(x,y)=>x==7&&y>=7?S(0x3a8a2a,.2):Math.hypot(x-7,y-4.5)<2.6?(x==7&&y==4?S(0xffe860):S(0xf5d020,.15)):null);
T(36,(x,y)=>x%3==1?null:y>=16-(4+(x*5)%9)?S(0x4f7f33,.35):null);
T(37,(x,y)=>x<1||x>14||y<1||y>14?S(0x4a3820,.1):y>=3&&y<=5&&x>=4&&x<=11?S(0xcfeaff,.05):y==8&&x==12?S(0xdddddd):y%8==7?S(0x6b5030,.2):S(0xa88050,.15));
const FL=(t,h,v)=>T(t,()=>S(h,v)),SK=(t,h,h2,p)=>T(t,()=>rnd()<(p||.25)?S(h2,.2):S(h,.25)),BR=(t,h,m)=>T(t,(x,y)=>y%4==3||(x+(y>>2&1)*4)%8==0?S(m,.1):S(h,.25)),OR2=(t,h,b)=>T(t,(x,y)=>OR.some(p=>p[0]==x&&p[1]==y)?S(h,.2):b());
T(38,(x,y)=>rnd()<.08&&y%5==1?S(0x222222,.2):S(0xd8d5c8,.1));T(39,(x,y)=>{const d=Math.max(Math.abs(x-7.5),Math.abs(y-7.5));return d>6.5?S(0xd8d5c8,.1):(d|0)%2?S(0xc8b888,.1):S(0xdccf9a,.1)});
SK(40,0x888888,0xa0a0a0);SK(41,0xc8c8c8,0x8a8a8a);SK(42,0x9a6a58,0xc08878,.3);SK(43,0x4a4a50,0x35353a,.3);
T(44,(x,y)=>rnd()<.25?S(0x4f7a38,.3):(x+(y/4|0)%2*3)%6==0||y%5==0?S(0x5a5a5a,.2):S(0x858585,.35));
FL(45,0x9a9a9a,.05);SK(46,0x6f2f2f,0x8a4040,.3);BR(47,0x2c1519,0x1a0c0e);SK(48,0x544033,0x3a2c22,.3);FL(49,0xf0ebe3,.04);SK(50,0xdbe0a0,0xc8cd88,.3);
OR2(51,0xe0825a,STN);OR2(52,0xe02020,STN);OR2(53,0x2a50c0,STN);OR2(54,0x41d27a,STN);
T(55,(x,y)=>x<1||y<1||x>14||y>14?S(0xb0b0b0,.05):S(0xe8e8e8,.06));FL(56,0xf2f2f2,.22);FL(57,0xf2f2f2,.03);FL(58,0xd6b8a6,.08);
T(59,(x,y)=>y<2||y>13?S(0xb98d55,.12):y==8?S(0x6b5030,.2):S([0xa04030,0x3050a0,0x40803a,0xb09030][(x>>1)%4],.3));
T(60,(x,y)=>y>=6&&y<=9?S(0xe8e0d0,.06):S(0xc02a1a,.15));T(61,(x,y)=>x==7||y==7?S(0x333333,.1):S(0xc02a1a,.15));
T(62,(x,y)=>x<2||y<2||x>13||y>13||x==7||y==7?S(0x6b4a2b,.15):S(0xb98d55,.12));T(63,(x,y)=>y<3?S(0x6b4a2b,.15):y>12?S(0x8a6a40,.15):(x+y)%5==0?S(0x808080,.2):S(0xa0784a,.2));
T(64,(x,y)=>x>3&&x<12&&y>5&&y<11?S(y>8?0xe08020:0x202020,.3):S(0x7a7a7a,.2));
T(65,x=>x%4==0?S(0xb85a10,.15):S(0xe07a18,.15));FL(66,0xd06a10,.2);T(67,x=>x%4<2?S(0x4a8a2a,.2):S(0x7ab040,.2));FL(68,0x6aa030,.25);
FL(69,0x6e5a70,.25);T(70,(x,y)=>y<3+(x*3%2)?S(0x6e5a70,.25):DI());FL(71,0x5a4328,.25);T(72,(x,y)=>y<3?S(0x5a4328,.25):DI());FL(73,0x6e4a30,.3);FL(74,0xa0a6b8,.1);FL(75,0xb8582a,.12);
T(76,(x,y)=>x%8==0||y%8==0?S(0xa0d0c8,.1):S(0xd8f0ec,.08));SK(77,0x5aa8a0,0x3c8880,.35);
T(78,x=>x%4==0?S(0xb8b4a0,.1):S(0xe0dcc8,.08));FL(79,0xe0dcc8,.08);T(80,(x,y)=>y%4==0?S(0xa08818,.15):S(0xd8b830,.2));T(81,(x,y)=>(x+y)%4?S(0xd8b830,.2):S(0xa08818,.15));
SK(82,0x2a1410,0xe0601a,.3);FL(83,0xa8d0f0,.08);SK(84,0xd4c850,0x8a8030,.2);T(85,(x,y)=>y<2||y>13?S(0xb85a30,.1):S(0xc46a38,.1));FL(86,0xc46a38,.08);
T(88,(x,y)=>rnd()<.2?S(0x4f7a38,.3):y%8==7||(x+(y>>3&1)*8)%16==0?S(0x5f5f5f,.1):S(0x7f7f7f,.2));
T(89,()=>S(rnd()<.3?0xffb020:0xe05a10,.3));T(90,()=>rnd()<.2?S(0xd070ff,.2):S(0x7a20c0,.3));T(91,()=>rnd()<.06?S(0xdde8ff,.1):S(0x070514,.3));T(92,()=>rnd()<.2?S(0xa0fff0,.2):S(0x20b8c8,.3));
T(96,(x,y)=>Math.hypot(x-7.5,y-8)<6?S(rnd()<.3?0x8a2a1a:0xb04030,.2):null);
T(97,(x,y)=>Math.abs(x-y)<1.3?S(0x8a6a3a,.2):null);T(98,(x,y)=>Math.hypot(x-7.5,y-8)<5?S(0x222222,.3):null);T(99,(x,y)=>Math.abs(x-7.5)+Math.abs(y-8)<6?S(0x5decf5,.15):null);
T(100,(x,y)=>y>5&&y<11&&x>2&&x<13?S(0xd8d8d8,.1):null);T(101,(x,y)=>y>5&&y<11&&x>2&&x<13?S(0xf8d93a,.1):null);
[[102,0xb98d55],[103,0x888888],[104,0xdcdcdc],[105,0x5decf5]].forEach(([t,c])=>T(t,(x,y)=>Math.abs(x+y-16)<1.4&&y>3?S(0x8a6a3a,.2):(Math.hypot(x-9,y-9)>4.5&&Math.hypot(x-9,y-9)<7&&y<7&&x>3?S(c,.12):null)));
T(106,(x,y)=>x==0||y==0||x==15||y==15||(x+y==7&&x>=2&&x<=5)?'rgba(255,255,255,.95)':'rgba(255,255,255,.42)');
T(107,(x,y)=>y<2||y>13||x<1||x>14?S(0x6b4a2b,.1):y<5?S(0xe8e8e8,.06):S(0xb02e26,.12));
[[108,0xb98d55],[109,0x888888],[110,0xdcdcdc],[111,0x5decf5]].forEach(([t,c])=>T(t,(x,y)=>Math.abs(x+y-15)<1.4&&y>=1&&y<=9?S(c,.12):(y==10&&x>=3&&x<=6)?S(0x8a6a3a,.2):(Math.abs(x+y-15)<1.1&&y>10&&y<=14?S(0x8a6a3a,.2):null)));
[[112,0xdcdcdc],[113,0x5decf5]].forEach(([t,c])=>T(t,(x,y)=>((x>=3&&x<=12&&y>=3&&y<=13&&!(y<=4&&x>=6&&x<=9))||(y>=3&&y<=7&&(x==1||x==2||x==13||x==14)))?S(c,.15):null));
T(114,(x,y)=>Math.hypot(x-7.5,y-8.5)<5?S(0xc02020,.15):(x==8&&y>=2&&y<=4?S(0x5a3a1a,.1):(x==9&&y==3?S(0x3a8a2a,.1):null)));
T(115,(x,y)=>Math.hypot(x-7.5,y-8)<5.5?S(rnd()<.3?0x4a2a1a:0x8a4a2a,.2):null);
T(116,()=>rnd()<.25?S(0x4a6a22,.3):S(0x5c7f2c,.3));T(117,()=>rnd()<.3?S(0x6a5a4a,.25):S(0x8a7864,.2));
T(118,()=>rnd()<.27?null:rnd()<.3?S(0xe08aa8,.2):S(0xf2b4c8,.25));T(119,(x,y)=>y%6==0?S(0x4a7a2a,.1):S(0x7ab040,.12));
T(94,(x,y)=>y%4==3?S(0x9a8a50,.2):(x+(y>>2)*5)%8==0?S(0xb0a060,.2):S(0xd5c98c,.1))}
const tex2=new THREE.CanvasTexture(A);tex2.magFilter=THREE.NearestFilter;tex2.minFilter=THREE.LinearMipmapLinearFilter;tex2.anisotropy=R.capabilities.getMaxAnisotropy();const SHP=m=>{m.onBeforeCompile=sh=>{sh.fragmentShader=sh.fragmentShader.replace('texture2D( map, vUv )','texture2D( map, vUv, -.5 )')}};
const A2=document.createElement('canvas');A2.width=128;A2.height=256;
const mkA2=()=>{const im=A.getContext('2d').getImageData(0,0,128,256),d=im.data,q=v=>Math.max(0,Math.min(255,Math.round(v/51)*51));
for(let i=0;i<d.length;i+=4){if(!d[i+3])continue;const p=i/4,x=p%16,y=(p/128|0)%16,l=(d[i]+d[i+1]+d[i+2])/3,o=(x==0||y==0||x==15||y==15)?.55:1;
d[i]=q(l+(d[i]-l)*1.5)*o;d[i+1]=q(l+(d[i+1]-l)*1.5)*o;d[i+2]=q(l+(d[i+2]-l)*1.5)*o}
A2.getContext('2d').putImageData(im,0,0)};
const A3=document.createElement('canvas');A3.width=128;A3.height=256;
const mkA3=()=>{const d=A.getContext('2d').getImageData(0,0,128,256),o=A3.getContext('2d').createImageData(128,256),S=d.data,D=o.data;
for(let y=0;y<256;y++)for(let x=0;x<128;x++){const tx=x&~15,ty=y&~15;let r=0,g=0,b=0,a=0,n=0;for(let j=-2;j<=2;j++)for(let i=-2;i<=2;i++){const xx=Math.min(tx+15,Math.max(tx,x+i)),yy=Math.min(ty+15,Math.max(ty,y+j)),k=(yy*128+xx)*4;if(S[k+3]){r+=S[k];g+=S[k+1];b+=S[k+2];n++}a+=S[k+3]}const p=(y*128+x)*4;if(n){const e=(x&15)==0||(y&15)==0||(x&15)==15||(y&15)==15?.88:1,o=S[p+3];D[p]=Math.min(255,(r/n*.7+(o?S[p]:r/n)*.3)*e);D[p+1]=Math.min(255,(g/n*.7+(o?S[p+1]:g/n)*.3)*e);D[p+2]=Math.min(255,(b/n*.7+(o?S[p+2]:b/n)*.3)*e)}D[p+3]=Math.round(a/25)}
A3.getContext('2d').putImageData(o,0,0)};
const A4=document.createElement('canvas');A4.width=512;A4.height=1024;
const mkA4=()=>{const g=A4.getContext('2d');g.imageSmoothingEnabled=true;g.imageSmoothingQuality='high';g.drawImage(A,0,0,128,256,0,0,512,1024);const im=g.getImageData(0,0,512,1024),d=im.data,
 hn=(x,y)=>{const v=Math.sin(x*12.9898+y*78.233)*43758.5453;return v-Math.floor(v)},
 sm=(x,y,s,o)=>{const X=x/s+o,Y=y/s+o*1.7,xi=Math.floor(X),yi=Math.floor(Y),fx=X-xi,fy=Y-yi,u=fx*fx*(3-2*fx),v=fy*fy*(3-2*fy),a=hn(xi,yi),b=hn(xi+1,yi),c=hn(xi,yi+1),e=hn(xi+1,yi+1);return a+(b-a)*u+(c-a)*v+(a-b-c+e)*u*v},
 ST=[3,12,18,19,20,21,22,40,41,42,43,44,45,46,47,50,51,52,53,54,88],DT=[2,16],WV=[5,6,38,39],WH=[9,94],SD=[4,13,14,75];
 for(let y=0;y<1024;y++)for(let x=0;x<512;x++){const i=(y*512+x)*4;if(d[i+3]<8)continue;const t=((y>>6)<<3)+(x>>6),ly=y&63,n1=sm(x,y,2.5,1),n2=sm(x,y,6,2),n3=sm(x,y,14,3),n4=sm(x,y,32,4);
  let m=1+(n1-.5)*.1+(n2-.5)*.16+(n3-.5)*.12+(n4-.5)*.08,r=1,gg=1,bb=1;
  if(t==0||(t==1&&ly<20)){const st=sm(x*2.4,y*.5,5,5)-.5;m=1+(n1-.5)*.22+(n2-.5)*.3+(n3-.5)*.22+st*.3;r=1+(n3-.5)*.2+st*.1;gg=1+st*.16;bb=1-(n3-.5)*.14}
  else if(ST.includes(t)){m=1+(n1-.5)*.2+(n2-.5)*.26+(n3-.5)*.3+(n4-.5)*.12;if(Math.abs(sm(x,y,22,6)-.5)<.018)gg=r=bb=.72}
  else if(DT.includes(t)||t==1){m=1+(n1-.5)*.22+(n2-.5)*.3+(n3-.5)*.2;if(n2>.82)r=gg=bb=1.22}
  else if(WV.includes(t)){m=1+(sm(x,y*.12,3.5,7)-.5)*.5+(n2-.5)*.14}
  else if(WH.includes(t)){m=1+(sm(x*.15,y,3.5,8)-.5)*.4+(n2-.5)*.12}
  else if(SD.includes(t)){m=1+(n1-.5)*.18+(n2-.5)*.14}
  d[i]=Math.min(255,d[i]*m*r);d[i+1]=Math.min(255,d[i+1]*m*gg);d[i+2]=Math.min(255,d[i+2]*m*bb)}
 g.putImageData(im,0,0)};
const A5=document.createElement('canvas');A5.width=512;A5.height=1024;
const mkA5=()=>{const g=A5.getContext('2d');g.imageSmoothingEnabled=false;g.clearRect(0,0,512,1024);g.drawImage(A,0,0,128,256,0,0,512,1024);
const im=g.getImageData(0,0,512,1024),D=im.data,
HH=(x,y,s)=>{let h=Math.imul(x+101,374761393)^Math.imul(y+101,668265263)^Math.imul(s+7,1274126177);h=Math.imul(h^(h>>>13),1274126177);return((h^(h>>>16))>>>0)/4294967296},
SM=(x,y,s,k)=>{const X=x/k,Y=y/k,xi=Math.floor(X),yi=Math.floor(Y),fx=X-xi,fy=Y-yi,u=fx*fx*(3-2*fx),v=fy*fy*(3-2*fy),a=HH(xi,yi,s),b=HH(xi+1,yi,s),c=HH(xi,yi+1,s),d=HH(xi+1,yi+1,s);return a+(b-a)*u+(c-a)*v+(a-b-c+d)*u*v},
NV=(x,y,s)=>(HH(x,y,s)*.55+SM(x,y,s+1,3)*.3+SM(x,y,s+2,8)*.15-.5)*1.5+.5,
C=(h,k)=>{k=k||1;return[Math.min(255,(h>>16)*k),Math.min(255,(h>>8&255)*k),Math.min(255,(h&255)*k)]},
P=(p,v,k)=>C(p[Math.min(p.length-1,Math.max(0,Math.floor(v*p.length)))],k),
W=(t,fn)=>{const ox=(t&7)*64,oy=(t>>3)*64;for(let y=0;y<32;y++)for(let x=0;x<32;x++){const c=fn(x,y);for(let dy=0;dy<2;dy++)for(let dx=0;dx<2;dx++){const i=((oy+y*2+dy)*512+ox+x*2+dx)*4;if(c){D[i]=c[0];D[i+1]=c[1];D[i+2]=c[2];D[i+3]=255}else D[i+3]=0}}},
VR=(x,y,cs,s)=>{const n=32/cs;let d1=1e9,d2=1e9,id=0;const cx=Math.floor(x/cs),cy=Math.floor(y/cs);for(let j=-1;j<=1;j++)for(let i=-1;i<=1;i++){const gx=cx+i,gy=cy+j,wx=((gx%n)+n)%n,wy=((gy%n)+n)%n,px=(gx+.15+HH(wx,wy,s)*.7)*cs,py=(gy+.15+HH(wx,wy,s+1)*.7)*cs,d=Math.hypot(x-px,y-py);if(d<d1){d2=d1;d1=d;id=HH(wx,wy,s+2)}else if(d<d2)d2=d}return[d2-d1,id]};
for(let by=0;by<512;by++)for(let bx=0;bx<256;bx++){const j=1+(HH(bx,by,3)-.5)*.1;for(let dy=0;dy<2;dy++)for(let dx=0;dx<2;dx++){const i=((by*2+dy)*512+bx*2+dx)*4;if(D[i+3]){D[i]=Math.min(255,D[i]*j);D[i+1]=Math.min(255,D[i+1]*j);D[i+2]=Math.min(255,D[i+2]*j)}}}
const GR=[0x29502a,0x325c33,0x3c683c,0x467545,0x50824f,0x5b8f5a],DT=[0x5a3d26,0x6b4a2f,0x7a5636,0x866043,0x93704c,0xa07d58],ST=[0x6a6a6a,0x767676,0x818181,0x8c8c8c,0x979797],SA=[0xcdbf80,0xd6c88b,0xdfd297,0xe6daa4,0xece1b2],SN=[0xe8f1f8,0xf0f7fc,0xf8fcff,0xffffff],
BK=[0x2f2112,0x3e2c17,0x4f3a1f,0x5e4a2c,0x70593a],LV=[0x1d5a1b,0x2a7523,0x38892c,0x479c35,0x58b042],BP=[0x8f6d3d,0x9c7a46,0xa8844f,0xb58f5a,0xc09a64],
dirt=(x,y)=>HH(x,y,5)>.975?C(0x8d8576):P(DT,NV(x,y,2)),stn=(x,y)=>HH(x,y,31)>.94?C(0x5e5e5e):P(ST,NV(x,y,30)),
ore=(t,pal)=>W(t,(x,y)=>SM(x+t*5,y+t*3,110+t,5)>.66&&HH(x,y,111)>.15?P(pal,HH(x,y,112)):stn(x,y)),
LFt=(x,y)=>{const ax=Math.abs(x-15.5);return ax>1.5&&ax<6&&y>=19&&Math.abs(y-(25-(ax-1.5)*.9))<1.3};
W(0,(x,y)=>P(GR,NV(x,y,10)));
W(1,(x,y)=>{const j=6+(HH(x,0,20)*4|0)+(HH(x>>1,1,21)>.7?2:0);return y<j?P(GR,NV(x,y,10)*.95,y>=j-2?.82:1):dirt(x,y)});
W(2,dirt);W(3,stn);W(4,(x,y)=>P(SA,NV(x,y,40)));
W(5,(x,y)=>{const v=SM(x*1.2,y*.18,50,2.2)*.6+HH(x,0,51)*.3+HH(x,y,52)*.1;return P(BK,(v-.5)*1.5+.5)});
W(6,(x,y)=>{const d=Math.max(Math.abs(x-15.5),Math.abs(y-15.5));if(d>=14)return P(BK,NV(x,y,53));if(d<2)return C(0x8a6a3a,.9+HH(x,y,54)*.2);const ring=Math.floor(d/2.2)%2;return C(ring?0xc29a63:0xa9824c,.92+HH(x,y,55)*.16)});
W(7,(x,y)=>SM(x,y,60,3)>.74&&HH(x,y,61)>.25?null:P(LV,NV(x,y,62)));
W(9,(x,y)=>{const row=y>>3;if((y&7)==7)return C(0x6a4f2a);if(x==(row*13+5)%32)return C(0x7a5a30);const k=.92+.16*HH(row,(x+row*13)>>4,72);return P(BP,SM(x*.3,y,70,2)*.6+HH(x,y,71)*.4,k)});
W(12,(x,y)=>{const r=VR(x,y,8,80);return r[0]<1.5?C(0x4a4a4a):P([0x6e6e6e,0x7b7b7b,0x888888,0x969696],r[1]*.7+HH(x,y,81)*.3)});
W(15,(x,y)=>P(SN,NV(x,y,15)));
W(16,(x,y)=>{const j=7+(HH(x,0,160)*3|0);return y<j?P(SN,NV(x,y,15)):dirt(x,y)});
W(17,(x,y)=>{const r=VR(x,y,4,90);return r[0]<1?C(0x5a5551):P([0x77726e,0x8a8580,0x9c9792,0xaaa59f,0x6b6460],r[1])});
W(22,(x,y)=>{if(y%8==7)return C(0x5a5a5a);const xs=(y>>3)%2?8:24;if(x==xs||x==(xs+16)%32)return C(0x5a5a5a);return P(ST,NV(x,y,150))});
ore(18,[0x1c1c1c,0x2b2b2b,0x3a3a3a]);ore(19,[0xd8af93,0xc99c80,0xe8c8ad]);ore(20,[0xfcee4b,0xe0d03a,0xfff67a]);ore(21,[0x5decf5,0x44c8d2,0x9af8fc]);
ore(51,[0xe0825a,0xc46a46,0xf0a07a]);ore(52,[0xe02020,0xb01010,0xff5050]);ore(53,[0x2a50c0,0x1f3d99,0x4a70e0]);ore(54,[0x41d27a,0x2fb060,0x7af0a8]);
W(36,(x,y)=>{for(let i=0;i<10;i++){const x0=1.5+i*3.1+(HH(i,0,120)-.5)*1.6,h=11+HH(i,1,121)*17,lean=(HH(i,2,122)-.5)*9,t=(31-y)/h;if(t<0||t>1)continue;const cx=x0+lean*t*t,w=1.4*(1-t)+.55;if(Math.abs(x-cx)<w)return C([0x5c9a30,0x6aa83a,0x79b845][i%3],.62+.5*t+(HH(x,y,123)-.5)*.2)}return null});
W(34,(x,y)=>{if(Math.abs(x-15.5)<1.1&&y>=16)return C(0x3f7a2a,.8+HH(x,y,130)*.4);if(LFt(x,y))return C(0x4f9a35,.85+HH(x,y,131)*.3);const dx=x-15.5,dy=y-9,r=Math.hypot(dx,dy);if(r<2)return C(0x1a1a1a);if(r<7){const pet=.5+.5*Math.cos(Math.atan2(dy,dx)*5);if(r<5.2+pet*1.8)return C([0xa51220,0xc41c28,0xdc2a35,0xe84a4a][Math.min(3,Math.floor(r/7*3+HH(x,y,132)*1.2))])}return null});
W(35,(x,y)=>{if(Math.abs(x-15.5-Math.sin(y*.3)*.5)<.9&&y>=14)return C(0x4a8a30,.85+HH(x,y,140)*.3);if(LFt(x,y))return C(0x4f9a35,.85+HH(x,y,141)*.3);const dx=x-15.5,dy=y-10,r=Math.hypot(dx,dy),j=.5+.5*Math.cos(Math.atan2(dy,dx)*9);if(r<2)return C(0xd68a00);if(r<4.2+j*1.6)return C([0xe8b400,0xf5cc10,0xffe040][Math.min(2,Math.floor(HH(x,y,142)*3))]);return null});
g.putImageData(im,0,0)};
const ATR=document.createElement('canvas');ATR.width=512;ATR.height=1024;let UG=.01,US=.98;
const mkAR=()=>{const T=56,CE=64,GU=4,g=ATR.getContext('2d');g.clearRect(0,0,512,1024);g.imageSmoothingEnabled=true;g.imageSmoothingQuality='high';
 {const tmp=document.createElement('canvas');tmp.width=tmp.height=64;const tg=tmp.getContext('2d');for(let t=0;t<128;t++){tg.imageSmoothingEnabled=false;tg.clearRect(0,0,64,64);tg.drawImage(A,(t&7)*16,(t>>3)*16,16,16,0,0,64,64);g.drawImage(tmp,0,0,64,64,(t&7)*CE+GU,(t>>3)*CE+GU,T,T)}}
 const im=g.getImageData(0,0,512,1024),D=im.data,PX={},PY={},HERO={};
 const H=(x,y,s)=>{let h=Math.imul(x|0,374761393)^Math.imul(y|0,668265263)^Math.imul((s|0)+7,1274126177);h=Math.imul(h^(h>>>13),1274126177);return((h^(h>>>16))>>>0)/4294967296};
 const PN=(x,y,s,c,d)=>{d=d||c;const nx=T/c,ny=T/d,X=x/c,Y=y/d,xi=Math.floor(X),yi=Math.floor(Y),fx=X-xi,fy=Y-yi,u=fx*fx*(3-2*fx),v=fy*fy*(3-2*fy),x0=((xi%nx)+nx)%nx,x1=(x0+1)%nx,y0=((yi%ny)+ny)%ny,y1=(y0+1)%ny,a=H(x0,y0,s),b=H(x1,y0,s),e=H(x0,y1,s),f=H(x1,y1,s);return a+(b-a)*u+(e-a)*v+(a-b-e+f)*u*v};
 const FB=(x,y,s)=>PN(x,y,s,28)*.34+PN(x,y,s+1,14)*.28+PN(x,y,s+2,7)*.2+PN(x,y,s+3,4)*.1+PN(x,y,s+4,2)*.08;
 const C=h=>[h>>16,h>>8&255,h&255],ml=(c,k)=>[c[0]*k,c[1]*k,c[2]*k],mx=(a,b,k)=>[a[0]+(b[0]-a[0])*k,a[1]+(b[1]-a[1])*k,a[2]+(b[2]-a[2])*k],
 PL=(a,v)=>{v=Math.max(0,Math.min(.9999,v))*(a.length-1);const i=Math.floor(v),f=v-i,p=C(a[i]),q=C(a[i+1]);return[p[0]+(q[0]-p[0])*f,p[1]+(q[1]-p[1])*f,p[2]+(q[2]-p[2])*f]},
 pv=(v,k)=>(v-.5)*k+.5;
 const W=(t,fn,px,py)=>{PX[t]=px;PY[t]=py;HERO[t]=1;const ox=(t&7)*CE+GU,oy=(t>>3)*CE+GU;for(let y=0;y<T;y++)for(let x=0;x<T;x++){const c=fn(x,y),i=((oy+y)*512+ox+x)*4;if(c){D[i]=c[0];D[i+1]=c[1];D[i+2]=c[2];D[i+3]=c[3]===undefined?255:c[3]}else D[i+3]=0}};
 const VO=(x,y,cs,s)=>{const n=T/cs,cx=Math.floor(x/cs),cy=Math.floor(y/cs);let d1=1e9,d2=1e9,id=0;for(let j=-1;j<=1;j++)for(let i=-1;i<=1;i++){const gx=cx+i,gy=cy+j,wx=((gx%n)+n)%n,wy=((gy%n)+n)%n,px=(gx+.2+.6*H(wx,wy,s))*cs,py=(gy+.2+.6*H(wx,wy,s+1))*cs,d=Math.hypot(x-px,y-py);if(d<d1){d2=d1;d1=d;id=H(wx,wy,s+2)}else if(d<d2)d2=d}return[d1,d2,id]};
 const GR=[0x1d3a21,0x264826,0x305630,0x39643a,0x437244,0x4d7f4e],DT=[0x3a2a1c,0x48341f,0x573f29,0x674c34,0x77593e],ST=[0x555555,0x626262,0x6e6e6e,0x7a7a7a,0x868686],SA=[0xbfae82,0xc9ba90,0xd3c59c,0xddd1aa,0xe6dcb8],
 BK=[0x281d13,0x35271a,0x433220,0x52402b,0x634e36],WD=[0x9c7c4e,0xaa8a5a,0xb8996a,0xc6a87b,0xd2b78c],PLK=[0x86683b,0x937543,0x9f814d,0xac8e58,0xb89b64],LV=[0x1a3a1d,0x254a27,0x315a31,0x3f6d3b,0x4e8047],
 GRV=[0x5a5855,0x6c6a66,0x7e7b76,0x908d87,0xa19e97,0x7a6a58],SN=[0xd9e2ea,0xe5ecf2,0xeff4f8,0xf7fafc];
 const grass=(x,y)=>{const a=FB(x,y,10),b=PN(x,y,11,2),c=H(x,y,12),d=PN(x,y,13,4),sk=PNs(x,y);let col=PL(GR,pv(a*.5+b*.22+c*.18+d*.1,1.7));col=ml(col,.86+.28*PN(x,y,14,7));col=ml(col,.94+.12*sk);if(c>.972)col=mx(col,[128,122,76],.45);return col};
 const PNs=(x,y)=>PN(x,y,16,2,14);
 const dirt=(x,y)=>{const a=FB(x,y,30),b=PN(x,y,31,2),c=H(x,y,32);let col=PL(DT,pv(a*.55+b*.25+c*.2,1.6));const pe=PN(x,y,33,7);if(pe>.7&&H(x>>1,y>>1,34)>.4)col=mx(col,[132,118,102],.5+.3*PN(x,y,35,4));return ml(col,.9+.2*PN(x,y,36,14))};
 const stone=(x,y,sd)=>{const a=FB(x,y,40+sd),b=PN(x,y,41+sd,2),c=H(x,y,42+sd);let col=PL(ST,pv(a*.55+b*.25+c*.2,1.7));const r=Math.abs(PN(x,y,43+sd,14)-.5)*2,r2=Math.abs(PN(x,y,44+sd,7)-.5)*2;if(r<.04)col=ml(col,.6+r*8);else if(r2<.028)col=ml(col,.78+r2*7);if(c>.986)col=mx(col,[196,196,192],.28);return ml(col,.92+.16*PN(x,y,45+sd,28))};
 const sand=(x,y,k)=>{const g1=H(x,y,50),g2=PN(x,y,51,2),a=FB(x,y,52),rip=Math.sin(2*Math.PI*((x*2+y*3)/T)+(FB(x,y,53)-.5)*5)*.5+.5;let col=PL(SA,pv(a*.3+g2*.22+g1*.48,1.9));col=ml(col,.965+.07*rip);const q=H(x,y,54);if(q>.93)col=ml(col,1.1);else if(q<.08)col=ml(col,.8);if(H(x,y,56)>.991)col=[150,128,98];if(k)col=mx(col,[214,170,140],.18);return col};
 const edge=(x,s,b)=>b+9*PN(x,0,s,7)+6*PN(x,0,s+1,2);
 W(0,grass,1,1);
 W(1,(x,y)=>{const e=edge(x,21,13);if(y<e){let c=grass(x,y+9);return ml(c,.72+.28*Math.min(1,(e-y)/5))}const q=Math.min(1,(y-e)/6);return ml(dirt(x,y),.78+.22*q)},1,0);
 W(2,dirt,1,1);W(3,(x,y)=>stone(x,y,0),1,1);W(4,(x,y)=>sand(x,y,0),1,1);
 W(15,(x,y)=>{const a=FB(x,y,60)*.7+PN(x,y,61,2)*.3;let c=PL(SN,pv(a,1.6));c=ml(c,.97+.03*PN(x,y,62,14));if(H(x,y,63)>.985)c=[255,255,255];return[c[0]*.99,c[1],c[2]*1.01]},1,1);
 W(16,(x,y)=>{const e=edge(x,64,16);if(y<e){let c=PL(SN,pv(FB(x,y,60)*.7+PN(x,y,61,2)*.3,1.6));return ml(c,.82+.18*Math.min(1,(e-y)/5))}return ml(dirt(x,y),.8+.2*Math.min(1,(y-e)/6))},1,0);
 W(17,(x,y)=>{const[d1,d2,id]=VO(x,y,7,70),e=d2-d1;let c=PL(GRV,id);c=ml(c,.78+.28*Math.min(1,d1/4.5)+(H(x,y,73)-.5)*.14);if(e<1.1)c=ml(c,.5+e*.4);return c},1,1);
 W(12,(x,y)=>{const[d1,d2,id]=VO(x,y,14,80),e=d2-d1;if(e<1.7)return ml(stone(x,y,5),.38+e*.12);let c=ml(stone(x,y,6+(id*7|0)),.8+.4*id);const bev=Math.min(1,e/5);c=ml(c,.78+.28*bev+(.12-d1/70));return c},1,1);
 W(5,(x,y)=>{const f=PN(x,y,70,2,28)*.5+PN(x,y,71,4,14)*.3+PN(x,y,72,4)*.2;let c=PL(BK,pv(f,1.7));const xs=((x+Math.round((PN(x,y,74,56,28)-.5)*8))%T+T)%T,rr=Math.abs(PN(xs,0,74,7)-.5)*2;if(rr<.16)c=ml(c,.5+rr*3);return ml(c,.92+.16*PN(x,y,75,14))},1,1);
 W(6,(x,y)=>{const dx=x-27.5,dy=y-27.5,r=Math.hypot(dx,dy),ed=Math.min(x,y,55-x,55-y);if(ed<3||r>26){const f=PN(x,y,76,4,14)*.6+PN(x,y,77,2)*.4;return ml(PL(BK,pv(f,1.6)),.95)}const w=(FB(x,y,78)-.5)*6,ring=Math.sin((r+w)*.98)*.5+.5;let c=PL(WD,pv(.35+ring*.4+PN(x,y,79,2)*.15,1.2));if(r<2.2)c=ml(c,.7);const an=Math.atan2(dy,dx);if(Math.abs(Math.sin(an*5+w))<.03&&r>4)c=ml(c,.82);return ml(c,.94+.1*PN(x,y,80,7))},0,0);
 W(7,(x,y)=>{const m=PN(x,y,60,4)*.5+PN(x,y,61,2)*.28+H(x,y,62)*.22;if(m<.4)return null;const sh=PN(x,y,63,14),c=PL(LV,pv(m*.55+sh*.45,1.5));return ml(c,.8+.4*H(x,y,64))},1,1);
 W(9,(x,y)=>{const b=Math.floor(y/14),yy=y%14;if(yy==0)return[48,34,20];const jx=(b*19+11)%T,jw=Math.min(Math.abs(x-jx),T-Math.abs(x-jx));if(jw<1)return[58,42,26];const gx=(x+b*13)%T,gr=PN(gx,y,81+b,28,2)*.55+PN(gx,y,90+b,14,1)*.2+PN(gx,y,100,2)*.2;let c=PL(PLK,pv(gr*.8+H(b,0,82)*.35,1.5));if(yy==1)c=ml(c,1.12);if(yy==13)c=ml(c,.88);const kx=(b*23+9)%T,kd=Math.hypot(x-kx,(y-b*14-7)*1.5);if(H(b,1,83)>.45&&kd<4.5)c=ml(c,.62+kd*.07);return c},1,1);
 W(11,(x,y)=>{const r=Math.floor(y/14),yy=y%14,off=r%2?14:0,xx=(x+off)%28,bi=Math.floor((x+off)/28)%2;if(yy<2||xx<2){const m=H(x,y,110)*.1+.9;return[176*m,170*m,160*m]}const id=H(r,bi,111);let c=PL([0x7a3324,0x8e4030,0xa24d38,0xb25c42],id);c=ml(c,.82+.3*(FB(x,y,112)));c=ml(c,.9+.2*H(x,y,113));if(yy==2)c=ml(c,1.15);if(yy==13||xx==27)c=ml(c,.82);return c},1,1);
 W(22,(x,y)=>{const r=Math.floor(y/28),yy=y%28,off=r%2?14:0,xx=(x+off)%28,bi=Math.floor((x+off)/28)%2;if(yy<2||xx<2)return[58,58,58];let c=ml(stone(x,y,r*3+bi),.86+.2*H(r,bi,120));if(yy==2||xx==2)c=ml(c,1.14);if(yy==27||xx==27)c=ml(c,.84);return c},1,1);
 W(13,(x,y)=>{let c=sand(x,y,1);const band=Math.sin(y*.55+FB(x,y,130)*4)*.5+.5;c=ml(c,.9+.14*band);return y%14==0?ml(c,.84):c},1,1);
 W(14,(x,y)=>sand(x,y,1),1,1);
 const ORE=(t,pal,hl,sd)=>W(t,(x,y)=>{let c=stone(x,y,3);let best=1e9,bi=0;for(let i=0;i<6;i++){const cx=H(i,t,1)*T,cy=H(i,t,2)*T,r=3.5+H(i,t,3)*4.5;let dx=Math.abs(x-cx),dy=Math.abs(y-cy);dx=Math.min(dx,T-dx);dy=Math.min(dy,T-dy);const d=Math.hypot(dx,dy)+(PN(x,y,90+i,4)-.5)*4-r;if(d<best){best=d;bi=i}}
  if(best<0){const o=PL(pal,pv(PN(x,y,95,2)*.6+H(x,y,96)*.4,1.5));let k=.82+.28*Math.min(1,-best/2.5);let q=ml(o,k);if(H(x,y,97)>.93)q=mx(q,hl,.6);return q}if(best<1.6)return ml(c,.7+best*.18);return c},1,1);
 ORE(18,[0x0d0d0f,0x1a1a1d,0x2b2b30,0x3b3b42],[110,110,120]);ORE(19,[0xb98466,0xcf9a7a,0xe0b293,0xefc7ad],[255,225,205]);ORE(20,[0xc9961a,0xe3b628,0xf5d54a,0xfde98a],[255,250,190]);ORE(21,[0x1fa5b0,0x35c8d4,0x6ee6ee,0xb8fbff],[240,255,255]);
 ORE(51,[0xa5532f,0xc4693f,0xdc8456,0x47a889],[250,190,150]);ORE(52,[0x8c0a0a,0xb01212,0xd82020,0xff5a5a],[255,170,170]);ORE(53,[0x1c2f8c,0x2848b4,0x3d62d8,0x6f8cf2],[190,205,255]);ORE(54,[0x1f9c4e,0x35c26a,0x66e196,0xb4f8cf],[235,255,240]);
 const GR2=[0x2f5430,0x3e6a3c,0x4f7e48,0x62915a,0x7aa56c];
 W(36,(x,y)=>{for(let i=0;i<10;i++){const x0=3+i*5.4+(H(i,0,140)-.5)*3,h=26+H(i,1,141)*28,lean=(H(i,2,142)-.5)*18,t=(55-y)/h;if(t<0||t>1)continue;const cx=x0+lean*t*t,w=1.9*(1-t)+.6;if(Math.abs(x-cx)<w){const c=PL(GR2,.15+t*.75);return ml(c,.72+.4*t+(H(x,y,143)-.5)*.18)}}return null},0,0);
 const LFt=(u,v)=>{const ax=Math.abs(u-15.5);return ax>1.5&&ax<6&&v>=19&&Math.abs(v-(25-(ax-1.5)*.9))<1.3};
 {const el=(x,y,cx,cy,rx,ry,r)=>{const c=Math.cos(r),sn=Math.sin(r),dx=x-cx,dy=y-cy,u=(dx*c+dy*sn)/rx,v=(-dx*sn+dy*c)/ry;return u*u+v*v};
 const stem=(x,y,xs0,y0)=>{const xs=xs0+Math.sin(y*.11)*1.3;return Math.abs(x-xs)<1.5&&y>=y0};
 const leaf=(x,y)=>{const a=el(x,y,20,39,7.5,2.6,-.55),b=el(x,y,35,33,7.2,2.5,.5);return a<1?[a,0]:b<1?[b,1]:null};
 const stemC=(x,y,i)=>ml(mx([46,98,38],[72,128,52],PN(x,y,600+i,5)),.85+H(x,y,601+i)*.3);
 W(34,(x,y)=>{if(stem(x,y,27.5,18))return stemC(x,y,0);const l=leaf(x,y);if(l)return ml(mx([48,104,40],[78,140,58],1-Math.min(1,l[0])),.82+H(x,y,610)*.3);
  const dx=x-27.5,dy=y-17,r=Math.hypot(dx,dy),th=Math.atan2(dy,dx),R=9.6*(.8+.2*Math.abs(Math.cos(2*th+.35)));
  if(r<3.3)return[22,18,24];if(r<5.2&&H(Math.round(th*3),0,620)>.45)return[46,30,50];
  if(r<R){const t=r/R,vein=.5+.5*Math.cos(th*4+.7);const base=PL([0x7e0d1a,0xa01426,0xc42031,0xdf3640,0xea5a57],t*.92+.06*vein+H(x,y,621)*.1);return ml(base,.9+.14*H(x,y,622)-(R-r<1.2?.18:0))}return null});
 W(35,(x,y)=>{if(stem(x,y,27.5,20))return stemC(x,y,3);const l=leaf(x,y);if(l)return ml(mx([50,108,42],[84,146,60],1-Math.min(1,l[0])),.82+H(x,y,630)*.3);
  if(el(x,y,36,30,3.2,3.2,0)<1)return ml([120,150,50],.85+H(x,y,631)*.3);
  const dx=x-27.5,dy=y-17,r=Math.hypot(dx,dy),th=Math.atan2(dy,dx),j=Math.abs(Math.cos(th*13+.3)),R=5.2+j*5.4;
  if(r<3.4)return ml([224,150,10],.9+.2*H(x,y,632));if(r<R)return ml(PL([0xe0a800,0xf2c112,0xfbdd4a,0xfff088],Math.min(1,r/R*.85+H(x,y,633)*.2)),.92+.1*H(x,y,634));return null});}
 {const gl=(x,y)=>{const u=x/T,v=y/T,e=Math.min(x,y,T-1-x,T-1-y);if(e<2)return[205,232,244,245];if(e<4)return[196,224,240,70+(4-e)*40];const d=u+v;let a=22+H(x,y,500)*8,w=0;if(Math.abs(d-.62)<.05)w=Math.max(w,.78*(1-Math.abs(d-.62)/.05)*(u<.5?1:.6));if(Math.abs(d-.8)<.022)w=Math.max(w,.5);if(Math.abs(d-.7)<.012&&u>.15&&u<.55)w=Math.max(w,.35);if(d>1.45)a+=28*(d-1.45);return w>0?[255,255,255,Math.min(255,a+w*210)]:[206,234,246,a]};
 W(10,gl);
 W(33,(x,y)=>{const dx=Math.abs(x-27.5)/27.5,v=Math.max(0,1-dx*.95-y/80+(PN(x,y,510,5)-.5)*.35);return v>.72?[255,246,190]:v>.5?mx([255,200,60],[255,244,176],(v-.5)/.22):v>.25?mx([255,130,26],[255,200,60],(v-.25)/.25):mx([210,70,22],[255,130,26],v/.25)});
 W(95,(x,y)=>{if(y<10)return ml([45,33,24],.8+H(x,y,520)*.4);const edge=Math.min(x,T-1-x)<5?.72:1,gr=.86+.2*PN(x,y,521,3,22)+.06*Math.sin(x*1.9+PN(x,y,522,12)*3);return ml(mx([122,90,43],[150,113,58],PN(x,y,523,6)),edge*gr*(1-.18*Math.max(0,(y-30)/26)))});}
 for(let t=0;t<128;t++){if(HERO[t])continue;const ox=(t&7)*CE+GU,oy=(t>>3)*CE+GU;for(let y=0;y<T;y++)for(let x=0;x<T;x++){const i=((oy+y)*512+ox+x)*4;if(D[i+3]<8)continue;const k=.93+.14*H(x,y,300+t)*.6+.06*PN(x,y,400,4);D[i]*=k;D[i+1]*=k;D[i+2]*=k}}
 {const B=2,Nn=T/B,Q=new Float32Array(Nn*Nn*4),LU=new Float32Array(Nn*Nn);for(let t=0;t<128;t++){const ox=(t&7)*CE+GU,oy=(t>>3)*CE+GU;let any=0;for(let by=0;by<Nn;by++)for(let bx=0;bx<Nn;bx++){let r=0,gg=0,b=0,a=0;for(let y=0;y<B;y++)for(let x=0;x<B;x++){const i=((oy+by*B+y)*512+ox+bx*B+x)*4;r+=D[i];gg+=D[i+1];b+=D[i+2];a+=D[i+3]}const q=(by*Nn+bx)*4;Q[q]=r/4;Q[q+1]=gg/4;Q[q+2]=b/4;Q[q+3]=a/4;LU[by*Nn+bx]=.3*Q[q]+.59*Q[q+1]+.11*Q[q+2];if(a>0)any=1}if(!any)continue;
 for(let by=0;by<Nn;by++)for(let bx=0;bx<Nn;bx++){const q=(by*Nn+bx)*4,L=(x,y)=>LU[((y+Nn)%Nn)*Nn+((x+Nn)%Nn)];let k=1;if(Q[q+3]>200){const e=(L(bx-1,by)+L(bx,by-1)-L(bx+1,by)-L(bx,by+1))*.5;k=1+Math.max(-.2,Math.min(.16,e*.0042));if(L(bx,by)<L(bx-1,by-1)-26)k*=.9}
  for(let y=0;y<B;y++)for(let x=0;x<B;x++){const i=((oy+by*B+y)*512+ox+bx*B+x)*4;if(Q[q+3]<64){D[i+3]=0;continue}D[i]=Math.min(255,Q[q]*k);D[i+1]=Math.min(255,Q[q+1]*k);D[i+2]=Math.min(255,Q[q+2]*k);D[i+3]=Q[q+3]>200?255:Q[q+3]*1.0}}}}
 for(let t=0;t<128;t++){const ox=(t&7)*CE,oy=(t>>3)*CE,wx=PX[t],wy=PY[t];for(let gy=-GU;gy<T+GU;gy++)for(let gx=-GU;gx<T+GU;gx++){if(gx>=0&&gx<T&&gy>=0&&gy<T)continue;const sx=wx?((gx%T)+T)%T:Math.max(0,Math.min(T-1,gx)),sy=wy?((gy%T)+T)%T:Math.max(0,Math.min(T-1,gy)),a=((oy+GU+sy)*512+ox+GU+sx)*4,b=((oy+GU+gy)*512+ox+GU+gx)*4;D[b]=D[a];D[b+1]=D[a+1];D[b+2]=D[a+2];D[b+3]=D[a+3]}}
 g.putImageData(im,0,0)};
const CUBE=(()=>{const mk=fn=>{const c=document.createElement('canvas');c.width=c.height=128;fn(c.getContext('2d'));return c};
const side=sun=>mk(g=>{const r=g.createLinearGradient(0,0,0,128);r.addColorStop(0,'#2f64a8');r.addColorStop(.38,'#5f93c6');r.addColorStop(.5,'#8fb2cc');r.addColorStop(.62,'#6f6552');r.addColorStop(1,'#5a4c3a');g.fillStyle=r;g.fillRect(0,0,128,128)});
const up=mk(g=>{g.fillStyle='#2f64a8';g.fillRect(0,0,128,128)}),dn=mk(g=>{g.fillStyle='#5a4c3a';g.fillRect(0,0,128,128)});
const t=new THREE.CubeTexture([side(1),side(0),up,dn,side(0),side(0)]);t.needsUpdate=true;return t})();
const TL={1:[0,1,2],2:[2],3:[3],4:[4],5:[6,5,6],6:[7],7:[8],8:[9],9:[10],10:[11],11:[12],12:[14,13,14],13:[15,16,2],14:[17],15:[18],16:[19],17:[20],18:[21],19:[22],20:[23],21:[24],22:[26,25,26],23:[27],24:[28],25:[29],26:[30],27:[31],28:[32]};
for(let i=40;i<48;i++)TL[i]=[i<44?9:12];for(let i=48;i<56;i++)TL[i]=[37];Object.assign(TL,{29:[9],30:[12],33:[33],34:[34],35:[35],36:[36]});
const TN={},NB=[['シラカバの原木',[39,38,39]],['トウヒの原木',[6,5,6],0x9a8a80],['ジャングルの原木',[6,5,6],0xd0a888],['アカシアの原木',[6,5,6],0xb0b0a8],['ダークオークの原木',[6,5,6],0x707070],
['トウヒの板材',[9],0x8a6a50],['シラカバの板材',[94]],['ジャングルの板材',[9],0xe0a080],['アカシアの板材',[9],0xf09060],['ダークオークの板材',[9],0x5a4030],
['トウヒの葉',[7],0x6a9a7a],['シラカバの葉',[7],0xc0ff90],['ジャングルの葉',[7],0xa0ff90],['アカシアの葉',[7],0xd0d080],['ダークオークの葉',[7],0x80a070],
['安山岩',[40]],['閃緑岩',[41]],['花崗岩',[42]],['深層岩',[43]],['苔むした丸石',[44]],['なめらかな石',[45]],['ネザーラック',[46]],['ネザーレンガ',[47]],['ソウルサンド',[48]],['クォーツブロック',[49]],['エンドストーン',[50]],
['銅鉱石',[51]],['レッドストーン鉱石',[52]],['ラピスラズリ鉱石',[53]],['エメラルド鉱石',[54]],
['鉄ブロック',[55]],['石炭ブロック',[55],0x303030],['ラピスラズリブロック',[55],0x3050c0],['レッドストーンブロック',[55],0xd01818],['エメラルドブロック',[55],0x30d060],['銅ブロック',[55],0xd88050],
['本棚',[9,59,9]],['TNT',[61,60,61]],['作業台',[62,63,9]],['かまど',[3,64,3]],['カボチャ',[66,65,66]],['スイカ',[68,67,68]],['菌糸',[69,70,2]],['ポドゾル',[71,72,2]],['粗い土',[73]],['粘土',[74]],['赤い砂',[75]],['シーランタン',[76]],['プリズマリン',[77]],['骨ブロック',[79,78,79]],['干し草の俵',[81,80,81]],['マグマブロック',[82]],['氷塊',[83]],['スポンジ',[84]],['赤い砂岩',[86,85,86]],['青氷',[83],0x70a0ff],['雪ブロック',[15]],['苔むした石レンガ',[88]],['ひび割れた石レンガ',[22],0xb0b0b0]];
const CL=[['白',0xf0f0f0],['オレンジ',0xf08a20],['赤紫',0xc84fc8],['空色',0x58b0e8],['黄色',0xf5d020],['黄緑',0x80c818],['ピンク',0xf09ab8],['灰色',0x484848],['薄灰色',0x9a9a92],['青緑',0x188a98],['紫',0x7a2ab0],['青',0x3040a8],['茶色',0x6a4428],['緑',0x4a6a18],['赤',0xb02e26],['黒',0x181820]];
[['の羊毛',56],['のコンクリート',57],['のテラコッタ',58]].forEach(([n,t])=>CL.forEach(([c,h])=>NB.push([c+n,[t],h])));
TN[204]=[1,.75,.78];TN[205]=[1,.78,.82];Object.assign(TL,{164:[90],165:[91],166:[92],167:[96],168:[97],169:[98],170:[99],171:[100],172:[101],173:[102],174:[103],175:[104],176:[105],31:[107],193:[108],194:[109],195:[110],196:[111],197:[112],198:[113],199:[114],200:[115],201:[116],202:[117],203:[118],204:[6,5,6],205:[9],32:[119]});NB.forEach((r,i)=>{TL[56+i]=r[1];if(r[2])TN[56+i]=[r[2]>>16&255,r[2]>>8&255,r[2]&255].map(q=>q/255)});
CL.forEach(([c,h],i)=>{TL[177+i]=[106];TN[177+i]=[h>>16&255,h>>8&255,h&255].map(q=>q/255)});
const ISO=b=>b<33||b==29||b==30||(b>=40&&b<48)||(b>=56&&b<167)||(b>=177&&b<=192)||(b>=203&&b<=205);
const ico0=b=>{const t=TL[b]||[3],c=document.createElement('canvas'),x=c.getContext('2d'),AT_=window.AT||A,TS_=AT_.width/8,tn=TN[b],ti=t[1]||t[0];x.imageSmoothingEnabled=AT_.width>128;x.imageSmoothingQuality='high';const gx=UG*TS_,sw=US*TS_;
if(ISO(b)){c.width=c.height=32;const face=(i,m,sh)=>{x.save();x.setTransform(...m);x.drawImage(AT_,(i&7)*TS_+gx,(i>>3)*TS_+gx,sw,sw,0,0,16,16);if(sh){x.fillStyle='rgba(0,0,0,'+sh+')';x.fillRect(0,0,16,16)}x.restore()};
face(ti,[14/16,7/16,0,14/16,2,9],.22);face(ti,[14/16,-7/16,0,14/16,16,16],.42);face(t[0],[14/16,7/16,14/16,-7/16,2,9],0)}
else{c.width=c.height=16;x.drawImage(AT_,(ti&7)*TS_+gx,(ti>>3)*TS_+gx,sw,sw,0,0,16,16);if(b==33){x.clearRect(0,0,16,16);x.fillStyle='#7a5a2b';x.fillRect(7,5,2,10);x.fillStyle='#ff9020';x.fillRect(7,2,2,3);x.fillStyle='#ffe070';x.fillRect(7,2,2,1)}}
if(tn){const d=x.getImageData(0,0,c.width,c.height),a=d.data;for(let k=0;k<a.length;k+=4)if(a[k+3]){a[k]*=tn[0];a[k+1]*=tn[1];a[k+2]*=tn[2]}x.putImageData(d,0,0)}
return'url('+c.toDataURL()+')'};
const ICC={},ico=b=>{const k=(window.TXS===undefined?'u':window.TXS)+','+b;return ICC[k]||(ICC[k]=ico0(b))};
const sunL=new THREE.DirectionalLight(0xffffff,1),hemi=new THREE.HemisphereLight(0xa8d0ff,0x6b5a45,.5),tv=new THREE.Vector3(),tp=new THREE.Vector3();let fn=0;
scene.add(sunL,sunL.target,hemi);sunL.castShadow=true;
{const sm=2048,SR=TOUCH?45:75,sc=sunL.shadow.camera;sunL.shadow.mapSize.set(sm,sm);sc.left=sc.bottom=-SR;sc.right=sc.top=SR;sc.near=1;sc.far=300;sunL.shadow.bias=-.0004;sunL.shadow.normalBias=.05}
const mk=o=>new THREE.MeshLambertMaterial(Object.assign({vertexColors:true,map:tex2},o));
const MT=[mk({}),mk({transparent:true,opacity:.62,depthWrite:false,side:THREE.DoubleSide}),mk({transparent:true,alphaTest:.05,depthWrite:false,side:THREE.DoubleSide}),mk({alphaTest:.5,side:THREE.DoubleSide}),mk({alphaTest:.5,side:THREE.DoubleSide})];
const MV0=mk({}),MS0=new THREE.MeshPhongMaterial({vertexColors:true,map:tex2,shininess:50,specular:0x333333,envMap:CUBE,reflectivity:.12,combine:THREE.MixOperation}),MS2=MT[2],MG0=new THREE.MeshPhongMaterial({vertexColors:true,map:tex2,shininess:95,specular:0x777777,envMap:CUBE,reflectivity:.3,combine:THREE.MixOperation}),MG2=new THREE.MeshPhongMaterial({vertexColors:true,map:tex2,shininess:90,specular:0x666666,envMap:CUBE,reflectivity:.35,combine:THREE.MixOperation,transparent:true,alphaTest:.05,depthWrite:false,side:THREE.DoubleSide});
[MV0,MS0,MS2,MG0,MG2,MT[3]].forEach(SHP);
MT[4].onBeforeCompile=sh=>{sh.uniforms.uT=WT;sh.fragmentShader=sh.fragmentShader.replace('texture2D( map, vUv )','texture2D( map, vUv, -.5 )');sh.vertexShader='uniform float uT;\n'+sh.vertexShader.replace('#include <begin_vertex>','vec3 transformed=vec3(position);vec4 wq=modelMatrix*vec4(position,1.);transformed.x+=sin(uT*1.3+wq.x*.6+wq.z*.4)*.035;transformed.z+=cos(uT*1.1+wq.z*.5+wq.y*.3)*.035;transformed.y+=sin(uT*1.7+wq.x*.8)*.015;')};
MT[0]=MS0;MT[5]=MS0;const SHN=new Uint8Array(256);[17,18,21,23,24,25,26,76,80,85,86,87,88,89,90,91,103,104,108,111].forEach(i=>SHN[i]=1);
const WT={value:0},WL={value:0};MT[1].onBeforeCompile=sh=>{sh.uniforms.uT=WT;sh.uniforms.uCam={value:cam.position};sh.uniforms.uSky={value:cSky};sh.uniforms.uSun={value:dir};sh.uniforms.uLv=WL;sh.uniforms.uRip={value:RIPT};
sh.vertexShader='uniform float uT;varying vec3 vWp;\n'+sh.vertexShader.replace('#include <begin_vertex>','vec3 transformed=vec3(position);vec4 wp0=modelMatrix*vec4(position,1.);vWp=wp0.xyz;transformed.y+=(sin(wp0.x*.35-uT*.9+wp0.z*.12)*.55+sin(wp0.z*.5+wp0.x*.2-uT*.7)*.45)*.045-.08;');
sh.fragmentShader='uniform float uT,uLv;uniform sampler2D uRip;uniform vec3 uCam,uSky,uSun;varying vec3 vWp;\nfloat h21(vec2 p){return fract(sin(dot(p,vec2(127.1,311.7)))*43758.5453);}\nfloat vnz(vec2 p){vec2 i=floor(p),f=fract(p);f=f*f*(3.-2.*f);return mix(mix(h21(i),h21(i+vec2(1,0)),f.x),mix(h21(i+vec2(0,1)),h21(i+vec2(1,1)),f.x),f.y);}\nfloat wh(vec2 q,float t){return vnz(q*1.1+vec2(t*.18,t*.07))*.6+vnz(q*2.7-vec2(t*.11,-t*.15))*.3+vnz(q*6.3+vec2(t*.2,t*.1))*.1;}\n'+sh.fragmentShader.replace('#include <fog_fragment>',`
if(uLv<.5){
vec2 p=vWp.xz;float t=uT;vec2 q=p*.35+vec2(t*.1,t*.04);
float h=vnz(q);vec2 g=vec2(vnz(q+vec2(.06,0.))-h,vnz(q+vec2(0.,.06))-h)*16.;
float a1=p.x*.35-t*.9+p.y*.12,a2=p.y*.5+p.x*.2-t*.7;vec2 sw=vec2(.55*cos(a1)*.35+.45*cos(a2)*.2,.55*cos(a1)*.12+.45*cos(a2)*.5)*.25;
vec3 wn=normalize(vec3(-g.x*.05-sw.x,1.,-g.y*.05-sw.y));
vec2 ru=vWp.xz/32.;float fd=smoothstep(18.,8.,distance(vWp.xz,uCam.xz));
float rl=texture2D(uRip,ru-vec2(.0078,0.)).r,rr=texture2D(uRip,ru+vec2(.0078,0.)).r,rd=texture2D(uRip,ru-vec2(0.,.0078)).r,rv=texture2D(uRip,ru+vec2(0.,.0078)).r;
wn=normalize(wn+vec3(-(rr-rl),0.,-(rv-rd))*14.*fd);
vec3 vd=normalize(uCam-vWp);float cv=clamp(dot(vd,wn),0.,1.),fr=clamp(.04+pow(1.-cv,5.)*.96,0.,1.);
float L=clamp(dot(gl_FragColor.rgb,vec3(.3,.59,.11))*2.4,.3,1.4);
vec3 base=mix(vec3(.12,.42,.46),vec3(.02,.12,.24),.7+h*.15)*L;
vec3 rf=reflect(-vd,wn);float sp=pow(max(dot(rf,normalize(uSun)),0.),60.)*.5;
gl_FragColor.rgb=mix(base,uSky*.92+.08,fr)+vec3(1.,.95,.8)*sp*step(0.,uSun.y);
gl_FragColor.a=clamp(.72+fr*.2,0.,.94);
}
#include <fog_fragment>`)};
const QF=[[[1,0,1],[1,0,0],[1,1,0],[1,1,1]],[[0,0,0],[0,0,1],[0,1,1],[0,1,0]],[[0,1,1],[1,1,1],[1,1,0],[0,1,0]],[[0,0,0],[1,0,0],[1,0,1],[0,0,1]],[[0,0,1],[1,0,1],[1,1,1],[0,1,1]],[[1,0,0],[0,0,0],[0,1,0],[1,1,0]]],UVQ=[[0,0],[1,0],[1,1],[0,1]];
const uvq=(t,k)=>[(t%8+UG+UVQ[k][0]*US)/8,1-((t>>3)+1)/16+(UG+UVQ[k][1]*US)/16];
function bx(g,x,y,z,a,b,c,d,e,f,t,full){for(let q=0;q<6;q++){const n0=g.p.length/3,m=full?full:SH[q];
for(let k=0;k<4;k++){const v=QF[q][k];g.p.push(x+(v[0]?d:a),y+(v[1]?e:b),z+(v[2]?f:c));g.c.push(m,m,m);g.n.push(FD[q][0],FD[q][1],FD[q][2]);g.u.push(...uvq(t,k))}
g.i.push(n0,n0+1,n0+2,n0,n0+2,n0+3)}}
const PQ=[[0,0,0,1,0,1,1,1,1,0,1,0],[1,0,0,0,0,1,0,1,1,1,1,0]];
function spc(G,b,x,y,z){const g=G[0];
if(b==29||b==30)bx(g,x,y,z,0,0,0,1,.5,1,b==29?9:12);
else if(b==31)bx(g,x,y,z,0,0,0,1,.5625,1,107);else if(b==32)bx(g,x,y,z,.4375,0,.4375,.5625,1,.5625,119);else if(b>=40&&b<48){const t=b<44?9:12,B=[[0,.5,0,1,1,.5],[.5,.5,0,1,1,1],[0,.5,.5,1,1,1],[0,.5,0,.5,1,1]][(b-40)&3];bx(g,x,y,z,0,0,0,1,.5,1,t);bx(g,x,y,z,...B,t)}
else if(b==33){window.CT.push(window.CO[0]+x+.5,y+.75,window.CO[1]+z+.5);bx(g,x,y,z,.4375,0,.4375,.5625,.5,.5625,95,0);bx(g,x,y,z,.4375,.5,.4375,.5625,.6875,.5625,33,2.2)}
else if(b>=48){const d=((b-48)&3)+((b-48)>>2)&3,B=[[0,0,0,1,1,.1875],[.8125,0,0,1,1,1],[0,0,.8125,1,1,1],[0,0,0,.1875,1,1]][d];bx(g,x,y,z,...B,37)}
else{const h=G[3],v4=window.TXS==4,jx=v4?(hs(window.CO[0]+x,y,window.CO[1]+z)-.5)*.5:0,jz=v4?(hs(window.CO[0]+x,y+9,window.CO[1]+z)-.5)*.5:0,sy=v4?.78+hs(window.CO[0]+x,y+5,window.CO[1]+z)*.3:1;const fs=(b==34||b==35)?.6:1;PQ.forEach(q=>{const n0=h.p.length/3;for(let k=0;k<4;k++){h.p.push(x+.5+(q[k*3]-.5)*fs+jx,y+q[k*3+1]*sy*fs,z+.5+(q[k*3+2]-.5)*fs+jz);h.c.push(.95,.95,.95);h.n.push(0,1,0);h.u.push(...uvq(b,k))}h.i.push(n0,n0+1,n0+2,n0,n0+2,n0+3)})}}
const OPT=new Uint8Array(256);for(let i=0;i<256;i++)OPT[i]=OP(i)?1:0;
function build(cx,cz){
const k=ck(cx,cz),old=meshes.get(k);
if(old)old.forEach(m=>{scene.remove(m);m.geometry.dispose()});
window.CT=[];TOR.set(k,window.CT);window.CO=[cx*CS,cz*CS];
const c=chunk(cx,cz),G=[0,1,2,3,4,5].map(()=>({p:[],c:[],i:[],u:[],n:[]})),ox=cx*CS,oz=cz*CS;
const at=(x,y,z)=>y<0?3:y>=H?0:(x>=0&&x<16&&z>=0&&z<16)?c[x+16*(z+16*y)]:getB(ox+x,y,oz+z);
const TY=new Int16Array(256);for(let z=0;z<16;z++)for(let x=0;x<16;x++){let y=H-1;while(y>0&&!c[x+16*(z+16*y)])y--;TY[x+16*z]=y}
const TQ=[];for(let i=0;i<c.length;i++)if(c[i]==33)TQ.push(ox+(i&15)+.5,(i>>8)+.75,oz+((i>>4)&15)+.5);for(let dx=-1;dx<=1;dx++)for(let dz=-1;dz<=1;dz++){if(!dx&&!dz)continue;const a=TOR.get(ck(cx+dx,cz+dz));if(a)for(let i=0;i<a.length;i++)TQ.push(a[i])}
let MY=1;for(let i=0;i<256;i++)if(TY[i]>MY)MY=TY[i];MY=Math.min(H-1,MY+1);for(let y=0;y<=MY;y++)for(let z=0;z<16;z++)for(let x=0;x<16;x++){
const b=c[x+16*(z+16*y)];if(!b)continue;if(b>=29&&b<56){spc(G,b,x,y,z);continue}
if(x>0&&x<15&&z>0&&z<15&&y>0&&y<H-1){const q=x+16*(z+16*y);if(OPT[c[q+1]]&OPT[c[q-1]]&OPT[c[q+16]]&OPT[c[q-16]]&OPT[c[q+256]]&OPT[c[q-256]])continue}
const g=G[b==7?1:(b==9||b>163&&b<167||(b>=177&&b<=192))?2:(b==6||((b>=66&&b<=70)||b==203))?4:SHN[b]?5:0],tc=TN[b]||[1,1,1],soft=b==7||b==9||(b>163&&b<167)||(b>=177&&b<=192);
for(let f=0;f<6;f++){
const d=FD[f],nx=x+d[0],ny=y+d[1],nz=z+d[2],nb=at(nx,ny,nz);
if(OP(nb)||(nb==b&&(b==6||((b>65&&b<71)||b==203)||soft)))continue;
const tp=(nx>=0&&nx<16&&nz>=0&&nz<16)?TY[nx+16*nz]:TY[x+16*z],lt=(DIM||b==21||b==103||b==107||ny>=tp-1)?1:Math.max(.3,1-(tp-1-ny)*.09),tl=TL[b],ti=tl[d[1]>0?0:d[1]<0?2:1]||tl[0],sh=.95+.1*vn((ox+x+y*.7)/10,(oz+z-y*.6)/10),n0=g.p.length/3,ao=[];
for(let q=0;q<4;q++){
const i=(q==1||q==2)?1:0,j=q>1?1:0,ia=2*i-1,jb=2*j-1;
g.p.push(x+(d[0]>0?1:0)+d[3]*i+d[6]*j,y+(d[1]>0?1:0)+d[4]*i+d[7]*j,z+(d[2]>0?1:0)+d[5]*i+d[8]*j);
let a=3;
if(!soft){
const s1=OP(at(nx+d[3]*ia,ny+d[4]*ia,nz+d[5]*ia))?1:0,s2=OP(at(nx+d[6]*jb,ny+d[7]*jb,nz+d[8]*jb))?1:0,cr=OP(at(nx+d[3]*ia+d[6]*jb,ny+d[4]*ia+d[7]*jb,nz+d[5]*ia+d[8]*jb))?1:0;
a=s1&&s2?0:3-s1-s2-cr}
ao.push(a);let m=sh*(.38+a*.21)*lt,cr=tc[0],cg=tc[1],cb=tc[2];const vx=ox+g.p[g.p.length-3],vy=g.p[g.p.length-2],vz=oz+g.p[g.p.length-1];
if(b==1){const n1=vn(vx/6+11,vz/6+3),n2=vn(vx/23,vz/23+7),k=d[1]>0?1:.5;cr*=1+k*(n2*.2-.1);cg*=1+k*(n1*.16-.08);cb*=1+k*(n2*.2-.1)}else if(b==2||b==3||b==4||b==14){m*=.95+.1*vn(vx/9+5,vz/9+vy/9)}
if(TQ.length){let tb=0;for(let u=0;u<TQ.length;u+=3){const dx=vx-TQ[u],dy=vy-TQ[u+1],dz=vz-TQ[u+2],d2=dx*dx+dy*dy+dz*dz;if(d2<121){const r=Math.sqrt(d2),q=1-r/11,w=q*q*(.55+.45*Math.max(0,-(d[0]*dx+d[1]*dy+d[2]*dz)/(r+.3)));if(w>tb)tb=w}}
if(tb>.01){m=Math.max(m,tb*(.72+a*.09));const w2=Math.min(1,tb*1.6);cr*=1+.32*w2;cg*=1-.06*w2;cb*=1-.5*w2}}
g.c.push(m*cr,m*cg,m*cb);g.n.push(d[0],d[1],d[2]);let sw=d[4],uu=sw?j:i,vv=sw?i:j;if(b==1&&d[1]>0||((b==2||b==3||b==4||b==14)&&d[1]!=0)){const rq=hs(ox+x,y+d[1],oz+z)*8|0;if(rq&1)uu=1-uu;if(rq&2)vv=1-vv;if(rq&4){const tq=uu;uu=vv;vv=tq}}else if(b==2||b==3||b==4||b==14||b==1){if(hs(ox+x,y,oz+z+f)>.5)uu=1-uu}
g.u.push((ti%8+UG+uu*US)/8,1-((ti>>3)+1)/16+(UG+vv*US)/16)}
if(ao[0]+ao[2]<ao[1]+ao[3])g.i.push(n0+1,n0+2,n0+3,n0+1,n0+3,n0);else g.i.push(n0,n0+1,n0+2,n0,n0+2,n0+3)}}
const ms=[];
G.forEach((g,gi)=>{if(!g.i.length)return;const ge=new THREE.BufferGeometry();
ge.setAttribute('position',new THREE.Float32BufferAttribute(g.p,3));ge.setAttribute('color',new THREE.Float32BufferAttribute(g.c,3));ge.setAttribute('normal',new THREE.Float32BufferAttribute(g.n,3));ge.setAttribute('uv',new THREE.Float32BufferAttribute(g.u,2));ge.setIndex(g.i);
const m=new THREE.Mesh(ge,MT[gi]);m.position.set(ox,0,oz);m.renderOrder=gi;m.castShadow=m.receiveShadow=(gi==0||gi==4||gi==5);scene.add(m);ms.push(m)});
meshes.set(k,ms)}
function setB(x,y,z,b){
if(y<1||y>=H)return;if(b==0)WQ.push([x,y,z]);const cx=x>>4,cz=z>>4,i=(x&15)+16*((z&15)+16*y);const ob=chunk(cx,cz)[i];chunk(cx,cz)[i]=b;
const k=ck(cx,cz);(ed[k]=ed[k]||{})[i]=b;
const rb=(a,c)=>meshes.has(ck(a,c))&&build(a,c);
if(b==33||ob==33){for(let a=-1;a<=1;a++)for(let c2=-1;c2<=1;c2++)if(a||c2)rb(cx+a,cz+c2)}
rb(cx,cz);if((x&15)==0)rb(cx-1,cz);if((x&15)==15)rb(cx+1,cz);if((z&15)==0)rb(cx,cz-1);if((z&15)==15)rb(cx,cz+1)}
const disc=(c,s)=>{const m=new THREE.Mesh(new THREE.PlaneGeometry(s,s),new THREE.MeshBasicMaterial({color:c,fog:false,depthWrite:false}));scene.add(m);return m};
const sun=disc(0xfff1a8,60),moon=disc(0xdfe8ff,38),sp=[];
for(let i=0;i<500;i++){const a=Math.random()*6.283,b=Math.acos(Math.random()*2-1);sp.push(Math.sin(b)*Math.cos(a)*500,Math.abs(Math.sin(b)*Math.sin(a))*500,Math.cos(b)*500)}
const sg=new THREE.BufferGeometry();sg.setAttribute('position',new THREE.Float32BufferAttribute(sp,3));
const stars=new THREE.Points(sg,new THREE.PointsMaterial({color:0xffffff,size:2,sizeAttenuation:false,fog:false,transparent:true,depthWrite:false}));scene.add(stars);
const cSky=new THREE.Color(),cN=new THREE.Color(0x060a1c),cD=new THREE.Color(0x8fcdf0),cO=new THREE.Color(0xf09a5a),cW=new THREE.Color(0x2a56a8),dir=new THREE.Vector3();
const SKU={uZ:{value:new THREE.Color()},uH:{value:new THREE.Color()},uS:{value:new THREE.Vector3()},uT:{value:0},uD:{value:1}},cZc=new THREE.Color(0x3a78c8);
const dome=new THREE.Mesh(new THREE.SphereGeometry(420,24,12),new THREE.ShaderMaterial({uniforms:SKU,side:THREE.BackSide,depthWrite:false,depthTest:false,vertexShader:'varying vec3 vP;void main(){vP=position;gl_Position=projectionMatrix*modelViewMatrix*vec4(position,1.);}',fragmentShader:`uniform vec3 uZ,uH,uS;uniform float uT,uD;varying vec3 vP;
float hh(vec2 p){return fract(sin(dot(p,vec2(127.1,311.7)))*43758.5);}
float nz(vec2 p){vec2 i=floor(p),f=fract(p);f=f*f*(3.-2.*f);return mix(mix(hh(i),hh(i+vec2(1,0)),f.x),mix(hh(i+vec2(0,1)),hh(i+vec2(1,1)),f.x),f.y);}
void main(){vec3 d=normalize(vP);vec3 c=mix(uH,uZ,pow(max(d.y,0.),.45));float s=max(dot(d,uS),0.);
c+=vec3(1.,.8,.5)*pow(s,48.)*.6*uD+vec3(1.,.9,.7)*pow(s,6.)*.18*uD;
if(d.y>.02){vec2 p=d.xz/(d.y+.12)*1.6+uT*.03;float n=nz(p)*.55+nz(p*2.1)*.3+nz(p*4.3)*.15;float cl=smoothstep(.52,.78,n)*smoothstep(.02,.2,d.y);c=mix(c,mix(vec3(.2,.22,.3),vec3(1.),uD),cl*.85);}
gl_FragColor=vec4(c,1.);}`}));dome.renderOrder=-10;dome.frustumCulled=false;scene.add(dome);
let RT=null;const mkRT=()=>{try{RT&&RT.dispose();const k=R.getPixelRatio(),P2=window.PORT,w=(P2?innerHeight:innerWidth)*k|0,h=(P2?innerWidth:innerHeight)*k|0;RT=R.capabilities.isWebGL2?new THREE.WebGLMultisampleRenderTarget(w,h):new THREE.WebGLRenderTarget(w,h)}catch(e){RT=null}};
const PS=new THREE.Scene(),PC=new THREE.OrthographicCamera(-1,1,1,-1,0,1),PU={tD:{value:null},uSun:{value:new THREE.Vector2(.5,.5)},uSv:{value:0},uUW:{value:0},uT:{value:0}};
PS.add(new THREE.Mesh(new THREE.PlaneGeometry(2,2),new THREE.ShaderMaterial({uniforms:PU,depthTest:false,vertexShader:'varying vec2 v;void main(){v=uv;gl_Position=vec4(position.xy,0.,1.);}',fragmentShader:`uniform sampler2D tD;uniform vec2 uSun;uniform float uSv,uUW,uT;varying vec2 v;
vec3 aces(vec3 x){return clamp((x*(2.51*x+.03))/(x*(2.43*x+.59)+.14),0.,1.);}
void main(){vec2 vv=v+uUW*vec2(sin(v.y*28.+uT*2.2),cos(v.x*24.+uT*1.9))*.003;vec3 c=texture2D(tD,vv).rgb,b=vec3(0.);
for(int i=0;i<6;i++){float a=float(i)*1.0472;vec2 o=vec2(cos(a),sin(a));b+=max(texture2D(tD,v+o*.006).rgb-.7,0.)+max(texture2D(tD,v+o*.016).rgb-.7,0.);}
c+=b*.12;vec2 d=(uSun-v)*.06,p=v;float g=0.;
for(int i=0;i<7;i++){p+=d*2.;g+=smoothstep(.8,1.,dot(texture2D(tD,p).rgb,vec3(.33)))*.14*(1.-float(i)/7.);}
c+=vec3(1.,.85,.6)*g*uSv;c=mix(c,aces(c*1.1),.55);float l=dot(c,vec3(.3,.59,.11));c+=vec3(.012,.006,-.012)*smoothstep(.5,1.,l)-vec3(.012,.003,-.014)*(1.-smoothstep(0.,.35,l));c=mix(vec3(l),c,1.04);
c=mix(c,c*vec3(.55,.85,1.)+vec3(0.,.035,.06),uUW*.75);c*=1.-(.35+.25*uUW)*pow(length(v-.5)*1.25,2.);gl_FragColor=vec4(c,1.);}`})));
function env(){
const a=T*6.2832,sh=Math.sin(a);dir.set(Math.cos(a),sh,.25).normalize();
const dk=DIM?[0,.45,.3,.8][DIM]:Math.max(0,Math.min(1,sh*2.5+.5));
cSky.copy(cN).lerp(cD,dk).lerp(cO,Math.max(0,1-Math.abs(sh)/.25)*.5);
const p=cam.position,uw=getB(Math.floor(p.x),Math.floor(p.y),Math.floor(p.z))==7;
if(uw)cSky.lerp(cW,.8).multiplyScalar(.5+.5*dk);
if(DIM&&!uw)cSky.setRGB(...[[0,0,0],[.33,.07,.05],[.04,.02,.09],[.82,.52,.92]][DIM]);
if(window.RK>0)cSky.multiplyScalar(1-.4*window.RK);
scene.background=cSky;scene.fog.color.copy(cSky);scene.fog.near=uw?.5:CS*RD*.65;scene.fog.far=uw?22:CS*RD-8;
const ah=Math.abs(sh),li=Math.min(1,ah*4);tv.copy(dir).multiplyScalar(sh>0?1:-1);
tp.set(Math.round(p.x/2)*2,Math.round(p.y/2)*2,Math.round(p.z/2)*2);
sunL.position.copy(tp).addScaledVector(tv,130);sunL.target.position.copy(tp);sunL.target.updateMatrixWorld();
sunL.color.set(sh>0?0xfff1dc:0x8fa8ff);if(sh>0)sunL.color.lerp(cO,Math.max(0,1-ah*4)*.6);
sunL.intensity=(sh>0?1.12:.22)*li;hemi.intensity=(.12+.26*dk)*(.6+(OD.br||50)/125);hemi.color.copy(cSky).lerp(cD,.5);
sun.position.copy(p).addScaledVector(dir,400);sun.lookAt(p);
moon.position.copy(p).addScaledVector(dir,-400);moon.lookAt(p);
stars.position.copy(p);stars.material.opacity=1-dk;stars.visible=dk<.95;
dome.position.copy(p);dome.visible=!uw;SKU.uH.value.copy(cSky);SKU.uZ.value.copy(cN).lerp(cZc,dk);SKU.uS.value.copy(dir);SKU.uD.value=dk*(1-.5*(window.RK||0));SKU.uT.value=performance.now()/1000;
if(DIM){if(DIM!=3)dome.visible=false;sun.visible=moon.visible=DIM==3;stars.visible=DIM!=1;stars.material.opacity=DIM==2?1:.5;sunL.intensity=DIM==3?.8:.1;if(DIM==1)hemi.intensity=.8;if(DIM==2)hemi.intensity=.55}else sun.visible=moon.visible=true;if(OD.tx==3||OD.tx==4){sunL.intensity*=.8;hemi.intensity*=1.2}sunL.intensity*=1-.6*(window.RK||0);window.UW=uw?1:0;document.getElementById('uwo').style.opacity=uw?1:0}
const HB=[1,2,3,11,5,8,9,19,21];let sel=0;const bar=document.getElementById('bar'),hud=document.getElementById('hud');
HB.forEach((b,i)=>{const d=document.createElement('div');d.className='s';d.innerHTML='<i>'+(i+1)+'</i>';d.onclick=()=>{sel=i;selUI()};bar.appendChild(d)});
const hbUI=()=>[...bar.children].forEach((d,i)=>{const sv=window.SVM,n=sv?(window.INV[HB[i]]||0):0;d.style.backgroundImage=sv&&!n?'none':ico(HB[i]);d.innerHTML='<i>'+(i+1)+'</i>'+(sv&&n?'<b>'+n+'</b>':'');d.style.opacity=1});hbUI();
const selUI=()=>[...bar.children].forEach((d,i)=>d.classList.toggle('on',i==sel));selUI();
const hl=new THREE.LineSegments(new THREE.EdgesGeometry(new THREE.BoxGeometry(1.004,1.004,1.004)),new THREE.LineBasicMaterial({color:0x111111}));scene.add(hl);
function ray(){
const d=new THREE.Vector3();cam.getWorldDirection(d);const o=cam.position;
d.x=d.x||1e-9;d.y=d.y||1e-9;d.z=d.z||1e-9;
let x=Math.floor(o.x),y=Math.floor(o.y),z=Math.floor(o.z),px=x,py=y,pz=z;
const sx=d.x>0?1:-1,sy=d.y>0?1:-1,sz=d.z>0?1:-1,dx=Math.abs(1/d.x),dy=Math.abs(1/d.y),dz=Math.abs(1/d.z);
let tx=(d.x>0?x+1-o.x:o.x-x)*dx,ty=(d.y>0?y+1-o.y:o.y-y)*dy,tz=(d.z>0?z+1-o.z:o.z-z)*dz,t=0;
while(t<REACH){const b=getB(x,y,z);if(b&&b!=7)return{x,y,z,px,py,pz};
px=x;py=y;pz=z;
if(tx<ty&&tx<tz){x+=sx;t=tx;tx+=dx}else if(ty<tz){y+=sy;t=ty;ty+=dy}else{z+=sz;t=tz;tz+=dz}}
return null}
const fixB=b=>{const d=(4-Math.round(yaw/1.5708))&3;return b>=40&&b<48?(b&~3)+d:b>=48&&b<52?48+d:b};
function act(b){window.SW=.3;
if(OD.sv&&b==0&&hitMob())return;
if(b==2&&FOOD[HB[sel]]){const fi=HB[sel];if(OD.sv&&INV[fi]>0&&hun<20){INV[fi]--;hun=Math.min(20,hun+FOOD[fi]);hbUI();snd(300,.1,1)}return}
const r=ray();if(!r)return;
if(b==0){if(OD.sv)return;const ob=getB(r.x,r.y,r.z);brkFx(r.x,r.y,r.z,ob);setB(r.x,r.y,r.z,0);const dd=DRP(ob);if(dd)dropItem(r.x+.5,r.y+.3,r.z+.5,dd);return}
{const hb=getB(r.x,r.y,r.z);if(OD.sv&&(hb==94||hb==95)){openCr(hb==94?1:2);return}if(hb==93){setB(r.x,r.y,r.z,0);primeTNT(r.x+.5,r.y+.5,r.z+.5);return}if(hb==31){sleepBed();return}if(hb>=48&&hb<56){[0,1,-1].forEach(dy=>{const q=getB(r.x,r.y+dy,r.z);if(q>=48&&q<56)setB(r.x,r.y+dy,r.z,q<52?q+4:q-4)});bsnd(hb,1);return}}
const X=r.px,Y=r.py,Z=r.pz;if(X==r.x&&Y==r.y&&Z==r.z)return;
if(X+1>P.x-.3&&X<P.x+.3&&Z+1>P.z-.3&&Z<P.z+.3&&Y+1>P.y&&Y<P.y+1.8)return;
const it=HB[sel];if(it>=167)return;if(OD.sv){if(!(INV[it]>0))return;INV[it]--;hbUI()}
const id=fixB(it);setB(X,Y,Z,id);bsnd(id,1)}
const K={};let JX=0,JY=0,playing=0,locked=0,wasLocked=0,drag=0,btn=-1,cd=0,lastSp=0;
function spawn(){P.x=8.5;P.z=8.5;P.y=Math.max(th(8,8),SEA)+2;vx=vy=vz=0}
function newWorld(){DIM=0;TL[7]=[8];meshes.forEach(ms=>ms.forEach(m=>{scene.remove(m);m.geometry.dispose()}));meshes.clear();ch.clear();ed={};seed=(Math.random()*1e9)|0;lc=null;spawn()}
addEventListener('keydown',e=>{
if(e.code=='Space')e.preventDefault();if(e.repeat)return;K[e.code]=1;
if(e.code=='Space'){const n=performance.now();if(n-lastSp<300){fly=!fly;vy=0}lastSp=n}
if(/^Digit[1-9]$/.test(e.code)){sel=+e.code[5]-1;selUI()}
if(e.code=='F3'){e.preventDefault();hud.style.display=hud.style.display=='none'?'':'none'}
if(e.code=='Escape'&&!locked)pause();
if(!playing)return;
if(e.code=='KeyN')newWorld();if(e.code=='KeyF')act(0);if(e.code=='KeyG')act(2)});
addEventListener('keyup',e=>K[e.code]=0);
cv.addEventListener('mousedown',e=>{if(!playing)return;if(locked){btn=e.button;act(e.button);cd=.25}else{drag=1;if(!TOUCH)lock()}});
addEventListener('mouseup',()=>{btn=-1;drag=0});
addEventListener('mousemove',e=>{if(locked||drag){yaw-=e.movementX*.0023*SNv;pitch=Math.max(-1.55,Math.min(1.55,pitch-e.movementY*.0023*SNv))}});
cv.addEventListener('contextmenu',e=>e.preventDefault());
addEventListener('wheel',e=>{sel=(sel+(e.deltaY>0?1:8))%9;selUI()},{passive:true});
const lock=()=>{try{const p=cv.requestPointerLock();if(p&&p.catch)p.catch(()=>{})}catch(e){}};
document.addEventListener('pointerlockchange',()=>{locked=document.pointerLockElement===cv?1:0;
if(locked)wasLocked=1;else if(wasLocked){wasLocked=0;pause()}});
if(TOUCH)document.body.classList.add('touch');
const $=id=>document.getElementById(id);
{const js=$('js'),kn=$('kn');let id=null;
const mv=e=>{const r=js.getBoundingClientRect();let[dx,dy]=TD((e.clientX-r.left-60)/50,(e.clientY-r.top-60)/50);const l=Math.hypot(dx,dy);if(l>1){dx/=l;dy/=l}JX=dx;JY=dy;kn.style.transform='translate('+dx*36+'px,'+dy*36+'px)'};
js.addEventListener('pointerdown',e=>{const n=performance.now();if(n-(window.LJ||0)<320){SPR=1;window.SPG=n+3000}window.LJ=n;window.JH=1;id=e.pointerId;js.setPointerCapture(id);mv(e)});
js.addEventListener('pointermove',e=>{if(e.pointerId==id)mv(e)});
const up=e=>{if(e.pointerId==id){id=null;window.JH=0;JX=JY=0;kn.style.transform=''}};
js.addEventListener('pointerup',up);js.addEventListener('pointercancel',up)}
{let lp=null,lx=0,ly=0,t0=0,mvd=0,hl=0;
cv.addEventListener('pointerdown',e=>{if(e.pointerType=='touch'&&lp==null){lp=e.pointerId;lx=e.clientX;ly=e.clientY;t0=performance.now();mvd=0;hl=0;cv.setPointerCapture(lp)}});
cv.addEventListener('pointermove',e=>{if(e.pointerId==lp){const[a,b]=TD(e.clientX-lx,e.clientY-ly);mvd+=Math.abs(e.clientX-lx)+Math.abs(e.clientY-ly);yaw-=a*.005;pitch=Math.max(-1.55,Math.min(1.55,pitch-b*.005));lx=e.clientX;ly=e.clientY}});
setInterval(()=>{if(lp!=null&&!hl&&playing&&performance.now()-t0>260&&mvd<14){hl=1;btn=0;act(0);cd=.25}},50);
const le=e=>{if(e.pointerId==lp){if(hl)btn=-1;else if(playing&&performance.now()-t0<260&&mvd<14)act(2);lp=null}};cv.addEventListener('pointerup',le);cv.addEventListener('pointercancel',le)}
const hold=(id,dn,up)=>{const b=$(id);b.addEventListener('pointerdown',e=>{e.preventDefault();dn()});['pointerup','pointercancel','pointerleave'].forEach(t=>b.addEventListener(t,up))};
hold('bb',()=>{btn=0;act(0);cd=.25},()=>{btn=-1});
hold('bp',()=>act(2),()=>{});
hold('bj',()=>{K.Space=1;const n=performance.now();if(n-lastSp<300){fly=!fly;vy=0}lastSp=n},()=>{K.Space=0});
hold('bf',()=>{K.ShiftLeft=1},()=>{K.ShiftLeft=0});
let SPR=0,SF=0,lastW=0;
addEventListener('keydown',e=>{if(e.code=='KeyW'&&!e.repeat){const n=performance.now();if(n-lastW<300)SPR=1;lastW=n}if(e.shiftKey)K.ShiftLeft=1});
addEventListener('keyup',e=>{if(e.code=='KeyW')SPR=0;if(!e.shiftKey&&e.code.startsWith('Shift'))K.ShiftLeft=0});
function hit(px,py,pz){const r=.3;
for(let x=Math.floor(px-r);x<=Math.floor(px+r);x++)for(let y=Math.floor(py);y<=Math.floor(py+1.79);y++)for(let z=Math.floor(pz-r);z<=Math.floor(pz+r);z++){const b=getB(x,y,z);if(SOL(b))return 1}
return 0}
function update(dt){
const f=(K.KeyW?1:0)-(K.KeyS?1:0)-JY,s=(K.KeyD?1:0)-(K.KeyA?1:0)+JX,sh=K.ShiftLeft||K.ShiftRight;
const inW=getB(Math.floor(P.x),Math.floor(P.y+.5),Math.floor(P.z))==7;
const sn=Math.sin(yaw),cs=Math.cos(yaw);let wx=-sn*f+cs*s,wz=-cs*f-sn*s;const l=Math.hypot(wx,wz);if(l>1){wx/=l;wz/=l}
if(f<=0&&!window.JH&&performance.now()>(window.SPG||0))SPR=0;const spr=((sh&&!fly)||SPR||K.ControlLeft||K.SprHold)&&f>0;SF+=((spr?(fly?12:7):0)-SF)*Math.min(1,dt*8);if(Math.abs(SF-(cam.fov-OD.fov))>.05){cam.fov=OD.fov+SF;cam.updateProjectionMatrix()}$('bs').style.opacity=SPR?1:.6;
let spd=fly?(spr?32:12):spr?6.6:4.3;if(inW&&!fly)spd*=.6;
const k=Math.min(1,dt*(fly?6:ground?14:4));vx+=(wx*spd-vx)*k;vz+=(wz*spd-vz)*k;
if(fly)vy+=(((K.Space?1:0)-(sh?1:0))*9-vy)*Math.min(1,dt*8);
else if(inW){vy=Math.max(vy-12*dt,-4);if(K.Space){vy=Math.min(vy+25*dt,4.2);if(getB(Math.floor(P.x),Math.floor(P.y+1.1),Math.floor(P.z))!=7)vy=Math.max(vy,8.2)}}
else{vy=Math.max(vy-28*dt,-50);if(K.Space&&ground)vy=8.6}
let n=P.x+vx*dt;if(!hit(n,P.y,P.z))P.x=n;else vx=0;
n=P.z+vz*dt;if(!hit(P.x,P.y,n))P.z=n;else vz=0;
ground=0;{const rem=vy*dt,stp=Math.max(1,Math.ceil(Math.abs(rem)/.35)),sd=rem/stp;for(let i=0;i<stp;i++){n=P.y+sd;if(!hit(P.x,n,P.z))P.y=n;else{if(vy<0){ground=1;P.y=Math.floor(n)+1}vy=0;break}}}
if(!fly)for(let q=0;q<4&&hit(P.x,P.y,P.z);q++)P.y=Math.floor(P.y+.001)+1;
if(ground&&fly)fly=0}
function placeCam(){cam.position.set(P.x,P.y+1.62,P.z);cam.rotation.set(pitch,yaw,0)}
let lc=null,list=[],want=new Set();
function stream(){
const pc=Math.floor(P.x/CS),pz=Math.floor(P.z/CS),key=pc+','+pz;
if(key!=lc){lc=key;list=[];want.clear();
for(let i=-RD;i<=RD;i++)for(let j=-RD;j<=RD;j++){const d=i*i+j*j;if(d<=RD*RD){list.push([pc+i,pz+j,d]);want.add(ck(pc+i,pz+j))}}
list.sort((a,b)=>a[2]-b[2]);
for(const[k,ms]of meshes)if(!want.has(k)){ms.forEach(m=>{scene.remove(m);m.geometry.dispose()});meshes.delete(k)}}
const t0=performance.now();
for(const[cx,cz]of list){if(meshes.has(ck(cx,cz)))continue;build(cx,cz);if(performance.now()-t0>8)break}}
function save(){if(!inG)return;try{localStorage.setItem('vc1',JSON.stringify({v:3,s:seed,e:ed,t:T,p:P,y:yaw,q:pitch,d:DIM}))}catch(e){}}
function TD(dx,dy){return window.PORT?(window.FR?[-dy,dx]:[dy,-dx]):[dx,dy]}
function rs(){window.PORT=TOUCH&&innerHeight>innerWidth;const w=window.PORT?innerHeight:innerWidth,h=window.PORT?innerWidth:innerHeight;document.body.classList.toggle('fl',!!window.PORT);document.body.classList.toggle('fr',!!window.FR);R.setSize(w,h,false);cam.aspect=w/h;cam.updateProjectionMatrix();mkRT()}
addEventListener('resize',rs);rs();
addEventListener('pagehide',save);setInterval(save,5000);
const OD=Object.assign({fov:70,sn:100,rd:TOUCH?5:12,sh:1,fx:TOUCH?0:1,vol:50,mus:50,fr:0,tx:0,sv:0,bgm:0,br:50},(()=>{try{return JSON.parse(localStorage.getItem('vco'))}catch(e){return 0}})());if(OD.tv!=2){OD.tx=0;OD.tv=2}
let st='ti',inG=0,pan=0,prev='ti';
const SC={};['ti','ws','ld','op','pa','iv','dt','cr'].forEach(k=>SC[k]=$(k));
const show=n=>{for(const k in SC)SC[k].style.display=k==n?'flex':'none';st=n;document.body.classList.toggle('ng',!inG)};
const has=()=>{try{return!!localStorage.getItem('vc1')}catch(e){return 0}};
function apply(){cam.fov=OD.fov;cam.updateProjectionMatrix();SNv=OD.sn/100;window.FR=OD.fr;window.SVM=OD.sv;if(window.TXS!=OD.tx){const ot=window.TXS,kOf=v=>v===undefined?-1:(v==0||v==2)?2:(v==1||v==5)?0:3,k0=kOf(ot),k1=kOf(OD.tx),sm=OD.tx==2||OD.tx==3;window.TXS=OD.tx;
if(OD.tx==0&&!window.ARd){mkAR();window.ARd=1}if(OD.tx==1&&!window.A2d){mkA2();window.A2d=1}if(OD.tx==2&&!window.A3d){mkA3();window.A3d=1}if(OD.tx==3&&!window.A4d){mkA4();window.A4d=1}if(OD.tx==4&&!window.A5d){mkA5();window.A5d=1}
window.AT=[ATR,A2,A3,A4,A5,A][OD.tx];UG=OD.tx==0?.0625:.01;US=OD.tx==0?.875:.98;tex2.image=window.AT;tex2.magFilter=sm?THREE.LinearFilter:THREE.NearestFilter;tex2.minFilter=THREE.LinearMipmapLinearFilter;tex2.needsUpdate=true;
for(const kk in GEO)delete GEO[kk];hid=-1;MT[0]=k1==2?MV0:k1==3?MV0:MS0;MT[5]=k1==2?MG0:MT[0];MT[2]=k1==2?MG2:MS2;meshes.forEach(ms=>ms.forEach(m=>{scene.remove(m);m.geometry.dispose()}));meshes.clear();lc=null}if(mzB)mzB.gain.value=OD.mus/100*.45;sunL.castShadow=!!OD.sh;R.shadowMap.needsUpdate=true;if(RD!=OD.rd){RD=OD.rd;lc=null}try{localStorage.setItem('vco',JSON.stringify(OD))}catch(e){}}
function pause(){if(!inG||!playing)return;playing=0;btn=-1;rainSound(0);show('pa')}
const go=()=>{inG=1;playing=1;show(null);if(!TOUCH)lock();if(!DIM&&hit(P.x,P.y,P.z)){const y2=safeY(Math.floor(P.x),Math.floor(P.z),H-4);if(y2)P.y=y2}};
function begin(nw){T=.04;if(nw)newWorld();else{meshes.forEach(ms=>ms.forEach(m=>{scene.remove(m);m.geometry.dispose()}));meshes.clear();lc=null}show('ld')}
function ldp(){const n=list.length;if(!n)return;const p=Math.min(1,meshes.size/Math.min(n,60));$('lb').style.width=p*100+'%';$('lt').textContent='地形を生成中 '+(p*100|0)+'%';if(p>=1)go()}
const B=(i,f)=>$(i).onclick=f;
B('b1',()=>{if(has()){$('wi').textContent='シード: '+seed;show('ws')}else begin(1)});
B('wp',()=>begin(0));B('wn',()=>begin(1));B('wc',()=>show('ti'));
B('wd',()=>{try{localStorage.removeItem('vc1')}catch(e){}show('ti')});
B('b2',()=>{prev='ti';show('op')});B('p2',()=>{prev='pa';show('op')});B('od',()=>show(prev));
B('b3',()=>{document.body.innerHTML='<p style="color:#fff;text-align:center;margin-top:40vh;font:16px sans-serif">ゲームを終了しました。タブを閉じてください。</p>'});
B('p1',()=>{playing=1;show(null);if(!TOUCH)lock()});
B('p4',()=>{playing=1;show(null);if(!TOUCH)lock();warp((DIM+1)%4,DIM)});
B('p3',()=>{save();inG=0;hg.visible=false;pm.visible=false;playing=0;try{document.exitPointerLock()}catch(e){}show('ti')});
const lockL=()=>{if(!TOUCH)return;const o=screen.orientation,d=document.documentElement,L=()=>o&&o.lock&&o.lock('landscape').catch(()=>{});try{L();if(!document.fullscreenElement&&d.requestFullscreen)d.requestFullscreen().then(L).catch(()=>{})}catch(e){}};addEventListener('pointerdown',lockL,{once:true});
$('bz').onclick=pause;$('bi').onclick=inv;{const b=$('bs');let lt=0;b.addEventListener('pointerdown',e=>{const n=performance.now();if(n-lt<320){SPR=1;window.SPG=n+3000}else K.SprHold=1;lt=n;b.setPointerCapture(e.pointerId)});const u=()=>{K.SprHold=0};b.addEventListener('pointerup',u);b.addEventListener('pointercancel',u)}$('ic').onclick=inv;$('iv').onclick=e=>{if(e.target.id=='iv')inv()};
function inv(){if(st=='iv'){playing=1;show(null);if(!TOUCH)lock()}else{playing=0;btn=-1;ivRef();show('iv');try{document.exitPointerLock()}catch(e){}}}
addEventListener('keydown',e=>{if(!inG)return;if(st=='iv'&&(e.code=='KeyE'||e.code=='Escape'))inv();else if(st=='cr'&&(e.code=='KeyE'||e.code=='Escape'))closeCr();else if(playing&&e.code=='KeyE')inv()});
const NM={1:'草ブロック',2:'土',3:'石',4:'砂',5:'オークの原木',6:'葉',8:'オークの板材',9:'ガラス',10:'レンガ',11:'丸石',12:'砂岩',13:'雪の草ブロック',14:'砂利',15:'石炭鉱石',16:'鉄鉱石',17:'金鉱石',18:'ダイヤモンド鉱石',19:'石レンガ',20:'赤色の羊毛',21:'グロウストーン',22:'サボテン',23:'氷',24:'黒曜石',25:'金ブロック',26:'ダイヤモンドブロック',27:'テラコッタ',28:'岩盤',29:'オークのハーフブロック',30:'丸石のハーフブロック',33:'松明',34:'ポピー',35:'タンポポ',36:'草',40:'オークの階段',44:'丸石の階段',48:'オークのドア'};
Object.assign(NM,{164:'ネザーポータル',165:'エンドポータル',166:'シフトポータル',167:'生肉',168:'棒',169:'石炭',170:'ダイヤモンド',171:'鉄インゴット',172:'金インゴット',173:'木のツルハシ',174:'石のツルハシ',175:'鉄のツルハシ',176:'ダイヤのツルハシ',31:'ベッド',193:'木の剣',194:'石の剣',195:'鉄の剣',196:'ダイヤの剣',197:'鉄の防具',198:'ダイヤの防具',199:'リンゴ',200:'ステーキ',201:'苔ブロック',202:'鍾乳石',203:'サクラの葉',204:'サクラの原木',205:'サクラの板材',32:'タケ'});NB.forEach((r,i)=>NM[56+i]=r[0]);CL.forEach(([c],i)=>NM[177+i]=c+'のガラス');Object.keys(NM).forEach(k=>{const d=document.createElement('div');d.className='it';d.style.backgroundImage=ico(+k);d.onmouseenter=()=>{$('in').textContent=NM[k]};d.onmousemove=e=>{const T_=$('tt');T_.textContent=NM[k];T_.style.display='block';T_.style.left=e.clientX+12+'px';T_.style.top=e.clientY-8+'px'};d.onmouseleave=()=>{$('tt').style.display='none'};d.onclick=()=>{$('in').textContent=NM[k]+' → スロット'+(sel+1);HB[sel]=+k;hbUI()};$('ig').appendChild(d)});
[['視野角','fov',30,110,v=>v==70?'標準':v],['感度','sn',0,200,v=>v==100?'標準':v+'%'],['明るさ','br',0,100,v=>v==50?'標準':v+'%'],['音量','vol',0,100,v=>v+'%'],['音楽','mus',0,100,v=>v+'%'],['描画距離','rd',2,32,v=>v+'チャンク']].forEach(([n,k,a,b,f])=>{const d=document.createElement('label');d.className='mb sl';d.innerHTML='<i></i><span></span><input type=range min='+a+' max='+b+'>';const i=d.querySelector('input'),s=d.querySelector('span');i.value=OD[k];const u=()=>{s.textContent=n+': '+f(+i.value);d.firstChild.style.width=(i.value-a)/(b-a)*100+'%'};u();i.oninput=()=>{OD[k]=+i.value;u();apply()};$('ol').appendChild(d)});
const tg=(t,f)=>{const b=document.createElement('button');b.className='mb';b.onclick=()=>{f();b.textContent=t()};b.textContent=t();$('ol').appendChild(b)};
const rIc=()=>{hbUI();[...$('ig').children].forEach((d,i)=>d.style.backgroundImage=ico(+Object.keys(NM)[i]))};
const mzNm=()=>{try{return['ランダム'].concat(mzPCS.map(p=>p.n))}catch(e){return['ランダム']}};
tg(()=>'BGM: '+mzNm()[OD.bgm%mzNm().length],()=>{OD.bgm=(OD.bgm%(mzPCS.length+1)+1)%(mzPCS.length+1);mzQ=null;if(AC)mzN=AC.currentTime+.5});
tg(()=>'ゲームモード: '+(OD.sv?'サバイバル':'クリエイティブ'),()=>{OD.sv^=1;apply();hp=20;hun=20;lastSt='x';hbUI()});
tg(()=>'テクスチャ: '+['標準（リアル）','ポップ（アニメ調）','つるつる鏡面','バニラ・リアル','バニラ（本家風・反射なし）','ドット絵（旧標準）'][OD.tx],()=>{OD.tx=(OD.tx+1)%6;apply();rIc()});
if(TOUCH)tg(()=>'横表示の向き: '+(OD.fr?'右回り':'左回り'),()=>{OD.fr^=1;apply();rs()});
tg(()=>'シェーダー: '+(OD.fx?'ON':'OFF'),()=>{OD.fx^=1;apply()});
tg(()=>'影: '+(OD.sh?'ON':'OFF'),()=>{OD.sh^=1;apply()});
tg(()=>'全画面表示: '+(document.fullscreenElement?'OFF':'ON'),()=>{try{document.fullscreenElement?document.exitFullscreen():document.documentElement.requestFullscreen()}catch(e){}});
tg(()=>'操作設定...',()=>{$('ct').hidden=!$('ct').hidden});
{const c=document.createElement('canvas');c.width=c.height=16;const g=c.getContext('2d');for(let y=0;y<16;y++)for(let x=0;x<16;x++){const k=(.6+Math.random()*.4)*.8;g.fillStyle='rgb('+[134*k|0,102*k|0,63*k|0]+')';g.fillRect(x,y,1,1)}document.documentElement.style.setProperty('--dirt','url('+c.toDataURL()+')')}
$('sp').textContent=['ブロックを積もう！','100%ボクセル！','Three.js製！','ダブルジャンプで飛行！','夜も楽しもう！','ファンメイド！'][Math.random()*6|0];
let AC;function snd(f,d,n,v,lp,dl){if(!OD.vol)return;try{AC=AC||new AudioContext();const sr=AC.sampleRate,b=AC.createBuffer(1,sr*d|0,sr),a=b.getChannelData(0);for(let i=0;i<a.length;i++)a[i]=(n?Math.random()*2-1:Math.sin(i/(sr/f)*6.28))*(1-i/a.length);const o=AC.createBufferSource(),g=AC.createGain();g.gain.value=OD.vol/200*(v||1);o.buffer=b;let l=o;if(lp){const q=AC.createBiquadFilter();q.type='lowpass';q.frequency.value=lp;o.connect(q);l=q}l.connect(g);g.connect(window.SFX||(window.SFX=(()=>{const f=AC.createBiquadFilter();f.type='lowpass';f.frequency.value=22000;f.connect(AC.destination);return f})()));o.start(AC.currentTime+(dl||0))}catch(e){}}
const MB=[],MM={},ML=c=>MM[c]||(MM[c]=new THREE.MeshLambertMaterial({color:c})),SB=(x,y,z)=>SOL(getB(Math.floor(x),Math.floor(y),Math.floor(z)));let spT=0;
const mbx=(g,c,w,h,d,x,y,z)=>{const m=new THREE.Mesh(new THREE.BoxGeometry(w,h,d),ML(c));m.position.set(x,y,z);m.castShadow=true;g.add(m);return m};
const TXC={},jt=(h,v)=>{const k=1+(Math.random()-.5)*v;return'rgb('+[h>>16&255,h>>8&255,h&255].map(q=>Math.min(255,q*k|0))+')'};
const tm=(key,fn)=>TXC[key]||(TXC[key]=(()=>{const c=document.createElement('canvas');c.width=c.height=8;const g=c.getContext('2d');for(let y=0;y<8;y++)for(let x=0;x<8;x++){g.fillStyle=fn(x,y);g.fillRect(x,y,1,1)}const t=new THREE.CanvasTexture(c);t.magFilter=t.minFilter=THREE.NearestFilter;return new THREE.MeshLambertMaterial({map:t})})());
const pl=(k,h,v)=>tm(k,()=>jt(h,v||.18)),fcm=(k,base,rows,cm)=>tm(k,(x,y)=>{const c=cm[rows[y][x]];return c!=null?jt(c,.08):jt(base,.16)});
const mbt=(g,m,w,h,d,x,y,z)=>{const o=new THREE.Mesh(new THREE.BoxGeometry(w,h,d),m);o.position.set(x,y,z);o.castShadow=true;g.add(o);return o};
const hd=(k,base,rows,cm)=>{const s=pl(k,base);return[s,s,s,s,s,fcm(k+'f',base,rows,cm)]};
const hz=(a,b,c)=>{let h=Math.imul(a+7,374761393)^Math.imul(b+13,668265263)^Math.imul(c+29,1274126177);h=Math.imul(h^h>>>13,1274126177);return((h^h>>>16)>>>0)/4294967296};
const T6=(key,sd,base,fn,n)=>TXC[key]||(TXC[key]=(()=>{const ms=[];for(let f=0;f<6;f++){const c=document.createElement('canvas');c.width=c.height=16;const g=c.getContext('2d');
for(let y=0;y<16;y++)for(let x=0;x<16;x++){let col=fn?fn(f,x,y):null;if(col==null)col=base;const k=(1+(hz(x,y,f+sd)-.5)*(n==null?.1:n))*(f<2||f>3?1-.1*y/15:1);
g.fillStyle='rgb('+[col>>16&255,col>>8&255,col&255].map(q=>Math.min(255,q*k|0))+')';g.fillRect(x,y,1,1)}
const t=new THREE.CanvasTexture(c);t.magFilter=t.minFilter=THREE.NearestFilter;ms.push(new THREE.MeshLambertMaterial({map:t}))}return ms})());
const eyeF=(f,x,y,l)=>f==5&&y>=l&&y<=l+1?(x==2||x==3||x==12||x==13?0xf4f4f4:x==4||x==11?0x1c1c2c:null):null;
function mkMob(t){const g=new THREE.Group(),L=[],E=0x111111;
if(t==0){const b=0xf0a0a0,pb=T6('pgb',1,b,(f,x,y)=>f==3||y>12?0xe08c8c:f==2&&hz(x>>2,y>>2,5)<.25?0xf6b0b0:null,.08);mbt(g,pb,.6,.55,1,0,.7,0);
mbt(g,T6('pgh',2,b,(f,x,y)=>eyeF(f,x,y,6),.08),.45,.45,.45,0,.95,-.65);
mbt(g,T6('pgs',3,0xe28f8f,(f,x,y)=>f==5&&(x==4||x==5||x==10||x==11)&&y>=5&&y<=9?0x8e4848:f==5&&(y==0||y==15)?0xd47c7c:null,.06),.22,.16,.1,0,.88,-.92);
for(const x of[-.17,.17])mbt(g,T6('pge',4,0xe89494,null,.1),.12,.1,.06,x,1.2,-.6);mbt(g,T6('pgt',5,0xe08c8c,null),.06,.06,.1,0,.88,.54);
for(const x of[-.2,.2])for(const z of[-.3,.3])L.push(mbt(g,T6('pgl',6,b,(f,x,y)=>y>=12?0xc07878:null,.1),.18,.4,.18,x,.2,z))}
else if(t==1){const w=0xe8e4dc,d=0x3a2a22,bd=T6('cwb',7,w,(f,x,y)=>{if(f==3)return 0xd8d2c8;const m=hz(x>>2,y>>2,f+11)*.6+hz((x+2)>>3,(y+1)>>3,f+21)*.4;return m<.34?d:null},.09);mbt(g,bd,.6,.55,1,0,.7,0);
mbt(g,T6('cwh',8,d,(f,x,y)=>{if(f==5){if(y>=9&&x>=4&&x<=11)return(y==11||y==12)&&(x==5||x==10)?0x4a3a34:0xc9b5a2;return eyeF(f,x,y,6)}return f==2&&x>=6&&x<=9?0xe8e4dc:null},.1),.45,.45,.45,0,.95,-.65);
for(const x of[-.22,.22])mbt(g,T6('cwr',9,0xe6dfc8,(f,x,y)=>y>12?0x9a9482:null,.06),.08,.14,.08,x,1.22,-.62);
mbt(g,T6('cwu',10,0xe9a9a9,null,.08),.22,.1,.24,0,.37,.3);
for(const x of[-.2,.2])for(const z of[-.3,.3])L.push(mbt(g,T6('cwl',12,w,(f,x,y)=>y>=12?0x4a4038:(f<2||f>3)&&hz(x>>2,y>>2,3)<.3&&y<5?d:null,.1),.18,.4,.18,x,.2,z))}
else if(t==2){const wl=T6('swb',13,0xeceae4,(f,x,y)=>{const c=hz(x>>1,y>>1,f+31);return c<.25?0xd4d2ca:c>.78?0xf8f7f2:null},.12);mbt(g,wl,.68,.62,1.04,0,.74,0);
mbt(g,T6('swh',14,0xa89478,(f,x,y)=>{if(f==5){if(y>=10&&y<=11&&x>=6&&x<=9)return 0xd8a09a;if(y==13&&x>=5&&x<=10)return 0x7a6a56;return eyeF(f,x,y,6)}return null},.1),.4,.4,.4,0,.95,-.65);
mbt(g,wl,.44,.12,.42,0,1.2,-.6);for(const x of[-.26,.26])mbt(g,T6('swe',15,0xa08c70,null,.1),.1,.07,.16,x,1.04,-.62);
for(const x of[-.2,.2])for(const z of[-.3,.3])L.push(mbt(g,T6('swl',16,0x9a8a72,(f,x,y)=>y>=12?0x403830:y<6?0xeceae4:null,.1),.16,.4,.16,x,.2,z))}
else if(t==3){const r=0x6b4a2b,k=0xc89a78;mbt(g,pl('vr',r),.5,.75,.3,0,1.1,0);mbt(g,hd('vh',k,['........','........','........','.GG..GG.','...NN...','...NN...','...NN...','........'],{G:0x3a8a3a,N:0xa8764f}),.45,.55,.45,0,1.65,0);mbt(g,pl('va',r),.6,.2,.22,0,1.15,-.2);for(const x of[-.12,.12])L.push(mbt(g,pl('vr',r),.22,.7,.22,x,.35,0))}
else if(t==4){const sk=0x4f8a4f;mbt(g,hd('zh',sk,['........','........','........','.EE..EE.','...NN...','..MMMM..','..M..M..','........'],{E:0x111122,N:0x3a6a3a,M:0x2a4a2a}),.5,.5,.5,0,1.75,0);mbt(g,pl('zt',0x1f9a9a),.5,.75,.25,0,1.125,0);for(const x of[-.375,.375])mbt(g,pl('zs',sk),.25,.25,.7,x,1.4,-.32);for(const x of[-.125,.125])L.push(mbt(g,pl('zl',0x2b2f8f),.25,.75,.25,x,.375,0))}
else if(t==5){const gr=0x4ea44a,m=tm('cr',(x,y)=>(x*7+y*3)%5<2?jt(0x2d6a2a,.2):jt(gr,.25));mbt(g,[m,m,m,m,m,fcm('crf',gr,['........','.XX..XX.','.XX..XX.','...XX...','..XXXX..','..XXXX..','..X..X..','........'],{X:0x101810})],.5,.5,.5,0,1.375,0);mbt(g,m,.5,.75,.25,0,.75,0);for(const x of[-.125,.125])for(const z of[-.125,.125])L.push(mbt(g,m,.25,.375,.25,x,.1875,z))}
else if(t==7){const w=0xf4f4f0;mbt(g,T6('ckb',17,w,(f,x,y)=>hz(x>>1,y>>1,f+41)<.2?0xe2e2dc:null,.08),.35,.3,.5,0,.45,0);
mbt(g,T6('ckh',18,w,(f,x,y)=>f==5?(y>=5&&y<=6?(x==2||x==3?0x181818:x==12||x==13?0x181818:null):null):null,.06),.2,.22,.2,0,.72,-.3);
mbt(g,T6('ckk',19,0xf0a030,null,.05),.12,.06,.1,0,.69,-.45);mbt(g,T6('ckw',20,0xc42020,null,.06),.05,.1,.04,0,.62,-.43);mbt(g,T6('ckc',21,0xc42020,null,.06),.05,.07,.12,0,.86,-.3);
for(const x of[-.2,.2])mbt(g,T6('ckg',22,0xe6e6e0,(f,x,y)=>y>11?0xcfcfc8:null,.08),.05,.2,.3,x,.46,0);mbt(g,T6('ckt',23,w,null,.1),.1,.16,.05,0,.6,.28);
for(const x of[-.08,.08])L.push(mbt(g,T6('ckl',24,0xe8b040,(f,x,y)=>y>12?0xd09028:null,.08),.06,.25,.06,x,.12,0))}
 else if(t==8){const sp=0x3a3030;mbt(g,pl('spb',sp,.2),.7,.35,.55,0,.5,.15);mbt(g,hd('sph',sp,['........','.R....R.','.RR..RR.','........','..WWWW..','..W..W..','........','........'],{R:0xc01010,W:0xd8d0c0}),.4,.35,.4,0,.5,-.4);for(const z of[-.15,0,.15,.3])for(const x of[-1,1])mbt(g,pl('spl',0x2a2020),.5,.06,.06,x*.5,.4,z)}
 else{const bn=0xcfcfc0;mbt(g,hd('kh',bn,['........','........','.EE..EE.','.EE..EE.','...NN...','..MMMM..','..M..M..','........'],{E:0x1a1a1a,N:0x707068,M:0x4a4a44}),.5,.5,.5,0,1.75,0);mbt(g,tm('kt',(x,y)=>y%2?jt(0x6a6a62,.1):jt(bn,.1)),.5,.75,.25,0,1.125,0);for(const x of[-.31,.31])mbt(g,pl('ka',bn),.125,.75,.125,x,1.2,-.1).rotation.x=-.6;for(const x of[-.125,.125])L.push(mbt(g,pl('kl',bn),.125,.75,.125,x,.375,0))}
return{g,L}}
let pcd=0;
const safeY=(x,z,top)=>{for(let y=top;y>1;y--)if(SOL(getB(x,y,z))&&!SOL(getB(x,y+1,z))&&!SOL(getB(x,y+2,z))&&getB(x,y+1,z)!=7)return y+1;return 0};
function mkPortal(x,y,z,pid){for(let i=0;i<4;i++)for(let j=-1;j<=3;j++){const e=i==0||i==3||j==-1||j==3;setB(x+i,y+j,z,e?24:pid);setB(x+i,y+j,z-1,j<0?24:0);setB(x+i,y+j,z+1,j<0?24:0)}}
function warp(d,old){const v=OD.vol;OD.vol=0;
meshes.forEach(ms=>ms.forEach(m=>{scene.remove(m);m.geometry.dispose()}));meshes.clear();lc=null;MB.forEach(m=>scene.remove(m.g));MB.length=0;
DIM=d;TL[7]=[d==1?89:8];
const x=d==2?0:Math.floor(P.x),z=d==2?0:Math.floor(P.z);let y=safeY(x,z,d==1?64:H-4);
if(!y){y=40;for(let i=-2;i<=2;i++)for(let j=-2;j<=2;j++){setB(x+i,y-1,z+j,d==1?77:d==2?24:131);for(let k=0;k<3;k++)setB(x+i,y+k,z+j,0)}}
P.x=x+.5;P.y=y;P.z=z+.5;vx=vy=vz=0;pcd=3;fallMax=y;mkPortal(x+3,y,z,163+(d||old));OD.vol=v}
function portal(dt){pcd-=dt;if(P.y<-30){warp(DIM,DIM);return}
const b=getB(Math.floor(P.x),Math.floor(P.y+.6),Math.floor(P.z));if(pcd<=0&&b>163&&b<167)warp(DIM?0:b-163,DIM)}
const INV={};window.INV=INV;
const mat=b=>b==4||b==14||b==102?3:b==9||b==23||b==103||b==108||b==111||(b>=177&&b<=192)?4:b==6||b==33||(b>=34&&b<=36)||((b>=66&&b<=70)||b==203)||(b>=115&&b<=130)||b==96||b==97||b==106||b==109||b==93||b==167||b==31?5:(b==25||b==26||(b>=86&&b<=91))?6:(b==1||b==2||b==13||(b>=98&&b<=101)||b==112||b==201)?1:(b==5||b==8||b==29||(b>=40&&b<=43)||(b>=48&&b<=55)||(b>=56&&b<=65)||b==92||b==94||b==32||b==204||b==205)?2:0;
const SND=[[[140,.12,0],[0,.06,1]],[[90,.1,0],[0,.09,1]],[[210,.14,0],[330,.08,0]],[[0,.16,1],[0,.1,1]],[[1700,.12,0],[2300,.09,0]],[[0,.09,1]],[[700,.2,0],[1100,.15,0]]];
const sfxBus=()=>window.SFX||(window.SFX=(()=>{const f=AC.createBiquadFilter();f.type='lowpass';f.frequency.value=22000;f.connect(AC.destination);return f})());
function pop(v){if(!OD.vol)return;try{AC=AC||new AudioContext();const t=AC.currentTime,o=AC.createOscillator(),g=AC.createGain(),k=1+(Math.random()-.5)*.1;o.type='sine';o.frequency.setValueAtTime(1000*k,t);o.frequency.exponentialRampToValueAtTime(2000*k,t+.04);g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(OD.vol/100*.4*(v||1),t+.003);g.gain.exponentialRampToValueAtTime(.001,t+.075);g.gain.linearRampToValueAtTime(0,t+.085);o.connect(g);g.connect(sfxBus());o.start(t);o.stop(t+.09)}catch(e){}}
function glassSnd(soft){if(!OD.vol)return;try{AC=AC||new AudioContext();const t=AC.currentTime,vol=OD.vol/100,B=sfxBus(),n=soft?3:12,sr=AC.sampleRate;
 const nb=AC.createBuffer(1,sr*.14|0,sr),a=nb.getChannelData(0);for(let i=0;i<a.length;i++)a[i]=(Math.random()*2-1)*Math.pow(1-i/a.length,3);const ns=AC.createBufferSource(),hp=AC.createBiquadFilter(),ng=AC.createGain();ns.buffer=nb;hp.type='highpass';hp.frequency.value=2600;ng.gain.value=vol*(soft?.18:.5);ns.connect(hp);hp.connect(ng);ng.connect(B);ns.start(t);
 if(!soft){const o=AC.createOscillator(),g=AC.createGain();o.type='sine';o.frequency.setValueAtTime(260,t);o.frequency.exponentialRampToValueAtTime(110,t+.06);g.gain.setValueAtTime(vol*.3,t);g.gain.exponentialRampToValueAtTime(.001,t+.07);o.connect(g);g.connect(B);o.start(t);o.stop(t+.08)}
 for(let i=0;i<n;i++){const o=AC.createOscillator(),o2=AC.createOscillator(),g=AC.createGain(),f=2400+Math.random()*5200,st=t+Math.random()*(soft?.05:.2),d=.04+Math.random()*(soft?.07:.16);o.type='sine';o2.type='sine';o.frequency.value=f;o2.frequency.value=f*(1.5+Math.random()*.9);g.gain.setValueAtTime(0,st);g.gain.linearRampToValueAtTime(vol*(soft?.07:.13)*(.5+Math.random()*.5),st+.002);g.gain.exponentialRampToValueAtTime(.0005,st+d);const g2=AC.createGain();g2.gain.value=.35;o.connect(g);o2.connect(g2);g2.connect(g);g.connect(B);o.start(st);o2.start(st);o.stop(st+d+.02);o2.stop(st+d+.02)}}catch(e){}}
const bsnd=(b,p)=>mat(b)==4?glassSnd(!!p):SND[mat(b)].forEach(([f,d,n])=>snd(f*(p?1.25:1),d,n));
const HRD=b=>b==28?1e9:[2,.6,1.4,.5,.35,.25,3.2][mat(b)]*(b==24?4:1)*((b>=15&&b<=18)||(b>=82&&b<=85)?1.5:1)*(b==33||(b>=34&&b<=36)?.1:1);
const DRP=b=>b==15?169:b==18?170:b==1||b==13||b==99||b==100?2:b==3?11:(b==28||b==7||(b>163&&b<167)||b==9||b==23||b==103||b==6||((b>=66&&b<=70)||b==203)||(b>=177&&b<=192))?0:(b>=40&&b<48)?(b>=44?44:40):(b>=48&&b<56)?48:b;
const BC={},bcol=b=>BC[b]||(()=>{const t=TL[b]||[3],i=t[1]||t[0],d=A.getContext('2d').getImageData((i&7)*16,(i>>3)*16,16,16).data;let r=0,g=0,u=0,n=0;for(let k=0;k<d.length;k+=4)if(d[k+3]){r+=d[k];g+=d[k+1];u+=d[k+2];n++}n=n||1;const tn=TN[b]||[1,1,1];return BC[b]=[r/n/255*tn[0],g/n/255*tn[1],u/n/255*tn[2]]})();
function mkPS(add,size,max){const g=new THREE.BufferGeometry(),p=new Float32Array(max*3),c=new Float32Array(max*3);g.setAttribute('position',new THREE.BufferAttribute(p,3));g.setAttribute('color',new THREE.BufferAttribute(c,3));const m=new THREE.Points(g,new THREE.PointsMaterial({size,vertexColors:true,transparent:true,depthWrite:false,blending:add?THREE.AdditiveBlending:THREE.NormalBlending}));m.frustumCulled=false;scene.add(m);return{g,p,c,a:[],max,add}}
const PF=mkPS(1,.16,160),PB=mkPS(0,.12,240),padd=(S,o)=>{if(S.a.length<S.max)S.a.push(o)};
function pfx(S,dt){for(let i=S.a.length-1;i>=0;i--){const q=S.a[i];q.l-=dt;if(q.l<=0){S.a.splice(i,1);continue}q.vy-=q.gr*dt;q.x+=q.vx*dt;q.y+=q.vy*dt;q.z+=q.vz*dt}
S.a.forEach((q,i)=>{const f=S.add?Math.min(1,q.l*3):1;S.p[i*3]=q.x;S.p[i*3+1]=q.y;S.p[i*3+2]=q.z;S.c[i*3]=q.r*f;S.c[i*3+1]=q.g*f;S.c[i*3+2]=q.b*f});
S.g.setDrawRange(0,S.a.length);S.g.attributes.position.needsUpdate=S.g.attributes.color.needsUpdate=true}
function brkFx(x,y,z,b){const c=bcol(b);for(let i=0;i<14;i++){const k=.8+Math.random()*.4;padd(PB,{x:x+Math.random(),y:y+Math.random(),z:z+Math.random(),vx:(Math.random()-.5)*3,vy:Math.random()*3,vz:(Math.random()-.5)*3,l:.7+Math.random()*.4,gr:14,r:c[0]*k,g:c[1]*k,b:c[2]*k})}bsnd(b,0)}
const TOR=new Map(),TLG=[0,1,2,3].map(()=>{const l=new THREE.PointLight(0xffa850,0,13,1.4);scene.add(l);return l});let tq=0,tNear=[];
function torchTick(dt){tq-=dt;if(tq<=0){tq=.25;tNear=[];TOR.forEach((a,k)=>{if(!meshes.has(k))return;for(let i=0;i<a.length;i+=3){const d=(a[i]-P.x)**2+(a[i+1]-P.y)**2+(a[i+2]-P.z)**2;if(d<400)tNear.push([d,a[i],a[i+1],a[i+2]])}});tNear.sort((a,b)=>a[0]-b[0]);PG.p.fill(0);tNear.slice(0,16).forEach((t,i)=>{PG.p[i*3]=t[1];PG.p[i*3+1]=t[2]-.05;PG.p[i*3+2]=t[3]});PG.g.setDrawRange(0,Math.min(16,tNear.length));PG.g.attributes.position.needsUpdate=true}
PG.m.material.size=1.5+.15*Math.sin(performance.now()/110);
TLG.forEach((l,i)=>{const t=tNear[i];if(t){l.position.set(t[1],t[2],t[3]);l.intensity=2.4*(.9+.1*Math.sin(performance.now()/90+i*3))}else l.intensity=0});
tNear.slice(0,6).forEach(t=>{if(Math.random()<dt*10)padd(PF,{x:t[1]+(Math.random()-.5)*.15,y:t[2]+.1,z:t[3]+(Math.random()-.5)*.15,vx:(Math.random()-.5)*.3,vy:.5+Math.random()*.6,vz:(Math.random()-.5)*.3,l:.5+Math.random()*.4,gr:-.2,r:1,g:.55+Math.random()*.3,b:.15})})}
const IT=[];
function dropItem(x,y,z,b,n){const m=new THREE.Mesh(itemGeo(b),HM2);m.scale.setScalar(FLAT(b)?.4:.25);m.position.set(x,y,z);m.castShadow=true;scene.add(m);IT.push({m,b,x,y,z,vx:(Math.random()-.5)*2,vy:3,vz:(Math.random()-.5)*2,t:0,n:n||1})}
function itemTick(dt){for(let i=IT.length-1;i>=0;i--){const q=IT[i];q.t+=dt;q.vy-=20*dt;let ny=q.y+q.vy*dt;if(SB(q.x,ny-.12,q.z)){ny=Math.floor(ny-.12)+1.12;q.vy=0;q.vx*=.8;q.vz*=.8}q.x+=q.vx*dt;q.z+=q.vz*dt;q.y=ny;q.m.position.set(q.x,q.y+Math.sin(q.t*3)*.05+.08,q.z);q.m.rotation.y=q.t*2;
if((Math.hypot(q.x-P.x,q.y-P.y-.8,q.z-P.z)<1.6&&q.t>.5)||q.t>300||q.y<-20){if(q.t<=300&&q.y>=-20){if(OD.sv)give(q.b,q.n);pop()}scene.remove(q.m);IT.splice(i,1)}}}
let hp=20,hun=20,hungT=0,hurtT=0,fT=0,regT=0,dead=0,fallMax=0,brk=null,lastSt='';
function stUI(){$('xp').style.display=OD.sv?'block':'none';const h=Math.ceil(hp/2),g=Math.ceil(hun/2);$('st').innerHTML=OD.sv?'<span style=color:#e83a3a>'+'♥'.repeat(h)+'</span><span style=color:#555>'+'♥'.repeat(10-h)+'</span> <span style=color:#d89030>'+'●'.repeat(g)+'</span><span style=color:#555>'+'●'.repeat(10-g)+'</span>'+(air<10?' <span style=color:#6ac8ff>'+'○'.repeat(Math.max(0,Math.ceil(air)))+'</span>':''):''}
function hurt(n){if(!OD.sv||dead||hurtT>0)return;n=Math.max(1,Math.round(n*(1-armorPts()*.04)));hp-=n;hurtT=.8;snd(120,.15,0);stUI();document.body.style.boxShadow='inset 0 0 80px #f00a';setTimeout(()=>document.body.style.boxShadow='',200);if(hp<=0){dead=1;playing=0;btn=-1;try{document.exitPointerLock()}catch(e){}show('dt')}}
B('rs1',()=>{hp=20;hun=20;dead=0;hurtT=1;lastSt='x';if(DIM)warp(0,DIM);else spawn();playing=1;show(null);if(!TOUCH)lock()});
function survTick(dt){if(!OD.sv){if(lastSt!==''){lastSt='';stUI()}return}
if(dead)return;hurtT-=dt;const w=getB(Math.floor(P.x),Math.floor(P.y+.5),Math.floor(P.z))==7;
if(ground){if(!fly&&!w&&fallMax-P.y>3.5)hurt(Math.floor(fallMax-P.y-3));fallMax=P.y}else fallMax=(fly||w)?P.y:Math.max(fallMax,P.y);
hungT+=dt*(1+Math.hypot(vx,vz)/4);if(hungT>30){hungT=0;if(hun>0)hun--}
if(hun<=0){fT+=dt;if(fT>4){fT=0;if(hp>1)hurt(1)}}else if(hun>=18&&hp<20){regT+=dt;if(regT>3){regT=0;hp++}}
const hw=getB(Math.floor(P.x),Math.floor(P.y+1.6),Math.floor(P.z))==7;if(hw){air-=dt;if(air<=0){air=0;drT-=dt;if(drT<=0){drT=1;hurt(2)}}}else air=Math.min(10,air+dt*5);if(w&&DIM==1){lavaT-=dt;if(lavaT<=0){lavaT=.5;hurt(2)}}const q=hp+','+hun+','+Math.ceil(air);if(q!=lastSt){lastSt=q;stUI()}}
function brkTick(dt){const e=document.getElementById('pg');crackM.visible=false;
if(!OD.sv||btn!=0||!playing){brk=null;e.style.display='none';return}
const r=ray();if(!r){brk=null;e.style.display='none';return}
const b=getB(r.x,r.y,r.z);if(!brk||brk.x!=r.x||brk.y!=r.y||brk.z!=r.z)brk={x:r.x,y:r.y,z:r.z,t:0};
brk.t+=dt;const tl=tool(),need=HRD(b)/((mat(b)==0||mat(b)==6)&&tl?1+tl*1.2:1);crackM.visible=true;crackM.position.set(r.x+.5,r.y+.5,r.z+.5);crackM.material.map=CRK[Math.min(9,Math.floor(brk.t/need*10))];e.style.display='block';e.style.background='linear-gradient(90deg,#fff '+Math.min(100,brk.t/need*100)+'%,#0006 0)';
if(brk.t>=need){const d=tool()>=REQ(b)?DRP(b):0;brkFx(r.x,r.y,r.z,b);setB(r.x,r.y,r.z,0);if(d)dropItem(r.x+.5,r.y+.3,r.z+.5,d);else if(b==6&&Math.random()<.08)dropItem(r.x+.5,r.y+.3,r.z+.5,199);addXp((b>=15&&b<=18)||(b>=82&&b<=85)?3:0);brk=null}}
function hitMob(){const dx=-Math.sin(yaw)*Math.cos(pitch),dy=Math.sin(pitch),dz=-Math.cos(yaw)*Math.cos(pitch);
for(const m of MB){const ax=m.x-P.x,ay=m.y+.7-(P.y+1.6),az=m.z-P.z,d=Math.hypot(ax,ay,az);if(d<4&&(ax*dx+ay*dy+az*dz)/d>.9){m.hp=(m.hp||4)-atk();m.x+=ax/d*.6;m.z+=az/d*.6;m.vy=4;snd(200,.08,1);
if(m.hp<=0){m.dead=1;addXp(HO(m.t)?5:2);if(!HO(m.t)){dropItem(m.x,m.y+.4,m.z,167,1+(Math.random()*2|0));if(m.t==2)dropItem(m.x,m.y+.6,m.z,115,1+(Math.random()*2|0))}else if(m.t==6)dropItem(m.x,m.y+.4,m.z,168,1+(Math.random()*2|0));else if(m.t==5)dropItem(m.x,m.y+.4,m.z,169,1);for(let i=0;i<10;i++)padd(PB,{x:m.x,y:m.y+.5,z:m.z,vx:(Math.random()-.5)*3,vy:Math.random()*3,vz:(Math.random()-.5)*3,l:.7,gr:14,r:.8,g:.2,b:.2})}return 1}}return 0}
function ivRef(){$('icr').style.display=OD.sv?'':'none';document.querySelector('#ip h3').textContent=OD.sv?'持ち物':'クリエイティブ・インベントリ';[...$('ig').children].forEach((d,i)=>{const k=+Object.keys(NM)[i];d.style.display=(!OD.sv||INV[k]>0)?'':'none';d.dataset.n=OD.sv?(INV[k]||''):''})}
let mzNB=null;const mzN2=()=>mzNB||(mzNB=(()=>{const b=AC.createBuffer(1,AC.sampleRate,AC.sampleRate),a=b.getChannelData(0);for(let i=0;i<a.length;i++)a[i]=Math.random()*2-1;return b})());
function mzNoise(t,l,v,type,fr){const o=AC.createBufferSource(),f=AC.createBiquadFilter(),g=AC.createGain();o.buffer=mzN2();f.type=type;f.frequency.value=fr;g.gain.setValueAtTime(v,t);g.gain.exponentialRampToValueAtTime(.0008,t+l);o.connect(f);f.connect(g);g.connect(mzB);o.start(t);o.stop(t+l+.05)}
const GRP={P:[8,61,62,63,64,65,205],L:[5,56,57,58,59,60]},cnt=k=>GRP[k]?GRP[k].reduce((a,b)=>a+(INV[b]||0),0):(INV[k]||0);
const take=(k,n)=>{if(!GRP[k]){INV[k]-=n;return}for(const b of GRP[k]){const q=Math.min(n,INV[b]||0);INV[b]-=q;n-=q;if(!n)break}};
const give=(b,n)=>{INV[b]=(INV[b]||0)+n;if(!HB.includes(b)){const s2=HB.findIndex(x=>!(INV[x]>0));if(s2>=0)HB[s2]=b}hbUI()};
const tool=()=>{const b=HB[sel];return INV[b]>0&&b>=173&&b<=176?b-172:0},REQ=b=>b==15?1:b==16||b==82||b==84?2:b==17||b==18||b==83||b==85?3:b==24?4:b!=28&&(mat(b)==0||mat(b)==6)?(mat(b)==6?2:1):0;
const RC=[[168,4,{P:2},0],[94,1,{P:4},0],[33,4,{169:1,168:1},0],[48,3,{P:6},1],[29,6,{P:3},1],[40,4,{P:6},1],[44,4,{11:6},1],[30,6,{11:3},1],[95,1,{11:8},1],[19,4,{3:4},1],[173,1,{P:3,168:2},1],[174,1,{11:3,168:2},1],[175,1,{171:3,168:2},1],[176,1,{170:3,168:2},1],[171,1,{16:1,169:1},2],[172,1,{17:1,169:1},2],[9,1,{4:1,169:1},2],[3,1,{11:1,169:1},2]];
[[5,8],[56,62],[57,61],[58,63],[59,64],[60,65]].forEach(([l,p])=>RC.unshift([p,4,{[l]:1},0]));
let crSt=0;
function crRef(){const L=$('crl');L.innerHTML='';$('crt').textContent=crSt==2?'かまど':crSt==1?'作業台':'作業（2×2）';
RC.forEach(r=>{if(r[3]==2&&crSt!=2||r[3]==1&&crSt==0)return;const ok=Object.entries(r[2]).every(([k,n])=>cnt(k)>=n),d=document.createElement('div');d.className='rw';
d.innerHTML='<div class=ri style="background-image:'+ico(r[0])+'"></div><span>'+NM[r[0]]+' ×'+r[1]+'<br><small>'+Object.entries(r[2]).map(([k,n])=>(k=='P'?'板材':k=='L'?'原木':NM[k])+'×'+n).join(' ')+'</small></span>';
const b=document.createElement('button');b.className='mb';b.textContent='作る';b.disabled=!ok;b.onclick=()=>{Object.entries(r[2]).forEach(([k,n])=>take(k,n));give(r[0],r[1]);snd(500,.08,0);crRef()};d.appendChild(b);L.appendChild(d)})}
function openCr(s){crSt=s;playing=0;btn=-1;try{document.exitPointerLock()}catch(e){}crRef();show('cr')}
function closeCr(){playing=1;show(null);if(!TOUCH)lock()}
B('crc',closeCr);B('icr',()=>openCr(0));
let stA=0;const STP=[[[220,.04,0,.5],[0,.04,1,.35,3000]],[[0,.07,1,.55,900]],[[170,.06,0,.7],[0,.03,1,.3,1500]],[[0,.05,1,.5,4500],[0,.05,1,.4,5000,.05],[0,.04,1,.3,5500,.1]],[[1500,.04,0,.3]],[[0,.06,1,.3,1200]],[[600,.06,0,.4]]];
function stepTick(dt){if(!ground||fly){stA=0;return}stA+=Math.hypot(vx,vz)*dt;if(stA>2.1){stA=0;const b=getB(Math.floor(P.x),Math.floor(P.y-.3),Math.floor(P.z));if(!b||b==7)return;(b==1||b==13?[[0,.09,1,.55,2200],[0,.05,1,.3,3200,.04]]:STP[mat(b)]).forEach(([f,d,n,v,l,dl])=>snd(f,d,n,v,l,dl))}}
const gl=(()=>{const c=document.createElement('canvas');c.width=c.height=32;const g=c.getContext('2d'),r=g.createRadialGradient(16,16,0,16,16,16);r.addColorStop(0,'rgba(255,200,120,1)');r.addColorStop(.4,'rgba(255,140,50,.35)');r.addColorStop(1,'rgba(255,100,20,0)');g.fillStyle=r;g.fillRect(0,0,32,32);return new THREE.CanvasTexture(c)})();
const PG=(()=>{const n=16,g=new THREE.BufferGeometry(),p=new Float32Array(n*3);g.setAttribute('position',new THREE.BufferAttribute(p,3));const m=new THREE.Points(g,new THREE.PointsMaterial({size:1.6,map:gl,transparent:true,depthWrite:false,blending:THREE.AdditiveBlending}));m.frustumCulled=false;scene.add(m);return{g,p,m}})();
const FLAT=b=>b>=167||(b>=33&&b<=36)||(b>=48&&b<56),GEO={};
const HM=new THREE.MeshLambertMaterial({vertexColors:true,map:tex2,depthTest:false,alphaTest:.1,side:THREE.DoubleSide}),HM2=new THREE.MeshLambertMaterial({vertexColors:true,map:tex2,alphaTest:.1,side:THREE.DoubleSide});
function itemGeo(b){if(GEO[b])return GEO[b];const g={p:[],c:[],i:[],u:[],n:[]},t=TL[b]||[3],tn=TN[b]||[1,1,1];
if(FLAT(b)){[[0,0],[1,0],[1,1],[0,1]].forEach((v,k)=>{g.p.push(v[0]-.5,v[1]-.5,0);g.c.push(1,1,1);g.n.push(0,0,1);g.u.push(...uvq(t[0],k))});g.i.push(0,1,2,0,2,3)}
else for(let q=0;q<6;q++){const n0=g.p.length/3,ti=t[q==2?0:q==3?2:1]||t[0],m=SH[q];for(let k=0;k<4;k++){const v=QF[q][k];g.p.push(v[0]-.5,v[1]-.5,v[2]-.5);g.c.push(m*tn[0],m*tn[1],m*tn[2]);g.n.push(FD[q][0],FD[q][1],FD[q][2]);g.u.push(...uvq(ti,k))}g.i.push(n0,n0+1,n0+2,n0,n0+2,n0+3)}
const ge=new THREE.BufferGeometry();ge.setAttribute('position',new THREE.Float32BufferAttribute(g.p,3));ge.setAttribute('color',new THREE.Float32BufferAttribute(g.c,3));ge.setAttribute('normal',new THREE.Float32BufferAttribute(g.n,3));ge.setAttribute('uv',new THREE.Float32BufferAttribute(g.u,2));ge.setIndex(g.i);return GEO[b]=ge}
const CRK=[];for(let s2=0;s2<10;s2++){const c=document.createElement('canvas');c.width=c.height=16;const g=c.getContext('2d');g.fillStyle='rgba(0,0,0,.6)';let r=13;const rn=()=>((r=(r*1103515245+12345)&0x7fffffff)/0x7fffffff);for(let i=0;i<(s2+1)*9;i++){const x=Math.floor(rn()*16),y=Math.floor(rn()*16);g.fillRect(x,y,1,1);if(i%3==0&&x<15)g.fillRect(x+1,y,1,1)}const t=new THREE.CanvasTexture(c);t.magFilter=t.minFilter=THREE.NearestFilter;CRK.push(t)}
const crackM=new THREE.Mesh(new THREE.BoxGeometry(1.004,1.004,1.004),new THREE.MeshBasicMaterial({map:CRK[0],transparent:true,depthWrite:false,polygonOffset:true,polygonOffsetFactor:-1}));crackM.visible=false;scene.add(crackM);
scene.add(cam);const hg=new THREE.Group(),hm=new THREE.Mesh(itemGeo(1),HM),arm=new THREE.Mesh(new THREE.BoxGeometry(.14,.14,.55),new THREE.MeshLambertMaterial({color:0xc89a78,depthTest:false}));
hm.renderOrder=arm.renderOrder=99;hg.add(hm,arm);hg.position.set(.42,-.4,-.75);hg.visible=false;cam.add(hg);let hid=-1,hph=0,nmT=0;
function heldTick(dt){hg.visible=view==0;const id=HB[sel],has=!OD.sv||INV[id]>0;
if(hid!==(has?id:0)){hid=has?id:0;const n=$('nm');if(has){hm.geometry=itemGeo(id);hm.visible=true;arm.visible=false;if(FLAT(id)){hm.scale.setScalar(.5);hm.rotation.set(0,-.5,.3);hm.position.set(-.05,.02,-.05)}else{hm.scale.setScalar(.3);hm.rotation.set(.15,-.75,.05);hm.position.set(0,0,0)}n.textContent=NM[id]||'';n.style.opacity=1;nmT=2}else{hm.visible=false;arm.visible=true;arm.rotation.set(.3,-.2,0);arm.position.set(.02,-.05,-.1);n.style.opacity=0}}
if(nmT>0){nmT-=dt;if(nmT<=0)$('nm').style.opacity=0}
const br=btn==0&&playing&&!!ray();let sw=0;if(br){hph+=dt*9;sw=Math.abs(Math.sin(hph))}else if((window.SW||0)>0){window.SW-=dt;sw=Math.sin(Math.max(0,1-window.SW/.3)*Math.PI)}else hph=0;
hg.rotation.x=-sw*1.1;hg.rotation.z=-sw*.25;hg.position.set(.42-sw*.1,-.4-sw*.05,-.75+sw*.08)}
function musInit(){if(mzB||!OD.mus)return;try{AC=AC||new AudioContext();AC.resume();const sr=AC.sampleRate,n=sr*4.6|0,ir=AC.createBuffer(2,n,sr);
for(let c=0;c<2;c++){const d=ir.getChannelData(c);let lo=0,hi=0,hp=0;const pre=Math.floor(sr*.016);
 for(let i=pre;i<n;i++){const t=(i-pre)/sr,w=Math.random()*2-1;lo+=(w-lo)*.06;hi+=(w-hi)*.55;const h2=hi-hp;hp+=(hi-hp)*.5;d[i]=(lo*3.2*Math.exp(-t/1.55)+h2*.9*Math.exp(-t/.55))*Math.min(1,t/.03)}
 for(let k=0;k<9;k++){const di=pre+Math.floor(sr*(.006+Math.random()*.075)*(1+k*.15));if(di<n)d[di]+=(Math.random()<.5?-1:1)*(.55-k*.05)*(1+(c?.1:-.1))}}
const cv=AC.createConvolver(),w=AC.createGain(),lp=AC.createBiquadFilter(),cp=AC.createDynamicsCompressor();cv.buffer=ir;w.gain.value=.9;mzB=AC.createGain();mzB.gain.value=OD.mus/100*.5;lp.type='lowpass';lp.frequency.value=7000;window.mzLP=lp;cp.threshold.value=-24;cp.knee.value=18;cp.ratio.value=2.2;cp.attack.value=.03;cp.release.value=.35;lp.connect(cp);cp.connect(AC.destination);mzB.connect(lp);mzB.connect(cv);cv.connect(w);w.connect(lp);mzN=AC.currentTime+2}catch(e){}}
function pno(m,t,l,v){const f=mzF(m),fl=AC.createBiquadFilter();fl.type='lowpass';fl.frequency.value=(360+v*1500+f*.7)*(window.PNF||1);fl.connect(mzB);l*=Math.min(1.8,Math.max(.7,330/f))*1.3;
 [[1,1,0],[2,.28,.3],[3,.07,.7]].forEach(([p,a,d])=>{const o=AC.createOscillator(),g=AC.createGain(),e=t+l/(1+d);o.type='sine';o.frequency.value=f*p*(1+.0001*p*p);g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(a*v,t+.012);g.gain.exponentialRampToValueAtTime(.0003,e);o.connect(g);g.connect(fl);o.start(t);o.stop(e+.05)});
 mzNoise(t,.03,v*.03,'bandpass',f*2)}
function adv(m,t,l,v,P,att,rel,lp){const f=mzF(m),g=AC.createGain(),fl=AC.createBiquadFilter();fl.type='lowpass';fl.frequency.value=lp||2200;g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(v,t+att);g.gain.setValueAtTime(v,t+Math.max(att,l-rel));g.gain.linearRampToValueAtTime(0,t+l);fl.connect(g);g.connect(mzB);P.forEach(([h,a])=>{const o=AC.createOscillator(),og=AC.createGain();o.frequency.value=f*h;og.gain.value=a;o.connect(og);og.connect(fl);o.start(t);o.stop(t+l+.05)})}
function prc(m,t,l,v,P){const f=mzF(m),g=AC.createGain();g.gain.setValueAtTime(v,t);g.gain.exponentialRampToValueAtTime(.0004,t+l);g.connect(mzB);P.forEach(([h,a])=>{const o=AC.createOscillator(),og=AC.createGain();o.frequency.value=f*h;og.gain.value=a;o.connect(og);og.connect(g);o.start(t);o.stop(t+l+.05)})}
const strg=(m,t,l,v)=>adv(m,t,l,v*1.5,[[1,1],[2,.7],[3,.5],[4,.32],[5,.2],[6,.1]],.5,.6,1300),hrn=(m,t,l,v)=>adv(m,t,l,v*1.4,[[1,1],[2,.5],[3,.2],[4,.08]],.6,.7,900),cln=(m,t,l,v)=>adv(m,t,l,v*1.2,[[1,1],[3,.45],[5,.2],[7,.08]],.1,.4,1800);
function flt(m,t,l,v){adv(m,t,l,v*1.2,[[1,1],[2,.22],[3,.08]],.14,.5,2400);mzNoise(t,l*.5,v*.06,'bandpass',mzF(m)*2)}
function plk(m,t,l,v,br){const f=mzF(m),o=AC.createOscillator(),o2=AC.createOscillator(),g=AC.createGain(),fl=AC.createBiquadFilter();o.type='triangle';o2.type='sine';o.frequency.value=f;o2.frequency.value=f*2;fl.type='lowpass';fl.frequency.setValueAtTime(br||3000,t);fl.frequency.exponentialRampToValueAtTime(400,t+l*.6);g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(v,t+.004);g.gain.exponentialRampToValueAtTime(.0004,t+l);o.connect(fl);o2.connect(fl);fl.connect(g);g.connect(mzB);o.start(t);o2.start(t);o.stop(t+l+.1);o2.stop(t+l+.1);mzNoise(t,.015,v*.2,'bandpass',f*3)}
function drm(t,v,p){const o=AC.createOscillator(),g=AC.createGain();o.frequency.setValueAtTime(p,t);o.frequency.exponentialRampToValueAtTime(p*.5,t+.16);g.gain.setValueAtTime(v,t);g.gain.exponentialRampToValueAtTime(.0008,t+.35);o.connect(g);g.connect(mzB);o.start(t);o.stop(t+.4);mzNoise(t,.05,v*.35,'lowpass',700)}
const mzSCL={min:[0,2,3,5,7,8,10],maj:[0,2,4,5,7,9,11],dor:[0,2,3,5,7,9,10],lyd:[0,2,4,6,7,9,11],phr:[0,1,3,5,7,8,10]},mzdg=(S,d)=>S[((d%7)+7)%7]+12*Math.floor(d/7);
const mzMP=(s,bpb)=>{const o=[];s.split('|').forEach((b,i)=>b.trim().split(/\s+/).forEach(n=>{if(!n)return;const q=n.split(':').map(Number);o.push([i*bpb+q[0],q[1],q[2]])}));return o};
const mzKC={};
function mzKS(f,dur,damp,bright){const sr=AC.sampleRate,n=Math.floor(sr*dur),N=Math.max(2,Math.round(sr/f)),b=AC.createBuffer(1,n,sr),d=b.getChannelData(0),r=new Float32Array(N);let lp=0,m=0,pk=1e-6;
 for(let i=0;i<N;i++){lp+=((Math.random()*2-1)-lp)*bright;r[i]=lp;m+=lp}m/=N;for(let i=0;i<N;i++){r[i]-=m;pk=Math.max(pk,Math.abs(r[i]))}for(let i=0;i<N;i++)r[i]/=pk;
 let p=0;for(let i=0;i<n;i++){const a=r[p],c=r[(p+1)%N];d[i]=a;r[p]=(a+c)*.5*damp;p=(p+1)%N}
 const fo=Math.min(n,Math.floor(sr*.06));for(let i=0;i<fo;i++)d[n-1-i]*=i/fo;return b}
/* ===== realism layer v3 ===== */
const mzPan=(p)=>{const n=AC.createStereoPanner?AC.createStereoPanner():null;if(n){n.pan.value=Math.max(-1,Math.min(1,p));n.connect(mzB);return n}return mzB};
const mzRnd=(a)=>(Math.random()*2-1)*a;
/* --- piano: additive model rendered to a buffer (inharmonic partials, 3 strings, hammer thump), time-sliced --- */
const mzPC={},mzJobs=[];let mzPumping=0;
function mzPnoJob(m,hard){const key=m+(hard?'h':'s'),sr=AC.sampleRate,f=mzF(m),vel=hard?.95:.4;
 const tau0=Math.max(1.4,Math.min(8.5,6.2*Math.pow(261/f,.38))),dur=Math.min(7,tau0*1.5+.4),n=Math.floor(sr*dur),B=.00006*Math.pow(f/261,1.7)+.00003,NP=Math.max(5,Math.min(16,Math.floor((hard?7500:4200)/f))),d=new Float32Array(n);
 const P=[];for(let k=1;k<=NP;k++){const fk=k*f*Math.sqrt(1+B*k*k);if(fk>sr*.45)break;
  const am=Math.pow(k,-.85)*(.3+.7*Math.abs(Math.sin(Math.PI*k*.125+.2)))*Math.exp(-(k-1)*(hard?.16:.42)),tk=tau0/(1+.45*(k-1)*(f<200?.7:1));
  [[0,.55,1],[.9+Math.random()*.5,.32,1.18],[-1.1-Math.random()*.5,.32,.82]].forEach(([ct,sa,sd])=>{const w=2*Math.PI*fk*Math.pow(2,ct/1200)/sr,r=Math.exp(-6.91/(tk*sd*sr)),ph=Math.random()*6.28;P.push({a:am*sa,c:Math.cos(w)*r,s:Math.sin(w)*r,x:Math.cos(ph),y:Math.sin(ph)})})}
 let pos=0,pk=0;const noiseLP=(hard?1800:700)/sr*6.28,th=[0,0];
 return{key,step(budget){const e=Math.min(n,pos+budget);for(let i=pos;i<e;i++){let a=0;for(let j=0;j<P.length;j++){const p=P[j],nx=p.x*p.c-p.y*p.s;p.y=p.x*p.s+p.y*p.c;p.x=nx;a+=p.a*p.y}d[i]=a}pos=e;return pos>=n},
  finish(){const sm=Math.floor(sr*.004),hl=Math.floor(sr*.03);let lp=0,lp2=0;for(let i=0;i<hl&&i<n;i++){const w=Math.random()*2-1;lp+=(w-lp)*noiseLP;d[i]+=lp*Math.pow(1-i/hl,2)*(hard?.5:.2)*(.6+.4*vel)}
   const th0=Math.floor(sr*.09);for(let i=0;i<th0&&i<n;i++)d[i]+=Math.sin(i/sr*6.283*(55+f*.12))*Math.exp(-i/sr*55)*.28*vel;
   for(let i=0;i<sm;i++)d[i]*=i/sm;const fo=Math.floor(sr*.08);for(let i=0;i<fo;i++)d[n-1-i]*=i/fo;
   for(let i=0;i<n;i++){const a=Math.abs(d[i]);if(a>pk)pk=a}const g=1/(pk||1);for(let i=0;i<n;i++)d[i]*=g;
   const b=AC.createBuffer(1,n,sr);b.copyToChannel(d,0);mzPC[key]=b}}}
function mzPump(){if(mzPumping)return;mzPumping=1;const run=()=>{const t0=performance.now();while(mzJobs.length&&performance.now()-t0<6){const j=mzJobs[0];if(j.step(9000)){j.finish();mzJobs.shift()}}if(mzJobs.length)setTimeout(run,0);else mzPumping=0};setTimeout(run,0)}
function mzPre(ev){mzJobs.length=0;const seen={};ev.forEach(e=>{if(e[1]===mzPnoN){const k=e[2]+(e[4]>mzVB.p*.62?'h':'s');if(!mzPC[k]&&!seen[k]){seen[k]=1;mzJobs.push(mzPnoJob(e[2],e[4]>mzVB.p*.62))}}});if(mzJobs.length)mzPump()}
const mzReady=()=>mzJobs.length==0;
function mzPnoN(m,t,l,v){const hard=v>mzVB.p*.62,b=mzPC[m+(hard?'h':'s')];if(!b){return}
 const s=AC.createBufferSource(),g=AC.createGain(),pn=mzPan((m-62)/70);s.buffer=b;s.playbackRate.value=1+mzRnd(.0008);
 const hold=Math.max(.5,l*1.5)*(m<48?1.4:1),end=t+Math.min(b.duration-.1,hold+1.1);
 g.gain.setValueAtTime(v*1.25,t);g.gain.setValueAtTime(v*1.25,t+hold*.55);g.gain.exponentialRampToValueAtTime(v*.1,t+hold+.5);g.gain.linearRampToValueAtTime(0,end);
 s.connect(g);g.connect(pn);s.start(t);s.stop(end+.02)}
/* --- generic ensemble voice: detuned oscillator stack, random vibrato per voice, body formants, bow/breath noise --- */
const mzWV={};function mzWave(k,H){if(mzWV[k])return mzWV[k];const re=new Float32Array(H.length+1),im=new Float32Array(H.length+1);H.forEach((a,i)=>im[i+1]=a);return mzWV[k]=AC.createPeriodicWave(re,im)}
function mzV(m,t,l,v,o){const f=mzF(m),nv=o.n||3,sp=o.sp||8,att=o.att||.2,rel=o.rel||.4,out=AC.createGain(),lp=AC.createBiquadFilter(),env=AC.createGain();l=Math.max(l,att+rel+.1);
 const saw=mzWave('saw',Array.from({length:24},(_,i)=>1/(i+1))),sq=mzWave('sq',Array.from({length:24},(_,i)=>i%2==0?1/(i+1):0)),w=o.w=='sq'?sq:o.w=='sine'?null:saw;
 lp.type='lowpass';lp.Q.value=o.q||.7;const c0=(o.lp||2000)*(.7+.5*Math.min(1,v/(o.vr||.2)));lp.frequency.setValueAtTime(c0*.45,t);lp.frequency.linearRampToValueAtTime(c0,t+att*1.3);
 for(let i=0;i<nv;i++){const os=AC.createOscillator(),vg=AC.createGain(),pn=AC.createStereoPanner?AC.createStereoPanner():null;if(w)os.setPeriodicWave(w);else os.type='sine';
  const dt=nv>1?(i/(nv-1)*2-1)*sp+mzRnd(sp*.18):mzRnd(2);os.frequency.value=f;os.detune.value=dt;
  if(o.vib){const lf=AC.createOscillator(),lg=AC.createGain();lf.frequency.value=o.vib*(1+mzRnd(.1));lg.gain.setValueAtTime(0,t);lg.gain.setValueAtTime(0,t+(o.vd||.4));lg.gain.linearRampToValueAtTime(o.va*1200*(1+mzRnd(.2)),t+(o.vd||.4)+.7);lf.connect(lg);lg.connect(os.detune);lf.start(t+Math.random()*.2);lf.stop(t+l+rel+.2)}
  vg.gain.value=1/Math.sqrt(nv);os.connect(vg);if(pn){pn.pan.value=nv>1?(i/(nv-1)*2-1)*(o.wd||.5):0;vg.connect(pn);pn.connect(lp)}else vg.connect(lp);os.start(t+Math.random()*.012);os.stop(t+l+rel+.1)}
 let last=lp;(o.fm||[]).forEach(([fr,q,gn])=>{const b=AC.createBiquadFilter();b.type='peaking';b.frequency.value=fr;b.Q.value=q;b.gain.value=gn;last.connect(b);last=b});
 if(o.ns){const src=AC.createBufferSource(),bp=AC.createBiquadFilter(),ng=AC.createGain();src.buffer=mzN2();src.loop=true;bp.type='bandpass';bp.frequency.value=Math.min(8000,f*(o.nf||3));bp.Q.value=o.nq||1.2;ng.gain.setValueAtTime(0,t);ng.gain.linearRampToValueAtTime(o.ns,t+att*.7);ng.gain.setValueAtTime(o.ns*.6,t+l);ng.gain.linearRampToValueAtTime(0,t+l+rel);src.connect(bp);bp.connect(ng);ng.connect(out);src.start(t);src.stop(t+l+rel+.1)}
 env.gain.setValueAtTime(0,t);env.gain.linearRampToValueAtTime(v,t+att);const sw=o.sw||.06;env.gain.linearRampToValueAtTime(v*(1+sw),t+att+(l-att)*.55);env.gain.linearRampToValueAtTime(v*(1-sw*.5),t+l);env.gain.linearRampToValueAtTime(0,t+l+rel);
 last.connect(env);env.connect(out);out.connect(mzB)}
const mzVio=(m,t,l,v,low)=>mzV(m,t,l,v*(low?1.5:1.5),low?{n:3,sp:7,att:.22,rel:.45,lp:1700,vib:4.8,va:.0035,vd:.5,fm:[[230,1.4,4],[650,1.6,3],[1100,2,2]],ns:.012,nf:5}:{n:3,sp:8,att:.16,rel:.4,lp:3600,vib:5.4,va:.0042,vd:.45,fm:[[450,1.5,3],[2400,1.4,4],[3400,2,2]],ns:.01,nf:4});
const mzCel=(m,t,l,v)=>mzVio(m,t,l,v,1),
mzClo=(m,t,l,v)=>mzV(m,t,Math.max(l,2),v*2.2,{n:4,sp:13,att:.55,rel:.8,lp:1250,sw:.1,fm:[[240,1.2,3]],wd:.7}),
mzPad=(m,t,l,v)=>mzV(m,t,Math.max(l,2.4),v*1.5,{n:6,sp:18,att:1.2,rel:1.5,lp:1500,sw:.12,wd:.9,vr:.12}),
mzStr=(m,t,l,v)=>mzV(m,t,Math.max(l,1.8),v*2.4,{n:5,sp:15,att:.65,rel:.9,lp:1500,sw:.1,wd:.85,vib:5,va:.002,vd:.9,fm:[[500,1,2],[2200,1,2]]}),
mzFlt=(m,t,l,v)=>mzV(m,t,l,v*1.8,{n:2,sp:4,att:.12,rel:.35,lp:3600,w:'sine',vib:5.1,va:.004,vd:.7,ns:.03,nf:2,nq:.7,fm:[[1400,1,2]],sw:.1}),
mzCln=(m,t,l,v)=>mzV(m,t,l,v*1.5,{n:2,sp:3,att:.09,rel:.3,lp:2300,w:'sq',vib:4.8,va:.0022,vd:.8,ns:.012,nf:3,fm:[[1000,1.3,3]]}),
mzOb=(m,t,l,v)=>mzV(m,t,l,v*1.5,{n:2,sp:5,att:.07,rel:.3,lp:3000,vib:5.3,va:.0032,vd:.5,fm:[[1100,2.2,6],[2800,1.5,2]],ns:.01,nf:3}),
mzAcc=(m,t,l,v)=>mzV(m,t,l,v*1.4,{n:3,sp:11,att:.07,rel:.25,lp:2500,w:'sq',wd:.6,sw:.04,fm:[[1800,1,3]]}),
mzOrg=(m,t,l,v)=>mzV(m,t,l,v*1.3,{n:3,sp:3,att:.35,rel:.5,lp:1700,w:'sq',sw:.02,wd:.4}),
mzCho=(m,t,l,v)=>mzV(m,t,Math.max(l,2),v*2,{n:5,sp:9,att:Math.min(1.4,l*.4),rel:1,lp:2500,vib:5,va:.003,vd:.8,wd:.8,ns:.02,nf:2,nq:.5,fm:[[600,4,6],[1050,5,4],[2500,4,3]]});
/* --- struck/plucked: separate decay per partial, body resonance, pan --- */
function mzPr(m,t,l,v,P,o){o=o||{};const f=mzF(m),pn=mzPan((m-64)/64*.4+mzRnd(.1)),det=1+mzRnd(.0007);
 P.forEach(([h,a,dk],i)=>{const os=AC.createOscillator(),og=AC.createGain(),d=l/(dk||(1+i*.9));os.frequency.value=f*h*det;os.type='sine';og.gain.setValueAtTime(0,t);og.gain.linearRampToValueAtTime(a*v,t+.003);og.gain.exponentialRampToValueAtTime(.0004,t+Math.max(.08,d));os.connect(og);og.connect(pn);os.start(t);os.stop(t+Math.max(.08,d)+.05)});
 if(o.tk)mzNoise(t,.02,v*o.tk,'bandpass',f*(o.tf||3))}
const mzBel=(m,t,l,v)=>mzPr(m,t,l,v*.9,[[1,1,1],[2.01,.3,.5],[2.76,.34,.42],[4.07,.16,.28],[5.43,.14,.2],[8.9,.05,.1]],{tk:.05,tf:4}),
mzBox=(m,t,l,v)=>mzPr(m+12,t,Math.min(l,2.4),v*.7,[[1,1,1],[3,.2,.4],[5.1,.08,.2],[7.2,.03,.12]],{tk:.04,tf:5}),
mzKal=(m,t,l,v)=>mzPr(m,t,Math.min(l,1.6),v,[[1,1,1],[5.4,.1,.15],[8.9,.03,.08],[.5,.06,1.3]],{tk:.1,tf:3}),
mzMar=(m,t,l,v)=>mzPr(m,t,Math.min(l,1.2),v*1.2,[[1,1,1],[4,.28,.2],[10,.07,.08],[.5,.1,1.2]],{tk:.14,tf:2}),
mzVib=(m,t,l,v)=>{l=Math.max(l,3);mzPr(m,t,l,v*1.1,[[1,1,1],[4,.25,.3],[10,.05,.1]],{});const f=mzF(m),pn=mzPan(mzRnd(.2)),lf=AC.createOscillator(),lg=AC.createGain(),o=AC.createOscillator(),g=AC.createGain();o.frequency.value=f;g.gain.setValueAtTime(v*.25,t);g.gain.exponentialRampToValueAtTime(.0004,t+l);lf.frequency.value=5.1;lg.gain.value=v*.12;lf.connect(lg);lg.connect(g.gain);o.connect(g);g.connect(pn);o.start(t);lf.start(t);o.stop(t+l+.05);lf.stop(t+l+.05)};
/* guitar/harp: karplus-strong + body resonance + pick noise */
function mzPl2(m,t,v,kind){const f=mzF(m),key=kind+m;let b=mzKC[key];
 if(!b){const tau=kind=='g'?1.5:2.6;b=mzKC[key]=mzKS(f,kind=='g'?4:5,Math.min(.9998,1-1/(tau*f)),kind=='g'?.42:.7)}
 const s=AC.createBufferSource(),g=AC.createGain(),lp=AC.createBiquadFilter(),b1=AC.createBiquadFilter(),b2=AC.createBiquadFilter(),pn=mzPan((m-60)/60*.5+mzRnd(.08));s.buffer=b;s.playbackRate.value=1+mzRnd(.0006);
 lp.type='lowpass';lp.frequency.value=(kind=='g'?2400:4200)*(.8+.4*Math.min(1,v/.5));b1.type='peaking';b1.frequency.value=kind=='g'?110:200;b1.Q.value=1.4;b1.gain.value=kind=='g'?5:3;b2.type='peaking';b2.frequency.value=kind=='g'?2200:3000;b2.Q.value=1;b2.gain.value=2.5;
 g.gain.value=v*(.9+mzRnd(.12));s.connect(lp);lp.connect(b1);b1.connect(b2);b2.connect(g);g.connect(pn);s.start(t);if(kind=='g')mzNoise(t,.012,v*.12,'bandpass',f*4)}
const mzGtr=(m,t,l,v)=>mzPl2(m,t,v,'g'),mzHrp=(m,t,l,v)=>mzPl2(m,t,v,'h');

const mzSub=(m,t,l,v)=>{l=Math.max(l,.7);const f=mzF(m),o=AC.createOscillator(),o2=AC.createOscillator(),g=AC.createGain(),g2=AC.createGain(),lp=AC.createBiquadFilter(),pn=mzPan(0);o.type='triangle';o2.type='sine';o.frequency.value=f;o2.frequency.value=f*.5;lp.type='lowpass';lp.frequency.setValueAtTime(800,t);lp.frequency.exponentialRampToValueAtTime(240,t+l);g2.gain.value=.6;g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(v,t+.04);g.gain.setValueAtTime(v*.85,t+l*.55);g.gain.linearRampToValueAtTime(0,t+l+.5);o.connect(lp);o2.connect(g2);g2.connect(lp);lp.connect(g);g.connect(pn);o.start(t);o2.start(t);o.stop(t+l+.6);o2.stop(t+l+.6)};
const mzRho=(m,t,l,v)=>{const f=mzF(m),c=AC.createOscillator(),md=AC.createOscillator(),mg=AC.createGain(),g=AC.createGain(),pn=mzPan((m-60)/60*.3+mzRnd(.1)),tr=AC.createOscillator(),tg=AC.createGain(),d=Math.min(l*1.4+1.2,4.5);c.frequency.value=f;md.frequency.value=f;mg.gain.setValueAtTime(f*1.5*(.5+Math.min(1,v/.3)),t);mg.gain.exponentialRampToValueAtTime(f*.1,t+.55);md.connect(mg);mg.connect(c.frequency);g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(v,t+.006);g.gain.exponentialRampToValueAtTime(v*.3,t+.5);g.gain.exponentialRampToValueAtTime(.001,t+d);tr.frequency.value=4.6;tg.gain.value=v*.05;tr.connect(tg);tg.connect(g.gain);c.connect(g);g.connect(pn);c.start(t);md.start(t);tr.start(t);c.stop(t+d+.05);md.stop(t+d+.05);tr.stop(t+d+.05)};

const mzINS={q:mzSub,r:mzRho,p:mzPnoN,g:mzGtr,h:mzHrp,b:mzBel,x:mzBox,k:mzKal,m:mzMar,v:mzVib,c:mzClo,e:mzCel,y:mzVio,s:mzStr,f:mzFlt,l:mzCln,w:mzOb,a:mzAcc,o:mzOrg,u:mzCho,d:mzPad},
mzVB={q:.21,r:.49,p:.66,g:1.08,h:.515,b:.365,x:.738,k:.514,m:.365,v:.309,c:.035,e:.079,y:.079,s:.03,f:.145,l:.144,w:.18,a:.096,o:.069,u:.052,d:.089},mzPERC={p:1,b:1,x:1,h:1,g:1,k:1,m:1,v:1};
const mzPCS=[
{n:'孤独のランタン',r:57,sc:'min',bpb:4,spb:.8,pnf:1,sec:[
 {ch:[0,0],cp:'none',ld:'0:14:1 1:11:1 2:9:2|2:7:2',li:[['k',0,1]],vel:.85},
 {ch:[0,5,2,6],cp:'roll',ld:'0:7:1.5 1.5:9:.5 2:11:2|0:9:1.5 1.5:7:.5 2:5:2|0:11:2 2:13:1.5 3.5:11:.5|0:10:1.5 1.5:8:.5 2:6:2',li:[['p',0,1]]},
 {ch:[0,5,2,6],cp:'roll',ld:'0:7:1 1:9:1 2:11:2|0:12:2 2:11:1 3:9:1|0:13:1.5 1.5:11:.5 2:9:2|0:10:2 2:8:1 3:6:1',li:[['p',0,1],['k',0,.5]],pd:1},
 {ch:[3,5,0,4],cp:'roll',v2:1,ld:'0:10:1 1:12:1 2:14:2|0:12:1.5 1.5:14:.5 2:16:2|0:16:1 1:14:1 2:11:2|0:15:2 2:13:1 3:11:1',li:[['p',0,1],['l',0,.8]],pd:1,bs:1,vel:1.1},
 {ch:[5,6,0,4],cp:'roll',v2:1,ld:'0:14:2 2:16:2|0:17:1.5 1.5:15:.5 2:13:2|0:16:1 1:14:1 2:16:1 3:18:1|0:18:3 3:15:1',li:[['p',0,1],['s',0,1],['w',0,.8]],pd:1,bs:1,vel:1.35},
 {ch:[0,5,2,6],cp:'roll',ld:'0:7:1.5 1.5:9:.5 2:11:2|0:9:1.5 1.5:7:.5 2:5:2|0:11:2 2:13:1.5 3.5:11:.5|0:10:1.5 1.5:8:.5 2:6:2',li:[['g',-12,1]],vel:.7},
 {ch:[0,0],cp:'roll',ld:'0:14:6|0:7:6',li:[['k',0,1]],vel:.7}]},
{n:'夜明けの平原',r:60,sc:'maj',bpb:6,spb:.5,w:.7,pnf:1,sec:[
 {ch:[0,4],cp:'pad',ld:null,li:[],pd:1,vel:.75},
 {ch:[0,4,5,3],cp:'arp6',ld:'0:9:2 2:11:1 3:9:3|0:8:2 2:6:1 3:8:3|0:9:2 2:7:1 3:9:1 4:12:2|0:10:3 3:9:1 4:7:2',li:[['f',0,1],['m',0,.35]]},
 {ch:[0,4,5,3],cp:'arp6',ld:'0:11:2 2:9:1 3:11:3|0:8:1 1:11:1 2:13:1 3:11:3|0:12:2 2:9:1 3:12:1 4:14:2|0:12:2 2:10:1 3:9:3',li:[['f',0,1],['m',0,.45]],pd:1},
 {ch:[3,4,2,5],cp:'arp6',ld:'0:12:2 2:10:1 3:12:3|0:11:2 2:13:1 3:15:3|0:13:2 2:11:1 3:9:3|0:12:3 3:11:1 4:9:2',li:[['f',0,1],['p',0,.7]],pd:1,bs:1,vel:1.05},
 {ch:[3,4,5,2],cp:'arp6',ld:'0:14:3 3:12:3|0:15:3 3:13:3|0:16:2 2:14:1 3:12:3|0:13:6',li:[['f',0,1],['y',0,.8],['s',0,1]],pd:1,bs:1,vel:1.3},
 {ch:[0,4,5,3],cp:'arp6',ld:'0:9:2 2:11:1 3:9:3|0:8:2 2:6:1 3:8:3|0:9:2 2:7:1 3:9:1 4:12:2|0:10:3 3:9:1 4:7:2',li:[['m',0,1]],vel:.75},
 {ch:[0,0],cp:'arp6',ld:'0:9:3 3:7:3|0:7:6',li:[['p',0,1]],vel:.7}]},
{n:'石の下で',gn:1.5,r:50,sc:'min',bpb:4,spb:1.3,w:.45,cave:1,pnf:.7,sec:[
 {ch:[0,0],cp:'none',ld:'0:7:4|2:7:2',li:[['q',-12,1]],vel:.95},
 {ch:[3,5,0,6],cp:'drone',ld:'0:9:4|1:11:2 3:9:1|0:7:4|2:8:2',li:[['e',0,1]],pd:1},
 {ch:[5,6,0,4],cp:'drone',ld:'0:12:3 3:14:1|0:13:3 3:16:1|0:17:4|0:16:3',li:[['p',0,1],['e',12,.8],['s',0,1]],pd:1,bs:1,vel:1.2},
 {ch:[0,5],cp:'drone',ld:'0:14:6|',li:[['p',0,1]],vel:.7}]},
{n:'たそがれのワルツ',r:55,sc:'min',bpb:3,spb:.78,pnf:.9,sec:[
 {ch:[0,5],cp:'waltz',ld:null,li:[],vel:.85},
 {ch:[0,5,2,6],cp:'waltz',ld:'0:11:2 2:9:1|0:9:2 2:7:1|0:9:1.5 1.5:11:.5 2:13:1|0:10:2 2:8:1',li:[['p',0,1]]},
 {ch:[0,5,2,6],cp:'waltz',ld:'0:11:1 1:13:1 2:11:1|0:12:2 2:9:1|0:13:2 2:11:1|0:8:3',li:[['p',0,1],['a',0,.6]],pd:1},
 {ch:[3,5,6,0],cp:'waltz',ld:'0:10:1 1:12:1 2:14:1|0:14:2 2:12:1|0:13:1.5 1.5:15:.5 2:17:1|0:14:3',li:[['p',0,1],['a',0,.7],['s',0,1]],pd:1,bs:1,vel:1.1},
 {ch:[5,2,6,0],cp:'waltz',ld:'0:14:1 1:16:1 2:14:1|0:16:1.5 1.5:18:.5 2:16:1|0:17:2 2:15:1|0:14:3',li:[['p',0,1],['s',0,1],['l',0,.7]],pd:1,bs:1,vel:1.3},
 {ch:[0,5,2,6],cp:'waltz',ld:'0:11:2 2:9:1|0:9:2 2:7:1|0:9:1.5 1.5:11:.5 2:13:1|0:10:2 2:8:1',li:[['x',0,1]],vel:.7},
 {ch:[0,0],cp:'waltz',ld:'0:11:3|0:7:3',li:[['x',0,1]],vel:.6}]},
{n:'遠い汽笛',r:50,sc:'min',bpb:6,spb:.62,pnf:.8,sec:[
 {ch:[0,0],cp:'none',ld:'0:7:5|0:7:5',li:[['l',-12,1]],vel:.85},
 {ch:[0,5,2,6],cp:'sway',ld:'0:11:3 3:9:2 5:7:1|0:12:3 3:9:3|0:13:3 3:11:2 5:9:1|0:8:3 3:10:2 5:13:1',li:[['e',0,1]]},
 {ch:[0,5,2,6],cp:'sway',ld:'0:14:3 3:13:2 5:11:1|0:12:3 3:14:3|0:13:3 3:16:2 5:13:1|0:15:3 3:13:3',li:[['e',0,1],['y',0,.7]],pd:1},
 {ch:[3,5,0,4],cp:'sway',ld:'0:14:3 3:12:3|0:14:3 3:16:3|0:18:3 3:16:3|0:17:3 3:15:3',li:[['y',0,1],['w',0,.8]],pd:1,bs:1,vel:1.1},
 {ch:[5,6,0,0],cp:'sway',ld:'0:19:3 3:18:3|0:20:3 3:17:3|0:21:6|0:18:3 3:16:3',li:[['y',0,1],['w',0,.9],['s',0,1]],pd:1,bs:1,vel:1.15},
 {ch:[0,0],cp:'sway',ld:'0:11:6|0:7:6',li:[['p',0,1]],vel:.6}]},
{n:'帰り道の手紙',r:58,sc:'min',bpb:4,spb:1,pnf:1,sec:[
 {ch:[0,0],cp:'none',ld:'0:11:1 1:9:1 2:11:1 3:9:1|0:11:1 1:9:1 2:12:2',li:[['r',0,1]],vel:.85},
 {ch:[0,2,3,4],cp:'bal',ld:'0:11:2 2:9:1 3:7:1|0:13:2 2:11:1 3:9:1|0:12:2 2:10:1 3:12:1|0:13:1.5 1.5:11:.5 2:8:2',li:[['l',0,1]]},
 {ch:[0,2,3,4],cp:'bal',ld:'0:7:1 1:9:1 2:11:2|0:13:1 1:11:1 2:9:2|0:10:1 1:12:1 2:14:2|0:15:2 2:13:1 3:11:1',li:[['l',0,1],['y',0,.6]],pd:1},
 {ch:[5,3,0,4],cp:'bal',ld:'0:12:2 2:9:1 3:7:1|0:10:2 2:12:1 3:14:1|0:11:2 2:9:1 3:11:1|0:11:2 2:13:2',li:[['y',0,1],['p',0,.6]],pd:1,bs:1,vel:1.05},
 {ch:[3,4,5,0],cp:'bal',ld:'0:14:2 2:12:1 3:14:1|0:15:2 2:13:1 3:15:1|0:16:2 2:14:1 3:12:1|0:14:4',li:[['y',0,1],['l',0,.8],['s',0,1],['e',-12,.7]],pd:1,bs:1,vel:1.1},
 {ch:[0,2,3,4],cp:'bal',ld:'0:11:2 2:9:1 3:7:1|0:13:2 2:11:1 3:9:1|0:12:2 2:10:1 3:12:1|0:13:1.5 1.5:11:.5 2:8:2',li:[['p',0,1]],vel:.7},
 {ch:[0,0],cp:'bal',ld:'0:11:6|',li:[['p',0,1]],vel:.6}]},
{n:'空っぽの部屋',gn:1.4,r:57,sc:'min',bpb:4,spb:1.35,pnf:.7,w:1.3,sec:[
 {ch:[0],cp:'open',ld:null,li:[],vel:1.4},
 {ch:[0,5,3,4],cp:'open',ld:'0:11:3|1.5:12:2|0:10:2.5 2.5:9:1|0:11:4',li:[['p',0,1]]},
 {ch:[0,5,3,4],cp:'open',ld:'0:14:2 2:12:2|0:11:3|0:9:2 2:8:2|0:7:4',li:[['p',0,1]]},
 {ch:[5,3,0,4],cp:'open',ld:'0:14:3 3:16:1|0:15:2 2:14:2|0:14:3 3:13:1|0:12:4',li:[['p',0,1],['s',-12,.7]],pd:1,vel:.9},
 {ch:[0,5,3,4],cp:'open',ld:'0:9:4|2:7:2|0:8:4|0:7:4',li:[['p',0,1]],vel:.7},
 {ch:[0,0],cp:'open',ld:'0:7:6|',li:[['p',0,1]],vel:.5}]},
{n:'冬の弦',gn:1.8,r:50,sc:'min',bpb:3,spb:1,pnf:.8,w:1.2,cave:1,sec:[
 {ch:[0,6],cp:'bow',ld:null,li:[],pd:1,vel:.7},
 {ch:[0,6,5,4],cp:'bow',ld:'0:11:3|0:10:2 2:8:1|0:12:2 2:9:1|0:11:1.5 1.5:8:1.5',li:[['e',0,1]],pd:1,vel:.8},
 {ch:[0,6,5,4],cp:'bow',ld:'0:14:3|0:13:2 2:11:1|0:12:2 2:14:1|0:11:3',li:[['e',0,1],['y',0,.7]],pd:1},
 {ch:[3,5,0,4],cp:'bow',ld:'0:14:2 2:12:1|0:16:3|0:17:2 2:16:1|0:15:3',li:[['y',0,1],['e',-12,.8]],pd:1,vel:1.2},
 {ch:[5,6,0,4],cp:'bow',ld:'0:14:3|0:13:3|0:11:3|0:8:3',li:[['y',0,1],['e',0,.8]],pd:1,vel:.9},
 {ch:[4,4],cp:'bow',ld:'0:8:6|',li:[['y',0,.8]],pd:1,vel:.5}]},
{n:'夜更けのギター',r:52,sc:'min',bpb:4,spb:.95,pnf:1,w:1.1,sec:[
 {ch:[0,5],cp:'nt',ld:null,li:[],vel:.8},
 {ch:[0,5,2,6],cp:'nt',ld:'1:11:2 3:9:1|0:12:2 2:9:2|0:13:2 2:11:2|0:10:2 2:8:2',li:[['l',0,1]]},
 {ch:[0,5,2,6],cp:'nt',ld:'1:11:2 3:9:1|0:12:2 2:9:2|0:13:2 2:11:2|0:10:2 2:8:2',li:[['w',0,.9]],pd:1,vel:.9},
 {ch:[3,0,4,0],cp:'nt',ld:'0:14:3 3:12:1|0:11:2 2:9:2|0:13:2 2:12:1 3:11:1|0:7:4',li:[['f',0,1]],pd:1,vel:1.05},
 {ch:[0,5,2,6],cp:'nt',ld:'1:11:2 3:9:1|0:12:2 2:9:2|0:13:2 2:11:2|0:10:2 2:8:2',li:[['g',0,1]],vel:.7},
 {ch:[0,0],cp:'nt',ld:'0:7:6|',li:[['l',0,1]],vel:.6}]},
{n:'遠い海鳴り',r:55,sc:'min',bpb:5,spb:.7,pnf:.8,w:1.1,sec:[
 {ch:[0,0],cp:'none',ld:'0:11:5|0:9:5',li:[['f',0,1]],vel:.75},
 {ch:[0,5,2,6],cp:'sea',ld:'0:11:3 3:9:2|0:12:3 3:9:2|0:13:2 2:11:3|0:10:3 3:8:2',li:[['f',0,1]]},
 {ch:[0,5,2,6],cp:'sea',ld:'0:11:3 3:9:2|0:12:3 3:9:2|0:13:2 2:11:3|0:10:3 3:8:2',li:[['f',0,1],['w',0,.6]],pd:1},
 {ch:[3,5,0,4],cp:'sea',ld:'0:14:3 3:12:2|0:12:3 3:14:2|0:11:5|0:13:2 2:11:3',li:[['f',0,1],['y',0,.7]],pd:1,vel:1.1},
 {ch:[0,5,2,6],cp:'sea',ld:'0:11:3 3:9:2|0:12:3 3:9:2|0:13:2 2:11:3|0:10:3 3:8:2',li:[['w',0,1]],vel:.7},
 {ch:[0,0],cp:'sea',ld:'0:11:5|',li:[['f',0,1]],vel:.5}]},
{n:'ひとりの庭',r:60,sc:'maj',bpb:4,spb:1,pnf:.8,w:1.3,sec:[
 {ch:[0,0],cp:'sw',ld:null,li:[],vel:.8},
 {ch:[0,5,3,4],cp:'sw',ld:'1:14:1.5 2.5:12:.5 3:11:1|1:12:1.5 2.5:11:.5 3:9:1|1:11:1.5 2.5:9:.5 3:11:1|0:12:3',li:[['p',0,1]],vel:.85},
 {ch:[3,0,5,4],cp:'sw',ld:'1:16:1.5 2.5:14:.5 3:12:1|1:14:1.5 2.5:12:.5 3:11:1|1:12:1.5 2.5:11:.5 3:9:1|0:11:3 3:9:1',li:[['p',0,1],['r',0,.45]],v2:1},
 {ch:[0,5,3,4],cp:'sw',ld:'1:11:1.5 2.5:12:.5 3:14:1|1:12:1.5 2.5:14:.5 3:16:1|1:14:1.5 2.5:12:.5 3:11:1|0:9:3',li:[['p',0,1],['r',0,.5]],v2:1,vel:1.05},
 {ch:[5,3,0,4],cp:'sw',ld:'1:12:1.5 2.5:11:.5 3:9:1|1:11:1.5 2.5:9:.5 3:7:1|1:9:1.5 2.5:11:.5 3:12:1|0:11:3',li:[['p',0,1],['x',12,.6]],vel:.8},
 {ch:[0,5,3,4],cp:'sw',ld:'1:14:1.5 2.5:12:.5 3:11:1|1:12:1.5 2.5:11:.5 3:9:1|1:11:1.5 2.5:9:.5 3:11:1|0:12:3',li:[['p',0,1]],vel:.7},
 {ch:[0,0],cp:'sw',ld:'0:14:3|0:11:5',li:[['p',0,1]],vel:.55}]}];
let mzQ=null,mzI=0,mzEnd=0,mzLast=-1;
function mzCompose(pc){const S=mzSCL[pc.sc],bpb=pc.bpb,sp=pc.spb,R=pc.r+[-2,0,0,2][Math.random()*4|0],ev=[];let T0=0;
 const N=(i,m,bt,lb,v)=>ev.push([T0+bt*sp+(Math.random()-.5)*(i=='p'||i=='g'||i=='h'?.05:.03)+(i=='p'?.004:0),mzINS[i],m,mzPERC[i]?Math.max(lb*sp*1.6,2.4):lb*sp,v*mzVB[i]*(pc.gn||1)*(.88+Math.random()*.24)]);
 pc.sec.forEach(sec=>{const nb=sec.ch.length,rep=sec.rep||1,vl=sec.vel||1,ph=sec.ld?mzMP(sec.ld,bpb):[];
  for(let rp=0;rp<rep;rp++){
   for(let b=0;b<nb;b++){const c=sec.ch[b],bt=b*bpb,r0=R+mzdg(S,c),tr=[r0,R+mzdg(S,c+2),R+mzdg(S,c+4)],cp=sec.cp;
    if(cp=='roll'){N('p',r0-12,bt,bpb,vl*1.1);tr.forEach((m,k)=>N('p',m,bt+2+k*.14,2,vl*.65));if(sec.v2)N('p',tr[2]+12,bt+3.5,1.5,vl*.4)}
    else if(cp=='arp6'){const nt=[tr[0],tr[1],tr[2],tr[0]+12];[0,1,2,3,2,1].forEach((k,j)=>N('h',nt[k],bt+j,2,vl*(j==0?1.1:.7)));N('h',r0-12,bt,3,vl*.9)}
    else if(cp=='pad'){tr.forEach(m=>N('d',m,bt,bpb*.98,vl))}
    else if(cp=='drone'){N('c',r0-12,bt,bpb,vl*1.2)}
    else if(cp=='waltz'){N('p',r0-12,bt,2,vl*1.1);N('p',tr[1],bt+1,1,vl*.55);N('p',tr[2],bt+2,1,vl*.5)}
    else if(cp=='cas'){for(let k=0;k<8;k++)N('b',tr[k%3]+12*((k/3)|0),bt+k*.5,2,vl*(.6+k*.05));tr.forEach(m=>N('d',m,bt,bpb*.98,vl*.8))}
    else if(cp=='fp'){[[0,r0-12],[.5,tr[2]],[1,tr[1]],[1.5,tr[2]],[2,tr[2]-12],[2.5,tr[2]],[3,tr[1]],[3.5,tr[2]]].forEach(([q,m],k)=>N('g',m,bt+q,2,vl*(k%4==0?1.1:.7)))}
    else if(cp=='sway'){tr.forEach(m=>N('o',m,bt,bpb,vl*.8));N('p',r0-12,bt,3,vl);N('p',tr[1],bt+3,2,vl*.5);N('p',tr[2],bt+4.5,1.5,vl*.4)}
    else if(cp=='ost'){[[0,tr[0]],[.75,tr[2]],[1.5,tr[1]+12],[2,tr[2]],[2.75,tr[0]+12],[3.5,tr[1]+12]].forEach(([q,m],k)=>N('m',m,bt+q,1,vl*(k%3==0?1:.7)));N('h',r0-12,bt,2,vl*.8);N('h',tr[2]-12,bt+2,2,vl*.6)}
    else if(cp=='chor'){tr.forEach(m=>N('u',m,bt,bpb,vl*.9));[tr[0],tr[1],tr[2],tr[0]+12].forEach((m,k)=>N('h',m,bt+k,2,vl*.8))}
    else if(cp=='sw'){N('p',r0-12,bt,2.5,vl*1.05);N('q',r0-24,bt,3.6,vl*.9);N('p',tr[0],bt+1,1.5,vl*.5);N('p',tr[1],bt+1.75,1.5,vl*.45);N('p',tr[2],bt+2.5,1.5,vl*.5);N('p',tr[1],bt+3.25,.75,vl*.35);if(sec.v2)N('d',tr[1],bt,bpb*.98,vl*.5)}
    else if(cp=='bal'){N('p',r0-12,bt,2,vl*1.1);tr.forEach(m=>N('p',m,bt+1,1.2,vl*.4));N('p',tr[2]-12,bt+2,1.5,vl*.8);tr.forEach(m=>N('p',m,bt+3,1,vl*.35))}
    else if(cp=='open'){N('p',r0-12,bt,bpb,vl*1.1);if(b%2==1)N('p',tr[2]-12,bt+1.5,2,vl*.45)}
    else if(cp=='bow'){N('c',r0-12,bt,bpb,vl*1.1)}
    else if(cp=='lull'){N('c',r0-12,bt,bpb,vl*.8);N('d',tr[1],bt,bpb,vl*.6)}
    else if(cp=='cho'){tr.forEach(m=>N('u',m,bt,bpb*1.02,vl*.7));N('c',r0-12,bt,bpb,vl*.9)}
    else if(cp=='nt'){[[0,r0-12],[1,tr[0]],[1.5,tr[1]],[2,tr[2]],[3,tr[1]],[3.5,tr[2]]].forEach(([q,m],k)=>N('g',m,bt+q,2,vl*(k==0?1.1:.7)))}
    else if(cp=='sea'){[r0-12,tr[0],tr[1],tr[2],tr[1]].forEach((m,k)=>N('h',m,bt+k,2,vl*(k==0?1.1:.6)));N('c',r0-12,bt,bpb,vl*.9)}
    if(sec.pd)tr.forEach(m=>N('s',m,bt,bpb,vl));
    if(sec.bs)N('c',r0-12,bt,bpb,vl)}
   ph.forEach(([bt,d,l])=>sec.li.forEach(([i,o,vm])=>N(i,R+mzdg(S,d)+o,bt,l,vl*vm)));
   T0+=nb*bpb*sp}});
 if(pc.rit){const Ls=T0*pc.rit[0];ev.forEach(e=>{if(e[0]>Ls){const u=(e[0]-Ls)/(T0-Ls);e[0]=Ls+(e[0]-Ls)*(1+pc.rit[1]*u)}})}
 ev.forEach(e=>{e[0]+=sp*(.05*Math.sin(e[0]/7.3+1)+.035*Math.sin(e[0]/2.9))});
 return ev.sort((a,b)=>a[0]-b[0])}
const mzIx=n=>Math.max(0,mzPCS.findIndex(p=>p.n==n));
function mzPick(){const L=mzPCS.length,b=OD.bgm%(L+1);if(b>0)return b-1;if(DIM==1)return mzIx('石の下で');if(DIM==2)return mzIx('冬の弦');if(DIM==3)return mzIx('遠い海鳴り');
 const und=window.COV&&P.y<SEA-8,w=mzPCS.map(p=>und?(p.cave?4:.3):(p.w||1));if(mzLast>=0)w[mzLast]=0;let r=Math.random()*w.reduce((a,b)=>a+b,0);for(let i=0;i<L;i++){r-=w[i];if(r<=0)return i}return 0}
let mzPend=null;function mzStart(){const ix=mzPick(),pc=mzPCS[ix];mzLast=ix;const ev=mzCompose(pc);mzPre(ev);mzPend={ev,pc}}
function mzGo(){const{ev,pc}=mzPend;mzPend=null;const t0=AC.currentTime+.5;ev.forEach(e=>e[0]+=t0);mzQ=ev;mzI=0;mzEnd=ev[ev.length-1][0]+7;window.PNF=pc.pnf||1;toast('♪ '+pc.n)}
function mzTick(){if(!mzB||!OD.mus||!AC)return;const now=AC.currentTime;
 if(mzPend){if(mzReady())mzGo();return}
 if(!mzQ){if(now<mzN)return;mzStart();return}
 while(mzI<mzQ.length&&mzQ[mzI][0]<now+.8){const e=mzQ[mzI++];if(e[0]>now-.3)try{e[1](e[2],Math.max(now,e[0]),e[3],e[4])}catch(x){}}
 if(mzI>=mzQ.length&&now>mzEnd){mzQ=null;mzN=now+40+Math.random()*80}}
let view=0,air=10,drT=1,lavaT=.5,xp=0,typing=0,pPh=0;
const FOOD={167:3,199:4,200:8},atk=()=>{const b=HB[sel];return INV[b]>0&&b>=193&&b<=196?b-191:1},armorPts=()=>INV[198]>0?10:INV[197]>0?6:0;
RC.push([31,1,{115:3,P:3},1],[193,1,{P:2,168:1},1],[194,1,{11:2,168:1},1],[195,1,{171:2,168:1},1],[196,1,{170:2,168:1},1],[197,1,{171:8},1],[198,1,{170:8},1],[200,1,{167:1,169:1},2]);
const MSG=[];function toast(t){MSG.push(t);if(MSG.length>5)MSG.shift();const e=$('ms');e.textContent=MSG.join('\n');setTimeout(()=>{MSG.shift();e.textContent=MSG.join('\n')},6000)}
function addXp(n){if(!n||!OD.sv)return;xp+=n;const l=Math.floor(Math.sqrt(xp/3)),b=l*l*3,e=(l+1)*(l+1)*3;$('xp').firstChild.style.width=(xp-b)/(e-b)*100+'%';$('xp').lastChild.textContent=l;snd(1200,.05,0,.5)}
const CM=$('cmd');
document.addEventListener('contextmenu',e=>e.preventDefault());document.addEventListener('selectstart',e=>{if(e.target.id!='cmd')e.preventDefault()});['gesturestart','gesturechange'].forEach(t=>document.addEventListener(t,e=>e.preventDefault()));
[['朝にする','time set day'],['夜にする','time set night'],['晴れ','weather clear'],['雨','weather rain'],['雷雨','weather thunder'],['クリエイティブ','gamemode c'],['サバイバル','gamemode s'],['地上','dimension 0'],['ネザー','dimension 1'],['エンド','dimension 2'],['シフト','dimension 3'],['スポーン','spawn']].forEach(([n,c])=>{const b=document.createElement('button');b.className='mb';b.style.cssText='width:auto;padding:0 12px;height:34px;line-height:30px;font-size:13px';b.textContent=n;b.onclick=()=>{closeCmd();runCmd(c)};$('cp').appendChild(b)});
function openCmd(pre){typing=1;playing=0;btn=-1;try{document.exitPointerLock()}catch(e){}CM.style.display='block';$('cp').style.display='flex';CM.value=pre||'';CM.focus()}
function closeCmd(){typing=0;CM.style.display='none';$('cp').style.display='none';CM.blur();playing=1;if(!TOUCH)lock()}
CM.addEventListener('keydown',e=>{e.stopPropagation();if(e.key=='Enter'){const v=CM.value.trim();closeCmd();if(v)runCmd(v)}else if(e.key=='Escape')closeCmd()});
addEventListener('keydown',e=>{if(!inG||typing||!playing)return;if(e.code=='KeyT'||e.key=='/'){e.preventDefault();openCmd(e.key=='/'?'/':'')}if(e.code=='F5'||e.code=='KeyV'){e.preventDefault();view=(view+1)%3}if(e.code=='F2'){e.preventDefault();window.SHOT=1}});
$('bc').onclick=()=>openCmd('');$('bv').onclick=()=>{view=(view+1)%3};
function runCmd(v){const a=v.replace(/^\//,'').split(/\s+/),c=a[0];
if(c=='time'){const x=a[2]||a[1];T=x=='day'?.04:x=='night'?.6:x=='noon'?.25:(+x/24000||T);toast('時間を設定しました')}
else if(c=='gamemode'){OD.sv=(a[1]=='s'||a[1]=='survival'||a[1]=='1')?1:0;apply();hp=20;hun=20;lastSt='x';hbUI();toast('ゲームモード: '+(OD.sv?'サバイバル':'クリエイティブ'))}
else if(c=='tp'){P.x=+a[1];P.y=+a[2];P.z=+a[3];vx=vy=vz=0;toast('テレポートしました')}
else if(c=='give'){const id=+a[1];if(NM[id]){give(id,+a[2]||1);toast(NM[id]+' ×'+(+a[2]||1))}else toast('不明なアイテム: '+a[1])}
else if(c=='weather')setWeather(a[1]);
else if(c=='dimension'){warp(+a[1]||0,DIM);toast('移動しました')}
else if(c=='spawn'){spawn();vx=vy=vz=0;toast('スポーン地点へ移動')}else if(c=='seed')toast('シード: '+seed);
else toast('不明なコマンド: '+c)}
const RNn=700,RR=15,rp=new Float32Array(RNn*6),rg=new THREE.BufferGeometry(),rDs=new Float32Array(RNn*3),rDy=new Float32Array(RNn);let rInit=1;
for(let i=0;i<RNn;i++){rDs[i*3]=.8+Math.random()*.45;rDs[i*3+1]=.5+Math.random()*.45;rDs[i*3+2]=Math.random()}
rg.setAttribute('position',new THREE.BufferAttribute(rp,3));const rm=new THREE.LineSegments(rg,new THREE.LineBasicMaterial({color:0xaac4ee,transparent:true,opacity:.4}));rm.frustumCulled=false;rm.visible=false;scene.add(rm);
const SPN=110,spP=new Float32Array(SPN*3).fill(-9999),spL=new Float32Array(SPN),spB=new Float32Array(SPN),spG=new THREE.BufferGeometry();let spI=0;spG.setAttribute('position',new THREE.BufferAttribute(spP,3));
const spM=new THREE.Points(spG,new THREE.PointsMaterial({color:0xdfeaff,size:.09,transparent:true,opacity:.65,depthWrite:false}));spM.frustumCulled=false;scene.add(spM);
const rainTop=(x,z)=>{x=Math.floor(x);z=Math.floor(z);const y0=Math.min(H-1,Math.floor(P.y+16)),y1=Math.max(0,Math.floor(P.y-24));for(let y=y0;y>=y1;y--)if(getB(x,y,z))return y+1;return y1};
let wea=0,weaT=150,RK=0,thT=10,rainSnd=0;window.RK=0;
let rnS=null;
function rainSound(k){if(!AC||!OD.vol){if(rnS)rnS.g.gain.value=0;return}
 if(!rnS){try{const sr=AC.sampleRate,buf=AC.createBuffer(1,sr*4,sr),a=buf.getChannelData(0);let l=0,l2=0;for(let i=0;i<a.length;i++){const w=Math.random()*2-1;l=l*.82+w*.18;l2=l2*.97+w*.03;a[i]=(l*1.6+l2*5)*.9}
  const s=AC.createBufferSource(),f1=AC.createBiquadFilter(),f2=AC.createBiquadFilter(),g=AC.createGain();s.buffer=buf;s.loop=true;f1.type='highpass';f1.frequency.value=500;f2.type='lowpass';f2.frequency.value=5200;g.gain.value=0;s.connect(f1);f1.connect(f2);f2.connect(g);g.connect(AC.destination);s.start();rnS={g,f2}}catch(e){return}}
 rnS.g.gain.setTargetAtTime(OD.vol/100*.09*k,AC.currentTime,.6);rnS.f2.frequency.setTargetAtTime(window.UW?800:5200,AC.currentTime,.3)}
function setWeather(n){wea=n=='rain'?1:n=='thunder'?2:0;weaT=90+Math.random()*120;toast('天気: '+['晴れ','雨','雷雨'][wea])}
function weatherTick(dt){if(DIM){rm.visible=false;window.RK=0;rainSound(0);return}
weaT-=dt;if(weaT<=0){wea=wea?0:(Math.random()<.35?2:1);weaT=wea?60+Math.random()*90:120+Math.random()*240}
RK+=((wea?1:0)-RK)*Math.min(1,dt*.5);window.RK=RK;
const snow=[3,7,14].includes(bm(P.x|0,P.z|0)),show=RK>.05&&!window.COV;rm.visible=show;rainSound(snow?0:RK*(window.COV?.4:1));
if(show){const sp=snow?3.2:26,a=rp,wx=snow?.9:(wea==2?3.4:2),wz=snow?.4:.8,fx=wx/sp,fz=wz/sp;
for(let i=0;i<RNn;i++){const j=i*6,q=i*3;let hx=a[j],hy=a[j+1],hz=a[j+2],re=rInit;
 if(!re){const k=rDs[q];hy-=sp*k*dt;hx+=wx*dt*k;hz+=wz*dt*k;if(hx-P.x>RR){hx-=2*RR;re=2}else if(hx-P.x<-RR){hx+=2*RR;re=2}if(hz-P.z>RR){hz-=2*RR;re=2}else if(hz-P.z<-RR){hz+=2*RR;re=2}
  if(hy-rDs[q+1]<rDy[i]){if(!snow&&Math.abs(hx-P.x)<11&&Math.abs(hz-P.z)<11){const o=spI*3;spP[o]=hx;spP[o+1]=rDy[i]+.03;spP[o+2]=hz;spL[spI]=.2;spB[spI]=rDy[i]+.03;spI=(spI+1)%SPN}re=1}}
 if(re==1||rInit){hx=P.x+(Math.random()-.5)*2*RR;hz=P.z+(Math.random()-.5)*2*RR;hy=P.y+4+Math.random()*(rInit?12:12)}
 if(re){rDy[i]=rainTop(hx,hz)}
 const len=rDs[q+1]*(snow?.18:1);a[j]=hx;a[j+1]=hy;a[j+2]=hz;a[j+3]=hx-fx*len;a[j+4]=hy-len;a[j+5]=hz-fz*len}
rInit=0;rg.attributes.position.needsUpdate=true;rm.position.set(0,0,0);rm.material.color.set(snow?0xffffff:0xaac4ee);rm.material.opacity=(snow?.8:.4)*RK;
let any=0;for(let i=0;i<SPN;i++){if(spL[i]>0){spL[i]-=dt;any=1;const u=1-Math.max(0,spL[i])/.2;spP[i*3+1]=spL[i]>0?spB[i]+.1*Math.sin(Math.PI*u):-9999}}
if(any||1)spG.attributes.position.needsUpdate=true}else rInit=1;
if(wea==2&&!window.COV){thT-=dt;if(thT<=0){thT=8+Math.random()*18;const e=$('fl');e.style.opacity=.9;setTimeout(()=>e.style.opacity=0,120);setTimeout(()=>{snd(55,1.8,0,1.3,260);snd(0,1.6,1,.9,350)},300+Math.random()*1200)}}}
function sleepBed(){if(Math.sin(T*6.2832)<0){const e=$('fl');e.style.background='#000';e.style.opacity=1;setTimeout(()=>{T=.04;e.style.opacity=0;e.style.background='#fff';toast('朝になりました')},900)}else toast('今は眠れません（夜のみ）')}
const TNTL=[];function primeTNT(x,y,z){const m=new THREE.Mesh(new THREE.BoxGeometry(.98,.98,.98),new THREE.MeshLambertMaterial({color:0xc02a1a}));m.position.set(x,y,z);scene.add(m);TNTL.push({m,x,y,z,t:3});snd(0,.8,1,.6,1500)}
function tntTick(dt){for(let i=TNTL.length-1;i>=0;i--){const q=TNTL[i];q.t-=dt;q.m.material.emissive.setHex(Math.floor(q.t*4)%2?0xffffff:0);q.m.scale.setScalar(1+Math.max(0,.12*Math.sin(q.t*20)));if(q.t<=0){scene.remove(q.m);TNTL.splice(i,1);boom({x:q.x,y:q.y-.4,z:q.z,dead:0},4.5)}}}
const pm=new THREE.Group(),pL=[];let phd;{const sk=0xc89a78,hs=pl('phs',0x4a3222);phd=mbt(pm,[hs,hs,hs,pl('pk',sk),hs,fcm('ph1',sk,['HHHHHHHH','HHHHHHHH','H......H','.EE..EE.','........','..MMMM..','........','........'],{H:0x4a3222,E:0x2a3a8a,M:0xa0705a})],.5,.5,.5,0,1.75,0);
mbt(pm,pl('pt',0x2a9a9a),.5,.75,.25,0,1.125,0);for(const x of[-.375,.375])pL.push(mbt(pm,pl('pa',sk),.25,.75,.25,x,1.125,0));for(const x of[-.125,.125])pL.push(mbt(pm,pl('pg',0x3a3aa0),.25,.75,.25,x,.375,0))}
pm.visible=false;scene.add(pm);
function pmTick(dt){pm.visible=inG&&view>0;if(!pm.visible)return;pm.position.set(P.x,P.y,P.z);pm.rotation.y=yaw;phd.rotation.x=pitch;const sp=Math.hypot(vx,vz);pPh+=dt*sp*2.2;const a=Math.sin(pPh)*.7*Math.min(1,sp/3);pL[0].rotation.x=a;pL[1].rotation.x=-a;pL[2].rotation.x=-a;pL[3].rotation.x=a}
function tpv(){const cp=Math.cos(pitch),dx=-Math.sin(yaw)*cp,dy=Math.sin(pitch),dz=-Math.cos(yaw)*cp,s2=view==1?-1:1;let k=4;for(;k>.6;k-=.5){if(!SB(P.x+dx*k*s2,P.y+1.62+dy*k*s2,P.z+dz*k*s2))break}cam.position.set(P.x+dx*k*s2,P.y+1.62+dy*k*s2,P.z+dz*k*s2);if(view==2)cam.lookAt(P.x,P.y+1.5,P.z)}
const WQ=[],WL2=new Map(),wk=(x,y,z)=>x+','+y+','+z,wLv=(x,y,z)=>getB(x,y,z)==7?(WL2.get(wk(x,y,z))||8):0;let wT=0;
function waterTick(dt){wT+=dt;if(wT<.22||!WQ.length)return;wT=0;const batch=WQ.splice(0,40),v=OD.vol;OD.vol=0;
 for(const[x,y,z]of batch){const b0=getB(x,y,z);if(b0&&!NS(b0))continue;let lv=0;
  if(wLv(x,y+1,z)>0)lv=8;else for(const[dx,dz]of[[1,0],[-1,0],[0,1],[0,-1]]){const l=wLv(x+dx,y,z+dz)-1;if(l>lv)lv=l}
  if(lv>0){setB(x,y,z,7);WL2.set(wk(x,y,z),lv);ripAt(x+.5,z+.5,.25);WQ.push([x,y-1,z]);if(lv>1)for(const[dx,dz]of[[1,0],[-1,0],[0,1],[0,-1]])WQ.push([x+dx,y,z+dz])}}
 OD.vol=v}
let lfT=0;
function leafTick(dt){if(DIM)return;lfT-=dt;if(lfT>0)return;lfT=.12;const cb=bm(P.x|0,P.z|0)==15;
 if(cb&&Math.random()<.8)padd(PB,{x:P.x+(Math.random()-.5)*28,y:P.y+5+Math.random()*9,z:P.z+(Math.random()-.5)*28,vx:(Math.random()-.5)*.6,vy:-.4,vz:(Math.random()-.5)*.6,l:8,gr:.1,r:.97,g:.72,b:.82});
 for(let i=0;i<(cb?18:6);i++){const x=Math.floor(P.x+(Math.random()-.5)*36),z=Math.floor(P.z+(Math.random()-.5)*36),y=Math.floor(P.y-6+Math.random()*28),b=getB(x,y,z);
  if((b==6||(b>=66&&b<=70)||b==203)&&!getB(x,y-1,z)){const ch=b==203,c=ch?[.97,.7,.8]:b==6?[.35,.55,.2]:[.4,.6,.25];padd(PB,{x:x+Math.random(),y:y+.1,z:z+Math.random(),vx:(Math.random()-.5)*.5,vy:-.35,vz:(Math.random()-.5)*.5,l:ch?7:5,gr:.15,r:c[0],g:c[1],b:c[2]});break}}}
const HO=t=>t==4||t==5||t==6||t==8;RC.unshift([205,4,{204:1},0]);
const plamp=new THREE.PointLight(0xffd9a0,0,22,1.3);scene.add(plamp);
const AR=[];
function shoot(m){const a=new THREE.Mesh(new THREE.BoxGeometry(.05,.05,.5),ML(0x8a6a3a)),dx=P.x-m.x,dy=P.y+1.2-(m.y+1.5),dz=P.z-m.z,d=Math.hypot(dx,dy,dz);a.position.set(m.x,m.y+1.5,m.z);a.lookAt(P.x,P.y+1.2,P.z);scene.add(a);AR.push({a,vx:dx/d*14,vy:dy/d*14+d*.35,vz:dz/d*14,t:0});snd(700,.06,0,.6)}
function arrowTick(dt){for(let i=AR.length-1;i>=0;i--){const q=AR[i],p=q.a.position;q.t+=dt;q.vy-=9*dt;p.x+=q.vx*dt;p.y+=q.vy*dt;p.z+=q.vz*dt;q.a.lookAt(p.x+q.vx,p.y+q.vy,p.z+q.vz);
if(Math.hypot(p.x-P.x,p.y-P.y-1,p.z-P.z)<.8){hurt(2);q.t=99}else if(SB(p.x,p.y,p.z))q.t=99;
if(q.t>4){scene.remove(q.a);AR.splice(i,1)}}}
function boom(m,R){R=R||3.2;m.dead=1;const cx=Math.floor(m.x),cy=Math.floor(m.y+.5),cz=Math.floor(m.z),dd=Math.hypot(P.x-m.x,P.y+1-m.y,P.z-m.z);if(dd<6)hurt(Math.round(Math.max(1,12-dd*2)));
const Rc=Math.ceil(R);for(let i=-Rc;i<=Rc;i++)for(let j=-Rc;j<=Rc;j++)for(let k=-Rc;k<=Rc;k++){const r=Math.hypot(i,j,k);if(r>R||(r>R*.75&&Math.random()<.4))continue;const x=cx+i,y=cy+j,z=cz+k;if(y<1||y>=H)continue;const c=chunk(x>>4,z>>4),ix=(x&15)+16*((z&15)+16*y);if(c[ix]&&c[ix]!=28){c[ix]=0;WQ.push([x,y,z]);const ek=ck(x>>4,z>>4);(ed[ek]||(ed[ek]={}))[ix]=0}}
for(let a=(cx-Rc-1)>>4;a<=(cx+Rc+1)>>4;a++)for(let b=(cz-Rc-1)>>4;b<=(cz+Rc+1)>>4;b++)meshes.has(ck(a,b))&&build(a,b);
for(let i=0;i<40;i++)padd(PB,{x:m.x,y:m.y+.8,z:m.z,vx:(Math.random()-.5)*8,vy:Math.random()*6,vz:(Math.random()-.5)*8,l:.8,gr:10,r:.5,g:.5,b:.5});snd(70,.4,0,2);snd(0,.5,1,1.2,500)}
function HAI(m,dt){const dx=P.x-m.x,dz=P.z-m.z,d=Math.hypot(dx,dz);m.go=1;m.h=Math.atan2(dx,dz);m.sv=1.7;
if(m.t==4||m.t==8){if(m.t==8)m.sv=2.2;if(d<1.3&&Math.abs(m.y-P.y)<2)hurt(m.t==8?2:3)}
else if(m.t==5){m.sv=1.5;if(d<3){m.fuse=(m.fuse||0)+dt;m.sv=0;m.g.scale.setScalar(1+Math.sin(m.fuse*20)*.06+m.fuse*.12);if(m.fuse>1.5)boom(m)}else{m.fuse=0;m.g.scale.setScalar(1)}}
else{m.fh=m.h;m.sk=(m.sk||0)-dt;if(d<6){m.h+=Math.PI;m.sv=1.6}else if(d<11)m.sv=0;else m.sv=1.5;if(d<16&&m.sk<=0){m.sk=2;shoot(m)}}}
const RPN=128,RPS=32,RPD=new Uint8Array(RPN*RPN*4).fill(128);let RP0=new Float32Array(RPN*RPN),RP1=new Float32Array(RPN*RPN),ripAct=0,ripAcc=0;
const RIPT=new THREE.DataTexture(RPD,RPN,RPN,THREE.RGBAFormat);RIPT.wrapS=RIPT.wrapT=THREE.RepeatWrapping;RIPT.magFilter=RIPT.minFilter=THREE.LinearFilter;
function ripAt(x,z,a){const u=((x/RPS)%1+1)%1,v=((z/RPS)%1+1)%1,ix=Math.floor(u*RPN),iy=Math.floor(v*RPN);for(let j=-1;j<=1;j++)for(let i=-1;i<=1;i++)RP0[((iy+j+RPN)%RPN)*RPN+((ix+i+RPN)%RPN)]+=a*(i||j?.5:1);ripAct=6}
function ripStep(){for(let y=0;y<RPN;y++){const ym=((y+RPN-1)%RPN)*RPN,yp=((y+1)%RPN)*RPN,yy=y*RPN;for(let x=0;x<RPN;x++){const xm=(x+RPN-1)%RPN,xp=(x+1)%RPN,i=yy+x;RP1[i]=((RP0[ym+x]+RP0[yp+x]+RP0[yy+xm]+RP0[yy+xp])*.5-RP1[i])*.975}}const t=RP0;RP0=RP1;RP1=t}
function ripTick(dt,w){if(w){const sp=Math.hypot(vx,vz);if(sp>.4)ripAt(P.x,P.z,sp*.05)}
MB.forEach(m=>{if(m.go&&getB(Math.floor(m.x),Math.floor(m.y+.2),Math.floor(m.z))==7)ripAt(m.x,m.z,.12)});
if(ripAct<=0)return;ripAct-=dt;ripAcc+=dt;let n=0;while(ripAcc>.05&&n++<3){ripAcc-=.05;ripStep()}
for(let i=0;i<RP0.length;i++)RPD[i*4]=Math.max(0,Math.min(255,128+RP0[i]*100));RIPT.needsUpdate=true}
function splash(x,y,z){for(let i=0;i<16;i++)padd(PB,{x,y:y+.2,z,vx:(Math.random()-.5)*2.5,vy:2+Math.random()*2.5,vz:(Math.random()-.5)*2.5,l:.8,gr:12,r:.7,g:.88,b:1})}
let wasW=0,wasH=0,bubT=0;
function uwTick(dt){const x=Math.floor(P.x),z=Math.floor(P.z),w=getB(x,Math.floor(P.y+.4),z)==7,h=getB(x,Math.floor(P.y+1.6),z)==7;
ripTick(dt,w);if(w!=wasW){wasW=w;snd(0,.4,1,1.1,1500);snd(260,.14,0,.5);ripAt(P.x,P.z,w?-3:2);splash(P.x,P.y,P.z)}
if(h!=wasH){wasH=h;if(AC){const q=AC.currentTime;if(window.SFX)SFX.frequency.setTargetAtTime(h?500:22000,q,.08);if(window.mzLP)mzLP.frequency.setTargetAtTime(h?600:7000,q,.12)}}
if(h){bubT-=dt;if(bubT<=0){bubT=.4+Math.random()*1.1;for(let i=0;i<3;i++)padd(PB,{x:P.x+(Math.random()-.5)*.6,y:P.y+1.3,z:P.z+(Math.random()-.5)*.6,vx:0,vy:1.1,vz:0,l:1.4,gr:-.4,r:.75,g:.92,b:1})}}}
let evT=0;function evTick(dt){evT-=dt;if(evT>0)return;evT=5;const pcx=Math.floor(P.x)>>4,pcz=Math.floor(P.z)>>4,lim=RD+3;ch.forEach((c,k)=>{const dm=Math.floor(k/4294967296),r=k%4294967296,cx=Math.floor(r/65536)-32768,cz=r%65536-32768;if(dm!=DIM||Math.abs(cx-pcx)>lim||Math.abs(cz-pcz)>lim){ch.delete(k);TOR.delete(k)}})}
function mobs(dt){heldTick(dt);pmTick(dt);weatherTick(dt);tntTick(dt);waterTick(dt);leafTick(dt);portal(dt);arrowTick(dt);uwTick(dt);evTick(dt);
if(OD.sv&&!DIM&&Math.sin(T*6.2832)<-.1&&MB.length<16&&Math.random()<dt*.5){const a=Math.random()*6.283,r=16+Math.random()*14,x=Math.floor(P.x+Math.cos(a)*r),z=Math.floor(P.z+Math.sin(a)*r);if(meshes.has(ck(x>>4,z>>4))){let y=H-2;while(y>0&&!getB(x,y,z))y--;if(!getB(x,y+1,z)&&SOL(getB(x,y,z))){const tt=[4,5,6,8][Math.random()*4|0],m=mkMob(tt);scene.add(m.g);MB.push(Object.assign(m,{t:tt,x:x+.5,y:y+1,z:z+.5,vy:0,h:0,tm:0,sp:0,on:0,go:1,hp:tt==5?5:6}))}}}survTick(dt);brkTick(dt);itemTick(dt);pfx(PF,dt);pfx(PB,dt);torchTick(dt);stepTick(dt);
{let cov=0;const px=Math.floor(P.x),pz=Math.floor(P.z);if(!DIM)for(let k=3;k<14;k++)if(SOL(getB(px,Math.floor(P.y)+k,pz))){cov=1;break}window.COV=cov;plamp.position.set(P.x,P.y+1.4,P.z);plamp.intensity+=((cov?2.2:0)-plamp.intensity)*Math.min(1,dt*4)}spT-=dt;
if(spT<=0&&MB.length<(OD.rd>8?18:10)){spT=2;const a=Math.random()*6.283,r=12+Math.random()*30,x=Math.floor(P.x+Math.cos(a)*r),z=Math.floor(P.z+Math.sin(a)*r),bi=bm(x,z);
if(bi!=2&&bi!=9&&meshes.has(ck(x>>4,z>>4))){let y=H-2;while(y>0&&!getB(x,y,z))y--;const b=getB(x,y,z);
if((b==1||b==13)&&!getB(x,y+1,z)){const t=bi==13?1:bi==3||bi==7?2:bi==6?1:bi==5?0:Math.random()<.12?3:Math.random()<.2?7:Math.random()*3|0,m=mkMob(t);if(t<3)m.g.scale.setScalar(t==1?1.15:1);scene.add(m.g);MB.push(Object.assign(m,{t,x:x+.5,y:y+1,z:z+.5,vy:0,h:Math.random()*6.28,tm:0,sp:0,on:0,go:0}))}}}
for(let i=MB.length-1;i>=0;i--){const m=MB[i];
if(m.dead||(HO(m.t)&&(DIM||Math.sin(T*6.2832)>.05))||Math.hypot(m.x-P.x,m.z-P.z)>80){scene.remove(m.g);MB.splice(i,1);continue}
m.tm-=dt;if(m.tm<=0){m.tm=2+Math.random()*4;m.go=Math.random()<.6;m.h=Math.random()*6.28}
if(HO(m.t))HAI(m,dt);
const v=m.go?(m.sv!=null?m.sv:1.1):0,nx=m.x+Math.sin(m.h)*v*dt,nz=m.z+Math.cos(m.h)*v*dt;
if(!SB(nx,m.y+.1,nz)){m.x=nx;m.z=nz}else if(!SB(nx,m.y+1.1,nz)&&m.on)m.vy=6.5;else m.tm=0;
m.vy-=22*dt;let ny=m.y+m.vy*dt;m.on=0;if(SB(m.x,ny,m.z)){if(m.vy<0){ny=Math.floor(ny)+1;m.on=1}m.vy=0}
m.y=Math.max(1,ny);m.sp+=dt*v*6;m.L.forEach((l,k)=>l.rotation.x=Math.sin(m.sp)*(k%2?.6:-.6));
m.g.position.set(m.x,m.y,m.z);m.g.rotation.y=(m.fh!=null?m.fh:m.h)+Math.PI}}
let mzB=null,mzN=0,mzS=0,mzP=null;
const mzF=m=>440*2**((m-69)/12);
setInterval(mzTick,250);addEventListener('pointerdown',musInit);addEventListener('keydown',musInit);
TL[7]=[DIM==1?89:8];hud.style.display='none';apply();rIc();sunL.shadow.bias=-.0006;sunL.shadow.normalBias=.065;rs();show('ti');
if(!saved)spawn();
placeCam();for(let i=0;i<12;i++)stream();
let last=performance.now(),fc=0,ft=0,fps=0;
function loop(now){
requestAnimationFrame(loop);const dt=Math.min(.05,(now-last)/1000);last=now;
if(playing){update(dt);mobs(dt);T=(T+dt/360)%1;cd-=dt;if(btn>=0&&(locked||TOUCH)&&cd<=0){act(btn);cd=.2}}
if(inG){placeCam();if(view)tpv()}else{cam.position.set(P.x,P.y+2,P.z);cam.rotation.set(-.15,pan+=dt*.05,0)}stream();if(st=='ld')ldp();env();if(++fn%4==0)R.shadowMap.needsUpdate=true;
const r=playing?ray():null;hl.visible=!!r;if(r)hl.position.set(r.x+.5,r.y+.5,r.z+.5);
WT.value=now/1000;WL.value=DIM==1?1:0;
if(OD.fx&&RT){const q=cam.position.clone().addScaledVector(dir,400).project(cam);PU.uSun.value.set(q.x*.5+.5,q.y*.5+.5);PU.uSv.value=q.z<1?Math.max(0,Math.min(1,dir.y*3+.3)):0;PU.uUW.value+=((window.UW||0)-PU.uUW.value)*.15;PU.uT.value=now/1000;PU.tD.value=RT.texture;R.setRenderTarget(RT);R.render(scene,cam);R.setRenderTarget(null);R.render(PS,PC)}else R.render(scene,cam);if(window.SHOT){window.SHOT=0;const a=document.createElement('a');a.href=cv.toDataURL('image/png');a.download='voxelcraft.png';a.click();toast('スクリーンショットを保存')}
fc++;ft+=dt;if(ft>.5){fps=Math.round(fc/ft);fc=0;ft=0;
hud.textContent='X '+P.x.toFixed(0)+'  Y '+P.y.toFixed(0)+'  Z '+P.z.toFixed(0)+'   '+fps+' fps   '+(fly?'飛行':'歩行')+'   '+(Math.sin(T*6.2832)>0?'昼':'夜')+'   '+(DIM?DN[DIM]:BN[bm(P.x|0,P.z|0)])+(window.COV&&!DIM?(()=>{const q=vn(P.x/90+1000,P.z/90+500);return q>.62?'・苔の洞窟':q<.28?'・鍾乳洞':''})():'')}}
requestAnimationFrame(loop);
</script>
</body></html>
