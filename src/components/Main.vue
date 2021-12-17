<template>
  <v-content class="black">
    <div class="gridContainer">

      <Card :img="'https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Netflix_icon.svg/611px-Netflix_icon.svg.png'" />
      <Card :img="'https://store-images.s-microsoft.com/image/apps.1088.14430220018100179.56fbea89-a097-47a3-9258-2a653b16c1e1.877f32d2-7452-4682-97d6-02b18d4627c5'" />
      <Card :img="'https://www.boldscandinavia.com/wp-content/uploads/2019/05/cmore-2.jpg'" />
      <Card :img="'https://cdn.vox-cdn.com/thumbor/SlOubMprG_kt-04eJXmiDNEF7Hs=/31x0:736x470/1200x800/filters:focal(31x0:736x470)/cdn.vox-cdn.com/assets/1327686/hbonordic.jpg'" />
      <Card :img="'https://www.newsmax.com/CMSPages/GetFile.aspx?guid=8f039070-ce08-4af3-9eff-b820e901c83a&SiteName=Newsmax'" />
      <Card :img="'https://press.discoveryplus.com/wp-content/uploads/2021/01/discovery-plus-logo-vertical-white-wordmark.jpg'" />
    </div>
    <div class="white">
      <div class="creators">

      </div>
      <div class="phoneNumber">

      </div>
    </div>

  </v-content>
</template>
<script>
import Card from "./Card"

export default {
  components: {
    Card,
  },
  data () {
    return {
      dialogm1: "",
      dialog: false,
    }
  },
};
</script>
<style>
.gridContainer {
  padding: 15px;
  display: grid;
  margin-top: 200px;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  grid-auto-rows: 400px;
}
</style>
