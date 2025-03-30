<template>
     <div class="sec8-data-div">
          <div class="mini-headline-div">
               <h1>Explore the Best Deals & Prime Locations</h1>
          </div>
          <div class="all-data">
               <h1>
                    Find Your Perfect Property<br/>
                    Today!
               </h1>
               <p>
                    Your dream home or ideal investment is just a step away.<br/>
                    Discover top properties in the best locations, handpicked for<br/>
                    you. Let’s make your real estate journey seamless and<br/>
                    rewarding!
               </p>
               <button>
                    <a href="#">
                         Get Started
                    </a>
               </button>
          </div>
     </div>
</template>

<script setup></script>

<style scoped>
.sec8-data-div {
     height: 100%;
     width: 50%;
     display: flex;
     flex-direction: column;
     align-items: start;
     justify-content: center;
}

.mini-headline-div {
     height: 10%;
     width: 100%;
     display: flex;
     align-items: center;
}

.mini-headline-div h1 {
     font-size: 1rem;
     font-weight: 400;
     color: #6582AD;
     border-bottom: 1px solid #6582AD;
     padding-bottom: 0.4rem;
}

.all-data {
     height: 80%;
     width: 100%;
     display: flex;
     flex-direction: column;
     align-items: start;
     justify-content: center;
     gap: 2rem;
}

.all-data h1 {
      font-size: 3rem;
      font-weight: 500;
}

.all-data p {
     font-size: 1.5rem;
     font-weight: 400;
}

.all-data button {
     height: 3.5rem;
     width: 13rem;
     border-radius: 0.5rem;
     border: 2px solid #6582AD;
     background-color: white;
}

.all-data button a {
     font-family: "Orbitron";
     font-size: 1.5rem;
     text-decoration: none;
     color: #6582AD;
}
</style>