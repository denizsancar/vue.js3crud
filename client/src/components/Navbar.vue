<template>
    <nav class="navbar navbar-expand-sm fixed-top navbar-light bg-transparent" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <a class="navbar-item" href="http://localhost:8080">
                <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Ff%2Ff1%2FVue.png&f=1&nofb=1" 
                    width="36"
                    height="50">
            </a>

            <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
            <div class="navbar-start">
                <strong class="navbar-item">Vue.js CRUD API</strong>
            </div>

            <div class="navbar-end">
                <div class="navbar-item">
                    <div class="buttons">
                        <RouterLink to="/create" class="button is-primary">
                            <strong>Create</strong>
                        </RouterLink>
                        
                    </div>
                </div>
            </div>
        </div>
    </nav>
</template>


  
<style lang="scss"></style>