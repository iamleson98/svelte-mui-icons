<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M24 0v24H0V0h24z" fill={color} opacity=".87"/><path d="M14 7l-5 5 5 5V7z"/></svg>