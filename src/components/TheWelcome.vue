<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Who is he?</template>

    Riku Kandaは日本在住の大学生です. 
    <ul>
      <li>年齢: 19歳(2004年生まれ)</li>
      <li>拠点: 名古屋</li>
      <li>学歴: 名古屋外国語大学 (在学)</li>
      <li>性格: 週７で家に女を連れ込むクズ. 付き合った女をメンヘラにする</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>About Him</template>

    Riku Kandaはスケボーのプロフェッショナルです. 彼のスケボースキルのせいで親友の口癖を「リクはスケボーがあるやん」に変えてしまいました.
     <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading> Product</template>
    <ul>
      <li>ファッションEC「
        <a href="https://imaceobitch.netlify.app/">nne7er</a>
        」</li>Stack: Django, Vue.js, AWS
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>
    週一で優秀な弟子にモテのイロハを教えています. 弟子は全てを吸収する姿勢で今では外見で2人を区別することはできません.  また, メイヘム計画の首謀者です.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>
    <ul>
      <li>Instagram: 
        <a href="https://www.instagram.com/__al_.sxce/">@__al_.sxce</a>
      </li>
    </ul>
    <!-- <img alt="Vue logo" src="./assets/スクリーンショット 2023-12-27 20.58.52.png" class="logo"  width="270" height="352" /> -->
  </WelcomeItem>
</template>