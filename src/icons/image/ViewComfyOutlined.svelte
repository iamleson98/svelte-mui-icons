<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M2,4v12h16V4H2z M16.5,5.5v3.75h-13V5.5H16.5z M3.5,10.75H7v3.75H3.5V10.75z M8.5,14.5v-3.75h8v3.75H8.5z"/></g></svg>