<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RecrutAI</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,200;0,9..144,500;0,9..144,700;0,9..144,900;1,9..144,200;1,9..144,400&family=Instrument+Sans:ital,wght@0,400;0,500;0,600;0,700;1,400&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --iv:#F4F0E8;--iv2:#EDE8DE;--iv3:#E0D8CC;--iv4:#D4CBBB;
  --ink:#16120E;--ink2:#2A2318;--ink3:#3D3328;
  --mid:#8A7D6E;--muted:#B8AC9E;
  --el:#0038FF;--el2:#E8EDFF;--el3:rgba(0,56,255,0.08);
  --gn:#1A7A4A;--gn2:#E8F5EE;
  --am:#C84B1A;--am2:#FFF0EB;
  --rd:#B83232;--rd2:#FFEAEA;
  --yw:#8A6500;--yw2:#FFF8E0;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html,body{height:100%;overflow:hidden;}
body{font-family:'Instrument Sans',sans-serif;background:var(--iv);color:var(--ink);-webkit-font-smoothing:antialiased;}
::-webkit-scrollbar{width:5px;height:5px;}::-webkit-scrollbar-track{background:var(--iv2);}::-webkit-scrollbar-thumb{background:var(--iv3);}
 
/* SCREENS */
.screen{display:none;height:100vh;overflow:hidden;}.screen.active{display:flex;}
 
/* AUTH */
#auth-screen{align-items:center;justify-content:center;background:var(--ink);position:relative;overflow:hidden;}
#auth-screen::before{content:'';position:absolute;inset:0;background:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.8' numOctaves='4'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.05'/%3E%3C/svg%3E");pointer-events:none;}
.auth-glow{position:absolute;width:500px;height:500px;border-radius:50%;background:radial-gradient(circle,rgba(0,56,255,0.12) 0%,transparent 70%);top:-100px;right:-100px;pointer-events:none;}
.auth-box{background:var(--iv);width:420px;padding:44px;position:relative;z-index:1;animation:fadeUp 0.5s ease;}
.auth-logo{display:flex;align-items:center;gap:10px;margin-bottom:32px;}
.auth-logo-sq{width:32px;height:32px;background:var(--ink);display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-size:18px;font-weight:900;color:var(--iv);}
.auth-logo-name{font-family:'Fraunces',serif;font-size:20px;font-weight:700;letter-spacing:-0.5px;color:var(--ink);}
.auth-title{font-family:'Fraunces',serif;font-size:28px;font-weight:800;letter-spacing:-1px;margin-bottom:6px;}
.auth-sub{font-size:13.5px;color:var(--mid);margin-bottom:28px;}
.auth-tabs{display:flex;border-bottom:1px solid var(--iv3);margin-bottom:24px;}
.auth-tab{padding:10px 0;margin-right:24px;font-size:13.5px;font-weight:600;cursor:pointer;border-bottom:2px solid transparent;color:var(--mid);transition:all 0.18s;}
.auth-tab.active{color:var(--ink);border-bottom-color:var(--ink);}
.form-group{margin-bottom:16px;}
.form-label{font-size:12px;font-weight:700;letter-spacing:0.5px;text-transform:uppercase;color:var(--mid);margin-bottom:7px;display:block;}
.form-input{width:100%;background:var(--iv2);border:1px solid var(--iv3);padding:11px 14px;font-family:'Instrument Sans',sans-serif;font-size:14px;color:var(--ink);outline:none;transition:border-color 0.18s;}
.form-input:focus{border-color:var(--el);}
.form-input::placeholder{color:var(--muted);}
textarea.form-input{resize:vertical;min-height:90px;line-height:1.55;}
.btn-auth{width:100%;background:var(--ink);color:var(--iv);border:none;padding:13px;font-family:'Instrument Sans',sans-serif;font-size:14px;font-weight:700;cursor:pointer;transition:all 0.2s;margin-top:8px;letter-spacing:0.02em;}
.btn-auth:hover{background:var(--el);}
 
/* APP SHELL */
#app-screen{flex-direction:row;}
.sidebar{width:220px;min-width:220px;background:var(--ink);display:flex;flex-direction:column;height:100vh;border-right:1px solid rgba(255,255,255,0.05);}
.sidebar-logo{padding:18px 20px 14px;display:flex;align-items:center;gap:10px;border-bottom:1px solid rgba(255,255,255,0.06);}
.sidebar-logo-sq{width:28px;height:28px;background:var(--iv);display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-size:15px;font-weight:900;color:var(--ink);}
.sidebar-logo-name{font-family:'Fraunces',serif;font-size:16px;font-weight:700;color:var(--iv);letter-spacing:-0.3px;}
.sidebar-nav{flex:1;padding:10px 10px;overflow-y:auto;}
.nav-section-label{font-family:'DM Mono',monospace;font-size:9px;font-weight:500;letter-spacing:2px;text-transform:uppercase;color:rgba(244,240,232,0.2);padding:12px 10px 5px;}
.nav-item{display:flex;align-items:center;gap:10px;padding:8px 10px;cursor:pointer;color:rgba(244,240,232,0.45);font-size:12.5px;font-weight:500;transition:all 0.15s;position:relative;}
.nav-item:hover{color:rgba(244,240,232,0.85);background:rgba(255,255,255,0.04);}
.nav-item.active{color:var(--iv);background:rgba(255,255,255,0.08);}
.nav-item.active::before{content:'';position:absolute;left:0;top:4px;bottom:4px;width:2px;background:var(--iv);}
.nav-icon{font-size:14px;width:18px;text-align:center;flex-shrink:0;}
.nav-badge{margin-left:auto;background:var(--el);color:#fff;font-family:'DM Mono',monospace;font-size:9px;font-weight:700;padding:2px 6px;border-radius:10px;}
.sidebar-bottom{padding:10px;border-top:1px solid rgba(255,255,255,0.06);}
.sidebar-user{display:flex;align-items:center;gap:10px;padding:8px 10px;cursor:pointer;}
.sidebar-avatar{width:28px;height:28px;background:rgba(244,240,232,0.1);display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-size:11px;font-weight:700;color:rgba(244,240,232,0.6);}
.sidebar-user-name{font-size:12px;font-weight:600;color:rgba(244,240,232,0.6);}
.sidebar-user-plan{font-size:10px;color:rgba(244,240,232,0.25);margin-top:1px;}
 
/* MAIN */
.main{flex:1;display:flex;flex-direction:column;height:100vh;overflow:hidden;background:var(--iv);}
.topbar{height:50px;min-height:50px;border-bottom:1px solid var(--iv3);display:flex;align-items:center;padding:0 24px;gap:10px;background:var(--iv);}
.topbar-title{font-family:'Fraunces',serif;font-size:16px;font-weight:700;letter-spacing:-0.4px;flex:1;}
.btn-top{border:none;cursor:pointer;font-family:'Instrument Sans',sans-serif;font-size:12.5px;font-weight:600;padding:7px 14px;transition:all 0.18s;}
.btn-top-primary{background:var(--ink);color:var(--iv);}
.btn-top-primary:hover{background:var(--el);}
.btn-top-ghost{background:none;border:1px solid var(--iv3);color:var(--mid);}
.btn-top-ghost:hover{border-color:var(--ink3);color:var(--ink);}
.page{flex:1;overflow-y:auto;padding:22px 24px;display:none;}
.page.active{display:block;}
 
/* COMPONENTS */
.overline{font-family:'DM Mono',monospace;font-size:9.5px;font-weight:500;text-transform:uppercase;letter-spacing:2px;color:var(--mid);margin-bottom:5px;}
.page-h1{font-family:'Fraunces',serif;font-size:24px;font-weight:800;letter-spacing:-1px;margin-bottom:4px;}
.section-title{font-family:'Fraunces',serif;font-size:15px;font-weight:700;letter-spacing:-0.3px;margin-bottom:12px;}
.card{background:#fff;border:1px solid var(--iv3);}
.card-pad{padding:18px;}
 
/* Pills */
.pill{display:inline-block;padding:3px 9px;font-size:11px;font-weight:700;border:1px solid;}
.pill-green{background:var(--gn2);color:var(--gn);border-color:rgba(26,122,74,0.25);}
.pill-blue{background:var(--el2);color:var(--el);border-color:rgba(0,56,255,0.2);}
.pill-yellow{background:var(--yw2);color:var(--yw);border-color:rgba(138,101,0,0.25);}
.pill-amber{background:var(--am2);color:var(--am);border-color:rgba(200,75,26,0.25);}
.pill-muted{background:var(--iv2);color:var(--mid);border-color:var(--iv3);}
.pill-red{background:var(--rd2);color:var(--rd);border-color:rgba(184,50,50,0.25);}
 
/* Score */
.score-badge{font-family:'DM Mono',monospace;font-size:12px;font-weight:700;padding:3px 9px;border:1px solid;}
.score-high{background:var(--gn2);color:var(--gn);border-color:rgba(26,122,74,0.25);}
.score-mid{background:var(--yw2);color:var(--yw);border-color:rgba(138,101,0,0.25);}
.score-low{background:var(--iv2);color:var(--mid);border-color:var(--iv3);}
 
/* Buttons */
.btn{border:none;cursor:pointer;font-family:'Instrument Sans',sans-serif;font-weight:600;transition:all 0.18s;}
.btn:disabled{opacity:0.5;cursor:not-allowed;}
.btn-ink{background:var(--ink);color:var(--iv);font-size:13px;padding:9px 16px;}
.btn-ink:hover:not(:disabled){background:var(--el);}
.btn-ghost{background:none;border:1px solid var(--iv3);color:var(--mid);font-size:13px;padding:8px 14px;}
.btn-ghost:hover:not(:disabled){border-color:var(--ink3);color:var(--ink);}
.btn-el{background:var(--el);color:#fff;font-size:13px;padding:9px 16px;}
.btn-el:hover:not(:disabled){background:#002ACC;}
.btn-danger{background:var(--rd2);color:var(--rd);border:1px solid rgba(184,50,50,0.25);font-size:13px;padding:8px 14px;}
.btn-danger:hover:not(:disabled){background:var(--rd);color:#fff;}
.btn-sm{font-size:12px !important;padding:6px 11px !important;}
.btn-icon{background:none;border:1px solid var(--iv3);color:var(--mid);padding:6px 9px;font-size:13px;cursor:pointer;transition:all 0.18s;}
.btn-icon:hover{border-color:var(--ink3);color:var(--ink);}
 
/* AI Block */
.ai-block{background:var(--el3);border:1px solid rgba(0,56,255,0.15);padding:14px 16px;margin-bottom:14px;}
.ai-block-title{font-family:'DM Mono',monospace;font-size:9.5px;font-weight:500;letter-spacing:2px;text-transform:uppercase;color:var(--el);margin-bottom:8px;display:flex;align-items:center;gap:8px;}
.ai-block-title::before{content:'';width:12px;height:1px;background:var(--el);}
.ai-block p{font-size:13px;color:var(--ink3);line-height:1.65;}
.warn-block{background:var(--am2);border:1px solid rgba(200,75,26,0.2);padding:12px 14px;margin-bottom:12px;}
.warn-title{font-family:'DM Mono',monospace;font-size:9.5px;font-weight:500;letter-spacing:1.5px;text-transform:uppercase;color:var(--am);margin-bottom:7px;}
.warn-item{font-size:13px;color:var(--ink3);padding-left:10px;border-left:2px solid rgba(200,75,26,0.35);margin-bottom:4px;}
 
/* Stats */
.stats-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:18px;}
.stat-card{background:#fff;border:1px solid var(--iv3);padding:16px 18px;}
.stat-label{font-family:'DM Mono',monospace;font-size:9px;font-weight:500;text-transform:uppercase;letter-spacing:1.5px;color:var(--mid);margin-bottom:8px;}
.stat-value{font-family:'Fraunces',serif;font-size:30px;font-weight:900;letter-spacing:-1.5px;line-height:1;}
.stat-delta{font-size:11px;color:var(--gn);font-weight:600;margin-top:5px;}
 
/* Candidate layout */
.cand-layout{display:grid;grid-template-columns:268px 1fr;gap:0;height:calc(100vh - 50px - 44px);border:1px solid var(--iv3);}
.cand-list{border-right:1px solid var(--iv3);overflow-y:auto;background:#fff;}
.cand-list-header{padding:12px 14px;border-bottom:1px solid var(--iv3);background:var(--iv2);}
.search-input{width:100%;background:var(--iv);border:1px solid var(--iv3);padding:7px 11px;font-family:'Instrument Sans',sans-serif;font-size:13px;color:var(--ink);outline:none;margin-top:7px;}
.search-input:focus{border-color:var(--el);}
.cand-item{padding:12px 14px;border-bottom:1px solid var(--iv3);cursor:pointer;transition:background 0.14s;border-left:3px solid transparent;}
.cand-item:hover{background:var(--iv2);}
.cand-item.selected{background:var(--el3);border-left-color:var(--el);}
.cand-detail{overflow-y:auto;background:var(--iv);}
.cand-detail-header{padding:20px 22px;border-bottom:1px solid var(--iv3);background:#fff;}
.cand-detail-body{padding:20px 22px;}
.detail-actions{display:flex;gap:7px;margin-bottom:16px;flex-wrap:wrap;}
 
/* Pipeline */
.pipeline-wrap{overflow-x:auto;padding-bottom:16px;}
.pipeline-grid{display:grid;grid-template-columns:repeat(5,210px);gap:12px;min-width:fit-content;}
.pipe-col-head{padding:8px 12px;margin-bottom:8px;border-bottom:2px solid;display:flex;align-items:center;justify-content:space-between;}
.pipe-col-title{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:0.5px;}
.pipe-col-count{font-family:'DM Mono',monospace;font-size:10px;font-weight:700;padding:2px 6px;border:1px solid;}
.pipe-card{background:#fff;border:1px solid var(--iv3);padding:12px;margin-bottom:7px;cursor:pointer;transition:all 0.15s;}
.pipe-card:hover{border-color:var(--ink3);}
.pipe-empty{border:1px dashed var(--iv3);padding:18px;text-align:center;font-size:12px;color:var(--muted);}
 
/* Modal */
.modal-overlay{display:none;position:fixed;inset:0;background:rgba(22,18,14,0.55);z-index:1000;align-items:center;justify-content:center;backdrop-filter:blur(4px);}
.modal-overlay.open{display:flex;}
.modal{background:var(--iv);max-height:92vh;overflow-y:auto;animation:fadeUp 0.22s ease;position:relative;}
.modal-header{padding:22px 22px 0;display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:18px;}
.modal-title{font-family:'Fraunces',serif;font-size:20px;font-weight:800;letter-spacing:-0.5px;}
.modal-close{background:none;border:none;font-size:22px;cursor:pointer;color:var(--mid);padding:0;line-height:1;}
.modal-close:hover{color:var(--ink);}
.modal-body{padding:0 22px 22px;}
.modal-footer{padding:14px 22px;border-top:1px solid var(--iv3);display:flex;gap:9px;justify-content:flex-end;}
 
/* Form */
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:12px;}
 
/* Toast */
.toast{position:fixed;bottom:22px;right:22px;background:var(--ink);color:var(--iv);padding:11px 18px;font-size:13px;font-weight:600;z-index:9999;animation:slideToast 0.3s ease;max-width:300px;display:none;}
@keyframes slideToast{from{transform:translateY(20px);opacity:0;}to{transform:translateY(0);opacity:1;}}
 
/* Spinner */
.spinner{display:inline-block;width:13px;height:13px;border:2px solid rgba(244,240,232,0.3);border-top-color:var(--iv);border-radius:50%;animation:spin 0.7s linear infinite;flex-shrink:0;}
.spinner-dark{border:2px solid var(--iv3);border-top-color:var(--ink);}
@keyframes spin{to{transform:rotate(360deg);}}
@keyframes fadeUp{from{opacity:0;transform:translateY(14px);}to{opacity:1;transform:translateY(0);}}
.fadein{animation:fadeUp 0.3s ease;}
 
/* Empty state */
.empty-state{text-align:center;padding:50px 20px;color:var(--mid);}
.empty-icon{font-size:32px;margin-bottom:12px;opacity:0.4;}
.empty-title{font-family:'Fraunces',serif;font-size:18px;font-weight:700;color:var(--ink);margin-bottom:5px;}
.empty-sub{font-size:13px;line-height:1.55;max-width:300px;margin:0 auto 18px;}
 
/* Analytics */
.analytics-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-bottom:18px;}
.chart-card{background:#fff;border:1px solid var(--iv3);padding:18px;}
.chart-title{font-size:12px;font-weight:700;text-transform:uppercase;letter-spacing:0.5px;color:var(--mid);margin-bottom:14px;}
.bar-chart{display:flex;flex-direction:column;gap:8px;}
.bar-row{display:flex;align-items:center;gap:10px;}
.bar-label{font-size:12px;color:var(--mid);width:80px;flex-shrink:0;text-align:right;}
.bar-wrap{flex:1;height:22px;background:var(--iv2);position:relative;overflow:hidden;}
.bar-fill{height:100%;transition:width 1s cubic-bezier(.4,0,.2,1);display:flex;align-items:center;padding-left:8px;}
.bar-val{font-family:'DM Mono',monospace;font-size:11px;font-weight:700;color:#fff;}
.donut-wrap{display:flex;align-items:center;gap:20px;}
.donut-legend{display:flex;flex-direction:column;gap:6px;}
.donut-item{display:flex;align-items:center;gap:7px;font-size:12px;color:var(--mid);}
.donut-dot{width:10px;height:10px;flex-shrink:0;}
 
/* Comparaison */
.compare-grid{display:grid;gap:0;border:1px solid var(--iv3);}
.compare-header{background:var(--iv2);border-bottom:1px solid var(--iv3);padding:14px 18px;display:flex;align-items:center;gap:12px;}
.compare-row{display:grid;border-bottom:1px solid var(--iv3);padding:12px 18px;align-items:start;}
.compare-row:last-child{border-bottom:none;}
.compare-row-label{font-family:'DM Mono',monospace;font-size:10px;font-weight:500;text-transform:uppercase;letter-spacing:1.5px;color:var(--mid);padding-top:2px;}
.score-bar{height:8px;background:var(--iv2);margin-top:5px;overflow:hidden;}
.score-bar-fill{height:100%;transition:width 0.8s ease;}
 
/* Email templates */
.email-template{background:var(--iv2);border:1px solid var(--iv3);padding:12px 14px;margin-bottom:8px;cursor:pointer;transition:all 0.15s;}
.email-template:hover{border-color:var(--el);background:var(--el3);}
.email-template.selected{border-color:var(--el);background:var(--el3);}
.email-template-title{font-weight:700;font-size:13px;margin-bottom:3px;}
.email-template-desc{font-size:12px;color:var(--mid);}
 
/* Jobboards */
.jb-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;}
.jb-card{background:#fff;border:1px solid var(--iv3);padding:14px;display:flex;align-items:center;gap:12px;cursor:pointer;transition:all 0.15s;text-decoration:none;}
.jb-card:hover{border-color:var(--el);background:var(--el3);}
.jb-logo{width:36px;height:36px;display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-size:11px;font-weight:700;flex-shrink:0;}
.jb-name{font-weight:700;font-size:13px;}
.jb-desc{font-size:11.5px;color:var(--mid);margin-top:2px;}
 
/* PDF print */
@media print{
  .sidebar,.topbar,.detail-actions,.btn,.modal-overlay,.toast,.nav-item{display:none!important;}
  body,html{overflow:visible!important;height:auto!important;}
  .main{overflow:visible!important;}
  #app-screen{overflow:visible!important;}
  .cand-layout{display:block!important;height:auto!important;}
  .cand-list{display:none!important;}
  .cand-detail{overflow:visible!important;}
  .page{display:block!important;padding:0!important;}
  .card{break-inside:avoid;}
  body{background:#fff!important;}
}
 
/* Onboarding */
.onboarding-step{display:none;}.onboarding-step.active{display:block;}
.onboarding-features{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin:20px 0;}
.onboarding-feature{background:var(--iv2);border:1px solid var(--iv3);padding:14px;display:flex;align-items:flex-start;gap:10px;}
.onboarding-icon{font-size:20px;flex-shrink:0;}
.onboarding-feature-title{font-size:13px;font-weight:700;margin-bottom:3px;}
.onboarding-feature-desc{font-size:12px;color:var(--mid);line-height:1.5;}
.onboarding-progress{display:flex;gap:6px;justify-content:center;margin-top:20px;}
.onboarding-dot{width:8px;height:8px;border-radius:50%;background:var(--iv3);transition:all 0.2s;}
.onboarding-dot.active{background:var(--ink);width:20px;border-radius:4px;}
 
/* Responsive */
@media(max-width:900px){
  .sidebar{width:52px;}
  .sidebar-logo-name,.nav-item span:not(.nav-icon),.nav-section-label,.sidebar-user-name,.sidebar-user-plan,.nav-badge{display:none;}
  .nav-item{justify-content:center;padding:9px;}
  .stats-grid{grid-template-columns:repeat(2,1fr);}
  .cand-layout{grid-template-columns:1fr;}
  .cand-list{max-height:280px;}
  .pipeline-grid{grid-template-columns:repeat(5,180px);}
  .form-row{grid-template-columns:1fr;}
  .analytics-grid{grid-template-columns:1fr;}
  .compare-grid .compare-row{grid-template-columns:1fr!important;}
}
@media(max-width:600px){
  .sidebar{display:none;}
  .stats-grid{grid-template-columns:1fr 1fr;}
  .topbar,.page{padding-left:16px;padding-right:16px;}
  .modal{width:96vw!important;}
  .jb-grid{grid-template-columns:1fr;}
}
</style>
</head>
<body>
 
<!-- ═══ AUTH ═══ -->
<div id="auth-screen" class="screen active">
  <div class="auth-glow"></div>
  <div class="auth-box fadein">
    <div class="auth-logo"><div class="auth-logo-sq">R</div><span class="auth-logo-name">RecrutAI</span></div>
    <h1 class="auth-title">Bienvenue</h1>
    <p class="auth-sub">Recrutez avec l'intelligence artificielle</p>
    <div class="auth-tabs">
      <div class="auth-tab active" onclick="switchAuthTab('login')">Se connecter</div>
      <div class="auth-tab" onclick="switchAuthTab('signup')">Creer un compte</div>
    </div>
    <div id="auth-login">
      <div class="form-group"><label class="form-label">Email</label><input class="form-input" id="login-email" type="email" placeholder="vous@entreprise.com" value="demo@recrut-ai.com"></div>
      <div class="form-group"><label class="form-label">Mot de passe</label><input class="form-input" id="login-pwd" type="password" placeholder="••••••••" value="demo1234"></div>
      <button class="btn-auth" onclick="login()">Se connecter</button>
    </div>
    <div id="auth-signup" style="display:none;">
      <div class="form-row">
        <div class="form-group" style="margin:0;"><label class="form-label">Prenom</label><input class="form-input" id="signup-first" type="text" placeholder="Sophie"></div>
        <div class="form-group" style="margin:0;"><label class="form-label">Nom</label><input class="form-input" id="signup-last" type="text" placeholder="Martin"></div>
      </div>
      <div class="form-group" style="margin-top:12px;"><label class="form-label">Entreprise</label><input class="form-input" id="signup-company" type="text" placeholder="Mon Entreprise SAS"></div>
      <div class="form-group"><label class="form-label">Email</label><input class="form-input" id="signup-email" type="email" placeholder="vous@entreprise.com"></div>
      <div class="form-group"><label class="form-label">Mot de passe</label><input class="form-input" id="signup-pwd" type="password" placeholder="8 caracteres minimum"></div>
      <button class="btn-auth" onclick="signup()">Creer mon compte</button>
    </div>
  </div>
</div>
 
<!-- ═══ APP ═══ -->
<div id="app-screen" class="screen">
  <div class="sidebar">
    <div class="sidebar-logo"><div class="sidebar-logo-sq">R</div><span class="sidebar-logo-name">RecrutAI</span></div>
    <nav class="sidebar-nav">
      <div class="nav-section-label">Principal</div>
      <div class="nav-item active" onclick="gotoPage('dashboard',this)"><span class="nav-icon">◈</span><span>Tableau de bord</span></div>
      <div class="nav-item" onclick="gotoPage('jobs',this)"><span class="nav-icon">◻</span><span>Offres</span><span class="nav-badge" id="jobs-badge">0</span></div>
      <div class="nav-item" onclick="gotoPage('candidates',this)"><span class="nav-icon">◎</span><span>Candidats</span></div>
      <div class="nav-item" onclick="gotoPage('pipeline',this)"><span class="nav-icon">◫</span><span>Pipeline</span></div>
      <div class="nav-item" onclick="gotoPage('compare',this)"><span class="nav-icon">⊞</span><span>Comparaison</span></div>
      <div class="nav-item" onclick="gotoPage('analytics',this)"><span class="nav-icon">◉</span><span>Analytics</span></div>
      <div class="nav-section-label">Outils IA</div>
      <div class="nav-item" onclick="gotoPage('generator',this)"><span class="nav-icon">✦</span><span>Generateur d'offres</span></div>
      <div class="nav-item" onclick="gotoPage('analyzer',this)"><span class="nav-icon">⊕</span><span>Analyse CV</span></div>
      <div class="nav-section-label">Compte</div>
      <div class="nav-item" onclick="gotoPage('settings',this)"><span class="nav-icon">⊙</span><span>Parametres</span></div>
    </nav>
    <div class="sidebar-bottom">
      <div class="sidebar-user" onclick="gotoPage('settings',null)">
        <div class="sidebar-avatar" id="sidebar-av">--</div>
        <div><div class="sidebar-user-name" id="sidebar-name">Utilisateur</div><div class="sidebar-user-plan">Plan Growth</div></div>
      </div>
    </div>
  </div>
 
  <div class="main">
    <div class="topbar">
      <div class="topbar-title" id="topbar-title">Tableau de bord</div>
      <div id="topbar-actions" style="display:flex;gap:8px;align-items:center;"></div>
    </div>
 
    <!-- DASHBOARD -->
    <div id="page-dashboard" class="page active fadein">
      <div class="stats-grid" id="dash-stats"></div>
      <div style="display:grid;grid-template-columns:1.5fr 1fr;gap:14px;">
        <div class="card card-pad"><div class="section-title">Offres actives</div><div id="dash-jobs-list"></div></div>
        <div class="card card-pad"><div class="section-title">Top candidats IA</div><div id="dash-top-candidates"></div></div>
      </div>
    </div>
 
    <!-- JOBS -->
    <div id="page-jobs" class="page fadein"><div id="jobs-content"></div></div>
 
    <!-- CANDIDATES -->
    <div id="page-candidates" class="page fadein" style="padding:0;overflow:hidden;">
      <div class="cand-layout">
        <div class="cand-list">
          <div class="cand-list-header">
            <div style="font-size:13px;font-weight:700;" id="cand-list-title">Tous les candidats</div>
            <input class="search-input" placeholder="Rechercher..." oninput="filterCandidates(this.value)" id="cand-search">
          </div>
          <div id="cand-list-items"></div>
        </div>
        <div class="cand-detail" id="cand-detail">
          <div style="display:flex;align-items:center;justify-content:center;height:100%;color:var(--mid);font-size:14px;">Selectionnez un candidat</div>
        </div>
      </div>
    </div>
 
    <!-- PIPELINE -->
    <div id="page-pipeline" class="page fadein">
      <div class="pipeline-wrap"><div class="pipeline-grid" id="pipeline-grid"></div></div>
    </div>
 
    <!-- COMPARAISON -->
    <div id="page-compare" class="page fadein">
      <div class="overline">Outil</div>
      <div class="page-h1" style="margin-bottom:18px;">Comparaison de candidats</div>
      <div style="display:flex;gap:10px;margin-bottom:18px;flex-wrap:wrap;" id="compare-selectors"></div>
      <div id="compare-result"></div>
    </div>
 
    <!-- ANALYTICS -->
    <div id="page-analytics" class="page fadein">
      <div class="overline">Reporting</div>
      <div class="page-h1" style="margin-bottom:18px;">Analytics</div>
      <div class="stats-grid" id="analytics-stats"></div>
      <div class="analytics-grid" id="analytics-charts"></div>
    </div>
 
    <!-- GENERATOR -->
    <div id="page-generator" class="page fadein">
      <div style="max-width:700px;">
        <div class="overline">Outil IA</div>
        <div class="page-h1" style="margin-bottom:18px;">Generateur d'offres d'emploi</div>
        <div class="card card-pad" style="margin-bottom:14px;">
          <div class="form-row" style="margin-bottom:12px;">
            <div class="form-group" style="margin:0;"><label class="form-label">Intitule du poste</label><input class="form-input" id="gen-title" placeholder="ex: Developpeur Full Stack"></div>
            <div class="form-group" style="margin:0;"><label class="form-label">Departement</label><input class="form-input" id="gen-dept" placeholder="ex: Tech, Produit, Marketing"></div>
          </div>
          <div class="form-row" style="margin-bottom:12px;">
            <div class="form-group" style="margin:0;"><label class="form-label">Niveau d'experience</label><input class="form-input" id="gen-level" placeholder="ex: 3-5 ans, Junior, Senior"></div>
            <div class="form-group" style="margin:0;"><label class="form-label">Type de contrat</label><input class="form-input" id="gen-contract" placeholder="ex: CDI, CDD, Freelance"></div>
          </div>
          <div class="form-group" style="margin-bottom:12px;"><label class="form-label">Brief du poste</label><textarea class="form-input" id="gen-brief" placeholder="Missions, contexte, equipe..."></textarea></div>
          <div class="form-group" style="margin:0;"><label class="form-label">Competences cles</label><input class="form-input" id="gen-skills" placeholder="ex: React, Node.js, PostgreSQL..."></div>
        </div>
        <button class="btn btn-ink" style="width:100%;padding:12px;font-size:14px;" id="gen-btn" onclick="generateJobOffer()">✦ Generer l'offre avec l'IA</button>
        <div id="gen-result" style="margin-top:14px;display:none;">
          <div class="ai-block"><div class="ai-block-title">Offre generee</div><div id="gen-result-text" style="font-size:13px;color:var(--ink3);line-height:1.7;white-space:pre-wrap;"></div></div>
          <div style="display:flex;gap:8px;flex-wrap:wrap;">
            <button class="btn btn-ink btn-sm" onclick="saveGeneratedJob()">Enregistrer comme offre</button>
            <button class="btn btn-ghost btn-sm" onclick="copyGenResult()">Copier</button>
            <button class="btn btn-ghost btn-sm" onclick="openMultidiffusion()">Diffuser sur jobboards</button>
          </div>
        </div>
      </div>
    </div>
 
    <!-- ANALYZER -->
    <div id="page-analyzer" class="page fadein">
      <div style="max-width:700px;">
        <div class="overline">Outil IA</div>
        <div class="page-h1" style="margin-bottom:18px;">Analyse de CV</div>
        <div class="card card-pad" style="margin-bottom:14px;">
          <div class="form-row" style="margin-bottom:12px;">
            <div class="form-group" style="margin:0;"><label class="form-label">Nom du candidat</label><input class="form-input" id="an-name" placeholder="Prenom Nom"></div>
            <div class="form-group" style="margin:0;"><label class="form-label">Poste cible</label><input class="form-input" id="an-job" placeholder="ex: Lead Designer"></div>
          </div>
          <div class="form-group" style="margin-bottom:12px;"><label class="form-label">Contenu du CV</label><textarea class="form-input" id="an-cv" style="min-height:150px;" placeholder="Collez ici le texte du CV..."></textarea></div>
          <div class="form-group" style="margin:0;"><label class="form-label">Criteres du poste (optionnel)</label><textarea class="form-input" id="an-criteria" style="min-height:70px;" placeholder="Criteres specifiques pour un scoring personnalise..."></textarea></div>
        </div>
        <button class="btn btn-ink" style="width:100%;padding:12px;font-size:14px;" id="an-btn" onclick="analyzeCV()">✦ Analyser le CV avec l'IA</button>
        <div id="an-result" style="margin-top:14px;display:none;"></div>
      </div>
    </div>
 
    <!-- SETTINGS -->
    <div id="page-settings" class="page fadein">
      <div style="max-width:560px;">
        <div class="overline">Configuration</div>
        <div class="page-h1" style="margin-bottom:20px;">Parametres</div>
        <div class="card card-pad" style="margin-bottom:14px;">
          <div class="section-title">Profil</div>
          <div class="form-row" style="margin-bottom:12px;">
            <div class="form-group" style="margin:0;"><label class="form-label">Prenom</label><input class="form-input" id="set-first" placeholder="Prenom"></div>
            <div class="form-group" style="margin:0;"><label class="form-label">Nom</label><input class="form-input" id="set-last" placeholder="Nom"></div>
          </div>
          <div class="form-group"><label class="form-label">Entreprise</label><input class="form-input" id="set-company" placeholder="Mon Entreprise"></div>
          <button class="btn btn-ink btn-sm" onclick="saveProfile()">Enregistrer</button>
        </div>
        <div class="card card-pad" style="margin-bottom:14px;">
          <div class="section-title">Email de l'entreprise</div>
          <p style="font-size:13px;color:var(--mid);margin-bottom:12px;">Utilise comme expediteur dans les emails candidats.</p>
          <div class="form-group"><label class="form-label">Email expediteur</label><input class="form-input" id="set-email" placeholder="recrutement@entreprise.com" type="email"></div>
          <button class="btn btn-ink btn-sm" onclick="saveEmail()">Enregistrer</button>
        </div>
        <div class="card card-pad" style="margin-bottom:14px;border-color:rgba(184,50,50,0.2);">
          <div class="section-title" style="color:var(--rd);">Zone de danger</div>
          <p style="font-size:13px;color:var(--mid);margin-bottom:12px;">Supprimer toutes vos donnees locales.</p>
          <button class="btn btn-danger btn-sm" onclick="resetAll()">Reinitialiser toutes les donnees</button>
        </div>
      </div>
    </div>
  </div>
</div>
 
<!-- ═══ MODALS ═══ -->
 
<!-- New Job -->
<div class="modal-overlay" id="modal-new-job">
  <div class="modal" style="width:540px;">
    <div class="modal-header"><div class="modal-title">Nouvelle offre</div><button class="modal-close" onclick="closeModal('modal-new-job')">×</button></div>
    <div class="modal-body">
      <div class="form-row" style="margin-bottom:12px;">
        <div class="form-group" style="margin:0;"><label class="form-label">Intitule du poste</label><input class="form-input" id="nj-title" placeholder="ex: Developpeur Full Stack"></div>
        <div class="form-group" style="margin:0;"><label class="form-label">Departement</label><input class="form-input" id="nj-dept" placeholder="ex: Tech, Produit..."></div>
      </div>
      <div class="form-group" style="margin-bottom:12px;"><label class="form-label">Description</label><textarea class="form-input" id="nj-desc" placeholder="Missions, contexte, equipe..."></textarea></div>
      <div class="form-group" style="margin-bottom:12px;"><label class="form-label">Competences requises</label><input class="form-input" id="nj-skills" placeholder="ex: React, Node.js, 3 ans min..."></div>
      <div class="form-row">
        <div class="form-group" style="margin:0;"><label class="form-label">Localisation</label><input class="form-input" id="nj-location" placeholder="Paris, Remote..."></div>
        <div class="form-group" style="margin:0;"><label class="form-label">Salaire</label><input class="form-input" id="nj-salary" placeholder="ex: 45-55k€"></div>
      </div>
    </div>
    <div class="modal-footer">
      <button class="btn btn-ghost" onclick="closeModal('modal-new-job')">Annuler</button>
      <button class="btn btn-ink" onclick="createJob()">Creer l'offre</button>
    </div>
  </div>
</div>
 
<!-- New Candidate -->
<div class="modal-overlay" id="modal-new-candidate">
  <div class="modal" style="width:580px;">
    <div class="modal-header"><div class="modal-title">Ajouter un candidat</div><button class="modal-close" onclick="closeModal('modal-new-candidate')">×</button></div>
    <div class="modal-body">
      <div class="form-row" style="margin-bottom:12px;">
        <div class="form-group" style="margin:0;"><label class="form-label">Prenom Nom</label><input class="form-input" id="nc-name" placeholder="Sophie Martin"></div>
        <div class="form-group" style="margin:0;"><label class="form-label">Email</label><input class="form-input" id="nc-email" placeholder="sophie@email.com" type="email"></div>
      </div>
      <div class="form-row" style="margin-bottom:12px;">
        <div class="form-group" style="margin:0;"><label class="form-label">Localisation</label><input class="form-input" id="nc-location" placeholder="Paris, Lyon..."></div>
        <div class="form-group" style="margin:0;"><label class="form-label">Experience</label><input class="form-input" id="nc-exp" placeholder="ex: 5 ans"></div>
      </div>
      <div class="form-group" style="margin-bottom:12px;">
        <label class="form-label">Offre associee</label>
        <select class="form-input" id="nc-job-id" style="cursor:pointer;"></select>
      </div>
      <div class="form-group" style="margin:0;"><label class="form-label">CV (coller le texte) — analyse IA automatique</label><textarea class="form-input" id="nc-cv" style="min-height:110px;" placeholder="Coller ici le texte du CV..."></textarea></div>
    </div>
    <div class="modal-footer">
      <button class="btn btn-ghost" onclick="closeModal('modal-new-candidate')">Annuler</button>
      <button class="btn btn-ink" onclick="createCandidate()">Ajouter et analyser</button>
    </div>
  </div>
</div>
 
<!-- Email Modal -->
<div class="modal-overlay" id="modal-email">
  <div class="modal" style="width:560px;">
    <div class="modal-header"><div class="modal-title">Envoyer un email</div><button class="modal-close" onclick="closeModal('modal-email')">×</button></div>
    <div class="modal-body">
      <p style="font-size:13px;color:var(--mid);margin-bottom:14px;">Choisissez un template et personnalisez avant d'envoyer.</p>
      <div id="email-templates" style="margin-bottom:16px;"></div>
      <div class="form-group" style="margin-bottom:12px;"><label class="form-label">Objet</label><input class="form-input" id="email-subject" placeholder="Objet de l'email"></div>
      <div class="form-group" style="margin:0;"><label class="form-label">Message</label><textarea class="form-input" id="email-body" style="min-height:160px;"></textarea></div>
    </div>
    <div class="modal-footer">
      <button class="btn btn-ghost" onclick="closeModal('modal-email')">Annuler</button>
      <button class="btn btn-ink" onclick="sendEmail()">Ouvrir dans la messagerie</button>
    </div>
  </div>
</div>
 
<!-- Multidiffusion Modal -->
<div class="modal-overlay" id="modal-multidiff">
  <div class="modal" style="width:520px;">
    <div class="modal-header"><div class="modal-title">Diffuser l'offre</div><button class="modal-close" onclick="closeModal('modal-multidiff')">×</button></div>
    <div class="modal-body">
      <p style="font-size:13px;color:var(--mid);margin-bottom:16px;">Publiez votre offre sur les principaux jobboards francais et internationaux.</p>
      <div class="jb-grid" id="jb-grid"></div>
      <div style="margin-top:16px;padding:12px;background:var(--iv2);border:1px solid var(--iv3);">
        <div style="font-size:12px;font-weight:700;color:var(--mid);margin-bottom:8px;">Texte de l'offre a copier</div>
        <div id="jb-offer-text" style="font-size:12px;color:var(--ink3);line-height:1.6;max-height:100px;overflow-y:auto;white-space:pre-wrap;"></div>
        <button class="btn btn-ghost btn-sm" style="margin-top:8px;" onclick="copyJobText()">Copier le texte</button>
      </div>
    </div>
    <div class="modal-footer"><button class="btn btn-ghost" onclick="closeModal('modal-multidiff')">Fermer</button></div>
  </div>
</div>
 
<!-- Onboarding Modal -->
<div class="modal-overlay" id="modal-onboarding">
  <div class="modal" style="width:560px;">
    <div class="modal-body" style="padding:32px;">
      <div id="onboarding-step-1" class="onboarding-step active">
        <div style="text-align:center;margin-bottom:24px;">
          <div style="width:56px;height:56px;background:var(--ink);display:flex;align-items:center;justify-content:center;margin:0 auto 16px;font-family:'Fraunces',serif;font-size:28px;font-weight:900;color:var(--iv);">R</div>
          <div style="font-family:'Fraunces',serif;font-size:26px;font-weight:800;letter-spacing:-1px;margin-bottom:6px;">Bienvenue sur RecrutAI</div>
          <div style="font-size:14px;color:var(--mid);">L'IA qui comprend vraiment vos candidats</div>
        </div>
        <div class="onboarding-features">
          <div class="onboarding-feature"><div class="onboarding-icon">◈</div><div><div class="onboarding-feature-title">Analyse CV par l'IA</div><div class="onboarding-feature-desc">Score 0-100 justifie en francais, red flags detectes automatiquement.</div></div></div>
          <div class="onboarding-feature"><div class="onboarding-icon">◫</div><div><div class="onboarding-feature-title">Pipeline Kanban</div><div class="onboarding-feature-desc">Suivez vos candidats de la candidature a l'offre en un coup d'oeil.</div></div></div>
          <div class="onboarding-feature"><div class="onboarding-icon">✦</div><div><div class="onboarding-feature-title">Generateur d'offres</div><div class="onboarding-feature-desc">Redigez une fiche de poste complete depuis un brief de 3 lignes.</div></div></div>
          <div class="onboarding-feature"><div class="onboarding-icon">⊞</div><div><div class="onboarding-feature-title">Comparaison IA</div><div class="onboarding-feature-desc">Comparez vos meilleurs candidats cote a cote pour decider vite.</div></div></div>
        </div>
      </div>
      <div id="onboarding-step-2" class="onboarding-step">
        <div style="font-family:'Fraunces',serif;font-size:22px;font-weight:800;letter-spacing:-0.5px;margin-bottom:8px;">Commencez en 3 etapes</div>
        <p style="font-size:13.5px;color:var(--mid);margin-bottom:20px;">Voici comment tirer le meilleur de RecrutAI des aujourd'hui.</p>
        <div style="display:flex;flex-direction:column;gap:12px;">
          <div style="display:flex;gap:14px;align-items:flex-start;padding:14px;background:var(--iv2);border:1px solid var(--iv3);">
            <div style="width:28px;height:28px;background:var(--ink);color:var(--iv);display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-size:13px;font-weight:700;flex-shrink:0;">1</div>
            <div><div style="font-weight:700;font-size:13.5px;margin-bottom:3px;">Creez votre premiere offre</div><div style="font-size:12.5px;color:var(--mid);">Allez dans "Offres" et cliquez sur "+ Nouvelle offre", ou utilisez le generateur IA.</div></div>
          </div>
          <div style="display:flex;gap:14px;align-items:flex-start;padding:14px;background:var(--iv2);border:1px solid var(--iv3);">
            <div style="width:28px;height:28px;background:var(--ink);color:var(--iv);display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-size:13px;font-weight:700;flex-shrink:0;">2</div>
            <div><div style="font-weight:700;font-size:13.5px;margin-bottom:3px;">Ajoutez vos candidats</div><div style="font-size:12.5px;color:var(--mid);">Collez le texte du CV — l'IA analyse automatiquement et genere un score.</div></div>
          </div>
          <div style="display:flex;gap:14px;align-items:flex-start;padding:14px;background:var(--iv2);border:1px solid var(--iv3);">
            <div style="width:28px;height:28px;background:var(--ink);color:var(--iv);display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-size:13px;font-weight:700;flex-shrink:0;">3</div>
            <div><div style="font-weight:700;font-size:13.5px;margin-bottom:3px;">Decidez avec la Comparaison IA</div><div style="font-size:12.5px;color:var(--mid);">Comparez vos finalistes cote a cote pour choisir le meilleur profil.</div></div>
          </div>
        </div>
      </div>
      <div class="onboarding-progress" id="onboarding-progress">
        <div class="onboarding-dot active"></div>
        <div class="onboarding-dot"></div>
      </div>
      <div style="display:flex;justify-content:space-between;margin-top:20px;" id="onboarding-nav">
        <button class="btn btn-ghost btn-sm" id="ob-back" onclick="obPrev()" style="visibility:hidden;">Precedent</button>
        <button class="btn btn-ink" id="ob-next" onclick="obNext()">Suivant</button>
      </div>
    </div>
  </div>
</div>
 
<div class="toast" id="toast"></div>
 
<script>
// ═══════════════════════════════════════
// STORAGE & STATE
// ═══════════════════════════════════════
const DB={get:k=>{try{return JSON.parse(localStorage.getItem('rai_'+k))}catch{return null}},set:(k,v)=>localStorage.setItem('rai_'+k,JSON.stringify(v)),del:k=>localStorage.removeItem('rai_'+k)};
let STATE={user:null,jobs:[],candidates:[],selectedCandidate:null,filterJob:null,emailCandidate:null,genJobText:null,genJobTitle:null,genJobDept:null,obStep:1};
 
// ═══════════════════════════════════════
// AUTH
// ═══════════════════════════════════════
function switchAuthTab(tab){
  document.querySelectorAll('.auth-tab').forEach((t,i)=>t.classList.toggle('active',(i===0&&tab==='login')||(i===1&&tab==='signup')));
  document.getElementById('auth-login').style.display=tab==='login'?'block':'none';
  document.getElementById('auth-signup').style.display=tab==='signup'?'block':'none';
}
function login(){
  const email=document.getElementById('login-email').value.trim(),pwd=document.getElementById('login-pwd').value;
  if(!email||!pwd){showToast('Remplissez tous les champs');return;}
  if(email==='demo@recrut-ai.com'){loadApp({email,name:'Demo User',first:'Demo',last:'User',company:'RecrutAI Demo'});return;}
  const users=DB.get('users')||{};
  if(!users[email]){showToast('Compte introuvable');return;}
  if(users[email].pwd!==pwd){showToast('Mot de passe incorrect');return;}
  DB.set('current_user',users[email]);loadApp(users[email]);
}
function signup(){
  const first=document.getElementById('signup-first').value.trim(),last=document.getElementById('signup-last').value.trim(),
    company=document.getElementById('signup-company').value.trim(),email=document.getElementById('signup-email').value.trim(),
    pwd=document.getElementById('signup-pwd').value;
  if(!first||!last||!email||!pwd){showToast('Remplissez tous les champs');return;}
  if(pwd.length<8){showToast('Mot de passe trop court');return;}
  const users=DB.get('users')||{};
  if(users[email]){showToast('Email deja utilise');return;}
  const user={email,first,last,name:first+' '+last,company,pwd};
  users[email]=user;DB.set('users',users);DB.set('current_user',user);
  loadApp(user,true);
}
function loadApp(user,isNew=false){
  STATE.user=user;
  STATE.jobs=DB.get('jobs_'+user.email)||getDefaultJobs();
  STATE.candidates=DB.get('candidates_'+user.email)||getDefaultCandidates();
  document.getElementById('auth-screen').classList.remove('active');
  document.getElementById('app-screen').classList.add('active');
  const ini=((user.first||user.name||'U')[0]+(user.last||user.name?.split(' ')[1]||'U')[0]).toUpperCase();
  document.getElementById('sidebar-av').textContent=ini;
  document.getElementById('sidebar-name').textContent=user.first||user.name;
  document.getElementById('set-first').value=user.first||'';
  document.getElementById('set-last').value=user.last||'';
  document.getElementById('set-company').value=user.company||'';
  document.getElementById('set-email').value=DB.get('sender_email')||'';
  renderDashboard();updateBadges();
  const seen=DB.get('onboarding_seen');
  if(!seen||isNew){openModal('modal-onboarding');DB.set('onboarding_seen',true);}
}
window.addEventListener('DOMContentLoaded',()=>{
  const u=DB.get('current_user');
  if(u){loadApp(u);return;}
  // Lire le hash pour pré-sélectionner l'onglet
  const hash=window.location.hash;
  if(hash==='#signup') switchAuthTab('signup');
  else switchAuthTab('login');
});
function resetAll(){if(!confirm('Supprimer toutes vos donnees ?'))return;const u=STATE.user;DB.del('jobs_'+u.email);DB.del('candidates_'+u.email);DB.del('current_user');location.reload();}
function saveProfile(){
  const first=document.getElementById('set-first').value.trim(),last=document.getElementById('set-last').value.trim(),company=document.getElementById('set-company').value.trim();
  STATE.user.first=first;STATE.user.last=last;STATE.user.company=company;STATE.user.name=first+' '+last;
  const users=DB.get('users')||{};if(users[STATE.user.email]){users[STATE.user.email]={...users[STATE.user.email],first,last,company};DB.set('users',users);}
  DB.set('current_user',STATE.user);
  document.getElementById('sidebar-name').textContent=first||STATE.user.name;
  document.getElementById('sidebar-av').textContent=((first||'U')[0]+(last||'U')[0]).toUpperCase();
  showToast('Profil mis a jour');
}
function saveEmail(){const e=document.getElementById('set-email').value.trim();DB.set('sender_email',e);showToast('Email enregistre');}
 
// ═══════════════════════════════════════
// ONBOARDING
// ═══════════════════════════════════════
function obNext(){
  if(STATE.obStep<2){STATE.obStep++;renderOb();}
  else{closeModal('modal-onboarding');}
}
function obPrev(){if(STATE.obStep>1){STATE.obStep--;renderOb();}}
function renderOb(){
  document.querySelectorAll('.onboarding-step').forEach(s=>s.classList.remove('active'));
  document.getElementById('onboarding-step-'+STATE.obStep).classList.add('active');
  document.querySelectorAll('.onboarding-dot').forEach((d,i)=>d.classList.toggle('active',i===STATE.obStep-1));
  document.getElementById('ob-back').style.visibility=STATE.obStep>1?'visible':'hidden';
  document.getElementById('ob-next').textContent=STATE.obStep===2?'Commencer':'Suivant';
}
 
// ═══════════════════════════════════════
// NAVIGATION
// ═══════════════════════════════════════
function gotoPage(page,navEl){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  document.getElementById('page-'+page).classList.add('active');
  if(navEl)navEl.classList.add('active');
  const titles={dashboard:'Tableau de bord',jobs:'Offres d\'emploi',candidates:'Candidats',pipeline:'Pipeline',compare:'Comparaison',analytics:'Analytics',generator:'Generateur d\'offres',analyzer:'Analyse CV',settings:'Parametres'};
  document.getElementById('topbar-title').textContent=titles[page]||page;
  const act=document.getElementById('topbar-actions');act.innerHTML='';
  if(page==='jobs')act.innerHTML='<button class="btn btn-top btn-top-primary" onclick="openModal(\'modal-new-job\')">+ Nouvelle offre</button>';
  else if(page==='candidates')act.innerHTML='<button class="btn btn-top btn-top-primary" onclick="openAddCandidate()">+ Ajouter un candidat</button>';
  else if(page==='pipeline'){
    const sel=document.createElement('select');
    sel.style.cssText='background:var(--iv2);border:1px solid var(--iv3);padding:6px 11px;font-family:inherit;font-size:12.5px;color:var(--ink);cursor:pointer;outline:none;';
    sel.innerHTML='<option value="">Toutes les offres</option>'+STATE.jobs.map(j=>`<option value="${j.id}">${j.title}</option>`).join('');
    sel.onchange=e=>{STATE.filterJob=e.target.value||null;renderPipeline();};act.appendChild(sel);
  } else if(page==='analytics')act.innerHTML='<button class="btn btn-top btn-top-ghost" onclick="exportAnalyticsPDF()">Exporter PDF</button>';
  if(page==='dashboard')renderDashboard();
  if(page==='jobs')renderJobs();
  if(page==='candidates')renderCandidates();
  if(page==='pipeline')renderPipeline();
  if(page==='compare')renderCompare();
  if(page==='analytics')renderAnalytics();
}
 
// ═══════════════════════════════════════
// DEFAULT DATA
// ═══════════════════════════════════════
function getDefaultJobs(){return[
  {id:'j1',title:'Lead Designer',dept:'Produit',description:'Concevoir et piloter la strategie design produit de notre plateforme SaaS B2B.',skills:'Figma, Design System, UX Research',location:'Paris',salary:'55-70k€',status:'actif',created:Date.now()-5*86400000},
  {id:'j2',title:'Ingenieur Full Stack',dept:'Tech',description:'Developper les nouvelles fonctionnalites de notre produit principal.',skills:'React, Node.js, PostgreSQL, AWS',location:'Remote',salary:'60-80k€',status:'actif',created:Date.now()-10*86400000},
  {id:'j3',title:'Head of Growth',dept:'Marketing',description:'Piloter la strategie d\'acquisition et de retention utilisateurs.',skills:'SEO, Paid Ads, Analytics, A/B Testing',location:'Paris',salary:'65-85k€',status:'actif',created:Date.now()-3*86400000},
];}
function getDefaultCandidates(){return[
  {id:'c1',name:'Sophie Marchand',email:'sophie.m@email.com',location:'Paris',exp:'7 ans',jobId:'j1',cvText:'7 ans en design produit SaaS. Doctolib 4 ans, direction equipe design 4 personnes, refonte design system. Figma expert, UX Research, Design System.',aiScore:94,aiSummary:'Profil exceptionnel. 7 ans en design produit B2B SaaS, direction equipe chez Doctolib. Maitrise avancee de Figma et architecture de design system. Fortement recommandee.',aiRedFlags:[],aiTags:['Figma','Design System','UX Research','Leadership'],status:'entretien',created:Date.now()-4*86400000},
  {id:'c2',name:'Thomas Lefevre',email:'t.lefevre@email.com',location:'Lyon',exp:'5 ans',jobId:'j1',cvText:'5 ans design agence. Clients PME retail et services. Figma, Sketch, After Effects, motion design.',aiScore:72,aiSummary:'Bon profil creatif, experience agence solide. Manque d\'exposition SaaS B2B. Merite un entretien pour evaluer son adaptabilite produit.',aiRedFlags:['Changement de poste tous les 18 mois'],aiTags:['Figma','Motion Design','UI'],status:'screening',created:Date.now()-2*86400000},
  {id:'c3',name:'Amina Benali',email:'amina.b@email.com',location:'Bordeaux',exp:'4 ans',jobId:'j1',cvText:'4 ans UX/UI designer startup Series A. Sessions recherche utilisateur, prototypage Figma, integration HTML/CSS.',aiScore:68,aiSummary:'Profil polyvalent UX/UI avec forte dimension recherche utilisateur. Experience startup autonome. Moins d\'exposition aux design systems a grande echelle.',aiRedFlags:[],aiTags:['UX Research','Figma','HTML/CSS'],status:'nouveau',created:Date.now()-86400000},
  {id:'c4',name:'Marc Dupont',email:'marc.d@email.com',location:'Paris',exp:'8 ans',jobId:'j2',cvText:'8 ans developpeur full stack. CTO 2 ans startup. React, Node.js, PostgreSQL, Redis, AWS. Architecture microservices, CI/CD.',aiScore:88,aiSummary:'Profil senior tres solide. 8 ans full stack avec evolution vers responsabilite technique (CTO). Expertise React/Node confirmee, maitrise architecture cloud AWS.',aiRedFlags:[],aiTags:['React','Node.js','PostgreSQL','AWS','Architecture'],status:'entretien',created:Date.now()-6*86400000},
];}
function saveData(){if(!STATE.user)return;DB.set('jobs_'+STATE.user.email,STATE.jobs);DB.set('candidates_'+STATE.user.email,STATE.candidates);}
 
// ═══════════════════════════════════════
// DASHBOARD
// ═══════════════════════════════════════
function renderDashboard(){
  const{jobs:J,candidates:C}=STATE;
  const activeJ=J.filter(j=>j.status==='actif').length,totalC=C.length,interviews=C.filter(c=>c.status==='entretien').length;
  const scored=C.filter(c=>c.aiScore);const avgScore=scored.length?Math.round(scored.reduce((a,c)=>a+c.aiScore,0)/scored.length):0;
  document.getElementById('dash-stats').innerHTML=[
    {l:'Offres actives',v:activeJ,d:`${J.length} total`},
    {l:'Candidats',v:totalC,d:`${C.filter(c=>c.status==='nouveau').length} nouveaux`},
    {l:'En entretien',v:interviews,d:'cette semaine'},
    {l:'Score IA moyen',v:avgScore+'%',d:'sur tous les CVs'}
  ].map(s=>`<div class="stat-card"><div class="stat-label">${s.l}</div><div class="stat-value">${s.v}</div><div class="stat-delta">${s.d}</div></div>`).join('');
  const jl=document.getElementById('dash-jobs-list');
  jl.innerHTML=!J.length?'<div style="color:var(--mid);font-size:13px;padding:8px 0;">Aucune offre.</div>':
    J.slice(0,4).map(j=>`<div style="display:flex;align-items:center;justify-content:space-between;padding:11px 0;border-bottom:1px solid var(--iv3);cursor:pointer;" onclick="gotoPage('jobs',document.querySelector('[onclick*=jobs]'))">
      <div><div style="font-weight:700;font-size:13.5px;">${j.title}</div><div style="font-size:12px;color:var(--mid);">${j.dept} — ${C.filter(c=>c.jobId===j.id).length} candidats</div></div>
      <span class="pill ${j.status==='actif'?'pill-green':'pill-muted'}">${j.status==='actif'?'Actif':'Pause'}</span></div>`).join('');
  const top=[...C].filter(c=>c.aiScore).sort((a,b)=>b.aiScore-a.aiScore).slice(0,4);
  document.getElementById('dash-top-candidates').innerHTML=!top.length?'<div style="color:var(--mid);font-size:13px;padding:8px 0;">Aucun candidat analyse.</div>':
    top.map(c=>`<div style="display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--iv3);cursor:pointer;" onclick="gotoPage('candidates',document.querySelector('[onclick*=candidates]'));setTimeout(()=>selectCandidate('${c.id}'),50)">
      ${avHtml(c,32)}<div style="flex:1;"><div style="font-weight:700;font-size:13px;">${c.name}</div><div style="font-size:11.5px;color:var(--mid);">${c.exp} — ${c.location}</div></div>
      <span class="score-badge ${scCls(c.aiScore)}">${c.aiScore}%</span></div>`).join('');
}
 
// ═══════════════════════════════════════
// JOBS
// ═══════════════════════════════════════
function renderJobs(){
  updateBadges();const el=document.getElementById('jobs-content');
  if(!STATE.jobs.length){el.innerHTML=`<div class="empty-state"><div class="empty-icon">◻</div><div class="empty-title">Aucune offre</div><div class="empty-sub">Creez votre premiere offre d'emploi.</div><button class="btn btn-ink" onclick="openModal('modal-new-job')">+ Creer une offre</button></div>`;return;}
  el.innerHTML=`<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:12px;">${STATE.jobs.map(j=>{
    const nc=STATE.candidates.filter(c=>c.jobId===j.id).length;
    const topScore=Math.max(0,...STATE.candidates.filter(c=>c.jobId===j.id&&c.aiScore).map(c=>c.aiScore));
    return`<div class="card card-pad" style="cursor:pointer;">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:12px;">
        <div><div style="font-family:'Fraunces',serif;font-size:17px;font-weight:700;letter-spacing:-0.3px;">${j.title}</div><div style="font-size:12px;color:var(--mid);margin-top:2px;">${j.dept}${j.location?' — '+j.location:''}</div></div>
        <span class="pill ${j.status==='actif'?'pill-green':'pill-muted'}">${j.status==='actif'?'Actif':'Pause'}</span>
      </div>
      ${j.description?`<p style="font-size:12.5px;color:var(--mid);line-height:1.55;margin-bottom:12px;">${j.description.slice(0,90)}${j.description.length>90?'...':''}</p>`:''}
      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin-bottom:12px;">
        <div style="background:var(--iv2);padding:9px;text-align:center;"><div style="font-family:'Fraunces',serif;font-size:20px;font-weight:800;">${nc}</div><div style="font-size:9.5px;color:var(--mid);margin-top:1px;text-transform:uppercase;letter-spacing:0.5px;">Candidats</div></div>
        <div style="background:var(--iv2);padding:9px;text-align:center;"><div style="font-family:'Fraunces',serif;font-size:20px;font-weight:800;color:var(--gn);">${topScore||'—'}</div><div style="font-size:9.5px;color:var(--mid);margin-top:1px;text-transform:uppercase;letter-spacing:0.5px;">Top score</div></div>
        <div style="background:var(--iv2);padding:9px;text-align:center;"><div style="font-family:'Fraunces',serif;font-size:20px;font-weight:800;">${STATE.candidates.filter(c=>c.jobId===j.id&&c.status==='entretien').length}</div><div style="font-size:9.5px;color:var(--mid);margin-top:1px;text-transform:uppercase;letter-spacing:0.5px;">Entretiens</div></div>
      </div>
      <div style="display:flex;gap:7px;">
        <button class="btn btn-ghost btn-sm" style="flex:1;" onclick="filterByJob('${j.id}')">Voir candidats</button>
        <button class="btn btn-ghost btn-sm" onclick="openMultidiffusionJob('${j.id}')" title="Diffuser">↗</button>
        <button class="btn btn-icon btn-sm" onclick="toggleJobStatus('${j.id}')" title="${j.status==='actif'?'Pause':'Reactiver'}">${j.status==='actif'?'⏸':'▶'}</button>
        <button class="btn btn-icon btn-sm" onclick="deleteJob('${j.id}')" style="color:var(--rd);border-color:rgba(184,50,50,0.2);">✕</button>
      </div>
    </div>`;}).join('')}</div>`;
}
function filterByJob(jobId){STATE.filterJob=jobId;gotoPage('candidates',document.querySelector('[onclick*=candidates]'));}
function createJob(){
  const title=document.getElementById('nj-title').value.trim();if(!title){showToast('Titre requis');return;}
  const job={id:'j'+Date.now(),title,dept:document.getElementById('nj-dept').value.trim(),description:document.getElementById('nj-desc').value.trim(),skills:document.getElementById('nj-skills').value.trim(),location:document.getElementById('nj-location').value.trim(),salary:document.getElementById('nj-salary').value.trim(),status:'actif',created:Date.now()};
  STATE.jobs.push(job);saveData();closeModal('modal-new-job');
  ['nj-title','nj-dept','nj-desc','nj-skills','nj-location','nj-salary'].forEach(id=>document.getElementById(id).value='');
  showToast('Offre creee');renderJobs();
}
function toggleJobStatus(id){const j=STATE.jobs.find(j=>j.id===id);if(j){j.status=j.status==='actif'?'pause':'actif';saveData();renderJobs();}}
function deleteJob(id){if(!confirm('Supprimer cette offre ?'))return;STATE.jobs=STATE.jobs.filter(j=>j.id!==id);saveData();renderJobs();showToast('Offre supprimee');}
function updateBadges(){document.getElementById('jobs-badge').textContent=STATE.jobs.filter(j=>j.status==='actif').length;}
 
// ═══════════════════════════════════════
// CANDIDATES
// ═══════════════════════════════════════
function renderCandidates(){
  const jf=STATE.filterJob,search=(document.getElementById('cand-search')?.value||'').toLowerCase();
  let cands=STATE.candidates;
  if(jf)cands=cands.filter(c=>c.jobId===jf);
  if(search)cands=cands.filter(c=>c.name.toLowerCase().includes(search)||c.location?.toLowerCase().includes(search));
  const jn=jf?STATE.jobs.find(j=>j.id===jf)?.title:null;
  document.getElementById('cand-list-title').textContent=jn||`Tous les candidats (${cands.length})`;
  const lel=document.getElementById('cand-list-items');
  if(!cands.length){lel.innerHTML='<div style="padding:18px;text-align:center;color:var(--mid);font-size:13px;">Aucun candidat</div>';return;}
  lel.innerHTML=cands.sort((a,b)=>(b.aiScore||0)-(a.aiScore||0)).map(c=>`
    <div class="cand-item ${STATE.selectedCandidate===c.id?'selected':''}" id="ci-${c.id}" onclick="selectCandidate('${c.id}')">
      <div style="display:flex;align-items:center;gap:9px;margin-bottom:7px;">
        ${avHtml(c,32)}<div style="flex:1;min-width:0;"><div style="font-weight:700;font-size:12.5px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;">${c.name}</div><div style="font-size:11px;color:var(--mid);">${c.exp||''}${c.exp&&c.location?' — ':''}${c.location||''}</div></div>
        ${c.aiScore?`<span class="score-badge ${scCls(c.aiScore)}" style="font-size:11px;">${c.aiScore}%</span>`:'<span style="font-size:11px;color:var(--muted);">—</span>'}
      </div>
      <div style="display:flex;gap:5px;flex-wrap:wrap;">${(c.aiTags||[]).slice(0,2).map(t=>`<span style="font-size:10px;background:var(--iv2);border:1px solid var(--iv3);padding:1px 6px;color:var(--mid);">${t}</span>`).join('')}${statusPill(c.status)}</div>
    </div>`).join('');
  if(STATE.selectedCandidate)selectCandidate(STATE.selectedCandidate);
  else if(cands.length)selectCandidate(cands[0].id);
}
function filterCandidates(){renderCandidates();}
function selectCandidate(id){
  STATE.selectedCandidate=id;
  document.querySelectorAll('.cand-item').forEach(el=>el.classList.toggle('selected',el.id==='ci-'+id));
  const c=STATE.candidates.find(x=>x.id===id);if(c)renderCandidateDetail(c);
}
function renderCandidateDetail(c){
  const det=document.getElementById('cand-detail'),job=STATE.jobs.find(j=>j.id===c.jobId);
  det.innerHTML=`
    <div class="cand-detail-header">
      <div style="display:flex;align-items:flex-start;justify-content:space-between;">
        <div style="display:flex;gap:12px;align-items:center;">
          ${avHtml(c,48)}
          <div>
            <div style="font-family:'Fraunces',serif;font-size:20px;font-weight:800;letter-spacing:-0.5px;">${c.name}</div>
            <div style="font-size:12.5px;color:var(--mid);margin-top:2px;">${c.exp||''}${c.exp&&c.location?' — ':''}${c.location||''}${job?' — '+job.title:''}</div>
            <div style="display:flex;gap:5px;margin-top:7px;flex-wrap:wrap;">${(c.aiTags||[]).map(t=>`<span style="font-size:11px;background:var(--iv2);border:1px solid var(--iv3);padding:2px 7px;color:var(--mid);">${t}</span>`).join('')}</div>
          </div>
        </div>
        ${c.aiScore?`<div style="text-align:right;"><div style="font-family:'Fraunces',serif;font-size:44px;font-weight:900;letter-spacing:-2px;color:${c.aiScore>=80?'var(--gn)':c.aiScore>=60?'var(--yw)':'var(--mid)'};line-height:1;">${c.aiScore}</div><div style="font-family:'DM Mono',monospace;font-size:9px;letter-spacing:2px;text-transform:uppercase;color:var(--mid);margin-top:1px;">Score IA</div></div>`:''}
      </div>
    </div>
    <div class="cand-detail-body">
      <div class="detail-actions">
        <select class="form-input" style="padding:6px 11px;font-size:12px;cursor:pointer;width:auto;" onchange="updateCandStatus('${c.id}',this.value)">
          ${['nouveau','screening','entretien','offre','refus'].map(s=>`<option value="${s}" ${c.status===s?'selected':''}>${s.charAt(0).toUpperCase()+s.slice(1)}</option>`).join('')}
        </select>
        <button class="btn btn-ghost btn-sm" onclick="analyzeCandidateCV('${c.id}')">${c.aiScore?'Re-analyser':'✦ Analyser CV'}</button>
        <button class="btn btn-ghost btn-sm" onclick="openEmailModal('${c.id}')">Email</button>
        <button class="btn btn-ghost btn-sm" onclick="exportCandidatePDF('${c.id}')">Export PDF</button>
        <button class="btn btn-danger btn-sm" onclick="deleteCandidate('${c.id}')">Supprimer</button>
      </div>
      ${c.aiSummary?`<div class="ai-block"><div class="ai-block-title">Analyse IA</div><p>${c.aiSummary}</p></div>`:''}
      ${c.aiRedFlags&&c.aiRedFlags.length?`<div class="warn-block"><div class="warn-title">Points de vigilance</div>${c.aiRedFlags.map(r=>`<div class="warn-item">${r}</div>`).join('')}</div>`:''}
      ${c.cvText?`<div style="margin-bottom:18px;"><div class="section-title">CV</div><div style="background:var(--iv2);border:1px solid var(--iv3);padding:14px;font-size:12.5px;color:var(--ink3);line-height:1.65;white-space:pre-wrap;max-height:160px;overflow-y:auto;">${c.cvText}</div></div>`:''}
      <div style="border-top:1px solid var(--iv3);padding-top:18px;">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px;">
          <div class="section-title" style="margin:0;">Questions d'entretien IA</div>
          <button class="btn btn-ghost btn-sm" id="qbtn-${c.id}" onclick="generateQuestions('${c.id}')">✦ Generer</button>
        </div>
        <div id="questions-${c.id}"><div style="background:var(--iv2);border:1px dashed var(--iv3);padding:18px;text-align:center;font-size:13px;color:var(--mid);">Cliquez "Generer" pour des questions personnalisees pour ${c.name}</div></div>
      </div>
    </div>`;
}
function updateCandStatus(id,status){const c=STATE.candidates.find(x=>x.id===id);if(c){c.status=status;saveData();renderCandidates();showToast('Statut : '+status);}}
function deleteCandidate(id){if(!confirm('Supprimer ?'))return;STATE.candidates=STATE.candidates.filter(c=>c.id!==id);STATE.selectedCandidate=null;saveData();renderCandidates();showToast('Candidat supprime');}
function openAddCandidate(){
  const sel=document.getElementById('nc-job-id');
  sel.innerHTML='<option value="">-- Aucune offre --</option>'+STATE.jobs.map(j=>`<option value="${j.id}">${j.title}</option>`).join('');
  if(STATE.filterJob)sel.value=STATE.filterJob;
  openModal('modal-new-candidate');
}
async function createCandidate(){
  const name=document.getElementById('nc-name').value.trim();if(!name){showToast('Nom requis');return;}
  const c={id:'c'+Date.now(),name,email:document.getElementById('nc-email').value.trim(),location:document.getElementById('nc-location').value.trim(),exp:document.getElementById('nc-exp').value.trim(),jobId:document.getElementById('nc-job-id').value||null,cvText:document.getElementById('nc-cv').value.trim(),status:'nouveau',created:Date.now(),aiScore:null,aiSummary:null,aiRedFlags:[],aiTags:[]};
  STATE.candidates.push(c);saveData();closeModal('modal-new-candidate');
  ['nc-name','nc-email','nc-location','nc-exp','nc-cv'].forEach(id=>document.getElementById(id).value='');
  showToast('Candidat ajoute');renderCandidates();selectCandidate(c.id);
  if(c.cvText)setTimeout(()=>analyzeCandidateCV(c.id),400);
}
 
// ═══════════════════════════════════════
// PIPELINE
// ═══════════════════════════════════════
function renderPipeline(){
  const stages=[
    {key:'nouveau',label:'Nouveaux',color:'var(--el)',border:'rgba(0,56,255,0.3)',bg:'var(--el2)'},
    {key:'screening',label:'Screening',color:'var(--yw)',border:'rgba(138,101,0,0.3)',bg:'var(--yw2)'},
    {key:'entretien',label:'Entretien',color:'var(--am)',border:'rgba(200,75,26,0.3)',bg:'var(--am2)'},
    {key:'offre',label:'Offre envoyee',color:'var(--gn)',border:'rgba(26,122,74,0.3)',bg:'var(--gn2)'},
    {key:'refus',label:'Refus',color:'var(--mid)',border:'var(--iv3)',bg:'var(--iv2)'},
  ];
  let cands=STATE.candidates;if(STATE.filterJob)cands=cands.filter(c=>c.jobId===STATE.filterJob);
  document.getElementById('pipeline-grid').innerHTML=stages.map(s=>{
    const cols=cands.filter(c=>c.status===s.key);
    return`<div><div class="pipe-col-head" style="border-color:${s.border};background:${s.bg};"><span class="pipe-col-title" style="color:${s.color};">${s.label}</span><span class="pipe-col-count" style="color:${s.color};border-color:${s.border};">${cols.length}</span></div>
    ${cols.length?cols.map(c=>`<div class="pipe-card" onclick="gotoPage('candidates',document.querySelector('[onclick*=candidates]'));setTimeout(()=>selectCandidate('${c.id}'),50)">
      <div style="display:flex;align-items:center;gap:8px;margin-bottom:7px;">${avHtml(c,28)}<div><div style="font-weight:700;font-size:12px;">${c.name}</div><div style="font-size:10.5px;color:var(--mid);">${c.location||'—'}</div></div></div>
      <div style="display:flex;justify-content:space-between;align-items:center;"><span style="font-size:10.5px;color:var(--mid);">${c.exp||'—'}</span>${c.aiScore?`<span class="score-badge ${scCls(c.aiScore)}" style="font-size:10px;padding:2px 6px;">${c.aiScore}%</span>`:''}</div>
    </div>`).join(''):`<div class="pipe-empty">Aucun candidat</div>`}</div>`;
  }).join('');
}
 
// ═══════════════════════════════════════
// COMPARAISON
// ═══════════════════════════════════════
function renderCompare(){
  const sel=document.getElementById('compare-selectors');
  const scored=[...STATE.candidates].filter(c=>c.aiScore).sort((a,b)=>b.aiScore-a.aiScore);
  sel.innerHTML=`<div style="font-size:13px;color:var(--mid);display:flex;align-items:center;gap:10px;flex-wrap:wrap;">
    <span style="font-weight:600;color:var(--ink);">Comparer :</span>
    ${scored.slice(0,8).map(c=>`<label style="display:flex;align-items:center;gap:6px;cursor:pointer;font-size:13px;">
      <input type="checkbox" class="compare-cb" value="${c.id}" onchange="updateCompare()" style="cursor:pointer;"> ${c.name} <span class="score-badge ${scCls(c.aiScore)}" style="font-size:10px;padding:2px 6px;">${c.aiScore}%</span></label>`).join('')}
  </div>`;
  document.getElementById('compare-result').innerHTML='<div style="color:var(--mid);font-size:13px;padding:20px 0;">Selectionnez 2 a 4 candidats pour les comparer.</div>';
}
function updateCompare(){
  const checked=[...document.querySelectorAll('.compare-cb:checked')].map(cb=>cb.value);
  if(checked.length<2){document.getElementById('compare-result').innerHTML='<div style="color:var(--mid);font-size:13px;padding:16px 0;">Selectionnez au moins 2 candidats.</div>';return;}
  const cands=checked.slice(0,4).map(id=>STATE.candidates.find(c=>c.id===id)).filter(Boolean);
  const cols=cands.length;
  const rows=[
    {label:'Score IA',key:'score'},
    {label:'Experience',key:'exp'},
    {label:'Localisation',key:'location'},
    {label:'Competences',key:'tags'},
    {label:'Statut',key:'status'},
    {label:'Analyse IA',key:'summary'},
    {label:'Red flags',key:'flags'},
  ];
  const gridCols=`120px ${cands.map(()=>'1fr').join(' ')}`;
  document.getElementById('compare-result').innerHTML=`
    <div class="compare-grid" style="border:1px solid var(--iv3);">
      <div class="compare-header" style="display:grid;grid-template-columns:${gridCols};">
        <div style="font-family:'DM Mono',monospace;font-size:9.5px;text-transform:uppercase;letter-spacing:1.5px;color:var(--mid);">Critere</div>
        ${cands.map(c=>`<div style="display:flex;align-items:center;gap:10px;">${avHtml(c,32)}<div><div style="font-weight:700;font-size:13px;">${c.name}</div><div style="font-size:11px;color:var(--mid);">${c.exp||''}</div></div></div>`).join('')}
      </div>
      ${rows.map(row=>`
        <div class="compare-row" style="display:grid;grid-template-columns:${gridCols};border-bottom:1px solid var(--iv3);padding:12px 18px;">
          <div class="compare-row-label">${row.label}</div>
          ${cands.map(c=>{
            if(row.key==='score')return`<div><div style="font-family:'Fraunces',serif;font-size:28px;font-weight:900;letter-spacing:-1px;color:${c.aiScore>=80?'var(--gn)':c.aiScore>=60?'var(--yw)':'var(--mid)'};">${c.aiScore||'—'}</div><div class="score-bar"><div class="score-bar-fill" style="width:${c.aiScore||0}%;background:${c.aiScore>=80?'var(--gn)':c.aiScore>=60?'var(--yw)':'var(--muted)'};"></div></div></div>`;
            if(row.key==='exp')return`<div style="font-size:13px;font-weight:600;">${c.exp||'—'}</div>`;
            if(row.key==='location')return`<div style="font-size:13px;">${c.location||'—'}</div>`;
            if(row.key==='tags')return`<div style="display:flex;gap:4px;flex-wrap:wrap;">${(c.aiTags||[]).map(t=>`<span style="font-size:10.5px;background:var(--iv2);border:1px solid var(--iv3);padding:1px 6px;color:var(--mid);">${t}</span>`).join('')||'—'}</div>`;
            if(row.key==='status')return`<div>${statusPill(c.status)}</div>`;
            if(row.key==='summary')return`<div style="font-size:12px;color:var(--ink3);line-height:1.55;">${c.aiSummary?c.aiSummary.slice(0,120)+'...':'—'}</div>`;
            if(row.key==='flags')return`<div>${(c.aiRedFlags||[]).length?c.aiRedFlags.map(r=>`<div style="font-size:11.5px;color:var(--am);padding:2px 0;">• ${r}</div>`).join(''):'<span style="font-size:12px;color:var(--gn);">Aucun</span>'}</div>`;
            return'<div>—</div>';
          }).join('')}
        </div>`).join('')}
    </div>`;
}
 
// ═══════════════════════════════════════
// ANALYTICS
// ═══════════════════════════════════════
function renderAnalytics(){
  const C=STATE.candidates,J=STATE.jobs;
  const byStatus={nouveau:0,screening:0,entretien:0,offre:0,refus:0};
  C.forEach(c=>{if(byStatus[c.status]!==undefined)byStatus[c.status]++;});
  const scored=C.filter(c=>c.aiScore);
  const avgScore=scored.length?Math.round(scored.reduce((a,c)=>a+c.aiScore,0)/scored.length):0;
  const topJob=J.reduce((a,j)=>{const n=C.filter(c=>c.jobId===j.id).length;return n>a.n?{j,n}:{...a}},{j:null,n:0});
  document.getElementById('analytics-stats').innerHTML=[
    {l:'Taux de conversion',v:C.length?Math.round((byStatus.entretien+byStatus.offre)/C.length*100)+'%':'0%',d:'candidature → entretien'},
    {l:'Score IA moyen',v:avgScore+'%',d:'sur CVs analyses'},
    {l:'Taux de refus',v:C.length?Math.round(byStatus.refus/C.length*100)+'%':'0%',d:'des candidatures'},
    {l:'CVs analyses',v:scored.length,d:`sur ${C.length} total`},
  ].map(s=>`<div class="stat-card"><div class="stat-label">${s.l}</div><div class="stat-value">${s.v}</div><div class="stat-delta">${s.d}</div></div>`).join('');
 
  const colors={'nouveau':'var(--el)','screening':'var(--yw)','entretien':'var(--am)','offre':'var(--gn)','refus':'var(--muted)'};
  const total=C.length||1;
  // Score distribution
  const brackets=[{l:'90-100',min:90,max:101,c:'var(--gn)'},{l:'70-89',min:70,max:90,c:'var(--yw)'},{l:'50-69',min:50,max:70,c:'var(--am)'},{l:'<50',min:0,max:50,c:'var(--muted)'}];
  document.getElementById('analytics-charts').innerHTML=`
    <div class="chart-card">
      <div class="chart-title">Pipeline par statut</div>
      <div class="bar-chart">${Object.entries(byStatus).map(([s,n])=>`
        <div class="bar-row">
          <div class="bar-label">${s.charAt(0).toUpperCase()+s.slice(1)}</div>
          <div class="bar-wrap"><div class="bar-fill" style="width:${Math.round(n/total*100)}%;background:${colors[s]||'var(--mid)'}"><div class="bar-val">${n}</div></div></div>
        </div>`).join('')}
      </div>
    </div>
    <div class="chart-card">
      <div class="chart-title">Distribution des scores IA</div>
      <div class="bar-chart">${brackets.map(b=>{const n=scored.filter(c=>c.aiScore>=b.min&&c.aiScore<b.max).length;return`
        <div class="bar-row">
          <div class="bar-label">${b.l}</div>
          <div class="bar-wrap"><div class="bar-fill" style="width:${scored.length?Math.round(n/scored.length*100):0}%;background:${b.c}"><div class="bar-val">${n}</div></div></div>
        </div>`;}).join('')}
      </div>
    </div>
    <div class="chart-card">
      <div class="chart-title">Candidats par offre</div>
      <div class="bar-chart">${J.map(j=>{const n=C.filter(c=>c.jobId===j.id).length;return`
        <div class="bar-row">
          <div class="bar-label" style="width:90px;font-size:11px;">${j.title.slice(0,12)}${j.title.length>12?'..':''}</div>
          <div class="bar-wrap"><div class="bar-fill" style="width:${C.length?Math.round(n/C.length*100):0}%;background:var(--el)"><div class="bar-val">${n}</div></div></div>
        </div>`;}).join('')||'<div style="color:var(--mid);font-size:12px;">Aucune offre</div>'}
      </div>
    </div>`;
}
function exportAnalyticsPDF(){window.print();}
 
// ═══════════════════════════════════════
// EMAIL
// ═══════════════════════════════════════
const EMAIL_TEMPLATES=[
  {id:'convocation',title:'Convocation entretien',desc:'Inviter le candidat pour un entretien',
    subject:(n)=>`Invitation a un entretien — ${n}`,
    body:(c,comp)=>`Bonjour ${c.name.split(' ')[0]},\n\nNous avons examine votre candidature avec attention et nous serions ravis de vous rencontrer pour un entretien.\n\nMerci de nous faire part de vos disponibilites pour les prochains jours.\n\nCordialement,\nL'equipe Recrutement\n${comp||''}`},
  {id:'remerciement',title:'Remerciement apres entretien',desc:'Remercier un candidat apres entretien',
    subject:(n)=>`Merci pour votre entretien — ${n}`,
    body:(c,comp)=>`Bonjour ${c.name.split(' ')[0]},\n\nNous vous remercions d'avoir pris le temps de nous rencontrer. Votre profil est tres interessant et nous revenons vers vous rapidement.\n\nCordialement,\nL'equipe Recrutement\n${comp||''}`},
  {id:'offre',title:'Proposition d\'offre',desc:'Envoyer une offre d\'emploi au candidat',
    subject:(n)=>`Proposition d'emploi — ${n}`,
    body:(c,comp)=>`Bonjour ${c.name.split(' ')[0]},\n\nNous avons le plaisir de vous proposer de rejoindre notre equipe. Nous souhaiterions discuter des modalites de votre integration.\n\nMerci de nous confirmer votre interet.\n\nCordialement,\nL'equipe Recrutement\n${comp||''}`},
  {id:'refus',title:'Refus de candidature',desc:'Informer le candidat d\'un refus',
    subject:(n)=>`Suite a votre candidature — ${n}`,
    body:(c,comp)=>`Bonjour ${c.name.split(' ')[0]},\n\nNous vous remercions de l'interet que vous portez a notre entreprise. Apres examen attentif de votre candidature, nous n'avons pas pu y donner une suite favorable.\n\nNous vous souhaitons plein succes dans vos recherches.\n\nCordialement,\nL'equipe Recrutement\n${comp||''}`},
];
function openEmailModal(candId){
  const c=STATE.candidates.find(x=>x.id===candId);if(!c)return;
  STATE.emailCandidate=c;
  const comp=STATE.user?.company||'';
  document.getElementById('email-templates').innerHTML=EMAIL_TEMPLATES.map(t=>`
    <div class="email-template" id="etpl-${t.id}" onclick="selectEmailTemplate('${t.id}')">
      <div class="email-template-title">${t.title}</div>
      <div class="email-template-desc">${t.desc}</div>
    </div>`).join('');
  selectEmailTemplate('convocation');
  openModal('modal-email');
}
function selectEmailTemplate(id){
  document.querySelectorAll('.email-template').forEach(el=>el.classList.remove('selected'));
  document.getElementById('etpl-'+id)?.classList.add('selected');
  const t=EMAIL_TEMPLATES.find(x=>x.id===id);
  const c=STATE.emailCandidate;const comp=STATE.user?.company||'';
  if(t&&c){document.getElementById('email-subject').value=t.subject(c.name);document.getElementById('email-body').value=t.body(c,comp);}
}
function sendEmail(){
  const c=STATE.emailCandidate;if(!c||!c.email){showToast('Email candidat manquant');return;}
  const subject=encodeURIComponent(document.getElementById('email-subject').value);
  const body=encodeURIComponent(document.getElementById('email-body').value);
  window.open(`mailto:${c.email}?subject=${subject}&body=${body}`,'_blank');
  closeModal('modal-email');showToast('Messagerie ouverte');
}
 
// ═══════════════════════════════════════
// EXPORT PDF
// ═══════════════════════════════════════
function exportCandidatePDF(id){
  const c=STATE.candidates.find(x=>x.id===id);if(!c)return;
  const job=STATE.jobs.find(j=>j.id===c.jobId);
  const win=window.open('','_blank');
  win.document.write(`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>Rapport — ${c.name}</title>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@700;900&family=Instrument+Sans:wght@400;600;700&display=swap" rel="stylesheet">
  <style>body{font-family:'Instrument Sans',sans-serif;max-width:700px;margin:40px auto;color:#16120E;background:#fff;-webkit-print-color-adjust:exact;}
  h1{font-family:'Fraunces',serif;font-size:28px;font-weight:900;letter-spacing:-1px;margin-bottom:4px;}
  .sub{font-size:13px;color:#8A7D6E;margin-bottom:24px;}
  .score-big{font-family:'Fraunces',serif;font-size:56px;font-weight:900;letter-spacing:-2px;color:${c.aiScore>=80?'#1A7A4A':c.aiScore>=60?'#8A6500':'#8A7D6E'};}
  .section{margin-bottom:20px;padding:16px;background:#F4F0E8;border:1px solid #E0D8CC;}
  .section-title{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:2px;color:#8A7D6E;margin-bottom:8px;}
  .ai-block{background:#E8EDFF;border:1px solid rgba(0,56,255,0.2);padding:16px;margin-bottom:14px;}
  .warn-block{background:#FFF0EB;border:1px solid rgba(200,75,26,0.2);padding:14px;margin-bottom:14px;}
  .tag{background:#EDE8DE;border:1px solid #E0D8CC;padding:2px 8px;font-size:11px;color:#8A7D6E;margin-right:4px;display:inline-block;margin-bottom:4px;}
  @media print{body{margin:20px;}}
  </style></head><body>
  <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:24px;border-bottom:2px solid #16120E;padding-bottom:20px;">
    <div>
      <div style="font-family:'Fraunces',serif;font-size:12px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#8A7D6E;margin-bottom:6px;">RAPPORT CANDIDAT — RecrutAI</div>
      <h1>${c.name}</h1>
      <div class="sub">${c.exp||''}${c.exp&&c.location?' — ':''}${c.location||''}${job?' — '+job.title:''}</div>
      <div>${(c.aiTags||[]).map(t=>`<span class="tag">${t}</span>`).join('')}</div>
    </div>
    ${c.aiScore?`<div style="text-align:center;"><div class="score-big">${c.aiScore}</div><div style="font-size:10px;text-transform:uppercase;letter-spacing:2px;color:#8A7D6E;">Score IA</div></div>`:''}
  </div>
  ${c.aiSummary?`<div class="ai-block"><div class="section-title">Analyse IA</div><p style="font-size:13.5px;line-height:1.65;">${c.aiSummary}</p></div>`:''}
  ${c.aiRedFlags&&c.aiRedFlags.length?`<div class="warn-block"><div class="section-title" style="color:#C84B1A;">Points de vigilance</div>${c.aiRedFlags.map(r=>`<div style="font-size:13px;padding-left:12px;border-left:2px solid rgba(200,75,26,0.4);margin-bottom:5px;">${r}</div>`).join('')}</div>`:''}
  ${c.cvText?`<div class="section"><div class="section-title">CV</div><div style="font-size:12.5px;line-height:1.65;white-space:pre-wrap;">${c.cvText}</div></div>`:''}
  <div style="margin-top:32px;padding-top:14px;border-top:1px solid #E0D8CC;font-size:11px;color:#B8AC9E;display:flex;justify-content:space-between;">
    <span>RecrutAI — Rapport genere le ${new Date().toLocaleDateString('fr-FR')}</span>
    <span>${c.email||''}</span>
  </div>
  <script>window.onload=()=>{window.print();}<\/script>
  </body></html>`);win.document.close();
}
 
// ═══════════════════════════════════════
// MULTIDIFFUSION
// ═══════════════════════════════════════
const JOBBOARDS=[
  {name:'Indeed France',desc:'Leader mondial, 10M+ visiteurs/mois',url:'https://emplois.indeed.com/job/create',color:'#003A9B',logo:'IN'},
  {name:'LinkedIn',desc:'Reseau professionnel, ideal cadres',url:'https://www.linkedin.com/job-posting/new',color:'#0A66C2',logo:'LI'},
  {name:'Welcome to the Jungle',desc:'Premium, startup & scale-up',url:'https://solutions.welcometothejungle.com',color:'#1B1B1B',logo:'WJ'},
  {name:'APEC',desc:'Cadres et jeunes diplomes',url:'https://recruteurs.apec.fr',color:'#E2001A',logo:'AP'},
  {name:'HelloWork',desc:'PME et emploi regional',url:'https://recruteur.hellowork.com',color:'#FF6B35',logo:'HW'},
  {name:'France Travail',desc:'Gratuit, tous profils',url:'https://www.pole-emploi.fr/employeur',color:'#2B6CB0',logo:'PE'},
];
function openMultidiffusion(){openMultidiffusionWithText(STATE.genJobText||'',STATE.genJobTitle||'');}
function openMultidiffusionJob(jobId){
  const j=STATE.jobs.find(x=>x.id===jobId);if(!j)return;
  openMultidiffusionWithText(`${j.title}\n\n${j.description||''}\n\nCompetences : ${j.skills||''}\nLocalisation : ${j.location||''}\nSalaire : ${j.salary||''}`,j.title);
}
function openMultidiffusionWithText(text,title){
  document.getElementById('jb-offer-text').textContent=text||'Generez d\'abord une offre avec le generateur IA.';
  document.getElementById('jb-grid').innerHTML=JOBBOARDS.map(jb=>`
    <a class="jb-card" href="${jb.url}" target="_blank" rel="noopener">
      <div class="jb-logo" style="background:${jb.color}18;border:1px solid ${jb.color}30;color:${jb.color};">${jb.logo}</div>
      <div><div class="jb-name">${jb.name}</div><div class="jb-desc">${jb.desc}</div></div>
    </a>`).join('');
  openModal('modal-multidiff');
}
function copyJobText(){const t=document.getElementById('jb-offer-text').textContent;navigator.clipboard.writeText(t).then(()=>showToast('Texte copie !'));}
 
// ═══════════════════════════════════════
// AI CALLS
// ═══════════════════════════════════════
async function callAI(prompt,systemPrompt){
  const res=await fetch('/api/ai',{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({prompt,system:systemPrompt,max_tokens:1200})});
  if(!res.ok){const err=await res.json().catch(()=>({}));throw new Error(err.error||'Erreur serveur');}
  const data=await res.json();return data.text;
}
 
async function analyzeCandidateCV(id){
  const c=STATE.candidates.find(x=>x.id===id);if(!c||!c.cvText){showToast('Aucun CV a analyser');return;}
  const job=STATE.jobs.find(j=>j.id===c.jobId);
  const btn=document.querySelector(`[onclick="analyzeCandidateCV('${id}')"]`);
  if(btn){btn.disabled=true;btn.innerHTML='<span class="spinner spinner-dark"></span>';}
  try{
    const text=await callAI(`Candidat: ${c.name}\nPoste: ${job?.title||'Non precise'}\nCriteres: ${job?.skills||'Non precise'}\n\nCV:\n${c.cvText}`,
      `Tu es un expert RH senior francais. Analyse ce CV et reponds UNIQUEMENT en JSON: {"score":number,"summary":"string","redFlags":["string"],"tags":["string"]}. score=0-100. summary=2-3 phrases en francais. redFlags=points negatifs (vide si aucun). tags=4-6 competences cles.`);
    const result=JSON.parse(text.replace(/```json|```/g,'').trim());
    c.aiScore=result.score;c.aiSummary=result.summary;c.aiRedFlags=result.redFlags||[];c.aiTags=result.tags||[];
    saveData();renderCandidateDetail(c);renderCandidates();showToast(`Score IA : ${c.aiScore}%`);
  }catch(e){showToast('Erreur analyse : '+e.message);}
}
 
async function generateQuestions(candId){
  const c=STATE.candidates.find(x=>x.id===candId);if(!c)return;
  const btn=document.getElementById(`qbtn-${candId}`),area=document.getElementById(`questions-${candId}`);
  if(!btn||!area)return;
  btn.disabled=true;btn.innerHTML='<span class="spinner spinner-dark"></span>';
  area.innerHTML='<div style="padding:14px;color:var(--mid);font-size:13px;display:flex;align-items:center;gap:9px;"><span class="spinner spinner-dark"></span> Generation...</div>';
  try{
    const text=await callAI(`Candidat: ${c.name}, ${c.exp} d\'exp\nCompetences: ${(c.aiTags||[]).join(', ')}\nVigilance: ${(c.aiRedFlags||[]).join(', ')||'aucun'}\nAnalyse: ${c.aiSummary||'N/A'}`,
      `Tu es un expert RH senior francais. Genere 4 questions d\'entretien. JSON: {"questions":[{"category":"string","question":"string","why":"string"}]}`);
    const data=JSON.parse(text.replace(/```json|```/g,'').trim());
    area.innerHTML=data.questions.map(q=>`<div style="background:var(--iv2);border:1px solid var(--iv3);padding:12px 14px;margin-bottom:7px;">
      <div style="font-family:'DM Mono',monospace;font-size:9px;font-weight:500;letter-spacing:1.5px;text-transform:uppercase;color:var(--el);margin-bottom:5px;">${q.category}</div>
      <div style="font-size:13px;font-weight:600;margin-bottom:4px;line-height:1.45;">${q.question}</div>
      ${q.why?`<div style="font-size:11.5px;color:var(--mid);font-style:italic;">→ ${q.why}</div>`:''}</div>`).join('');
  }catch(e){area.innerHTML=`<div style="color:var(--rd);font-size:13px;padding:12px;">${e.message}</div>`;}
  btn.disabled=false;btn.innerHTML='↻ Regenerer';
}
 
async function generateJobOffer(){
  const title=document.getElementById('gen-title').value.trim(),brief=document.getElementById('gen-brief').value.trim();
  if(!title&&!brief){showToast('Remplissez au moins le titre et le brief');return;}
  const btn=document.getElementById('gen-btn');btn.disabled=true;btn.innerHTML='<span class="spinner"></span> Generation...';
  document.getElementById('gen-result').style.display='none';
  try{
    const text=await callAI(`Poste: ${title||'?'}\nDepartement: ${document.getElementById('gen-dept').value||'?'}\nNiveau: ${document.getElementById('gen-level').value||'?'}\nContrat: ${document.getElementById('gen-contract').value||'CDI'}\nBrief: ${brief||'?'}\nCompetences: ${document.getElementById('gen-skills').value||'?'}`,
      `Tu es un expert RH senior francais specialise en employer branding. Redige une offre d\'emploi complete, attractive et inclusive. Inclus : accroche, contexte entreprise, missions (5-7 bullets), profil recherche (5 criteres), avantages, processus de recrutement.`);
    document.getElementById('gen-result-text').textContent=text;
    document.getElementById('gen-result').style.display='block';
    STATE.genJobText=text;STATE.genJobTitle=title;STATE.genJobDept=document.getElementById('gen-dept').value;
  }catch(e){showToast('Erreur : '+e.message);}
  btn.disabled=false;btn.innerHTML='✦ Generer l\'offre avec l\'IA';
}
function saveGeneratedJob(){
  if(!STATE.genJobText)return;
  const job={id:'j'+Date.now(),title:STATE.genJobTitle||'Nouvelle offre',dept:STATE.genJobDept||'',description:STATE.genJobText.slice(0,300),skills:'',location:'',salary:'',status:'actif',created:Date.now()};
  STATE.jobs.push(job);saveData();showToast('Offre enregistree');gotoPage('jobs',document.querySelector('[onclick*=jobs]'));
}
function copyGenResult(){if(STATE.genJobText)navigator.clipboard.writeText(STATE.genJobText).then(()=>showToast('Copie !'));}
 
async function analyzeCV(){
  const cv=document.getElementById('an-cv').value.trim();if(!cv){showToast('Collez le contenu du CV');return;}
  const btn=document.getElementById('an-btn'),result=document.getElementById('an-result');
  btn.disabled=true;btn.innerHTML='<span class="spinner"></span> Analyse...';result.style.display='none';
  try{
    const text=await callAI(`Candidat: ${document.getElementById('an-name').value||'Anonyme'}\nPoste: ${document.getElementById('an-job').value||'?'}\nCriteres: ${document.getElementById('an-criteria').value||'?'}\n\nCV:\n${cv}`,
      `Tu es un expert RH senior francais. Analyse ce CV. JSON: {"score":number,"summary":"string","strengths":["string"],"redFlags":["string"],"tags":["string"],"recommendation":"string"}`);
    const data=JSON.parse(text.replace(/```json|```/g,'').trim());
    result.innerHTML=`<div class="ai-block"><div class="ai-block-title">Resultat</div>
      <div style="display:flex;align-items:center;gap:14px;margin-bottom:12px;">
        <div style="font-family:'Fraunces',serif;font-size:52px;font-weight:900;letter-spacing:-2px;color:${data.score>=80?'var(--gn)':data.score>=60?'var(--yw)':'var(--mid)'};">${data.score}</div>
        <div><div style="font-size:9px;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:1.5px;color:var(--mid);margin-bottom:4px;">Score IA</div>
        <div style="display:flex;gap:4px;flex-wrap:wrap;">${(data.tags||[]).map(t=>`<span style="font-size:11px;background:var(--iv2);border:1px solid var(--iv3);padding:2px 7px;color:var(--mid);">${t}</span>`).join('')}</div></div>
      </div>
      <p style="margin-bottom:8px;">${data.summary}</p>
      ${data.recommendation?`<p style="font-style:italic;font-weight:600;font-size:13px;">→ ${data.recommendation}</p>`:''}</div>
      ${data.strengths&&data.strengths.length?`<div style="background:var(--gn2);border:1px solid rgba(26,122,74,0.2);padding:12px 14px;margin-bottom:12px;"><div style="font-family:'DM Mono',monospace;font-size:9px;text-transform:uppercase;letter-spacing:1.5px;color:var(--gn);margin-bottom:7px;">Points forts</div>${data.strengths.map(s=>`<div style="font-size:13px;color:var(--ink3);padding-left:10px;border-left:2px solid rgba(26,122,74,0.3);margin-bottom:4px;">${s}</div>`).join('')}</div>`:''}
      ${data.redFlags&&data.redFlags.length?`<div class="warn-block"><div class="warn-title">Points de vigilance</div>${data.redFlags.map(r=>`<div class="warn-item">${r}</div>`).join('')}</div>`:''}`;
    result.style.display='block';
  }catch(e){showToast('Erreur : '+e.message);}
  btn.disabled=false;btn.innerHTML='✦ Analyser le CV avec l\'IA';
}
 
// ═══════════════════════════════════════
// HELPERS
// ═══════════════════════════════════════
const COLORS=['#2563EB','#16A34A','#D97706','#DC2626','#7C3AED','#0891B2','#BE185D','#B45309'];
function getColor(n){let h=0;for(let i=0;i<n.length;i++)h=n.charCodeAt(i)+h*31;return COLORS[Math.abs(h)%COLORS.length];}
function getIni(n){const p=n.trim().split(' ');return(p[0]?.[0]+(p[1]?.[0]||'')).toUpperCase();}
function avHtml(c,size=34){const col=getColor(c.name);return`<div style="width:${size}px;height:${size}px;font-size:${Math.round(size*0.33)}px;background:${col}18;border:1.5px solid ${col}44;color:${col};display:inline-flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-weight:700;flex-shrink:0;">${getIni(c.name)}</div>`;}
function scCls(s){return s>=80?'score-high':s>=60?'score-mid':'score-low';}
function statusPill(s){const m={nouveau:'pill-blue Nouveau',screening:'pill-yellow Screening',entretien:'pill-amber Entretien',offre:'pill-green Offre',refus:'pill-muted Refuse'};const[cls,l]=(m[s]||'pill-muted Inconnu').split(' ');return`<span class="pill ${cls}" style="font-size:10px;padding:2px 7px;">${l}</span>`;}
function openModal(id){document.getElementById(id).classList.add('open');}
function closeModal(id){document.getElementById(id).classList.remove('open');}
document.querySelectorAll('.modal-overlay').forEach(o=>o.addEventListener('click',e=>{if(e.target===o)o.classList.remove('open');}));
function showToast(msg){const t=document.getElementById('toast');t.textContent=msg;t.style.display='block';clearTimeout(t._t);t._t=setTimeout(()=>t.style.display='none',2800);}
document.addEventListener('keydown',e=>{if(e.key==='Escape')document.querySelectorAll('.modal-overlay.open').forEach(m=>m.classList.remove('open'));});
</script>
</body>
</html>
 
