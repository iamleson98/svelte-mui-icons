<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16,4.98v-1c0-0.82-0.67-1.5-1.5-1.5S13,3.15,13,3.98v1h-1v4h5v-4H16z M13.75,3.98c0-0.41,0.34-0.75,0.75-0.75 c0.41,0,0.75,0.34,0.75,0.75v1h-1.5V3.98z M17,12.37l0,4.67C9.27,17.04,2.96,10.73,2.96,3l4.67,0l0.79,3.55L5.98,8.98 c1.15,2.11,2.89,3.85,5,5l2.48-2.39L17,12.37L17,12.37z"/></svg>