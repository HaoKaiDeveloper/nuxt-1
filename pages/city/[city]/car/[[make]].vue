<!-- /city/:city/car/:make
    /city是固定的,
    /city/:city，其中的:city是動態的變數,
    /car是固定的,
    /:make，看起來是動態的，但他的檔案結構是[[make]]].vue，這樣代表可以填也可以不填，是非必要填的路由
    也就是說這條路徑，
    /city/abcd/car可以
    /city/abcd/car/2345也可以
    /city/abcd，不行
     -->
<template>
  <div>
      <CarCards /> 
  </div>
</template>
