<script setup>
import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue'
</script>

<template>
    <Header />
    <main>
        <div class="section-content">
            <div class="section-text">
                <h1 class="heading">Muguo 的故事</h1>
                <p>話說大宋仁宗天子在位，嘉佑三年三月三日五更三點，天子駕坐紫哀殿，受百官朝賀。但見：</p>
                <p>祥雲迷鳳閣，瑞氣罩龍樓。含煙禦柳拂籃旗，帶露宮花迎劍戟。天香影里，玉吞珠履聚丹墀；仙樂聲中，繡襖錦衣扶御駕。珍珠簾卷，黃金殿上現金輿；鳳羽扇開，白王階前停寶輦。隱隱凈鞭三下響，層層文武兩班齊。</p>
            </div>
            <img class="section-image" src="/src/assets/eating_mooncake.jpeg">
        </div>
        <div class="section-content">
            <img class="section-image" src="/src/assets/lotsa_mooncakes.jpeg">
            <div class="section-text">
                <h1 class="heading">不只用愛心，還有高級材料</h1>
                <p>當有殿頭官喝道：「有事出班早奏，無事卷簾退朝。」只見班部叢中，宰相趙哲、參政文彥博出班奏曰：「目今京師瘟疫盛行，傷損軍民甚多。伏望陛下釋罪寬恩，省刑薄稅，祈禳天災，救濟萬民。」天子聽奏，急敕翰林院隨即草詔：一面降赦天下罪囚，應有民間稅賦悉皆赦免；一面命在京宮觀寺院，修設好事禳災。不料其年瘟疫轉盛。
                </p>
            </div>
        </div>
    </main>
    <Footer />
</template>

<style scoped>
main {
    background-color: white;
    padding: 50px 250px;
}

.section-content {
    display: flex;
    gap: 50px;
    margin-bottom: 50px;
}

.section-image {
    height: 300px;
    width: 300px;
    object-fit: cover;
}
</style>