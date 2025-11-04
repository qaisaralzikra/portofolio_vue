<template>
  <footer class="overflow-x-hidden bg-color-sec py-20 grid">
    <div class="flex flex-col gap-3">
      <div class="font-bold text-center">
        <span class="color-font-primary md:text-[48px] text-[28px]"
          >Mari <i class="color-font-normal md:text-[48px] text-[28px]">Berkolaborasi</i></span
        >
      </div>
      <div class="grid justify-center">
        <span class="h-[10px] bg-primary-crem md:w-[400px] w-[300px] rounded-[20px]"></span>
      </div>
      <div class="text-center grid justify-center">
        <div class="md:w-[700px] w-[340px]">
          <span class="font-medium md:text-[24px] text-[16px] color-font-normal"
            >Punya proyek menarik? Mari diskusikan bagaimana Saya bisa membantu mewujudkan ide
            Anda</span
          >
        </div>
      </div>
    </div>
    <div class="md:mt-[100px] mt-[50px] flex md:flex-row flex-col md:gap-[150px] gap-[80px] justify-center">
      <div class="flex flex-col md:gap-[150px] gap-[80px] ms-5 md:ms-0">
        <div class="flex flex-col gap-16">
          <div class="flex flex-row items-center md:gap-8 gap-5">
            <div
              class="md:w-[70px] md:h-[70px] w-[50px] h-[50px] bg-hijau rounded-[10px] border-4 border-color-hijau shadow-hijau grid justify-center"
            >
              <p class="ri-mail-fill md:text-[40px] text-[30px] color-font-normal"></p>
            </div>
            <div class="flex flex-col md:gap-1 gap-0">
              <span class="font-bold md:text-[24px] text-[18px] color-font-normal">Email</span>
              <div class="h-[4px] w-[100px] bg-primary-crem rounded-[10px]"></div>
              <span class="font-medium md:text-[15px] text-[14px] color-font-normal opacity-75"
                >qaisaralzikrah@gmail.com</span
              >
            </div>
          </div>
          <div class="flex flex-row items-center md:gap-8 gap-5">
            <div
              class="md:w-[70px] md:h-[70px] w-[50px] h-[50px] bg-hijau rounded-[10px] border-4 border-color-hijau shadow-hijau grid justify-center"
            >
              <p class="ri-phone-fill md:text-[40px] text-[30px] color-font-normal"></p>
            </div>
            <div class="flex flex-col md:gap-1 gap-0">
              <span class="font-bold md:text-[24px] text-[18px] color-font-normal">Telepon</span>
              <div class="h-[4px] w-[100px] bg-primary-crem rounded-[10px]"></div>
              <span class="font-medium md:text-[15px] text-[14px] color-font-normal opacity-75"
                >+62 89685482284</span
              >
            </div>
          </div>
          <div class="flex flex-row items-center md:gap-8 gap-5">
            <div
              class="md:w-[70px] md:h-[70px] w-[50px] h-[50px] bg-hijau rounded-[10px] border-4 border-color-hijau shadow-hijau grid justify-center"
            >
              <p class="ri-map-pin-fill md:text-[40px] text-[30px] color-font-normal"></p>
            </div>
            <div class="flex flex-col md:gap-1 gap-0">
              <span class="font-bold md:text-[24px] text-[18px] color-font-normal">Lokasi</span>
              <div class="h-[4px] w-[100px] bg-primary-crem rounded-[10px]"></div>
              <span class="font-medium md:text-[15px] text-[14px] color-font-normal opacity-75"
                >Perumahan Dosen Unhas, Tamalanrea</span
              >
            </div>
          </div>
        </div>

        <div class="flex gap-5 flex-col">
          <div class="font-bold md:text-[40px] text-[30px]">
            <span class="color-font-primary"
              >Ikuti <i class="color-font-normal font-bold md:text-[40px] text-[30px]">Saya</i></span
            >
          </div>
          <div class="flex flex-row gap-16">
            <div
              class="md:w-[70px] md:h-[70px] w-[50px] h-[50px] bg-hijau rounded-[10px] border-4 border-color-hijau shadow-hijau grid justify-center"
            >
              <p class="ri-instagram-fill md:text-[40px] text-[30px] color-font-normal"></p>
            </div>
            <div
              class="md:w-[70px] md:h-[70px] w-[50px] h-[50px] bg-hijau rounded-[10px] border-4 border-color-hijau shadow-hijau grid justify-center"
            >
              <p class="ri-whatsapp-fill md:text-[40px] text-[30px] color-font-normal"></p>
            </div>
            <div
              class="md:w-[70px] md:h-[70px] w-[50px] h-[50px] bg-hijau rounded-[10px] border-4 border-color-hijau shadow-hijau grid justify-center"
            >
              <p class="ri-linkedin-box-fill md:text-[40px] text-[30px] color-font-normal"></p>
            </div>
          </div>
        </div>
      </div>
      <div class="grid justify-center ">
        <div
          class="md:w-[545px] w-[340px] rounded-[30px] border-[3px] border-solid border-color-crem-primary shadow-hijau bg-hijau"
        >
          <form action="" class="md:py-10 md:px-10 py-5 px-5 flex flex-col md:gap-8 gap-5">
            <div class="flex flex-col gap-2">
              <label for="" class="font-bold md:text-[20px] color-font-normal">Nama Lengkap</label>
              <input
                type="text"
                required
                class="h-[45px] px-3 py-3 text-white rounded-[10px] border-2 border-solid border-color-crem-primary shadow-hijau"
                style="background-color: rgba(220, 215, 201, 0.1)"
              />
            </div>
            <div class="flex flex-col gap-2">
              <label for="" class="font-bold md:text-[20px] color-font-normal">Email</label>
              <input
                type="text"
                required
                class="h-[45px] px-3 py-3 text-white rounded-[10px] border-2 border-solid border-color-crem-primary shadow-hijau"
                style="background-color: rgba(220, 215, 201, 0.1)"
              />
            </div>
            <div class="flex flex-col gap-2">
              <label for="" class="font-bold md:text-[20px] color-font-normal">Subjek</label>
              <input
                type="text"
                required
                class="h-[45px] px-3 py-3 text-white rounded-[10px] border-2 border-solid border-color-crem-primary shadow-hijau"
                style="background-color: rgba(220, 215, 201, 0.1)"
              />
            </div>
            <div class="flex flex-col gap-2">
              <label for="" class="font-bold md:text-[20px] color-font-normal">Pesan</label>
              <textarea
                type="text"
                required
                class="h-[160px] px-3 text-white rounded-[10px] border-2 border-solid border-color-crem-primary shadow-hijau py-3"
                style="background-color: rgba(220, 215, 201, 0.1)"
              ></textarea>
            </div>
            <button
              type="submit"
              class="w-full bg-normal text-[16px] border-2 border-solid border-color-crem-primary color-font-hijau py-3 px-6 rounded-lg font-semibold transition-colors glow-effect"
            >
              Kirim Pesan
            </button>
          </form>
        </div>
      </div>
    </div>
    <div class="grid justify-center mt-[100px]">
      <div
        class="md:w-[700px] rounded-[30px] bg-normal text-center md:px-[70px] px-7 mx-5 flex flex-col md:gap-8 gap-5 md:py-10 py-5"
      >
        <div>
          <span class="font-bold md:text-[40px] text-[30px] color-font-primary">VisionStack</span>
          <br />
          <span class="font-semibold md:text-[24px] text-[16px] color-font-hijau"
            >Menciptakan Pengalaman Web Yang Luar Biasa</span
          >
        </div>
        <div class="h-[10px] w-full bg-primary-crem rounded-[10px]"></div>
        <div>
          <span class="font-medium md:text-[24px] text-[16px] color-font-hijau"
            >© 2025 VisionStack. Semua hak dilindungi.</span
          >
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup></script>

<style lang="scss" scoped></style>
