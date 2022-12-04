<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M15.5,17h-11C3.67,17,3,16.33,3,15.5v-11C3,3.67,3.67,3,4.5,3h11C16.33,3,17,3.67,17,4.5v11C17,16.33,16.33,17,15.5,17z"/></g></svg>