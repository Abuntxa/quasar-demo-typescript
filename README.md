# Quasar App

Shows the problems when using the extension of quasar-framework @quasar/typescript

Steps to reproduce the environment
1. Create a new quasar empty project with the newest quasar-cli (betav1) 
> quasar create -b dev
2. Add the extension @quasar/typescript with the quasar-cli
> quasar ext add @quasar/typescript
3. Add the vue-property-decorator dependency
> yarn add vue-property-decorator
4. Modify Index.vue to make use of the decorator syntax
