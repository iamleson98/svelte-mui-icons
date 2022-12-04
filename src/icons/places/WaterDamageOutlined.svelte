<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M12,3L2,12h3v8h14v-8h3L12,3z M7,18v-7.81l5-4.5l5,4.5V18H7z M14,14c0,1.1-0.9,2-2,2s-2-0.9-2-2c0-1.1,2-4,2-4 S14,12.9,14,14z"/></svg>