<template>
    <div>
        <b-container fluid class="bv-example-row">
            <b-row>
                <b-col class="container" style="padding: 15px;" sm="12" md="8">
                    <h1>
                        Hello
                    </h1>
                </b-col>
                <b-col class="container" hidden-xs style="color: black; padding: 15px;" md="4">
                    <BioCard />
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
import BioCard from "./BioCard"

export default {
    components: {
        BioCard
        }
}
</script>

<style>

</style>