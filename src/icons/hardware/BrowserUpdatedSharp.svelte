<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M18,10.5V15h-5l1,1v1H6v-1l1-1H2V3h8.25v1.5H3.5v9h13v-3H18z M16.5,9l-3.25,0V3h-1.5v6L8.5,9l4,4L16.5,9z"/></g></svg>