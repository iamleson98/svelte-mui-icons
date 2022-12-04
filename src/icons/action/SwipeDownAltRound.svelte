<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M12.47,14.47c-0.29-0.29-0.77-0.29-1.06,0l-0.66,0.66l0-3.2C12.6,11.58,14,9.95,14,8c0-2.21-1.79-4-4-4C7.79,4,6,5.79,6,8 c0,1.95,1.4,3.58,3.25,3.93l0,3.2l-0.66-0.66c-0.29-0.29-0.77-0.29-1.06,0s-0.29,0.77,0,1.06l1.76,1.76c0.39,0.39,1.02,0.39,1.41,0 l1.76-1.76C12.76,15.24,12.76,14.76,12.47,14.47z"/></g></svg>