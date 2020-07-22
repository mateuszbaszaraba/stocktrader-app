<template>
    <b-container class="mt-4">
        <b-navbar toggleable="lg" type="dark" variant="info">
            <router-link class="cursor-pointer" to='/' tag='b-navbar-brand'>Stock Trader</router-link>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>

                    <router-link to='/portfolio' tag="b-nav-item">Portfolio</router-link>
                    <router-link to='/stocks' tag="b-nav-item">Stocks</router-link>

                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">

                    <b-nav-item-dropdown text="Save & Load" right>
                        <b-dropdown-item href="#">Save</b-dropdown-item>
                        <b-dropdown-item href="#">Load</b-dropdown-item>
                    </b-nav-item-dropdown>

                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </b-container>
</template>

<style>
    .cursor-pointer {
        cursor: pointer;
    }
</style>
