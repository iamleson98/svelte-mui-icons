<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17.5,14c0,1.38-1.12,2.5-2.5,2.5h-1.5V15H16v-4.86l-5.18-1.57c-0.33-0.1-0.6-0.3-0.79-0.57H7V7h2.75V6H7V5h2.75V2.5H3V15 h2.5v1.5H2V18h13c2.21,0,4-1.79,4-4H17.5z M12,16.5H7V15h5V16.5z"/></svg>