<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M4.5,7.91l7-2.72V10h-4v5.5h-3V7.91z M15.5,15.5H13V13h-1.5v2.5H9v-4h6.5V15.5z" opacity=".3"/><path d="M15.5,8.5C14.67,8.5,14,9.17,14,10h-1V3L3,6.89V17h14v-7C17,9.17,16.33,8.5,15.5,8.5z M4.5,7.91l7-2.72V10h-4v5.5h-3V7.91z M15.5,15.5H13V13h-1.5v2.5H9v-4h6.5V15.5z"/></svg>