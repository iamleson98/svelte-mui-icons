<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M2,4v12h16V4H2z M9,14H6v-3h3V14z M9,9H6V6h3V9z M14,14h-3v-3h3V14z M14,9h-3V6h3V9z"/></g></g></svg>