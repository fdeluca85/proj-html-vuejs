<template>
    <footer class="footer">
        
            <div class="container">
                <FooterAddress />
            <FooterExplore :exploreLinks="exploreLinks" />
            <FooterInfo :infos="infos" />
            <FooterInstagram />
            </div>
        
    </footer>
  
</template>

<script>
import FooterAddress from "../sections/FooterAddress.vue"
import FooterExplore from "../sections/FooterExplore.vue"
import FooterInfo from "../sections/FooterInfo.vue"
import FooterInstagram from "../sections/FooterInstagram.vue"

export default {
    name: "Footer",
    components: {
        FooterAddress,
        FooterExplore,
        FooterInfo,
        FooterInstagram
        },
        data(){
            return{
                exploreLinks: [
                    {
                        text: "Start here",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Success Story",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Blog",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Courses",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Contact us",
                        url: "#",
                        current: false
                    },
                ],
                infos: [
                    {
                        text: "Membership",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Purchase guide",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Privacy policy",
                        url: "#",
                        current: false
                    },
                    {
                        text: "Terms of service",
                        url: "#",
                        current: false
                    },

                ]
            }
        }
}
</script>

<style lang="scss" scoped>
footer{
    border-top: 1px solid blue;
}


</style>