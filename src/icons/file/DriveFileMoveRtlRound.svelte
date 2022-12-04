<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M13,11.02c-0.01,0.41-0.37,0.73-0.78,0.73H10v1.04c0,0.45-0.54,0.67-0.85,0.35l-1.79-1.79c-0.2-0.2-0.2-0.51,0-0.71 l1.79-1.79C9.46,8.54,10,8.76,10,9.21v1.04h2.25C12.67,10.25,13.01,10.6,13,11.02z M16.5,6H10L8.44,4.44C8.16,4.16,7.78,4,7.38,4 H3.5C2.67,4,2,4.67,2,5.5v9C2,15.33,2.67,16,3.5,16h13c0.83,0,1.5-0.67,1.5-1.5v-7C18,6.67,17.33,6,16.5,6z"/></svg>