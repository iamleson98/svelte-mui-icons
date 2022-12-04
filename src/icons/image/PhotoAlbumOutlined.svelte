<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M14.5,2h-9C4.67,2,4,2.67,4,3.5v13C4,17.33,4.67,18,5.5,18h9c0.83,0,1.5-0.67,1.5-1.5v-13C16,2.67,15.33,2,14.5,2z M14.5,16.5h-9v-13H9V10l2-1l2,1V3.5h1.5V16.5z"/><polygon points="9.5,14 8.12,12.17 6,15 14,15 11.38,11.5"/></g></g></svg>