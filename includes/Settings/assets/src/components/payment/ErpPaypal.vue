<template>
    <base-layout
        section_id="erp-payment-gateway"
        sub_section_id="paypal"
        :enable_content="true"
    />
</template>

<script>
import BaseLayout from "../layouts/BaseLayout.vue";

export default {
    name: "ErpPaypal",

    components: {
        BaseLayout,
    },
};
</script>
