<template>
    <h1>HELLO WORLD?</h1>
    <p>
        <strong>Current Root Path: </strong>{{ $route.fullPath }}
    </p>
    <nav>
        <div>
            <router-link class='link' to='/'>Home</router-link>
            <router-link class='link' to='/about'>About</router-link>
        </div>
    </nav>
    <main>
        <router-view/>
    </main>
</template>