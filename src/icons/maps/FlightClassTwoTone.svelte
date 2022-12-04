<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><rect height="3.75" opacity=".3" width="1.5" x="11.5" y="5.5"/><path d="M13,4h-1.5C10.67,4,10,4.67,10,5.5v3.75c0,0.83,0.67,1.5,1.5,1.5H13c0.83,0,1.5-0.67,1.5-1.5V5.5C14.5,4.67,13.83,4,13,4z M13,9.25h-1.5V5.5H13V9.25z M8.4,13H15v1.5H8.4c-0.66,0-1.24-0.43-1.43-1.06L5,7V4h1.5v3L8.4,13z M7.5,15.5H15V17H7.5V15.5z"/></svg>