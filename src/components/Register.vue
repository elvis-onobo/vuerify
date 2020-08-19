<template>
  <div>
    <form>
      <label>
        First Name
        <input type="text" name="firstname" v-model.lazy="firstname" />
      </label>
      {{firstname}}
      <label>
        Last Name
        <input type="text" name="lastname" v-model.lazy="lastname" />
      </label>

      <label>
        Email
        <input type="text" name="email" v-model.lazy="email" />
      </label>

      <label>
        Phone Number
        <input type="text" name="phone" v-model.lazy="phone" />
      </label>

      <label>
        Password
        <input type="text" name="password" v-model.lazy="password" />
      </label>

      <button>Register</button>
    </form>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      firstname: "",
      lastname: "",
      email: "",
      phone: "",
      password: "",
    };
  },
};
</script>

<style scoped>
</style>