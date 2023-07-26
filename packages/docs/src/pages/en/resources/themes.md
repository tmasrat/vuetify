---
meta:
  nav: Vuetify Themes
  title: Free & Premium Vuetify themes
  description: Vuetify offers numerous pre-build starter and premium themes. Kickstart your next application today, no design skills needed.
  keywords: vuetify themes, pre-built material themes, premium themes
related:
  - /getting-started/installation/
  - /features/blueprints/
  - /features/theme/
---

<script setup>
  // Components
  import ThemeVendor from '@/components/doc/ThemeVendor.vue'

  // Utilities
  import { onMounted } from 'vue'

  // Stores
  import { useShopifyStore } from '@/store/shopify'

  const store = useShopifyStore()

  onMounted(() => {
    store.fetch()
  })
</script>

# Vuetify Themes

Vuetify offers both **free** and **premium** pre-made themes designed to get you started in a flash. Free themes are available to install through Vue CLI or you can simply download the source.

---

## Vuetify

The following themes are created and maintained by Vuetify. They are available for free through the Vuetify store.

<ThemeVendor name="Vuetify" />

----

<br>

## Theme Selection

Theme Selection offers an array of visually appealing, user-friendly UI kits and themes. Catering to a variety of platforms, they deliver efficient design solutions for a streamlined digital experience.

<ThemeVendor name="ThemeSelection" />

<br>

::: success

Want to feature your themes here? [Contact us!](mailto:hello@vuetifyjs.com?subject=Theme+affiliation) to learn more about becoming a vendor.

:::
