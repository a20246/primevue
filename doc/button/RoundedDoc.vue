<template>
    <DocSectionText v-bind="$attrs">
        <p>Rounded buttons have a circular border radius.</p>
    </DocSectionText>
    <div class="card flex justify-content-center flex-wrap gap-3">
        <Button label="Primary" rounded />
        <Button label="Secondary" severity="secondary" rounded />
        <Button label="Success" severity="success" rounded />
        <Button label="Info" severity="info" rounded />
        <Button label="Warning" severity="warning" rounded />
        <Button label="Help" severity="help" rounded />
        <Button label="Danger" severity="danger" rounded />
    </div>
    <DocSectionCode :code="code" />
</template>

<script>
export default {
    data() {
        return {
            code: {
                basic: `
<Button label="Primary" rounded />
<Button label="Secondary" severity="secondary" rounded />
<Button label="Success" severity="success" rounded />
<Button label="Info" severity="info" rounded />
<Button label="Warning" severity="warning" rounded />
<Button label="Help" severity="help" rounded />
<Button label="Danger" severity="danger" rounded />
`,
                options: `
<template>
    <div class="card flex justify-content-center flex-wrap gap-3">
        <Button label="Primary" rounded />
        <Button label="Secondary" severity="secondary" rounded />
        <Button label="Success" severity="success" rounded />
        <Button label="Info" severity="info" rounded />
        <Button label="Warning" severity="warning" rounded />
        <Button label="Help" severity="help" rounded />
        <Button label="Danger" severity="danger" rounded />
    </div>
</template>

<script>
<\/script>
`,
                composition: `
<template>
    <div class="card flex justify-content-center flex-wrap gap-3">
        <Button label="Primary" rounded />
        <Button label="Secondary" severity="secondary" rounded />
        <Button label="Success" severity="success" rounded />
        <Button label="Info" severity="info" rounded />
        <Button label="Warning" severity="warning" rounded />
        <Button label="Help" severity="help" rounded />
        <Button label="Danger" severity="danger" rounded />
    </div>
</template>

<script setup>
<\/script>
`
            }
        };
    }
};
</script>
