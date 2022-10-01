<template>
    <div>
         <nuxt />
    </div>
</template>
<style>
#wrapper {
    height: calc(100vh - 63px);
}
#sidebar {
    width: 80px;
    height: 100%;
    transition: all 0.3s ease;
}
.sidebar-item {
    white-space: nowrap;
}

.text-sidebar {
    display: none;
    margin-left: 9px;
}

#sidebar.change {
    width: 280px;
}
.change .text-sidebar {
    display: inline;
}

.line1,
.line2,
.line3 {
    width: 30px;
    height: 2px;
    background: rgb(0, 0, 0);
    margin: 5px;
    transition: all 0.3s;
}

.change .line1 {
    transform: rotate(-405deg) translate(-5px, 5px);
    background: rgb(0, 0, 0);
}

.change .line2 {
    opacity: 0;
}

.change .line3 {
    transform: rotate(405deg) translate(-5px, -5px);
    background: rgb(0, 0, 0);
}
</style>
<script>
export default {
    data() {
        return {
            sidebarOpen: false,
        };
    },
};
</script>


