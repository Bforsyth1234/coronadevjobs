<template>
   <section>
      <b-container fluid>
        <b-row class="height-50 bg-gray-100">
          <b-col sm="12" md="7" lg="6" class="p-5" order="2" order-sm="1">
            <div class="text-center pb-5">
            <g-image
              class="d-md-none d-lg-none"
              src="~/resources/images/brainstorming.svg"
              width="256"
            />
            </div>
            <h3 class="display-4 text-center">Th!nk different</h3>
            <p class="lead">


              Lost your job to the pandemic? 
              <br>
              List yourself on this website so employers can reach out. Then browse the jobs listed here.

            <p class="text-center">
              <g-link to="/jobs" class="btn btn-lg btn-primary">Browse all jobs</g-link>
            </p>
          </b-col>

          <b-col md="5" lg="6" order="1" order-sm="2" class="height-20 d-none d-sm-none d-md-block">
            <g-image
              class="bg-image "
              src="~/resources/images/brainstorming.svg"
              width="400"
              alt="Think different"
            />
          </b-col>
        </b-row>
        
      </b-container>
    </section>
</template>