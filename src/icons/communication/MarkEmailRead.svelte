<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M16,4H4C3.45,4,3,4.45,3,5v10c0,0.55,0.45,1,1,1h6.1c-0.07-0.32-0.1-0.66-0.1-1c0-2.76,2.24-5,5-5c0.71,0,1.39,0.15,2,0.42 V5C17,4.45,16.55,4,16,4z M16,6.18L10,10L4,6.18V5l6,3.82L16,5V6.18z M13.76,17l-2.12-2.12l0.71-0.71l1.41,1.41l3.54-3.54L18,12.76 L13.76,17z"/></g></svg>