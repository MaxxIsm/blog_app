<template>
  <div class="container mx-auto w-1/2 py-8">
    <h3 class="text-3xl font-bold">
      <NuxtLink :to="`/posts/1`"> Title of Post </NuxtLink>
    </h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Date</div>
      <div>&middot;</div>
      <div>Name</div>
    </div>
    <div class="post-content mt-4">
      {{ $route.params.id }} Lorem ipsum dolor sit amet consectetur adipisicing
      elit. Officia repellat, omnis repellendus architecto facere deserunt
      eligendi commodi quasi blanditiis! Ut.
    </div>
  </div>
</template>
