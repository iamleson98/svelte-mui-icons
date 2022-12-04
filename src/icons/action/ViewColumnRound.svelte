<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M13.5,15h3c0.28,0,0.5-0.22,0.5-0.5v-9C17,5.22,16.78,5,16.5,5h-3C13.22,5,13,5.22,13,5.5v9C13,14.78,13.22,15,13.5,15z M8,5.5v9C8,14.78,8.22,15,8.5,15h3c0.28,0,0.5-0.22,0.5-0.5v-9C12,5.22,11.78,5,11.5,5h-3C8.22,5,8,5.22,8,5.5z M7,14.5v-9 C7,5.22,6.78,5,6.5,5h-3C3.22,5,3,5.22,3,5.5v9C3,14.78,3.22,15,3.5,15h3C6.78,15,7,14.78,7,14.5z"/></svg>