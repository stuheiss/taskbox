<!-- src/containers/TaskList.vue -->

<template>
  <PureTaskList :tasks="tasks" v-on="$listeners" @archive-task="archiveTask" @pin-task="pinTask" />
</template>

<script>
  import PureTaskList from '@/components/PureTaskList';
  import { mapState, mapActions } from 'vuex';

  export default {
    components: { PureTaskList },

    methods: mapActions(['archiveTask', 'pinTask']),

    computed: mapState(['tasks']),
  };
</script>
