<template>
    <v-card color="grey-lighten-3">
        <v-container>
            <v-sheet class="pa-12">
                <v-col>
                    <v-row class="d-flex">
                        <h3>ข้อมูลเกี่ยวกับทริป</h3>
                        <v-btn class="btn ml-auto ">
                            <p class="p_btn ">ถัดไป</p>
                        </v-btn>
                    </v-row>
                    <v-row class="mt-6">
                        <v-col class="d-flex justify-center">
                            <Uploat_img/>
                        </v-col>
                        <!-- <v-file-input label="File input" variant="filled" prepend-icon="mdi-camera"></v-file-input> -->
                    </v-row>
                    <v-row>
                        <v-col cols="12" md="4">
                            <p>ชื่อทริป</p>
                            <v-text-field :counter="10" label="ทริป low carbon สมาคม TEATA" variant="outlined"
                                required></v-text-field>
                        </v-col>
                        <v-col cols="12" md="4">
                            <p>จังหวัด</p>
                            <v-select label="กระบี่"
                                :items="['กรุงเทพ', 'นครสวรรค์', 'สุพรรณบุรี่', 'ชัยนาท', 'ระยอง', 'ระนอง']"
                                variant="outlined" required></v-select>
                        </v-col>
                    </v-row>
                    <v-row class="d-flex">
                        <Radio_time />
                    </v-row>
                    <v-row>
                        <v-col cols="12" md="4">
                            <p>วันที่เริ่มต้น</p>
                            <v-text-field type="date" persistent-hint variant="outlined" required></v-text-field>
                        </v-col>
                        <v-col cols="12" md="4">
                            <p>วันที่สิ้นสุด</p>
                            <v-text-field type="date" persistent-hint variant="outlined" required></v-text-field>
                        </v-col>
                        <v-col cols="12" md="4">
                            <p>ราคา</p>
                            <v-text-field label="1000 บาท" persistent-hint variant="outlined" required></v-text-field>
                        </v-col>
                    </v-row>
                    <v-row>
                        <v-col cols="12" md="4">
                            <p>จำนวนคนขั้นต่ำ</p>
                            <v-text-field label="10 ท่าน" persistent-hint variant="outlined" required></v-text-field>
                        </v-col>
                        <v-col cols="12" md="4">
                            <p>จำนวนคนสูงสุด</p>
                            <v-text-field label="26 ท่าน" persistent-hint variant="outlined" required></v-text-field>
                        </v-col>
                        <v-col cols="12" md="4">
                            <p>Link การจอง</p>
                            <v-text-field label="Traveloga/toca" persistent-hint variant="outlined" required></v-text-field>
                        </v-col>
                    </v-row>
                    <v-row>
                        <v-col>
                            <p>รายละเอียดและสิ่งที่ลูกค้าได้รับ</p>
                            <v-textarea variant="outlined"></v-textarea>
                        </v-col>
                    </v-row>
                    <v-row>
                        <v-col>
                            <p>เงื่อนไข</p>
                            <v-textarea variant="outlined"></v-textarea>
                        </v-col>
                    </v-row>
                    <v-row>
                        <v-col>
                            <p>รายการกิจกรรม Organic</p>
                            <p>Detail</p>
                            <button_toggle />
                        </v-col>
                    </v-row>
                </v-col>
            </v-sheet>
        </v-container>
    </v-card>
</template>

<script lang="ts" setup>
import Radio_time from '@/components/radio_time.vue';
import Button_toggle from '@/components/button_toggle.vue';
import Uploat_img from '@/components/uploat_img.vue';


</script>

<style scoped>
.btn {
    background-color: #2E8E69;
}

.p_btn {
    color: white;
    margin-top: 8px;
    font-size: 16px;
}

p {
    margin-bottom: 10px;
}
</style>