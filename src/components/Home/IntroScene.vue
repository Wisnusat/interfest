<template>
  <section class="scene-intro" id="intro">
    <div class="static-container">
      <h1 class="title">
        <span class="iuri">inter</span>
        <span class="func">.fest()</span>
      </h1>

      <TextBlock>
        <p class="-purple">2024</p>
        <p class="-gray">HIMA IF Telkom University</p>
      </TextBlock>
    </div>
  </section>
</template>

<script>
import TextBlock from '../TextBlock.vue'

export default {
  name: 'IntroScene',
  components: { TextBlock },
}
</script>
