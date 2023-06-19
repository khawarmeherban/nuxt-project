<template>
  <div
    style="min-width: 1200px"
    class="flex items-center w-screen h-screen overflow-hidden bg-gray-100 min-w-max"
  >
    <div class="bg-white w-1/2 h-full relative rounded-r-3xl">
      <div
        class="flex w-96 flex-col justify-center items-center mx-auto py-4 px-4"
      >
        <div class="w-full flex items-center">
          <svg
            width="60"
            height="33"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 60 33"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M59.9906 23.5561V12.796V2.0563C59.9906 1.85289 59.9906 1.62915 59.97 1.42575C59.8878 0.57145 59.189 -0.0387612 58.3874 0.00191951C57.6063 0.0426003 57.0103 0.652812 56.9486 1.48677V2.0563V23.4137C56.9486 23.6578 56.9486 23.8815 56.9692 24.1256C57.0308 24.9596 57.6269 25.5087 58.4696 25.5087C59.2918 25.5087 59.9084 24.9392 59.9906 24.1256C60.0044 24.0028 59.9997 23.8709 59.9951 23.7421C59.9928 23.6789 59.9906 23.6164 59.9906 23.5561ZM42.2724 9.70443C47.3903 6.75508 54.0087 10.0095 54.8925 15.7862C55.5502 20.1594 52.6316 24.6343 47.7809 25.3869C45.6021 25.7326 43.5468 25.3462 41.7175 24.0647L41.7174 24.0647L41.7174 24.0647L41.7174 24.0647C41.553 23.9426 41.3886 23.8206 41.2036 23.6986C41.0597 23.5969 40.9775 23.6579 40.9775 23.8207V24.3902V30.472C40.9775 30.7567 40.9775 31.0415 40.8953 31.3059C40.7103 31.9771 39.9909 32.445 39.3127 32.3636C38.5933 32.2822 37.9972 31.6924 37.9355 30.9601V30.472V23.4749C37.9355 22.8414 37.9322 22.2079 37.9288 21.5745C37.9204 19.9908 37.9121 18.4072 37.9561 16.8236C38.0383 13.6708 39.5387 11.2706 42.2724 9.70443ZM40.9775 17.0473C40.957 19.9967 43.4029 22.4782 46.4037 22.4578C49.754 22.4578 51.9533 19.6916 51.8711 17.1083C51.9533 14.22 49.5074 11.6978 46.4654 11.6978C43.444 11.6978 40.9981 14.0776 40.9775 17.0473ZM26.4221 12.9574C26.7509 12.876 26.9359 12.5303 26.8331 12.2049L26.0522 9.0728C25.97 8.74739 25.6206 8.56435 25.2918 8.66604L24.6136 8.86942C24.2847 8.95077 24.0998 9.29652 24.2025 9.62192L25.2507 12.6726C25.3329 12.998 25.6822 13.1811 26.0111 13.0794L26.4221 12.9574ZM30.1639 12.9992C30.0201 13.3043 29.6501 13.4467 29.3419 13.3043L28.9514 13.1416C28.6431 12.9992 28.4993 12.6331 28.6431 12.3281L29.8762 9.33837C30.0201 9.0333 30.39 8.89093 30.6983 9.0333L31.3559 9.31803C31.6642 9.4604 31.8081 9.80614 31.6642 10.1316L30.1639 12.9992ZM23.7699 13.8122C24.0576 13.9952 24.1193 14.3817 23.9343 14.6664L23.6877 15.0122C23.5027 15.2969 23.1123 15.3579 22.8245 15.1749L20.0501 13.4665C19.7624 13.2834 19.7007 12.897 19.8857 12.6123L20.2761 12.0225C20.4611 11.7377 20.8516 11.6767 21.1393 11.8598L23.7699 13.8122ZM22.4754 16.8851C22.8042 16.8445 23.1125 17.0885 23.1536 17.4139L23.1947 17.8207C23.2358 18.1461 22.9892 18.4512 22.6604 18.4918L19.4338 18.98C19.1049 19.0206 18.7967 18.7766 18.7556 18.4512L18.6734 17.7597C18.6322 17.4343 18.8789 17.1292 19.2077 17.0885L22.4754 16.8851ZM24.3049 20.0565C24.0583 19.8328 23.6678 19.8532 23.4418 20.0972L21.0989 22.3344C20.8728 22.5785 20.8934 22.9649 21.14 23.1886L21.6538 23.6767C21.9004 23.9004 22.2909 23.8801 22.517 23.636L24.6543 21.1955C24.8804 20.9514 24.8598 20.565 24.6132 20.3413L24.3049 20.0565ZM26.3189 21.9272C26.3395 21.5814 26.6272 21.3373 26.9766 21.3577L27.4081 21.378C27.7575 21.3984 28.0041 21.6831 27.9836 22.0288L27.9219 25.2626C27.9014 25.6083 27.6137 25.8524 27.2643 25.8321L26.5655 25.7914C26.2162 25.771 25.9695 25.4863 25.9901 25.1406L26.3189 21.9272ZM29.6496 20.7276C29.3619 20.931 29.3003 21.3174 29.5058 21.5818L31.2938 24.2868C31.4993 24.5715 31.8898 24.6325 32.1569 24.4291L32.7324 24.0224C33.0201 23.819 33.0817 23.4326 32.8762 23.1682L30.8622 20.6259C30.6567 20.3412 30.2662 20.2802 29.999 20.4836L29.6496 20.7276ZM31.8478 19.1608C31.519 19.0794 31.3135 18.754 31.3957 18.4286L31.4985 18.0218C31.5807 17.6964 31.9095 17.4931 32.2383 17.5744L35.4444 18.2252C35.7732 18.3066 35.9787 18.632 35.8965 18.9574L35.7321 19.6489C35.6499 19.9743 35.3211 20.1777 34.9922 20.0963L31.8478 19.1608ZM31.2928 15.4812C31.4366 15.7863 31.8066 15.9083 32.1148 15.7659L35.1359 14.5253C35.4442 14.3829 35.5675 14.0169 35.4236 13.7118L35.1154 13.0813C34.9715 12.7762 34.6016 12.6542 34.2933 12.7966L31.3955 14.2813C31.0873 14.4236 30.964 14.7897 31.1078 15.0948L31.2928 15.4812ZM4.35029 9.72347C9.46821 6.77412 16.0866 10.0082 16.9704 15.8052C17.6281 20.1581 14.7095 24.633 9.83818 25.4059C7.65947 25.7517 5.58353 25.3449 3.73368 24.0431C3.65146 23.9922 3.57438 23.9363 3.49731 23.8804C3.42023 23.8244 3.34315 23.7685 3.26094 23.7176C3.11706 23.6159 3.0554 23.6973 3.0554 23.8397V24.4092V30.491C3.0554 30.7758 3.0554 31.0605 2.97318 31.3249C2.7882 32.0165 2.06881 32.464 1.39053 32.3826C0.671147 32.3013 0.0750846 31.7114 0.0134229 30.9792V30.491V23.4939C0.0134229 22.8604 0.0100672 22.227 0.00671147 21.5935C-0.00167787 20.0099 -0.0100672 18.4262 0.0339768 16.8426C0.116192 13.6898 1.61663 11.2897 4.35029 9.72347ZM3.07595 17.0257C3.03484 19.9954 5.48076 22.4565 8.48162 22.4565C11.8525 22.4565 14.0312 19.6903 13.949 17.107C14.0312 14.1983 11.5853 11.6761 8.56384 11.6761C5.54242 11.6761 3.09651 14.056 3.07595 17.0257Z"
              fill="black"
            ></path>
          </svg>
          <div class="w-6 bg-gray-200 h-px transform rotate-90 my-0 mx-2"></div>
          <div>
            <span class="text-gray-400 text-lg font-medium">Log in</span>
          </div>
        </div>

        <div class="mb-4 w-full pt-6">
          <span
            class="text-black inline-block text-sm font-semibold leading-5 pb-2"
            >Email</span
          >
          <input
            class="text-sm bg-gray-100 rounded-xl h-12 outline-none w-full pl-5 leading-normal"
            placeholder="Email"
            type="email"
            id="email"
            v-model="email"
          />
        </div>
        <div class="mb-4 w-full">
          <span
            class="text-black inline-block text-sm font-semibold leading-5 pb-2"
            >Password</span
          >

          <div class="min-h-12 max-h-12">
            <div class="flex items-center relative pl-5 h-12 px-6 py-3 rounded-xl bg-gray-100">
              <input
                v-model="password"
                name="passwordVisible"
                placeholder="Password"
                :type="passwordVisible ? 'text' : 'password'"
                class="text-sm border-none outline-none bg-transparent leading-normal h-full"
              />
              <div
                @click="togglePasswordVisibility"
                class="absolute inset-y-0 right-0 flex pr-4 items-center"
              >
                <svg
                  width="20"
                  height="20"
                  viewBox="0 0 20 20"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M10 12C11.1046 12 12 11.1046 12 10C12 8.89543 11.1046 8 10 8C8.89543 8 8 8.89543 8 10C8 11.1046 8.89543 12 10 12Z"
                    fill="#828282"
                  ></path>
                  <path
                    d="M18 10C15.8664 14.0003 13.2 16 10 16C6.8 16 4.1336 14.0003 2 10C4.1336 5.99971 6.8 4 10 4C13.2 4 15.8664 5.99971 18 10Z"
                    stroke="#828282"
                    stroke-width="1.5"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
        </div>

        <div
          class="cursor-pointer text-gray-500 text-xs font-semibold ml-auto w-fit-content"
        >
          Forgot password?
        </div>

        <div class="mb-4 w-full pt-5">
          <button
            class="bg-black w-full text-sm text-white py-2 px-4 rounded-full"
            type="submit"
          >
            Log in
          </button>
        </div>

        <div class="py-7 flex items-center w-full max-w-360">
          <hr class="w-56 h-px border-none bg-gray-300" />
          <span class="text-gray-500 text-xs font-semibold mx-2">OR</span>
          <hr class="w-56 h-px border-none bg-gray-300" />
        </div>

        <div class="w-full">
          <button
            @click="openGoogleLogin"
            class="py-2 mx-auto rounded-full text-xs flex justify-center items-center border border-gray-300 w-full text-gray-900"
          >
            <span class="flex items-center">
              <svg
                class="w-5 h-5 mr-2"
                viewBox="0 0 21 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M19.4996 10.2114C19.4996 9.58745 19.449 8.96007 19.3411 8.34619H10.6826V11.8811H15.6409C15.4352 13.0211 14.774 14.0297 13.806 14.6705V16.9641H16.7641C18.5012 15.3654 19.4996 13.0043 19.4996 10.2114Z"
                  fill="#4285F4"
                ></path>
                <path
                  d="M10.6855 19.1803C13.1613 19.1803 15.2491 18.3674 16.7704 16.9643L13.8123 14.6706C12.9893 15.2306 11.9268 15.5476 10.6889 15.5476C8.29407 15.5476 6.26353 13.932 5.53497 11.7598H2.48242V14.1242C4.04074 17.224 7.21471 19.1803 10.6855 19.1803V19.1803Z"
                  fill="#34A853"
                ></path>
                <path
                  d="M5.52956 11.76C5.14504 10.6199 5.14504 9.38538 5.52956 8.24532V5.88086H2.48038C1.17841 8.47468 1.17841 11.5306 2.48038 14.1244L5.52956 11.76V11.76Z"
                  fill="#FBBC04"
                ></path>
                <path
                  d="M10.6855 4.45387C11.9942 4.43364 13.2591 4.92609 14.2069 5.83005L16.8277 3.20924C15.1682 1.65093 12.9656 0.794191 10.6855 0.821175C7.21471 0.821175 4.04074 2.7775 2.48242 5.88064L5.53159 8.2451C6.25678 6.06953 8.29069 4.45387 10.6855 4.45387V4.45387Z"
                  fill="#EA4335"
                ></path>
              </svg>
              Continue with Google
            </span>
          </button>
        </div>

        <div class="pt-4 w-full">
          <button
            @click="openMicrosoftLogin"
            class="py-2 mx-auto rounded-full flex justify-center items-center border border-gray-300 w-full text-gray-900 text-xs"
          >
            <span class="flex items-center">
              <svg
                class="w-5 h-5 mr-2"
                viewBox="0 0 23 23"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path fill="#f3f3f3" d="M0 0h23v23H0z"></path>
                <path fill="#f35325" d="M1 1h10v10H1z"></path>
                <path fill="#81bc06" d="M12 1h10v10H12z"></path>
                <path fill="#05a6f0" d="M1 12h10v10H1z"></path>
                <path fill="#ffba08" d="M12 12h10v10H12z"></path>
              </svg>
              Continue with Microsoft
            </span>
          </button>
        </div>

        <div class="flex justify-center py-7">
          <span class="text-black text-lg font-semibold cursor-pointer"
            >New to Popl?
            <span class="text-sky-500 font-semibold">Create account</span></span
          >
        </div>
      </div>
    </div>

    <div class="h-screen w-1/2 relative">
      <div class="w-full flex justify-end main-image">
        <img
          alt="trusted by"
          class="w-96 h-80 flex justify-end"
          src="~/assets/cutoff.png"
        />
      </div>
      <div
        class="absolute w-1/2 trusted-wraper flex flex-col justify-center items-center z-10"
      >
        <h4 class="text-gray-900 text-lg text-center font-medium tracking-wide">
          Trusted By
        </h4>

        <img src="~/assets/trustedBy.png" alt="trusted by" class="h-24 mt-8" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: "",
      password: "",
      passwordVisible: false,
    };
  },
  methods: {
    login() {
      console.log("Login clicked");
    },
    togglePasswordVisibility() {
      this.passwordVisible = !this.passwordVisible;
    },
    openGoogleLogin() {
      const authUrl =
        "https://accounts.google.com/o/oauth2/auth/oauthchooseaccount?response_type=code&client_id=1016915496422-0psqeusnp7ldabum6euge875kfii7nu6.apps.googleusercontent.com&redirect_uri=https%3A%2F%2Fpoplco.firebaseapp.com%2F__%2Fauth%2Fhandler&state=AMbdmDmbnO80h13w1ZIZGHvKSDA9ZGu4lbldiX8TlF2o-XJLLUZeo0X2zdhQtqWI7wyt5SlXYtMNE-uoN2oGbl4FSp89VhtOatKsZXmCtAQbCvbZfRVFso9xZl0yeL1ouwWktIFgXxOtOOV5Y6_22NwM6i8D9OIYCnpcR-nT5UC0HS5ViM5xTGZpbhc5CGQPX-yBkLmkL1dl2OhYQotersg9XTkphUEiltyoCY_i3PNYkV2LrEXH6AqVVt2DMoNyc8zROUKjPiKMhEHwVmCjFPy8eDJHHdWC2lLNh8cnUjgbKad_URzXbX2oDiKwY5KFCw&scope=openid%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fuserinfo.email%20profile&context_uri=https%3A%2F%2Fdash.popl.co&service=lso&o2v=1&flowName=GeneralOAuthFlow";

      const width = 500;
      const height = 600;
      const left = window.innerWidth / 2 - width / 2;
      const top = window.innerHeight / 2 - height / 2;
      const options = `width=${width},height=${height},left=${left},top=${top},scrollbars=yes`;

      window.open(authUrl, "Google Login", options);
    },
    openMicrosoftLogin() {
      const authUrl =
        "https://login.microsoftonline.com/common/oauth2/v2.0/authorize?client_id=b906a008-63c6-415e-8698-31a6f908313d&scope=openid%20profile%20User.Read%20offline_access&redirect_uri=https%3A%2F%2Fdash.popl.co%2F&client-request-id=f7b54162-97d8-4755-bd32-3bac4f953a9b&response_mode=fragment&response_type=code&x-client-SKU=msal.js.browser&x-client-VER=2.32.2&client_info=1&code_challenge=hdgVPncCnl7XNUqEGV6mVY1iv0LtGEKhMXDwBZOEsZk&code_challenge_method=S256&prompt=select_account&nonce=8ed7d88e-db80-4159-a7ec-b4d9b2ce0367&state=eyJpZCI6IjU4M2U0M2ExLTcyY2UtNDk0Yi1hZDkyLWM2MTU4NDc0ZGUxNCIsIm1ldGEiOnsiaW50ZXJhY3Rpb25UeXBlIjoicG9wdXAifX0%3D";

      const width = 500;
      const height = 600;
      const left = window.innerWidth / 2 - width / 2;
      const top = window.innerHeight / 2 - height / 2;
      const options = `width=${width},height=${height},left=${left},top=${top},scrollbars=yes`;

      window.open(authUrl, "Microsoft Login", options);
    },
  },
};
</script>

<style>
* {
    box-sizing: border-box;
    font-family: Inter,Open Sans,sans-serif;
    margin: 0;
    padding: 0;
}
.trusted-wraper {
  position: absolute;
  transform: translateX(-50%);
  top: calc(100vh - 300px);
  left: 50%;
  min-width: 560px;
}

@media (max-height: 850px) {
  .trusted-wraper {
    top: calc(100vh - 230px);
  }
}
@media (max-height: 500px) {
  .main-image img {
    width: 63px;
    height: 55px;
  }
}
</style>
