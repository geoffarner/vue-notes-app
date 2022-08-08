<script>
export default {
  props: ["note"],
};
</script>

<template>
  <div class="note-selector active">
    <p class="note-selector-title">{{ note.body }}</p>
    <p class="note-selector-timestamp"></p>
  </div>
  <template />
</template>
