<template>
    <div class="card">
    <div class="card-body">
        <p class="card-title">Downloads</p>
        <p class="text-muted mb-2">Watching ice melt. This is fun. Only you could make those words cute.</p>
        <div class="row mt-4">
            <div class="col-md-6 stretch-card">
                <div class="row d-flex align-items-center">
                    <div class="col-6">
                        <div id="offlineProgress"></div>
                    </div>
                    <div class="col-6 pl-0">
                        <p class="mb-0">Offline</p>
                        <h2 id="offline-amount">45,324</h2>
                    </div>
                </div>
            </div>
            <div class="col-md-6 stretch-card mt-4 mt-md-0">
                <div class="row d-flex align-items-center">
                    <div class="col-6">
                        <div id="onlineProgress"></div>
                    </div>
                    <div class="col-6 pl-0">
                        <p class="mb-0">Online</p>
                        <h2 id="online-amount">12,236</h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'downloads'
}
</script>