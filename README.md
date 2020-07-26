<!doctype html>
<html dir="ltr" class="details"><head><style class="vjs-styles-defaults">
      .video-js {
        width: 300px;
        height: 150px;
      }

      .vjs-fluid {
        padding-top: 56.25%
      }
    </style><script type="text/javascript" src="https://bam.nr-data.net/1/10f957f1ae?a=3787364&amp;v=1169.7b094c0&amp;to=IV8LTUAOWVwER0lcVBRVCWZBDkBCAlAVH0IKXxI%3D&amp;rst=2436&amp;ck=1&amp;ref=https://studio.code.org/c/1160767285&amp;ap=51&amp;be=393&amp;fe=2408&amp;dc=2370&amp;af=err,xhr,stn,ins,spa&amp;perf=%7B%22timing%22:%7B%22of%22:1595768080084,%22n%22:0,%22f%22:6,%22dn%22:6,%22dne%22:6,%22c%22:6,%22ce%22:6,%22rq%22:26,%22rp%22:319,%22rpe%22:324,%22dl%22:335,%22di%22:2367,%22ds%22:2369,%22de%22:2398,%22dc%22:2404,%22l%22:2406,%22le%22:2415%7D,%22navigation%22:%7B%7D%7D&amp;fp=1898&amp;fcp=1898&amp;jsonp=NREUM.setToken"></script><script src="https://js-agent.newrelic.com/nr-spa-1169.min.js"></script><script type="text/javascript" async="" src="//cdn3.optimizely.com/js/geo2.js"></script>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Code.org</title>

<script async="" src="https://www.googletagmanager.com/gtm.js?id=GTM-TZZBRK5"></script><script async="" src="//www.google-analytics.com/analytics.js"></script><script>window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"10f957f1ae","applicationID":"3787364","transactionName":"IV8LTUAOWVwER0lcVBRVCWZBDkBCAlAVH0IKXxI=","queueTime":0,"applicationTime":51,"agent":""}</script>
<script>(window.NREUM||(NREUM={})).loader_config={xpid:"UQYGVVBQGwAHXFZRAQU=",licenseKey:"10f957f1ae",applicationID:"3787364"};window.NREUM||(NREUM={}),__nr_require=function(t,e,n){function r(n){if(!e[n]){var o=e[n]={exports:{}};t[n][0].call(o.exports,function(e){var o=t[n][1][e];return r(o||e)},o,o.exports)}return e[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var o=0;o<n.length;o++)r(n[o]);return r}({1:[function(t,e,n){function r(t){try{s.console&&console.log(t)}catch(e){}}var o,i=t("ee"),a=t(25),s={};try{o=localStorage.getItem("__nr_flags").split(","),console&&"function"==typeof console.log&&(s.console=!0,o.indexOf("dev")!==-1&&(s.dev=!0),o.indexOf("nr_dev")!==-1&&(s.nrDev=!0))}catch(c){}s.nrDev&&i.on("internal-error",function(t){r(t.stack)}),s.dev&&i.on("fn-err",function(t,e,n){r(n.stack)}),s.dev&&(r("NR AGENT IN DEVELOPMENT MODE"),r("flags: "+a(s,function(t,e){return t}).join(", ")))},{}],2:[function(t,e,n){function r(t,e,n,r,s){try{l?l-=1:o(s||new UncaughtException(t,e,n),!0)}catch(f){try{i("ierr",[f,c.now(),!0])}catch(d){}}return"function"==typeof u&&u.apply(this,a(arguments))}function UncaughtException(t,e,n){this.message=t||"Uncaught error with no additional information",this.sourceURL=e,this.line=n}function o(t,e){var n=e?null:c.now();i("err",[t,n])}var i=t("handle"),a=t(26),s=t("ee"),c=t("loader"),f=t("gos"),u=window.onerror,d=!1,p="nr@seenError",l=0;c.features.err=!0,t(1),window.onerror=r;try{throw new Error}catch(h){"stack"in h&&(t(13),t(12),"addEventListener"in window&&t(6),c.xhrWrappable&&t(14),d=!0)}s.on("fn-start",function(t,e,n){d&&(l+=1)}),s.on("fn-err",function(t,e,n){d&&!n[p]&&(f(n,p,function(){return!0}),this.thrown=!0,o(n))}),s.on("fn-end",function(){d&&!this.thrown&&l>0&&(l-=1)}),s.on("internal-error",function(t){i("ierr",[t,c.now(),!0])})},{}],3:[function(t,e,n){t("loader").features.ins=!0},{}],4:[function(t,e,n){function r(){L++,C=g.hash,this[u]=y.now()}function o(){L--,g.hash!==C&&i(0,!0);var t=y.now();this[h]=~~this[h]+t-this[u],this[d]=t}function i(t,e){E.emit("newURL",[""+g,e])}function a(t,e){t.on(e,function(){this[e]=y.now()})}var s="-start",c="-end",f="-body",u="fn"+s,d="fn"+c,p="cb"+s,l="cb"+c,h="jsTime",m="fetch",v="addEventListener",w=window,g=w.location,y=t("loader");if(w[v]&&y.xhrWrappable){var x=t(10),b=t(11),E=t(8),O=t(6),R=t(13),P=t(7),T=t(14),N=t(9),M=t("ee"),S=M.get("tracer");t(16),y.features.spa=!0;var C,L=0;M.on(u,r),M.on(p,r),M.on(d,o),M.on(l,o),M.buffer([u,d,"xhr-done","xhr-resolved"]),O.buffer([u]),R.buffer(["setTimeout"+c,"clearTimeout"+s,u]),T.buffer([u,"new-xhr","send-xhr"+s]),P.buffer([m+s,m+"-done",m+f+s,m+f+c]),E.buffer(["newURL"]),x.buffer([u]),b.buffer(["propagate",p,l,"executor-err","resolve"+s]),S.buffer([u,"no-"+u]),N.buffer(["new-jsonp","cb-start","jsonp-error","jsonp-end"]),a(T,"send-xhr"+s),a(M,"xhr-resolved"),a(M,"xhr-done"),a(P,m+s),a(P,m+"-done"),a(N,"new-jsonp"),a(N,"jsonp-end"),a(N,"cb-start"),E.on("pushState-end",i),E.on("replaceState-end",i),w[v]("hashchange",i,!0),w[v]("load",i,!0),w[v]("popstate",function(){i(0,L>1)},!0)}},{}],5:[function(t,e,n){function r(t){}if(window.performance&&window.performance.timing&&window.performance.getEntriesByType){var o=t("ee"),i=t("handle"),a=t(13),s=t(12),c="learResourceTimings",f="addEventListener",u="resourcetimingbufferfull",d="bstResource",p="resource",l="-start",h="-end",m="fn"+l,v="fn"+h,w="bstTimer",g="pushState",y=t("loader");y.features.stn=!0,t(8),"addEventListener"in window&&t(6);var x=NREUM.o.EV;o.on(m,function(t,e){var n=t[0];n instanceof x&&(this.bstStart=y.now())}),o.on(v,function(t,e){var n=t[0];n instanceof x&&i("bst",[n,e,this.bstStart,y.now()])}),a.on(m,function(t,e,n){this.bstStart=y.now(),this.bstType=n}),a.on(v,function(t,e){i(w,[e,this.bstStart,y.now(),this.bstType])}),s.on(m,function(){this.bstStart=y.now()}),s.on(v,function(t,e){i(w,[e,this.bstStart,y.now(),"requestAnimationFrame"])}),o.on(g+l,function(t){this.time=y.now(),this.startPath=location.pathname+location.hash}),o.on(g+h,function(t){i("bstHist",[location.pathname+location.hash,this.startPath,this.time])}),f in window.performance&&(window.performance["c"+c]?window.performance[f](u,function(t){i(d,[window.performance.getEntriesByType(p)]),window.performance["c"+c]()},!1):window.performance[f]("webkit"+u,function(t){i(d,[window.performance.getEntriesByType(p)]),window.performance["webkitC"+c]()},!1)),document[f]("scroll",r,{passive:!0}),document[f]("keypress",r,!1),document[f]("click",r,!1)}},{}],6:[function(t,e,n){function r(t){for(var e=t;e&&!e.hasOwnProperty(u);)e=Object.getPrototypeOf(e);e&&o(e)}function o(t){s.inPlace(t,[u,d],"-",i)}function i(t,e){return t[1]}var a=t("ee").get("events"),s=t("wrap-function")(a,!0),c=t("gos"),f=XMLHttpRequest,u="addEventListener",d="removeEventListener";e.exports=a,"getPrototypeOf"in Object?(r(document),r(window),r(f.prototype)):f.prototype.hasOwnProperty(u)&&(o(window),o(f.prototype)),a.on(u+"-start",function(t,e){var n=t[1],r=c(n,"nr@wrapped",function(){function t(){if("function"==typeof n.handleEvent)return n.handleEvent.apply(n,arguments)}var e={object:t,"function":n}[typeof n];return e?s(e,"fn-",null,e.name||"anonymous"):n});this.wrapped=t[1]=r}),a.on(d+"-start",function(t){t[1]=this.wrapped||t[1]})},{}],7:[function(t,e,n){function r(t,e,n){var r=t[e];"function"==typeof r&&(t[e]=function(){var t=i(arguments),e={};o.emit(n+"before-start",[t],e);var a;e[m]&&e[m].dt&&(a=e[m].dt);var s=r.apply(this,t);return o.emit(n+"start",[t,a],s),s.then(function(t){return o.emit(n+"end",[null,t],s),t},function(t){throw o.emit(n+"end",[t],s),t})})}var o=t("ee").get("fetch"),i=t(26),a=t(25);e.exports=o;var s=window,c="fetch-",f=c+"body-",u=["arrayBuffer","blob","json","text","formData"],d=s.Request,p=s.Response,l=s.fetch,h="prototype",m="nr@context";d&&p&&l&&(a(u,function(t,e){r(d[h],e,f),r(p[h],e,f)}),r(s,"fetch",c),o.on(c+"end",function(t,e){var n=this;if(e){var r=e.headers.get("content-length");null!==r&&(n.rxSize=r),o.emit(c+"done",[null,e],n)}else o.emit(c+"done",[t],n)}))},{}],8:[function(t,e,n){var r=t("ee").get("history"),o=t("wrap-function")(r);e.exports=r;var i=window.history&&window.history.constructor&&window.history.constructor.prototype,a=window.history;i&&i.pushState&&i.replaceState&&(a=i),o.inPlace(a,["pushState","replaceState"],"-")},{}],9:[function(t,e,n){function r(t){function e(){c.emit("jsonp-end",[],p),t.removeEventListener("load",e,!1),t.removeEventListener("error",n,!1)}function n(){c.emit("jsonp-error",[],p),c.emit("jsonp-end",[],p),t.removeEventListener("load",e,!1),t.removeEventListener("error",n,!1)}var r=t&&"string"==typeof t.nodeName&&"script"===t.nodeName.toLowerCase();if(r){var o="function"==typeof t.addEventListener;if(o){var a=i(t.src);if(a){var u=s(a),d="function"==typeof u.parent[u.key];if(d){var p={};f.inPlace(u.parent,[u.key],"cb-",p),t.addEventListener("load",e,!1),t.addEventListener("error",n,!1),c.emit("new-jsonp",[t.src],p)}}}}}function o(){return"addEventListener"in window}function i(t){var e=t.match(u);return e?e[1]:null}function a(t,e){var n=t.match(p),r=n[1],o=n[3];return o?a(o,e[r]):e[r]}function s(t){var e=t.match(d);return e&&e.length>=3?{key:e[2],parent:a(e[1],window)}:{key:t,parent:window}}var c=t("ee").get("jsonp"),f=t("wrap-function")(c);if(e.exports=c,o()){var u=/[?&](?:callback|cb)=([^&#]+)/,d=/(.*)\.([^.]+)/,p=/^(\w+)(\.|$)(.*)$/,l=["appendChild","insertBefore","replaceChild"];Node&&Node.prototype&&Node.prototype.appendChild?f.inPlace(Node.prototype,l,"dom-"):(f.inPlace(HTMLElement.prototype,l,"dom-"),f.inPlace(HTMLHeadElement.prototype,l,"dom-"),f.inPlace(HTMLBodyElement.prototype,l,"dom-")),c.on("dom-start",function(t){r(t[0])})}},{}],10:[function(t,e,n){var r=t("ee").get("mutation"),o=t("wrap-function")(r),i=NREUM.o.MO;e.exports=r,i&&(window.MutationObserver=function(t){return this instanceof i?new i(o(t,"fn-")):i.apply(this,arguments)},MutationObserver.prototype=i.prototype)},{}],11:[function(t,e,n){function r(t){var e=a.context(),n=s(t,"executor-",e),r=new f(n);return a.context(r).getCtx=function(){return e},a.emit("new-promise",[r,e],e),r}function o(t,e){return e}var i=t("wrap-function"),a=t("ee").get("promise"),s=i(a),c=t(25),f=NREUM.o.PR;e.exports=a,f&&(window.Promise=r,["all","race"].forEach(function(t){var e=f[t];f[t]=function(n){function r(t){return function(){a.emit("propagate",[null,!o],i),o=o||!t}}var o=!1;c(n,function(e,n){Promise.resolve(n).then(r("all"===t),r(!1))});var i=e.apply(f,arguments),s=f.resolve(i);return s}}),["resolve","reject"].forEach(function(t){var e=f[t];f[t]=function(t){var n=e.apply(f,arguments);return t!==n&&a.emit("propagate",[t,!0],n),n}}),f.prototype["catch"]=function(t){return this.then(null,t)},f.prototype=Object.create(f.prototype,{constructor:{value:r}}),c(Object.getOwnPropertyNames(f),function(t,e){try{r[e]=f[e]}catch(n){}}),a.on("executor-start",function(t){t[0]=s(t[0],"resolve-",this),t[1]=s(t[1],"resolve-",this)}),a.on("executor-err",function(t,e,n){t[1](n)}),s.inPlace(f.prototype,["then"],"then-",o),a.on("then-start",function(t,e){this.promise=e,t[0]=s(t[0],"cb-",this),t[1]=s(t[1],"cb-",this)}),a.on("then-end",function(t,e,n){this.nextPromise=n;var r=this.promise;a.emit("propagate",[r,!0],n)}),a.on("cb-end",function(t,e,n){a.emit("propagate",[n,!0],this.nextPromise)}),a.on("propagate",function(t,e,n){this.getCtx&&!e||(this.getCtx=function(){if(t instanceof Promise)var e=a.context(t);return e&&e.getCtx?e.getCtx():this})}),r.toString=function(){return""+f})},{}],12:[function(t,e,n){var r=t("ee").get("raf"),o=t("wrap-function")(r),i="equestAnimationFrame";e.exports=r,o.inPlace(window,["r"+i,"mozR"+i,"webkitR"+i,"msR"+i],"raf-"),r.on("raf-start",function(t){t[0]=o(t[0],"fn-")})},{}],13:[function(t,e,n){function r(t,e,n){t[0]=a(t[0],"fn-",null,n)}function o(t,e,n){this.method=n,this.timerDuration=isNaN(t[1])?0:+t[1],t[0]=a(t[0],"fn-",this,n)}var i=t("ee").get("timer"),a=t("wrap-function")(i),s="setTimeout",c="setInterval",f="clearTimeout",u="-start",d="-";e.exports=i,a.inPlace(window,[s,"setImmediate"],s+d),a.inPlace(window,[c],c+d),a.inPlace(window,[f,"clearImmediate"],f+d),i.on(c+u,r),i.on(s+u,o)},{}],14:[function(t,e,n){function r(t,e){d.inPlace(e,["onreadystatechange"],"fn-",s)}function o(){var t=this,e=u.context(t);t.readyState>3&&!e.resolved&&(e.resolved=!0,u.emit("xhr-resolved",[],t)),d.inPlace(t,g,"fn-",s)}function i(t){y.push(t),h&&(b?b.then(a):v?v(a):(E=-E,O.data=E))}function a(){for(var t=0;t<y.length;t++)r([],y[t]);y.length&&(y=[])}function s(t,e){return e}function c(t,e){for(var n in t)e[n]=t[n];return e}t(6);var f=t("ee"),u=f.get("xhr"),d=t("wrap-function")(u),p=NREUM.o,l=p.XHR,h=p.MO,m=p.PR,v=p.SI,w="readystatechange",g=["onload","onerror","onabort","onloadstart","onloadend","onprogress","ontimeout"],y=[];e.exports=u;var x=window.XMLHttpRequest=function(t){var e=new l(t);try{u.emit("new-xhr",[e],e),e.addEventListener(w,o,!1)}catch(n){try{u.emit("internal-error",[n])}catch(r){}}return e};if(c(l,x),x.prototype=l.prototype,d.inPlace(x.prototype,["open","send"],"-xhr-",s),u.on("send-xhr-start",function(t,e){r(t,e),i(e)}),u.on("open-xhr-start",r),h){var b=m&&m.resolve();if(!v&&!m){var E=1,O=document.createTextNode(E);new h(a).observe(O,{characterData:!0})}}else f.on("fn-end",function(t){t[0]&&t[0].type===w||a()})},{}],15:[function(t,e,n){function r(t){if(!i(t))return null;var e=window.NREUM;if(!e.loader_config)return null;var n=(e.loader_config.accountID||"").toString()||null,r=(e.loader_config.agentID||"").toString()||null,s=(e.loader_config.trustKey||"").toString()||null;if(!n||!r)return null;var c=a.generateCatId(),f=a.generateCatId(),u=Date.now(),d=o(c,f,u,n,r,s);return{header:d,guid:c,traceId:f,timestamp:u}}function o(t,e,n,r,o,i){var a="btoa"in window&&"function"==typeof window.btoa;if(!a)return null;var s={v:[0,1],d:{ty:"Browser",ac:r,ap:o,id:t,tr:e,ti:n}};return i&&r!==i&&(s.d.tk=i),btoa(JSON.stringify(s))}function i(t){var e=!1,n=!1,r={};if("init"in NREUM&&"distributed_tracing"in NREUM.init&&(r=NREUM.init.distributed_tracing,n=!!r.enabled),n)if(t.sameOrigin)e=!0;else if(r.allowed_origins instanceof Array)for(var o=0;o<r.allowed_origins.length;o++){var i=s(r.allowed_origins[o]);if(t.hostname===i.hostname&&t.protocol===i.protocol&&t.port===i.port){e=!0;break}}return n&&e}var a=t(23),s=t(17);e.exports={generateTracePayload:r,shouldGenerateTrace:i}},{}],16:[function(t,e,n){function r(t){var e=this.params,n=this.metrics;if(!this.ended){this.ended=!0;for(var r=0;r<p;r++)t.removeEventListener(d[r],this.listener,!1);e.aborted||(n.duration=a.now()-this.startTime,this.loadCaptureCalled||4!==t.readyState?null==e.status&&(e.status=0):i(this,t),n.cbTime=this.cbTime,u.emit("xhr-done",[t],t),s("xhr",[e,n,this.startTime]))}}function o(t,e){var n=c(e),r=t.params;r.host=n.hostname+":"+n.port,r.pathname=n.pathname,t.parsedOrigin=c(e),t.sameOrigin=t.parsedOrigin.sameOrigin}function i(t,e){t.params.status=e.status;var n=v(e,t.lastSize);if(n&&(t.metrics.rxSize=n),t.sameOrigin){var r=e.getResponseHeader("X-NewRelic-App-Data");r&&(t.params.cat=r.split(", ").pop())}t.loadCaptureCalled=!0}var a=t("loader");if(a.xhrWrappable){var s=t("handle"),c=t(17),f=t(15).generateTracePayload,u=t("ee"),d=["load","error","abort","timeout"],p=d.length,l=t("id"),h=t(21),m=t(20),v=t(18),w=window.XMLHttpRequest;a.features.xhr=!0,t(14),t(7),u.on("new-xhr",function(t){var e=this;e.totalCbs=0,e.called=0,e.cbTime=0,e.end=r,e.ended=!1,e.xhrGuids={},e.lastSize=null,e.loadCaptureCalled=!1,t.addEventListener("load",function(n){i(e,t)},!1),h&&(h>34||h<10)||window.opera||t.addEventListener("progress",function(t){e.lastSize=t.loaded},!1)}),u.on("open-xhr-start",function(t){this.params={method:t[0]},o(this,t[1]),this.metrics={}}),u.on("open-xhr-end",function(t,e){"loader_config"in NREUM&&"xpid"in NREUM.loader_config&&this.sameOrigin&&e.setRequestHeader("X-NewRelic-ID",NREUM.loader_config.xpid);var n=f(this.parsedOrigin);n&&n.header&&(e.setRequestHeader("newrelic",n.header),this.dt=n)}),u.on("send-xhr-start",function(t,e){var n=this.metrics,r=t[0],o=this;if(n&&r){var i=m(r);i&&(n.txSize=i)}this.startTime=a.now(),this.listener=function(t){try{"abort"!==t.type||o.loadCaptureCalled||(o.params.aborted=!0),("load"!==t.type||o.called===o.totalCbs&&(o.onloadCalled||"function"!=typeof e.onload))&&o.end(e)}catch(n){try{u.emit("internal-error",[n])}catch(r){}}};for(var s=0;s<p;s++)e.addEventListener(d[s],this.listener,!1)}),u.on("xhr-cb-time",function(t,e,n){this.cbTime+=t,e?this.onloadCalled=!0:this.called+=1,this.called!==this.totalCbs||!this.onloadCalled&&"function"==typeof n.onload||this.end(n)}),u.on("xhr-load-added",function(t,e){var n=""+l(t)+!!e;this.xhrGuids&&!this.xhrGuids[n]&&(this.xhrGuids[n]=!0,this.totalCbs+=1)}),u.on("xhr-load-removed",function(t,e){var n=""+l(t)+!!e;this.xhrGuids&&this.xhrGuids[n]&&(delete this.xhrGuids[n],this.totalCbs-=1)}),u.on("addEventListener-end",function(t,e){e instanceof w&&"load"===t[0]&&u.emit("xhr-load-added",[t[1],t[2]],e)}),u.on("removeEventListener-end",function(t,e){e instanceof w&&"load"===t[0]&&u.emit("xhr-load-removed",[t[1],t[2]],e)}),u.on("fn-start",function(t,e,n){e instanceof w&&("onload"===n&&(this.onload=!0),("load"===(t[0]&&t[0].type)||this.onload)&&(this.xhrCbStart=a.now()))}),u.on("fn-end",function(t,e){this.xhrCbStart&&u.emit("xhr-cb-time",[a.now()-this.xhrCbStart,this.onload,e],e)}),u.on("fetch-before-start",function(t){var e,n=t[1]||{};"string"==typeof t[0]?e=t[0]:t[0]&&t[0].url&&(e=t[0].url),e&&(this.parsedOrigin=c(e),this.sameOrigin=this.parsedOrigin.sameOrigin);var r=f(this.parsedOrigin);if(r&&r.header){var o=r.header;if("string"==typeof t[0]){var i={};for(var a in n)i[a]=n[a];i.headers=new Headers(n.headers||{}),i.headers.set("newrelic",o),this.dt=r,t.length>1?t[1]=i:t.push(i)}else t[0]&&t[0].headers&&(t[0].headers.append("newrelic",o),this.dt=r)}})}},{}],17:[function(t,e,n){var r={};e.exports=function(t){if(t in r)return r[t];var e=document.createElement("a"),n=window.location,o={};e.href=t,o.port=e.port;var i=e.href.split("://");!o.port&&i[1]&&(o.port=i[1].split("/")[0].split("@").pop().split(":")[1]),o.port&&"0"!==o.port||(o.port="https"===i[0]?"443":"80"),o.hostname=e.hostname||n.hostname,o.pathname=e.pathname,o.protocol=i[0],"/"!==o.pathname.charAt(0)&&(o.pathname="/"+o.pathname);var a=!e.protocol||":"===e.protocol||e.protocol===n.protocol,s=e.hostname===document.domain&&e.port===n.port;return o.sameOrigin=a&&(!e.hostname||s),"/"===o.pathname&&(r[t]=o),o}},{}],18:[function(t,e,n){function r(t,e){var n=t.responseType;return"json"===n&&null!==e?e:"arraybuffer"===n||"blob"===n||"json"===n?o(t.response):"text"===n||""===n||void 0===n?o(t.responseText):void 0}var o=t(20);e.exports=r},{}],19:[function(t,e,n){function r(){}function o(t,e,n){return function(){return i(t,[f.now()].concat(s(arguments)),e?null:this,n),e?void 0:this}}var i=t("handle"),a=t(25),s=t(26),c=t("ee").get("tracer"),f=t("loader"),u=NREUM;"undefined"==typeof window.newrelic&&(newrelic=u);var d=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],p="api-",l=p+"ixn-";a(d,function(t,e){u[e]=o(p+e,!0,"api")}),u.addPageAction=o(p+"addPageAction",!0),u.setCurrentRouteName=o(p+"routeName",!0),e.exports=newrelic,u.interaction=function(){return(new r).get()};var h=r.prototype={createTracer:function(t,e){var n={},r=this,o="function"==typeof e;return i(l+"tracer",[f.now(),t,n],r),function(){if(c.emit((o?"":"no-")+"fn-start",[f.now(),r,o],n),o)try{return e.apply(this,arguments)}catch(t){throw c.emit("fn-err",[arguments,this,t],n),t}finally{c.emit("fn-end",[f.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(t,e){h[e]=o(l+e)}),newrelic.noticeError=function(t,e){"string"==typeof t&&(t=new Error(t)),i("err",[t,f.now(),!1,e])}},{}],20:[function(t,e,n){e.exports=function(t){if("string"==typeof t&&t.length)return t.length;if("object"==typeof t){if("undefined"!=typeof ArrayBuffer&&t instanceof ArrayBuffer&&t.byteLength)return t.byteLength;if("undefined"!=typeof Blob&&t instanceof Blob&&t.size)return t.size;if(!("undefined"!=typeof FormData&&t instanceof FormData))try{return JSON.stringify(t).length}catch(e){return}}}},{}],21:[function(t,e,n){var r=0,o=navigator.userAgent.match(/Firefox[\/\s](\d+\.\d+)/);o&&(r=+o[1]),e.exports=r},{}],22:[function(t,e,n){function r(t,e){var n=t.getEntries();n.forEach(function(t){"first-paint"===t.name?c("timing",["fp",Math.floor(t.startTime)]):"first-contentful-paint"===t.name&&c("timing",["fcp",Math.floor(t.startTime)])})}function o(t,e){var n=t.getEntries();n.length>0&&c("lcp",[n[n.length-1]])}function i(t){if(t instanceof u&&!p){var e,n=Math.round(t.timeStamp);e=n>1e12?Date.now()-n:f.now()-n,p=!0,c("timing",["fi",n,{type:t.type,fid:e}])}}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var a,s,c=t("handle"),f=t("loader"),u=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){a=new PerformanceObserver(r),s=new PerformanceObserver(o);try{a.observe({entryTypes:["paint"]}),s.observe({entryTypes:["largest-contentful-paint"]})}catch(d){}}if("addEventListener"in document){var p=!1,l=["click","keydown","mousedown","pointerdown","touchstart"];l.forEach(function(t){document.addEventListener(t,i,!1)})}}},{}],23:[function(t,e,n){function r(){function t(){return e?15&e[n++]:16*Math.random()|0}var e=null,n=0,r=window.crypto||window.msCrypto;r&&r.getRandomValues&&(e=r.getRandomValues(new Uint8Array(31)));for(var o,i="xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx",a="",s=0;s<i.length;s++)o=i[s],"x"===o?a+=t().toString(16):"y"===o?(o=3&t()|8,a+=o.toString(16)):a+=o;return a}function o(){function t(){return e?15&e[n++]:16*Math.random()|0}var e=null,n=0,r=window.crypto||window.msCrypto;r&&r.getRandomValues&&Uint8Array&&(e=r.getRandomValues(new Uint8Array(31)));for(var o=[],i=0;i<16;i++)o.push(t().toString(16));return o.join("")}e.exports={generateUuid:r,generateCatId:o}},{}],24:[function(t,e,n){function r(t,e){if(!o)return!1;if(t!==o)return!1;if(!e)return!0;if(!i)return!1;for(var n=i.split("."),r=e.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var o=null,i=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var s=navigator.userAgent,c=s.match(a);c&&s.indexOf("Chrome")===-1&&s.indexOf("Chromium")===-1&&(o="Safari",i=c[1])}e.exports={agent:o,version:i,match:r}},{}],25:[function(t,e,n){function r(t,e){var n=[],r="",i=0;for(r in t)o.call(t,r)&&(n[i]=e(r,t[r]),i+=1);return n}var o=Object.prototype.hasOwnProperty;e.exports=r},{}],26:[function(t,e,n){function r(t,e,n){e||(e=0),"undefined"==typeof n&&(n=t?t.length:0);for(var r=-1,o=n-e||0,i=Array(o<0?0:o);++r<o;)i[r]=t[e+r];return i}e.exports=r},{}],27:[function(t,e,n){e.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(t,e,n){function r(){}function o(t){function e(t){return t&&t instanceof r?t:t?c(t,s,i):i()}function n(n,r,o,i){if(!p.aborted||i){t&&t(n,r,o);for(var a=e(o),s=m(n),c=s.length,f=0;f<c;f++)s[f].apply(a,r);var d=u[y[n]];return d&&d.push([x,n,r,a]),a}}function l(t,e){g[t]=m(t).concat(e)}function h(t,e){var n=g[t];if(n)for(var r=0;r<n.length;r++)n[r]===e&&n.splice(r,1)}function m(t){return g[t]||[]}function v(t){return d[t]=d[t]||o(n)}function w(t,e){f(t,function(t,n){e=e||"feature",y[n]=e,e in u||(u[e]=[])})}var g={},y={},x={on:l,addEventListener:l,removeEventListener:h,emit:n,get:v,listeners:m,context:e,buffer:w,abort:a,aborted:!1};return x}function i(){return new r}function a(){(u.api||u.feature)&&(p.aborted=!0,u=p.backlog={})}var s="nr@context",c=t("gos"),f=t(25),u={},d={},p=e.exports=o();p.backlog=u},{}],gos:[function(t,e,n){function r(t,e,n){if(o.call(t,e))return t[e];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(t,e,{value:r,writable:!0,enumerable:!1}),r}catch(i){}return t[e]=r,r}var o=Object.prototype.hasOwnProperty;e.exports=r},{}],handle:[function(t,e,n){function r(t,e,n,r){o.buffer([t],r),o.emit(t,e,n)}var o=t("ee").get("handle");e.exports=r,r.ee=o},{}],id:[function(t,e,n){function r(t){var e=typeof t;return!t||"object"!==e&&"function"!==e?-1:t===window?0:a(t,i,function(){return o++})}var o=1,i="nr@id",a=t("gos");e.exports=r},{}],loader:[function(t,e,n){function r(){if(!E++){var t=b.info=NREUM.info,e=l.getElementsByTagName("script")[0];if(setTimeout(u.abort,3e4),!(t&&t.licenseKey&&t.applicationID&&e))return u.abort();f(y,function(e,n){t[e]||(t[e]=n)}),c("mark",["onload",a()+b.offset],null,"api");var n=l.createElement("script");n.src="https://"+t.agent,e.parentNode.insertBefore(n,e)}}function o(){"complete"===l.readyState&&i()}function i(){c("mark",["domContent",a()+b.offset],null,"api")}function a(){return O.exists&&performance.now?Math.round(performance.now()):(s=Math.max((new Date).getTime(),s))-b.offset}var s=(new Date).getTime(),c=t("handle"),f=t(25),u=t("ee"),d=t(24),p=window,l=p.document,h="addEventListener",m="attachEvent",v=p.XMLHttpRequest,w=v&&v.prototype;NREUM.o={ST:setTimeout,SI:p.setImmediate,CT:clearTimeout,XHR:v,REQ:p.Request,EV:p.Event,PR:p.Promise,MO:p.MutationObserver};var g=""+location,y={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-spa-1169.min.js"},x=v&&w&&w[h]&&!/CriOS/.test(navigator.userAgent),b=e.exports={offset:s,now:a,origin:g,features:{},xhrWrappable:x,userAgent:d};t(19),t(22),l[h]?(l[h]("DOMContentLoaded",i,!1),p[h]("load",r,!1)):(l[m]("onreadystatechange",o),p[m]("onload",r)),c("mark",["firstbyte",s],null,"api");var E=0,O=t(27)},{}],"wrap-function":[function(t,e,n){function r(t){return!(t&&t instanceof Function&&t.apply&&!t[a])}var o=t("ee"),i=t(26),a="nr@original",s=Object.prototype.hasOwnProperty,c=!1;e.exports=function(t,e){function n(t,e,n,o){function nrWrapper(){var r,a,s,c;try{a=this,r=i(arguments),s="function"==typeof n?n(r,a):n||{}}catch(f){p([f,"",[r,a,o],s])}u(e+"start",[r,a,o],s);try{return c=t.apply(a,r)}catch(d){throw u(e+"err",[r,a,d],s),d}finally{u(e+"end",[r,a,c],s)}}return r(t)?t:(e||(e=""),nrWrapper[a]=t,d(t,nrWrapper),nrWrapper)}function f(t,e,o,i){o||(o="");var a,s,c,f="-"===o.charAt(0);for(c=0;c<e.length;c++)s=e[c],a=t[s],r(a)||(t[s]=n(a,f?s+o:o,i,s))}function u(n,r,o){if(!c||e){var i=c;c=!0;try{t.emit(n,r,o,e)}catch(a){p([a,n,r,o])}c=i}}function d(t,e){if(Object.defineProperty&&Object.keys)try{var n=Object.keys(t);return n.forEach(function(n){Object.defineProperty(e,n,{get:function(){return t[n]},set:function(e){return t[n]=e,e}})}),e}catch(r){p([r])}for(var o in t)s.call(t,o)&&(e[o]=t[o]);return e}function p(e){try{t.emit("internal-error",e)}catch(n){}}return t||(t=o),n.inPlace=f,n.flag=a,n}},{}]},{},["loader",2,16,5,3,4]);</script>
<meta name="viewport" content="width=1200, minimal-ui, initial-scale=1.1383333333333334, minimum-scale=1.1383333333333334, target-densityDpi=device-dpi, viewport-fit=cover">
<!--[if IE 9]>
<meta content='IE=Edge' http-equiv='X-UA-Compatible'>
<![endif]-->
<link rel="stylesheet" media="all" href="/assets/css/code-studio-bf8125f7cf322c38c2c18f302d5fcf68c4ba7c2c8a6735fabac3824a38587997.css">
<link rel="stylesheet" media="all" href="/assets/application-24ace111e7737087b3eb2bcda7e815d0a156b54e8712f61646ada1840cecd6d9.css">
<script>
  // Google Analytics snippet (https://developers.google.com/analytics/devguides/collection/analyticsjs/)
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
  
  ga('create', 'UA-37745279-1', 'auto', {"cookieDomain":"auto"});
  
  var dimensions = {"dimension5":"production"};
  if ('devicePixelRatio' in window) {
    dimensions["dimension6"] = window.devicePixelRatio.toString();
  }
  
  ga('set', dimensions);
  ga('set', 'anonymizeIp', true);
  
  ga('send', 'pageview');
  
  function trackEvent(category, action, label, value) {
    ga('send', 'event', category, action, label, value);
  }
  
  (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
  new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
  j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
  'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
  })(window,document,'script','dataLayer','GTM-TZZBRK5');
</script>

<!-- / webpack-runtime.js must appear exactly once on any page containing webpack entries -->
<script src="/assets/js/webpack-runtimewp7bed445c31b4bdaed120.min.js"></script>
<!-- / essential.js is ordered above application.js to filter new relic errors -->
<script src="/assets/js/essentialwp96d6ce3e557721b0980f.min.js"></script>
<script src="/assets/js/vendorswp850179a572c0984ae8af.min.js"></script>

<script src="/assets/application-912e89b6e376b99f2ff5449303396cbe88c17d7c392c075c77d2368388b309bb.js"></script>
<script src="/assets/js/en_us/common_localewpb6e42012a16509c1bebabcb0648e9c1c.js"></script>
<script src="https://cdn.optimizely.com/js/12977480133.js"></script>
<script src="/assets/js/code-studio-commonwp718511b0695220278c29.min.js"></script>
<meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="Xb9rA0d+bKgDfEua/XwaKxpV/LJuFnUwEmPiLFhn5cSbgVZX6P0/OFuhqPNqVTRnSS56M3XVggrfUfry83yJ4w==">

<meta name="viewport" content="initial-scale=1">
<meta property="fb:app_id" content="500177453358606">
<meta property="og:site_name" content="Code.org">
<meta property="og:type" content="article">
<meta property="article:publisher" content="https://www.facebook.com/Code.org">
<meta name="twitter:site" content="@codeorg">
<meta name="twitter:card" content="photo">
<meta property="og:title" content="Check out what I made">
<meta property="og:description" content="I wrote the code myself with Code.org">
<meta property="og:url" content="https://studio.code.org/c/1160767285">
<meta property="og:image" content="https://studio.code.org/assets/flappy_sharing_drawing-4a1fdd6261fc60084efc6e8eb02debdc21e584abbaddc190f05d5b019ec07afa.png">
<meta property="og:image:secure_url" content="https://studio.code.org/assets/flappy_sharing_drawing-4a1fdd6261fc60084efc6e8eb02debdc21e584abbaddc190f05d5b019ec07afa.png">
<meta property="og:image:width" content="400">
<meta property="og:image:height" content="400">
<meta name="twitter:title" content="Check out what I made">
<meta name="twitter:description" content="I wrote the code myself with Code.org">
<meta name="twitter:url" content="https://studio.code.org/c/1160767285">
<meta name="twitter:image" content="https://studio.code.org/assets/flappy_sharing_drawing-4a1fdd6261fc60084efc6e8eb02debdc21e584abbaddc190f05d5b019ec07afa.png">
<meta name="twitter:image:secure_url" content="https://studio.code.org/assets/flappy_sharing_drawing-4a1fdd6261fc60084efc6e8eb02debdc21e584abbaddc190f05d5b019ec07afa.png">
<meta name="twitter:image:width" content="400">
<meta name="twitter:image:height" content="400">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<link rel="apple-touch-icon" href="https://studio.code.org/assets/flappy_icon-6fd1aad2c13653a1aca2577ea77c2930131a4724d315b40b4821223566827d11.png">

<style>[touch-action="none"]{ -ms-touch-action: none; touch-action: none; }
body /shadow-deep/ [touch-action="none"]{ -ms-touch-action: none; touch-action: none; }
[touch-action="auto"]{ -ms-touch-action: auto; touch-action: auto; }
body /shadow-deep/ [touch-action="auto"]{ -ms-touch-action: auto; touch-action: auto; }
[touch-action="pan-x"]{ -ms-touch-action: pan-x; touch-action: pan-x; }
body /shadow-deep/ [touch-action="pan-x"]{ -ms-touch-action: pan-x; touch-action: pan-x; }
[touch-action="pan-y"]{ -ms-touch-action: pan-y; touch-action: pan-y; }
body /shadow-deep/ [touch-action="pan-y"]{ -ms-touch-action: pan-y; touch-action: pan-y; }
[touch-action="pan-x pan-y"],[touch-action="pan-y pan-x"]{ -ms-touch-action: pan-x pan-y; touch-action: pan-x pan-y; }
body /shadow-deep/ [touch-action="pan-x pan-y"],body /shadow-deep/ [touch-action="pan-y pan-x"]{ -ms-touch-action: pan-x pan-y; touch-action: pan-x pan-y; }
</style><style type="text/css">/*
Basis for this CSS from:
https://weblog.west-wind.com/posts/2015/Feb/26/Using-FontAwesome-Fonts-for-HTML-Radio-Buttons-and-Checkboxes
*/

input[type=radio].with-font {
    border: 0;
    clip: rect(0 0 0 0);
    width: 1px;
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
}
input[type=radio].with-font ~ label:before {
    font-family: FontAwesome;
    display: inline-block;
    content: "\F1DB";  /* fa-circle-thin */
    font-size: 18px;
    color: color.black;
    width: 15px;
    height: 15px;
    text-align: center;
    vertical-align: bottom;
}
input[type=radio].with-font:checked ~ label:before  {
    font-family: FontAwesome;
    display:inline-block;
    content: "\F058";  /* fa-check-circle */
    font-size: 18px;
    color: #0094ca;
    width: 15px;
    height: 15px;
    line-height: 16px;
    background-color: white;
    text-align: center;
    border-radius: 60%;
}

label.hidden-label-checked-radio-button {
    margin: 0px;
    width: 16px;
    height: 16px;
    line-height: 16px;
}</style><style type="text/css">.blocklyFieldAngleTextInput {
  border: 1px solid #ccc;
  margin-top: -10px;
}
.blocklyFieldAngleDropdown {
  box-shadow: 4px 4px 6px #bbb;
  border-style: solid;
  border-width: 1px;
}
.blocklyFieldAngleDropdown > div {
  float: left;
}
.blocklyFieldAngleDropdown .goog-menu {
  box-shadow: none;
  border-style: none;
}
.blocklyFieldAngleDropdown .goog-menu::after {
  content: '';
  border-left: 1px solid #949ca2;
  position: absolute;
  height: 80%;
  right: 0;
  top: 10%;
}
.blocklyLimit rect {
 fill: #a69bc1;
}
.blocklyLimit.overLimit rect {
 fill: #daa53a;
}
.blocklyLimit .blocklyText {
 font-size: 10pt;
 fill: #fff;
}
.blocklyUnused .blocklyLimit rect {
 fill: #c6cacd;
}
.blocklyUnused .blocklyLimit .blocklyText {
 fill: #5b6770
}
.blocklyUnused .blocklyPath, .blocklyUnused .blocklyPathDark, .blocklyUnused .blocklyPathLight, .blocklyUnused .blocklyEditableText {
 opacity: 0.25;
}
.blocklyUnused .blocklyUnusedFrame {
 transition: opacity 2s;
 opacity: 0.8;
}
.blocklyUnused .blocklyUnusedFrame .blocklyText {
 fill: #000;
}
.blocklyUnused .blocklyUnusedFrame.hidden {
 opacity: 0;
 visibility: hidden
}
.blocklyUnused .blocklyHelp {
 cursor: pointer;
}
.blocklyUnused .blocklyHelp .blocklyText {
 fill: #fff;
 font-size: 10pt;
 text-anchor: middle;
 dominant-baseline: central;
}
.blocklyDraggable {
  cursor: url(/blockly/media/handopen.cur) 8 5, auto;
}
.dragging, .dragging .blocklySvg, .dragging .blocklyDraggable {
  cursor: url(/blockly/media/handclosed.cur) 7 3, auto !important;
}
#codeWorkspace {
  border: 1px solid #ddd;
}
#codeWorkspace .userHidden {
  display: none;
}
#codeWorkspace .hiddenFlyout, #blocklyDragCanvas .hiddenFlyout, .readOnlyBlockSpace .hiddenFlyout {
  display: none !important;
}
#codeWorkspace.edit .userHidden {
  display: inline;
  fill-opacity: 0.5;
}
#codeWorkspace.edit .userHidden .blocklyPath {
  fill-opacity: 0.5;
}
#codeWorkspace.edit .userHidden .blocklyPathDark, #codeWorkspace.edit .userHidden .blocklyPathLight {
  display: none;
}
.blocklySvg {
  cursor: pointer;
  background-color: #fff;
  overflow: hidden;
}
.blocklySvg.inline {
  vertical-align: top;
}
g.blocklyDraggable {
  -ms-touch-action: none;
  touch-action: none;
}
.blocklyWidgetDiv {
  position: absolute;
  display: none;
  z-index: 999;
}
.blocklyResizeSE {
  fill: #aaa;
  cursor: se-resize;
}
.blocklyResizeSW {
  fill: #aaa;
  cursor: sw-resize;
}
.blocklyResizeLine {
  stroke-width: 1;
  stroke: #888;
}
.blocklyHighlightedConnectionPath {
  stroke-width: 4px;
  stroke: #fc3;
  fill: none;
}
.blocklyPathLight {
  fill: none;
  stroke-width: 2;
  stroke-linecap: round;
}
.blocklyTypeHint {
  fill: none;
  stroke-width: 5;
}
.blocklySelected>.blocklyTypeHint, .blocklyUnused .blocklyTypeHint {
  display: none;
}
.blocklySpotlight>.blocklyPath {
  fill: #fc3;
}
.blocklySelected>.blocklyPath {
  stroke-width: 3px;
  stroke: #fc3;
  fill: #fc3;
  fill-opacity: 0.8;
}
.blocklySelected>.blocklyPathLight {
  display: none;
}
.blocklyUndeletable>.blocklyEditableText>rect {
  fill-opacity: 1.0;
  fill: #ffdb74;
}
#blocklyDragCanvas {
  display: none;
  pointer-events: none;
  position: absolute;
  top: -1px;
  left: -1px;
  border: 1px solid #fff;
  z-index: 10;
}
#blocklyDragCanvas.isDragging {
  display: block;
}
.blocklyDragging>.blocklyPath,
.blocklyDragging>.blocklyPathLight {
  fill-opacity: 0.8;
  stroke-opacity: 0.8;
}
.blocklyDragging>.blocklyPathDark {
  display: none;
}
.blocklyDisabled>.blocklyPath {
  fill-opacity: 0.50;
  stroke-opacity: 0.50;
}
.blocklyDisabled>.blocklyPathLight,
.blocklyDisabled>.blocklyPathDark {
  display: none;
}
.blocklyText {
  cursor: default;
  font-family: sans-serif;
  font-size: 11pt;
  fill: #fff;
}
.innerModalDiv {
  pointer-events: none !important;
}
.innerModalDiv .goog-flat-menu-button,
.innerModalDiv textarea,
.innerModalDiv input,
.innerModalDiv button {
  pointer-events: auto;
}
.flyoutColorGray {
  background-color: #DDD;
}
.contractEditor #paramAddButton {
  margin-top: 3px;
  margin-left: 10px;
  margin-bottom: 4px;
}
.contractEditorHeaderText {
  cursor: default;
  font-size: 12pt;
  fill: #fff;
}
.contract-type-hint {
  color: #898989;
  font-size: 11px;
}
.exampleAreaDiv {
  pointer-events: none;
}
.callResultText {
  color: #000;
  position: absolute;
}
.exampleAreaButton {
  pointer-events: initial;
  position: absolute;
}
.core-clearfix {
  overflow: auto;
}
.testButton {
  padding: 3px 0 !important;
  min-width: 95px !important;
}
.resetButton {
  border: 1px solid #0094ca !important;
  background-color: #0094ca !important;
}
.example-result-text {
  position: absolute;
  font-size: 16px;
}
.color-square-icon {
  float: left;
  width: 21px;
  height: 18px;
  margin-right: 9px !important;
  margin-left: 6px !important;
}
.goog-menuitem .color-square-icon {
  margin-left: -3px !important;
  margin-top: 2px !important;
}
.blocklyNonEditableText>text {
  pointer-events: none;
}
.blocklyNonEditableText>rect,
.blocklyEditableText>rect {
  fill: #fff;
  fill-opacity: 0.6;
}
.blocklyNonEditableText>text,
.blocklyEditableText>text {
  fill: #000;
}
.blocklyEditableText:hover>rect {
  stroke-width: 2;
  stroke: #fff;
}
/*
 * Don't allow users to select text.  It gets annoying when trying to
 * drag a block and selected text moves instead.
 */
.blocklySvg text {
  -moz-user-select: none;
  -webkit-user-select: none;
  user-select: none;
  cursor: inherit;
}
.blocklyHidden {
  display: none;
}
.blocklyFieldDropdown:not(.blocklyHidden) {
  display: block;
}
.blocklyTooltipBackground {
  fill: #ffffc7;
  stroke-width: 1px;
  stroke: #d8d8d8;
}
.blocklyTooltipShadow,
.blocklyContextMenuShadow,
.blocklyDropdownMenuShadow {
  fill: #bbb;
  filter: url(#blocklyShadowFilter);
}
.blocklyTooltipText {
  font-family: sans-serif;
  font-size: 9pt;
  fill: #000;
}
#modalEditorClose:hover>rect {
  fill: #0094ca;
}
.svgTextButton:hover>rect {
  fill: #0094ca;
}
.red-delete-button {
  background-color: #cc0000 !important;
  border: 1px solid #cc0000 !important;
}
.blocklyIconShield {
  cursor: default;
  fill: #00c;
  stroke-width: 1px;
  stroke: #ccc;
}
.blocklyIconGroup:hover>.blocklyIconShield {
  fill: #00f;
  stroke: #fff;
}
.blocklyIconGroup:hover>.blocklyIconMark {
  fill: #fff;
}
.blocklyIconMark {
  cursor: default !important;
  font-family: sans-serif;
  font-size: 9pt;
  font-weight: bold;
  fill: #ccc;
  text-anchor: middle;
}
.blocklyWarningBody {
}
.blocklyMinimalBody {
  margin: 0;
  padding: 0;
}
.blocklyHtmlInput {
  font-family: sans-serif;
  font-size: 11pt;
  border: none;
  outline: none;
  width: 100%;
  -moz-appearance: textfield;
}
.blocklyHtmlInput::-webkit-inner-spin-button, .blocklyHtmlInput::-webkit-outer-spin-button {
  -webkit-appearance: none;
}
.blocklyContextMenuBackground,
.blocklyMutatorBackground {
  fill: #fff;
  stroke-width: 1;
  stroke: #ddd;
}
.newFunctionDiv {
  position: absolute;
  top: 120px;
  left: 600px;
}
#modalContainer .goog-flat-menu-button-caption {
  color: #555555;
  margin-left: 1px;
  margin-right: 0;
  min-width: 55px;
}
.blocklyContextMenuOptions>.blocklyMenuDiv,
.blocklyContextMenuOptions>.blocklyMenuDivDisabled,
.blocklyDropdownMenuOptions>.blocklyMenuDiv {
  fill: #fff;
}
.blocklyContextMenuOptions>.blocklyMenuDiv:hover>rect,
.blocklyDropdownMenuOptions>.blocklyMenuDiv:hover>rect {
  fill: #57e;
}
.blocklyMenuSelected>rect {
  fill: #57e;
}
.blocklyMenuText {
  cursor: default !important;
  font-family: sans-serif;
  font-size: 15px; /* All context menu sizes are based on pixels. */
  fill: #000;
}
.blocklyContextMenuOptions>.blocklyMenuDiv:hover>.blocklyMenuText,
.blocklyDropdownMenuOptions>.blocklyMenuDiv:hover>.blocklyMenuText {
  fill: #fff;
}
.blocklyMenuSelected>.blocklyMenuText {
  fill: #fff;
}
.blocklyMenuDivDisabled>.blocklyMenuText {
  fill: #ccc;
}
.blocklyFlyoutBackground {
  fill: #ddd;
  fill-opacity: 0.8;
}
.blocklyToolboxBackground {
  fill: #ddd;
}
.blocklyBackground {
  fill: #666;
}
.blocklyScrollbarBackground {
  fill: #fff;
  stroke-width: 1;
  stroke: #e4e4e4;
}
.blocklyScrollbarKnob {
  fill: #ccc;
}
.blocklyScrollbarBackground:hover+.blocklyScrollbarKnob,
.blocklyScrollbarKnob:hover {
  fill: #bbb;
}
.blocklyInvalidInput {
  background: #faa;
}
.blocklyAngleCircle {
  stroke: #444;
  stroke-width: 1;
  fill: #ddd;
  fill-opacity: 0.8;
}
.blocklyAngleMarks {
  stroke: #444;
  stroke-width: 1;
}
.blocklyAngleGuage {
  fill: #d00;
  fill-opacity: 0.8;  
}
.blocklyContextMenu {
  border-radius: 4px;
}
.blocklyDropdownMenu {
  padding: 0 !important;
  position: relative !important;
}
.blocklyRectangularDropdownMenu .goog-menuitem {
  height: 100%;
  padding: 0 !important;
  border-radius: 5px;
  margin-bottom: 4px !important;
}
.fieldRectangularDropdownBackdrop {
  fill: #fff;
  fill-opacity: 0.6;
}
.blocklyRectangularDropdownArrow {
  fill: #7965a1;
  font-size: 20px !important;
}
.blocklyRectangularDropdownMenu .goog-menuitem-highlight, .goog-menuitem-hover {
  border-color: #7965a1 !important;
  border-style: dotted !important;
  border-width: 0px !important;
  margin: -4px -4px 0 !important;
  border-width: 4px !important;
  border-style: solid !important;
  padding-bottom: 0px !important;
  padding-top: 0px !important;
}
.colored-type-dropdown .goog-menuitem-content {
  color: #555555;
  float: left;
}
.colored-type-dropdown > .goog-menuitem {
  padding: 0px 40px 2px 13px;
}
.goog-menu {
  box-shadow: 4px 4px 6px #bbb;
  border-width: 2px;
}
.goog-menuitem {
  height: 20px;
  padding-top: 0;
  padding-bottom: 0;
}
.goog-menuitem-highlight,
.goog-menuitem-hover {
  border-width: 0;
  background-color: #57e;
}
.goog-menuitem-highlight .goog-menuitem-content {
  color: #fff;
}
.goog-option-selected .goog-menuitem-checkbox:before {
  content: "✓";
}
.goog-menuitem-checkbox {
  background: ""
}
.blocklyRectangularDropdownMenu img {
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  border-radius: 5px;
}
.blocklyRectangularDropdownMenu {
  border-radius: 5px;
  box-shadow: none !important;
}
.goog-option-selected .goog-menuitem-checkbox,
.goog-option-selected .goog-menuitem-icon {
}
/* Category tree in Toolbox. */
.blocklyToolboxDiv {
  display: none;
  overflow-x: visible;
  overflow-y: auto;
  position: absolute;
}
.blocklyTreeRoot {
  padding: 4px 0;
}
.blocklyTreeRoot:focus {
  outline: none;
}
.blocklyTreeRow {
  line-height: 22px;
  height: 22px;
  padding-right: 1em;
  white-space: nowrap;
}
.blocklyToolboxDiv[dir="RTL"] .blocklyTreeRow {
  padding-right: 0;
  padding-left: 1em !important;
}
.blocklyTreeRow:hover {
  background-color: #e4e4e4;
}
.blocklyTreeIcon {
  height: 16px;
  width: 16px;
  vertical-align: middle;
  background-image: url(/blockly/media/tree.png);
}
.blocklyTreeIconClosedLtr {
  background-position: -32px -1px;
}
.blocklyTreeIconClosedRtl {
  background-position: 0px -1px;
}
.blocklyTreeIconOpen {
  background-position: -16px -1px;
}
.blocklyTreeIconNone {
  background-position: -48px -1px;
}
.blocklyTreeSelected>.blocklyTreeIconClosedLtr {
  background-position: -32px -17px;
}
.blocklyTreeSelected>.blocklyTreeIconClosedRtl {
  background-position: 0px -17px;
}
.blocklyTreeSelected>.blocklyTreeIconOpen {
  background-position: -16px -17px;
}
.blocklyTreeSelected>.blocklyTreeIconNone {
  background-position: -48px -17px;
}
.blocklyTreeLabel {
  cursor: default;
  font-family: sans-serif;
  font-size: 16px;
  padding: 0 3px;
  vertical-align: middle;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.blocklyTreeSelected {
  background-color: #57e !important;
}
.blocklyTreeSelected .blocklyTreeLabel {
  color: #fff;
}
.blocklyArrow {
  font-size: 80%;
}
.paramToolbox {
  padding: 0 0 5px 0;
  pointer-events: auto;
}
.paramToolbox input, .paramToolbox textarea {
  box-sizing: border-box;
  width: 100%;
  margin: 0;
  resize: none;
}
.paramToolbox input, .paramToolbox button {
  height: 30px;
  margin: 0;
}
.paramToolbox div {
  margin: 4px 10px;
}
#modalContainer {
  position: absolute;
  width: 100%;
  bottom: 0;
}
#modalContainer > svg {
  position: absolute;
  top: 0;
  left: 0;
  background: transparent;
  pointer-events: none;
}
#modalContainer > svg * {
  pointer-events: visiblePainted;
}
/*
 * Copyright 2007 The Closure Library Authors. All Rights Reserved.
 *
 * Use of this source code is governed by the Apache License, Version 2.0.
 * See the COPYING file for details.
 */
/* Author: pupius@google.com (Daniel Pupius) */
/*
 Styles to make the colorpicker look like the old gmail color picker
 NOTE: without CSS scoping this will override styles defined in palette.css
*/
.goog-palette {
  outline: none;
  cursor: default;
}
.goog-palette-table {
  border: 1px solid #666;
  border-collapse: collapse;
}
.goog-palette-cell {
  height: 25px;
  width: 25px;
  margin: 0;
  border: 0;
  text-align: center;
  vertical-align: middle;
  border-right: 1px solid #666;
  font-size: 1px;
}
.goog-palette-colorswatch {
  position: relative;
  height: 25px;
  width: 25px;
  border: 1px solid #666;
}
.goog-palette-cell-hover .goog-palette-colorswatch {
  border: 1px solid #FFF;
}
.goog-palette-cell-selected .goog-palette-colorswatch {
  border: 1px solid #000;
  color: #fff;
}
.goog-menu {
  background: #fff;
  border-color: #ccc #666 #666 #ccc;
  border-style: solid;
  border-width: 1px;
  cursor: default;
  font: normal 13px Arial, sans-serif;
  margin: 0;
  outline: none;
  padding: 4px 0;
  position: absolute;
  z-index: 20000;
}
.goog-menuitem {
  color: #000;
  font: normal 13px Arial, sans-serif;
  list-style: none;
  margin: 0;
  padding: 4px 7em 4px 28px;
  white-space: nowrap;
}
.goog-menuitem.goog-menuitem-rtl {
  padding-left: 7em;
  padding-right: 28px;
}
.goog-menu-nocheckbox .goog-menuitem,
.goog-menu-noicon .goog-menuitem {
  padding-left: 12px;
}
.goog-menu-noaccel .goog-menuitem:not(.goog-menuitem-rtl) {
  padding-right: 20px;
}
.goog-menu-noaccel .goog-menuitem.goog-menuitem-rtl {
  padding-left: 20px;
}
.goog-menuitem-content {
  color: #000;
  font-size: 15px;
}
.goog-menuitem-disabled .goog-menuitem-accel,
.goog-menuitem-disabled .goog-menuitem-content {
  color: #ccc !important;
}
.goog-menuitem-disabled .goog-menuitem-icon {
  opacity: 0.3;
  -moz-opacity: 0.3;
  filter: alpha(opacity=30);
}
.goog-menuitem-highlight,
.goog-menuitem-hover {
  background-color: #d6e9f8;
  border-color: #d6e9f8;
  border-style: dotted;
  border-width: 1px 0;
  padding-bottom: 3px;
  padding-top: 3px;
}
.goog-menuitem-checkbox,
.goog-menuitem-icon {
  background-repeat: no-repeat;
  height: 16px;
  left: 6px;
  position: absolute;
  right: auto;
  vertical-align: middle;
  width: 16px;
}
.goog-menuitem-rtl .goog-menuitem-checkbox,
.goog-menuitem-rtl .goog-menuitem-icon {
  left: auto;
  right: 6px;
}
.goog-option-selected .goog-menuitem-checkbox,
.goog-option-selected .goog-menuitem-icon {
}
.goog-menuitem-accel {
  color: #999;
  direction: ltr;
  left: auto;
  padding: 0 6px;
  position: absolute;
  right: 0;
  text-align: right;
}
.goog-menuitem-rtl .goog-menuitem-accel {
  left: 0;
  right: auto;
  text-align: left;
}
.goog-menuitem-mnemonic-hint {
  text-decoration: underline;
}
.goog-menuitem-mnemonic-separator {
  color: #999;
  font-size: 12px;
  padding-left: 4px;
}
.goog-menuseparator {
  border-top: 1px solid #ccc;
  margin: 4px 0;
  padding: 0;
}
.goog-flat-menu-button {
  background-color: #fff;
  border: 1px solid #c9c9c9;
  color: #333;
  cursor: pointer;
  font: normal 95%;
  list-style: none;
  margin: 0 2px;
  outline: none;
  padding: 1px 4px;
  position: relative;
  text-decoration: none;
  vertical-align: middle;
}
.goog-flat-menu-button-disabled * {
  border-color: #ccc;
  color: #999;
  cursor: default;
}
.goog-flat-menu-button-hover {
  border-color: #9cf #69e #69e #7af !important; /* Hover border wins. */
}
.goog-flat-menu-button-active {
  background-color: #bbb;
  background-position: bottom left;
}
.goog-flat-menu-button-focused {
  border-color: #bbb;
}
.goog-flat-menu-button-caption {
  padding-right: 10px;
  vertical-align: top;
}
.goog-flat-menu-button-dropdown {
  /* Client apps may override the URL at which they serve the sprite. */
  background: url(https://ssl.gstatic.com/editor/editortoolbar.png) no-repeat -388px 0;
  position: absolute;
  right: 2px;
  top: 0;
  vertical-align: top;
  width: 7px;
}
.goog-inline-block {
  position: relative;
  display: -moz-inline-box; /* Ignored by FF3 and later. */
  display: inline-block;
}
</style></head>
<body class="legacy-share-view WireframeButtons_container" style="background-color: rgb(32, 43, 52);"><div class="WireframeButtons_containerLeft"></div>
<div id="gdpr-dialog"></div>
<script data-gdpr="{}" data-usertype="null" src="/assets/js/code-studiowp41f17813be835d58ad77.min.js"></script>
<div class="wrapper withWireframeButtons">


<div class="full_container">

<span id="fa-preload" style="font: 1px FontAwesome; position: absolute;">&nbsp;</span>
<div id="codeApp" class="hide-source"><div data-reactroot=""><!-- react-empty: 2 --><!-- react-empty: 3 --><!-- react-empty: 4 --><div id="visualizationColumn" class="wireframeShare" style="width: 400px;"><div id="phoneFrameScreen"><div id="visualizationContainer"><span><div id="visualization" class=""><svg version="1.1" id="svgFlappy" width="400" height="400"><image xlink:href="/blockly/media/skins/flappy/background.png" id="background" height="400" width="400" x="0" y="0"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_top.png" id="obstacle_top0" height="320" width="52" x="600" y="-223"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_bottom.png" id="obstacle_bottom0" height="320" width="52" x="600" y="197"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_top.png" id="obstacle_top1" height="320" width="52" x="850" y="-117"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_bottom.png" id="obstacle_bottom1" height="320" width="52" x="850" y="303"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_top.png" id="obstacle_top2" height="320" width="52" x="1100" y="-261"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_bottom.png" id="obstacle_bottom2" height="320" width="52" x="1100" y="159"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_top.png" id="obstacle_top3" height="320" width="52" x="1350" y="-152"></image><image xlink:href="/blockly/media/skins/flappy/obstacle_bottom.png" id="obstacle_bottom3" height="320" width="52" x="1350" y="268"></image><image xlink:href="/blockly/media/skins/flappy/ground.png" id="ground0" height="48" width="400" x="0" y="352"></image><image xlink:href="/blockly/media/skins/flappy/ground.png" id="ground1" height="48" width="400" x="400" y="352"></image><clipPath id="avatArclipPath"><rect id="avatArclipRect" width="400" height="352"></rect></clipPath><image id="avatar" xlink:href="/blockly/media/skins/flappy/avatar.png" height="24" width="34" clip-path="url(#avatArclipPath)" transform="" x="110" y="150"></image><image xlink:href="/blockly/media/skins/flappy/instructions.png" id="instructions" height="50" width="159" x="110" y="170" visibility="hidden"></image><image xlink:href="/blockly/media/skins/flappy/getready.png" id="getready" height="50" width="183" x="108" y="80" visibility="hidden"></image><image xlink:href="/blockly/media/skins/flappy/clickrun.png" id="clickrun" height="41" width="273" x="64" y="200" visibility="visible"></image><image xlink:href="/blockly/media/skins/flappy/gameover.png" id="gameover" height="41" width="192" x="104" y="80" visibility="hidden"></image><text id="score" class="flappy-score" x="200" y="60" visibility="hidden">0</text><rect width="400" height="400" fill-opacity="0"></rect></svg></div><div><div id="gameButtons" data-radium="true" style="margin-bottom: -18px;"><span id="runButtonWrapper" data-radium="true"><button type="button" id="runButton" class="launch blocklyLaunch" data-radium="true" style="display: inline-block;"><div>Run</div><img src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAkAAAEALAAAAAABAAEAAAICTAEAOw==" class="run26"></button></span><button type="button" id="resetButton" class="launch blocklyLaunch" data-radium="true" style="display: none; min-width: 96px;" disabled=""><div>Reset</div><img src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAkAAAEALAAAAAABAAEAAAICTAEAOw==" class="reset26"></button><!-- react-text: 18 --> <!-- /react-text --><div id="right-button-cell" data-radium="true" class="right-button-cell-enabled"><button type="button" id="rightButton" class="share" data-radium="true"><img src="/blockly/media/1x1.gif"><!-- react-text: 22 -->Finish<!-- /react-text --></button></div></div><div id="gameButtonExtras"></div></div><div id="belowVisualization"><div>

<div id="make-your-own">

  <h1><a href="http://code.org/flappy">Make Your Own Flappy Game</a></h1>
  <a href="http://code.org/flappy"><img src="/blockly/media/flappy_promo.png"></a>

</div>
</div></div></span></div><div id="footerDiv"><div data-reactroot="" class="dark"><div class="small-footer-base" style="padding-left: 0px; width: 400px;"><button type="button" class="more-link"><!-- react-text: 4 -->Built on Code Studio<!-- /react-text --><!-- react-text: 5 -->&nbsp;<!-- /react-text --><i class="fa fa-caret-up"></i></button></div><div id="copyright-flyout" style="display: none; position: absolute; bottom: 0px; width: 650px; max-width: 50%; min-width: 400px;"><div id="copyright-scroll-area" style="max-height: 210px; margin-bottom: 28px;"><h4></h4><div><p><!-- react-text: 12 -->We thank our <!-- /react-text --><a href="https://code.org/about/donors"><!-- react-text: 14 -->donors<!-- /react-text --></a><!-- react-text: 15 -->, <!-- /react-text --><a href="https://code.org/about/partners"><!-- react-text: 17 -->partners<!-- /react-text --></a><!-- react-text: 18 -->, our <!-- /react-text --><a href="https://code.org/about/team"><!-- react-text: 20 -->extended team<!-- /react-text --></a><!-- react-text: 21 -->, our video cast, and our <!-- /react-text --><a href="https://code.org/about/advisors"><!-- react-text: 23 -->education advisors<!-- /react-text --></a><!-- react-text: 24 --> for their support in creating Code Studio.<!-- /react-text --></p></div><p>We especially want to recognize the engineers from Amazon, Google, and Microsoft who helped create these materials.</p><div><p><!-- react-text: 28 -->Minecraft™ © 2020 Microsoft. All Rights Reserved.<!-- /react-text --><br><!-- react-text: 30 -->Star Wars™ © 2020 Disney and Lucasfilm. All Rights Reserved.<!-- /react-text --><br><!-- react-text: 32 -->Frozen™ © 2020 Disney. All Rights Reserved.<!-- /react-text --><br><!-- react-text: 34 -->Ice Age™ © 2020 20th Century Fox. All Rights Reserved.<!-- /react-text --><br><!-- react-text: 36 -->Angry Birds™ © 2009-2020 Rovio Entertainment Ltd. All Rights Reserved.<!-- /react-text --><br><!-- react-text: 38 -->Plants vs. Zombies™ © 2020 Electronic Arts Inc. All Rights Reserved.<!-- /react-text --><br><!-- react-text: 40 -->The Amazing World of Gumball is trademark and © 2020 Cartoon Network.<!-- /react-text --></p></div><div><p><!-- react-text: 43 -->Code.org uses p5.play, which is licensed under <!-- /react-text --><a href="http://www.gnu.org/licenses/old-licenses/lgpl-2.1-standalone.html"><!-- react-text: 45 -->the GNU LGPL 2.1<!-- /react-text --></a><!-- react-text: 46 -->.<!-- /react-text --></p></div><p>Powered by Amazon Web Services</p><div><p><!-- react-text: 50 -->© Code.org, 2020. Code.org®, the CODE logo and Hour of Code® are trademarks of Code.org.<!-- /react-text --></p></div></div></div><ul id="more-menu" style="display: none; bottom: 29px; width: 400px;"><li class="ui-test-try-hoc"><a href="https://code.org/learn" target="_blank">Try an Hour of Code!</a></li><li class="ui-test-how-it-works"><a href="https://studio.code.org/c/1160767285/edit" target="_parent">How it Works (View Code)</a></li><li class="ui-test-report-abuse"><a href="/report_abuse" target="_blank">Report Abuse</a></li><li class="ui-test-undefined"><a href="javascript:void(0)" target="_parent">Copyright</a></li><li class="ui-test-undefined"><a href="https://code.org/tos" target="_blank">Terms of Service</a></li><li class="ui-test-undefined"><a href="https://code.org/privacy" target="_blank">Privacy Policy</a></li></ul></div></div></div></div><div id="visualizationResizeBar" class="fa fa-ellipsis-v" style="display: none;"></div><span><div></div><div class="editor-column" style="position: absolute; right: 0px; bottom: 0px; margin-left: 15px; top: 0px; display: none;"><div id="codeWorkspace" dir="LTR" style="position: absolute; left: 0px; right: 0px; bottom: 0px; top: 0px; border-style: solid none none; border-top-width: 1px; border-top-color: rgb(221, 221, 221); display: none;"><span id="codeWorkspaceWrapper" data-radium="true"><div id="headers" dir="ltr" class="" data-radium="true" style="height: 30px; background-color: rgb(118, 101, 160); color: rgb(255, 255, 255); overflow-y: hidden; user-select: none;"><div id="codeModeHeaders" data-radium="true"><div id="toolbox-header" data-radium="true" style="text-align: center; white-space: nowrap; overflow-x: hidden; height: 30px; line-height: 30px;"><i id="hide-toolbox-icon" class="fa fa-chevron-circle-right" data-radium="true" style="display: none; font-size: 18px;"></i><span>Blocks</span></div><div id="show-toolbox-header" data-radium="true" style="text-align: center; white-space: nowrap; overflow-x: hidden; height: 30px; line-height: 30px; display: none;"><span id="show-toolbox-click-target" data-radium="true"><i id="show-toolbox-icon" class="fa fa-chevron-circle-right" data-radium="true" style="font-size: 18px;"></i><span>Show Toolbox</span></span></div><div id="show-code-header" data-radium="true" style="cursor: pointer; float: right; overflow: hidden; background-color: rgb(166, 155, 193); margin: 3px 3px 3px 0px; height: 24px; border-radius: 4px; font-family: &quot;Gotham 5r&quot;, sans-serif; line-height: 18px; display: none;"><span data-radium="true" style="padding: 0px 12px;"><img src="data:image/gif;base64,R0lGODlhEAAQAIAAAP///////yH+GkNyZWF0ZWQgd2l0aCBHSU1QIG9uIGEgTWFjACH5BAEKAAEALAAAAAAQABAAAAIdjI+py40AowRp2molznBzB3LTIWpGGZEoda7gCxYAOw==" data-radium="true" style="display: none; height: 18px; line-height: 24px; vertical-align: text-bottom; padding-right: 8px;"><i class="fa fa-code" data-radium="true" style="line-height: 24px; padding-right: 8px; font-size: 15px; font-weight: bold;"></i><span>Show Code</span></span></div><div id="clear-puzzle-header" data-radium="true" style="cursor: pointer; float: right; overflow: hidden; background-color: rgb(166, 155, 193); margin: 3px 3px 3px 0px; height: 24px; border-radius: 4px; font-family: &quot;Gotham 5r&quot;, sans-serif; line-height: 18px;"><span data-radium="true" style="padding: 0px 12px;"><i class="fa fa-undo" data-radium="true" style="line-height: 24px; padding-right: 8px; font-size: 15px; font-weight: bold;"></i><span>Start Over</span></span></div><div id="versions-header" data-radium="true" style="cursor: pointer; float: right; overflow: hidden; background-color: rgb(166, 155, 193); margin: 3px 3px 3px 0px; height: 24px; border-radius: 4px; font-family: &quot;Gotham 5r&quot;, sans-serif; line-height: 18px;"><span data-radium="true" style="padding: 0px 12px;"><i class="fa fa-clock-o" data-radium="true" style="line-height: 24px; padding-right: 8px; font-size: 15px; font-weight: bold;"></i><span>Version History</span></span></div><div id="workspace-header" data-radium="true" style="text-align: center; white-space: nowrap; overflow-x: hidden; height: 30px; line-height: 30px;"><span id="workspace-header-span">Workspace</span><div id="blockCounter" data-radium="true" style="display: none;"><span>: </span><div id="blockUsed" class="block-counter-default">15</div><span> / </span><span id="idealBlockNumber">Infinity</span><span> blocks</span></div></div></div></div></span><svg id="blocklyFilters" width="0" height="0" style="display: block"><defs id="blocklySvgDefsGlobal"><filter id="blocklyEmboss"><feGaussianBlur in="SourceAlpha" stdDeviation="1" result="blur"></feGaussianBlur><feSpecularLighting in="blur" surfaceScale="1" specularConstant="0.5" specularExponent="10" lighting-color="white" result="specOut"><fePointLight x="-5000" y="-10000" z="20000"></fePointLight></feSpecularLighting><feComposite in="specOut" in2="SourceAlpha" operator="in" result="specOut"></feComposite><feComposite in="SourceGraphic" in2="specOut" operator="arithmetic" k1="0" k2="1" k3="1" k4="0"></feComposite></filter><filter id="blocklyTrashcanShadowFilter" height="150%" y="-20%"><feGaussianBlur in="SourceAlpha" stdDeviation="2" result="blur"></feGaussianBlur><feOffset in="blur" dx="1" dy="1" result="offsetBlur"></feOffset><feMerge><feMergeNode in="offsetBlur"></feMergeNode><feMergeNode in="SourceGraphic"></feMergeNode></feMerge></filter><filter id="blocklyShadowFilter"><feGaussianBlur stdDeviation="2"></feGaussianBlur></filter><pattern id="blocklyDisabledPattern" patternUnits="userSpaceOnUse" width="10" height="10"><rect width="10" height="10" fill="#aaa"></rect><path d="M 0 0 L 10 10 M 10 0 L 0 10" stroke="#cc0"></path></pattern><filter id="blocklyTypeHintFilter"><feConvolveMatrix order="5,5" kernelMatrix="0 0 0 0 0 0 0 0 0.5 1 0.5 1 1 1 1 0 0 0 0 0 0 0 0 0.5 1"></feConvolveMatrix></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:html="http://www.w3.org/1999/xhtml" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" class="blocklySvg" width="0px" height="1px" style="background-color: rgb(255, 255, 255);"><defs id="blocklySvgDefs"></defs><g class="svgFlyoutGroup" transform="translate(0,0)" style="display: block;"><path class="blocklyFlyoutBackground" d="M 0,0 h 27 a 8 8 0 0 1 8 8 v 0 a 8 8 0 0 1 -8 8 h -27 z"></path><g class="svgGroup"><g class="svgClippingGroup"><defs><clipPath id="clipToolbox"><rect x="0" y="0" width="0"></rect></clipPath></defs><g class="svgBlockCanvas" clip-path="url(#clipToolbox)" transform="translate(0,8)"><rect fill-opacity="0" width="0" height="0" x="16" y="8"></rect><g tabindex="0" block-id="1" class="blocklyDraggable" transform="translate(16, 8)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">flap&nbsp;a</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">normal<tspan class="blocklyArrow" style="fill: rgb(0, 176, 189);"> ▼</tspan></text></g><text class="blocklyText" transform="translate(10, 18)">amount</text></g><rect fill-opacity="0" width="0" height="0" x="16" y="32"></rect><g tabindex="0" block-id="2" class="blocklyDraggable" transform="translate(16, 32)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">play</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">wing<tspan class="blocklyArrow" style="fill: rgb(0, 176, 189);"> ▼</tspan></text></g><text class="blocklyText" transform="translate(10, 18)">sound</text></g><rect fill-opacity="0" width="0" height="0" x="16" y="56"></rect><g tabindex="0" block-id="3" class="blocklyDraggable" transform="translate(16, 56)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">score&nbsp;a&nbsp;point</text></g><rect fill-opacity="0" width="0" height="0" x="16" y="80"></rect><g tabindex="0" block-id="4" class="blocklyDraggable" transform="translate(16, 80)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">end&nbsp;game</text></g><rect fill-opacity="0" width="0" height="0" x="16" y="104"></rect><g tabindex="0" block-id="5" class="blocklyDraggable" transform="translate(16, 104)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;speed</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">normal<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g><rect fill-opacity="0" width="0" height="0" x="16" y="128"></rect><g tabindex="0" block-id="6" class="blocklyDraggable" transform="translate(16, 128)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;scene</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">City&nbsp;(day)<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g><rect fill-opacity="0" width="0" height="0" x="16" y="152"></rect><g tabindex="0" block-id="7" class="blocklyDraggable" transform="translate(16, 152)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;player</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">Yellow&nbsp;Bird<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g><rect fill-opacity="0" width="0" height="0" x="16" y="176"></rect><g tabindex="0" block-id="8" class="blocklyDraggable" transform="translate(16, 176)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;obstacle</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">Pipe<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g><rect fill-opacity="0" width="0" height="0" x="16" y="200"></rect><g tabindex="0" block-id="9" class="blocklyDraggable" transform="translate(16, 200)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;ground</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">Ground<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g><rect fill-opacity="0" width="0" height="0" x="16" y="224"></rect><g tabindex="0" block-id="10" class="blocklyDraggable" transform="translate(16, 224)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;a</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">normal<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g><text class="blocklyText" transform="translate(10, 18)">gap</text></g><rect fill-opacity="0" width="0" height="0" x="16" y="248"></rect><g tabindex="0" block-id="11" class="blocklyDraggable" transform="translate(16, 248)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;gravity</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: default;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">normal<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g><rect fill-opacity="0" width="0" height="0" x="16" y="272"></rect><g tabindex="0" block-id="12" class="blocklyDraggable" transform="translate(16, 272)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,8 A 8,8 0 0,1 8,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,7 A 7,7 0 0,1 8,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;score</text><g class="blocklyEditableText" transform="translate(10, 18)" style="cursor: text;"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">0</text></g></g></g></g><g class="svgBubbleCanvas"></g><g transform="translate(20, 8)"><rect class="blocklyScrollbarBackground" width="15" height="0"></rect><rect class="blocklyScrollbarKnob" rx="4" ry="4" width="9" x="3" height="0" y="0"></rect></g><g><rect class="blocklyScrollbarBackground" width="15"></rect><rect class="blocklyScrollbarKnob" rx="4" ry="4" width="9" x="3"></rect></g><g class="svgDebugCanvas"></g></g><g id="trashcan" filter="url(#blocklyTrashcanShadowFilter)" style="display: none; pointer-events: none" transform="translate(-17, 20)"><image width="70" height="70" xlink:href="/blockly/media/canclosed.png"></image><image width="70" height="70" visibility="hidden" xlink:href="/blockly/media/canopen.png"></image><g visibility="hidden"><line x1="15" y1="15" x2="55" y2="55" stroke="#c00" stroke-width="5"></line><circle cx="36" cy="34" r="28" stroke="#c00" stroke-width="5" fill="none"></circle></g></g></g><g class="svgGroup"><g class="svgClippingGroup"><g class="svgBlockCanvas" transform="translate(35,0)"><g tabindex="0" block-id="13" class="blocklyDraggable blocklyDeletable" transform="translate(20, 20)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#986200" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#fda400" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#febf4d" d="m 1,7 A 7,7 0 0,1 8,1 H 40 M 39,1 M 1,25 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">when&nbsp;run</text><g tabindex="0" block-id="14" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 1,25 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;player</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">Shark<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g><g tabindex="0" block-id="15" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 1,25 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;scene</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">Underwater<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g><g tabindex="0" block-id="16" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 1,25 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;obstacle</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">Plant<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g><g tabindex="0" block-id="17" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 1,25 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;gravity</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">normal<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g><g tabindex="0" block-id="18" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#5f4059" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#9e6b94" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#bb97b4" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 H 40 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">set&nbsp;speed</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">normal<tspan class="blocklyArrow" style="fill: rgb(158, 107, 148);"> ▼</tspan></text></g></g></g></g></g></g></g><g tabindex="0" block-id="19" class="blocklyDraggable blocklyDeletable" transform="translate(230, 20)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#007126" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00bd3f" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#4dd179" d="m 1,7 A 7,7 0 0,1 8,1 H 40 M 39,1 M 1,25 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">when&nbsp;hit&nbsp;the&nbsp;ground</text><g tabindex="0" block-id="20" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">end&nbsp;game</text></g></g><g tabindex="0" block-id="21" class="blocklyDraggable blocklyDeletable" transform="translate(230, 140)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#007126" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00bd3f" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#4dd179" d="m 1,7 A 7,7 0 0,1 8,1 H 40 M 39,1 M 1,25 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">when&nbsp;hit&nbsp;an&nbsp;obstacle</text><g tabindex="0" block-id="22" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">end&nbsp;game</text></g></g><g tabindex="0" block-id="23" class="blocklyDraggable blocklyDeletable" transform="translate(20, 140)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#007126" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00bd3f" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#4dd179" d="m 1,7 A 7,7 0 0,1 8,1 H 40 M 39,1 M 1,25 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">when&nbsp;click</text><g tabindex="0" block-id="24" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 1,25 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">flap&nbsp;a</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">small<tspan class="blocklyArrow" style="fill: rgb(0, 176, 189);"> ▼</tspan></text></g><text class="blocklyText" transform="translate(10, 18)">amount</text><g tabindex="0" block-id="25" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">play</text><g class="blocklyEditableText" style="cursor: default;" transform="translate(10, 18)"><rect rx="4" ry="4" x="-5" y="-12" height="16" width="10"></rect><text class="blocklyText">splash<tspan class="blocklyArrow" style="fill: rgb(0, 176, 189);"> ▼</tspan></text></g><text class="blocklyText" transform="translate(10, 18)">sound</text></g></g></g><g tabindex="0" block-id="26" class="blocklyDraggable blocklyDeletable" transform="translate(230, 260)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#007126" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00bd3f" d="m 0,8 A 8,8 0 0,1 8,0  H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 0 z
"></path><path class="blocklyPathLight" stroke="#4dd179" d="m 1,7 A 7,7 0 0,1 8,1 H 40 M 39,1 M 1,25 V 8
"></path><text class="blocklyText" transform="translate(10, 18)">when&nbsp;pass&nbsp;obstacle</text><g tabindex="0" block-id="27" class="blocklyDraggable" transform="translate(0, 26)"><path class="blocklyPathDark" transform="translate(1, 1)" fill-rule="evenodd" fill="#006a71" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPath" fill-rule="evenodd" fill="#00b0bd" d="m 0,0  H 15 l 6,4 3,0 6,-4 H 40 v 25  H 30 l -6,4 -3,0 -6,-4 H 8 a 8,8 0 0,1 -8,-8 z
"></path><path class="blocklyPathLight" stroke="#4dc8d1" d="m 1,1 H 15 l 6.5,4 2,0 6.5,-4 H 40 M 39,1 M 3.050252531694167,21.949747468305834 A 7,7 0 0,1 1,17 V 1
"></path><text class="blocklyText" transform="translate(10, 18)">score&nbsp;a&nbsp;point</text></g></g></g></g><g class="svgBubbleCanvas" transform="translate(35,0)"></g><g transform="translate(-15, 0)"><rect class="blocklyScrollbarBackground" width="15" height="1"></rect><rect class="blocklyScrollbarKnob" rx="4" ry="4" width="9" x="3" height="0.01" y="0"></rect></g><g class="svgDebugCanvas"></g></g><g class="blocklyHidden"><rect class="blocklyTooltipShadow" x="2" y="2"></rect><rect class="blocklyTooltipBackground"></rect><text class="blocklyTooltipText"></text></g></svg></div></div></span><div class="clear"></div></div></div>
<script>
  //<![CDATA[
  var script_path = "";
  var appOptions = {"levelGameName":"CustomFlappy","skinId":"flappy","baseUrl":"/blockly/","app":"flappy","droplet":false,"level":{"startBlocks":"\u003cxml\u003e\u003cblock type=\"when_run\" deletable=\"false\"\u003e\u003cnext\u003e\u003cblock type=\"flappy_setPlayer\"\u003e\u003ctitle name=\"VALUE\"\u003e\"shark\"\u003c/title\u003e\u003cnext\u003e\u003cblock type=\"flappy_setBackground\"\u003e\u003ctitle name=\"VALUE\"\u003e\"underwater\"\u003c/title\u003e\u003cnext\u003e\u003cblock type=\"flappy_setObstacle\"\u003e\u003ctitle name=\"VALUE\"\u003e\"underwater\"\u003c/title\u003e\u003cnext\u003e\u003cblock type=\"flappy_setGravity\"\u003e\u003ctitle name=\"VALUE\"\u003eFlappy.Gravity.NORMAL\u003c/title\u003e\u003cnext\u003e\u003cblock type=\"flappy_setSpeed\"\u003e\u003ctitle name=\"VALUE\"\u003eFlappy.LevelSpeed.NORMAL\u003c/title\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\"flappy_whenCollideGround\" deletable=\"false\"\u003e\u003cnext\u003e\u003cblock type=\"flappy_endGame\"\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\"flappy_whenCollideObstacle\" deletable=\"false\"\u003e\u003cnext\u003e\u003cblock type=\"flappy_endGame\"\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\"flappy_whenClick\" deletable=\"false\"\u003e\u003cnext\u003e\u003cblock type=\"flappy_flap_height\"\u003e\u003ctitle name=\"VALUE\"\u003eFlappy.FlapHeight.SMALL\u003c/title\u003e\u003cnext\u003e\u003cblock type=\"flappy_playSound\"\u003e\u003ctitle name=\"VALUE\"\u003e\"splash\"\u003c/title\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\"flappy_whenEnterObstacle\" deletable=\"false\"\u003e\u003cnext\u003e\u003cblock type=\"flappy_incrementPlayerScore\"\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/xml\u003e","toolbox":"\u003cxml id=\"toolbox\" style=\"display: none;\"\u003e\u003cblock type=\"flappy_flap_height\"/\u003e\u003cblock type=\"flappy_playSound\"/\u003e\u003cblock type=\"flappy_incrementPlayerScore\"/\u003e\u003cblock type=\"flappy_endGame\"/\u003e\u003cblock type=\"flappy_setSpeed\"/\u003e\u003cblock type=\"flappy_setBackground\"/\u003e\u003cblock type=\"flappy_setPlayer\"/\u003e\u003cblock type=\"flappy_setObstacle\"/\u003e\u003cblock type=\"flappy_setGround\"/\u003e\u003cblock type=\"flappy_setGapHeight\"/\u003e\u003cblock type=\"flappy_setGravity\"/\u003e\u003cblock type=\"flappy_setScore\"/\u003e\u003c/xml\u003e","levelBuilderRequiredBlocks":"\u003cxml/\u003e","skin":"flappy","shareable":true,"obstacles":true,"ground":true,"score":true,"freePlay":true,"scale":"{\"snapRadius\":2}","shortInstructions":"Create your own Flappy game. You can change all the visuals and all the rules, even the gravity. When you're done, click Finish to let friends try your game on their phones.","embed":null,"instructionsImportant":false,"isK1":false,"skipInstructionsPopup":false,"neverAutoplayVideo":false,"disableParamEditing":true,"disableVariableEditing":false,"disableProcedureAutopopulate":false,"useModalFunctionEditor":false,"useContractEditor":false,"contractHighlight":false,"contractCollapse":false,"examplesHighlight":false,"examplesCollapse":false,"examplesRequired":false,"definitionHighlight":false,"definitionCollapse":false,"disableExamples":false,"hideShareAndRemix":false,"disableIfElseEditing":false,"defaultFlap":"NORMAL","hintPromptAttemptsThreshold":3,"sharedBlocks":[],"levelId":"custom","editCode":false,"puzzle_number":1,"stage_total":1,"lastAttempt":null,"submittable":false,"levelVideos":[],"mapReference":null,"referenceLinks":null},"textToSpeechEnabled":null,"fullWidth":true,"noHeader":true,"noFooter":true,"codeStudioLogo":true,"hasI18n":true,"callouts":[],"isLegacyShare":true,"postMilestoneMode":"all","puzzleRatingsUrl":"/puzzle_ratings","authoredHintViewRequestsUrl":"/authored_hint_view_requests.json","serverLevelId":337,"publicCaching":false,"hasContainedLevels":false,"hideSource":true,"share":true,"legacyShareStyle":true,"isSignedIn":false,"isTooYoung":false,"pinWorkspaceToBottom":true,"hasVerticalScrollbars":true,"showExampleTestButtons":true,"report":{"fallback_response":null,"callback":"https://studio.code.org/milestone/0/level/337","sublevelCallback":null},"isStartMode":false,"isUS":false,"copyrightStrings":{"thank_you":"We%20thank%20our%20%3Ca%20href=%22https://code.org/about/donors%22%3Edonors%3C/a%3E,%20%3Ca%20href=%22https://code.org/about/partners%22%3Epartners%3C/a%3E,%20our%20%3Ca%20href=%22https://code.org/about/team%22%3Eextended%20team%3C/a%3E,%20our%20video%20cast,%20and%20our%20%3Ca%20href=%22https://code.org/about/advisors%22%3Eeducation%20advisors%3C/a%3E%20for%20their%20support%20in%20creating%20Code%20Studio.","help_from_html":"We especially want to recognize the engineers from Amazon, Google, and Microsoft who helped create these materials.","art_from_html":"Minecraft\u0026%238482;%20\u0026copy;%202020%20Microsoft.%20All%20Rights%20Reserved.%3Cbr%20/%3EStar%20Wars\u0026%238482;%20\u0026copy;%202020%20Disney%20and%20Lucasfilm.%20All%20Rights%20Reserved.%3Cbr%20/%3EFrozen\u0026%238482;%20\u0026copy;%202020%20Disney.%20All%20Rights%20Reserved.%3Cbr%20/%3EIce%20Age\u0026%238482;%20\u0026copy;%202020%2020th%20Century%20Fox.%20All%20Rights%20Reserved.%3Cbr%20/%3EAngry%20Birds\u0026%238482;%20\u0026copy;%202009-2020%20Rovio%20Entertainment%20Ltd.%20All%20Rights%20Reserved.%3Cbr%20/%3EPlants%20vs.%20Zombies\u0026%238482;%20\u0026copy;%202020%20Electronic%20Arts%20Inc.%20All%20Rights%20Reserved.%3Cbr%20/%3EThe%20Amazing%20World%20of%20Gumball%20is%20trademark%20and%20\u0026copy;%202020%20Cartoon%20Network.","code_from_html":"Code.org%20uses%20p5.play,%20which%20is%20licensed%20under%20%3Ca%20href=%22http://www.gnu.org/licenses/old-licenses/lgpl-2.1-standalone.html%22%3Ethe%20GNU%20LGPL%202.1%3C/a%3E.","powered_by_aws":"Powered by Amazon Web Services","trademark":"\u0026copy;%20Code.org,%202020.%20Code.org\u0026reg;,%20the%20CODE%20logo%20and%20Hour%20of%20Code\u0026reg;%20are%20trademarks%20of%20Code.org."},"dialog":{"skipSound":false,"preTitle":null,"fallbackResponse":"null","callback":"https://studio.code.org/milestone/0/level/337","sublevelCallback":null,"app":"flappy","level":"custom","shouldShowDialog":true}};
  appOptions.locale = 'en_us';
  //]]>
</script>



</div>
</div>


<link href="/assets/css/common-906caf213bee7178f5d8f27713a05635cdb473fe5e34ce6629ed6f47acb37afd.css" rel="stylesheet" type="text/css">
<link href="/assets/css/flappy-acae0701e190808fd18bfc946d95f15b9ca361c2f294647cd6e9aeacca53c01c.css" rel="stylesheet" type="text/css">
<script src="/assets/js/blocklywpc89966d840d431006297.min.js"></script><iframe src="https://a400912536.cdn.optimizely.com/client_storage/a400912536.html" hidden="" tabindex="-1" title="Optimizely Internal Frame" height="0" width="0" style="display: none;"></iframe>
<script src="/assets/js/en_us/blockly_localewpa16f0d7df4251188beabc52e3c071cd3.js"></script>
<script src="/assets/js/commonwp0f8f5d3e098d4e3ced44.min.js"></script>
<script src="/assets/js/en_us/flappy_localewp581cb4dd47c419cba3d46d6c550de05b.js"></script>
<script data-appoptions="{&quot;levelGameName&quot;:&quot;CustomFlappy&quot;,&quot;skinId&quot;:&quot;flappy&quot;,&quot;baseUrl&quot;:&quot;/blockly/&quot;,&quot;app&quot;:&quot;flappy&quot;,&quot;droplet&quot;:false,&quot;level&quot;:{&quot;startBlocks&quot;:&quot;\u003cxml\u003e\u003cblock type=\&quot;when_run\&quot; deletable=\&quot;false\&quot;\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_setPlayer\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003e\&quot;shark\&quot;\u003c/title\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_setBackground\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003e\&quot;underwater\&quot;\u003c/title\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_setObstacle\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003e\&quot;underwater\&quot;\u003c/title\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_setGravity\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003eFlappy.Gravity.NORMAL\u003c/title\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_setSpeed\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003eFlappy.LevelSpeed.NORMAL\u003c/title\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\&quot;flappy_whenCollideGround\&quot; deletable=\&quot;false\&quot;\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_endGame\&quot;\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\&quot;flappy_whenCollideObstacle\&quot; deletable=\&quot;false\&quot;\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_endGame\&quot;\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\&quot;flappy_whenClick\&quot; deletable=\&quot;false\&quot;\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_flap_height\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003eFlappy.FlapHeight.SMALL\u003c/title\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_playSound\&quot;\u003e\u003ctitle name=\&quot;VALUE\&quot;\u003e\&quot;splash\&quot;\u003c/title\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003cblock type=\&quot;flappy_whenEnterObstacle\&quot; deletable=\&quot;false\&quot;\u003e\u003cnext\u003e\u003cblock type=\&quot;flappy_incrementPlayerScore\&quot;\u003e\u003c/block\u003e\u003c/next\u003e\u003c/block\u003e\u003c/xml\u003e&quot;,&quot;toolbox&quot;:&quot;\u003cxml id=\&quot;toolbox\&quot; style=\&quot;display: none;\&quot;\u003e\u003cblock type=\&quot;flappy_flap_height\&quot;/\u003e\u003cblock type=\&quot;flappy_playSound\&quot;/\u003e\u003cblock type=\&quot;flappy_incrementPlayerScore\&quot;/\u003e\u003cblock type=\&quot;flappy_endGame\&quot;/\u003e\u003cblock type=\&quot;flappy_setSpeed\&quot;/\u003e\u003cblock type=\&quot;flappy_setBackground\&quot;/\u003e\u003cblock type=\&quot;flappy_setPlayer\&quot;/\u003e\u003cblock type=\&quot;flappy_setObstacle\&quot;/\u003e\u003cblock type=\&quot;flappy_setGround\&quot;/\u003e\u003cblock type=\&quot;flappy_setGapHeight\&quot;/\u003e\u003cblock type=\&quot;flappy_setGravity\&quot;/\u003e\u003cblock type=\&quot;flappy_setScore\&quot;/\u003e\u003c/xml\u003e&quot;,&quot;levelBuilderRequiredBlocks&quot;:&quot;\u003cxml/\u003e&quot;,&quot;skin&quot;:&quot;flappy&quot;,&quot;shareable&quot;:true,&quot;obstacles&quot;:true,&quot;ground&quot;:true,&quot;score&quot;:true,&quot;freePlay&quot;:true,&quot;scale&quot;:&quot;{\&quot;snapRadius\&quot;:2}&quot;,&quot;shortInstructions&quot;:&quot;Create your own Flappy game. You can change all the visuals and all the rules, even the gravity. When you're done, click Finish to let friends try your game on their phones.&quot;,&quot;embed&quot;:null,&quot;instructionsImportant&quot;:false,&quot;isK1&quot;:false,&quot;skipInstructionsPopup&quot;:false,&quot;neverAutoplayVideo&quot;:false,&quot;disableParamEditing&quot;:true,&quot;disableVariableEditing&quot;:false,&quot;disableProcedureAutopopulate&quot;:false,&quot;useModalFunctionEditor&quot;:false,&quot;useContractEditor&quot;:false,&quot;contractHighlight&quot;:false,&quot;contractCollapse&quot;:false,&quot;examplesHighlight&quot;:false,&quot;examplesCollapse&quot;:false,&quot;examplesRequired&quot;:false,&quot;definitionHighlight&quot;:false,&quot;definitionCollapse&quot;:false,&quot;disableExamples&quot;:false,&quot;hideShareAndRemix&quot;:false,&quot;disableIfElseEditing&quot;:false,&quot;defaultFlap&quot;:&quot;NORMAL&quot;,&quot;hintPromptAttemptsThreshold&quot;:3,&quot;sharedBlocks&quot;:[],&quot;levelId&quot;:&quot;custom&quot;,&quot;editCode&quot;:false,&quot;puzzle_number&quot;:1,&quot;stage_total&quot;:1,&quot;lastAttempt&quot;:null,&quot;submittable&quot;:false,&quot;levelVideos&quot;:[],&quot;mapReference&quot;:null,&quot;referenceLinks&quot;:null},&quot;textToSpeechEnabled&quot;:null,&quot;fullWidth&quot;:true,&quot;noHeader&quot;:true,&quot;noFooter&quot;:true,&quot;codeStudioLogo&quot;:true,&quot;hasI18n&quot;:true,&quot;callouts&quot;:[],&quot;isLegacyShare&quot;:true,&quot;postMilestoneMode&quot;:&quot;all&quot;,&quot;puzzleRatingsUrl&quot;:&quot;/puzzle_ratings&quot;,&quot;authoredHintViewRequestsUrl&quot;:&quot;/authored_hint_view_requests.json&quot;,&quot;serverLevelId&quot;:337,&quot;publicCaching&quot;:false,&quot;hasContainedLevels&quot;:false,&quot;hideSource&quot;:true,&quot;share&quot;:true,&quot;legacyShareStyle&quot;:true,&quot;isSignedIn&quot;:false,&quot;isTooYoung&quot;:false,&quot;pinWorkspaceToBottom&quot;:true,&quot;hasVerticalScrollbars&quot;:true,&quot;showExampleTestButtons&quot;:true,&quot;report&quot;:{&quot;fallback_response&quot;:null,&quot;callback&quot;:&quot;https://studio.code.org/milestone/0/level/337&quot;,&quot;sublevelCallback&quot;:null},&quot;isStartMode&quot;:false,&quot;isUS&quot;:false,&quot;copyrightStrings&quot;:{&quot;thank_you&quot;:&quot;We%20thank%20our%20%3Ca%20href=%22https://code.org/about/donors%22%3Edonors%3C/a%3E,%20%3Ca%20href=%22https://code.org/about/partners%22%3Epartners%3C/a%3E,%20our%20%3Ca%20href=%22https://code.org/about/team%22%3Eextended%20team%3C/a%3E,%20our%20video%20cast,%20and%20our%20%3Ca%20href=%22https://code.org/about/advisors%22%3Eeducation%20advisors%3C/a%3E%20for%20their%20support%20in%20creating%20Code%20Studio.&quot;,&quot;help_from_html&quot;:&quot;We especially want to recognize the engineers from Amazon, Google, and Microsoft who helped create these materials.&quot;,&quot;art_from_html&quot;:&quot;Minecraft\u0026%238482;%20\u0026copy;%202020%20Microsoft.%20All%20Rights%20Reserved.%3Cbr%20/%3EStar%20Wars\u0026%238482;%20\u0026copy;%202020%20Disney%20and%20Lucasfilm.%20All%20Rights%20Reserved.%3Cbr%20/%3EFrozen\u0026%238482;%20\u0026copy;%202020%20Disney.%20All%20Rights%20Reserved.%3Cbr%20/%3EIce%20Age\u0026%238482;%20\u0026copy;%202020%2020th%20Century%20Fox.%20All%20Rights%20Reserved.%3Cbr%20/%3EAngry%20Birds\u0026%238482;%20\u0026copy;%202009-2020%20Rovio%20Entertainment%20Ltd.%20All%20Rights%20Reserved.%3Cbr%20/%3EPlants%20vs.%20Zombies\u0026%238482;%20\u0026copy;%202020%20Electronic%20Arts%20Inc.%20All%20Rights%20Reserved.%3Cbr%20/%3EThe%20Amazing%20World%20of%20Gumball%20is%20trademark%20and%20\u0026copy;%202020%20Cartoon%20Network.&quot;,&quot;code_from_html&quot;:&quot;Code.org%20uses%20p5.play,%20which%20is%20licensed%20under%20%3Ca%20href=%22http://www.gnu.org/licenses/old-licenses/lgpl-2.1-standalone.html%22%3Ethe%20GNU%20LGPL%202.1%3C/a%3E.&quot;,&quot;powered_by_aws&quot;:&quot;Powered by Amazon Web Services&quot;,&quot;trademark&quot;:&quot;\u0026copy;%20Code.org,%202020.%20Code.org\u0026reg;,%20the%20CODE%20logo%20and%20Hour%20of%20Code\u0026reg;%20are%20trademarks%20of%20Code.org.&quot;},&quot;dialog&quot;:{&quot;skipSound&quot;:false,&quot;preTitle&quot;:null,&quot;fallbackResponse&quot;:&quot;null&quot;,&quot;callback&quot;:&quot;https://studio.code.org/milestone/0/level/337&quot;,&quot;sublevelCallback&quot;:null,&quot;app&quot;:&quot;flappy&quot;,&quot;level&quot;:&quot;custom&quot;,&quot;shouldShowDialog&quot;:true},&quot;locale&quot;:&quot;en_us&quot;}" src="/assets/js/flappywp04a5b4e975d4518a9288.min.js"></script>




<div><!-- react-empty: 1 --></div><div><div data-reactroot=""><!-- react-empty: 2 --><!-- react-empty: 3 --></div></div><div class="WireframeButtons_containerRight"><div data-reactroot="" style="font: 12pt &quot;Gotham 5r&quot;, sans-serif;"><span style="display: inline-block;"><a class="WireframeButtons_button"><i class="fa fa-mobile"></i><!-- react-text: 5 --> <!-- /react-text --><!-- react-text: 6 -->Send to phone<!-- /react-text --></a></span><br></div></div><svg id="blocklyDragCanvas" width="100%" height="100%"><g class="svgDragCanvas" transform="translate(35,0)"></g><g class="svgDragCanvas"></g></svg><div class="blocklyWidgetDiv" style="direction: ltr;"></div></body></html>
