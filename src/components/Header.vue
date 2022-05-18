<template>
  <header>
    <div class="logo">
      <img src="@/assets/images/cloud-sun.svg" /> Moeyy Weather
    </div>
  </header>
</template>

<script>
export default {
  name: "Hearder",
};
</script>

<style scoped>
header {
  display: flex;
  padding: 0 48px;
  height: 64px;
  justify-content: space-between;
  align-items: center;
  user-select: none;
  border-bottom: 1px solid #eaeaea;
  background: #fafafa;
}
header .logo {
  font-size: 26px;
  font-weight: 600;
  font-style: italic;
  color: rgba(0, 0, 0, 0.85);
  display: flex;
  align-items: center;
  justify-content: center;
}
header .logo img {
  height: 24px;
  padding-right: 8px;
}
header ol {
  list-style: none;
}
header ol a {
  height: 30px;
  border-radius: 8px;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #242424;
  font-weight: 500;
  font-size: 16px;
  padding: 0 8px;
  border: 2px solid #242424;
  box-sizing: border-box;
  fill: #242424;
  text-decoration: none;
}
header ol a:hover {
  background: #242424;
  color: #fff;
  fill: #fff;
  transition: ease 0.2s;
}
header ol a:active {
  background: #000;
}
header ol svg {
  padding-right: 4px;
  height: 16px;
}
header ol span {
  padding-top: 1px;
}

@media (max-width: 768px) {
  header {
    padding: 0px 16px;
  }
}
</style>