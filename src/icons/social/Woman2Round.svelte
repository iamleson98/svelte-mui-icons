<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="10" cy="3.75" r="1.75"/><path d="M11.39,7.92C11.15,7.36,10.61,7,10,7S8.85,7.36,8.61,7.92L6.3,13.3C6.16,13.63,6.4,14,6.76,14H9v3.5 C9,17.78,9.22,18,9.5,18h1c0.28,0,0.5-0.22,0.5-0.5V14h2.24c0.36,0,0.6-0.37,0.46-0.7L11.39,7.92z"/></g></g></svg>