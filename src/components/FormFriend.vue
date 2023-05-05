<template>
  form@-----------------------------------------------
  <form>
    @submit.prevent="
    <div>
      <label for="name">FullName</label>
      <input type="text" name="name" />
    </div>

    <div>
      <label for="address">Address</label>
      <input type="text" name="address" />
    </div>

    <div>
      <label for="email">Email</label>
      <input type="text" name="email" />
    </div>

    <div>
      <label for="phone">Phone</label>
      <input type="text" name="phone" />
    </div>

    <input type="submit" value="Create a new friend" />
  </form>
</template>

<script>
export default {
  props: ["creatFriend"],
  data() {
    return {
      image: " ",
      name: " ",
      phone: " ",
      email: " ",
      adresse: " ",
    };
  },
};
</script>

<style scoped></style>
