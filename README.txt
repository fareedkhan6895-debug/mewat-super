MEWAT SUPER — विस्तारित शुरुआती प्रोजेक्ट

इस पैकेज में:
- index.html: मोबाइल/डेस्कटॉप UI, YouTube search, embedded player
- पसंदीदा गाने (इस डिवाइस पर सेव)
- हाल में सुने गए गानों का इतिहास
- मेवाती/हरियाणवी/सैड/रीमिक्स क्विक सर्च
- PWA manifest और service worker
- मोबाइल होम स्क्रीन पर इंस्टॉल के लिए आधार

सेटअप:
1) ZIP को फोन/कंप्यूटर पर Extract करें.
2) GitHub repository mewat-super के मुख्य (root) पेज पर index.html, manifest.json और sw.js अपलोड करें.
3) README.txt वैकल्पिक है.
4) Settings > Pages > Deploy from a branch > main > /(root) > Save.
5) YouTube Data API v3 चालू करके API key बनाएँ; वेबसाइट खोलकर Settings में key डालें.
6) HTTPS लिंक खोलकर Android Chrome menu से Add to Home screen / Install app करें.

सीमाएँ:
- यह अभी production-level पूर्ण सेवा नहीं है; इसमें user accounts, server/backend, admin dashboard, user song uploads, moderation, subscriptions/payments, recommendations, analytics, native APK या rights management शामिल नहीं हैं.
- YouTube search के लिए API key/Google Cloud project और quota आवश्यक है.
- सार्वजनिक साइट पर API key उजागर हो सकती है. Google Cloud में HTTP referrer और API restrictions लगाएँ; बड़े सार्वजनिक लॉन्च के लिए सुरक्षित backend रखें.
- YouTube वीडियो YouTube के official embed player से चलते हैं; कुछ वीडियो embed/playback को रोक सकते हैं.
- केवल ऐसे गाने/वीडियो का उपयोग करें जिन्हें दिखाने/चलाने की अनुमति है और YouTube/API terms का पालन करें.
