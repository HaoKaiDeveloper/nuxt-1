<!-- 
這條路由是/car/[name]-[id],
其中[name]跟[id]都是動態的，
如果你是[name]、[id]那他們都是必填項目，
/car/toyota-5之類的，
-->
<template>
  <Navbar />
  <div
    class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-3/5"
  >
    <div>
      <CarDetailHero />
    </div>
    <CarDetailAttributes />
    <CarDetailDescription />
    <CarDetailContact />
  </div>
</template>
