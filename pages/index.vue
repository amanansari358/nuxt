<template>
  <div>
    <section class="bg-green-700">
      <div class="container mx-auto text-4xl px-20 py-10">
        <!-- nav bar -->
        <div class="flex text-white justify-between">
          <a href>Realstore</a>
          <div class="flex gap-8">
            <a href>Home</a>
            <a href>Product</a>
          </div>
          <a href>Login</a>
          <!-- nav nbar end -->
        </div>
      </div>
    </section>

    <!-- Hero Section Start -->
    <section>
      <div
        class="container mx-auto px-20 py-10 text-white-400 flex justify-between items-center"
      >
        <div>
          <img
            class="h-[500px]"
            src="../assets/img/download__3_-removebg-preview (1).png "
            alt
          />
        </div>

        <div class="display-flex justify-between gap-50px">
          <div>
            <h1 class="text-black text-5xl padding- down-20px">
              NO.STORE IN THE WORLD !
            </h1>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fuga,
            aliquam.
          </p>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
        </div>
        <div
          class="items-starts py-2 px-5 bg-violet-800 text-white font-semibold rounded-full shadow-md hover:bg-violet-700 focus:outline-none focus:ring focus:ring-violet-400 focus:ring-opacity-75"
        >
          <button>Explore</button>
        </div>
      </div>
    </section>
    <!-- Hero Section ENd  -->
    <!-- popular product section -->
    <!-- products -->
    <div class="bg-green-100 px-14">
      <div>
        <h1 class="text-center text-2xl pt-5">POPULAR PRODUCTS</h1>
      </div>

      <div class="gap-3 pt-16 grid grid-cols-5">
        <div class="bg-white h-auto w-48 mb-20 pl-3 py-5 rounded-lg shadow-xl">
          <img
            class="h-64"
            src="https://m.media-amazon.com/images/I/411BWLkycpL._AC_UY1000_.jpg"
            alt
          />
          <h1>
            <b>School bag</b>
          </h1>
          <p>Price: $ 109.95</p>
          <nuxt-link class="text-green-700" to>View details</nuxt-link>
        </div>

        <div class="bg-white h-80 w-48 mb-20 pl-3 py-3 rounded-lg shadow-xl">
          <img
            class="h-56"
            src="https://png.pngtree.com/png-vector/20230902/ourmid/pngtree-white-t-shirt-mockup-realistic-t-shirt-png-image_9906363.png"
            alt
          />
          <h1>
            <b>White T-shirt</b>
          </h1>
          <p>Price: $ 175.95</p>
          <nuxt-link class="text-green-700" to>View details</nuxt-link>
        </div>

        <div class="bg-white h-72 w-48 mb-20 pl-3 py-3 rounded-lg shadow-xl">
          <img
            class="h-48"
            src="https://down-ph.img.susercontent.com/file/b12509df5340bbd6bcfffa2ad48f3110"
            alt
          />
          <h1>
            <b>Winter Jacket</b>
          </h1>
          <p>Price: $ 120.95</p>
          <nuxt-link class="text-green-700" to>View details</nuxt-link>
        </div>

        <div class="bg-white h-80 w-48 mb-20 pl-3 py-3 rounded-lg shadow-xl">
          <img
            class="h-56"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQiy6kCSpBas8iHz6XaF3kb-WzF8Ktx80HM5w&s"
            alt
          />
          <h1>
            <b>Denim jacket</b>
          </h1>
          <p>Price: $ 275.95</p>
          <nuxt-link class="text-green-700" to>View details</nuxt-link>
        </div>

        <div class="bg-white h-auto w-48 mb-20 pl-3 py-5 rounded-lg shadow-xl">
          <img
            class="h-64"
            src="https://i5.walmartimages.com/seo/Pandora-Moments-Silver-Bracelet-with-Heart-Clasp_072455f9-f2e5-48b2-a289-63d0f3b76770_1.f502a209ece723d1d2cb6394289dc760.jpeg"
            alt
          />
          <h1>
            <b>Pandora braclet</b>
          </h1>
          <p>Price: $ 398.95</p>
          <nuxt-link class="text-green-700" to>View details</nuxt-link>
        </div>
      </div>
    </div>

    <!-- popular product section end -->
 
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
