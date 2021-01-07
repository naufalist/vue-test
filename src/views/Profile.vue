<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="media text-left">
            <img
              src="https://awsimages.detik.net.id/community/media/visual/2018/02/15/f91bd7e4-25b5-4ac7-b1a1-4844d3a3b89b.jpeg?w=700&q=90"
              class="user-pic mr-3"
            />
            <div class="media-body">
              <h5 class="mt-0">{{ firstName }} {{ lastName }}</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <div class="container">
      <div class="row header my-5 p-3">
        <div class="col-lg-12">
          <h2>나는 오늘 무엇을합니까?</h2>
        </div>
      </div>
      <div class="row content">
        <div class="col-lg-12">
          <div class="pekerjaan-rumah">
            <div class="row">
              <div
                v-for="tugasSaya in tugas"
                v-bind:key="tugasSaya.id"
                class="mb-4 tugas col-lg-12 text-left"
              >
                <ItemTugas v-bind:tugasSaya="tugasSaya" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
  </div>
</template>

<script>
// @ is an alias to /src
import ItemTugas from "@/components/ItemTugas.vue";

export default {
  name: "Profile",
  data: function () {
    return {
      firstName: "Bae",
      lastName: "Su-ji",
      tugas: [
        {
          id: 1,
          namaTugas: "Bernyanyi",
          isDone: false,
        },
        {
          id: 2,
          namaTugas: "Main Drakor",
          isDone: false,
        },
        {
          id: 3,
          namaTugas: "Ngebucin",
          isDone: false,
        },
        {
          id: 4,
          namaTugas: "Tidur 2 Jam Rasa 12 Jam",
          isDone: false,
        },
      ],
    };
  },
  components: {
    ItemTugas,
  },
};
</script>

<style scoped>
.user-pic {
  border-radius: 200%;
  height: 80px;
  width: 80px;
}
</style>