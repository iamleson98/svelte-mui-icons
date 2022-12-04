<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><path d="M15,11V8l-4.25-2.55v-1.2h1.75v-1.5h-1.75V1h-1.5v1.75H7.5v1.5h1.75v1.2L5,8v3l-3,1v6h7v-3c0-0.55,0.45-1,1-1s1,0.45,1,1 v3h7v-6L15,11z M16.5,16.5h-4V15c0-1.38-1.12-2.5-2.5-2.5S7.5,13.62,7.5,15v1.5h-4v-3.42l3-1V8.85l3.5-2.1l3.5,2.1v3.23l3,1V16.5z"/><circle cx="10" cy="10" r="1.25"/></g></g></svg>