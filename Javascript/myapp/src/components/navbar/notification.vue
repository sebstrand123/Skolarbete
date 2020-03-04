<template>
  <a class="dropdown-item preview-item">
    <div class="preview-thumbnail">
      <div class="preview-icon bg-success">
        <i class="mdi mdi-information mx-0"></i>
      </div>
    </div>
    <div class="preview-item-content">
      <h6 class="preview-subject font-weight-normal">{{notification.title}}</h6>
      <p class="font-weight-light small-text mb-0 text-muted">{{notification.subtitle}}</p>
    </div>
  </a>
</template>

<script>
export default {
  name: "notification",
    props: {
        notification: Object
    }
};
</script>