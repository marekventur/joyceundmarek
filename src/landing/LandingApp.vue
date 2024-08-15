<script setup lang="ts">
  import Header from "../sections/Header.vue";
  import Pullquote from "../sections/Pullquote.vue";
  import DuoResponsive from "../sections/DuoResponsive.vue";
  import Location from "../sections/Location.vue";
  import Day from "../sections/Day.vue";
  import DayLocation from "@/sections/DayLocation.vue";
  import DayGroup from "../sections/DayGroup.vue";
  import DaySection from "../sections/DaySection.vue";
  import LocationSection from "../sections/LocationSection.vue";
  import StickyHeader from "../sections/StickyHeader.vue";
  import Gifts from "../sections/Gifts.vue";
  import GiftsImage from "../sections/GiftsImage.vue";
  import Footer from "../sections/Footer.vue";
  import DressCode from "@/sections/DressCode.vue";
  import DressCodeImage from "@/sections/DressCodeImage.vue";

  import imgCake from '@/assets/cake.png'
  import imgPartyFood from '@/assets/party_food.png'
  import imgDance from '@/assets/dance.png'
  import imgPub from '@/assets/pub.png'
  import imgFood from '@/assets/food.png'
  import imgDrinks from '@/assets/drinks.png'
  import imgDay1 from '@/assets/day1.png'
  import imgDay2 from '@/assets/day2.png'
  import imgClissoldHouse from '@/assets/clissold_house.png'
  

  import { ref } from 'vue';
  

  
</script>

<template>
  <div>
    <Header type="7" />
    <DuoResponsive>
      <Pullquote />
      <Location  type="pub" color="#C8E2FF">
        <LocationSection title="<strong>Hotel Glockenspitze</strong>" address="Im Sportzentrum 2, 57610 Altenkirchen" link="https://maps.app.goo.gl/tZN4esGW6nQRg9h97" />
        <div class="box">
          Wir speisen im Hotelrestaurant <i>Maracana</i>
        </div>
      </Location>
    </DuoResponsive>
    <Day>
      <DayGroup>
        <DaySection :img="imgDrinks" time="18:00 Uhr">
          Ankunft<br />
          Sektempfang
        </DaySection>
        <DaySection :img="imgFood" time="19:00 Uhr">
          Abendessen
        </DaySection>
      </DayGroup>
    </Day>
    <DuoResponsive desktopTopMargin>
      <GiftsImage />
      <Gifts />
    </DuoResponsive>
    <Footer />
    <StickyHeader href="https://docs.google.com/forms/d/e/1FAIpQLSdh3k6dcgNVipJ4PJk-cC--eyeLcJkEi3uuEWUXIrmRDj_ViA/viewform?usp=sf_link" />
    
  </div>
</template>

<style scoped>
 
</style>
