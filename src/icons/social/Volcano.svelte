<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><polygon points="15,7 9,7 8,11 5,11 2,18 18,18"/></g><g><rect height={size} width="1.5" x="11.25" y="1"/></g><g><rect height="1.5" transform="matrix(0.7071 -0.7071 0.7071 0.7071 1.7627 11.8536)" width={size} x="13.69" y="3.05"/></g><g><rect height={size} transform="matrix(0.7071 -0.7071 0.7071 0.7071 -0.1067 7.3403)" width="1.5" x="8.06" y="2.3"/></g></g></g></svg>