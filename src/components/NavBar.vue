<template>
  <div id="ileg4d8-2" class="navbar navbar-expand-lg nav-contain">
    <div id="icruubr-2" class="container-fluid"><a href="/" id="iyaz8hz-2" class="navbar-brand"><img
          src="../assets/logo.png" id="i6ukl7o-2"></a><button type="button" data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent" id="i4dxoqi-2" class="navbar-toggler"><span id="iyls165-2"
          class="navbar-toggler-icon"></span></button>
      <div id="i6yq6ef-2" class="collapse navbar-collapse">
        <ul id="iv24gxz-2" class="navbar-nav me-auto mb-2 mb-lg-0">
          <li id="ixahy2b-2" class="nav-item"><a aria-current="page" href="/" id="it6bivs-2" class="nav-link active"><span
                id="ishq82j-2">Home</span></a></li>
          <li id="ipccc6k-2" class="nav-item"></li>
          <li id="i2dad0x-2" class="nav-item dropdown"><a href="#" role="button" data-bs-toggle="dropdown" id="il3z1jo-2"
              class="nav-link dropdown-toggle">Resources</a>
            <ul aria-labelledby="navbarDropdown" id="idpv7nu-2" class="dropdown-menu">
              <li id="ipiyx8k-2"><a href="https://docs.peppubuild.com" id="ioce80v-2"
                  class="dropdown-item">Documentation</a></li>
              <li id="ix1vc1i-2"><a href="https://blog.peppubuild.com" id="ik7jk5h-2" class="dropdown-item">Blog</a></li>
              <li id="ip3l60w-2">
                <hr id="i6vmgnf-2" class="dropdown-divider">
              </li>
              <li id="izgly9o-2"><a href="https://github.com/Peppu-Group/Peppubuild" id="ic46owf-2"
                  class="dropdown-item">Github</a></li>
            </ul>
          </li>
          <li id="i2dad0x-2" class="nav-item dropdown"><a href="#" role="button" data-bs-toggle="dropdown" id="il3z1jo-2"
              class="nav-link dropdown-toggle">Products</a>
            <ul aria-labelledby="navbarDropdown" id="idpv7nu-2" class="dropdown-menu">
              <li id="ipiyx8k-2"><a href="https://proctored.peppubuild.com" id="ioce80v-2" class="dropdown-item">Proctored by
                  Peppubuild</a></li>
              <li id="ipiyx8k-2"><a href="#" id="ioce80v-2" class="dropdown-item" @click="comingSoon()">Paytrack</a>
              </li>
              <li id="ix1vc1i-2"><a href="/products/peppubuild" id="ik7jk5h-2" class="dropdown-item">Peppubuild</a>
              </li>
              <li id="ip3l60w-2">
                <hr id="i6vmgnf-2" class="dropdown-divider">
              </li>
              <li id="izgly9o-2"><a href="#" id="ic46owf-2" @click="comingSoon()"
                  class="dropdown-item">Marine Tech</a></li>
            </ul>
          </li>
        </ul>
        <form id="iwozbj2-2" class="d-flex"><a href="https://calendly.com/ugochi-ukpai-peppubuild/30min" title="peppubuild" id="imbh0uo-2"
            class="btn btn-primary">Consult Us</a></form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',

  methods: {
    comingSoon() {
      Swal.fire('Coming Soon', 'This product is under review, if you are in our mailing list, we will let you know once it is ready via mail.', 'info')
    }
  }
}
</script>