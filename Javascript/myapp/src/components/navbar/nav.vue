<template>
    <div class="horizontal-menu">
    <nav class="navbar top-navbar col-lg-12 col-12 p-0">
        <div class="container">
            <div class="navbar-menu-wrapper d-flex align-items-center">
                <ul class="navbar-nav navbar-nav-right">
                    <li class="nav-item dropdown mr-1">

                        <Messages />

                    </li>
                    <li class="nav-item dropdown mr-4">

                        <Notifications />

                    </li>
                    <li class="nav-item nav-profile dropdown mr-0 mr-sm-2">
                        <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown" id="profileDropdown">
                            <img src="https://via.placeholder.com/40x40" alt="profile" />
                            <span class="nav-profile-name">Don Richards</span>
                        </a>
                        <div class="dropdown-menu dropdown-menu-right navbar-dropdown"
                            aria-labelledby="profileDropdown">
                            <a class="dropdown-item">
                                <i class="mdi mdi-settings text-primary"></i>
                                Settings
                            </a>
                            <a class="dropdown-item">
                                <i class="mdi mdi-logout text-primary"></i>
                                Logout
                            </a>
                        </div>
                    </li>
                </ul>
                <button class="navbar-toggler navbar-toggler-right d-lg-none align-self-center" type="button"
                    data-toggle="horizontal-menu-toggle">
                    <span class="mdi mdi-menu"></span>
                </button>
            </div>
        </div>
    </nav>
</div>
</template>

<script>
import Messages from './messages'
import Notifications from './notifications'

export default {
    name: "nav",
    components: {
        Messages,
        Notifications,
    }
}
</script>