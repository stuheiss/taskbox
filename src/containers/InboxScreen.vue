<!-- src/containers/InboxScreen.vue -->

<template>
  <PureInboxScreen :error="error" />
</template>

<script>
  import PureInboxScreen from '../components/PureInboxScreen';
  import { mapState } from 'vuex';

  export default {
    name: 'InboxScreen',
    components: { PureInboxScreen },
    computed: mapState(['error']),
  };
</script>
