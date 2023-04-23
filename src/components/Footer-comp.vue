<template>
    <v-footer dark paddless>
        <v-card flat tile class="black white--text py-12 px-5" width="100%">
            <v-row>
                <v-col cols="12" sm="4">
                    <v-card-text class="white--text pt-0">
                        <h3>Julio's Ecommerce</h3>
                    </v-card-text>

                    <v-card-text class="grey--text pt-0">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.<br>
                        Accusamus aliquam aut voluptate nesciunt harum.
                    </v-card-text>
                    <v-toolbar flat color="transparent">
                        <h5>Guia</h5>
                        <h5 class="ml-4">Termos de Uso</h5>
                        <h5 class="ml-4">Politica de Privacidade</h5>
                    </v-toolbar>

                    <v-card-text class="grey--text">&#169; 2021 - 2023</v-card-text>
                </v-col>

                <v-col col="12" sm="2">
                    <v-card-text class="white--text pt-0">
                        <h3>Ajuda</h3>
                    </v-card-text>

                    <v-card-text class="grey--text">
                        Status do Pedido
                    </v-card-text>

                    <v-card-text class="grey--text mt-n4">
                        Entrega e Devolução
                    </v-card-text>

                    <v-card-text class="grey--text mt-n4">
                        Opções de Pagamento
                    </v-card-text>

                    <v-card-text class="grey--text mt-n4">
                        Contate-nos
                    </v-card-text>
                </v-col>

                <v-col col="12" sm="2">
                    <v-card-text class="white--text pt-0">
                        <h3>Sobre Nós</h3>
                    </v-card-text>

                    <v-card-text class="grey--text">
                        Trabalhe Conosco
                    </v-card-text>

                    <v-card-text class="grey--text mt-n4">
                        Sustentabilidade
                    </v-card-text>

                    <v-card-text class="grey--text mt-n4">
                        Serviço
                    </v-card-text>
                </v-col>

                <v-col cols="12" sm="4">
                    <v-card-text class="pt-0">
                        <v-btn v-for="icon in icons" :key="icon" class="mx-1 white--text" icon>
                            <v-icon size="24px">{{ icon }}</v-icon>
                        </v-btn>
                    </v-card-text>

                    <v-card-text class="grey--text mt-14">
                        Metodos de Pagamento:
                    </v-card-text>
                    <v-toolbar flat color="transparent">
                        <v-spacer></v-spacer>
                        <v-icon large>fab fa-cc-visa</v-icon>
                        <v-icon class="mx-2" large>fab fa-cc-paypal</v-icon>
                        <v-icon large>fab fa-cc-mastercard</v-icon>
                    </v-toolbar>
                </v-col>
            </v-row>
        </v-card>
    </v-footer>
</template>

<script>
export default {
    data: () => ({
        icons: [
            'mdi-facebook',
            'mdi-twitter',
            'mdi-linkedin',
            'mdi-instagram'
        ]
    })
}


</script>

<style lang="scss" scoped>

</style>