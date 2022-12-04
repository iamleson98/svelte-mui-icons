<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M12.25,10h3.25c0.83,0,1.5,0.67,1.5,1.5v4c0,0.83-0.67,1.5-1.5,1.5h-3.25c-0.83,0-1.5-0.67-1.5-1.5v-4 C10.75,10.67,11.42,10,12.25,10z M4.5,3C3.67,3,3,3.67,3,4.5v10.94C3,16.3,3.7,17,4.56,17h3.19c0.83,0,1.5-0.67,1.5-1.5v-11 c0-0.83-0.67-1.5-1.5-1.5H4.5z M17,7V4.5C17,3.67,16.33,3,15.5,3h-3.25c-0.83,0-1.5,0.67-1.5,1.5V7c0,0.83,0.67,1.5,1.5,1.5h3.25 C16.33,8.5,17,7.83,17,7z"/></svg>