<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="10" cy="3.75" r="1.75"/><path d="M11.39,7.92C11.15,7.36,10.61,7,10,7S8.85,7.36,8.61,7.92L6.6,12.61C6.31,13.27,6.8,14,7.52,14H8.5v3c0,0.55,0.45,1,1,1 h1.01c0.55,0,1-0.45,1-1v-3h0.98c0.72,0,1.2-0.73,0.92-1.39L11.39,7.92z"/></g></g></svg>