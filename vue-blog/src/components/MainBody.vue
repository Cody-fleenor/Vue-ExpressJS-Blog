<template>
    <div>
        <b-container fluid class="bv-example-row">
            <b-row>
                <b-col class="container" style="padding: 15px;" sm="12" md="7">
                    <b-card
                        title="Card Title"
                        img-src="https://picsum.photos/600/300/?image=25"
                        img-alt="Image"
                        img-top
                        tag="article"
                        class="mb-2"
                    >
                        <b-card-text>
                        Some quick example text to build on the card title and make up the bulk of the card's content.
                        </b-card-text>

                        <b-button href="#" variant="primary">Go somewhere</b-button>
                    </b-card>
                </b-col>
                <b-col class="container" style="color: black; padding: 15px;" sm="12" md="5">
                    <BioCard />
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
import BioCard from "./BioCard"
export default {
    components: BioCard
}
</script>

<style>

</style>