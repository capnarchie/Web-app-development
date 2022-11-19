<script>
import * as post from '/public/post.js'

export default {
  data() {
    return {
      message: `Hello ${post.MY_CONST}!` // Hello Vue.js!
    }
  }
}
</script>
<template>
<body>
    <div class="flex-container flex-column">
    <!--<header>

        <div class="dropdown profile-picture">
            <button id="dropdown-button" class="dropdownbtn"></button>
            <div id="user-dropdown" class="dropdown-content">
                <a href="#">John Doe</a>
                <a href="mailto:john.doe@ut.ee">john.doe@ut.ee</a>
                <a href="login.html">Log out</a>
            </div>
             <img class="logo" src="user.png" width="64" height="64" alt=""/>
        </div>

    </nav>
    </header>-->
    

    <div class="flex-container">
        <aside></aside>
        <main class="flex-container flex-column justify-space" id="posts">
        </main>
        <aside></aside>
    </div>
    
    <footer>
        <p id="para1">footer area</p>
    </footer>
    </div>
</body>
  </template>



  <style scoped>

  </style>