<template>
    <NuxtLayout>
        <div class="content-vh" align="center">
            <div class="container">
                <a-typography-title style="font-weight: bold; font-size: 128px; color: #1677FF; margin: 0;">
                    404
                </a-typography-title>

                <a-typography-title style="font-weight: bold; margin: 0 0 10px 0;" :level="2">
                    PAGE NOT FOUND
                </a-typography-title>

                <a-typography-text style="font-size: 20px;">
                    Vous avez l'air perdu. Allez en arrière.
                </a-typography-text>

                <br />

                <NuxtLink to="/">
                    <a-button type="primary" style="margin: 20px 0; width: 100%;">
                        Go Back Home
                    </a-button>
                </NuxtLink>
            </div>
        </div>
    </NuxtLayout>
</template>
