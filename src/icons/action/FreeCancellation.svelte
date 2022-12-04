<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M9.21,16.5H4.5V9h11v3.09l1.5-1.5V5.5C17,4.68,16.33,4,15.5,4H14V2h-1.5v2h-5V2H6v2H4.5C3.67,4,3,4.68,3,5.5v11 C3,17.32,3.67,18,4.5,18h6.21L9.21,16.5z M13.33,16.38l3.54-3.54l1.06,1.06l-4.6,4.6l-2.83-2.83l1.06-1.06L13.33,16.38z M8.81,12.25 L10,13.44L8.94,14.5l-1.19-1.19L6.56,14.5L5.5,13.44l1.19-1.19L5.5,11.06L6.56,10l1.19,1.19L8.94,10L10,11.06L8.81,12.25z"/></svg>