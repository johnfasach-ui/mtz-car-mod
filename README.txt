Stage Zero Configurator
=======================
Serve this folder from any web server (double-clicking index.html will not work: browsers block fetch and modules on file://).
Quick local start, inside this folder:
  python3 -m http.server 8000
then open http://localhost:8000

Files
  index.html                 the whole site
  data/golf7-gti.glb         Golf 7 GTI model (original binary GLB)
  data/golf5-gti.glb         Golf 5 GTI model (original binary GLB)

Three.js 0.160.0 loads from cdn.jsdelivr.net and fonts from Google Fonts, so internet access is needed.

Credits
  Golf 7 GTI: "Volkswagen Golf GTI MK7" by RPMRender (Sketchfab Standard license, check redistribution terms)
  Golf 5 GTI: "vw golf 5 gti" by giuffridanicolo54 (Sketchfab, CC BY 4.0, attribution required)
