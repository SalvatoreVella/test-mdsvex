<script>
  export let posts;
  import HelloWorld from "./hello-world.md"
 </script>
 
 <ul>
<!--   {#each  posts as {path, metadata: {title}} }
   <li>
    <a href={`/blog/${path.replace(".md","")}`}>{title}</a>
   </li>
  {/each} -->
 </ul>
 <HelloWorld />