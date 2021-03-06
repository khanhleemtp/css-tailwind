# css-tailwind

==================What is Tailwind CSS ? ========================================

- CSS framework made up for utility classes
- Much lower-level than Boostrap, Materialize etc

==================How Tailwind Works ?============================================
- styles.css => Tailwind => styles.css ---------- index.html
- src file ----------------> public file

===============================Fonts,Colors =======================================
- font-bold, font-semibold
- text-gray-700, text-6xl
- upppercase

===============================Padding, Margin, Borders=============================
- px-4 py-4 pl- pr- pb- pt- p
- mt-8 ml- mr- mb- mx- my- m
- border-gray-200 border-b-1 

===========================Tailwind Config =========================================
- npx tailwind init --full
- npx tailwind init
- npm run build-css
- bg-secondary-100

============================Custom Fonts ==========================================
- font-mono
- font-serif
- font-sans(default)

===========================Using FlexBox ==========================================
- flex justify-end
- flex items-end

===========================Responsive Classes=====================================
- (min-width: 640px) sm:
- (min-width: 768px) md:
- (min-width: 1024px) lg:
- (min-width: 1280px) xl:

==========================Cards==================================================
- bg-white rounded overflow-hidden shadow-md
- w-full h-32 sm:h-48 object-cover: Zoom hình ảnh theo chiều dài
- block text-gray-500 text-sm

===========================Badges================================================
- relative
- absolute top 0
===========================Apply==================================================
- .card{
    @apply bg-white rounded overflow-hidden shadow-md relative;
}
==========================Grids===================================================
- grid grid-cols-3 gap-10
 + col-span-2
 + col-span-1

=========================Button====================================================
- tracking-wider: Khoảng cách các từ

======================================Icon========================================
- heroicons.dev
- w-5 inline-block

===========================Hover Effect===========================================
- hover:shadow-inner
- hover:shadow-lg
- hover:text-gray-700

=============================Responsive Nav=======================================
- JS
=============================Transtion ===========================================
- transform hover:scale-125 hover:bg-opacity-50 transition ease-out duration-200 