<template>
  <div id="app">
    <Hello/>
    <GoodBye/>
  </div>
</template>

<script>
import Hello from './components/Hello';
import GoodBye from './components/GoodBye';

export default {
  name: 'app',
  components: {
    Hello,
    GoodBye,
  }
}
</script>
