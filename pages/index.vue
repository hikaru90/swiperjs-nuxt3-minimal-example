<script setup>
  import { Swiper, SwiperSlide } from 'swiper/vue';
  import 'swiper/css';

  const onSwiper = (swiper) => {
    console.log(swiper);
  };
  const onSlideChange = () => {
    console.log("slide change");
  };
</script>

<template>
  <div>
    <swiper
    :slides-per-view="1"
    :space-between="50"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    <swiper-slide style="background: aquamarine; height: 200px;">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi obcaecati modi nihil, veniam fugiat aut iusto et accusantium fugit totam!
    </swiper-slide>
    <swiper-slide style="background: green; height: 200px;">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti magnam iure et minima voluptatem sunt voluptatibus nulla quaerat nisi hic excepturi veniam, praesentium quis assumenda harum obcaecati voluptate facere. Magni minus ea optio necessitatibus in soluta incidunt quo veniam, atque facere illum commodi molestias, deleniti id alias labore mollitia corporis temporibus. At, tempore esse, blanditiis dolores sit ab eveniet dolor quis optio facere, natus perspiciatis ducimus! Modi pariatur porro at fugiat harum, eveniet facilis quod ducimus, quas quo quis nobis! Obcaecati non repellat, architecto sunt tenetur illo impedit omnis eligendi! Repellendus asperiores earum maiores architecto rem temporibus, eos tempore atque illo neque, ratione deserunt amet possimus est commodi error voluptatem porro, impedit repudiandae a! Officia accusamus id fugiat ipsum eligendi nisi tenetur cupiditate dignissimos? Assumenda iure reprehenderit ducimus reiciendis distinctio hic a eos eum odit! Magnam tempore, quos voluptates iusto ea repellat hic magni saepe nostrum illum corporis consectetur voluptas perferendis id natus fugiat error, ut deleniti eaque tenetur alias sint odio, impedit facilis! Ipsam ipsum expedita illo quibusdam excepturi minima nulla repudiandae minus dolorum provident? Placeat, mollitia libero odit cumque doloremque ipsam magnam ut nulla rerum! Omnis, et, similique optio a voluptatibus odio esse incidunt error officia laborum fugiat.
    </swiper-slide>
    <swiper-slide style="background: aliceblue; height: 200px;">
      Slide 3
    </swiper-slide>
    ...
  </swiper>
  </div>
</template>
