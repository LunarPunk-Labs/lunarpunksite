<template>
  <LayoutHero>
    <template slot="hero">
      <hero-container :bg="heroBG">
        <div  class="text-center">
          <div>
            <h1 class="text-6xl">LunarPunk Labs</h1>
          </div>
          <div>
            <h3> Systemic solutions</h3>
          </div>
        </div>
      </hero-container>
    </template>

    <div class="flex flex-wrap my-10">
      <card v-for="card in cards" v-bind="card" :key="card.title"></card>
    </div>

    <div class="bg-white shadow-lg p-10">
      <h2>Our thesis</h2>
      <p>
        According to <a href="https://carbontracker.org/reports/2020-vision-why-you-should-see-the-fossil-fuel-peak-coming/">CarbonTracker.org</a>, the fossil fuel industry is looking at $25tn of fixed assets vunerable to stranding with systemic risks to financial markets as they seek to divest. 
        Fund managers are resultently looking to balance their risk through ESG investments (Enviromental, Social, Governance). 
        The true value of these organisations will very likely be unlocked and accelerated by "Self Soverign Identity" and "Web of Trust" technology. 
      </p>

      <p>
        In our view distributed Identity will:
        <ul class="list-disc py-4 px-4">
          <li> Bring trust back to the internet and become ubiquitous</li>
          <li> Merge with all things physical (Rivers, Forests, Cars, Devices)</li>
          <li> Create new forms of wealth via personal and local currencies</li>
          <li> Create new business models and decimate vendor lock-in by enabling data portability</li>
          <li> Positivly impact user experience through human centric design</li>
          <li> Enable a sense of agency and autonomy by requiring user consent</li>
          <li> Foster the bottom up and build flatter institutions</li>
          <li><strong> Build a resilient world </strong></li>
        </ul>


      </p>
      <h3 id="details">Details</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam lacinia egestas vehicula. Nunc congue augue nunc. Nam fringilla ornare ante a ultricies. Sed tincidunt consequat lorem at lacinia. Donec sit amet commodo augue, sed lacinia arcu. Quisque lacinia risus egestas viverra tincidunt. Donec molestie tellus vel nunc euismod, in suscipit risus fringilla. Nunc congue tincidunt nisi sed eleifend. Nam interdum mauris sed massa viverra, eu porttitor velit ullamcorper. Mauris ac nibh fermentum, faucibus metus eu, placerat ipsum.
        Nunc nec nisi et mauris finibus ultrices nec in neque. Vivamus ut eleifend arcu. Morbi laoreet malesuada congue. Nam mattis tristique finibus. Nulla mattis rhoncus augue in tincidunt. Proin nec lacus ac urna vulputate euismod. Praesent sit amet risus elit. Nulla eget orci vel arcu vestibulum consectetur vel sit amet massa. Nullam congue tincidunt purus, at gravida eros. Donec vitae odio massa. Sed condimentum lectus sit amet arcu luctus, eget suscipit mauris pretium. Sed ac egestas neque. Mauris tortor velit, venenatis et justo sit amet, venenatis lacinia tortor. Nunc nec laoreet magna.
        Vestibulum ac viverra enim. Proin vitae imperdiet tortor. Fusce sed ex pharetra mi elementum efficitur. Sed turpis ligula, lacinia id imperdiet sit amet, viverra eget erat. Maecenas ullamcorper, mi eu pulvinar vulputate, odio lectus fringilla risus, id semper ante nunc in libero. Ut id ipsum augue. Nulla condimentum tellus leo, sed mattis mauris accumsan elementum. Ut aliquet posuere ante sit amet varius. Mauris luctus sed elit nec consectetur. Pellentesque bibendum tellus a venenatis mollis.
        Ut id blandit nibh. Nulla facilisi. Vestibulum in diam varius, ultricies erat id, interdum tellus. Phasellus in purus ut dolor pretium molestie ac at purus. Nullam ullamcorper nec dui eu rutrum. Proin porttitor odio eget odio feugiat blandit ut sed nibh. Nunc sollicitudin quis turpis vitae malesuada. Vivamus dapibus consectetur erat eget lacinia. Nam vel urna lacus. Suspendisse euismod lorem vitae mi convallis, ut interdum enim feugiat. In scelerisque tortor eu elit pharetra sagittis. Sed semper libero ut scelerisque luctus. Morbi vitae dui ex. Phasellus risus odio, laoreet non risus at, placerat consequat tortor. Proin vitae massa iaculis, posuere quam nec, ultrices ante. Nulla tincidunt cursus nibh vel elementum.
        Proin et mauris erat. Nulla ut lacinia leo. Cras sollicitudin diam pellentesque, molestie libero vel, ultricies justo. Duis ut volutpat risus. Donec nec nulla in erat tempus molestie eget nec purus. Cras blandit velit at lorem venenatis, ut condimentum dui luctus. Nullam ornare porttitor fringilla. Donec mauris sapien, imperdiet in magna eget, pellentesque faucibus urna. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis lorem in ante bibendum, at congue enim condimentum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Fusce non diam bibendum, rhoncus lacus et, sagittis lorem.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam lacinia egestas vehicula. Nunc congue augue nunc. Nam fringilla ornare ante a ultricies. Sed tincidunt consequat lorem at lacinia. Donec sit amet commodo augue, sed lacinia arcu. Quisque lacinia risus egestas viverra tincidunt. Donec molestie tellus vel nunc euismod, in suscipit risus fringilla. Nunc congue tincidunt nisi sed eleifend. Nam interdum mauris sed massa viverra, eu porttitor velit ullamcorper. Mauris ac nibh fermentum, faucibus metus eu, placerat ipsum.
        Nunc nec nisi et mauris finibus ultrices nec in neque. Vivamus ut eleifend arcu. Morbi laoreet malesuada congue. Nam mattis tristique finibus. Nulla mattis rhoncus augue in tincidunt. Proin nec lacus ac urna vulputate euismod. Praesent sit amet risus elit. Nulla eget orci vel arcu vestibulum consectetur vel sit amet massa. Nullam congue tincidunt purus, at gravida eros. Donec vitae odio massa. Sed condimentum lectus sit amet arcu luctus, eget suscipit mauris pretium. Sed ac egestas neque. Mauris tortor velit, venenatis et justo sit amet, venenatis lacinia tortor. Nunc nec laoreet magna.
        Vestibulum ac viverra enim. Proin vitae imperdiet tortor. Fusce sed ex pharetra mi elementum efficitur. Sed turpis ligula, lacinia id imperdiet sit amet, viverra eget erat. Maecenas ullamcorper, mi eu pulvinar vulputate, odio lectus fringilla risus, id semper ante nunc in libero. Ut id ipsum augue. Nulla condimentum tellus leo, sed mattis mauris accumsan elementum. Ut aliquet posuere ante sit amet varius. Mauris luctus sed elit nec consectetur. Pellentesque bibendum tellus a venenatis mollis.
        Ut id blandit nibh. Nulla facilisi. Vestibulum in diam varius, ultricies erat id, interdum tellus. Phasellus in purus ut dolor pretium molestie ac at purus. Nullam ullamcorper nec dui eu rutrum. Proin porttitor odio eget odio feugiat blandit ut sed nibh. Nunc sollicitudin quis turpis vitae malesuada. Vivamus dapibus consectetur erat eget lacinia. Nam vel urna lacus. Suspendisse euismod lorem vitae mi convallis, ut interdum enim feugiat. In scelerisque tortor eu elit pharetra sagittis. Sed semper libero ut scelerisque luctus. Morbi vitae dui ex. Phasellus risus odio, laoreet non risus at, placerat consequat tortor. Proin vitae massa iaculis, posuere quam nec, ultrices ante. Nulla tincidunt cursus nibh vel elementum.
        Proin et mauris erat. Nulla ut lacinia leo. Cras sollicitudin diam pellentesque, molestie libero vel, ultricies justo. Duis ut volutpat risus. Donec nec nulla in erat tempus molestie eget nec purus. Cras blandit velit at lorem venenatis, ut condimentum dui luctus. Nullam ornare porttitor fringilla. Donec mauris sapien, imperdiet in magna eget, pellentesque faucibus urna. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis lorem in ante bibendum, at congue enim condimentum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Fusce non diam bibendum, rhoncus lacus et, sagittis lorem.
      </p>
    </div>
  </LayoutHero>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  },

  data() {
    return {
      heroBG: "bg.jpg",
      cards: [
        //{
        //  title: "We're Human",
        //  img: "lunarprint.jpg",
        //  // extraClassImg: "h-64",
        //  content:
        //    "We’re experienced practitioners of human-centric design. We build local first solutions and generalized software that can scale. "
        //},
        
        //{
        //  title: "We're Fluid",
        //  img: "fluidmoon.jpg",
        //  //link: "https://vuejs.org/v2/guide/components-props.html",
        //  content:
        //    "Our direction remains open to change. Our tech stack is flexible, which enables us to iterate quickly and pivot whenever needed. "
        //},

        //{
        //  title: "We're Mycelia",
        //  img: "glowmushrooms.jpg",
        //  content:
        //    "We harness the power of networked thought from within the Hackalong network. Knowledge without borders from collaborators far and wide. "
        //},
        {
          title: "Enviromental",
          img: "glowmushrooms.jpg",
          content:
            "We harness the power of networked thought from within the Hackalong network. Knowledge without borders from collaborators far and wide. "
        },
         {
          title: "Social",
          img: "glowmushrooms.jpg",
          content:
            "We harness the power of networked thought from within the Hackalong network. Knowledge without borders from collaborators far and wide. "
        },
        {
          title: "Governace",
          img: "glowmushrooms.jpg",
          content:
            "We harness the power of networked thought from within the Hackalong network. Knowledge without borders from collaborators far and wide. "
        }
      ]
    };
  }
};
</script>

<style lang="scss">
</style>
