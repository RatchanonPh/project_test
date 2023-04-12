<template>
    <v-container fluid >
        <v-row >
            <v-col class="d-flex ">
                <label class="custom-file-upload" >
                    <div class="pp">  
                        <input type="file" />
                        <v-icon icon="mdi-camera"></v-icon><br>
                        <i class="fa fa-cloud-upload"></i> อัปโหลดรูปภาพ    
                    </div>
                </label>
            </v-col>
        </v-row>
    </v-container>
</template>

<script lang="ts" setup>
</script>

<style>
input[type="file"] {
    display: none;
}

.custom-file-upload {
    border: 1px solid #ccc;
    border-style: dashed;
    display: inline-block;
    padding: 55px;
    cursor: pointer;
    width: 65rem;
    height: 10rem;
}

.pp {
    text-align: center;
}
</style>