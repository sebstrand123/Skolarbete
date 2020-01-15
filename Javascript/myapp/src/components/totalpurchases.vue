<template>
    <div class="card-body">
    <div class="d-flex flex-md-column flex-xl-row flex-wrap  align-items-center justify-content-between">
        <div class="icon-rounded-inverse-info icon-rounded-lg">
            <i class="mdi mdi-basket"></i>
        </div>
        <div class="text-white">
            <p class="font-weight-medium mt-md-2 mt-xl-0 text-md-center text-xl-left">Total Purchases</p>
            <div
                class="d-flex flex-md-column flex-xl-row flex-wrap align-items-baseline align-items-md-center align-items-xl-baseline">
                <h3 id="total-purchases" class="mb-0 mb-md-1 mb-lg-0 mr-1">$387</h3>
                <small class="mb-0">This month</small>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'totalpurchases'
}
</script>