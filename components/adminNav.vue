<template>
  <nav class="navbar navbar-expand-lg navbar-dark  bg-primary padding fixed-top">
    <NuxtLink class="navbar-brand" to="/admin">Kibeho Sanctuary</NuxtLink>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div id="navbarSupportedContent" class="collapse navbar-collapse ml-auto">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
                <NuxtLink to="/admin/events" class="nav-link">Events <span class="sr-only">(current)</span></NuxtLink>
            </li>
            <li class="nav-item active">
                <NuxtLink to="/admin/events_details" class="nav-link">Events-Details <span class="sr-only">(current)</span></NuxtLink>
            </li>
            <li class="nav-item active">
                <NuxtLink to="/login" class="nav-link">Logout <span class="sr-only">(current)</span></NuxtLink>
            </li>
        </ul>
    </div>
  </nav>

</template>

<script>
export default {

}
</script>

<style>



</style>
