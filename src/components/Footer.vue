<script setup></script>

<template>
    <footer>
        <h1 class="contacts-title heading">跟我們聯絡</h1>
        <h2 class="contacts-subtitle">下訂單跟探險我們的內容</h2>
        <ul class="contacts-list">
            <li class="contacts-item">
                <a class="contacts-item-link">
                    <i class="contacts-item-icon fa-brands fa-line"></i>
                </a>
            </li>
            <li class="contacts-item">
                <a class="contacts-item-link">
                    <i class="contacts-item-icon fa-brands fa-facebook"></i>
                </a>
            </li>
            <li class="contacts-item">
                <a class="contacts-item-link">
                    <i class="contacts-item-icon fa-brands fa-instagram"></i>
                </a>
            </li>
        </ul>
        <p>© Copyright 2023 Muguo</p>
    </footer>
</template>

<style scoped>
footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 50px 0px;
}

.contacts-title {
    margin: 0px;
}

.contacts-subtitle {
    font-weight: 500;
    font-family: 'Noto Serif TC';
}

.contacts-list {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 30px;
    align-items: center;
    justify-content: center;
    margin: 30px 0px;
}

.contacts-item-icon {
    font-size: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: white;
    color: var(--text);
    padding: 10px;
    border-radius: 50%;
}

.contacts-item-icon:hover {
    color: #3e4e50c5
}
</style>