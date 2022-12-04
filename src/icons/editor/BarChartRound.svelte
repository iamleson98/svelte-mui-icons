<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M13,11.5v3c0,0.83,0.67,1.5,1.5,1.5h0c0.83,0,1.5-0.67,1.5-1.5v-3c0-0.83-0.67-1.5-1.5-1.5h0C13.67,10,13,10.67,13,11.5z"/><path d="M5.5,16L5.5,16C6.33,16,7,15.33,7,14.5v-5C7,8.67,6.33,8,5.5,8h0C4.67,8,4,8.67,4,9.5v5C4,15.33,4.67,16,5.5,16z"/><path d="M10,16L10,16c0.83,0,1.5-0.67,1.5-1.5v-9C11.5,4.67,10.83,4,10,4h0C9.17,4,8.5,4.67,8.5,5.5v9C8.5,15.33,9.17,16,10,16z"/></g></g></svg>