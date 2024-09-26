<template>
    <div class="signup">
        <div class="container">
            <form @submit.prevent="signup">
                <h2>Sign up</h2>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" v-model="email" required>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" v-model="password" required>
                </div>
                <div class="form-group">
                    <label for="confirmPassword">Confirm Password</label>
                    <input type="password" id="confirmPassword" v-model="confirmPassword" required>
                </div>
                <button type="submit">Sign up</button>
            </form>
        </div>
    </div>
</template>