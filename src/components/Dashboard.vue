<script setup>

</script>

<template>
  <main class="flex items-center justify-center px-4 py-8 grow">
    <div>

      <div class="flex justify-center mb-6">
        <div class="flex px-8 py-4 border rounded-lg gap-6"> <!-- main location -->
          <div>
            <div class="relative block w-32 h-32 border rounded-full rotate-[114deg]"> <!-- wind direction -->
              <div class="absolute inline-block border-[10px] border-transparent border-t-[4rem] border-t-slate-500 top-1/2 left-1/2 -translate-x-1/2 -translate-y-3/4"></div>
            </div>
          </div>
          <div class="flex flex-col text-left gap-5">
            <div> <!-- title -->
              <span>Локация 0</span>
            </div>
            <div class="flex flex-col text-sm italic text-slate-500 gap-1"> <!-- text data -->
              <span>+24&deg;</span>
              <span>747 мм рт. ст.</span>
              <span>2.4 м/с (114&deg;)</span>
            </div>
          </div>
        </div>
      </div>

      <div class="justify-center place-content-center grid grid-cols-3 gap-4">

        <div class="flex px-4 py-4 border rounded-lg gap-4"> <!-- location -->
          <div>
            <div class="relative block w-20 h-20 border rounded-full rotate-[214deg]">
              <div class="absolute inline-block border-[6px] border-transparent border-t-[2.5rem] border-t-slate-500 top-1/2 left-1/2 -translate-x-1/2 -translate-y-3/4"></div>
            </div>
          </div>
          <div class="flex flex-col text-left gap-2">
            <div>
              <span>Локация 1</span>
            </div>
            <div class="flex flex-col text-sm italic text-slate-500 gap-1">
              <span>1.8 м/c</span>
              <span>(214&deg;)</span>
            </div>
          </div>
        </div>

        <div class="flex px-4 py-4 border rounded-lg gap-4"> <!-- location -->
          <div>
            <div class="relative block w-20 h-20 border rounded-full rotate-[14deg]">
              <div class="absolute inline-block border-[6px] border-transparent border-t-[2.5rem] border-t-slate-500 top-1/2 left-1/2 -translate-x-1/2 -translate-y-3/4"></div>
            </div>
          </div>
          <div class="flex flex-col text-left gap-2">
            <div>
              <span>Локация 2</span>
            </div>
            <div class="flex flex-col text-sm italic text-slate-500 gap-1">
              <span>3.9 м/c</span>
              <span>(14&deg;)</span>
            </div>
          </div>
        </div>

        <div class="flex px-4 py-4 border rounded-lg gap-4"> <!-- location -->
          <div>
            <div class="relative block w-20 h-20 border rounded-full rotate-[301deg]">
              <div class="absolute inline-block border-[6px] border-transparent border-t-[2.5rem] border-t-slate-500 top-1/2 left-1/2 -translate-x-1/2 -translate-y-3/4"></div>
            </div>
          </div>
          <div class="flex flex-col text-left gap-2">
            <div>
              <span>Локация 3</span>
            </div>
            <div class="flex flex-col text-sm italic text-slate-500 gap-1">
              <span>0.4 м/c</span>
              <span>(301&deg;)</span>
            </div>
          </div>
        </div>

        <div class="flex px-4 py-4 border rounded-lg gap-4"> <!-- location -->
          <div>
            <div class="relative block w-20 h-20 border rounded-full rotate-[251deg]">
              <div class="absolute inline-block border-[6px] border-transparent border-t-[2.5rem] border-t-slate-500 top-1/2 left-1/2 -translate-x-1/2 -translate-y-3/4"></div>
            </div>
          </div>
          <div class="flex flex-col text-left gap-2">
            <div>
              <span>Локация 4</span>
            </div>
            <div class="flex flex-col text-sm italic text-slate-500 gap-1">
              <span>5.1 м/c</span>
              <span>(251&deg;)</span>
            </div>
          </div>
        </div>

        <div class="flex px-4 py-4 border rounded-lg gap-4"> <!-- location -->
          <div>
            <div class="relative block w-20 h-20 border rounded-full rotate-[47deg]">
              <div class="absolute inline-block border-[6px] border-transparent border-t-[2.5rem] border-t-slate-500 top-1/2 left-1/2 -translate-x-1/2 -translate-y-3/4"></div>
            </div>
          </div>
          <div class="flex flex-col text-left gap-2">
            <div>
              <span>Локация 5</span>
            </div>
            <div class="flex flex-col text-sm italic text-slate-500 gap-1">
              <span>2.4 м/c</span>
              <span>(47&deg;)</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </main>
</template>
