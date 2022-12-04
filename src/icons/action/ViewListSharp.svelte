<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M6,12.33V15H3v-2.67H6z M6,8.67H3v2.67h3V8.67z M6,5H3v2.67h3V5z M7,8.67v2.67h10V8.67H7z M7,15h10v-2.67H7V15z M17,7.67V5 H7v2.67H17z"/></svg>