<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M7.08,4.96l2.56-2.6c0.2-0.2,0.52-0.2,0.71,0l4.17,4.23l0,0c1.07,1.1,1.72,2.6,1.72,4.24c0,0.96-0.23,1.86-0.62,2.67 L10,7.88V4.14L8.14,6.02L7.08,4.96z M15.48,17.6l-1.8-1.8C12.65,16.55,11.38,17,10,17c-3.45,0-6.25-2.76-6.25-6.16 c0-1.39,0.47-2.67,1.26-3.7L2.4,4.52c-0.29-0.29-0.29-0.77,0-1.06l0,0c0.29-0.29,0.77-0.29,1.06,0l13.08,13.08 c0.29,0.29,0.29,0.77,0,1.06l0,0C16.25,17.89,15.77,17.89,15.48,17.6z M10,12.12L6.09,8.21c-0.54,0.77-0.84,1.68-0.84,2.63 c0,2.57,2.13,4.66,4.75,4.66V12.12z"/></svg>