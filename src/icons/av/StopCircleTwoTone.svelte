<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,4.5c-3.04,0-5.5,2.46-5.5,5.5c0,3.04,2.46,5.5,5.5,5.5s5.5-2.46,5.5-5.5C15.5,6.96,13.04,4.5,10,4.5z M13,13H7V7h6V13z" opacity=".3"/><path d="M10,3c-3.87,0-7,3.13-7,7c0,3.87,3.13,7,7,7s7-3.13,7-7C17,6.13,13.87,3,10,3z M10,15.5c-3.04,0-5.5-2.46-5.5-5.5 c0-3.04,2.46-5.5,5.5-5.5s5.5,2.46,5.5,5.5C15.5,13.04,13.04,15.5,10,15.5z M13,13H7V7h6V13z"/></svg>