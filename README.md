# cg_web
Fixes:
index.html: <base href="/"> 
  -> <base href="/cg_web/web/">
flutter_service_worker.js: const CORE = ["main.dart.js", "index.html", "assets/AssetManifest.json", "assets/FontManifest.json"];
  -> ["/", "main.dart.js", "index.html", "assets/AssetManifest.json", "assets/FontManifest.json"];
