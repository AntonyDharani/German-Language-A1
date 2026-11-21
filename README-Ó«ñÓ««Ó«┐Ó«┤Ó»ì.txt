Deutsch A1 – Study Path : APK செய்வது எப்படி (இலவசம்)
=====================================================

இந்த folder-ல் உள்ளவை:
  index.html, manifest.json, sw.js, icon-192.png, icon-512.png
  (இவை இணைந்து, போனில் install செய்யக்கூடிய ஒரு app ஆக வேலை செய்யும். Internet இல்லாமலும் இயங்கும்.)

படி 1 – இலவச website-ல் போடுங்கள் (GitHub Pages)
  1. github.com-ல் இலவச account உருவாக்குங்கள்.
  2. "New repository" → பெயர்: deutsch-a1 → Public → Create.
  3. "uploading an existing file" → இந்த 5 files-ஐயும் upload செய்து → Commit.
  4. Settings → Pages → Branch: main → Save.
  5. 1-2 நிமிடம் கழித்து உங்கள் link கிடைக்கும்:
     https://<உங்கள்-username>.github.io/deutsch-a1/

  ⭐ இப்போதே எல்லோரும் அந்த link-ஐ Chrome-ல் திறந்து
     ⋮ menu → "Add to Home screen / Install app" அழுத்தினால் app ஆக install ஆகிவிடும்.

படி 2 – APK file உருவாக்குங்கள் (PWABuilder, இலவசம்)
  1. pwabuilder.com திறங்கள் → உங்கள் GitHub Pages link-ஐ ஒட்டுங்கள் → Start.
  2. "Package for stores" → Android → Generate Package.
  3. ஒரு .zip download ஆகும். அதில் .apk file இருக்கும்
     (கூட signing key file-ம் இருக்கும் — அதை பத்திரமாக வைத்துக்கொள்ளுங்கள், பின்னால் update செய்ய அது தேவை).

படி 3 – எல்லோருக்கும் பகிருங்கள்
  • இலவசமாக: .apk-ஐ Google Drive / GitHub Releases / Telegram-ல் போட்டு link பகிருங்கள்.
    Install செய்பவர்கள் "Install unknown apps" அனுமதி கொடுக்க வேண்டும்.
  • Play Store-ல் போட வேண்டுமென்றால்: Google Play Developer account (ஒரு முறை USD 25) தேவை.
    PWABuilder கொடுக்கும் .aab file-ஐ அங்கே upload செய்யுங்கள்.

Update செய்ய: GitHub-ல் index.html-ஐ மாற்றினால் போதும். App தானாகவே புதிய version-ஐ எடுத்துக்கொள்ளும்
(மாற்றம் தெரியவில்லை என்றால், sw.js-ல் உள்ள 'deutsch-a1-v2' என்பதை v3 என்று மாற்றுங்கள்).

குறிப்பு: கேள்விகள் எல்லாம் புதிதாக எழுதப்பட்டவை. புத்தகத்தின் பக்கங்களோ படங்களோ இதில் இல்லை.
பொதுவில் பகிரும்போது, புத்தகத்தின் scan-களையோ audio-வையோ சேர்க்காதீர்கள்.
