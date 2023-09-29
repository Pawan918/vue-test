<template>
    <div class="test">
        <br/>
        <br/>
        <div class="">{{ message }}</div>
        <input type="text" v-model="message"/>
    </div>
</template>

<script>
export default{
    name : 'TestComp',
    data : ()=>{
        return {
            message : ''
        }
    },
    created : function(){
        console.log("created")
    },
    mounted : function(){
        console.log("mounted")
    },
    // updated : function(){
    //     console.log(updated)
    // },

}
</script>