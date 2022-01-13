<template>
    <footer class="footer">
        
            <div class="container">
                <FooterAddress />
                <FooterExplore :exploreLinks="exploreLinks" />
                <FooterInfo :infos="infos" />
                <FooterInstagram :images="images" />
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

                ],
                // images: [
                //     {
                //         id: "01",
                //         url: 'src/assets/img/120012142_177596140500760_8623485824101406058_n.jpg'
                //     },
                //     {
                //         id: "02",
                //         url: 'src/assets/img/120084500_197897808368764_8114555493043279565_n.jpg'
                //     },
                //     {
                //         id: "03",
                //         url: 'src/assets/img/120099363_364334431619755_7198812647386067017_n.jpg'
                //     }
                // ]
            }
        }
}
</script>

<style lang="scss" scoped>
footer{
    // border-top: 1px solid blue;
    padding: 20px;    
}



</style>