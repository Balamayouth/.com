<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>فريق تطوع شباب بلعما</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #f8fafc; /* لون خلفية أفتح */
    }
    .list-disc {
      padding-right: 1.25rem;
      padding-left: 0;
    }
    .mobile-menu {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease-out;
    }
    .mobile-menu.open {
      max-height: 500px;
    }
  </style>
</head>
<body class="text-gray-800">
  <header class="bg-blue-50 text-blue-800 py-4 sticky top-0 z-50 border-b border-blue-100">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <div class="flex items-center">
        
        <h1 class="text-2xl md:text-3xl font-bold">فريق تطوع شباب بلعما</h1>
      </div>
      
      <!-- قائمة الجوال (هامبرجر) -->
      <div class="md:hidden">
        <button id="menu-toggle" class="text-blue-700 focus:outline-none">
          <i class="fas fa-bars text-2xl"></i>
        </button>
      </div>
      
      <!-- قائمة التنقل الرئيسية (للكمبيوتر) -->
      <nav class="hidden md:block">
        <ul class="flex space-x-4 space-x-reverse">
          <li><a class="hover:text-blue-600 px-2 py-1" href="#vision">الرؤية</a></li>
          <li><a class="hover:text-blue-600 px-2 py-1" href="#mission">الرسالة</a></li>
          <li><a class="hover:text-blue-600 px-2 py-1" href="#goals">الأهداف</a></li>
          <li><a class="hover:text-blue-600 px-2 py-1" href="#initiatives">المبادرات الحالية</a></li>
          <li><a class="hover:text-blue-600 px-2 py-1" href="#future">التطلعات المستقبلية</a></li>
          <li><a class="hover:text-blue-600 px-2 py-1" href="#team">الهيكل التنظيمي</a></li>
        </ul>
      </nav>
    </div>
    
    <!-- قائمة الجوال المنسدلة -->
    <div id="mobile-menu" class="mobile-menu md:hidden bg-blue-50">
      <ul class="flex flex-col space-y-2 p-4">
        <li><a class="block hover:bg-blue-100 px-3 py-2 rounded text-blue-700" href="#vision">الرؤية</a></li>
        <li><a class="block hover:bg-blue-100 px-3 py-2 rounded text-blue-700" href="#mission">الرسالة</a></li>
        <li><a class="block hover:bg-blue-100 px-3 py-2 rounded text-blue-700" href="#goals">الأهداف</a></li>
        <li><a class="block hover:bg-blue-100 px-3 py-2 rounded text-blue-700" href="#initiatives">المبادرات الحالية</a></li>
        <li><a class="block hover:bg-blue-100 px-3 py-2 rounded text-blue-700" href="#future">التطلعات المستقبلية</a></li>
        <li><a class="block hover:bg-blue-100 px-3 py-2 rounded text-blue-700" href="#team">الهيكل التنظيمي</a></li>
      </ul>
    </div>
  </header>

  <main class="container mx-auto px-4 py-8">
    <section class="mb-12" id="introduction">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">في قلب لواء بلعما</h2>
      <p class="mb-6 text-right text-lg leading-relaxed">
        بدافع من توجيهات سيدي صاحب الجلالة ورؤية سمو الأمير الحسين بن عبدالله الثاني في تعزيز التكافل المجتمعي وتفعيل دور المواطنة الفاعلة، انطلقت فكرة فريق تطوع شباب بلعما كفريق مستقل لا يتبع لأي جهة، ليكون نموذجًا حيًا للعطاء والعمل الجماعي المنظم. بدأ الفريق بمرحلة الترخيص منذ عام 2024، مؤمنًا بأن القرية قادرة على تصدير الأفكار والإبداعات للمدينة، ليُثبت أن التنمية تبدأ من الجذور وتنمو لتصل إلى أبعد مدى.
      </p>
      <div class="rounded-lg overflow-hidden shadow-md border border-blue-100">
        <img alt="صورة تعبر عن العمل التطوعي في لواء بلعما" class="w-full h-auto" src="https://i.ibb.co/Z1d3JYCh/8.png"/>
      </div>
    </section>

    <section class="mb-12" id="vision">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">الرؤية</h2>
      <p class="mb-6 text-right text-lg leading-relaxed">
        نؤمن بأن الشباب هم حجر الأساس في بناء المجتمع، ونسعى إلى تمكينهم ليكونوا قادة في العمل التطوعي، مساهمين في إحداث تغيير إيجابي ومستدام في المجتمع، عبر مشاريع تنموية تعزز روح التكافل والتعاون.
      </p>
      <div class="rounded-lg overflow-hidden shadow-md border border-blue-100">
        <img alt="صورة تعبر عن رؤية الفريق في تمكين الشباب" class="w-full h-auto" src="https://i.ibb.co/Qjx6MFJ9/9.png"/>
      </div>
    </section>

    <section class="mb-12" id="mission">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">الرسالة</h2>
      <p class="mb-6 text-right text-lg leading-relaxed">
        نعمل على تنظيم وتطوير العمل التطوعي في لواء بلعما من خلال مبادرات مستدامة، تركز على الأمن الغذائي، والتنمية الاقتصادية، وبناء قاعدة بيانات دقيقة للأسر المحتاجة، مع السعي لخلق فرص عمل ودعم المشاريع الإنتاجية، بما يعزز من قدرة المجتمع على تحقيق الاكتفاء الذاتي.
      </p>
      <div class="rounded-lg overflow-hidden shadow-md border border-blue-100">
        <img alt="صورة تعبر عن رسالة الفريق في العمل التطوعي" class="w-full h-auto" src="https://i.ibb.co/Qjx6MFJ9/9.png"/>
      </div>
    </section>

    <section class="mb-12" id="goals">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">الأهداف</h2>
      <div class="bg-white p-6 rounded-lg shadow-md mb-6 border border-blue-100">
        <ul class="list-disc pr-5 text-right space-y-3 text-lg">
          <li>تعزيز ثقافة العمل التطوعي بين الشباب، وتنظيم جهودهم ضمن إطار مؤسسي.</li>
          <li>تقديم الدعم الغذائي للأسر العفيفة عبر مبادرات مستدامة تعتمد على التبرعات والمشاريع الإنتاجية.</li>
          <li>إنشاء مشاريع زراعية وإنتاجية لاستدامة العمل الخيري، مثل البيوت البلاستيكية ومزارع الأسماك، وتوفير فرص عمل لأبناء اللواء.</li>
          <li>بناء قاعدة بيانات للأسر المحتاجة، وفق نظام تصنيف (ABC) يضمن وصول المساعدات إلى مستحقيها بطريقة عادلة ومنظمة.</li>
          <li>تنمية الموارد المالية للفريق من خلال مشاريع استثمارية، لضمان استمرارية العطاء بعيدًا عن التبرعات الآنية.</li>
        </ul>
      </div>
      <div class="rounded-lg overflow-hidden shadow-md border border-blue-100">
        <img alt="صورة تعبر عن أهداف الفريق في العمل التطوعي" class="w-full h-auto" src="https://i.ibb.co/fd8BBb2Q/Whats-App-Image-2025-03-27-at-12-31-40-AM.jpg"/>
      </div>
    </section>

    <section class="mb-12" id="initiatives">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">المبادرات الحالية</h2>
      <p class="mb-6 text-right text-lg">
        بدأ الفريق عمله بمبادرتين رئيسيتين:
      </p>
      <div class="grid md:grid-cols-2 gap-8 mb-6">
        <div class="bg-white p-6 rounded-lg shadow-md border border-blue-100">
          <h3 class="text-xl font-bold mb-3 text-right text-blue-600">مبادرة "بحبة خضرة نطعمي أسرة"</h3>
          <p class="text-right text-lg mb-4">
            حيث توضع سلال بلاستيكية في محلات الخضار لتشجيع الناس على التبرع ولو بحبة خضار واحدة، تُجمع التبرعات يوميًا وتُوزع على الأسر المحتاجة.
          </p>
          <div class="rounded-lg overflow-hidden">
            <img alt="صورة للمبادرة" class="w-full h-auto" src="https://i.ibb.co/7xY3n1rF/10.png"/>
          </div>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md border border-blue-100">
          <h3 class="text-xl font-bold mb-3 text-right text-blue-600">مبادرة "رغيف"</h3>
          <p class="text-right text-lg mb-4">
            يتم وضع صناديق للتبرع في المخابز، ويتم جمع التبرعات وفرزها وتوزيعها بعد صلاة العشاء.
          </p>
          <div class="rounded-lg overflow-hidden">
            <img alt="صورة للمبادرة" class="w-full h-auto" src="https://i.ibb.co/fd8BBb2Q/Whats-App-Image-2025-03-27-at-12-31-40-AM.jpg"/>
          </div>
        </div>
      </div>
    </section>

    <section class="mb-12" id="future">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">التطلعات المستقبلية</h2>
      <p class="mb-6 text-right text-lg">
        لضمان استدامة العطاء، يطمح الفريق إلى:
      </p>
      <div class="bg-white p-6 rounded-lg shadow-md border border-blue-100">
        <ul class="list-disc pr-5 text-right space-y-3 text-lg">
          <li>مأسسة المشروع ليكون يعمل تحت اطار مؤسسي.</li>
          <li>إقامة المشاريع الربحية التي تعود على المبادرة بالمال الذي يعمل على استدامة المبادرة.</li>
          <li>إنشاء صندوق خيري مستدام، يديره أمين مختص، لضمان توفير الدعم المالي على مدار العام، خاصة مع اقتراب شهر رمضان المبارك.</li>
        </ul>
      </div>
    </section>

    <section class="mb-12" id="team">
      <h2 class="text-2xl font-bold mb-6 text-right border-b-2 border-blue-200 pb-2 text-blue-700">الهيكل التنظيمي للفريق</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        
        <!-- رئيس الفريق -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة لرئيس الفريق مراد عليان الخوالدة" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/rKYFQvSX/11.png"/>
            <h3 class="text-xl font-bold mt-4">مراد عليان الخوالدة</h3>
            <p class="text-blue-600">رئيس الفريق</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>الإشراف العام على الفريق والتأكد من تحقيق رؤيته وأهدافه.</li>
            <li>تمثيل الفريق رسميًا أمام الجهات الخارجية.</li>
            <li>اتخاذ القرارات الاستراتيجية بالتشاور مع باقي الأعضاء.</li>
            <li>الإشراف على أداء اللجان والتأكد من سير العمل بسلاسة.</li>
          </ul>
        </div>

        <!-- نائب الرئيس -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة لنائب الرئيس هديب عيسى الخوالدة" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/YF4zQHjL/12.png"/>
            <h3 class="text-xl font-bold mt-4">هديب عيسى الخوالدة</h3>
            <p class="text-blue-600">نائب الرئيس</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>دعم الرئيس في إدارة الفريق واتخاذ القرارات.</li>
            <li>الإشراف على الميزانية وإدارة المصاريف والتبرعات.</li>
            <li>إعداد التقارير المالية وتقديمها للفريق عند الحاجة.</li>
            <li>مساعدة اللجان المختلفة في تأمين الاحتياجات المالية عند توفر الموارد.</li>
          </ul>
        </div>

        <!-- المشرف العام -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة للمشرف العام احمد عيد" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/TxY5Qf6t/13.png"/>
            <h3 class="text-xl font-bold mt-4">احمد عيد</h3>
            <p class="text-blue-600">المشرف العام</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>التوجيه والدعم: ضمان التزام الفريق بالرؤية والأهداف دون فرض قرارات.</li>
            <li>المتابعة والتقييم: تقديم ملاحظات لتحسين جودة العمل دون رقابة مباشرة.</li>
            <li>تعزيز بيئة الفريق: تحفيز الأعضاء وتشجيع العمل الجماعي.</li>
            <li>التنسيق والتمثيل: بناء علاقات مع الجهات الداعمة دون تدخل إداري.</li>
            <li>التطوير والاستدامة: اقتراح أفكار لضمان استمرارية الفريق ومبادراته.</li>
            <li>الإشراف العام على جميع اللجان.</li>
            <li>الناطق الإعلامي باسم الفريق.</li>
          </ul>
        </div>

        <!-- رئيس اللجنة الإعلامية -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة لرئيس اللجنة الإعلامية معاذ احمد الخوالدة" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/MytGdsB4/14.png"/>
            <h3 class="text-xl font-bold mt-4">معاذ احمد الخوالدة</h3>
            <p class="text-blue-600">رئيس اللجنة الإعلامية</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>التنسيق التقني.</li>
            <li>إدارة أي منصات إلكترونية يستخدمها الفريق (موقع إلكتروني، قاعدة بيانات، تطبيقات).</li>
            <li>تقديم الدعم التقني للفرق واللجان الأخرى عند الحاجة.</li>
            <li>تطوير الأدوات التقنية التي تساعد في تنظيم العمل الداخلي.</li>
            <li>إعداد وتصميم المنشورات والمحتوى الإعلامي الخاص بالفريق.</li>
            <li>إدارة حسابات الفريق على وسائل التواصل الاجتماعي.</li>
          </ul>
        </div>

        <!-- رئيس لجنة العلاقات العامة -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة لرئيس لجنة العلاقات العامة ابراهيم سعود" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/pvVdhqb3/15.png"/>
            <h3 class="text-xl font-bold mt-4">ابراهيم سعود</h3>
            <p class="text-blue-600">رئيس لجنة العلاقات العامة</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>بناء علاقات مع الجهات الداعمة والشركاء المحتملين.</li>
            <li>تنظيم اللقاءات والاجتماعات مع المؤسسات والمجتمع المحلي.</li>
            <li>البحث عن فرص شراكة وتمويل لدعم أنشطة الفريق.</li>
          </ul>
        </div>

        <!-- عضو لجنة العلاقات العامة -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة لعضو لجنة العلاقات العامة المهندس فرحان الخوالدة" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/LdD0GjZf/16.png"/>
            <h3 class="text-xl font-bold mt-4">المهندس فرحان الخوالدة</h3>
            <p class="text-blue-600">عضو لجنة العلاقات العامة</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>بناء علاقات مع الجهات الداعمة والشركاء المحتملين.</li>
            <li>تنظيم اللقاءات والاجتماعات مع المؤسسات والمجتمع المحلي.</li>
            <li>البحث عن فرص شراكة وتمويل لدعم أنشطة الفريق.</li>
          </ul>
        </div>

        <!-- رئيس لجنة الموارد البشرية -->
        <div class="bg-white p-6 rounded-lg shadow-md text-right border border-blue-100">
          <div class="flex flex-col items-center mb-4">
            <img alt="صورة لرئيس لجنة الموارد البشرية احمد عليان" class="w-32 h-32 rounded-full object-cover border-4 border-blue-100" src="https://i.ibb.co/xtcqRQFp/17.png"/>
            <h3 class="text-xl font-bold mt-4">احمد عليان</h3>
            <p class="text-blue-600">رئيس لجنة الموارد البشرية (HR)</p>
          </div>
          <ul class="list-disc pr-5 space-y-2">
            <li>استقبال طلبات التطوع وفرزها وفقًا لاحتياجات الفريق.</li>
            <li>تنظيم قاعدة بيانات للمتطوعين وتصنيفهم حسب المهارات.</li>
            <li>تنظيم دورات تعريفية وتدريبية للمتطوعين الجدد.</li>
            <li>متابعة أداء المتطوعين وتقديم التغذية الراجعة لتحسين العمل الجماعي.</li>
          </ul>
        </div>

      </div>
    </section>
  </main>

  <footer class="bg-blue-50 text-blue-800 py-8 border-t border-blue-100">
    <div class="container mx-auto px-4">
      <div class="flex flex-col md:flex-row justify-between items-center">
        <div class="mb-4 md:mb-0 text-center md:text-right">
          <h3 class="text-xl font-bold mb-2">فريق تطوع شباب بلعما</h3>
          <p>لواء بلعما - المملكة الأردنية الهاشمية</p>
        </div>
        <div class="flex space-x-4 space-x-reverse">
          <a href="#" class="text-blue-600 hover:text-blue-800 text-2xl"><i class="fab fa-facebook"></i></a>
          <a href="#" class="text-blue-600 hover:text-blue-800 text-2xl"><i class="fab fa-twitter"></i></a>
          <a href="#" class="text-blue-600 hover:text-blue-800 text-2xl"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
      <div class="border-t border-blue-200 mt-6 pt-6 text-center">
        <p>© 2024 فريق تطوع شباب بلعما. جميع الحقوق محفوظة.</p>
      </div>
    </div>
  </footer>

  <script>
    // تفعيل قائمة الهاتف
    const menuToggle = document.getElementById('menu-toggle');
    const mobileMenu = document.getElementById('mobile-menu');
    
    menuToggle.addEventListener('click', () => {
      mobileMenu.classList.toggle('open');
    });
    
    // إغلاق القائمة عند النقر على رابط
    const navLinks = document.querySelectorAll('#mobile-menu a');
    navLinks.forEach(link => {
      link.addEventListener('click', () => {
        mobileMenu.classList.remove('open');
      });
    });
  </script>
</body>
</html>
