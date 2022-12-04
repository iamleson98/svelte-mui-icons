<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M13,9h-1V5c0-1.1-0.9-2-2-2h0C8.9,3,8,3.9,8,5v4H7c-1.66,0-3,1.34-3,3v4c0,0.55,0.45,1,1,1h10c0.55,0,1-0.45,1-1v-4 C16,10.34,14.66,9,13,9z M15,16h-2v-1.5c0-0.28-0.22-0.5-0.5-0.5S12,14.22,12,14.5V16h-1.5v-1.5c0-0.28-0.22-0.5-0.5-0.5 s-0.5,0.22-0.5,0.5V16H8v-1.5C8,14.22,7.78,14,7.5,14S7,14.22,7,14.5V16H5v-4c0-1.1,0.9-2,2-2h6c1.1,0,2,0.9,2,2V16z"/></g></svg>