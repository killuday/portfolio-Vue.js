<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark}">
    <NavigationBar/>
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="Snapchat-1937804819.jpg" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h3 class="red--text text=darken-4 top">Hello I am Uday Bhanu</h3>
          <h1 class="grey--text">Visual Designer</h1>
          <p clas="black--text">
            Hello I am Uday Bhanu a Web Developer fresher with knowledge of 
            Java,Vanilla JavaScript,TypeScript,HTML,CSS and JavaScript frameworks,libraries Node.js,Vue.js,React.js,express.js, 
            and i worked on databases too both relational and non relational MySQL,MongoDB.
          </p>
          <v-btn title color="#A7121D" dark href="https://www.instagram.com/killuday/" target="_blank">about me</v-btn>
        </v-col>
        <v-col cols="12" class="padd">
        <div class="first" id="project">
          <v-row>
            <v-col cols="12">
              <div class="child bgColor1">
                <v-icon color="#A7121D" x-large class="ml-3">
                  mdi-palette-swatch
                </v-icon>
                <h3 class="black--text ml-3 mt-4">UI Design</h3>
                <p class="grey--text ml-3 mt-6">
                  I design user interfaces with  <br>
                  JavaScript Frameworks,libraries 
                  
                </p> 
                <v-btn color="#A7121D" dark text href="https://xd.adobe.com/ideas/process/ui-design/" target="_blank">
                  know more
                  <v-icon right>mdi-arrow-right</v-icon>
                </v-btn>
              </div>
              <div class="child bgColor2">
                <v-icon color="#A7121D" x-large class="ml-3">
                  mdi-network-pos
                </v-icon>
                <h3 class="black--text ml-3 mt-4">Server Side</h3>
                <p class="grey--text ml-3 mt-6">
                I love to work in server side<br>
                speically with Node.js
                </p>
                <v-btn color="#A7121D" dark text href="https://nodejs.dev/en/" target="_blank">
                  know more
                  <v-icon right>mdi-arrow-right</v-icon>
                </v-btn>
              </div>
              <div class="child bgColor1">
                <v-icon color="#A7121D" x large class="ml-3">
                  mdi-database
                </v-icon>
                <h3 class="black--text ml-3 mt-4">Database</h3>
                <p class="grey--text ml-3 mt-6">
                  I can handle databases too<br>
                Both relational and non-relational.
                </p>
                <v-btn color="#A7121D" dark text href="https://www.mongodb.com/" target="_blank">
                  know more
                  <v-icon right>mdi-arrow-right</v-icon>
                </v-btn>
              </div>
            </v-col>
            <v-col cols="12" class="mt-10">
              <div class="child1">
                <h1 class="red--text text-darken-4 mt-4 number">2</h1>
                <h3 class="black--text mt-4">Two months experience</h3>
              </div>
              <div class="child2 mRight">
                <v-row>
                  <v-col cols="12" class="childcol1">
                    <div class="child2 mButton padding bgColor1">
                    <h1 class="red--text text--darken-4 ">60+</h1>
                    <p class="grey--text ">Intern days</p>
                  </div>
                  </v-col>
                  <v-col cols="12" class="childcol1">
                    <div class="child2 padding bgColor1">
                    <h1 class="red--text text--darken-4 ">12+</h1>
                    <p class="grey--text ">Completed Projects</p>
                  </div>
                  </v-col>
                </v-row>
              </div>
              <div class="child2">
                <v-row>
                  <v-col cols="12" class="childcol1">
                    <div class="child2 mButton padding bgColor1">
                    <h1 class="red--text text--darken-4 ">02</h1>
                    <p class="grey--text ">Months Experience</p>
                  </div>
                  </v-col>
                  <v-col cols="12" class="childcol1">
                    <div class="child2 padding bgColor1">
                    <h1 class="red--text text--darken-4 ">10</h1>
                    <p class="grey--text ">Achievements</p>
                  </div>
                  </v-col>
                </v-row>
              </div>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <v-col md="3" offset-md="3" id="about">
        <h4 class="black-text">Featured Projects</h4>
        <p class="grey--text">
          Thank you very much<br>
          enhanced monitoring procedures.
        </p>
      </v-col>
      <v-col md="3" class="text-end">
      <v-btn title color="#A7121D" dark>View All</v-btn>
      </v-col>
      <v-col md="3" offset-md="3">
        <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
          <v-img src="node.jpg" contain></v-img>
        </v-card>
      </v-col>
      <v-col md="3" >
        <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
          <v-img src="html.png" contain></v-img>
        </v-card>
      </v-col>
      <v-col md="3" offset-md="3">
        <v-btn color="black" light class text="ml-n4">
          Node.js
        </v-btn><br />
        <v-btn color="#A7121D" light text class="m1-n4">
          know more
          <v-icon right>mdi-arrow-right</v-icon>
        </v-btn>
      </v-col>
      <v-col md="3">
        <v-btn color="black" light class text="ml-n4">
          HTML,CSS,JavaScript
        </v-btn><br />
        <v-btn color="#A7121D" light text class="m1-n4">
          know more
          <v-icon right>mdi-arrow-right</v-icon>
        </v-btn>
      </v-col>
      <v-col md="3" offset-md="3">
        <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
          <v-img src="nest2.jpg" contain></v-img>
        </v-card>
      </v-col>
      <v-col md="3" >
        <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
          <v-img src="database.jpg" contain></v-img>
        </v-card>
      </v-col>
      <v-col md="3" offset-md="3">
        <v-btn color="white" light class text="ml-n4">
          Nest.js
        </v-btn><br />
        <v-btn color="#A7121D" light text class="m1-n4">
          know more
          <v-icon right>mdi-arrow-right</v-icon>
        </v-btn>
      </v-col>
      <v-col md="3">
        <v-btn color="white" light class text="ml-n4">
          Databases
        </v-btn><br />
        <v-btn color="#A7121D" light text class="m1-n4">
          know more
          <v-icon right>mdi-arrow-right</v-icon>
        </v-btn>
      </v-col>
      <v-col cols="12" class="padd topInverse">
        <div class="second">
          <div class="secondchild1" id="contact">
            <v-row>
              <v-col cols="7">
                <h1 class="white--text">
                  Lets work together on<br />
                  your next project
                </h1>
                <p class="grey--text">
                  Conceptualizing original ideas that bring simplicity
                  and user friendliness to complex design roadblocks
                </p>
              </v-col>
              <v-col cols="5">
                <v-btn tile color="#A7121D" light class="mt-16" href ="mailto:bhanusharm122@gmail.com">Contact</v-btn>
              </v-col>
            </v-row>
          </div>
        </div>
        <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Home</v-btn>
              <v-btn text>Project</v-btn>
              <v-btn text>about</v-btn>
              <v-btn text> contact</v-btn>
            </div>
          </v-toolbar>
      </v-col>
      </v-row>
    </v-container>
    <FooterBar />
  </v-app>
  
</template>


<script>

import NavigationBar from '../components/NavigationBar.vue';
import FooterBar from '../components/FooterBar.vue';

  export default {
    name: 'HomeView',

    components: {
    NavigationBar,
    FooterBar,
},
  }
</script>
<style scoped>
  .top{
    margin-top: 180px;
  }

  .topInverse{
    margin-top: -250px;
  }

  .topToolbar{
    margin-top:100px;
    text-align: center;
  }

  .first{
    width:100%;
    height:610px;
    background: linear-gradient(
      to right,
      #181818,
      #181818 50%,
      #111111 50%,
      #111111 50%,
    );
    text-align: center;
    padding: 2rem 2rem;
  }
   .second {
    width:100%;
    height:600px;
    background:#181818;
    text-align: center;
    padding: 2rem 2rem;
   }

   .secondchild1{
    display: inline-block;
    background-color: #1e1e1e;
    padding: 2rem 1rem;
    vertical-align:middle;
    text-align: left;
    margin-top: 250px;
   }

   .child{
    display: inline-block;
    padding: 2rem 1rem;
    vertical-align: middle;
    text-align: left;
    margin-right: 8px;
   }

   .bgcolor1{
    background-color: #1e1e1e;
   }

   .bdcolor2{
    background-color: #ce1d2a;
   }

   .child1{
    display:inline-block;
    padding: 2rem 1rem;
    vertical-align: middle;
    margin-right: 5px;
    width:240px;
   }

   .child2{
    display: inline-block;
    width: 245px;
    vertical-align: middle;
   }

   .mRight{
    margin-right: 8px;
   }

   .mButton{
    margin-bottom: 8px;
   }

   .padding{
    padding:8px 0px ;
   }

   .col-12.padd{
    padding: 12px 0 !important;
   }

   .col-12.childcol{
    padding:0 !important;
   }

   h1.number{
    font-size: 50px;
    font-weight: bold;
   }


</style>
