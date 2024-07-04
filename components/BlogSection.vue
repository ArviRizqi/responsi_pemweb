<template>
  <div class="container-fluid py-5 px-5 mx-auto bg-slate-50" id="blog">
        <h1 class="font-semibold">
            Blog.
            <hr class="w-40 h-[2px] mt-0 mb-3 bg-gray-100 border-0 rounded md:my-10 dark:bg-blue-700">
        </h1>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Blog Post 1 -->
            <div class="bg-white p-6 rounded-lg shadow-md border border-gray-100">
                <h2 class="text-2xl font-bold mb-2">Blog Post Title 1</h2>
                <p class="text-gray-700 mb-4">This is a brief summary of the blog post. It should give an overview of the content.</p>
                <a href="#" class="text-blue-500 hover:underline">Read more</a>
            </div>

            <!-- Blog Post 2 -->
            <div class="bg-white p-6 rounded-lg shadow-md border border-gray-100">
                <h2 class="text-2xl font-bold mb-2">Blog Post Title 2</h2>
                <p class="text-gray-700 mb-4">This is a brief summary of the blog post. It should give an overview of the content.</p>
                <a href="#" class="text-blue-500 hover:underline">Read more</a>
            </div>

            <!-- Blog Post 3 -->
            <div class="bg-white p-6 rounded-lg shadow-md border border-gray-100">
                <h2 class="text-2xl font-bold mb-2">Blog Post Title 3</h2>
                <p class="text-gray-700 mb-4">This is a brief summary of the blog post. It should give an overview of the content.</p>
                <a href="#" class="text-blue-500 hover:underline">Read more</a>
            </div>

            <!-- Blog Post 4 -->
            <div class="bg-white p-6 rounded-lg shadow-md border border-gray-100">
                <h2 class="text-2xl font-bold mb-2">Blog Post Title 4</h2>
                <p class="text-gray-700 mb-4">This is a brief summary of the blog post. It should give an overview of the content.</p>
                <a href="#" class="text-blue-500 hover:underline">Read more</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'BlogSection'
}
</script>

<style scoped>


</style>
