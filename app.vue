<template>
  <div>
    <NuxtRouteAnnouncer />
    <button @click="download"/>
  </div>
</template>

<script lang="ts" setup>
import { saveAs } from 'file-saver';

function download(){
  saveAs();
}

</script>
