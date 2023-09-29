<template>
    <div class="test">
        {{ msg }}
        <br/>
        <br/>
        <input type="text" v-model="name"/>
    </div>
</template>

<script>
export default{
    name : 'TestComp',
    data : ()=>{
        return {
            name : "manish1"
        }
    }
}
</script>