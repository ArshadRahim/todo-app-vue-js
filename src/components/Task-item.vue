 <template>
    
 <li> 
            <button> <i class="far fa-circle"></i> {{task.title}}</button>
            <button @click="$emit('remove')" ><i class="far fa-trash-alt"></i></button>
          </li>
    
</template>

<script>
    export default {
        name : "taskItem",
        props : ['task']
    }
</script>

<style lang="scss" scoped>

</style>