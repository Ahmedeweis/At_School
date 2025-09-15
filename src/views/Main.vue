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
          <h2 class="text-3xl md:text-4xl font-bold text-gray-900">لماذا تتعلّم مع <span class="text-[#FB7D46]"> @سكول
            </span>؟</h2>
          <p class="text-gray-600 mt-4 font-bold">نظام متكامل يساعد الأطفال على التعلم والممارسة والتطور في مهارات
            البرمجة</p>
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
            <p class="text-gray-700 text-sm">تواصل مع مدربين شخصيين متخصصين ف المجال</p>
          </div>
        </div>
      </section>
      <!-- قسم مسار التعلم -->
      <section class="bg-gray-50 py-20 px-8">
        <!-- العنوان -->
        <div class="text-center max-w-3xl mx-auto mb-16">
          <h1 class="text-[#FB7D46] font-semibold uppercase text-4xl tracking-wide">التعلّم</h1>
          <h3 class="text-4xl font-bold text-gray-900 mt-2 mb-4">
            طريقك نحو إتقان البرمجة
          </h3>
          <p class="text-lg text-gray-600">
            اكتشف تجربة تعليمية مصممة لتسريع مهاراتك في البرمجة خطوة بخطوة
          </p>
        </div>
        <!-- الشبكة -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- الكارت 1 -->
          <div
            class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden max-w-sm mx-auto flex flex-col">
            <!-- الصورة -->
            <div class="h-56 bg-gray-200 flex items-center justify-center relative">
              <img src="../assets/imgs/admin.png" alt="لوحة التحكم" class="w-full h-full object-cover" />
              <span
                class="absolute bottom-[-14px] z-50 right-10 bg-[#FB7D46] text-white text-sm font-bold px-4 py-1 rounded">
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
              <a href="#" class="text-right flex items-center justify-end
             bg-[#FB7D46]
             w-max px-6 py-2.5
             cursor-pointer
             border-2 border-[#FB7D46] text-white ml-auto rounded-lg">
                استكشف
              </a>
            </div>
          </div>
          <!-- الكارت 2 -->
          <div
            class="bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden max-w-sm mx-auto flex flex-col">
            <!-- الصورة -->
            <div class="h-56 bg-gray-200 flex items-center justify-center relative">
              <img src="../assets/imgs/project.jpg" salt="المشاريع" class="w-full h-full object-cover" />
              <span
                class="absolute bottom-[-14px] z-50 right-10 bg-[#FB7D46] text-white text-sm font-bold px-4 py-1 rounded">
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
              <a href="#" class="text-right flex items-center justify-end
             bg-[#FB7D46]
             w-max px-6 py-2.5
             cursor-pointer
             border-2 border-[#FB7D46] text-white ml-auto rounded-lg">
                عرض المشاريع
              </a>
            </div>
          </div>
          <!-- الكارت 3 -->
          <div
            class=" bg-white rounded-xl shadow-md hover:shadow-xl transition transform hover:-translate-y-1 overflow-hidden max-w-sm mx-auto flex flex-col">
            <!-- الصورة -->
            <div class="h-56 bg-gray-200 flex items-center justify-center relative">
              <img src="../assets/imgs/team.jpg" alt="المجتمع" class="w-full h-full object-cover" />
              <span
                class="absolute bottom-[-14px] z-50 right-10 bg-[#FB7D46] text-white text-sm font-bold px-4 py-1 rounded">
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
              <a href="#" class="text-right flex items-center justify-end
             bg-[#FB7D46]
             w-max px-6 py-2.5
             cursor-pointer
             border-2 border-[#FB7D46] text-white ml-auto rounded-lg">
                انضم للمجتمع
              </a>
            </div>
          </div>
        </div>
      </section>
<!-- Pricing Section -->
  <section class="py-10 md:py-20 bg-[#EFEFEF]" id="pricing">
    <div class="max-w-[1200px] mx-auto text-center px-4">
      <!-- العنوان -->
      <h2 class="text-3xl md:text-4xl font-bold mb-10">
        خطط تناسب احتياجاتك
      </h2>
<!-- Dropdown مخصص -->
<div class="mb-8 flex justify-center cursor-pointer ">
  <div class="relative w-100 cursor-pointer ">
    <!-- الزر -->
    <button
      @click="isOpen = !isOpen"
      class="w-full  cursor-pointer flex justify-between items-center border border-gray-300 rounded-xl px-4 py-3 text-gray-700 font-medium bg-white shadow-sm hover:shadow-md focus:ring-2 focus:ring-[#FB7D46] transition"
    >
      <span>{{ selectedParent || 'اختر الفئة العمرية' }}</span>
      <svg
        class="w-5 h-5 text-gray-500 transform transition"
        :class="{ 'rotate-180': isOpen }"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
      </svg>
    </button>
    <!-- القائمة -->
    <ul
      v-show="isOpen"
      class="absolute z-10 mt-2 w-full bg-white border border-gray-200 rounded-xl shadow-lg overflow-hidden"
    >
      <li
        v-for="(parent, index) in parentPlans"
        :key="index"
        @click="selectParent(parent.parentTitle)"
        class="px-4 py-3 text-gray-700 hover:bg-[#FB7D46] hover:text-white  transition"
      >
        {{ parent.parentTitle }}
      </li>
    </ul>
  </div>
</div>
      <!-- الكروت -->
<div
  v-if="selectedPlans.length"
  class="grid gap-6 justify-items-center"
  style="grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));"
>
  <div
    v-for="(plan, index) in selectedPlans"
    :key="index"
    dir="rtl"
    class="pricing-card rounded-xl p-6 md:p-8   relative text-gray-800 flex flex-col items-start justify-end transition duration-500 hover:scale-105 shadow-lg"
    :class="[plan.className, { 'overflow-hidden': plan.popular }]"
  >
          <!-- شارة مميزة -->
          <span v-if="plan.popular"
            class="absolute top-2 right-2 bg-[#FB7D46] text-white text-xs font-semibold px-3 py-1 rounded"
            style="
              position: absolute;
              top: -1px;
              right: -3px;
              color: rgb(255, 255, 255);
              font-size: 0.9rem;
              font-weight: 500;
              padding: 5px 10px;
              border-radius: 6px;">
            الأكثر شهرة
          </span>
          <!-- العنوان -->
          <h3 class="text-2xl font-extrabold mb-4" :class="plan.titleColor">
            {{ plan.title }}
          </h3>
          <!-- السعر -->
          <div class="mb-4 flex justify-between items-start pt-2">
            <p class="text-[14px] font-bold text-gray-400 line-through mb-[10px] ">
              {{ plan.oldPrice }}
            </p>
            <p class="text-3xl font-extrabold text-[#FB7D46] pt-1 pr-2">
              {{ plan.price }}
            </p>
          </div>
          <!-- معدل الحصة -->
          <p v-if="plan.rate"
            class="text-[#2D3E50] bg-[#FEEFD6] px-4 py-2 rounded-lg text-sm font-medium mb-4 w-full text-right">
            معدل <span class="font-bold">{{ plan.rate }}</span> لكل حصة
          </p>
          <!-- المدة -->
          <p v-if="plan.duration"
            class="bg-[#E8F5E9] text-green-700 px-4 py-2 rounded-lg text-base font-semibold mb-3 w-full text-right">
            {{ plan.duration }}
          </p>
          <!-- الفئة العمرية -->
          <p v-if="plan.age"
            class="bg-[#E3F2FD] text-blue-700 px-4 py-2 rounded-lg text-base font-semibold mb-6 w-full text-right">
            {{ plan.age }}
          </p>
          <!-- المنهج -->
          <h4 class="font-semibold text-gray-900 mb-3 text-lg">المنهج :</h4>
          <ul class="space-y-3 mb-6 text-gray-700 text-sm leading-6">
            <li v-for="(feature, i) in plan.features" :key="i" class="flex items-start gap-2 text-right">
              <svg class="w-5 h-5 text-green-500 flex-shrink-0" xmlns="http://www.w3.org/2000/svg"
                fill="currentColor" viewBox="0 0 24 24">
                <path
                  d="M21.2928 4.29285L22.7071 5.70706L8.70706 19.7071C8.51952 19.8946 8.26517 20 7.99995 20C7.73474 20 7.48038 19.8946 7.29285 19.7071L0.292847 12.7071L1.70706 11.2928L7.99995 17.5857L21.2928 4.29285Z" />
              </svg>
              {{ feature }}
            </li>
          </ul>
          <!-- زر CTA -->
          <button
            class="w-full bg-[#FB7D46]  cursor-pointer text-white font-bold py-3 px-6 rounded-lg text-lg hover:bg-[#e66a34] transition duration-300">
            أبدأ تجربتك
          </button>
        </div>
      </div>
    </div>
  </section>
  <section class=" py-10 font-sans">
    <!-- Header Section -->
    <div class="text-center pt-10">
        <h1 class="text-2xl md:text-3xl font-bold text-gray-800">
            مسار التعلم الخاص بك
        </h1>
        <p class="text-gray-500 mt-2">
            حدد صف\عمر الطالب لاستكشاف مسار التعلم الموصى به
        </p>
    </div>
  <div class="flex flex-wrap justify-center gap-4 mt-6">
      <button
        v-for="(grade, index) in grades"
        :key="index"
        @click="selectGrade(index)"
        class=" cursor-pointer"
        :class="[
          'px-6 py-2 rounded-full font-medium',
          grade.isActive
            ? 'bg-[#FB7D46] text-white'
            : 'bg-white text-[#FB7D46] border border-gray-200 shadow-sm',
        ]"
      >
        {{ grade.label }}
      </button>
    </div>
    <div class="container mx-auto mt-12 px-4">
      <div
        class="flex flex-col md:flex-row justify-between items-center relative"
      >
        <div
          class="hidden md:block absolute top-1/2 w-full border-t-2 border-dotted border-blue-400 z-0"
        ></div>
        <div
          v-for="(course, index) in courses"
          :key="index"
          class="flex flex-col items-center text-center mb-10 md:mb-0 z-10"
        >
          <div class="w-40 h-60 rounded-lg overflow-hidden shadow-md">
            <img
              :src="course.image"
              :alt="'Course ' + (index + 1)"
              class="w-full h-full object-cover"
            />
          </div>
          <p class="mt-3 font-bold text-gray-700">{{ course.duration }}</p>
          <p class="text-gray-500 text-sm">{{ course.sessions }}</p>
        </div>
      </div>
    </div>
</section>
 <section class="bg-[#EFEFEF] font-sans" dir="rtl">
    <section class="py-12 ">
      <div class="text-center max-w-3xl mx-auto">
        <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-2">
          اكتشف أكثر من <span class="text-[#FB7D46]">60,000+</span> من مشاريع الطلاب
        </h2>
        <p class="text-gray-600 text-sm md:text-base">
          تصفح مشاريع مبرمجي أي سكول الآن في أكثر من عشرين دولة
        </p>
      </div>
      <div
        ref="slider"
        class="flex gap-6 mt-10 overflow-x-scroll scrollbar-hide cursor-grab active:cursor-grabbing"
        @mousedown="startDragging"
        @mouseleave="stopDragging"
        @mouseup="stopDragging"
        @mousemove="moveSlider"
        @touchstart="startDragging"
        @touchend="stopDragging"
        @touchmove="moveSlider"
      >
        <div
          v-for="project in projects"
          :key="project.id"
          class="bg-white rounded-lg shadow-sm overflow-hidden flex flex-col flex-shrink-0 w-64 md:w-80"
        >
          <img :src="project.image" :alt="project.title" class="w-full h-40 object-cover" />
          <div class="p-4">
            <h3 class="text-[#FB7D46] font-semibold text-base mb-1">{{ project.title }}</h3>
            <p class="text-gray-600 text-sm leading-relaxed">{{ project.description }}</p>
          </div>
        </div>
      </div>
      <div class="flex flex-col md:flex-row items-center justify-center gap-4 mt-10">
        <a href="#" class="bg-[#FB7D46] text-white px-6 py-2 rounded-full font-medium hover:bg-[#ffa179] transition">
          تواصل معنا
        </a>
        <a href="#" class="bg-gray-100 text-gray-700 px-6 py-2 rounded-full font-medium hover:bg-gray-200 transition">
          المزيد من المشاريع
        </a>
      </div>
    </section>
  </section>
  <section class="bg-white py-12 px-4 font-sans">
    <div class="text-center mb-10">
      <h2 class="text-3xl font-bold text-gray-800">
        آراء طلابنا
      </h2>
      <p class="text-gray-500 mt-2">
        اكتشف ما يقوله الطلاب وأولياء الأمور عن تجربتهم معنا.
      </p>
    </div>
    <div
      ref="testimonialsSlider"
      class="flex gap-8 overflow-x-scroll scrollbar-hide cursor-grab active:cursor-grabbing pb-8"
      @mousedown="startTestimonialDragging"
      @mouseleave="stopTestimonialDragging"
      @mouseup="stopTestimonialDragging"
      @mousemove="moveTestimonialSlider"
      @touchstart="startTestimonialDragging"
      @touchend="stopTestimonialDragging"
      @touchmove="moveTestimonialSlider"
    >
      <div
        v-for="(testimonial, index) in testimonials"
        :key="index"
        class="flex-shrink-0 bg-white rounded-lg p-6 w-full max-w-sm flex flex-col items-center text-center
               border-t-4 border-[#FB7D46] shadow-lg transform transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl"
      >
        <div class="w-24 h-24 rounded-full overflow-hidden mb-4 border-4 border-[#FB7D46] shadow-lg">
          <img
            :src="testimonial.image"
            :alt="testimonial.name"
            class="w-full h-full object-cover"
          />
        </div>
        <p class="text-gray-800 mb-4 leading-snug font-semibold">
          "{{ testimonial.quote }}"
        </p>
        <div class="w-12 h-1 bg-[#FB7D46] rounded-full mb-3"></div>
        <div class="flex flex-col items-center">
          <p class="font-bold text-xl text-[#FB7D46]">{{ testimonial.name }}</p>
          <p class="text-sm text-[#FB7D46] font-medium mt-1">{{ testimonial.age }}</p>
        </div>
      </div>
    </div>
  </section>
        <!-- Final CTA Section -->
      <section class="bg-[#FB7D46] text-white text-center py-20 px-8">
  <div class="max-w-3xl mx-auto space-y-6">
    <h2 class="text-3xl md:text-4xl font-bold">
      مستعد لبدء رحلتك في البرمجة؟
    </h2>
    <p class="text-lg opacity-90">
      انضم إلى آلاف المتعلمين الذين يغيرون مسارهم المهني من خلال منصتنا التعليمية الشاملة للبرمجة.
    </p>
    <div class="flex flex-col sm:flex-row gap-4 justify-center">
      <a href="#" class="px-6 py-3 bg-white text-[#FB7D46] font-medium rounded-lg hover:bg-gray-100 transition">
        سجل الآن
      </a>
      <a href="#"
        class="px-6 py-3 bg-white/20 border border-white/30 text-white font-medium rounded-lg hover:bg-white/30 transition">
        تجربة مجانية
      </a>
    </div>
  </div>
</section>
<footer class="bg-gray-900 text-gray-300 py-12 px-8">
  <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-12 mb-8 text-right md:text-right" dir="rtl">
    <div>
      <h3 class="text-xl font-bold text-white mb-4">School@</h3>
      <p class="mb-4">
        نُحدث ثورة في تعليم البرمجة من خلال التعلم التفاعلي القائم على المشاريع.
      </p>
      <div class="mb-4 space-y-2 text-sm">
        <p><strong>العنوان:</strong> الدور الأول، 12 تيك لاين، سان فرانسيسكو، كاليفورنيا 94105</p>
        <p><strong>للتواصل:</strong> 1-800-CODE-EDU | support@school.com</p>
      </div>
      <div class="flex gap-3 justify-start md:justify-start">
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">f</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">t</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">in</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">ig</a>
        <a href="#" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center hover:bg-indigo-600 text-white">yt</a>
      </div>
    </div>
    <div class="md:text-right">
      <h4 class="text-white font-semibold mb-4">المنتجات</h4>
      <ul class="space-y-2">
        <li><a href="#" class="hover:text-white">الدورات</a></li>
        <li><a href="#" class="hover:text-white">المميزات</a></li>
        <li><a href="#" class="hover:text-white">المجتمع</a></li>
        <li><a href="#" class="hover:text-white">المصادر</a></li>
        <li><a href="#" class="hover:text-white">عن الشركة</a></li>
      </ul>
    </div>
    <div class="md:text-right">
      <h4 class="text-white font-semibold mb-4">الدعم</h4>
      <ul class="space-y-2">
        <li><a href="#" class="hover:text-white">الوظائف</a></li>
        <li><a href="#" class="hover:text-white">المدونة</a></li>
        <li><a href="#" class="hover:text-white">الفعاليات</a></li>
        <li><a href="#" class="hover:text-white">مركز المساعدة</a></li>
        <li><a href="#" class="hover:text-white">تواصل مع الدعم</a></li>
      </ul>
    </div>
  </div>
  <div class="border-t border-gray-700 pt-6 flex flex-col md:flex-row justify-between items-start text-sm text-gray-400 gap-4" dir="rtl">
    <p>© 2024 iSchool. جميع الحقوق محفوظة.</p>
    <div class="flex flex-col md:flex-row gap-3">
      <a href="#" class="hover:text-white">سياسة الخصوصية</a>
      <p class="hidden md:block">|</p>
      <a href="#" class="hover:text-white">شروط الخدمة</a>
      <p class="hidden md:block">|</p>
      <a href="#" class="hover:text-white">إعدادات ملفات تعريف الارتباط</a>
    </div>
  </div>
</footer>
    </section>
  </template>
<script setup>
import { ref, computed, onMounted } from "vue";
// Define the courses data using ref
const courses = ref([
  {
    image: new URL("../assets/imgs/course/1.webp", import.meta.url).href,
    duration: "3 شهور",
    sessions: "(12 حصة)",
  },
  {
    image: new URL("../assets/imgs/course/2.webp", import.meta.url).href,
    duration: "6 شهور",
    sessions: "(12 حصة)",
  },
  {
    image: new URL("../assets/imgs/course/3.webp", import.meta.url).href,
    duration: "9 شهور",
    sessions: "(12 حصة)",
  },
  {
    image: new URL("../assets/imgs/course/4.webp", import.meta.url).href,
    duration: "12 شهر",
    sessions: "(12 حصة)",
  },
]);
const grades = ref([
  { label: "الصف 11-12", isActive: true },
  { label: "الصف 9-10", isActive: false },
  { label: "الصف 7-8", isActive: false },
  { label: "الصف 5-6", isActive: false },
  { label: "الصف 3-4", isActive: false },
  { label: "الصف 1-2", isActive: false },
]);
const selectGrade = (selectedIndex) => {
  grades.value.forEach((grade, index) => {
    grade.isActive = index === selectedIndex;
  });
};
const parentPlans = ref([
  {
    parentTitle: "الصف الأول والثاني – 6 و 7 سنوات",
    levels: [
      {
        title: "المستوى المبتدئ",
        oldPrice: "5,200 ج.م",
        price: "3,900 ج.م",
        rate: "81 ج.م",
        duration: "3 شهر – 12 حصة لايف",
        age: "6-7 سنوات \\ الصف 1-2",
        features: [
          "تعلم أساسيات الكمبيوتر والبرمجة",
          "أنشطة تفاعلية مرحة",
          "بناء مشاريع بسيطة",
        ],
        className: "pricing-card border border-blue-200",
        titleColor: "text-blue-600",
        priceColor: "text-blue-600",
        popular: false,
      },
      {
        title: "المستوى المتقدم",
        oldPrice: "11,600 ج.م",
        price: "8,800 ج.م",
        rate: "183 ج.م",
        duration: "6 شهر – 24 حصة لايف",
        age: "6-7 سنوات \\ الصف 1-2",
        features: [
          "مفاهيم متقدمة في البرمجة",
          "بناء ألعاب ومشاريع أكبر",
          "تنمية التفكير المنطقي",
        ],
        className: "pricing-card border border-purple-200",
        titleColor: "text-purple-600",
        priceColor: "text-purple-600",
        popular: false,
      },
      {
        title: "المستوى الاحترافي",
        oldPrice: "20,000 ج.م",
        price: "15,800 ج.م",
        rate: "329 ج.م",
        duration: "12 شهر – 48 حصة لايف",
        age: "6-7 سنوات \\ الصف 1-2",
        features: [
          "إتقان البرمجة بالأنشطة العملية",
          "مشاريع احترافية تناسب العمر",
          "حل مشكلات معقدة بالبرمجة",
        ],
        className: "pricing-card border border-orange-200",
        titleColor: "text-[#FB7D46]",
        priceColor: "text-[#FB7D46]",
        popular: true,
      },
    ],
  },
  {
    parentTitle: "الصف الثالث والرابع – 8 و 9 سنوات",
    levels: [
      {
        title: "المستوى المبتدئ",
        oldPrice: "6,500 ج.م",
        price: "4,900 ج.م",
        rate: "102 ج.م",
        duration: "12 شهر – 3 حصة لايف",
        age: "8-9 سنوات \\ الصف 3-4",
        features: [
          "تعلم الأساسيات بخطوات عملية",
          "تصميم مشاريع صغيرة",
          "ألعاب تعليمية ممتعة",
        ],
        className: "pricing-card border border-blue-200",
        titleColor: "text-blue-600",
        priceColor: "text-blue-600",
        popular: false,
      },
      {
        title: "المستوى المتقدم",
        oldPrice: "13,200 ج.م",
        price: "9,900 ج.م",
        rate: "206 ج.م",
        duration: "6 شهر – 24 حصة لايف",
        age: "8-9 سنوات \\ الصف 3-4",
        features: [
          "مفاهيم البرمجة الشيئية",
          "إنشاء ألعاب وبرامج تعليمية",
          "تنمية مهارات التفكير الحسابي",
        ],
        className: "pricing-card border border-purple-200",
        titleColor: "text-purple-600",
        priceColor: "text-purple-600",
        popular: false,
      },
      {
        title: "المستوى الاحترافي",
        oldPrice: "22,000 ج.م",
        price: "16,500 ج.م",
        rate: "344 ج.م",
        duration: "12 شهر – 48 حصة لايف",
        age: "8-9 سنوات \\ الصف 3-4",
        features: [
          "مشاريع واقعية أكبر",
          "إتقان أدوات البرمجة",
          "تدريب على التفكير المنهجي",
        ],
        className: "pricing-card border border-orange-200",
        titleColor: "text-[#FB7D46]",
        priceColor: "text-[#FB7D46]",
        popular: true,
      },
    ],
  },
  {
    parentTitle: "الصف الخامس والسادس – 10 و 11 سنوات",
    levels: [
      {
        title: "المستوى المبتدئ",
        oldPrice: "7,200 ج.م",
        price: "5,500 ج.م",
        rate: "115 ج.م",
        duration: "3 شهر – 12 حصة لايف",
        age: "10-11 سنوات \\ الصف 5-6",
        features: [
          "مدخل إلى البرمجة المتقدمة",
          "تصميم تطبيقات بسيطة",
          "استخدام التفكير المنطقي في المشاريع",
        ],
        className: "pricing-card border border-blue-200",
        titleColor: "text-blue-600",
        priceColor: "text-blue-600",
        popular: false,
      },
      {
        title: "المستوى المتقدم",
        oldPrice: "14,800 ج.م",
        price: "11,000 ج.م",
        rate: "229 ج.م",
        duration: "6 شهر – 24 حصة لايف",
        age: "10-11 سنوات \\ الصف 5-6",
        features: [
          "تعلم الخوارزميات المبسطة",
          "برمجة الألعاب والمشاريع التعليمية",
          "بناء تطبيقات صغيرة عملية",
        ],
        className: "pricing-card border border-purple-200",
        titleColor: "text-purple-600",
        priceColor: "text-purple-600",
        popular: false,
      },
      {
        title: "المستوى الاحترافي",
        oldPrice: "24,000 ج.م",
        price: "18,200 ج.م",
        rate: "379 ج.م",
        duration: "12 شهر – 48 حصة لايف",
        age: "10-11 سنوات \\ الصف 5-6",
        features: [
          "مشاريع متكاملة باستخدام البرمجة",
          "حل تحديات برمجية متقدمة",
          "إعداد الطفل للمراحل الأعلى",
        ],
        className: "pricing-card border border-orange-200",
        titleColor: "text-[#FB7D46]",
        priceColor: "text-[#FB7D46]",
        popular: true,
      },
    ],
  },
  {
    parentTitle: "الصف السابع والثامن – 12 و 13 سنوات",
    levels: [
      {
        title: "المستوى المبتدئ",
        oldPrice: "8,000 ج.م",
        price: "6,000 ج.م",
        rate: "125 ج.م",
        duration: "3 شهر – 12 حصة لايف",
        age: "12-13 سنوات \\ الصف 7-8",
        features: [
          "أساسيات البرمجة بلغة متقدمة",
          "مشاريع متوسطة الحجم",
          "تدريب على حل المشكلات",
        ],
        className: "pricing-card border border-blue-200",
        titleColor: "text-blue-600",
        priceColor: "text-blue-600",
        popular: false,
      },
      {
        title: "المستوى المتقدم",
        oldPrice: "16,000 ج.م",
        price: "12,500 ج.م",
        rate: "260 ج.م",
        duration: "6 شهر – 24 حصة لايف",
        age: "12-13 سنوات \\ الصف 7-8",
        features: [
          "برمجة التطبيقات والألعاب",
          "مفاهيم متقدمة في التفكير الحاسوبي",
          "تطبيقات عملية أكبر",
        ],
        className: "pricing-card border border-purple-200",
        titleColor: "text-purple-600",
        priceColor: "text-purple-600",
        popular: false,
      },
      {
        title: "المستوى الاحترافي",
        oldPrice: "26,000 ج.م",
        price: "20,000 ج.م",
        rate: "417 ج.م",
        duration: "12 شهر – 48 حصة لايف",
        age: "12-13 سنوات \\ الصف 7-8",
        features: [
          "بناء مشاريع معقدة",
          "إتقان أدوات تطوير متقدمة",
          "حل تحديات حقيقية",
        ],
        className: "pricing-card border border-orange-200",
        titleColor: "text-[#FB7D46]",
        priceColor: "text-[#FB7D46]",
        popular: true,
      },
    ],
  },
  {
    parentTitle: "الصف التاسع والعاشر – 14 و 15 سنوات",
    levels: [
      {
        title: "المستوى المبتدئ",
        oldPrice: "9,000 ج.م",
        price: "6,800 ج.م",
        rate: "142 ج.م",
        duration: "3 شهر – 12 حصة لايف",
        age: "14-15 سنوات \\ الصف 9-10",
        features: [
          "البرمجة الأساسية للغات متعددة",
          "مشاريع تطبيقية",
          "بناء مواقع أو تطبيقات بسيطة",
        ],
        className: "pricing-card border border-blue-200",
        titleColor: "text-blue-600",
        priceColor: "text-blue-600",
        popular: false,
      },
      {
        title: "المستوى المتقدم",
        oldPrice: "18,000 ج.م",
        price: "14,000 ج.م",
        rate: "292 ج.م",
        duration: "6 شهر – 24 حصة لايف",
        age: "14-15 سنوات \\ الصف 9-10",
        features: [
          "تصميم وبرمجة تطبيقات أكبر",
          "فهم هياكل البيانات المبسطة",
          "مشاريع عملية متقدمة",
        ],
        className: "pricing-card border border-purple-200",
        titleColor: "text-purple-600",
        priceColor: "text-purple-600",
        popular: false,
      },
      {
        title: "المستوى الاحترافي",
        oldPrice: "28,000 ج.م",
        price: "22,000 ج.م",
        rate: "458 ج.م",
        duration: "12 شهر – 48 حصة لايف",
        age: "14-15 سنوات \\ الصف 9-10",
        features: [
          "مشاريع برمجية احترافية",
          "تطبيقات كاملة من البداية للنهاية",
          "تدريب على منهجية التفكير المتقدم",
        ],
        className: "pricing-card border border-orange-200",
        titleColor: "text-[#FB7D46]",
        priceColor: "text-[#FB7D46]",
        popular: true,
      },
    ],
  },
  {
    parentTitle: "الصف الحادي عشر والثاني عشر – 16 و 17 سنوات",
    levels: [
      {
        title: "المستوى المبتدئ",
        oldPrice: "10,000 ج.م",
        price: "7,500 ج.م",
        rate: "156 ج.م",
        duration: "3 شهر – 12 حصة لايف",
        age: "16-17 سنوات \\ الصف 11-12",
        features: [
          "تعلم لغة برمجة رئيسية بعمق",
          "مشاريع متوسطة – تطبيقات أو مواقع",
          "مهارات تفكير برمجي متقدم",
        ],
        className: "pricing-card border border-blue-200",
        titleColor: "text-blue-600",
        priceColor: "text-blue-600",
        popular: false,
      },
      {
        title: "المستوى المتقدم",
        oldPrice: "20,000 ج.م",
        price: "15,000 ج.م",
        rate: "313 ج.م",
        duration: "6 شهر – 12 حصة لايف",
        age: "16-17 سنوات \\ الصف 11-12",
        features: [
          "مشاريع متقدمة متعددة التخصصات",
          "فهم مفاهيم متقدمة في علوم الكمبيوتر",
          "حل مسائل برمجية أعقد",
        ],
        className: "pricing-card border border-purple-200",
        titleColor: "text-purple-600",
        priceColor: "text-purple-600",
        popular: false,
      },
      {
        title: "المستوى الاحترافي",
        oldPrice: "30,000 ج.م",
        price: "23,000 ج.م",
        rate: "479 ج.م",
        duration: "12 شهر – 48 حصة لايف",
        age: "16-17 سنوات \\ الصف 11-12",
        features: [
          "مشاريع برمجية شاملة",
          "استخدام أدوات برمجة احترافية",
          "تجهيز للجامعة أو سوق العمل",
        ],
        className: "pricing-card border border-orange-200",
        titleColor: "text-[#FB7D46]",
        priceColor: "text-[#FB7D46]",
        popular: true,
      },
    ],
  },
]);
const selectedParent = ref(parentPlans.value[0].parentTitle); // أول اختيار افتراضي
// بعد الـ onMounted نحط أول اختيار افتراضي
onMounted(() => {
  if (parentPlans.value.length > 0) {
    selectedParent.value = parentPlans.value[0].parentTitle;
  }
});
// computed: رجّع الـ plans الخاصة بالاختيار الحالي
const selectedPlans = computed(() => {
  const parent = parentPlans.value.find(
    (p) => p.parentTitle === selectedParent.value
  );
  return parent ? parent.levels : [];
});
const isOpen = ref(false);
function selectParent(title) {
  selectedParent.value = title;
  isOpen.value = false;
}
// ---------------------------------
const projects = ref([
  { id: 1, image: new URL('../assets/imgs/projects/1.webp', import.meta.url).href, title: 'سيارات القيادة الذاتية', description: 'باستخدام تقنية الرؤية الحاسوبية ودورة للأطفال، تعلم كيفية Python برمجة لإنشاء سيارات تقود نفسها' },
  { id: 2, image: new URL('../assets/imgs/projects/2.webp', import.meta.url).href, title: 'هروب هاجريد', description: 'ساعد هاجريد في الهروب من العوائق في هذه اللعبة ثلاثية الأبعاد التي ستقوم بإنشائها خلال دورة تطوير الألعاب للأطفال' },
  { id: 3, image: new URL('../assets/imgs/projects/3.webp', import.meta.url).href, title: 'دوار الأصبع', description: 'ابنِ دوار الأصابع الرقمي باستخدام لغة Python البصرية البرمجية.' },
  { id: 4, image: new URL('../assets/imgs/projects/4.webp', import.meta.url).href, title: 'صائد البوكيمون', description: 'اصطياد البوكيمون في بيئة ماين كرافت' },
  { id: 5, image: new URL('../assets/imgs/projects/1.webp', import.meta.url).href, title: 'الدرون', description: 'طُر في بيئة ثلاثية الأبعاد مذهلة مع ألعاب ثلاثية الأبعاد خاصة بك' },
  { id: 6, image: new URL('../assets/imgs/projects/2.webp', import.meta.url).href, title: 'مشروع 6', description: 'وصف المشروع السادس.' },
  { id: 7, image: new URL('../assets/imgs/projects/3.webp', import.meta.url).href, title: 'مشروع 7', description: 'وصف المشروع السابع.' },
  { id: 8, image: new URL('../assets/imgs/projects/4.webp', import.meta.url).href, title: 'مشروع 8', description: 'وصف المشروع الثامن.' },
]);
const slider = ref(null);
const isDown = ref(false);
const startX = ref(0);
const scrollLeft = ref(0);
const startDragging = (e) => {
  isDown.value = true;
  startX.value = e.pageX || e.touches[0].pageX - slider.value.offsetLeft;
  scrollLeft.value = slider.value.scrollLeft;
};
const stopDragging = () => {
  isDown.value = false;
};
const moveSlider = (e) => {
  if (!isDown.value) return;
  e.preventDefault();
  const x = e.pageX || e.touches[0].pageX - slider.value.offsetLeft;
  const walk = (x - startX.value) * 1.5; // Multiplier for faster scroll
  slider.value.scrollLeft = scrollLeft.value - walk;
};
// -------------------------------------------------
const testimonials = ref([
  {
    image: new URL('../assets/imgs/students/1.jpg', import.meta.url).href,
    quote: 'كانت تجربة رائعة! تعلمت الكثير في وقت قصير. المنهج سهل الفهم والمعلمون رائعون.',
    name: 'أحمد',
    age: '12 سنة'
  },
  {
    image: new URL('../assets/imgs/students/2.jpg', import.meta.url).href,
    quote: 'أحببت التحديات والمشاريع! أصبحت الآن أستطيع بناء ألعابي الخاصة. شكراً أي سكول!',
    name: 'ليلى',
    age: '10 سنوات'
  },
  {
    image: new URL('../assets/imgs/students/3.jpg', import.meta.url).href,
    quote: 'برمجة الروبوتات كانت ممتعة جداً. لم أكن أتخيل أنني سأفعل ذلك يوماً ما.',
    name: 'محمد',
    age: '14 سنة'
  },
  {
    image: new URL('../assets/imgs/students/4.jpg', import.meta.url).href,
    quote: 'المعسكر الصيفي كان الأفضل على الإطلاق! تعلمت البرمجة وكونت صداقات جديدة.',
    name: 'سارة',
    age: '11 سنة'
  },
  {
    image: new URL('../assets/imgs/students/5.jpg', import.meta.url).href,
    quote: 'بفضل أي سكول، أصبحت الآن أشارك في مسابقات البرمجة. هذا الشعور لا يُوصف!',
    name: 'يوسف',
    age: '15 سنة'
  },
  {
    image: new URL('../assets/imgs/students/6.jpg', import.meta.url).href,
    quote: 'فهمت أخيرًا أساسيات الذكاء الاصطناعي بطريقة بسيطة وممتعة.',
    name: 'فاطمة',
    age: '13 سنة'
  },
  {
    image: new URL('../assets/imgs/students/7.jpg', import.meta.url).href,
    quote: 'الدروس كانت منظمة جدًا وسهلة المتابعة. أنصح بها كل من يريد تعلم البرمجة.',
    name: 'علي',
    age: '9 سنوات'
  },
  {
    image: new URL('../assets/imgs/students/8.jpg', import.meta.url).href,
    quote: 'أكثر ما أعجبني هو تطبيق المشاريع العملية. شعرت أنني أصبحت مبرمجًا حقيقيًا.',
    name: 'نور',
    age: '16 سنة'
  }
]);
// المتغيرات
const testimonialsSlider = ref(null);
const isTestimonialDragging = ref(false);
const testimonialDragStartX = ref(0);
const testimonialInitialScrollLeft = ref(0);
// الدوال
const startTestimonialDragging = (e) => {
  isTestimonialDragging.value = true;
  testimonialDragStartX.value = e.pageX || e.touches[0].pageX;
  testimonialInitialScrollLeft.value = testimonialsSlider.value.scrollLeft;
};
const stopTestimonialDragging = () => {
  isTestimonialDragging.value = false;
};
const moveTestimonialSlider = (e) => {
  if (!isTestimonialDragging.value) return;
  e.preventDefault();
  const x = e.pageX || e.touches[0].pageX;
  const walk = (x - testimonialDragStartX.value) * 1.5;
  testimonialsSlider.value.scrollLeft = testimonialInitialScrollLeft.value - walk;
};
</script>
<style scoped>
.pricing-card {
  width: 98%;
  height: max-content;
  text-align: left;
  position: relative;
  color: #333;
  /* غامق مناسب للثيم الفاتح */
  display: flex;
  flex-direction: column;
  align-items: start;
  justify-content: flex-end;
  background: linear-gradient(149deg, #fff7f3 6.96%, #ffe5d6 40.17%, #ffffff 73.39%);
  border-radius: 15px;
  padding: 30px 20px;
  transition: 0.6s;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
}
.pricing-card {
  background: linear-gradient(149deg, #FFF7F3 6.96%, #FFEDE6 40.17%, #FFFFFF 73.39%);
  color: #333;
  border: 1px solid #f5d0b5;
}
/* Standard Card */
.pricing-card.standard {
  background: linear-gradient(149deg, #FFF3E8 6.96%, #FFE1CC 40.17%, #FFFFFF 73.39%);
  border: 1px solid #FB7D46;
  position: relative;
  overflow: hidden;
}
.pricing-card.standard::after {
  content: 'Most Popular';
  position: absolute;
  top: -1px;
  right: -3px;
  background: #FB7D46;
  color: #fff;
  font-size: 0.9rem;
  font-weight: 600;
  padding: 5px 10px;
  border-radius: 6px;
}
/* Premium Card */
.pricing-card.premium {
  background: linear-gradient(149deg, #FFF9F5 6.96%, #FFE6DD 40.17%, #FFFFFF 73.39%);
  border: 1px solid #f3c9b7;
}
.scrollbar-hide::-webkit-scrollbar {
  display: none;
}
/* لإخفاء شريط التمرير في Firefox */
.scrollbar-hide {
  scrollbar-width: none;
}
</style>
