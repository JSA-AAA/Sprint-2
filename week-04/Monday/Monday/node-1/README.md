# **Node.js part 1**

## **Required Topics**

>*Note: important topics are in **bold***

- Console
- ECMAScript Modules
- **Events - 重要**
- **Process - 重要**
- **Event loop - 重要**

## **Goal**

- [ ] Understand what is Node.js
- [ ] Able to use common console functions
- [ ] Understand Node.js EventEmitter api
- [ ] how to register events?
- [ ] Export/Import type
- [ ] Understand Node event loop and the execution order

## **Key Concepts**

- Node.js
- events
- event loop phases

## **Materials / Study Note**

- [Node.js Doc]( https://nodejs.org/docs/latest-v11.x/api/ )
- [Node.js 中文版]( http://nodejs.cn/api/ )

1. Node.js is a Javascript runtime enviroment built on Chrome V8 JavaScript Engine
   - [Node.js in WiKi]( https://en.wikipedia.org/wiki/Node.js )
   - [What is NodeJS used for?]( https://stackoverflow.com/questions/4531649/what-exactly-is-node-js-used-for )

2. Console Methods
   - [console.log( [data][, ...args] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_log_data_args )
   - [console.table( tabularData[, properties] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_table_tabulardata_properties )
   - [console.count( [label] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_count_label )
   - [console.countReset( [label] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_countreset_label )
   - [console.error( [data][, ...args] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_error_data_args )
   - [console.time( [label] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_time_label )
   - [console.timeLog( [label][, ...data] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_timelog_label_data )
   - [console.timeEnd( [label] )]( https://nodejs.org/docs/latest-v11.x/api/console.html#console_console_timeend_label )
  
3. Events (EventEmitter), process
   - [掘金：Node.js EventEmitter解读]( https://juejin.im/post/5b0189fe51882567161ad8ef )
   - [掘金：Node.js process解读]( https://juejin.im/post/5b0e97bef265da0914072515 )
  
4. Node.js contains support for EcmaScript Modules
   - [ECMAScript Modules](https://nodejs.org/docs/latest-v11.x/api/esm.html)
   - [ECMAScript Modules Vs. CommonJS]( https://www.html.cn/archives/10283 )
  
5. Event-loop
   - [NodeJS 事件系统详解]( https://blog.csdn.net/zccz14/article/details/51463715 )

## **Question Encountered**

>*Note: check after resolved by yourself or during discussion*

- [ ] how to receive return value of a event callback function?
- [ ] what is the value of `this` in event callbacks?
- [ ] what are the differences between setImmediate and setTimeout?
- [ ] node.js can have multiple instances of EventEmitter, and runs in one process, but process is also a instance of EventEmitter - confusing
- [ ] In NodeJS event loop, when poll step back to timer step?
- [ ] How I/O in node.js works?

## **Discussion**

## **Exercises** ( Optional )

- [console and events]( assets/node-1_questions.js )
- [Node.js event-loop]( assets/node_eventLoop.js )