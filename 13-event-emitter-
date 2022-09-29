const EventEmitter = require('events')

const customEmitter = new EventEmitter()

// on - listen for an event
// emit - emit an event
customEmitter.on('response', (name, id) => {
  console.log(`data recieved for ${name} width id ${id}`)
})

customEmitter.on('response', () => {
  console.log(`some logs`)
})

customEmitter.on('response', () => {
  console.log(`more logs`)
})


customEmitter.emit('response', 'dave', 24)