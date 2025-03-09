Create any layout in Tailwind CSS (Tutorial 1)

https://www.youtube.com/watch?v=eiRcOPiNoDs

Source Code

<!--<div class="grid gap-4 m-4 sm:grid-cols-2">
  <div class="bg-orange-500 rounded shadow-xl min-h-[100px]"></div>
  <div class="bg-teal-500 rounded shadow-xl min-h-[100px]"></div>
</div>-->

<!--<div class="m-4 grid gap-4 sm:grid-cols-4">
  <div class="min-h-[100px] rounded bg-orange-500 shadow-xl"></div>
  <div class="min-h-[100px] rounded bg-teal-500 shadow-xl"></div>
  <div class="min-h-[100px] rounded bg-red-500 shadow-xl"></div>
</div>-->

<!--<div class="m-4 grid gap-4 sm:grid-cols-12">
  <div class="sm:col-span-2 min-h-[100px] rounded bg-orange-500 shadow-xl"></div>
  <div class="sm:col-span-10 min-h-[100px] rounded bg-teal-500 shadow-xl"></div>
</div>-->


<div class="m-4 grid gap-4 sm:grid-cols-12">
  <div class="sm:col-span-2 hidden sm:block min-h-[100px] rounded bg-orange-500 shadow-xl"></div>
  <div class="sm:col-span-8 min-h-[100px] rounded bg-teal-500 shadow-xl"></div>
  <div class="sm:col-span-2 hidden sm:block min-h-[100px] rounded bg-red-500 shadow-xl"></div>
</div>
