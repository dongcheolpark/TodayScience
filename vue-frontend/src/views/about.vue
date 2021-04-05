<template>
  <div>
    <div class="about-card">
      <h1>이 사이트는 어떤 사이트인가요?</h1>
      <h4>
        이 사이트는 최근 핫한 과학기술들을 한눈에 확인할 수 있게 해줍니다. <br>
        각광받고 있는 기술들을 직접 확인해 보세요.

      </h4>
    </div>
    <div class="about-info">
      <b-contatiner>
        <b-row>
          <b-col>
            <h1>다양한 정보들을 확인해 보세요.</h1>
          </b-col>
        </b-row>
        <b-row align = "center">
          <b-col >
            <b-card class="about-info-card"
              title = "abc"
            >
              <b-card-text>
                abcdefjfoewiqfjowiejfowjqeofjwqoeijfwoj
              </b-card-text>
              
            </b-card>
          </b-col>
          <b-col >
            <b-card class="about-info-card"
              title = "abc"
            >
              <b-card-text>
                abcdefjfoewiqfjowiejfowjqeofjwqoeijfwoj
              </b-card-text>
              
            </b-card>
          </b-col>
          <b-col >
            <b-card class="about-info-card"
              title = "abc"
            >
              <b-card-text>
                abcdefjfoewiqfjowiejfowjqeofjwqoeijfwoj
              </b-card-text>
              
            </b-card>
          </b-col>
          <b-col >
            <b-card class="about-info-card"
              title = "abc"
            >
              <b-card-text>
                abcdefjfoewiqfjowiejfowjqeofjwqoeijfwoj
              </b-card-text>
              
            </b-card>
          </b-col>
        </b-row>
      </b-contatiner>
    </div>
  </div>
</template>
<script>

export default {
    name : "About",
};
</script>
<style>
.about-card{
  margin: 1rem;
  padding-top: 6rem;
  padding-bottom: 6rem;
  background-color: aliceblue;
}
.about-info{
  margin-top:4rem;
  margin-bottom: 4rem;
  text-align: center;
}
.about-info-card{
  margin : 2rem;
  max-width: 15rem;
}
</style>
