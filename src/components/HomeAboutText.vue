<template>
    <div class="frame-parent23">
        <div class="about-us-parent">
            <div class="about-us">About us</div>
            <div class="from-the-harmonious3">
                From the Harmonious union between a mixes of cereals flours and legumes
                flours, a new line of testy specialitiesrich in fiber and vegetable
                proteins is born.
            </div>
        </div>
        <div class="frame-parent24">
            <img class="frame-child9" alt="" src="../../../../public/assets/img/Frame 19353308.svg" />
            <img class="frame-child10" alt="" src="../../../../public/assets/img//frame 19353307.svg" />
            <img class="frame-child11" alt="" src="../../../../public/assets/img/frame 19353309.svg" />
            <div class="fresh-parent">
                <div class="fresh">Fresh</div>
                <div class="nothing-the-copy">
                    Nothing the copy said could convince her and so it didn’t take long.
                </div>
            </div>
            <div class="natural-parent">
                <div class="fresh">Natural</div>
                <div class="nothing-the-copy1">
                    Nothing the copy said could convince her and so it didn’t take long.
                </div>
            </div>
            <div class="tasty-parent">
                <div class="tasty">Tasty</div>
                <div class="nothing-the-copy2">
                    Nothing the copy said could convince her and so it didn’t take long.
                </div>
            </div>
        </div>
        <!-- <img
        class="vector-smart-object-44"
        alt=""
        src="../../../../public/assets/img/vector-smart-object43@2x.png"
      /> -->
    </div>
</template>
<script>
import { defineComponent } from "vue";

export default defineComponent({
    name: "Frame4",
});
</script>
<style scoped>
.about-us {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.02em;
    line-height: 90px;
    background: linear-gradient(121.97deg, #393230, #f99e58);
    /* -webkit-background-clip: text; */
    -webkit-text-fill-color: transparent;
}

.from-the-harmonious3 {
    position: relative;
    font-size: 16px;
    letter-spacing: -0.04em;
    line-height: 24px;
    font-family: Inter;
    display: inline-block;
    width: 592px;
    opacity: 0.6;
}

.about-us-parent {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    gap: 10px;
    z-index: 0;
}

.frame-child9 {
    position: absolute;
    top: 260px;
    left: calc(50%-300px);
    width: 350px;
    height: 323px;
}

.frame-child10 {
    position: absolute;
    top: 0px;
    left: calc(50%-150px);
    width: 300px;
    height: 314px;
}

.frame-child11 {
    position: absolute;
    top: 255.6px;
    left: calc(50%+150px);
    width: 350px;
    height: 327.4px;
}

.fresh {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.02em;
    background: linear-gradient(121.97deg, #393230, #f99e58);
    /* -webkit-background-clip: text; */
    -webkit-text-fill-color: transparent;
}

.nothing-the-copy {
    position: relative;
    font-size: 14px;
    letter-spacing: -0.04em;
    font-family: Inter;
    display: inline-block;
    width: 255px;
}

.fresh-parent {
    position: absolute;
    top: 149px;
    left: calc(50% + 188px);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 4px;
    text-align: left;
}

.nothing-the-copy1 {
    align-self: stretch;
    position: relative;
    font-size: 14px;
    letter-spacing: -0.04em;
    font-family: Inter;
}

.natural-parent {
    position: absolute;
    top: 575px;
    left: calc(50% - 154px);
    width: 308px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    gap: 4px;
}

.tasty {
    position: relative;
    letter-spacing: -0.02em;
    background: linear-gradient(121.97deg, #393230, #f99e58);
    /* -webkit-background-clip: text; */
    -webkit-text-fill-color: transparent;
}

.nothing-the-copy2 {
    position: relative;
    font-size: 14px;
    letter-spacing: -0.04em;
    font-family: Inter;
    text-align: right;
    display: inline-block;
    width: 246px;
}

.tasty-parent {
    position: absolute;
    top: 124px;
    left: calc(50% - 454px);
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    gap: 4px;
}

.frame-parent24 {
    position: relative;
    width: 100%;
    height: 673px;
    z-index: 1;
    font-size: 40px;
}

.vector-smart-object-44 {
    position: absolute;
    margin: 0 !important;
    top: 107px;
    left: 0px;
    width: 148px;
    height: 262px;
    object-fit: cover;
    opacity: 0.2;
    z-index: 2;
}

.frame-parent23 {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    gap: 40px;
    text-align: center;
    font-size: 60px;
    color: #182933;
    font-family: Cambon;
}

@media (max-width: 960px) {}
</style>


<!-- <template>
    <div v-html="data" v-if="!loading"></div>
</template>

<script>
export default {
    data: () => ({
        loading: true,
        data: null,
    }),
    async created(){
        const res = await this.call_api("get", "setting/home/home_about_text");
        if (res.data.success) {
            this.data = res.data.data
            this.loading = false
        }
    }
}
</script> -->
