<template>
  <div class="fs-xxl">
    <div class="msg bg-white px-2" style="background-color:White;">
        <h1 style="margin-left:20px;">Call For Papers</h1>
        <Cfp />
    </div>
    <!-- <h4 class="pt-2 text-center">
      Important Dates
      <i class="el-icon-date el-icon--right"></i>
    </h4>
    <el-row type="flex" class="row-bg" justify="space-around">
      <el-col :span="7.5">
        <div class="grid-content bg-purple"></div>
      </el-col>
    </el-row>
    <div class="mx-5 text-center">
      <TimeTable />
    </div> -->

    <!-- <h1>Call For Paper</h1>
    <p>The 2021 IEEE International Conference on Real-time Computing 
      and Robotics (IEEE RCAR 2021) will take place from July 15 to 19, 2021 in the beautiful 
      city of Xining, Qinghai, China. The objective of this conference is to provide a forum 
      for researchers in robotics and real-time computing to share the latest results and to 
      explore the opportunity of research collaboration. With wide applications of robots 
      in industry and services sectors, real-time computing plays one of the major roles 
      in various topics in robotics including real-time control, human-robot interactions, 
      sensor perception and fusion, robot intelligence, etc. The scope of IEEE RCAR 2021 
      covers research, development and applications in the dynamic and exciting areas of 
      real-time computing and robotics.</p>
    <p>
      <span class="phead fw-xxl text-red">Contributed Papers:</span> 
      Original papers are solicited in all related areas of robotics, 
      mechatronics, control engineering. Full papers must be submitted 
      in PDF format prepared strictly following the requirements for 
      creating PDF documents. The conference proceedings will be submitted 
      to the IEEE Xplore® digital library.
    </p>
    <p>
      <span class="phead fw-xxl text-red">Tutorials & Workshops:</span> 
      Proposals for tutorials and workshops addressing new topics related 
      to robotics and real-time computing are invited for submission to the T/W chairs.
    </p>
    <p>
      <span class="phead fw-xxl text-red">Journal Publications:</span> 
      Expanded versions of the accepted and presented papers with high 
      quality will be invited for publication in the RCAR 2021 special 
      issues in the selected leading international journals.
    </p>
    <p
      class="fw-xxl phead"
    >Areas and topics of contributed papers include but are not limited to the following:</p>
    <div class="pl-4">
      <p>• robotics and intelligent mechatronics systems;</p>
      <p>• sensing, perception and control theories and their applications;</p>
      <p>• real-time imaging, image/video processing and their applications;</p>
      <p>• selected frontier areas, such as soft robotics, artificial intelligence, computational biomechanics, etc, and their applications.</p>
    </div>
    <p>Xining, located in the northeast of the Qinghai-Tibet Plateau, is the capital of 
      Qinghai Province. Xining has good ecology and pleasant environment. With an average 
      temperature of 18.3℃ in summer, it is known as "Cool City in the World" and "China's 
      Summer Capital". Xining's multi-ethnic population, multi-religious coexistence, and 
      multi-cultural gathering have formed an open and inclusive city and a splendid local 
      customs. It is rich in tourism resources, including the famous Tibetan Buddhism holy 
      site Taer Monastery and Dongguan Mosque. It is only 150 kilometers away from Qinghai 
      Lake, the largest saltwater lake in inland China.</p>
    <p>IEEE RCAR 2021 promises to be a great event for all participants, with excellent 
      technical and social programs.</p> -->
  </div>
</template>


<script>
import Vue from "vue";
import Cfp from "./../components/Cfp.vue";
import TimeTable from "./../components/TimeTable.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "CallForPapers",
  components: {
    Cfp,
    TimeTable,
  },
};
</script>

<style>
.Cfp {
  max-width: 1366px;
  margin:auto;
}
</style>
