# Mis
ملخص الفصل الخامس من كتاب نضم المعلومات الاداريه
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شرح الفصل الخامس: إدارة قواعد البيانات</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
            color: #374151; /* Dark gray text */
        }
        .container {
            max-width: 960px; /* Max width for content */
        }
        h1, h2, h3, h4 {
            font-weight: 700; /* Bold headings */
            color: #1f2937; /* Even darker gray for headings */
        }
        .section-card {
            background-color: #ffffff; /* White card background */
            border-radius: 0.75rem; /* Rounded corners */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Subtle shadow */
            padding: 1.5rem; /* Padding inside cards */
            margin-bottom: 1.5rem; /* Space between cards */
        }
        .sub-section-title {
            color: #4b5563; /* Slightly lighter heading for sub-sections */
            font-weight: 600;
            margin-top: 1rem;
            margin-bottom: 0.5rem;
        }
        p {
            line-height: 1.75; /* Improved readability */
            margin-bottom: 1rem;
        }
        ul {
            list-style-type: disc;
            margin-right: 1.5rem;
            margin-bottom: 1rem;
        }
        ul li {
            margin-bottom: 0.5rem;
            line-height: 1.6;
        }
        .author-info {
            font-weight: 600;
            color: #2563eb;
            margin-top: 2rem;
            margin-bottom: 2rem;
            text-align: center;
            font-size: 1.125rem;
        }
        .figure-description {
            background-color: #f0f9ff; /* Very light blue for descriptions */
            border: 1px solid #bfdbfe;
            border-radius: 0.5rem;
            padding: 1rem;
            margin-top: 1rem;
            margin-bottom: 1rem;
            font-style: italic;
            color: #1e40af; /* Darker blue text for description */
        }
    </style>
</head>
<body class="p-4 sm:p-8">
    <div class="container mx-auto">
        <header class="text-center mb-8">
            <h1 class="text-4xl font-bold text-blue-700 mb-2">شرح الفصل الخامس: إدارة قواعد البيانات</h1>
            <p class="text-lg text-gray-600">فهم أساسيات تنظيم وإدارة البيانات في نظم المعلومات الإدارية</p>
            <div class="author-info">
                إعداد وتقديم: قيس طلال غالب الجازي
            </div>
        </header>

        <main id="main-content">
            <div class="section-card">
                <h2 class="text-2xl mb-4">مقدمة الفصل (صفحة 133)</h2>
                <p>
                    يبدأ الفصل بتوضيح أن <strong>أهم أهداف أنظمة المعلومات هو تزويد المستخدمين بالمعلومات الدقيقة ذات الصلة في الوقت المناسب</strong>[cite: 10]. ويشير إلى أن:
                </p>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>المعلومات الدقيقة:</strong> هي المعلومات الخالية من الأخطاء مثل التكرار وعدم التنسيق.
                    </li>
                    <li>
                        <strong>المعلومات ذات الصلة:</strong> تكون مفيدة لصانعي القرار ولإتمام العمل.
                    </li>
                    <li>
                        <strong>المعلومات في الوقت المناسب:</strong> تتوفر لصانعي القرار عندما يحتاجونها.
                    </li>
                </ul>
                <p>
                    الأنظمة الحديثة تخزن البيانات في ملفات إلكترونية على أجهزة الحواسيب. عندما تحفظ الملفات وتنظم بشكل جيد فإن المستخدمين يستطيعون:
                </p>
                <ul class="list-disc pr-6">
                    <li>تخزين البيانات (Data Saving)</li>
                    <li>الحصول على المعلومات (Query)</li>
                    <li>تعديل البيانات (Data Updating)</li>
                    <li>استرجاع المعلومات (Information Retrieving) بشكل سهل عندما يحتاجون لذلك.</li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">جدول محتويات الفصل (صفحة 134)</h2>
                <p>
                    (هذه الصفحة تحتوي على فهرس لموضوعات الفصل الخامس، وتوضح العناوين الرئيسية والفرعية التي سيتم تناولها في الصفحات التالية). [cite: 10]
                </p>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.1 تنظيم الملفات (صفحة 135)</h2>
                <p>
                    لتنظيم الملفات وفهم كيفية تخزين البيانات، يجب التعرف على الوحدات الأساسية التي تتكون منها البيانات في الحاسوب:
                </p>
                <h3 class="sub-section-title">البت (Bit):</h3>
                <ul class="list-disc pr-6">
                    <li>هو أصغر وحدة تخزين يمكن للحاسوب تخزينه حيث تكون قيمة (Bit) إما 1 أو صفر.</li>
                    <li>يعتبر اختصار لكلمة (Binary Digit).</li>
                </ul>
                <h3 class="sub-section-title">البايت (Byte):</h3>
                <ul class="list-disc pr-6">
                    <li>هو مجموعة من ثمانية (Bits).</li>
                    <li>يستخدم لتخزين الأرقام ما بين صفر و 255.</li>
                    <li>يمكن تصور (Byte) على الشكل التالي:</li>
                    <div class="figure-description">
                        <strong>جدول يوضح 8 خانات للبتات (تصور البايت):</strong>
                        <p>يُظهر هذا الجدول ثمانية مربعات متجاورة، يمثل كل منها "بت" واحد، ويمكن أن يحتوي على قيمة 0 أو 1. يوضح هذا الترتيب كيف تتجمع البتات لتشكل "بايت" واحد، وهو الوحدة الأساسية لتخزين حرف واحد أو رقم صغير.</p>
                    </div>
                    <li>إن أكبر قيمة يمكن تخزينها في (Byte) هي 11111111 وهي تعادل في النظام العشري 255.</li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">تابع: تنظيم الملفات (هيكلية البيانات) (صفحة 136)</h2>
                <p>
                    تتدرج وحدات تخزين البيانات في الحاسوب بشكل هرمي تبدأ من أصغر إلى أكبر وحدة على النحو التالي:
                </p>
                <ul class="list-disc pr-6">
                    <li><strong>البت (Bit):</strong> أصغر وحدة.</li>
                    <li><strong>البايت (Byte):</strong> مجموعة من البتات.</li>
                    <li>
                        <strong>الحقل (Field):</strong>
                        مجموعة من البايتات التي تشكل حرفًا أو كلمة أو رقمًا كاملاً. على سبيل المثال، "اسم الطالب" أو "رقم الهوية".
                    </li>
                    <li>
                        <strong>السجل (Record):</strong>
                        مجموعة من الحقول المترابطة التي تصف كيانًا واحدًا (مثل بيانات طالب كاملة: الاسم، رقم الهوية، التخصص).
                    </li>
                    <li>
                        <strong>الملف (File):</strong>
                        مجموعة من السجلات ذات الصلة (مثل ملف يحتوي على جميع سجلات الطلاب في الجامعة).
                    </li>
                    <li>
                        <strong>قاعدة البيانات (Database):</strong>
                        مجموعة من الملفات المترابطة والتي تم تصميمها للوصول إلى البيانات المخزنة فيها وتعديلها وإدارتها بكفاءة.
                    </li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.2 التنظيم التقليدي للملفات (صفحة 137)</h2>
                <p>
                    يشير هذا القسم إلى طريقة تخزين البيانات في ملفات منفصلة لكل تطبيق أو قسم في المؤسسة. على سبيل المثال، قد يكون لقسم المبيعات ملف بيانات خاص به، وقسم المحاسبة ملف آخر.
                </p>
                <p>
                    على الرغم من بساطتها الظاهرية، إلا أن هذه الطريقة تسبب مشاكل كبيرة.
                </p>
                <h3 class="sub-section-title">5.2.1 المشاكل في بيئة الملفات التقليدية (صفحة 138)</h3>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>تكرار البيانات (Data Redundancy):</strong>
                        نفس البيانات يمكن أن تكون مخزنة في ملفات متعددة. مثلاً، معلومات العميل قد تكون في ملف المبيعات وملف المحاسبة. هذا يؤدي إلى:
                        <ul>
                            <li>إهدار في مساحة التخزين.</li>
                            <li>زيادة في وقت الإدخال.</li>
                            <li>احتمالية عالية للأخطاء (إذا تم تحديث معلومة في مكان ولم يتم في مكان آخر).</li>
                        </ul>
                    </li>
                    <li>
                        <strong>عدم اتساق البيانات (Data Inconsistency):</strong>
                        بسبب التكرار، قد تظهر نفس البيانات بقيم مختلفة في ملفات مختلفة. مثلاً، عنوان العميل محدث في ملف واحد وغير محدث في آخر.
                    </li>
                    <li>
                        <strong>اعتماد البرامج على البيانات (Program-Data Dependence):</strong>
                        تكون البرامج مصممة للعمل مع تنسيق ملفات محدد. أي تغيير في هيكل الملف يتطلب تعديل البرنامج.
                    </li>
                    <li>
                        <strong>ضعف مشاركة البيانات (Poor Data Sharing):</strong>
                        صعوبة مشاركة البيانات بين التطبيقات أو الأقسام المختلفة بسبب عدم وجود تنسيق موحد أو مركزية للبيانات.
                    </li>
                    <li>
                        <strong>ضعف الأمن (Poor Security):</strong>
                        صعوبة فرض ضوابط أمنية موحدة على البيانات الموزعة في ملفات متعددة.
                    </li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.3 قاعدة البيانات (Database) (صفحة 141)</h2>
                <p>
                    هي مجموعة منظمة من البيانات المخزنة والوصول إليها إلكترونيًا. تهدف إلى حل مشاكل التنظيم التقليدي للملفات.
                </p>
                <h3 class="sub-section-title">5.3.1 نظام إدارة قاعدة البيانات (Database Management System - DBMS) (صفحة 141)</h3>
                <p>
                    هو برنامج وسيط بين المستخدمين وقاعدة البيانات. يسمح بإنشاء قاعدة البيانات، وإدارتها، وتعديلها، واسترجاع المعلومات منها.
                </p>
                <h3 class="sub-section-title">5.3.2 نماذج نظام إدارة قاعدة البيانات (DBMS Models) (صفحة 142)</h3>
                <p>
                    توجد عدة نماذج لتنظيم البيانات داخل قاعدة البيانات، وأكثرها شيوعًا هي:
                </p>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>النموذج العلائقي (Relational Database Model):</strong>
                        (الأكثر شيوعًا) ينظم البيانات في جداول (Tables) مكونة من صفوف (Rows) تمثل السجلات، وأعمدة (Columns) تمثل الحقول. يتم ربط الجداول ببعضها البعض باستخدام مفاتيح (Keys) مشتركة.
                    </li>
                    <li>
                        <strong>النموذج الهرمي (Hierarchical Database Model):</strong>
                        (أقدم) ينظم البيانات على شكل شجرة، حيث كل سجل "أب" يمكن أن يكون له عدة سجلات "أبناء"، ولكن كل سجل "ابن" يمكن أن يكون له أب واحد فقط.
                    </li>
                    <li>
                        <strong>نموذج الشبكة (Network Database Model):</strong>
                        (تطوير للهرمي) يسمح لكل سجل "ابن" أن يكون له عدة آباء، مما يوفر مرونة أكبر في الروابط.
                    </li>
                    <li>
                        <strong>نموذج الكائن الموجه (Object-Oriented Database Model):</strong>
                        يخزن البيانات في شكل كائنات (Objects) تحتوي على البيانات والعمليات المرتبطة بها، وهو مناسب للبيانات المعقدة مثل الوسائط المتعددة.
                    </li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.4 أنواع قواعد البيانات (صفحة 149)</h2>
                <p>يمكن تصنيف قواعد البيانات بناءً على عدة معايير:</p>
                <h3 class="sub-section-title">5.4.1 أعداد المستخدمين (صفحة 149)</h3>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>قاعدة بيانات المستخدم الواحد (Single User Database):</strong>
                        يستخدمها شخص واحد فقط في نفس الوقت.
                    </li>
                    <li>
                        <strong>قاعدة بيانات المستخدمين المتعددين (Multi-User Database):</strong>
                        يستخدمها عدة أشخاص في نفس الوقت.
                    </li>
                </ul>
                <h3 class="sub-section-title">5.4.2 المكان (صفحة 150)</h3>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>قاعدة بيانات مركزية (Centralized Database):</strong>
                        تخزن في مكان واحد (خادم واحد).
                    </li>
                    <li>
                        <strong>قاعدة بيانات موزعة (Distributed Database):</strong>
                        تخزن في عدة مواقع جغرافية، وتكون متصلة مع بعضها البعض.
                    </li>
                </ul>
                <h3 class="sub-section-title">5.4.3 الاستخدام (صفحة 150)</h3>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>قاعدة بيانات تشغيلية (Operational Database):</strong>
                        تستخدم لمعالجة المعاملات اليومية (مثلاً، تسجيل المبيعات).
                    </li>
                    <li>
                        <strong>قاعدة بيانات تحليلية (Analytical Database):</strong>
                        تستخدم لتحليل البيانات التاريخية واستخلاص الأنماط والقرارات (مثل مستودعات البيانات).
                    </li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.5 المكونات الرئيسية لنظام إدارة قاعدة البيانات (صفحة 150)</h2>
                <h3 class="sub-section-title">5.5.1 وظيفة تعريف البيانات (Data Definition Function) (صفحة 151)</h3>
                <p>
                    تسمح بتعريف هيكل قاعدة البيانات (الجداول، الحقول، أنواع البيانات، العلاقات).
                </p>
                <h3 class="sub-section-title">5.5.2 قاموس البيانات (Data Dictionary) (صفحة 151)</h3>
                <p>
                    يحتوي على تعريفات لكل عنصر بيانات في قاعدة البيانات (مثل اسم الحقل، نوعه، حجمه، وصفه).
                </p>
                <h3 class="sub-section-title">5.5.3 الاستعلام والتقارير (Query and Reporting) (صفحة 151)</h3>
                <p>
                    يوفر أدوات للمستخدمين لاسترجاع البيانات وتعديلها وتحليلها وإنشاء التقارير (مثل لغة SQL).
                </p>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.6 استخدام قاعدة البيانات لتحسين فعالية الأعمال واتخاذ القرارات (صفحة 152)</h2>
                <p>
                    تمكن قواعد البيانات الحديثة الشركات من جمع كميات هائلة من البيانات وتحليلها لدعم اتخاذ القرارات وتحسين العمليات.
                </p>
                <h3 class="sub-section-title">5.6.1 مستودع البيانات (Data Warehouse) (صفحة 153)</h3>
                <p>
                    قاعدة بيانات كبيرة مصممة لتخزين كميات ضخمة من البيانات التاريخية من مصادر متعددة، بهدف التحليل واتخاذ القرارات.
                </p>
                <h3 class="sub-section-title">5.6.2 مستودع البيانات الجزئي (Data Mart) (صفحة 153)</h3>
                <p>
                    نسخة مصغرة من مستودع البيانات، مصممة لتلبية احتياجات قسم معين أو وظيفة محددة في المؤسسة.
                </p>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.7 ذكاء الأعمال (Business Intelligence) (صفحة 154)</h2>
                <p>
                    مجموعة من التقنيات والأدوات والعمليات التي تساعد المؤسسات على تحويل البيانات الخام إلى معلومات قابلة للفهم لاتخاذ قرارات أفضل وأكثر استنارة. يشمل:
                </p>
                <ul class="list-disc pr-6">
                    <li>استخراج البيانات (Data Mining)</li>
                    <li>التحليل الإحصائي (Statistical Analysis)</li>
                    <li>العروض التقديمية للبيانات (Data Presentation)</li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.8 قاعدة البيانات والويب (Database and the Web) (صفحة 156)</h2>
                <p>
                    تسمح تقنيات الويب (مثل HTML, CSS, JavaScript) بالوصول إلى قواعد البيانات عبر الإنترنت. تطبيقات الويب تستخدم DBMS لجلب وعرض البيانات من قواعد البيانات للمستخدمين عبر المتصفح.
                </p>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.9 إدارة مصادر البيانات (Managing Data Resources) (صفحة 157)</h2>
                <p>
                    لضمان جودة وأمان البيانات، يجب إدارة مصادر البيانات بشكل فعال.
                </p>
                <h3 class="sub-section-title">5.9.1 إنشاء سياسة المعلومات (Establishing an Information Policy) (صفحة 157)</h3>
                <p>
                    تحديد القواعد والمسؤوليات لمن يمكنه الوصول إلى البيانات، وكيف يمكن استخدامها، ومن هو المسؤول عنها.
                </p>
                <h3 class="sub-section-title">5.9.2 ضمان جودة البيانات (Ensuring Data Quality) (صفحة 158)</h3>
                <p>
                    التأكد من أن البيانات دقيقة، كاملة، متناسقة، وفي الوقت المناسب. يتطلب ذلك عمليات تدقيق للبيانات وتنظيفها.
                </p>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.10 وحدات تخزين البيانات (Data Storage Units) (صفحة 159)</h2>
                <p>
                    بالإضافة إلى البت والبايت، توجد وحدات تخزين أكبر:
                </p>
                <ul class="list-disc pr-6">
                    <li>كيلوبايت (KB) = 1024 بايت</li>
                    <li>ميجابايت (MB) = 1024 كيلوبايت</li>
                    <li>جيجابايت (GB) = 1024 ميجابايت</li>
                    <li>تيرابايت (TB) = 1024 جيجابايت</li>
                    <li>بيتابايت (PB) = 1024 تيرابايت</li>
                </ul>
            </div>
        </main>

        <footer class="text-center text-gray-500 text-sm mt-8">
            <p>&copy; 2025 قيس طلال غالب الجازي. جميع الحقوق محفوظة.</p>
        </footer>
    </div>
</body>
