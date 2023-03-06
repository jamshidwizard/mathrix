<template>
 <main class="main">
   <div class="container">
      <div class="main-header"></div>
      <div class="main-subjects">
          <div class="row">
            <div class="main-subjects__block col-3" v-for="({img, title}, index) in subjects" :key="index">
              <div class="d-flex align-items-center justify-content-center flex-column">
                <img :src="img" :alt="title + 'subject'">
                <h2 v-text="title"/>
              </div>
            </div>
          </div>
      </div>
   </div>
 </main>
</template>

<script>
export default {
    name: "HomeView",

    data () {
      return {
        subjects: [
          {
            img: '../../assets/images/subjects/math.svg',
            title: 'Mathematics'
          },
          {
            img: '../../assets/images/subjects/physical.svg',
            title: 'Physical'
          },
          {
            img: '../../assets/images/subjects/svt.svg',
            title: 'SVT'
          },
          {
            img: '../../assets/images/subjects/history_sub.svg',
            title: 'History'
          },
          {
            img: '../../assets/images/subjects/chemistry.svg',
            title: 'Chemistry'
          },
          {
            img: '../../assets/images/subjects/numeric_sci.svg',
            title: 'Numeric Science'
          },
          {
            img: '../../assets/images/subjects/technology.svg',
            title: 'Technology'
          },
          {
            img: '../../assets/images/subjects/philosophy.svg',
            title: 'Philosophy'
          },
          {
            img: '../../assets/images/subjects/geographi.svg',
            title: 'Geography'
          },
          {
            img: '../../assets/images/subjects/french.svg',
            title: 'French'
          },
        ]
      }
    }
}
</script>