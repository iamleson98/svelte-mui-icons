<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="10" cy="3.75" r="1.75"/><path d="M11.39,7.92C11.15,7.36,10.61,7,10,7S8.85,7.36,8.61,7.92L6,14h2.5v4h3.01v-4H14L11.39,7.92z"/></g></g></svg>