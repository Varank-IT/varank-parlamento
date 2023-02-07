<template>
    <section class="bio-section">
        <div id="bio">
            <SectionLabel label="Başkanların Mesajı" />
            <p>
                Organizasyon ekibim adına sizi ilk gençlik parlamentomuza davet etmekten büyük zevk ve onur duyuyoruz.
                Eğlenceli ve en önemlisi öğretici bir program düzenlemek için yorulmadan çalıştık ve ülkenin en önemli
                sorunlardan bazılarını keşfederken bize katılmanızı dört gözle bekliyoruz. Akademik ekibimiz ilgi ve
                merak uyandıran komite konularını seçti ve bu konular sizler tarafından keşfedilmeyi bekliyor. Katılan
                siz vekillere kayda değer bir tecrübe sunmayı planlıyor, her bir vekilin parlamentoya getireceği farklı
                farklı düşünce tarzlarını merakla bekliyor ve heyecan duyuyoruz. Bu arada komiteler dışında da sizlere
                unutulmaz anılar yaşatmak için çalışıyoruz. Tüm katılımcılarımıza kaynaşabilecekleri, etkinliklere
                katılabilecekleri, sosyal beceriler ve arkadaşlıklar kurabilecekleri bir ortam sağlanacaktır. Ekibimiz,
                bu yıl size mümkün olan en iyi deneyimi sunmak için durmaksızın çalıştı ve çalışmaya devam edecek.
                Parlamentomuzun ulusumuza dair konulara olan ilginizi ateşleyeceğini ve önünüzdeki hayatınızda
                kullanabileceğiniz gerekli becerileri kazandıracağını umuyoruz.
                <br>
                <br>
                Bu zorlu ve sabır gerektiren organizasyon sürecinde her bir detayı bir üst kademeye hazırlanma ve başarı
                noktasında size “geçiş üstünlüğü” sağlayacak etkinliğimizde emeği geçen tüm ekip arkadaşlarımıza
                teşekkür ederken siz değerli katılımcılarımıza bu yolculukta başarı ve güzellikler diliyoruz. Varank
                Gençlik Parlamentosunda sizlerle buluşmayı dört gözle bekliyoruz.
            </p>
        </div>
        <div id="bio">
            <SectionLabel label="Etkinlik Hakkında" />
            <p>
                Gençlik Parlamentosu, öğrencilere bir meclis deneyimi yaşatmayı amaç edinen bir simülasyon etkinliğidir.
                <br>
                Varank Gençlik Parlamentosu ekibi olarak amacımız, katılımcılara eleştirel düşünme, takım çalışması ve
                liderlik yeteneklerine ek olarak katılımcıların araştırma, konuşma, tartışma, sosyal hayatta aktif
                bireyler olmalarına katkıda bulunmak ve kriz anlarında düşünme kabiliyetlerini geliştirmeleri
                yönündedir.
            </p>
            <h2 class="sub-h">Misyonumuz</h2>
            <p>
                Çevre okullarla aramızdaki etkileşimi arttırıp kaliteli vakit geçirmelerini ve farklı deneyimlere sahip
                olmalarını sağlamak, daha çok kişi arasında iletişimi ve yardımlaşma duygularını arttırarak kişiler
                arasındaki farklı görüş açılarını bulup dayanışmayı sağlamak sebebiyle gerçekleştirilmesine karar
                verdiğimiz bir organizasyondur.
            </p>
            <h2 class="sub-h">Vizyonumuz</h2>
            <p>
                Yenilikçi ve ilham verici fikirler aracılığıyla ülke sorunlarına çözüm üretip, alınan kararların,
                sonuçların organizasyon sonunda herkese kitapçık şeklinde dağıtılarak organizasyonunun kalıcılığını
                sağlamak amacıyla gerçekleştirilecektir.

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
    word-spacing: normal;
    text-align: center;
}

.sub-h {
    font-size: 30px;
}
</style>
