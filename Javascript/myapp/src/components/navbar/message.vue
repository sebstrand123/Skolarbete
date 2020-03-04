  <template>
  <a class="dropdown-item preview-item">
    <div class="preview-thumbnail">
      <img src="https://via.placeholder.com/36x36" alt="image" class="profile-pic" />
    </div>
    <div class="preview-item-content flex-grow">
      <h6 class="preview-subject ellipsis font-weight-normal">{{ message.from }}</h6>
      <p class="font-weight-light small-text text-muted mb-0">{{ message.title }}</p>
    </div>
  </a>
</template>

<script>
export default {
  name: "Message",
  props: {
    message: Object
  }
};
</script>