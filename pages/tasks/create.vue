<template>
    <div class="columns is-centered">
        <div class="column is-three-quarters-desktop is-full-touch">
            <base-form/>
        </div>
    </div>
</template>

<script>
import BaseForm from '~/components/tasks/bulma/pages/tasks/BaseForm.vue';

export default {
    name: 'tasks.create',
    meta: {
        breadcrumb: 'create',
        title: 'Create Task',
    },

    components: { BaseForm },
};
</script>
