/* eslint-disable vue/this-in-template */
<template>
  <div>
    <h1>searchページ</h1>
    <p>このページの存在に気づきましたか。あなたDeveloperですか</p>
    <v-row justify="center">
      <v-col cols="9">
        <h2>クエリーパラメータ取得結果：route.query</h2>
        <p>$route.query.keyword：</p>
        // eslint-disable-next-line vue/this-in-template
        {{ $route.query.keyword }}<br />
        <p>$route.query.name：</p>
        // eslint-disable-next-line vue/this-in-template //
        eslint-disable-next-line vue/this-in-template
        {{ $route.query.name }}<br />
        <v-btn color="cyan" @click="returnPage()">戻る</v-btn>
      </v-col>
    </v-row>
  </div>
</template>
