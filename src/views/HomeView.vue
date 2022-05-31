<template>
    <div class="home">
        <HeaderShayna />
        <HeroShayna />
        <WomenShayna />
        <InstaShayna />
        <PartnerShayna />
    </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenShayna from "@/components/WomenShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";

export default {
    name: "HomeView",
    components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna,
    InstaShayna,
    PartnerShayna
},
};
</script>
