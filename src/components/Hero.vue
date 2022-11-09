<template>
          <div class="hero">
            <div class="details">
                <div class="left-div-hero">
                    <h1 class="heading">Drone piloting made simple</h1>
                    <p>Enroll to become certified in drone piloting and operations,
                        explore how drone technologies operate with structed learning.
                    </p>
                    <div class="btn-group">
                    <ButtonVue/>
                    </div>
                </div>
                <div class="right-div-hero">
                    <img src='@/assets/drone.png' alt="" />
                </div>
            </div>
        </div>
</template>

<script>
import ButtonVue from '@/components/Button.vue'
export default {
  components: {
    ButtonVue
  }
}
</script>

<style>
.hero{
    margin-top: 3.5rem;
    padding: 1rem 4rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 70vh;
    text-align: left;
}
.details{
    display: flex;
    flex-direction: row;
    width: 100%;
    padding: 1rem 0;
}
.left-div-hero{
    width: 50%;
    display: flex;
    flex-direction: column;
}
.heading{
    font-size: 4rem;
    width: 70%;
}
.left-div-hero p{
    margin-top: 0.5rem;
    font-size: 1.1rem;
    width: 70%;
}
.btn-group{
    margin-top: 3rem;
    display: flex;
}
.btn-left{
    margin-left: 1rem;
}
.right-div-hero{
    display: flex;
    align-items: center;
    width: 50%;
}
.right-div-hero img{
    height: 15rem;
    width: 22rem;
    margin-left: 4rem;
}

</style>
