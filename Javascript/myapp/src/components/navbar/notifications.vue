<template>
<div>
    <a class="nav-link count-indicator dropdown-toggle d-flex align-items-center justify-content-center" id="notificationDropdown" href="#" data-toggle="dropdown">
        <i class="mdi mdi-bell mx-0"></i>
    </a>
    <div class="dropdown-menu dropdown-menu-right navbar-dropdown preview-list" 
    aria-labelledby="notificationDropdown">
    <p class="mb-0 font-weight-normal float-left dropdown-header">Notifications</p>

    <Notification :key="notification.title" v-for="notification of notifications" :notification="notification" />

    </div>
</div>    

</template>

<script>
import Notification from './notification'
export default {
    name: 'notifications',
    components: {
        Notification
    },
        data() {
        return {
            notifications: []
        }
    },
    methods() {
    },
    created() {
        fetch("https://inlupp-fa.azurewebsites.net/api/notifications")
        .then(res => res.json())
        .then(data => {
            this.notifications = data;
        })
    }
}
</script>