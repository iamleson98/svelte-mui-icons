<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M9.87,10.25H13v1.5H9.87l1.19,1.19L10,14l-3-3l3-3l1.06,1.06L9.87,10.25z M16.5,6H10L8,4H3.5C2.67,4,2,4.67,2,5.5v9 C2,15.33,2.67,16,3.5,16h13c0.83,0,1.5-0.67,1.5-1.5v-7C18,6.67,17.33,6,16.5,6z M16.5,14.5h-13v-9h3.88l2,2h7.12V14.5z"/></svg>