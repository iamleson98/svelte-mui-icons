<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><path d="M15.5,3h-11C3.67,3,3,3.67,3,4.5v3C3,8.33,3.67,9,4.5,9h11C16.33,9,17,8.33,17,7.5v-3C17,3.67,16.33,3,15.5,3z"/><path d="M15.5,11h-11C3.67,11,3,11.67,3,12.5v3C3,16.33,3.67,17,4.5,17h11c0.83,0,1.5-0.67,1.5-1.5v-3C17,11.67,16.33,11,15.5,11z"/></g></g></svg>