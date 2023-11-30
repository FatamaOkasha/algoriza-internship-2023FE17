<template>
  <div class="top">
    <div class="topLeft">
      <p>My Dream Place</p>
    </div>
    <div class="topCenter">
      <ul class="topList">
        <li class="topListItem">
          <a class="link" href="#"> Home </a>
        </li>
        <li class="topListItem">
          <a class="link" href="#">Discover</a>
        </li>
        <li class="topListItem">
          <a class="link" href="#">Activites</a>
        </li>
        <li class="topListItem">
          <a class="link" href="#">About</a>
        </li>
        <li class="topListItem">
          <a class="link" href="#">Contact</a>
        </li>
      </ul>
    </div>
    <div class="topRight">
      <li class="topListItem">
        <a class="login" href="/login"> Login </a>
      </li>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavbarItem",
};
</script>

<style scoped>
.top {
  width: 100%;
  height: 50px;
  background-color: white;
  position: sticky;
  top: 0;
  display: flex;
  align-items: center;
  z-index: 1;
  font-family: "Josefin Sans", sans-serif;
}

.topLeft,
.topRight {
  flex: 3;
  display: flex;
  align-items: center;
  justify-content: center;
}

.login {
  background-color: #0441aa;
  color: white;
  padding: 10px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  border-radius: 16px;
  text-decoration: none;
  list-style-type: none;
}
p {
  color: #444;
}
.link {
  text-decoration: none;
  color: #444;
}

.topIcon {
  font-size: 20px;
  margin-right: 10px;
  color: #444;
  cursor: pointer;
}

.topCenter {
  flex: 6;
}

.topList {
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 0;
  list-style: none;
}

.topListItem {
  margin-right: 20px;
  font-size: 18px;
  font-weight: 300;
  cursor: pointer;
  color: black;
  list-style-type: none;
}

.topListItem:hover {
  color: gray;
}

.topImg {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  object-fit: cover;
  margin-right: 15px;
  cursor: pointer;
}

.topSearchIcon {
  font-size: 18px;
  color: #666;
  cursor: pointer;
}
</style>
