<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><path d="M6.5,4C5.12,4,4,5.12,4,6.5C4,7.88,5.12,9,6.5,9S9,7.88,9,6.5C9,5.12,7.88,4,6.5,4z M6.5,7.5c-0.55,0-1-0.45-1-1 c0-0.55,0.45-1,1-1s1,0.45,1,1C7.5,7.05,7.05,7.5,6.5,7.5z M13.5,11c-1.38,0-2.5,1.12-2.5,2.5c0,1.38,1.12,2.5,2.5,2.5 s2.5-1.12,2.5-2.5C16,12.12,14.88,11,13.5,11z M13.5,14.5c-0.55,0-1-0.45-1-1c0-0.55,0.45-1,1-1s1,0.45,1,1 C14.5,14.05,14.05,14.5,13.5,14.5z M5.06,16L4,14.94L14.94,4L16,5.06L5.06,16z"/></g></g></svg>