[index (1).html](https://github.com/user-attachments/files/28226022/index.1.html)
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<meta name="theme-color" content="#070710">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="ArtisFlow">
<meta name="description" content="ArtisFlow — Музыкальная платформа">
<title>ArtisFlow</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<script>
const manifestData={name:"ArtisFlow",short_name:"ArtisFlow",start_url:"./",display:"standalone",background_color:"#070710",theme_color:"#8c64ff",icons:[{src:"data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 192 192'><rect width='192' height='192' rx='24' fill='%238c64ff'/><text y='130' x='30' font-size='120'>🎵</text></svg>",sizes:"192x192",type:"image/svg+xml"}]};
const blob=new Blob([JSON.stringify(manifestData)],{type:'application/json'});
const link=document.createElement('link');link.rel='manifest';link.href=URL.createObjectURL(blob);document.head.appendChild(link);
</script>
<style>
:root{--bg:#070710;--bg2:#0e0e1c;--bg3:#151526;--card:#1a1a30;--bord:rgba(140,100,255,0.15);--bord2:rgba(140,100,255,0.3);--pur:#8c64ff;--pur2:#6a45d6;--red:#ff4f4f;--ora:#ff9d3d;--tex:#eeeef8;--mut:#7070a0;--fh:'Syne',sans-serif;--fb:'Inter',sans-serif;}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;}
body{background:var(--bg);color:var(--tex);font-family:var(--fb);min-height:100vh;overflow-x:hidden;}
::-webkit-scrollbar{width:3px;}::-webkit-scrollbar-track{background:var(--bg2);}::-webkit-scrollbar-thumb{background:var(--pur2);border-radius:3px;}
.nav{position:fixed;top:0;left:0;right:0;z-index:200;background:rgba(7,7,16,0.97);backdrop-filter:blur(20px);border-bottom:1px solid var(--bord);padding:0 .75rem;display:flex;align-items:center;flex-wrap:nowrap;overflow-x:auto;scrollbar-width:none;}
.nav::-webkit-scrollbar{display:none;}
.logo{font-family:var(--fh);font-size:16px;font-weight:700;padding:12px 12px 12px 0;margin-right:6px;border-right:1px solid var(--bord);white-space:nowrap;background:linear-gradient(135deg,#fff,var(--pur));-webkit-background-clip:text;-webkit-text-fill-color:transparent;flex-shrink:0;}
.nb{background:none;border:none;color:var(--mut);font-size:11px;padding:12px 8px;cursor:pointer;border-bottom:2px solid transparent;margin-bottom:-1px;display:flex;align-items:center;gap:3px;white-space:nowrap;font-family:var(--fb);}
.nb:hover{color:var(--tex);}.nb.on{color:var(--pur);border-bottom-color:var(--pur);}
.nav-r{margin-left:auto;display:flex;align-items:center;gap:4px;flex-shrink:0;padding-left:6px;}
.lsw{display:flex;background:var(--bg3);border-radius:18px;padding:2px;border:1px solid var(--bord);}
.lb{background:none;border:none;color:var(--mut);font-size:10px;padding:3px 8px;border-radius:14px;cursor:pointer;font-weight:500;}.lb.on{background:var(--pur);color:#fff;}
.db-dot{width:7px;height:7px;border-radius:50%;background:var(--mut);flex-shrink:0;}.db-dot.on{background:#7fc352;}
.pg{display:none;padding:70px 1rem 90px;max-width:1100px;margin:0 auto;}.pg.on{display:block;}
.hero{background:linear-gradient(135deg,#0a0a1a,#160a2e 50%,#0a0f1a);border-radius:14px;padding:2.5rem 1.5rem;text-align:center;margin-bottom:1.25rem;border:1px solid var(--bord);position:relative;overflow:hidden;}
.hero::before{content:'';position:absolute;inset:0;background:radial-gradient(ellipse at 65% 0%,rgba(140,100,255,.12),transparent 60%);pointer-events:none;}
.hero-t{font-family:var(--fh);font-size:44px;font-weight:700;background:linear-gradient(135deg,#fff 30%,var(--pur));-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:6px;position:relative;}
.hero-s{font-size:13px;color:var(--mut);margin-bottom:1.75rem;position:relative;}
.hbtns{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;position:relative;}
.hb{background:none;border:1px solid rgba(140,100,255,0.3);color:var(--tex);padding:9px 16px;border-radius:22px;cursor:pointer;font-size:12px;display:flex;align-items:center;gap:6px;font-family:var(--fb);}
.hb:hover{border-color:var(--pur);color:var(--pur);}.hb.pr{background:var(--pur);border-color:var(--pur);color:#fff;}
.sec-t{font-family:var(--fh);font-size:17px;font-weight:700;margin-bottom:1rem;display:flex;align-items:center;gap:7px;}.sec-t i{color:var(--pur);}
.qgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px;}
.qcard{background:var(--card);border:1px solid var(--bord);border-radius:12px;padding:1rem;cursor:pointer;}.qcard:hover{border-color:var(--pur);}
.qcard i{font-size:22px;color:var(--pur);}.qcard .qt{font-family:var(--fh);font-size:13px;font-weight:600;margin-top:7px;}.qcard .qs{font-size:10px;color:var(--mut);margin-top:2px;}
.pbar{background:var(--bg3);border:1px solid var(--bord);border-radius:14px;padding:1rem 1.1rem;margin-bottom:1.1rem;display:flex;gap:1rem;align-items:center;flex-wrap:wrap;}
.alb{width:58px;height:58px;border-radius:10px;background:linear-gradient(135deg,var(--pur),var(--red));display:flex;align-items:center;justify-content:center;flex-shrink:0;overflow:hidden;}
.alb img{width:100%;height:100%;object-fit:cover;}.alb i{font-size:24px;color:#fff;}
.tinfo{flex:1;min-width:140px;}.tn{font-family:var(--fh);font-size:14px;font-weight:600;}.ta{font-size:10px;color:var(--mut);margin-top:1px;}
.ctrls{display:flex;align-items:center;gap:8px;margin-top:7px;}
.ct{background:none;border:none;color:var(--mut);cursor:pointer;font-size:17px;display:flex;align-items:center;}.ct:hover{color:var(--tex);}
.plb{background:var(--pur);color:#fff;width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;border:none;cursor:pointer;font-size:14px;}
.pw{display:flex;align-items:center;gap:7px;flex:1;min-width:180px;font-size:10px;color:var(--mut);}
.pw input[type=range]{flex:1;accent-color:var(--pur);}
.tlist{display:flex;flex-direction:column;gap:1px;}
.ti{display:flex;align-items:center;gap:10px;padding:9px 10px;border-radius:9px;cursor:pointer;}.ti:hover{background:var(--bg3);}.ti.on{background:rgba(140,100,255,.12);border-left:3px solid var(--pur);}
.ti .tnum{width:16px;font-size:10px;color:var(--mut);text-align:center;flex-shrink:0;}.ti .tm{flex:1;min-width:0;}
.ti .tt{font-size:12px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}.ti .tart{font-size:10px;color:var(--mut);}
.ti .tpl{font-size:10px;color:var(--mut);min-width:38px;text-align:right;}.ti .td{font-size:10px;color:var(--mut);}
.ti .talb{width:32px;height:32px;border-radius:4px;object-fit:cover;flex-shrink:0;}
.vgrid,.mgrid,.ggrid,.exgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:10px;}
.vcard,.mcard,.gitem,.excard{background:var(--card);border:1px solid var(--bord);border-radius:11px;overflow:hidden;cursor:pointer;}.vcard:hover,.mcard:hover,.gitem:hover,.excard:hover{border-color:var(--pur);}
.vth,.mimg,.gth,.exth{height:100px;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;}
.vth img,.mimg img,.gth img,.exth img{width:100%;height:100%;object-fit:cover;}
.vplay{position:absolute;width:32px;height:32px;background:rgba(140,100,255,.9);border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;color:#fff;}
.vinfo,.mbody,.ginfo,.exinfo{padding:8px 10px;}.vtitle,.mname,.gtitle,.exname{font-size:11px;font-weight:500;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.vmeta,.gsub{font-size:9px;color:var(--mut);margin-top:1px;}.mprice{font-size:13px;color:var(--pur);margin-top:3px;font-weight:600;}.mold{font-size:9px;color:var(--mut);text-decoration:line-through;margin-left:2px;}
.madd{width:100%;margin-top:7px;background:var(--pur);color:#fff;border:none;border-radius:7px;padding:6px;font-size:11px;cursor:pointer;font-family:var(--fb);}
.gtag{font-size:8px;padding:2px 5px;border-radius:7px;margin-top:3px;display:inline-block;}
.exlock{position:absolute;top:0;left:0;right:0;height:100px;background:rgba(7,7,16,.82);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:5px;}
.exlock i{font-size:20px;color:var(--pur);}.exlock span{font-size:9px;color:var(--mut);}
.unlockedbg{border-color:var(--pur)!important;}
.cstrip{background:rgba(140,100,255,.1);border:1px solid var(--bord);border-radius:9px;padding:9px 12px;margin-bottom:.875rem;display:flex;align-items:center;justify-content:space-between;}
.cstrip span{font-size:11px;color:var(--pur);}.chkbtn{background:var(--pur);color:#fff;border:none;border-radius:7px;padding:5px 13px;font-size:11px;cursor:pointer;}
.evlist{display:flex;flex-direction:column;gap:9px;}
.evcard{background:var(--card);border:1px solid var(--bord);border-radius:11px;padding:1rem;display:flex;align-items:center;gap:.875rem;flex-wrap:wrap;}
.evdate{background:var(--pur);border-radius:9px;padding:7px 10px;text-align:center;flex-shrink:0;min-width:50px;}
.evdate .eday{font-family:var(--fh);font-size:18px;font-weight:700;color:#fff;line-height:1;}.evdate .emon{font-size:8px;color:rgba(255,255,255,.75);text-transform:uppercase;}
.evinfo{flex:1;}.evtitle{font-family:var(--fh);font-size:13px;font-weight:600;}.evcity{font-size:10px;color:var(--mut);}
.evbtn{background:none;border:1px solid var(--pur);color:var(--pur);padding:6px 14px;border-radius:18px;cursor:pointer;font-size:11px;}.evbtn:hover{background:var(--pur);color:#fff;}
.excta{background:var(--bg3);border:1px solid var(--bord);border-radius:12px;padding:1.25rem;text-align:center;margin-bottom:1.25rem;}
.excta h3{font-family:var(--fh);font-size:15px;font-weight:700;margin-bottom:5px;}.excta p{font-size:12px;color:var(--mut);margin-bottom:1rem;}
.ubtn{background:linear-gradient(135deg,var(--pur),var(--red));color:#fff;border:none;padding:9px 22px;border-radius:22px;cursor:pointer;font-size:13px;font-weight:500;}
.doncard{background:var(--card);border:1px solid var(--bord);border-radius:11px;padding:1rem;margin-bottom:.875rem;}
.doncard h3{font-size:13px;font-weight:600;margin-bottom:5px;display:flex;align-items:center;gap:6px;}.doncard h3 i{color:var(--pur);}
.don-desc{font-size:10px;color:var(--mut);margin-bottom:8px;}
.don-data{background:var(--bg3);border-radius:7px;padding:9px 12px;display:flex;align-items:center;justify-content:space-between;gap:7px;flex-wrap:wrap;}
.don-val{font-size:11px;font-family:monospace;word-break:break-all;}
.cpybtn{background:none;border:1px solid var(--bord);color:var(--mut);padding:4px 9px;border-radius:5px;cursor:pointer;font-size:10px;}.cpybtn:hover{border-color:var(--pur);color:var(--pur);}
.don-amts{display:flex;gap:7px;margin-bottom:1rem;flex-wrap:wrap;}
.damt{background:none;border:1px solid var(--bord);color:var(--mut);padding:5px 14px;border-radius:18px;cursor:pointer;font-size:11px;}
.about-w{display:grid;grid-template-columns:1fr 2fr;gap:1.25rem;align-items:start;}
.about-i{background:linear-gradient(135deg,var(--pur),var(--red));border-radius:14px;aspect-ratio:1;display:flex;align-items:center;justify-content:center;overflow:hidden;}
.about-i img{width:100%;height:100%;object-fit:cover;}
.about-t h2{font-family:var(--fh);font-size:20px;font-weight:700;margin-bottom:8px;}.about-t p{font-size:12px;color:var(--mut);line-height:1.75;}
.astats2{display:flex;gap:1.25rem;margin-top:.875rem;flex-wrap:wrap;}.astat2 .val{font-family:var(--fh);font-size:22px;font-weight:700;color:var(--pur);}.astat2 .lbl{font-size:10px;color:var(--mut);}
.cgrid{display:grid;grid-template-columns:1fr 1fr;gap:1.25rem;}
.cform{display:flex;flex-direction:column;gap:10px;}.cff{display:flex;flex-direction:column;gap:3px;}.cff label{font-size:10px;color:var(--mut);}
.cff input,.cff textarea{background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;font-family:var(--fb);}
.cff input:focus,.cff textarea:focus{border-color:var(--pur);}
.sndbtn{background:var(--pur);color:#fff;border:none;border-radius:7px;padding:10px;font-size:13px;cursor:pointer;}
.ci{display:flex;flex-direction:column;gap:9px;}.ciitem{background:var(--card);border:1px solid var(--bord);border-radius:9px;padding:10px 12px;display:flex;align-items:center;gap:9px;}
.ciitem i{font-size:16px;color:var(--pur);}.ciitem .cl{font-size:9px;color:var(--mut);}.ciitem .cv{font-size:12px;}
.alog-w{display:flex;align-items:center;justify-content:center;min-height:70vh;}
.alog-c{background:var(--card);border:1px solid var(--bord);border-radius:14px;padding:1.75rem;width:300px;}
.alog-c h2{font-family:var(--fh);font-size:18px;font-weight:700;margin-bottom:3px;}.alog-c p{font-size:11px;color:var(--mut);margin-bottom:1.25rem;}
.af2{display:flex;flex-direction:column;gap:3px;margin-bottom:10px;}.af2 label{font-size:10px;color:var(--mut);}
.af2 input,.af2 textarea,.af2 select{background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;font-family:var(--fb);width:100%;}
.af2 input:focus,.af2 select:focus{border-color:var(--pur);}.af2 select option{background:var(--bg2);}
.alogbtn{width:100%;background:var(--pur);color:#fff;border:none;border-radius:7px;padding:10px;font-size:13px;cursor:pointer;}
.aerr{font-size:11px;color:var(--red);margin-top:7px;display:none;}
.apanel{display:none;}
.anav{display:flex;border-bottom:1px solid var(--bord);background:var(--bg2);padding:0 .875rem;flex-wrap:nowrap;overflow-x:auto;scrollbar-width:none;position:sticky;top:50px;z-index:100;}
.anav::-webkit-scrollbar{display:none;}
.anb{background:none;border:none;color:var(--mut);font-size:11px;padding:9px 9px;cursor:pointer;border-bottom:2px solid transparent;margin-bottom:-1px;white-space:nowrap;font-family:var(--fb);}.anb.on{color:var(--pur);border-bottom-color:var(--pur);}
.ac{padding:1rem;}
.adstats{display:grid;grid-template-columns:repeat(auto-fit,minmax(110px,1fr));gap:9px;margin-bottom:1.25rem;}
.ast{background:var(--bg3);border-radius:9px;padding:.875rem;}.ast .al{font-size:10px;color:var(--mut);margin-bottom:3px;}.ast .av{font-family:var(--fh);font-size:20px;font-weight:700;}
.atable{width:100%;border-collapse:collapse;font-size:11px;}.atable th{text-align:left;padding:7px 9px;color:var(--mut);border-bottom:1px solid var(--bord);font-weight:400;}
.atable td{padding:8px 9px;border-bottom:1px solid var(--bord);vertical-align:middle;}.atable tr:hover td{background:rgba(140,100,255,.04);}
.ab{background:none;border:1px solid var(--bord);color:var(--mut);padding:3px 9px;border-radius:5px;font-size:10px;cursor:pointer;}.ab:hover{border-color:var(--pur);color:var(--pur);}
.ab.danger{border-color:rgba(255,79,79,.35);color:var(--red);}.ab.danger:hover{background:rgba(255,79,79,.1);}
.aadd{background:var(--pur);color:#fff;border:none;padding:5px 12px;border-radius:5px;font-size:11px;cursor:pointer;display:flex;align-items:center;gap:3px;}
.ash{display:flex;align-items:center;justify-content:space-between;margin-bottom:9px;}.ash h3{font-family:var(--fh);font-size:14px;font-weight:700;}
.asub{display:none;}.asub.on{display:block;}
/* UPLOAD ZONE */
.upload-zone{border:2px dashed var(--bord2);border-radius:10px;padding:1.5rem;text-align:center;cursor:pointer;transition:all .2s;position:relative;margin-bottom:8px;}
.upload-zone:hover,.upload-zone.drag{border-color:var(--pur);background:rgba(140,100,255,.05);}
.upload-zone input[type=file]{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}
.upload-zone i{font-size:28px;color:var(--pur);margin-bottom:8px;display:block;}
.upload-zone .uz-title{font-size:12px;font-weight:500;margin-bottom:3px;}
.upload-zone .uz-sub{font-size:10px;color:var(--mut);}
.upload-preview{width:100%;height:80px;object-fit:cover;border-radius:7px;margin-top:6px;display:none;}
.upload-preview.show{display:block;}
.audio-preview{width:100%;margin-top:6px;display:none;}.audio-preview.show{display:block;}
.upload-progress{height:3px;background:var(--bg3);border-radius:3px;margin-top:8px;overflow:hidden;display:none;}
.upload-progress.show{display:block;}
.upload-progress-bar{height:100%;background:var(--pur);width:0%;transition:width .3s;}
.upload-status{font-size:10px;color:var(--mut);margin-top:4px;text-align:center;}
/* MODAL */
.modal-bg{display:none;position:fixed;inset:0;background:rgba(0,0,0,.85);z-index:999;align-items:center;justify-content:center;padding:1rem;}
.modal-bg.on{display:flex;}
.modal{background:var(--bg2);border:1px solid var(--bord2);border-radius:14px;padding:1.5rem;width:100%;max-width:400px;max-height:88vh;overflow-y:auto;}
.modal h3{font-family:var(--fh);font-size:15px;font-weight:700;margin-bottom:1rem;}
.mf{display:flex;flex-direction:column;gap:10px;}
.mbtnrow{display:flex;gap:7px;margin-top:1rem;}
.msave{flex:1;background:var(--pur);color:#fff;border:none;border-radius:7px;padding:10px;font-size:12px;cursor:pointer;}
.mcanc{background:none;border:1px solid var(--bord);color:var(--mut);border-radius:7px;padding:10px 14px;font-size:12px;cursor:pointer;}
.toast{position:fixed;bottom:80px;left:50%;transform:translateX(-50%);background:var(--card);border:1px solid var(--pur);border-radius:22px;padding:9px 18px;font-size:12px;color:var(--tex);z-index:1000;opacity:0;transition:opacity .3s;pointer-events:none;white-space:nowrap;}
.toast.show{opacity:1;}
.loading{display:flex;align-items:center;justify-content:center;gap:8px;padding:2rem;color:var(--mut);font-size:12px;}
.spinner{width:16px;height:16px;border:2px solid var(--bord);border-top-color:var(--pur);border-radius:50%;animation:spin .7s linear infinite;}
@keyframes spin{to{transform:rotate(360deg);}}
.bot-nav{position:fixed;bottom:0;left:0;right:0;background:rgba(7,7,16,0.97);backdrop-filter:blur(20px);border-top:1px solid var(--bord);padding:8px 0 max(8px,env(safe-area-inset-bottom));z-index:200;display:flex;justify-content:space-around;}
.bnb{background:none;border:none;color:var(--mut);font-size:9px;display:flex;flex-direction:column;align-items:center;gap:3px;cursor:pointer;padding:4px 8px;min-width:48px;}
.bnb i{font-size:20px;}.bnb.on{color:var(--pur);}
@media(max-width:768px){.hero-t{font-size:34px;}.about-w{grid-template-columns:1fr;}.cgrid{grid-template-columns:1fr;}}
</style>
</head>
<body>
<div id="toast" class="toast"></div>
<div class="modal-bg" id="modal-bg">
  <div class="modal">
    <h3 id="modal-title">Добавить</h3>
    <div class="mf" id="modal-form"></div>
    <div class="mbtnrow"><button class="mcanc" onclick="closeModal()">Отмена</button><button class="msave" id="modal-save-btn" onclick="saveModal()">Сохранить</button></div>
  </div>
</div>
<nav class="nav">
  <div class="logo">ArtisFlow</div>
  <button class="nb on" onclick="nav('home')" id="n-home"><i class="ti ti-home"></i><span class="t" data-ru="Главная" data-en="Home">Главная</span></button>
  <button class="nb" onclick="nav('music')" id="n-music"><i class="ti ti-music"></i><span class="t" data-ru="Музыка" data-en="Music">Музыка</span></button>
  <button class="nb" onclick="nav('video')" id="n-video"><i class="ti ti-video"></i><span class="t" data-ru="Видео" data-en="Video">Видео</span></button>
  <button class="nb" onclick="nav('gallery')" id="n-gallery"><i class="ti ti-photo"></i><span class="t" data-ru="Галерея" data-en="Gallery">Галерея</span></button>
  <button class="nb" onclick="nav('events')" id="n-events"><i class="ti ti-calendar-event"></i><span class="t" data-ru="События" data-en="Events">События</span></button>
  <button class="nb" onclick="nav('merch')" id="n-merch"><i class="ti ti-shopping-bag"></i><span class="t" data-ru="Мерч" data-en="Merch">Мерч</span></button>
  <button class="nb" onclick="nav('exclusive')" id="n-exclusive"><i class="ti ti-lock"></i><span class="t" data-ru="Эксклюзив" data-en="Exclusive">Эксклюзив</span></button>
  <button class="nb" onclick="nav('donate')" id="n-donate"><i class="ti ti-heart"></i><span class="t" data-ru="Поддержать" data-en="Support">Поддержать</span></button>
  <button class="nb" onclick="nav('about')" id="n-about"><i class="ti ti-user"></i></button>
  <button class="nb" onclick="nav('contacts')" id="n-contacts"><i class="ti ti-mail"></i></button>
  <div class="nav-r">
    <div class="db-dot" id="db-dot"></div>
    <div class="lsw"><button class="lb on" id="lb-ru" onclick="setLang('ru')">RU</button><button class="lb" id="lb-en" onclick="setLang('en')">EN</button></div>
    <button class="nb" onclick="nav('admin')" id="n-admin"><i class="ti ti-shield" style="font-size:15px;"></i></button>
  </div>
</nav>

<div class="pg on" id="pg-home">
  <div class="hero">
    <div class="hero-t" id="artist-name-display">ArtisFlow</div>
    <div class="hero-s" id="artist-bio-display">Музыкант · Артист · Творец</div>
    <div class="hbtns">
      <button class="hb pr" onclick="nav('music')"><i class="ti ti-player-play"></i><span class="t" data-ru="Слушать" data-en="Listen">Слушать</span></button>
      <button class="hb" onclick="nav('video')"><i class="ti ti-video"></i><span class="t" data-ru="Видео" data-en="Videos">Видео</span></button>
      <button class="hb" onclick="nav('merch')"><i class="ti ti-shopping-bag"></i><span class="t" data-ru="Мерч" data-en="Merch">Мерч</span></button>
      <button class="hb" onclick="nav('exclusive')"><i class="ti ti-star"></i><span class="t" data-ru="Эксклюзив" data-en="Exclusive">Эксклюзив</span></button>
      <button class="hb" onclick="nav('donate')"><i class="ti ti-heart"></i><span class="t" data-ru="Поддержать" data-en="Support">Поддержать</span></button>
    </div>
  </div>
  <div class="qgrid">
    <div class="qcard" onclick="nav('music')"><i class="ti ti-music"></i><div class="qt">Музыка</div><div class="qs" id="home-tc">— треков</div></div>
    <div class="qcard" onclick="nav('events')"><i class="ti ti-calendar-event" style="color:var(--red);"></i><div class="qt">События</div><div class="qs" id="home-ec">— событий</div></div>
    <div class="qcard" onclick="nav('merch')"><i class="ti ti-shopping-bag" style="color:var(--ora);"></i><div class="qt">Мерч</div><div class="qs" id="home-mc">— товаров</div></div>
    <div class="qcard" onclick="nav('exclusive')"><i class="ti ti-lock"></i><div class="qt">Эксклюзив</div><div class="qs">Для фанатов</div></div>
  </div>
</div>

<div class="pg" id="pg-music">
  <div class="sec-t"><i class="ti ti-music"></i>Музыка</div>
  <div class="pbar">
    <div class="alb" id="player-alb"><i class="ti ti-music"></i></div>
    <div class="tinfo">
      <div class="tn" id="p-title">—</div>
      <div class="ta" id="p-artist">ArtisFlow</div>
      <div class="ctrls">
        <button class="ct" onclick="prevT()"><i class="ti ti-player-skip-back"></i></button>
        <button class="plb" onclick="togPlay()" id="plbtn"><i class="ti ti-player-play" id="plico"></i></button>
        <button class="ct" onclick="nextT()"><i class="ti ti-player-skip-forward"></i></button>
        <button class="ct" onclick="togShuf()" id="shbtn"><i class="ti ti-arrows-shuffle"></i></button>
        <button class="ct" onclick="togRep()" id="repbtn"><i class="ti ti-repeat"></i></button>
      </div>
    </div>
    <div class="pw">
      <span id="ptime">0:00</span>
      <input type="range" id="pslider" min="0" max="100" value="0" oninput="seekT(this.value)">
      <span id="pdur">0:00</span>
    </div>
  </div>
  <audio id="audio-player" style="display:none;"></audio>
  <div class="tlist" id="tracklist"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-video">
  <div class="sec-t"><i class="ti ti-video"></i>Видео</div>
  <div class="vgrid" id="vgrid"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-gallery">
  <div class="sec-t"><i class="ti ti-photo"></i>Галерея</div>
  <div style="display:flex;gap:5px;margin-bottom:.875rem;flex-wrap:wrap;">
    <button class="ab on" id="gf-all" onclick="filtG(this,'all')">Все</button>
    <button class="ab" id="gf-photo" onclick="filtG(this,'photo')">Фото</button>
    <button class="ab" id="gf-art" onclick="filtG(this,'art')">Арт</button>
    <button class="ab" id="gf-live" onclick="filtG(this,'live')">Концерты</button>
  </div>
  <div class="ggrid" id="ggrid"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-events">
  <div class="sec-t"><i class="ti ti-calendar-event"></i>События</div>
  <div class="evlist" id="evlist"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-merch">
  <div class="sec-t"><i class="ti ti-shopping-bag"></i>Магазин</div>
  <div class="cstrip" id="cstrip" style="display:none;"><span id="cinfo">0 товаров</span><button class="chkbtn" onclick="checkout()">Оформить заказ</button></div>
  <div class="mgrid" id="mgrid"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-exclusive">
  <div class="sec-t"><i class="ti ti-lock"></i>Эксклюзив</div>
  <div class="excta" id="excta">
    <h3>Стань частью фан-клуба</h3>
    <p>Эксклюзивные материалы только для подписчиков</p>
    <button class="ubtn" onclick="unlockAll()">Разблокировать</button>
  </div>
  <div class="exgrid" id="exgrid"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-donate">
  <div class="sec-t"><i class="ti ti-heart"></i>Поддержать</div>
  <p style="font-size:12px;color:var(--mut);margin-bottom:1rem;">Твоя поддержка помогает создавать новую музыку</p>
  <div class="don-amts"><button class="damt">1$</button><button class="damt">5$</button><button class="damt">10$</button><button class="damt">Своя сумма</button></div>
  <div id="donate-methods"><div class="loading"><div class="spinner"></div>Загрузка...</div></div>
</div>

<div class="pg" id="pg-about">
  <div class="sec-t"><i class="ti ti-user"></i>Об артисте</div>
  <div class="about-w">
    <div class="about-i" id="about-img-wrap"><i class="ti ti-microphone-2" style="color:#fff;font-size:52px;"></i></div>
    <div class="about-t">
      <h2 id="about-name">ArtisFlow</h2>
      <p id="about-desc">Независимый музыкант и продюсер.</p>
      <div class="astats2">
        <div class="astat2"><div class="val">200K+</div><div class="lbl">Слушателей</div></div>
        <div class="astat2"><div class="val">12</div><div class="lbl">Альбомов</div></div>
        <div class="astat2"><div class="val">150+</div><div class="lbl">Концертов</div></div>
      </div>
    </div>
  </div>
</div>

<div class="pg" id="pg-contacts">
  <div class="sec-t"><i class="ti ti-mail"></i>Контакты</div>
  <div class="cgrid">
    <div class="cform">
      <div class="cff"><label>Имя</label><input type="text" placeholder="Ваше имя"></div>
      <div class="cff"><label>Email</label><input type="email" placeholder="email@example.com"></div>
      <div class="cff"><label>Сообщение</label><textarea rows="4"></textarea></div>
      <button class="sndbtn" onclick="toast('Отправлено! ✓')">Отправить</button>
    </div>
    <div class="ci">
      <div class="ciitem"><i class="ti ti-mail"></i><div><div class="cl">Email</div><div class="cv" id="c-email">contact@artisflow.com</div></div></div>
      <div class="ciitem"><i class="ti ti-brand-instagram"></i><div><div class="cl">Instagram</div><div class="cv" id="c-ig">@artisflow</div></div></div>
      <div class="ciitem"><i class="ti ti-brand-telegram"></i><div><div class="cl">Telegram</div><div class="cv" id="c-tg">@artisflow_music</div></div></div>
    </div>
  </div>
</div>

<div class="pg" id="pg-admin">
  <div class="alog-w" id="alog">
    <div class="alog-c">
      <h2>Вход в панель</h2>
      <p>Только для администраторов</p>
      <div class="af2"><label>Email</label><input type="email" id="a-em" value="admin@artisflow.com"></div>
      <div class="af2"><label>Пароль</label><input type="password" id="a-pw" placeholder="••••••••"></div>
      <button class="alogbtn" onclick="doLogin()">Войти</button>
      <div class="aerr" id="aerr">Неверные данные</div>
    </div>
  </div>
  <div class="apanel" id="apanel">
    <div class="anav">
      <button class="anb on" onclick="asec('dash')" id="an-dash">Обзор</button>
      <button class="anb" onclick="asec('atracks')" id="an-atracks">Треки</button>
      <button class="anb" onclick="asec('avideo')" id="an-avideo">Видео</button>
      <button class="anb" onclick="asec('agallery')" id="an-agallery">Галерея</button>
      <button class="anb" onclick="asec('amerch')" id="an-amerch">Мерч</button>
      <button class="anb" onclick="asec('aevents')" id="an-aevents">События</button>
      <button class="anb" onclick="asec('aexclusive')" id="an-aexclusive">Эксклюзив</button>
      <button class="anb" onclick="asec('adon')" id="an-adon">Донаты</button>
      <button class="anb" onclick="asec('abrand')" id="an-abrand">Брендинг</button>
      <div style="margin-left:auto;display:flex;align-items:center;"><button class="ab" style="margin:7px 0;" onclick="doLogout()"><i class="ti ti-logout"></i> Выйти</button></div>
    </div>
    <div class="ac">
      <div class="asub on" id="as-dash">
        <div class="adstats">
          <div class="ast"><div class="al">Треков</div><div class="av" id="d-tracks">—</div></div>
          <div class="ast"><div class="al">Товаров</div><div class="av" id="d-merch">—</div></div>
          <div class="ast"><div class="al">Событий</div><div class="av" id="d-events">—</div></div>
          <div class="ast"><div class="al">Видео</div><div class="av" id="d-videos">—</div></div>
        </div>
        <p style="font-size:12px;color:var(--mut);">Все изменения сохраняются в Firebase и видны всем пользователям. Файлы хранятся в Cloudinary.</p>
      </div>
      <div class="asub" id="as-atracks">
        <div class="ash"><h3>Треки</h3><button class="aadd" onclick="openModal('track')"><i class="ti ti-plus"></i> Добавить</button></div>
        <table class="atable"><thead><tr><th>Обложка</th><th>Название</th><th>Артист</th><th>Дл.</th><th></th></tr></thead><tbody id="at-body"></tbody></table>
      </div>
      <div class="asub" id="as-avideo">
        <div class="ash"><h3>Видео</h3><button class="aadd" onclick="openModal('video')"><i class="ti ti-plus"></i> Добавить</button></div>
        <table class="atable"><thead><tr><th>Превью</th><th>Название</th><th>Тип</th><th></th></tr></thead><tbody id="av-body"></tbody></table>
      </div>
      <div class="asub" id="as-agallery">
        <div class="ash"><h3>Галерея</h3><button class="aadd" onclick="openModal('gallery')"><i class="ti ti-plus"></i> Добавить</button></div>
        <table class="atable"><thead><tr><th>Фото</th><th>Название</th><th>Категория</th><th></th></tr></thead><tbody id="ag-body"></tbody></table>
      </div>
      <div class="asub" id="as-amerch">
        <div class="ash"><h3>Товары</h3><button class="aadd" onclick="openModal('merch')"><i class="ti ti-plus"></i> Добавить</button></div>
        <table class="atable"><thead><tr><th>Фото</th><th>Товар</th><th>Цена</th><th></th></tr></thead><tbody id="am-body"></tbody></table>
      </div>
      <div class="asub" id="as-aevents">
        <div class="ash"><h3>События</h3><button class="aadd" onclick="openModal('event')"><i class="ti ti-plus"></i> Добавить</button></div>
        <table class="atable"><thead><tr><th>Событие</th><th>Дата</th><th>Город</th><th></th></tr></thead><tbody id="ae-body"></tbody></table>
      </div>
      <div class="asub" id="as-aexclusive">
        <div class="ash"><h3>Эксклюзив</h3><button class="aadd" onclick="openModal('exclusive')"><i class="ti ti-plus"></i> Добавить</button></div>
        <table class="atable"><thead><tr><th>Превью</th><th>Название</th><th>Тип</th><th></th></tr></thead><tbody id="ax-body"></tbody></table>
      </div>
      <div class="asub" id="as-adon">
        <div class="ash"><h3>Донаты</h3><button class="aadd" onclick="saveDon()"><i class="ti ti-device-floppy"></i> Сохранить</button></div>
        <div style="display:flex;flex-direction:column;gap:10px;">
          <div class="doncard"><h3 style="color:var(--tex);"><i class="ti ti-credit-card"></i> Банковская карта</h3>
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:7px;margin-top:7px;">
              <div class="af2"><label>Банк</label><input id="d-bank" value="Сбербанк"></div>
              <div class="af2"><label>Номер</label><input id="d-card" value="4276 8800 1234 5678"></div>
              <div class="af2"><label>Держатель</label><input id="d-holder" value="Иван А."></div>
            </div>
          </div>
          <div class="doncard"><h3 style="color:var(--tex);"><i class="ti ti-wallet"></i> WebMoney</h3>
            <div class="af2" style="margin-top:7px;"><label>Кошелёк</label><input id="d-wm" value="Z123456789012"></div>
          </div>
          <div class="doncard"><h3 style="color:var(--tex);"><i class="ti ti-currency-bitcoin"></i> Bitcoin</h3>
            <div class="af2" style="margin-top:7px;"><label>Адрес</label><input id="d-btc" value="1A2B3C4D5E6F7G8H9I0J"></div>
          </div>
        </div>
      </div>
      <div class="asub" id="as-abrand">
        <div class="ash"><h3>Брендинг</h3><button class="aadd" onclick="saveBrand()"><i class="ti ti-device-floppy"></i> Сохранить</button></div>
        <div style="display:flex;flex-direction:column;gap:9px;max-width:460px;">
          <div class="af2"><label>Имя артиста</label><input id="b-name" value="ArtisFlow"></div>
          <div class="af2"><label>Подзаголовок</label><input id="b-sub" value="Музыкант · Артист · Творец"></div>
          <div class="af2"><label>О себе</label><textarea id="b-bio" rows="3" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;">Независимый музыкант и продюсер.</textarea></div>
          <div class="af2"><label>Email</label><input id="b-email" value="contact@artisflow.com"></div>
          <div class="af2"><label>Instagram</label><input id="b-ig" value="@artisflow"></div>
          <div class="af2"><label>Telegram</label><input id="b-tg" value="@artisflow_music"></div>
          <div class="af2"><label>Фото артиста</label>
            <div class="upload-zone" id="brand-photo-zone">
              <input type="file" accept="image/*" onchange="uploadFile(this,'brand-photo','image')">
              <i class="ti ti-user-circle"></i>
              <div class="uz-title">Загрузить фото артиста</div>
              <div class="uz-sub">JPG, PNG до 10MB</div>
              <img class="upload-preview" id="brand-photo-preview">
            </div>
            <div class="upload-progress" id="brand-photo-prog"><div class="upload-progress-bar" id="brand-photo-bar"></div></div>
            <div class="upload-status" id="brand-photo-status"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="bot-nav">
  <button class="bnb on" onclick="nav('home')" id="bn-home"><i class="ti ti-home"></i><span>Главная</span></button>
  <button class="bnb" onclick="nav('music')" id="bn-music"><i class="ti ti-music"></i><span>Музыка</span></button>
  <button class="bnb" onclick="nav('merch')" id="bn-merch"><i class="ti ti-shopping-bag"></i><span>Мерч</span></button>
  <button class="bnb" onclick="nav('events')" id="bn-events"><i class="ti ti-calendar-event"></i><span>События</span></button>
  <button class="bnb" onclick="nav('admin')" id="bn-admin"><i class="ti ti-shield"></i><span>Админ</span></button>
</div>

<script type="module">
import { initializeApp } from 'https://www.gstatic.com/firebasejs/10.12.0/firebase-app.js';
import { getFirestore, collection, getDocs, addDoc, doc, updateDoc, deleteDoc, setDoc, getDoc } from 'https://www.gstatic.com/firebasejs/10.12.0/firebase-firestore.js';

// ===== CLOUDINARY CONFIG =====
const CLOUDINARY = {
  cloudName: 'dz37lvitd',
  uploadPreset: 'artisflow_upload',
  apiKey: '321346784163187'
};

// ===== FIREBASE =====
let db = null;
let fbConnected = false;

const savedCfg = localStorage.getItem('af_firebase_cfg');
if (savedCfg) {
  try {
    const cfg = JSON.parse(savedCfg);
    const app = initializeApp(cfg, 'artisflow');
    db = getFirestore(app);
    getDocs(collection(db, 'brand')).then(() => {
      fbConnected = true;
      document.getElementById('db-dot').classList.add('on');
      initApp();
    }).catch(() => showSetup());
  } catch(e) { showSetup(); }
} else { showSetup(); }

function showSetup() {
  // Inline setup
  document.body.insertAdjacentHTML('beforeend', `
  <div id="setup-overlay" style="position:fixed;inset:0;background:var(--bg);z-index:9999;display:flex;align-items:center;justify-content:center;padding:1rem;">
    <div style="background:var(--card);border:1px solid var(--bord2);border-radius:16px;padding:2rem;max-width:500px;width:100%;">
      <div style="font-family:var(--fh);font-size:20px;font-weight:700;background:linear-gradient(135deg,#fff,var(--pur));-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:6px;">🔥 Подключение Firebase</div>
      <div style="font-size:12px;color:var(--mut);margin-bottom:1.25rem;">Вставь конфиг из Firebase console</div>
      <div style="display:flex;flex-direction:column;gap:8px;">
        <div class="af2"><label>apiKey</label><input id="s-apiKey" placeholder="AIzaSy..." style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;font-family:monospace;"></div>
        <div class="af2"><label>authDomain</label><input id="s-authDomain" placeholder="app.firebaseapp.com" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;font-family:monospace;"></div>
        <div class="af2"><label>projectId</label><input id="s-projectId" placeholder="your-project" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;font-family:monospace;"></div>
        <div class="af2"><label>storageBucket</label><input id="s-storageBucket" placeholder="app.appspot.com" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;font-family:monospace;"></div>
        <div class="af2"><label>messagingSenderId</label><input id="s-messagingSenderId" placeholder="123456789" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;font-family:monospace;"></div>
        <div class="af2"><label>appId</label><input id="s-appId" placeholder="1:123:web:abc" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;font-family:monospace;"></div>
      </div>
      <button onclick="connectFB()" style="width:100%;background:linear-gradient(135deg,var(--pur),var(--pur2));color:#fff;border:none;border-radius:8px;padding:12px;font-size:14px;font-weight:600;cursor:pointer;margin-top:12px;font-family:var(--fh);">🔥 Подключить Firebase</button>
      <div id="setup-status" style="font-size:12px;margin-top:8px;text-align:center;display:none;"></div>
      <button onclick="skipFB()" style="width:100%;background:none;border:1px solid var(--bord);color:var(--mut);border-radius:8px;padding:9px;font-size:12px;cursor:pointer;margin-top:8px;">Пропустить — работать без базы данных</button>
    </div>
  </div>`);
}

window.connectFB = async function() {
  const cfg = {};
  ['apiKey','authDomain','projectId','storageBucket','messagingSenderId','appId'].forEach(k => {
    cfg[k] = document.getElementById('s-'+k)?.value.trim() || '';
  });
  if (!cfg.apiKey || !cfg.projectId) { showSt('err','Заполни apiKey и projectId!'); return; }
  showSt('','Подключаемся...');
  try {
    const app = initializeApp(cfg, 'af-'+Date.now());
    db = getFirestore(app);
    await getDocs(collection(db, 'brand'));
    fbConnected = true;
    localStorage.setItem('af_firebase_cfg', JSON.stringify(cfg));
    showSt('ok','✅ Подключено!');
    document.getElementById('db-dot').classList.add('on');
    setTimeout(() => { document.getElementById('setup-overlay')?.remove(); initApp(); }, 1000);
  } catch(e) { showSt('err','❌ '+e.message); }
};

window.skipFB = function() {
  document.getElementById('setup-overlay')?.remove();
  initApp();
};

function showSt(type, msg) {
  const el = document.getElementById('setup-status');
  if (!el) return;
  el.style.display = 'block';
  el.style.color = type === 'ok' ? '#7fc352' : type === 'err' ? 'var(--red)' : 'var(--mut)';
  el.textContent = msg;
}

// ===== CLOUDINARY UPLOAD =====
window.uploadFile = async function(input, fieldId, type) {
  const file = input.files[0];
  if (!file) return;
  const zoneId = input.closest('.upload-zone')?.id;
  const progEl = document.getElementById(fieldId+'-prog');
  const barEl = document.getElementById(fieldId+'-bar');
  const statusEl = document.getElementById(fieldId+'-status');
  const previewEl = document.getElementById(fieldId+'-preview') || document.getElementById(fieldId+'-audio');
  if (progEl) { progEl.classList.add('show'); }
  if (statusEl) statusEl.textContent = 'Загрузка...';

  const formData = new FormData();
  formData.append('file', file);
  formData.append('upload_preset', CLOUDINARY.uploadPreset);
  formData.append('cloud_name', CLOUDINARY.cloudName);

  const resourceType = type === 'audio' ? 'video' : 'image';
  const url = `https://api.cloudinary.com/v1_1/${CLOUDINARY.cloudName}/${resourceType}/upload`;

  try {
    const xhr = new XMLHttpRequest();
    xhr.open('POST', url);
    xhr.upload.onprogress = (e) => {
      if (e.lengthComputable && barEl) {
        barEl.style.width = Math.round((e.loaded/e.total)*100)+'%';
      }
    };
    xhr.onload = () => {
      const data = JSON.parse(xhr.responseText);
      if (data.secure_url) {
        window['upload_'+fieldId] = data.secure_url;
        if (statusEl) statusEl.textContent = '✅ Загружено!';
        if (previewEl) {
          previewEl.src = data.secure_url;
          previewEl.classList.add('show');
        }
        toast('Файл загружен в Cloudinary! ☁️');
      } else {
        if (statusEl) statusEl.textContent = '❌ Ошибка загрузки';
      }
    };
    xhr.onerror = () => { if (statusEl) statusEl.textContent = '❌ Ошибка сети'; };
    xhr.send(formData);
  } catch(e) {
    if (statusEl) statusEl.textContent = '❌ '+e.message;
  }
};

// ===== DATA LAYER =====
async function fbGet(col) {
  if (!db) return [];
  try { const s = await getDocs(collection(db, col)); return s.docs.map(d => ({id:d.id,...d.data()})); }
  catch(e) { return []; }
}
async function fbAdd(col, data) {
  if (!db) return {...data, id:'local_'+Date.now()};
  const r = await addDoc(collection(db, col), data); return {id:r.id,...data};
}
async function fbUpdate(col, id, data) {
  if (!db) return;
  await updateDoc(doc(db, col, id), data);
}
async function fbDelete(col, id) {
  if (!db) return;
  await deleteDoc(doc(db, col, id));
}
async function fbSetDoc(col, id, data) {
  if (!db) return;
  await setDoc(doc(db, col, id), data);
}
async function fbGetDoc(col, id) {
  if (!db) return null;
  try { const d = await getDoc(doc(db, col, id)); return d.exists() ? d.data() : null; } catch(e) { return null; }
}

// ===== APP STATE =====
let DATA = { tracks:[], videos:[], gallery:[], merch:[], events:[], exclusive:[], donations:{}, brand:{} };
let curT=0, playing=false, shuf=false, rep=false, prog=0, tmr=null;
let cart=[], cartTotal=0, lang='ru', galFil='all', modalType=null, editId=null, exUnlocked=false;
const audio = document.getElementById('audio-player');

async function initApp() {
  const [tracks,videos,gallery,merch,events,exclusive,donations,brand] = await Promise.all([
    fbGet('tracks'),fbGet('videos'),fbGet('gallery'),fbGet('merch'),
    fbGet('events'),fbGet('exclusive'),fbGetDoc('settings','donations'),fbGetDoc('settings','brand')
  ]);
  DATA.tracks = tracks;
  DATA.videos = videos;
  DATA.gallery = gallery;
  DATA.merch = merch;
  DATA.events = events;
  DATA.exclusive = exclusive;
  DATA.donations = donations || {bank:'4276 8800 1234 5678',bankName:'Сбербанк',holder:'Иван А.',wm:'Z123456789012',btc:'1A2B3C4D5E6F7G8H9I0J'};
  DATA.brand = brand || {name:'ArtisFlow',sub:'Музыкант · Артист · Творец',bio:'Независимый музыкант и продюсер.',email:'contact@artisflow.com',ig:'@artisflow',tg:'@artisflow_music'};
  applyBrand();
  renderTracks();
  updateHome();
}
window.initApp = initApp;

function applyBrand() {
  const b = DATA.brand;
  if (!b) return;
  document.getElementById('artist-name-display').textContent = b.name||'ArtisFlow';
  document.getElementById('artist-bio-display').textContent = b.sub||'';
  document.getElementById('about-name').textContent = b.name||'ArtisFlow';
  document.getElementById('about-desc').textContent = b.bio||'';
  document.getElementById('c-email').textContent = b.email||'';
  document.getElementById('c-ig').textContent = b.ig||'';
  document.getElementById('c-tg').textContent = b.tg||'';
  if (b.photo) {
    const wrap = document.getElementById('about-img-wrap');
    wrap.innerHTML = `<img src="${b.photo}" style="width:100%;height:100%;object-fit:cover;">`;
  }
}

window.nav = function(p) {
  document.querySelectorAll('.pg').forEach(x=>x.classList.remove('on'));
  document.querySelectorAll('.nb,.bnb').forEach(x=>x.classList.remove('on'));
  document.getElementById('pg-'+p)?.classList.add('on');
  document.getElementById('n-'+p)?.classList.add('on');
  document.getElementById('bn-'+p)?.classList.add('on');
  if(p==='music'){renderTracks();updPH();}
  if(p==='video')renderVideos();
  if(p==='gallery')renderGallery();
  if(p==='events')renderEvents();
  if(p==='merch')renderMerch();
  if(p==='exclusive')renderExclusive();
  if(p==='donate')renderDonate();
};

window.setLang = function(l) {
  lang=l;
  ['lb-ru','lb-en'].forEach(id=>{const el=document.getElementById(id);if(el)el.classList.toggle('on',id.endsWith('-'+l));});
  document.querySelectorAll('.t,[data-ru]').forEach(el=>{const txt=el.getAttribute('data-'+l);if(txt)el.textContent=txt;});
};

window.toast = function(msg) {
  const el=document.getElementById('toast');el.textContent=msg;el.classList.add('show');setTimeout(()=>el.classList.remove('show'),2500);
};

function updateHome() {
  document.getElementById('home-tc').textContent=DATA.tracks.length+' треков';
  document.getElementById('home-ec').textContent=DATA.events.length+' событий';
  document.getElementById('home-mc').textContent=DATA.merch.length+' товаров';
  const dt=document.getElementById('d-tracks');if(dt)dt.textContent=DATA.tracks.length;
  const dm=document.getElementById('d-merch');if(dm)dm.textContent=DATA.merch.length;
  const de=document.getElementById('d-events');if(de)de.textContent=DATA.events.length;
  const dv=document.getElementById('d-videos');if(dv)dv.textContent=DATA.videos.length;
}

// ===== PLAYER WITH REAL AUDIO =====
function renderTracks() {
  const el = document.getElementById('tracklist');
  if (!DATA.tracks.length) { el.innerHTML='<p style="color:var(--mut);padding:1rem;font-size:12px;">Нет треков. Добавь в админке!</p>'; return; }
  el.innerHTML = DATA.tracks.map((t,i)=>`
  <div class="ti ${i===curT?'on':''}" onclick="selT(${i})">
    <div class="tnum">${i===curT?'<i class="ti ti-volume" style="color:var(--pur)"></i>':(i+1)}</div>
    ${t.cover?`<img class="talb" src="${t.cover}" alt="">`:''}
    <div class="tm"><div class="tt">${t.t}</div><div class="tart">${t.a}</div></div>
    <div class="tpl">${t.pl||'—'}</div>
    <div class="td">${t.dur||'—'}</div>
  </div>`).join('');
}

function updPH() {
  if (!DATA.tracks.length) return;
  const t = DATA.tracks[Math.min(curT,DATA.tracks.length-1)];
  document.getElementById('p-title').textContent = t.t;
  document.getElementById('p-artist').textContent = t.a+' · 2024';
  document.getElementById('pdur').textContent = t.dur||'—';
  const alb = document.getElementById('player-alb');
  if (t.cover) alb.innerHTML = `<img src="${t.cover}" style="width:100%;height:100%;object-fit:cover;">`;
  else alb.innerHTML = '<i class="ti ti-music"></i>';
  if (t.audio) { audio.src = t.audio; audio.load(); }
}

window.selT = function(i) {
  curT=i; prog=0;
  document.getElementById('pslider').value=0;
  document.getElementById('ptime').textContent='0:00';
  updPH();
  if(playing) { audio.play(); }
  renderTracks();
};

window.togPlay = function() {
  playing=!playing;
  document.getElementById('plico').className=playing?'ti ti-player-pause':'ti ti-player-play';
  if(playing) {
    if (DATA.tracks[curT]?.audio) audio.play();
    else startTimer();
  } else { audio.pause(); clearInterval(tmr); }
};

audio.ontimeupdate = () => {
  if (!audio.duration) return;
  const pct = Math.round((audio.currentTime/audio.duration)*100);
  document.getElementById('pslider').value = pct;
  const m=Math.floor(audio.currentTime/60),s=Math.floor(audio.currentTime%60);
  document.getElementById('ptime').textContent=m+':'+(s<10?'0':'')+s;
  const dm=Math.floor(audio.duration/60),ds=Math.floor(audio.duration%60);
  document.getElementById('pdur').textContent=dm+':'+(ds<10?'0':'')+ds;
};
audio.onended = () => nextT();

function startTimer(){clearInterval(tmr);tmr=setInterval(()=>{prog++;const tot=200;if(prog>=tot){prog=0;nextT();return;}document.getElementById('pslider').value=Math.round((prog/tot)*100);const m=Math.floor(prog/60),s=prog%60;document.getElementById('ptime').textContent=m+':'+(s<10?'0':'')+s;},1000);}
window.nextT=function(){selT(shuf?Math.floor(Math.random()*DATA.tracks.length):(curT+1)%DATA.tracks.length);if(playing){if(DATA.tracks[curT]?.audio)audio.play();else startTimer();}};
window.prevT=function(){selT((curT-1+DATA.tracks.length)%DATA.tracks.length);if(playing){if(DATA.tracks[curT]?.audio)audio.play();else startTimer();}};
window.seekT=function(v){if(audio.src&&audio.duration){audio.currentTime=(v/100)*audio.duration;}else{prog=Math.round((v/100)*200);}};
window.togShuf=function(){shuf=!shuf;document.getElementById('shbtn').style.color=shuf?'var(--pur)':'';};
window.togRep=function(){rep=!rep;audio.loop=rep;document.getElementById('repbtn').style.color=rep?'var(--pur)':'';};

// ===== VIDEO =====
function renderVideos(){document.getElementById('vgrid').innerHTML=DATA.videos.map(v=>`<div class="vcard"><div class="vth" style="background:#1a0a2e">${v.thumbnail?`<img src="${v.thumbnail}" alt="">`:`<i class="ti ti-video" style="font-size:26px;color:rgba(140,100,255,.5);"></i>`}<div class="vplay"><i class="ti ti-player-play"></i></div></div><div class="vinfo"><div class="vtitle">${v.t}</div><div class="vmeta">${v.type||'Видео'}</div></div></div>`).join('')||'<p style="color:var(--mut);font-size:12px;">Нет видео</p>';}

// ===== GALLERY =====
function renderGallery(){const items=galFil==='all'?DATA.gallery:DATA.gallery.filter(g=>g.cat===galFil);const tc={live:{bg:'rgba(59,109,17,.2)',c:'#7fc352',l:'концерт'},photo:{bg:'rgba(24,95,165,.2)',c:'#5b9ad8',l:'фото'},art:{bg:'rgba(140,100,255,.2)',c:'var(--pur)',l:'арт'}};document.getElementById('ggrid').innerHTML=items.map(g=>`<div class="gitem"><div class="gth" style="background:#1a0a2e">${g.image?`<img src="${g.image}" alt="">`:`<i class="ti ti-photo" style="font-size:26px;color:rgba(140,100,255,.5);"></i>`}</div><div class="ginfo"><div class="gtitle">${g.t}</div><div class="gsub">${g.s||''}</div><span class="gtag" style="background:${tc[g.cat]?.bg};color:${tc[g.cat]?.c}">${tc[g.cat]?.l||g.cat}</span></div></div>`).join('')||'<p style="color:var(--mut);font-size:12px;">Нет фото</p>';}
window.filtG=function(btn,cat){galFil=cat;document.querySelectorAll('[id^="gf-"]').forEach(b=>b.classList.remove('on'));btn.classList.add('on');renderGallery();};

// ===== EVENTS =====
function renderEvents(){document.getElementById('evlist').innerHTML=DATA.events.map(e=>`<div class="evcard"><div class="evdate"><div class="eday">${e.day}</div><div class="emon">${e.mon}</div></div><div class="evinfo"><div class="evtitle">${e.t}</div><div class="evcity">${e.city}${e.venue?' · '+e.venue:''}</div></div><button class="evbtn">Купить билет</button></div>`).join('')||'<p style="color:var(--mut);font-size:12px;">Нет событий</p>';}

// ===== MERCH =====
function renderMerch(){document.getElementById('mgrid').innerHTML=DATA.merch.map((m,i)=>`<div class="mcard"><div class="mimg" style="background:var(--bg3)">${m.image?`<img src="${m.image}" alt="">`:`<span style="font-size:36px;">${m.e||'🎁'}</span>`}</div><div class="mbody"><div class="mname">${m.n}</div><div style="display:flex;align-items:baseline;"><span class="mprice">${Number(m.p||0).toLocaleString()} ₽</span>${m.old?`<span class="mold">${Number(m.old).toLocaleString()} ₽</span>`:''}</div><button class="madd" onclick="addCart(${i})"><i class="ti ti-shopping-cart-plus"></i> В корзину</button></div></div>`).join('')||'<p style="color:var(--mut);font-size:12px;">Нет товаров</p>';}
window.addCart=function(i){cart.push(DATA.merch[i]);cartTotal+=Number(DATA.merch[i].p||0);document.getElementById('cstrip').style.display='flex';document.getElementById('cinfo').textContent=cart.length+' товаров · '+cartTotal.toLocaleString()+' ₽';toast('В корзину! 🛒');};
window.checkout=function(){toast('Для заказа: '+DATA.brand.email);};

// ===== EXCLUSIVE =====
function renderExclusive(){document.getElementById('exgrid').innerHTML=DATA.exclusive.map(e=>`<div class="excard ${e.unlocked||exUnlocked?'unlockedbg':''}"><div class="exth" style="background:#1a0a2e">${e.image?`<img src="${e.image}" alt="">`:`<span style="font-size:32px;">${e.e||'🔒'}</span>`}${!(e.unlocked||exUnlocked)?`<div class="exlock"><i class="ti ti-lock"></i><span>Только для фан-клуба</span></div>`:''}</div><div class="exinfo"><div class="exname">${e.n}</div><div style="font-size:9px;color:var(--mut)">${e.t||''}</div></div></div>`).join('');}
window.unlockAll=function(){exUnlocked=true;document.getElementById('excta').style.display='none';renderExclusive();toast('Разблокировано! 🔓');};

// ===== DONATE =====
function renderDonate(){const d=DATA.donations||{};document.getElementById('donate-methods').innerHTML=`<div class="doncard"><h3><i class="ti ti-credit-card"></i> Банковская карта</h3><div class="don-desc">${d.bankName||''} · ${d.holder||''}</div><div class="don-data"><span class="don-val">${d.bank||'—'}</span><button class="cpybtn" onclick="copyTxt('${d.bank||''}',this)"><i class="ti ti-copy"></i> Копировать</button></div></div><div class="doncard"><h3><i class="ti ti-wallet"></i> WebMoney</h3><div class="don-data"><span class="don-val">${d.wm||'—'}</span><button class="cpybtn" onclick="copyTxt('${d.wm||''}',this)"><i class="ti ti-copy"></i> Копировать</button></div></div><div class="doncard"><h3><i class="ti ti-currency-bitcoin"></i> Bitcoin</h3><div class="don-data"><span class="don-val">${d.btc||'—'}</span><button class="cpybtn" onclick="copyTxt('${d.btc||''}',this)"><i class="ti ti-copy"></i> Копировать</button></div></div>`;}
window.copyTxt=function(txt,btn){navigator.clipboard.writeText(txt).catch(()=>{});const o=btn.innerHTML;btn.innerHTML='<i class="ti ti-check"></i> OK';setTimeout(()=>btn.innerHTML=o,1500);};

// ===== ADMIN =====
window.doLogin=function(){const e=document.getElementById('a-em').value.trim(),p=document.getElementById('a-pw').value;if(e==='admin@artisflow.com'&&p==='ArtisFlow_Secure_2026'){document.getElementById('alog').style.display='none';document.getElementById('apanel').style.display='block';renderAllAdmin();updateHome();}else{document.getElementById('aerr').style.display='block';}};
window.doLogout=function(){document.getElementById('alog').style.display='flex';document.getElementById('apanel').style.display='none';document.getElementById('a-pw').value='';};
window.asec=function(s){document.querySelectorAll('.asub').forEach(x=>x.classList.remove('on'));document.querySelectorAll('.anb').forEach(x=>x.classList.remove('on'));document.getElementById('as-'+s)?.classList.add('on');document.getElementById('an-'+s)?.classList.add('on');};

function renderAllAdmin(){rAT();rAV();rAG();rAM();rAE();rAX();fillDonForm();fillBrandForm();}
function thumb(url,size=32){return url?`<img src="${url}" style="width:${size}px;height:${size}px;object-fit:cover;border-radius:4px;" alt="">`:'<span style="font-size:18px;">—</span>';}
function rAT(){document.getElementById('at-body').innerHTML=DATA.tracks.map(t=>`<tr><td>${thumb(t.cover)}</td><td>${t.t}</td><td>${t.a}</td><td>${t.dur||'—'}</td><td style="display:flex;gap:3px;"><button class="ab" onclick="openModal('track','${t.id}')">Edit</button><button class="ab danger" onclick="delItem('tracks','${t.id}')">Del</button></td></tr>`).join('')||'<tr><td colspan="5" style="color:var(--mut);text-align:center;padding:1rem;">Нет треков</td></tr>';}
function rAV(){document.getElementById('av-body').innerHTML=DATA.videos.map(v=>`<tr><td>${thumb(v.thumbnail)}</td><td>${v.t}</td><td>${v.type||'—'}</td><td style="display:flex;gap:3px;"><button class="ab" onclick="openModal('video','${v.id}')">Edit</button><button class="ab danger" onclick="delItem('videos','${v.id}')">Del</button></td></tr>`).join('')||'<tr><td colspan="4" style="color:var(--mut);text-align:center;padding:1rem;">Нет видео</td></tr>';}
function rAG(){document.getElementById('ag-body').innerHTML=DATA.gallery.map(g=>`<tr><td>${thumb(g.image)}</td><td>${g.t}</td><td>${g.cat||'—'}</td><td style="display:flex;gap:3px;"><button class="ab" onclick="openModal('gallery','${g.id}')">Edit</button><button class="ab danger" onclick="delItem('gallery','${g.id}')">Del</button></td></tr>`).join('')||'<tr><td colspan="4" style="color:var(--mut);text-align:center;padding:1rem;">Нет фото</td></tr>';}
function rAM(){document.getElementById('am-body').innerHTML=DATA.merch.map(m=>`<tr><td>${thumb(m.image)||m.e||'—'}</td><td>${m.n}</td><td>${Number(m.p||0).toLocaleString()} ₽</td><td style="display:flex;gap:3px;"><button class="ab" onclick="openModal('merch','${m.id}')">Edit</button><button class="ab danger" onclick="delItem('merch','${m.id}')">Del</button></td></tr>`).join('')||'<tr><td colspan="4" style="color:var(--mut);text-align:center;padding:1rem;">Нет товаров</td></tr>';}
function rAE(){document.getElementById('ae-body').innerHTML=DATA.events.map(e=>`<tr><td>${e.t}</td><td>${e.day} ${e.mon}</td><td>${e.city}</td><td style="display:flex;gap:3px;"><button class="ab" onclick="openModal('event','${e.id}')">Edit</button><button class="ab danger" onclick="delItem('events','${e.id}')">Del</button></td></tr>`).join('')||'<tr><td colspan="4" style="color:var(--mut);text-align:center;padding:1rem;">Нет событий</td></tr>';}
function rAX(){document.getElementById('ax-body').innerHTML=DATA.exclusive.map(x=>`<tr><td>${thumb(x.image)}</td><td>${x.n}</td><td>${x.t||'—'}</td><td style="display:flex;gap:3px;"><button class="ab" onclick="openModal('exclusive','${x.id}')">Edit</button><button class="ab danger" onclick="delItem('exclusive','${x.id}')">Del</button></td></tr>`).join('')||'<tr><td colspan="4" style="color:var(--mut);text-align:center;padding:1rem;">Нет контента</td></tr>';}

window.delItem=async function(col,id){if(!confirm('Удалить?'))return;await fbDelete(col,id);DATA[col]=DATA[col].filter(x=>x.id!==id);renderAllAdmin();updateHome();toast('Удалено!');};

function fillDonForm(){const d=DATA.donations||{};document.getElementById('d-bank').value=d.bankName||'';document.getElementById('d-card').value=d.bank||'';document.getElementById('d-holder').value=d.holder||'';document.getElementById('d-wm').value=d.wm||'';document.getElementById('d-btc').value=d.btc||'';}
function fillBrandForm(){const b=DATA.brand||{};['name','sub','bio','email','ig','tg'].forEach(k=>{const el=document.getElementById('b-'+k);if(el)el.value=b[k]||'';});if(b.photo){const p=document.getElementById('brand-photo-preview');if(p){p.src=b.photo;p.classList.add('show');}}}

window.saveDon=async function(){const d={bankName:document.getElementById('d-bank').value,bank:document.getElementById('d-card').value,holder:document.getElementById('d-holder').value,wm:document.getElementById('d-wm').value,btc:document.getElementById('d-btc').value};await fbSetDoc('settings','donations',d);DATA.donations=d;toast('Донаты сохранены! 🔥');};
window.saveBrand=async function(){const b={name:document.getElementById('b-name').value,sub:document.getElementById('b-sub').value,bio:document.getElementById('b-bio').value,email:document.getElementById('b-email').value,ig:document.getElementById('b-ig').value,tg:document.getElementById('b-tg').value};if(window.upload_brand_photo)b.photo=window.upload_brand_photo;await fbSetDoc('settings','brand',b);DATA.brand=b;applyBrand();toast('Брендинг сохранён! 🔥');};

// ===== MODALS WITH FILE UPLOAD =====
function uploadField(id, label, accept, type, hint) {
  return `<div class="af2"><label>${label}</label>
  <div class="upload-zone" id="${id}-zone">
    <input type="file" accept="${accept}" onchange="uploadFile(this,'${id}','${type}')">
    <i class="ti ${type==='audio'?'ti-music':'type'==='video'?'ti-video':'ti-photo'}"></i>
    <div class="uz-title">Нажми или перетащи файл</div>
    <div class="uz-sub">${hint}</div>
    ${type==='audio'?`<audio class="audio-preview" id="${id}-audio" controls></audio>`:`<img class="upload-preview" id="${id}-preview" alt="">`}
  </div>
  <div class="upload-progress" id="${id}-prog"><div class="upload-progress-bar" id="${id}-bar"></div></div>
  <div class="upload-status" id="${id}-status"></div>
  </div>`;
}

const FORMS = {
  track: (d) => `
    ${uploadField('track-audio','🎵 Аудиофайл (MP3, WAV)','audio/*','audio','MP3, WAV, OGG до 100MB')}
    ${uploadField('track-cover','🖼 Обложка трека','image/*','image','JPG, PNG до 10MB')}
    <div class="af2"><label>Название трека</label><input id="mf-t" value="${d?.t||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Артист</label><input id="mf-a" value="${d?.a||'ArtisFlow'}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Длительность (мм:сс)</label><input id="mf-d" value="${d?.dur||'3:00'}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>`,
  video: (d) => `
    ${uploadField('video-thumb','🖼 Превью видео','image/*','image','JPG, PNG до 10MB')}
    <div class="af2"><label>Название</label><input id="mf-t" value="${d?.t||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Тип</label><select id="mf-tp" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"><option>Клип</option><option>Концерт</option><option>Behind scenes</option><option>Лирик</option></select></div>
    <div class="af2"><label>Ссылка на YouTube (необязательно)</label><input id="mf-yt" value="${d?.youtube||''}" placeholder="https://youtube.com/..." style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>`,
  gallery: (d) => `
    ${uploadField('gal-img','📷 Фотография','image/*','image','JPG, PNG до 10MB')}
    <div class="af2"><label>Название</label><input id="mf-t" value="${d?.t||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Описание</label><input id="mf-s" value="${d?.s||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Категория</label><select id="mf-c" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"><option value="photo">Фото</option><option value="art">Арт</option><option value="live">Концерт</option></select></div>`,
  merch: (d) => `
    ${uploadField('merch-img','🛍 Фото товара','image/*','image','JPG, PNG до 10MB')}
    <div class="af2"><label>Название товара</label><input id="mf-n" value="${d?.n||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Эмодзи (если нет фото)</label><input id="mf-e" value="${d?.e||'🎁'}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:60%;"></div>
    <div class="af2"><label>Цена (₽)</label><input id="mf-p" type="number" value="${d?.p||0}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Старая цена (необязательно)</label><input id="mf-o" type="number" value="${d?.old||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>`,
  event: (d) => `
    <div class="af2"><label>Название события</label><input id="mf-t" value="${d?.t||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>День</label><input id="mf-day" value="${d?.day||'1'}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Месяц (Янв, Фев...)</label><input id="mf-mon" value="${d?.mon||'Янв'}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Город</label><input id="mf-city" value="${d?.city||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Площадка</label><input id="mf-v" value="${d?.venue||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Ссылка на билеты</label><input id="mf-link" value="${d?.ticketLink||''}" placeholder="https://..." style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>`,
  exclusive: (d) => `
    ${uploadField('excl-img','🔒 Медиафайл или превью','image/*','image','JPG, PNG до 10MB')}
    <div class="af2"><label>Название</label><input id="mf-t" value="${d?.n||''}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"></div>
    <div class="af2"><label>Эмодзи</label><input id="mf-e" value="${d?.e||'🔒'}" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:60%;"></div>
    <div class="af2"><label>Тип</label><select id="mf-tp" style="background:var(--bg3);border:1px solid var(--bord);border-radius:7px;padding:9px;color:var(--tex);font-size:12px;outline:none;width:100%;"><option value="photo">Фото</option><option value="video">Видео</option><option value="audio">Аудио</option><option value="text">Текст</option></select></div>`,
};

const TNAMES={track:'трек',video:'видео',gallery:'фото',merch:'товар',event:'событие',exclusive:'контент'};
const colMap={track:'tracks',video:'videos',gallery:'gallery',merch:'merch',event:'events',exclusive:'exclusive'};

window.openModal=function(type,id){
  modalType=type;editId=id||null;
  // Clear upload caches
  ['track-audio','track-cover','video-thumb','gal-img','merch-img','excl-img'].forEach(k=>delete window['upload_'+k]);
  const item=id?DATA[colMap[type]]?.find(x=>x.id===id):null;
  document.getElementById('modal-title').textContent=(id?'Редактировать ':'Добавить ')+TNAMES[type];
  document.getElementById('modal-form').innerHTML=FORMS[type]?FORMS[type](item):'';
  document.getElementById('modal-bg').classList.add('on');
};
window.closeModal=function(){document.getElementById('modal-bg').classList.remove('on');modalType=null;editId=null;};

window.saveModal=async function(){
  const btn=document.getElementById('modal-save-btn');
  btn.textContent='Сохранение...';btn.disabled=true;
  const col=colMap[modalType];
  const g=(id)=>{const el=document.getElementById(id);return el?el.value.trim():'';};
  let nd={};
  if(modalType==='track'){
    nd={t:g('mf-t'),a:g('mf-a'),dur:g('mf-d'),s:parseInt(g('mf-d').split(':')[0]||0)*60+parseInt(g('mf-d').split(':')[1]||0)||180,pl:'0'};
    if(window.upload_track_audio)nd.audio=window.upload_track_audio;
    if(window.upload_track_cover)nd.cover=window.upload_track_cover;
  }
  if(modalType==='video'){nd={t:g('mf-t'),type:g('mf-tp'),youtube:g('mf-yt')};if(window.upload_video_thumb)nd.thumbnail=window.upload_video_thumb;}
  if(modalType==='gallery'){nd={t:g('mf-t'),s:g('mf-s'),cat:g('mf-c')};if(window.upload_gal_img)nd.image=window.upload_gal_img;}
  if(modalType==='merch'){const op=parseInt(g('mf-o'));nd={n:g('mf-n'),e:g('mf-e'),p:parseInt(g('mf-p'))||0,old:op||null};if(window.upload_merch_img)nd.image=window.upload_merch_img;}
  if(modalType==='event')nd={t:g('mf-t'),day:g('mf-day'),mon:g('mf-mon'),city:g('mf-city'),venue:g('mf-v'),ticketLink:g('mf-link')};
  if(modalType==='exclusive'){nd={n:g('mf-t'),e:g('mf-e'),t:g('mf-tp'),unlocked:false};if(window.upload_excl_img)nd.image=window.upload_excl_img;}
  try {
    if(editId){await fbUpdate(col,editId,nd);const idx=DATA[col].findIndex(x=>x.id===editId);if(idx>=0)DATA[col][idx]={...DATA[col][idx],...nd};}
    else{const item=await fbAdd(col,nd);DATA[col].push(item);}
    closeModal();renderAllAdmin();updateHome();
    if(col==='tracks')renderTracks();
    toast(fbConnected?'Сохранено в Firebase! 🔥':'Сохранено!');
  } catch(e){toast('Ошибка: '+e.message);}
  btn.textContent='Сохранить';btn.disabled=false;
};

document.getElementById('modal-bg').addEventListener('click',function(e){if(e.target===this)closeModal();});

if('serviceWorker' in navigator){
  const sw=`const C='af-v1';self.addEventListener('install',e=>e.waitUntil(caches.open(C).then(c=>c.add('/'))));self.addEventListener('fetch',e=>e.respondWith(caches.match(e.request).then(r=>r||fetch(e.request))));`;
  const swBlob=new Blob([sw],{type:'application/javascript'});
  navigator.serviceWorker.register(URL.createObjectURL(swBlob)).catch(()=>{});
}
</script>
</body>
</html>
