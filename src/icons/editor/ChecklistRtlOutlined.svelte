<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M9,7.5H2V6h7V7.5z M9,12.5H2V14h7V12.5z M11.64,5.11l-1.06,1.06L13.4,9L18,4.4l-1.06-1.06L13.4,6.88L11.64,5.11z M11.64,11.61l-1.06,1.06l2.83,2.83l4.6-4.6l-1.06-1.06l-3.54,3.54L11.64,11.61z"/></svg>