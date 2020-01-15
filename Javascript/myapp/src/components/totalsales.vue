<template>
    <div class="card">
    <div class="card-body">
        <p class="card-title">Total Sales</p>
        <p class="text-muted">Audience to which the users belonged while on the current date Audience to which
            the users belonged while on the current date Audience to which the users belonged while on the current
            date </p>
        <div class="d-flex flex-wrap mb-4 mt-4 pb-4">
            <div class="mr-4 mr-md-5">
                <p class="mb-0">Revenue</p>
                <h4>13,956</h4>
            </div>
            <div class="mr-4 mr-md-5">
                <p class="mb-0">Returns</p>
                <h4>27,219</h4>
            </div>
            <div class="mr-4 mr-md-5">
                <p class="mb-0">Queries</p>
                <h4>03,386</h4>
            </div>
            <div class="mr-4 mr-md-5">
                <p class="mb-0">Invoices</p>
                <h4>04,739</h4>
            </div>
        </div>
        <canvas id="total-sales-chart"></canvas>
    </div>
</div>
</template>

<script>
export default {
    name: 'totalsales'
}
</script>