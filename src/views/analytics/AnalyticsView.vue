<script>
import PortfolioIntro from "../../components/common/PortfolioIntro.vue";
import UserPersona from "./UserPersona.vue";

export default {
  components: {
    UserPersona,
    PortfolioIntro,
  },
  data() {
    return {
      project: {
        title: "Analytics",
        startDate: "June",
        endDate: "September",
      },
    };
  },
};
</script>

<template>
  <nav>
    <RouterLink to="/analytics/user-persona">User Persona</RouterLink>
  </nav>
  <PortfolioIntro
    :endDate="project.endDate"
    :startDate="project.startDate"
    :title="project.title"
  >
    <template #about>Lorem ipsum 12345</template>
  </PortfolioIntro>
  <UserPersona />
</template>
