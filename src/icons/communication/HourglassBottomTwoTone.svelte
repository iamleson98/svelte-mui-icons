<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon opacity=".3" points="13,13.41 10,10.41 7,13.41 7,16 13,16"/><path d="M6,17h8v-4l-3-3l3-3V3H6v4l3,3l-3,3V17z M7,6.59V4h6v2.59l-3,3L7,6.59z M7,13.41l3-3l3,3V16H7V13.41z"/></g></g></svg>