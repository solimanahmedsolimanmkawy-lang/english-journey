English Journey v2 — Android-first free workflow

1) افتح index.html للتجربة. لتثبيت PWA على الهاتف، ارفع الملفات إلى HTTPS static hosting وافتح الرابط في Chrome ثم Install / Add to Home Screen.
2) AnkiDroid handoff: أضف كلمة ومعناها ثم اضغط مشاركة إلى AnkiDroid في قائمة مشاركة Android. أكمل البطاقة في AnkiDroid وتحقق من الوجه/الظهر قبل الحفظ. هذا إرسال بطاقة من التطبيق إلى AnkiDroid وليس قراءة أو مزامنة ثنائية الاتجاه.
3) Claude Pro: اكتب النص ثم جهّز الطلب. شاركه/انسخه إلى Claude. اطلب JSON كما هو موضح، ثم الصق كائن JSON في مربع استيراد نتيجة Claude. يسجل التطبيق وقت الاستيراد لكل تصحيح.
4) البيانات محلية. صدّر JSON بانتظام.
5) قيود معروفة: لا يمكن لصفحة PWA وحدها قراءة قاعدة بيانات AnkiDroid أو سجل المراجعات. المزامنة الكاملة تتطلب تطبيق Android أصلياً يدمج AnkiDroid API وصلاحياته. Claude Pro لا يشمل API usage؛ لا توجد API calls هنا.
