<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><g><rect height="1.5" width={size} x="2" y="16.5"/></g><g><polygon points="13,13.5 9,13.5 9,12 6,12 6,13.5 2,13.5 2,15 13,15"/></g><g><path d="M18,9.76V2h-5v7.76c0,1.27,0.67,2.44,1.75,3.09V18H18v-1.5h-1.75v-3.65C17.33,12.2,18,11.04,18,9.76z M16.5,3.5V7h-2V3.5 H16.5z"/></g></g></g></svg>