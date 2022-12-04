<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M13,3H7C6.45,3,6,3.45,6,4v2.59c0,0.27,0.11,0.52,0.29,0.71L9,10l-2.71,2.71C6.11,12.89,6,13.15,6,13.41V16 c0,0.55,0.45,1,1,1h6c0.55,0,1-0.45,1-1v-2.59c0-0.27-0.11-0.52-0.29-0.71L11,10l2.71-2.71C13.89,7.11,14,6.85,14,6.59V4 C14,3.45,13.55,3,13,3z M13,13.41v2.09c0,0.28-0.22,0.5-0.5,0.5h-5C7.22,16,7,15.78,7,15.5v-2.09l3-3L13,13.41z"/></g></svg>