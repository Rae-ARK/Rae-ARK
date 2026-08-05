diff --git a/README.md b/README.md
index 2bd90a3a98d3fce0db13172f4c093be992a85085..f596f91431bf982690c5cc5101b7addf789dcf29 100644
--- a/README.md
+++ b/README.md
@@ -55,10 +55,14 @@ Written short and focused, on purpose — one volume, four acts, meant to prove
 
 ## 🛠️ Vibe-Coded Projects
 
-### 🌐 Author Site
-A static 4-page site (Home / Works / Store / Journal / About + a Feedback page) built to host all three works, the paperback links, and a running journal of the writing process — no backend, no build step, just plain HTML/CSS/JS.
+### 🌐 Author Site + Android App
+A Vue 3 + TypeScript site (Home / Works / Store / Journal / About / Feedback / Privacy / Terms) with light/dark theming that follows your system, offline support, and a native Android app wrapped via Capacitor — hardware back button, native status bar, safe-area-aware layout for edge-to-edge screens. Debug APK builds automatically via CI on every push.
 
-`HTML` `CSS` `JavaScript` `Cloudflare Pages` `Claude`
+`Vue 3` `TypeScript` `Vite` `Capacitor` `Android` `Cloudflare Workers`
+
+[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Rae-ARK/My-Portfolio)
+
+> 🔄 **Next up:** migrating this site off Vue 3 and onto **[ARKlight](https://github.com/Rae-ARK/ARKlight)** — a Python-first static site compiler I'm building in parallel, write pages as Python functions and it compiles to plain HTML/CSS/JS.
 
 ---
