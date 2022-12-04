<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M16,15.5V3H4v12.5H2V17h16v-1.5H16z M11.5,4.5v11h-3v-11H11.5z M5.5,4.5H7v11H5.5V4.5z M13,15.5v-11h1.5v11H13z"/></g></svg>