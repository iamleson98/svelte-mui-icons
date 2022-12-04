<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10.75,10H17v7h-6.25V10z M9.25,3H3v14h6.25V3z M17,8.5V3h-6.25v5.5H17z"/></svg>