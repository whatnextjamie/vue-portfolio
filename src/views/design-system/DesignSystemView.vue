<script>
import PortfolioIntro from "../../components/common/PortfolioIntro.vue";

export default {
  components: {
    PortfolioIntro,
  },
  data() {
    return {
      project: {
        title: "Design System",
        startDate: "January",
        endDate: "June",
      },
    };
  },
};
</script>

<template>
  <PortfolioIntro
    :endDate="project.endDate"
    :startDate="project.startDate"
    :title="project.title"
  >
    <template #about>Lorem ipsum 67890</template>
  </PortfolioIntro>
</template>
