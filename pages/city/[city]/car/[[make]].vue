<!-- /city/:city/car/:make
    /city是固定的,
    /city/:city，其中的:city是動態，如果需要接續/car那就是必填的,
    /car是固定的,
    /:make，看起來是動態的，但他的檔案結構是[[make]]].vue，這樣代表可以填也可以不填，是非必要填的路由
    也就是說這條路徑，
    /city/abcd/car可以
    /city/abcd/car/2345也可以
     -->
<template>
  <div>
    <Navbar />
    <div
      class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-3/5"
    >
      <div class="mt-32 flex">
        <CarSideBar />
        <CarCards />
      </div>
    </div>
  </div>
</template>
