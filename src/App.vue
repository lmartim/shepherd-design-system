<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ButtonPrimary>
    Button label
  </ButtonPrimary>
  <HeadingSmall>
    Heading small
  </HeadingSmall>
  <SubtitleSmall>
    Subtitle small
  </SubtitleSmall>
  <Shape>
    <Paragraph>
      Lorem ipsum etc
    </Paragraph>
  </Shape>
  <br>
  <CardContent
    title="Card Content Title"
    subtitle="Card Content Subtitle"
    content="Card Content Content"
    buttonLabel="Card Content Button Label"
    buttonLink="http://www.pudim.com.br"
  />
</template>

<script>
import ButtonPrimary from './components/ButtonPrimary'
import HeadingSmall from './components/HeadingSmall'
import SubtitleSmall from './components/SubtitleSmall'
import Paragraph from './components/Paragraph'
import Shape from './components/Shape'
import CardContent from './components/CardContent'

export default {
  name: 'App',
  components: {
    ButtonPrimary,
    HeadingSmall,
    SubtitleSmall,
    Paragraph,
    Shape,
    CardContent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
