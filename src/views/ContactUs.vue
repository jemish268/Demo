<template>
    <form v-on:submit="submit">
        Enter Your Message
        <input type="text" placeholder="Enter your Message">
        <br><br>
        Enter Your Email
        <input type="email" placeholder="Enter your Email">
        <br><br>
        <button type="submit" value="Submit"> Submit  </button>

    </form>
</template>


<script>
export default {
    name:"Form",
    methods : {
        submit(event){
            event.preventDefault();
            console.log("Hello");
        }
    }
}
</script>