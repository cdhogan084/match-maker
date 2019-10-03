<template>
    <v-container class="grey lighten-5">
        <MatchItemCard />
    </v-container>
</template>
<script>
import MatchItemCard from "./MatchItemCard";

export default {
    name: "MatchItemsContainer",
    components: {
        MatchItemCard
    },
    data() {
        return;
    }
};
</script>