<template>
    <v-footer class="bg">
        <v-container >
            <v-col>
                <v-row class="d-flex ">
                    <v-col >
                        <h3>สมาคมผู้บริโภคอินทรีย์ไทย<br>
                            Thai Organic Consuser Association</h3>
                        <p class="mt-2">21 หมู่ ถนนเเพชรเกษม ค.ยายยา อ.สามพราน </p><br>
                        <v-img src="@/assets/pgs.jpg"></v-img>
                    </v-col>
                    <v-col>
                        <h3>เกี่ยวกับสมาคมฯ</h3>
                        <p>เกี่ยวกับเรา<br>
                            ข่าวประชาสัมพันธ์<br>
                            ปฏิทินกิจกรรม<br>
                            กิจกรรมและสถานที่<br>
                            สมัครสมาชิกสมาคม<br>
                            แผนผังเว็บไซต์</p>
                    </v-col>
                    <v-col>
                        <h3>TOCA PLATFORM</h3>
                        <P>เข้าสู่ระบบ<br>
                            สมัครสมาชิกทั่วไป (B2c)<br>
                            สมัครสมาชิกทธุรกิจ (B2b)<br>
                            ประกาศ TOCA Plation<br>
                            กระทู้ถามตอบ<br>
                            บทความ</P>
                    </v-col>
                    <v-col>
                        <h3>ติดต่อเรา</h3>
                        <p>เวลาทำการ: จันทร์ - อาทิตย์<br>
                            เวลา: 8.00 - 17.00 น. <br>
                            เบอร์โทรติดต่อ: 099-199-199<br>
                            อีเมล: in.toca20@gmail.com<br>
                            Line Official Account: @toca</p>
                    </v-col>
                    <v-col>
                        <v-img class="img1" src='@/assets/Picture1.jpg'
                            width="150"></v-img>
                    </v-col>
                </v-row>
                <v-row class="ml-1 ">
                    <hr>

                    <span>@copy Right 2020 สมาคมผู้บริโภคอินทรีย์ไทย - thaiorganicplatform </span>
                </v-row>
            </v-col>
        </v-container>
    </v-footer>
</template>
  
<script lang="ts" setup>

</script>

<style scoped>
hr {
    color: aliceblue;
    width: 100%;
    margin-bottom: 5px;
}

.bg {
    background-color: #2E8E69;
}

h3,
p {
    color: white;
    font-size: 16px;
    margin-left: auto;
    margin-right: auto;
}
.img1{
    margin-left: auto;
    margin-right: auto;
}
span{
    color: white;
    font-size: 16px;
}

</style>