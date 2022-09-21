<template>
  <div id="container">
    <div id="inviteContainer">
      <div class="logoContainer">
        <img class="logo" src="../assets/cmc.png" />
      </div>
      <div class="acceptContainer">
        <form>
          <h1>Welcome Back!</h1>
          <div class="formContainer">
            <div class="formDiv" style="transition-delay: 0.2s">
              <p>EMAIL</p>
              <input type="email" required="" />
            </div>
            <div class="formDiv" style="transition-delay: 0.4s">
              <p>PASSWSORD</p>
              <input type="password" required="" /><a class="forgotPas" href="#"
                >FORGOT YOUR PASSWORD?</a
              >
            </div>
            <div class="formDiv" style="transition-delay: 0.6s">
              <button class="acceptBtn" type="submit">Login</button
              ><span class="register"
                >Need an account?<a href="#">Register</a></span
              >
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
<script></script>
<style scoped>
@import url("https://fonts.googleapis.com/css?family=Montserrat:400,600,700|Work+Sans:300,400,700,900");
* {
  outline-width: 0;
  font-family: "Montserrat" !important;
}
#container {
  height: 100vh;
  background-size: cover !important;
  display: flex;
  justify-content: center;
  align-items: center;
}

#inviteContainer {
  display: flex;
  overflow: hidden;

  position: relative;
  border-radius: 5px;
  background: #000000;
  width: 40%;
  height: 35%;
}
.logoContainer {
  display: flex;
  height: 15vh;
  position: relative;
  padding-top: 80px;
  padding-left: 5%;
}
.acceptContainer {
  display: flex;
  height: 10vh;

  position: relative;
  padding-top: 30px;
  padding-left: 5%;
}
form {
  position: relative;
  text-align: center;
  height: 100%;
  left: -50px;
  top: 10px;
}
form h1 {
  position: relative;
  margin: 0 0 15px 0;
  font-family: "Work Sans" !important;
  font-weight: 700;
  font-size: 20px;
  color: #fff;
  text-align: center;
}
.formContainer {
  text-align: left;
}
.formContainer p {
  margin: 0;
  padding: 5px 0;
  font-weight: 700;
  color: #aaa;
  font-size: 10px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.formContainer input[type="password"],
.formContainer input[type="email"] {
  background: transparent;
  border: none;
  box-shadow: inset 0 -1px 0 rgba(255, 255, 255, 0.15);
  padding: 15px 0;
  box-sizing: border-box;
  color: #fff;
  width: 150%;
}
.formContainer input[type="password"]:focus,
.formContainer input[type="email"]:focus {
  box-shadow: inset 0 -2px 0 #fff;
}

.forgotPas {
  color: #aaa;
  opacity: 0.8;
  text-decoration: none;
  font-weight: 700;
  font-size: 10px;
  margin-top: 15px;
  padding: 5px 0;
  display: block;
  transition: 0.2s ease;
}
.forgotPas:hover {
  opacity: 1;
  color: #fff;
}

.acceptBtn {
  width: 150%;
  box-sizing: border-box;
  background: #9a72da;
  border: none;
  color: #fff;
  padding: 10px 0;
  border-radius: 3px;
  cursor: pointer;
  transition: 0.2s ease;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.acceptBtn:hover {
  background: #6b7fc5;
}

.register {
  color: #aaa;
  font-size: 12px;
  padding-top: 15px;
  display: block;
}
.register a {
  color: #fff;
  text-decoration: none;
  margin-left: 5px;
  box-shadow: inset 0 -2px 0 transparent;
  padding-bottom: 5px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.register a:hover {
  box-shadow: inset 0 -2px 0 #fff;
}
</style>
