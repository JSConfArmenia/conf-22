<template>
  <div class="Job" id="Jobs">
    <h2 class="Title"> JOBS</h2>

    <div class="row Vacancies">
    <!-- Frontend -->
      <div class="col-md-4">
        <a href="https://careers.adobe.com/us/en/job/R145407/Engineering-Manager" target="_blank">
            <h3 class="Vacancy">Engineering Manager</h3>
            <p class="Company">Adobe Armenia</p>
        </a>
      </div>
      <div class="col-md-4">
        <a href="https://www.linkedin.com/jobs/view/3932579437" target="_blank">
            <h3 class="Vacancy">Senior Frontend Developer</h3>
            <p class="Company">Nolan AI</p>
        </a>
      </div>
    <!-- Backend -->
      <div class="col-md-4">
        <a href="https://careers.adobe.com/us/en/job/R144037/Sr-Product-Manager" target="_blank">
            <h3 class="Vacancy">Sr. Product Manager</h3>
            <p class="Company">Adobe Armenia</p>
        </a>
      </div>
      <div class="col-md-4">
        <a href="https://www.linkedin.com/jobs/view/3932090364/" target="_blank">
            <h3 class="Vacancy">VP of Engineering</h3>
            <p class="Company">Nolan AI</p>
        </a>
      </div>
    <!-- Fullstack, Mobile & More -->
      <div class="col-md-4">
        <a href="https://www.simplytechnologies.net/backend-developer" target="_blank">
            <h3 class="Vacancy">Backend Developer</h3>
            <p class="Company">Simply Technologies</p>
        </a>
      </div>
    </div>

  </div>
</template>

<script>
export default {

};
</script>

<style scoped lang="scss">
.Job {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  flex-direction: column;
  padding: 100px 0;
}

a {
  color: #FF00AA;
  font-weight: bold;
}


.Title {
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 50px;
  color: #FF00AA;
  font-size: 32px;
}

.Vacancy {
  color: #333;
}

.Company {
  margin-bottom: 1.5em;
}

.Vacancies {
  width: 65%;
}

@media (max-width: 768px) {
  .Job {
    padding: 50px 0 20px;
  }

  .Vacancies {
    width: 100%;
  }

  .Title {
    font-size: 32px;
    margin-bottom: 20px;
  }

  .Vacancy {
    font-size: 1em;
  }
}
</style>
