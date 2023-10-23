<template>
  <main class="main">
    
    <div class="roadmap">
      <h2 class="section-title">PhD Application Roadmap</h2>
      <div class="roadmap-steps">
        <div class="roadmap-step">
          <div class="step-icon">
            <i class="fas fa-book"></i>
          </div>
          <div class="step-details">
            <h3>Improve Your CV</h3>
            <p>Start by publishing articles to enhance your CV.</p>
          </div>
        </div>
        <div class="roadmap-step">
          <div class="step-icon">
            <i class="fas fa-language"></i>
          </div>
          <div class="step-details">
            <h3>IELTS Preparation</h3>
            <p>Improve your English language skills and achieve a good IELTS score.</p>
          </div>
        </div>
        <div class="roadmap-step">
          <div class="step-icon">
            <i class="fas fa-users"></i>
          </div>
          <div class="step-details">
            <h3>Contact Supervisors</h3>
            <p>Reach out to potential supervisors for available positions.</p>
          </div>
        </div>
        <div class="roadmap-step">
          <div class="step-icon">
            <i class="fas fa-file-alt"></i>
          </div>
          <div class="step-details">
            <h3>Apply for Positions</h3>
            <p>Submit your applications for the available PhD positions.</p>
          </div>
        </div>
        <div class="roadmap-step">
          <div class="step-icon">
            <i class="fas fa-check-circle"></i>
          </div>
          <div class="step-details">
            <h3>Prepare for Interviews</h3>
            <p>Get ready for interviews and further evaluation.</p>
          </div>
        </div>
      </div>
    </div>
    <NewsLetter />
  </main>
</template>

<script>
import NewsLetter from './NewsLetter.vue';

export default {
  components: {
    NewsLetter,
  }
}
</script>

<style scoped>
/* Styles for the roadmap section */
.roadmap {
  text-align: center;
  margin: 2rem 0;
}

.section-title {
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 2rem;
}

/* Styles for roadmap steps */
.roadmap-steps {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 2rem;
}

.roadmap-step {
  flex: 0 0 calc(33.33% - 2rem);
  text-align: center;
  border: 2px solid #3498db;
  padding: 1.5rem;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.step-icon {
  font-size: 2rem;
  background:linear-gradient(135deg,  #2c3e50, #bdc3c7);
}

.step-details {
  margin-top: 1rem;
}

/* You can use Font Awesome icons in this example by adding the necessary FontAwesome library to your project. */
</style>
