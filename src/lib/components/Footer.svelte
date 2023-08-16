<footer>
    <div class="border-right">
        <p><b>PAGES</b></p>
        <ul>
           <li><a href="/">Home</a></li> 
           <li><a href="/blog">Blog</a></li> 
           <li><a href="/über-mich">Über mich</a></li> 
           <li><a href="/kontakt">Kontakt</a></li> 
        </ul>
    </div>
    <div class="border-right">
        <p><b>LINKS</b></p>
        <ul>
           <li>
            <a target="_blank" href="https://github.com/Robinho1997">GitHub</a>
           </li> 
           <li>
            <a target="_blank" href="https://robinkempen.netlify.app">Portfolio</a>
           </li> 
           <li>
            <a target="_blank" href="https://www.linkedin.com/in/robin-kempen-046324273/">Linkedin</a>
        </li> 
        </ul>
    </div>
    <div class="i">
        <i>  <p>© 2023 - Robin Kempen</p>
      
        <p>Erstellt mit <a target="_blank" href="https://kit.svelte.dev">Sveltekit</a>; hosted mit <a target="_blank" href="https://www.netlify.com/?attr=homepage-modal">Netlify</a></p>
    </i>
    </div>
</footer>

<style>
    footer {
  padding: 1rem;
  background: rgb(52, 100, 127);
  display: flex;
  justify-content: space-evenly;
  color: white;
  position: fixed;
  width: 100%;
  bottom: 0;
}

li {
    margin-bottom: 1rem;
    

}

a {
    color: inherit;
    text-decoration-color: rgb(255, 235, 122);
    text-underline-offset: 5px;
}

.i {
   
    padding-top: 103px;
}

.border-right {
    border-right: 1px solid;
    padding-right: 2rem;
}

@media(max-width:800px) {
    footer {
        flex-direction: column;
    }
}
</style>