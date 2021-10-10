<template>
  <div id="home">
    <div class="keyVisual">
      <canvas id="canvas"></canvas>
      <div class="canvas_on_layer"></div>
      <img src="../assets/welcome.png" alt=""> 
    </div>

    <div class="about">
      <h1>About</h1>
        <div class="about_contents">
          <img src="../assets/mypicture.png" alt="">

          <div>
            <p>名前：崎山 琴音（Sakiyama Kotone）</p>
            <p>趣味：旅行、映画鑑賞、建築鑑賞、モノづくり系のゲーム</p>
            <p>特技：どんな映画やドラマでも泣けること</p>
            <p>性格：計画を立ててから行動する、共感性・学習欲が高い</p>
          </div>
          
        </div>
    </div>

    <div class="skill">
      <h1>Skill</h1>
      <div class="skill_contents">
        <fade-animation>
          <div class="programming">
            <h2>プログラミング言語など</h2>
            <div class="prog_contents">
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-html5-plain colored"></i>
                  <div>
                    <p class="language">HTML/CSS</p>
                    <Star :data-rate="4"></Star>
                  </div>
                </div>
                <p class="language_about">個人での基本的なコーディングはもちろん、2度のチームでの実装経験があります。</p>
              </div>
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-javascript-plain"></i>
                  <div>
                    <p class="language">JavaScript</p>
                    <Star :data-rate="3"></Star>
                  </div>
                </div>
                <p class="language_about">ゲーム制作や、大学院での研究での使用経験があります。</p>
              </div>
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-vuejs-plain colored"></i>
                  <div>
                    <p class="language">Vue.js</p>
                    <Star :data-rate="3"></Star>
                  </div>
                </div>
                <p class="language_about">webサイト制作や、大学院での研究での使用経験があります。</p>
              </div>
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-wordpress-plain"></i>
                  <div>
                    <p class="language">WordPress</p>
                    <Star :data-rate="4"></Star>
                  </div>
                </div>
                <p class="language_about">phpを用いたオリジナルテーマの制作、チームでの実装経験があります。</p>
              </div>
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-ruby-plain"></i>
                  <div>
                    <p class="language">Ruby</p>
                    <Star :data-rate="2"></Star>
                  </div>
                </div>
                <p class="language_about">プログラミング初心者の高校生に教られる程度の理解と、1度のアプリ制作経験があります。</p>
              </div>
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-rails-plain"></i>
                  <div>
                    <p class="language">RubyonRails</p>
                    <Star :data-rate="2"></Star>
                  </div>
                </div>
                <p class="language_about">プログラミング初心者の高校生に教られる程度の理解と、1度のアプリ制作経験があります。</p>
              </div>
              <div class="prog_content">
                <div class="prog_content_inner">
                  <i class="devicon-python-plain"></i>
                  <div>
                    <p class="language">Python</p>
                    <Star :data-rate="2"></Star>
                  </div>
                </div>
                <p class="language_about">大学院での研究での使用経験があります。</p>
              </div>       
            </div>     
          </div>
        </fade-animation>
        <fade-animation>
          <div class="certification">
            <h2>資格</h2>
            <div class="cert_contents">
              <div class="cert_content">
                <p>基本情報技術者</p>
              </div>
              <div class="cert_content">
                <p>応用情報技術者</p>
              </div>
              <div class="cert_content">
                <p>TOEIC 725</p>
              </div>
            </div>
          </div>
        </fade-animation>
      </div>  
    </div>

    <div class="works">
      <h1>Works</h1>
      <div class="works_contents">

        <div class="works_content">
          <img src="../assets/clack_mockup.jpg" alt="">
          <a href="https://clack.ne.jp" class="work_title">NPO法人CLACK 公式サイト</a>
          <div class="work_skills">
            <p># HTML/CSS</p>
            <p># WordPress</p>
          </div>
          <p class="work_content_about">インターンとして働かせていただいている、NPO法人CLACKの公式サイトを制作しました。コーディングが主な担当でしたが、企 . . .</p>     
          <modal>
            <div class="modal">
              <h3>〇作品概要</h3>
              <p>インターンとして働かせていただいている、NPO法人CLACKのコーポレートサイトを制作しました。コーディングが主な担当でしたが、企画段階から制作に関わっているので、特に想い入れがある作品です。</p>
              
              <h3>〇作ったきっかけ</h3>
              <p>法人の規模を拡大させるにあたり、広報の顔となるコーポレートサイトが必要となりました。そんな時、デザインとプログラミングが好きだった私を、代表理事から「作ってみない？」と制作チームに誘って頂けたことがきっかけとなりました。</p>
              
              <h3>〇工夫点やこだわり</h3>
              <p>サイトを通じて、「誰に私たちの事業を知ってほしいか」「それはなぜか」を考え話しあい、「サイトを訪れた人にどう感じてほしいか」を一番大切にし、制作を行いました。<br>また、誰でも運用・管理がしやすいように、WordPressのオリジナルテーマとして制作をしています。</p>

              <p class="link">URL：<a href="https://clack.ne.jp">https://clack.ne.jp</a></p>
              <p class="link">GitHub：なし</p>
            </div>
          </modal>
          
        </div>
        
        <div class="works_content">
          <img src="../assets/portfolio_仮.png" alt="ポートフォリオサイトの画像">
          <a href="https://clack.ne.jp" class="work_title">ポートフォリオサイト</a>
          <div class="work_skills">
            <p># HTML/CSS</p>
            <p># JavaScript</p>
            <p># Vue.js</p>
          </div>
          <p class="work_content_about">今見ていただいているポートフォリオサイトです。シンプルで情報を把握しやすいサイトになるように心がけながら、vue.jsで. . . </p>
          <modal>
            <div>
              <h3>〇作品</h3>
              <p>今見ていただいているポートフォリオサイトです。シンプルで情報を把握しやすいサイトになるように心がけながら、vue.jsで制作しました。</p>
              
              <h3>〇作ったきっかけ</h3>
              <p>正直なところ、就職活動で必要だったためです。<br>
                ちょうどvue.jsを学んでいたこともあり、outputを兼ねてこのサイトを制作しました。まだまだ制作途中な箇所もあるため、日々アップデートしていきます。
              </p>
              
              <h3>〇工夫点やこだわり</h3>
              <p>必要な箇所にのみアニメーションをつけるようにし、軽量なサイトになるよう気をつけました。</p>
            
              <p class="link">URL：<a href=""></a></p>
              <p class="link">GitHub：</p>
              
            </div>
          </modal>
        </div>
      
        <div class="works_content">
          <img src="../assets/sackygram.png" alt="railsアプリの画像">
          <a href="https://sacky-gram.herokuapp.com/users/sign_in" class="work_title">Instagram風のWebアプリ</a>
          <div class="work_skills">
            <p># HTML/CSS</p>
            <p># Ruby on Rails</p>
          </div>
          <p class="work_content_about">インスタグラム風のWebアプリケーションです。Railsで写真投稿・ユーザ・コメント機能などを実装しました。</p>
          <modal>
            <div>
              <h3>〇作品</h3>
              <p>インスタグラム風のWebアプリケーションです。Railsで写真投稿・ユーザ・コメント機能などを実装しました。</p>
              
              <h3>〇作ったきっかけ</h3>
              <p>CLACKで高校生にプログラミング（RubyとRuby on Rails）を教えることになり、学び始めたこと、そして学びのoutputを制作したいと考えたことがきっかけです。「仕事で必要だから」と学び始めましたが、言語化して分かりやすく教えるにはどうしたら良いか、という目線で学び続けています。</p>
              
              <h3>〇工夫点やこだわり</h3>
              <p>webサイト制作ではなるべく手書きでコードを書くようにしていましたが、本作品では、Bootstrap（デザイン面）やDevise（サインアップ機能）を用いて、効率的に制作するようにしました。</p>
            
              <p class="link">URL：<a href="https://gentle-brook-59158.herokuapp.com/">https://gentle-brook-59158.herokuapp.com/</a></p>
              <p class="link">GitHub：</p>
            </div>
          </modal>
        </div>
      
      </div>
    </div>

    <div class="carrer">
      <h1>Carrer</h1>
      <div class="carrer_contents">
        <div class="carrer_ctn">
          <div class="carrer_ctn_inner">
            <fade-animation>
              <h2>経歴</h2>
              <table class="school">
                <tr>
                  <td class="thead">2014/04 ~ 2017/03</td>
                  <td>近畿大学附属高等学校 スーパー文理コース</td>
                </tr>
                <tr>
                  <td class="thead">2017/04 ~ 2021/03</td>
                  <td>大阪府立大学 現代システム科学域 知識情報システム学類（真嶋研究室）</td>
                </tr>
                <tr>
                  <td class="thead">2021/04 ~ 2023/03</td>
                  <td>大阪府立大学院 人間社会システム科学研究科 現代システム科学専攻</td>
                </tr>
                <tr>
                  <td class="thead"></td>
                  <td>知識情報システム学分野 卒業予定（真嶋研究室）</td>
                </tr>
              </table>
            </fade-animation>
            
            <fade-animation>
              <h2>(長期)インターン歴</h2>
              <table class="intern">
                <tr>
                  <td class="thead">2018/02 ~ 現在</td>
                  <td>NPO法人 CLACK</td>
                </tr>
                <tr>
                  <td class="thead"></td>
                  <td>高校生対象のプログラミング講師、Webサイト制作、教室運営</td>
                </tr>
                <tr>
                  <td class="thead">2019/09 ~ 2019/11</td>
                  <td>リタワークス株式会社</td>
                </tr>
                <tr>
                  <td class="thead"></td>
                  <td>Webディレクション業務</td>
                </tr>
              </table>
            </fade-animation>
          </div>
          
        </div>
      </div>  
    </div>

    <div class="contact"></div>
  </div>
</template>

<script>
import FadeAnimation from '../components/FadeAnimation.vue';
import Snow from "../js/snow";
import Modal from "../components/Modal.vue";
import Star from "../components/star.vue"


export default {
  name: 'Home',
  
  components: { 
    FadeAnimation,
    Modal,
    Star
  },
  mounted() {
    Snow.snow(); 
  },
  
};

</script>

<style scoped>
.keyVisual {
  height: 100vh;
  width: 100%;
}

.keyVisual .canvas_on_layer {
    top: 0;
    width: 100%;
    height: 100vh;
    position: absolute;
    z-index: 1;
    background-color: rgba(203, 220, 219, 0.7);
}

.keyVisual #canvas {
  background-color: #08233E;
  min-height:300px;
}

.keyVisual img {
  z-index: 2;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  font-family: 'Titillium Web', sans-serif;
  background-color: transparent;
}

.about,
.skill,
.works,
.carrer,
.contact {
  /* height: 100vh; */
  font-family: 'Titillium Web', sans-serif;
  padding: 60px 70px;
  box-sizing: border-box;
}

.about h1,
.skill h1,
.works h1,
.carrer h1,
.contact h1 {
  margin-bottom: 30px;
}
.about .about_contents {
  display: flex; 
  justify-content: space-evenly;
}
.about img {
  width: 250px;
  height: 250px;
  margin-right: 60px;
}
.about p {
  width: 500px;
  margin-top: 10px;
  text-align: left;
  line-height: 1.9;
}

.skill,
.carrer {
  background-color: rgba(203, 220, 219, 0.7);
}

.skill h2 {
  margin-bottom: 20px;
}

.skill .prog_contents,
.skill .cert_contents {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.skill .prog_content,
.skill .cert_content {
  /* アニメーション前 */
  background-color: #fff;
  border-radius: 10px;
  width: 30%;
  padding: 20px;
  margin-bottom: 20px;
  box-sizing: border-box;
	transition: .3s;
}

.skill .prog_content:hover,
.skill .cert_content:hover {
  box-shadow: 0 15px 30px -5px rgba(0,0,0,.15), 0 0 5px rgba(0,0,0,.1);
}

.skill .prog_content_inner {
  display: flex;
}

.skill .prog_contents p {
  text-align: left;
}

.skill .language {
  font-size: 20px;
}

.skill i {
  color: #4691f6;
  font-size: 40px;
  margin: 0 20px 0 10px;
  line-height: 1.3;
}

.works .works_contents {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.works .works_content {
  width: 300px;
  margin-bottom: 40px;
  box-shadow: 1px 0px 20px 0px rgb(0 0 0 / 10%);
  padding-bottom: 20px;
}

.works .works_contents img {
  width: 300px;
  height: 240px;
}

.works .work_skills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  color: gray;
}

.works .work_skills p{
  padding-right: 10px;
}

.works .work_content_about{
  text-align: left;
  padding: 15px;
}

.carrer_ctn {
  background-color: #fff;
  border-radius: 10px;
  margin-bottom: 20px;
  padding: 20px 10%;
}

.carrer_ctn h2{
  margin-bottom: 20px;
}

.carrer_ctn table {
  margin: 0;
  width: 707px;
  margin: 0 auto;
}

.carrer_ctn .school {
  padding-bottom: 80px;
}

.carrer_ctn td {
  text-align: left;
  line-height: 2;
}
.carrer_ctn .thead{
  padding-right: 40px;
}

 
</style>
