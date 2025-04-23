<template>
    <NavBar />
    <div id="ias93cg" class="gjs-row">
        <div id="ijuez9d" class="gjs-cell">
            <div id="icnbwsd" class="gjs-row">
                <div id="i625pjr" class="gjs-cell">
                    <div id="icyplkh">Get in touch<br></div>
                    <div id="i1v7gnh">Peppubuild lets you build anything for the web, without writing any code. Let us
                        know if you have any questions, concerns, or suggestions.</div>
                </div>
            </div>
            <div id="BUEr" class="new_home_web">
                <div class="responsive-container-block big-container"><img
                        src="https://workik-widget-assets.s3.amazonaws.com/widget-assets/images/aw65.png" class="imgBG">
                    <div class="responsive-container-block container">
                        <div id="i69b" class="responsive-cell-block wk-tab-12 wk-mobile-12 wk-desk-7 wk-ipadp-10 line">
                            <form method="get" class="form-box">
                                <div class="container-block form-wrapper">
                                    <div class="responsive-container-block">
                                        <div class="left4">
                                            <div id="i10mt-2"
                                                class="responsive-cell-block wk-ipadp-6 wk-tab-12 wk-mobile-12 wk-desk-6">
                                                <input type="text" id="ijowk-2" name="FirstName" placeholder="First Name"
                                                    class="input">
                                            </div>
                                            <div class="responsive-cell-block wk-desk-6 wk-ipadp-6 wk-tab-12 wk-mobile-12">
                                                <input type="text" id="indfi-2" name="Last Name" placeholder="Last Name"
                                                    class="input">
                                            </div>
                                            <div class="responsive-cell-block wk-desk-6 wk-ipadp-6 wk-tab-12 wk-mobile-12">
                                                <input type="text" id="ipmgh-2" name="Email" placeholder="Email Address"
                                                    class="input">
                                            </div>
                                            <div
                                                class="responsive-cell-block wk-desk-6 wk-ipadp-6 wk-tab-12 wk-mobile-12 lastPhone">
                                                <input type="text" id="imgis-2" name="PhoneNumber"
                                                    placeholder="Phone Number" class="input">
                                            </div>
                                        </div>
                                        <div id="i634i-2"
                                            class="responsive-cell-block wk-tab-12 wk-mobile-12 wk-desk-12 wk-ipadp-12">
                                            <textarea id="i5vyy-2" placeholder="Message" class="textinput"></textarea>
                                        </div>
                                    </div><a href="#" id="w-c-s-bgc_p-1-dm-id" class="send">
                                        Send
                                    </a>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <div id="ia0lvrl" class="gjs-row">
                <div id="i94jbxr" class="gjs-cell">
                    <FooterView />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import NavBar from '../components/NavBar.vue'
import FooterView from '../components/FooterView.vue'

export default {
    name: 'ContactView',
    components: { NavBar, FooterView },
}
</script>