<template>
    <div class="columns is-multiline is-centered">
        <div class="column is-two-thirds-desktop">
            <user-profile/>
        </div>
    </div>
</template>

<script>
import UserProfile from '~/components/users/bulma/pages/users/components/UserProfile.vue';

export default {
    name: 'administration.users.show',
    meta: {
        breadcrumb: 'show',
        title: 'User Profile',
    },

    components: { UserProfile },
};
</script>
