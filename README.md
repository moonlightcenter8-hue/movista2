Movista - منصة تواصل اجتماعي متقدمة مع الذكاء الاصطناعي
 
الوصف (Description)
Movista هي super-app تواصل اجتماعي شاملة ومتطورة، تجمع بين الشبكات الاجتماعية، الدردشة (نص، صوت، فيديو)، البث المباشر، والخدمات المدفوعة بمساعدة الذكاء الاصطناعي (AI). مصممة للمستخدمين العاديين، التجار، والمبدعين، تتيح بناء بروفايلات احترافية، إنشاء مواقع وفيديوهات AI، متاجر إلكترونية، ألعاب، مسابقات، وبث ثقافي/علمي. الموقع قابل للتوسع الدائم، مع لوحة تحكم إدارية لإدارة المحتوى والإعلانات.
بنيت باستخدام Next.js 14 للأداء العالي، مع دعم RTL للعربية، وتكاملات مثل Supabase للبيانات، Stripe للدفعات، وOpenAI للـ AI. MVP جاهز للإطلاق، ويمكن نشره على Vercel أو Hetzner.
Movista is an advanced social networking super-app that integrates social feeds, chat (text, voice, video), live streaming, and AI-powered paid services. Designed for everyday users, merchants, and creators, it enables professional profile building, AI-generated websites and videos, e-commerce stores, games, contests, and cultural/scientific live streams. The platform is infinitely expandable, with an admin dashboard for content and ad management.
Built with Next.js 14 for high performance, RTL support for Arabic, and integrations like Supabase for data, Stripe for payments, and OpenAI for AI. Ready-to-deploy MVP.
الميزات الرئيسية (Key Features)

* التسجيل السهل: باستخدام Google OAuth (Supabase Auth) – آمن وسريع.
* الصفحة الرئيسية (Home): عرض منشورات المستخدمين، إعلانات عشوائية، وأزرار الخدمات الإضافية (بروفايل، دردشة، متجر، ألعاب، بث مباشر، مسابقات).
* بروفايل متقدم (Advanced Profile):

للمستخدم العادي: بناء بروفايل، نشر، غاليري صور/فيديو، صفحات ثقافية.
للتاجر: إنشاء متجر داخلي (مجاني لأسبوع، ثم 10/شهرأو100/سنة)، يُنشر تلقائياً في المتجر العام.
مساعد AI: توليد وصف بروفايل، كود موقع، وسكريبت فيديو (OpenAI).


* إنشاء موقع خاص (Website Builder):

AI يولد HTML/CSS/JS احترافي بأحدث التقنيات وقوالب جاهزة (Tailwind).
لوحة تحكم (Dashboard) للتعديل/إضافة/حذف/معاينة.
اشتراك: 39/شهرأو32/سنة.
شراء دومين عبر Movista (تكامل Namecheap)، ربط بـ hosts موثوقة مثل Vercel/Hetzner.


* إنشاء فيديو AI احترافي (Professional AI Video):

توليد نصوص/سكريبت (OpenAI)، موسيقى/أغاني/ماسترينغ (ElevenLabs)، شخصيات بشرية/مواقع تصوير (Replicate Stable Diffusion).
محرر يدوي بسيط (React-Konva) لتعديل المشاهد/لقطات.
مجاني 30 ثانية؛ بعد ذلك 3.5$/دقيقة (حتى 120 دقيقة) – دفع عبر Stripe.


* التواصل والترفيه:

دردشة نص/صوت/فيديو (Simple-Peer WebRTC).
بث مباشر ثقافي/علمي مع متخصصين وAI (placeholder لـ Agora/Twilio).
منصة ألعاب متطورة (Phaser.js لألعاب ويب بسيطة).
صفحات مسابقات: أجمل صوت، ملكة جمال، تصميم أزياء، إلخ. (Supabase للتصويت/الإدخالات).


* المتجر العام (Public Store): عرض منتجات التجار، دفع عبر Stripe.
* لوحة الإدارة (Admin Dashboard): تحكم في المستخدمين، الإعلانات، المسابقات (RLS في Supabase).
* الدفعات: Stripe للاشتراكات (recurring) والدفعات الفردية (one-time)، مع تجربة مجانية.
* قابلية التوسع: API routes جاهزة لـ microservices، autoscaling على Vercel/Hetzner.
* الأمان والأداء: SSL تلقائي، realtime updates (Supabase)، UI متجاوب (Tailwind CSS).

لقطات شاشة (Screenshots)

*  – الصفحة الرئيسية مع المنشورات والإعلانات.
*  – بروفايل مع AI ومتجر.
*  – نموذج طلب فيديو AI.
*  – المتجر العام.

(أضف مجلد screenshots/ في الـ repo وصور تجريبية من Figma أو المتصفح).
التقنيات المستخدمة (Tech Stack)

* Frontend/Backend: Next.js 14 (App Router، TypeScript).
* قاعدة البيانات: Supabase (PostgreSQL، Auth، Storage، Realtime).
* الدفعات: Stripe (Subscriptions، Checkout).
* الذكاء الاصطناعي: OpenAI (GPT-4o للسكريبت/الكود)، ElevenLabs (صوت/موسيقى)، Replicate (صور/فيديو).
* الدردشة/البث: Simple-Peer (WebRTC)، placeholder لـ FFmpeg/Twilio.
* الألعاب: Phaser.js.
* المحرر: React-Konva (للفيديو).
* الدومين: Namecheap API.
* UI/Styles: Tailwind CSS (RTL، متجاوب).
* أخرى: React Hook Form، Lucide Icons، PM2 (للـ production).

التثبيت والإعداد (Installation & Setup)
المتطلبات

* Node.js 18+ (حمل من nodejs.org).
* حسابات: Supabase، Stripe، OpenAI، Google Cloud (OAuth)، ElevenLabs، Replicate، Namecheap.

خطوات التثبيت

1. 
نسخ المشروع:
git clone https://github.com/[اسم_المستخدم]/movista.git
cd movista


2. 
تثبيت الـ Dependencies:
npm install


3. 
إعداد Supabase (مجاني):

أنشئ مشروعاً في supabase.com.
في SQL Editor، شغّل الـ schemas (profiles، posts، subscriptions، videos، ads، websites، contests – انظر docs/schemas.sql إذا أضفتها).
فعّل Google Provider في Authentication (أضف Client ID من Google Console).
انسخ SUPABASE_URL و SUPABASE_ANON_KEY إلى .env.local.


4. 
إعداد Stripe:

أنشئ حساباً في stripe.com (test mode).
أنشئ Products/Prices: merchant_monthly (10)،merchanty​early(100)، website_monthly (39)،websitey​early(32)، video_min (3.5$ one-time).
انسخ STRIPE_SECRET_KEY و STRIPE_PUBLISHABLE_KEY إلى .env.local.


5. 
إعداد الـ AI والأدوات الأخرى:

OpenAI: OPENAI_API_KEY من openai.com.
Google: GOOGLE_CLIENT_ID من console.cloud.google.com.
ElevenLabs: ELEVENLABS_API_KEY من elevenlabs.io.
Replicate: REPLICATE_API_TOKEN من replicate.com.
Namecheap: NAMECHEAP_API_KEY من namecheap.com/reseller/api (sandbox للاختبار).
انسخ .env.local.example إلى .env.local واملأها.


6. 
تشغيل المشروع محلياً:
npm run dev


اذهب إلى http://localhost:3000.
جرب: تسجيل بـ Google، نشر منشور، توليد فيديو AI، دفع تجريبي.


7. 
بناء للـ Production:
npm run build
npm start



الاستخدام (Usage)

* للمستخدم: سجّل بـ Google، بنِ بروفايلك، استخدم AI للفيديو/الموقع، اشترِ في المتجر.
* للتاجر: حوّل بروفايلك إلى تاجر، أضف منتجات، ابدأ تجربة مجانية.
* للإدارة: اذهب إلى /admin (أضف نفسك كـ admin في Supabase).
* مثال API: POST /api/ai-generate لتوليد نص AI (مع prompt وtype).

النشر (Deployment)

* Vercel (موصى – مجاني للبداية):

اذهب إلى vercel.com، سجّل بـ GitHub.
Import الـ repo "movista".
أضف Env Vars (من .env.local).
Deploy – رابط فوري مثل movista.vercel.app (مع SSL ودامين مخصص).


* Hetzner (للتحكم الكامل، 4$/شهر):

أنشئ VPS في hetzner.com/cloud.
SSH: ssh root@your-ip، ثم git clone، npm install && npm run build && pm2 start npm -- start.
Wire Transfer للدفع (سهل في لبنان).


* أمان: فعّل RLS في Supabase، HTTPS في Vercel.

كيفية المساهمة (Contributing)

1. Fork الـ repo.
2. أنشئ branch: git checkout -b feature/new-feature.
3. Commit: git commit -m "Add new feature".
4. Push: git push origin feature/new-feature.
5. أرسل Pull Request.

يرجى اتباع Contributing Guidelines إذا أضفتها.
الترخيص (License)
هذا المشروع مرخص تحت MIT License. © 2025 Movista Project.
الدعم والتواصل (Support & Contact)

* افتح Issue للأخطاء أو الاقتراحات.
* تواصل: email@example.com أو @movista على X/Twitter.
* للدعم التقني: تحقق من docs/ أو اسأل في Discussions.

شكراً لدعمك! 🚀 Let's build the future of social networking together.

ملاحظات إضافية للـ README:

* أضف صوراً حقيقية في screenshots/ بعد تشغيل المشروع.
* أضف LICENSE ملف (MIT template من GitHub).
* أضف CONTRIBUTING.md إذا أردت تفاصيل أكثر.
* للترجمة: استخدم i18n في Next.js لدعم متعدد اللغات.

انسخ هذا إلى README.md في جذر الـ repo، ثم git add README.md && git commit -m "Add README" && git push
