<template>
  <div class="post-container py-8">
    <h3 class="text-3xl font-bold">
      <NuxtLink :to="`/posts/1`"> Title of Post </NuxtLink>
    </h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Date</div>
      <div>&middot;</div>
      <div>Name</div>
    </div>
    <div class="post-preview leading-relaxed mt-4">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem, distinctio
      numquam! Maxime amet soluta eaque error saepe quasi sequi modi!
    </div>
    <div class="mt-4">
      <NuxtLink
        :to="`/posts/1`"
        class="bg-blue-700 hover:bg-blue-800 text-white rounded inline-block px-4 py-2"
      >
        Read more
      </NuxtLink>
    </div>
  </div>
</template>
