<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10.75,8.63l-1.5-1.5V3h1.5V8.63z M14,9l-1.06-1.06L11.5,9.38l1.06,1.06L14,9z M17.07,17.07L2.93,2.93L1.87,3.99l4.57,4.57 L6,9l4,4l0.44-0.44l1.94,1.94H5.5V13H4v1.5C4,15.33,4.67,16,5.5,16h8.38l2.13,2.13L17.07,17.07z M16,13h-0.88L16,13.88V13z"/></svg>