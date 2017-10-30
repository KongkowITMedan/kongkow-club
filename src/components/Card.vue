<template>
  <div class="card">
    <header class="card-header">
      <a :href="link" class="card-header-title" target="_blank">
        <i :class="`fa ${icon}`"></i> &nbsp; {{ title }}
      </a>
      <a :href="link" class="card-header-icon" target="_blank">
        <span class="icon">
          <i class="fa fa-external-link"></i>
        </span>
      </a>
    </header>
    <div v-if="content" class="card-content">
      <div class="content"> {{ content }} </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'card',

  props: {
    title: String,
    content: String,
    icon: String,
    link: {
      type: String,
      Default: '#'
    }
  }
}
</script>

<style lang="sass" scoped>
  .card
    transition: 0.2s
    box-shadow: 0 6px 8px rgba(102,119,136,0.03), 0 1px 2px rgba(102,119,136,0.3), 0 8px 12px rgba(58,193,203,0.1)
    &:hover
      box-shadow: 0 12px 16px rgba(102,119,136,0.03), 0 2px 4px rgba(102,119,136,0.3), 0 16px 24px rgba(58,193,203,0.1)
</style>
