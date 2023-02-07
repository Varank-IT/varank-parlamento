<template>
    <section class="faq-section">
        <div class="faq-warp">
            <div class="container">
                <SectionLabel label="Sıkça Sorulan Sorular" />
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
                question: 'Etkinlik ne zaman ve nerede olacak?',
                answer: '4-5 Mart tarihlerinde Yeditepe Üniversitesinde 6 Martta ise Kadıköy Belediye Meclisinde olacağız. Adreslere sitenin en alt kısmından ulaşabilirsiniz.'
            },
            {
                question: 'Etkinliğe nasıl katılabilirim?',
                answer: 'İnternet sitemizden veya Instagram hesabımızda bulunan formdan başvuru yapabilirsiniz.'
            },
            {
                question: 'Dresscode olacak mı?',
                answer: 'Bir meclis simülasyonu olduğu için parlamentoya uygun resmi bir şekilde gelinmesi zorunludur.'
            },
            {
                question: 'Katılmak için zorunluluklar nelerdir?',
                answer: 'Lise öğrencisi herkes etkinliğimize katılabilir.'
            },
            {
                question: 'Etkinlik alanlarına toplu taşımayla nasıl gidebilirim?',
                answer: 'Başvurusu kabul edilen tüm katılımcılara etkinlik alanına nasıl gidileceği iletilecektir.'
            },
            {
                question: 'Arkadaşlarımla grup halinde katılabilir miyim?',
                answer: 'Tabii ki de!'
            },
            {
                question: 'Etkinlikte yemek servisi yapılacak mı?',
                answer: 'Evet yapılacaktır, üç gün boyunca yiyeceğiniz her şey katılım ücretine dahildir.'
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