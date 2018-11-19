<template>
    <div id="names" class="container my-3 col-lg-6">
        <ul class="list-group-flush">
            <li v-for="name in team" v-on:click="name.show= !name.show" class="list-group-item">
                <h3 class="text-warning"><span class="text-dark">Name:</span>{{name.name}}</h3>
                <h4 class="text-muted pl-4" v-show="name.show"><span class="text-dark">Speciality:</span> {{name.speciality}} </h4>
                <i v-show="name.show" class="fa fa-github-alt pl-5" aria-hidden="true"></i>
                <i v-show="name.show" class="fa fa-facebook pl-4" aria-hidden="true"></i>
                <i v-show="name.show" class="fa fa-google pl-4" aria-hidden="true"></i>
                <i v-show="name.show" class="fa fa-linkedin pl-4" aria-hidden="true"></i>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  data() {
    return {
      team: [
        { name: "Prahalad", speciality: "HTML", show: false },
        { name: "Ankesh", speciality: "CSS", show: false },
        { name: "Sumedh", speciality: "JS", show: false },
        { name: "Shubham", speciality: "php", show: false },
        { name: "Omkar", speciality: "Vue", show: false },
        { name: "Abhishek", speciality: "Bootstrap", show: false },
        { name: "Bhaktij", speciality: "React", show: false },
        { name: "Bhagyarsh", speciality: "Django", show: false }
      ]
    };
  }
};
</script>

<style scoped>
i {
  color: rgb(0, 255, 21);
}
i:hover {
  color: blue;
}
</style>
