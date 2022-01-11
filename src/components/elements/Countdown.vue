<template>
    <div class="countdown" >
        Starts TOMORROW! Our biggest event of the year... <span><i class="far fa-clock"></i> 00 : 00 : 00 </span> <button>Get Ticket</button>
        
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
            button{
        margin: auto 20px;
        }
}
span{
    color: black;
    padding: 10px;
    font-weight: bold;
}
</style>