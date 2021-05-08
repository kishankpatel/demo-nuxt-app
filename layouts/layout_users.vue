<template>
  <div>
    <Header />
    Users Layout
    <header>
        <p>This is users header</p>
    </header>
    <Nuxt />
  </div>
</template>

<script>
import Header from '~/components/header'
export default {
  component: {Header}
}
</script>
