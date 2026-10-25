# NODEZERO

A second-monitor coach for **Counter-Strike 2** and **Dota 2** on Windows. It shows your live match, your hardware, and your history, using only the data your game and your own accounts already send you.

**[Download the latest version](https://github.com/murathudavendigar/nodezero-releases/releases/latest)**: pick `NODEZERO_x.y.z_x64-setup.exe`.

## Kurulum (Türkçe)

1. Yukarıdaki bağlantıdan `NODEZERO_..._x64-setup.exe` dosyasını indir ve çalıştır.
2. Windows **"Bilgisayarınız Windows tarafından korundu"** derse **Ek bilgi → Yine de çalıştır**'a bas. Kurulum dosyası imzalı değil, uyarı bu yüzden çıkıyor.
3. NODEZERO açılınca Overview'daki **Get started** adımlarını izle:
   - **Install** tuşu CS2 ve Dota 2 klasörüne küçük bir config dosyası ekler. Bu Valve'ın resmî Game State Integration özelliğidir ve VAC açısından güvenlidir.
   - Dota 2 için Steam'de başlatma seçeneğine `-gamestateintegration` ekle.
   - Oyunu yeniden başlat. Canlı ekran kendiliğinden açılır.
4. İstersen Setup'tan kendi Steam, Leetify, FACEIT ve Gemini anahtarlarını ekle. Hepsi ücretsiz ve isteğe bağlı. Anahtar yoksa o bölüm `N/A` gösterir.

**Güncellemeler:** NODEZERO yeni sürüm çıkınca sol menüde bir ok simgesi gösterir. **About → Install** ile kurarsın. Oyun açıkken kurulum yapmaz.

## Install (English)

1. Download `NODEZERO_..._x64-setup.exe` from the link above and run it.
2. If Windows shows **"Windows protected your PC"**, press **More info → Run anyway**. The installer is not code-signed.
3. Follow **Get started** on the Overview: install the game configs, add `-gamestateintegration` to Dota 2's launch options, and restart the game.
4. Optional: add your own Steam, Leetify, FACEIT, and Gemini keys in Setup.

NODEZERO checks for updates and shows an arrow in the left rail when one is ready. Install it from **About**. It never installs while a game is running.

## What it does not do

- No cheats: it never reads game memory, injects anything, or shows information about the other team.
- Your data stays on your PC (`%APPDATA%\com.murat.second-monitor-app`). Lookups go only to the services you turn on, for your own account.

Requires Windows 10 or 11 (64-bit). FPS readings need Intel PresentMon; see Setup → FPS.
