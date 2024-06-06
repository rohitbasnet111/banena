<template>
  <v-app>
    <navbar />
    <section>
      <v-container>
        <v-card hover>
          <v-img src="https://i.ytimg.com/vi_webp/gw_cglJHnFY/maxresdefault.webp"></v-img>
          <v-title
            ><h1>Genshin Impact for PlayStation®5 Is Here - Download Now!</h1>
            <p>
              Genshin Impact for PlayStation®5 Is Here - Download Now!<br />
              Download on the PlayStation® Product Page >>><br />
              <a href="www.playstation.com/games/genshin-impact" target="_blank"
                >www.playstation.com/games/genshin-impact</a
              >
            </p>
            <a
              href="https://www.playstation.com/country-selector/index.html"
              target="_blank"
              ><v-img
                rounded
                hover
                height="90px"
                src="https://webstatic.hoyoverse.com/upload/event/2023/06/16/2577fdf3178c59e64861b4d41c8def13_1289788108854828378.png"
              ></v-img
            ></a>
          </v-title>
        </v-card>
      </v-container>
    </section>

    <section class="py-16">
      <div>
        <h1>Other Platforms:</h1>
      </div>

      <div class="d-flex justify-center items-center">
        <h1>
          FOR ANDROID
          <v-img
            height="20px"
            src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAflBMVEX///8AAACOjo6KiopkZGS/v7/k5ORvb2/39/fy8vKIiIjz8/OdnZ36+vrX19d5eXm4uLgwMDDq6upWVlbFxcWsrKzR0dFBQUFUVFTNzc08PDxPT08ZGRkPDw9HR0djY2MiIiJ/f3+ysrI2NjaioqKUlJQgICApKSkVFRVzc3MeEm9UAAAG2klEQVR4nO2d6XqyPBBAxa1iwd22blW6vLb3f4Mf2LLpJCYwmczXZ85PgTw5AiHJZOl0kJjt5wustDqL+X6GlhgSj0EQvKOltk1TG6GlhkSapwDrf59liSGlhUeUZmqPlNY+TStCSguRQ5qtD5SU1mlKB5SUcHnLHq0YIaE4S+gNISF0zmnGugjpfKbpnBHSwWeV/fdh62TCLJkVQn4c8Jpm7bt1KtM0lVeE3Lhgkv37w5aJDLNEJij5ccAxzdyyZRrLNI0jSm5csMj+/6dWSTxhPAcOyd6hbasUntMUpki5cUFWOw0GwIFwuFpHSf+4zDj2k2i9GkLF7gCnPHZI9i37qv8UDrrZuwWx7A6ubLL62idddpsQ1Opuo0EyV9jlvCeDshWxZlnlrrMu626LaHvHLuc5+mlaXupra5/ZN2H/W3eb7Qz1fnjJWl7ZM/7Pt8BdLmXFpGul90P3UmOAyilmvDeQK8HrJ3DHrJUhu+6ZG8JpK8EgSNj1z9SJWvpl4HQUuGFzQhAMgjnbpkXbB7Qk8a0C8oTml7Jn2Lz4xBQM+L2Nsapy3Zy+b6cai3/ogmlDE6NrEgnUV7DkwOZlXLkRDNh0ZwycCTLpdHN3B5kobpwKBgFe2LUhQ8eCweHRr+DItWBaS/Vr2K65a4bXT/8DlKNjFB0bqRyjzz70u8dw8BuQne2lB3Rh2s1WufBSpsTPwKF2gYIWLIDMFF1ltk3FU34hUAE8+Kq/QX93Edq0rckV9wn6vj74EQR7LMrDdpXxU3khdNhLH2MI5aRStL9aGe7KC8E4AL3fTzj0hsogEegZVvNcXniAjvfoBRW1tSKWZFsXKDoRwWfDRzNDEVMq+pDGlobj/EJFfxZ55FvZovjttLbv+b53IfVNVIcFx8M4HibWguntH8ajibpHsu0QCEvcNgphaJuKdp8CHEgHMDhvFYJQ1t0SL4aUncReBCmjp677ZlTQfTDAhi8BdE1hT4J0XTYTX4Zk48EwQtnNoGom4kfSTKGKDXsTrLYiXQJ1QFFBY+ij1p1D80XEjtjbQFPUJB4Nab75Lx4Nx/ezhwDOwKdm0HQNexRsORHAkNin4YnCkCAoqubrfv7ao+ixJYLC8HHc9QiF4R/jMWQ+KLkzCpsP1lgl2ywMdO6vuVqGH/1sau5hmzSpzc2qQa4xo2GCBaNaBMB2qk14Hf2rTMwd9LyVM73KvboO4WytRk8BPTFlndc2boZJWS/t3R60GLIBdtoXikDaZPS0mTCO3SjqZfmDysFQEWU0LVbBgUlBERlhYKiqV72YCSq7Q3tsDL9VxzdGhurOwhETQ3XVeKcTy9G0HWZMDNfqE0zeRM2w7W8mhprIkEnlRtOVdmZiuFefYDIRXPkWB7+tM/+GmhNMgv2qb0UGf0OTAcViKIZOEUMxFEMxdI8YiqEYiqF7xFAMxVAM3SOGYiiGYugeMRRDMRRD94ihGIqhGLpHDMVQDMXQPWIohmIohu4RQzEUQzF0jxiKoRiKoXvEUAzFUAzdg2KoWzKQv6HJAja6qdr8DU0WIfpQX/7KxFCzAq7JGqeaVRHHTAw1j5nRhHX15U9MDDW7EpgIqieRnjpMDDtn1XGzvYSVM6Xf2BgqlzU3XHJAUdbk62wxMFSVNcYLnMAz8vO1QzgYws+ZxbLt0F9UlFIcDMHFSYyWG8i53byiLIZZGAKKlrsnXC1bcKy8wjwMO/FV9dJ6P+9RZePpZW1tGyaGad2k0kjoNlrLahNNl7t+d3a1PBEbw7TAGXT7u+U0MlvSxBhGho4QQzEUQzH824Y0q3v6XM/brP3XFs06VM55IzH0tQdLBnLlRYHPpZKJVhndeROk2pnMftc4LMi2stSsl+aUM5Wgtx0uaMqZC4kXQdKdOn3sAEG8AWKzfanbQL49d/d+nlChqa/VmFB+Fne0G1jmPKk3DcXl29vW453OcDMoWOlu6npwja4C/7Iqz9vQ7wSsRDcC4HbBdN3GWN8ecm+CzvD2Ruj2MvW0l/pddKvXiqEY8kD38RBDMeRBIoY1xJAjf99QN25TDMWQB2JYRww5IoZ1xJAjuiEMYiiGPBDDOv9HQ104SgzFkAdiWEdnyDX2FGnybBddM5kJ6gPN7pfQvEDN2RFwOgc0dwWakqSZ6+oxqq1HOfERvCmah5o856ao8xwCZ6tveUKec1OUI0/hslEZFbfaJZ0W1Ux3ePKqajou15L0AjzeTTUsFB6o+k6aY1viOZBlddkPDvuH3llGxLfDhnTLHNw+1ifmgp3b/ij9sNfrgf9ca6Q1JtWX8e4kl7ham30mHAXcisX6YX4IvnY9swyveruv4DB/+HAygu0/+y2ThG3ZCKgAAAAASUVORK5CYII="
          ></v-img>
        </h1>
      </div>
      <div>
        <v-img
          rounded
          height="700px"
          src="https://img.tapimg.net/market/images/1f9b6bf1918f47765c21995f0a7f5789.jpg?imageView2/2/w/1080/h/1080/q/80/format/jpg/interlace/1/ignore-error/1"
        ></v-img>

        <a
          href="https://play.google.com/store/apps/details?id=com.miHoYo.GenshinImpact"
          target="_blank"
          ><v-img
            height="100px"
            rounded
            hover
            src="https://webstatic.hoyoverse.com/upload/event/2023/04/19/b844aa37a8f56c86dcb73ac608ef87bc_7486702195076102975.png"
          ></v-img></a
        >"
      </div>

      <div class="py-14 d-flex justify-center items-center">
        <h1>
          FOR IOS
          <v-img
            height="20px"
            src="data:image/png;base64,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"
          ></v-img>
        </h1>
      </div>
      <div>
        <v-img
          rounded
          height="700px"
          src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/66/05/e5/6605e569-2e39-cd10-673f-e601b346d2e5/ff3b20e9-f676-4c9b-b54d-8a2115c0c9bf_DE-4.jpg/643x0w.jpg"
        ></v-img>

        <a
          href="https://apps.apple.com/us/app/genshin-impact/id1517783697"
          target="_blank"
          ><v-img
            height="100px"
            rounded
            hover
            src="https://webstatic.hoyoverse.com/upload/event/2023/04/19/5dbe040157bb6434b0b18b8292282b32_3632237727328970001.png"
          ></v-img></a
        >"
      </div>
    </section>
  </v-app>
</template>

<script setup></script>

<style lang="scss" scoped></style>
