<template>
    <div class="home">
        <HeaderShayna />
        <HeroShayna />
        <WomenShayna />
    </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenShayna from "@/components/WomenShayna.vue";

export default {
    name: "HomeView",
    components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna
},
};
</script>
