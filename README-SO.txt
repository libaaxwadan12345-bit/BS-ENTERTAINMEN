BS ENTERTAINMENT — FULL WEBSITE VERSION
========================================

FILES
- index.html — dhammaan bogagga iyo foomamka
- style.css — naqshadda mobile/desktop
- app.js — shaqada website-ka iyo demo admin dashboard

SIDA LOO GELIYO GITHUB
1. Soo dejiso ZIP-kan oo Extract ku samee.
2. Fur folder-ka BS_Entertainment_Full_Website.
3. Gal GitHub repository-gaaga BS-Entertainment-.
4. Ka saar/ku beddel files-kii hore adigoo Uploading existing files isticmaalaya.
5. Geli index.html, style.css, app.js iyo README-SO.txt.
6. Commit changes samee. GitHub Pages badanaa dhowr daqiiqo gudahood ayuu cusbooneysiiyaa.
7. Fur URL-kii hore ee GitHub Pages; haddii uusan cusboonaan, refresh samee.

ADMIN
- Taabo Admin ee geeska hoose.
- Password bilow ah: BSstudio2026!
- Settings ka beddel password-ka.
- Tabs: Anime, Episodes, Team, Gallery, Auditions, Settings.
- Ku dar ama tirtir xogta qayb kasta.
- Sawirrada waxaa lagu daraa image URL, videos-na video URL.

MUHIIM — XADIDAADDA NOOCAN
Tani waa static website/demo. Xogta waxaa lagu kaydiyaa localStorage ee browser-ka qofka furay.
Taasi waxay ka dhigan tahay:
- Waxyaabaha admin-ku ku daro browser-kiisa keliya ayay ka muuqanayaan, mana wadaagaan dhammaan booqdayaasha.
- Codsiyada audition-ka laguma diro server; waxay ku kaydsan yihiin browser-ka soo gudbiyey oo keliya.
- Password-ka frontend-ka ma aha amni dhab ah; qof aqoon u leh browser-ka wuu dhaafi karaa.
- Upload-ku hadda wuxuu qaataa URL sawir/video, ma aha file upload server ah.

SI LOO HELO NIDAAM DHAB AH OO ONLINE AH
Waxaa loo baahan yahay backend/database iyo storage (tusaale Supabase):
- Admin authentication dhab ah
- Database wadaag ah oo projects, episodes, team, gallery kaydiya
- Storage sawirro iyo video
- Audition/contact submissions server ku dhacaya
- Row Level Security iyo xeerar amni
Supabase project waa in la abuuraa, kadib URL iyo anon key ayaa lagu xiraa. Waligaa ha gelin service_role key website-ka ama ha soo bandhigin password sir ah.

XUQUUQDA
Soo geli oo keliya anime, sawirro, muusig iyo muuqaallo aad fasax u haysato inaad isticmaasho. Hubi oggolaanshaha xubnaha ka hor intaadan daabicin xogtooda.


UPLOAD (NOOCAAN DEMO)
- Admin > Anime: dooro poster-ka telefoonkaaga; URL weli waa ikhtiyaari.
- Admin > Episodes: dooro video-ga telefoonkaaga (ugu badnaan 100 MB) ama geli URL.
- Admin > Team: dooro sawirka xubinta.
- Admin > Gallery: dooro sawirka gallery-ga.
- Faylashu waxay ku kaydsan yihiin IndexedDB-ga browser-ka aad ku upload-gareysay. Qalab kale ama booqdayaal kale ma arki doonaan.
- Si upload-ku ugu muuqdo qof kasta oo website-ka booqda, waa in lagu xiraa cloud storage sida Supabase Storage; GitHub Pages kaligiis ma kaydiyo uploads-ka booqdayaasha.
