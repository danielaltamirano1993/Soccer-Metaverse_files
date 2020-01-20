(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function ba(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var da="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ea(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ea(this);function n(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&da(c,a,{configurable:!0,writable:!0,value:b})}}
n("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.i=f;da(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.i};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
n("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&da(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(ba(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function p(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:ba(a)}}
function ia(a){if(!(a instanceof Array)){a=p(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ka(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var oa="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ka(d,e)&&(a[e]=d[e])}return a};
n("Object.assign",function(a){return a||oa});
var pa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},qa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=pa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),sa;
if("function"==typeof Object.setPrototypeOf)sa=Object.setPrototypeOf;else{var ta;a:{var ua={a:!0},va={};try{va.__proto__=ua;ta=va.a;break a}catch(a){}ta=!1}sa=ta?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var wa=sa;
function t(a,b){a.prototype=pa(b.prototype);a.prototype.constructor=a;if(wa)wa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Y=b.prototype}
function ya(){this.B=!1;this.m=null;this.j=void 0;this.i=1;this.o=this.s=0;this.v=this.l=null}
function za(a){if(a.B)throw new TypeError("Generator is already running");a.B=!0}
ya.prototype.N=function(a){this.j=a};
function Aa(a,b){a.l={Qb:b,Wb:!0};a.i=a.s||a.o}
ya.prototype.return=function(a){this.l={return:a};this.i=this.o};
function v(a,b,c){a.i=c;return{value:b}}
ya.prototype.u=function(a){this.i=a};
function Ba(a,b,c){a.s=b;void 0!=c&&(a.o=c)}
function Ca(a,b){a.i=b;a.s=0}
function Da(a){a.s=0;var b=a.l.Qb;a.l=null;return b}
function Ea(a){a.v=[a.l];a.s=0;a.o=0}
function Fa(a){var b=a.v.splice(0)[0];(b=a.l=a.l||b)?b.Wb?a.i=a.s||a.o:void 0!=b.u&&a.o<b.u?(a.i=b.u,a.l=null):a.i=a.o:a.i=0}
function Ga(a){this.i=new ya;this.j=a}
function Ha(a,b){za(a.i);var c=a.i.m;if(c)return Ia(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.i.return);
a.i.return(b);return Ja(a)}
function Ia(a,b,c,d){try{var e=b.call(a.i.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.i.B=!1,e;var f=e.value}catch(g){return a.i.m=null,Aa(a.i,g),Ja(a)}a.i.m=null;d.call(a.i,f);return Ja(a)}
function Ja(a){for(;a.i.i;)try{var b=a.j(a.i);if(b)return a.i.B=!1,{value:b.value,done:!1}}catch(c){a.i.j=void 0,Aa(a.i,c)}a.i.B=!1;if(a.i.l){b=a.i.l;a.i.l=null;if(b.Wb)throw b.Qb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ka(a){this.next=function(b){za(a.i);a.i.m?b=Ia(a,a.i.m.next,b,a.i.N):(a.i.N(b),b=Ja(a));return b};
this.throw=function(b){za(a.i);a.i.m?b=Ia(a,a.i.m["throw"],b,a.i.N):(Aa(a.i,b),b=Ja(a));return b};
this.return=function(b){return Ha(a,b)};
this[Symbol.iterator]=function(){return this}}
function La(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function w(a){return La(new Ka(new Ga(a)))}
function Ma(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
n("Reflect",function(a){return a?a:{}});
n("Reflect.construct",function(){return qa});
n("Reflect.setPrototypeOf",function(a){return a?a:wa?function(b,c){try{return wa(b,c),!0}catch(d){return!1}}:null});
n("Promise",function(a){function b(g){this.i=0;this.l=void 0;this.j=[];this.B=!1;var h=this.m();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.i=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.j=function(g){if(null==this.i){this.i=[];var h=this;this.l(function(){h.o()})}this.i.push(g)};
var e=fa.setTimeout;c.prototype.l=function(g){e(g,0)};
c.prototype.o=function(){for(;this.i&&this.i.length;){var g=this.i;this.i=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.m(m)}}}this.i=null};
c.prototype.m=function(g){this.l(function(){throw g;})};
b.prototype.m=function(){function g(m){return function(q){k||(k=!0,m.call(h,q))}}
var h=this,k=!1;return{resolve:g(this.K),reject:g(this.o)}};
b.prototype.K=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.R(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.J(g):this.s(g)}};
b.prototype.J=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.T(h,g):this.s(g)};
b.prototype.o=function(g){this.N(2,g)};
b.prototype.s=function(g){this.N(1,g)};
b.prototype.N=function(g,h){if(0!=this.i)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.i);this.i=g;this.l=h;2===this.i&&this.P();this.v()};
b.prototype.P=function(){var g=this;e(function(){if(g.F()){var h=fa.console;"undefined"!==typeof h&&h.error(g.l)}},1)};
b.prototype.F=function(){if(this.B)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.l;return k(g)};
b.prototype.v=function(){if(null!=this.j){for(var g=0;g<this.j.length;++g)f.j(this.j[g]);this.j=null}};
var f=new c;b.prototype.R=function(g){var h=this.m();g.Ua(h.resolve,h.reject)};
b.prototype.T=function(g,h){var k=this.m();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(x,u){return"function"==typeof x?function(A){try{m(x(A))}catch(D){q(D)}}:u}
var m,q,r=new b(function(x,u){m=x;q=u});
this.Ua(k(g,m),k(h,q));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Ua=function(g,h){function k(){switch(m.i){case 1:g(m.l);break;case 2:h(m.l);break;default:throw Error("Unexpected state: "+m.i);}}
var m=this;null==this.j?f.j(k):this.j.push(k);this.B=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=p(g),q=m.next();!q.done;q=m.next())d(q.value).Ua(h,k)})};
b.all=function(g){var h=p(g),k=h.next();return k.done?d([]):new b(function(m,q){function r(A){return function(D){x[A]=D;u--;0==u&&m(x)}}
var x=[],u=0;do x.push(void 0),u++,d(k.value).Ua(r(x.length-1),q),k=h.next();while(!k.done)})};
return b});
n("WeakMap",function(a){function b(k){this.i=(h+=Math.random()+1).toString();if(k){k=p(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ka(k,g)){var m=new c;da(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(q){if(q instanceof c)return q;Object.isExtensible(q)&&e(q);return m(q)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),q=new a([[k,2],[m,3]]);if(2!=q.get(k)||3!=q.get(m))return!1;q.delete(k);q.set(m,4);return!q.has(k)&&4==q.get(m)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ka(k,g))throw Error("WeakMap key fail: "+k);k[g][this.i]=m;return this};
b.prototype.get=function(k){return d(k)&&ka(k,g)?k[g][this.i]:void 0};
b.prototype.has=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.i)};
b.prototype.delete=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.i)?delete k[g][this.i]:!1};
return b});
n("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.i;return ha(function(){if(m){for(;m.head!=h.i;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var q=h.data_[m];if(q&&ka(h.data_,m))for(h=0;h<q.length;h++){var r=q[h];if(k!==k&&r.key!==r.key||k===r.key)return{id:m,list:q,index:h,entry:r}}return{id:m,list:q,index:-1,entry:void 0}}
function e(h){this.data_={};this.i=b();this.size=0;if(h){h=p(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(p([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),q=m.next();if(q.done||q.value[0]!=h||"s"!=q.value[1])return!1;q=m.next();return q.done||4!=q.value[0].x||"t"!=q.value[1]||!m.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.i,previous:this.i.previous,head:this.i,key:h,value:k},m.list.push(m.entry),this.i.previous.next=m.entry,this.i.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.i=this.i.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),q;!(q=m.next()).done;)q=q.value,h.call(k,q[1],q[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Na(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
n("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Na(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
n("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
n("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Na(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
n("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
n("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
n("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
function Oa(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
n("Array.prototype.entries",function(a){return a?a:function(){return Oa(this,function(b,c){return[b,c]})}});
n("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
n("Array.prototype.keys",function(a){return a?a:function(){return Oa(this,function(b){return b})}});
n("Set",function(a){function b(c){this.i=new Map;if(c){c=p(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.i.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(p([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.i.set(c,c);this.size=this.i.size;return this};
b.prototype.delete=function(c){c=this.i.delete(c);this.size=this.i.size;return c};
b.prototype.clear=function(){this.i.clear();this.size=0};
b.prototype.has=function(c){return this.i.has(c)};
b.prototype.entries=function(){return this.i.entries()};
b.prototype.values=function(){return this.i.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.i.forEach(function(f){return c.call(d,f,f,e)})};
return b});
n("Array.prototype.values",function(a){return a?a:function(){return Oa(this,function(b,c){return c})}});
n("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
n("Object.setPrototypeOf",function(a){return a||wa});
n("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
n("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
n("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Na(this,b,"includes").indexOf(b,c||0)}});
n("globalThis",function(a){return a||fa});
n("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push([d,b[d]]);return c}});
n("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push(b[d]);return c}});
var Pa=Pa||{},y=this||self;function z(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Qa(a){a.sb=void 0;a.getInstance=function(){return a.sb?a.sb:a.sb=new a}}
function Ra(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Sa(a){var b=Ra(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Ta(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ua(a){return Object.prototype.hasOwnProperty.call(a,Va)&&a[Va]||(a[Va]=++Wa)}
var Va="closure_uid_"+(1E9*Math.random()>>>0),Wa=0;function Xa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ya(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Za(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Za=Xa:Za=Ya;return Za.apply(null,arguments)}
function $a(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function ab(a,b){function c(){}
c.prototype=b.prototype;a.Y=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.gq=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function bb(a){return a}
;function cb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,cb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
ab(cb,Error);cb.prototype.name="CustomError";function db(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.l=!b&&/[?&]ae=1(&|$)/.test(a);this.m=!b&&/[?&]ae=2(&|$)/.test(a);if((this.i=/[?&]adurl=([^&]*)/.exec(a))&&this.i[1]){try{var c=decodeURIComponent(this.i[1])}catch(d){c=null}this.j=c}}
;function eb(){}
function fb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var gb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},hb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},ib=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},jb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},kb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
hb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function lb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function mb(a,b){b=gb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function nb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Sa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ob(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function pb(a){var b=qb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function rb(a){for(var b in a)return!1;return!0}
function sb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function tb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function ub(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function vb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function wb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=wb(a[c]);return b}
var xb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function yb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<xb.length;f++)c=xb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var zb;function Ab(){if(void 0===zb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:bb,createScript:bb,createScriptURL:bb})}catch(c){y.console&&y.console.error(c.message)}zb=a}else zb=a}return zb}
;function Bb(a,b){this.l=a===Cb&&b||""}
Bb.prototype.j=!0;Bb.prototype.i=function(){return this.l};
function Fb(a){return new Bb(Cb,a)}
var Cb={};Fb("");var Gb={};function Hb(a){this.l=Gb===Gb?a:"";this.j=!0}
Hb.prototype.toString=function(){return this.l.toString()};
Hb.prototype.i=function(){return this.l.toString()};function Ib(a,b){this.l=b===Jb?a:""}
Ib.prototype.toString=function(){return this.l+""};
Ib.prototype.j=!0;Ib.prototype.i=function(){return this.l.toString()};
function Kb(a){if(a instanceof Ib&&a.constructor===Ib)return a.l;Ra(a);return"type_error:TrustedResourceUrl"}
var Jb={};function Lb(a){var b=Ab();a=b?b.createScriptURL(a):a;return new Ib(a,Jb)}
;var Mb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Nb(a,b){return a<b?-1:a>b?1:0}
;function Ob(a,b){this.l=b===Pb?a:""}
Ob.prototype.toString=function(){return this.l.toString()};
Ob.prototype.j=!0;Ob.prototype.i=function(){return this.l.toString()};
function Qb(a){if(a instanceof Ob&&a.constructor===Ob)return a.l;Ra(a);return"type_error:SafeUrl"}
var Rb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Pb={},Sb=new Ob("about:invalid#zClosurez",Pb);function Tb(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Tb().indexOf(a)}
;function Ub(){return C("Trident")||C("MSIE")}
function Vb(){return C("Firefox")||C("FxiOS")}
function Wb(){return C("Safari")&&!(Xb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Vb()||C("Silk")||C("Android"))}
function Xb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function $b(){return C("Android")&&!(Xb()||Vb()||C("Opera")||C("Silk"))}
function ac(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function bc(a){var b=Tb();if("Internet Explorer"===a){if(Ub())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=ac(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Xb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Vb()||"Safari"===a&&Wb()||"Android Browser"===a&&$b()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function cc(a){a=bc(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var dc={};function ec(a){this.l=dc===dc?a:"";this.j=!0}
ec.prototype.i=function(){return this.l.toString()};
ec.prototype.toString=function(){return this.l.toString()};function fc(a,b){b instanceof Ob||b instanceof Ob||(b="object"==typeof b&&b.j?b.i():String(b),Rb.test(b)||(b="about:invalid#zClosurez"),b=new Ob(b,Pb));a.href=Qb(b)}
function gc(a,b){a.rel="stylesheet";a.href=Kb(b).toString();(b=hc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function ic(){return hc("script[nonce]")}
var jc=/^[\w+/_-]+[=]{0,2}$/;function hc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&jc.test(a)?a:"":""}
;function kc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var lc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function mc(a){return a?decodeURI(a):a}
function nc(a,b){return b.match(lc)[a]||null}
function oc(a){return mc(nc(3,a))}
function pc(a){var b=a.match(lc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function qc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function sc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)rc(a[b],a[b+1],c);return c.join("&")}
function tc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function uc(a,b){var c=2==arguments.length?sc(arguments[1],0):sc(arguments,1);return qc(a,c)}
function yc(a,b){b=tc(b);return qc(a,b)}
function zc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return qc(a,b+c)}
function Ac(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var Bc=/#|$/,Cc=/[?&]($|#)/;function Dc(a,b){for(var c=a.search(Bc),d=0,e,f=[];0<=(e=Ac(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Cc,"$1")}
;var Ec={};function Fc(a){if(a!==Ec)throw Error("requires a valid immutable API token");}
;function Gc(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Hc(){var a=Tb();if(C("Windows")){var b=/Windows (?:NT|Phone) ([0-9.]+)/;b.exec(a)}else Gc()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):-1!=Tb().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b.exec(a)):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b.exec(a)):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b.exec(a))}
;function Ic(a){Ic[" "](a);return a}
Ic[" "]=function(){};
function Jc(a){var b=Kc;return Object.prototype.hasOwnProperty.call(b,9)?b[9]:b[9]=a(9)}
;var Lc=C("Opera"),Mc=Ub(),Nc=C("Edge"),Oc=C("Gecko")&&!(-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Pc=-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"),Qc=C("Android");function Rc(){var a=y.document;return a?a.documentMode:void 0}
var Sc;a:{var Tc="",Uc=function(){var a=Tb();if(Oc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Nc)return/Edge\/([\d\.]+)/.exec(a);if(Mc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Pc)return/WebKit\/(\S+)/.exec(a);if(Lc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Uc&&(Tc=Uc?Uc[1]:"");if(Mc){var Vc=Rc();if(null!=Vc&&Vc>parseFloat(Tc)){Sc=String(Vc);break a}}Sc=Tc}var Wc=Sc,Kc={};
function Xc(){return Jc(function(){for(var a=0,b=Mb(String(Wc)).split("."),c=Mb("9").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Nb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Nb(0==f[2].length,0==g[2].length)||Nb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}return 0<=a})}
var Yc;if(y.document&&Mc){var Zc=Rc();Yc=Zc?Zc:parseInt(Wc,10)||void 0}else Yc=void 0;var $c=Yc;var ad=Gc()||C("iPod"),bd=C("iPad");$b();Xb();var cd=Wb()&&!(Gc()||C("iPad")||C("iPod"));var dd={},ed=null;
function fd(a,b){Sa(a);void 0===b&&(b=0);if(!ed){ed={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));dd[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===ed[h]&&(ed[h]=g)}}}b=dd[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],m=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|m>>4];m=b[(m&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+m+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var gd="undefined"!==typeof Uint8Array,hd={};var id;function jd(a){if(hd!==hd)throw Error("illegal external caller");this.ja=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
jd.prototype.isEmpty=function(){return null==this.ja};var kd="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function ld(a,b){Object.isFrozen(a)||(kd?a[kd]|=b:void 0!==a.ta?a.ta|=b:Object.defineProperties(a,{ta:{value:b,configurable:!0,writable:!0,enumerable:!1}}))}
function md(a){var b;kd?b=a[kd]:b=a.ta;return null==b?0:b}
function nd(a){return Array.isArray(a)?!!(md(a)&1):!1}
function od(a){ld(a,1);return a}
function pd(a){return Array.isArray(a)?!!(md(a)&2):!1}
function qd(a){if(!Array.isArray(a))throw Error("cannot mark non-array as immutable");ld(a,2)}
function wd(a,b){if(!Array.isArray(a))throw Error("cannot mark non-array as mutable");b?ld(a,8):Object.isFrozen(a)||(kd?a[kd]&=-9:void 0!==a.ta&&(a.ta&=-9))}
;function xd(a){return pd(a.I)}
function yd(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var zd,Ad=Object.freeze(od([]));function Bd(a){if(xd(a))throw Error("Cannot mutate an immutable Message");}
var Cd="undefined"!=typeof Symbol&&"undefined"!=typeof Symbol.hasInstance;function Dd(a){return{value:a,configurable:!1,writable:!1,enumerable:!1}}
;function Ed(a){return a.displayName||a.name||"unknown type name"}
function Fd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Ed(b)+" but got "+(a&&Ed(a.constructor)));return a}
function Gd(a,b,c){c=void 0===c?!1:c;if(Array.isArray(a))return new b(a);if(c)return new b}
;function Hd(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)){if(gd&&null!=a&&a instanceof Uint8Array)return fd(a);if(a instanceof jd){var b=a.ja;null!=b&&"string"!==typeof b&&(gd&&b instanceof Uint8Array?b=fd(b):(Ra(b),b=null));return null==b?"":a.ja=b}}}return a}
;function Id(a,b){b=void 0===b?Jd:b;return Kd(a,b)}
function Ld(a,b){if(null!=a){if(Array.isArray(a))a=Kd(a,b);else if(yd(a)){var c={},d;for(d in a)c[d]=Ld(a[d],b);a=c}else a=b(a);return a}}
function Kd(a,b){for(var c=a.slice(),d=0;d<c.length;d++)c[d]=Ld(c[d],b);nd(a)&&od(c);return c}
function Md(a){if(a&&"object"==typeof a&&a.toJSON)return a.toJSON();a=Hd(a);return Array.isArray(a)?Id(a,Md):a}
function Jd(a){return gd&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;function Nd(a){return a.j||(a.j=a.I[a.l+a.ra]={})}
function Od(a,b,c){return-1===b?null:b>=a.l?a.j?a.j[b]:void 0:(void 0===c?0:c)&&a.j&&(c=a.j[b],null!=c)?c:a.I[b+a.ra]}
function E(a,b,c,d,e){d=void 0===d?!1:d;(void 0===e?0:e)||Bd(a);b<a.l&&!d?a.I[b+a.ra]=c:Nd(a)[b]=c;return a}
function Pd(a,b,c,d){c=void 0===c?!0:c;var e=Od(a,b,d);Array.isArray(e)||(e=Ad);if(xd(a))c&&(qd(e),Object.freeze(e));else if(e===Ad||pd(e))e=od(e.slice()),E(a,b,e,d);return e}
function Qd(a,b,c){a=Od(a,b);return null==a?c:a}
function Rd(a,b,c){null==c?c=Ad:od(c);return E(a,b,c)}
function Sd(a,b,c,d){Bd(a);(c=Td(a,c))&&c!==b&&null!=d&&(a.i&&c in a.i&&(a.i[c]=void 0),E(a,c));return E(a,b,d)}
function Td(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Od(a,e)&&(0!==c&&E(a,c,void 0,!1,!0),c=e)}return c}
function Ud(a,b,c,d,e){e=void 0===e?!1:e;var f=e;if(-1===c)d=null;else{a.i||(a.i={});var g=a.i[c];if(g)d=g;else{var h=Od(a,c,f);b=Gd(h,b,d);void 0==b?d=g:(d&&b.I!==h&&E(a,c,b.I,f,!0),a.i[c]=b,xd(a)&&qd(b.I),d=b)}}if(null==d)return d;xd(d)&&!xd(a)&&(d=d.Bb(Ec),E(a,c,d.I,e),a.i[c]=d);return d}
function Vd(a,b,c,d,e){e=void 0===e?!0:e;a.i||(a.i={});var f=xd(a),g=a.i[c];d=Pd(a,c,!0,d);var h=f||pd(d);if(!g){g=[];f=f||h;for(var k=0;k<d.length;k++){var m=d[k];f=f||pd(m);m=Gd(m,b);void 0!==m&&(g.push(m),h&&qd(m.I))}a.i[c]=g;wd(d,!f)}b=h||e;e=pd(g);b&&!e&&(Object.isFrozen(g)&&(a.i[c]=g=g.slice()),qd(g),Object.freeze(g));!b&&e&&(a.i[c]=g=g.slice());return g}
function Wd(a,b,c,d){d=void 0===d?!1:d;var e=xd(a);b=Vd(a,b,c,d,e);a=Pd(a,c,d);if(!(c=e)&&(c=a)){if(!Array.isArray(a))throw Error("cannot check mutability state of non-array");c=!(md(a)&8)}if(c){for(c=0;c<b.length;c++)(d=b[c])&&xd(d)&&!e&&(b[c]=b[c].Bb(Ec),a[c]=b[c].I);wd(a,!0)}return b}
function G(a,b,c,d){Bd(a);a.i||(a.i={});b=null!=d?Fd(d,b).I:d;a.i[c]=d;return E(a,c,b)}
function Xd(a,b,c,d,e){Bd(a);a.i||(a.i={});b=null!=e?Fd(e,b).I:e;a.i[c]=e;Sd(a,c,d,b)}
function Yd(a,b,c,d){Bd(a);if(null!=d){var e=od([]);for(var f=!1,g=0;g<d.length;g++)e[g]=Fd(d[g],b).I,f=f||pd(e[g]);a.i||(a.i={});a.i[c]=d;wd(e,!f)}else a.i&&(a.i[c]=void 0),e=Ad;return E(a,c,e)}
function Zd(a,b,c,d){Bd(a);var e=Vd(a,c,b,void 0,!1);c=null!=d?Fd(d,c):new c;a=Pd(a,b);e.push(c);a.push(c.I);Fc(Ec);xd(c)&&wd(a,!1)}
;function $d(a,b,c){a||(a=ae);ae=null;var d=this.constructor.j;a||(a=d?[d]:[]);this.ra=(d?0:-1)-(this.constructor.i||0);this.i=void 0;this.I=a;a:{d=this.I.length;a=d-1;if(d&&(d=this.I[a],yd(d))){this.l=a-this.ra;this.j=d;break a}void 0!==b&&-1<b?(this.l=Math.max(b,a+1-this.ra),this.j=void 0):this.l=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)if(a=c[b],a<this.l)a+=this.ra,(d=this.I[a])?Array.isArray(d)&&od(d):this.I[a]=Ad;else{d=Nd(this);var e=d[a];e?Array.isArray(e)&&od(e):d[a]=Ad}}
$d.prototype.toJSON=function(){var a=this.I;return zd?a:Id(a,Md)};
function be(a){zd=!0;try{return JSON.stringify(a.toJSON(),ce)}finally{zd=!1}}
$d.prototype.clone=function(){var a=Id(this.I);ae=a;a=new this.constructor(a);ae=null;de(a,this);return a};
$d.prototype.isMutable=function(a){Fc(a);return!xd(this)};
$d.prototype.toString=function(){return this.I.toString()};
function ce(a,b){return Hd(b)}
function de(a,b){b.Ha&&(a.Ha=b.Ha.slice());var c=b.i;if(c){b=b.j;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=Wd(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)de(f[g],e[g])}else(f=Ud(a,e.constructor,g,void 0,f))&&de(f,e)}}}}
var ae;function ee(){$d.apply(this,arguments)}
t(ee,$d);ee.prototype.Bb=function(){return this};
if(Cd){var fe={};Object.defineProperties(ee,(fe[Symbol.hasInstance]=Dd(function(){throw Error("Cannot perform instanceof checks for MutableMessage");}),fe))};function ge(a){var b=this.i,c=this.j;return this.isRepeated?Wd(a,b,c,!0):Ud(a,b,c,void 0,!0)}
;function he(a,b,c,d,e,f){(a=a.i&&a.i[c])?Array.isArray(a)?(e=f.kb?od(a.slice()):a,Yd(b,0<e.length?e[0].constructor:void 0,c,e)):G(b,a.constructor,c,a):(gd&&d instanceof Uint8Array?e=d.length?new jd(new Uint8Array(d)):id||(id=new jd(null)):(Array.isArray(d)&&(e?qd(d):nd(d)&&f.kb&&(d=d.slice())),e=d),E(b,c,e))}
;function I(){ee.apply(this,arguments)}
t(I,ee);I.prototype.Bb=function(a){Fc(a);if(xd(this)){a={kb:!0};var b=xd(this);if(b&&!a.kb)throw Error("copyRepeatedFields must be true for frozen messages");var c=new this.constructor;this.Ha&&(c.Ha=this.Ha.slice());for(var d=this.I,e=0;e<d.length;e++){var f=d[e];if(e===d.length-1&&yd(f))for(h in f){var g=+h;Number.isNaN(g)?Nd(c)[h]=f[h]:he(this,c,g,f[h],b,a)}else he(this,c,e-this.ra,f,b,a)}var h=c}else h=this;return h};
if(Cd){var ie={};Object.defineProperties(I,(ie[Symbol.hasInstance]=Dd(Object[Symbol.hasInstance]),ie))};function je(a){this.Kb=a}
;function ke(a,b,c){this.j=a;this.m=b;this.i=c||[];this.xa=new Map}
l=ke.prototype;l.vc=function(a){var b=Ma.apply(1,arguments),c=this.nb(b);c?c.push(new je(a)):this.jc(a,b)};
l.jc=function(a){this.xa.set(this.Rb(Ma.apply(1,arguments)),[new je(a)])};
l.nb=function(){var a=this.Rb(Ma.apply(0,arguments));return this.xa.has(a)?this.xa.get(a):void 0};
l.Ic=function(){var a=this.nb(Ma.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.xa.clear()};
l.Rb=function(){var a=Ma.apply(0,arguments);return a?a.join(","):"key"};function le(a,b){ke.call(this,a,3,b)}
t(le,ke);le.prototype.l=function(a){var b=Ma.apply(1,arguments),c=0,d=this.Ic(b);d&&(c=d.Kb);this.jc(c+a,b)};function me(a,b){ke.call(this,a,2,b)}
t(me,ke);me.prototype.l=function(a){this.vc(a,Ma.apply(1,arguments))};function ne(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function oe(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Sa(d)?oe.apply(null,d):ne(d)}}
;function J(){this.N=this.N;this.B=this.B}
J.prototype.N=!1;J.prototype.i=function(){return this.N};
J.prototype.dispose=function(){this.N||(this.N=!0,this.C())};
function pe(a,b){qe(a,$a(ne,b))}
function qe(a,b){a.N?b():(a.B||(a.B=[]),a.B.push(b))}
J.prototype.C=function(){if(this.B)for(;this.B.length;)this.B.shift()()};function re(a,b){this.type=a;this.i=this.target=b;this.defaultPrevented=this.l=!1}
re.prototype.stopPropagation=function(){this.l=!0};
re.prototype.preventDefault=function(){this.defaultPrevented=!0};function se(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=te(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,ue[c])c=ue[c];else{c=String(c);if(!ue[c]){var f=/function\s+([^\(]+)/m.exec(c);ue[c]=f?f[1]:"[Anonymous]"}c=ue[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function te(a,b){b||(b={});b[ve(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[ve(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=te(a,b));return c}
function ve(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var ue={};var we=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",function(){},b),y.removeEventListener("test",function(){},b)}catch(c){}return a}();function Ae(a,b){re.call(this,a?a.type:"");this.relatedTarget=this.i=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.j=null;a&&this.init(a,b)}
ab(Ae,re);var Be={2:"touch",3:"pen",4:"mouse"};
Ae.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.i=b;if(b=a.relatedTarget){if(Oc){a:{try{Ic(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Be[a.pointerType]||"";this.state=a.state;
this.j=a;a.defaultPrevented&&Ae.Y.preventDefault.call(this)};
Ae.prototype.stopPropagation=function(){Ae.Y.stopPropagation.call(this);this.j.stopPropagation?this.j.stopPropagation():this.j.cancelBubble=!0};
Ae.prototype.preventDefault=function(){Ae.Y.preventDefault.call(this);var a=this.j;a.preventDefault?a.preventDefault():a.returnValue=!1};var Ce="closure_listenable_"+(1E6*Math.random()|0);var De=0;function Ee(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Ya=e;this.key=++De;this.Ja=this.Ta=!1}
function Fe(a){a.Ja=!0;a.listener=null;a.proxy=null;a.src=null;a.Ya=null}
;function Ge(a){this.src=a;this.listeners={};this.i=0}
Ge.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.i++);var g=He(a,b,d,e);-1<g?(b=a[g],c||(b.Ta=!1)):(b=new Ee(b,this.src,f,!!d,e),b.Ta=c,a.push(b));return b};
Ge.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=He(e,b,c,d);return-1<b?(Fe(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.i--),!0):!1};
function Ie(a,b){var c=b.type;c in a.listeners&&mb(a.listeners[c],b)&&(Fe(b),0==a.listeners[c].length&&(delete a.listeners[c],a.i--))}
function He(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Ja&&f.listener==b&&f.capture==!!c&&f.Ya==d)return e}return-1}
;var Je="closure_lm_"+(1E6*Math.random()|0),Ke={},Le=0;function Me(a,b,c,d,e){if(d&&d.once)Ne(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Me(a,b[f],c,d,e);else c=Oe(c),a&&a[Ce]?a.aa(b,c,Ta(d)?!!d.capture:!!d,e):Pe(a,b,c,!1,d,e)}
function Pe(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ta(e)?!!e.capture:!!e,h=Qe(a);h||(a[Je]=h=new Ge(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Re();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)we||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Se(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Le++}}
function Re(){function a(c){return b.call(a.src,a.listener,c)}
var b=Te;return a}
function Ne(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ne(a,b[f],c,d,e);else c=Oe(c),a&&a[Ce]?a.m.add(String(b),c,!0,Ta(d)?!!d.capture:!!d,e):Pe(a,b,c,!0,d,e)}
function Ue(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ue(a,b[f],c,d,e);else(d=Ta(d)?!!d.capture:!!d,c=Oe(c),a&&a[Ce])?a.m.remove(String(b),c,d,e):a&&(a=Qe(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=He(b,c,d,e)),(c=-1<a?b[a]:null)&&Ve(c))}
function Ve(a){if("number"!==typeof a&&a&&!a.Ja){var b=a.src;if(b&&b[Ce])Ie(b.m,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Se(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Le--;(c=Qe(b))?(Ie(c,a),0==c.i&&(c.src=null,b[Je]=null)):Fe(a)}}}
function Se(a){return a in Ke?Ke[a]:Ke[a]="on"+a}
function Te(a,b){if(a.Ja)a=!0;else{b=new Ae(b,this);var c=a.listener,d=a.Ya||a.src;a.Ta&&Ve(a);a=c.call(d,b)}return a}
function Qe(a){a=a[Je];return a instanceof Ge?a:null}
var We="__closure_events_fn_"+(1E9*Math.random()>>>0);function Oe(a){if("function"===typeof a)return a;a[We]||(a[We]=function(b){return a.handleEvent(b)});
return a[We]}
;function K(){J.call(this);this.m=new Ge(this);this.sc=this;this.ka=null}
ab(K,J);K.prototype[Ce]=!0;K.prototype.addEventListener=function(a,b,c,d){Me(this,a,b,c,d)};
K.prototype.removeEventListener=function(a,b,c,d){Ue(this,a,b,c,d)};
function Xe(a,b){var c=a.ka;if(c){var d=[];for(var e=1;c;c=c.ka)d.push(c),++e}a=a.sc;c=b.type||b;"string"===typeof b?b=new re(b,a):b instanceof re?b.target=b.target||a:(e=b,b=new re(c,a),yb(b,e));e=!0;if(d)for(var f=d.length-1;!b.l&&0<=f;f--){var g=b.i=d[f];e=Ye(g,c,!0,b)&&e}b.l||(g=b.i=a,e=Ye(g,c,!0,b)&&e,b.l||(e=Ye(g,c,!1,b)&&e));if(d)for(f=0;!b.l&&f<d.length;f++)g=b.i=d[f],e=Ye(g,c,!1,b)&&e}
K.prototype.C=function(){K.Y.C.call(this);if(this.m){var a=this.m,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Fe(d[e]);delete a.listeners[c];a.i--}}this.ka=null};
K.prototype.aa=function(a,b,c,d){return this.m.add(String(a),b,!1,c,d)};
function Ye(a,b,c,d){b=a.m.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Ja&&g.capture==c){var h=g.listener,k=g.Ya||g.src;g.Ta&&Ie(a.m,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Ze(a,b){this.l=a;this.m=b;this.j=0;this.i=null}
Ze.prototype.get=function(){if(0<this.j){this.j--;var a=this.i;this.i=a.next;a.next=null}else a=this.l();return a};
function $e(a,b){a.m(b);100>a.j&&(a.j++,b.next=a.i,a.i=b)}
;function af(a,b){return a+Math.random()*(b-a)}
;function bf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=bf.prototype;l.clone=function(){return new bf(this.x,this.y)};
l.equals=function(a){return a instanceof bf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function cf(a,b){this.width=a;this.height=b}
l=cf.prototype;l.clone=function(){return new cf(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.isEmpty=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function df(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function ef(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function ff(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var gf;function hf(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=ef("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Za(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Jb;c.Jb=null;e()}};
return function(e){d.next={Jb:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function jf(a){y.setTimeout(function(){throw a;},0)}
;function kf(){this.j=this.i=null}
kf.prototype.add=function(a,b){var c=lf.get();c.set(a,b);this.j?this.j.next=c:this.i=c;this.j=c};
kf.prototype.remove=function(){var a=null;this.i&&(a=this.i,this.i=this.i.next,this.i||(this.j=null),a.next=null);return a};
var lf=new Ze(function(){return new mf},function(a){return a.reset()});
function mf(){this.next=this.scope=this.i=null}
mf.prototype.set=function(a,b){this.i=a;this.scope=b;this.next=null};
mf.prototype.reset=function(){this.next=this.scope=this.i=null};var nf,of=!1,pf=new kf;function qf(a,b){nf||rf();of||(nf(),of=!0);pf.add(a,b)}
function rf(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);nf=function(){a.then(sf)}}else nf=function(){var b=sf;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!C("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(gf||(gf=hf()),gf(b)):y.setImmediate(b)}}
function sf(){for(var a;a=pf.remove();){try{a.i.call(a.scope)}catch(b){jf(b)}$e(lf,a)}of=!1}
;function tf(a){this.i=0;this.B=void 0;this.m=this.j=this.l=null;this.o=this.s=!1;if(a!=eb)try{var b=this;a.call(void 0,function(c){uf(b,2,c)},function(c){uf(b,3,c)})}catch(c){uf(this,3,c)}}
function vf(){this.next=this.context=this.onRejected=this.j=this.i=null;this.l=!1}
vf.prototype.reset=function(){this.context=this.onRejected=this.j=this.i=null;this.l=!1};
var wf=new Ze(function(){return new vf},function(a){a.reset()});
function xf(a,b,c){var d=wf.get();d.j=a;d.onRejected=b;d.context=c;return d}
function yf(a){return new tf(function(b,c){c(a)})}
tf.prototype.then=function(a,b,c){return zf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
tf.prototype.$goog_Thenable=!0;l=tf.prototype;l.gb=function(a,b){return zf(this,null,a,b)};
l.catch=tf.prototype.gb;l.cancel=function(a){if(0==this.i){var b=new Af(a);qf(function(){Bf(this,b)},this)}};
function Bf(a,b){if(0==a.i)if(a.l){var c=a.l;if(c.j){for(var d=0,e=null,f=null,g=c.j;g&&(g.l||(d++,g.i==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.i&&1==d?Bf(c,b):(f?(d=f,d.next==c.m&&(c.m=d),d.next=d.next.next):Cf(c),Df(c,e,3,b)))}a.l=null}else uf(a,3,b)}
function Ef(a,b){a.j||2!=a.i&&3!=a.i||Ff(a);a.m?a.m.next=b:a.j=b;a.m=b}
function zf(a,b,c,d){var e=xf(null,null,null);e.i=new tf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Af?g(h):f(k)}catch(m){g(m)}}:g});
e.i.l=a;Ef(a,e);return e.i}
l.qd=function(a){this.i=0;uf(this,2,a)};
l.rd=function(a){this.i=0;uf(this,3,a)};
function uf(a,b,c){if(0==a.i){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.i=1;a:{var d=c,e=a.qd,f=a.rd;if(d instanceof tf){Ef(d,xf(e||eb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ta(d))try{var k=d.then;if("function"===typeof k){Gf(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.B=c,a.i=b,a.l=null,Ff(a),3!=b||c instanceof Af||Hf(a,c))}}
function Gf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Ff(a){a.s||(a.s=!0,qf(a.Gc,a))}
function Cf(a){var b=null;a.j&&(b=a.j,a.j=b.next,b.next=null);a.j||(a.m=null);return b}
l.Gc=function(){for(var a;a=Cf(this);)Df(this,a,this.i,this.B);this.s=!1};
function Df(a,b,c,d){if(3==c&&b.onRejected&&!b.l)for(;a&&a.o;a=a.l)a.o=!1;if(b.i)b.i.l=null,If(b,c,d);else try{b.l?b.j.call(b.context):If(b,c,d)}catch(e){Jf.call(null,e)}$e(wf,b)}
function If(a,b,c){2==b?a.j.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Hf(a,b){a.o=!0;qf(function(){a.o&&Jf.call(null,b)})}
var Jf=jf;function Af(a){cb.call(this,a)}
ab(Af,cb);Af.prototype.name="cancel";function Kf(a,b){K.call(this);this.l=a||1;this.j=b||y;this.o=Za(this.od,this);this.s=Date.now()}
ab(Kf,K);l=Kf.prototype;l.enabled=!1;l.ca=null;function Lf(a,b){a.l=b;a.ca&&a.enabled?(a.stop(),a.start()):a.ca&&a.stop()}
l.od=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.l?this.ca=this.j.setTimeout(this.o,this.l-a):(this.ca&&(this.j.clearTimeout(this.ca),this.ca=null),Xe(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.ca||(this.ca=this.j.setTimeout(this.o,this.l),this.s=Date.now())};
l.stop=function(){this.enabled=!1;this.ca&&(this.j.clearTimeout(this.ca),this.ca=null)};
l.C=function(){Kf.Y.C.call(this);this.stop();delete this.j};
function Mf(a,b,c){if("function"===typeof a)c&&(a=Za(a,c));else if(a&&"function"==typeof a.handleEvent)a=Za(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:y.setTimeout(a,b||0)}
;function Nf(a){this.B=a;this.i=new Map;this.s=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.j=new Kf(this.flushInterval);this.j.aa("tick",this.ib,!1,this);this.o=!1}
l=Nf.prototype;l.hc=function(a){this.o=a;this.m=1};
function Of(a){a.j.enabled||a.j.start();a.l++;a.l>=a.m&&a.ib()}
l.ib=function(){var a=this.i.values();a=[].concat(ia(a)).filter(function(b){return b.xa.size});
a.length&&this.B.flush(a,this.o);Pf(a);this.l=0;this.j.enabled&&this.j.stop()};
l.wc=function(a){var b=Ma.apply(1,arguments);this.i.has(a)||this.i.set(a,new le(a,b))};
l.Hb=function(a){var b=Ma.apply(1,arguments);this.i.has(a)||this.i.set(a,new me(a,b))};
function Qf(a,b){return a.s.has(b)?void 0:a.i.get(b)}
l.Cb=function(a){this.pc.apply(this,[a,1].concat(ia(Ma.apply(1,arguments))))};
l.pc=function(a,b){var c=Ma.apply(2,arguments),d=Qf(this,a);d&&d instanceof le&&(d.l(b,c),Of(this))};
l.hb=function(a,b){var c=Ma.apply(2,arguments),d=Qf(this,a);d&&d instanceof me&&(d.l(b,c),Of(this))};
function Pf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Rf(a){this.i=a;this.i.Hb("/client_streamz/bg/fil",{mb:3,lb:"rk"})}
function Sf(a){this.i=a;this.i.wc("/client_streamz/bg/fsc",{mb:3,lb:"rk"})}
function Tf(a){this.i=a;this.i.Hb("/client_streamz/bg/fsl",{mb:3,lb:"rk"})}
;function Uf(a){I.call(this,a,-1,Vf)}
t(Uf,I);function Wf(a){I.call(this,a,-1,Xf)}
t(Wf,I);function Yf(a){I.call(this,a)}
t(Yf,I);function Zf(a){I.call(this,a)}
t(Zf,I);var Vf=[3,6,4],Xf=[1],$f=[1,2,3],ag=[1,2,3];function bg(a){I.call(this,a,-1,cg)}
t(bg,I);var cg=[1];function dg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function eg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;q=m=0}
function b(r){for(var x=g,u=0;64>u;u+=4)x[u/4]=r[u]<<24|r[u+1]<<16|r[u+2]<<8|r[u+3];for(u=16;80>u;u++)r=x[u-3]^x[u-8]^x[u-14]^x[u-16],x[u]=(r<<1|r>>>31)&4294967295;r=e[0];var A=e[1],D=e[2],F=e[3],N=e[4];for(u=0;80>u;u++){if(40>u)if(20>u){var O=F^A&(D^F);var Q=1518500249}else O=A^D^F,Q=1859775393;else 60>u?(O=A&D|F&(A|D),Q=2400959708):(O=A^D^F,Q=3395469782);O=((r<<5|r>>>27)&4294967295)+O+N+Q+x[u]&4294967295;N=F;F=D;D=(A<<30|A>>>2)&4294967295;A=r;r=O}e[0]=e[0]+r&4294967295;e[1]=e[1]+A&4294967295;e[2]=
e[2]+D&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+N&4294967295}
function c(r,x){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var u=[],A=0,D=r.length;A<D;++A)u.push(r.charCodeAt(A));r=u}x||(x=r.length);u=0;if(0==m)for(;u+64<x;)b(r.slice(u,u+64)),u+=64,q+=64;for(;u<x;)if(f[m++]=r[u++],q++,64==m)for(m=0,b(f);u+64<x;)b(r.slice(u,u+64)),u+=64,q+=64}
function d(){var r=[],x=8*q;56>m?c(h,56-m):c(h,64-(m-56));for(var u=63;56<=u;u--)f[u]=x&255,x>>>=8;b(f);for(u=x=0;5>u;u++)for(var A=24;0<=A;A-=8)r[x++]=e[u]>>A&255;return r}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,q;a();return{reset:a,update:c,digest:d,Cc:function(){for(var r=d(),x="",u=0;u<r.length;u++)x+="0123456789ABCDEF".charAt(Math.floor(r[u]/16))+"0123456789ABCDEF".charAt(r[u]%16);return x}}}
;function fg(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,gg(dg(d),a,c||null)].join(" "):null}
function gg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],hb(d,function(h){e.push(h)}),hg(e.join(" "));
var f=[],g=[];hb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];hb(d,function(h){e.push(h)});
a=hg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function hg(a){var b=eg();b.update(a);return b.Cc().toLowerCase()}
;var ig={};function jg(a){this.i=a||{cookie:""}}
l=jg.prototype;l.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{ab:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.wq;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ab}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.i.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.i.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Mb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ab:0,path:b,domain:c});return d};
l.qb=function(){return kg(this).keys};
l.isEmpty=function(){return!this.i.cookie};
l.clear=function(){for(var a=kg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function kg(a){a=(a.i.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Mb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var lg=new jg("undefined"==typeof document?null:document);function mg(a){return!!ig.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function ng(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;mg(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new jg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");mg(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function og(a,b,c,d){(a=y[a])||(a=(new jg(document)).get(b));return a?fg(a,c,d):null}
function pg(a,b){b=void 0===b?!1:b;var c=dg(String(y.location.href)),d=[];if(ng(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new jg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?fg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&mg(b)&&((b=og("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=og("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function qg(a){I.call(this,a,-1,rg)}
t(qg,I);var rg=[2];function sg(a){this.i=this.j=this.l=a}
sg.prototype.reset=function(){this.i=this.j=this.l};
sg.prototype.getValue=function(){return this.j};function tg(a){var b=[];ug(new vg,a,b);return b.join("")}
function vg(){}
function ug(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),ug(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),wg(d,c),c.push(":"),ug(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":wg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var xg={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},yg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function wg(a,b){b.push('"',a.replace(yg,function(c){var d=xg[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),xg[c]=d);return d}),'"')}
;function zg(){}
zg.prototype.i=null;zg.prototype.getOptions=function(){var a;(a=this.i)||(a={},Ag(this)&&(a[0]=!0,a[1]=!0),a=this.i=a);return a};var Bg;function Cg(){}
ab(Cg,zg);function Dg(a){return(a=Ag(a))?new ActiveXObject(a):new XMLHttpRequest}
function Ag(a){if(!a.j&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.j=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.j}
Bg=new Cg;function Eg(a){K.call(this);this.headers=new Map;this.K=a||null;this.j=!1;this.J=this.A=null;this.o=this.T="";this.l=this.R=this.v=this.P=!1;this.s=0;this.F=null;this.da="";this.W=this.X=!1}
ab(Eg,K);var Fg=/^https?$/i,Gg=["POST","PUT"],Hg=[];function Kg(a,b,c,d,e,f,g){var h=new Eg;Hg.push(h);b&&h.aa("complete",b);h.m.add("ready",h.Ac,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.X=g);h.send(a,c,d,e)}
l=Eg.prototype;l.Ac=function(){this.dispose();mb(Hg,this)};
l.send=function(a,b,c,d){if(this.A)throw Error("[goog.net.XhrIo] Object is active with another request="+this.T+"; newUri="+a);b=b?b.toUpperCase():"GET";this.T=a;this.o="";this.P=!1;this.j=!0;this.A=this.K?Dg(this.K):Dg(Bg);this.J=this.K?this.K.getOptions():Bg.getOptions();this.A.onreadystatechange=Za(this.Yb,this);try{this.getStatus(),this.R=!0,this.A.open(b,String(a),!0),this.R=!1}catch(g){this.getStatus();Lg(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=p(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=y.FormData&&a instanceof y.FormData;!(0<=gb(Gg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=p(c);for(d=b.next();!d.done;d=b.next())c=p(d.value),d=c.next().value,c=c.next().value,this.A.setRequestHeader(d,c);this.da&&(this.A.responseType=this.da);"withCredentials"in this.A&&this.A.withCredentials!==this.X&&(this.A.withCredentials=this.X);try{Mg(this),0<this.s&&(this.W=Ng(this.A),this.getStatus(),this.W?(this.A.timeout=this.s,this.A.ontimeout=Za(this.lc,this)):
this.F=Mf(this.lc,this.s,this)),this.getStatus(),this.v=!0,this.A.send(a),this.v=!1}catch(g){this.getStatus(),Lg(this,g)}};
function Ng(a){return Mc&&Xc()&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.lc=function(){"undefined"!=typeof Pa&&this.A&&(this.o="Timed out after "+this.s+"ms, aborting",this.getStatus(),Xe(this,"timeout"),this.abort(8))};
function Lg(a,b){a.j=!1;a.A&&(a.l=!0,a.A.abort(),a.l=!1);a.o=b;Og(a);Pg(a)}
function Og(a){a.P||(a.P=!0,Xe(a,"complete"),Xe(a,"error"))}
l.abort=function(){this.A&&this.j&&(this.getStatus(),this.j=!1,this.l=!0,this.A.abort(),this.l=!1,Xe(this,"complete"),Xe(this,"abort"),Pg(this))};
l.C=function(){this.A&&(this.j&&(this.j=!1,this.l=!0,this.A.abort(),this.l=!1),Pg(this,!0));Eg.Y.C.call(this)};
l.Yb=function(){this.i()||(this.R||this.v||this.l?Qg(this):this.Rc())};
l.Rc=function(){Qg(this)};
function Qg(a){if(a.j&&"undefined"!=typeof Pa)if(a.J[1]&&4==Rg(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==Rg(a))Mf(a.Yb,0,a);else if(Xe(a,"readystatechange"),a.isComplete()){a.getStatus();a.j=!1;try{if(Sg(a))Xe(a,"complete"),Xe(a,"success");else{try{var b=2<Rg(a)?a.A.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Og(a)}}finally{Pg(a)}}}
function Pg(a,b){if(a.A){Mg(a);var c=a.A,d=a.J[0]?function(){}:null;
a.A=null;a.J=null;b||Xe(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Mg(a){a.A&&a.W&&(a.A.ontimeout=null);a.F&&(y.clearTimeout(a.F),a.F=null)}
l.isActive=function(){return!!this.A};
l.isComplete=function(){return 4==Rg(this)};
function Sg(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=nc(1,String(a.T)),!a&&y.self&&y.self.location&&(a=y.self.location.protocol.slice(0,-1)),b=!Fg.test(a?a.toLowerCase():"");c=b}return c}
function Rg(a){return a.A?a.A.readyState:0}
l.getStatus=function(){try{return 2<Rg(this)?this.A.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.o?this.o:String(this.o)};function Tg(a){I.call(this,a)}
t(Tg,I);function Ug(a){I.call(this,a,-1,Vg)}
t(Ug,I);var Vg=[1];var Wg=["platform","platformVersion","architecture","model","uaFullVersion"];new Ug;function Xg(a){I.call(this,a)}
t(Xg,I);function Yg(a){I.call(this,a,31,Zg)}
t(Yg,I);var Zg=[3,20,27];function $g(a){I.call(this,a,17,ah)}
t($g,I);var ah=[3,5];function bh(a){I.call(this,a,6,ch)}
t(bh,I);var ch=[5];function dh(a){I.call(this,a)}
t(dh,I);var eh;eh=new function(a,b,c){this.j=a;this.fieldName=b;this.i=c;this.isRepeated=0;this.l=ge}(175237375,{mq:0},dh);function fh(a,b,c,d,e,f,g,h,k,m,q){K.call(this);var r=this;this.P="";this.l=[];this.Fb="";this.Gb=this.qa=-1;this.Qa=!1;this.J=this.o=null;this.F=0;this.tc=1;this.timeoutMillis=0;this.da=!1;K.call(this);this.Eb=b||function(){};
this.v=new gh(a,f);this.qc=d;this.Pa=q;this.uc=$a(af,0,1);this.T=e||null;this.K=c||null;this.W=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Ea=f||!1;!this.Ea&&(65<=cc("Chromium")||45<=cc("Firefox")||12<=cc("Safari")||(Gc()||C("iPad")||C("iPod"))&&Hc());a=E(new Xg,1,1);hh(this.v,a);this.s=new sg(1E4);this.j=new Kf(this.s.getValue());pe(this,this.j);m=ih(this,m);Me(this.j,"tick",m,!1,this);this.R=new Kf(6E5);pe(this,this.R);Me(this.R,"tick",m,!1,this);this.W||this.R.start();
this.Ea||(Me(document,"visibilitychange",function(){"hidden"===document.visibilityState&&r.X()}),Me(document,"pagehide",this.X,!1,this))}
t(fh,K);function ih(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
fh.prototype.C=function(){this.X();K.prototype.C.call(this)};
function jh(a){a.T||(a.T=.01>a.uc()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.T}
function kh(a,b){a.s=new sg(1>b?1:b);Lf(a.j,a.s.getValue())}
fh.prototype.log=function(a){a=a.clone();var b=this.tc++;E(a,21,b);this.P&&E(a,26,this.P);if(!Od(a,1)){b=a;var c=Date.now().toString();E(b,1,c)}null!=Od(a,15)||E(a,15,60*(new Date).getTimezoneOffset());this.o&&(b=this.o.clone(),G(a,qg,16,b));for(;1E3<=this.l.length;)this.l.shift(),++this.F;this.l.push(a);Xe(this,new lh(a));this.W||this.j.enabled||this.j.start()};
fh.prototype.flush=function(a,b){var c=this;if(0===this.l.length)a&&a();else if(this.da)mh(this);else{var d=Date.now();if(this.Gb>d&&this.qa<d)b&&b("throttled");else{var e=nh(this.v,this.l,this.F);d={};var f=this.Eb();f&&(d.Authorization=f);var g=jh(this);this.K&&(d["X-Goog-AuthUser"]=this.K,g=zc(g,"authuser",this.K));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=zc(g,"pageId",this.pageId));if(f&&this.Fb===f)b&&b("stale-auth-token");else{this.l=[];this.j.enabled&&this.j.stop();this.F=0;var h=be(e),
k;this.J&&this.J.isSupported(h.length)&&(k=this.J.compress(h));var m={url:g,body:h,yc:1,yb:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},q=function(u){c.s.reset();Lf(c.j,c.s.getValue());if(u){var A=null;try{var D=JSON.parse(u.replace(")]}'\n",""));A=new bh(D)}catch(F){}A&&(u=Number(Qd(A,1,"-1")),0<u&&(c.qa=Date.now(),c.Gb=c.qa+u),A=eh.l(A))&&(A=Qd(A,1,-1),-1!=A&&(c.Qa||kh(c,A)))}a&&a()},r=function(u,A){var D=Wd(e,Yg,3),F=c.s;
F.i=Math.min(3E5,2*F.i);F.j=Math.min(3E5,F.i+Math.round(.2*(Math.random()-.5)*F.i));Lf(c.j,c.s.getValue());401===u&&f&&(c.Fb=f);void 0===A&&(A=500<=u&&600>u||401===u||0===u);A&&(c.l=D.concat(c.l),c.W||c.j.enabled||c.j.start());b&&b("net-send-failed",u)},x=function(){c.Pa?c.Pa.send(m,q,r):c.qc(m,q,r)};
k?k.then(function(u){m.yb["Content-Encoding"]="gzip";m.yb["Content-Type"]="application/binary";m.body=u;m.yc=2;x()},function(){x()}):x()}}}};
fh.prototype.X=function(){this.flush()};
function mh(a){oh(a,function(b,c){b=zc(b,"format","json");b=window.navigator.sendBeacon(b,be(c));a.da&&!b&&(a.da=!1);return b})}
function oh(a,b){if(0!==a.l.length){var c=Dc(jh(a),"format");c=uc(c,"auth",a.Eb(),"authuser",a.K||"0");for(var d=0;10>d&&a.l.length;++d){var e=a.l.slice(0,32),f=nh(a.v,e,a.F);if(!b(c,f))break;a.F=0;a.l=a.l.slice(e.length)}a.j.enabled&&a.j.stop()}}
function lh(){re.call(this,"event-logged",void 0)}
t(lh,re);function gh(a,b){this.j=b=void 0===b?!1:b;this.uach=this.locale=null;this.i=new $g;E(this.i,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));hh(this,new Xg)}
function hh(a,b){G(a.i,Xg,1,b);Od(b,1)||E(b,1,1);a.j||(b=ph(a),Od(b,5)||E(b,5,a.locale));a.uach&&(b=ph(a),Ud(b,Ug,9)||G(b,Ug,9,a.uach))}
function qh(a,b){var c=void 0===c?Wg:c;b(window,c).then(function(d){a.uach=d;d=ph(a);G(d,Ug,9,a.uach);return!0}).catch(function(){return!1})}
function ph(a){a=Ud(a.i,Xg,1);var b=Ud(a,Tg,11);b||(b=new Tg,G(a,Tg,11,b));return b}
function nh(a,b,c){c=void 0===c?0:c;a=a.i.clone();var d=Date.now().toString();a=E(a,4,d);b=Yd(a,Yg,3,b);c&&E(b,14,c);return b}
;function rh(a,b,c){Kg(a.url,function(d){d=d.target;if(Sg(d)){try{var e=d.A?d.A.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.yb,a.timeoutMillis,a.withCredentials)}
;function sh(){this.l="https://play.google.com/log?format=json&hasfast=true";this.m=!1;this.s=rh;this.i=""}
;function th(){var a=void 0===a?"":a;var b=void 0===b?!1:b;var c=void 0===c?"":c;var d=new sh;d.i="";""!=a&&(d.l=a);b&&(d.m=!0);c&&(d.j=c);a=new fh(1828,d.J?d.J:pg,"0",d.s,d.l,d.m,!1,d.R,void 0,void 0,d.B?d.B:void 0);d.v&&hh(a.v,d.v);d.j&&(b=d.j,c=ph(a.v),E(c,7,b));d.o&&(a.J=d.o);d.i&&(a.P=d.i);d.N&&((b=d.N)?(a.o||(a.o=new qg),b=be(b),E(a.o,4,b)):a.o&&E(a.o,4,void 0,!1));d.K&&(b=d.K,a.o||(a.o=new qg),Rd(a.o,2,b));d.F&&(b=d.F,a.Qa=!0,kh(a,b));d.P&&qh(a.v,d.P);this.i=a}
th.prototype.flush=function(a){var b=a||[];if(b.length){a=new bg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e;var g=new Uf;g=E(g,1,f.j);for(var h=f,k=[],m=0;m<h.i.length;m++)k.push(h.i[m].lb);g=Rd(g,3,k);h=[];k=[];m=p(f.xa.keys());for(var q=m.next();!q.done;q=m.next())k.push(q.value.split(","));for(m=0;m<k.length;m++){q=k[m];var r=f.m;for(var x=f.nb(q)||[],u=[],A=0;A<x.length;A++){var D=x[A];D=D&&D.Kb;var F=new Zf;switch(r){case 3:Sd(F,1,ag,Number(D));break;case 2:Sd(F,2,ag,Number(D))}u.push(F)}r=
u;for(x=0;x<r.length;x++){u=r[x];A=new Wf;u=G(A,Zf,2,u);A=q;D=[];F=f;for(var N=[],O=0;O<F.i.length;O++)N.push(F.i[O].mb);F=N;for(N=0;N<F.length;N++){O=F[N];var Q=A[N],ca=new Yf;switch(O){case 3:Sd(ca,1,$f,String(Q));break;case 2:Sd(ca,2,$f,Number(Q));break;case 1:Sd(ca,3,$f,"true"==Q)}D.push(ca)}Yd(u,Yf,1,D);h.push(u)}}Yd(g,Wf,4,h);c.push(g);e.clear()}Yd(a,Uf,1,c);b=this.i;a instanceof Yg?b.log(a):(c=new Yg,a=be(a),a=E(c,8,a),b.log(a));this.i.flush()}};function uh(){this.o=vh();this.transport=new th;this.i=new Nf(this.transport);this.m=new Rf(this.i);this.j=new Sf(this.i);this.l=new Tf(this.i);this.Aa=window.document.location.hostname}
function vh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function wh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function xh(a){var b=this;this.Wa=!1;if(a.tq){var c;this.sa=null!=(c=a.sa)?c:new uh}c=a.program;a=a.globalName;var d=new wh;this.j=d.promise;this.md=p((0,y[a].a)(c,function(e,f){Promise.resolve().then(function(){var g;if(null!=(g=b.sa)){var h=vh()-g.o;g.m.i.hb("/client_streamz/bg/fil",h,g.Aa)}d.resolve({xc:e,jd:f})})},!0)).next().value;
this.hd=d.promise.then(function(){})}
xh.prototype.snapshot=function(a){var b=this;if(this.Wa)throw Error("Already disposed");var c=vh(),d;null!=(d=this.sa)&&d.j.i.Cb("/client_streamz/bg/fsc",d.Aa);return this.j.then(function(e){var f=e.xc;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.sa)){var m=vh()-c;k.l.i.hb("/client_streamz/bg/fsl",m,k.Aa)}g(h)},[a.Mb,
a.kd])})})};
xh.prototype.dispose=function(){var a;null!=(a=this.sa)&&a.i.ib();this.Wa=!0;this.j.then(function(b){(b=b.jd)&&b()})};
xh.prototype.i=function(){return this.Wa};var yh=window;Fb("csi.gstatic.com");Fb("googleads.g.doubleclick.net");Fb("partner.googleadservices.com");Fb("pubads.g.doubleclick.net");Fb("securepubads.g.doubleclick.net");Fb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
function zh(a,b){a.src=Kb(b);var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function Ah(a){var b=Bh;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Ch(){var a=[];Ah(function(b){a.push(b)});
return a}
var Bh={Ed:"allow-forms",Fd:"allow-modals",Gd:"allow-orientation-lock",Hd:"allow-pointer-lock",Id:"allow-popups",Jd:"allow-popups-to-escape-sandbox",Kd:"allow-presentation",Ld:"allow-same-origin",Md:"allow-scripts",Nd:"allow-top-navigation",Od:"allow-top-navigation-by-user-activation"},Dh=fb(function(){return Ch()});
function Eh(){var a=Fh(),b={};hb(Dh(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Fh(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Gh(a){this.isValid=a}
function Hh(a){return new Gh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Ih=[Hh("data"),Hh("http"),Hh("https"),Hh("mailto"),Hh("ftp"),new Gh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Jh(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Kh=(new Date).getTime();var Lh="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ia(Lh);function Mh(a){K.call(this);var b=this;this.v=this.l=0;this.Z=null!=a?a:{S:function(e,f){return setTimeout(e,f)},
fa:function(e){clearTimeout(e)}};
var c,d;this.j=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.o=function(){return w(function(e){return v(e,Nh(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.v||Oh(this)}
t(Mh,K);function Ph(){var a=Qh;Mh.i||(Mh.i=new Mh(a));return Mh.i}
Mh.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Z.fa(this.v);delete Mh.i};
Mh.prototype.L=function(){return this.j};
function Oh(a){a.v=a.Z.S(function(){var b;return w(function(c){if(1==c.i)return a.j?(null==(b=window.navigator)?0:b.onLine)?c.u(3):v(c,Nh(a),3):v(c,Nh(a),3);Oh(a);c.i=0})},3E4)}
function Nh(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return w(function(h){switch(h.i){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,Ba(h,2,3),d&&(a.l=a.Z.S(function(){d.abort()},b||2E4)),v(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ea(h);a.s=void 0;a.l&&(a.Z.fa(a.l),a.l=0);g!==a.j&&(a.j=g,a.j?Xe(a,"networkstatus-online"):Xe(a,"networkstatus-offline"));c(g);Fa(h);break;case 2:Da(h),g=!1,h.u(3)}})})}
;var Rh={Kh:"EMBEDDED_PLAYER_MODE_UNKNOWN",Hh:"EMBEDDED_PLAYER_MODE_DEFAULT",Jh:"EMBEDDED_PLAYER_MODE_PFP",Ih:"EMBEDDED_PLAYER_MODE_PFL"},Sh={Op:"WEB_DISPLAY_MODE_UNKNOWN",Kp:"WEB_DISPLAY_MODE_BROWSER",Mp:"WEB_DISPLAY_MODE_MINIMAL_UI",Np:"WEB_DISPLAY_MODE_STANDALONE",Lp:"WEB_DISPLAY_MODE_FULLSCREEN"};function Th(){this.data_=[];this.i=-1}
Th.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.i=-1)};
Th.prototype.get=function(a){return!!this.data_[a]};
function Uh(a){-1===a.i&&(a.i=kb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function Vh(a,b){this.i=a[y.Symbol.iterator]();this.j=b}
Vh.prototype[Symbol.iterator]=function(){return this};
Vh.prototype.next=function(){var a=this.i.next();return{value:a.done?void 0:this.j.call(void 0,a.value),done:a.done}};
function Wh(a,b){return new Vh(a,b)}
;function Xh(){this.blockSize=-1}
;function Yh(){this.blockSize=-1;this.blockSize=64;this.i=[];this.o=[];this.s=[];this.l=[];this.l[0]=128;for(var a=1;a<this.blockSize;++a)this.l[a]=0;this.m=this.j=0;this.reset()}
ab(Yh,Xh);Yh.prototype.reset=function(){this.i[0]=1732584193;this.i[1]=4023233417;this.i[2]=2562383102;this.i[3]=271733878;this.i[4]=3285377520;this.m=this.j=0};
function Zh(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.i[0];c=a.i[1];var g=a.i[2],h=a.i[3],k=a.i[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.i[0]=a.i[0]+b&4294967295;a.i[1]=a.i[1]+c&4294967295;a.i[2]=a.i[2]+g&4294967295;a.i[3]=a.i[3]+h&4294967295;a.i[4]=a.i[4]+k&4294967295}
Yh.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.j;d<b;){if(0==f)for(;d<=c;)Zh(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Zh(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Zh(this,e);f=0;break}}this.j=f;this.m+=b}};
Yh.prototype.digest=function(){var a=[],b=8*this.m;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.blockSize-(this.j-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;Zh(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.i[c]>>d&255,++b;return a};function $h(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function ai(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function bi(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:$h(a).match(/\S+/g)||[],b=0<=gb(a,b));return b}
function ci(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):bi(a,"inverted-hdpi")&&ai(a,Array.prototype.filter.call(a.classList?a.classList:$h(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function di(){}
di.prototype.next=function(){return ei};
var ei={done:!0,value:void 0};function fi(a){return{value:a,done:!1}}
di.prototype.ea=function(){return this};function gi(a){if(a instanceof hi||a instanceof ii||a instanceof ji)return a;if("function"==typeof a.next)return new hi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new hi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.ea)return new hi(function(){return a.ea()});
throw Error("Not an iterator or iterable.");}
function hi(a){this.j=a}
hi.prototype.ea=function(){return new ii(this.j())};
hi.prototype[Symbol.iterator]=function(){return new ji(this.j())};
hi.prototype.i=function(){return new ji(this.j())};
function ii(a){this.j=a}
t(ii,di);ii.prototype.next=function(){return this.j.next()};
ii.prototype[Symbol.iterator]=function(){return new ji(this.j)};
ii.prototype.i=function(){return new ji(this.j)};
function ji(a){hi.call(this,function(){return a});
this.l=a}
t(ji,hi);ji.prototype.next=function(){return this.l.next()};function ki(a,b){this.j={};this.i=[];this.na=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof ki)for(c=a.qb(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=ki.prototype;l.qb=function(){li(this);return this.i.concat()};
l.has=function(a){return mi(this.j,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||ni;li(this);for(var c,d=0;c=this.i[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function ni(a,b){return a===b}
l.isEmpty=function(){return 0==this.size};
l.clear=function(){this.j={};this.na=this.size=this.i.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return mi(this.j,a)?(delete this.j[a],--this.size,this.na++,this.i.length>2*this.size&&li(this),!0):!1};
function li(a){if(a.size!=a.i.length){for(var b=0,c=0;b<a.i.length;){var d=a.i[b];mi(a.j,d)&&(a.i[c++]=d);b++}a.i.length=c}if(a.size!=a.i.length){var e={};for(c=b=0;b<a.i.length;)d=a.i[b],mi(e,d)||(a.i[c++]=d,e[d]=1),b++;a.i.length=c}}
l.get=function(a,b){return mi(this.j,a)?this.j[a]:b};
l.set=function(a,b){mi(this.j,a)||(this.size+=1,this.i.push(a),this.na++);this.j[a]=b};
l.forEach=function(a,b){for(var c=this.qb(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new ki(this)};
l.keys=function(){return gi(this.ea(!0)).i()};
l.values=function(){return gi(this.ea(!1)).i()};
l.entries=function(){var a=this;return Wh(this.keys(),function(b){return[b,a.get(b)]})};
l.ea=function(a){li(this);var b=0,c=this.na,d=this,e=new di;e.next=function(){if(c!=d.na)throw Error("The map has changed since the iterator was created");if(b>=d.i.length)return ei;var f=d.i[b++];return fi(a?f:d.j[f])};
return e};
function mi(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function L(a){J.call(this);this.s=1;this.m=[];this.o=0;this.j=[];this.l={};this.v=!!a}
ab(L,J);l=L.prototype;l.subscribe=function(a,b,c){var d=this.l[a];d||(d=this.l[a]=[]);var e=this.s;this.j[e]=a;this.j[e+1]=b;this.j[e+2]=c;this.s=e+3;d.push(e);return e};
function oi(a,b,c,d){if(b=a.l[b]){var e=a.j;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Da(b)}}
l.Da=function(a){var b=this.j[a];if(b){var c=this.l[b];0!=this.o?(this.m.push(a),this.j[a+1]=function(){}):(c&&mb(c,a),delete this.j[a],delete this.j[a+1],delete this.j[a+2])}return!!b};
l.oa=function(a,b){var c=this.l[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];pi(this.j[g+1],this.j[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f&&!this.i();e++)g=c[e],this.j[g+1].apply(this.j[g+2],d)}finally{if(this.o--,0<this.m.length&&0==this.o)for(;c=this.m.pop();)this.Da(c)}}return 0!=e}return!1};
function pi(a,b,c){qf(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.l[a];b&&(b.forEach(this.Da,this),delete this.l[a])}else this.j.length=0,this.l={}};
l.C=function(){L.Y.C.call(this);this.clear();this.m.length=0};function qi(a){this.i=a}
qi.prototype.set=function(a,b){void 0===b?this.i.remove(a):this.i.set(a,tg(b))};
qi.prototype.get=function(a){try{var b=this.i.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
qi.prototype.remove=function(a){this.i.remove(a)};function ri(a){this.i=a}
ab(ri,qi);function si(a){this.data=a}
function ti(a){return void 0===a||a instanceof si?a:new si(a)}
ri.prototype.set=function(a,b){ri.Y.set.call(this,a,ti(b))};
ri.prototype.j=function(a){a=ri.Y.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
ri.prototype.get=function(a){if(a=this.j(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function ui(a){this.i=a}
ab(ui,ri);ui.prototype.set=function(a,b,c){if(b=ti(b)){if(c){if(c<Date.now()){ui.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}ui.Y.set.call(this,a,b)};
ui.prototype.j=function(a){var b=ui.Y.j.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())ui.prototype.remove.call(this,a);else return b}};function vi(){}
;function wi(){}
ab(wi,vi);wi.prototype[Symbol.iterator]=function(){return gi(this.ea(!0)).i()};
wi.prototype.clear=function(){var a=Array.from(this);a=p(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function xi(a){this.i=a}
ab(xi,wi);l=xi.prototype;l.isAvailable=function(){if(!this.i)return!1;try{return this.i.setItem("__sak","1"),this.i.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.i.setItem(a,b)}catch(c){if(0==this.i.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.i.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeItem(a)};
l.ea=function(a){var b=0,c=this.i,d=new di;d.next=function(){if(b>=c.length)return ei;var e=c.key(b++);if(a)return fi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return fi(e)};
return d};
l.clear=function(){this.i.clear()};
l.key=function(a){return this.i.key(a)};function yi(){var a=null;try{a=window.localStorage||null}catch(b){}this.i=a}
ab(yi,xi);function zi(a,b){this.j=a;this.i=null;var c;if(c=Mc)c=!(9<=Number($c));if(c){Ai||(Ai=new ki);this.i=Ai.get(a);this.i||(b?this.i=document.getElementById(b):(this.i=document.createElement("userdata"),this.i.addBehavior("#default#userData"),document.body.appendChild(this.i)),Ai.set(a,this.i));try{this.i.load(this.j)}catch(d){this.i=null}}}
ab(zi,wi);var Bi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Ai=null;function Ci(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Bi[b]})}
l=zi.prototype;l.isAvailable=function(){return!!this.i};
l.set=function(a,b){this.i.setAttribute(Ci(a),b);Di(this)};
l.get=function(a){a=this.i.getAttribute(Ci(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeAttribute(Ci(a));Di(this)};
l.ea=function(a){var b=0,c=this.i.XMLDocument.documentElement.attributes,d=new di;d.next=function(){if(b>=c.length)return ei;var e=c[b++];if(a)return fi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return fi(e)};
return d};
l.clear=function(){for(var a=this.i.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Di(this)};
function Di(a){try{a.i.save(a.j)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Ei(a,b){this.j=a;this.i=b+"::"}
ab(Ei,wi);Ei.prototype.set=function(a,b){this.j.set(this.i+a,b)};
Ei.prototype.get=function(a){return this.j.get(this.i+a)};
Ei.prototype.remove=function(a){this.j.remove(this.i+a)};
Ei.prototype.ea=function(a){var b=this.j[Symbol.iterator](),c=this,d=new di;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.i.length)!=c.i;){e=b.next();if(e.done)return e;e=e.value}return fi(a?e.slice(c.i.length):c.j.get(e))};
return d};function Fi(a){I.call(this,a)}
t(Fi,I);function Gi(a){I.call(this,a)}
t(Gi,I);Gi.prototype.getKey=function(){return Od(this,1)};
Gi.prototype.getValue=function(){return Od(this,2===Td(this,Hi)?2:-1)};
Gi.prototype.setValue=function(a){return Sd(this,2,Hi,a)};
var Hi=[2,3,4,5,6];function Ii(a){I.call(this,a)}
t(Ii,I);function Ji(a){I.call(this,a)}
t(Ji,I);function Ki(a){I.call(this,a,-1,Li)}
t(Ki,I);var Li=[2];function Mi(a){I.call(this,a,-1,Ni)}
t(Mi,I);Mi.prototype.getPlayerType=function(){return Od(this,36)};
Mi.prototype.setHomeGroupInfo=function(a){return G(this,Ki,81,a)};
var Ni=[9,66,24,32,86,100,101];function Oi(a){I.call(this,a,-1,Pi)}
t(Oi,I);var Pi=[15,26,28];function Qi(a){I.call(this,a)}
t(Qi,I);Qi.prototype.setToken=function(a){return E(this,2,a)};function Ri(a){I.call(this,a,-1,Si)}
t(Ri,I);Ri.prototype.setSafetyMode=function(a){return E(this,5,a)};
var Si=[12];function Ti(a){I.call(this,a,-1,Ui)}
t(Ti,I);Ti.prototype.s=function(a){G(this,Mi,1,a)};
var Ui=[12];function Vi(a){I.call(this,a,-1,Wi)}
t(Vi,I);function Xi(a){I.call(this,a)}
t(Xi,I);Xi.prototype.getKey=function(){return Qd(this,1,"")};
Xi.prototype.getValue=function(){return Qd(this,2,"")};
Xi.prototype.setValue=function(a){return E(this,2,a)};
var Wi=[4,5];function Yi(a){I.call(this,a)}
t(Yi,I);function Zi(a){I.call(this,a)}
t(Zi,I);var $i=[2,3,4];function aj(a){I.call(this,a)}
t(aj,I);aj.prototype.getMessage=function(){return Qd(this,1,"")};function bj(a){I.call(this,a)}
t(bj,I);function cj(a){I.call(this,a)}
t(cj,I);function dj(a){I.call(this,a,-1,ej)}
t(dj,I);var ej=[10,17];function fj(a){I.call(this,a)}
t(fj,I);function gj(a){I.call(this,a)}
t(gj,I);gj.prototype.V=function(a){E(this,1,a)};function hj(a){I.call(this,a)}
t(hj,I);function ij(a){I.call(this,a)}
t(ij,I);function jj(a){I.call(this,a)}
t(jj,I);function kj(a){I.call(this,a,-1,lj)}
t(kj,I);kj.prototype.getVideoData=function(){return Ud(this,jj,15)};
var lj=[4];function mj(a){I.call(this,a)}
t(mj,I);function nj(a,b){G(a,hj,1,b)}
mj.prototype.V=function(a){E(this,2,a)};
function oj(a){I.call(this,a)}
t(oj,I);function pj(a,b){G(a,hj,1,b)}
;function qj(a){I.call(this,a,-1,rj)}
t(qj,I);qj.prototype.V=function(a){E(this,1,a)};
function sj(a,b){G(a,hj,2,b)}
var rj=[3];function tj(a){I.call(this,a)}
t(tj,I);tj.prototype.V=function(a){E(this,1,a)};function uj(a){I.call(this,a)}
t(uj,I);uj.prototype.V=function(a){E(this,1,a)};function vj(a){I.call(this,a)}
t(vj,I);vj.prototype.V=function(a){E(this,1,a)};function wj(a){I.call(this,a)}
t(wj,I);wj.prototype.V=function(a){E(this,1,a)};function xj(a){I.call(this,a)}
t(xj,I);function yj(a){I.call(this,a)}
t(yj,I);function zj(a){I.call(this,a,-1,Aj)}
t(zj,I);function Bj(a,b){return E(a,1,b)}
zj.prototype.getPlayerType=function(){return Qd(this,7,0)};
zj.prototype.setVideoId=function(a){return E(this,19,a)};
function Cj(a,b){return E(a,25,b)}
function Dj(a,b){Zd(a,68,Ej,b)}
function Ej(a){I.call(this,a)}
t(Ej,I);Ej.prototype.getId=function(){return Qd(this,2,"")};
var Aj=[83,68];function Fj(a){I.call(this,a)}
t(Fj,I);function Gj(a){I.call(this,a)}
t(Gj,I);function Hj(a){I.call(this,a)}
t(Hj,I);function Ij(a){I.call(this,a,432)}
t(Ij,I);
var Jj=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,351,352,
353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117];var Kj={Ki:0,vi:1,Bi:2,Ci:4,Hi:8,Di:16,Ei:32,Ji:64,Ii:128,xi:256,zi:512,Gi:1024,yi:2048,Ai:4096,wi:8192,Fi:16384};function Lj(a){I.call(this,a)}
t(Lj,I);function Mj(a){I.call(this,a)}
t(Mj,I);Mj.prototype.setVideoId=function(a){return Sd(this,1,Nj,a)};
Mj.prototype.getPlaylistId=function(){return Od(this,2===Td(this,Nj)?2:-1)};
var Nj=[1,2];function Oj(a){I.call(this,a,-1,Pj)}
t(Oj,I);var Pj=[3];function Qj(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var lk=y.window,mk,nk,ok=(null==lk?void 0:null==(mk=lk.yt)?void 0:mk.config_)||(null==lk?void 0:null==(nk=lk.ytcfg)?void 0:nk.data_)||{};z("yt.config_",ok);function pk(){Qj(ok,arguments)}
function M(a,b){return a in ok?ok[a]:b}
function qk(){var a=ok.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;function P(a){a=rk(a);return"string"===typeof a&&"false"===a?!1:!!a}
function sk(a,b){a=rk(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function tk(){return M("EXPERIMENTS_TOKEN","")}
function rk(a){var b=M("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:M("EXPERIMENT_FLAGS",{})[a]}
function uk(){var a=[],b=M("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=M("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var vk=[];function wk(a){vk.forEach(function(b){return b(a)})}
function xk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){yk(b)}}:a}
function yk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=M("ERRORS",[]),e.push([a,"ERROR",b,c,d]),pk("ERRORS",e));wk(a)}
function zk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=M("ERRORS",[]),e.push([a,"WARNING",b,c,d]),pk("ERRORS",e))}
;function Ak(){var a=Bk;B("yt.ads.biscotti.getId_")||z("yt.ads.biscotti.getId_",a)}
function Ck(a){z("yt.ads.biscotti.lastId_",a)}
;var Dk=/^[\w.]*$/,Ek={q:!0,search_query:!0};function Fk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Gk(f[0]||""),h=Gk(f[1]||"");g in c?Array.isArray(c[g])?nb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var k=r,m=f[0],q=String(Fk);k.args=[{key:m,value:f[1],query:a,method:Hk==q?"unchanged":q}];Ek.hasOwnProperty(m)||zk(k)}}return c}
var Hk=String(Fk);function Ik(a){var b=[];ob(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];hb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Jk(a){"?"==a.charAt(0)&&(a=a.substr(1));return Fk(a,"&")}
function Kk(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Jk(1<a.length?a[1]:a[0])):{}}
function Lk(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Jk(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return yc(a,e)+d}
function Mk(a){if(!b)var b=window.location.href;var c=nc(1,a),d=oc(a);c&&d?(a=a.match(lc),b=b.match(lc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?oc(b)==d&&(Number(nc(4,b))||null)==(Number(nc(4,a))||null):!0;return a}
function Gk(a){return a&&a.match(Dk)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Nk(a){var b=Ok;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Kh;e.flash="0";a:{try{var f=b.i.top.location.href}catch(la){f=2;break a}f=f?f===b.j.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?yh:g;try{var h=g.history.length}catch(la){h=0}e.u_his=h;var k;e.u_h=null==(k=yh.screen)?void 0:k.height;var m;e.u_w=null==(m=yh.screen)?void 0:m.width;var q;e.u_ah=null==(q=yh.screen)?void 0:q.availHeight;var r;e.u_aw=
null==(r=yh.screen)?void 0:r.availWidth;var x;e.u_cd=null==(x=yh.screen)?void 0:x.colorDepth}catch(la){}h=b.i;try{var u=h.screenX;var A=h.screenY}catch(la){}try{var D=h.outerWidth;var F=h.outerHeight}catch(la){}try{var N=h.innerWidth;var O=h.innerHeight}catch(la){}try{var Q=h.screenLeft;var ca=h.screenTop}catch(la){}try{N=h.innerWidth,O=h.innerHeight}catch(la){}try{var aa=h.screen.availWidth;var ja=h.screen.availTop}catch(la){}u=[Q,ca,u,A,aa,ja,D,F,N,O];try{var ma=(b.i.top||window).document,na="CSS1Compat"==
ma.compatMode?ma.documentElement:ma.body;var H=(new cf(na.clientWidth,na.clientHeight)).round()}catch(la){H=new cf(-12245933,-12245933)}ma=H;H={};var ra=void 0===ra?y:ra;na=new Th;ra.SVGElement&&ra.document.createElementNS&&na.set(0);A=Eh();A["allow-top-navigation-by-user-activation"]&&na.set(1);A["allow-popups-to-escape-sandbox"]&&na.set(2);ra.crypto&&ra.crypto.subtle&&na.set(3);ra.TextDecoder&&ra.TextEncoder&&na.set(4);ra=Uh(na);H.bc=ra;H.bih=ma.height;H.biw=ma.width;H.brdim=u.join();b=b.j;b=(H.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,H.wgl=!!yh.WebGLRenderingContext,H);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Ok=new function(){var a=window.document;this.i=window;this.j=a};
z("yt.ads_.signals_.getAdSignalsString",function(a){return Ik(Nk(a))});Date.now();var Pk="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function Qk(){if(!Pk)return null;var a=Pk();return"open"in a?a:null}
function Rk(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Sk(a,b){"function"===typeof a&&(a=xk(a));return window.setTimeout(a,b)}
function Tk(a){window.clearTimeout(a)}
;var Uk={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},Vk="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(Lh)),Wk=!1;
function Xk(a,b){b=void 0===b?{}:b;var c=Mk(a),d=P("web_ajax_ignore_global_headers_if_set"),e;for(e in Uk){var f=M(Uk[e]);P("enable_visitor_header_for_vss")&&"X-Goog-Visitor-Id"===e&&!f&&(f=M("VISITOR_DATA"));!f||!c&&oc(a)||d&&void 0!==b[e]||!P("enable_web_eom_visitor_data")&&"X-Goog-EOM-Visitor-Id"===e||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!oc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!oc(a)){try{var g=
(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!oc(a))b["X-YouTube-Ad-Signals"]=Ik(Nk());return b}
function Yk(a){var b=window.location.search,c=oc(a);P("debug_handle_relative_url_for_query_forward_killswitch")||c||!Mk(a)||(c=document.location.hostname);var d=mc(nc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Jk(b),f={};hb(Vk,function(g){e[g]&&(f[g]=e[g])});
return Lk(a,f||{},!1)}
function Zk(a,b){var c=b.format||"JSON";a=$k(a,b);var d=al(a,b),e=!1,f=bl(a,function(k){if(!e){e=!0;h&&Tk(h);var m=Rk(k),q=null,r=400<=k.status&&500>k.status,x=500<=k.status&&600>k.status;if(m||r||x)q=cl(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(q&&q.return_code,10);break a;case "RAW":m=!0;break a}m=!!q}q=q||{};r=b.context||y;m?b.onSuccess&&b.onSuccess.call(r,k,q):b.onError&&b.onError.call(r,k,q);b.onFinish&&b.onFinish.call(r,k,q)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Sk(function(){e||(e=!0,f.abort(),Tk(h),g.call(b.context||y,f))},d)}return f}
function $k(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=M("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Lk(a,b||{},!0);return a}
function al(a,b){var c=M("XSRF_FIELD_NAME"),d=M("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=M("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||oc(a)&&!b.withCredentials&&oc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=Jk(e),yb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):tc(e));f=e||f&&!rb(f);!Wk&&f&&"POST"!=b.method&&(Wk=
!0,yk(Error("AJAX request with postData should use POST")));return e}
function cl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,zk(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?dl(a):null)e={},hb(a.getElementsByTagName("*"),function(g){e[g.tagName]=el(g)})}d&&fl(e);
return e}
function fl(a){if(Ta(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;Fb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=a[b],e=Ab();d=e?e.createHTML(d):d;a[c]=new ec(d)}else fl(a[b])}}
function dl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function el(a){var b="";hb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function bl(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&xk(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Qk();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;P("debug_forward_web_query_parameters")&&(a=Yk(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Xk(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function gl(a){var b=this;this.j=void 0;this.i=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.j=c});
a.addEventListener("appinstalled",function(){b.i=!0},{once:!0})}
function hl(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function il(a,b,c,d,e){lg.set(""+a,b,{ab:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function jl(){if(!lg.isEnabled())return!1;if(!lg.isEmpty())return!0;lg.set("TESTCOOKIESENABLED","1",{ab:60});if("1"!==lg.get("TESTCOOKIESENABLED"))return!1;lg.remove("TESTCOOKIESENABLED");return!0}
;var kl=B("ytglobal.prefsUserPrefsPrefs_")||{};z("ytglobal.prefsUserPrefsPrefs_",kl);function ll(){this.i=M("ALT_PREF_COOKIE_NAME","PREF");this.j=M("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=lg.get(""+this.i,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(kl[d]=c.toString())}}}
ll.prototype.get=function(a,b){ml(a);nl(a);a=void 0!==kl[a]?kl[a].toString():null;return null!=a?a:b?b:""};
ll.prototype.set=function(a,b){ml(a);nl(a);if(null==b)throw Error("ExpectedNotNull");kl[a]=b.toString()};
function ol(a){return!!((pl("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
ll.prototype.remove=function(a){ml(a);nl(a);delete kl[a]};
ll.prototype.clear=function(){for(var a in kl)delete kl[a]};
function nl(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function ml(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function pl(a){a=void 0!==kl[a]?kl[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Qa(ll);var ql={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},rl={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},sl={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},tl={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function ul(){var a=y.navigator;return a?a.connection:void 0}
function vl(){var a=ul();if(a){var b=ql[a.type||"unknown"]||"CONN_UNKNOWN";a=ql[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function wl(){var a=ul();if(null!=a&&a.effectiveType)return tl.hasOwnProperty(a.effectiveType)?tl[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function xl(){return"INNERTUBE_API_KEY"in ok&&"INNERTUBE_API_VERSION"in ok}
function yl(){return{innertubeApiKey:M("INNERTUBE_API_KEY"),innertubeApiVersion:M("INNERTUBE_API_VERSION"),rb:M("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Tb:M("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Kc:M("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:M("INNERTUBE_CONTEXT_CLIENT_VERSION"),Vb:M("INNERTUBE_CONTEXT_HL"),Ub:M("INNERTUBE_CONTEXT_GL"),Lc:M("INNERTUBE_HOST_OVERRIDE")||"",Nc:!!M("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Mc:!!M("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:M("SERIALIZED_CLIENT_CONFIG_DATA")}}
function zl(a){var b={client:{hl:a.Vb,gl:a.Ub,clientName:a.Tb,clientVersion:a.innertubeContextClientVersion,configInfo:a.rb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=tk();""!==c&&(b.client.experimentsToken=c);c=uk();0<c.length&&(b.request={internalExperimentFlags:c});Al(a,void 0,b);Bl(void 0,b);Cl(a,void 0,b);Dl(void 0,b);M("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&(b.user={onBehalfOfUser:M("DELEGATED_SESSION_ID")});
a=Object;c=a.assign;for(var d=b.client,e={},f=p(Object.entries(Jk(M("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=p(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function El(a){var b=new Ti,c=new Mi;E(c,1,a.Vb);E(c,2,a.Ub);E(c,16,a.Kc);E(c,17,a.innertubeContextClientVersion);if(a.rb){var d=a.rb,e=new Ii;d.coldConfigData&&E(e,1,d.coldConfigData);d.appInstallData&&E(e,6,d.appInstallData);d.coldHashData&&E(e,3,d.coldHashData);d.hotHashData&&E(e,5,d.hotHashData);G(c,Ii,62,e)}(d=y.devicePixelRatio)&&1!=d&&E(c,65,d);d=tk();""!==d&&E(c,54,d);d=uk();if(0<d.length){e=new Oi;for(var f=0;f<d.length;f++){var g=new Gi;E(g,1,d[f].key);g.setValue(d[f].value);Zd(e,15,Gi,
g)}G(b,Oi,5,e)}Al(a,c);Bl(c);Cl(a,c);Dl(c);M("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&(a=new Ri,E(a,3,M("DELEGATED_SESSION_ID")));a=p(Object.entries(Jk(M("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=p(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?E(c,12,e):"cmodel"===d?E(c,13,e):"cbr"===d?E(c,87,e):"cbrver"===d?E(c,88,e):"cos"===d?E(c,18,e):"cosver"===d?E(c,19,e):"cplatform"===d&&E(c,42,e);b.s(c);return b}
function Al(a,b,c){a=a.Tb;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Ud(b,Ji,96)||new Ji;var d=hl();d=Object.keys(Sh).indexOf(d);d=-1===d?null:d;null!==d&&E(c,3,d);G(b,Ji,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=hl())}
function Bl(a,b){var c;if(P("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?E(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Cl(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Ud(b,Ii,62))?d:new Ii;E(c,6,a.appInstallData);G(b,Ii,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Dl(a,b){var c=vl();c&&(a?E(a,61,rl[c]):b&&(b.client.connectionType=c));P("web_log_effective_connection_type")&&(c=wl())&&(a?E(a,94,sl[c]):b&&(b.client.effectiveConnectionType=c))}
function Fl(a,b,c){c=void 0===c?{}:c;var d={};P("enable_web_eom_visitor_data")&&M("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":M("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||M("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.fq||M("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().cq:b=pg([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=M("SESSION_INDEX",0),P("pageid_as_header_web")&&(d["X-Goog-PageId"]=M("DELEGATED_SESSION_ID")));return d}
;function Gl(a){a=Object.assign({},a);delete a.Authorization;var b=pg();if(b){var c=new Yh;c.update(M("INNERTUBE_API_KEY"));c.update(b);a.hash=fd(c.digest(),3)}return a}
;function Hl(a){var b=new yi;(b=b.isAvailable()?a?new Ei(b,a):b:null)||(a=new zi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.i=(a=b)?new ui(a):null;this.j=document.domain||window.location.hostname}
Hl.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.i)try{this.i.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(tg(b))}catch(f){return}else e=escape(b);il(a,e,c,this.j)};
Hl.prototype.get=function(a,b){var c=void 0,d=!this.i;if(!d)try{c=this.i.get(a)}catch(e){d=!0}if(d&&(c=lg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Hl.prototype.remove=function(a){this.i&&this.i.remove(a);var b=this.j;lg.remove(""+a,"/",void 0===b?"youtube.com":b)};var Il=window,R=Il.ytcsi&&Il.ytcsi.now?Il.ytcsi.now:Il.performance&&Il.performance.timing&&Il.performance.now&&Il.performance.timing.navigationStart?function(){return Il.performance.timing.navigationStart+Il.performance.now()}:function(){return(new Date).getTime()};var Jl;function Kl(){Jl||(Jl=new Hl("yt.innertube"));return Jl}
function Ll(a,b,c,d){if(d)return null;d=Kl().get("nextId",!0)||1;var e=Kl().get("requests",!0)||{};e[d]={method:a,request:b,authState:Gl(c),requestTime:Math.round(R())};Kl().set("nextId",d+1,86400,!0);Kl().set("requests",e,86400,!0);return d}
function Ml(a){var b=Kl().get("requests",!0)||{};delete b[a];Kl().set("requests",b,86400,!0)}
function Nl(a){var b=Kl().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(R())-d.requestTime)){var e=d.authState,f=Gl(Fl(!1));ub(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(R())),Ol(a,d.method,e,{}));delete b[c]}}Kl().set("requests",b,86400,!0)}}
;function Pl(){}
Pl.prototype.S=function(a,b){return Ql(a,1,b)};
function Rl(a,b){Ql(a,2,b)}
function Sl(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function Tl(){Pl.apply(this,arguments)}
t(Tl,Pl);function Ul(){Tl.i||(Tl.i=new Tl);return Tl.i}
function Ql(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Sk(a,c||0)}
Tl.prototype.fa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):Tk(a)}};
Tl.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
Tl.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};var Qh=Ul();var Vl=ad||bd;function Wl(a){var b=Tb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var Xl=function(){var a;return function(){a||(a=new Hl("ytidb"));return a}}();
function Yl(){var a;return null==(a=Xl())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Zl=[],$l,am=!1;function bm(){var a={};for($l=new cm(void 0===a.handleError?dm:a.handleError,void 0===a.logEvent?em:a.logEvent);0<Zl.length;)switch(a=Zl.shift(),a.type){case "ERROR":$l.handleError(a.payload);break;case "EVENT":$l.logEvent(a.eventType,a.payload)}}
function fm(a){am||($l?$l.handleError(a):(Zl.push({type:"ERROR",payload:a}),10<Zl.length&&Zl.shift()))}
function gm(a,b){am||($l?$l.logEvent(a,b):(Zl.push({type:"EVENT",eventType:a,payload:b}),10<Zl.length&&Zl.shift()))}
;function S(a){var b=Ma.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
t(S,Error);function hm(){try{return im(),!0}catch(a){return!1}}
function im(a){if(void 0!==M("DATASYNC_ID"))return M("DATASYNC_ID");throw new S("Datasync ID not set",void 0===a?"unknown":a);}
;function jm(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function km(a){return a.substr(0,a.indexOf(":"))||a}
;var lm={},mm=(lm.AUTH_INVALID="No user identifier specified.",lm.EXPLICIT_ABORT="Transaction was explicitly aborted.",lm.IDB_NOT_SUPPORTED="IndexedDB is not supported.",lm.MISSING_INDEX="Index not created.",lm.MISSING_OBJECT_STORES="Object stores not created.",lm.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",lm.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",lm.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
lm.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",lm.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",lm.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",lm.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",lm),nm={},om=(nm.AUTH_INVALID="ERROR",nm.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",nm.EXPLICIT_ABORT="IGNORED",nm.IDB_NOT_SUPPORTED="ERROR",nm.MISSING_INDEX=
"WARNING",nm.MISSING_OBJECT_STORES="ERROR",nm.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",nm.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",nm.QUOTA_EXCEEDED="WARNING",nm.QUOTA_MAYBE_EXCEEDED="WARNING",nm.UNKNOWN_ABORT="WARNING",nm.INCOMPATIBLE_DB_VERSION="WARNING",nm),pm={},qm=(pm.AUTH_INVALID=!1,pm.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,pm.EXPLICIT_ABORT=!1,pm.IDB_NOT_SUPPORTED=!1,pm.MISSING_INDEX=!1,pm.MISSING_OBJECT_STORES=!1,pm.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,pm.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,pm.QUOTA_EXCEEDED=!1,pm.QUOTA_MAYBE_EXCEEDED=!0,pm.UNKNOWN_ABORT=!0,pm.INCOMPATIBLE_DB_VERSION=!1,pm);function rm(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?mm[a]:c;d=void 0===d?om[a]:d;e=void 0===e?qm[a]:e;S.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.i=e;Object.setPrototypeOf(this,rm.prototype)}
t(rm,S);function sm(a,b){rm.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},mm.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,sm.prototype)}
t(sm,rm);function tm(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,tm.prototype)}
t(tm,Error);var um=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function vm(a,b,c,d){b=km(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof rm)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new rm("QUOTA_EXCEEDED",a);if(cd&&"UnknownError"===e.name)return new rm("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof tm)return new rm("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&um.some(function(f){return e.message.includes(f)}))return new rm("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new rm("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Zb:e.name})];e.level="WARNING";return e}
function wm(a,b,c){var d=Yl();return new rm("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function xm(a){if(!a)throw Error();throw a;}
function ym(a){return a}
function zm(a){this.i=a}
function Am(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=p(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=p(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.i=[];this.onRejected=[];a=a.i;try{a(c,b)}catch(e){b(e)}}
Am.all=function(a){return new Am(new zm(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={wa:0};f.wa<a.length;f={wa:f.wa},++f.wa)Am.resolve(a[f.wa]).then(function(g){return function(h){d[g.wa]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Am.resolve=function(a){return new Am(new zm(function(b,c){a instanceof Am?a.then(b,c):b(a)}))};
Am.reject=function(a){return new Am(new zm(function(b,c){c(a)}))};
Am.prototype.then=function(a,b){var c=this,d=null!=a?a:ym,e=null!=b?b:xm;return new Am(new zm(function(f,g){"PENDING"===c.state.status?(c.i.push(function(){Bm(c,c,d,f,g)}),c.onRejected.push(function(){Cm(c,c,e,f,g)})):"FULFILLED"===c.state.status?Bm(c,c,d,f,g):"REJECTED"===c.state.status&&Cm(c,c,e,f,g)}))};
Am.prototype.catch=function(a){return this.then(void 0,a)};
function Bm(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Am?Dm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Cm(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Am?Dm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Dm(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Am?Dm(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Em(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Fm(a){return new Promise(function(b,c){Em(a,b,c)})}
function Gm(a){return new Am(new zm(function(b,c){Em(a,b,c)}))}
;function Hm(a,b){return new Am(new zm(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Im(a,b){this.i=a;this.options=b;this.transactionCount=0;this.l=Math.round(R());this.j=!1}
l=Im.prototype;l.add=function(a,b,c){return Jm(this,[a],{mode:"readwrite",U:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return Jm(this,[a],{mode:"readwrite",U:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.i.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return Jm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).count(b)})};
function Km(a,b,c){a=a.i.createObjectStore(b,c);return new Lm(a)}
l.delete=function(a,b){return Jm(this,[a],{mode:"readwrite",U:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return Jm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).get(b)})};
function Mm(a,b){return Jm(a,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(c){c=c.objectStore("LogsRequestsStore");return Gm(c.i.put(b,void 0))})}
l.objectStoreNames=function(){return Array.from(this.i.objectStoreNames)};
function Jm(a,b,c,d){var e,f,g,h,k,m,q,r,x,u,A,D;return w(function(F){switch(F.i){case 1:var N={mode:"readonly",U:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?N.mode=c:Object.assign(N,c);e=N;a.transactionCount++;f=e.U?3:1;g=0;case 2:if(h){F.u(3);break}g++;k=Math.round(R());Ba(F,4);m=a.i.transaction(b,e.mode);N=new Nm(m);N=Om(N,d);return v(F,N,6);case 6:return q=F.j,r=Math.round(R()),Pm(a,k,r,g,void 0,b.join(),e),F.return(q);case 4:x=Da(F);u=Math.round(R());A=vm(x,a.i.name,b.join(),a.i.version);
if((D=A instanceof rm&&!A.i)||g>=f)Pm(a,k,u,g,A,b.join(),e),h=A;F.u(2);break;case 3:return F.return(Promise.reject(h))}})}
function Pm(a,b,c,d,e,f,g){b=c-b;e?(e instanceof rm&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&gm("QUOTA_EXCEEDED",{dbName:km(a.i.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof rm&&"UNKNOWN_ABORT"===e.type&&(c-=a.l,0>c&&c>=Math.pow(2,31)&&(c=0),gm("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.j=!0),Qm(a,!1,d,f,b,g.tag),fm(e)):Qm(a,!0,d,f,b,g.tag)}
function Qm(a,b,c,d,e,f){gm("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.j,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.i.name};
function Lm(a){this.i=a}
l=Lm.prototype;l.add=function(a,b){return Gm(this.i.add(a,b))};
l.autoIncrement=function(){return this.i.autoIncrement};
l.clear=function(){return Gm(this.i.clear()).then(function(){})};
l.count=function(a){return Gm(this.i.count(a))};
function Rm(a,b){return Sm(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?Rm(this,a):Gm(this.i.delete(a))};
l.get=function(a){return Gm(this.i.get(a))};
l.index=function(a){try{return new Tm(this.i.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new tm(a,this.i.name);throw b;}};
l.getName=function(){return this.i.name};
l.keyPath=function(){return this.i.keyPath};
function Sm(a,b,c){a=a.i.openCursor(b.query,b.direction);return Um(a).then(function(d){return Hm(d,c)})}
function Nm(a){var b=this;this.i=a;this.l=new Map;this.j=!1;this.done=new Promise(function(c,d){b.i.addEventListener("complete",function(){c()});
b.i.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.i.error)});
b.i.addEventListener("abort",function(){var e=b.i.error;if(e)d(e);else if(!b.j){e=rm;for(var f=b.i.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.i.db.name,mode:b.i.mode});d(e)}})})}
function Om(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return p(d).next().value})}
Nm.prototype.abort=function(){this.i.abort();this.j=!0;throw new rm("EXPLICIT_ABORT");};
Nm.prototype.objectStore=function(a){a=this.i.objectStore(a);var b=this.l.get(a);b||(b=new Lm(a),this.l.set(a,b));return b};
function Tm(a){this.i=a}
l=Tm.prototype;l.count=function(a){return Gm(this.i.count(a))};
l.delete=function(a){return Vm(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return Gm(this.i.get(a))};
l.getKey=function(a){return Gm(this.i.getKey(a))};
l.keyPath=function(){return this.i.keyPath};
l.unique=function(){return this.i.unique};
function Vm(a,b,c){a=a.i.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Um(a).then(function(d){return Hm(d,c)})}
function Wm(a,b){this.request=a;this.cursor=b}
function Um(a){return Gm(a).then(function(b){return b?new Wm(a,b):null})}
l=Wm.prototype;l.advance=function(a){this.cursor.advance(a);return Um(this.request)};
l.continue=function(a){this.cursor.continue(a);return Um(this.request)};
l.delete=function(){return Gm(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return Gm(this.cursor.update(a))};function Xm(a,b,c){return new Promise(function(d,e){function f(){x||(x=new Im(g.result,{closed:r}));return x}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,m=c.nd,q=c.upgrade,r=c.closed,x;g.addEventListener("upgradeneeded",function(u){try{if(null===u.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");u.dataLoss&&"none"!==u.dataLoss&&gm("IDB_DATA_CORRUPTED",{reason:u.dataLossMessage||"unknown reason",dbName:km(a)});var A=f(),D=new Nm(g.transaction);
q&&q(A,function(F){return u.oldVersion<F&&u.newVersion>=F},D);
D.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var u=g.result;k&&u.addEventListener("versionchange",function(){k(f())});
u.addEventListener("close",function(){gm("IDB_UNEXPECTEDLY_CLOSED",{dbName:km(a),dbVersion:u.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Ym(a,b,c){c=void 0===c?{}:c;return Xm(a,b,c)}
function Zm(a,b){b=void 0===b?{}:b;var c,d,e,f;return w(function(g){if(1==g.i)return Ba(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),v(g,Fm(c),4);
if(2!=g.i)return Ca(g,0);f=Da(g);throw vm(f,a,"",-1);})}
;function $m(a){return new Promise(function(b){Rl(function(){b()},a)})}
function an(a,b){this.name=a;this.options=b;this.m=!0;this.s=this.o=0;this.j=500}
an.prototype.l=function(a,b,c){c=void 0===c?{}:c;return Ym(a,b,c)};
an.prototype.delete=function(a){a=void 0===a?{}:a;return Zm(this.name,a)};
function bn(a,b){return new rm("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function cn(a,b){if(!b)throw wm("openWithToken",km(a.name));return dn(a)}
function dn(a){function b(){var f,g,h,k,m,q,r,x,u,A;return w(function(D){switch(D.i){case 1:return g=null!=(f=Error().stack)?f:"",Ba(D,2),v(D,a.l(a.name,a.options.version,d),4);case 4:h=D.j;for(var F=a.options,N=[],O=p(Object.keys(F.Ia)),Q=O.next();!Q.done;Q=O.next()){Q=Q.value;var ca=F.Ia[Q],aa=void 0===ca.Vc?Number.MAX_VALUE:ca.Vc;!(h.i.version>=ca.jb)||h.i.version>=aa||h.i.objectStoreNames.contains(Q)||N.push(Q)}k=N;if(0===k.length){D.u(5);break}m=Object.keys(a.options.Ia);q=h.objectStoreNames();
if(a.s<sk("ytidb_reopen_db_retries",0))return a.s++,h.close(),fm(new rm("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),D.return(b());if(!(a.o<sk("ytidb_remake_db_retries",1))){D.u(6);break}a.o++;if(!P("ytidb_remake_db_enable_backoff_delay")){D.u(7);break}return v(D,$m(a.j),8);case 8:a.j*=2;case 7:return v(D,a.delete(),9);case 9:return fm(new rm("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),D.return(b());
case 6:throw new sm(q,m);case 5:return D.return(h);case 2:r=Da(D);if(r instanceof DOMException?"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){D.u(10);break}return v(D,a.l(a.name,void 0,Object.assign({},d,{upgrade:void 0})),11);case 11:x=D.j;u=x.i.version;if(void 0!==a.options.version&&u>a.options.version+1)throw x.close(),
a.m=!1,bn(a,u);return D.return(x);case 10:throw c(),r instanceof Error&&!P("ytidb_async_stack_killswitch")&&(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),vm(r,a.name,"",null!=(A=a.options.version)?A:-1);}})}
function c(){a.i===e&&(a.i=void 0)}
if(!a.m)throw bn(a);if(a.i)return a.i;var d={blocking:function(f){f.close()},
closed:c,nd:c,upgrade:a.options.upgrade};var e=b();a.i=e;return a.i}
;var en=new an("YtIdbMeta",{Ia:{databases:{jb:1}},upgrade:function(a,b){b(1)&&Km(a,"databases",{keyPath:"actualName"})}});
function fn(a,b){var c;return w(function(d){if(1==d.i)return v(d,cn(en,b),2);c=d.j;return d.return(Jm(c,["databases"],{U:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Gm(f.i.put(a,void 0)).then(function(){})})}))})}
function gn(a,b){var c;return w(function(d){if(1==d.i)return a?v(d,cn(en,b),2):d.return();c=d.j;return d.return(c.delete("databases",a))})}
function hn(a,b){var c,d;return w(function(e){return 1==e.i?(c=[],v(e,cn(en,b),2)):3!=e.i?(d=e.j,v(e,Jm(d,["databases"],{U:!0,mode:"readonly"},function(f){c.length=0;return Sm(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function jn(a){return hn(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function kn(a,b,c){return hn(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function ln(a){var b,c;return w(function(d){if(1==d.i)return b=im("YtIdbMeta hasAnyMeta other"),v(d,hn(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.j;return d.return(0<c.length)})}
;var mn,nn=new function(){}(new function(){});
function on(){var a,b,c,d;return w(function(e){switch(e.i){case 1:a=Yl();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Vl)f=/WebKit\/([0-9]+)/.exec(Tb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Tb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Nc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
Ba(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return v(e,fn(d,nn),4);case 4:return v(e,gn("yt-idb-test-do-not-use",nn),5);case 5:return e.return(!0);case 2:return Da(e),e.return(!1)}})}
function pn(){if(void 0!==mn)return mn;am=!0;return mn=on().then(function(a){am=!1;var b;if(null!=(b=Xl())&&b.i){var c;b={hasSucceededOnce:(null==(c=Yl())?void 0:c.hasSucceededOnce)||a};var d;null==(d=Xl())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function qn(){return B("ytglobal.idbToken_")||void 0}
function rn(){var a=qn();return a?Promise.resolve(a):pn().then(function(b){(b=b?nn:void 0)&&z("ytglobal.idbToken_",b);return b})}
;var sn=0;function tn(a,b){sn||(sn=Qh.S(function(){var c,d,e,f,g;return w(function(h){switch(h.i){case 1:return v(h,rn(),2);case 2:c=h.j;if(!c)return h.return();d=!0;Ba(h,3);return v(h,kn(a,c,b),5);case 5:e=h.j;if(!e.length){d=!1;h.u(6);break}f=e[0];return v(h,Zm(f.actualName),7);case 7:return v(h,gn(f.actualName,c),6);case 6:Ca(h,4);break;case 3:g=Da(h),fm(g),d=!1;case 4:Qh.fa(sn),sn=0,d&&tn(a,b),h.i=0}})}))}
function un(){var a;return w(function(b){return 1==b.i?v(b,rn(),2):(a=b.j)?b.return(ln(a)):b.return(!1)})}
new wh;function vn(a){if(!hm())throw a=new rm("AUTH_INVALID",{dbName:a}),fm(a),a;var b=im();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function wn(a,b,c,d){var e,f,g,h,k,m;return w(function(q){switch(q.i){case 1:return f=null!=(e=Error().stack)?e:"",v(q,rn(),2);case 2:g=q.j;if(!g)throw h=wm("openDbImpl",a,b),P("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),fm(h),h;jm(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:vn(a);Ba(q,3);return v(q,fn(k,g),5);case 5:return v(q,Ym(k.actualName,b,d),6);case 6:return q.return(q.j);case 3:return m=Da(q),Ba(q,7),v(q,gn(k.actualName,g),9);case 9:Ca(q,
8);break;case 7:Da(q);case 8:throw m;}})}
function xn(a,b,c){c=void 0===c?{}:c;return wn(a,b,!1,c)}
function yn(a,b,c){c=void 0===c?{}:c;return wn(a,b,!0,c)}
function zn(a,b){b=void 0===b?{}:b;var c,d;return w(function(e){if(1==e.i)return v(e,rn(),2);if(3!=e.i){c=e.j;if(!c)return e.return();jm(a);d=vn(a);return v(e,Zm(d.actualName,b),3)}return v(e,gn(d.actualName,c),0)})}
function An(a,b,c){a=a.map(function(d){return w(function(e){return 1==e.i?v(e,Zm(d.actualName,b),2):v(e,gn(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Bn(){var a=void 0===a?{}:a;var b,c;return w(function(d){if(1==d.i)return v(d,rn(),2);if(3!=d.i){b=d.j;if(!b)return d.return();jm("LogsDatabaseV2");return v(d,jn(b),3)}c=d.j;return v(d,An(c,a,b),0)})}
function Cn(a,b){b=void 0===b?{}:b;var c;return w(function(d){if(1==d.i)return v(d,rn(),2);if(3!=d.i){c=d.j;if(!c)return d.return();jm(a);return v(d,Zm(a,b),3)}return v(d,gn(a,c),0)})}
;function Dn(a){this.Sa=this.i=!1;this.potentialEsfErrorCounter=this.j=0;this.handleError=function(){};
this.za=function(){};
this.now=Date.now;this.Ga=!1;var b;this.kc=null!=(b=a.kc)?b:100;var c;this.fc=null!=(c=a.fc)?c:1;var d;this.dc=null!=(d=a.dc)?d:2592E6;var e;this.ac=null!=(e=a.ac)?e:12E4;var f;this.ec=null!=(f=a.ec)?f:5E3;var g;this.G=null!=(g=a.G)?g:void 0;this.Xa=!!a.Xa;var h;this.Va=null!=(h=a.Va)?h:.1;var k;this.cb=null!=(k=a.cb)?k:10;a.handleError&&(this.handleError=a.handleError);a.za&&(this.za=a.za);a.Ga&&(this.Ga=a.Ga);a.Sa&&(this.Sa=a.Sa);this.H=a.H;this.Z=a.Z;this.O=a.O;this.M=a.M;this.ia=a.ia;this.wb=
a.wb;this.vb=a.vb;En(this)&&(!this.H||this.H("networkless_logging"))&&Fn(this)}
function Fn(a){En(a)&&!a.Ga&&(a.i=!0,a.Xa&&Math.random()<=a.Va&&a.O.zc(a.G),Gn(a),a.M.L()&&a.Ma(),a.M.aa(a.wb,a.Ma.bind(a)),a.M.aa(a.vb,a.Ib.bind(a)))}
l=Dn.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(En(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.O.set(d,this.G).then(function(e){d.id=e;c.M.L()&&Hn(c,d)}).catch(function(e){Hn(c,d);
In(c,e)})}else this.ia(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(En(this)&&this.i){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.H&&this.H("nwl_skip_retry")&&(e.skipRetry=c);if(this.M.L()||this.H&&this.H("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return w(function(k){if(1==k.i)return v(k,d.O.set(e,d.G).catch(function(m){In(d,m)}),2);
f(g,h);k.i=0})}}this.ia(a,b,e.skipRetry)}else this.O.set(e,this.G).catch(function(g){d.ia(a,b,e.skipRetry);
In(d,g)})}else this.ia(a,b,this.H&&this.H("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(En(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.O.ya(d.id,c.G):e=!0;c.M.ha&&c.H&&c.H("vss_network_hint")&&c.M.ha(!0);f(g,h)};
this.ia(d.url,d.options);this.O.set(d,this.G).then(function(g){d.id=g;e&&c.O.ya(d.id,c.G)}).catch(function(g){In(c,g)})}else this.ia(a,b)};
l.Ma=function(){var a=this;if(!En(this))throw wm("throttleSend");this.j||(this.j=this.Z.S(function(){var b;return w(function(c){if(1==c.i)return v(c,a.O.Sb("NEW",a.G),2);if(3!=c.i)return b=c.j,b?v(c,Hn(a,b),3):(a.Ib(),c.return());a.j&&(a.j=0,a.Ma());c.i=0})},this.kc))};
l.Ib=function(){this.Z.fa(this.j);this.j=0};
function Hn(a,b){var c,d;return w(function(e){switch(e.i){case 1:if(!En(a))throw c=wm("immediateSend"),c;if(void 0===b.id){e.u(2);break}return v(e,a.O.Pc(b.id,a.G),3);case 3:(d=e.j)?b=d:a.za(Error("The request cannot be found in the database."));case 2:if(Jn(a,b,a.dc)){e.u(4);break}a.za(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.u(5);break}return v(e,a.O.ya(b.id,a.G),5);case 5:return e.return();case 4:b.skipRetry||(b=Kn(a,b));if(!b){e.u(0);break}if(!b.skipRetry||
void 0===b.id){e.u(8);break}return v(e,a.O.ya(b.id,a.G),8);case 8:a.ia(b.url,b.options,!!b.skipRetry),e.i=0}})}
function Kn(a,b){if(!En(a))throw wm("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k;return w(function(m){switch(m.i){case 1:g=Ln(f);if(!(a.H&&a.H("nwl_consider_error_code")&&g||a.H&&!a.H("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.cb)){m.u(2);break}if(!a.M.Ka){m.u(3);break}return v(m,a.M.Ka(),3);case 3:if(a.M.L()){m.u(2);break}c(e,f);if(!a.H||!a.H("nwl_consider_error_code")||void 0===(null==(h=b)?void 0:h.id)){m.u(6);break}return v(m,a.O.zb(b.id,a.G,!1),6);case 6:return m.return();case 2:if(a.H&&a.H("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.cb)return m.return();a.potentialEsfErrorCounter++;if(void 0===(null==(k=b)?void 0:k.id)){m.u(8);break}return b.sendCount<a.fc?v(m,a.O.zb(b.id,a.G),12):v(m,a.O.ya(b.id,a.G),8);case 12:a.Z.S(function(){a.M.L()&&a.Ma()},a.ec);
case 8:c(e,f),m.i=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return w(function(h){if(1==h.i)return void 0===(null==(g=b)?void 0:g.id)?h.u(2):v(h,a.O.ya(b.id,a.G),2);a.M.ha&&a.H&&a.H("vss_network_hint")&&a.M.ha(!0);d(e,f);h.i=0})};
return b}
function Jn(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Gn(a){if(!En(a))throw wm("retryQueuedRequests");a.O.Sb("QUEUED",a.G).then(function(b){b&&!Jn(a,b,a.ac)?a.Z.S(function(){return w(function(c){if(1==c.i)return void 0===b.id?c.u(2):v(c,a.O.zb(b.id,a.G),2);Gn(a);c.i=0})}):a.M.L()&&a.Ma()})}
function In(a,b){a.oc&&!a.M.L()?a.oc(b):a.handleError(b)}
function En(a){return!!a.G||a.Sa}
function Ln(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function Mn(a,b){this.version=a;this.args=b}
;function Nn(a,b){this.topic=a;this.i=b}
Nn.prototype.toString=function(){return this.topic};var On=B("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.Da;L.prototype.publish=L.prototype.oa;L.prototype.clear=L.prototype.clear;z("ytPubsub2Pubsub2Instance",On);var Pn=B("ytPubsub2Pubsub2SubscribedKeys")||{};z("ytPubsub2Pubsub2SubscribedKeys",Pn);var Qn=B("ytPubsub2Pubsub2TopicToKeys")||{};z("ytPubsub2Pubsub2TopicToKeys",Qn);var Rn=B("ytPubsub2Pubsub2IsAsync")||{};z("ytPubsub2Pubsub2IsAsync",Rn);
z("ytPubsub2Pubsub2SkipSubKey",null);function Sn(a,b){var c=Tn();c&&c.publish.call(c,a.toString(),a,b)}
function Un(a){var b=Vn,c=Tn();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Pn[d])try{if(f&&b instanceof Nn&&b!=e)try{var h=b.i,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.na){var m=new h;h.na=m.version}var q=h.na}catch(F){}if(!q||k.version!=q)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{q=Reflect;var r=q.construct;
var x=k.args,u=x.length;if(0<u){var A=Array(u);for(k=0;k<u;k++)A[k]=x[k];var D=A}else D=[];f=r.call(q,h,D)}catch(F){throw F.message="yt.pubsub2.Data.deserialize(): "+F.message,F;}}catch(F){throw F.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+F.message,F;}a.call(window,f)}catch(F){yk(F)}},Rn[b.toString()]?B("yt.scheduler.instance")?Qh.S(g):Sk(g,0):g())});
Pn[d]=!0;Qn[b.toString()]||(Qn[b.toString()]=[]);Qn[b.toString()].push(d);return d}
function Wn(){var a=Xn,b=Un(function(c){a.apply(void 0,arguments);Yn(b)});
return b}
function Yn(a){var b=Tn();b&&("number"===typeof a&&(a=[a]),hb(a,function(c){b.unsubscribeByKey(c);delete Pn[c]}))}
function Tn(){return B("ytPubsub2Pubsub2Instance")}
;function Zn(a,b){an.call(this,a,b);this.options=b;jm(a)}
t(Zn,an);function $n(a,b){var c;return function(){c||(c=new Zn(a,b));return c}}
Zn.prototype.l=function(a,b,c){c=void 0===c?{}:c;return(this.options.Ab?yn:xn)(a,b,Object.assign({},c))};
Zn.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Ab?Cn:zn)(this.name,a)};
function ao(a,b){return $n(a,b)}
;var bo;
function co(){if(bo)return bo();var a={};bo=ao("LogsDatabaseV2",{Ia:(a.LogsRequestsStore={jb:2},a),Ab:!1,upgrade:function(b,c,d){c(2)&&Km(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.i.indexNames.contains("newRequest")&&d.i.deleteIndex("newRequest"),d.i.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.i.objectStoreNames.contains("sapisid")&&b.i.deleteObjectStore("sapisid");c(9)&&b.i.objectStoreNames.contains("SWHealthLog")&&b.i.deleteObjectStore("SWHealthLog")},
version:9});return bo()}
;function eo(a){return cn(co(),a)}
function fo(a,b){var c,d,e,f;return w(function(g){if(1==g.i)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},v(g,eo(b),2);if(3!=g.i)return d=g.j,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:M("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),v(g,Mm(d,e),3);f=g.j;c.pd=R();go(c);return g.return(f)})}
function ho(a,b){var c,d,e,f,g,h,k;return w(function(m){if(1==m.i)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},v(m,eo(b),2);if(3!=m.i)return d=m.j,e=M("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,R()],h=IDBKeyRange.bound(f,g),k=void 0,v(m,Jm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(q){return Vm(q.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(k=r.getValue(),"NEW"===a&&(k.status="QUEUED",
r.update(k)))})}),3);
c.pd=R();go(c);return m.return(k)})}
function io(a,b){var c;return w(function(d){if(1==d.i)return v(d,eo(b),2);c=d.j;return d.return(Jm(c,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Gm(f.i.put(g,void 0)).then(function(){return g})})}))})}
function jo(a,b,c){c=void 0===c?!0:c;var d;return w(function(e){if(1==e.i)return v(e,eo(b),2);d=e.j;return e.return(Jm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),Gm(g.i.put(h,void 0)).then(function(){return h})):Am.resolve(void 0)})}))})}
function ko(a,b){var c;return w(function(d){if(1==d.i)return v(d,eo(b),2);c=d.j;return d.return(c.delete("LogsRequestsStore",a))})}
function lo(a){var b,c;return w(function(d){if(1==d.i)return v(d,eo(a),2);b=d.j;c=R()-2592E6;return v(d,Jm(b,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){return Sm(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function mo(){return w(function(a){return v(a,Bn(),0)})}
function go(a){P("nwl_csi_killswitch")||.01>=Math.random()&&Sn("nwl_transaction_latency_payload",a)}
;var no={},oo=ao("ServiceWorkerLogsDatabase",{Ia:(no.SWHealthLog={jb:1},no),Ab:!0,upgrade:function(a,b){b(1)&&Km(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).i.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function po(a){return cn(oo(),a)}
function qo(a){var b,c;return w(function(d){if(1==d.i)return v(d,po(a),2);b=d.j;c=R()-2592E6;return v(d,Jm(b,["SWHealthLog"],{mode:"readwrite",U:!0},function(e){return Sm(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function ro(a){var b;return w(function(c){if(1==c.i)return v(c,po(a),2);b=c.j;return v(c,b.clear("SWHealthLog"),0)})}
;var so={},to=0;
function uo(a){var b=void 0===b?"":b;var c=void 0===c?!1:c;if(a)if(b)bl(a,void 0,"POST",b);else if(M("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))bl(a,void 0,"GET","",void 0,void 0,c);else{b:{try{var d=new db({url:a});if(d.l&&d.j||d.m){var e=mc(nc(5,a)),f;if(!(f=!e||!e.endsWith("/aclk"))){var g=a.search(Bc),h=Ac(a,0,"ri",g);if(0>h)var k=null;else{var m=a.indexOf("&",h);if(0>m||m>g)m=g;k=decodeURIComponent(a.slice(h+3,-1!==m?m:0).replace(/\+/g," "))}f="1"!==k}var q=!f;break b}}catch(x){}q=!1}if(q){b:{try{if(window.navigator&&
window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var r=!0;break b}}catch(x){}r=!1}b=r?!0:!1}else b=!1;b||vo(a)}}
function vo(a){var b=new Image,c=""+to++;so[c]=b;b.onload=b.onerror=function(){delete so[c]};
b.src=a}
;function wo(){this.i=new Map;this.j=!1}
function xo(){if(!wo.i){var a=B("yt.networkRequestMonitor.instance")||new wo;z("yt.networkRequestMonitor.instance",a);wo.i=a}return wo.i}
wo.prototype.requestComplete=function(a,b){b&&(this.j=!0);a=this.removeParams(a);this.i.get(a)||this.i.set(a,b)};
wo.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.i.get(a))?!1:!1===a&&this.j?!0:null};
wo.prototype.removeParams=function(a){return a.split("?")[0]};
wo.prototype.removeParams=wo.prototype.removeParams;wo.prototype.isEndpointCFR=wo.prototype.isEndpointCFR;wo.prototype.requestComplete=wo.prototype.requestComplete;wo.getInstance=xo;var yo;function zo(){yo||(yo=new Hl("yt.offline"));return yo}
function Ao(a){if(P("offline_error_handling")){var b=zo().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);zo().set("errors",b,2592E3,!0)}}
;function Bo(){K.call(this);var a=this;this.l=!1;this.j=Ph();this.j.aa("networkstatus-online",function(){if(a.l&&P("offline_error_handling")){var b=zo().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new S(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;yk(d)}zo().set("errors",{},2592E3,!0)}}})}
t(Bo,K);function Co(){if(!Bo.i){var a=B("yt.networkStatusManager.instance")||new Bo;z("yt.networkStatusManager.instance",a);Bo.i=a}return Bo.i}
l=Bo.prototype;l.L=function(){return this.j.L()};
l.ha=function(a){this.j.j=a};
l.Jc=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.Dc=function(){this.l=!0};
l.aa=function(a,b){return this.j.aa(a,b)};
l.Ka=function(a){a=Nh(this.j,a);a.then(function(b){P("use_cfr_monitor")&&xo().requestComplete("generate_204",b)});
return a};
Bo.prototype.sendNetworkCheckRequest=Bo.prototype.Ka;Bo.prototype.listen=Bo.prototype.aa;Bo.prototype.enableErrorFlushing=Bo.prototype.Dc;Bo.prototype.getWindowStatus=Bo.prototype.Jc;Bo.prototype.networkStatusHint=Bo.prototype.ha;Bo.prototype.isNetworkAvailable=Bo.prototype.L;Bo.getInstance=Co;function Do(a){a=void 0===a?{}:a;K.call(this);var b=this;this.j=this.s=0;this.l=Co();var c=B("yt.networkStatusManager.instance.listen").bind(this.l);c&&(a.fb?(this.fb=a.fb,c("networkstatus-online",function(){Eo(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Eo(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Xe(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Xe(b,"publicytnetworkstatus-offline")})))}
t(Do,K);Do.prototype.L=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.l)():!0};
Do.prototype.ha=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.l);b&&b(a)};
Do.prototype.Ka=function(a){var b=this,c;return w(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.l);return P("skip_network_check_if_cfr")&&xo().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ha((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.L())})):c?d.return(c(a)):d.return(!0)})};
function Eo(a,b){a.fb?a.j?(Qh.fa(a.s),a.s=Qh.S(function(){a.o!==b&&(Xe(a,b),a.o=b,a.j=R())},a.fb-(R()-a.j))):(Xe(a,b),a.o=b,a.j=R()):Xe(a,b)}
;var Fo;function Go(){Dn.call(this,{O:{zc:lo,ya:ko,Sb:ho,Pc:io,zb:jo,set:fo},M:Ho(),handleError:yk,za:zk,ia:Io,now:R,oc:Ao,Z:Ul(),wb:"publicytnetworkstatus-online",vb:"publicytnetworkstatus-offline",Xa:!0,Va:.1,cb:sk("potential_esf_error_limit",10),H:P,Ga:!(hm()&&Jo())});this.l=new wh;P("networkless_immediately_drop_all_requests")&&mo();Cn("LogsDatabaseV2")}
t(Go,Dn);function Ko(){var a=B("yt.networklessRequestController.instance");a||(a=new Go,z("yt.networklessRequestController.instance",a),P("networkless_logging")&&rn().then(function(b){a.G=b;Fn(a);a.l.resolve();a.Xa&&Math.random()<=a.Va&&a.G&&qo(a.G);P("networkless_immediately_drop_sw_health_store")&&Lo(a)}));
return a}
Go.prototype.writeThenSend=function(a,b){b||(b={});hm()||(this.i=!1);Dn.prototype.writeThenSend.call(this,a,b)};
Go.prototype.sendThenWrite=function(a,b,c){b||(b={});hm()||(this.i=!1);Dn.prototype.sendThenWrite.call(this,a,b,c)};
Go.prototype.sendAndWrite=function(a,b){b||(b={});hm()||(this.i=!1);Dn.prototype.sendAndWrite.call(this,a,b)};
Go.prototype.awaitInitialization=function(){return this.l.promise};
function Lo(a){var b;w(function(c){if(!a.G)throw b=wm("clearSWHealthLogsDb"),b;return c.return(ro(a.G).catch(function(d){a.handleError(d)}))})}
function Io(a,b,c){P("use_cfr_monitor")&&Mo(a,b);var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(R());c&&0===Object.keys(b).length?uo(a):Zk(a,b)}
function Ho(){Fo||(Fo=new Do({Oc:!0,Ec:!0}));return Fo}
function Mo(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){xo().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){xo().requestComplete(a,!0);d(e,f)}}
function Jo(){return"www.youtube-nocookie.com"!==oc(document.location.toString())}
;var No=!1,Oo=0,Po=0,Qo,Ro=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:No,potentialEsfErrorCounter:Po};z("ytNetworklessLoggingInitializationOptions",Ro);
function So(){var a;w(function(b){switch(b.i){case 1:return v(b,rn(),2);case 2:a=b.j;if(!a||!hm()&&!P("nwl_init_require_datasync_id_killswitch")||!Jo()){b.u(0);break}No=!0;Ro.isNwlInitialized=No;if(!P("use_new_nwl_initialization")){b.u(4);break}return v(b,Ko().awaitInitialization(),5);case 5:return b.return();case 4:return v(b,Cn("LogsDatabaseV2"),6);case 6:if(!(.1>=Math.random())){b.u(7);break}return v(b,lo(a),8);case 8:return v(b,qo(a),7);case 7:To();Uo().L()&&Vo();Uo().aa("publicytnetworkstatus-online",
Vo);Uo().aa("publicytnetworkstatus-offline",Wo);if(!P("networkless_immediately_drop_sw_health_store")){b.u(10);break}return v(b,Xo(),10);case 10:if(P("networkless_immediately_drop_all_requests"))return v(b,mo(),0);b.u(0)}})}
function Yo(a,b){function c(d){var e=Uo().L();if(!Zo()||!d||e&&P("vss_networkless_bypass_write"))$o(a,b);else{var f={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0};fo(f,d).then(function(g){f.id=g;Uo().L()&&ap(f)}).catch(function(g){ap(f);
Uo().L()?yk(g):Ao(g)})}}
b=void 0===b?{}:b;P("skip_is_supported_killswitch")?rn().then(function(d){c(d)}):c(qn())}
function bp(a,b){function c(d){if(Zo()&&d){var e={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(k,m){P("use_cfr_monitor")&&xo().requestComplete(e.url,!0);void 0!==e.id?ko(e.id,d):f=!0;P("vss_network_hint")&&Uo().ha(!0);g(k,m)};
if(P("use_cfr_monitor")){var h=b.onError?b.onError:function(){};
e.options.onError=function(k,m){xo().requestComplete(e.url,!1);h(k,m)}}$o(e.url,e.options);
fo(e,d).then(function(k){e.id=k;f&&ko(e.id,d)}).catch(function(k){Uo().L()?yk(k):Ao(k)})}else $o(a,b)}
b=void 0===b?{}:b;P("skip_is_supported_killswitch")?rn().then(function(d){c(d)}):c(qn())}
function Vo(){var a=qn();if(!a)throw wm("throttleSend");Oo||(Oo=Qh.S(function(){var b;return w(function(c){if(1==c.i)return v(c,ho("NEW",a),2);if(3!=c.i)return b=c.j,b?v(c,ap(b),3):(Wo(),c.return());Oo&&(Oo=0,Vo());c.i=0})},100))}
function Wo(){Qh.fa(Oo);Oo=0}
function ap(a){var b,c,d;return w(function(e){switch(e.i){case 1:b=qn();if(!b)throw c=wm("immediateSend"),c;if(void 0===a.id){e.u(2);break}return v(e,io(a.id,b),3);case 3:(d=e.j)?a=d:zk(Error("The request cannot be found in the database."));case 2:if(cp(a,2592E6)){e.u(4);break}zk(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.u(5);break}return v(e,ko(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=dp(a));var f=a,g,h;if(null==f?0:null==(g=f.options)?
0:null==(h=g.postParams)?0:h.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(R());a=f;if(!a){e.u(0);break}if(!a.skipRetry||void 0===a.id){e.u(8);break}return v(e,ko(a.id,b),8);case 8:$o(a.url,a.options,!!a.skipRetry),e.i=0}})}
function dp(a){var b=qn();if(!b)throw wm("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g,h,k;return w(function(m){switch(m.i){case 1:P("use_cfr_monitor")&&xo().requestComplete(a.url,!1);g=Ln(f);if(!(P("nwl_consider_error_code")&&g||!P("nwl_consider_error_code")&&ep()<=sk("potential_esf_error_limit",10))){m.u(2);break}if(P("skip_checking_network_on_cfr_failure")&&(!P("skip_checking_network_on_cfr_failure")||xo().isEndpointCFR(a.url))){m.u(3);break}return v(m,Uo().Ka(),3);case 3:if(Uo().L()){m.u(2);break}c(e,f);if(!P("nwl_consider_error_code")||void 0===
(null==(h=a)?void 0:h.id)){m.u(6);break}return v(m,jo(a.id,b,!1),6);case 6:return m.return();case 2:if(P("nwl_consider_error_code")&&!g&&ep()>sk("potential_esf_error_limit",10))return m.return();B("ytNetworklessLoggingInitializationOptions")&&Ro.potentialEsfErrorCounter++;Po++;if(void 0===(null==(k=a)?void 0:k.id)){m.u(8);break}return 1>a.sendCount?v(m,jo(a.id,b),12):v(m,ko(a.id,b),8);case 12:Qh.S(function(){Uo().L()&&Vo()},5E3);
case 8:c(e,f),m.i=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){var g;return w(function(h){if(1==h.i)return P("use_cfr_monitor")&&xo().requestComplete(a.url,!0),void 0===(null==(g=a)?void 0:g.id)?h.u(2):v(h,ko(a.id,b),2);P("vss_network_hint")&&Uo().ha(!0);d(e,f);h.i=0})};
return a}
function cp(a,b){a=a.timestamp;return R()-a>=b?!1:!0}
function To(){var a=qn();if(!a)throw wm("retryQueuedRequests");ho("QUEUED",a).then(function(b){b&&!cp(b,12E4)?Qh.S(function(){return w(function(c){if(1==c.i)return void 0===b.id?c.u(2):v(c,jo(b.id,a),2);To();c.i=0})}):Uo().L()&&Vo()})}
function Xo(){var a,b;return w(function(c){a=qn();if(!a)throw b=wm("clearSWHealthLogsDb"),b;return c.return(ro(a).catch(function(d){yk(d)}))})}
function Uo(){if(P("use_new_nwl"))return Ho();Qo||(Qo=new Do({Oc:!0,Ec:!0}));return Qo}
function $o(a,b,c){c&&0===Object.keys(b).length?uo(a):Zk(a,b)}
function Zo(){return B("ytNetworklessLoggingInitializationOptions")?Ro.isNwlInitialized:No}
function ep(){return B("ytNetworklessLoggingInitializationOptions")?Ro.potentialEsfErrorCounter:Po}
;function fp(a){var b=this;this.config_=null;a?this.config_=a:xl()&&(this.config_=yl());Ql(function(){Nl(b)},0,5E3)}
fp.prototype.isReady=function(){!this.config_&&xl()&&(this.config_=yl());return!!this.config_};
function Ol(a,b,c,d){function e(A){A=void 0===A?!1:A;var D;if(d.retry&&"www.youtube-nocookie.com"!=h&&(A||P("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(D=Ll(b,c,m,k)),D)){var F=g.onSuccess,N=g.onFetchSuccess;g.onSuccess=function(O,Q){Ml(D);F(O,Q)};
c.onFetchSuccess=function(O,Q){Ml(D);N(O,Q)}}try{A&&d.retry&&!d.Xb.bypassNetworkless?(g.method="POST",d.Xb.writeThenSend?P("use_new_nwl_wts")?Ko().writeThenSend(u,g):Yo(u,g):P("use_new_nwl_saw")?Ko().sendAndWrite(u,g):bp(u,g)):(g.method="POST",g.postParams||(g.postParams={}),Zk(u,g))}catch(O){if("InvalidAccessError"==O.name)D&&(Ml(D),D=0),zk(Error("An extension is blocking network request."));
else throw O;}D&&Ql(function(){Nl(a)},0,5E3)}
!M("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&zk(new S("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new S("innertube xhrclient not ready",b,c,d);yk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(A,D){if(d.onSuccess)d.onSuccess(D)},
onFetchSuccess:function(A){if(d.onSuccess)d.onSuccess(A)},
onError:function(A,D){if(d.onError)d.onError(D)},
onFetchError:function(A){if(d.onError)d.onError(A)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Lc)&&(h=f);var k=a.config_.Nc||!1,m=Fl(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var q="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},x=a.config_.Mc&&f;x=x&&f.startsWith("Bearer");x||(r.key=a.config_.innertubeApiKey);var u=Lk(""+h+q,r||{},!0);P("use_new_nwl")&&Ko().i||!P("use_new_nwl")&&
Zo()?pn().then(function(A){e(A)}):e(!1)}
;var gp=0,hp=Pc?"webkit":Oc?"moz":Mc?"ms":Lc?"o":"";z("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++gp});var ip={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function xp(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in ip||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.i=a.pageX;this.j=a.pageY}}catch(e){}}
function Wp(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.i=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.j=a.clientY+b}}
xp.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
xp.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
xp.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var qb=y.ytEventsEventsListeners||{};z("ytEventsEventsListeners",qb);var Xp=y.ytEventsEventsCounter||{count:0};z("ytEventsEventsCounter",Xp);
function Yp(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return pb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ta(e[4])&&Ta(d)&&ub(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Zp=fb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function $p(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Yp(a,b,c,d);if(e)return e;e=++Xp.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new xp(h);if(!ff(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new xp(h);
h.currentTarget=a;return c.call(a,h)};
g=xk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Zp()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);qb[e]=[a,b,c,g,d];return e}
function aq(a){a&&("string"==typeof a&&(a=[a]),hb(a,function(b){if(b in qb){var c=qb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Zp()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete qb[b]}}))}
;var bq=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function cq(a){this.F=a;this.j=null;this.o=0;this.v=null;this.s=0;this.l=[];for(a=0;4>a;a++)this.l.push(0);this.m=0;this.K=$p(window,"mousemove",Za(this.P,this));a=Za(this.J,this);"function"===typeof a&&(a=xk(a));this.R=window.setInterval(a,25)}
ab(cq,J);cq.prototype.P=function(a){void 0===a.i&&Wp(a);var b=a.i;void 0===a.j&&Wp(a);this.j=new bf(b,a.j)};
cq.prototype.J=function(){if(this.j){var a=bq();if(0!=this.o){var b=this.v,c=this.j,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.l[this.m]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.l[c]||0;3<=b&&this.F();this.s=d}this.o=a;this.v=this.j;this.m=(this.m+1)%4}};
cq.prototype.C=function(){window.clearInterval(this.R);aq(this.K)};var dq={};
function eq(a){var b=void 0===a?{}:a;a=void 0===b.Tc?!1:b.Tc;b=void 0===b.Fc?!0:b.Fc;if(null==B("_lact",window)){var c=parseInt(M("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;z("_lact",c,window);z("_fact",c,window);-1==c&&fq();$p(document,"keydown",fq);$p(document,"keyup",fq);$p(document,"mousedown",fq);$p(document,"mouseup",fq);a?$p(window,"touchmove",function(){gq("touchmove",200)},{passive:!0}):($p(window,"resize",function(){gq("resize",200)}),b&&$p(window,"scroll",function(){gq("scroll",200)}));
new cq(function(){gq("mouse",100)});
$p(document,"touchstart",fq,{passive:!0});$p(document,"touchend",fq,{passive:!0})}}
function gq(a,b){dq[a]||(dq[a]=!0,Qh.S(function(){fq();dq[a]=!1},b))}
function fq(){null==B("_lact",window)&&eq();var a=Date.now();z("_lact",a,window);-1==B("_fact",window)&&z("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function hq(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var iq=y.ytPubsubPubsubInstance||new L,jq=y.ytPubsubPubsubSubscribedKeys||{},kq=y.ytPubsubPubsubTopicToKeys||{},lq=y.ytPubsubPubsubIsSynchronous||{};function mq(a,b){var c=nq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){jq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{lq[a]?f():Sk(f,0)}catch(g){yk(g)}},void 0);
jq[d]=!0;kq[a]||(kq[a]=[]);kq[a].push(d);return d}return 0}
function oq(a){var b=nq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),hb(a,function(c){b.unsubscribeByKey(c);delete jq[c]}))}
function pq(a,b){var c=nq();c&&c.publish.apply(c,arguments)}
function qq(a){var b=nq();if(b)if(b.clear(a),a)rq(a);else for(var c in kq)rq(c)}
function nq(){return y.ytPubsubPubsubInstance}
function rq(a){kq[a]&&(a=kq[a],hb(a,function(b){jq[b]&&delete jq[b]}),a.length=0)}
L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.Da;L.prototype.publish=L.prototype.oa;L.prototype.clear=L.prototype.clear;z("ytPubsubPubsubInstance",iq);z("ytPubsubPubsubTopicToKeys",kq);z("ytPubsubPubsubIsSynchronous",lq);z("ytPubsubPubsubSubscribedKeys",jq);var sq=y.window;sq.ytExports||(sq.ytExports={logging:{transport:{leaderQueueLength:0,leaderChosen:!1}}});var tq=sk("initial_gel_batch_timeout",2E3),uq=Math.pow(2,16)-1,vq=!1,wq=void 0;function xq(){this.l=this.i=this.j=0}
var yq=new xq,zq=new xq,Aq=!0,Bq=y.ytLoggingTransportGELQueue_||new Map;z("ytLoggingTransportGELQueue_",Bq);var Cq=new Map,Dq=y.ytLoggingTransportGELProtoQueue_||new Map;z("ytLoggingTransportGELProtoQueue_",Dq);var Eq=y.ytLoggingTransportTokensToCttTargetIds_||{};z("ytLoggingTransportTokensToCttTargetIds_",Eq);var Fq=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};z("ytLoggingTransportTokensToJspbCttTargetIds_",Fq);
function Gq(){P("jspb_with_transport_leader")&&!sq.ytExports.logging.transport.leaderChosen&&(vq=sq.ytExports.logging.transport.leaderChosen=!0,document.addEventListener("FLUSH_REQUEST",function(){Hq(void 0,void 0,!0)}))}
function Iq(a,b){Gq();if("log_event"===a.endpoint){Jq(a);var c=Kq(a),d=Bq.get(c)||[];Bq.set(c,d);d.push(a.payload);Lq(b,d,c)}}
function Mq(a,b){Gq();if("log_event"===a.endpoint){Jq(void 0,a);var c=Kq(a,!0);if(P("jspb_with_transport_leader")&&vq){var d=Cq.get(c)||[];Cq.set(c,d);sq.ytExports.logging.transport.leaderQueueLength++;d.push(a.payload);Lq(b,d,c,!0)}else d=Dq.get(c)||[],Dq.set(c,d),a=a.payload.toJSON(),d.push(a),Lq(b,d,c,!0)}}
function Lq(a,b,c,d){d=void 0===d?!1:d;a&&(wq=new a);a=sk("tvhtml5_logging_max_batch")||sk("web_logging_max_batch")||100;var e=R(),f=d?zq.l:yq.l,g=Dq.get(c)||[];P("jspb_with_transport_leader")&&(vq&&b.length+g.length>=a||!vq&&sq.ytExports.logging.transport.leaderQueueLength+b.length>=a)||b.length>=a?Hq({writeThenSend:!0},P("flush_only_full_queue")?c:void 0,d):10<=e-f&&(Nq(d),d?zq.l=e:yq.l=e)}
function Oq(a,b){Gq();if("log_event"===a.endpoint){Jq(a);var c=Kq(a),d=new Map;d.set(c,[a.payload]);b&&(wq=new b);return new tf(function(e,f){wq&&wq.isReady()?Pq(d,e,f,{bypassNetworkless:!0},!0):e()})}}
function Qq(a,b){Gq();if("log_event"===a.endpoint){Jq(void 0,a);var c=Kq(a,!0),d=new Map,e=new Map;P("jspb_with_transport_leader")&&vq?e.set(c,[a.payload]):d.set(c,[a.payload.toJSON()]);b&&(wq=new b);return new tf(function(f){wq&&wq.isReady()?Rq(d,e,f,{bypassNetworkless:!0},!0):f()})}}
function Kq(a,b){var c="";if(a.Fa)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new Mj;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Sd(d,2,Nj,c.playlistId);Fq[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Eq[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Hq(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new tf(function(d,e){c?(Tk(zq.j),Tk(zq.i),zq.i=0):(Tk(yq.j),Tk(yq.i),yq.i=0);if(P("jspb_with_transport_leader")&&!vq&&c)document.dispatchEvent(new CustomEvent("FLUSH_REQUEST")),d();else if(wq&&wq.isReady())if(void 0!==b)if(c){e=new Map;var f=new Map,g=Dq.get(b)||[];e.set(b,g);P("jspb_with_transport_leader")&&(g=Cq.get(b)||[],f.set(b,g));Rq(e,f,d,a);P("jspb_with_transport_leader")&&Cq.delete(b);Dq.delete(b)}else f=new Map,g=Bq.get(b)||[],f.set(b,
g),Pq(f,d,e,a),Bq.delete(b);else c?(Rq(Dq,Cq,d,a),Dq.clear(),P("jspb_with_transport_leader")&&Cq.clear()):(Pq(Bq,d,e,a),Bq.clear());else Nq(c),d()})}
function Nq(a){a=void 0===a?!1:a;if(P("web_gel_timeout_cap")&&(!a&&!yq.i||a&&!zq.i)){var b=Sk(function(){Hq({writeThenSend:!0},void 0,a)},6E4);
a?zq.i=b:yq.i=b}Tk(a?zq.j:yq.j);b=M("LOGGING_BATCH_TIMEOUT",sk("web_gel_debounce_ms",1E4));P("shorten_initial_gel_batch_timeout")&&Aq&&(b=tq);b=Sk(function(){Hq({writeThenSend:!0},void 0,a)},b);
a?zq.j=b:yq.j=b}
function Pq(a,b,c,d,e){var f=wq;d=void 0===d?{}:d;var g=Math.round(R()),h=a.size;a=p(a);for(var k=a.next();!k.done;k=a.next()){var m=p(k.value);k=m.next().value;var q=m.next().value;m=k;k=wb({context:zl(f.config_||yl())});k.events=q;(q=Eq[m])&&Sq(k,m,q);delete Eq[m];m="visitorOnlyApprovedKey"===m;Tq(k,g,m);Uq(d);q=function(){h--;h||b()};
var r=function(){h--;h||b()};
try{Ol(f,"log_event",k,Vq(d,m,q,r,e)),Aq=!1}catch(x){yk(x),c()}}}
function Rq(a,b,c,d,e){var f=wq;d=void 0===d?{}:d;var g=Math.round(R()),h=a.size+b.size,k=new Map([].concat(ia(a),ia(b)));k=p(k);for(var m=k.next();!m.done;m=k.next()){var q=p(m.value).next().value,r=a.get(q),x=b.get(q)||[];m=new Oj;var u=El(f.config_||yl());G(m,Ti,1,u);r=r?Wq(r):[];r=p(r);for(u=r.next();!u.done;u=r.next())Zd(m,3,Ij,u.value);x=p(x);for(r=x.next();!r.done;r=x.next())Zd(m,3,Ij,r.value);(x=Fq[q])&&Xq(m,q,x);delete Fq[q];q="visitorOnlyApprovedKey"===q;Yq(m,g,q);Uq(d);m=be(m);q=Vq(d,q,
function(){sq.ytExports.logging.transport.leaderQueueLength=0;h--;h||c()},function(){sq.ytExports.logging.transport.leaderQueueLength=0;
h--;h||c()},e);
q.headers={"Content-Type":"application/json+protobuf"};q.postBodyFormat="JSPB";q.postBody=m;Ol(f,"log_event","",q);Aq=!1}}
function Uq(a){P("always_send_and_write")&&(a.writeThenSend=!1)}
function Vq(a,b,c,d,e){return{retry:!0,onSuccess:c,onError:d,Xb:a,Fa:b,hq:!!e,headers:{},postBodyFormat:"",postBody:""}}
function Tq(a,b,c){a.requestTimeMs=String(b);P("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=M("EVENT_ID"))&&(c=Zq(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Yq(a,b,c){E(a,2,b);if(!c&&(b=M("EVENT_ID"))){c=Zq();var d=new Lj;E(d,1,b);E(d,2,c);G(a,Lj,5,d)}}
function Zq(){var a=M("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*uq/2));a++;a>uq&&(a=1);pk("BATCH_CLIENT_COUNTER",a);return a}
function Sq(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Xq(a,b,c){if(Od(c,1===Td(c,Nj)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;G(a,Mj,4,c);a=Ud(a,Ti,1)||new Ti;c=Ud(a,Ri,3)||new Ri;var e=new Qi;e.setToken(b);E(e,1,d);Zd(c,12,Qi,e);G(a,Ri,3,c)}
function Wq(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Ij(a[c]))}catch(d){yk(new S("Transport failed to deserialize "+String(a[c])))}return b}
function Jq(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);z("yt.logging.transport.scrapedPayloadsForTesting",c)}}
;var $q=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",$q);function ar(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||R());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=hq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};P("log_sequence_info_on_gel_web")&&d.ba&&(a=e.context,b=d.ba,b={index:br(b),groupKey:b},a.sequence=b,d.Pb&&delete $q[d.ba]);(d.hc?Oq:Iq)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,Fa:d.Fa},c)}
function cr(a){Hq(void 0,void 0,void 0===a?!1:a)}
function br(a){$q[a]=a in $q?$q[a]+1:0;return $q[a]}
;var dr=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",dr);function er(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||R());E(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=hq();d=new Hj;E(d,1,c.timestamp||!isFinite(e)?-1:e);if(P("log_sequence_info_on_gel_web")&&c.ba){e=c.ba;var f=br(e),g=new Gj;E(g,2,f);E(g,1,e);G(d,Gj,3,g);c.Pb&&delete dr[c.ba]}G(a,Hj,33,d);(c.hc?Qq:Mq)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,Fa:c.Fa},b)}
;function fr(a,b){b=void 0===b?{}:b;var c=!1;M("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);er(a,c?null:fp,b)}
;function gr(a,b){var c=new Ij;Xd(c,vj,72,Jj,a);fr(c,b)}
function hr(a,b,c){var d=new Ij;Xd(d,uj,73,Jj,a);c?er(d,c,b):fr(d,b)}
function ir(a,b,c){var d=new Ij;Xd(d,tj,78,Jj,a);c?er(d,c,b):fr(d,b)}
function jr(a,b,c){var d=new Ij;Xd(d,wj,208,Jj,a);c?er(d,c,b):fr(d,b)}
function kr(a,b,c){var d=new Ij;Xd(d,mj,156,Jj,a);c?er(d,c,b):fr(d,b)}
function lr(a,b,c){var d=new Ij;Xd(d,qj,215,Jj,a);c?er(d,c,b):fr(d,b)}
function mr(a,b,c){var d=new Ij;Xd(d,ij,111,Jj,a);c?er(d,c,b):fr(d,b)}
;function em(a,b,c){c=void 0===c?{}:c;if(P("migrate_events_to_ts")){c=void 0===c?{}:c;var d=fp;M("ytLoggingEventsDefaultDisabled",!1)&&fp===fp&&(d=null);ar(a,b,d,c)}else d=fp,M("ytLoggingEventsDefaultDisabled",!1)&&fp==fp&&(d=null),ar(a,b,d,c)}
;var nr=[{ub:function(a){return"Cannot read property '"+a.key+"'"},
bb:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{ub:function(a){return"Cannot call '"+a.key+"'"},
bb:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{ub:function(a){return a.key+" is not defined"},
bb:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var pr={ma:[],la:[{callback:or,weight:500}]};function or(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function qr(){this.la=[];this.ma=[]}
var rr;function sr(){if(!rr){var a=rr=new qr;a.ma.length=0;a.la.length=0;pr.ma&&a.ma.push.apply(a.ma,pr.ma);pr.la&&a.la.push.apply(a.la,pr.la)}return rr}
;var tr=new L;function ur(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=vr(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=vr(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=vr(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function vr(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function wr(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=xr(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=ur(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?xr(e+".ve",f,g,h):0;d+=g;d+=xr(e,a[e],b,c);if(500<d)break}}else c[b]=yr(a),d+=c[b].length;else c[b]=yr(a),d+=c[b].length;return d}
function xr(a,b,c,d){c+="."+a;a=yr(b);d[c]=a;return c.length+a.length}
function yr(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var zr=new Set,Ar=0,Br=0,Cr=0,Dr=[],Er=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function dm(a){Fr(a)}
function Gr(a){Fr(a,"WARNING")}
function Fr(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||M("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||M("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(P("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=Ar)){var m=Dr,q=se(a),r=q.message||"Unknown Error",x=q.name||"UnknownError",u=q.stack||a.j||"Not available";if(u.startsWith(x+": "+r)){var A=u.split("\n");A.shift();u=A.join("\n")}var D=q.lineNumber||"Not available",F=q.fileName||"Not available",N=u,O=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var Q=0;Q<a.args.length&&!(O=wr(a.args[Q],"params."+Q,g,O),500<=O);Q++);else if(a.hasOwnProperty("params")&&
a.params){var ca=a.params;if("object"===typeof a.params)for(var aa in ca){if(ca[aa]){var ja="params."+aa,ma=yr(ca[aa]);g[ja]=ma;O+=ja.length+ma.length;if(500<O)break}}else g.params=yr(ca)}if(m.length)for(var na=0;na<m.length&&!(O=wr(m[na],"params.context."+na,g,O),500<=O);na++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var H={message:r,name:x,lineNumber:D,fileName:F,stack:N,params:g,sampleWeight:1},ra=Number(a.columnNumber);isNaN(ra)||(H.lineNumber=H.lineNumber+
":"+ra);if("IGNORED"===a.level)var la=0;else a:{for(var rd=sr(),sd=p(rd.ma),xa=sd.next();!xa.done;xa=sd.next()){var jp=xa.value;if(H.message&&H.message.match(jp.pq)){la=jp.weight;break a}}for(var kp=p(rd.la),Rj=kp.next();!Rj.done;Rj=kp.next()){var lp=Rj.value;if(lp.callback(H)){la=lp.weight;break a}}la=1}H.sampleWeight=la;for(var mp=p(nr),Sj=mp.next();!Sj.done;Sj=mp.next()){var Tj=Sj.value;if(Tj.bb[H.name])for(var np=p(Tj.bb[H.name]),Uj=np.next();!Uj.done;Uj=np.next()){var op=Uj.value,Ig=H.message.match(op.regexp);
if(Ig){H.params["params.error.original"]=Ig[0];for(var Vj=op.groups,pp={},td=0;td<Vj.length;td++)pp[Vj[td]]=Ig[td+1],H.params["params.error."+Vj[td]]=Ig[td+1];H.message=Tj.ub(pp);break}}}H.params||(H.params={});var qp=sr();H.params["params.errorServiceSignature"]="msg="+qp.ma.length+"&cb="+qp.la.length;H.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(H.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Fb("sample").constructor!==
Bb&&(H.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(H);if(0!==H.sampleWeight&&!zr.has(H.message)){if("ERROR"===h){tr.oa("handleError",H);if(P("record_app_crashed_web")&&0===Cr&&1===H.sampleWeight)if(Cr++,P("errors_via_jspb")){var Wj=new fj;E(Wj,1,1);if(!P("report_client_error_with_app_crash_ks")){var rp=new aj;E(rp,1,H.message);var sp=new bj;G(sp,aj,3,rp);var tp=new cj;G(tp,bj,5,sp);var up=new dj;G(up,cj,9,tp);G(Wj,dj,4,up)}var vp=new Ij;Xd(vp,fj,20,
Jj,Wj);fr(vp)}else{var wp={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};P("report_client_error_with_app_crash_ks")||(wp.systemHealth={crashData:{clientError:{logMessage:{message:H.message}}}});em("appCrashed",wp)}Br++}else"WARNING"===h&&tr.oa("handleWarning",H);if(P("kevlar_gel_error_routing"))a:{var xe=h;if(P("errors_via_jspb")){if(Hr())var yp=void 0;else{var ud=new Yi;E(ud,1,H.stack);H.fileName&&E(ud,4,H.fileName);var Db=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Db.length&&(1!==
Db.length||isNaN(Number(Db[0]))?2!==Db.length||isNaN(Number(Db[0]))||isNaN(Number(Db[1]))||(E(ud,2,Number(Db[0])),E(ud,3,Number(Db[1]))):E(ud,2,Number(Db[0])));var vc=new aj;E(vc,1,H.message);E(vc,3,H.name);E(vc,6,H.sampleWeight);"ERROR"===xe?E(vc,2,2):"WARNING"===xe?E(vc,2,1):E(vc,2,0);var Xj=new Zi;E(Xj,1,!0);Xd(Xj,Yi,3,$i,ud);var Yb=new Vi;E(Yb,3,window.location.href);for(var zp=M("FEXP_EXPERIMENTS",[]),Yj=0;Yj<zp.length;Yj++){var sv=zp[Yj];Bd(Yb);Pd(Yb,5).push(sv)}var Zj=M("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!qk()&&Zj)for(var Ap=p(Object.keys(Zj)),wc=Ap.next();!wc.done;wc=Ap.next()){var Bp=wc.value,ak=new Xi;E(ak,1,Bp);ak.setValue(String(Zj[Bp]));Zd(Yb,4,Xi,ak)}var bk=H.params;if(bk){var Cp=p(Object.keys(bk));for(wc=Cp.next();!wc.done;wc=Cp.next()){var Dp=wc.value,ck=new Xi;E(ck,1,"client."+Dp);ck.setValue(String(bk[Dp]));Zd(Yb,4,Xi,ck)}}var Ep=M("SERVER_NAME"),Fp=M("SERVER_VERSION");if(Ep&&Fp){var dk=new Xi;E(dk,1,"server.name");dk.setValue(Ep);Zd(Yb,4,Xi,dk);var ek=new Xi;E(ek,1,"server.version");
ek.setValue(Fp);Zd(Yb,4,Xi,ek)}var Jg=new bj;G(Jg,Vi,1,Yb);G(Jg,Zi,2,Xj);G(Jg,aj,3,vc);yp=Jg}var Gp=yp;if(!Gp)break a;var Hp=new Ij;Xd(Hp,bj,163,Jj,Gp);fr(Hp)}else{if(Hr())var Ip=void 0;else{var ye={stackTrace:H.stack};H.fileName&&(ye.filename=H.fileName);var Eb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Eb.length&&(1!==Eb.length||isNaN(Number(Eb[0]))?2!==Eb.length||isNaN(Number(Eb[0]))||isNaN(Number(Eb[1]))||(ye.lineNumber=Number(Eb[0]),ye.columnNumber=Number(Eb[1])):ye.lineNumber=
Number(Eb[0]));var fk={level:"ERROR_LEVEL_UNKNOWN",message:H.message,errorClassName:H.name,sampleWeight:H.sampleWeight};"ERROR"===xe?fk.level="ERROR_LEVEL_ERROR":"WARNING"===xe&&(fk.level="ERROR_LEVEL_WARNNING");var tv={isObfuscated:!0,browserStackInfo:ye},vd={pageUrl:window.location.href,kvPairs:[]};M("FEXP_EXPERIMENTS")&&(vd.experimentIds=M("FEXP_EXPERIMENTS"));var gk=M("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!qk()&&gk)for(var Jp=p(Object.keys(gk)),xc=Jp.next();!xc.done;xc=Jp.next()){var Kp=
xc.value;vd.kvPairs.push({key:Kp,value:String(gk[Kp])})}var hk=H.params;if(hk){var Lp=p(Object.keys(hk));for(xc=Lp.next();!xc.done;xc=Lp.next()){var Mp=xc.value;vd.kvPairs.push({key:"client."+Mp,value:String(hk[Mp])})}}var Np=M("SERVER_NAME"),Op=M("SERVER_VERSION");Np&&Op&&(vd.kvPairs.push({key:"server.name",value:Np}),vd.kvPairs.push({key:"server.version",value:Op}));Ip={errorMetadata:vd,stackTrace:tv,logMessage:fk}}var Pp=Ip;if(!Pp)break a;em("clientError",Pp)}if("ERROR"===xe||P("errors_flush_gel_always_killswitch"))b:if(P("migrate_events_to_ts"))c:{if(P("web_fp_via_jspb")&&
(cr(!0),!P("web_fp_via_jspb_and_json")))break c;cr()}else{if(P("web_fp_via_jspb")&&(cr(!0),!P("web_fp_via_jspb_and_json")))break b;cr()}}if(!P("suppress_error_204_logging")){var ze=H.params||{},Zb={urlParams:{a:"logerror",t:"jserror",type:H.name,msg:H.message.substr(0,250),line:H.lineNumber,level:h,"client.name":ze.name},postParams:{url:M("PAGE_NAME",window.location.href),file:H.fileName},method:"POST"};ze.version&&(Zb["client.version"]=ze.version);if(Zb.postParams){H.stack&&(Zb.postParams.stack=
H.stack);for(var Qp=p(Object.keys(ze)),ik=Qp.next();!ik.done;ik=Qp.next()){var Rp=ik.value;Zb.postParams["client."+Rp]=ze[Rp]}var jk=M("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(jk)for(var Sp=p(Object.keys(jk)),kk=Sp.next();!kk.done;kk=Sp.next()){var Tp=kk.value;Zb.postParams[Tp]=jk[Tp]}var Up=M("SERVER_NAME"),Vp=M("SERVER_VERSION");Up&&Vp&&(Zb.postParams["server.name"]=Up,Zb.postParams["server.version"]=Vp)}Zk(M("ECATCHER_REPORT_HOST","")+"/error_204",Zb)}try{zr.add(H.message)}catch(Uw){}Ar++}}}}
function Hr(){for(var a=p(Er),b=a.next();!b.done;b=a.next())if(Wl(b.value.toLowerCase()))return!0;return!1}
function Ir(a){var b=Ma.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ia(b))}
;function Jr(){this.register=new Map}
function Kr(a){a=p(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.sq("ABORTED")}
Jr.prototype.clear=function(){Kr(this);this.register.clear()};
var Lr=new Jr;var Mr=Date.now().toString();
function Nr(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Mr)for(a=1,b=0;b<Mr.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Mr.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Or=y.ytLoggingDocDocumentNonce_;Or||(Or=Nr(),z("ytLoggingDocDocumentNonce_",Or));var Pr=Or;var Qr={wh:0,ie:1,se:2,ol:3,yh:4,Bp:5,em:6,Kn:7,en:8,yn:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function Rr(a){this.i=a}
function Sr(a){return new Rr({trackingParams:a})}
Rr.prototype.getAsJson=function(){var a={};void 0!==this.i.trackingParams?a.trackingParams=this.i.trackingParams:(a.veType=this.i.veType,void 0!==this.i.veCounter&&(a.veCounter=this.i.veCounter),void 0!==this.i.elementIndex&&(a.elementIndex=this.i.elementIndex));void 0!==this.i.dataElement&&(a.dataElement=this.i.dataElement.getAsJson());void 0!==this.i.youtubeData&&(a.youtubeData=this.i.youtubeData);return a};
Rr.prototype.getAsJspb=function(){var a=new hj;void 0!==this.i.trackingParams?E(a,1,this.i.trackingParams):(void 0!==this.i.veType&&E(a,2,this.i.veType),void 0!==this.i.veCounter&&E(a,6,this.i.veCounter),void 0!==this.i.elementIndex&&E(a,3,this.i.elementIndex));if(void 0!==this.i.dataElement){var b=this.i.dataElement.getAsJspb();G(a,hj,7,b)}void 0!==this.i.youtubeData&&G(a,Fi,8,this.i.jspbYoutubeData);return a};
Rr.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Rr.prototype.isClientVe=function(){return!this.i.trackingParams&&!!this.i.veType};function Tr(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function Ur(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Vr(a){return M(Ur(void 0===a?0:a))}
z("yt_logging_screen.getRootVeType",Vr);function Wr(a){return(a=Vr(void 0===a?0:a))?new Rr({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function Xr(){var a=M("csn-to-ctt-auth-info");a||(a={},pk("csn-to-ctt-auth-info",a));return a}
function Yr(a){a=M(Tr(void 0===a?0:a));if(!a&&!M("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
z("yt_logging_screen.getCurrentCsn",Yr);function Zr(a,b,c){var d=Xr();(c=Yr(c))&&delete d[c];b&&(d[a]=b)}
function $r(a){return Xr()[a]}
z("yt_logging_screen.getCttAuthInfo",$r);
function as(a,b,c,d){c=void 0===c?0:c;if(a!==M(Tr(c))||b!==M(Ur(c)))if(Zr(a,d,c),pk(Tr(c),a),pk(Ur(c),b),b=function(){setTimeout(function(){if(a)if(P("web_time_via_jspb")){var e=new ij;E(e,1,Pr);E(e,2,a);P("use_default_heartbeat_client")?mr(e):mr(e,void 0,fp)}else e={clientDocumentNonce:Pr,clientScreenNonce:a},P("use_default_heartbeat_client")?em("foregroundHeartbeatScreenAssociated",e):ar("foregroundHeartbeatScreenAssociated",e,fp)},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
z("yt_logging_screen.setCurrentScreen",as);var bs=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};z("yt.msgs_",bs);function cs(a){Qj(bs,arguments)}
;var ds={he:3611,td:27686,ud:85013,vd:23462,xd:42016,yd:62407,zd:26926,wd:43781,Ad:51236,Bd:79148,Cd:50160,Dd:77504,Pd:153587,Qd:87907,Rd:18630,Sd:54445,Td:80935,Ud:152172,Vd:105675,Wd:150723,Xd:37521,Yd:147285,Zd:47786,ae:98349,be:123695,ce:6827,de:29434,ee:7282,ge:124448,ke:32276,je:76278,le:147868,me:147869,ne:93911,oe:106531,pe:27259,qe:27262,re:27263,te:21759,ue:27107,we:62936,xe:49568,ye:38408,ze:80637,Ae:68727,Be:68728,Ce:80353,De:80356,Ee:74610,Fe:45707,Ge:83962,He:83970,Ie:46713,Je:89711,
Ke:74612,Le:93265,Me:74611,Ne:131380,Pe:128979,Qe:139311,Re:128978,Oe:131391,Se:105350,Ue:139312,Ve:134800,Te:131392,Xe:113533,Ye:93252,Ze:99357,bf:94521,cf:114252,df:113532,ef:94522,af:94583,ff:88E3,gf:139580,hf:93253,jf:93254,kf:94387,lf:94388,mf:93255,nf:97424,We:72502,pf:110111,qf:76019,sf:117092,tf:117093,rf:89431,uf:110466,vf:77240,wf:60508,xf:148123,yf:148124,zf:137401,Af:137402,Bf:137046,Cf:73393,Df:113534,Ef:92098,Ff:131381,Gf:84517,Hf:83759,If:80357,Jf:86113,Kf:72598,Lf:72733,Mf:107349,
Nf:124275,Of:118203,Pf:133275,Qf:152569,Rf:133274,Sf:133272,Tf:133273,Uf:133276,Vf:144507,Wf:143247,Xf:143248,Yf:143249,Zf:143250,ag:143251,cg:144401,eg:117431,dg:133797,fg:153964,gg:128572,hg:133405,ig:117429,jg:117430,kg:117432,lg:120080,mg:117259,ng:121692,og:145656,pg:145655,qg:145653,rg:145654,sg:145657,tg:132972,ug:133051,vg:133658,wg:132971,xg:97615,zg:143359,yg:143356,Bg:143361,Ag:143358,Dg:143360,Cg:143357,Eg:142303,Fg:143353,Gg:143354,Hg:144479,Ig:143355,Jg:31402,Lg:133624,Mg:146477,Ng:133623,
Og:133622,Kg:133621,Pg:84774,Qg:95117,Rg:150497,Sg:98930,Tg:98931,Ug:98932,Vg:43347,Wg:129889,Xg:149123,Yg:45474,Zg:100352,ah:84758,bh:98443,dh:117985,eh:74613,fh:74614,gh:64502,hh:136032,ih:74615,jh:74616,kh:122224,lh:74617,mh:77820,nh:74618,oh:93278,ph:93274,qh:93275,rh:93276,sh:22110,th:29433,uh:133798,vh:132295,xh:120541,zh:82047,Ah:113550,Bh:75836,Ch:75837,Dh:42352,Eh:84512,Fh:76065,Gh:75989,Lh:16623,Mh:32594,Nh:27240,Oh:32633,Ph:74858,Rh:3945,Qh:16989,Sh:45520,Th:25488,Uh:25492,Vh:25494,Wh:55760,
Xh:14057,Yh:18451,Zh:57204,ai:57203,bi:17897,ci:57205,di:18198,fi:17898,gi:17909,hi:43980,ii:46220,ji:11721,ki:147994,li:49954,mi:96369,ni:3854,oi:151633,ri:56251,si:25624,ti:152036,Li:16906,Mi:99999,Ni:68172,Oi:27068,Pi:47973,Qi:72773,Ri:26970,Si:26971,Ti:96805,Ui:17752,Vi:73233,Wi:109512,Xi:22256,Yi:14115,Zi:22696,aj:89278,bj:89277,cj:109513,dj:43278,ej:43459,fj:43464,gj:89279,hj:43717,ij:55764,jj:22255,kj:147912,lj:89281,mj:40963,nj:43277,oj:43442,pj:91824,qj:120137,rj:96367,sj:36850,tj:72694,
uj:37414,vj:36851,xj:124863,wj:121343,yj:73491,zj:54473,Aj:43375,Bj:46674,Cj:143815,Dj:139095,Ej:144402,Fj:149968,Gj:149969,Hj:32473,Ij:72901,Jj:72906,Kj:50947,Lj:50612,Mj:50613,Nj:50942,Oj:84938,Pj:84943,Qj:84939,Rj:84941,Sj:84944,Tj:84940,Uj:84942,Vj:35585,Wj:51926,Xj:79983,Yj:63238,Zj:18921,ak:63241,bk:57893,ck:41182,dk:135732,ek:33424,fk:22207,gk:42993,hk:36229,ik:22206,jk:22205,kk:18993,lk:19001,mk:18990,nk:18991,pk:18997,qk:18725,rk:19003,sk:36874,tk:44763,uk:33427,vk:67793,wk:22182,xk:37091,
yk:34650,zk:50617,Ak:47261,Bk:22287,Ck:25144,Dk:97917,Ek:62397,Fk:150871,Gk:150874,Hk:125598,Ik:137935,Jk:36961,Kk:108035,Lk:27426,Mk:27857,Nk:27846,Ok:27854,Pk:69692,Qk:61411,Rk:39299,Sk:38696,Tk:62520,Uk:36382,Vk:108701,Wk:50663,Xk:36387,Yk:14908,Zk:37533,al:105443,bl:61635,dl:62274,fl:133818,il:65702,jl:65703,kl:65701,ll:76256,ml:37671,nl:49953,pl:36216,ql:28237,rl:39553,sl:29222,ul:26107,vl:38050,wl:26108,yl:120745,xl:26109,zl:26110,Al:66881,Bl:28236,Cl:14586,Dl:57929,El:74723,Fl:44098,Gl:44099,
Jl:23528,Kl:61699,Hl:134104,Il:134103,Ll:59149,Ml:101951,Nl:97346,Ol:118051,Pl:95102,Ql:64882,Rl:119505,Sl:63595,Tl:63349,Ul:95101,Vl:75240,Wl:27039,Xl:68823,Yl:21537,Zl:83464,am:75707,bm:83113,cm:101952,dm:101953,fm:79610,gm:125755,hm:24402,im:24400,jm:32925,km:57173,lm:122502,mm:145268,nm:138480,om:64423,pm:64424,qm:33986,rm:100828,sm:129089,tm:21409,xm:135155,ym:135156,zm:135157,Am:135158,Bm:135159,Cm:135160,Dm:135161,Em:135162,Fm:135163,Gm:135164,Hm:135165,Im:135166,um:11070,vm:11074,wm:17880,
Jm:14001,Lm:30709,Mm:30707,Nm:30711,Om:30710,Pm:30708,Km:26984,Qm:146143,Rm:63648,Sm:63649,Tm:51879,Um:111059,Vm:5754,Wm:20445,Xm:151308,Ym:151152,an:130975,Zm:130976,bn:110386,cn:113746,dn:66557,fn:17310,gn:28631,hn:21589,jn:154946,kn:68012,ln:60480,mn:138664,nn:141121,pn:31571,qn:141978,rn:150105,sn:150106,tn:150107,un:150108,vn:76980,wn:41577,xn:45469,zn:38669,An:13768,Bn:13777,Cn:141842,Dn:62985,En:4724,Fn:59369,Gn:43927,Hn:43928,In:12924,Jn:100355,Mn:56219,Nn:27669,On:10337,Ln:47896,Pn:122629,
Rn:139723,Qn:139722,Sn:121258,Tn:107598,Un:127991,Vn:96639,Wn:107536,Xn:130169,Yn:96661,Zn:145188,ao:96658,bo:116646,co:121122,eo:96660,fo:127738,ho:127083,jo:147842,ko:104443,lo:96659,mo:147595,no:106442,oo:134840,po:63667,qo:63668,ro:63669,so:130686,to:147036,uo:78314,vo:147799,wo:148649,xo:55761,yo:127098,zo:134841,Ao:96368,Bo:67374,Co:48992,Do:146176,Eo:49956,Fo:31961,Go:26388,Ho:23811,Io:5E4,Jo:126250,Ko:96370,Lo:47355,Mo:47356,No:37935,Oo:45521,Po:21760,Qo:83769,Ro:49977,So:49974,To:93497,Uo:93498,
Vo:34325,Wo:140759,Xo:115803,Yo:123707,Zo:100081,ap:35309,bp:68314,cp:25602,ep:100339,fp:143516,gp:59018,hp:18248,ip:50625,jp:9729,kp:37168,lp:37169,mp:21667,np:16749,qp:18635,rp:39305,sp:18046,tp:53969,up:8213,vp:93926,wp:102852,xp:110099,yp:22678,zp:69076,Ap:137575,Cp:139224,Dp:100856,Ep:154430,Fp:17736,Gp:3832,Hp:147111,Ip:55759,Jp:64031,Pp:93044,Qp:93045,Rp:34388,Sp:17657,Tp:17655,Up:39579,Vp:39578,Wp:77448,Xp:8196,Yp:11357,Zp:69877,aq:8197,bq:82039};function es(){var a=vb(fs),b;return(new tf(function(c,d){a.onSuccess=function(e){Rk(e)?c(new gs(e)):d(new hs("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new hs("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new hs("Request timed out","net.timeout",e))};
b=Zk("//googleads.g.doubleclick.net/pagead/id",a)})).gb(function(c){c instanceof Af&&b.abort();
return yf(c)})}
function hs(a,b,c){cb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
t(hs,cb);function gs(a){this.xhr=a}
;function is(){this.i=0;this.ja=null}
is.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.ja))&&"function"===typeof a.then?a:js(a):2===this.i&&b?(a=b.call(c,this.ja))&&"function"===typeof a.then?a:ks(a):this};
is.prototype.getValue=function(){return this.ja};
is.prototype.$goog_Thenable=!0;function ks(a){var b=new is;a=void 0===a?null:a;b.i=2;b.ja=void 0===a?null:a;return b}
function js(a){var b=new is;a=void 0===a?null:a;b.i=1;b.ja=void 0===a?null:a;return b}
;function ls(a,b){return{method:void 0===b?"POST":b,mode:Mk(a)?"same-origin":"cors",credentials:Mk(a)?"same-origin":"include"}}
;function ms(){return ng()||Vl&&Wl("applewebkit")&&!Wl("version")&&(!Wl("safari")||Wl("gsa/"))||Qc&&Wl("version/")?!0:M("EOM_VISITOR_DATA")?!1:!0}
;function ns(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in Rh)if(Rh[c]==b.embeddedPlayerMode){b=Rh[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function os(a){cb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof ps;this.isTimeout=a instanceof hs&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Af}
t(os,cb);os.prototype.name="BiscottiError";function ps(){cb.call(this,"Biscotti ID is missing from server")}
t(ps,cb);ps.prototype.name="BiscottiMissingError";var fs={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},qs=null;
function Bk(){if(P("disable_biscotti_fetch_entirely_for_all_web_clients"))return yf(Error("Biscotti id fetching has been disabled entirely."));if(!ms())return yf(Error("User has not consented - not fetching biscotti id."));var a=M("PLAYER_VARS",{});if("1"==tb(a))return yf(Error("Biscotti ID is not available in private embed mode"));if(ns(a))return yf(Error("Biscotti id fetching has been disabled for pfl."));qs||(qs=es().then(rs).gb(function(b){return ss(2,b)}));
return qs}
function rs(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new ps;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new ps;a=a.id;Ck(a);qs=js(a);ts(18E5,2);return a}
function ss(a,b){b=new os(b);Ck("");qs=ks(b);0<a&&ts(12E4,a-1);throw b;}
function ts(a,b){Sk(function(){es().then(rs,function(c){return ss(b,c)}).gb(eb)},a)}
function us(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Bk()}catch(b){return yf(b)}}
;function vs(a){if("1"!=tb(M("PLAYER_VARS",{}))){a&&Ak();try{us().then(function(){},function(){}),Sk(vs,18E5)}catch(b){yk(b)}}}
;function ws(){this.ld=!0}
function xs(a){var b={},c=pg([]);c&&(b.Authorization=c,c=a=null==a?void 0:a.sessionIndex,void 0===c&&(c=Number(M("SESSION_INDEX",0)),c=isNaN(c)?0:c),P("voice_search_auth_header_removal")||(b["X-Goog-AuthUser"]=c),"INNERTUBE_HOST_OVERRIDE"in ok||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in ok&&(b["X-Goog-PageId"]=M("DELEGATED_SESSION_ID")));return b}
;var ys=Symbol("injectionDeps");function zs(a){this.name=a}
zs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function As(){this.key=Bs}
function Cs(){this.providers=new Map;this.i=new Map}
Cs.prototype.resolve=function(a){return a instanceof As?Ds(this,a.key,[],!0):Ds(this,a,[])};
function Ds(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.providers.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.providers.get(b);c.push(b);if(d.nc)var e=d.nc;else if(d.sd)e=d[ys]?Es(a,d[ys],c):[],e=d.sd.apply(d,ia(e));else if(d.mc){e=d.mc;var f=e[ys]?Es(a,e[ys],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.zq||a.i.set(b,e);
return e}
function Es(a,b,c){return b?b.map(function(d){return d instanceof As?Ds(a,d.key,c,!0):Ds(a,d,c)}):[]}
;var Fs;var Gs={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var Hs=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Is(){var a=void 0===a?window.location.href:a;if(P("kevlar_disable_theme_param"))return null;mc(nc(5,a));try{var b=Kk(a).theme;return Hs.get(b)||null}catch(c){}return null}
;function Js(){this.i={};if(this.j=jl()){var a=lg.get("CONSISTENCY",void 0);a&&Ks(this,{encryptedTokenJarContents:a})}}
Js.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.ga.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=p(b);for(c=e.next();!c.done;c=e.next())delete this.i[c.value.encryptedTokenJarContents];Ks(this,a)}};
function Ks(a,b){if(b.encryptedTokenJarContents&&(a.i[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.i[b.encryptedTokenJarContents]},1E3*c);
a.j&&il("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Ls=window.location.hostname.split(".").slice(-2).join(".");function Ms(){var a=M("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===M("INNERTUBE_CLIENT_NAME")&&(this.i=Ns(this))&&(a=this.i.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.j=void 0)}
var Os;Ms.getInstance=function(){Os=B("yt.clientLocationService.instance");Os||(Os=new Ms,z("yt.clientLocationService.instance",Os));return Os};
Ms.prototype.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.j?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.j.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.j.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.j.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
Ms.prototype.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.j=void 0,"TVHTML5"===M("INNERTUBE_CLIENT_NAME")?(this.i=Ns(this))&&this.i.set("yt-location-playability-token",a,15552E3):il("YT_CL",JSON.stringify({loctok:a}),15552E3,Ls,!0))};
function Ns(a){return void 0===a.i?new Hl("yt-client-location"):a.i}
Ms.prototype.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition)||!P("web_enable_browser_geolocation_api")&&!P("enable_handoff_location_2fa_on_mweb"))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;P("enable_handoff_location_2fa_on_mweb")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.j=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
Ms.prototype.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Ps(a,b){var c;if((null==(c=a.signalServiceEndpoint)?0:c.signal)&&b.La&&(c=b.La[a.signalServiceEndpoint.signal]))return c();var d;if((null==(d=a.continuationCommand)?0:d.request)&&b.Bc&&(d=b.Bc[a.continuationCommand.request]))return d();for(var e in a)if(b.Lb[e]&&(a=b.Lb[e]))return a()}
;function Qs(a){return function(){return new a}}
;var Rs={},Ss=(Rs.WEB_UNPLUGGED="^unplugged/",Rs.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Rs.WEB_UNPLUGGED_OPS="^unplugged/",Rs.WEB_UNPLUGGED_PUBLIC="^unplugged/",Rs.WEB_CREATOR="^creator/",Rs.WEB_KIDS="^kids/",Rs.WEB_EXPERIMENTS="^experiments/",Rs.WEB_MUSIC="^music/",Rs.WEB_REMIX="^music/",Rs.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Rs.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Rs);
function Ts(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Ss[b];if(c){var d=new RegExp(c),e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Ss).forEach(function(g){var h=p(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Us(){}
Us.prototype.o=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Gs:c;var d=a.clickTrackingParams,e=this.m,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=M("INNERTUBE_CONTEXT");if(g){g=wb(g);P("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=M("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;ll.getInstance();var m="USER_INTERFACE_THEME_LIGHT";ol(165)?m="USER_INTERFACE_THEME_DARK":ol(174)?m="USER_INTERFACE_THEME_LIGHT":!P("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:Is()||m;h.userInterfaceTheme=k;if(!f){if(k=
vl())h.connectionType=k;P("web_log_effective_connection_type")&&(k=wl())&&(g.client.effectiveConnectionType=k)}var q;if(P("web_log_memory_total_kbytes")&&(null==(q=y.navigator)?0:q.deviceMemory)){var r;q=null==(r=y.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*q}r=Kk(y.location.href);!P("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:y.location.href},P("kevlar_woffle")&&
gl.i&&(r=gl.i,h.mainAppWebInfo.pwaInstallabilityStatus=!r.i&&r.j?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=hl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!P("web_lr_app_quality_killswitch")&&(r=M("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=M("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||
{},{certificationScope:r}));if(!P("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var x=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(ma){}x=void 0}x&&(h.timeZone=x)}(x=tk())?h.experimentsToken=x:delete h.experimentsToken;x=uk();Js.i||(Js.i=new Js);h=Js.i.i;r=[];q=0;for(var u in h)r[q++]=h[u];g.request=Object.assign({},g.request,{internalExperimentFlags:x,consistencyTokenJars:r});!P("web_prequest_context_killswitch")&&(u=M("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&
(g.request.externalPrequestContext=u);x=ll.getInstance();u=ol(58);x=x.get("gsml","");g.user=Object.assign({},g.user);u&&(g.user.enableSafetyMode=u);x&&(g.user.lockedSafetyMode=!0);P("warm_op_csn_cleanup")?e&&(f=Yr())&&(g.clientScreenNonce=f):!f&&(f=Yr())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;P("web_enable_client_location_service")&&Ms.getInstance().setLocationOnInnerTubeContext(g);try{var A=Nk(),D=A.bid;delete A.bid;
g.adSignalsInfo={params:[],bid:D};var F=p(Object.entries(A));for(var N=F.next();!N.done;N=F.next()){var O=p(N.value),Q=O.next().value,ca=O.next().value;A=Q;D=ca;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:A,value:""+D})}}catch(ma){Fr(ma)}F=g}else Fr(Error("Error: No InnerTubeContext shell provided in ytconfig.")),F={};F={context:F};if(N=this.i(a)){this.j(F,N,b);var aa;b="/youtubei/v1/"+Ts(this.l());var ja;(N=null==(aa=a.commandMetadata)?void 0:null==(ja=aa.webCommandMetadata)?void 0:ja.apiUrl)&&
(b=N);aa=b;(ja=M("INNERTUBE_HOST_OVERRIDE"))&&(aa=String(ja)+String(pc(aa)));ja={};ja.key=M("INNERTUBE_API_KEY");P("json_condensed_response")&&(ja.prettyPrint="false");aa=Lk(aa,ja||{},!1);a=P("kevlar_response_command_processor_page")?Object.assign({},{command:a},void 0):Object.assign({},void 0);a={input:aa,Ba:ls(aa),ga:F,config:a};a.config.Ra?a.config.Ra.identity=c:a.config.Ra={identity:c};return a}Fr(new S("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(Us.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Vs(){}
t(Vs,Us);Vs.prototype.o=function(){return{input:"/getDatasyncIdsEndpoint",Ba:ls("/getDatasyncIdsEndpoint","GET"),ga:{}}};
Vs.prototype.l=function(){return[]};
Vs.prototype.i=function(){};
Vs.prototype.j=function(){};var Ws={},Xs=(Ws.GET_DATASYNC_IDS=Qs(Vs),Ws);function Ys(a){var b=Ma.apply(1,arguments);if(!Zs(a)||b.some(function(d){return!Zs(d)}))throw Error("Only objects may be merged.");
b=p(b);for(var c=b.next();!c.done;c=b.next())$s(a,c.value);return a}
function $s(a,b){for(var c in b)if(Zs(b[c])){if(c in a&&!Zs(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});$s(a[c],b[c])}else if(at(b[c])){if(c in a&&!at(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);bt(a[c],b[c])}else a[c]=b[c];return a}
function bt(a,b){b=p(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Zs(c)?a.push($s({},c)):at(c)?a.push(bt([],c)):a.push(c);return a}
function Zs(a){return"object"===typeof a&&!Array.isArray(a)}
function at(a){return"object"===typeof a&&Array.isArray(a)}
;function ct(a,b){Mn.call(this,1,arguments);this.timer=b}
t(ct,Mn);var dt=new Nn("aft-recorded",ct);var et=window;function ft(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var T=et.performance||et.mozPerformance||et.msPerformance||et.webkitPerformance||new ft;var gt=!1,ht={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Za(T.clearResourceTimings||T.webkitClearResourceTimings||T.mozClearResourceTimings||T.msClearResourceTimings||T.oClearResourceTimings||eb,T);function jt(a){var b=kt(a);if(b.aft)return b.aft;a=M((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function lt(){var a;if(P("csi_use_performance_navigation_timing")||P("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==T?void 0:null==(a=T.getEntriesByType)?void 0:null==(b=a.call(T,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=mt(e.requestStart),e.responseEnd=mt(e.responseEnd),e.redirectStart=mt(e.redirectStart),e.redirectEnd=mt(e.redirectEnd),e.domainLookupEnd=mt(e.domainLookupEnd),e.connectStart=mt(e.connectStart),e.connectEnd=
mt(e.connectEnd),e.responseStart=mt(e.responseStart),e.secureConnectionStart=mt(e.secureConnectionStart),e.domainLookupStart=mt(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=T.timing}else a=T.timing;return a}
function nt(){return(P("csi_use_time_origin")||P("csi_use_time_origin_tvhtml5"))&&T.timeOrigin?Math.floor(T.timeOrigin):T.timing.navigationStart}
function mt(a){return Math.round(nt()+a)}
function ot(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},z("ytcsi."+(a||"")+"data_",b));return b}
function pt(a){a=ot(a);a.info||(a.info={});return a.info}
function kt(a){a=ot(a);a.tick||(a.tick={});return a.tick}
function qt(a){a=ot(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function rt(a){a=qt(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function st(a){var b=ot(a).nonce;b||(b=Nr(),ot(a).nonce=b);return b}
function tt(a){var b=kt(a||""),c=jt(a);c&&!gt&&(Sn(dt,new ct(Math.round(c-b._start),a)),gt=!0)}
function ut(a,b){for(var c=p(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!ut(a[d],b[d]))return!1;return!0}
;function vt(){if(T.getEntriesByType){var a=T.getEntriesByType("paint");if(a=lb(a,function(b){return"first-paint"===b.name}))return mt(a.startTime)}a=T.timing;
return a.Qc?Math.max(0,a.Qc):0}
;function wt(){var a=B("ytcsi.debug");a||(a=[],z("ytcsi.debug",a),z("ytcsi.reference",{}));return a}
function xt(a){a=a||"";var b=B("ytcsi.reference");b||(wt(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=wt(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var U={},zt=(U.auto_search="LATENCY_ACTION_AUTO_SEARCH",U.ad_to_ad="LATENCY_ACTION_AD_TO_AD",U.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",U["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",U.app_startup="LATENCY_ACTION_APP_STARTUP",U["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",U["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",U["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",U["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",U.browse="LATENCY_ACTION_BROWSE",
U.cast_splash="LATENCY_ACTION_CAST_SPLASH",U.channels="LATENCY_ACTION_CHANNELS",U.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",U["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",U["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",U["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",U["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",U["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",U["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",
U["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",U["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",U["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",U["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",U["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",U["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",U.chips="LATENCY_ACTION_CHIPS",U["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",
U["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",U["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",U.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",U.embed="LATENCY_ACTION_EMBED",U.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",U.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",U.explore="LATENCY_ACTION_EXPLORE",U.home="LATENCY_ACTION_HOME",U.library="LATENCY_ACTION_LIBRARY",U.live="LATENCY_ACTION_LIVE",
U.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",U.onboarding="LATENCY_ACTION_ONBOARDING",U.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",U.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",U.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",U.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",U["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",U["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",U.prebuffer="LATENCY_ACTION_PREBUFFER",U.prefetch=
"LATENCY_ACTION_PREFETCH",U.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",U.profile_switcher="LATENCY_ACTION_LOGIN",U.reel_watch="LATENCY_ACTION_REEL_WATCH",U.results="LATENCY_ACTION_RESULTS",U.search_ui="LATENCY_ACTION_SEARCH_UI",U.search_suggest="LATENCY_ACTION_SUGGEST",U.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",U.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",U.seek="LATENCY_ACTION_PLAYER_SEEK",U.settings="LATENCY_ACTION_SETTINGS",U.store="LATENCY_ACTION_STORE",U.tenx="LATENCY_ACTION_TENX",
U.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",U.watch="LATENCY_ACTION_WATCH",U.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",U["watch,watch7"]="LATENCY_ACTION_WATCH",U["watch,watch7_html5"]="LATENCY_ACTION_WATCH",U["watch,watch7ad"]="LATENCY_ACTION_WATCH",U["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",U.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",U.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",U["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",U["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",
U["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",U["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",U["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",U["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",U["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",U["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",U["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",U.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",
U.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",U.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",U),V={},At=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",
V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",V.is_continuation="isContinuation",V.is_nav="isNavigation",V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",
V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt="playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",
V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs="tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",
V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),Bt="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
Ct={},Dt=(Ct.ccs="CANARY_STATE_",Ct.mver="MEASUREMENT_VERSION_",Ct.pis="PLAYER_INITIALIZED_STATE_",Ct.yt_pt="LATENCY_PLAYER_",Ct.pa="LATENCY_ACTION_",Ct.ctop="TOP_ENTITY_TYPE_",Ct.yt_vst="VIDEO_STREAM_TYPE_",Ct),Et="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Ft(a){return zt[a]||"LATENCY_ACTION_UNKNOWN"}
function Gt(a,b,c){c=qt(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in At){c=At[a];0<=gb(Bt,c)&&(b=!!b);a in Dt&&"string"===typeof b&&(b=Dt[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Ys({},d)}0<=gb(Et,a)||Gr(new S("Unknown label logged with GEL CSI",a))}
;var W={LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,
LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,
LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,
LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,
LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,
LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,
LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,
LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,
LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,
LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,
LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_WATCH_UI:181,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,
LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,
LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_HOME:1,
LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_UNKNOWN:0};W[W.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";W[W.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";W[W.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";
W[W.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";W[W.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";W[W.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";W[W.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";W[W.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";
W[W.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";W[W.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";W[W.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";
W[W.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";W[W.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";W[W.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";W[W.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";
W[W.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";W[W.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";W[W.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";W[W.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";W[W.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";
W[W.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";W[W.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";W[W.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";W[W.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";W[W.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";W[W.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";W[W.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";
W[W.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";W[W.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";W[W.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";W[W.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";W[W.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";
W[W.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";W[W.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";W[W.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";W[W.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";W[W.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";W[W.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";
W[W.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";W[W.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";W[W.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";W[W.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";W[W.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";W[W.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";W[W.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";
W[W.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";W[W.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";W[W.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";W[W.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";W[W.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";W[W.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";
W[W.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";W[W.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";W[W.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";W[W.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";W[W.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";W[W.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";W[W.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";
W[W.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";W[W.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";W[W.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";W[W.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";W[W.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";W[W.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";W[W.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";W[W.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";
W[W.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";W[W.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";W[W.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";W[W.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";W[W.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";W[W.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";
W[W.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";W[W.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";W[W.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";W[W.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";W[W.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";W[W.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";
W[W.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";W[W.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";W[W.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";W[W.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";
W[W.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";W[W.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";W[W.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";W[W.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";W[W.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";W[W.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";W[W.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";W[W.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";
W[W.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";W[W.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";W[W.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";W[W.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";W[W.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";
W[W.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";W[W.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";
W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";W[W.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";
W[W.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";W[W.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";W[W.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";W[W.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";
W[W.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";W[W.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";W[W.LATENCY_ACTION_WATCH_UI]="LATENCY_ACTION_WATCH_UI";W[W.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";W[W.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";
W[W.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";W[W.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";W[W.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";W[W.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";W[W.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";W[W.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";W[W.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";W[W.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";
W[W.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";W[W.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";W[W.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";W[W.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";W[W.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";
W[W.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";W[W.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";W[W.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";W[W.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";W[W.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";W[W.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";W[W.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";
W[W.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";W[W.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";W[W.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";W[W.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";W[W.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";W[W.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";W[W.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";W[W.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";W[W.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";
W[W.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";W[W.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";W[W.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var Ht={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Ht[Ht.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Ht[Ht.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Ht[Ht.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var X={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};X[X.CONN_INVALID]="CONN_INVALID";X[X.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";X[X.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";X[X.CONN_WIFI_METERED]="CONN_WIFI_METERED";X[X.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";X[X.CONN_DISCO]="CONN_DISCO";
X[X.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";X[X.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";X[X.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";X[X.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";X[X.CONN_WIFI]="CONN_WIFI";X[X.CONN_NONE]="CONN_NONE";X[X.CONN_UNKNOWN]="CONN_UNKNOWN";X[X.CONN_DEFAULT]="CONN_DEFAULT";
var Y={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Y[Y.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Y[Y.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Y[Y.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Y[Y.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Y[Y.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Y[Y.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Y[Y.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Y[Y.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Y[Y.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Y[Y.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Y[Y.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Y[Y.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Y[Y.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Y[Y.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Y[Y.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Y[Y.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Y[Y.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Y[Y.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Y[Y.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Y[Y.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Y[Y.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Y[Y.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Y[Y.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Y[Y.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Y[Y.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Y[Y.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Y[Y.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var It={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};It[It.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
It[It.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";It[It.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";It[It.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";It[It.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";It[It.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";It[It.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";It[It.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var Jt={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};Jt[Jt.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";Jt[Jt.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";Jt[Jt.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";Jt[Jt.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var Kt={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
Kt[Kt.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";Kt[Kt.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var Lt={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};Lt[Lt.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";Lt[Lt.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";Lt[Lt.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
Lt[Lt.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";Lt[Lt.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";Lt[Lt.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var Mt={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};Mt[Mt.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";Mt[Mt.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";Mt[Mt.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";Mt[Mt.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var Nt={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};Nt[Nt.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";Nt[Nt.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";Nt[Nt.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var Ot={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};Ot[Ot.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
Ot[Ot.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";Ot[Ot.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var Pt="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo prefetchInfo accelerationSession webInfo tvInfo kabukiInfo mwebInfo musicInfo".split(" ");var Qt=y.ytLoggingLatencyUsageStats_||{};z("ytLoggingLatencyUsageStats_",Qt);function Rt(){this.i=0}
function St(){Rt.i||(Rt.i=new Rt);return Rt.i}
Rt.prototype.tick=function(a,b,c,d){Tt(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},P("web_csi_via_jspb")?(d=new Fj,E(d,1,a),E(d,2,b),a=new Ij,Xd(a,Fj,5,Jj,d),fr(a,c)):em("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
Rt.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Tt(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,em("latencyActionInfo",a,{cttAuthInfo:c}))};
Rt.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));Tt(this,"info_"+d+"_"+b)||(E(a,2,b),b={cttAuthInfo:c},c=new Ij,Xd(c,zj,7,Jj,a),fr(c,b))};
Rt.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Tt(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,em("latencyActionSpan",a,{cttAuthInfo:c}))};
function Tt(a,b){Qt[b]=Qt[b]||{count:0};var c=Qt[b];c.count++;c.time=R();a.i||(a.i=Ql(function(){var d=R(),e;for(e in Qt)Qt[e]&&6E4<d-Qt[e].time&&delete Qt[e];a&&(a.i=0)},0,5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new S("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Gr(c)),!0):!1}
;function Ut(){var a=["ol"];xt("").info.actionType="embed";a&&pk("TIMING_AFT_KEYS",a);pk("TIMING_ACTION","embed");Vt();a=pt();var b=rt();if("cold"===a.yt_lt||"cold"===b.loadType){var c=kt(),d=qt();d=d.gelTicks?d.gelTicks:d.gelTicks={};for(var e in c)e in d||Z(e,c[e]);e={};c=!1;d=p(Object.keys(a));for(var f=d.next();!f.done;f=d.next())f=f.value,(f=Gt(f,a[f]))&&!ut(rt(),f)&&(Ys(b,f),Ys(e,f),c=!0);c&&Wt(e)}z("ytglobal.timingready_",!0);a=M("TIMING_ACTION");B("ytglobal.timingready_")&&a&&"_start"in kt()&&
jt()&&tt()}
function Xt(a,b,c,d){null!==b&&(pt(c)[a]=b,(a=Gt(a,b,c))&&Wt(a,c,d))}
function Wt(a,b,c){if(!P("web_csi_via_jspb")||(void 0===c?0:c))c=xt(b||""),Ys(c.info,a),Ys(rt(b),a),c=st(b),b=ot(b).cttAuthInfo,St().info(a,c,b);else{c=new zj;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":Bj(c,W[a[e]]);break;case "clientActionNonce":E(c,2,a[e]);break;case "clientScreenNonce":E(c,4,a[e]);break;case "loadType":E(c,3,a[e]);break;case "isPrewarmedLaunch":E(c,92,a[e]);break;case "isFirstInstall":E(c,55,a[e]);break;case "networkType":E(c,
5,Ht[a[e]]);break;case "connectionType":E(c,26,X[a[e]]);break;case "detailedConnectionType":E(c,27,Y[a[e]]);break;case "isVisible":E(c,6,a[e]);break;case "playerType":E(c,7,It[a[e]]);break;case "clientPlaybackNonce":E(c,8,a[e]);break;case "adClientPlaybackNonce":E(c,28,a[e]);break;case "previousCpn":E(c,77,a[e]);break;case "targetCpn":E(c,76,a[e]);break;case "isMonetized":E(c,9,a[e]);break;case "isPrerollAllowed":E(c,16,a[e]);break;case "isPrerollShown":E(c,17,a[e]);break;case "adType":E(c,12,a[e]);
break;case "adTypesAllowed":E(c,36,a[e]);break;case "adNetworks":E(c,37,a[e]);break;case "previousAction":E(c,13,W[a[e]]);break;case "isRedSubscriber":E(c,14,a[e]);break;case "serverTimeMs":E(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":E(c,20,a[e]);break;case "targetVideoId":E(c,78,a[e]);break;case "adBreakType":E(c,21,Jt[a[e]]);break;case "isNavigation":Cj(c,a[e]);break;case "viewportHeight":E(c,29,a[e]);break;case "viewportWidth":E(c,30,a[e]);break;case "screenHeight":E(c,
84,a[e]);break;case "screenWidth":E(c,85,a[e]);break;case "browseId":E(c,31,a[e]);break;case "isCacheHit":E(c,32,a[e]);break;case "httpProtocol":E(c,33,a[e]);break;case "transportProtocol":E(c,34,a[e]);break;case "searchQuery":E(c,41,a[e]);break;case "isContinuation":E(c,42,a[e]);break;case "availableProcessors":E(c,43,a[e]);break;case "sdk":E(c,44,a[e]);break;case "isLocalStream":E(c,45,a[e]);break;case "navigationRequestedSameUrl":E(c,64,a[e]);break;case "shellStartupDurationMs":E(c,70,a[e]);break;
case "appInstallDataAgeMs":E(c,73,a[e]);break;case "latencyActionError":E(c,71,Kt[a[e]]);break;case "actionStep":E(c,79,a[e]);break;case "jsHeapSizeLimit":E(c,80,a[e]);break;case "totalJsHeapSize":E(c,81,a[e]);break;case "usedJsHeapSize":E(c,82,a[e]);break;case "sourceVideoDurationMs":E(c,90,a[e]);break;case "videoOutputFrames":E(c,93,a[e]);break;case "isResume":E(c,104,a[e]);break;case "adPrebufferedTimeSecs":E(c,39,a[e]);break;case "isLivestream":E(c,47,a[e]);break;case "liveStreamMode":E(c,91,
Lt[a[e]]);break;case "adCpn2":E(c,48,a[e]);break;case "adDaiDriftMillis":E(c,49,a[e]);break;case "videoStreamType":E(c,53,Mt[a[e]]);break;case "playbackRequiresTap":E(c,56,a[e]);break;case "performanceNavigationTiming":E(c,67,a[e]);break;case "transactionType":E(c,74,Nt[a[e]]);break;case "playerRotationType":E(c,101,Ot[a[e]]);break;case "allowedPreroll":E(c,10,a[e]);break;case "shownPreroll":E(c,11,a[e]);break;case "getHomeRequestId":E(c,57,a[e]);break;case "getSearchRequestId":E(c,60,a[e]);break;
case "getPlayerRequestId":E(c,61,a[e]);break;case "getWatchNextRequestId":E(c,62,a[e]);break;case "getBrowseRequestId":E(c,63,a[e]);break;case "getLibraryRequestId":E(c,66,a[e]);break;default:Pt.includes(f)&&yk(new S("Codegen laipb translator asked to translate message field",""+f))}}catch(g){yk(Error("Codegen laipb translator failed to set "+f))}}Yt(c,b)}}
function Yt(a,b){var c=qt(b);c.jspbInfos||(c.jspbInfos=[]);c.jspbInfos.push(a);xt(b||"").jspbInfo.push(a);c=st(b);b=ot(b).cttAuthInfo;St().jspbInfo(a,c,b)}
function Z(a,b,c){if(!b&&"_"!==a[0]){var d=a;T.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),T.mark(d))}d=xt(c||"");d.tick[a]=b||R();if(d.callback&&d.callback[a]){d=p(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=qt(c);d.gelTicks&&(d.gelTicks[a]=!0);d=kt(c);e=b||R();d[a]=e;e=st(c);var f=ot(c).cttAuthInfo;if("_start"===a){var g=St();Tt(g,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},P("web_csi_via_jspb")?(f=new xj,E(f,1,e),e=new Ij,Xd(e,xj,6,Jj,f),fr(e,
b)):em("latencyActionBaselined",{clientActionNonce:e},b))}else St().tick(a,e,b,f);tt(c);return d[a]}
function Zt(){var a=st();requestAnimationFrame(function(){setTimeout(function(){a===st()&&Z("ol",void 0,void 0)},0)})}
function $t(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=hp+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Vt(){function a(f){var g=lt(),h=nt(),k=M("CSI_START_TIMESTAMP_MILLIS",0);0<k&&!P("embeds_web_enable_csi_start_override_killswitch")&&(h=k);h&&(Z("srt",g.responseStart),1!==f.prerender&&Z("_start",h,void 0));f=vt();0<f&&Z("fpt",f);f=lt();f.isPerformanceNavigationTiming&&Wt({performanceNavigationTiming:!0});Z("nreqs",f.requestStart,void 0);Z("nress",f.responseStart,void 0);Z("nrese",f.responseEnd,void 0);0<f.redirectEnd-f.redirectStart&&(Z("nrs",f.redirectStart,void 0),Z("nre",f.redirectEnd,
void 0));0<f.domainLookupEnd-f.domainLookupStart&&(Z("ndnss",f.domainLookupStart,void 0),Z("ndnse",f.domainLookupEnd,void 0));0<f.connectEnd-f.connectStart&&(Z("ntcps",f.connectStart,void 0),Z("ntcpe",f.connectEnd,void 0));f.secureConnectionStart>=nt()&&0<f.connectEnd-f.secureConnectionStart&&(Z("nstcps",f.secureConnectionStart,void 0),Z("ntcpe",f.connectEnd,void 0));T&&"getEntriesByType"in T&&au()}
var b=M("TIMING_INFO",{});if(P("web_csi_via_jspb")){b=bu(b);Yt(b);b=Bj(Cj(new zj,!0),W[Ft(M("TIMING_ACTION"))]);var c=M("PREVIOUS_ACTION");c&&E(b,13,W[Ft(c)]);(c=M("CLIENT_PROTOCOL"))&&E(b,33,c);(c=M("CLIENT_TRANSPORT"))&&E(b,34,c);(c=Yr())&&"UNDEFINED_CSN"!==c&&E(b,4,c);c=$t();1!==c&&-1!==c||E(b,6,!0);c=pt();E(b,3,"cold");a(c);c=cu();if(0<c.length){c=p(c);for(var d=c.next();!d.done;d=c.next()){d=d.value;var e=new yj;E(e,1,d);Zd(b,83,yj,e)}}Yt(b)}else{for(c in b)b.hasOwnProperty(c)&&Xt(c,b[c]);b=
{isNavigation:!0,actionType:Ft(M("TIMING_ACTION"))};if(c=M("PREVIOUS_ACTION"))b.previousAction=Ft(c);if(c=M("CLIENT_PROTOCOL"))b.httpProtocol=c;if(c=M("CLIENT_TRANSPORT"))b.transportProtocol=c;(c=Yr())&&"UNDEFINED_CSN"!==c&&(b.clientScreenNonce=c);c=$t();if(1===c||-1===c)b.isVisible=!0;c=pt();b.loadType="cold";a(c);c=cu();if(0<c.length)for(b.resourceInfo=[],c=p(c),d=c.next();!d.done;d=c.next())b.resourceInfo.push({resourceCache:d.value});Wt(b)}}
function bu(a){var b=new zj;a=p(Object.entries(a));for(var c=a.next();!c.done;c=a.next()){var d=p(c.value);c=d.next().value;d=d.next().value;switch(c){case "GetBrowse_rid":var e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "GetGuide_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "GetHome_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "GetPlayer_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "GetSearch_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;
case "GetSettings_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "GetTrending_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "GetWatchNext_rid":e=new Ej;E(e,1,c);E(e,2,String(d));Dj(b,e);break;case "yt_red":E(b,14,!!d);break;case "yt_ad":E(b,9,!!d)}}return b}
function du(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);ic()&&a.setAttribute("nonce",ic());return c?(a=T.getEntriesByName(c))&&a[0]&&(a=a[0],c=nt(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function cu(){var a=[];if(document.querySelector&&T&&T.getEntriesByName)for(var b in ht)if(ht.hasOwnProperty(b)){var c=ht[b];du(b,c)&&a.push(c)}return a}
function au(){var a=window.location.protocol,b=T.getEntriesByType("resource");b=ib(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=kb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",mt(b.startTime)),Z("wffe",mt(b.responseEnd)))}
var eu=window;eu.ytcsi&&(eu.ytcsi.info=Xt,eu.ytcsi.tick=Z);var fu="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),gu=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function hu(a,b,c,d){this.o=a;this.M=b;this.m=c;this.l=d;this.j=void 0;this.i=new Map;a.La||(a.La={});a.La=Object.assign({},Xs,a.La)}
function iu(a,b,c,d){if(void 0!==hu.i){if(d=hu.i,a=[a!==d.o,b!==d.M,c!==d.m,!1,!1,void 0!==d.j],a.some(function(e){return e}))throw new S("InnerTubeTransportService is already initialized",a);
}else hu.i=new hu(a,b,c,d)}
function ju(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Gs:c;var d=Ps(b,a.o);if(!d)return yf(new S("Error: No request builder found for command.",b));var e=d.o(b,void 0,c);return e?new tf(function(f){var g,h,k;return w(function(m){if(1==m.i){h="cors"===(null==(g=e.Ba)?void 0:g.mode)?"cors":void 0;if(a.m.ld){var q=e.config,r;q=null==q?void 0:null==(r=q.Ra)?void 0:r.sessionIndex;r=xs({sessionIndex:q});k=Object.assign({},ku(h),r);return m.u(2)}return v(m,lu(e.config,
h),3)}2!=m.i&&(k=m.j);f(mu(a,e,k));m.i=0})}):yf(new S("Error: Failed to build request for command.",b))}
function mu(a,b,c){var d,e,f,g,h,k,m,q,r,x,u,A,D,F,N,O,Q,ca,aa,ja,ma,na,H,ra,la,rd,sd;return w(function(xa){switch(xa.i){case 1:xa.u(2);break;case 3:if((d=xa.j)&&!d.isExpired())return xa.return(Promise.resolve(d.i()));case 2:if(null==(e=b)?0:null==(f=e.ga)?0:f.context)for(g=p([]),h=g.next();!h.done;h=g.next())k=h.value,k.rq(b.ga.context);if(null==(m=a.j)?0:m.yq(b.input,b.ga))return xa.return(a.j.oq(b.input,b.ga));(x=null==(r=b.config)?void 0:r.Aa)&&a.i.has(x)&&P("web_memoize_inflight_requests")?q=
a.i.get(x):(u=JSON.stringify(b.ga),b.Ba=Object.assign({},b.Ba,{headers:c}),A=Object.assign({},b.Ba),"POST"===b.Ba.method&&(A=Object.assign({},A,{body:u})),(null==(D=b.config)?0:D.Wc)&&Z(b.config.Wc),F=function(){return a.M.fetch(b.input,A,b.config)},q=F(),x&&a.i.set(x,q));
return v(xa,q,4);case 4:N=xa.j;if(P("web_one_platform_error_handling")&&(null==(O=N)?0:null==(Q=O.error)?0:Q.details))for(ca=N.error.details,aa=p(ca),ja=aa.next();!ja.done;ja=aa.next())ma=ja.value,(na=ma["@type"])&&-1<gu.indexOf(na)&&(delete ma["@type"],N=ma);x&&a.i.has(x)&&a.i.delete(x);(null==(H=b.config)?0:H.Xc)&&Z(b.config.Xc);if(N||null==(ra=a.j)||!ra.iq(b.input,b.ga)){xa.u(5);break}return v(xa,a.j.nq(b.input,b.ga),6);case 6:N=xa.j;case 5:if(N&&(null==(la=N.xq)||!la.Aq)&&a.l)for(rd=p(fu),h=rd.next();!h.done;h=
rd.next())sd=h.value,a.l[sd]&&a.l[sd].handleResponse(N,b);return xa.return(N)}})}
function lu(a,b){var c,d,e,f;return w(function(g){if(1==g.i){e=null==(c=a)?void 0:null==(d=c.Ra)?void 0:d.sessionIndex;var h=xs({sessionIndex:e});if(!(h instanceof tf)){var k=new tf(eb);uf(k,2,h);h=k}return v(g,h,2)}f=g.j;return g.return(Promise.resolve(Object.assign({},ku(b),f)))})}
function ku(a){var b={"Content-Type":"application/json"};P("enable_web_eom_visitor_data")&&M("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=M("EOM_VISITOR_DATA"):M("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=M("VISITOR_DATA"));P("track_webfe_innertube_auth_mismatch")&&(b["X-Youtube-Bootstrap-Logged-In"]=M("LOGGED_IN",!1));"cors"!==a&&((a=M("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=M("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=M("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=M("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var nu=new zs("INNERTUBE_TRANSPORT_TOKEN");var ou=["share/get_web_player_share_panel"],pu=["feedback"],qu=["notification/modify_channel_preference"],ru=["browse/edit_playlist"],su=["subscription/subscribe"],tu=["subscription/unsubscribe"];function uu(){}
t(uu,Us);uu.prototype.l=function(){return su};
uu.prototype.i=function(a){return a.subscribeEndpoint};
uu.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(uu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function vu(){}
t(vu,Us);vu.prototype.l=function(){return tu};
vu.prototype.i=function(a){return a.unsubscribeEndpoint};
vu.prototype.j=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(vu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function wu(){}
t(wu,Us);wu.prototype.l=function(){return pu};
wu.prototype.i=function(a){return a.feedbackEndpoint};
wu.prototype.j=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(wu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function xu(){}
t(xu,Us);xu.prototype.l=function(){return qu};
xu.prototype.i=function(a){return a.modifyChannelNotificationPreferenceEndpoint};
xu.prototype.j=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function yu(){}
t(yu,Us);yu.prototype.l=function(){return ru};
yu.prototype.i=function(a){return a.playlistEditEndpoint};
yu.prototype.j=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function zu(){}
t(zu,Us);zu.prototype.l=function(){return ou};
zu.prototype.i=function(a){return a.webPlayerShareEntityServiceEndpoint};
zu.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Bs=new zs("NETWORK_SLI_TOKEN");function Au(a){this.i=a}
Au.prototype.fetch=function(a,b){var c=this,d,e;return w(function(f){c.i&&(d=mc(nc(5,Dc(a,"key")))||"/UNKNOWN_PATH",c.i.start(d));e=new window.Request(a,b);return P("web_fetch_promise_cleanup_killswitch")?f.return(Promise.resolve(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Gr(g)}))):f.return(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Gr(g)}))})};
Au.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.i&&this.i.success():(this.i&&this.i.failure(),b=b.then(function(c){Gr(new S("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
Au[ys]=[new As];var Bu=new zs("NETWORK_MANAGER_TOKEN");var Cu;function Du(a){Mn.call(this,1,arguments);this.csn=a}
t(Du,Mn);var Vn=new Nn("screen-created",Du),Eu=[],Gu=Fu,Hu=0;function Iu(a,b,c,d,e,f,g){function h(){Gr(new S("newScreen() parent element does not have a VE - rootVe",b))}
var k=Gu();f=new Rr({veType:b,youtubeData:f,jspbYoutubeData:void 0});e={cttAuthInfo:e,ba:k};if(P("il_via_jspb")){var m=new mj;m.V(k);nj(m,f.getAsJspb());c&&c.visualElement?(f=new oj,c.clientScreenNonce&&E(f,2,c.clientScreenNonce),pj(f,c.visualElement.getAsJspb()),g&&E(f,4,Kj[g]),G(m,oj,5,f)):c&&h();d&&E(m,3,d);kr(m,e,a)}else f={csn:k,pageVe:f.getAsJson()},c&&c.visualElement?(f.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(f.implicitGesture.gestureType=
g)):c&&h(),d&&(f.cloneCsn=d),a?ar("screenCreated",f,a,e):em("screenCreated",f,e);Sn(Vn,new Du(k));return k}
function Ju(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:$r(b),
ba:b};d=p(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(rb(g)||!g.trackingParams&&!g.veType)&&Gr(Error("Child VE logged with no data"));if(P("il_via_jspb")){var h=new qj;h.V(b);sj(h,c.getAsJspb());jb(e,function(k){k=k.getAsJspb();Zd(h,3,hj,k)});
"UNDEFINED_CSN"==b?Ku("visualElementAttached",h,f):lr(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:jb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"==b?Ku("visualElementAttached",c,f):a?ar("visualElementAttached",c,a,f):em("visualElementAttached",c,f)}
function Fu(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return fd(b,3)}
function Ku(a,b,c){Eu.push({payloadName:a,payload:b,options:c});Hu||(Hu=Wn())}
function Xn(a){if(Eu){for(var b=p(Eu),c=b.next();!c.done;c=b.next())if(c=c.value,c.payload)if(P("il_via_jspb"))switch(c.payload.V(a.csn),c.payloadName){case "screenCreated":kr(c.payload,c.options);break;case "visualElementAttached":lr(c.payload,c.options);break;case "visualElementShown":gr(c.payload,c.options);break;case "visualElementHidden":hr(c.payload,c.options);break;case "visualElementGestured":ir(c.payload,c.options);break;case "visualElementStateChanged":jr(c.payload,c.options);break;default:Gr(new S("flushQueue unable to map payloadName to JSPB setter"))}else c.payload.csn=
a.csn,ar(c.payloadName,c.payload,null,c.options);Eu.length=0}Hu=0}
;function Lu(){this.j=new Set;this.i=new Set;this.l=new Map}
Lu.prototype.s=function(){};
Lu.prototype.clear=function(){this.j.clear();this.i.clear();this.l.clear()};
Qa(Lu);function Mu(){this.o=[];this.N=[];this.i=[];this.m=[];this.B=[];this.j=new Set;this.v=new Map}
Mu.prototype.s=function(a){this.client=a};
function Nu(a,b,c){c=void 0===c?0:c;b.then(function(d){a.j.has(c)&&a.l&&a.l();var e=Yr(c),f=Wr(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&Ju(a.client,e,f,[Sr(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&Ju(a.client,e,f,[Sr(d.playerResponse.trackingParams)])}})}
function Ou(a,b,c,d){d=void 0===d?0:d;if(a.j.has(d))a.o.push([b,c]);else{var e=Yr(d);c=c||Wr(d);e&&c&&Ju(a.client,e,c,[b])}}
Mu.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Yr(void 0===c?0:c)){a=this.client;var e=Sr(d);d={cttAuthInfo:$r(c),ba:c};if(P("il_via_jspb")){var f=new tj;f.V(c);e=e.getAsJspb();G(f,hj,2,e);E(f,4,Kj.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK);b&&G(f,kj,3);"UNDEFINED_CSN"==c?Ku("visualElementGestured",f,d):ir(f,d,a)}else f={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(f.clientData=b),"UNDEFINED_CSN"==c?
Ku("visualElementGestured",f,d):a?ar("visualElementGestured",f,a,d):em("visualElementGestured",f,d);b=!0}else b=!1;else b=!1;return b};
function Pu(a,b,c){c=void 0===c?{}:c;a.j.add(c.layer||0);a.l=function(){Qu(a,b,c);var f=Wr(c.layer);if(f){for(var g=p(a.o),h=g.next();!h.done;h=g.next())h=h.value,Ou(a,h[0],h[1]||f,c.layer);f=p(a.N);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=Yr(g);var m=k[0]||Wr(g);if(h&&m){g=a.client;var q=k[1];k={cttAuthInfo:$r(h),ba:h};P("il_via_jspb")?(q=new wj,q.V(h),m=m.getAsJspb(),G(q,hj,2,m),"UNDEFINED_CSN"==h?Ku("visualElementStateChanged",q,k):jr(q,k,g)):(m={csn:h,ve:m.getAsJson(),
clientData:q},"UNDEFINED_CSN"==h?Ku("visualElementStateChanged",m,k):g?ar("visualElementStateChanged",m,g,k):em("visualElementStateChanged",m,k))}}}};
Yr(c.layer)||a.l();if(c.Ob)for(var d=p(c.Ob),e=d.next();!e.done;e=d.next())Nu(a,e.value,c.layer);else Fr(Error("Delayed screen needs a data promise."))}
function Qu(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Sc?c.Sc:c.layer;var e=Yr(d);d=Wr(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=M("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=Iu(a.client,b,f,c.Nb,c.cttAuthInfo,g,c.lq)}catch(m){Ir(m,{uq:b,rootVe:d,parentVisualElement:void 0,jq:e,qq:f,Nb:c.Nb});Fr(m);return}as(k,b,
c.layer,c.cttAuthInfo);if(b=e&&"UNDEFINED_CSN"!==e&&d){a:{b=p(Object.values(Qr));for(f=b.next();!f.done;f=b.next())if(Yr(f.value)===e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,g=!0,h=(g=void 0===g?!1:g)?16:8,f={cttAuthInfo:$r(e),ba:e,Pb:g},P("il_via_jspb")?(h=new uj,h.V(e),d=d.getAsJspb(),G(h,hj,2,d),E(h,4,g?16:8),"UNDEFINED_CSN"==e?Ku("visualElementHidden",h,f):hr(h,f,b)):(d={csn:e,ve:d.getAsJson(),eventType:h},"UNDEFINED_CSN"==e?Ku("visualElementHidden",d,f):b?ar("visualElementHidden",d,b,f):em("visualElementHidden",
d,f)));a.i[a.i.length-1]&&!a.i[a.i.length-1].csn&&(a.i[a.i.length-1].csn=k||"");Wt({clientScreenNonce:k});Lu.getInstance().clear();d=Wr(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(P("web_mark_root_visible")||P("music_web_mark_root_visible"))&&(e=k,k={cttAuthInfo:$r(e),ba:e},P("il_via_jspb")?(b=new vj,b.V(e),f=d.getAsJspb(),G(b,hj,2,f),E(b,4,1),"UNDEFINED_CSN"==e?Ku("visualElementShown",b,k):gr(b,k)):(b={csn:e,ve:d.getAsJson(),eventType:1},"UNDEFINED_CSN"==e?Ku("visualElementShown",b,k):em("visualElementShown",
b,k)));a.j.delete(c.layer||0);a.l=void 0;e=p(a.v);for(k=e.next();!k.done;k=e.next())b=p(k.value),k=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Ou(a,k,d,c.layer);for(c=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(m){Fr(m)}}for(c=a.m.length=0;c<a.B.length;c++){e=a.B[c];try{e()}catch(m){Fr(m)}}}
;function Ru(){var a,b;return w(function(c){if(1==c.i)return a=hu.i,a?v(c,ju(a),2):(Gr(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),c.return(void 0));if(b=c.j)return b.errorMetadata?(Gr(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),c.return(void 0)):c.return(b.kq);Gr(Error("Network request to get Datasync IDs failed."));return c.return(void 0)})}
;var Su=y.caches,Tu;function Uu(a){var b=a.indexOf(":");return-1===b?{Zb:a}:{Zb:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Vu(){return w(function(a){if(void 0!==Tu)return a.return(Tu);Tu=new Promise(function(b){var c;return w(function(d){switch(d.i){case 1:return Ba(d,2),v(d,Su.open("test-only"),4);case 4:return v(d,Su.delete("test-only"),5);case 5:Ca(d,3);break;case 2:if(c=Da(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.i=0}})});
return a.return(Tu)})}
function Wu(a){var b,c,d,e,f,g,h;w(function(k){if(1==k.i)return v(k,Vu(),2);if(3!=k.i){if(!k.j)return k.return(!1);b=[];return v(k,Su.keys(),3)}c=k.j;d=p(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Uu(f),h=g.datasyncId,!h||a.includes(h)||b.push(Su.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(q){return q})}))})}
function Xu(){var a,b,c,d,e,f,g;return w(function(h){if(1==h.i)return v(h,Vu(),2);if(3!=h.i){if(!h.j)return h.return(!1);a=im("cache contains other");return v(h,Su.keys(),3)}b=h.j;c=p(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Uu(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Yu(){try{return!!self.localStorage}catch(a){return!1}}
;function Zu(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function $u(a){if(Yu()){var b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Zu(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function av(){if(!Yu())return!1;var a=im(),b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next())if(c=Zu(c.value),void 0!==c&&c!==a)return!0;return!1}
;function bv(){Ru().then(function(a){a&&(tn(a),Wu(a),$u(a))})}
function cv(){var a=new Do;Qh.S(function(){var b,c,d,e;return w(function(f){switch(f.i){case 1:if(P("ytidb_clear_optimizations_killswitch")){f.u(2);break}b=im("clear");if(b.startsWith("V")){var g=[b];tn(g);Wu(g);$u(g);return f.return()}c=av();return v(f,Xu(),3);case 3:return d=f.j,v(f,un(),4);case 4:if(e=f.j,!c&&!d&&!e)return f.return();case 2:a.L()?bv():a.m.add("publicytnetworkstatus-online",bv,!0,void 0,void 0),f.i=0}})})}
;function dv(a){a&&(a.dataset?a.dataset[ev("loaded")]="true":a.setAttribute("data-loaded","true"))}
function fv(a,b){return a?a.dataset?a.dataset[ev(b)]:a.getAttribute("data-"+b):null}
var gv={};function ev(a){return gv[a]||(gv[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var hv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,iv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function jv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(hv,""),c=c.replace(iv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else kv(a,b,c)}
function kv(a,b,c){c=void 0===c?null:c;var d=lv(a),e=document.getElementById(d),f=e&&fv(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=mq(d,b),b=""+Ua(b),mv[b]=f),g||(e=nv(a,d,function(){fv(e,"loaded")||(dv(e),pq(d),Sk($a(qq,d),0))},c)))}
function nv(a,b,c,d){d=void 0===d?null:d;var e=ef("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);zh(e,Lb(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function ov(a){a=lv(a);var b=document.getElementById(a);b&&(qq(a),b.parentNode.removeChild(b))}
function pv(a,b){a&&b&&(a=""+Ua(b),(a=mv[a])&&oq(a))}
function lv(a){var b=document.createElement("a");fc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+kc(a)}
var mv={};var qv=[],rv=!1;function uv(){if(!P("disable_biscotti_fetch_for_ad_blocker_detection")&&!P("disable_biscotti_fetch_entirely_for_all_web_clients")&&ms()){var a=M("PLAYER_VARS",{});if("1"!=tb(a)&&!ns(a)){var b=function(){rv=!0;"google_ad_status"in window?pk("DCLKSTAT",1):pk("DCLKSTAT",2)};
try{jv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}qv.push(Qh.S(function(){if(!(rv||"google_ad_status"in window)){try{pv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}rv=!0;pk("DCLKSTAT",3)}},5E3))}}}
function vv(){var a=Number(M("DCLKSTAT",0));return isNaN(a)?0:a}
;function wv(){this.state=1;this.i=null}
wv.prototype.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterScript)?d:null,f;d=null!=(f=a.interpreterUrl)?f:null;a.interpreterSafeScript&&(e=a.interpreterSafeScript,Fb("From proto message. b/166824318"),e=e.privateDoNotAccessOrElseSafeScriptWrappedValue||"",e=(f=Ab())?f.createScript(e):e,e=(new Hb(e)).toString());a.interpreterSafeUrl&&(d=a.interpreterSafeUrl,Fb("From proto message. b/166824318"),d=Lb(d.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());
xv(this,e,d,a.program,b,c)}else Gr(Error("Cannot initialize botguard without program"))};
function xv(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,jv(c,function(){window[g]?yv(a,d,g,e):(a.state=3,ov(c),Gr(new S("Unable to load Botguard","from "+c)))},f)):b?(f=ef("SCRIPT"),f.textContent=b,f.nonce=ic(),document.head.appendChild(f),document.head.removeChild(f),window[g]?yv(a,d,g,e):(a.state=4,Gr(new S("Unable to load Botguard from JS")))):Gr(new S("Unable to load VM; no url or JS provided"))}
wv.prototype.isInitialized=function(){return!!this.i};
function yv(a,b,c,d){a.state=5;try{var e=new xh({program:b,globalName:c});e.hd.then(function(){a.state=6;d&&d(b)});
zv(a,e)}catch(f){a.state=7,f instanceof Error&&Gr(f)}}
wv.prototype.invoke=function(a){a=void 0===a?{}:a;var b=this.i;if(b){var c={Mb:a};if(b.Wa)throw Error("Already disposed");a=vh();var d;null!=(d=b.sa)&&d.j.i.Cb("/client_streamz/bg/fsc",d.Aa);d=b.md([c.Mb,c.kd]);null!=(b=b.sa)&&(a=vh()-a,b.l.i.hb("/client_streamz/bg/fsl",a,b.Aa));b=d}else b=null;return b};
wv.prototype.dispose=function(){zv(this,null);this.state=8};
function zv(a,b){ne(a.i);a.i=b}
;var Av=new wv;function Bv(){return Av.isInitialized()}
function Cv(a){a=void 0===a?{}:a;return Av.invoke(a)}
;function Dv(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Ul():d;this.m=c;this.l=d;this.j=new wh;this.i=a;a={};c=p(this.i.entries());for(d=c.next();!d.done;a={Ca:a.Ca,Na:a.Na},d=c.next()){var e=p(d.value);d=e.next().value;e=e.next().value;a.Na=d;a.Ca=e;d=function(f){return function(){f.Ca.tb();b.i[f.Na].eb=!0;b.i.every(function(g){return!0===g.eb})&&b.j.resolve()}}(a);
e=Ql(d,Ev(this,a.Ca));this.i[a.Na]=Object.assign({},a.Ca,{tb:d,Za:e})}}
function Fv(a){var b=Array.from(a.i.keys()).sort(function(d,e){return Ev(a,a.i[e])-Ev(a,a.i[d])});
b=p(b);for(var c=b.next();!c.done;c=b.next())c=a.i[c.value],void 0===c.Za||c.eb||(a.l.fa(c.Za),Ql(c.tb,10))}
Dv.prototype.cancel=function(){for(var a=p(this.i),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.Za||b.eb||this.l.fa(b.Za),b.eb=!0;this.j.resolve()};
function Ev(a,b){var c;return null!=(c=b.priority)?c:a.m}
;function Gv(a){this.state=a;this.plugins=[];this.s=void 0}
Gv.prototype.install=function(){this.plugins.push.apply(this.plugins,ia(Ma.apply(0,arguments)))};
Gv.prototype.transition=function(a,b){var c=this,d=this.B.find(function(f){return f.from===c.state&&f.D===a});
if(d){this.l&&(Fv(this.l),this.l=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Hv(this,e,this.s),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Hv(a,b,c){return function(){var d=Ma.apply(0,arguments),e=b.filter(function(k){var m;return 10===(null!=(m=null!=c?c:k.priority)?m:0)}),f=b.filter(function(k){var m;
return 10!==(null!=(m=null!=c?c:k.priority)?m:0)});
Ul();var g={};e=p(e);for(var h=e.next();!h.done;g={Oa:g.Oa},h=e.next())g.Oa=h.value,Sl(function(k){return function(){k.Oa.callback.apply(k.Oa,ia(d))}}(g));
f=f.map(function(k){var m;return{tb:function(){k.callback.apply(k,ia(d))},
priority:null!=(m=null!=c?c:k.priority)?m:0}});
f.length&&(a.l=new Dv(f))}}
fa.Object.defineProperties(Gv.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Iv(a){Gv.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.i=new Map;this.B=[{from:"document_active",D:"document_disposed_preventable",action:this.N},{from:"document_active",D:"document_disposed",action:this.m},{from:"document_disposed_preventable",D:"document_disposed",action:this.m},{from:"document_disposed_preventable",D:"flush_logs",action:this.o},{from:"document_disposed_preventable",D:"document_active",action:this.j},{from:"document_disposed",D:"flush_logs",action:this.o},
{from:"document_disposed",D:"document_active",action:this.j},{from:"document_disposed",D:"document_disposed",action:function(){}},
{from:"flush_logs",D:"document_active",action:this.j}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
t(Iv,Gv);Iv.prototype.N=function(a,b){if(!this.i.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.i=new Map;this.transition("document_active");return}}this.i.set("document_disposed_preventable",!0);this.i.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Iv.prototype.m=function(a,b){this.i.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.i.set("document_disposed",!0),this.transition("flush_logs"))};
Iv.prototype.o=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Iv.prototype.j=function(){this.i=new Map};function Jv(a){Gv.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.B=[{from:"document_visibility_unknown",D:"document_visible",action:this.j},{from:"document_visibility_unknown",D:"document_hidden",action:this.i},{from:"document_visibility_unknown",D:"document_foregrounded",action:this.o},{from:"document_visibility_unknown",D:"document_backgrounded",action:this.m},{from:"document_visible",D:"document_hidden",action:this.i},{from:"document_visible",D:"document_foregrounded",action:this.o},
{from:"document_visible",D:"document_visible",action:this.j},{from:"document_foregrounded",D:"document_visible",action:this.j},{from:"document_foregrounded",D:"document_hidden",action:this.i},{from:"document_foregrounded",D:"document_foregrounded",action:this.o},{from:"document_hidden",D:"document_visible",action:this.j},{from:"document_hidden",D:"document_backgrounded",action:this.m},{from:"document_hidden",D:"document_hidden",action:this.i},{from:"document_backgrounded",D:"document_hidden",action:this.i},
{from:"document_backgrounded",D:"document_backgrounded",action:this.m},{from:"document_backgrounded",D:"document_visible",action:this.j}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
P("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
t(Jv,Gv);Jv.prototype.j=function(a,b){a(null==b?void 0:b.event);P("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Jv.prototype.i=function(a,b){a(null==b?void 0:b.event);P("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Jv.prototype.m=function(a,b){a(null==b?void 0:b.event)};
Jv.prototype.o=function(a,b){a(null==b?void 0:b.event)};function Kv(){this.i=new Iv;this.j=new Jv}
Kv.prototype.install=function(){var a=Ma.apply(0,arguments);this.i.install.apply(this.i,ia(a));this.j.install.apply(this.j,ia(a))};function Lv(){Kv.call(this);var a={};this.install((a.document_disposed={callback:this.l},a));a={};this.install((a.flush_logs={callback:this.m},a))}
var Mv;t(Lv,Kv);Lv.prototype.m=function(){if(P("web_fp_via_jspb")){var a=new gj,b=Yr();b&&a.V(b);b=new Ij;Xd(b,gj,380,Jj,a);fr(b);P("web_fp_via_jspb_and_json")&&em("finalPayload",{csn:Yr()})}else em("finalPayload",{csn:Yr()})};
Lv.prototype.l=function(){Kr(Lr)};function Nv(){}
Nv.getInstance=function(){var a=B("ytglobal.storage_");a||(a=new Nv,z("ytglobal.storage_",a));return a};
Nv.prototype.estimate=function(){var a,b,c;return w(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(Ov()):d.return()})};
function Ov(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
z("ytglobal.storageClass_",Nv);function cm(a,b){var c=this;this.handleError=a;this.i=b;this.j=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.j=!0});
this.l=Math.random()<=sk("ytidb_transaction_ended_event_rate_limit",.02)}
cm.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":P("idb_data_corrupted_killswitch")||this.i("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.i("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":P("idb_is_supported_completed_killswitch")||this.i("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Pv(this,b);break;case "TRANSACTION_ENDED":this.l&&this.i("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,
{hasWindowUnloaded:this.j}),this.i("idbTransactionAborted",a)}};
function Pv(a,b){Nv.getInstance().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Qv(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Qv(null==c?void 0:c.quota)});a.i("idbQuotaExceeded",c)})}
function Qv(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Rv(a,b,c){J.call(this);var d=this;c=c||M("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.channel="widget";this.F=!!a;this.v=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.F&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.o&&(!d.s||0<=gb(d.s,f.func))&&d.o(f.func,f.args,e.origin)}}};
this.s=this.j=this.o=null;window.addEventListener("message",this.v)}
t(Rv,J);Rv.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){zk(d)}}};
Rv.prototype.C=function(){window.removeEventListener("message",this.v);J.prototype.C.call(this)};function Sv(){this.j=[];this.isReady=!1;this.l={};var a=this.i=new Rv(!!M("WIDGET_ID_ENFORCE")),b=this.Uc.bind(this);a.o=b;a.s=null;this.i.channel="widget";if(a=M("WIDGET_ID"))this.i.sessionId=a}
l=Sv.prototype;l.Uc=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.l[a]||"onReady"===a||(this.addEventListener(a,Tv(this,a)),this.l[a]=!0)):this.Db(a,b,c)};
l.Db=function(){};
function Tv(a,b){return function(c){return a.sendMessage(b,c)}}
l.addEventListener=function(){};
l.Hc=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.pb());this.sendMessage("onReady");hb(this.j,this.ic,this);this.j=[]};
l.pb=function(){return null};
function Uv(a,b){a.sendMessage("infoDelivery",b)}
l.ic=function(a){this.isReady?this.i.sendMessage(a):this.j.push(a)};
l.sendMessage=function(a,b){this.ic({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.i=null};function Vv(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Wv(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Xv(a,b,c,d){if(Ta(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Yv(a){Sv.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.ed.bind(this));this.addEventListener("onVolumeChange",this.fd.bind(this));this.addEventListener("onApiChange",this.Yc.bind(this));this.addEventListener("onPlaybackQualityChange",this.bd.bind(this));this.addEventListener("onPlaybackRateChange",this.cd.bind(this));this.addEventListener("onStateChange",this.dd.bind(this));this.addEventListener("onWebglSettingsChanged",
this.gd.bind(this))}
t(Yv,Sv);l=Yv.prototype;
l.Db=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Vv(a)){var d=b;if(Ta(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Wv(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Wv(e);break;case "loadPlaylist":case "cuePlaylist":e=Xv(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Vv(a)&&Uv(this,this.pb())}};
l.onReady=function(){var a=this.Hc.bind(this);this.i.j=a};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.pb=function(){if(!this.api)return null;var a=this.api.getApiInterface();mb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.dd=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Uv(this,a)};
l.bd=function(a){Uv(this,{playbackQuality:a})};
l.cd=function(a){Uv(this,{playbackRate:a})};
l.Yc=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.fd=function(){Uv(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.ed=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Uv(this,a)};
l.gd=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Uv(this,a)};
l.dispose=function(){Sv.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Zv(a){J.call(this);this.j={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.cc,this)}
t(Zv,J);l=Zv.prototype;l.start=function(){this.started||this.i()||(this.started=!0,this.connection.va("RECEIVING"))};
l.va=function(a,b){this.started&&!this.i()&&this.connection.va(a,b)};
l.cc=function(a,b,c){if(this.started&&!this.i()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=$v(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=aw(a,c))&&this.va(a,c))}}};
l.addListener=function(a){if(!(a in this.j)){var b=this.Zc.bind(this,a);this.j[a]=b;this.addEventListener(a,b)}};
l.Zc=function(a,b){this.started&&!this.i()&&this.connection.va(a,this.ob(a,b))};
l.ob=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.j&&(this.removeEventListener(a,this.j[a]),delete this.j[a])};
l.C=function(){var a=this.connection;a.i()||oi(a.j,"command",this.cc,this);this.connection=null;for(var b in this.j)this.j.hasOwnProperty(b)&&this.removeListener(b);J.prototype.C.call(this)};function bw(a,b){Zv.call(this,b);this.api=a;this.start()}
t(bw,Zv);bw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
bw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function $v(a,b){switch(a){case "loadVideoById":return a=Wv(b),[a];case "cueVideoById":return a=Wv(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Xv(b),[a];case "cuePlaylist":return a=Xv(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function aw(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
bw.prototype.ob=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Zv.prototype.ob.call(this,a,b)};
bw.prototype.C=function(){Zv.prototype.C.call(this);delete this.api};function cw(a){a=void 0===a?!1:a;J.call(this);this.j=new L(a);pe(this,this.j)}
ab(cw,J);cw.prototype.subscribe=function(a,b,c){return this.i()?0:this.j.subscribe(a,b,c)};
cw.prototype.m=function(a,b){this.i()||this.j.oa.apply(this.j,arguments)};function dw(a,b,c){cw.call(this);this.l=a;this.destination=b;this.id=c}
t(dw,cw);dw.prototype.va=function(a,b){this.i()||this.l.va(this.destination,this.id,a,b)};
dw.prototype.C=function(){this.destination=this.l=null;cw.prototype.C.call(this)};function ew(a,b,c){J.call(this);this.destination=a;this.origin=c;this.j=$p(window,"message",this.l.bind(this));this.connection=new dw(this,a,b);pe(this,this.connection)}
t(ew,J);ew.prototype.va=function(a,b,c,d){this.i()||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(tg(a),this.origin))};
ew.prototype.l=function(a){var b;if(b=!this.i())if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.i()||c.m("command",b.command,b.data,a.origin))}};
ew.prototype.C=function(){aq(this.j);this.destination=null;J.prototype.C.call(this)};function fw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||vb(b);this.assets=a.assets||{};this.attrs=a.attrs||vb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
fw.prototype.clone=function(){var a=new fw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ra(c)?a[b]=vb(c):a[b]=c}return a};var gw=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function hw(a){a=a||"";if(window.spf){var b=a.match(gw);spf.style.load(a,b?b[1]:"",void 0)}else iw(a)}
function iw(a){var b=jw(a),c=document.getElementById(b),d=c&&fv(c,"loaded");d||c&&!d||(c=kw(a,b,function(){fv(c,"loaded")||(dv(c),pq(b),Sk($a(qq,b),0))}))}
function kw(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Lb(a);gc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function jw(a){var b=ef("A");Fb("This URL is never added to the DOM");fc(b,new Ob(a,Pb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+kc(a)}
;function lw(){J.call(this);this.j=[]}
t(lw,J);lw.prototype.C=function(){for(;this.j.length;){var a=this.j.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.C.call(this)};function mw(){lw.apply(this,arguments)}
t(mw,lw);function nw(a,b,c,d){J.call(this);var e=this;this.v=b;this.webPlayerContextConfig=d;this.da=!1;this.api={};this.W=this.s=null;this.K=new L;this.j={};this.R=this.X=this.elementId=this.qa=this.config=null;this.P=!1;this.m=this.F=null;this.ka={};this.Pa=["onReady"];this.lastError=null;this.Ea=NaN;this.J={};this.Qa=new mw(this);this.T=0;this.l=this.o=a;pe(this,this.K);ow(this);pw(this);pe(this,this.Qa);c?this.T=Sk(function(){e.loadNewVideoConfig(c)},0):d&&(qw(this),rw(this))}
t(nw,J);l=nw.prototype;l.getId=function(){return this.v};
l.loadNewVideoConfig=function(a){if(!this.i()){this.T&&(Tk(this.T),this.T=0);var b=a||{};b instanceof fw||(b=new fw(b));this.config=b;this.setConfig(a);rw(this);this.isReady()&&sw(this)}};
function qw(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.l)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.qa=a;this.config=tw(a);qw(this);if(!this.X){var b;this.X=uw(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.l&&(this.l.style.width=Jh(Number(b)||b)),(a=a.height)&&this.l&&(this.l.style.height=Jh(Number(a)||a))};
function sw(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function vw(a){var b=!0,c=ww(a);c&&a.config&&(a=xw(a),b=fv(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function rw(a){if(!a.i()&&!a.P){var b=vw(a);if(b&&"html5"===(ww(a)?"html5":null))a.R="html5",a.isReady()||yw(a);else if(zw(a),a.R="html5",b&&a.m&&a.o)a.o.appendChild(a.m),yw(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.F=function(){c=!0;var d=Aw(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?tw(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig);yw(a)};
a.P=!0;b?a.F():(jv(xw(a),a.F),(b=Bw(a))&&hw(b),Cw(a)&&!c&&z("yt.player.Application.create",null))}}}
function ww(a){var b=df(a.elementId);!b&&a.l&&a.l.querySelector&&(b=a.l.querySelector("#"+a.elementId));return b}
function yw(a){if(!a.i()){var b=ww(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.P=!1;if(!Aw(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Dw(a)}else a.Ea=Sk(function(){yw(a)},50)}}
function Dw(a){ow(a);a.da=!0;var b=ww(a);if(b){a.s=Ew(a,b,"addEventListener");a.W=Ew(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Ew(a,b,f))}}for(var g in a.j)a.j.hasOwnProperty(g)&&a.s&&a.s(g,a.j[g]);sw(a);a.X&&a.X(a.api);a.K.oa("onReady",a.api)}
function Ew(a,b,c){var d=b[c];return function(){var e=Ma.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Gr(f))}}}
function ow(a){a.da=!1;if(a.W)for(var b in a.j)a.j.hasOwnProperty(b)&&a.W(b,a.j[b]);for(var c in a.J)a.J.hasOwnProperty(c)&&Tk(Number(c));a.J={};a.s=null;a.W=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.qa};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.da};
function pw(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){pq("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){pq("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=uw(this,b);d&&(0<=gb(this.Pa,a)||this.j[a]||(b=Fw(this,a),this.s&&this.s(a,b)),this.K.subscribe(a,d),"onReady"===a&&this.isReady()&&Sk(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.i()||(b=uw(this,b))&&oi(this.K,a,b)};
function uw(a,b){var c=b;if("string"===typeof b){if(a.ka[b])return a.ka[b];c=function(){var d=Ma.apply(0,arguments),e=B(b);if(e)try{e.apply(y,d)}catch(f){Fr(f)}};
a.ka[b]=c}return c?c:null}
function Fw(a,b){var c="ytPlayer"+b+a.v;a.j[b]=c;y[c]=function(d){var e=Sk(function(){if(!a.i()){try{a.K.oa(b,null!=d?d:void 0)}catch(h){Gr(new S("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.J,g=String(e);g in f&&delete f[g]}},0);
sb(a.J,String(e))};
return c}
l.getPlayerType=function(){return this.R||(ww(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function zw(a){a.cancel();ow(a);a.R=null;a.config&&(a.config.loaded=!1);var b=ww(a);b&&(vw(a)||!Cw(a)?a.m=b:(b&&b.destroy&&b.destroy(),a.m=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.F&&pv(xw(this),this.F);Tk(this.Ea);this.P=!1};
l.C=function(){zw(this);if(this.m&&this.config&&this.m.destroy)try{this.m.destroy()}catch(b){Fr(b)}this.ka=null;for(var a in this.j)this.j.hasOwnProperty(a)&&(y[this.j[a]]=null);this.qa=this.config=this.api=null;delete this.o;delete this.l;J.prototype.C.call(this)};
function Cw(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function xw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Bw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Aw(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Fk(c||"","&")[b]}
function tw(a){for(var b={},c=p(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?vb(e):e}return b}
;var Gw={},Hw="player_uid_"+(1E9*Math.random()>>>0);function Iw(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?df(d):d;var e=Hw+"_"+Ua(d),f=Gw[e];if(f&&c)return Jw(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new nw(d,e,a,b);Gw[e]=f;pq("player-added",f.api);qe(f,function(){delete Gw[f.getId()]});
return f.api}
function Jw(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Kw=null,Lw=null,Mw=null;function Nw(){Ow()}
function Pw(){Ow()}
function Ow(){var a=Kw.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function Qw(a,b,c){a="ST-"+kc(a).toString(36);b=b?tc(b):"";c=c||5;ms()&&il(a,b,c)}
;function Rw(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=M("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=M("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=oc(window.location.href);g&&f.push(g);g=oc(d);if(0<=gb(f,g)||!g&&0==d.lastIndexOf("/",0))if(P("autoescape_tempdata_url")&&(f=document.createElement("a"),fc(f,d),d=f.href),d&&(d=pc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Yr()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
Qw(d,b,h)}else Qw(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var q=void 0===q?window:q;c=q.location;a=yc(a,k)+m;var r=void 0===r?Ih:r;a:{r=void 0===r?Ih:r;for(k=0;k<r.length;++k)if(m=r[k],m instanceof Gh&&m.isValid(a)){r=new Ob(a,Pb);break a}r=void 0}c.href=Qb(r||Sb)}return!0}
;z("yt.setConfig",pk);z("yt.config.set",pk);z("yt.setMsg",cs);z("yt.msgs.set",cs);z("yt.logging.errors.log",Fr);
z("writeEmbed",function(){var a=M("PLAYER_CONFIG");if(!a){var b=M("PLAYER_VARS");b&&(a={args:b})}vs(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=M("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);P("embeds_js_api_set_1p_cookie")&&(c=Kk(window.location.href),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));Ut();if((c=M("WEB_PLAYER_CONTEXT_CONFIGS"))&&
"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c){c=c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Kk(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}Kw=Iw(a,c,!1)}else Kw=Iw(a);Kw.addEventListener("onVideoDataChange",Nw);Kw.addEventListener("onReady",Pw);a=M("POST_MESSAGE_ID","player");M("ENABLE_JS_API")?Mw=new Yv(Kw):M("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Lw=new ew(window.parent,
a,b),Mw=new bw(Kw,Lw.connection));uv();P("ytidb_create_logger_embed_killswitch")||bm();a={};Mv||(Mv=new Lv);Mv.install((a.flush_logs={callback:function(){Hq()}},a));
P("embeds_web_enable_new_nwl")?Ko():So();P("ytidb_clear_embedded_player")&&Qh.S(function(){var e;if(!Cu){Fs||(Fs=new Cs);var f=Fs;var g={xb:Bu,mc:Au};f.providers.set(g.xb,g);g={Lb:{feedbackEndpoint:Qs(wu),modifyChannelNotificationPreferenceEndpoint:Qs(xu),playlistEditEndpoint:Qs(yu),subscribeEndpoint:Qs(uu),unsubscribeEndpoint:Qs(vu),webPlayerShareEntityServiceEndpoint:Qs(zu)}};var h=P("web_enable_client_location_service")?Ms.getInstance():void 0,k={};h&&(k.client_location=h);if(void 0===m){ws.i||
(ws.i=new ws);var m=ws.i}void 0===e&&(e=f.resolve(Bu));iu(g,e,m,k);m={xb:nu,nc:hu.i};f.providers.set(m.xb,m);Cu=hu.i}cv()})});
var Sw=xk(function(){Zt();var a=ll.getInstance(),b=ol(119),c=1<window.devicePixelRatio;if(document.body&&bi(document.body,"exp-invert-logo"))if(c&&!bi(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!bi(d,"inverted-hdpi")){var e=$h(d);ai(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&bi(document.body,"inverted-hdpi")&&ci();if(b!=c){b="f"+(Math.floor(119/31)+1);d=pl(b)||0;d=c?d|67108864:d&-67108865;0==d?delete kl[b]:(c=d.toString(16),
kl[b]=c.toString());c=!0;P("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.i;d=[];for(var f in kl)d.push(f+"="+encodeURIComponent(String(kl[f])));il(b,d.join("&"),63072E3,a.j,c)}Mu.i||(Mu.i=new Mu);a=Mu.i;f=16623;var g=void 0===g?{}:g;Object.values(ds).includes(f)||(Gr(new S("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.i.push({rootVe:f,key:g.key||""});a.o=[];a.N=[];g.Ob?Pu(a,f,g):Qu(a,f,g)}),Tw=xk(function(){Kw&&Kw.sendAbandonmentPing&&Kw.sendAbandonmentPing();
M("PL_ATT")&&Av.dispose();for(var a=Qh,b=0,c=qv.length;b<c;b++)a.fa(qv[b]);qv.length=0;ov("//static.doubleclick.net/instream/ad_status.js");rv=!1;pk("DCLKSTAT",0);oe(Mw,Lw);Kw&&(Kw.removeEventListener("onVideoDataChange",Nw),Kw.destroy())});
window.addEventListener?(window.addEventListener("load",Sw),window.addEventListener("pagehide",Tw)):window.attachEvent&&(window.attachEvent("onload",Sw),window.attachEvent("onunload",Tw));z("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||Bv);z("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||Cv);z("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||vv);z("yt.player.exports.navigate",B("yt.player.exports.navigate")||Rw);
z("yt.util.activity.init",B("yt.util.activity.init")||eq);z("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||hq);z("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||fq);}).call(this);
