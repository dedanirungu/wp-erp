<template>
    <base-layout
        section_id="erp-payment-gateway"
        sub_section_id="stripe"
        :enable_content="true"
    />
</template>

<script>
import BaseLayout from "../layouts/BaseLayout.vue";

export default {
    name: "ErpStripe",

    components: {
        BaseLayout,
    },
};
</script>
