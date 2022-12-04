<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="10.75,10 10.75,13.25 17.11,13.25 16.5,10"/><polygon points="2.89,13.25 9.25,13.25 9.25,10 3.5,10"/><polygon points="2,18 9.25,18 9.25,14.75 2.61,14.75"/><polygon points="17.39,14.75 10.75,14.75 10.75,18 18,18"/><rect height={size} width="1.5" x="9.25" y="7"/><rect height={size} transform="matrix(0.7071 -0.7071 0.7071 0.7071 -0.3314 12.1139)" width="1.5" x="13.71" y="5.46"/><rect height="1.5" transform="matrix(0.7071 -0.7071 0.7071 0.7071 -2.9423 5.8107)" width={size} x="4.54" y="5.71"/><rect height="1.5" width={size} x="3" y="2.05"/><rect height="1.5" width={size} x="15" y="2.05"/><path d="M10,6c2.21,0,4-1.79,4-4H6C6,4.21,7.79,6,10,6z"/></g></g></svg>