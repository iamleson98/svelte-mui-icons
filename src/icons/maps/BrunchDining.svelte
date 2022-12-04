<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width={size} x="3" y="16"/><polygon points="9,13 7,13 7,14 3,14 3,15 13,15 13,14 9,14"/><path d="M17,9.76V3h-4v6.76c0,1.17,0.57,2.25,1.5,2.93V17H17v-1h-1.5v-3.31C16.43,12.02,17,10.94,17,9.76z M14,7V4h2v3H14z"/></g></g></svg>