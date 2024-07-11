<script>
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Footer,
  },
};
</script>

<template>
  <main class="py-[85px] bg-lightGray sm:py-[139px]">
    <div
      class="bg-white mx-auto w-[85%] p-[14px] rounded-[13px] max-w-[320px] sm:rounded-[20px] sm:p-[16px] shadow-[0_25px_25px_0_rgba(0,0,0,0.04)]"
    >
      <img
        class="rounded-[15px]"
        src="./assets/image-qr-code.png"
        alt="qr code"
      />
      <div class="px-[10px] mt-[21px] sm:mt-[24px]">
        <h1
          class="text-center text-darkBlue font-bold text-[20.5px] leading-[28px] [word-spacing:-1.8px] sm:text-[22px]"
        >
          Improve your front-end skills by building projects
        </h1>
        <p
          class="text-center text-grayishBlue mt-[16px] text-[15px] leading-[20px] pb-[23px]"
        >
          Scan the QR code to visit Frontend Mentor and take your coding skills
          to the next level
        </p>
      </div>
    </div>
  </main>
  <Footer />
</template>
