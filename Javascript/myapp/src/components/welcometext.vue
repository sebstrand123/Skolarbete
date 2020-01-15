<template>
    <div class="row">
    <div class="col-md-12 grid-margin">
        <div class="card bg-white">
            <div class="card-body d-flex align-items-center justify-content-between">
                <h4 id="welcome-message" class="mt-1 mb-1">Hi {{name}}, Welcomeback!</h4>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'welcome',
    props: {
        name: String
    }
}
</script>