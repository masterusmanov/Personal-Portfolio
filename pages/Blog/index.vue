<script setup>
</script>

<template>
    <Backbtn/>
  <section class="flex pb-24">
    <div class="mx-auto mt-10 w-[1200px]">
      <h1 class="text-4xl font-bold">Blog</h1>
      <div class="flex justify-beetwen items-center gap-6 mt-10">
        <div class="w-[30%]">
            <img src="../../public/my_photo.JPG" alt="Blog" class="rounded-xl">
        </div>
        <div class="w-[100%] text-justify p-4 pt-14 border-b border-gray-500">
            <h1 class="font-bold text-2xl pt-5">ABOUTE BLOG</h1>
            <p class="pt-4 text-xl pb-5">I am, Usmanov Elyor Elmuratovich, was born in 1987 in a family of workers. I am married, I have 4 children. I graduated from high school in 1994-2002. In 2002-2005, I graduated from Uchkurgan College of Economics, majoring in "Information Technologies". From 2005 to 2022, I had my own "Radio electronics and computer repair" workshop and worked there. In 2022-2023, I studied in the "Foundation" and "Bootcamp Full-stack (NodeJS+VueJs)" courses at the "Salvation Education" educational center.</p>
            <p class="pt-4 font-bold text-right">{{ new Date().getDay()+18 }}.{{ new Date().getMonth()+1}}.{{new Date().getFullYear()}}</p>
          </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped></style>
