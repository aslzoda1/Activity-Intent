<p align="center"> 🧬 𝑨𝑪𝑻𝑰𝑽𝑰𝑻𝒀 𝑳𝑰𝑭𝑬𝑪𝒀𝑪𝑳𝑬 & 𝑰𝑵𝑻𝑬𝑵𝑻: 𝑼𝑳𝑻𝑰𝑴𝑨𝑻𝑬 𝑮𝑼𝑰𝑫𝑬 📱 </p><p align="center"><img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"></p><p align="center"><img src="https://img.shields.io/badge/LANGUAGE-KOTLIN-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/PLATFORM-ANDROID_SDK-3DDC84?style=for-the-badge&logo=android&logoColor=white" />&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/DESIGN-MODERN_QUIZ-gold?style=for-the-badge" /></p>🌌 𝑶𝒗𝒆𝒓𝒗𝒊𝒆𝒘: 𝑻𝒉𝒆 𝑬𝒅𝒖𝒄𝒂𝒕𝒊𝒐𝒏𝒂𝒍 𝑷𝒐𝒓𝒕𝒂𝒍[ 𝑳𝒊𝒇𝒆𝒄𝒚𝒄𝒍𝒆 & 𝑰𝒏𝒕𝒆𝒏𝒕 ] — bu Android dasturlashning "yuragi" hisoblangan tushunchalarni amaliyotda ko'rsatib beruvchi interaktiv qo'llanma. Loyiha Quiz formatida qurilgan bo'lib, har bir qadamda Activity'larning holati va ma'lumotlar oqimi vizual tarzda tushuntiriladi. 🚀[!IMPORTANT]🚀 𝑾𝒉𝒚 𝒕𝒉𝒊𝒔 𝒑𝒓𝒐𝒋𝒆𝒄𝒕?Bu shunchaki ilova emas, balki Activity Lifecycle va Intent ni tushunish uchun eng IDEAL AMALIY NAMUNA. Kodlar toza, tushunarli va professional darajada izohlangan. 📘🚀 𝑲𝒆𝒚 𝑰𝒏𝒕𝒆𝒍 (𝑭𝒆𝒂𝒕𝒖𝒓𝒆𝒔)𝑴𝒐𝒅𝒖𝒍𝑭𝒖𝒏𝒌𝒔𝒊𝒐𝒏𝒂𝒍𝒍𝒊𝒌𝑻𝒆𝒙𝒏𝒊𝒌 𝑰𝒛𝒐𝒉  🔄 Lifecycle  6 ta asosiy holatni to'liq qamrab olish..onCreate() dan .onDestroy() gacha.  📤 Intent  Activity'lar orasida ma'lumot uzatish.putExtra() orqali ma'lumot yuborish.  📥 Data Core  Ma'lumotni qabul qilish va tahlil qilish.getIntent() funksiyalari orqali.  📊 Result  To'g'ri/xato javoblar statistikasi.Vizual natijalar tahlili.🏗️ [ 𝑻𝑯𝑬𝑶𝑹𝑬𝑻𝑰𝑪𝑨𝑳 𝑭𝑶𝑼𝑵𝑫𝑨𝑻𝑰𝑶𝑵 ]Kotlin/**
 * 🔄 ACTIVITY LIFECYCLE TRACKING
 * Monitor real-time state changes in Logcat.
 */

override fun onResume() {
    super.onResume()
    Log.d("Lifecycle", "Activity is now Interactive ⚡")
}
Kotlin/**
 * 📤 SMART INTENT DATA TRANSFER
 * Passing the quiz score to the next activity.
 */

val intent = Intent(this, ResultActivity::class.java).apply {
    putExtra("SCORE", finalResult)
}
startActivity(intent)
📸 𝑷𝒓𝒆𝒎𝒊𝒖𝒎 𝑬𝒙𝒉𝒊𝒃𝒊𝒕𝒊𝒐𝒏 (7 𝑲𝒆𝒚 𝑺𝒄𝒓𝒆𝒆𝒏𝒔)<div align="center"><table border="0" cellspacing="25" cellpadding="10"><tr><td align="center"><img src="https://github.com/user-attachments/assets/2349f0d9-de06-4b70-b404-d21ba584534d" width="220" style="border-radius: 25px; border: 3px solid #00E5FF; box-shadow: 0 10px 20px rgba(0,229,255,0.3);" /><b>💠 𝑰𝒏𝒊𝒕 (𝑺𝒑𝒍𝒂𝒔𝒉)</b></td><td align="center"><img src="https://github.com/user-attachments/assets/cdb2ecbe-954a-4f9a-8b37-1bd4d1987171" width="220" style="border-radius: 25px; border: 3px solid #7F52FF; box-shadow: 0 10px 20px rgba(127,82,255,0.3);" /><b>🚀 𝑴𝒂𝒊𝒏 (𝑯𝒖𝒃)</b></td><td align="center"><img src="https://github.com/user-attachments/assets/e3f7aef2-53c3-4f18-a84a-e9fc8bc5246c" width="220" style="border-radius: 25px; border: 3px solid #00E5FF; box-shadow: 0 10px 20px rgba(0,229,255,0.3);" /><b>📘 𝑻𝒉𝒆𝒐𝒓𝒚 (𝑳𝒆𝒂𝒓𝒏)</b></td></tr><tr><td align="center"><img src="https://github.com/user-attachments/assets/61fc242a-d717-4929-97db-d134fdbd87c3" width="220" style="border-radius: 25px; border: 3px solid #7F52FF; box-shadow: 0 10px 20px rgba(127,82,255,0.3);" /><b>🧠 𝑸𝒖𝒊𝒛 (𝑺𝒕𝒂𝒓𝒕)</b></td><td align="center"><img src="https://github.com/user-attachments/assets/2dea1a75-8b10-4921-9610-dba17eaa7610" width="220" style="border-radius: 25px; border: 3px solid #00E5FF; box-shadow: 0 10px 20px rgba(0,229,255,0.3);" /><b>🧪 𝑸𝒖𝒆𝒔𝒕𝒊𝒐𝒏 𝑼𝑰</b></td><td align="center"><img src="https://github.com/user-attachments/assets/09ac2cb3-dc09-4192-a09f-ebe8c680eb8a" width="220" style="border-radius: 25px; border: 3px solid #7F52FF; box-shadow: 0 10px 20px rgba(127,82,255,0.3);" /><b>📊 𝑹𝒆𝒔𝒖𝒍𝒕 (𝑺𝒕𝒂𝒕𝒔)</b></td></tr><tr><td align="center" colspan="3" style="padding-top: 40px;"><img src="https://github.com/user-attachments/assets/5dc39522-a2a2-4081-9282-90f5cf177c9e" width="760" style="border-radius: 25px; border: 2px dashed #00E5FF; box-shadow: 0 10px 30px rgba(0,229,255,0.2);" />


<b>📡 𝑨𝒄𝒕𝒊𝒗𝒊𝒕𝒚 𝑳𝒊𝒇𝒆𝒄𝒚𝒄𝒍𝒆 𝑳𝒐𝒈𝒔 𝑽𝒊𝒔𝒖𝒂𝒍𝒊𝒛𝒆𝒅</b></td></tr></table></div>
👩‍💻 𝑨𝒃𝒐𝒖𝒕 𝒕𝒉𝒆 𝑨𝒓𝒄𝒉𝒊𝒕𝒆𝒄𝒕Aslzoda Bozorboyeva — Android Developer."Code is not just logic, it's an educational story." ✨

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"></p>
  <p align="center">
    📡 <b>Connect with the Future:</b>
    <a href="https://linkedin.com/in/aslzoda-bozorboyeva-593abb3b5/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://github.com/aslzoda1"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a></p><p align="center"><b>Designed with ❤️ by Aslzoda</b><i>Powered by Kotlin & Educational Passion</i></p>
