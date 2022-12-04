<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><path d="M4.5,16.5h11V8h-11V16.5z M8,10h4v1.5H8V10z" enable-background="new" opacity=".3"/><rect enable-background="new" height={size} opacity=".3" width={size} x="3.5" y="3.5"/><path d="M16.5,2h-13C2.67,2,2,2.67,2,3.5v3c0,0.65,0.42,1.2,1,1.41v8.59C3,17.33,3.67,18,4.5,18h11c0.83,0,1.5-0.67,1.5-1.5V7.91 c0.58-0.21,1-0.76,1-1.41v-3C18,2.67,17.33,2,16.5,2z M15.5,16.5h-11V8h11V16.5z M16.5,6.5h-13v-3h13V6.5z"/><rect height="1.5" width={size} x="8" y="10"/></g></g></svg>