<template>
  <div>
    <h4 class="text-center">FigmaApp</h4>
    <q-section-item>
      <div class="flex bg-light-blue-10 items1 q-p-5">
        <div class="items2">
          <h4>
            <span class="text-white">Enjoy</span>
            <span class="text-orange">
              Fast and
              <br />Secure
              <br />
              <span class="text-white">Digital payments</span>
            </span>
          </h4>
          <p class="text-white">
            Helping millions of Nigeria buyers and
            <br />sellers transact safely from any where
            without doubt or fear
          </p>

          <div class="flex itemsflex">
            <p>make payment</p>
            <p>Recived Delivery</p>
            <p>Validate payment</p>
          </div>
          <div class="item12">
            <p>Buyer |protection</p>
            <p>Sell | verification</p>
            <p>Transaction |security</p>
          </div>
          <br />
          <br />
          <br />
          <br />
          <br />
        </div>

        <!-- END -->
        <form class="item3 bg-white q-mt-5">
          <p class="text-center">
            <b>Sign up</b>
          </p>
          <p class="text-center">
            Already have an account?
            <span class="text-center text-orange">Log in</span>
          </p>
          <div>
            <p class="para">Full Name</p>
            <input type="text" />
          </div>
          <br />

          <div>
            <p class="para">Phone Number</p>
            <input type="text" />
          </div>
          <br />
          <div>
            <p class="para">Email</p>
            <input type="text" />
          </div>
          <br />
          <div>
            <p class="para">password</p>
            <input type="password" />
          </div>
          <br />
          <div>
            <p class="para">Confirm password</p>
            <input type="text" />
          </div>
          <br />
          <br />
          <small class="small1">
            By signing up i agree to paylidate's
            <span class="text-orange">terms and condition</span>
          </small>
          <br />

          <small class="text-center link">
            See our
            <a class="text-orange">privacy polices</a>

            <span>to understand brhow we manage user personal</span>
          </small>
          <br />
          <br />
          <button class="bg-orange btn-lg">Sign Up</button>
        </form>
      </div>
      <br />
      <br />
      <!-- End1 -->

      <div class="flex bg-light-blue-10 items1 q-p-3">
        <form class="item3 bg-white q-mt-5">
          <p class="text-center">
            <b>Login</b>
          </p>
          <div>
            <p class="para">Email</p>
            <input type="text" />
          </div>
          <br />

          <div>
            <p class="para">Password</p>
            <input type="text" />
          </div>
          <div class="reed">
            <p>Signup</p>
            <p>Login</p>
          </div>
          <br />

          <button class="bg-orange btn-lg">Sign Up</button>
        </form>
      </div>
      <!-- END -->

      <br />
      <br />
      <br />
      <div class="flex bg-light-blue-10 items1 q-p-3">
        <form class="item3 bg-white q-mt-5">
          <p class="text-center">
            <b>Login</b>
          </p>
          <div>
            <p class="para">Password</p>
            <input type="text" />
          </div>
          <div class="reed">
            <p>Signup</p>
            <p>Login</p>
          </div>
          <br />

          <button class="bg-orange btn-lg">Sign Up</button>
        </form>
      </div>
    </q-section-item>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media screen and (max-width: 700px) and (min-width: 300px) {
  .items1 {
    width: 100%;
  }
  .item3 {
    width: 80%;
  }

  bottom {
    width: 80%;
    position: absolute;
  }
}
/* @media screen and (max-width: 767px) {
  .sidebar {
    display: none !important;
    margin: 0 auto;
  }
} */
.items1 {
  display: flex;
  justify-content: space-around;
  width: 60%;
  margin: 0 auto;
}
.items2 {
  width: 40%;
}

form {
  margin-top: 20px;
  width: 40%;
  border-radius: 10px;
}
input {
  width: 85%;
  margin-left: 1em;
  border: none;
  background-color: rgb(213, 225, 225);
  border-radius: 5px;
}

.para {
  margin-left: 2em;
  color: gray;
}

.small1 {
  font-size: 11px;
  /* margin-top: 5em; */
  margin-left: 3em;
}
.link {
  font-size: 9px;
  margin-left: 3em;
}
button {
  margin-left: 2em;
  width: 80%;
  border: none;
  color: white;
  border-radius: 5px;
}
.itemsflex {
  display: flex;
  justify-content: space-between;
  color: white;
  padding-top: 5em;
}
.item12 {
  display: flex;
  justify-content: space-between;
  color: white;
  padding-top: 5em;
}
.reed {
  display: flex;
  justify-content: space-around;
  color: red;
}
</style> 