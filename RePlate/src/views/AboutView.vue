<template>
  <div class="scroll-container">
    <div class="about"style=" max-width: fit-content; max-height: fit-content;">
      <h1 class="main_title">About Us</h1>
      <div class="info-container">
        <div class="section">
          <div class="purpose">
            <div class="image-container"><img alt="Our Purpose" src="@/assets/our-purpose.png" width="100" height="100" class="mix-blend-multiply" /></div>
            <h2 class="title">Our Purpose</h2>
            <p class="powerful_description">Turning food waste into community support: RePlate.</p>
            <p class="description">
              RePlate aims to eliminate food waste and foster community values by bridging the gap between businesses with surplus food and individuals and charities who can use it.
            </p>
            <p class="description">
              Whether we are connecting bakeries with unsold pastries or a restaurant with extra meals, we make it easy for them to connect with local organisations and people in real time. Businesses reduce waste, and people in need are able to access sustainable, quality meals.
            </p>
          </div>
        </div>

        <div class="section">
          <div class="do">
            <div class="image-container"><img alt="What we do" src="@/assets/what-we-do.png" width="100" height="100" class="mix-blend-multiply" /></div>
            <h2 class="title">What We Do</h2>
            <p class="description">
              We connect people and businesses with excess food, with those who need it. If you have perfectly good food that will otherwise go to waste, simply post a photo of the food and what people need to know, and others can come and collect it!
            </p>
          </div>
        </div>

        <div class="section">
          <div class="us">
            <div class="image-container"><img alt="Us" src="@/assets/the-team.png" width="100" height="100" class="mix-blend-multiply"/></div>
            <h2 class="title">Who Are We?</h2>
            <p class="description">
              We are a group of University students who are passionate about sustainability and supporting our local community. Being the change we want to see: we have embarked on this journey to minimise quality food that goes to the bin, hoping that one day no one has to go to bed hungry.
            </p>
          </div>
        </div>

        <div class="section">
          <div class="involved">
            <div class="image-container"><img alt="Unity Image" src="@/assets/unity.png" width="100" height="100" class="mix-blend-multiply"/></div>
            <h2 class="title">Get Involved</h2>
            <p class="description">No matter how big or small: Sign up today to start sharing and collecting valuable ingredients.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .scroll-container {
  width: 100%;
  max-width: 5000px; 
  max-height: 800px; 
  overflow: auto;
  border: 0px solid #ccc;
  padding: 20px;
  background: var(--vt-c-green);
  margin: auto;
}
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
  }

  .main_title {
    font-family:Georgia, 'Times New Roman', Times, serif;
    color: #ffffff;
    font-size: 3rem;
    font-weight: 600;
    margin-bottom: 20px;
  }

  .section {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 20px;
  }

  .title {
    color: #a2611f;
    font-size: 2rem;
    margin-bottom: 10px;
  }

  .powerful_description {
    font-size: 1.25rem;
    color: #a2611f;
    max-width: 800px;
    text-align: center;
    margin-bottom: 10px;
  }

  .description {
    font-size: 0.9rem;
    max-width: 800px;
    line-height: 1.5;
    color: #2A2420;
    text-align: center;
  }

  .purpose, .do, .us, .involved {
    background-color: #D9D8D5;
    padding: 20px;
    border-radius: 15px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    width: 100%;
  }

  .image-container {
  display: grid;
  place-items: center;
  }
}
</style>

