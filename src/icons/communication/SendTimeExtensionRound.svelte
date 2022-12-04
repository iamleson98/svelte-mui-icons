<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17,11.32V4.5C17,3.67,16.33,3,15.5,3H12c0-1.1-0.9-2-2-2S8,1.9,8,3H4.5C3.67,3,3,3.67,3,4.5V8c1.1,0,2,0.9,2,2 s-0.9,2-2,2v3.5C3,16.33,3.67,17,4.5,17H8c0-0.93,0.64-1.71,1.5-1.93V10V7.57l2.17,1.09L17,11.32z"/><polygon points="11,10 11,13 14,14 11,15 11,18 19,14"/></g></g></svg>