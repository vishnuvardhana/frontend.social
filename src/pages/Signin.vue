<template>
  <b-container>
    <b-row>
      <b-col md="12">
        <div class="sign-in">
          <div class="join-box">
            <div>Sign in to see customized results for you</div>
            <SignInButtons />
          </div>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import SignInButtons from "@/components/Signin/SignInButtons";

export default {
  components: {
    SignInButtons
  },
  created() {},
  methods: {}
};
</script>

<style scoped lang="scss">
.join-box {
  width: 100%;
  text-align: center;
}
</style>
