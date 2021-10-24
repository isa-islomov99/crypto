(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function t(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
t("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ha(a){if(!(a instanceof Array)){a=u(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ia="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ja=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ia(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ka;
if("function"==typeof Object.setPrototypeOf)ka=Object.setPrototypeOf;else{var la;a:{var ma={a:!0},na={};try{na.__proto__=ma;la=na.a;break a}catch(a){}la=!1}ka=la?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var oa=ka;
function v(a,b){a.prototype=ia(b.prototype);a.prototype.constructor=a;if(oa)oa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.O=b.prototype}
function pa(){this.A=!1;this.l=null;this.i=void 0;this.h=1;this.o=this.m=0;this.C=this.j=null}
function qa(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
pa.prototype.B=function(a){this.i=a};
function ra(a,b){a.j={Za:b,bb:!0};a.h=a.m||a.o}
pa.prototype.return=function(a){this.j={return:a};this.h=this.o};
function w(a,b,c){a.h=c;return{value:b}}
pa.prototype.u=function(a){this.h=a};
function sa(a,b,c){a.m=b;void 0!=c&&(a.o=c)}
function ta(a){a.m=0;var b=a.j.Za;a.j=null;return b}
function ua(a){a.C=[a.j];a.m=0;a.o=0}
function va(a){var b=a.C.splice(0)[0];(b=a.j=a.j||b)?b.bb?a.h=a.m||a.o:void 0!=b.u&&a.o<b.u?(a.h=b.u,a.j=null):a.h=a.o:a.h=0}
function wa(a){this.h=new pa;this.i=a}
function xa(a,b){qa(a.h);var c=a.h.l;if(c)return ya(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Aa(a)}
function ya(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.A=!1,e;var f=e.value}catch(g){return a.h.l=null,ra(a.h,g),Aa(a)}a.h.l=null;d.call(a.h,f);return Aa(a)}
function Aa(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.A=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ra(a.h,c)}a.h.A=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.bb)throw b.Za;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ba(a){this.next=function(b){qa(a.h);a.h.l?b=ya(a,a.h.l.next,b,a.h.B):(a.h.B(b),b=Aa(a));return b};
this.throw=function(b){qa(a.h);a.h.l?b=ya(a,a.h.l["throw"],b,a.h.B):(ra(a.h,b),b=Aa(a));return b};
this.return=function(b){return xa(a,b)};
this[Symbol.iterator]=function(){return this}}
function x(a,b){b=new Ba(new wa(b));oa&&a.prototype&&oa(b,a.prototype);return b}
t("Reflect",function(a){return a?a:{}});
t("Reflect.construct",function(){return ja});
t("Reflect.setPrototypeOf",function(a){return a?a:oa?function(b,c){try{return oa(b,c),!0}catch(d){return!1}}:null});
function Ca(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
t("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Ca(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Ca(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Ca(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Ca(k,g)&&Ca(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Ca(k,g)&&Ca(k[g],this.h)?delete k[g][this.h]:!1};
return b});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return fa(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.data_[l];if(n&&Ca(h.data_,l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.entry),this.h.previous.next=l.entry,this.h.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ea(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ea(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
t("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ea(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
t("Object.setPrototypeOf",function(a){return a||oa});
var Fa="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Ca(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||Fa});
t("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.A=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.o()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.o=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.T),reject:g(this.o)}};
b.prototype.T=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ga(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.L(g):this.m(g)}};
b.prototype.L=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.ha(h,g):this.m(g)};
b.prototype.o=function(g){this.B(2,g)};
b.prototype.m=function(g){this.B(1,g)};
b.prototype.B=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.U();this.C()};
b.prototype.U=function(){var g=this;e(function(){if(g.J()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.J=function(){if(this.A)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.C=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ga=function(g){var h=this.l();g.ra(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,q){return"function"==typeof r?function(y){try{l(r(y))}catch(B){n(B)}}:q}
var l,n,p=new b(function(r,q){l=r;n=q});
this.ra(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.ra=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.A=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),n=l.next();!n.done;n=l.next())d(n.value).ra(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(y){return function(B){r[y]=B;q--;0==q&&l(r)}}
var r=[],q=0;do r.push(void 0),q++,d(k.value).ra(p(r.length-1),n),k=h.next();while(!k.done)})};
return b});
function Ga(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.entries",function(a){return a?a:function(){return Ga(this,function(b,c){return[b,c]})}});
t("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Ca(b,d)&&c.push([d,b[d]]);return c}});
t("Array.prototype.keys",function(a){return a?a:function(){return Ga(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return Ga(this,function(b,c){return c})}});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ea(this,b,"includes").indexOf(b,c||0)}});
t("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
t("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
t("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
t("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Ca(b,d)&&c.push(b[d]);return c}});
var z=this||self;function A(a,b,c){a=a.split(".");c=c||z;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function C(a,b){a=a.split(".");b=b||z;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ha(){}
function Ia(a){a.Ka=void 0;a.getInstance=function(){return a.Ka?a.Ka:a.Ka=new a}}
function Ja(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ka(a){var b=Ja(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function La(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Na(a){return Object.prototype.hasOwnProperty.call(a,Oa)&&a[Oa]||(a[Oa]=++Pa)}
var Oa="closure_uid_"+(1E9*Math.random()>>>0),Pa=0;function Qa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ra(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Sa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Sa=Qa:Sa=Ra;return Sa.apply(null,arguments)}
function Ta(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Ua(a,b){A(a,b,void 0)}
function D(a,b){function c(){}
c.prototype=b.prototype;a.O=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Gm=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Va(a){return a}
;function Wa(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Wa);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.rb=b)}
D(Wa,Error);Wa.prototype.name="CustomError";function Xa(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Ya(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Za=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},E=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},$a=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},ab=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},bb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
E(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function cb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function db(a,b){b=Za(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function eb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function fb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ka(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function gb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function hb(a){var b=ib,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function jb(a){for(var b in a)return!1;return!0}
function kb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function lb(){var a=F("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function mb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function nb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function ob(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=ob(a[c]);return b}
var pb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function qb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<pb.length;f++)c=pb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var rb;function sb(){if(void 0===rb){var a=null,b=z.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Va,createScript:Va,createScriptURL:Va})}catch(c){z.console&&z.console.error(c.message)}rb=a}else rb=a}return rb}
;function tb(a,b){this.h=a===ub&&b||""}
tb.prototype.X=!0;tb.prototype.W=function(){return this.h};
function vb(a){return new tb(ub,a)}
var ub={};vb("");var wb={};function xb(a){this.h=wb===wb?a:"";this.X=!0}
xb.prototype.W=function(){return this.h.toString()};
xb.prototype.toString=function(){return this.h.toString()};function yb(a,b){this.h=b===zb?a:""}
m=yb.prototype;m.X=!0;m.W=function(){return this.h.toString()};
m.Ja=!0;m.Fa=function(){return 1};
m.toString=function(){return this.h+""};
function Ab(a){if(a instanceof yb&&a.constructor===yb)return a.h;Ja(a);return"type_error:TrustedResourceUrl"}
var zb={};function Bb(a){var b=sb();a=b?b.createScriptURL(a):a;return new yb(a,zb)}
;var Cb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Db=/&/g,Eb=/</g,Fb=/>/g,Gb=/"/g,Hb=/'/g,Ib=/\x00/g,Jb=/[\x00&<>"']/;function Kb(a,b){this.h=b===Lb?a:""}
m=Kb.prototype;m.X=!0;m.W=function(){return this.h.toString()};
m.Ja=!0;m.Fa=function(){return 1};
m.toString=function(){return this.h.toString()};
function Mb(a){if(a instanceof Kb&&a.constructor===Kb)return a.h;Ja(a);return"type_error:SafeUrl"}
var Ob=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),Pb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Qb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Lb={},Rb=new Kb("about:invalid#zClosurez",Lb);var Sb;a:{var Tb=z.navigator;if(Tb){var Ub=Tb.userAgent;if(Ub){Sb=Ub;break a}}Sb=""}function H(a){return-1!=Sb.indexOf(a)}
;function Vb(){return H("Firefox")||H("FxiOS")}
function Wb(){return(H("Chrome")||H("CriOS"))&&!H("Edge")}
;var Xb={};function Yb(a,b,c){this.h=c===Xb?a:"";this.i=b;this.X=this.Ja=!0}
Yb.prototype.Fa=function(){return this.i};
Yb.prototype.W=function(){return this.h.toString()};
Yb.prototype.toString=function(){return this.h.toString()};
function Zb(a,b){var c=sb();a=c?c.createHTML(a):a;return new Yb(a,b,Xb)}
;function $b(a,b){b instanceof Kb||b instanceof Kb||(b="object"==typeof b&&b.X?b.W():String(b),Qb.test(b)||(b="about:invalid#zClosurez"),b=new Kb(b,Lb));a.href=Mb(b)}
function ac(a,b){a.rel="stylesheet";a.href=Ab(b).toString();(b=bc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function cc(){return bc("script[nonce]",void 0)}
var dc=/^[\w+/_-]+[=]{0,2}$/;function bc(a,b){b=(b||z).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&dc.test(a)?a:"":""}
;function ec(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var fc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function gc(a){return a?decodeURI(a):a}
function hc(a){return gc(a.match(fc)[3]||null)}
function ic(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)ic(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function jc(a){var b=[],c;for(c in a)ic(c,a[c],b);return b.join("&")}
function kc(a,b){b=jc(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var lc=/#|$/;function I(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function mc(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;function nc(a){nc[" "](a);return a}
nc[" "]=Ha;var oc=H("Opera"),pc=H("Trident")||H("MSIE"),qc=H("Edge"),rc=H("Gecko")&&!(-1!=Sb.toLowerCase().indexOf("webkit")&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),sc=-1!=Sb.toLowerCase().indexOf("webkit")&&!H("Edge"),tc=H("Android");function uc(){var a=z.document;return a?a.documentMode:void 0}
var vc;a:{var wc="",xc=function(){var a=Sb;if(rc)return/rv:([^\);]+)(\)|;)/.exec(a);if(qc)return/Edge\/([\d\.]+)/.exec(a);if(pc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(sc)return/WebKit\/(\S+)/.exec(a);if(oc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
xc&&(wc=xc?xc[1]:"");if(pc){var yc=uc();if(null!=yc&&yc>parseFloat(wc)){vc=String(yc);break a}}vc=wc}var zc=vc,Ac;if(z.document&&pc){var Bc=uc();Ac=Bc?Bc:parseInt(zc,10)||void 0}else Ac=void 0;var Cc=Ac;Vb();var Dc=mc()||H("iPod"),Ec=H("iPad");!H("Android")||Wb()||Vb();Wb();var Fc=H("Safari")&&!(Wb()||H("Coast")||H("Opera")||H("Edge")||H("Edg/")||H("OPR")||Vb()||H("Silk")||H("Android"))&&!(mc()||H("iPad")||H("iPod"));var Gc={},Hc=null;
function Ic(a,b){Ka(a);void 0===b&&(b=0);if(!Hc){Hc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Gc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Hc[h]&&(Hc[h]=g)}}}b=Gc[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Jc="function"===typeof Uint8Array;function Kc(a,b,c){if(null!=a)return"object"===typeof a?Jc&&a instanceof Uint8Array?c(a):Lc(a,b,c):b(a)}
function Lc(a,b,c){if(Array.isArray(a)){for(var d=Array(a.length),e=0;e<a.length;e++)d[e]=Kc(a[e],b,c);Array.isArray(a)&&a.Fb&&Mc(d);return d}d={};for(e in a)d[e]=Kc(a[e],b,c);return d}
function Nc(a){return"number"===typeof a?isFinite(a)?a:String(a):a}
function Oc(a){return new Uint8Array(a)}
function Pc(a){return a}
var Qc={Fb:{value:!0,configurable:!0}};function Mc(a){Array.isArray(a)&&!Object.isFrozen(a)&&Object.defineProperties(a,Qc);return a}
;function Rc(a,b){this.h=a;this.i=b;this.map={};this.j=!0;if(0<this.h.length){for(a=0;a<this.h.length;a++){b=this.h[a];var c=b[0];this.map[c.toString()]=new Sc(c,b[1])}this.j=!0}}
m=Rc.prototype;m.isFrozen=function(){return!1};
m.toJSON=function(){var a=this.P(!1);return Lc(a,Nc,Ic)};
m.P=function(a){if(this.j){if(this.i){var b=this.map,c;for(c in b)if(Object.prototype.hasOwnProperty.call(b,c)){var d=b[c].h;d&&d.P(a)}}}else{this.h.length=0;b=Tc(this);b.sort();for(c=0;c<b.length;c++){d=this.map[b[c]];var e=d.h;e&&e.P(a);this.h.push([d.key,d.value])}this.j=!0}return this.h};
m.clear=function(){this.map={};this.j=!1};
m.entries=function(){var a=[],b=Tc(this);b.sort();for(var c=0;c<b.length;c++){var d=this.map[b[c]];a.push([d.key,Uc(this,d)])}return new Vc(a)};
m.keys=function(){var a=[],b=Tc(this);b.sort();for(var c=0;c<b.length;c++)a.push(this.map[b[c]].key);return new Vc(a)};
m.values=function(){var a=[],b=Tc(this);b.sort();for(var c=0;c<b.length;c++)a.push(Uc(this,this.map[b[c]]));return new Vc(a)};
m.forEach=function(a,b){var c=Tc(this);c.sort();for(var d=0;d<c.length;d++){var e=this.map[c[d]];a.call(b,Uc(this,e),e.key,this)}};
m.set=function(a,b){var c=new Sc(a);this.i?(c.h=b,c.value=b.P(!1)):c.value=b;this.map[a.toString()]=c;this.j=!1;return this};
function Uc(a,b){return a.i?(b.h||(b.h=new a.i(b.value),a.isFrozen()&&null(b.h)),b.h):b.value}
m.get=function(a){if(a=this.map[a.toString()])return Uc(this,a)};
m.has=function(a){return a.toString()in this.map};
function Tc(a){a=a.map;var b=[],c;for(c in a)Object.prototype.hasOwnProperty.call(a,c)&&b.push(c);return b}
Rc.prototype[Symbol.iterator]=function(){return this.entries()};
function Sc(a,b){this.key=a;this.value=b;this.h=void 0}
function Vc(a){this.i=0;this.h=a}
Vc.prototype.next=function(){return this.i<this.h.length?{done:!1,value:this.h[this.i++]}:{done:!0,value:void 0}};
Vc.prototype[Symbol.iterator]=function(){return this};var Wc;function Xc(a,b,c){var d=Wc;Wc=null;a||(a=d);d=this.constructor.Km;a||(a=d?[d]:[]);this.l=d?0:-1;this.h=null;this.i=a;a:{d=this.i.length;a=d-1;if(d&&(d=this.i[a],!(null===d||"object"!=typeof d||Array.isArray(d)||Jc&&d instanceof Uint8Array))){this.o=a-this.l;this.j=d;break a}void 0!==b&&-1<b?(this.o=Math.max(b,a+1-this.l),this.j=null):this.o=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)a=c[b],a<this.o?(a+=this.l,(d=this.i[a])?Mc(d):this.i[a]=Yc):(Zc(this),(d=this.j[a])?Mc(d):this.j[a]=Yc)}
var Yc=Object.freeze(Mc([]));function Zc(a){var b=a.o+a.l;a.i[b]||(a.j=a.i[b]={})}
function $c(a,b,c){return-1===b?null:(void 0===c?0:c)||b>=a.o?a.j?a.j[b]:void 0:a.i[b+a.l]}
function ad(a,b,c){a.h||(a.h={});if(b in a.h)return a.h[b];var d=$c(a,b);d||(d=Mc([]),bd(a,b,d));c=new Rc(d,c);return a.h[b]=c}
function bd(a,b,c,d){(void 0===d?0:d)||b>=a.o?(Zc(a),a.j[b]=c):a.i[b+a.l]=c}
function cd(a,b,c,d){if(-1===c)return null;a.h||(a.h={});a.h[c]||(d=$c(a,c,void 0===d?!1:d))&&(a.h[c]=new b(d));return a.h[c]}
function dd(a,b,c){a.h||(a.h={});var d=a.h[c];if(!d){var e=void 0===e?!1:e;d=$c(a,c,e);null==d&&(d=Yc);d===Yc&&(d=Mc([]),bd(a,c,d,e));e=d;d=[];for(var f=0;f<e.length;f++)d[f]=new b(e[f]);a.h[c]=d}return d}
Xc.prototype.toJSON=function(){var a=this.P(!1);return Lc(a,Nc,Ic)};
Xc.prototype.P=function(a){if(this.h)for(var b in this.h){var c=this.h[b];if(Array.isArray(c))for(var d=0;d<c.length;d++)c[d]&&c[d].P(a);else c&&c.P(a)}return this.i};
Xc.prototype.toString=function(){return this.P(!1).toString()};
Xc.prototype.clone=function(){var a=this.constructor,b=Lc(this.P(!1),Pc,Oc);Wc=b;a=new a(b);Wc=null;ed(a,this);return a};
function ed(a,b){b.m&&(a.m=b.m.slice());var c=b.h;if(c){b=b.j;var d={},e;for(e in c){var f=c[e];if(f){var g=!(!b||!b[e]),h=+e;if(Array.isArray(f)){if(f.length)for(g=dd(a,f[0].constructor,h),h=0;h<Math.min(g.length,f.length);h++)ed(g[h],f[h])}else f instanceof Rc?f.i&&(d.Ba=ad(a,h,f.i),f.forEach(function(k){return function(l,n){return ed(k.Ba.get(n),l)}}(d))):(g=cd(a,f.constructor,h,g))&&ed(g,f)}d={Ba:d.Ba}}}}
;var fd=window;vb("csi.gstatic.com");vb("googleads.g.doubleclick.net");vb("pagead2.googlesyndication.com");vb("partner.googleadservices.com");vb("pubads.g.doubleclick.net");vb("securepubads.g.doubleclick.net");vb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var gd={};function hd(){}
function id(a){this.h=a}
v(id,hd);id.prototype.toString=function(){return this.h};
var jd=new id("about:invalid#zTSz",gd);function kd(a){this.isValid=a}
function ld(a){return new kd(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var md=[ld("data"),ld("http"),ld("https"),ld("mailto"),ld("ftp"),new kd(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function nd(a){if(a instanceof hd)if(a instanceof id)a=a.h;else throw Error("");else a=Mb(a);return a}
;function od(a,b){a.src=Ab(b);var c;b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document;var d=null===(c=b.querySelector)||void 0===c?void 0:c.call(b,"script[nonce]");(c=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function pd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=pd.prototype;m.clone=function(){return new pd(this.x,this.y)};
m.equals=function(a){return a instanceof pd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function qd(a,b){this.width=a;this.height=b}
m=qd.prototype;m.clone=function(){return new qd(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function rd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function sd(a,b){gb(b,function(c,d){c&&"object"==typeof c&&c.X&&(c=c.W());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:td.hasOwnProperty(d)?a.setAttribute(td[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var td={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function ud(a,b,c){var d=arguments,e=document,f=d[1],g=vd(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):sd(g,f));2<d.length&&wd(e,g,d);return g}
function wd(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Ka(f)||La(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(La(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}E(g?eb(f):f,d)}}}
function vd(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function xd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function yd(a){var b=zd;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Ad(){var a=[];yd(function(b){a.push(b)});
return a}
var zd={lc:"allow-forms",mc:"allow-modals",nc:"allow-orientation-lock",oc:"allow-pointer-lock",pc:"allow-popups",qc:"allow-popups-to-escape-sandbox",sc:"allow-presentation",tc:"allow-same-origin",uc:"allow-scripts",wc:"allow-top-navigation",xc:"allow-top-navigation-by-user-activation"},Bd=Ya(function(){return Ad()});
function Cd(){var a=Dd(),b={};E(Bd(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Dd(){var a=void 0===a?document:a;var b="IFRAME";"application/xhtml+xml"===(null==a?void 0:a.contentType)&&(b=b.toLowerCase());return a.createElement(b)}
;function Ed(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Fd=(new Date).getTime();function Gd(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Hd(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var r=g,q=0;64>q;q+=4)r[q/4]=p[q]<<24|p[q+1]<<16|p[q+2]<<8|p[q+3];for(q=16;80>q;q++)p=r[q-3]^r[q-8]^r[q-14]^r[q-16],r[q]=(p<<1|p>>>31)&4294967295;p=e[0];var y=e[1],B=e[2],G=e[3],R=e[4];for(q=0;80>q;q++){if(40>q)if(20>q){var P=G^y&(B^G);var K=1518500249}else P=y^B^G,K=1859775393;else 60>q?(P=y&B|G&(y|B),K=2400959708):(P=y^B^G,K=3395469782);P=((p<<5|p>>>27)&4294967295)+P+R+K+r[q]&4294967295;R=G;G=B;B=(y<<30|y>>>2)&4294967295;y=p;p=P}e[0]=e[0]+p&4294967295;e[1]=e[1]+y&4294967295;e[2]=
e[2]+B&4294967295;e[3]=e[3]+G&4294967295;e[4]=e[4]+R&4294967295}
function c(p,r){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var q=[],y=0,B=p.length;y<B;++y)q.push(p.charCodeAt(y));p=q}r||(r=p.length);q=0;if(0==l)for(;q+64<r;)b(p.slice(q,q+64)),q+=64,n+=64;for(;q<r;)if(f[l++]=p[q++],n++,64==l)for(l=0,b(f);q+64<r;)b(p.slice(q,q+64)),q+=64,n+=64}
function d(){var p=[],r=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var q=63;56<=q;q--)f[q]=r&255,r>>>=8;b(f);for(q=r=0;5>q;q++)for(var y=24;0<=y;y-=8)p[r++]=e[q]>>y&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,tb:function(){for(var p=d(),r="",q=0;q<p.length;q++)r+="0123456789ABCDEF".charAt(Math.floor(p[q]/16))+"0123456789ABCDEF".charAt(p[q]%16);return r}}}
;function Id(a,b,c){var d=String(z.location.href);return d&&a&&b?[b,Jd(Gd(d),a,c||null)].join(" "):null}
function Jd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],E(d,function(h){e.push(h)}),Kd(e.join(" "));
var f=[],g=[];E(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];E(d,function(h){e.push(h)});
a=Kd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Kd(a){var b=Hd();b.update(a);return b.tb().toLowerCase()}
;var Ld={};function Md(a){this.h=a||{cookie:""}}
m=Md.prototype;m.isEnabled=function(){if(!z.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{La:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Pm;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.La}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Cb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{La:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=Cb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Nd=new Md("undefined"==typeof document?null:document);function Od(a){return!!Ld.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Pd(a){a=void 0===a?!1:a;var b=z.__SAPISID||z.__APISID||z.__3PSAPISID||z.__OVERRIDE_SID;Od(a)&&(b=b||z.__1PSAPISID);if(b)return!0;var c=new Md(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");Od(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Qd(a,b,c,d){(a=z[a])||(a=(new Md(document)).get(b));return a?Id(a,c,d):null}
function Rd(a){var b=void 0===b?!1:b;var c=Gd(String(z.location.href)),d=[];if(Pd(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?z.__SAPISID:z.__APISID;e||(e=new Md(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Id(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Od(b)&&((b=Qd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Qd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Sd(){this.data_=[];this.h=-1}
Sd.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Sd.prototype.get=function(a){return!!this.data_[a]};
function Td(a){-1==a.h&&(a.h=bb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Ud(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Ud.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Vd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Wd;
function Xd(){var a=z.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=vd(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Sa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!H("Trident")&&!H("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Va;c.Va=null;e()}};
return function(e){d.next={Va:e};d=d.next;b.port2.postMessage(0)}}return function(e){z.setTimeout(e,0)}}
;function Yd(a){z.setTimeout(function(){throw a;},0)}
;function Zd(){this.i=this.h=null}
Zd.prototype.add=function(a,b){var c=$d.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Zd.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var $d=new Ud(function(){return new ae},function(a){return a.reset()});
function ae(){this.next=this.scope=this.h=null}
ae.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
ae.prototype.reset=function(){this.next=this.scope=this.h=null};function be(a,b){ce||de();ee||(ce(),ee=!0);fe.add(a,b)}
var ce;function de(){if(z.Promise&&z.Promise.resolve){var a=z.Promise.resolve(void 0);ce=function(){a.then(ge)}}else ce=function(){var b=ge;
"function"!==typeof z.setImmediate||z.Window&&z.Window.prototype&&!H("Edge")&&z.Window.prototype.setImmediate==z.setImmediate?(Wd||(Wd=Xd()),Wd(b)):z.setImmediate(b)}}
var ee=!1,fe=new Zd;function ge(){for(var a;a=fe.remove();){try{a.h.call(a.scope)}catch(b){Yd(b)}Vd($d,a)}ee=!1}
;function he(a,b){this.h=a[z.Symbol.iterator]();this.i=b;this.j=0}
he.prototype[Symbol.iterator]=function(){return this};
he.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function ie(a,b){return new he(a,b)}
;function je(){this.blockSize=-1}
;function ke(){this.blockSize=-1;this.blockSize=64;this.h=[];this.o=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
D(ke,je);ke.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function le(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
ke.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.i;d<b;){if(0==f)for(;d<=c;)le(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){le(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){le(this,e);f=0;break}}this.i=f;this.l+=b}};
ke.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;le(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function me(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||z.$googDebugFname||b}catch(g){e="Not available",c=!0}b=ne(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,oe[c])c=oe[c];else{c=String(c);if(!oe[c]){var f=/function\s+([^\(]+)/m.exec(c);oe[c]=f?f[1]:"[Anonymous]"}c=oe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function ne(a,b){b||(b={});b[pe(a)]=!0;var c=a.stack||"";(a=a.rb)&&!b[pe(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=ne(a,b));return c}
function pe(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var oe={};function qe(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function re(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ka(d)?re.apply(null,d):qe(d)}}
;function J(){this.h=this.h;this.o=this.o}
J.prototype.h=!1;J.prototype.dispose=function(){this.h||(this.h=!0,this.D())};
function se(a,b){a.h?b():(a.o||(a.o=[]),a.o.push(b))}
J.prototype.D=function(){if(this.o)for(;this.o.length;)this.o.shift()()};function te(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function ue(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function ve(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:te(a).match(/\S+/g)||[],b=0<=Za(a,b));return b}
function we(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):ve(a,"inverted-hdpi")&&ue(a,Array.prototype.filter.call(a.classList?a.classList:te(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var xe="StopIteration"in z?z.StopIteration:{message:"StopIteration",stack:""};function ye(){}
ye.prototype.R=function(){throw xe;};
ye.prototype.M=function(){return this};function ze(a){if(a instanceof Ae||a instanceof Be||a instanceof Ce)return a;if("function"==typeof a.R)return new Ae(function(){return De(a)});
if("function"==typeof a[Symbol.iterator])return new Ae(function(){return a[Symbol.iterator]()});
if("function"==typeof a.M)return new Ae(function(){return De(a.M())});
throw Error("Not an iterator or iterable.");}
function De(a){if(!(a instanceof ye))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.R();break}catch(d){if(d!==xe)throw d;b=!0}return{value:c,done:b}}}}
function Ae(a){this.i=a}
Ae.prototype.M=function(){return new Be(this.i())};
Ae.prototype[Symbol.iterator]=function(){return new Ce(this.i())};
Ae.prototype.h=function(){return new Ce(this.i())};
function Be(a){this.i=a}
v(Be,ye);Be.prototype.R=function(){var a=this.i.next();if(a.done)throw xe;return a.value};
Be.prototype[Symbol.iterator]=function(){return new Ce(this.i)};
Be.prototype.h=function(){return new Ce(this.i)};
function Ce(a){Ae.call(this,function(){return a});
this.j=a}
v(Ce,Ae);Ce.prototype.next=function(){return this.j.next()};function Ee(a,b){this.i={};this.h=[];this.ca=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Ee)for(c=Fe(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function Fe(a){Ge(a);return a.h.concat()}
m=Ee.prototype;m.has=function(a){return He(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Ie;Ge(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Ie(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.ca=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return He(this.i,a)?(delete this.i[a],--this.size,this.ca++,this.h.length>2*this.size&&Ge(this),!0):!1};
function Ge(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];He(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],He(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return He(this.i,a)?this.i[a]:b};
m.set=function(a,b){He(this.i,a)||(this.size+=1,this.h.push(a),this.ca++);this.i[a]=b};
m.forEach=function(a,b){for(var c=Fe(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new Ee(this)};
m.keys=function(){return ze(this.M(!0)).h()};
m.values=function(){return ze(this.M(!1)).h()};
m.entries=function(){var a=this;return ie(this.keys(),function(b){return[b,a.get(b)]})};
m.M=function(a){Ge(this);var b=0,c=this.ca,d=this,e=new ye;e.R=function(){if(c!=d.ca)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)throw xe;var f=d.h[b++];return a?f:d.i[f]};
return e};
function He(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function Je(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Je.prototype.stopPropagation=function(){this.j=!0};
Je.prototype.preventDefault=function(){this.defaultPrevented=!0};var Ke=function(){if(!z.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{z.addEventListener("test",Ha,b),z.removeEventListener("test",Ha,b)}catch(c){}return a}();function Le(a,b){Je.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
D(Le,Je);var Me={2:"touch",3:"pen",4:"mouse"};
Le.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(rc){a:{try{nc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Me[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Le.O.preventDefault.call(this)};
Le.prototype.stopPropagation=function(){Le.O.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Le.prototype.preventDefault=function(){Le.O.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Ne="closure_listenable_"+(1E6*Math.random()|0);var Oe=0;function Pe(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.wa=e;this.key=++Oe;this.la=this.qa=!1}
function Qe(a){a.la=!0;a.listener=null;a.proxy=null;a.src=null;a.wa=null}
;function Re(a){this.src=a;this.listeners={};this.h=0}
Re.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Se(a,b,d,e);-1<g?(b=a[g],c||(b.qa=!1)):(b=new Pe(b,this.src,f,!!d,e),b.qa=c,a.push(b));return b};
Re.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Se(e,b,c,d);return-1<b?(Qe(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Te(a,b){var c=b.type;c in a.listeners&&db(a.listeners[c],b)&&(Qe(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Se(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.la&&f.listener==b&&f.capture==!!c&&f.wa==d)return e}return-1}
;var Ue="closure_lm_"+(1E6*Math.random()|0),Ve={},We=0;function Xe(a,b,c,d,e){if(d&&d.once)Ye(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Xe(a,b[f],c,d,e);else c=Ze(c),a&&a[Ne]?a.Y(b,c,La(d)?!!d.capture:!!d,e):$e(a,b,c,!1,d,e)}
function $e(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=La(e)?!!e.capture:!!e,h=af(a);h||(a[Ue]=h=new Re(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=bf();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ke||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(cf(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");We++}}
function bf(){function a(c){return b.call(a.src,a.listener,c)}
var b=df;return a}
function Ye(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ye(a,b[f],c,d,e);else c=Ze(c),a&&a[Ne]?a.i.add(String(b),c,!0,La(d)?!!d.capture:!!d,e):$e(a,b,c,!0,d,e)}
function ef(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ef(a,b[f],c,d,e);else(d=La(d)?!!d.capture:!!d,c=Ze(c),a&&a[Ne])?a.i.remove(String(b),c,d,e):a&&(a=af(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Se(b,c,d,e)),(c=-1<a?b[a]:null)&&ff(c))}
function ff(a){if("number"!==typeof a&&a&&!a.la){var b=a.src;if(b&&b[Ne])Te(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(cf(c),d):b.addListener&&b.removeListener&&b.removeListener(d);We--;(c=af(b))?(Te(c,a),0==c.h&&(c.src=null,b[Ue]=null)):Qe(a)}}}
function cf(a){return a in Ve?Ve[a]:Ve[a]="on"+a}
function df(a,b){if(a.la)a=!0;else{b=new Le(b,this);var c=a.listener,d=a.wa||a.src;a.qa&&ff(a);a=c.call(d,b)}return a}
function af(a){a=a[Ue];return a instanceof Re?a:null}
var gf="__closure_events_fn_"+(1E9*Math.random()>>>0);function Ze(a){if("function"===typeof a)return a;a[gf]||(a[gf]=function(b){return a.handleEvent(b)});
return a[gf]}
;function hf(){J.call(this);this.i=new Re(this);this.L=this;this.A=null}
D(hf,J);hf.prototype[Ne]=!0;hf.prototype.addEventListener=function(a,b,c,d){Xe(this,a,b,c,d)};
hf.prototype.removeEventListener=function(a,b,c,d){ef(this,a,b,c,d)};
function jf(a,b){var c=a.A;if(c){var d=[];for(var e=1;c;c=c.A)d.push(c),++e}a=a.L;c=b.type||b;"string"===typeof b?b=new Je(b,a):b instanceof Je?b.target=b.target||a:(e=b,b=new Je(c,a),qb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=kf(g,c,!0,b)&&e}b.j||(g=b.h=a,e=kf(g,c,!0,b)&&e,b.j||(e=kf(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=kf(g,c,!1,b)&&e}
hf.prototype.D=function(){hf.O.D.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Qe(d[e]);delete a.listeners[c];a.h--}}this.A=null};
hf.prototype.Y=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function kf(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.la&&g.capture==c){var h=g.listener,k=g.wa||g.src;g.qa&&Te(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function lf(a){mf();return Bb(a)}
var mf=Ha;function nf(a){var b=[];of(new pf,a,b);return b.join("")}
function pf(){}
function of(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),of(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),qf(d,c),c.push(":"),of(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":qf(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var rf={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},sf=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function qf(a,b){b.push('"',a.replace(sf,function(c){var d=rf[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),rf[c]=d);return d}),'"')}
;function tf(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function uf(a){this.h=0;this.A=void 0;this.l=this.i=this.j=null;this.o=this.m=!1;if(a!=Ha)try{var b=this;a.call(void 0,function(c){vf(b,2,c)},function(c){vf(b,3,c)})}catch(c){vf(this,3,c)}}
function wf(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
wf.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var xf=new Ud(function(){return new wf},function(a){a.reset()});
function yf(a,b,c){var d=xf.get();d.i=a;d.onRejected=b;d.context=c;return d}
function zf(a){return new uf(function(b,c){c(a)})}
uf.prototype.then=function(a,b,c){return Af(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
uf.prototype.$goog_Thenable=!0;function Bf(a,b){return Af(a,null,b,void 0)}
uf.prototype.cancel=function(a){if(0==this.h){var b=new Cf(a);be(function(){Ef(this,b)},this)}};
function Ef(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Ef(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Ff(c),Gf(c,e,3,b)))}a.j=null}else vf(a,3,b)}
function Hf(a,b){a.i||2!=a.h&&3!=a.h||If(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Af(a,b,c,d){var e=yf(null,null,null);e.h=new uf(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Cf?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Hf(a,e);return e.h}
uf.prototype.C=function(a){this.h=0;vf(this,2,a)};
uf.prototype.J=function(a){this.h=0;vf(this,3,a)};
function vf(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.C,f=a.J;if(d instanceof uf){Hf(d,yf(e||Ha,f||null,a));var g=!0}else if(tf(d))d.then(e,f,a),g=!0;else{if(La(d))try{var h=d.then;if("function"===typeof h){Jf(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.A=c,a.h=b,a.j=null,If(a),3!=b||c instanceof Cf||Kf(a,c))}}
function Jf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function If(a){a.m||(a.m=!0,be(a.B,a))}
function Ff(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
uf.prototype.B=function(){for(var a;a=Ff(this);)Gf(this,a,this.h,this.A);this.m=!1};
function Gf(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.o;a=a.j)a.o=!1;if(b.h)b.h.j=null,Lf(b,c,d);else try{b.j?b.i.call(b.context):Lf(b,c,d)}catch(e){Mf.call(null,e)}Vd(xf,b)}
function Lf(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Kf(a,b){a.o=!0;be(function(){a.o&&Mf.call(null,b)})}
var Mf=Yd;function Cf(a){Wa.call(this,a)}
D(Cf,Wa);Cf.prototype.name="cancel";function L(a){J.call(this);this.A=1;this.l=[];this.m=0;this.i=[];this.j={};this.B=!!a}
D(L,J);m=L.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.A;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.A=e+3;d.push(e);return e};
function Nf(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.ka(b)}}
m.ka=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ha):(c&&db(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.da=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.B)for(e=0;e<c.length;e++){var g=c[e];Of(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h;e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.ka(c)}}return 0!=e}return!1};
function Of(a,b,c){be(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.ka,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.D=function(){L.O.D.call(this);this.clear();this.l.length=0};function Pf(a){this.h=a}
Pf.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,nf(b))};
Pf.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Pf.prototype.remove=function(a){this.h.remove(a)};function Qf(a){this.h=a}
D(Qf,Pf);function Rf(a){this.data=a}
function Sf(a){return void 0===a||a instanceof Rf?a:new Rf(a)}
Qf.prototype.set=function(a,b){Qf.O.set.call(this,a,Sf(b))};
Qf.prototype.i=function(a){a=Qf.O.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Qf.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Tf(a){this.h=a}
D(Tf,Qf);Tf.prototype.set=function(a,b,c){if(b=Sf(b)){if(c){if(c<Date.now()){Tf.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Tf.O.set.call(this,a,b)};
Tf.prototype.i=function(a){var b=Tf.O.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Tf.prototype.remove.call(this,a);else return b}};function Uf(){}
;function Vf(){}
D(Vf,Uf);Vf.prototype[Symbol.iterator]=function(){return ze(this.M(!0)).h()};
Vf.prototype.clear=function(){var a=Array.from(this);a=u(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Wf(a){this.h=a}
D(Wf,Vf);m=Wf.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.M=function(a){var b=0,c=this.h,d=new ye;d.R=function(){if(b>=c.length)throw xe;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function Xf(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
D(Xf,Wf);function Yf(a,b){this.i=a;this.h=null;var c;if(c=pc)c=!(9<=Number(Cc));if(c){Zf||(Zf=new Ee);this.h=Zf.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Zf.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
D(Yf,Vf);var $f={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Zf=null;function ag(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return $f[b]})}
m=Yf.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(ag(a),b);bg(this)};
m.get=function(a){a=this.h.getAttribute(ag(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(ag(a));bg(this)};
m.M=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new ye;d.R=function(){if(b>=c.length)throw xe;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);bg(this)};
function bg(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function cg(a,b){this.i=a;this.h=b+"::"}
D(cg,Vf);cg.prototype.set=function(a,b){this.i.set(this.h+a,b)};
cg.prototype.get=function(a){return this.i.get(this.h+a)};
cg.prototype.remove=function(a){this.i.remove(this.h+a)};
cg.prototype.M=function(a){var b=this.i.M(!0),c=this,d=new ye;d.R=function(){for(var e=b.R();e.substr(0,c.h.length)!=c.h;)e=b.R();return a?e.substr(c.h.length):c.i.get(e)};
return d};function dg(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;function eg(a){Xc.call(this,a,92,fg)}
v(eg,Xc);var fg=[82];var gg,hg,ig,jg=z.window,kg=(null===(gg=null===jg||void 0===jg?void 0:jg.yt)||void 0===gg?void 0:gg.config_)||(null===(hg=null===jg||void 0===jg?void 0:jg.ytcfg)||void 0===hg?void 0:hg.data_)||{},lg=(null===(ig=null===jg||void 0===jg?void 0:jg.ytcfg)||void 0===ig?void 0:ig.obfuscatedData_)||[];new eg(lg);A("yt.config_",kg,void 0);A("yt.configJspb_",lg,void 0);function M(a){for(var b=0;b<arguments.length;++b);dg(kg,arguments)}
function F(a,b){return a in kg?kg[a]:b}
;var mg=[];function ng(a){mg.forEach(function(b){return b(a)})}
function og(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){pg(b)}}:a}
function pg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=F("ERRORS",[]),e.push([a,"ERROR",b,c,d]),M("ERRORS",e));ng(a)}
function qg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=F("ERRORS",[]),e.push([a,"WARNING",b,c,d]),M("ERRORS",e))}
;var rg=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",rg,void 0);function sg(a){dg(rg,arguments)}
;function N(a){a=tg(a);return"string"===typeof a&&"false"===a?!1:!!a}
function ug(a,b){a=tg(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function tg(a){var b=F("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:F("EXPERIMENT_FLAGS",{})[a]}
;var vg=0,wg=sc?"webkit":rc?"moz":pc?"ms":oc?"o":"";A("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++vg},void 0);var xg={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function yg(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in xg||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function zg(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
yg.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
yg.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
yg.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ib=z.ytEventsEventsListeners||{};A("ytEventsEventsListeners",ib,void 0);var Ag=z.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Ag,void 0);
function Bg(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return hb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=La(e[4])&&La(d)&&mb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Cg=Ya(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Dg(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Bg(a,b,c,d);if(e)return e;e=++Ag.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new yg(h);if(!xd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new yg(h);
h.currentTarget=a;return c.call(a,h)};
g=og(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Cg()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ib[e]=[a,b,c,g,d];return e}
function Eg(a){a&&("string"==typeof a&&(a=[a]),E(a,function(b){if(b in ib){var c=ib[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Cg()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ib[b]}}))}
;var Fg=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Gg(a,b){"function"===typeof a&&(a=og(a));return window.setTimeout(a,b)}
function Hg(a){window.clearTimeout(a)}
;function Ig(a){this.C=a;this.i=null;this.m=0;this.B=null;this.A=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.L=Dg(window,"mousemove",Sa(this.T,this));a=Sa(this.J,this);"function"===typeof a&&(a=og(a));this.U=window.setInterval(a,25)}
D(Ig,J);Ig.prototype.T=function(a){void 0===a.h&&zg(a);var b=a.h;void 0===a.i&&zg(a);this.i=new pd(b,a.i)};
Ig.prototype.J=function(){if(this.i){var a=Fg();if(0!=this.m){var b=this.B,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.A)/this.A)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.C();this.A=d}this.m=a;this.B=this.i;this.l=(this.l+1)%4}};
Ig.prototype.D=function(){window.clearInterval(this.U);Eg(this.L)};function Jg(){}
function Kg(a,b){return Lg(a,0,b)}
function Mg(a,b){return Lg(a,1,b)}
;function Ng(){Jg.apply(this,arguments)}
v(Ng,Jg);function Og(){Ng.h||(Ng.h=new Ng);return Ng.h}
function Lg(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Gg(a,c||0)}
function Pg(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):Hg(a)}}
Ng.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
Ng.prototype.pause=function(){var a=C("yt.scheduler.instance.pause");a&&a()};Og();var Qg={};
function Rg(a){var b=void 0===a?{}:a;a=void 0===b.Lb?!1:b.Lb;b=void 0===b.vb?!0:b.vb;if(null==C("_lact",window)){var c=parseInt(F("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Sg();Dg(document,"keydown",Sg);Dg(document,"keyup",Sg);Dg(document,"mousedown",Sg);Dg(document,"mouseup",Sg);a?Dg(window,"touchmove",function(){Tg("touchmove",200)},{passive:!0}):(Dg(window,"resize",function(){Tg("resize",200)}),b&&Dg(window,"scroll",function(){Tg("scroll",200)}));
new Ig(function(){Tg("mouse",100)});
Dg(document,"touchstart",Sg,{passive:!0});Dg(document,"touchend",Sg,{passive:!0})}}
function Tg(a,b){Qg[a]||(Qg[a]=!0,Mg(function(){Sg();Qg[a]=!1},b))}
function Sg(){null==C("_lact",window)&&Rg();var a=Date.now();A("_lact",a,window);-1==C("_fact",window)&&A("_fact",a,window);(a=C("ytglobal.ytUtilActivityCallback_"))&&a()}
function Ug(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function Vg(){var a=Wg;C("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a,void 0)}
function Xg(a){A("yt.ads.biscotti.lastId_",a,void 0)}
;var Yg=/^[\w.]*$/,Zg={q:!0,search_query:!0};function $g(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=ah(f[0]||""),h=ah(f[1]||"");g in c?Array.isArray(c[g])?fb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String($g);k.args=[{key:l,value:f[1],query:a,method:bh==n?"unchanged":n}];Zg.hasOwnProperty(l)||qg(k)}}return c}
var bh=String($g);function ch(a){var b=[];gb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];E(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function dh(a){"?"==a.charAt(0)&&(a=a.substr(1));return $g(a,"&")}
function eh(){var a=window.location.href;return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),dh(1<a.length?a[1]:a[0])):{}}
function fh(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=dh(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return kc(a,e)+d}
function gh(a){if(!b)var b=window.location.href;var c=a.match(fc)[1]||null,d=hc(a);c&&d?(a=a.match(fc),b=b.match(fc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?hc(b)==d&&(Number(b.match(fc)[4]||null)||null)==(Number(a.match(fc)[4]||null)||null):!0;return a}
function ah(a){return a&&a.match(Yg)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function hh(a){var b=ih;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Fd;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ma){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?fd:g;try{var h=g.history.length}catch(Ma){h=0}e.u_his=h;var k;e.u_h=null==(k=fd.screen)?void 0:k.height;var l;e.u_w=null==(l=fd.screen)?void 0:l.width;var n;e.u_ah=null==(n=fd.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=fd.screen)?void 0:p.availWidth;var r;e.u_cd=null==(r=fd.screen)?void 0:r.colorDepth}catch(Ma){}h=b.h;try{var q=h.screenX;var y=h.screenY}catch(Ma){}try{var B=h.outerWidth;var G=h.outerHeight}catch(Ma){}try{var R=h.innerWidth;var P=h.innerHeight}catch(Ma){}try{var K=h.screenLeft;var ea=h.screenTop}catch(Ma){}try{R=h.innerWidth,P=h.innerHeight}catch(Ma){}try{var Df=h.screen.availWidth;var bn=h.screen.availTop}catch(Ma){}q=[K,ea,q,y,Df,bn,B,G,R,P];y=b.h.top;try{var Nb=(y||window).document,za=
"CSS1Compat"==Nb.compatMode?Nb.documentElement:Nb.body;var Da=(new qd(za.clientWidth,za.clientHeight)).round()}catch(Ma){Da=new qd(-12245933,-12245933)}Nb=Da;Da={};za=new Sd;z.SVGElement&&z.document.createElementNS&&za.set(0);y=Cd();y["allow-top-navigation-by-user-activation"]&&za.set(1);y["allow-popups-to-escape-sandbox"]&&za.set(2);z.crypto&&z.crypto.subtle&&za.set(3);z.TextDecoder&&z.TextEncoder&&za.set(4);za=Td(za);Da.bc=za;Da.bih=Nb.height;Da.biw=Nb.width;Da.brdim=q.join();b=b.i;b=(Da.vis={visible:1,
hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Da.wgl=!!fd.WebGLRenderingContext,Da);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var ih=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return ch(hh(a))},void 0);Date.now();var jh="XMLHttpRequest"in z?function(){return new XMLHttpRequest}:null;
function kh(){if(!jh)return null;var a=jh();return"open"in a?a:null}
function lh(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var mh={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},nh="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ha("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),oh=!1;
function ph(a,b){b=void 0===b?{}:b;var c=gh(a),d=N("web_ajax_ignore_global_headers_if_set"),e;for(e in mh){var f=F(mh[e]);!f||!c&&hc(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!hc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!hc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!hc(a))b["X-YouTube-Ad-Signals"]=ch(hh(void 0));return b}
function qh(a){var b=window.location.search,c=hc(a);N("debug_handle_relative_url_for_query_forward_killswitch")||c||!gh(a)||(c=document.location.hostname);var d=gc(a.match(fc)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=dh(b),f={};E(nh,function(g){e[g]&&(f[g]=e[g])});
return fh(a,f||{},!1)}
function rh(a,b){var c=b.format||"JSON";a=sh(a,b);var d=th(a,b),e=!1,f=uh(a,function(k){if(!e){e=!0;h&&Hg(h);var l=lh(k),n=null,p=400<=k.status&&500>k.status,r=500<=k.status&&600>k.status;if(l||p||r)n=vh(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||z;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,k,n)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=Gg(function(){e||(e=!0,f.abort(),Hg(h),g.call(b.context||z,f))},b.timeout)}return f}
function sh(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=F("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=fh(a,b||{},!0);return a}
function th(a,b){var c=F("XSRF_FIELD_NAME",void 0),d=F("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=F("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||hc(a)&&!b.withCredentials&&hc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=dh(e),qb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):jc(e));f=e||f&&!jb(f);!oh&&f&&
"POST"!=b.method&&(oh=!0,pg(Error("AJAX request with postData should use POST")));return e}
function vh(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,qg(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?wh(a):null)e={},E(a.getElementsByTagName("*"),function(g){e[g.tagName]=xh(g)})}d&&yh(e);
return e}
function yh(a){if(La(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;vb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Zb(a[b],null);a[c]=d}else yh(a[b])}}
function wh(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function xh(a){var b="";E(a.childNodes,function(c){b+=c.nodeValue});
return b}
function uh(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&og(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=kh();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;N("debug_forward_web_query_parameters")&&(a=qh(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=ph(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var zh=Dc||Ec;function Ah(a){var b=Sb;return b?0<=b.toLowerCase().indexOf(a):!1}
;var Bh={},Ch=0;
function Dh(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Ah("cobalt")){if(a){a instanceof Kb||(a="object"==typeof a&&a.X?a.W():String(a),Qb.test(a)?a=new Kb(a,Lb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Pb))&&Ob.test(b[1])?new Kb(a,Lb):null));b=Mb(a||Rb);if("about:invalid#zClosurez"===b||b.startsWith("data"))a="";else{if(b instanceof Yb)a=b;else{var f="object"==typeof b;a=null;f&&b.Ja&&(a=b.Fa());b=f&&b.X?b.W():String(b);Jb.test(b)&&(-1!=b.indexOf("&")&&(b=b.replace(Db,"&amp;")),-1!=b.indexOf("<")&&
(b=b.replace(Eb,"&lt;")),-1!=b.indexOf(">")&&(b=b.replace(Fb,"&gt;")),-1!=b.indexOf('"')&&(b=b.replace(Gb,"&quot;")),-1!=b.indexOf("'")&&(b=b.replace(Hb,"&#39;")),-1!=b.indexOf("\x00")&&(b=b.replace(Ib,"&#0;")));a=Zb(b,a)}a instanceof Yb&&a.constructor===Yb?a=a.h:(Ja(a),a="type_error:SafeHtml");a=encodeURIComponent(String(nf(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=ud("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))}}else if(e)uh(a,
b,"POST",e,d);else if(F("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)uh(a,b,"GET","",d);else{b:{try{var g=new Xa({url:a});if(g.j&&g.i||g.l){var h=gc(a.match(fc)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(lc);d:{for(c=0;0<=(c=a.indexOf("ri",c))&&c<l;){var n=a.charCodeAt(c-1);if(38==n||63==n){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var r=c;break d}}c+=3}r=-1}if(0>r)var q=null;else{var y=a.indexOf("&",r);if(0>y||y>l)y=l;r+=3;q=decodeURIComponent(a.substr(r,y-r).replace(/\+/g,
" "))}k="1"!==q}f=!k;break b}}catch(B){}f=!1}f?Eh(a)?(b&&b(),f=!0):f=!1:f=!1;f||Fh(a,b)}}
function Gh(a,b,c){c=void 0===c?"":c;Eh(a,c)?b&&b():Dh(a,b,void 0,void 0,c)}
function Eh(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Fh(a,b){var c=new Image,d=""+Ch++;Bh[d]=c;c.onload=c.onerror=function(){b&&Bh[d]&&b();delete Bh[d]};
c.src=a}
;var Hh=z.ytPubsubPubsubInstance||new L,Ih=z.ytPubsubPubsubSubscribedKeys||{},Jh=z.ytPubsubPubsubTopicToKeys||{},Kh=z.ytPubsubPubsubIsSynchronous||{};function Lh(a,b){var c=Mh();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Ih[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Kh[a]?f():Gg(f,0)}catch(g){pg(g)}},void 0);
Ih[d]=!0;Jh[a]||(Jh[a]=[]);Jh[a].push(d);return d}return 0}
function Nh(a){var b=Mh();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),E(a,function(c){b.unsubscribeByKey(c);delete Ih[c]}))}
function Oh(a,b){var c=Mh();c&&c.publish.apply(c,arguments)}
function Ph(a){var b=Mh();if(b)if(b.clear(a),a)Qh(a);else for(var c in Jh)Qh(c)}
function Mh(){return z.ytPubsubPubsubInstance}
function Qh(a){Jh[a]&&(a=Jh[a],E(a,function(b){Ih[b]&&delete Ih[b]}),a.length=0)}
L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.ka;L.prototype.publish=L.prototype.da;L.prototype.clear=L.prototype.clear;A("ytPubsubPubsubInstance",Hh,void 0);A("ytPubsubPubsubTopicToKeys",Jh,void 0);A("ytPubsubPubsubIsSynchronous",Kh,void 0);A("ytPubsubPubsubSubscribedKeys",Ih,void 0);var Rh=window,O=Rh.ytcsi&&Rh.ytcsi.now?Rh.ytcsi.now:Rh.performance&&Rh.performance.timing&&Rh.performance.now&&Rh.performance.timing.navigationStart?function(){return Rh.performance.timing.navigationStart+Rh.performance.now()}:function(){return(new Date).getTime()};var Sh=ug("initial_gel_batch_timeout",2E3),Th=Math.pow(2,16)-1,Uh=void 0,Vh=0,Wh=0,Xh=0,Yh=!0,Zh=z.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",Zh,void 0);var $h=z.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",$h,void 0);
function ai(a,b){if("log_event"===a.endpoint){var c="";a.ta?c="visitorOnlyApprovedKey":a.cttAuthInfo&&($h[a.cttAuthInfo.token]=bi(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=Zh.get(c)||[];Zh.set(c,d);d.push(a.payload);b&&(Uh=new b);a=ug("tvhtml5_logging_max_batch")||ug("web_logging_max_batch")||100;b=O();d.length>=a?ci({writeThenSend:!0},N("flush_only_full_queue")?c:void 0):10<=b-Xh&&(di(),Xh=b)}}
function ei(a,b){if("log_event"===a.endpoint){var c="";a.ta?c="visitorOnlyApprovedKey":a.cttAuthInfo&&($h[a.cttAuthInfo.token]=bi(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=new Map;d.set(c,[a.payload]);b&&(Uh=new b);return new uf(function(e){Uh&&Uh.isReady()?fi(d,e,{bypassNetworkless:!0},!0):e()})}}
function ci(a,b){a=void 0===a?{}:a;new uf(function(c){Hg(Vh);Hg(Wh);Wh=0;if(Uh&&Uh.isReady())if(void 0!==b){var d=new Map,e=Zh.get(b)||[];d.set(b,e);fi(d,c,a);Zh.delete(b)}else fi(Zh,c,a),Zh.clear();else di(),c()})}
function di(){N("web_gel_timeout_cap")&&!Wh&&(Wh=Gg(function(){ci({writeThenSend:!0})},6E4));
Hg(Vh);var a=F("LOGGING_BATCH_TIMEOUT",ug("web_gel_debounce_ms",1E4));N("shorten_initial_gel_batch_timeout")&&Yh&&(a=Sh);Vh=Gg(function(){ci({writeThenSend:!0})},a)}
function fi(a,b,c,d){var e=Uh;c=void 0===c?{}:c;var f=Math.round(O()),g=a.size;a=u(a);for(var h=a.next();!h.done;h=a.next()){var k=u(h.value);h=k.next().value;var l=k=k.next().value;k=ob({context:gi(e.config_||hi())});k.events=l;(l=$h[h])&&ii(k,h,l);delete $h[h];h="visitorOnlyApprovedKey"===h;ji(k,f,h);N("always_send_and_write")&&(c.writeThenSend=!1);N("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Gh("/generate_204");ki(e,"log_event",k,{retry:!0,onSuccess:function(){g--;
g||b()},
onError:function(){g--;g||b()},
gb:c,ta:h,Hm:!!d});Yh=!1}}
function ji(a,b,c){a.requestTimeMs=String(b);N("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=F("EVENT_ID",void 0))&&((c=F("BATCH_CLIENT_COUNTER",void 0)||0)||(c=Math.floor(Math.random()*Th/2)),c++,c>Th&&(c=1),M("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function ii(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function bi(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var li=z.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",li,void 0);
function mi(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||O());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=Ug();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};N("log_sequence_info_on_gel_web")&&d.ba&&(a=e.context,b=d.ba,li[b]=b in li?li[b]+1:0,a.sequence={index:li[b],groupKey:b},d.wb&&delete li[d.ba]);(d.Qm?ei:ai)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,ta:d.ta},c)}
;function ni(){if(!z.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return z.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":z.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":z.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":z.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function oi(a,b,c,d,e){Nd.set(""+a,b,{La:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
;var pi=C("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",pi,void 0);function qi(){this.h=F("ALT_PREF_COOKIE_NAME","PREF");this.i=F("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Nd.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(pi[d]=c.toString())}}}
qi.prototype.get=function(a,b){ri(a);si(a);a=void 0!==pi[a]?pi[a].toString():null;return null!=a?a:b?b:""};
qi.prototype.set=function(a,b){ri(a);si(a);if(null==b)throw Error("ExpectedNotNull");pi[a]=b.toString()};
qi.prototype.remove=function(a){ri(a);si(a);delete pi[a]};
qi.prototype.clear=function(){for(var a in pi)delete pi[a]};
function si(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function ri(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function ti(a){a=void 0!==pi[a]?pi[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ia(qi);var ui={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},vi={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function wi(){var a=z.navigator;return a?a.connection:void 0}
;function xi(){return"INNERTUBE_API_KEY"in kg&&"INNERTUBE_API_VERSION"in kg}
function hi(){return{innertubeApiKey:F("INNERTUBE_API_KEY",void 0),innertubeApiVersion:F("INNERTUBE_API_VERSION",void 0),yb:F("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),zb:F("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Bb:F("INNERTUBE_CONTEXT_HL",void 0),Ab:F("INNERTUBE_CONTEXT_GL",void 0),Cb:F("INNERTUBE_HOST_OVERRIDE",void 0)||"",Eb:!!F("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Db:!!F("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:F("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function gi(a){var b={client:{hl:a.Bb,gl:a.Ab,clientName:a.zb,clientVersion:a.innertubeContextClientVersion,configInfo:a.yb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=z.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=F("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=F("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=F("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===
d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});f=b.client.clientName;if("WEB"===f||"MWEB"===f||1===f||2===f){if(!N("web_include_display_mode_killswitch")){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=ni()}}else if(g=b.client.clientName,("WEB_REMIX"===g||76===g)&&!N("music_web_display_mode_killswitch")){var h;b.client.fb=null!=(h=b.client.fb)?h:{};b.client.fb.webDisplayMode=ni()}a.appInstallData&&
(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);F("DELEGATED_SESSION_ID")&&!N("pageid_as_header_web")&&(b.user={onBehalfOfUser:F("DELEGATED_SESSION_ID")});a:{if(h=wi()){a=ui[h.type||"unknown"]||"CONN_UNKNOWN";h=ui[h.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==h&&(a=h);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==h){a=h;break a}}a=void 0}a&&(b.client.connectionType=a);N("web_log_effective_connection_type")&&
(a=wi(),a=null!==a&&void 0!==a&&a.effectiveType?vi.hasOwnProperty(a.effectiveType)?vi[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&(b.client.effectiveConnectionType=a));a=Object;h=a.assign;g=b.client;f={};e=u(Object.entries(dh(F("DEVICE",""))));for(c=e.next();!c.done;c=e.next())d=u(c.value),c=d.next().value,d=d.next().value,"cbrand"===c?f.deviceMake=d:"cmodel"===c?f.deviceModel=d:"cbr"===c?f.browserName=d:"cbrver"===c?f.browserVersion=d:"cos"===c?f.osName=d:"cosver"===c?f.osVersion=
d:"cplatform"===c&&(f.platform=d);b.client=h.call(a,g,f);return b}
function yi(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||F("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Fm||F("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().Em:b=Rd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=F("SESSION_INDEX",0),N("pageid_as_header_web")&&(d["X-Goog-PageId"]=F("DELEGATED_SESSION_ID")));return d}
;function zi(a){a=Object.assign({},a);delete a.Authorization;var b=Rd();if(b){var c=new ke;c.update(F("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=Ic(c.digest(),3)}return a}
;function Ai(a){var b=new Xf;(b=b.isAvailable()?a?new cg(b,a):b:null)||(a=new Yf(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Tf(a):null;this.i=document.domain||window.location.hostname}
Ai.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(nf(b))}catch(f){return}else e=escape(b);oi(a,e,c,this.i)};
Ai.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Nd.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Ai.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Nd.remove(""+a,"/",void 0===b?"youtube.com":b)};var Bi;function Ci(){Bi||(Bi=new Ai("yt.innertube"));return Bi}
function Di(a,b,c,d){if(d)return null;d=Ci().get("nextId",!0)||1;var e=Ci().get("requests",!0)||{};e[d]={method:a,request:b,authState:zi(c),requestTime:Math.round(O())};Ci().set("nextId",d+1,86400,!0);Ci().set("requests",e,86400,!0);return d}
function Ei(a){var b=Ci().get("requests",!0)||{};delete b[a];Ci().set("requests",b,86400,!0)}
function Fi(a){var b=Ci().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(O())-d.requestTime)){var e=d.authState,f=zi(yi(!1));mb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(O())),ki(a,d.method,e,{}));delete b[c]}}Ci().set("requests",b,86400,!0)}}
;var Gi=function(){var a;return function(){a||(a=new Ai("ytidb"));return a}}();
function Hi(){var a;return null===(a=Gi())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
function Ii(a){var b=Hi();this.result={hasSucceededOnce:(null===b||void 0===b?void 0:b.hasSucceededOnce)||a};var c,d;null!==(c=Gi())&&void 0!==c&&c.h&&(null===(d=Gi())||void 0===d?void 0:d.set("LAST_RESULT_ENTRY_KEY",this.result,2592E3,!0))}
Ii.prototype.isSupported=function(){return this.result.hasSucceededOnce};var Ji=[],Ki=!1;function Li(a){Ki||(Ji.push({type:"ERROR",payload:a}),10<Ji.length&&Ji.shift())}
function Mi(a,b){Ki||(Ji.push({type:"EVENT",eventType:a,payload:b}),10<Ji.length&&Ji.shift())}
;function Ni(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(ha(c))}
v(Ni,Error);function Oi(){try{return Pi(),!0}catch(a){return!1}}
function Pi(){if(void 0!==F("DATASYNC_ID",void 0))return F("DATASYNC_ID",void 0);throw new Ni("Datasync ID not set","unknown");}
;function Qi(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Ri(a){return a.substr(0,a.indexOf(":"))||a}
;var Si={},Ti=(Si.AUTH_INVALID="No user identifier specified.",Si.EXPLICIT_ABORT="Transaction was explicitly aborted.",Si.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Si.MISSING_INDEX="Index not created.",Si.MISSING_OBJECT_STORE="Object store not created.",Si.DB_DELETED_BY_MISSING_OBJECT_STORE="Database is deleted because an expected object store was not created.",Si.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",Si.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",
Si.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Si.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Si.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Si),Ui={},Vi=(Ui.AUTH_INVALID="ERROR",Ui.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Ui.EXPLICIT_ABORT="IGNORED",Ui.IDB_NOT_SUPPORTED="ERROR",Ui.MISSING_INDEX="WARNING",Ui.MISSING_OBJECT_STORE="ERROR",Ui.DB_DELETED_BY_MISSING_OBJECT_STORE=
"WARNING",Ui.QUOTA_EXCEEDED="WARNING",Ui.QUOTA_MAYBE_EXCEEDED="WARNING",Ui.UNKNOWN_ABORT="WARNING",Ui.INCOMPATIBLE_DB_VERSION="WARNING",Ui),Wi={},Xi=(Wi.AUTH_INVALID=!1,Wi.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Wi.EXPLICIT_ABORT=!1,Wi.IDB_NOT_SUPPORTED=!1,Wi.MISSING_INDEX=!1,Wi.MISSING_OBJECT_STORE=!1,Wi.DB_DELETED_BY_MISSING_OBJECT_STORE=!1,Wi.QUOTA_EXCEEDED=!1,Wi.QUOTA_MAYBE_EXCEEDED=!0,Wi.UNKNOWN_ABORT=!0,Wi.INCOMPATIBLE_DB_VERSION=!1,Wi);
function Q(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Ti[a]:c;d=void 0===d?Vi[a]:d;e=void 0===e?Xi[a]:e;Ni.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Q.prototype)}
v(Q,Ni);function Yi(a){Q.call(this,"MISSING_OBJECT_STORE",{Hb:a},Ti.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,Yi.prototype)}
v(Yi,Q);function Zi(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Zi.prototype)}
v(Zi,Error);var $i=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function aj(a,b,c,d){b=Ri(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Q)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Q("QUOTA_EXCEEDED",a);if(Fc&&"UnknownError"===e.name)return new Q("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Zi)return new Q("MISSING_INDEX",Object.assign(Object.assign({},a),{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&$i.some(function(f){return e.message.includes(f)}))return new Q("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Q("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign(Object.assign({},a),{name:"IdbError",Mm:e.name})];e.level="WARNING";return e}
function bj(a,b,c){return new Q("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c}})}
;function cj(a){if(!a)throw Error();throw a;}
function dj(a){return a}
function ej(a){this.h=a}
function S(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
S.all=function(a){return new S(new ej(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={fa:0};f.fa<a.length;f={fa:f.fa},++f.fa)fj(S.resolve(a[f.fa]).then(function(g){return function(h){d[g.fa]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
S.resolve=function(a){return new S(new ej(function(b,c){a instanceof S?a.then(b,c):b(a)}))};
S.reject=function(a){return new S(new ej(function(b,c){c(a)}))};
S.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:dj,e=null!==b&&void 0!==b?b:cj;return new S(new ej(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){gj(c,c,d,f,g)}),c.onRejected.push(function(){hj(c,c,e,f,g)})):"FULFILLED"===c.state.status?gj(c,c,d,f,g):"REJECTED"===c.state.status&&hj(c,c,e,f,g)}))};
function fj(a,b){a.then(void 0,b)}
function gj(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof S?ij(a,b,f,d,e):d(f)}catch(g){e(g)}}
function hj(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof S?ij(a,b,f,d,e):d(f)}catch(g){e(g)}}
function ij(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof S?ij(a,b,f,d,e):d(f)},function(f){e(f)})}
;function jj(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function kj(a){return new Promise(function(b,c){jj(a,b,c)})}
function T(a){return new S(new ej(function(b,c){jj(a,b,c)}))}
;function lj(a,b){return new S(new ej(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function mj(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(O());this.i=!1}
m=mj.prototype;m.add=function(a,b,c){return nj(this,[a],{mode:"readwrite",K:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return nj(this,[a],{mode:"readwrite",K:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return nj(this,[a],{mode:"readonly",K:!0},function(c){return c.objectStore(a).count(b)})};
function oj(a,b,c){a=a.h.createObjectStore(b,c);return new pj(a)}
m.delete=function(a,b){return nj(this,[a],{mode:"readwrite",K:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return nj(this,[a],{mode:"readonly",K:!0},function(c){return c.objectStore(a).get(b)})};
function qj(a,b){return nj(a,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(c){c=c.objectStore("LogsRequestsStore");return T(c.h.put(b,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function nj(a,b,c,d){return I(a,function f(){var g=this,h,k,l,n,p,r,q,y,B,G,R,P;return x(f,function(K){switch(K.h){case 1:var ea={mode:"readonly",K:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?ea.mode=c:Object.assign(ea,c);h=ea;g.transactionCount++;k=h.K?3:1;l=0;case 2:if(n){K.u(3);break}l++;p=Math.round(O());sa(K,4);r=g.h.transaction(b,h.mode);ea=new rj(r);ea=sj(ea,d);return w(K,ea,6);case 6:return q=K.i,y=Math.round(O()),tj(g,p,y,l,void 0,b.join(),h),K.return(q);case 4:B=ta(K);G=Math.round(O());
R=aj(B,g.h.name,b.join(),g.h.version);if((P=R instanceof Q&&!R.h)||l>=k)tj(g,p,G,l,R,b.join(),h),n=R;K.u(2);break;case 3:return K.return(Promise.reject(n))}})})}
function tj(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Q&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Mi("QUOTA_EXCEEDED",{dbName:Ri(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Q&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),Mi("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),uj(a,!1,d,f,b,g.tag),Li(e)):uj(a,!0,d,f,b,g.tag)}
function uj(a,b,c,d,e,f){Mi("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function pj(a){this.h=a}
m=pj.prototype;m.add=function(a,b){return T(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return T(this.h.clear()).then(function(){})};
m.count=function(a){return T(this.h.count(a))};
function vj(a,b){return wj(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?vj(this,a):T(this.h.delete(a))};
m.get=function(a){return T(this.h.get(a))};
m.index=function(a){try{return new xj(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Zi(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function wj(a,b,c){a=a.h.openCursor(b.query,b.direction);return yj(a).then(function(d){return lj(d,c)})}
function rj(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=Q;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function sj(a,b){var c=new Promise(function(d,e){try{fj(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
rj.prototype.abort=function(){this.h.abort();this.i=!0;throw new Q("EXPLICIT_ABORT");};
rj.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new pj(a),this.j.set(a,b));return b};
function xj(a){this.h=a}
m=xj.prototype;m.count=function(a){return T(this.h.count(a))};
m.delete=function(a){return zj(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return T(this.h.get(a))};
m.getKey=function(a){return T(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function zj(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return yj(a).then(function(d){return lj(d,c)})}
function Aj(a,b){this.request=a;this.cursor=b}
function yj(a){return T(a).then(function(b){return b?new Aj(a,b):null})}
m=Aj.prototype;m.advance=function(a){this.cursor.advance(a);return yj(this.request)};
m.continue=function(a){this.cursor.continue(a);return yj(this.request)};
m.delete=function(){return T(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return T(this.cursor.update(a))};function Bj(a,b,c){return new Promise(function(d,e){function f(){r||(r=new mj(g.result,{closed:p}));return r}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.Wb,n=c.upgrade,p=c.closed,r;g.addEventListener("upgradeneeded",function(q){try{if(null===q.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");q.dataLoss&&"none"!==q.dataLoss&&Mi("IDB_DATA_CORRUPTED",{reason:q.dataLossMessage||"unknown reason",dbName:Ri(a)});var y=f(),B=new rj(g.transaction);
n&&n(y,function(G){return q.oldVersion<G&&q.newVersion>=G},B);
B.done.catch(function(G){e(G)})}catch(G){e(G)}});
g.addEventListener("success",function(){var q=g.result;k&&q.addEventListener("versionchange",function(){k(f())});
q.addEventListener("close",function(){Mi("IDB_UNEXPECTEDLY_CLOSED",{dbName:Ri(a),dbVersion:q.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Cj(a,b,c){c=void 0===c?{}:c;return Bj(a,b,c)}
function Dj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f,g;return x(d,function(h){e=self.indexedDB.deleteDatabase(a);f=b;(g=f.blocked)&&e.addEventListener("blocked",function(){g()});
return w(h,kj(e),0)})})}
;function Ej(a,b){this.name=a;this.options=b;this.l=!0;this.j=!1}
Ej.prototype.i=function(a,b,c){c=void 0===c?{}:c;return Cj(a,b,c)};
Ej.prototype.delete=function(a){a=void 0===a?{}:a;return Dj(this.name,a)};
function Fj(a,b){return new Q("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
Ej.prototype.open=function(){function a(){return I(c,function g(){var h,k,l,n=this,p,r,q,y,B;return x(g,function(G){switch(G.h){case 1:return l=null!==(h=Error().stack)&&void 0!==h?h:"",sa(G,2),w(G,n.i(n.name,n.options.version,e),4);case 4:p=G.i;a:{var R=n.options;for(var P=u(Object.keys(R.xa)),K=P.next();!K.done;K=P.next()){K=K.value;var ea=R.xa[K],Df=void 0===ea.Nb?Number.MAX_VALUE:ea.Nb;if(p.h.version>=ea.Ea&&!(p.h.version>=Df)&&!p.h.objectStoreNames.contains(K)){R=K;break a}}R=void 0}r=R;if(void 0===
r){G.u(5);break}if(n.j){G.u(6);break}n.j=!0;return w(G,n.delete(),7);case 7:return Li(new Q("DB_DELETED_BY_MISSING_OBJECT_STORE",{dbName:n.name,Hb:r})),G.return(a());case 6:throw new Yi(r);case 5:return G.return(p);case 2:q=ta(G);if(q instanceof DOMException?"VersionError"!==q.name:"DOMError"in self&&q instanceof DOMError?"VersionError"!==q.name:!(q instanceof Object&&"message"in q)||"An attempt was made to open a database using a lower version than the existing version."!==q.message){G.u(8);break}return w(G,
n.i(n.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),9);case 9:y=G.i;B=y.h.version;if(void 0!==n.options.version&&B>n.options.version+1)throw y.close(),n.l=!1,Fj(n,B);return G.return(y);case 8:throw b(),q instanceof Error&&!N("ytidb_async_stack_killswitch")&&(q.stack=q.stack+"\n"+l.substring(l.indexOf("\n")+1)),aj(q,n.name,"",null!==(k=n.options.version)&&void 0!==k?k:-1);}})})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw Fj(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Wb:b,upgrade:this.options.upgrade};return this.h=d=a()};var Gj=new Ej("YtIdbMeta",{xa:{databases:{Ea:1}},upgrade:function(a,b){b(1)&&oj(a,"databases",{keyPath:"actualName"})}});
function Hj(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,Gj.open(),2);d=e.i;return e.return(nj(d,["databases"],{K:!0,mode:"readwrite"},function(f){var g=f.objectStore("databases");return g.get(a.actualName).then(function(h){if(h?a.actualName!==h.actualName||a.publicName!==h.publicName||a.userIdentifier!==h.userIdentifier:1)return T(g.h.put(a,void 0)).then(function(){})})}))})})}
function Ij(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return a?w(e,Gj.open(),2):e.return();d=e.i;return e.return(d.delete("databases",a))})})}
function Jj(a){return I(this,function c(){var d,e;return x(c,function(f){return 1==f.h?(d=[],w(f,Gj.open(),2)):3!=f.h?(e=f.i,w(f,nj(e,["databases"],{K:!0,mode:"readonly"},function(g){d.length=0;return wj(g.objectStore("databases"),{},function(h){a(h.getValue())&&d.push(h.getValue());return h.continue()})}),3)):f.return(d)})})}
function Kj(){return Jj(function(a){return"LogsDatabaseV2"===a.publicName&&void 0!==a.userIdentifier})}
;var Lj,Mj=new function(){}(new function(){});
function Nj(){return I(this,function b(){var c,d,e;return x(b,function(f){switch(f.h){case 1:c=Hi();if(null===c||void 0===c?0:c.hasSucceededOnce)return f.return(new Ii(!0));var g;if(g=zh)g=/WebKit\/([0-9]+)/.exec(Sb),g=!!(g&&600<=parseInt(g[1],10));g&&(g=/WebKit\/([0-9]+)/.exec(Sb),g=!(g&&602<=parseInt(g[1],10)));if(g||qc)return f.return(new Ii(!1));try{if(d=self,!(d.indexedDB&&d.IDBIndex&&d.IDBKeyRange&&d.IDBObjectStore))return f.return(new Ii(!1))}catch(h){return f.return(new Ii(!1))}if(!("IDBTransaction"in
self&&"objectStoreNames"in IDBTransaction.prototype))return f.return(new Ii(!1));sa(f,2);e={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(f,Hj(e),4);case 4:return w(f,Ij("yt-idb-test-do-not-use"),5);case 5:return f.return(new Ii(!0));case 2:return ta(f),f.return(new Ii(!1))}})})}
function Oj(){if(void 0!==Lj)return Lj;Ki=!0;return Lj=Nj().then(function(a){Ki=!1;return a.isSupported()})}
function Pj(){return Oj().then(function(a){return a?Mj:void 0})}
;new function(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})};function Qj(a){if(!Oi())throw a=new Q("AUTH_INVALID",{dbName:a}),Li(a),a;var b=Pi();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Rj(a,b,c,d){var e;return I(this,function g(){var h,k,l,n,p;return x(g,function(r){switch(r.h){case 1:return h=null!==(e=Error().stack)&&void 0!==e?e:"",w(r,Pj(),2);case 2:k=r.i;if(!k)throw l=bj("openDbImpl",a,b),N("ytidb_async_stack_killswitch")||(l.stack=l.stack+"\n"+h.substring(h.indexOf("\n")+1)),Li(l),l;Qi(a);n=c?{actualName:a,publicName:a,userIdentifier:void 0}:Qj(a);sa(r,3);return w(r,Hj(n),5);case 5:return w(r,Cj(n.actualName,b,d),6);case 6:return r.return(r.i);case 3:return p=ta(r),
sa(r,7),w(r,Ij(n.actualName),9);case 9:r.h=8;r.m=0;break;case 7:ta(r);case 8:throw p;}})})}
function Sj(a,b,c){c=void 0===c?{}:c;return Rj(a,b,!1,c)}
function Tj(a,b,c){c=void 0===c?{}:c;return Rj(a,b,!0,c)}
function Uj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f;return x(d,function(g){if(1==g.h)return w(g,Pj(),2);if(3!=g.h){e=g.i;if(!e)return g.return();Qi(a);f=Qj(a);return w(g,Dj(f.actualName,b),3)}return w(g,Ij(f.actualName),0)})})}
function Vj(a,b){var c=this;a=a.map(function(d){return I(c,function f(){return x(f,function(g){return 1==g.h?w(g,Dj(d.actualName,b),2):w(g,Ij(d.actualName),0)})})});
return Promise.all(a).then(function(){})}
function Wj(){var a=void 0===a?{}:a;return I(this,function c(){var d,e;return x(c,function(f){if(1==f.h)return w(f,Pj(),2);if(3!=f.h){d=f.i;if(!d)return f.return();Qi("LogsDatabaseV2");return w(f,Kj(),3)}e=f.i;return w(f,Vj(e,a),0)})})}
function Xj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Pj(),2);if(3!=f.h){e=f.i;if(!e)return f.return();Qi(a);return w(f,Dj(a,b),3)}return w(f,Ij(a),0)})})}
;function Yj(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ja=function(){};
this.now=Date.now;this.nb=null!==(b=a.nb)&&void 0!==b?b:100;this.lb=null!==(c=a.lb)&&void 0!==c?c:1;this.jb=null!==(d=a.jb)&&void 0!==d?d:2592E6;this.hb=null!==(e=a.hb)&&void 0!==e?e:12E4;this.kb=null!==(f=a.kb)&&void 0!==f?f:5E3;this.databaseToken=null!==(g=a.databaseToken)&&void 0!==g?g:void 0;this.va=!!a.va;this.sa=null!==(h=a.sa)&&void 0!==h?h:.1;this.za=null!==(k=a.za)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.ja&&(this.ja=a.ja);this.F=a.F;this.cb=a.cb;this.G=a.G;this.I=
a.I;this.S=a.S;this.Oa=a.Oa;this.Na=a.Na;this.databaseToken&&(!this.F||this.F("networkless_logging"))&&Zj(this)}
function Zj(a){I(a,function c(){var d=this;return x(c,function(e){if(!d.databaseToken)return e.return();ak(d);d.I.H()&&d.ma();d.I.Y(d.Oa,d.ma.bind(d));d.I.Y(d.Na,d.Ua.bind(d));d.h=!0;return d.va&&Math.random()<=d.sa?w(e,d.G.sb(d.databaseToken),0):e.u(0)})})}
m=Yj.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.G.set(d,this.databaseToken).then(function(e){d.id=e;c.I.H()&&bk(c,d)}).catch(function(e){bk(c,d);
ck(c,e)})}else this.S(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.F&&this.F("nwl_skip_retry")&&(e.skipRetry=c);if(this.I.H()){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return I(d,function l(){var n=this,p;return x(l,function(r){if(1==r.h)return p=n,w(r,n.G.set(e,n.databaseToken).catch(function(q){ck(p,q)}),2);
f(g,h);r.h=0})})}}this.S(a,b,e.skipRetry)}else this.G.set(e,this.databaseToken).catch(function(g){d.S(a,b,e.skipRetry);
ck(d,g)})}else this.S(a,b,this.F&&this.F("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.G.ia(d.id,c.databaseToken):e=!0;c.I.aa&&c.F&&c.F("vss_network_hint")&&c.I.aa(!0);f(g,h)};
this.S(d.url,d.options);this.G.set(d,this.databaseToken).then(function(g){d.id=g;e&&c.G.ia(d.id,c.databaseToken)}).catch(function(g){ck(c,g)})}else this.S(a,b)};
m.ma=function(){var a=this;if(!this.databaseToken)throw bj("throttleSend");this.i||(this.i=Mg(function(){return I(a,function c(){var d=this,e;return x(c,function(f){if(1==f.h)return w(f,d.G.ab("NEW",d.databaseToken),2);if(3!=f.h)return e=f.i,e?w(f,bk(d,e),3):(d.Ua(),f.return());d.i&&(d.i=0,d.ma());f.h=0})})},this.nb))};
m.Ua=function(){Pg(this.i);this.i=0};
function bk(a,b){return I(a,function d(){var e=this,f,g;return x(d,function(h){switch(h.h){case 1:if(!e.databaseToken)throw f=bj("immediateSend"),f;if(void 0===b.id){h.u(2);break}return w(h,e.G.Gb(b.id,e.databaseToken),3);case 3:(g=h.i)?b=g:e.ja(Error("The request cannot be found in the database."));case 2:if(dk(e,b,e.jb)){h.u(4);break}e.ja(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){h.u(5);break}return w(h,e.G.ia(b.id,e.databaseToken),5);case 5:return h.return();
case 4:b.skipRetry||(b=ek(e,b));if(!b){h.u(0);break}if(!b.skipRetry||void 0===b.id){h.u(8);break}return w(h,e.G.ia(b.id,e.databaseToken),8);case 8:e.S(b.url,b.options,!!b.skipRetry),h.h=0}})})}
function ek(a,b){if(!a.databaseToken)throw bj("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){return I(a,function h(){var k=this,l,n;return x(h,function(p){switch(p.h){case 1:l=k;n=fk(f);if(!(k.F&&k.F("nwl_consider_error_code")&&n||k.F&&!k.F("nwl_consider_error_code")&&k.potentialEsfErrorCounter<=k.za)){p.u(2);break}if(!k.I.N){p.u(3);break}return w(p,k.I.N(),3);case 3:if(k.I.H()){p.u(2);break}c(e,f);if(!k.F||!k.F("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){p.u(6);break}return w(p,k.G.Pa(b.id,k.databaseToken,!1),6);case 6:return p.return();
case 2:if(k.F&&k.F("nwl_consider_error_code")&&!n&&k.potentialEsfErrorCounter>k.za)return p.return();k.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){p.u(8);break}return b.sendCount<k.lb?w(p,k.G.Pa(b.id,k.databaseToken),12):w(p,k.G.ia(b.id,k.databaseToken),8);case 12:Mg(function(){l.I.H()&&l.ma()},k.kb);
case 8:c(e,f),p.h=0}})})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return I(a,function h(){var k=this;return x(h,function(l){if(1==l.h)return void 0===(null===b||void 0===b?void 0:b.id)?l.u(2):w(l,k.G.ia(b.id,k.databaseToken),2);k.I.aa&&k.F&&k.F("vss_network_hint")&&k.I.aa(!0);d(e,f);l.h=0})})};
return b}
function dk(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function ak(a){if(!a.databaseToken)throw bj("retryQueuedRequests");a.G.ab("QUEUED",a.databaseToken).then(function(b){b&&!dk(a,b,a.hb)?Mg(function(){return I(a,function d(){var e=this;return x(d,function(f){if(1==f.h)return void 0===b.id?f.u(2):w(f,e.G.Pa(b.id,e.databaseToken),2);ak(e);f.h=0})})}):a.I.H()&&a.ma()})}
function ck(a,b){a.ob&&!a.I.H()?a.ob(b):a.handleError(b)}
function fk(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function gk(a,b){this.version=a;this.args=b}
;function hk(a,b){this.topic=a;this.h=b}
hk.prototype.toString=function(){return this.topic};var ik=C("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.ka;L.prototype.publish=L.prototype.da;L.prototype.clear=L.prototype.clear;A("ytPubsub2Pubsub2Instance",ik,void 0);var jk=C("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",jk,void 0);var kk=C("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",kk,void 0);var lk=C("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",lk,void 0);
A("ytPubsub2Pubsub2SkipSubKey",null,void 0);function mk(a,b){var c=nk();c&&c.publish.call(c,a.toString(),a,b)}
function ok(a){var b=pk,c=nk();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=C("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(jk[d])try{if(f&&b instanceof hk&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ca){var l=new h;h.ca=l.version}var n=h.ca}catch(p){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
eb(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){pg(p)}},lk[b.toString()]?C("yt.scheduler.instance")?Lg(g,1,void 0):Gg(g,0):g())});
jk[d]=!0;kk[b.toString()]||(kk[b.toString()]=[]);kk[b.toString()].push(d);return d}
function qk(){var a=rk,b=ok(function(c){a.apply(void 0,arguments);sk(b)});
return b}
function sk(a){var b=nk();b&&("number"===typeof a&&(a=[a]),E(a,function(c){b.unsubscribeByKey(c);delete jk[c]}))}
function nk(){return C("ytPubsub2Pubsub2Instance")}
;function tk(a,b){Ej.call(this,a,b);this.options=b;Qi(a)}
v(tk,Ej);function uk(a,b){var c;return function(){c||(c=new tk(a,b));return c}}
tk.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.Qa?Tj:Sj)(a,b,Object.assign({},c))};
tk.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Qa?Xj:Uj)(this.name,a)};
function vk(a,b){return uk(a,b)}
;var wk;
function xk(){if(wk)return wk();var a={};wk=vk("LogsDatabaseV2",{xa:(a.LogsRequestsStore={Ea:2},a),Qa:!1,upgrade:function(b,c,d){c(2)&&oj(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return wk()}
;function yk(a){return I(this,function c(){var d,e,f,g;return x(c,function(h){if(1==h.h)return d={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(h,xk().open(),2);if(3!=h.h)return e=h.i,f=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:F("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(h,qj(e,f),3);g=h.i;d.Xb=O();zk(d);return h.return(g)})})}
function Ak(a){return I(this,function c(){var d,e,f,g,h,k,l;return x(c,function(n){if(1==n.h)return d={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(n,xk().open(),2);if(3!=n.h)return e=n.i,f=F("INNERTUBE_CONTEXT_CLIENT_NAME",0),g=[a,f,0],h=[a,f,O()],k=IDBKeyRange.bound(g,h),l=void 0,w(n,nj(e,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(p){return zj(p.objectStore("LogsRequestsStore").index("newRequestV2"),{query:k,direction:"prev"},function(r){r.getValue()&&(l=r.getValue(),
"NEW"===a&&(l.status="QUEUED",r.update(l)))})}),3);
d.Xb=O();zk(d);return n.return(l)})})}
function Bk(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,xk().open(),2);d=e.i;return e.return(nj(d,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){if(h)return h.status="QUEUED",T(g.h.put(h,void 0)).then(function(){return h})})}))})})}
function Ck(a,b,c){c=void 0===c?!0:c;return I(this,function e(){var f;return x(e,function(g){if(1==g.h)return w(g,xk().open(),2);f=g.i;return g.return(nj(f,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(h){var k=h.objectStore("LogsRequestsStore");return k.get(a).then(function(l){return l?(l.status="NEW",c&&(l.sendCount+=1),T(k.h.put(l,void 0)).then(function(){return l})):S.resolve(void 0)})}))})})}
function Dk(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,xk().open(),2);d=e.i;return e.return(d.delete("LogsRequestsStore",a))})})}
function Ek(){return I(this,function b(){var c,d;return x(b,function(e){if(1==e.h)return w(e,xk().open(),2);c=e.i;d=O()-2592E6;return w(e,nj(c,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(f){return wj(f.objectStore("LogsRequestsStore"),{},function(g){if(g.getValue().timestamp<=d)return g.delete().then(function(){return g.continue()})})}),0)})})}
function Fk(){return I(this,function b(){return x(b,function(c){return w(c,Wj(),0)})})}
function zk(a){N("nwl_csi_killswitch")||.01>=Math.random()&&mk("nwl_transaction_latency_payload",a)}
;var Gk={},Hk=vk("ServiceWorkerLogsDatabase",{xa:(Gk.SWHealthLog={Ea:1},Gk),Qa:!0,upgrade:function(a,b){b(1)&&oj(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Ik(){return I(this,function b(){var c,d;return x(b,function(e){if(1==e.h)return N("web_clean_sw_logs_store")?w(e,Hk().open(),3):e.u(0);c=e.i;d=O()-2592E6;return w(e,nj(c,["SWHealthLog"],{mode:"readwrite",K:!0},function(f){return wj(f.objectStore("SWHealthLog"),{},function(g){if(g.getValue().timestamp<=d)return g.delete().then(function(){return g.continue()})})}),0)})})}
function Jk(){return I(this,function b(){var c;return x(b,function(d){if(1==d.h)return w(d,Hk().open(),2);c=d.i;return w(d,c.clear("SWHealthLog"),0)})})}
;var Kk;function Lk(){Kk||(Kk=new Ai("yt.offline"));return Kk}
function Mk(a){if(N("offline_error_handling")){var b=Lk().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Lk().set("errors",b,2592E3,!0)}}
;var Nk=ug("network_polling_interval",3E4);function U(){hf.call(this);this.C=0;this.J=this.l=!1;this.j=this.Ia();Ok(this);Pk(this)}
v(U,hf);function Qk(){if(!U.h){var a=C("yt.networkStatusManager.instance")||new U;A("yt.networkStatusManager.instance",a,void 0);U.h=a}return U.h}
m=U.prototype;m.H=function(){return this.j};
m.aa=function(a,b){a!==this.j&&((void 0===b?0:b)?this.N():this.j=a)};
m.Ib=function(a){this.l=!0;if(void 0===a?0:a)this.C||Rk(this)};
m.Ia=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.ub=function(){this.J=!0};
m.Y=function(a,b){return hf.prototype.Y.call(this,a,b)};
function Pk(a){window.addEventListener("online",function(){return I(a,function c(){var d=this;return x(c,function(e){if(1==e.h)return w(e,d.N(),2);if(d.J&&N("offline_error_handling")){var f=Lk().get("errors",!0);if(f){for(var g in f)if(f[g]){var h=new Ni(g,"sent via offline_errors");h.name=f[g].name;h.stack=f[g].stack;h.level=f[g].level;pg(h)}Lk().set("errors",{},2592E3,!0)}}e.h=0})})})}
function Ok(a){window.addEventListener("offline",function(){return I(a,function c(){var d=this;return x(c,function(e){return w(e,d.N(),0)})})})}
function Rk(a){a.C=Kg(function(){return I(a,function c(){var d=this;return x(c,function(e){if(1==e.h)return d.j?d.Ia()||!d.l?e.u(3):w(e,d.N(),3):w(e,d.N(),3);Rk(d);e.h=0})})},Nk)}
m.N=function(a){var b=this;return this.m?this.m:this.m=new Promise(function(c){return I(b,function e(){var f,g,h,k=this;return x(e,function(l){switch(l.h){case 1:return f=window.AbortController?new window.AbortController:void 0,g=null===f||void 0===f?void 0:f.signal,h=!1,sa(l,2,3),f&&(k.B=Mg(function(){f.abort()},a||2E4)),w(l,fetch("/generate_204",{method:"HEAD",
signal:g}),5);case 5:h=!0;case 3:ua(l);k.m=void 0;k.B&&Pg(k.B);h!==k.j&&(k.j=h,k.j&&k.l?jf(k,"ytnetworkstatus-online"):k.l&&jf(k,"ytnetworkstatus-offline"));c(h);va(l);break;case 2:ta(l),h=!1,l.u(3)}})})})};
U.prototype.sendNetworkCheckRequest=U.prototype.N;U.prototype.listen=U.prototype.Y;U.prototype.enableErrorFlushing=U.prototype.ub;U.prototype.getWindowStatus=U.prototype.Ia;U.prototype.monitorNetworkStatusChange=U.prototype.Ib;U.prototype.networkStatusHint=U.prototype.aa;U.prototype.isNetworkAvailable=U.prototype.H;U.getInstance=Qk;function Sk(a){a=void 0===a?{}:a;hf.call(this);var b=this;this.l=this.B=0;this.j=Qk();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.j);c&&c(a.Ya);a.eb&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.j))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.j))a.Aa?(this.Aa=a.Aa,c("ytnetworkstatus-online",function(){Tk(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){Tk(b,"publicytnetworkstatus-offline")})):
(c("ytnetworkstatus-online",function(){jf(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){jf(b,"publicytnetworkstatus-offline")}))}
v(Sk,hf);Sk.prototype.H=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.j);return a?a():!0};
Sk.prototype.aa=function(a,b){b=void 0===b?!1:b;var c=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);c&&c(a,b)};
Sk.prototype.N=function(a){return I(this,function c(){var d=this,e;return x(c,function(f){return(e=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(d.j))?f.return(e(a)):f.return(!0)})})};
function Tk(a,b){a.Aa?a.l?(Pg(a.B),a.B=Mg(function(){a.m!==b&&(jf(a,b),a.m=b,a.l=O())},a.Aa-(O()-a.l))):(jf(a,b),a.m=b,a.l=O()):jf(a,b)}
;var Uk=!1,Vk,Wk=0,Xk=0,Yk,Zk=z.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Uk,databaseToken:Vk,potentialEsfErrorCounter:Xk,isIdbSupported:!!Vk};A("ytNetworklessLoggingInitializationOptions",Zk,void 0);
function $k(){I(this,function b(){return x(b,function(c){switch(c.h){case 1:return w(c,Pj(),2);case 2:Vk=c.i;if(!Vk||!Oi()&&!N("nwl_init_require_datasync_id_killswitch")){c.u(0);break}Uk=!0;Zk.isNwlInitialized=Uk;Zk.databaseToken=Vk;Zk.isIdbSupported=!!Vk;return w(c,Xj("LogsDatabaseV2"),4);case 4:if(!(.1>=Math.random())){c.u(5);break}return w(c,Ek(Vk),6);case 6:return w(c,Ik(),5);case 5:al();bl().H()&&cl();bl().Y("publicytnetworkstatus-online",cl);bl().Y("publicytnetworkstatus-offline",dl);if(!N("networkless_immediately_drop_sw_health_store")){c.u(8);
break}return w(c,el(),8);case 8:if(N("networkless_immediately_drop_all_requests"))return w(c,Fk(),0);c.u(0)}})})}
function fl(a,b){function c(d){var e=bl().H();if(!gl()||!d||e&&N("vss_networkless_bypass_write"))hl(a,b);else{var f={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0};yk(f,d).then(function(g){f.id=g;bl().H()&&il(f)}).catch(function(g){il(f);
bl().H()?pg(g):Mk(g)})}}
b=void 0===b?{}:b;N("skip_is_supported_killswitch")?Pj().then(function(d){c(d)}):c(jl())}
function kl(a,b){function c(d){if(gl()&&d){var e={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(h,k){void 0!==e.id?Dk(e.id,d):f=!0;N("vss_network_hint")&&bl().aa(!0);g(h,k)};
hl(e.url,e.options);yk(e,d).then(function(h){e.id=h;f&&Dk(e.id,d)}).catch(function(h){bl().H()?pg(h):Mk(h)})}else hl(a,b)}
b=void 0===b?{}:b;N("skip_is_supported_killswitch")?Pj().then(function(d){c(d)}):c(jl())}
function cl(){var a=this,b=jl();if(!b)throw bj("throttleSend");Wk||(Wk=Mg(function(){return I(a,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Ak("NEW",b),2);if(3!=f.h)return e=f.i,e?w(f,il(e),3):(dl(),f.return());Wk&&(Wk=0,cl());f.h=0})})},100))}
function dl(){Pg(Wk);Wk=0}
function il(a){return I(this,function c(){var d,e,f;return x(c,function(g){switch(g.h){case 1:d=jl();if(!d)throw e=bj("immediateSend"),e;if(void 0===a.id){g.u(2);break}return w(g,Bk(a.id,d),3);case 3:(f=g.i)?a=f:qg(Error("The request cannot be found in the database."));case 2:if(ll(a,2592E6)){g.u(4);break}qg(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){g.u(5);break}return w(g,Dk(a.id,d),5);case 5:return g.return();case 4:a.skipRetry||(a=ml(a));var h=a,k,l;
if(null===(l=null===(k=null===h||void 0===h?void 0:h.options)||void 0===k?void 0:k.postParams)||void 0===l?0:l.requestTimeMs)h.options.postParams.requestTimeMs=Math.round(O());a=h;if(!a){g.u(0);break}if(!a.skipRetry||void 0===a.id){g.u(8);break}return w(g,Dk(a.id,d),8);case 8:hl(a.url,a.options,!!a.skipRetry),g.h=0}})})}
function ml(a){var b=this,c=jl();if(!c)throw bj("updateRequestHandlers");var d=a.options.onError?a.options.onError:function(){};
a.options.onError=function(f,g){return I(b,function k(){var l;return x(k,function(n){switch(n.h){case 1:l=fk(g);if(!(N("nwl_consider_error_code")&&l||!N("nwl_consider_error_code")&&nl()<=ug("potential_esf_error_limit",10))){n.u(2);break}return w(n,bl().N(),3);case 3:if(bl().H()){n.u(2);break}d(f,g);if(!N("nwl_consider_error_code")||void 0===(null===a||void 0===a?void 0:a.id)){n.u(5);break}return w(n,Ck(a.id,c,!1),5);case 5:return n.return();case 2:if(N("nwl_consider_error_code")&&!l&&nl()>ug("potential_esf_error_limit",
10))return n.return();C("ytNetworklessLoggingInitializationOptions")&&Zk.potentialEsfErrorCounter++;Xk++;if(void 0===(null===a||void 0===a?void 0:a.id)){n.u(7);break}return 1>a.sendCount?w(n,Ck(a.id,c),11):w(n,Dk(a.id,c),7);case 11:Mg(function(){bl().H()&&cl()},5E3);
case 7:d(f,g),n.h=0}})})};
var e=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(f,g){return I(b,function k(){return x(k,function(l){if(1==l.h)return void 0===(null===a||void 0===a?void 0:a.id)?l.u(2):w(l,Dk(a.id,c),2);N("vss_network_hint")&&bl().aa(!0);e(f,g);l.h=0})})};
return a}
function ll(a,b){a=a.timestamp;return O()-a>=b?!1:!0}
function al(){var a=this,b=jl();if(!b)throw bj("retryQueuedRequests");Ak("QUEUED",b).then(function(c){c&&!ll(c,12E4)?Mg(function(){return I(a,function e(){return x(e,function(f){if(1==f.h)return void 0===c.id?f.u(2):w(f,Ck(c.id,b),2);al();f.h=0})})}):bl().H()&&cl()})}
function el(){return I(this,function b(){var c,d;return x(b,function(e){c=jl();if(!c)throw d=bj("clearSWHealthLogsDb"),d;return e.return(Jk().catch(function(f){pg(f)}))})})}
function bl(){Yk||(Yk=new Sk({eb:!0,Ya:!0}));return Yk}
function hl(a,b,c){if(N("networkless_with_beacon")){var d=["method","postBody"];if(Object.keys(b).length>d.length)c=!0;else{c=0;d=u(d);for(var e=d.next();!e.done;e=d.next())b.hasOwnProperty(e.value)&&c++;c=Object.keys(b).length!==c}c?rh(a,b):Gh(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?Dh(a):rh(a,b)}
function gl(){return C("ytNetworklessLoggingInitializationOptions")?Zk.isNwlInitialized:Uk}
function jl(){return C("ytNetworklessLoggingInitializationOptions")?Zk.databaseToken:Vk}
function nl(){return C("ytNetworklessLoggingInitializationOptions")?Zk.potentialEsfErrorCounter:Xk}
;function ol(){Yj.call(this,{G:{sb:Ek,ia:Dk,ab:Ak,Gb:Bk,Pa:Ck,set:yk},I:new Sk({eb:!0,Ya:!0}),handleError:pg,ja:qg,S:pl,now:O,ob:Mk,cb:Og(),Oa:"publicytnetworkstatus-online",Na:"publicytnetworkstatus-offline",va:!0,sa:.1,za:ug("potential_esf_error_limit",10),F:N});this.va&&Math.random()<=this.sa&&this.databaseToken&&Ik();N("networkless_immediately_drop_sw_health_store")&&ql(this);N("networkless_immediately_drop_all_requests")&&Fk();Xj("LogsDatabaseV2")}
v(ol,Yj);function rl(){var a=C("yt.networklessRequestController.instance");a||(a=new ol,A("yt.networklessRequestController.instance",a,void 0),N("networkless_logging")&&Pj().then(function(b){a.databaseToken=b;Zj(a)}));
return a}
ol.prototype.writeThenSend=function(a,b){b||(b={});Oi()||(this.h=!1);Yj.prototype.writeThenSend.call(this,a,b)};
ol.prototype.sendThenWrite=function(a,b,c){b||(b={});Oi()||(this.h=!1);Yj.prototype.sendThenWrite.call(this,a,b,c)};
ol.prototype.sendAndWrite=function(a,b){b||(b={});Oi()||(this.h=!1);Yj.prototype.sendAndWrite.call(this,a,b)};
function ql(a){I(a,function c(){var d=this,e,f;return x(c,function(g){e=d;if(!d.databaseToken)throw f=bj("clearSWHealthLogsDb"),f;return g.return(Jk().catch(function(h){e.handleError(h)}))})})}
function pl(a,b,c){var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(O());if(N("networkless_with_beacon")){c=b;var e=["method","postBody"];if(Object.keys(c).length>e.length)c=!0;else{d=0;e=u(e);for(var f=e.next();!f.done;f=e.next())c.hasOwnProperty(f.value)&&d++;c=Object.keys(c).length!==d}c?rh(a,b):Gh(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?Dh(a):rh(a,b)}
;function sl(a){var b=this;this.config_=null;a?this.config_=a:xi()&&(this.config_=hi());Kg(function(){Fi(b)},5E3)}
sl.prototype.isReady=function(){!this.config_&&xi()&&(this.config_=hi());return!!this.config_};
function ki(a,b,c,d){function e(y){y=void 0===y?!1:y;var B;if(d.retry&&"www.youtube-nocookie.com"!=h&&(y||N("skip_ls_gel_retry")||(B=Di(b,c,l,k)),B)){var G=g.onSuccess,R=g.onFetchSuccess;g.onSuccess=function(P,K){Ei(B);G(P,K)};
c.onFetchSuccess=function(P,K){Ei(B);R(P,K)}}try{y&&d.retry&&!d.gb.bypassNetworkless?(g.method="POST",d.gb.writeThenSend?N("use_new_nwl")?rl().writeThenSend(q,g):fl(q,g):N("use_new_nwl")?rl().sendAndWrite(q,g):kl(q,g)):(g.method="POST",g.postParams||(g.postParams={}),rh(q,g))}catch(P){if("InvalidAccessError"==P.name)B&&(Ei(B),B=0),qg(Error("An extension is blocking network request."));
else throw P;}B&&Kg(function(){Fi(a)},5E3)}
!F("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&qg(new Ni("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Ni("innertube xhrclient not ready",b,c,d);pg(f);throw f;}var g={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(y,B){if(d.onSuccess)d.onSuccess(B)},
onFetchSuccess:function(y){if(d.onSuccess)d.onSuccess(y)},
onError:function(y,B){if(d.onError)d.onError(B)},
onFetchError:function(y){if(d.onError)d.onError(y)},
timeout:d.timeout,withCredentials:!0},h="";(f=a.config_.Cb)&&(h=f);var k=a.config_.Eb||!1,l=yi(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},r=a.config_.Db&&f;N("omit_innertube_api_key_for_Bearer_auth_header")&&(r=r&&f.startsWith("Bearer"));r||(p.key=a.config_.innertubeApiKey);var q=fh(""+h+n,p||{},!0);N("use_new_nwl")||gl()?Oj().then(function(y){e(y)}):e(!1)}
;function V(a,b,c){c=void 0===c?{}:c;var d=sl;F("ytLoggingEventsDefaultDisabled",!1)&&sl==sl&&(d=null);mi(a,b,d,c)}
;var tl=[{Ma:function(a){return"Cannot read property '"+a.key+"'"},
ya:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ma:function(a){return"Cannot call '"+a.key+"'"},
ya:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ma:function(a){return a.key+" is not defined"},
ya:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var vl={Z:[],V:[{Ta:ul,weight:500}]};function ul(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function wl(){this.V=[];this.Z=[]}
var xl;function yl(){if(!xl){var a=xl=new wl;a.Z.length=0;a.V.length=0;vl.Z&&a.Z.push.apply(a.Z,vl.Z);vl.V&&a.V.push.apply(a.V,vl.V)}return xl}
;var zl=new L;function Al(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Bl(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Bl(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Bl(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Bl(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Cl(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Dl(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Al(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Dl(e+".ve",f,g,h):0;d+=g;d+=Dl(e,a[e],b,c);if(500<d)break}}else c[b]=El(a),d+=c[b].length;else c[b]=El(a),d+=c[b].length;return d}
function Dl(a,b,c,d){c+="."+a;a=El(b);d[c]=a;return c.length+a.length}
function El(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
;var Fl=new Set,Gl=0,Hl=0,Il=0,Jl=[],Kl=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Ll(a){Ml(a,"WARNING")}
function Ml(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||F("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),N("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+
a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=Gl))){var g=me(a);d=g.message||"Unknown Error";e=g.name||"UnknownError";var h=g.stack||a.i||"Not available";h.startsWith(e+": "+d)&&(f=h.split("\n"),f.shift(),h=f.join("\n"));f=g.lineNumber||"Not available";g=g.fileName||"Not available";var k=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var l=0;l<a.args.length&&!(k=Cl(a.args[l],"params."+l,c,k),500<=k);l++);else if(a.hasOwnProperty("params")&&a.params){var n=
a.params;if("object"===typeof a.params)for(l in n){if(n[l]){var p="params."+l,r=El(n[l]);c[p]=r;k+=p.length+r.length;if(500<k)break}}else c.params=El(n)}if(Jl.length)for(l=0;l<Jl.length&&!(k=Cl(Jl[l],"params.context."+l,c,k),500<=k);l++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);l={message:d,name:e,lineNumber:f,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(l.lineNumber=l.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=
yl();c=u(a.Z);for(d=c.next();!d.done;d=c.next())if(d=d.value,l.message&&l.message.match(d.Lm)){a=d.weight;break a}a=u(a.V);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Ta(l)){a=c.weight;break a}a=1}l.sampleWeight=a;a=u(tl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.ya[l.name])for(e=u(c.ya[l.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=l.message.match(f.regexp)){l.params["params.error.original"]=d[0];e=f.groups;f={};for(g=0;g<e.length;g++)f[e[g]]=d[g+1],l.params["params.error."+e[g]]=
d[g+1];l.message=c.Ma(f);break}l.params||(l.params={});a=yl();l.params["params.errorServiceSignature"]="msg="+a.Z.length+"&cb="+a.V.length;l.params["params.serviceWorker"]="false";z.document&&z.document.querySelectorAll&&(l.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));vb("sample").constructor!==tb&&(l.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(l);if(0!==l.sampleWeight&&!Fl.has(l.message)){"ERROR"===b?(zl.da("handleError",
l),N("record_app_crashed_web")&&0===Il&&1===l.sampleWeight&&(Il++,V("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),Hl++):"WARNING"===b&&zl.da("handleWarning",l);if(N("kevlar_gel_error_routing")){a=b;b:{c=u(Kl);for(d=c.next();!d.done;d=c.next())if(Ah(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:l.stack};l.fileName&&(d.filename=l.fileName);c=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?2!==c.length||
isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};e={pageUrl:window.location.href,kvPairs:[]};F("FEXP_EXPERIMENTS")&&(e.experimentIds=F("FEXP_EXPERIMENTS"));if(f=l.params)for(g=u(Object.keys(f)),h=g.next();!h.done;h=
g.next())h=h.value,e.kvPairs.push({key:"client."+h,value:String(f[h])});f=F("SERVER_NAME",void 0);g=F("SERVER_VERSION",void 0);f&&g&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:g}));c={errorMetadata:e,stackTrace:d,logMessage:c}}c&&(V("clientError",c),("ERROR"===a||N("errors_flush_gel_always_killswitch"))&&ci())}if(!N("suppress_error_204_logging")){a=l.params||{};b={urlParams:{a:"logerror",t:"jserror",type:l.name,msg:l.message.substr(0,250),line:l.lineNumber,
level:b,"client.name":a.name},postParams:{url:F("PAGE_NAME",window.location.href),file:l.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){l.stack&&(b.postParams.stack=l.stack);c=u(Object.keys(a));for(d=c.next();!d.done;d=c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=u(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=F("SERVER_NAME",void 0);c=F("SERVER_VERSION",void 0);
a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}rh(F("ECATCHER_REPORT_HOST","")+"/error_204",b)}try{Fl.add(l.message)}catch(q){}Gl++}}}
function Nl(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];a.args||(a.args=[]);a.args.push.apply(a.args,ha(c))}
;var Ol={Lc:3611,Yb:27686,Zb:85013,ac:23462,dc:42016,ec:62407,fc:26926,cc:43781,hc:51236,ic:79148,jc:50160,kc:77504,yc:87907,zc:18630,Ac:54445,Bc:80935,Cc:105675,Dc:37521,Ec:47786,Fc:98349,Gc:123695,Hc:6827,Ic:29434,Jc:7282,Kc:124448,Oc:32276,Nc:76278,Pc:93911,Qc:106531,Rc:27259,Sc:27262,Tc:27263,Vc:21759,Wc:27107,Xc:62936,Yc:49568,Zc:38408,bd:80637,cd:68727,dd:68728,ed:80353,fd:80356,gd:74610,hd:45707,jd:83962,kd:83970,ld:46713,md:89711,nd:74612,od:93265,pd:74611,qd:131380,sd:128979,td:128978,rd:131391,
ud:105350,wd:134800,vd:131392,yd:113533,zd:93252,Ad:99357,Cd:94521,Dd:114252,Ed:113532,Fd:94522,Bd:94583,Gd:88E3,Hd:93253,Id:93254,Jd:94387,Kd:94388,Ld:93255,Md:97424,xd:72502,Nd:110111,Od:76019,Qd:117092,Rd:117093,Pd:89431,Sd:110466,Td:77240,Ud:60508,Vd:137401,Wd:137402,Xd:137046,Yd:73393,Zd:113534,ae:92098,be:131381,ce:84517,de:83759,ee:80357,ge:86113,he:72598,ie:72733,je:107349,ke:124275,le:118203,me:133275,ne:133274,oe:133272,pe:133273,qe:133276,se:117431,re:133797,te:128572,ue:133405,we:117429,
xe:117430,ye:117432,ze:120080,Ae:117259,Be:121692,Ce:132972,De:133051,Ee:133658,Fe:132971,Ge:97615,He:31402,Je:133624,Ke:133623,Le:133622,Ie:133621,Me:84774,Ne:95117,Oe:98930,Pe:98931,Qe:98932,Re:43347,Se:129889,Te:45474,Ue:100352,Ve:84758,We:98443,Xe:117985,Ye:74613,Ze:74614,af:64502,bf:136032,cf:74615,df:74616,ef:122224,ff:74617,gf:77820,hf:74618,jf:93278,kf:93274,lf:93275,mf:93276,nf:22110,pf:29433,qf:133798,rf:132295,tf:120541,vf:82047,wf:113550,xf:75836,yf:75837,zf:42352,Af:84512,Bf:76065,Cf:75989,
Df:16623,Ef:32594,Ff:27240,Gf:32633,Hf:74858,Jf:3945,If:16989,Kf:45520,Lf:25488,Mf:25492,Nf:25494,Of:55760,Pf:14057,Qf:18451,Rf:57204,Sf:57203,Tf:17897,Uf:57205,Vf:18198,Wf:17898,Xf:17909,Yf:43980,Zf:46220,ag:11721,cg:49954,dg:96369,eg:3854,fg:56251,gg:25624,hg:16906,ig:99999,jg:68172,kg:27068,lg:47973,mg:72773,ng:26970,og:26971,pg:96805,qg:17752,rg:73233,sg:109512,tg:22256,ug:14115,vg:22696,wg:89278,xg:89277,yg:109513,zg:43278,Ag:43459,Bg:43464,Cg:89279,Dg:43717,Eg:55764,Fg:22255,Gg:89281,Hg:40963,
Ig:43277,Jg:43442,Kg:91824,Lg:120137,Mg:96367,Ng:36850,Og:72694,Pg:37414,Qg:36851,Sg:124863,Rg:121343,Tg:73491,Ug:54473,Vg:43375,Wg:46674,Xg:32473,Yg:72901,Zg:72906,ah:50947,bh:50612,dh:50613,eh:50942,fh:84938,gh:84943,hh:84939,ih:84941,jh:84944,kh:84940,lh:84942,mh:35585,nh:51926,oh:79983,ph:63238,qh:18921,rh:63241,sh:57893,th:41182,uh:135732,vh:33424,wh:22207,xh:42993,yh:36229,zh:22206,Ah:22205,Bh:18993,Ch:19001,Dh:18990,Eh:18991,Fh:18997,Gh:18725,Hh:19003,Ih:36874,Jh:44763,Kh:33427,Lh:67793,Mh:22182,
Nh:37091,Oh:34650,Ph:50617,Qh:47261,Rh:22287,Sh:25144,Th:97917,Uh:62397,Vh:125598,Wh:137935,Xh:36961,Yh:108035,Zh:27426,ai:27857,bi:27846,ci:27854,di:69692,fi:61411,gi:39299,hi:38696,ii:62520,ji:36382,ki:108701,li:50663,mi:36387,ni:14908,oi:37533,ri:105443,si:61635,ti:62274,vi:133818,wi:65702,xi:65703,yi:65701,zi:76256,Ai:37671,Bi:49953,Di:36216,Ei:28237,Fi:39553,Gi:29222,Hi:26107,Ii:38050,Ji:26108,Li:120745,Ki:26109,Mi:26110,Ni:66881,Oi:28236,Pi:14586,Qi:57929,Ri:74723,Si:44098,Ti:44099,Wi:23528,
Xi:61699,Ui:134104,Vi:134103,Yi:59149,Zi:101951,aj:97346,bj:118051,cj:95102,dj:64882,ej:119505,fj:63595,gj:63349,hj:95101,ij:75240,jj:27039,kj:68823,lj:21537,mj:83464,nj:75707,oj:83113,pj:101952,qj:101953,sj:79610,tj:125755,uj:24402,vj:24400,wj:32925,xj:57173,yj:122502,zj:64423,Aj:64424,Bj:33986,Cj:100828,Dj:129089,Ej:21409,Ij:135155,Jj:135156,Kj:135157,Lj:135158,Mj:135159,Nj:135160,Oj:135161,Pj:135162,Qj:135163,Rj:135164,Sj:135165,Tj:135166,Fj:11070,Gj:11074,Hj:17880,Uj:14001,Wj:30709,Xj:30707,Yj:30711,
Zj:30710,ak:30708,Vj:26984,bk:63648,ck:63649,dk:51879,ek:111059,fk:5754,gk:20445,ik:130975,hk:130976,jk:110386,kk:113746,lk:66557,mk:17310,nk:28631,pk:21589,qk:68012,rk:60480,sk:31571,tk:76980,uk:41577,vk:45469,wk:38669,xk:13768,yk:13777,zk:62985,Ak:4724,Bk:59369,Ck:43927,Dk:43928,Ek:12924,Fk:100355,Ik:56219,Jk:27669,Kk:10337,Hk:47896,Lk:122629,Mk:121258,Nk:107598,Ok:127991,Pk:96639,Qk:107536,Rk:130169,Sk:96661,Tk:96658,Uk:116646,Vk:121122,Wk:96660,Xk:127738,Yk:127083,Zk:104443,al:96659,bl:106442,
dl:134840,fl:63667,il:63668,jl:63669,kl:130686,ll:78314,ml:55761,nl:127098,ol:134841,pl:96368,ql:67374,rl:48992,sl:49956,ul:31961,vl:26388,wl:23811,xl:5E4,yl:126250,zl:96370,Al:47355,Bl:47356,Cl:37935,Dl:45521,El:21760,Fl:83769,Gl:49977,Hl:49974,Il:93497,Jl:93498,Kl:34325,Ll:115803,Ml:123707,Nl:100081,Ol:35309,Pl:68314,Ql:25602,Rl:100339,Sl:59018,Tl:18248,Ul:50625,Vl:9729,Wl:37168,Xl:37169,Yl:21667,Zl:16749,am:18635,bm:39305,cm:18046,dm:53969,em:8213,fm:93926,gm:102852,hm:110099,im:22678,jm:69076,
km:137575,mm:100856,nm:17736,om:3832,pm:55759,qm:64031,rm:93044,sm:93045,tm:34388,um:17657,vm:17655,wm:39579,xm:39578,ym:77448,zm:8196,Am:11357,Bm:69877,Cm:8197,Dm:82039};function Pl(){var a=nb(Ql),b;return Bf(new uf(function(c,d){a.onSuccess=function(e){lh(e)?c(new Rl(e)):d(new Sl("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Sl("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Sl("Request timed out","net.timeout",e))};
b=rh("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Cf&&b.abort();
return zf(c)})}
function Sl(a,b,c){Wa.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(Sl,Wa);function Rl(a){this.xhr=a}
;function Tl(){this.i=0;this.h=null}
Tl.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),tf(a)?a:Ul(a)):2===this.i&&b?(a=b.call(c,this.h),tf(a)?a:Vl(a)):this};
Tl.prototype.getValue=function(){return this.h};
Tl.prototype.$goog_Thenable=!0;function Vl(a){var b=new Tl;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function Ul(a){var b=new Tl;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function Wl(){if(Pd())return!0;var a=F("INNERTUBE_CLIENT_NAME");return!a||"WEB"!==a&&"MWEB"!==a||zh&&Ah("applewebkit")&&!Ah("version")&&(!Ah("safari")||Ah("gsa/"))||tc&&Ah("version/")?!0:(a=Nd.get("CONSENT",void 0))?a.startsWith("YES+"):!0}
;function Xl(a){Wa.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Yl;this.isTimeout=a instanceof Sl&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Cf}
v(Xl,Wa);Xl.prototype.name="BiscottiError";function Yl(){Wa.call(this,"Biscotti ID is missing from server")}
v(Yl,Wa);Yl.prototype.name="BiscottiMissingError";var Ql={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Zl=null;function Wg(){if(N("disable_biscotti_fetch_entirely_for_all_web_clients"))return zf(Error("Biscotti id fetching has been disabled entirely."));if(!Wl())return zf(Error("User has not consented - not fetching biscotti id."));if("1"==lb())return zf(Error("Biscotti ID is not available in private embed mode"));Zl||(Zl=Bf(Pl().then($l),function(a){return am(2,a)}));
return Zl}
function $l(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Yl;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Yl;a=a.id;Xg(a);Zl=Ul(a);bm(18E5,2);return a}
function am(a,b){b=new Xl(b);Xg("");Zl=Vl(b);0<a&&bm(12E4,a-1);throw b;}
function bm(a,b){Gg(function(){Bf(Pl().then($l,function(c){return am(b,c)}),Ha)},a)}
function cm(){try{var a=C("yt.ads.biscotti.getId_");return a?a():Wg()}catch(b){return zf(b)}}
;function dm(a){if("1"!=lb()){a&&Vg();try{cm().then(function(){},function(){}),Gg(dm,18E5)}catch(b){pg(b)}}}
;var em=Date.now().toString();
function fm(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(em)for(a=1,b=0;b<em.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^em.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var gm,hm=z.ytLoggingDocDocumentNonce_;hm||(hm=fm(),Ua("ytLoggingDocDocumentNonce_",hm));gm=hm;var im={sf:0,Mc:1,Uc:2,Ci:3,uf:4,lm:5,rj:6,Gk:7,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE"};function jm(a){this.h=a}
function km(a){return new jm({trackingParams:a})}
jm.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
jm.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
jm.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function lm(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function mm(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function nm(a){return F(mm(void 0===a?0:a),void 0)}
A("yt_logging_screen.getRootVeType",nm,void 0);function om(a){return(a=nm(void 0===a?0:a))?new jm({veType:a,youtubeData:void 0}):null}
function pm(){var a=F("csn-to-ctt-auth-info");a||(a={},M("csn-to-ctt-auth-info",a));return a}
function qm(a){a=void 0===a?0:a;var b=F(lm(a));if(!b&&!F("USE_CSN_FALLBACK",!0))return null;b||!N("use_undefined_csn_any_layer")&&0!=a||(b="UNDEFINED_CSN");return b?b:null}
A("yt_logging_screen.getCurrentCsn",qm,void 0);function rm(a,b,c){var d=pm();(c=qm(c))&&delete d[c];b&&(d[a]=b)}
function sm(a){return pm()[a]}
A("yt_logging_screen.getCttAuthInfo",sm,void 0);function tm(a,b,c,d){c=void 0===c?0:c;if(a!==F(lm(c))||b!==F(mm(c)))rm(a,d,c),M(lm(c),a),M(mm(c),b),b=function(){setTimeout(function(){a&&mi("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:gm,clientScreenNonce:a},sl)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
A("yt_logging_screen.setCurrentScreen",tm,void 0);function um(a){gk.call(this,1,arguments);this.csn=a}
v(um,gk);var pk=new hk("screen-created",um),vm=[],xm=wm,ym=0;function zm(a,b,c,d){var e=d.filter(function(f){f.csn!==b?(f.csn=b,f=!0):f=!1;return f});
c={csn:b,parentVe:c.getAsJson(),childVes:ab(e,function(f){return f.getAsJson()})};
d=u(d);for(e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(jb(e)||!e.trackingParams&&!e.veType)&&Ll(Error("Child VE logged with no data"));d={cttAuthInfo:sm(b),ba:b};"UNDEFINED_CSN"==b?Am("visualElementAttached",c,d):a?mi("visualElementAttached",c,a,d):V("visualElementAttached",c,d)}
function wm(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return Ic(b,3)}
function Am(a,b,c){vm.push({payloadName:a,payload:b,options:c});ym||(ym=qk())}
function rk(a){if(vm){for(var b=u(vm),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,mi(c.payloadName,c.payload,null,c.options));vm.length=0}ym=0}
;function Bm(){this.i=new Set;this.h=new Set;this.j=new Map}
Bm.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
Ia(Bm);function Cm(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!Dm(a)||c.some(function(e){return!Dm(e)}))throw Error("Only objects may be merged.");
c=u(c);for(d=c.next();!d.done;d=c.next())Em(a,d.value);return a}
function Em(a,b){for(var c in b)if(Dm(b[c])){if(c in a&&!Dm(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Em(a[c],b[c])}else if(Fm(b[c])){if(c in a&&!Fm(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Gm(a[c],b[c])}else a[c]=b[c];return a}
function Gm(a,b){b=u(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Dm(c)?a.push(Em({},c)):Fm(c)?a.push(Gm([],c)):a.push(c);return a}
function Dm(a){return"object"===typeof a&&!Array.isArray(a)}
function Fm(a){return"object"===typeof a&&Array.isArray(a)}
;function Hm(a,b){gk.call(this,1,arguments)}
v(Hm,gk);function Im(a,b){gk.call(this,1,arguments)}
v(Im,gk);var Jm=new hk("aft-recorded",Hm),Km=new hk("timing-sent",Im);var Lm=window;function Mm(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var W=Lm.performance||Lm.mozPerformance||Lm.msPerformance||Lm.webkitPerformance||new Mm;var Nm=!1,Om={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Sa(W.clearResourceTimings||W.webkitClearResourceTimings||W.mozClearResourceTimings||W.msClearResourceTimings||W.oClearResourceTimings||Ha,W);function Pm(a){var b=Qm(a);if(b.aft)return b.aft;a=F((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function Rm(){var a;if(N("csi_use_performance_navigation_timing")){var b,c,d,e=null===(d=null===(c=null===(b=null===(a=null===W||void 0===W?void 0:W.getEntriesByType)||void 0===a?void 0:a.call(W,"navigation"))||void 0===b?void 0:b[0])||void 0===c?void 0:c.toJSON)||void 0===d?void 0:d.call(c);e?(e.requestStart=Sm(e.requestStart),e.responseEnd=Sm(e.responseEnd),e.redirectStart=Sm(e.redirectStart),e.redirectEnd=Sm(e.redirectEnd),e.domainLookupEnd=Sm(e.domainLookupEnd),e.connectStart=Sm(e.connectStart),
e.connectEnd=Sm(e.connectEnd),e.responseStart=Sm(e.responseStart),e.secureConnectionStart=Sm(e.secureConnectionStart),e.domainLookupStart=Sm(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=W.timing}else a=W.timing;return a}
function Tm(){return N("csi_use_time_origin")&&W.timeOrigin?Math.floor(W.timeOrigin):W.timing.navigationStart}
function Sm(a){return Math.round(Tm()+a)}
function Um(a){var b;(b=C("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Ua("ytcsi."+(a||"")+"data_",b));return b}
function Vm(a){a=Um(a);a.info||(a.info={});return a.info}
function Qm(a){a=Um(a);a.tick||(a.tick={});return a.tick}
function Wm(a){var b=Um(a).nonce;b||(b=fm(),Um(a).nonce=b);return b}
function Xm(a){var b=Qm(a||""),c=Pm(a);c&&!Nm&&(mk(Jm,new Hm(Math.round(c-b._start),a)),Nm=!0)}
;function Ym(){if(W.getEntriesByType){var a=W.getEntriesByType("paint");if(a=cb(a,function(b){return"first-paint"===b.name}))return Sm(a.startTime)}a=W.timing;
return a.Jb?Math.max(0,a.Jb):0}
;function Zm(){var a=C("ytcsi.debug");a||(a=[],A("ytcsi.debug",a,void 0),A("ytcsi.reference",{},void 0));return a}
function $m(a){a=a||"";var b=C("ytcsi.reference");b||(Zm(),b=C("ytcsi.reference"));if(b[a])return b[a];var c=Zm(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var an=z.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",an,void 0);function cn(){this.h=0}
function dn(){cn.h||(cn.h=new cn);return cn.h}
cn.prototype.tick=function(a,b,c,d){en(this,"tick_"+a+"_"+b)||V("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
cn.prototype.info=function(a,b,c){var d=Object.keys(a).join("");en(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,V("latencyActionInfo",a,{cttAuthInfo:c}))};
cn.prototype.span=function(a,b,c){var d=Object.keys(a).join("");en(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,V("latencyActionSpan",a,{cttAuthInfo:c}))};
function en(a,b){an[b]=an[b]||{count:0};var c=an[b];c.count++;c.time=O();a.h||(a.h=Kg(function(){var d=O(),e;for(e in an)an[e]&&6E4<d-an[e].time&&delete an[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Ni("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Ll(c)),!0):!1}
;var X={},fn=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X.browse="LATENCY_ACTION_BROWSE",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard=
"LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.playlists"]=
"LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf=
"LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard=
"LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest=
"LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X),Y={},gn=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an=
"adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cs="commandSource",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",
Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.ncnp="webInfo.nonPreloadedNodeCount",Y.pnt="performanceNavigationTiming",
Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs=
"tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",
Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),hn="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),jn={},kn=(jn.ccs="CANARY_STATE_",
jn.mver="MEASUREMENT_VERSION_",jn.pis="PLAYER_INITIALIZED_STATE_",jn.yt_pt="LATENCY_PLAYER_",jn.pa="LATENCY_ACTION_",jn.ctop="TOP_ENTITY_TYPE_",jn.yt_vst="VIDEO_STREAM_TYPE_",jn),ln="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function mn(a){return!!F("FORCE_CSI_ON_GEL",!1)||N("csi_on_gel")||N("enable_csi_on_gel")||N("unplugged_tvhtml5_csi_on_gel")||!!Um(a).useGel}
function nn(a,b,c){var d=on(c);d.gelTicks&&(d.gelTicks["tick_"+a]=!0);c||b||O();if(mn(c)){$m(c||"").tick[a]=b||O();d=Wm(c);var e=Um(c).cttAuthInfo;"_start"===a?(a=dn(),en(a,"baseline_"+d)||V("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:e})):dn().tick(a,d,b,e);Xm(c);return!0}return!1}
function pn(a,b,c){c=on(c);if(c.gelInfos)c.gelInfos["info_"+a]=!0;else{var d={};c.gelInfos=(d["info_"+a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in gn){c=gn[a];0<=Za(hn,c)&&(b=!!b);a in kn&&"string"===typeof b&&(b=kn[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Cm({},d)}0<=Za(ln,a)||Ll(new Ni("Unknown label logged with GEL CSI",a))}
function on(a){a=Um(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function qn(a){a=on(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
;function rn(a,b,c){null!==b&&(Vm(c)[a]=b,mn(c)?(a=pn(a,b,c))&&mn(c)&&(b=$m(c||""),Cm(b.info,a),Cm(qn(c),a),b=Wm(c),c=Um(c).cttAuthInfo,dn().info(a,b,c)):$m(c||"").info[a]=b)}
function Z(a,b,c){var d=Qm(c);if(!b&&"_"!==a[0]){var e=a;W.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),W.mark(e))}e=b||O();d[a]=e;nn(a,b,c)||c||(sn(),$m("").tick[a]=b||O());return d[a]}
function tn(){var a=Wm(void 0);requestAnimationFrame(function(){setTimeout(function(){a===Wm(void 0)&&Z("ol",void 0,void 0)},0)})}
function sn(){if(!C("yt.timing.pingSent_")){var a=F("TIMING_ACTION",void 0),b=Qm();if(a=!!C("ytglobal.timingready_")&&a)a="_start"in Qm(void 0);if(a&&Pm()){Xm();a=!0;var c=F("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in b)){a=!1;break}if(a&&!mn()){c=Qm();d=Vm();e=c._start;var f=F("CSI_SERVICE_NAME","youtube");a={v:2,s:f,action:F("TIMING_ACTION",void 0)};b=d.srt;void 0!==c.srt&&delete d.srt;c.aft=Pm();var g=Qm(void 0),h=g.pbr,k=g.vc;g=g.pbs;h&&k&&g&&h<k&&k<g&&Vm(void 0).yt_pvis&&
"youtube"===f&&(rn("yt_lt","hot_bg"),f=c.vc,h=c.pbs,delete c.aft,d.aft=Math.round(h-f));for(var l in d)"_"!==l.charAt(0)&&(a[l]=d[l]);c.ps=O();l={};f=[];for(var n in c)"_"!==n.charAt(0)&&(h=Math.round(c[n]-e),l[n]=h,f.push(n+"."+h));a.rt=f.join(",");n=!!d.ap;c="";for(var p in a)a.hasOwnProperty(p)&&(c+="&"+p+"="+a[p]);p="/csi_204?"+c.substring(1);window.navigator&&n?Gh(p):Dh(p);A("yt.timing.pingSent_",!0,void 0);mk(Km,new Im(l.aft+(Number(b)||0)))}}}}
function un(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=wg+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function vn(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);cc()&&a.setAttribute("nonce",cc());return c?(a=W.getEntriesByName(c))&&a[0]&&(a=a[0],c=Tm(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function wn(){var a=window.location.protocol,b=W.getEntriesByType("resource");b=$a(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=bb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",Sm(b.startTime)),Z("wffe",Sm(b.responseEnd)))}
var xn=window;xn.ytcsi&&(xn.ytcsi.info=rn,xn.ytcsi.tick=Z);function yn(){this.o=[];this.A=[];this.h=[];this.l=[];this.m=[];this.i=new Set;this.B=new Map}
function zn(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=qm(c),h=om(c);g&&h&&((null===(e=d.response)||void 0===e?0:e.trackingParams)&&zm(a.client,g,h,[km(d.response.trackingParams)]),(null===(f=d.playerResponse)||void 0===f?0:f.trackingParams)&&zm(a.client,g,h,[km(d.playerResponse.trackingParams)]))})}
function An(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.o.push([b,c]);else{var e=qm(d);c=c||om(d);e&&c&&zm(a.client,e,c,[b])}}
yn.prototype.clickCommand=function(a,b,c){a=a.clickTrackingParams;c=void 0===c?0:c;if(a)if(c=qm(void 0===c?0:c)){var d=this.client;var e="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";a={csn:c,ve:km(a).getAsJson(),gestureType:e};b&&(a.clientData=b);b={cttAuthInfo:sm(c),ba:c};"UNDEFINED_CSN"==c?Am("visualElementGestured",a,b):d?mi("visualElementGestured",a,d,b):V("visualElementGestured",a,b);b=!0}else b=!1;else b=!1;return b};
function Bn(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Cn(a,b,c);var f=om(c.layer);if(f){for(var g=u(a.o),h=g.next();!h.done;h=g.next())h=h.value,An(a,h[0],h[1]||f,c.layer);f=u(a.A);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=qm(g);var l=k[0]||om(g);h&&l&&(g=a.client,k=k[1],k={csn:h,ve:l.getAsJson(),clientData:k},l={cttAuthInfo:sm(h),ba:h},"UNDEFINED_CSN"==h?Am("visualElementStateChanged",k,l):g?mi("visualElementStateChanged",k,g,l):V("visualElementStateChanged",
k,l))}}};
qm(c.layer)||a.j();if(c.Xa)for(var d=u(c.Xa),e=d.next();!e.done;e=d.next())zn(a,e.value,c.layer);else Ml(Error("Delayed screen needs a data promise."))}
function Cn(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Kb?c.Kb:c.layer;var e=qm(d);d=om(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=F("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=a.client;h=f;var l=c.Wa,n=c.cttAuthInfo,p=c.Jm,r=xm(),q={csn:r,pageVe:(new jm({veType:b,youtubeData:g})).getAsJson()};h&&h.visualElement?(q.implicitGesture=
{parentCsn:h.clientScreenNonce,gesturedVe:h.visualElement.getAsJson()},p&&(q.implicitGesture.gestureType=p)):h&&Ll(new Ni("newScreen() parent element does not have a VE - rootVe",b));l&&(q.cloneCsn=l);l={cttAuthInfo:n,ba:r};k?mi("screenCreated",q,k,l):V("screenCreated",q,l);mk(pk,new um(r));var y=r}catch(B){Nl(B,{Om:b,rootVe:d,parentVisualElement:void 0,Im:e,Nm:f,Wa:c.Wa});Ml(B);return}tm(y,b,c.layer,c.cttAuthInfo);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=N("screen_manager_skip_hide_killswitch"))){a:{b=
u(Object.values(im));for(f=b.next();!f.done;f=b.next())if(qm(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,f=!0,k=(f=void 0===f?!1:f)?16:8,d={csn:e,ve:d.getAsJson(),eventType:k},f={cttAuthInfo:sm(e),ba:e,wb:f},"UNDEFINED_CSN"==e?Am("visualElementHidden",d,f):b?mi("visualElementHidden",d,b,f):V("visualElementHidden",d,f));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=y||"");rn("csn",y);Bm.getInstance().clear();d=om(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(N("web_mark_root_visible")||
N("music_web_mark_root_visible"))&&(e=y,y={csn:e,ve:d.getAsJson(),eventType:1},b={cttAuthInfo:sm(e),ba:e},"UNDEFINED_CSN"==e?Am("visualElementShown",y,b):V("visualElementShown",y,b));a.i.delete(c.layer||0);a.j=void 0;e=u(a.B);for(y=e.next();!y.done;y=e.next())b=u(y.value),y=b.next().value,b=b.next().value,b.has(c.layer)&&d&&An(a,y,d,c.layer);for(c=0;c<a.l.length;c++){e=a.l[c];try{e()}catch(B){Ml(B)}}for(c=a.l.length=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(B){Ml(B)}}}
;function Dn(a){a&&(a.dataset?a.dataset[En("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Fn(a,b){return a?a.dataset?a.dataset[En(b)]:a.getAttribute("data-"+b):null}
var Gn={};function En(a){return Gn[a]||(Gn[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Hn=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,In=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Jn(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Hn,""),c=c.replace(In,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Kn(a,b,c)}
function Kn(a,b,c){c=void 0===c?null:c;var d=Ln(a),e=document.getElementById(d),f=e&&Fn(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Lh(d,b),b=""+Na(b),Mn[b]=f),g||(e=Nn(a,d,function(){Fn(e,"loaded")||(Dn(e),Oh(d),Gg(Ta(Ph,d),0))},c)))}
function Nn(a,b,c,d){d=void 0===d?null:d;var e=vd(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);od(e,lf(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function On(a){a=Ln(a);var b=document.getElementById(a);b&&(Ph(a),b.parentNode.removeChild(b))}
function Pn(a,b){a&&b&&(a=""+Na(b),(a=Mn[a])&&Nh(a))}
function Ln(a){var b=document.createElement("a");$b(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+ec(a)}
var Mn={};var Qn=[],Rn=!1;function Sn(){if(!N("disable_biscotti_fetch_for_ad_blocker_detection")&&!N("disable_biscotti_fetch_entirely_for_all_web_clients")&&Wl()&&"1"!=lb()){var a=function(){Rn=!0;"google_ad_status"in window?M("DCLKSTAT",1):M("DCLKSTAT",2)};
try{Jn("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Qn.push(Mg(function(){if(!(Rn||"google_ad_status"in window)){try{Pn("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Rn=!0;M("DCLKSTAT",3)}},5E3))}}
function Tn(){var a=Number(F("DCLKSTAT",0));return isNaN(a)?0:a}
;function Un(){this.i=!1;this.h=null}
Un.prototype.initialize=function(a,b,c,d){d=void 0===d?!1:d;var e,f;if(a.program){var g=null!==(e=a.interpreterScript)&&void 0!==e?e:null,h=null!==(f=a.interpreterUrl)&&void 0!==f?f:null;if(a.interpreterSafeScript){g=a.interpreterSafeScript;vb("From proto message. b/166824318");g=g.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var k=sb();g=k?k.createScript(g):g;g=(new xb(g)).toString()}a.interpreterSafeUrl&&(h=a.interpreterSafeUrl,vb("From proto message. b/166824318"),h=Bb(h.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||
"").toString());Vn(this,g,h,a.program,b,c,d)}else Ll(Error("Cannot initialize botguard without program"))};
function Vn(a,b,c,d,e,f,g){g=void 0===g?!1:g;c?(a.i=!0,Jn(c,function(){a.i=!1;var h=0<=c.indexOf("/th/");(h?window.trayride:window.botguard)?Wn(a,d,!!g,h,e):(On(c),Ll(new Ni("Unable to load Botguard","from "+c)))},f)):b&&(f=vd(document,"SCRIPT"),f.textContent=b,f.nonce=cc(),document.head.appendChild(f),document.head.removeChild(f),((b=b.includes("trayride"))?window.trayride:window.botguard)?Wn(a,d,!!g,b,e):Ll(Error("Unable to load Botguard from JS")))}
function Wn(a,b,c,d,e){var f,g;if(d=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{Xn(a,new d(b,e?function(){return e(b)}:Ha))}catch(h){h instanceof Error&&Ll(h)}else{try{Xn(a,new d(b))}catch(h){h instanceof Error&&Ll(h)}e&&e(b)}else Ll(Error("Failed to finish initializing VM"))}
Un.prototype.invoke=function(a){a=void 0===a?{}:a;return this.h?this.h.hasOwnProperty("hot")?this.h.hot(void 0,void 0,a):this.h.invoke(void 0,void 0,a):null};
Un.prototype.dispose=function(){this.h=null};
function Xn(a,b){a.h=b}
;var Yn=new Un;function Zn(){return!!Yn.h}
function $n(a){a=void 0===a?{}:a;return Yn.invoke(a)}
;var ao=window,bo=/[A-Za-z]+\/[0-9.]+/g;function co(a,b){if(a.replace(bo,"")!==b.replace(bo,""))return!1;a=a.match(bo);b=b.match(bo);if(a.length!==b.length)return!1;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(!d.startsWith(e)&&!e.startsWith(d))return!1}return!0}
function eo(){var a=ao.uaChPolyfill.state;if(0===a.type)V("clientHintsPolyfillEvent",{clientHintsSupported:!1});else{var b=navigator.userAgent,c=void 0!==a.syntheticUa&&co(a.syntheticUa,b),d={clientHintsSupported:!0,uaAccessedBeforePolyfill:a.didAccessUaBeforePolyfillAvailable,syntheticUaMatches:c};a.didAccessUaBeforePolyfillAvailable&&(d.uaAccessBeforePolyfillCount=a.uaAccessBeforePolyfillCount,a.firstAccessUaError&&(d.firstUaAccessStack=String(a.firstAccessUaError.stack).replace(/\n/g,""),Ml(a.firstAccessUaError)),
d.polyfillAvailabilityDelayMs=a.polyfillAvailabilityDelay);V("clientHintsPolyfillEvent",d);c||(b={syntheticUa:a.syntheticUa,ua:b},b.brand=a.data.brands.map(function(e){return'"'+e.brand+'"; v="'+e.version+'"'}),b.mobileness=a.data.mobile,a=a.data.values,a.architecture&&(b.platformArchitecture=a.architecture),a.model&&(b.model=a.model),a.platform&&(b.platformBrand=a.platform),a.platformVersion&&(b.platformVersion=a.platformVersion),a.uaFullVersion&&(b.fullVersion=a.uaFullVersion),V("clientHintsPolyfillDiagnostics",
b))}}
var fo=!1;function go(){var a;1===(null===(a=ao.uaChPolyfill)||void 0===a?void 0:a.state.type)?fo||(ao.uaChPolyfill.onReady=go,fo=!0):ao.uaChPolyfill&&eo()}
;function ho(a,b,c){J.call(this);var d=this;c=c||F("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.C="*";this.l=c;this.sessionId=null;this.channel="widget";this.J=!!a;this.B=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.J&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.C=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.A||0<=Za(d.A,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.A=this.i=this.m=null;window.addEventListener("message",this.B)}
v(ho,J);ho.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.C)}catch(d){qg(d)}}};
ho.prototype.D=function(){window.removeEventListener("message",this.B);J.prototype.D.call(this)};function io(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new ho(!!F("WIDGET_ID_ENFORCE")),b=this.Mb.bind(this);a.m=b;a.A=null;this.h.channel="widget";if(a=F("WIDGET_ID"))this.h.sessionId=a}
m=io.prototype;m.Mb=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,jo(this,a)),this.j[a]=!0)):this.Ra(a,b,c)};
m.Ra=function(){};
function jo(a,b){return function(c){return a.sendMessage(b,c)}}
m.addEventListener=function(){};
m.xb=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Ha());this.sendMessage("onReady");E(this.i,this.mb,this);this.i=[]};
m.Ha=function(){return null};
function ko(a,b){a.sendMessage("infoDelivery",b)}
m.mb=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.mb({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};function lo(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function mo(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function no(a,b,c,d){if(La(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function oo(a){io.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Tb.bind(this));this.addEventListener("onVolumeChange",this.Ub.bind(this));this.addEventListener("onApiChange",this.Ob.bind(this));this.addEventListener("onPlaybackQualityChange",this.Qb.bind(this));this.addEventListener("onPlaybackRateChange",this.Rb.bind(this));this.addEventListener("onStateChange",this.Sb.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Vb.bind(this))}
v(oo,io);m=oo.prototype;
m.Ra=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&lo(a)){var d=b;if(La(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=mo(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=mo(e);break;case "loadPlaylist":case "cuePlaylist":e=no(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);lo(a)&&ko(this,this.Ha())}};
m.onReady=function(){var a=this.xb.bind(this);this.h.i=a};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Ha=function(){if(!this.api)return null;var a=this.api.getApiInterface();db(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Sb=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());ko(this,a)};
m.Qb=function(a){ko(this,{playbackQuality:a})};
m.Rb=function(a){ko(this,{playbackRate:a})};
m.Ob=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Ub=function(){ko(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Tb=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());ko(this,a)};
m.Vb=function(){var a={sphericalProperties:this.api.getSphericalProperties()};ko(this,a)};
m.dispose=function(){io.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function po(a){J.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.ib,this)}
v(po,J);m=po.prototype;m.start=function(){this.started||this.h||(this.started=!0,this.connection.ea("RECEIVING"))};
m.ea=function(a,b){this.started&&!this.h&&this.connection.ea(a,b)};
m.ib=function(a,b,c){if(this.started&&!this.h){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=qo(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=ro(a,c))&&this.ea(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Pb.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Pb=function(a,b){this.started&&!this.h&&this.connection.ea(a,this.Ga(a,b))};
m.Ga=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.D=function(){var a=this.connection;a.h||Nf(a.i,"command",this.ib,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);J.prototype.D.call(this)};function so(a,b){po.call(this,b);this.api=a;this.start()}
v(so,po);so.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
so.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function qo(a,b){switch(a){case "loadVideoById":return a=mo(b),[a];case "cueVideoById":return a=mo(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=no(b),[a];case "cuePlaylist":return a=no(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function ro(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
so.prototype.Ga=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return po.prototype.Ga.call(this,a,b)};
so.prototype.D=function(){po.prototype.D.call(this);delete this.api};function to(a){a=void 0===a?!1:a;J.call(this);this.i=new L(a);se(this,Ta(qe,this.i))}
D(to,J);to.prototype.subscribe=function(a,b,c){return this.h?0:this.i.subscribe(a,b,c)};
to.prototype.l=function(a,b){this.h||this.i.da.apply(this.i,arguments)};function uo(a,b,c){to.call(this);this.j=a;this.destination=b;this.id=c}
v(uo,to);uo.prototype.ea=function(a,b){this.h||this.j.ea(this.destination,this.id,a,b)};
uo.prototype.D=function(){this.destination=this.j=null;to.prototype.D.call(this)};function vo(a,b,c){J.call(this);this.destination=a;this.origin=c;this.i=Dg(window,"message",this.j.bind(this));this.connection=new uo(this,a,b);se(this,Ta(qe,this.connection))}
v(vo,J);vo.prototype.ea=function(a,b,c,d){this.h||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(nf(a),this.origin))};
vo.prototype.j=function(a){var b;if(b=!this.h)if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h||c.l("command",b.command,b.data,a.origin))}};
vo.prototype.D=function(){Eg(this.i);this.destination=null;J.prototype.D.call(this)};function wo(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||nb(b);this.assets=a.assets||{};this.attrs=a.attrs||nb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
wo.prototype.clone=function(){var a=new wo,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ja(c)?a[b]=nb(c):a[b]=c}return a};var xo=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function yo(a){a=a||"";if(window.spf){var b=a.match(xo);spf.style.load(a,b?b[1]:"",void 0)}else zo(a)}
function zo(a){var b=Ao(a),c=document.getElementById(b),d=c&&Fn(c,"loaded");d||c&&!d||(c=Bo(a,b,function(){Fn(c,"loaded")||(Dn(c),Oh(b),Gg(Ta(Ph,b),0))}))}
function Bo(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=lf(a);ac(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Ao(a){var b=vd(document,"A");vb("This URL is never added to the DOM");$b(b,new Kb(a,Lb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+ec(a)}
;function Co(){J.call(this);this.i=[]}
v(Co,J);Co.prototype.D=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.Ta,void 0)}J.prototype.D.call(this)};function Do(){Co.apply(this,arguments)}
v(Do,Co);function Eo(a,b,c,d){J.call(this);var e=this;this.J=b;this.webPlayerContextConfig=d;this.Ca=!1;this.api={};this.ha=this.A=null;this.L=new L;this.i={};this.U=this.na=this.elementId=this.Da=this.config=null;this.T=!1;this.l=this.B=null;this.oa={};this.pb=["onReady"];this.lastError=null;this.Sa=NaN;this.C={};this.qb=new Do(this);this.ga=0;this.j=this.m=a;se(this,Ta(qe,this.L));Fo(this);Go(this);se(this,Ta(qe,this.qb));c?this.ga=Gg(function(){e.loadNewVideoConfig(c)},0):d&&(Ho(this),Io(this))}
v(Eo,J);m=Eo.prototype;m.getId=function(){return this.J};
m.loadNewVideoConfig=function(a){if(!this.h){this.ga&&(Hg(this.ga),this.ga=0);var b=a||{};b instanceof wo||(b=new wo(b));this.config=b;this.setConfig(a);Io(this);this.isReady()&&Jo(this)}};
function Ho(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.J,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.J:a.config.attrs.id=a.J);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){var b;this.Da=a;this.config=Ko(a);Ho(this);this.na||(this.na=Lo(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=Ed(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=Ed(Number(a)||a))};
function Jo(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function Mo(a){var b=!0,c=No(a);c&&a.config&&(a=Oo(a),b=Fn(c,"version")===a);return b&&!!C("yt.player.Application.create")}
function Io(a){if(!a.h&&!a.T){var b=Mo(a);if(b&&"html5"===(No(a)?"html5":null))a.U="html5",a.isReady()||Po(a);else if(Qo(a),a.U="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Po(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.B=function(){c=!0;var d=Ro(a,"player_bootstrap_method")?C("yt.player.Application.createAlternate")||C("yt.player.Application.create"):C("yt.player.Application.create");var e=a.config?Ko(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig);Po(a)};
a.T=!0;b?a.B():(Jn(Oo(a),a.B),(b=So(a))&&yo(b),To(a)&&!c&&A("yt.player.Application.create",null,void 0))}}}
function No(a){var b=rd(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Po(a){var b;if(!a.h){var c=No(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.T=!1,!Ro(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||Uo(a)):a.Sa=Gg(function(){Po(a)},50)}}
function Uo(a){Fo(a);a.Ca=!0;var b=No(a);if(b){a.A=Vo(a,b,"addEventListener");a.ha=Vo(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Vo(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.A&&a.A(g,a.i[g]);Jo(a);a.na&&a.na(a.api);a.L.da("onReady",a.api)}
function Vo(a,b,c){var d=b[c];return function(e){for(var f=[],g=0;g<arguments.length;++g)f[g-0]=arguments[g];try{return a.lastError=null,d.apply(b,f)}catch(h){"sendAbandonmentPing"!==c&&(h.params=c,a.lastError=h,Ll(h))}}}
function Fo(a){a.Ca=!1;if(a.ha)for(var b in a.i)a.i.hasOwnProperty(b)&&a.ha(b,a.i[b]);for(var c in a.C)a.C.hasOwnProperty(c)&&Hg(Number(c));a.C={};a.A=null;a.ha=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Da};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ca};
function Go(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Oh("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Oh("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){Oh("a11y-announce",b)})}
m.addEventListener=function(a,b){var c=this,d=Lo(this,b);d&&(0<=Za(this.pb,a)||this.i[a]||(b=Wo(this,a),this.A&&this.A(a,b)),this.L.subscribe(a,d),"onReady"===a&&this.isReady()&&Gg(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h||(b=Lo(this,b))&&Nf(this.L,a,b)};
function Lo(a,b){var c=b;if("string"===typeof b){if(a.oa[b])return a.oa[b];c=function(d){for(var e=[],f=0;f<arguments.length;++f)e[f-0]=arguments[f];if(f=C(b))try{f.apply(z,e)}catch(g){Ml(g)}};
a.oa[b]=c}return c?c:null}
function Wo(a,b){var c="ytPlayer"+b+a.J;a.i[b]=c;z[c]=function(d){var e=Gg(function(){if(!a.h){a.L.da(b,d);var f=a.C,g=String(e);g in f&&delete f[g]}},0);
kb(a.C,String(e))};
return c}
m.getPlayerType=function(){return this.U||(No(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function Qo(a){a.cancel();Fo(a);a.U=null;a.config&&(a.config.loaded=!1);var b=No(a);b&&(Mo(a)||!To(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.B&&Pn(Oo(this),this.B);Hg(this.Sa);this.T=!1};
m.D=function(){Qo(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Ml(b)}this.oa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(z[this.i[a]]=null);this.Da=this.config=this.api=null;delete this.m;delete this.j;J.prototype.D.call(this)};
function To(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Oo(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function So(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Ro(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===$g(d||"","&")[b]}
function Ko(a){for(var b={},c=u(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?nb(e):e}return b}
;var Xo={},Yo="player_uid_"+(1E9*Math.random()>>>0);function Zo(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?rd(d):d;var e=Yo+"_"+Na(d),f=Xo[e];if(f&&c)return $o(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Eo(d,e,a,b);Xo[e]=f;Oh("player-added",f.api);se(f,function(){delete Xo[f.getId()]});
return f.api}
function $o(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var ap=null,bp=null,cp=null;function dp(){var a=ap.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function ep(a,b,c){a="ST-"+ec(a).toString(36);b=b?jc(b):"";c=c||5;Wl()&&oi(a,b,c)}
;function fp(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=F("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=F("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=hc(window.location.href);g&&f.push(g);g=hc(d);if(0<=Za(f,g)||!g&&0==d.lastIndexOf("/",0))if(N("autoescape_tempdata_url")&&(f=document.createElement("a"),$b(f,d),d=f.href),d){g=d.match(fc);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:qm()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&ep(d,b,k)}else ep(d,b)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var n=void 0===n?"":n;var p=void 0===p?window:p;c=p.location;a=kc(a,l)+n;var r=void 0===r?md:r;a:{r=void 0===r?md:r;for(l=0;l<r.length;++l)if(n=r[l],n instanceof kd&&n.isValid(a)){r=new id(a,gd);break a}r=void 0}c.href=nd(r||jd)}return!0}
;A("yt.setConfig",M,void 0);A("yt.config.set",M,void 0);A("yt.setMsg",sg,void 0);A("yt.msgs.set",sg,void 0);A("yt.logging.errors.log",Ml,void 0);
A("writeEmbed",function(){var a=F("PLAYER_CONFIG",void 0);if(!a){var b=F("PLAYER_VARS",void 0);b&&(a={args:b})}dm(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=F("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);N("embeds_js_api_set_1p_cookie")&&(c=eh(),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));M("FORCE_CSI_ON_GEL",!0);
c=["ol"];$m("").info.actionType="embed";c&&M("TIMING_AFT_KEYS",c);M("TIMING_ACTION","embed");c=F("TIMING_INFO",{});for(var d in c)c.hasOwnProperty(d)&&rn(d,c[d]);rn("is_nav",1);(d=qm())&&rn("csn",d);(d=F("PREVIOUS_ACTION",void 0))&&!mn()&&rn("pa",d);d=Vm();c=F("CLIENT_PROTOCOL");var e=F("CLIENT_TRANSPORT");c&&rn("p",c);e&&rn("t",e);rn("yt_vis",un());rn("yt_lt","cold");c=Rm();if(e=Tm())Z("srt",c.responseStart),1!==d.prerender&&(rn("yt_sts","n",void 0),Z("_start",e,void 0));d=Ym();0<d&&Z("fpt",d);d=
Rm();d.isPerformanceNavigationTiming&&rn("pnt",1,void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Tm()&&0<d.connectEnd-
d.secureConnectionStart&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));W&&W.getEntriesByType&&wn();d=[];if(document.querySelector&&W&&W.getEntriesByName)for(var f in Om)Om.hasOwnProperty(f)&&(c=Om[f],vn(f,c)&&d.push(c));for(f=0;f<d.length;f++)rn("rc",d[f]);if(mn(void 0)){f={actionType:fn[F("TIMING_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN",previousAction:fn[F("PREVIOUS_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN"};if(d=qm())f.clientScreenNonce=d;d=Wm(void 0);c=Um(void 0).cttAuthInfo;
dn().info(f,d,c)}f=Vm();c=Qm();if("cold"===f.yt_lt&&(d=on(),e=d.gelTicks?d.gelTicks:d.gelTicks={},d=d.gelInfos?d.gelInfos:d.gelInfos={},mn())){for(var g in c)"tick_"+g in e||nn(g,c[g]);g=qn();c=Wm();e=Um().cttAuthInfo;var h={},k=!1,l;for(l in f)if(!("info_"+l in d)){var n=pn(l,f[l]);n&&(Cm(g,n),Cm(h,n),k=!0)}k&&dn().info(h,c,e)}A("ytglobal.timingready_",!0,void 0);sn();(l=F("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in l?(l=l.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,
l.serializedForcedExperimentIds||(g=eh(),g.forced_experiments&&(l.serializedForcedExperimentIds=g.forced_experiments)),ap=Zo(a,l,!1)):ap=Zo(a);ap.addEventListener("onVideoDataChange",dp);a=F("POST_MESSAGE_ID","player");F("ENABLE_JS_API")?cp=new oo(ap):F("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(bp=new vo(window.parent,a,b),cp=new so(ap,bp.connection));Sn();N("networkless_logging_web_embedded")&&(N("embeds_web_enable_new_nwl")?rl():$k());N("embeds_enable_ua_ch_polyfill")&&go()},
void 0);
var gp=og(function(){tn();var a=qi.getInstance(),b=!!((ti("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&ve(document.body,"exp-invert-logo"))if(c&&!ve(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!ve(d,"inverted-hdpi")){var e=te(d);ue(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&ve(document.body,"inverted-hdpi")&&we();if(b!=c){b="f"+(Math.floor(119/31)+1);d=ti(b)||0;d=c?d|67108864:
d&-67108865;0==d?delete pi[b]:(c=d.toString(16),pi[b]=c.toString());c=!0;N("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in pi)d.push(f+"="+encodeURIComponent(String(pi[f])));oi(b,d.join("&"),63072E3,a.i,c)}yn.h||(yn.h=new yn);a=yn.h;f=16623;var g=void 0===g?{}:g;Object.values(Ol).includes(f)||(Ll(new Ni("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.o=[];a.A=[];g.Xa?Bn(a,f,g):Cn(a,f,g)}),hp=og(function(){ap&&
ap.sendAbandonmentPing&&ap.sendAbandonmentPing();
F("PL_ATT")&&Yn.dispose();for(var a=0,b=Qn.length;a<b;a++)Pg(Qn[a]);Qn.length=0;On("//static.doubleclick.net/instream/ad_status.js");Rn=!1;M("DCLKSTAT",0);re(cp,bp);ap&&(ap.removeEventListener("onVideoDataChange",dp),ap.destroy())});
window.addEventListener?(window.addEventListener("load",gp),window.addEventListener("unload",hp)):window.attachEvent&&(window.attachEvent("onload",gp),window.attachEvent("onunload",hp));Ua("yt.abuse.player.botguardInitialized",C("yt.abuse.player.botguardInitialized")||Zn);Ua("yt.abuse.player.invokeBotguard",C("yt.abuse.player.invokeBotguard")||$n);Ua("yt.abuse.dclkstatus.checkDclkStatus",C("yt.abuse.dclkstatus.checkDclkStatus")||Tn);
Ua("yt.player.exports.navigate",C("yt.player.exports.navigate")||fp);Ua("yt.util.activity.init",C("yt.util.activity.init")||Rg);Ua("yt.util.activity.getTimeSinceActive",C("yt.util.activity.getTimeSinceActive")||Ug);Ua("yt.util.activity.setTimestamp",C("yt.util.activity.setTimestamp")||Sg);}).call(this);
