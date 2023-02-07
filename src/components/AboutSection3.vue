<template>
    <section class="faq-section">
        <div class="faq-warp">
            <div class="container">
                <SectionLabel label="Gruplar" />
                <div class="row">
                    <div class="faq">
                        <AccordionItem v-for="(faq, index) in faqs" :key="faq" :info="faq" :badgeNumber="index + 1" />
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import Badge from './accordion/Badge.vue';
import SectionLabel from './SectionLabel.vue'
import AccordionItem from './accordion/AccordionItem.vue';

export default {
    name: 'FaqSection',
    components: {
        Badge,
        SectionLabel,
        AccordionItem
    },
    data: () => ({
        faqs: [
            {
                question: 'Milliyetçilik',
                answer: 'Milliyetçilik, belirli bir coğrafyada ortak kültürel ve/veya etnik kökene sahip toplulukların siyasî ve tarihî meşruiyetiyle yüceltilmesini hedefleyen siyasal, sosyal, kültürel, dinî düşünce ve yaklaşımlarla ideolojik anlamda millî devletin güçlenmesini en önemli hedef sayan bir ideolojidir. Milliyetçilik, her devletin kendisini dışardan gelecek olan müdahalelerden bağımsız olarak yönetilmesi gerektiğini savunur. Milliyetçiler kendi halkına katkı sağlayan fikirlere destek verir. Ekonomik yapısı yerli üretimi destekleyecek şekilde olması gerekir. Emek, mal ve sermaye gibi konular üzerinde düzenleme yapar ve bu üç konu üzerinde gelişmeyi hedefleyerek ulusal ekonomiyi olabilecek en üst düzeye çıkarmayı amaç edinirler.'
            },
            {
                question: 'Merkez Sağ',
                answer: 'Merkez sağ siyasi yelpazenin sağına doğru eğilir, ancak merkeze diğerlerinden daha yakındır. Toplumun dini değerlerine saygılıdır. Toplumun dini değerleri yanında milli-yerel değerlerini, ülkenin birlik ve bütünlüğünü, dilini, gelenek ve göreneklerini sahiplenir. Merkez Sağ mevcut durumu savunurlar, her türlü yeniliğe karşıdırlar. Sermaye ve toprak sahiplerinin mülkiyet haklarını korurlar ekonomik olarak kalkınmacı bir politika izlerler. Bu noktada merkez sağ ideolojisi, ekonomide liberal anlayıştan esinlenirken toplumda muhafazakarlık etkisindedir.',
            },
            {
                question: 'Liberalizm',
                answer: 'Liberalizm, bireyin özgürlüğü üzerine kurulmuş bir siyasi felsefe akımıdır. Bu noktada bireyler ancak devlet otoritesinin en az olduğu ve herhangi bir keyfi kısıtlama altında olmadıkları taktirde özgürlerdir. Liberalizm, siyasi iktidarın anayasa ve hukukun üstünlüğü ile güvence altına alınmasına çok önem verirler. Buradaki amaç, bireyin özgürlüğünü sağlayıp devleti kısıtlamaktır. Kısıtlanmış devlet kavramında kastedilen sosyalist ideolojideki toplumsal alanı kısıtlayan ve çevreleyen devlet yapısına zıt bir anlayıştır.Lakin hiçbir liberal hükümette hükümetin görev alanı o denli dar değildir.Liberalizm, bu noktada “koordinasyon faaliyetleri” adı altında sosyal hayatı tamamen kontrol altına almaması kaydıyla devletin yurttaşlarına yardımlarda bulunmasını, altyapı yatırımları yapmasını, eğitim kurumları açmasını uygun görür.'
            },
            {
                question: 'Cumhuriyetçilik',
                answer: 'Cumhuriyetçilik, Atatürk’ün ilkelerinden ana ve esas olanıdır. Cumhuriyet, devlet düzen ve yönetiminde şahsilik ve keyfiliğin hâkim olmasını önleyen en sağlam teminattır. Cumhuriyetçilik akımı dünya üzerinde farklı ideolojilere evirilmiş olsa bile Türk halkı üzerinde Cumhuriyetçilik anlayışı, Atatürk’ün ilkeleri doğrultusunda gelişmiştir. Türk Cumhuriyetçiliğinde laik, halkçı, inkılapçı ve devletçilik ön plandadır. Laiklik anlayışına göre devlet kendi başına tüzel bir kişiliktir ve genel geçer ahlaki olgulardan ziyade devletin kendi çıkarları ön plandadır. Halkçılığa göre, ulusun egemenliği ön plandadır ve devlet halkı değil, halk devleti etkisi altında tutar. Bu halkçılığa göre tüm bireyler eşit imkan ve olanaklara sahiptir. Devletin karşısında hiçbir birey ayrıcalıklara sahip değildir. Devletçiliğe göre serbest piyasa ve bireyin özgürlüğü egemenken serbest piyasanın olmadığı yerlerde devlet de el atabilmelidir.'
            },
            {
                question: 'Sosyal Demokrasi',
                answer: 'Sosyal demokrasi eşitsizlikleri ortadan kaldırmayı hedefleyen politik bir ideolojidir. Sınıfların çıkarı dengeye gelmelidir. Sosyal demokrasi emekçilerin çıkarını savunurken, öteki sınıfların yaşam hakkını yok saymaz. Demokratik özgürlükler sınıfsal çıkarlara kurban edilmemelidir. Sosyal demokrasi, sınıflar arası çıkar dengesini en iyi sağlayacak ortamın, siyasal haklarda eşitliğe dayalı demokratik ortam olduğu inancındadır. Ekonomik yapı çoğulcu olmalıdır. Ulusal üretim, soyut bir serbest piyasa ekonomisi tutkusuna kurban edilmemelidir. Özel teşebbüsün yetişemediği pahalı teknolojiyi gerektiren yatırımları devlet yüklenmeli ve bu yoldan ekonomik yapıyı değiştirmelidir.'
            }
        ]
    })
}
</script>

<style scoped>
.faq-section {
    min-height: 100vh;
    min-height: 50vh;
    font-weight: bold;
    text-align: left;
}

.faq-warp {
    /*padding: 6vh 4vw;*/
    padding: 2vh 12vw;
}

.faq {
    background: #FFFFFF;
    box-shadow: 0 2px 48px 0 rgba(0, 0, 0, 0.06);
    border-radius: 4px;
}

@media (max-width: 1000px) {
    .faq {
        margin-bottom: 30px;
    }
}
</style>