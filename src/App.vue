<template>
  <div>
    <div>
      <NoteTab/>
    </div>
    <NoteContent/>
  </div>    
</template>

<script>
import NoteTab from '@/components/NoteTab.vue';
import NoteContent from '@/components/NoteContent.vue';

export default {
  created: function() {
    console.log('Vue App created!');
  },
  components: {
    NoteTab,
    NoteContent,
  },
}
</script>

<style scoped>

</style>
