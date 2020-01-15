<template>
    <div class="card">
    <div class="card-body">
        <p class="card-title">Open Invoices</p>
        <div class="row">
            <div class="col-md-12">
                <p class="text-muted mb-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Temporibus,
                    quibusdam eum, totam ut minus dolor eaque alias ratione repellat voluptate, libero beatae nobis
                    facere quod. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cumque harum maxime quaerat
                    quasi earum totam consectetur eius quisquam deleniti et.</p>
            </div>
        </div>
        <div class="table-responsive">
            <table class="table table-striped">
                <thead>
                    <tr class="border-top-0">
                        <th class="text-muted">Invoice</th>
                        <th class="text-muted">Customer</th>
                        <th class="text-muted">Ship</th>
                        <th class="text-muted">Best Price</th>
                        <th class="text-muted">Purchsed Price</th>
                        <th class="text-muted">Status</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>50014</td>
                        <td>David Grey</td>
                        <td>Italy</td>
                        <td class="font-weight-bold">$6300</td>
                        <td>$2100</td>
                        <td>
                            <div class="badge badge-success badge-fw">Progress</div>
                        </td>
                    </tr>
                    <tr>
                        <td>50015</td>
                        <td>Stella Johnson</td>
                        <td>Brazil</td>
                        <td class="font-weight-bold">$4500</td>
                        <td>$4300</td>
                        <td>
                            <div class="badge badge-warning badge-fw">Open</div>
                        </td>
                    </tr>
                    <tr>
                        <td>50016</td>
                        <td>Marina Michel</td>
                        <td>Japan</td>
                        <td class="font-weight-bold">$4300</td>
                        <td>$6440</td>
                        <td>
                            <div class="badge badge-danger badge-fw">On hold</div>
                        </td>
                    </tr>
                    <tr>
                        <td>50017</td>
                        <td>John Doe</td>
                        <td>India</td>
                        <td class="font-weight-bold">$6400</td>
                        <td>$2200</td>
                        <td>
                            <div class="badge badge-success badge-fw">Progress</div>
                        </td>
                    </tr>
                    <tr>
                        <td>50015</td>
                        <td>Stella Johnson</td>
                        <td>Brazil</td>
                        <td class="font-weight-bold">$4500</td>
                        <td>$4300</td>
                        <td>
                            <div class="badge badge-warning badge-fw">Open</div>
                        </td>
                    </tr>
                    <tr>
                        <td>50014</td>
                        <td>David Grey</td>
                        <td>Italy</td>
                        <td class="font-weight-bold">$6300</td>
                        <td>$2100</td>
                        <td>
                            <div class="badge badge-success badge-fw">Progress</div>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'openinvoices'
}
</script>