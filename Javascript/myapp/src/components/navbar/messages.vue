<template>
    <div>
        <a class="nav-link count-indicator dropdown-toggle d-flex justify-content-center align-items-center" id="messageDropdown" href="#" data-toggle="dropdown">
            <i class="mdi mdi-email mx-0"></i>
        </a>
                    
        <div class="dropdown-menu dropdown-menu-right navbar-dropdown preview-list" aria-labelledby="messageDropdown">
            <p class="mb-0 font-weight-normal float-left dropdown-header">Messages</p>
                       
            <Message :key="message.from" v-for="message of messages" :message="message" />

        </div>  
    </div>
</template>

<script>
import Message from './message'
export default {
    name: "Messages",
    components: {
        Message
    },
    data() {
        return {
            messages: []
        }
    },
    methods() {
    },
    created() {
        fetch("https://inlupp-fa.azurewebsites.net/api/messages")
        .then(res => res.json())
        .then(data => {
            this.messages = data;
        })
    }
}
</script>