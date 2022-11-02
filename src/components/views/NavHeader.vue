<template>
  <div class="header navbar-fixed-top">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
          <a href="index.html"><img src="../../mainboard/images/logo.png" /></a>
        </div>
        <div class="col-lg-8 col-md-8 col-sm-12 col-xs-12">
          <div class="navigation">
            <div id="navigation">
              <ul>
                <li class="active">
                  <router-link to="/" title="Home">홈</router-link>
                </li>
                <li class="active">
                  <router-link to="#" title="Home">소개</router-link>
                </li>
                <li class="active">
                  <router-link to="#" title="Home">이용방법</router-link>
                </li>
                <li class="active">
                  <router-link to="/board" title="Home">게시판</router-link>
                </li>
                <li class="has-sub">
                  <router-link to="#" title="Blog ">로그인</router-link>
                  <ul>
                    <li>
                      <router-link to="/login" title="Blog">로그인</router-link>
                    </li>
                    <li>
                      <router-link to="/" title="Blog Single ">회원가입</router-link>
                    </li>
                  </ul>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavHeader',
  setup () {
    return {}
  }
}
</script>
<style>
@import '../../mainboard/css/style.css';
</style>

