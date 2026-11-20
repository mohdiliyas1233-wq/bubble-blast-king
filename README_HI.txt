BUBBLE BLAST PRO - ANDROID PROJECT

इस ZIP में पूरा Android प्रोजेक्ट और GitHub Actions build workflow है।

महत्वपूर्ण:
1. ZIP को Extract करें।
2. GitHub Repository में पहले से मौजूद गलत/अधूरे Android.yml workflow को हटाएँ या disable करें।
3. इस प्रोजेक्ट के अंदर की सभी फाइलें और फोल्डर Repository की root में उसी structure के साथ upload करें।
4. खास तौर पर .github/workflows/android.yml, app/build.gradle, app/src/main/AndroidManifest.xml,
   app/src/main/java/.../MainActivity.java और app/src/main/assets/index.html मौजूद होने चाहिए।
5. GitHub Actions में “Build Bubble Blast Pro Android” workflow Run करें।
6. सफल होने पर Artifacts में APK और AAB ZIP के रूप में मिलेंगे।

यह debug APK परीक्षण के लिए है। Play Store पर प्रकाशित करने से पहले AAB को release signing, store listing,
privacy policy, testing और Play Console की आवश्यकताओं के अनुसार तैयार करना होगा।

Package: com.bubbleblastpro.game
Target SDK: 36
Minimum SDK: 23
