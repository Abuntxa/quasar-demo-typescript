# Quasar App

Shows my problems when trying to use the extension of quasar-framework @quasar/typescript with the vue-property-decorator with the template and typescript code in the same file.

Steps to reproduce the environment
1. Create a new quasar empty project with the newest quasar-cli (betav1) 
> quasar create -b dev
2. Add the extension @quasar/typescript with the quasar-cli
> quasar ext add @quasar/typescript
3. Add the vue-property-decorator and vue-class-component dependency
> yarn add vue-property-decorator vue-class-component
4. Modify src/pages/Index.vue to make use of the decorator syntax (copy paste the vue-property-decorator example)

If I set the typescript code in a separate file and reference it from the template `<script lang="ts" src="Index.ts" />` the compiling problems dissapear.
