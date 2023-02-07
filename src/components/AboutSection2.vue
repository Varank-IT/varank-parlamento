<template>
    <section class="bio-section">
        <div id="bio">
            <SectionLabel label="Disiplin Cezaları ve Vekil Disiplin Kurulu" />
            <p style="text-align: left">Katılımcılara verilebilecek disiplin cezaları üç aşamadan oluşur;</p>
            <ul style="text-align: left">
                <li>Uyarma</li>
                <li>Kınama</li>
                <li>Vekillikten İhraç</li>
            </ul>
            <h3 class="sub-h3" style="text-align: left">Uyarma</h3>
            <p style="text-align: left">Uyarma cezasını gerektiren haller şunlardır:</p>
            <ol style="text-align: left">
                <li>Söz kesmek</li>
                <li>Güncel siyaseti art niyetle veya şaka niyetiyle kullanmak</li>
                <li>Sükuneti ve çalışma düzenini bozmak</li>
                <li>Şahsiyatıyla uğraşmak</li>
            </ol>
            <h3 class="sub-h3" style="text-align: left">Kınama</h3>
            <p style="text-align: left">Kınama cezasını gerektiren haller şunlardır:</p>
            <ul style="text-align: left">
                <li>Aynı oturumda iki kere uyarma cezası aldığı halde bunu gerektiren hareketten vazgeçmemek</li>
                <li>Kaba ve yaralayıcı sözler sarf etmek ve hareketler yapmak</li>
                <li>Saldırıda bulunmak</li>
                <li>Mecliste gürültü ve kavgaya sebep olmak veya meclisin görevini yerine getirmesini önlemek</li>
            </ul>
            <h2 class="sub-h2">Cezaların Uygulanması</h2>
            <p>Disiplin cezalarının verilmesinin gereğini takdir ve yerine getirme yetkisi, Divan’a aittir.
                <br><br>Disiplin
                cezası alan üye kendisini savunma hakkına sahiptir, bu üyeye oturumun sonunda söz verilir. Divan,
                gerekirse, daha önce söz verebilir. <br><br>Bir kere kınama cezası alan üye içinde bulunduğu Meclis
                Simülasyonu döneminde Komisyonlarda ve Genel Kurulda oy kullanamaz. <br><br>Aynı dönemde iki kere kınama
                cezası alan veya etkinliğin genel düzenine bariz zarar veren üye vekillikten ihraç edilir ve takip eden
                dönemde üye olması engellenir. Disiplin cezalarına itiraz Vekil Disiplin Kurulu’na yapılır. Vekil
                Disiplin Kurulu, Üst Divan üyelerinden oluşur ve kararlarını salt çoğunlukla alır.
            </p>
        </div>
    </section>
</template>

<script>
import SectionLabel from './SectionLabel.vue'

export default {
    name: 'AboutSection',
    components: {
        SectionLabel
    }
}
</script>

<style scoped>
#bio {
    font-size: 20px;
    margin-left: 12%;
    margin-right: 12%;
    margin-top: 50px;
    margin-bottom: 50px;
    word-spacing: normal;
    text-align: left;
}

.sub-h2 {
    font-size: 35px;
}

.sub-h3 {
    font-size: 25px;
}
</style>
