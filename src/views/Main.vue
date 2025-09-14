  <template>
      <section class="">
    <!-- Navigation -->
<nav class="bg-white shadow h-16 flex items-center px-8">
  <div class="flex justify-between items-center w-full">
    <!-- Logo -->
    <div class="flex items-center font-bold text-xl text-[#FB7D46]">
    @School
    </div>
    <!-- Links -->
    <div class="hidden md:flex gap-8">
      <a href="#" class="font-bold text-gray-700 hover:text-[#FB7D46]">الدورات</a>
      <a href="#" class="font-bold text-gray-700 hover:text-[#FB7D46]">المميزات</a>
      <a href="#" class="font-bold text-gray-700 hover:text-[#FB7D46]">المجتمع</a>
      <a href="#" class="font-bold text-gray-700 hover:text-[#FB7D46]">المصادر</a>
      <a href="#" class="font-bold text-gray-700 hover:text-[#FB7D46]">تسجيل الدخول</a>
    </div>
    <!-- Buttons -->
    <div class="flex gap-4">
      <a href="#"
        class="px-3 py-1 rounded bg-[#FB7D46] text-white border-[2px] border-[#FB7D46] hover:bg-white hover:text-[#FB7D46] transition">
        ابدأ مجاناً
      </a>
    </div>
  </div>
</nav>
<section class="bg-white text-black w-full">
  <!-- Hero Section -->
  <div class="grid grid-cols-1 md:grid-cols-2 gap-10 px-8 md:px-16 py-12">
    <!-- Right image -->
    <div class="flex items-center">
      <div class="border-4 border-[#FB7D46] p-1 flex items-center rounded-2xl justify-center">
        <img src="../assets/imgs/herp.png" class="w-80 rounded-lg" />
      </div>
    </div>
    <!-- Left content -->
    <div class="flex flex-col justify-end text-right items-end space-y-6">
      <div
        class="inline-flex items-center space-x-2 border-[2px] border-black rounded-full px-4 py-2 text-sm text-black w-max">
        <span class="w-4 h-4 border-[2px] border-black rounded-full inline-block"></span>
        <span class="font-bold">موثوق من أكثر من 25 ألف ولي أمر حول العالم</span>
      </div>
      <h1 class="text-4xl md:text-5xl font-bold leading-tight">
        <span class="text-[#FB7D46]">تعلّم بذكاء</span> وحقق التقدم <br> وركز على أهدافك
      </h1>
      <p class="text-gray-600 text-lg">
        منصتنا تساعد طفلك على تعلم البرمجة خطوة بخطوة، من الأساسيات حتى الاحتراف،
        بطريقة ممتعة ومشوقة.
      </p>
      <div class="flex space-x-4 pt-4">
        <a href="#"
          class="bg-[#FB7D46] text-white font-medium px-6 py-3 rounded-lg text-sm flex items-center space-x-2 hover:bg-orange-600">
          <span>ابدأ التجربة المجانية</span>
        </a>
        <a href="#"
          class="border border-gray-400 text-gray-700 px-6 py-3 rounded-lg text-sm font-medium hover:bg-gray-100">
          ابدأ أول درس لك
        </a>
      </div>
      <div class="grid grid-cols-3 gap-6 pt-8">
        <div>
          <div class="text-2xl font-bold text-gray-900">2000+</div>
          <div class="text-gray-600 text-xl">ساعات تعليم</div>
        </div>
        <div>
          <div class="text-2xl font-bold text-gray-900">10+</div>
          <div class="text-gray-600 text-xl">دول حول العالم</div>
        </div>
        <div>
          <div class="text-2xl font-bold text-gray-900">25k+</div>
          <div class="text-gray-600 text-xl">أولياء أمور سعداء</div>
        </div>
      </div>
    </div>
  </div>
</section>
    <!-- Features -->
<!-- Features Section -->
<!-- قسم المميزات -->
<section class="py-20 px-8 bg-[#efefef]">
  <div class="max-w-6xl mx-auto text-center mb-12">
    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">لماذا تتعلّم مع <span class="text-[#FB7D46]"> @سكول </span>؟</h2>
    <p class="text-gray-600 mt-4 font-bold">نظام متكامل يساعد الأطفال على التعلم والممارسة والتطور في مهارات البرمجة</p>
  </div>
<div class="grid md:grid-cols-4 gap-8">
  <!-- التعلم -->
  <div
    class="p-6 rounded-lg cursor-pointer bg-[#f9f9f9] shadow-xl hover:-translate-y-1 hover:shadow-2xl transition flex flex-col items-center text-center">
    <img src="../assets/icons/learning.png" alt="تعلم" class="w-12 h-12 mb-4" />
    <h3 class="mb-2 text-[#FB7D46] font-bold text-lg">التعلّم</h3>
    <p class="text-gray-700 text-sm">محتوى برمجي شامل يناسب جميع المستويات</p>
  </div>
  <!-- الممارسة -->
  <div
    class="p-6 rounded-lg cursor-pointer bg-[#f9f9f9] shadow-xl hover:-translate-y-1 hover:shadow-2xl transition flex flex-col items-center text-center">
    <img src="../assets/icons/coding.png" alt="ممارسة" class="w-12 h-12 mb-4" />
    <h3 class="mb-2 text-[#FB7D46] font-bold text-lg">الممارسة</h3>
    <p class="text-gray-700 text-sm">تحديات ومشاريع تفاعلية لتطبيق المهارات</p>
  </div>
  <!-- التطور -->
  <div
    class="p-6 rounded-lg cursor-pointer bg-[#f9f9f9] shadow-xl hover:-translate-y-1 hover:shadow-2xl transition flex flex-col items-center text-center">
    <img src="../assets/icons/App.png" alt="تطور" class="w-12 h-12 mb-4" />
    <h3 class="mb-2 text-[#FB7D46] font-bold text-lg">التطوّر</h3>
    <p class="text-gray-700 text-sm">بناء مهارات برمجية واقعية واحترافية</p>
  </div>
  <!-- التواصل -->
  <div
    class="p-6 rounded-lg cursor-pointer bg-[#f9f9f9] shadow-xl hover:-translate-y-1 hover:shadow-2xl transition flex flex-col items-center text-center">
    <img src="../assets/icons/link.png" alt="تواصل" class="w-12 h-12 mb-4" />
    <h3 class="mb-2 text-[#FB7D46] font-bold text-lg">التواصل</h3>
    <p class="text-gray-700 text-sm">انضم إلى مجتمع عالمي من المتعلمين</p>
  </div>
</div>
</section>
<!-- قسم مسار التعلم -->
<section class="bg-gray-50 py-20 px-8">
  <!-- العنوان -->
  <div class="text-center max-w-3xl mx-auto mb-16">
    <span class="text-[#FB7D46] font-semibold uppercase tracking-wide">التعلّم</span>
    <h2 class="text-4xl font-bold text-gray-900 mt-2 mb-4">
      طريقك نحو إتقان البرمجة
    </h2>
    <p class="text-lg text-gray-600">
      اكتشف تجربة تعليمية مصممة لتسريع مهاراتك في البرمجة خطوة بخطوة
    </p>
  </div>
  <!-- الشبكة -->
  <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- الكارت 1 -->
<div
  class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden max-w-sm mx-auto flex flex-col"
>
  <!-- الصورة -->
<div class="h-56 bg-gray-200 flex items-center justify-center relative">
  <img src="../assets/imgs/admin.png" alt="لوحة التحكم" class="w-full h-full object-cover" />
  <span class="absolute bottom-[-14px] z-50 right-10 bg-[#FB7D46] text-white text-sm font-bold px-4 py-1 rounded">
    لوحة التحكم
  </span>
</div>
  <!-- المحتوى -->
  <div class="p-8 flex flex-col justify-between flex-1 text-right">
    <div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">
        لوحة تعلم شخصية
      </h3>
      <p class="text-gray-600 mb-6">
        تابع تقدّمك واحصل على توصيات مخصّصة لمسارك التعليمي
      </p>
    </div>
    <a
      href="#"
      class="text-right flex items-center justify-end
             bg-[#FB7D46]
             w-max px-6 py-2.5
             cursor-pointer
             border-2 border-[#FB7D46] text-white ml-auto rounded-lg"
    >
      استكشف
    </a>
  </div>
</div>
<!-- الكارت 2 -->
<div
  class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden max-w-sm mx-auto flex flex-col"
>
  <!-- الصورة -->
<div class="h-56 bg-gray-200 flex items-center justify-center relative">
  <img src="../assets/imgs/project.jpg"  salt="المشاريع" class="w-full h-full object-cover" />
  <span class="absolute bottom-[-14px] z-50 right-10 bg-[#FB7D46] text-white text-sm font-bold px-4 py-1 rounded">
  المشاريع
  </span>
</div>
  <!-- المحتوى -->
  <div class="p-8 flex flex-col justify-between flex-1 text-right">
    <div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">
        مشاريع واقعية
      </h3>
      <p class="text-gray-600 mb-6">
        أنشئ تطبيقات عملية تُظهر مهاراتك البرمجية المتنامية
      </p>
    </div>
    <a
      href="#"
      class="text-right flex items-center justify-end
             bg-[#FB7D46]
             w-max px-6 py-2.5
             cursor-pointer
             border-2 border-[#FB7D46] text-white ml-auto rounded-lg"
    >
      عرض المشاريع
    </a>
  </div>
</div>
    <!-- الكارت 3 -->
<div
  class=" bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden max-w-sm mx-auto flex flex-col"
>
  <!-- الصورة -->
<div class="h-56 bg-gray-200 flex items-center justify-center relative">
  <img src="../assets/imgs/team.jpg"  alt="المجتمع" class="w-full h-full object-cover" />
  <span class="absolute bottom-[-14px] z-50 right-10 bg-[#FB7D46] text-white text-sm font-bold px-4 py-1 rounded">
    المجتمع
  </span>
</div>
  <!-- اللابل (المجتمع) -->
  <!-- المحتوى -->
  <div class="p-8 flex flex-col justify-between flex-1 text-right">
    <div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">
        منصة مراجعة الأقران
      </h3>
      <p class="text-gray-600 mb-6">
        تعاون مع زملائك وحسّن مهاراتك من خلال ملاحظات بنّاءة على الكود
      </p>
    </div>
    <a
      href="#"
      class="text-right flex items-center justify-end
             bg-[#FB7D46]
             w-max px-6 py-2.5
             cursor-pointer
             border-2 border-[#FB7D46] text-white ml-auto rounded-lg"
    >
      انضم للمجتمع
    </a>
  </div>
</div>
  </div>
</section>
    <!-- ------------------------- -->
<section class="flex flex-col items-center justify-center h-96 bg-gray-200 text-gray-600 text-4xl font-extrabold">
   تحت الإنشاء والتطوير
  <p class="text-lg text-gray-500 mt-4">هذا القسم لا يزال قيد التطوير وسيتم تحديثه قريبًا.</p>
</section>
<!-- Hero -->
    <section class="py-28 px-8 text-center text-white bg-gradient-to-br from-indigo-600 to-purple-700">
      <div class="max-w-3xl mx-auto">
        <h1 class="text-5xl font-bold mb-6 leading-tight">Transform Your Coding Skills with iSchool</h1>
        <p class="text-lg opacity-90 mb-10">Learn programming through interactive, personalized experiences that take you from beginner to professional. Master coding with hands-on projects and expert guidance.</p>
        <div class="flex gap-4 justify-center">
          <a href="#" class="px-6 py-3 rounded bg-indigo-600 text-white border border-indigo-600 hover:bg-purple-700 transition">Start Learning</a>
          <a href="#" class="px-6 py-3 rounded border border-white text-white hover:bg-white hover:text-indigo-600 transition">Explore Courses</a>
        </div>
      </div>
    </section>
         <!-- Two-column -->
    <section class="py-20 px-8 grid md:grid-cols-2 gap-12 items-center bg-white">
      <div>
        <h2 class="text-3xl font-bold text-indigo-600 mb-4">Learn by Doing</h2>
        <p class="text-gray-600 mb-6">Our platform emphasizes hands-on learning. Practice coding challenges, build real-world projects, and gain skills that matter in the tech industry.</p>
        <a href="#" class="px-5 py-3 rounded bg-indigo-600 text-white border border-indigo-600 hover:bg-purple-700 transition">Start Learning</a>
      </div>
      <div class="rounded-lg overflow-hidden shadow-lg">
        <img src="https://picsum.photos/600/400" alt="Learn by Doing" class="w-full h-auto" />
      </div>
    </section>
    <!-- Cards -->
    <section class="py-20 px-8 bg-gray-50">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold text-indigo-600">Our Courses</h2>
        <p class="text-gray-600">Explore our wide range of programming courses designed for different skill levels</p>
      </div>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="p-6 rounded-lg bg-white shadow hover:-translate-y-1 hover:shadow-lg transition">
          <h3 class="text-lg font-semibold mb-2">Beginner Basics</h3>
          <p class="text-gray-600">Get started with programming fundamentals and build a strong foundation.</p>
        </div>
        <div class="p-6 rounded-lg bg-white shadow hover:-translate-y-1 hover:shadow-lg transition">
          <h3 class="text-lg font-semibold mb-2">Intermediate Projects</h3>
          <p class="text-gray-600">Apply your skills through guided projects that simulate real-world scenarios.</p>
        </div>
        <div class="p-6 rounded-lg bg-white shadow hover:-translate-y-1 hover:shadow-lg transition">
          <h3 class="text-lg font-semibold mb-2">Advanced Topics</h3>
          <p class="text-gray-600">Master complex concepts and prepare for professional development.</p>
        </div>
      </div>
    </section>
    <!-- CTA -->
    <section class="py-20 px-8 text-center text-white bg-gradient-to-r from-indigo-600 to-purple-700">
      <h2 class="text-3xl font-bold mb-4">Ready to Start Your Coding Journey?</h2>
      <p class="mb-8 opacity-90">Join thousands of learners today and take the first step towards becoming a professional programmer.</p>
      <a href="#" class="px-6 py-3 rounded bg-white text-indigo-600 font-semibold hover:bg-gray-100 transition">Sign Up Now</a>
    </section>
    <!-- Testimonials -->
    <section class="py-20 px-8 bg-white">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold text-indigo-600">What Our Students Say</h2>
        <p class="text-gray-600">Real stories from our community of learners</p>
      </div>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="p-6 bg-gray-50 rounded-lg shadow hover:-translate-y-1 hover:shadow-lg transition">
          <p class="mb-4 text-gray-700">"iSchool transformed my career. The interactive learning style kept me engaged and motivated."</p>
          <div class="font-semibold text-indigo-600">Sarah K.</div>
        </div>
        <div class="p-6 bg-gray-50 rounded-lg shadow hover:-translate-y-1 hover:shadow-lg transition">
          <p class="mb-4 text-gray-700">"The community support and real-world projects made all the difference in my learning journey."</p>
          <div class="font-semibold text-indigo-600">James L.</div>
        </div>
        <div class="p-6 bg-gray-50 rounded-lg shadow hover:-translate-y-1 hover:shadow-lg transition">
          <p class="mb-4 text-gray-700">"From beginner to job-ready in months. iSchool is the best investment I've made in myself."</p>
          <div class="font-semibold text-indigo-600">Maria R.</div>
        </div>
      </div>
    </section>
    <!-- Footer -->
    <footer class="py-12 px-8 bg-gray-900 text-gray-300 text-center">
      <div class="mb-4 font-bold text-white">iSchool</div>
      <div class="flex justify-center gap-6 mb-6">
        <a href="#" class="hover:text-white">About</a>
        <a href="#" class="hover:text-white">Careers</a>
        <a href="#" class="hover:text-white">Contact</a>
      </div>
      <div class="text-sm">&copy; 2025 iSchool. All rights reserved.</div>
    </footer>
     <!-- --------------------------------- -->
     <!-- Code Playground Section -->
<section class="py-20 px-16">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
    <!-- النص -->
    <div>
      <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">
        Code Anywhere with Interactive Playground
      </h2>
      <p class="text-lg text-gray-500 mb-8">
        Practice coding instantly in your browser without complex setup. Experiment with multiple programming languages and see results in real-time.
      </p>
      <div class="flex gap-4">
        <a href="#"
          class="px-5 py-2 rounded border border-indigo-600 text-indigo-600 font-medium hover:bg-indigo-600 hover:text-white transition">
          Try Playground
        </a>
        <a href="#"
          class="px-5 py-2 rounded font-medium text-indigo-600 hover:underline">
          Learn More
        </a>
      </div>
    </div>
    <!-- الصورة / Placeholder -->
    <div
      class="rounded-xl bg-gradient-to-br from-gray-200 to-gray-300 h-[400px] flex items-center justify-center text-gray-500 text-lg font-medium">
      Interactive Code Playground
    </div>
  </div>
</section>
    <!-- Skill Tree Section -->
<section class="py-20 px-8 bg-white">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center max-w-6xl mx-auto">
    <!-- Image Placeholder -->
    <div
      class="h-64 md:h-96 bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center text-gray-600 font-semibold rounded-lg shadow-inner"
    >
      Skill Tree Visualization
    </div>
    <!-- Content -->
    <div class="space-y-6">
      <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
        Level Up Your Coding Skills
      </h2>
      <p class="text-lg text-gray-500 leading-relaxed">
        Our gamified skill tree transforms learning into an exciting journey,
        unlocking new programming abilities as you progress.
      </p>
      <div class="flex gap-4">
        <a
          href="#"
          class="px-6 py-3 border-2 border-indigo-600 text-indigo-600 font-medium rounded-lg hover:bg-indigo-50 transition"
        >
          Start Journey
        </a>
        <a
          href="#"
          class="px-6 py-3 bg-indigo-600 text-white font-medium rounded-lg hover:bg-indigo-700 transition"
        >
          Learn More
        </a>
      </div>
    </div>
  </div>
</section>
    <!-- Debugging Arena Section -->
<section class="bg-gray-50 py-20 px-8">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center max-w-6xl mx-auto">
    <!-- Content -->
    <div class="space-y-6">
      <span class="inline-block text-indigo-600 font-semibold uppercase tracking-wide">
        Debug
      </span>
      <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
        Master Problem-Solving in Debugging Arena
      </h2>
      <p class="text-lg text-gray-500 leading-relaxed">
        Sharpen your skills by solving complex coding challenges and learning
        advanced debugging techniques.
      </p>
      <div class="flex gap-4">
        <a
          href="#"
          class="px-6 py-3 border-2 border-indigo-600 text-indigo-600 font-medium rounded-lg hover:bg-indigo-50 transition"
        >
          Enter Arena
        </a>
        <a
          href="#"
          class="px-6 py-3 bg-indigo-600 text-white font-medium rounded-lg hover:bg-indigo-700 transition"
        >
          Learn More
        </a>
      </div>
    </div>
    <!-- Image Placeholder -->
    <div
      class="h-64 md:h-96 bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center text-gray-600 font-semibold rounded-lg shadow-inner"
    >
      Debugging Interface
    </div>
  </div>
</section>
<!-- Growth Resources Section -->
<section class="py-20 px-8 bg-white">
  <!-- Heading -->
  <div class="text-center max-w-3xl mx-auto mb-16">
    <span class="inline-block text-indigo-600 font-semibold uppercase tracking-wide">
      Grow
    </span>
    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mt-2 mb-4">
      Beyond Code Learning
    </h2>
    <p class="text-lg text-gray-500">
      Comprehensive resources to support your professional development
    </p>
  </div>
  <!-- Cards Grid -->
  <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
    <!-- Card 1 -->
    <div
      class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden"
    >
      <div class="p-8">
        <span class="text-indigo-600 font-semibold mb-2 block">Insights</span>
        <h3 class="text-xl font-bold text-gray-900 mb-3">
          Tech Trends and Career Guidance
        </h3>
        <p class="text-gray-500 mb-6">
          Stay updated with latest industry insights and emerging technologies
        </p>
        <a
          href="#"
          class="text-indigo-600 font-medium hover:underline"
        >
          Read More
        </a>
      </div>
      <div
        class="h-48 bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center text-gray-600 font-semibold"
      >
        Tech Insights
      </div>
    </div>
    <!-- Card 2 -->
    <div
      class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden"
    >
      <div class="p-8">
        <span class="text-indigo-600 font-semibold mb-2 block">Mentorship</span>
        <h3 class="text-xl font-bold text-gray-900 mb-3">
          Ask-a-Mentor Live Sessions
        </h3>
        <p class="text-gray-500 mb-6">
          Get expert guidance and answers to your coding questions
        </p>
        <a
          href="#"
          class="text-indigo-600 font-medium hover:underline"
        >
          Join Session
        </a>
      </div>
      <div
        class="h-48 bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center text-gray-600 font-semibold"
      >
        Mentorship Session
      </div>
    </div>
    <!-- Card 3 -->
    <div
      class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden"
    >
      <div class="p-8">
        <span class="text-indigo-600 font-semibold mb-2 block">Community</span>
        <h3 class="text-xl font-bold text-gray-900 mb-3">
          Hackathons and Challenges
        </h3>
        <p class="text-gray-500 mb-6">
          Participate in competitive coding events and enhance your skills
        </p>
        <a
          href="#"
          class="text-indigo-600 font-medium hover:underline"
        >
          Join Challenge
        </a>
      </div>
      <div
        class="h-48 bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center text-gray-600 font-semibold"
      >
        Hackathon Event
      </div>
    </div>
  </div>
</section>
<!-- Portfolio Section -->
<section class="bg-gray-50 py-20 px-8">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center max-w-6xl mx-auto">
    <!-- Image Placeholder -->
    <div
      class="h-64 md:h-96 bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center text-gray-600 font-semibold rounded-lg shadow-inner"
    >
      Portfolio Showcase
    </div>
    <!-- Content -->
    <div class="space-y-6">
      <span class="inline-block text-indigo-600 font-semibold uppercase tracking-wide">
        Portfolio
      </span>
      <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
        Build Your Professional Coding Portfolio
      </h2>
      <p class="text-lg text-gray-500 leading-relaxed">
        Automatically generate a sharable portfolio that showcases your
        programming achievements and projects.
      </p>
      <div class="flex gap-4">
        <a
          href="#"
          class="px-6 py-3 border-2 border-indigo-600 text-indigo-600 font-medium rounded-lg hover:bg-indigo-50 transition"
        >
          Create Portfolio
        </a>
        <a
          href="#"
          class="px-6 py-3 bg-indigo-600 text-white font-medium rounded-lg hover:bg-indigo-700 transition"
        >
          Learn More
        </a>
      </div>
    </div>
  </div>
</section>
<!-- Final CTA Section -->
<section class="bg-gradient-to-r from-indigo-600 to-purple-700 text-white text-center py-20 px-8">
  <div class="max-w-3xl mx-auto space-y-6">
    <h2 class="text-3xl md:text-4xl font-bold">
      Ready to Start Your Coding Journey?
    </h2>
    <p class="text-lg opacity-90">
      Join thousands of learners transforming their careers through our
      comprehensive programming education platform.
    </p>
    <div class="flex flex-col sm:flex-row gap-4 justify-center">
      <a
        href="#"
        class="px-6 py-3 bg-white text-indigo-600 font-medium rounded-lg hover:bg-gray-100 transition"
      >
        Sign Up
      </a>
      <a
        href="#"
        class="px-6 py-3 bg-white/20 border border-white/30 text-white font-medium rounded-lg hover:bg-white/30 transition"
      >
        Explore Free Trial
      </a>
    </div>
  </div>
</section>
<!-- Testimonials Section -->
<section class="bg-gray-50 py-20 px-8">
  <div class="max-w-4xl mx-auto text-center mb-12">
    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
      What Our Learners Say
    </h2>
    <p class="text-lg text-gray-600 mt-4">
      Hear from students who have transformed their careers with iSchool
    </p>
  </div>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
    <!-- Testimonial 1 -->
    <div class="bg-white p-8 rounded-xl shadow-md text-center hover:shadow-lg transition">
      <div class="italic text-gray-700 mb-6">
        "iSchool turned my coding dreams into reality. The structured
        curriculum and supportive community helped me land my first
        developer job in just 6 months!"
      </div>
      <div class="w-16 h-16 rounded-full mx-auto mb-4 bg-gradient-to-r from-indigo-600 to-purple-600 flex items-center justify-center text-white font-bold">
        SJ
      </div>
      <div class="font-semibold text-indigo-600">Sarah Johnson</div>
      <div class="text-sm text-gray-500">Software Engineer, Tech Innovations</div>
    </div>
    <!-- Testimonial 2 -->
    <div class="bg-white p-8 rounded-xl shadow-md text-center hover:shadow-lg transition">
      <div class="italic text-gray-700 mb-6">
        "The interactive learning experience is unmatched. Being able to
        code right in the browser while learning theory made complex
        concepts much easier to grasp."
      </div>
      <div class="w-16 h-16 rounded-full mx-auto mb-4 bg-gradient-to-r from-indigo-600 to-purple-600 flex items-center justify-center text-white font-bold">
        MC
      </div>
      <div class="font-semibold text-indigo-600">Michael Chen</div>
      <div class="text-sm text-gray-500">Web Developer, Digital Solutions</div>
    </div>
    <!-- Testimonial 3 -->
    <div class="bg-white p-8 rounded-xl shadow-md text-center hover:shadow-lg transition">
      <div class="italic text-gray-700 mb-6">
        "A game-changing platform for aspiring programmers. The
        project-based approach gave me the practical skills I needed to
        transition into a tech career."
      </div>
      <div class="w-16 h-16 rounded-full mx-auto mb-4 bg-gradient-to-r from-indigo-600 to-purple-600 flex items-center justify-center text-white font-bold">
        ER
      </div>
      <div class="font-semibold text-indigo-600">Emily Rodriguez</div>
      <div class="text-sm text-gray-500">Data Scientist, Analytics Corp</div>
    </div>
  </div>
</section>
<!-- Footer -->
<footer class="bg-gray-900 text-gray-300 py-12 px-8">
  <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-12 mb-8">
    <!-- Brand -->
    <div>
      <h3 class="text-xl font-bold text-white mb-4">iSchool</h3>
      <p class="mb-4">
        Transforming coding education through interactive, project-based learning.
      </p>
      <div class="mb-4 space-y-2 text-sm">
        <p><strong>Address:</strong> Level 1, 12 Tech Lane, San Francisco CA 94105</p>
        <p><strong>Contact:</strong> 1-800-CODE-EDU | support@ischool.com</p>
      </div>
      <div class="flex gap-3">
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">f</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">t</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">in</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">ig</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">yt</a>
      </div>
    </div>
    <!-- Product Links -->
    <div>
      <h4 class="text-white font-semibold mb-4">Product</h4>
      <ul class="space-y-2">
        <li><a href="#" class="hover:text-white">Courses</a></li>
        <li><a href="#" class="hover:text-white">Features</a></li>
        <li><a href="#" class="hover:text-white">Community</a></li>
        <li><a href="#" class="hover:text-white">Resources</a></li>
        <li><a href="#" class="hover:text-white">About Us</a></li>
      </ul>
    </div>
    <!-- Support Links -->
    <div>
      <h4 class="text-white font-semibold mb-4">Support</h4>
      <ul class="space-y-2">
        <li><a href="#" class="hover:text-white">Careers</a></li>
        <li><a href="#" class="hover:text-white">Blog</a></li>
        <li><a href="#" class="hover:text-white">Events</a></li>
        <li><a href="#" class="hover:text-white">Help Center</a></li>
        <li><a href="#" class="hover:text-white">Contact Support</a></li>
      </ul>
    </div>
  </div>
  <!-- Bottom -->
  <div class="border-t border-gray-700 pt-6 flex flex-col md:flex-row justify-between items-center text-sm text-gray-400 gap-4">
    <p>© 2024 iSchool. All rights reserved.</p>
    <div class="space-x-3">
      <a href="#" class="hover:text-white">Privacy Policy</a> |
      <a href="#" class="hover:text-white">Terms of Service</a> |
      <a href="#" class="hover:text-white">Cookies Settings</a>
    </div>
  </div>
</footer>
  </section>
  </template>
  <script setup>
</script>
