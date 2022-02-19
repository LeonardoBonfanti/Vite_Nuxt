<template>
    <v-row justify="end">
        <div style="padding-left: 50px">
            <VuetifyLogo :_size='30'/>
        </div>
        <v-spacer />
        <NuxtLink to="/">
            <span class="header_items">{{ $t('OUTSET') }}</span>
        </NuxtLink>
        <v-separator />
        <NuxtLink to="/why">
            <span class="header_items">{{ $t('WHY') }}</span>
        </NuxtLink>
        <NuxtLink to="/partner">
            <span class="header_items">{{ $t('BECOME_PARTNER') }}</span>
        </NuxtLink>
        <NuxtLink to="/esg">
            <span class="header_items">{{ $t('ESG') }}</span>
        </NuxtLink>
        <NuxtLink to="/contact">
            <span class="header_items">{{ $t('CONTACT') }}</span>
        </NuxtLink>
        <NuxtLink to="/login">
            <span class="header_items">{{ $t('LOGIN') }}</span>
        </NuxtLink>
    </v-row>
</template>

<script>
    import VuetifyLogo from "./VuetifyLogo.vue";

    export default {
        name: 'Header',
        components: { VuetifyLogo }
    }
</script>

<style scoped>
    .header_items {
        padding: 10px;
    }
</style>