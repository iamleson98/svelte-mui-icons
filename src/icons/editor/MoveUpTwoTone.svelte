<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width={size} x="12.5" y="12.5"/><rect height={size} width={size} x="11" y="4"/><path d="M11,16h7v-5h-7V16z M12.5,12.5h4v2h-4V12.5z"/><path d="M5.57,8.06l1.06,1.06L9.5,6.25L6.62,3.37L5.56,4.43l1.06,1.06V5.5H6.25C3.35,5.5,1,7.85,1,10.75C1,13.65,3.35,16,6.25,16 H9.5v-1.5H6.25c-2.07,0-3.75-1.68-3.75-3.75C2.5,8.68,4.18,7,6.25,7h0.37v0.01L5.57,8.06z"/></g></g></svg>