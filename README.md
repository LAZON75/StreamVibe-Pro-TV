# StreamVibe Pro — Android / Android TV

This repository wraps the web app in a Capacitor Android app and builds a **debug APK** with GitHub Actions.

## Build APK with GitHub

1. Create a new GitHub repository and upload all files in this folder.
2. Open **Actions** and enable workflows if GitHub asks.
3. Run **Build StreamVibe Pro APK** using **Run workflow**, or push to `main`.
4. Open the completed workflow run and download the `StreamVibe-Pro-debug-apk` artifact.
5. Install the APK on your Android TV / Google TV or Android phone.

## Important notes

- This workflow creates a debug APK for testing; it is not a signed Play Store release.
- Live channel availability depends on each playlist/provider, region, network, and stream format.
- The app uses public IPTV-org playlist indexes as in the original file. Only add playlists and streams you are authorized to access.
- The web app uses HLS.js from a CDN, so the first launch requires internet access.
- The single HTML file is the source supplied in this conversation. If your previous project had separate files or a second HTML page, those files have not been included here.


## فصل الأقسام والمحتوى
- البث المباشر يعرض قنوات البث المباشر فقط، مع التصفح حسب الدولة واللغة.
- الرياضة والأخبار والأطفال والوثائقيات تفتح قوائم القنوات المباشرة المصنفة حسب الفئة.
- قسما الأفلام والمسلسلات منفصلان عن البث المباشر ويحمّلان قوائم التصنيف الخاصة بهما.
- ملاحظة: قوائم IPTV العامة قد تحتوي قنوات أفلام/مسلسلات تبث على الهواء، وليست مكتبة أفلام عند الطلب (VOD). للحصول على أفلام كاملة ومسلسلات عند الطلب، يلزم مصدر قانوني مرخّص يدعم VOD.
