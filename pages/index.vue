<template>
  <div>
    <div>
      <h1>ノラネコ技術工房<small>NORANEKO.tech</small></h1>
      <img src="/img/logo/logo02.svg" width="400" />
    </div>

    <div>
      <h2>ノラネコ技術工房とは<small>About</small></h2>
      <h3>“正しいものをともにつくる”</h3>
      <p>
        プロダクトエンジニアの藤本永一です。<br />
        大阪を中心にプロダクト創りをお手伝いしています。世界を良くしたい方に、エンジニアリングでお手伝いしています。<br />
        アジャイルな心意気で、共に創ります。<br />
        社会、市場、会社、チーム、自分、技術、様々な部分が不確実な時代に入り、更に現行のシステムの老朽化や新しい働き方から世界中のシステムが新しいものに変化していっています。<br />
        もはや自社にエンジニアを持つことは、この変化についていくために必須であり、更に変化の中で勝っていくには重要な職種となりました。とはいえ、立ち上がったばかりの人、これまでエンジニアを持てなかった人がどうして良いかわからないという状態は日本各地、特に地方に多いのではないかと思います。<br />
        はじめの手段としてお声がけいただければ幸いです。変化を求めている人、志の高い人との仕事とその先の喜びを求めています。<br />
      </p>
    </div>

    <div>
      <h2>事業内容<small>Works</small></h2>
      <ul>
        <li>開発組織支援</li>
        <li>猫について考える事業</li>
      </ul>
    </div>

    <div>
      <h2>メンバー<small>Members</small></h2>
      <div>
        <h3>藤本 永一 <small>代表/プロダクトエンジニア</small></h3>
        <img src="/img/members/001-001.png" width="150" />
        <p>
          FAエンジニアからプログラマを目指して、専門学校で学び直し、デジタルマーケティング会社にWEBエンジニアとして再就職、社内システム、受託でのサイトやシステム作成、自社のSaaS開発を経てエンジニアチームのマネジメントも担当。経験を活かし、世界を変えたい人や、楽しく働ける環境を作りたい人へエンジニアリングでお手伝いするため独立。
        </p>
        <ul>
          <li>
            <a href="https://github.com/eiichi-worker" target="_blank"
              >GitHub</a
            >
          </li>
          <li>
            <a href="https://twitter.com/EiichiCat" target="_blank">Twitter</a>
          </li>
        </ul>
      </div>
      <div>
        <h3>ブラックタイガーえびすけ <small>猫</small></h3>
        <img src="/img/members/002-001.jpg" width="150" />
        <p>
          NPO法人地域猫管理協会さんに保護してもらった3兄弟の一人。
          2020/05/01頃生まれ、6月末に藤本家の一員となる。現在は保護猫の可愛さを世界に届けるため、インスタグラムを更新している。
          幸せな猫が1匹でも多く増えることを願っている。 （しらんけど）
        </p>
        <ul>
          <li>
            <a
              href="https://www.instagram.com/blacktiger_ebisuke/"
              target="_blank"
              >Instagram</a
            >
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script setup>
const ctx = useRuntimeConfig();

// const { data } = await useFetch("/blog", {
//   baseURL: ctx.baseURL,
//   headers: {
//     "X-MICROCMS-API-KEY": ctx.apiKey,
//   },
// });
</script>
