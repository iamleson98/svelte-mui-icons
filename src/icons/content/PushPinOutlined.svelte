<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M15,10c-1.1,0-2-0.9-2-2V4h0.5C13.78,4,14,3.78,14,3.5C14,3.22,13.78,3,13.5,3h-7C6.22,3,6,3.22,6,3.5C6,3.78,6.22,4,6.5,4 H7v4c0,1.1-0.9,2-2,2v1h4.5v5.5L10,17l0.5-0.5V11H15V10z M7.23,10C7.71,9.47,8,8.77,8,8V4h4v4c0,0.77,0.29,1.47,0.77,2H7.23z"/></g></svg>