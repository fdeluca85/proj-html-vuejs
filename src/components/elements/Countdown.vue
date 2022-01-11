<template>
    <div class="countdown" >
        Starts TOMORROW! Our biggest biggest event of the year... <i class="far fa-clock"></i> 00:00:00 <button>Get Ticket</button>
        
    </div>
  
</template>

<script>
export default {
    name: 'Countdown'
}
</script>

<style lang="scss" scoped>
.countdown{
    background-color: #F5F5F5;
    text-align: center;
    color: #777777;
    height: 50px;
    line-height: 50px;
    font-size: 0.9em;
        .fa-clock{
        color: black;
        margin: 0 5px 0 20px;
            }
            button{
        margin: auto 20px;
    }
}

</style>