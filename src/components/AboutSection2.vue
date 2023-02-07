<template>
    <section class="bio-section">
        <div id="bio">
            <SectionLabel label="Disiplin Cezaları ve Vekil Disiplin Kurulu" />
            <p>Katılımcılara verilebilecek disiplin cezaları üç aşamadan oluşur;</p>
            <ul>
                <li>Uyarma</li>
                <li>Kınama</li>
                <li>Vekillikten İhraç</li>
            </ul>
            <h2 class="sub-h">Uyarma</h2>
            <p>Uyarma cezasını gerektiren haller şunlardır:</p>
            <ol>
                <li>Söz kesmek</li>
                <li>Güncel siyaseti art niyetle veya şaka niyetiyle kullanmak</li>
                <li>Sükuneti ve çalışma düzenini bozmak</li>
                <li>Şahsiyatıyla uğraşmak</li>
            </ol>
            <h2 class="sub-h">Kınama</h2>
            <p>Kınama cezasını gerektiren haller şunlardır:</p>
            <ul>
                <li>Aynı oturumda iki kere uyarma cezası aldığı halde bunu gerektiren hareketten vazgeçmemek</li>
                <li>Kaba ve yaralayıcı sözler sarf etmek ve hareketler yapmak</li>
                <li>Saldırıda bulunmak</li>
                <li>Mecliste gürültü ve kavgaya sebep olmak veya meclisin görevini yerine getirmesini önlemek</li>
            </ul>
            <h2 class="sub-h">Cezaların Uygulanamsı</h2>
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
    text-align: justify;
}

.sub-h {
    font-size: 30px;
}
</style>
