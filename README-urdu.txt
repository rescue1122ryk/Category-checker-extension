GITHUB PAR KYA UPLOAD KARNA HY
==============================
Repo: rescue1122ryk/Category-checker-extension  (Settings > Pages ON hona chahiye, branch main, folder / (root))

Repo ke root mein yeh files rakhein:
  1) categories-remote.json   <- categories badalni hon to sirf isay edit karein (auto update)
  2) updates.json             <- Firefox ke liye (sirf naya version sign karne par badalta hy)
  3) emergency-category-checker-2.7.xpi  <- signed xpi (sign-firefox.bat se bani)

CATEGORIES BADALNA (signing ki zaroorat nahi)
  - GitHub par categories-remote.json kholein > pencil (Edit) > badlav karein > Commit changes.
  - 1-10 minute baad har PC (Firefox + Chrome + Edge) par agle page load (F5) par naya data use hoga.
  - Yeh JSON hy: har naam "double quotes" mein ho, har line ke aakhir mein comma (aakhri item ke baad nahi).
  - Comments (// ya /* */) JSON mein NAHI chalte.
  - Agar file mein ghalti ho gayi to extension purani sahi copy chalata rahe ga (kuch toot'ta nahi).

CODE BADALNA (content.js / background.js / manifest.json)
  - Version badhayein (2.7 -> 2.7), Firefox ke liye sign-firefox.bat chalayein, naya xpi + updates.json upload karein.
  - Chrome/Edge: files badal kar update.bat ya reload.
