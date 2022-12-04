<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><path d="M1,5v14h22V5H1z M18,17H6V7h12V17z"/><rect height="1.5" width="1.5" x="12.5" y="11.25"/><rect height="1.5" width="1.5" x="15" y="11.25"/><rect height="1.5" width="1.5" x="10" y="11.25"/><rect height="1.5" width="1.5" x="7.5" y="11.25"/></g></g></svg>