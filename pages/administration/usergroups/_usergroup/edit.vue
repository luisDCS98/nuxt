<template>
    <div class="columns is-centered">
        <div class="column is-half-desktop is-full-touch">
            <enso-form class="box has-background-light raises-on-hover"/>
        </div>
    </div>
</template>

<script>
import { EnsoForm } from '@enso-ui/forms/bulma';

export default {
    name: 'administration.userGroups.edit',
    // path: ':userGroup/edit',
    meta: {
        breadcrumb: 'edit',
        title: 'Edit User Group',
    },

    components: { EnsoForm },
};
</script>
