<template>
 <div>

  <header>
   <ul>
    <li>
     <NuxtLink to="/contacts">To contacts</NuxtLink>
    </li>
    <li>
     <NuxtLink to="/">To home</NuxtLink>
    </li>
    <li>
     <NuxtLink to="/products">To products</NuxtLink>
    </li>
   </ul>
  </header>
  
  <div>
   <slot/>
  </div>
  
 </div>
</template>