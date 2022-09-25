<template>
  <Layout>

    <div class="content">
      <g-image alt="Example image" src="~/info.png" width="135" class="image"/>
      <h1 class="nom">Lelika TAGATAMANOGI</h1>
      <p class="description">
        Etudiant en licence pro MIAW
      </p>
      <p class="lien">
        <a href="https://github.com/Lelika02/appGridsome" target="_blank" rel="noopener">GitHub du projet</a>
        <a href="https://tagatalelika.wixsite.com/site-latai" target="_blank" rel="noopener" class="lien2">Portfolio</a>
      </p>
    </div>
    
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'App Lelika'
  }
}
</script>

<style>
.lien a{
  color: black;
  background-color: #439709;
  text-decoration: none;
  padding: 0.5em;
}

.lien2{
  margin-left: 1em;
}

.lien {
  margin-left: 15em;
}

.lien a:hover{
  background-color: #2D6903;
}

.content{
  background-color: #E9F5E0;
  margin: auto;
  padding: 2em;
}

.image{
  margin-left: 19em;
}

.nom{
  margin-left: 6em;
}

.description{
  margin-left: 15em;
}
</style>
