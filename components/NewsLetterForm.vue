/* eslint-disable */
<template>
  <div>
   Twitter: @FurNews<br>TikTock: @FurNews
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: ''
    }
  },
  computed: {
    formAction() {
      if (this.$siteConfig.newsletter.mailchimp.on) {
        return this.$siteConfig.newsletter.mailchimp.formAction
      }
      return this.$siteConfig.newsletter.custom.formAction
    }
  }
}
</script>
/* eslint-disable */
