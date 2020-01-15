<template>
    <div class="card-body">
    <p class="card-title">Sales report overview</p>
    <p class="pb-2 text-muted">Sale information on advertising, exhibitions, market research, online
        media, customer desires, PR and much more</p>
    <div class="d-flex flex-wrap justify-content-start mt-3 mr-4">
        <div class="mr-3">
            <p class="mb-0">Downloads</p>
            <h4>13,956</h4>
        </div>
        <div class="mr-3">
            <p class="mb-0">Purchases</p>
            <h4>55,123</h4>
        </div>
        <div class="mr-3">
            <p class="mb-0">Users</p>
            <h4>29829</h4>
        </div>
    </div>
    <div class="d-flex mb-3">
        <i class="mdi mdi-arrow-expand-up mb-0 text-success mr-2 mt-1"></i>
        <p class="mb-0 text-dark">15% more than last week</p>
    </div>
    <div class="d-flex flex-wrap mb-5">
        <button class="btn btn-info mt-3 mr-2">Update</button>
        <button class="btn btn-outline-light mt-3 text-dark">More</button>
    </div>
</div>
</template>

<script>
export default {
    name: 'salesreportoverview'
}
</script>