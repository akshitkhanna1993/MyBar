.<template>
  
     <ion-card>
       <img  :src="drink.strDrinkThumb"/>
       <ion-card-header>
         <ion-card-subtitle>
           {{drink.strCategory}} | served in {{drink.strGlass}}
         </ion-card-subtitle>
            </ion-card-header>
         <ion-card-title>
           {{drink.strDrink}}
         </ion-card-title>
         <ion-card-content>
           <p>  {{drink.strInstructions}} </p>
           <ion-list-header>Ingredients</ion-list-header>
           <ion-list>
             <ion-item  v-if="drink.strIngredient1">
               <ion-label>
                 <span v-if="drink.strMeasure1"> 
                   {{drink.strMeasure1}}
                 </span>
                 {{drink.strIngredient1}}
               </ion-label>
             </ion-item>
                <ion-item  v-if="drink.strIngredient2">
               <ion-label>
                 <span v-if="drink.strMeasure2"> 
                   {{drink.strMeasure2}}
                 </span>
                 {{drink.strIngredient2}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient3">
               <ion-label>
                 <span v-if="drink.strMeasure3"> 
                   {{drink.strMeasure3}}
                 </span>
                 {{drink.strIngredient3}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient4">
               <ion-label>
                 <span v-if="drink.strMeasure4"> 
                   {{drink.strMeasure4}}
                 </span>
                 {{drink.strIngredient4}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient5">
               <ion-label>
                 <span v-if="drink.strMeasure5"> 
                   {{drink.strMeasure5}}
                 </span>
                 {{drink.strIngredient5}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient6">
               <ion-label>
                 <span v-if="drink.strMeasure6"> 
                   {{drink.strMeasure6}}
                 </span>
                 {{drink.strIngredient6}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient7">
               <ion-label>
                 <span v-if="drink.strMeasure7"> 
                   {{drink.strMeasure7}}
                 </span>
                 {{drink.strIngredient7}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient8">
               <ion-label>
                 <span v-if="drink.strMeasure8"> 
                   {{drink.strMeasure8}}
                 </span>
                 {{drink.strIngredient8}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient9">
               <ion-label>
                 <span v-if="drink.strMeasure9"> 
                   {{drink.strMeasure9}}
                 </span>
                 {{drink.strIngredient9}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient10">
               <ion-label>
                 <span v-if="drink.strMeasure10"> 
                   {{drink.strMeasure10}}
                 </span>
                 {{drink.strIngredient10}}
               </ion-label>

             </ion-item>
              <ion-item  v-if="drink.strIngredient11">
               <ion-label>
                 <span v-if="drink.strMeasure11"> 
                   {{drink.strMeasure11}}
                 </span>
                 {{drink.strIngredient11}}
               </ion-label>

             </ion-item>

             
           </ion-list>
         </ion-card-content>
    
     </ion-card>
</template>

<script  lang="ts">


export default {

name:"DrinkCard",
props:{
    drink:Object
}


}
</script>
