<template>
  <div>
    <div class="container-scroller">

      <Nav />

      <div class="container-fluid page-body-wrapper">
        <div class="main-panel">
          <div class="content-wrapper">
            <div class="row">
              <div class="col-md-12 grid-margin">

            <Welcometext :name="name" />

              </div>
            </div>
            <div class="row">
              <div class="col-xl-6 grid-margin">
                <div class="row">
                  <div class="col-md-6 grid-margin stretch-card">
                    <div class="card">

                      <Users />

                      <canvas id="users-chart"></canvas>
                    </div>
                  </div>

                  <div class="col-md-6 grid-margin stretch-card">
                    <div class="card">

                      <Projects />

                      <canvas id="projects-chart"></canvas>
                    </div>
                  </div>
                </div>

                <div class="row">
                  <div class="col-md-12 stretch-card">

                    <Downloads />

                  </div>
                </div>
              </div>

              <div class="col-xl-6 grid-margin stretch-card">

                <Totalsales />

              </div>
            </div>

            <div class="row">
              <div class="col-md-3 grid-margin stretch-card">
                <div class="card border-0 border-radius-2 bg-success">

                  <Salesthismonth />

                </div>
              </div>
              <div class="col-md-3 grid-margin stretch-card">
                <div class="card border-0 border-radius-2 bg-info">

                  <Totalpurchases />

                </div>
              </div>
              <div class="col-md-3 grid-margin stretch-card">
                <div class="card border-0 border-radius-2 bg-danger">

                  <Totalorders />

                </div>
              </div>
              <div class="col-md-3 grid-margin stretch-card">
                <div class="card border-0 border-radius-2 bg-warning">

                  <Totalgrowth />

                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-xl-8 grid-margin stretch-card">
                <div class="card">

                  <Tickets />

                </div>
              </div>
              <div class="col-xl-4 grid-margin stretch-card">
                <div class="card">

                  <Updates />

                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-xl-3 grid-margin stretch-card">
                <div class="card">

                  <Distribution />

                  <canvas id="distribution-chart"></canvas>

                  <Body />

                </div>
              </div>

              <div class="col-xl-9 grid-margin stretch-card">
                <div class="card">
                  <div class="row">
                    <div class="col-md-7 col-lg-6 col-xl-7">

                      <Salesreport />

                    </div>
                    <div class="col-md-5 col-lg-6 col-xl-5">

                      <Salesreportoverview />

                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-12">

                <Openinvoices />

              </div>
            </div>
          </div>

          <Footer />

        </div>
      </div>
    </div>
  </div>
</template>



<script>
import Nav from "./components/navbar/nav";
import Welcometext from "./components/welcometext";
import Users from "./components/users";
import Projects from "./components/projects";
import Downloads from "./components/downloads";
import Totalsales from "./components/totalsales";
import Salesthismonth from "./components/salesthismonth";
import Totalpurchases from "./components/totalpurchases";
import Totalorders from "./components/totalorders";
import Totalgrowth from "./components/totalgrowth";
import Tickets from "./components/tickets";
import Updates from "./components/updates";
import Distribution from "./components/distributiontext/distribution";
import Body from "./components/distributiontext/body";
import Salesreport from "./components/salesreport";
import Salesreportoverview from "./components/salesreportoverview";
import Openinvoices from "./components/openinvoices";
import Footer from "./components/footer";

export default {
  name: "app",
  components: {
    Nav,
    Welcometext,
    Users,
    Projects,
    Downloads,
    Totalsales,
    Salesthismonth,
    Totalpurchases,
    Totalorders,
    Totalgrowth,
    Tickets,
    Updates,
    Distribution,
    Body,
    Salesreport,
    Salesreportoverview,
    Openinvoices,
    Footer
  },
  data() {
    return {
      name: String
    };
  },
  created() {
    fetch(
      "https://inlupp-fa.azurewebsites.net/api/users?firstname=Sebastian&lastname=Strandberg"
    )
      .then(res => res.text())
      .then(data => {
        this.name = data;
      });
  }
};
</script>

