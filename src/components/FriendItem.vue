<template>
    <li>
     <img :src="image" :alt="name"/>   
     <h2>
        {{ name }}
         </h2>
         <button>Show Détails</button>
<ul>
    <li>adress : {{adress}}</li>
    <li>Phone :{{Phone}}</li>
    <li>Email : {{Email}}</li>
</ul>

</template>