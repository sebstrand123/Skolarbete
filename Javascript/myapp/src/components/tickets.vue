<template>
    <div class="card-body">
    <div class="d-flex justify-content-between align-items-md-end flex-wrap">
        <p class="card-title">Tickets</p>
        <div class="dropdown mb-3 mb-md-0">
            <button class="btn btn-sm btn-outline-light dropdown-toggle text-dark" type="button" id="dropdownMenuDate1"
                data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                2018
            </button>
            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="dropdownMenuDate1">
                <a class="dropdown-item" href="#">2015</a>
                <a class="dropdown-item" href="#">2016</a>
                <a class="dropdown-item" href="#">2017</a>
                <a class="dropdown-item" href="#">2018</a>
            </div>
        </div>
    </div>
    <div class="table-responsive">
        <table class="table tickets-table mb-2">
            <thead>
                <th class="text-muted pl-0">
                    Name
                </th>
                <th></th>
                <th class="text-muted">
                    Date
                </th>
                <th class="text-muted">
                    Projects
                </th>
            </thead>
            <tbody>
                <tr>
                    <td class="pl-0">
                        <div class="icon-rounded-primary icon-rounded-md">
                            <h4 class="font-weight-medium">AL</h4>
                        </div>
                    </td>
                    <td>
                        <p class="mb-0">Alta Lucas</p>
                        <p class="text-muted mb-0">Connecticut</p>
                    </td>
                    <td>
                        <p class="mb-0">31 Aug 2018</p>
                        <p class="text-muted mb-0">9:30 am</p>
                    </td>
                    <td>
                        <p class="mb-0">6770 Verner Burgs</p>
                        <p class="text-muted mb-0">View on map</p>
                    </td>
                    <td class="pr-0">
                        <i class="mdi mdi-dots-horizontal icon-sm cursor-pointer"></i>
                    </td>
                </tr>
                <tr>
                    <td class="pl-0">
                        <div class="icon-rounded-info icon-rounded-md">
                            <h4 class="font-weight-medium">TS</h4>
                        </div>
                    </td>
                    <td>
                        <p class="mb-0">Teresa Shaw</p>
                        <p class="text-muted mb-0">Florida</p>
                    </td>
                    <td>
                        <p class="mb-0">13 May 2018</p>
                        <p class="text-muted mb-0">10:30 am</p>
                    </td>
                    <td>
                        <p class="mb-0">1300 Gideon Divide Apt. 400</p>
                        <p class="text-muted mb-0">Start session</p>
                    </td>
                    <td class="pr-0">
                        <i class="mdi mdi-dots-horizontal icon-sm cursor-pointer"></i>
                    </td>
                </tr>
                <tr>
                    <td class="pl-0">
                        <div class="icon-rounded-danger icon-rounded-md">
                            <h4 class="font-weight-medium">RU</h4>
                        </div>
                    </td>
                    <td>
                        <p class="mb-0">Rosa Underwood</p>
                        <p class="text-muted mb-0">North Dakota</p>
                    </td>
                    <td>
                        <p class="mb-0">02 Jan 2018</p>
                        <p class="text-muted mb-0">11:00 am</p>
                    </td>
                    <td>
                        <p class="mb-0">9576 Rempel Extension</p>
                        <p class="text-muted mb-0">End session</p>
                    </td>
                    <td class="pr-0">
                        <i class="mdi mdi-dots-horizontal icon-sm cursor-pointer"></i>
                    </td>
                </tr>
                <tr>
                    <td class="pl-0">
                        <div class="icon-rounded-warning icon-rounded-md">
                            <h4 class="font-weight-medium">VR</h4>
                        </div>
                    </td>
                    <td>
                        <p class="mb-0">Vilson Rowa</p>
                        <p class="text-muted mb-0">Densar</p>
                    </td>
                    <td>
                        <p class="mb-0">05 Nov 2018</p>
                        <p class="text-muted mb-0">02:30 am</p>
                    </td>
                    <td>
                        <p class="mb-0">1072 Orion Expansion</p>
                        <p class="text-muted mb-0">On Way</p>
                    </td>
                    <td class="pr-0">
                        <i class="mdi mdi-dots-horizontal icon-sm cursor-pointer"></i>
                    </td>
                </tr>
                <tr>
                    <td class="pl-0">
                        <div class="icon-rounded-info icon-rounded-md">
                            <h4 class="font-weight-medium">TS</h4>
                        </div>
                    </td>
                    <td>
                        <p class="mb-0">Teresa Shaw</p>
                        <p class="text-muted mb-0">Florida</p>
                    </td>
                    <td>
                        <p class="mb-0">13 May 2018</p>
                        <p class="text-muted mb-0">10:30 am</p>
                    </td>
                    <td>
                        <p class="mb-0">1300 Gideon Divide Apt. 400</p>
                        <p class="text-muted mb-0">Start session</p>
                    </td>
                    <td class="pr-0">
                        <i class="mdi mdi-dots-horizontal icon-sm cursor-pointer"></i>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</div>
</template>

<script>
export default {
    name: 'tickets'
}
</script>