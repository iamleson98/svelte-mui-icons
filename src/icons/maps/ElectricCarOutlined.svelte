<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><circle cx="13" cy="9.5" r="1"/><circle cx="7" cy="9.5" r="1"/><path d="M14.28,3.55C14.11,3.21,13.76,3,13.38,3H6.62C6.24,3,5.89,3.21,5.72,3.55L4,7v5.5C4,12.78,4.22,13,4.5,13h1 C5.78,13,6,12.78,6,12.5V12h8v0.5c0,0.28,0.22,0.5,0.5,0.5h1c0.28,0,0.5-0.22,0.5-0.5V7L14.28,3.55z M6.62,4h6.76l1.5,3H5.12 L6.62,4z M15,11H5V8h10V11z"/></g><polygon points="7,15 9.5,15 9.5,14 13,16 10.5,16 10.5,17"/></g></svg>