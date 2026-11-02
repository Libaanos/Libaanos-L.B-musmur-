LIBAANOS (L.B) MUSMUR — Android starter project

Maal qaba:
- Bifa gurraacha fi warqee
- Waraabuu fi dhaabuu (microphone)
- Sagalee m4a app keessatti olkaa'uu
- Tarree sagalee waraabame dhaggeeffachuu
- Dirree maqaa fi jechoota faarfannaa barreessuu

Akka itti banu:
1. Android Studio install godhi.
2. ZIP kana extract godhi.
3. Android Studio keessatti Open filadhu; folder Libaanos_LB_Musmur filadhu.
4. Gradle sync xumuri.
5. Bilbila Android USB debugging dandeessiftee walqabsiisi, yookaan emulator fayyadami.
6. Run (triangle magariisa) cuqaasi.
7. Yeroo appiin microphone gaafatu, eeyyami.

Hubachiisa:
- Kun project jalqabaa/source code dha; APK qophaa'e miti.
- Android Studio fi SDK barbaachisuun build godhamuu qaba.
- Waraabbiin app kana keessatti kuufamu; uninstall yoo goote ni haqama.
- Barreeffamni faarfannaa amma yeroo appii banaa jiru qofaaf jira; database/persistence itti dabaluun ni danda'ama.

Suuraa abbaa appii:
- Suuraan ati erge fuula jalqabaa appii irratti dabalameera.
- Faarfannaa fi sagaleen amma bilbila kee keessatti qofa kuufamu; appiin kun server irratti hin maxxansu.
- Namoonni biroon appii kana keessatti faayila olkaa'uu hin danda'an; hojii olkaa'uu kan qabdu ati bilbila kee irratti qofa.

APK ijaaruu GitHub Actions:
1. Project kana GitHub repository haaraa keessatti upload godhi.
2. Tab Actions bani; workflow "Build Android APK" filadhu.
3. "Run workflow" cuqaasi (yookaan push booda ofumaan ni jalqaba).
4. Build milkaa'e booda workflow run keessaa Artifacts jalatti
   "Libaanos-LB-Musmur-debug-apk" buufadhu.
5. ZIP artifact sana keessaa app-debug.apk bilbila Android irratti baniitii install godhi.
