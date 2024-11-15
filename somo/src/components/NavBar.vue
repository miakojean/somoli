<template>
  <nav>
    <div class="nav__logo"><a href="#">Somoli</a></div>
    <div class="search">
      <input type="text" name="" id="" placeholder="Entrer la ville">
    </div>
    <div class="nav__menu__btn" id="menu-btn">
      <button class="btn" type="button">Commencer</button>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      isMenuOpen: false, // État du menu (ouvert/fermé)
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen; // Inverser l'état du menu
    },
  },
};
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

:root{
  --primary-color: #18534F;
  --secondary-color: #2a9d8f;
  --textcolor: #272323;
}

.btn{
  padding: 0.5rem;
  font-size: 0.8rem;
  font-family: 'poppins', sans-serif;
  border-radius: 0.5rem;
  background: #2a9d8f;
  color: aliceblue;
  border: none;
}


/*============================================================*/

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'poppins', sans-serif;
}


/*nav*/

nav {
  position: fixed;
  top: 0;
  left: 0; /* Assure que le nav commence bien à gauche */
  width: 100%; /* Utilise toute la largeur sans débordement */
  padding: 0.5rem 1rem; /* Ajuste les marges et paddings */
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  background-color: white;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
  overflow-x: hidden; /* Empêche le débordement horizontal */
}

.nav__logo a{
  text-decoration: none;
  font-size: 1.5rem;
  font-weight: 600;
  color: #2a9d8f;
}

.search{
  display: flex;
}

input{
  padding: 0.5rem;
  border: 1px solid #2a9d8f;
  border-radius: 0.8rem;
  font-size: 0.9rem;
  max-width: 600px;
}

input:focus{
  outline: none;
}
/*nav*/
</style>
