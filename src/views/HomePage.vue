<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <div class="grid gap-[20px] p-8">
        <!-- Header -->
        <div class="flex justify-between items-center">
          <!-- Profile (to left) -->
          <img class="w-12 h-12 rounded-full" src="https://i.ibb.co/zrVsNG1/Image-48.png" alt="Profile" />

          <!-- Notify Btn (to right) -->
          <div class="w-10 h-10 flex justify-center items-center bg-[#4d4a4f] rounded-[11px]">
            <IconBell class="w-[22px] h-[22px] text-[#eeeeee]" />
          </div>
        </div>

        <div class="w-full">
          <!-- Container with the gradient -->
          <div
            class="w-full h-[140px] p-4 bg-gradient-to-b from-[#A552BA] to-[#ce4f51] rounded-lg flex flex-col justify-center items-center gap-1">
            <div class="flex justify-start items-center gap-x-5">
              <!-- Title and description -->
              <div class="w-full sm:w-[150px] flex-col justify-start items-start inline-flex">
                <div class="h-[35px] text-[#eeeeee] text-4xl font-semibold font-inter tracking-tight mb-[13px]">
                  VAULT
                </div>
                <div class="text-[#eeeeee] text-sm font-light font-inter tracking-tight">
                  45 Secure Passwords
                </div>
              </div>
              <!-- Icon of LOCKER -->
              <div>
                <IconLockPassword class="w-[110px] h-[110px] text-[#eeeeee] stroke-1" />
              </div>
            </div>
          </div>
        </div>

        <div>
          <div class="text-white text-lg font-medium font-inter tracking-tight mb-[10px]">Category</div>
          <div class="grid grid-cols-2 gap-[10px]">
            <!-- Box 1 -->
            <div class="w-[158px] h-[124px] relative bg-[#4d4a4f] rounded-[10px]">
              <div class="w-[30px] h-[30px] left-[10px] top-[20px] absolute bg-[#77737b] rounded"></div>
              <div
                class="w-[17.50px] h-[17.50px] pl-[1.46px] pr-[1.82px] pt-[1.46px] pb-[1.82px] left-[16px] top-[26px] absolute justify-center items-center inline-flex">
                <IconApps class="w-[15px] h-[15px] text-[#eeeeee]" />
              </div>
              <div
                class="left-[10px] top-[64px] absolute text-[#eeeeee] text-base font-normal font-inter tracking-tight">
                Apps</div>
              <div class="left-[10px] top-[89px] absolute text-[#eeeeee] text-xs font-light font-inter tracking-tight">
                15 Passwords</div>
            </div>

            <!-- Box 2 -->
            <div class="w-[158px] h-[124px] relative bg-[#4d4a4f] rounded-[10px]">
              <div
                class="left-[10px] top-[64px] absolute text-neutral-100 text-base font-normal font-inter tracking-tight">
                Finances</div>
              <div
                class="left-[10px] top-[89px] absolute text-neutral-100 text-xs font-light font-inter tracking-tight">
                15 Passwords</div>
              <div class="w-[30px] h-[30px] left-[10px] top-[20px] absolute bg-[#78737b] rounded"></div>
              <div
                class="w-[17.50px] h-[17.50px] pl-[1.46px] pr-px pt-[2.19px] pb-[1.33px] left-[16px] top-[26px] absolute justify-center items-center inline-flex">
                <IconWallet class="w-[15px] h-[15px] text-[#eeeeee]" />
              </div>
            </div>

            <!-- Box 3 -->
            <div class="w-[158px] h-[124px] relative bg-[#4d4a4f] rounded-[10px]">
              <div class="w-[30px] h-[30px] left-[10px] top-[20px] absolute bg-[#78737b] rounded"></div>
              <div
                class="w-[17.50px] h-[17.50px] pl-[0.73px] pr-[0.90px] pt-[2.92px] pb-[2.34px] left-[16px] top-[26px] absolute justify-center items-center inline-flex">
                <IconUsersGroup class="w-[15px] h-[15px] text-[#eeeeee]" />
              </div>
              <div
                class="left-[10px] top-[64px] absolute text-[#eeeeee] text-base font-normal font-inter tracking-tight">
                Socials</div>
              <div class="left-[10px] top-[89px] absolute text-[#eeeeee] text-xs font-light font-inter tracking-tight">
                15 Passwords</div>
            </div>

            <!-- Box 4 -->
            <div class="w-[158px] h-[124px] relative bg-[#4d4a4f] rounded-[10px]">
              <div class="w-[30px] h-[30px] left-[10px] top-[20px] absolute bg-[#78737b] rounded"></div>
              <div
                class="w-[17.50px] h-[17.50px] pl-[0.73px] pr-[0.90px] pt-[2.92px] pb-[2.34px] left-[16px] top-[26px] absolute justify-center items-center inline-flex">
                <IconSocial class="w-[15px] h-[15px] text-[#eeeeee]" />
              </div>
              <div
                class="left-[10px] top-[64px] absolute text-neutral-100 text-base font-normal font-inter tracking-tight">
                All Services</div>
              <div class="left-[10px] top-[89px] absolute text-[#eeeeee] text-xs font-light font-inter tracking-tight">
                45 Passwords</div>
            </div>
          </div>
        </div>



        <div>
          <div class="w-full text-white text-lg font-medium font-inter tracking-tight mb-[11px]">
            Recently Added
          </div>
          <div class="w-full grid gap-3">
            <!-- Card 1 -->
            <div class="w-full h-16 relative bg-[#4d4a4f] rounded-[10px] shadow-md flex items-center px-4">
              <div class="w-10 h-10 bg-[#3b5998] rounded-[10px] flex items-center justify-center shadow-sm">
                <!-- Placeholder logo or icon -->
              </div>
              <div class="ml-4 flex-1">
                <div class="text-[#eeeeee] text-base font-normal font-inter tracking-tight">
                  Facebook
                </div>
                <div class="text-[#eeeeee] text-[13px] font-light font-inter tracking-tight">
                  user123@gmail.com
                </div>
              </div>
              <div class="w-6 h-6 transform rotate-180">
                <!-- Placeholder for dropdown icon -->
                <IconCopy class="w-[20px] h-[20px] text-[#eeeeee]" />
              </div>
            </div>
            <!-- Card 2 -->
            <div class="w-full h-16 relative bg-[#4d4a4f] rounded-[10px] shadow-md flex items-center px-4">
              <div class="w-10 h-10 bg-[#ea4c89] rounded-[10px] flex items-center justify-center shadow-sm">
                <!-- Placeholder logo or icon -->
              </div>
              <div class="ml-4 flex-1">
                <div class="text-white text-base font-normal font-inter tracking-tight">
                  Dribbble
                </div>
                <div class="text-white text-[13px] font-light font-inter tracking-tight">
                  user123@gmail.com
                </div>
              </div>
              <div class="w-6 h-6 transform rotate-180">
                <!-- Placeholder for dropdown icon -->
                <IconCopy class="w-[20px] h-[20px] text-[#eeeeee]" />
              </div>
            </div>
            <!-- Card 3 -->
            <div class="w-full h-16 relative bg-[#4d4a4f] rounded-[10px] shadow-md flex items-center px-4">
              <div class="w-10 h-10 bg-[#fbad50] rounded-[10px] flex items-center justify-center shadow-sm">
                <!-- Placeholder logo or icon -->
              </div>
              <div class="ml-4 flex-1">
                <div class="text-[#eeeeee] text-base font-normal font-inter tracking-tight">
                  Instagram
                </div>
                <div class="text-white text-[13px] font-light font-inter tracking-tight">
                  user123@gmail.com
                </div>
              </div>
              <div class="w-6 h-6 transform rotate-180">
                <!-- Placeholder for dropdown icon -->
                <IconCopy class="w-[20px] h-[20px] text-[#eeeeee]" />
              </div>
            </div>
            <!-- Card 4 -->
            <div class="w-full h-16 relative bg-[#4d4a4f] rounded-[10px] shadow-md flex items-center px-4">
              <div class="w-10 h-10 bg-[#232324] rounded-[10px] flex items-center justify-center shadow-sm">
                <!-- Placeholder logo or icon -->
              </div>
              <div class="ml-4 flex-1">
                <div class="text-[#eeeeee] text-base font-normal font-inter tracking-tight">
                  Google
                </div>
                <div class="text-white text-[13px] font-light font-inter tracking-tight">
                  user123@gmail.com
                </div>
              </div>
              <div class="w-6 h-6 transform rotate-180">
                <!-- Placeholder for dropdown icon -->
                <IconCopy class="w-[20px] h-[20px] text-[#eeeeee]" />
              </div>
            </div>
          </div>
        </div>

        <!-- Btn for add new credentials -->
        <div
          class="w-[50px] h-[50px] fixed bottom-4 right-4 bg-[#dc6062] rounded-full flex justify-center items-center">
          <IconPlus class="w-[30px] h-[30px] text-[#eeeeee]" stroke-width="3" />
        </div>

      </div>
    </ion-content>
  </ion-page>
</template>

<script setup>
  import { IonContent, IonPage } from '@ionic/vue';
  import { IconLockPassword, IconBell, IconPlus, IconApps, IconWallet, IconUsersGroup, IconSocial, IconCopy } from '@tabler/icons-vue';
</script>