<template>
  <div>
    <NavBar />
    <PageTitle />
    <UserNameType />
  </div>
</template>

<script>
import NavBar from "@c/common/NavBar";
import PageTitle from "./components/PageTitle";
import UserNameType from "./components/UserNameType";
export default {
  name: "Login",
  components: { NavBar, PageTitle, UserNameType }
};
</script>

<style lang="scss" scoped></style>
