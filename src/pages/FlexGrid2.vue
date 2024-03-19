<template>
  <q-page padding>
    <section class="row q-col-gutter-x-xl q-py-lg">
      <div class="col-12 col-sm-auto q-py-md flex flex-center">
        <q-avatar size="150px">
          <q-img src="https://cdn.quasar.dev/img/avatar.png" />
        </q-avatar>
      </div>
      <div class="col-grow column justify-between">
        <div class="row items-center">
          <span class="text-h6 text-weight-bold">dev_yezzang</span>
          <q-space />
          <div class="q-gutter-x-sm">
            <q-btn outline color="secondary" label="프로필 편집1" />
            <q-btn outline color="secondary" label="프로필 편집2" />
            <q-btn outline color="secondary" label="프로필 편집3" />
            <q-btn flat color="secondary" icon="more_horiz" />
          </div>
        </div>
        <div class="q-gutter-x-lg">
          <span>게시물 238</span>
          <span>팔로워 2,032</span>
          <span>팔로워 1,432</span>
        </div>
        <div>
          <span>코린이</span>
          <span>#INTP 개발 열심히</span>
          <span>blog.naver.com/kingyezzang</span>
        </div>
      </div>
    </section>
    <section>
      <div class="row no-wrap scroll q-col-gutter-x-xl">
        <div class="col-auto" v-for="n in 15" :key="n">
          <article>
            <q-avatar size="70px">
              <q-img src="https://cdn.quasar.dev/img/avatar.png" />
            </q-avatar>
            <div class="text-center q-mt-sm">제목</div>
          </article>
        </div>
      </div>
    </section>
    <section class="q-mt-xl">
      <div class="row q-col-gutter-md">
        <div v-for="n in 18" :key="n" class="col-12 col-sm-6 col-md-4 col-lg-3">
          <!-- 반응형 적용-->
          <q-card class="my-card">
            <q-img src="https://cdn.quasar.dev/img/parallax2.jpg">
              <div
                class="absolute-bottom text-subtitle2 flex flex-center full-height"
              >
                Title
              </div>
            </q-img>
          </q-card>
        </div>
      </div>
    </section>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped>
.q-page {
  background-color: #fafafa;
}
</style>
