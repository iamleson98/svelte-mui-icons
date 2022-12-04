<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M7.62,5.5H17V7H9.12L7.62,5.5z M12.87,10.75H15v-1.5h-3.63L12.87,10.75z M16.01,18.13l1.06-1.06L2.93,2.93L1.87,3.99 L3.38,5.5H3V7h1.88l2.25,2.25H5v1.5h3.63L10.88,13L8,13v1.5h4v-0.38L16.01,18.13z"/></g></svg>