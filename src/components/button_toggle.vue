<template>
    <v-card variant="outlined" height="250">
        <div class="d-flex ">
            <v-btn-toggle v-model="formatting" multiple variant="outlined" divided>
                <v-btn>
                    <v-icon icon="mdi-format-italic"></v-icon>
                </v-btn>

                <v-btn>
                    <v-icon icon="mdi-format-bold"></v-icon>
                </v-btn>

                <v-btn>
                    <v-icon icon="mdi-format-underline"></v-icon>
                </v-btn>

                <v-btn>
                    <div class="d-flex align-center flex-column justify-center">
                        <v-icon icon="mdi-format-color-text"></v-icon>

                        <v-sheet tile height="4" width="26" color="purple" ></v-sheet>
                    </div>
                </v-btn>
            </v-btn-toggle>

            <v-btn-toggle v-model="alignment" variant="outlined" divided>
                <v-btn>
                    <v-icon icon="mdi-format-align-center"></v-icon>
                </v-btn>

                <v-btn>
                    <v-icon icon="mdi-format-align-left"></v-icon>
                </v-btn>

                <v-btn>
                    <v-icon icon="mdi-format-align-right"></v-icon>
                </v-btn>
            </v-btn-toggle>
        </div>

        <v-sheet class="text-center" >
            <v-textarea v-model="value" variant="outlined" auto-grow full-width  rows="7" ></v-textarea>
        </v-sheet>
    </v-card>
</template>

<script lang="ts">
export default {
    data: () => ({
        alignment: 1,
        formatting: [],
        numbers: [1, 2, 3, 4, 5, 6, 7, 8, 9, 0],
        letters: 'qwertyuiop'.split(''),
        value: ''
    }),
}
</script>

<style></style>