<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M9.21,16.5H4.5V9h11v3.09l1.5-1.5V4h-3V2h-1.5v2h-5V2H6v2H3v14h7.71L9.21,16.5z M13.33,16.38l3.54-3.54l1.06,1.06l-4.6,4.6 l-2.83-2.83l1.06-1.06L13.33,16.38z M8.81,12.25L10,13.44L8.94,14.5l-1.19-1.19L6.56,14.5L5.5,13.44l1.19-1.19L5.5,11.06L6.56,10 l1.19,1.19L8.94,10L10,11.06L8.81,12.25z"/></svg>