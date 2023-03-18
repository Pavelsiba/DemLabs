<template>
  <div class="relative flex min-h-screen">
    <!--sidebar-->
    <div class="sidebar">
      <div class="h-10">
        <Logo name="logo" class="w-12 h-12" />
      </div>
      <nav class="font-nav">
        <NuxtLink to="/" class="link"
          ><Wallet name="wallet" class="w-6 h-3.5 mr-5"></Wallet>
          <span class="text-white">Wallet</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Dex name="dex" class="w-6 h-6 mr-5"></Dex>
          <span class="text-white">DEX</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Txexplorer name="txexplorer" class="w-6 h-6 mr-5"></Txexplorer>
          <span class="text-white">TX explorer</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Certificates name="certificates" class="w-6 h-6 mr-5"></Certificates>
          <span class="text-white">Certificates</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Tokens name="tokens" class="w-6 h-6 mr-5"></Tokens>
          <span class="text-white">Tokens</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Vclients name="vclients" class="w-6 h-6 mr-5"></Vclients>
          <span class="text-white">VPN client</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Vservice name="vservice" class="w-6 h-6 mr-5"></Vservice>
          <span class="text-white">VPN service</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Conslesvg name="conslesvg" class="w-6 h-6 mr-5"></Conslesvg>
          <span class="text-white">Console</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Logs name="logs" class="w-6 h-6 mr-5"></Logs>
          <span class="text-white">Logs</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Settings name="settings" class="w-6 h-6 mr-5"></Settings>
          <span class="text-white">Settings</span>
        </NuxtLink>
        <NuxtLink to="/" class="link"
          ><Dapps name="dapps" class="w-6 h-6 mr-5"></Dapps>
          <span class="text-white">Dapps</span>
        </NuxtLink>
      </nav>
    </div>
    <!--Main Content -->
    <div class="">
      <!--Header-->
      <div class= "search">Search</div>
      <!--Content-->
      <div class="p-8 text-cyan-700 font-extrabold">Content</div>
    </div>
  </div>
</template>

<script>
import Logo from "./Icons/Logo.vue";
import Wallet from "./Icons/Wallet.vue";
import Dex from "./Icons/Dex.vue";
import Txexplorer from "./Icons/Txexplorer.vue";
import Certificates from "./Icons/Certificates.vue";
import Tokens from "./Icons/Tokens.vue";
import Vclients from "./Icons/Vclients.vue";
import Vservice from "./Icons/Vservice.vue";
import Conslesvg from "./Icons/Conslesvg.vue";
import Logs from "./Icons/Logs.vue";
import Settings from "./Icons/Settings.vue";
import Dapps from "./Icons/Dapps.vue";

export default {
  components: {
    Logo,
    Wallet,
    Dex,
    Txexplorer,
    Certificates,
    Tokens,
    Vclients,
    Vservice,
    Conslesvg,
    Logs,
    Settings,
    Dapps
  },
};
</script>

<style scoped>
a:hover {
  box-shadow: 1px 1px 0px rgba(107, 102, 126, 0.49), inset 3px 3px 5px rgba(8, 7, 13, 0.25);
}

.font-nav {
  font-family: "Quicksand", sans-serif;
  font-style: normal;
  font-size: 13px;
  line-height: 16px;
}
</style>