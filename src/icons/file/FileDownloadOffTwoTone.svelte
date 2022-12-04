<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><polygon enable-background="new" opacity=".3" points="9.5,4.5 9.5,7.38 10.5,8.38 10.5,4.5"/><path d="M9.5,7.38L8,5.88V3h4v5h3l-2.44,2.44L10.5,8.38V4.5h-1V7.38z M17.07,17.07L2.93,2.93L1.87,3.99L5.88,8H5l5,5l0.44-0.44 l1.94,1.94H5V16h8.88l2.13,2.13L17.07,17.07z"/></svg>