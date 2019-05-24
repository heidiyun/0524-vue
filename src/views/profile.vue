<template>
  <div>
    <div class="name">이름: 구윤정</div>
    <div class="favorite">
      좋아하는 것
      <div class="movie">영화 : 리틀포레스트</div>
      <div class="food">음식 : 초밥</div>
    </div>
    <div class="dislike">
      싫어하는 것
      <div class="movie">영화 : 무서운장르</div>
      <div class="food">음식 : 들깨칼국수</div>
    </div>
  </div>
</template>

<style lang = "scss">
.name {
  height: 100px;
  font-weight: bold;
  font-size: 30px;
}

.favorite {
  height: 50px;
  font-size: 10px;
  background: #345453;
  .movie {
    color: #fefefe;
  }

  .food {
    color: #fefefe;
  }
}

.dislike {
  height: 50px;
  font-size: 10px;
  background: #648473;
  .movie {
    color: #fefefe;
  }

  .food {
    color: #fefefe;
  }
}
</style>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({})
export default class Home extends Vue {}
</script>