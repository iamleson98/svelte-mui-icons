<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><circle cx="5" cy="14" r="1"/><circle cx="15" cy="14" r="1"/><circle cx="7.5" cy="17" r="1"/><circle cx="10" cy="14" r="1"/><circle cx="12.5" cy="17" r="1"/><path d="M10 6c-2.21 0-4 1.79-4 4v1h8v-1c0-2.21-1.79-4-4-4z"/><rect height={size} width="1.5" x="9.25" y="1.5"/><rect height={size} transform="matrix(-1.836970e-16 1 -1 -1.836970e-16 27 -7)" width="1.5" x="16.25" y="8.5"/><rect height={size} transform="matrix(0.7071 0.7071 -0.7071 0.7071 7.9497 -9.0919)" width="1.5" x="14.2" y="3.55"/><rect height={size} transform="matrix(-0.7071 0.7071 -0.7071 -0.7071 12.1924 5.0503)" width="1.5" x="4.3" y="3.55"/><rect height="1.5" width={size} x="1.5" y="9.25"/></g></svg>