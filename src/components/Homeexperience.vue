<template>
<section>
    <v-container grid-list-lg id="experience">
        <v-layout row>
            <v-flex xs12 class="text-xs-center display-1 font-weight-black my-5" data-aos= "zoom-in">Experience</v-flex>
        </v-layout>
            <v-flex xs12 sm12 md12> 
                <v-timeline align-top xs12 sm12 md12>
                    <v-timeline-item
                    v-for="(item, i) in items"
                    :key="i"
                    :text="item.text"
                    :body="item.body"
                    :sub="item.sub"
                    :at="item.at"
                    :color="item.color"
                    :icon="item.icon"
                    :year="items.year"
                    fill-dot
                    >
                    <template v-slot:opposite>
                        <span
                        class="font-weight-bold subheading"
                        v-text="item.year"
                        ></span>
                    </template>
                    <v-card
                        :color="item.color"
                        dark
                        class="card-shadow" data-aos="zoom-in-down"
                    >
                        <v-card-title class="title headline">{{item.text}} </v-card-title>
                        <v-card-text class="white text--primary subheading">
                        <p><strong>{{item.body}} </strong></p>
                        <p><strong>{{item.sub}} </strong></p>
                        <p>{{item.at}}</p>
                        </v-card-text>
                    </v-card>
                    </v-timeline-item>
                </v-timeline>
            </v-flex>
    </v-container>
  </section>  
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Prince of Songkla University',
          body: 'Bechelor of Science',
          sub: 'Information and Communication Technology',
           at: 'GPA : 2.54',
          color: 'green lighten-1',
          icon: 'school',
          year: '2011 - 2016'
        },
        {
          text: 'Freelance Photography', 
          body: 'Congratulations Day , Party Concert , Wedding Day , ',
          sub: 'Photobook , Event',
           at: 'Hatyai , Thailand',
          color: 'amber darken-2',
          icon: 'camera_alt',
          year: '2013-2016'
        },
        {
          text: 'Pretest Thailand',  
          body: 'POSITION : Graphic Design & Multimedia',
          sub: '',
           at: 'Hatyai , Thailand',
          color: 'red lighten-2 ',
          icon: 'business_center',
          year: '2017-2018'
        },
        {
          text: 'Phuket Fantasea', 
          body: 'POSITION : Web & Graphic Design', 
          sub: '',
           at: 'Phuket , Thailand',
          color: 'grey darken-1',
          icon: 'business_center',
          year: '2018-2019'
        }
      ]
    })
  }
</script>

<style>
.card-shadow{
    -webkit-box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
          box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
}
</style>