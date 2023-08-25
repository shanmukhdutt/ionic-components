<!-- BUTTONS -->

<!-- <template>
  <ion-button expand="block">Block</ion-button>
  <ion-button expand="full">Full</ion-button>
</template>

<script>
import {IonButton} from '@ionic/vue';
import {defineComponent} from 'vue';

export default defineComponent({
  components:{IonButton},
});
</script> -->

<!-- <template>
  <ion-button>Default</ion-button>
  <ion-button :disabled="true">Disabled</ion-button>
</template>
<script lang="ts">
import {IonButton} from '@ionic/vue';
import {defineComponent} from 'vue';

export default defineComponent({
  components:{IonButton},
});

</script> -->
<!-- <template>
  <ion-button expand="block">Block</ion-button>
  <ion-button expand="full">Full</ion-button>
</template>
<script lang="ts">
import{IonButton} from '@ionic/vue';
import { defineComponent } from 'vue';
export default defineComponent({
  components:{IonButton}
});

</script> -->
<!-- <template>
  <ion-button>Default</ion-button>
  <ion-button fill="clear">Clear</ion-button>
  <ion-button fill="outline">Outline</ion-button>
  <ion-button fill="solid"  >Solid</ion-button>
</template> -->
<!-- <template>
  <ion-button size="small">Small</ion-button>
  <ion-button size="default">Default</ion-button>
  <ion-button size="large">Large</ion-button>
</template> -->
<!-- <template>
  <ion-button size="small" fill="outline" expand="full" :disabled="false"  >Button</ion-button>
</template>
<script lang="ts">
import {IonButton} from '@ionic/vue';
import {defineComponent} from 'vue';
export default defineComponent({
  components:{IonButton}
});

</script> -->

<!-- ICONS -->

<!-- <template>
  <ion-button>Left Icon
    <ion-icon slot="start" :icon="star"></ion-icon>
  </ion-button>
  <ion-button>Right Icon
    <ion-icon slot="end" :icon="star"></ion-icon>
  </ion-button>
  <ion-button>
    <ion-icon slot="icon-only" :icon="star"></ion-icon>
  </ion-button>
</template>
<script lang="ts">
import { IonButton,IonIcon } from '@ionic/vue';
import {defineComponent} from 'vue';
import{star} from 'ionicons/icons';
export default defineComponent({
  components:{IonButton,IonIcon},
  setup(){
    return {star};
  },
});
</script> -->


<!-- <template>
  <ion-button>Left Icon
    <ion-Icon></ion-Icon>
  </ion-button>
  <ion-button>Right Icon
    <icon-button></icon-button>
  </ion-button>
  <ion-button>
    <icon-button></icon-button>
  </ion-button>
</template>
<script lang="ts">
import{IonButton,IonIcon} from '@ionic/vue';
import{defineComponent} from 'vue';
import{star} from 'ionicons/icons';
export default defineComponent({
  components:{IonButton,IonIcon},
  setup(){
    return{star};
  },
});
</script>
 -->

 <!-- <template>
 <ion-button>Custom Button</ion-button> 
 </template>
 <script lang="ts">
 import {IonButton} from '@ionic/vue';

</script> -->

<!-- <template>
  <ion-button expand="block">Block</ion-button>
</template>
<script lang="ts">
import {IonButton} from '@ionic/vue';
import {defineComponent} from 'vue';

export default defineComponent({
  components:{IonButton},
});

</script> -->


<!-- <template>
  <div class="wrapper">
    <b>Click on a shape to see the ripple</b>
    <div class="ion-activatable ripple-parent custom-parent">
      Custom Parent color
      <ion-ripple-effect></ion-ripple-effect>
    </div>
    <div class="ion-activable ripple-parent">
      Custom Ripple 
      <ion-ripple-effect class="custom-ripple"></ion-ripple-effect>
    </div>
  </div>
</template>
<script lang="ts">
import { IonRippleEffect } from '@ionic/vue';
import {defineComponent} from 'vue';
export default defineComponent({
  components:{IonRippleEffect},
});
</script>
<style >
  .wrapper{
    display:flex;
    flex-wrap:wrap;
    align-items:center;
    justify-content: space-between;
    text-align:center;
    height:170px;
    width:400px;
    margin:0 auto ;
  }
  b{
    width:100%;
  }
  .ripple-parent{
    display:flex;
    align-items:center;
    justify-content:center;
    position:relative;
    overflow:hidden;
    border:1px solid #ddd;
    user-select:none;
    width:100px;
    height:50px;
    border-radius:8px;
  }
  .custom-parent{
    color:#de1e7e;
  }
  .custom-ripple{
    color:#501ace;
  }
</style> -->
<template>
  <ion-card>
    <ion-card-header>
      <ion-card-title>Card Title</ion-card-title>
      <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
    </ion-card-header>
    <ion-card-content>
      <ion-list>
        <ion-item>
          <ion-thumbnail slot="start">
           <img alt="RcRBridge" src="https://en.wikipedia.org/wiki/File:Nwgbridge.JPG" />
        </ion-thumbnail>
        <ion-lable>Item</ion-lable>
        </ion-item>
        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="ArcBridge" src="https://en.wikipedia.org/wiki/File:Archbridgegodavari.JPG"/>
          </ion-thumbnail>
        </ion-item>
      </ion-list>
    </ion-card-content>
  </ion-card>
</template> 
<script lang="ts">
import { IonCard,IonCardContent,IonCardHeader,IonCardSubtitle} from '@ionic/vue';
import {  defineComponent } from 'vue';
export default defineComponent({
  components:{IonCard,IonCardContent,IonCardHeader,IonCardSubtitle}
});
</script>
<style scoped>
ion-item{
  --padding-start:0;
}
ion-card-header.ios{
  display:flex;
  flex-flow:column-reverse
}
</style>