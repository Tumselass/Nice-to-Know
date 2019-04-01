# Nice-to-Know
Tips and tricks I don't want to spend yet another 30 min of my life searching the web for

# Vue.js
Disable eslint in `<Template>`<br/><br/>
`<!-- eslint-disable -->`<br/>
`<!-- eslint-enable -->`<br/>
`<!-- eslint-disable-line -->`<br/>
`<!-- eslint-disable-next-line -->`<br/>


Emit event from functional single file component

    <template functional>
      <button @click="listeners['custom-event']('message from child')">
        Button from child
      </button>
    </template>

https://stackoverflow.com/questions/50288996/how-to-emit-an-event-from-vue-js-functional-component
