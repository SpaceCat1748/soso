/*! For license information please see main.e2d3e81b.js.LICENSE.txt */
( () => {
    "use strict";
    var e = {
        2730: (e, t, n) => {
            var r = n(5043)
              , a = n(8853);
            function o(e) {
                for (var t = "https://reactjs.org/docs/error-decoder.html?invariant=" + e, n = 1; n < arguments.length; n++)
                    t += "&args[]=" + encodeURIComponent(arguments[n]);
                return "Minified React error #" + e + "; visit " + t + " for the full message or use the non-minified dev environment for full errors and additional helpful warnings."
            }
            var i = new Set
              , l = {};
            function s(e, t) {
                u(e, t),
                u(e + "Capture", t)
            }
            function u(e, t) {
                for (l[e] = t,
                e = 0; e < t.length; e++)
                    i.add(t[e])
            }
            var c = !("undefined" === typeof window || "undefined" === typeof window.document || "undefined" === typeof window.document.createElement)
              , d = Object.prototype.hasOwnProperty
              , p = /^[:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD][:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD\-.0-9\u00B7\u0300-\u036F\u203F-\u2040]*$/
              , f = {}
              , m = {};
            function h(e, t, n, r, a, o, i) {
                this.acceptsBooleans = 2 === t || 3 === t || 4 === t,
                this.attributeName = r,
                this.attributeNamespace = a,
                this.mustUseProperty = n,
                this.propertyName = e,
                this.type = t,
                this.sanitizeURL = o,
                this.removeEmptyString = i
            }
            var g = {};
            "children dangerouslySetInnerHTML defaultValue defaultChecked innerHTML suppressContentEditableWarning suppressHydrationWarning style".split(" ").forEach((function(e) {
                g[e] = new h(e,0,!1,e,null,!1,!1)
            }
            )),
            [["acceptCharset", "accept-charset"], ["className", "class"], ["htmlFor", "for"], ["httpEquiv", "http-equiv"]].forEach((function(e) {
                var t = e[0];
                g[t] = new h(t,1,!1,e[1],null,!1,!1)
            }
            )),
            ["contentEditable", "draggable", "spellCheck", "value"].forEach((function(e) {
                g[e] = new h(e,2,!1,e.toLowerCase(),null,!1,!1)
            }
            )),
            ["autoReverse", "externalResourcesRequired", "focusable", "preserveAlpha"].forEach((function(e) {
                g[e] = new h(e,2,!1,e,null,!1,!1)
            }
            )),
            "allowFullScreen async autoFocus autoPlay controls default defer disabled disablePictureInPicture disableRemotePlayback formNoValidate hidden loop noModule noValidate open playsInline readOnly required reversed scoped seamless itemScope".split(" ").forEach((function(e) {
                g[e] = new h(e,3,!1,e.toLowerCase(),null,!1,!1)
            }
            )),
            ["checked", "multiple", "muted", "selected"].forEach((function(e) {
                g[e] = new h(e,3,!0,e,null,!1,!1)
            }
            )),
            ["capture", "download"].forEach((function(e) {
                g[e] = new h(e,4,!1,e,null,!1,!1)
            }
            )),
            ["cols", "rows", "size", "span"].forEach((function(e) {
                g[e] = new h(e,6,!1,e,null,!1,!1)
            }
            )),
            ["rowSpan", "start"].forEach((function(e) {
                g[e] = new h(e,5,!1,e.toLowerCase(),null,!1,!1)
            }
            ));
            var v = /[\-:]([a-z])/g;
            function y(e) {
                return e[1].toUpperCase()
            }
            function b(e, t, n, r) {
                var a = g.hasOwnProperty(t) ? g[t] : null;
                (null !== a ? 0 !== a.type : r || !(2 < t.length) || "o" !== t[0] && "O" !== t[0] || "n" !== t[1] && "N" !== t[1]) && (function(e, t, n, r) {
                    if (null === t || "undefined" === typeof t || function(e, t, n, r) {
                        if (null !== n && 0 === n.type)
                            return !1;
                        switch (typeof t) {
                        case "function":
                        case "symbol":
                            return !0;
                        case "boolean":
                            return !r && (null !== n ? !n.acceptsBooleans : "data-" !== (e = e.toLowerCase().slice(0, 5)) && "aria-" !== e);
                        default:
                            return !1
                        }
                    }(e, t, n, r))
                        return !0;
                    if (r)
                        return !1;
                    if (null !== n)
                        switch (n.type) {
                        case 3:
                            return !t;
                        case 4:
                            return !1 === t;
                        case 5:
                            return isNaN(t);
                        case 6:
                            return isNaN(t) || 1 > t
                        }
                    return !1
                }(t, n, a, r) && (n = null),
                r || null === a ? function(e) {
                    return !!d.call(m, e) || !d.call(f, e) && (p.test(e) ? m[e] = !0 : (f[e] = !0,
                    !1))
                }(t) && (null === n ? e.removeAttribute(t) : e.setAttribute(t, "" + n)) : a.mustUseProperty ? e[a.propertyName] = null === n ? 3 !== a.type && "" : n : (t = a.attributeName,
                r = a.attributeNamespace,
                null === n ? e.removeAttribute(t) : (n = 3 === (a = a.type) || 4 === a && !0 === n ? "" : "" + n,
                r ? e.setAttributeNS(r, t, n) : e.setAttribute(t, n))))
            }
            "accent-height alignment-baseline arabic-form baseline-shift cap-height clip-path clip-rule color-interpolation color-interpolation-filters color-profile color-rendering dominant-baseline enable-background fill-opacity fill-rule flood-color flood-opacity font-family font-size font-size-adjust font-stretch font-style font-variant font-weight glyph-name glyph-orientation-horizontal glyph-orientation-vertical horiz-adv-x horiz-origin-x image-rendering letter-spacing lighting-color marker-end marker-mid marker-start overline-position overline-thickness paint-order panose-1 pointer-events rendering-intent shape-rendering stop-color stop-opacity strikethrough-position strikethrough-thickness stroke-dasharray stroke-dashoffset stroke-linecap stroke-linejoin stroke-miterlimit stroke-opacity stroke-width text-anchor text-decoration text-rendering underline-position underline-thickness unicode-bidi unicode-range units-per-em v-alphabetic v-hanging v-ideographic v-mathematical vector-effect vert-adv-y vert-origin-x vert-origin-y word-spacing writing-mode xmlns:xlink x-height".split(" ").forEach((function(e) {
                var t = e.replace(v, y);
                g[t] = new h(t,1,!1,e,null,!1,!1)
            }
            )),
            "xlink:actuate xlink:arcrole xlink:role xlink:show xlink:title xlink:type".split(" ").forEach((function(e) {
                var t = e.replace(v, y);
                g[t] = new h(t,1,!1,e,"http://www.w3.org/1999/xlink",!1,!1)
            }
            )),
            ["xml:base", "xml:lang", "xml:space"].forEach((function(e) {
                var t = e.replace(v, y);
                g[t] = new h(t,1,!1,e,"http://www.w3.org/XML/1998/namespace",!1,!1)
            }
            )),
            ["tabIndex", "crossOrigin"].forEach((function(e) {
                g[e] = new h(e,1,!1,e.toLowerCase(),null,!1,!1)
            }
            )),
            g.xlinkHref = new h("xlinkHref",1,!1,"xlink:href","http://www.w3.org/1999/xlink",!0,!1),
            ["src", "href", "action", "formAction"].forEach((function(e) {
                g[e] = new h(e,1,!1,e.toLowerCase(),null,!0,!0)
            }
            ));
            var x = r.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED
              , w = Symbol.for("react.element")
              , A = Symbol.for("react.portal")
              , k = Symbol.for("react.fragment")
              , S = Symbol.for("react.strict_mode")
              , E = Symbol.for("react.profiler")
              , j = Symbol.for("react.provider")
              , N = Symbol.for("react.context")
              , C = Symbol.for("react.forward_ref")
              , R = Symbol.for("react.suspense")
              , O = Symbol.for("react.suspense_list")
              , T = Symbol.for("react.memo")
              , L = Symbol.for("react.lazy");
            Symbol.for("react.scope"),
            Symbol.for("react.debug_trace_mode");
            var U = Symbol.for("react.offscreen");
            Symbol.for("react.legacy_hidden"),
            Symbol.for("react.cache"),
            Symbol.for("react.tracing_marker");
            var P = Symbol.iterator;
            function I(e) {
                return null === e || "object" !== typeof e ? null : "function" === typeof (e = P && e[P] || e["@@iterator"]) ? e : null
            }
            var F, z = Object.assign;
            function M(e) {
                if (void 0 === F)
                    try {
                        throw Error()
                    } catch (n) {
                        var t = n.stack.trim().match(/\n( *(at )?)/);
                        F = t && t[1] || ""
                    }
                return "\n" + F + e
            }
            var B = !1;
            function q(e, t) {
                if (!e || B)
                    return "";
                B = !0;
                var n = Error.prepareStackTrace;
                Error.prepareStackTrace = void 0;
                try {
                    if (t)
                        if (t = function() {
                            throw Error()
                        }
                        ,
                        Object.defineProperty(t.prototype, "props", {
                            set: function() {
                                throw Error()
                            }
                        }),
                        "object" === typeof Reflect && Reflect.construct) {
                            try {
                                Reflect.construct(t, [])
                            } catch (u) {
                                var r = u
                            }
                            Reflect.construct(e, [], t)
                        } else {
                            try {
                                t.call()
                            } catch (u) {
                                r = u
                            }
                            e.call(t.prototype)
                        }
                    else {
                        try {
                            throw Error()
                        } catch (u) {
                            r = u
                        }
                        e()
                    }
                } catch (u) {
                    if (u && r && "string" === typeof u.stack) {
                        for (var a = u.stack.split("\n"), o = r.stack.split("\n"), i = a.length - 1, l = o.length - 1; 1 <= i && 0 <= l && a[i] !== o[l]; )
                            l--;
                        for (; 1 <= i && 0 <= l; i--,
                        l--)
                            if (a[i] !== o[l]) {
                                if (1 !== i || 1 !== l)
                                    do {
                                        if (i--,
                                        0 > --l || a[i] !== o[l]) {
                                            var s = "\n" + a[i].replace(" at new ", " at ");
                                            return e.displayName && s.includes("<anonymous>") && (s = s.replace("<anonymous>", e.displayName)),
                                            s
                                        }
                                    } while (1 <= i && 0 <= l);
                                break
                            }
                    }
                } finally {
                    B = !1,
                    Error.prepareStackTrace = n
                }
                return (e = e ? e.displayName || e.name : "") ? M(e) : ""
            }
            function D(e) {
                switch (e.tag) {
                case 5:
                    return M(e.type);
                case 16:
                    return M("Lazy");
                case 13:
                    return M("Suspense");
                case 19:
                    return M("SuspenseList");
                case 0:
                case 2:
                case 15:
                    return e = q(e.type, !1);
                case 11:
                    return e = q(e.type.render, !1);
                case 1:
                    return e = q(e.type, !0);
                default:
                    return ""
                }
            }
            function H(e) {
                if (null == e)
                    return null;
                if ("function" === typeof e)
                    return e.displayName || e.name || null;
                if ("string" === typeof e)
                    return e;
                switch (e) {
                case k:
                    return "Fragment";
                case A:
                    return "Portal";
                case E:
                    return "Profiler";
                case S:
                    return "StrictMode";
                case R:
                    return "Suspense";
                case O:
                    return "SuspenseList"
                }
                if ("object" === typeof e)
                    switch (e.$$typeof) {
                    case N:
                        return (e.displayName || "Context") + ".Consumer";
                    case j:
                        return (e._context.displayName || "Context") + ".Provider";
                    case C:
                        var t = e.render;
                        return (e = e.displayName) || (e = "" !== (e = t.displayName || t.name || "") ? "ForwardRef(" + e + ")" : "ForwardRef"),
                        e;
                    case T:
                        return null !== (t = e.displayName || null) ? t : H(e.type) || "Memo";
                    case L:
                        t = e._payload,
                        e = e._init;
                        try {
                            return H(e(t))
                        } catch (n) {}
                    }
                return null
            }
            function Q(e) {
                var t = e.type;
                switch (e.tag) {
                case 24:
                    return "Cache";
                case 9:
                    return (t.displayName || "Context") + ".Consumer";
                case 10:
                    return (t._context.displayName || "Context") + ".Provider";
                case 18:
                    return "DehydratedFragment";
                case 11:
                    return e = (e = t.render).displayName || e.name || "",
                    t.displayName || ("" !== e ? "ForwardRef(" + e + ")" : "ForwardRef");
                case 7:
                    return "Fragment";
                case 5:
                    return t;
                case 4:
                    return "Portal";
                case 3:
                    return "Root";
                case 6:
                    return "Text";
                case 16:
                    return H(t);
                case 8:
                    return t === S ? "StrictMode" : "Mode";
                case 22:
                    return "Offscreen";
                case 12:
                    return "Profiler";
                case 21:
                    return "Scope";
                case 13:
                    return "Suspense";
                case 19:
                    return "SuspenseList";
                case 25:
                    return "TracingMarker";
                case 1:
                case 0:
                case 17:
                case 2:
                case 14:
                case 15:
                    if ("function" === typeof t)
                        return t.displayName || t.name || null;
                    if ("string" === typeof t)
                        return t
                }
                return null
            }
            function Y(e) {
                switch (typeof e) {
                case "boolean":
                case "number":
                case "string":
                case "undefined":
                case "object":
                    return e;
                default:
                    return ""
                }
            }
            function W(e) {
                var t = e.type;
                return (e = e.nodeName) && "input" === e.toLowerCase() && ("checkbox" === t || "radio" === t)
            }
            function G(e) {
                e._valueTracker || (e._valueTracker = function(e) {
                    var t = W(e) ? "checked" : "value"
                      , n = Object.getOwnPropertyDescriptor(e.constructor.prototype, t)
                      , r = "" + e[t];
                    if (!e.hasOwnProperty(t) && "undefined" !== typeof n && "function" === typeof n.get && "function" === typeof n.set) {
                        var a = n.get
                          , o = n.set;
                        return Object.defineProperty(e, t, {
                            configurable: !0,
                            get: function() {
                                return a.call(this)
                            },
                            set: function(e) {
                                r = "" + e,
                                o.call(this, e)
                            }
                        }),
                        Object.defineProperty(e, t, {
                            enumerable: n.enumerable
                        }),
                        {
                            getValue: function() {
                                return r
                            },
                            setValue: function(e) {
                                r = "" + e
                            },
                            stopTracking: function() {
                                e._valueTracker = null,
                                delete e[t]
                            }
                        }
                    }
                }(e))
            }
            function V(e) {
                if (!e)
                    return !1;
                var t = e._valueTracker;
                if (!t)
                    return !0;
                var n = t.getValue()
                  , r = "";
                return e && (r = W(e) ? e.checked ? "true" : "false" : e.value),
                (e = r) !== n && (t.setValue(e),
                !0)
            }
            function Z(e) {
                if ("undefined" === typeof (e = e || ("undefined" !== typeof document ? document : void 0)))
                    return null;
                try {
                    return e.activeElement || e.body
                } catch (t) {
                    return e.body
                }
            }
            function K(e, t) {
                var n = t.checked;
                return z({}, t, {
                    defaultChecked: void 0,
                    defaultValue: void 0,
                    value: void 0,
                    checked: null != n ? n : e._wrapperState.initialChecked
                })
            }
            function J(e, t) {
                var n = null == t.defaultValue ? "" : t.defaultValue
                  , r = null != t.checked ? t.checked : t.defaultChecked;
                n = Y(null != t.value ? t.value : n),
                e._wrapperState = {
                    initialChecked: r,
                    initialValue: n,
                    controlled: "checkbox" === t.type || "radio" === t.type ? null != t.checked : null != t.value
                }
            }
            function X(e, t) {
                null != (t = t.checked) && b(e, "checked", t, !1)
            }
            function _(e, t) {
                X(e, t);
                var n = Y(t.value)
                  , r = t.type;
                if (null != n)
                    "number" === r ? (0 === n && "" === e.value || e.value != n) && (e.value = "" + n) : e.value !== "" + n && (e.value = "" + n);
                else if ("submit" === r || "reset" === r)
                    return void e.removeAttribute("value");
                t.hasOwnProperty("value") ? ee(e, t.type, n) : t.hasOwnProperty("defaultValue") && ee(e, t.type, Y(t.defaultValue)),
                null == t.checked && null != t.defaultChecked && (e.defaultChecked = !!t.defaultChecked)
            }
            function $(e, t, n) {
                if (t.hasOwnProperty("value") || t.hasOwnProperty("defaultValue")) {
                    var r = t.type;
                    if (!("submit" !== r && "reset" !== r || void 0 !== t.value && null !== t.value))
                        return;
                    t = "" + e._wrapperState.initialValue,
                    n || t === e.value || (e.value = t),
                    e.defaultValue = t
                }
                "" !== (n = e.name) && (e.name = ""),
                e.defaultChecked = !!e._wrapperState.initialChecked,
                "" !== n && (e.name = n)
            }
            function ee(e, t, n) {
                "number" === t && Z(e.ownerDocument) === e || (null == n ? e.defaultValue = "" + e._wrapperState.initialValue : e.defaultValue !== "" + n && (e.defaultValue = "" + n))
            }
            var te = Array.isArray;
            function ne(e, t, n, r) {
                if (e = e.options,
                t) {
                    t = {};
                    for (var a = 0; a < n.length; a++)
                        t["$" + n[a]] = !0;
                    for (n = 0; n < e.length; n++)
                        a = t.hasOwnProperty("$" + e[n].value),
                        e[n].selected !== a && (e[n].selected = a),
                        a && r && (e[n].defaultSelected = !0)
                } else {
                    for (n = "" + Y(n),
                    t = null,
                    a = 0; a < e.length; a++) {
                        if (e[a].value === n)
                            return e[a].selected = !0,
                            void (r && (e[a].defaultSelected = !0));
                        null !== t || e[a].disabled || (t = e[a])
                    }
                    null !== t && (t.selected = !0)
                }
            }
            function re(e, t) {
                if (null != t.dangerouslySetInnerHTML)
                    throw Error(o(91));
                return z({}, t, {
                    value: void 0,
                    defaultValue: void 0,
                    children: "" + e._wrapperState.initialValue
                })
            }
            function ae(e, t) {
                var n = t.value;
                if (null == n) {
                    if (n = t.children,
                    t = t.defaultValue,
                    null != n) {
                        if (null != t)
                            throw Error(o(92));
                        if (te(n)) {
                            if (1 < n.length)
                                throw Error(o(93));
                            n = n[0]
                        }
                        t = n
                    }
                    null == t && (t = ""),
                    n = t
                }
                e._wrapperState = {
                    initialValue: Y(n)
                }
            }
            function oe(e, t) {
                var n = Y(t.value)
                  , r = Y(t.defaultValue);
                null != n && ((n = "" + n) !== e.value && (e.value = n),
                null == t.defaultValue && e.defaultValue !== n && (e.defaultValue = n)),
                null != r && (e.defaultValue = "" + r)
            }
            function ie(e) {
                var t = e.textContent;
                t === e._wrapperState.initialValue && "" !== t && null !== t && (e.value = t)
            }
            function le(e) {
                switch (e) {
                case "svg":
                    return "http://www.w3.org/2000/svg";
                case "math":
                    return "http://www.w3.org/1998/Math/MathML";
                default:
                    return "http://www.w3.org/1999/xhtml"
                }
            }
            function se(e, t) {
                return null == e || "http://www.w3.org/1999/xhtml" === e ? le(t) : "http://www.w3.org/2000/svg" === e && "foreignObject" === t ? "http://www.w3.org/1999/xhtml" : e
            }
            var ue, ce, de = (ce = function(e, t) {
                if ("http://www.w3.org/2000/svg" !== e.namespaceURI || "innerHTML"in e)
                    e.innerHTML = t;
                else {
                    for ((ue = ue || document.createElement("div")).innerHTML = "<svg>" + t.valueOf().toString() + "</svg>",
                    t = ue.firstChild; e.firstChild; )
                        e.removeChild(e.firstChild);
                    for (; t.firstChild; )
                        e.appendChild(t.firstChild)
                }
            }
            ,
            "undefined" !== typeof MSApp && MSApp.execUnsafeLocalFunction ? function(e, t, n, r) {
                MSApp.execUnsafeLocalFunction((function() {
                    return ce(e, t)
                }
                ))
            }
            : ce);
            function pe(e, t) {
                if (t) {
                    var n = e.firstChild;
                    if (n && n === e.lastChild && 3 === n.nodeType)
                        return void (n.nodeValue = t)
                }
                e.textContent = t
            }
            var fe = {
                animationIterationCount: !0,
                aspectRatio: !0,
                borderImageOutset: !0,
                borderImageSlice: !0,
                borderImageWidth: !0,
                boxFlex: !0,
                boxFlexGroup: !0,
                boxOrdinalGroup: !0,
                columnCount: !0,
                columns: !0,
                flex: !0,
                flexGrow: !0,
                flexPositive: !0,
                flexShrink: !0,
                flexNegative: !0,
                flexOrder: !0,
                gridArea: !0,
                gridRow: !0,
                gridRowEnd: !0,
                gridRowSpan: !0,
                gridRowStart: !0,
                gridColumn: !0,
                gridColumnEnd: !0,
                gridColumnSpan: !0,
                gridColumnStart: !0,
                fontWeight: !0,
                lineClamp: !0,
                lineHeight: !0,
                opacity: !0,
                order: !0,
                orphans: !0,
                tabSize: !0,
                widows: !0,
                zIndex: !0,
                zoom: !0,
                fillOpacity: !0,
                floodOpacity: !0,
                stopOpacity: !0,
                strokeDasharray: !0,
                strokeDashoffset: !0,
                strokeMiterlimit: !0,
                strokeOpacity: !0,
                strokeWidth: !0
            }
              , me = ["Webkit", "ms", "Moz", "O"];
            function he(e, t, n) {
                return null == t || "boolean" === typeof t || "" === t ? "" : n || "number" !== typeof t || 0 === t || fe.hasOwnProperty(e) && fe[e] ? ("" + t).trim() : t + "px"
            }
            function ge(e, t) {
                for (var n in e = e.style,
                t)
                    if (t.hasOwnProperty(n)) {
                        var r = 0 === n.indexOf("--")
                          , a = he(n, t[n], r);
                        "float" === n && (n = "cssFloat"),
                        r ? e.setProperty(n, a) : e[n] = a
                    }
            }
            Object.keys(fe).forEach((function(e) {
                me.forEach((function(t) {
                    t = t + e.charAt(0).toUpperCase() + e.substring(1),
                    fe[t] = fe[e]
                }
                ))
            }
            ));
            var ve = z({
                menuitem: !0
            }, {
                area: !0,
                base: !0,
                br: !0,
                col: !0,
                embed: !0,
                hr: !0,
                img: !0,
                input: !0,
                keygen: !0,
                link: !0,
                meta: !0,
                param: !0,
                source: !0,
                track: !0,
                wbr: !0
            });
            function ye(e, t) {
                if (t) {
                    if (ve[e] && (null != t.children || null != t.dangerouslySetInnerHTML))
                        throw Error(o(137, e));
                    if (null != t.dangerouslySetInnerHTML) {
                        if (null != t.children)
                            throw Error(o(60));
                        if ("object" !== typeof t.dangerouslySetInnerHTML || !("__html"in t.dangerouslySetInnerHTML))
                            throw Error(o(61))
                    }
                    if (null != t.style && "object" !== typeof t.style)
                        throw Error(o(62))
                }
            }
            function be(e, t) {
                if (-1 === e.indexOf("-"))
                    return "string" === typeof t.is;
                switch (e) {
                case "annotation-xml":
                case "color-profile":
                case "font-face":
                case "font-face-src":
                case "font-face-uri":
                case "font-face-format":
                case "font-face-name":
                case "missing-glyph":
                    return !1;
                default:
                    return !0
                }
            }
            var xe = null;
            function we(e) {
                return (e = e.target || e.srcElement || window).correspondingUseElement && (e = e.correspondingUseElement),
                3 === e.nodeType ? e.parentNode : e
            }
            var Ae = null
              , ke = null
              , Se = null;
            function Ee(e) {
                if (e = ba(e)) {
                    if ("function" !== typeof Ae)
                        throw Error(o(280));
                    var t = e.stateNode;
                    t && (t = wa(t),
                    Ae(e.stateNode, e.type, t))
                }
            }
            function je(e) {
                ke ? Se ? Se.push(e) : Se = [e] : ke = e
            }
            function Ne() {
                if (ke) {
                    var e = ke
                      , t = Se;
                    if (Se = ke = null,
                    Ee(e),
                    t)
                        for (e = 0; e < t.length; e++)
                            Ee(t[e])
                }
            }
            function Ce(e, t) {
                return e(t)
            }
            function Re() {}
            var Oe = !1;
            function Te(e, t, n) {
                if (Oe)
                    return e(t, n);
                Oe = !0;
                try {
                    return Ce(e, t, n)
                } finally {
                    Oe = !1,
                    (null !== ke || null !== Se) && (Re(),
                    Ne())
                }
            }
            function Le(e, t) {
                var n = e.stateNode;
                if (null === n)
                    return null;
                var r = wa(n);
                if (null === r)
                    return null;
                n = r[t];
                e: switch (t) {
                case "onClick":
                case "onClickCapture":
                case "onDoubleClick":
                case "onDoubleClickCapture":
                case "onMouseDown":
                case "onMouseDownCapture":
                case "onMouseMove":
                case "onMouseMoveCapture":
                case "onMouseUp":
                case "onMouseUpCapture":
                case "onMouseEnter":
                    (r = !r.disabled) || (r = !("button" === (e = e.type) || "input" === e || "select" === e || "textarea" === e)),
                    e = !r;
                    break e;
                default:
                    e = !1
                }
                if (e)
                    return null;
                if (n && "function" !== typeof n)
                    throw Error(o(231, t, typeof n));
                return n
            }
            var Ue = !1;
            if (c)
                try {
                    var Pe = {};
                    Object.defineProperty(Pe, "passive", {
                        get: function() {
                            Ue = !0
                        }
                    }),
                    window.addEventListener("test", Pe, Pe),
                    window.removeEventListener("test", Pe, Pe)
                } catch (ce) {
                    Ue = !1
                }
            function Ie(e, t, n, r, a, o, i, l, s) {
                var u = Array.prototype.slice.call(arguments, 3);
                try {
                    t.apply(n, u)
                } catch (c) {
                    this.onError(c)
                }
            }
            var Fe = !1
              , ze = null
              , Me = !1
              , Be = null
              , qe = {
                onError: function(e) {
                    Fe = !0,
                    ze = e
                }
            };
            function De(e, t, n, r, a, o, i, l, s) {
                Fe = !1,
                ze = null,
                Ie.apply(qe, arguments)
            }
            function He(e) {
                var t = e
                  , n = e;
                if (e.alternate)
                    for (; t.return; )
                        t = t.return;
                else {
                    e = t;
                    do {
                        0 !== (4098 & (t = e).flags) && (n = t.return),
                        e = t.return
                    } while (e)
                }
                return 3 === t.tag ? n : null
            }
            function Qe(e) {
                if (13 === e.tag) {
                    var t = e.memoizedState;
                    if (null === t && (null !== (e = e.alternate) && (t = e.memoizedState)),
                    null !== t)
                        return t.dehydrated
                }
                return null
            }
            function Ye(e) {
                if (He(e) !== e)
                    throw Error(o(188))
            }
            function We(e) {
                return null !== (e = function(e) {
                    var t = e.alternate;
                    if (!t) {
                        if (null === (t = He(e)))
                            throw Error(o(188));
                        return t !== e ? null : e
                    }
                    for (var n = e, r = t; ; ) {
                        var a = n.return;
                        if (null === a)
                            break;
                        var i = a.alternate;
                        if (null === i) {
                            if (null !== (r = a.return)) {
                                n = r;
                                continue
                            }
                            break
                        }
                        if (a.child === i.child) {
                            for (i = a.child; i; ) {
                                if (i === n)
                                    return Ye(a),
                                    e;
                                if (i === r)
                                    return Ye(a),
                                    t;
                                i = i.sibling
                            }
                            throw Error(o(188))
                        }
                        if (n.return !== r.return)
                            n = a,
                            r = i;
                        else {
                            for (var l = !1, s = a.child; s; ) {
                                if (s === n) {
                                    l = !0,
                                    n = a,
                                    r = i;
                                    break
                                }
                                if (s === r) {
                                    l = !0,
                                    r = a,
                                    n = i;
                                    break
                                }
                                s = s.sibling
                            }
                            if (!l) {
                                for (s = i.child; s; ) {
                                    if (s === n) {
                                        l = !0,
                                        n = i,
                                        r = a;
                                        break
                                    }
                                    if (s === r) {
                                        l = !0,
                                        r = i,
                                        n = a;
                                        break
                                    }
                                    s = s.sibling
                                }
                                if (!l)
                                    throw Error(o(189))
                            }
                        }
                        if (n.alternate !== r)
                            throw Error(o(190))
                    }
                    if (3 !== n.tag)
                        throw Error(o(188));
                    return n.stateNode.current === n ? e : t
                }(e)) ? Ge(e) : null
            }
            function Ge(e) {
                if (5 === e.tag || 6 === e.tag)
                    return e;
                for (e = e.child; null !== e; ) {
                    var t = Ge(e);
                    if (null !== t)
                        return t;
                    e = e.sibling
                }
                return null
            }
            var Ve = a.unstable_scheduleCallback
              , Ze = a.unstable_cancelCallback
              , Ke = a.unstable_shouldYield
              , Je = a.unstable_requestPaint
              , Xe = a.unstable_now
              , _e = a.unstable_getCurrentPriorityLevel
              , $e = a.unstable_ImmediatePriority
              , et = a.unstable_UserBlockingPriority
              , tt = a.unstable_NormalPriority
              , nt = a.unstable_LowPriority
              , rt = a.unstable_IdlePriority
              , at = null
              , ot = null;
            var it = Math.clz32 ? Math.clz32 : function(e) {
                return e >>>= 0,
                0 === e ? 32 : 31 - (lt(e) / st | 0) | 0
            }
              , lt = Math.log
              , st = Math.LN2;
            var ut = 64
              , ct = 4194304;
            function dt(e) {
                switch (e & -e) {
                case 1:
                    return 1;
                case 2:
                    return 2;
                case 4:
                    return 4;
                case 8:
                    return 8;
                case 16:
                    return 16;
                case 32:
                    return 32;
                case 64:
                case 128:
                case 256:
                case 512:
                case 1024:
                case 2048:
                case 4096:
                case 8192:
                case 16384:
                case 32768:
                case 65536:
                case 131072:
                case 262144:
                case 524288:
                case 1048576:
                case 2097152:
                    return 4194240 & e;
                case 4194304:
                case 8388608:
                case 16777216:
                case 33554432:
                case 67108864:
                    return 130023424 & e;
                case 134217728:
                    return 134217728;
                case 268435456:
                    return 268435456;
                case 536870912:
                    return 536870912;
                case 1073741824:
                    return 1073741824;
                default:
                    return e
                }
            }
            function pt(e, t) {
                var n = e.pendingLanes;
                if (0 === n)
                    return 0;
                var r = 0
                  , a = e.suspendedLanes
                  , o = e.pingedLanes
                  , i = 268435455 & n;
                if (0 !== i) {
                    var l = i & ~a;
                    0 !== l ? r = dt(l) : 0 !== (o &= i) && (r = dt(o))
                } else
                    0 !== (i = n & ~a) ? r = dt(i) : 0 !== o && (r = dt(o));
                if (0 === r)
                    return 0;
                if (0 !== t && t !== r && 0 === (t & a) && ((a = r & -r) >= (o = t & -t) || 16 === a && 0 !== (4194240 & o)))
                    return t;
                if (0 !== (4 & r) && (r |= 16 & n),
                0 !== (t = e.entangledLanes))
                    for (e = e.entanglements,
                    t &= r; 0 < t; )
                        a = 1 << (n = 31 - it(t)),
                        r |= e[n],
                        t &= ~a;
                return r
            }
            function ft(e, t) {
                switch (e) {
                case 1:
                case 2:
                case 4:
                    return t + 250;
                case 8:
                case 16:
                case 32:
                case 64:
                case 128:
                case 256:
                case 512:
                case 1024:
                case 2048:
                case 4096:
                case 8192:
                case 16384:
                case 32768:
                case 65536:
                case 131072:
                case 262144:
                case 524288:
                case 1048576:
                case 2097152:
                    return t + 5e3;
                default:
                    return -1
                }
            }
            function mt(e) {
                return 0 !== (e = -1073741825 & e.pendingLanes) ? e : 1073741824 & e ? 1073741824 : 0
            }
            function ht() {
                var e = ut;
                return 0 === (4194240 & (ut <<= 1)) && (ut = 64),
                e
            }
            function gt(e) {
                for (var t = [], n = 0; 31 > n; n++)
                    t.push(e);
                return t
            }
            function vt(e, t, n) {
                e.pendingLanes |= t,
                536870912 !== t && (e.suspendedLanes = 0,
                e.pingedLanes = 0),
                (e = e.eventTimes)[t = 31 - it(t)] = n
            }
            function yt(e, t) {
                var n = e.entangledLanes |= t;
                for (e = e.entanglements; n; ) {
                    var r = 31 - it(n)
                      , a = 1 << r;
                    a & t | e[r] & t && (e[r] |= t),
                    n &= ~a
                }
            }
            var bt = 0;
            function xt(e) {
                return 1 < (e &= -e) ? 4 < e ? 0 !== (268435455 & e) ? 16 : 536870912 : 4 : 1
            }
            var wt, At, kt, St, Et, jt = !1, Nt = [], Ct = null, Rt = null, Ot = null, Tt = new Map, Lt = new Map, Ut = [], Pt = "mousedown mouseup touchcancel touchend touchstart auxclick dblclick pointercancel pointerdown pointerup dragend dragstart drop compositionend compositionstart keydown keypress keyup input textInput copy cut paste click change contextmenu reset submit".split(" ");
            function It(e, t) {
                switch (e) {
                case "focusin":
                case "focusout":
                    Ct = null;
                    break;
                case "dragenter":
                case "dragleave":
                    Rt = null;
                    break;
                case "mouseover":
                case "mouseout":
                    Ot = null;
                    break;
                case "pointerover":
                case "pointerout":
                    Tt.delete(t.pointerId);
                    break;
                case "gotpointercapture":
                case "lostpointercapture":
                    Lt.delete(t.pointerId)
                }
            }
            function Ft(e, t, n, r, a, o) {
                return null === e || e.nativeEvent !== o ? (e = {
                    blockedOn: t,
                    domEventName: n,
                    eventSystemFlags: r,
                    nativeEvent: o,
                    targetContainers: [a]
                },
                null !== t && (null !== (t = ba(t)) && At(t)),
                e) : (e.eventSystemFlags |= r,
                t = e.targetContainers,
                null !== a && -1 === t.indexOf(a) && t.push(a),
                e)
            }
            function zt(e) {
                var t = ya(e.target);
                if (null !== t) {
                    var n = He(t);
                    if (null !== n)
                        if (13 === (t = n.tag)) {
                            if (null !== (t = Qe(n)))
                                return e.blockedOn = t,
                                void Et(e.priority, (function() {
                                    kt(n)
                                }
                                ))
                        } else if (3 === t && n.stateNode.current.memoizedState.isDehydrated)
                            return void (e.blockedOn = 3 === n.tag ? n.stateNode.containerInfo : null)
                }
                e.blockedOn = null
            }
            function Mt(e) {
                if (null !== e.blockedOn)
                    return !1;
                for (var t = e.targetContainers; 0 < t.length; ) {
                    var n = Kt(e.domEventName, e.eventSystemFlags, t[0], e.nativeEvent);
                    if (null !== n)
                        return null !== (t = ba(n)) && At(t),
                        e.blockedOn = n,
                        !1;
                    var r = new (n = e.nativeEvent).constructor(n.type,n);
                    xe = r,
                    n.target.dispatchEvent(r),
                    xe = null,
                    t.shift()
                }
                return !0
            }
            function Bt(e, t, n) {
                Mt(e) && n.delete(t)
            }
            function qt() {
                jt = !1,
                null !== Ct && Mt(Ct) && (Ct = null),
                null !== Rt && Mt(Rt) && (Rt = null),
                null !== Ot && Mt(Ot) && (Ot = null),
                Tt.forEach(Bt),
                Lt.forEach(Bt)
            }
            function Dt(e, t) {
                e.blockedOn === t && (e.blockedOn = null,
                jt || (jt = !0,
                a.unstable_scheduleCallback(a.unstable_NormalPriority, qt)))
            }
            function Ht(e) {
                function t(t) {
                    return Dt(t, e)
                }
                if (0 < Nt.length) {
                    Dt(Nt[0], e);
                    for (var n = 1; n < Nt.length; n++) {
                        var r = Nt[n];
                        r.blockedOn === e && (r.blockedOn = null)
                    }
                }
                for (null !== Ct && Dt(Ct, e),
                null !== Rt && Dt(Rt, e),
                null !== Ot && Dt(Ot, e),
                Tt.forEach(t),
                Lt.forEach(t),
                n = 0; n < Ut.length; n++)
                    (r = Ut[n]).blockedOn === e && (r.blockedOn = null);
                for (; 0 < Ut.length && null === (n = Ut[0]).blockedOn; )
                    zt(n),
                    null === n.blockedOn && Ut.shift()
            }
            var Qt = x.ReactCurrentBatchConfig
              , Yt = !0;
            function Wt(e, t, n, r) {
                var a = bt
                  , o = Qt.transition;
                Qt.transition = null;
                try {
                    bt = 1,
                    Vt(e, t, n, r)
                } finally {
                    bt = a,
                    Qt.transition = o
                }
            }
            function Gt(e, t, n, r) {
                var a = bt
                  , o = Qt.transition;
                Qt.transition = null;
                try {
                    bt = 4,
                    Vt(e, t, n, r)
                } finally {
                    bt = a,
                    Qt.transition = o
                }
            }
            function Vt(e, t, n, r) {
                if (Yt) {
                    var a = Kt(e, t, n, r);
                    if (null === a)
                        Yr(e, t, r, Zt, n),
                        It(e, r);
                    else if (function(e, t, n, r, a) {
                        switch (t) {
                        case "focusin":
                            return Ct = Ft(Ct, e, t, n, r, a),
                            !0;
                        case "dragenter":
                            return Rt = Ft(Rt, e, t, n, r, a),
                            !0;
                        case "mouseover":
                            return Ot = Ft(Ot, e, t, n, r, a),
                            !0;
                        case "pointerover":
                            var o = a.pointerId;
                            return Tt.set(o, Ft(Tt.get(o) || null, e, t, n, r, a)),
                            !0;
                        case "gotpointercapture":
                            return o = a.pointerId,
                            Lt.set(o, Ft(Lt.get(o) || null, e, t, n, r, a)),
                            !0
                        }
                        return !1
                    }(a, e, t, n, r))
                        r.stopPropagation();
                    else if (It(e, r),
                    4 & t && -1 < Pt.indexOf(e)) {
                        for (; null !== a; ) {
                            var o = ba(a);
                            if (null !== o && wt(o),
                            null === (o = Kt(e, t, n, r)) && Yr(e, t, r, Zt, n),
                            o === a)
                                break;
                            a = o
                        }
                        null !== a && r.stopPropagation()
                    } else
                        Yr(e, t, r, null, n)
                }
            }
            var Zt = null;
            function Kt(e, t, n, r) {
                if (Zt = null,
                null !== (e = ya(e = we(r))))
                    if (null === (t = He(e)))
                        e = null;
                    else if (13 === (n = t.tag)) {
                        if (null !== (e = Qe(t)))
                            return e;
                        e = null
                    } else if (3 === n) {
                        if (t.stateNode.current.memoizedState.isDehydrated)
                            return 3 === t.tag ? t.stateNode.containerInfo : null;
                        e = null
                    } else
                        t !== e && (e = null);
                return Zt = e,
                null
            }
            function Jt(e) {
                switch (e) {
                case "cancel":
                case "click":
                case "close":
                case "contextmenu":
                case "copy":
                case "cut":
                case "auxclick":
                case "dblclick":
                case "dragend":
                case "dragstart":
                case "drop":
                case "focusin":
                case "focusout":
                case "input":
                case "invalid":
                case "keydown":
                case "keypress":
                case "keyup":
                case "mousedown":
                case "mouseup":
                case "paste":
                case "pause":
                case "play":
                case "pointercancel":
                case "pointerdown":
                case "pointerup":
                case "ratechange":
                case "reset":
                case "resize":
                case "seeked":
                case "submit":
                case "touchcancel":
                case "touchend":
                case "touchstart":
                case "volumechange":
                case "change":
                case "selectionchange":
                case "textInput":
                case "compositionstart":
                case "compositionend":
                case "compositionupdate":
                case "beforeblur":
                case "afterblur":
                case "beforeinput":
                case "blur":
                case "fullscreenchange":
                case "focus":
                case "hashchange":
                case "popstate":
                case "select":
                case "selectstart":
                    return 1;
                case "drag":
                case "dragenter":
                case "dragexit":
                case "dragleave":
                case "dragover":
                case "mousemove":
                case "mouseout":
                case "mouseover":
                case "pointermove":
                case "pointerout":
                case "pointerover":
                case "scroll":
                case "toggle":
                case "touchmove":
                case "wheel":
                case "mouseenter":
                case "mouseleave":
                case "pointerenter":
                case "pointerleave":
                    return 4;
                case "message":
                    switch (_e()) {
                    case $e:
                        return 1;
                    case et:
                        return 4;
                    case tt:
                    case nt:
                        return 16;
                    case rt:
                        return 536870912;
                    default:
                        return 16
                    }
                default:
                    return 16
                }
            }
            var Xt = null
              , _t = null
              , $t = null;
            function en() {
                if ($t)
                    return $t;
                var e, t, n = _t, r = n.length, a = "value"in Xt ? Xt.value : Xt.textContent, o = a.length;
                for (e = 0; e < r && n[e] === a[e]; e++)
                    ;
                var i = r - e;
                for (t = 1; t <= i && n[r - t] === a[o - t]; t++)
                    ;
                return $t = a.slice(e, 1 < t ? 1 - t : void 0)
            }
            function tn(e) {
                var t = e.keyCode;
                return "charCode"in e ? 0 === (e = e.charCode) && 13 === t && (e = 13) : e = t,
                10 === e && (e = 13),
                32 <= e || 13 === e ? e : 0
            }
            function nn() {
                return !0
            }
            function rn() {
                return !1
            }
            function an(e) {
                function t(t, n, r, a, o) {
                    for (var i in this._reactName = t,
                    this._targetInst = r,
                    this.type = n,
                    this.nativeEvent = a,
                    this.target = o,
                    this.currentTarget = null,
                    e)
                        e.hasOwnProperty(i) && (t = e[i],
                        this[i] = t ? t(a) : a[i]);
                    return this.isDefaultPrevented = (null != a.defaultPrevented ? a.defaultPrevented : !1 === a.returnValue) ? nn : rn,
                    this.isPropagationStopped = rn,
                    this
                }
                return z(t.prototype, {
                    preventDefault: function() {
                        this.defaultPrevented = !0;
                        var e = this.nativeEvent;
                        e && (e.preventDefault ? e.preventDefault() : "unknown" !== typeof e.returnValue && (e.returnValue = !1),
                        this.isDefaultPrevented = nn)
                    },
                    stopPropagation: function() {
                        var e = this.nativeEvent;
                        e && (e.stopPropagation ? e.stopPropagation() : "unknown" !== typeof e.cancelBubble && (e.cancelBubble = !0),
                        this.isPropagationStopped = nn)
                    },
                    persist: function() {},
                    isPersistent: nn
                }),
                t
            }
            var on, ln, sn, un = {
                eventPhase: 0,
                bubbles: 0,
                cancelable: 0,
                timeStamp: function(e) {
                    return e.timeStamp || Date.now()
                },
                defaultPrevented: 0,
                isTrusted: 0
            }, cn = an(un), dn = z({}, un, {
                view: 0,
                detail: 0
            }), pn = an(dn), fn = z({}, dn, {
                screenX: 0,
                screenY: 0,
                clientX: 0,
                clientY: 0,
                pageX: 0,
                pageY: 0,
                ctrlKey: 0,
                shiftKey: 0,
                altKey: 0,
                metaKey: 0,
                getModifierState: En,
                button: 0,
                buttons: 0,
                relatedTarget: function(e) {
                    return void 0 === e.relatedTarget ? e.fromElement === e.srcElement ? e.toElement : e.fromElement : e.relatedTarget
                },
                movementX: function(e) {
                    return "movementX"in e ? e.movementX : (e !== sn && (sn && "mousemove" === e.type ? (on = e.screenX - sn.screenX,
                    ln = e.screenY - sn.screenY) : ln = on = 0,
                    sn = e),
                    on)
                },
                movementY: function(e) {
                    return "movementY"in e ? e.movementY : ln
                }
            }), mn = an(fn), hn = an(z({}, fn, {
                dataTransfer: 0
            })), gn = an(z({}, dn, {
                relatedTarget: 0
            })), vn = an(z({}, un, {
                animationName: 0,
                elapsedTime: 0,
                pseudoElement: 0
            })), yn = z({}, un, {
                clipboardData: function(e) {
                    return "clipboardData"in e ? e.clipboardData : window.clipboardData
                }
            }), bn = an(yn), xn = an(z({}, un, {
                data: 0
            })), wn = {
                Esc: "Escape",
                Spacebar: " ",
                Left: "ArrowLeft",
                Up: "ArrowUp",
                Right: "ArrowRight",
                Down: "ArrowDown",
                Del: "Delete",
                Win: "OS",
                Menu: "ContextMenu",
                Apps: "ContextMenu",
                Scroll: "ScrollLock",
                MozPrintableKey: "Unidentified"
            }, An = {
                8: "Backspace",
                9: "Tab",
                12: "Clear",
                13: "Enter",
                16: "Shift",
                17: "Control",
                18: "Alt",
                19: "Pause",
                20: "CapsLock",
                27: "Escape",
                32: " ",
                33: "PageUp",
                34: "PageDown",
                35: "End",
                36: "Home",
                37: "ArrowLeft",
                38: "ArrowUp",
                39: "ArrowRight",
                40: "ArrowDown",
                45: "Insert",
                46: "Delete",
                112: "F1",
                113: "F2",
                114: "F3",
                115: "F4",
                116: "F5",
                117: "F6",
                118: "F7",
                119: "F8",
                120: "F9",
                121: "F10",
                122: "F11",
                123: "F12",
                144: "NumLock",
                145: "ScrollLock",
                224: "Meta"
            }, kn = {
                Alt: "altKey",
                Control: "ctrlKey",
                Meta: "metaKey",
                Shift: "shiftKey"
            };
            function Sn(e) {
                var t = this.nativeEvent;
                return t.getModifierState ? t.getModifierState(e) : !!(e = kn[e]) && !!t[e]
            }
            function En() {
                return Sn
            }
            var jn = z({}, dn, {
                key: function(e) {
                    if (e.key) {
                        var t = wn[e.key] || e.key;
                        if ("Unidentified" !== t)
                            return t
                    }
                    return "keypress" === e.type ? 13 === (e = tn(e)) ? "Enter" : String.fromCharCode(e) : "keydown" === e.type || "keyup" === e.type ? An[e.keyCode] || "Unidentified" : ""
                },
                code: 0,
                location: 0,
                ctrlKey: 0,
                shiftKey: 0,
                altKey: 0,
                metaKey: 0,
                repeat: 0,
                locale: 0,
                getModifierState: En,
                charCode: function(e) {
                    return "keypress" === e.type ? tn(e) : 0
                },
                keyCode: function(e) {
                    return "keydown" === e.type || "keyup" === e.type ? e.keyCode : 0
                },
                which: function(e) {
                    return "keypress" === e.type ? tn(e) : "keydown" === e.type || "keyup" === e.type ? e.keyCode : 0
                }
            })
              , Nn = an(jn)
              , Cn = an(z({}, fn, {
                pointerId: 0,
                width: 0,
                height: 0,
                pressure: 0,
                tangentialPressure: 0,
                tiltX: 0,
                tiltY: 0,
                twist: 0,
                pointerType: 0,
                isPrimary: 0
            }))
              , Rn = an(z({}, dn, {
                touches: 0,
                targetTouches: 0,
                changedTouches: 0,
                altKey: 0,
                metaKey: 0,
                ctrlKey: 0,
                shiftKey: 0,
                getModifierState: En
            }))
              , On = an(z({}, un, {
                propertyName: 0,
                elapsedTime: 0,
                pseudoElement: 0
            }))
              , Tn = z({}, fn, {
                deltaX: function(e) {
                    return "deltaX"in e ? e.deltaX : "wheelDeltaX"in e ? -e.wheelDeltaX : 0
                },
                deltaY: function(e) {
                    return "deltaY"in e ? e.deltaY : "wheelDeltaY"in e ? -e.wheelDeltaY : "wheelDelta"in e ? -e.wheelDelta : 0
                },
                deltaZ: 0,
                deltaMode: 0
            })
              , Ln = an(Tn)
              , Un = [9, 13, 27, 32]
              , Pn = c && "CompositionEvent"in window
              , In = null;
            c && "documentMode"in document && (In = document.documentMode);
            var Fn = c && "TextEvent"in window && !In
              , zn = c && (!Pn || In && 8 < In && 11 >= In)
              , Mn = String.fromCharCode(32)
              , Bn = !1;
            function qn(e, t) {
                switch (e) {
                case "keyup":
                    return -1 !== Un.indexOf(t.keyCode);
                case "keydown":
                    return 229 !== t.keyCode;
                case "keypress":
                case "mousedown":
                case "focusout":
                    return !0;
                default:
                    return !1
                }
            }
            function Dn(e) {
                return "object" === typeof (e = e.detail) && "data"in e ? e.data : null
            }
            var Hn = !1;
            var Qn = {
                color: !0,
                date: !0,
                datetime: !0,
                "datetime-local": !0,
                email: !0,
                month: !0,
                number: !0,
                password: !0,
                range: !0,
                search: !0,
                tel: !0,
                text: !0,
                time: !0,
                url: !0,
                week: !0
            };
            function Yn(e) {
                var t = e && e.nodeName && e.nodeName.toLowerCase();
                return "input" === t ? !!Qn[e.type] : "textarea" === t
            }
            function Wn(e, t, n, r) {
                je(r),
                0 < (t = Gr(t, "onChange")).length && (n = new cn("onChange","change",null,n,r),
                e.push({
                    event: n,
                    listeners: t
                }))
            }
            var Gn = null
              , Vn = null;
            function Zn(e) {
                Mr(e, 0)
            }
            function Kn(e) {
                if (V(xa(e)))
                    return e
            }
            function Jn(e, t) {
                if ("change" === e)
                    return t
            }
            var Xn = !1;
            if (c) {
                var _n;
                if (c) {
                    var $n = "oninput"in document;
                    if (!$n) {
                        var er = document.createElement("div");
                        er.setAttribute("oninput", "return;"),
                        $n = "function" === typeof er.oninput
                    }
                    _n = $n
                } else
                    _n = !1;
                Xn = _n && (!document.documentMode || 9 < document.documentMode)
            }
            function tr() {
                Gn && (Gn.detachEvent("onpropertychange", nr),
                Vn = Gn = null)
            }
            function nr(e) {
                if ("value" === e.propertyName && Kn(Vn)) {
                    var t = [];
                    Wn(t, Vn, e, we(e)),
                    Te(Zn, t)
                }
            }
            function rr(e, t, n) {
                "focusin" === e ? (tr(),
                Vn = n,
                (Gn = t).attachEvent("onpropertychange", nr)) : "focusout" === e && tr()
            }
            function ar(e) {
                if ("selectionchange" === e || "keyup" === e || "keydown" === e)
                    return Kn(Vn)
            }
            function or(e, t) {
                if ("click" === e)
                    return Kn(t)
            }
            function ir(e, t) {
                if ("input" === e || "change" === e)
                    return Kn(t)
            }
            var lr = "function" === typeof Object.is ? Object.is : function(e, t) {
                return e === t && (0 !== e || 1 / e === 1 / t) || e !== e && t !== t
            }
            ;
            function sr(e, t) {
                if (lr(e, t))
                    return !0;
                if ("object" !== typeof e || null === e || "object" !== typeof t || null === t)
                    return !1;
                var n = Object.keys(e)
                  , r = Object.keys(t);
                if (n.length !== r.length)
                    return !1;
                for (r = 0; r < n.length; r++) {
                    var a = n[r];
                    if (!d.call(t, a) || !lr(e[a], t[a]))
                        return !1
                }
                return !0
            }
            function ur(e) {
                for (; e && e.firstChild; )
                    e = e.firstChild;
                return e
            }
            function cr(e, t) {
                var n, r = ur(e);
                for (e = 0; r; ) {
                    if (3 === r.nodeType) {
                        if (n = e + r.textContent.length,
                        e <= t && n >= t)
                            return {
                                node: r,
                                offset: t - e
                            };
                        e = n
                    }
                    e: {
                        for (; r; ) {
                            if (r.nextSibling) {
                                r = r.nextSibling;
                                break e
                            }
                            r = r.parentNode
                        }
                        r = void 0
                    }
                    r = ur(r)
                }
            }
            function dr(e, t) {
                return !(!e || !t) && (e === t || (!e || 3 !== e.nodeType) && (t && 3 === t.nodeType ? dr(e, t.parentNode) : "contains"in e ? e.contains(t) : !!e.compareDocumentPosition && !!(16 & e.compareDocumentPosition(t))))
            }
            function pr() {
                for (var e = window, t = Z(); t instanceof e.HTMLIFrameElement; ) {
                    try {
                        var n = "string" === typeof t.contentWindow.location.href
                    } catch (r) {
                        n = !1
                    }
                    if (!n)
                        break;
                    t = Z((e = t.contentWindow).document)
                }
                return t
            }
            function fr(e) {
                var t = e && e.nodeName && e.nodeName.toLowerCase();
                return t && ("input" === t && ("text" === e.type || "search" === e.type || "tel" === e.type || "url" === e.type || "password" === e.type) || "textarea" === t || "true" === e.contentEditable)
            }
            function mr(e) {
                var t = pr()
                  , n = e.focusedElem
                  , r = e.selectionRange;
                if (t !== n && n && n.ownerDocument && dr(n.ownerDocument.documentElement, n)) {
                    if (null !== r && fr(n))
                        if (t = r.start,
                        void 0 === (e = r.end) && (e = t),
                        "selectionStart"in n)
                            n.selectionStart = t,
                            n.selectionEnd = Math.min(e, n.value.length);
                        else if ((e = (t = n.ownerDocument || document) && t.defaultView || window).getSelection) {
                            e = e.getSelection();
                            var a = n.textContent.length
                              , o = Math.min(r.start, a);
                            r = void 0 === r.end ? o : Math.min(r.end, a),
                            !e.extend && o > r && (a = r,
                            r = o,
                            o = a),
                            a = cr(n, o);
                            var i = cr(n, r);
                            a && i && (1 !== e.rangeCount || e.anchorNode !== a.node || e.anchorOffset !== a.offset || e.focusNode !== i.node || e.focusOffset !== i.offset) && ((t = t.createRange()).setStart(a.node, a.offset),
                            e.removeAllRanges(),
                            o > r ? (e.addRange(t),
                            e.extend(i.node, i.offset)) : (t.setEnd(i.node, i.offset),
                            e.addRange(t)))
                        }
                    for (t = [],
                    e = n; e = e.parentNode; )
                        1 === e.nodeType && t.push({
                            element: e,
                            left: e.scrollLeft,
                            top: e.scrollTop
                        });
                    for ("function" === typeof n.focus && n.focus(),
                    n = 0; n < t.length; n++)
                        (e = t[n]).element.scrollLeft = e.left,
                        e.element.scrollTop = e.top
                }
            }
            var hr = c && "documentMode"in document && 11 >= document.documentMode
              , gr = null
              , vr = null
              , yr = null
              , br = !1;
            function xr(e, t, n) {
                var r = n.window === n ? n.document : 9 === n.nodeType ? n : n.ownerDocument;
                br || null == gr || gr !== Z(r) || ("selectionStart"in (r = gr) && fr(r) ? r = {
                    start: r.selectionStart,
                    end: r.selectionEnd
                } : r = {
                    anchorNode: (r = (r.ownerDocument && r.ownerDocument.defaultView || window).getSelection()).anchorNode,
                    anchorOffset: r.anchorOffset,
                    focusNode: r.focusNode,
                    focusOffset: r.focusOffset
                },
                yr && sr(yr, r) || (yr = r,
                0 < (r = Gr(vr, "onSelect")).length && (t = new cn("onSelect","select",null,t,n),
                e.push({
                    event: t,
                    listeners: r
                }),
                t.target = gr)))
            }
            function wr(e, t) {
                var n = {};
                return n[e.toLowerCase()] = t.toLowerCase(),
                n["Webkit" + e] = "webkit" + t,
                n["Moz" + e] = "moz" + t,
                n
            }
            var Ar = {
                animationend: wr("Animation", "AnimationEnd"),
                animationiteration: wr("Animation", "AnimationIteration"),
                animationstart: wr("Animation", "AnimationStart"),
                transitionend: wr("Transition", "TransitionEnd")
            }
              , kr = {}
              , Sr = {};
            function Er(e) {
                if (kr[e])
                    return kr[e];
                if (!Ar[e])
                    return e;
                var t, n = Ar[e];
                for (t in n)
                    if (n.hasOwnProperty(t) && t in Sr)
                        return kr[e] = n[t];
                return e
            }
            c && (Sr = document.createElement("div").style,
            "AnimationEvent"in window || (delete Ar.animationend.animation,
            delete Ar.animationiteration.animation,
            delete Ar.animationstart.animation),
            "TransitionEvent"in window || delete Ar.transitionend.transition);
            var jr = Er("animationend")
              , Nr = Er("animationiteration")
              , Cr = Er("animationstart")
              , Rr = Er("transitionend")
              , Or = new Map
              , Tr = "abort auxClick cancel canPlay canPlayThrough click close contextMenu copy cut drag dragEnd dragEnter dragExit dragLeave dragOver dragStart drop durationChange emptied encrypted ended error gotPointerCapture input invalid keyDown keyPress keyUp load loadedData loadedMetadata loadStart lostPointerCapture mouseDown mouseMove mouseOut mouseOver mouseUp paste pause play playing pointerCancel pointerDown pointerMove pointerOut pointerOver pointerUp progress rateChange reset resize seeked seeking stalled submit suspend timeUpdate touchCancel touchEnd touchStart volumeChange scroll toggle touchMove waiting wheel".split(" ");
            function Lr(e, t) {
                Or.set(e, t),
                s(t, [e])
            }
            for (var Ur = 0; Ur < Tr.length; Ur++) {
                var Pr = Tr[Ur];
                Lr(Pr.toLowerCase(), "on" + (Pr[0].toUpperCase() + Pr.slice(1)))
            }
            Lr(jr, "onAnimationEnd"),
            Lr(Nr, "onAnimationIteration"),
            Lr(Cr, "onAnimationStart"),
            Lr("dblclick", "onDoubleClick"),
            Lr("focusin", "onFocus"),
            Lr("focusout", "onBlur"),
            Lr(Rr, "onTransitionEnd"),
            u("onMouseEnter", ["mouseout", "mouseover"]),
            u("onMouseLeave", ["mouseout", "mouseover"]),
            u("onPointerEnter", ["pointerout", "pointerover"]),
            u("onPointerLeave", ["pointerout", "pointerover"]),
            s("onChange", "change click focusin focusout input keydown keyup selectionchange".split(" ")),
            s("onSelect", "focusout contextmenu dragend focusin keydown keyup mousedown mouseup selectionchange".split(" ")),
            s("onBeforeInput", ["compositionend", "keypress", "textInput", "paste"]),
            s("onCompositionEnd", "compositionend focusout keydown keypress keyup mousedown".split(" ")),
            s("onCompositionStart", "compositionstart focusout keydown keypress keyup mousedown".split(" ")),
            s("onCompositionUpdate", "compositionupdate focusout keydown keypress keyup mousedown".split(" "));
            var Ir = "abort canplay canplaythrough durationchange emptied encrypted ended error loadeddata loadedmetadata loadstart pause play playing progress ratechange resize seeked seeking stalled suspend timeupdate volumechange waiting".split(" ")
              , Fr = new Set("cancel close invalid load scroll toggle".split(" ").concat(Ir));
            function zr(e, t, n) {
                var r = e.type || "unknown-event";
                e.currentTarget = n,
                function(e, t, n, r, a, i, l, s, u) {
                    if (De.apply(this, arguments),
                    Fe) {
                        if (!Fe)
                            throw Error(o(198));
                        var c = ze;
                        Fe = !1,
                        ze = null,
                        Me || (Me = !0,
                        Be = c)
                    }
                }(r, t, void 0, e),
                e.currentTarget = null
            }
            function Mr(e, t) {
                t = 0 !== (4 & t);
                for (var n = 0; n < e.length; n++) {
                    var r = e[n]
                      , a = r.event;
                    r = r.listeners;
                    e: {
                        var o = void 0;
                        if (t)
                            for (var i = r.length - 1; 0 <= i; i--) {
                                var l = r[i]
                                  , s = l.instance
                                  , u = l.currentTarget;
                                if (l = l.listener,
                                s !== o && a.isPropagationStopped())
                                    break e;
                                zr(a, l, u),
                                o = s
                            }
                        else
                            for (i = 0; i < r.length; i++) {
                                if (s = (l = r[i]).instance,
                                u = l.currentTarget,
                                l = l.listener,
                                s !== o && a.isPropagationStopped())
                                    break e;
                                zr(a, l, u),
                                o = s
                            }
                    }
                }
                if (Me)
                    throw e = Be,
                    Me = !1,
                    Be = null,
                    e
            }
            function Br(e, t) {
                var n = t[ha];
                void 0 === n && (n = t[ha] = new Set);
                var r = e + "__bubble";
                n.has(r) || (Qr(t, e, 2, !1),
                n.add(r))
            }
            function qr(e, t, n) {
                var r = 0;
                t && (r |= 4),
                Qr(n, e, r, t)
            }
            var Dr = "_reactListening" + Math.random().toString(36).slice(2);
            function Hr(e) {
                if (!e[Dr]) {
                    e[Dr] = !0,
                    i.forEach((function(t) {
                        "selectionchange" !== t && (Fr.has(t) || qr(t, !1, e),
                        qr(t, !0, e))
                    }
                    ));
                    var t = 9 === e.nodeType ? e : e.ownerDocument;
                    null === t || t[Dr] || (t[Dr] = !0,
                    qr("selectionchange", !1, t))
                }
            }
            function Qr(e, t, n, r) {
                switch (Jt(t)) {
                case 1:
                    var a = Wt;
                    break;
                case 4:
                    a = Gt;
                    break;
                default:
                    a = Vt
                }
                n = a.bind(null, t, n, e),
                a = void 0,
                !Ue || "touchstart" !== t && "touchmove" !== t && "wheel" !== t || (a = !0),
                r ? void 0 !== a ? e.addEventListener(t, n, {
                    capture: !0,
                    passive: a
                }) : e.addEventListener(t, n, !0) : void 0 !== a ? e.addEventListener(t, n, {
                    passive: a
                }) : e.addEventListener(t, n, !1)
            }
            function Yr(e, t, n, r, a) {
                var o = r;
                if (0 === (1 & t) && 0 === (2 & t) && null !== r)
                    e: for (; ; ) {
                        if (null === r)
                            return;
                        var i = r.tag;
                        if (3 === i || 4 === i) {
                            var l = r.stateNode.containerInfo;
                            if (l === a || 8 === l.nodeType && l.parentNode === a)
                                break;
                            if (4 === i)
                                for (i = r.return; null !== i; ) {
                                    var s = i.tag;
                                    if ((3 === s || 4 === s) && ((s = i.stateNode.containerInfo) === a || 8 === s.nodeType && s.parentNode === a))
                                        return;
                                    i = i.return
                                }
                            for (; null !== l; ) {
                                if (null === (i = ya(l)))
                                    return;
                                if (5 === (s = i.tag) || 6 === s) {
                                    r = o = i;
                                    continue e
                                }
                                l = l.parentNode
                            }
                        }
                        r = r.return
                    }
                Te((function() {
                    var r = o
                      , a = we(n)
                      , i = [];
                    e: {
                        var l = Or.get(e);
                        if (void 0 !== l) {
                            var s = cn
                              , u = e;
                            switch (e) {
                            case "keypress":
                                if (0 === tn(n))
                                    break e;
                            case "keydown":
                            case "keyup":
                                s = Nn;
                                break;
                            case "focusin":
                                u = "focus",
                                s = gn;
                                break;
                            case "focusout":
                                u = "blur",
                                s = gn;
                                break;
                            case "beforeblur":
                            case "afterblur":
                                s = gn;
                                break;
                            case "click":
                                if (2 === n.button)
                                    break e;
                            case "auxclick":
                            case "dblclick":
                            case "mousedown":
                            case "mousemove":
                            case "mouseup":
                            case "mouseout":
                            case "mouseover":
                            case "contextmenu":
                                s = mn;
                                break;
                            case "drag":
                            case "dragend":
                            case "dragenter":
                            case "dragexit":
                            case "dragleave":
                            case "dragover":
                            case "dragstart":
                            case "drop":
                                s = hn;
                                break;
                            case "touchcancel":
                            case "touchend":
                            case "touchmove":
                            case "touchstart":
                                s = Rn;
                                break;
                            case jr:
                            case Nr:
                            case Cr:
                                s = vn;
                                break;
                            case Rr:
                                s = On;
                                break;
                            case "scroll":
                                s = pn;
                                break;
                            case "wheel":
                                s = Ln;
                                break;
                            case "copy":
                            case "cut":
                            case "paste":
                                s = bn;
                                break;
                            case "gotpointercapture":
                            case "lostpointercapture":
                            case "pointercancel":
                            case "pointerdown":
                            case "pointermove":
                            case "pointerout":
                            case "pointerover":
                            case "pointerup":
                                s = Cn
                            }
                            var c = 0 !== (4 & t)
                              , d = !c && "scroll" === e
                              , p = c ? null !== l ? l + "Capture" : null : l;
                            c = [];
                            for (var f, m = r; null !== m; ) {
                                var h = (f = m).stateNode;
                                if (5 === f.tag && null !== h && (f = h,
                                null !== p && (null != (h = Le(m, p)) && c.push(Wr(m, h, f)))),
                                d)
                                    break;
                                m = m.return
                            }
                            0 < c.length && (l = new s(l,u,null,n,a),
                            i.push({
                                event: l,
                                listeners: c
                            }))
                        }
                    }
                    if (0 === (7 & t)) {
                        if (s = "mouseout" === e || "pointerout" === e,
                        (!(l = "mouseover" === e || "pointerover" === e) || n === xe || !(u = n.relatedTarget || n.fromElement) || !ya(u) && !u[ma]) && (s || l) && (l = a.window === a ? a : (l = a.ownerDocument) ? l.defaultView || l.parentWindow : window,
                        s ? (s = r,
                        null !== (u = (u = n.relatedTarget || n.toElement) ? ya(u) : null) && (u !== (d = He(u)) || 5 !== u.tag && 6 !== u.tag) && (u = null)) : (s = null,
                        u = r),
                        s !== u)) {
                            if (c = mn,
                            h = "onMouseLeave",
                            p = "onMouseEnter",
                            m = "mouse",
                            "pointerout" !== e && "pointerover" !== e || (c = Cn,
                            h = "onPointerLeave",
                            p = "onPointerEnter",
                            m = "pointer"),
                            d = null == s ? l : xa(s),
                            f = null == u ? l : xa(u),
                            (l = new c(h,m + "leave",s,n,a)).target = d,
                            l.relatedTarget = f,
                            h = null,
                            ya(a) === r && ((c = new c(p,m + "enter",u,n,a)).target = f,
                            c.relatedTarget = d,
                            h = c),
                            d = h,
                            s && u)
                                e: {
                                    for (p = u,
                                    m = 0,
                                    f = c = s; f; f = Vr(f))
                                        m++;
                                    for (f = 0,
                                    h = p; h; h = Vr(h))
                                        f++;
                                    for (; 0 < m - f; )
                                        c = Vr(c),
                                        m--;
                                    for (; 0 < f - m; )
                                        p = Vr(p),
                                        f--;
                                    for (; m--; ) {
                                        if (c === p || null !== p && c === p.alternate)
                                            break e;
                                        c = Vr(c),
                                        p = Vr(p)
                                    }
                                    c = null
                                }
                            else
                                c = null;
                            null !== s && Zr(i, l, s, c, !1),
                            null !== u && null !== d && Zr(i, d, u, c, !0)
                        }
                        if ("select" === (s = (l = r ? xa(r) : window).nodeName && l.nodeName.toLowerCase()) || "input" === s && "file" === l.type)
                            var g = Jn;
                        else if (Yn(l))
                            if (Xn)
                                g = ir;
                            else {
                                g = ar;
                                var v = rr
                            }
                        else
                            (s = l.nodeName) && "input" === s.toLowerCase() && ("checkbox" === l.type || "radio" === l.type) && (g = or);
                        switch (g && (g = g(e, r)) ? Wn(i, g, n, a) : (v && v(e, l, r),
                        "focusout" === e && (v = l._wrapperState) && v.controlled && "number" === l.type && ee(l, "number", l.value)),
                        v = r ? xa(r) : window,
                        e) {
                        case "focusin":
                            (Yn(v) || "true" === v.contentEditable) && (gr = v,
                            vr = r,
                            yr = null);
                            break;
                        case "focusout":
                            yr = vr = gr = null;
                            break;
                        case "mousedown":
                            br = !0;
                            break;
                        case "contextmenu":
                        case "mouseup":
                        case "dragend":
                            br = !1,
                            xr(i, n, a);
                            break;
                        case "selectionchange":
                            if (hr)
                                break;
                        case "keydown":
                        case "keyup":
                            xr(i, n, a)
                        }
                        var y;
                        if (Pn)
                            e: {
                                switch (e) {
                                case "compositionstart":
                                    var b = "onCompositionStart";
                                    break e;
                                case "compositionend":
                                    b = "onCompositionEnd";
                                    break e;
                                case "compositionupdate":
                                    b = "onCompositionUpdate";
                                    break e
                                }
                                b = void 0
                            }
                        else
                            Hn ? qn(e, n) && (b = "onCompositionEnd") : "keydown" === e && 229 === n.keyCode && (b = "onCompositionStart");
                        b && (zn && "ko" !== n.locale && (Hn || "onCompositionStart" !== b ? "onCompositionEnd" === b && Hn && (y = en()) : (_t = "value"in (Xt = a) ? Xt.value : Xt.textContent,
                        Hn = !0)),
                        0 < (v = Gr(r, b)).length && (b = new xn(b,e,null,n,a),
                        i.push({
                            event: b,
                            listeners: v
                        }),
                        y ? b.data = y : null !== (y = Dn(n)) && (b.data = y))),
                        (y = Fn ? function(e, t) {
                            switch (e) {
                            case "compositionend":
                                return Dn(t);
                            case "keypress":
                                return 32 !== t.which ? null : (Bn = !0,
                                Mn);
                            case "textInput":
                                return (e = t.data) === Mn && Bn ? null : e;
                            default:
                                return null
                            }
                        }(e, n) : function(e, t) {
                            if (Hn)
                                return "compositionend" === e || !Pn && qn(e, t) ? (e = en(),
                                $t = _t = Xt = null,
                                Hn = !1,
                                e) : null;
                            switch (e) {
                            case "paste":
                            default:
                                return null;
                            case "keypress":
                                if (!(t.ctrlKey || t.altKey || t.metaKey) || t.ctrlKey && t.altKey) {
                                    if (t.char && 1 < t.char.length)
                                        return t.char;
                                    if (t.which)
                                        return String.fromCharCode(t.which)
                                }
                                return null;
                            case "compositionend":
                                return zn && "ko" !== t.locale ? null : t.data
                            }
                        }(e, n)) && (0 < (r = Gr(r, "onBeforeInput")).length && (a = new xn("onBeforeInput","beforeinput",null,n,a),
                        i.push({
                            event: a,
                            listeners: r
                        }),
                        a.data = y))
                    }
                    Mr(i, t)
                }
                ))
            }
            function Wr(e, t, n) {
                return {
                    instance: e,
                    listener: t,
                    currentTarget: n
                }
            }
            function Gr(e, t) {
                for (var n = t + "Capture", r = []; null !== e; ) {
                    var a = e
                      , o = a.stateNode;
                    5 === a.tag && null !== o && (a = o,
                    null != (o = Le(e, n)) && r.unshift(Wr(e, o, a)),
                    null != (o = Le(e, t)) && r.push(Wr(e, o, a))),
                    e = e.return
                }
                return r
            }
            function Vr(e) {
                if (null === e)
                    return null;
                do {
                    e = e.return
                } while (e && 5 !== e.tag);
                return e || null
            }
            function Zr(e, t, n, r, a) {
                for (var o = t._reactName, i = []; null !== n && n !== r; ) {
                    var l = n
                      , s = l.alternate
                      , u = l.stateNode;
                    if (null !== s && s === r)
                        break;
                    5 === l.tag && null !== u && (l = u,
                    a ? null != (s = Le(n, o)) && i.unshift(Wr(n, s, l)) : a || null != (s = Le(n, o)) && i.push(Wr(n, s, l))),
                    n = n.return
                }
                0 !== i.length && e.push({
                    event: t,
                    listeners: i
                })
            }
            var Kr = /\r\n?/g
              , Jr = /\u0000|\uFFFD/g;
            function Xr(e) {
                return ("string" === typeof e ? e : "" + e).replace(Kr, "\n").replace(Jr, "")
            }
            function _r(e, t, n) {
                if (t = Xr(t),
                Xr(e) !== t && n)
                    throw Error(o(425))
            }
            function $r() {}
            var ea = null
              , ta = null;
            function na(e, t) {
                return "textarea" === e || "noscript" === e || "string" === typeof t.children || "number" === typeof t.children || "object" === typeof t.dangerouslySetInnerHTML && null !== t.dangerouslySetInnerHTML && null != t.dangerouslySetInnerHTML.__html
            }
            var ra = "function" === typeof setTimeout ? setTimeout : void 0
              , aa = "function" === typeof clearTimeout ? clearTimeout : void 0
              , oa = "function" === typeof Promise ? Promise : void 0
              , ia = "function" === typeof queueMicrotask ? queueMicrotask : "undefined" !== typeof oa ? function(e) {
                return oa.resolve(null).then(e).catch(la)
            }
            : ra;
            function la(e) {
                setTimeout((function() {
                    throw e
                }
                ))
            }
            function sa(e, t) {
                var n = t
                  , r = 0;
                do {
                    var a = n.nextSibling;
                    if (e.removeChild(n),
                    a && 8 === a.nodeType)
                        if ("/$" === (n = a.data)) {
                            if (0 === r)
                                return e.removeChild(a),
                                void Ht(t);
                            r--
                        } else
                            "$" !== n && "$?" !== n && "$!" !== n || r++;
                    n = a
                } while (n);
                Ht(t)
            }
            function ua(e) {
                for (; null != e; e = e.nextSibling) {
                    var t = e.nodeType;
                    if (1 === t || 3 === t)
                        break;
                    if (8 === t) {
                        if ("$" === (t = e.data) || "$!" === t || "$?" === t)
                            break;
                        if ("/$" === t)
                            return null
                    }
                }
                return e
            }
            function ca(e) {
                e = e.previousSibling;
                for (var t = 0; e; ) {
                    if (8 === e.nodeType) {
                        var n = e.data;
                        if ("$" === n || "$!" === n || "$?" === n) {
                            if (0 === t)
                                return e;
                            t--
                        } else
                            "/$" === n && t++
                    }
                    e = e.previousSibling
                }
                return null
            }
            var da = Math.random().toString(36).slice(2)
              , pa = "__reactFiber$" + da
              , fa = "__reactProps$" + da
              , ma = "__reactContainer$" + da
              , ha = "__reactEvents$" + da
              , ga = "__reactListeners$" + da
              , va = "__reactHandles$" + da;
            function ya(e) {
                var t = e[pa];
                if (t)
                    return t;
                for (var n = e.parentNode; n; ) {
                    if (t = n[ma] || n[pa]) {
                        if (n = t.alternate,
                        null !== t.child || null !== n && null !== n.child)
                            for (e = ca(e); null !== e; ) {
                                if (n = e[pa])
                                    return n;
                                e = ca(e)
                            }
                        return t
                    }
                    n = (e = n).parentNode
                }
                return null
            }
            function ba(e) {
                return !(e = e[pa] || e[ma]) || 5 !== e.tag && 6 !== e.tag && 13 !== e.tag && 3 !== e.tag ? null : e
            }
            function xa(e) {
                if (5 === e.tag || 6 === e.tag)
                    return e.stateNode;
                throw Error(o(33))
            }
            function wa(e) {
                return e[fa] || null
            }
            var Aa = []
              , ka = -1;
            function Sa(e) {
                return {
                    current: e
                }
            }
            function Ea(e) {
                0 > ka || (e.current = Aa[ka],
                Aa[ka] = null,
                ka--)
            }
            function ja(e, t) {
                ka++,
                Aa[ka] = e.current,
                e.current = t
            }
            var Na = {}
              , Ca = Sa(Na)
              , Ra = Sa(!1)
              , Oa = Na;
            function Ta(e, t) {
                var n = e.type.contextTypes;
                if (!n)
                    return Na;
                var r = e.stateNode;
                if (r && r.__reactInternalMemoizedUnmaskedChildContext === t)
                    return r.__reactInternalMemoizedMaskedChildContext;
                var a, o = {};
                for (a in n)
                    o[a] = t[a];
                return r && ((e = e.stateNode).__reactInternalMemoizedUnmaskedChildContext = t,
                e.__reactInternalMemoizedMaskedChildContext = o),
                o
            }
            function La(e) {
                return null !== (e = e.childContextTypes) && void 0 !== e
            }
            function Ua() {
                Ea(Ra),
                Ea(Ca)
            }
            function Pa(e, t, n) {
                if (Ca.current !== Na)
                    throw Error(o(168));
                ja(Ca, t),
                ja(Ra, n)
            }
            function Ia(e, t, n) {
                var r = e.stateNode;
                if (t = t.childContextTypes,
                "function" !== typeof r.getChildContext)
                    return n;
                for (var a in r = r.getChildContext())
                    if (!(a in t))
                        throw Error(o(108, Q(e) || "Unknown", a));
                return z({}, n, r)
            }
            function Fa(e) {
                return e = (e = e.stateNode) && e.__reactInternalMemoizedMergedChildContext || Na,
                Oa = Ca.current,
                ja(Ca, e),
                ja(Ra, Ra.current),
                !0
            }
            function za(e, t, n) {
                var r = e.stateNode;
                if (!r)
                    throw Error(o(169));
                n ? (e = Ia(e, t, Oa),
                r.__reactInternalMemoizedMergedChildContext = e,
                Ea(Ra),
                Ea(Ca),
                ja(Ca, e)) : Ea(Ra),
                ja(Ra, n)
            }
            var Ma = null
              , Ba = !1
              , qa = !1;
            function Da(e) {
                null === Ma ? Ma = [e] : Ma.push(e)
            }
            function Ha() {
                if (!qa && null !== Ma) {
                    qa = !0;
                    var e = 0
                      , t = bt;
                    try {
                        var n = Ma;
                        for (bt = 1; e < n.length; e++) {
                            var r = n[e];
                            do {
                                r = r(!0)
                            } while (null !== r)
                        }
                        Ma = null,
                        Ba = !1
                    } catch (a) {
                        throw null !== Ma && (Ma = Ma.slice(e + 1)),
                        Ve($e, Ha),
                        a
                    } finally {
                        bt = t,
                        qa = !1
                    }
                }
                return null
            }
            var Qa = []
              , Ya = 0
              , Wa = null
              , Ga = 0
              , Va = []
              , Za = 0
              , Ka = null
              , Ja = 1
              , Xa = "";
            function _a(e, t) {
                Qa[Ya++] = Ga,
                Qa[Ya++] = Wa,
                Wa = e,
                Ga = t
            }
            function $a(e, t, n) {
                Va[Za++] = Ja,
                Va[Za++] = Xa,
                Va[Za++] = Ka,
                Ka = e;
                var r = Ja;
                e = Xa;
                var a = 32 - it(r) - 1;
                r &= ~(1 << a),
                n += 1;
                var o = 32 - it(t) + a;
                if (30 < o) {
                    var i = a - a % 5;
                    o = (r & (1 << i) - 1).toString(32),
                    r >>= i,
                    a -= i,
                    Ja = 1 << 32 - it(t) + a | n << a | r,
                    Xa = o + e
                } else
                    Ja = 1 << o | n << a | r,
                    Xa = e
            }
            function eo(e) {
                null !== e.return && (_a(e, 1),
                $a(e, 1, 0))
            }
            function to(e) {
                for (; e === Wa; )
                    Wa = Qa[--Ya],
                    Qa[Ya] = null,
                    Ga = Qa[--Ya],
                    Qa[Ya] = null;
                for (; e === Ka; )
                    Ka = Va[--Za],
                    Va[Za] = null,
                    Xa = Va[--Za],
                    Va[Za] = null,
                    Ja = Va[--Za],
                    Va[Za] = null
            }
            var no = null
              , ro = null
              , ao = !1
              , oo = null;
            function io(e, t) {
                var n = Tu(5, null, null, 0);
                n.elementType = "DELETED",
                n.stateNode = t,
                n.return = e,
                null === (t = e.deletions) ? (e.deletions = [n],
                e.flags |= 16) : t.push(n)
            }
            function lo(e, t) {
                switch (e.tag) {
                case 5:
                    var n = e.type;
                    return null !== (t = 1 !== t.nodeType || n.toLowerCase() !== t.nodeName.toLowerCase() ? null : t) && (e.stateNode = t,
                    no = e,
                    ro = ua(t.firstChild),
                    !0);
                case 6:
                    return null !== (t = "" === e.pendingProps || 3 !== t.nodeType ? null : t) && (e.stateNode = t,
                    no = e,
                    ro = null,
                    !0);
                case 13:
                    return null !== (t = 8 !== t.nodeType ? null : t) && (n = null !== Ka ? {
                        id: Ja,
                        overflow: Xa
                    } : null,
                    e.memoizedState = {
                        dehydrated: t,
                        treeContext: n,
                        retryLane: 1073741824
                    },
                    (n = Tu(18, null, null, 0)).stateNode = t,
                    n.return = e,
                    e.child = n,
                    no = e,
                    ro = null,
                    !0);
                default:
                    return !1
                }
            }
            function so(e) {
                return 0 !== (1 & e.mode) && 0 === (128 & e.flags)
            }
            function uo(e) {
                if (ao) {
                    var t = ro;
                    if (t) {
                        var n = t;
                        if (!lo(e, t)) {
                            if (so(e))
                                throw Error(o(418));
                            t = ua(n.nextSibling);
                            var r = no;
                            t && lo(e, t) ? io(r, n) : (e.flags = -4097 & e.flags | 2,
                            ao = !1,
                            no = e)
                        }
                    } else {
                        if (so(e))
                            throw Error(o(418));
                        e.flags = -4097 & e.flags | 2,
                        ao = !1,
                        no = e
                    }
                }
            }
            function co(e) {
                for (e = e.return; null !== e && 5 !== e.tag && 3 !== e.tag && 13 !== e.tag; )
                    e = e.return;
                no = e
            }
            function po(e) {
                if (e !== no)
                    return !1;
                if (!ao)
                    return co(e),
                    ao = !0,
                    !1;
                var t;
                if ((t = 3 !== e.tag) && !(t = 5 !== e.tag) && (t = "head" !== (t = e.type) && "body" !== t && !na(e.type, e.memoizedProps)),
                t && (t = ro)) {
                    if (so(e))
                        throw fo(),
                        Error(o(418));
                    for (; t; )
                        io(e, t),
                        t = ua(t.nextSibling)
                }
                if (co(e),
                13 === e.tag) {
                    if (!(e = null !== (e = e.memoizedState) ? e.dehydrated : null))
                        throw Error(o(317));
                    e: {
                        for (e = e.nextSibling,
                        t = 0; e; ) {
                            if (8 === e.nodeType) {
                                var n = e.data;
                                if ("/$" === n) {
                                    if (0 === t) {
                                        ro = ua(e.nextSibling);
                                        break e
                                    }
                                    t--
                                } else
                                    "$" !== n && "$!" !== n && "$?" !== n || t++
                            }
                            e = e.nextSibling
                        }
                        ro = null
                    }
                } else
                    ro = no ? ua(e.stateNode.nextSibling) : null;
                return !0
            }
            function fo() {
                for (var e = ro; e; )
                    e = ua(e.nextSibling)
            }
            function mo() {
                ro = no = null,
                ao = !1
            }
            function ho(e) {
                null === oo ? oo = [e] : oo.push(e)
            }
            var go = x.ReactCurrentBatchConfig;
            function vo(e, t, n) {
                if (null !== (e = n.ref) && "function" !== typeof e && "object" !== typeof e) {
                    if (n._owner) {
                        if (n = n._owner) {
                            if (1 !== n.tag)
                                throw Error(o(309));
                            var r = n.stateNode
                        }
                        if (!r)
                            throw Error(o(147, e));
                        var a = r
                          , i = "" + e;
                        return null !== t && null !== t.ref && "function" === typeof t.ref && t.ref._stringRef === i ? t.ref : (t = function(e) {
                            var t = a.refs;
                            null === e ? delete t[i] : t[i] = e
                        }
                        ,
                        t._stringRef = i,
                        t)
                    }
                    if ("string" !== typeof e)
                        throw Error(o(284));
                    if (!n._owner)
                        throw Error(o(290, e))
                }
                return e
            }
            function yo(e, t) {
                throw e = Object.prototype.toString.call(t),
                Error(o(31, "[object Object]" === e ? "object with keys {" + Object.keys(t).join(", ") + "}" : e))
            }
            function bo(e) {
                return (0,
                e._init)(e._payload)
            }
            function xo(e) {
                function t(t, n) {
                    if (e) {
                        var r = t.deletions;
                        null === r ? (t.deletions = [n],
                        t.flags |= 16) : r.push(n)
                    }
                }
                function n(n, r) {
                    if (!e)
                        return null;
                    for (; null !== r; )
                        t(n, r),
                        r = r.sibling;
                    return null
                }
                function r(e, t) {
                    for (e = new Map; null !== t; )
                        null !== t.key ? e.set(t.key, t) : e.set(t.index, t),
                        t = t.sibling;
                    return e
                }
                function a(e, t) {
                    return (e = Uu(e, t)).index = 0,
                    e.sibling = null,
                    e
                }
                function i(t, n, r) {
                    return t.index = r,
                    e ? null !== (r = t.alternate) ? (r = r.index) < n ? (t.flags |= 2,
                    n) : r : (t.flags |= 2,
                    n) : (t.flags |= 1048576,
                    n)
                }
                function l(t) {
                    return e && null === t.alternate && (t.flags |= 2),
                    t
                }
                function s(e, t, n, r) {
                    return null === t || 6 !== t.tag ? ((t = zu(n, e.mode, r)).return = e,
                    t) : ((t = a(t, n)).return = e,
                    t)
                }
                function u(e, t, n, r) {
                    var o = n.type;
                    return o === k ? d(e, t, n.props.children, r, n.key) : null !== t && (t.elementType === o || "object" === typeof o && null !== o && o.$$typeof === L && bo(o) === t.type) ? ((r = a(t, n.props)).ref = vo(e, t, n),
                    r.return = e,
                    r) : ((r = Pu(n.type, n.key, n.props, null, e.mode, r)).ref = vo(e, t, n),
                    r.return = e,
                    r)
                }
                function c(e, t, n, r) {
                    return null === t || 4 !== t.tag || t.stateNode.containerInfo !== n.containerInfo || t.stateNode.implementation !== n.implementation ? ((t = Mu(n, e.mode, r)).return = e,
                    t) : ((t = a(t, n.children || [])).return = e,
                    t)
                }
                function d(e, t, n, r, o) {
                    return null === t || 7 !== t.tag ? ((t = Iu(n, e.mode, r, o)).return = e,
                    t) : ((t = a(t, n)).return = e,
                    t)
                }
                function p(e, t, n) {
                    if ("string" === typeof t && "" !== t || "number" === typeof t)
                        return (t = zu("" + t, e.mode, n)).return = e,
                        t;
                    if ("object" === typeof t && null !== t) {
                        switch (t.$$typeof) {
                        case w:
                            return (n = Pu(t.type, t.key, t.props, null, e.mode, n)).ref = vo(e, null, t),
                            n.return = e,
                            n;
                        case A:
                            return (t = Mu(t, e.mode, n)).return = e,
                            t;
                        case L:
                            return p(e, (0,
                            t._init)(t._payload), n)
                        }
                        if (te(t) || I(t))
                            return (t = Iu(t, e.mode, n, null)).return = e,
                            t;
                        yo(e, t)
                    }
                    return null
                }
                function f(e, t, n, r) {
                    var a = null !== t ? t.key : null;
                    if ("string" === typeof n && "" !== n || "number" === typeof n)
                        return null !== a ? null : s(e, t, "" + n, r);
                    if ("object" === typeof n && null !== n) {
                        switch (n.$$typeof) {
                        case w:
                            return n.key === a ? u(e, t, n, r) : null;
                        case A:
                            return n.key === a ? c(e, t, n, r) : null;
                        case L:
                            return f(e, t, (a = n._init)(n._payload), r)
                        }
                        if (te(n) || I(n))
                            return null !== a ? null : d(e, t, n, r, null);
                        yo(e, n)
                    }
                    return null
                }
                function m(e, t, n, r, a) {
                    if ("string" === typeof r && "" !== r || "number" === typeof r)
                        return s(t, e = e.get(n) || null, "" + r, a);
                    if ("object" === typeof r && null !== r) {
                        switch (r.$$typeof) {
                        case w:
                            return u(t, e = e.get(null === r.key ? n : r.key) || null, r, a);
                        case A:
                            return c(t, e = e.get(null === r.key ? n : r.key) || null, r, a);
                        case L:
                            return m(e, t, n, (0,
                            r._init)(r._payload), a)
                        }
                        if (te(r) || I(r))
                            return d(t, e = e.get(n) || null, r, a, null);
                        yo(t, r)
                    }
                    return null
                }
                function h(a, o, l, s) {
                    for (var u = null, c = null, d = o, h = o = 0, g = null; null !== d && h < l.length; h++) {
                        d.index > h ? (g = d,
                        d = null) : g = d.sibling;
                        var v = f(a, d, l[h], s);
                        if (null === v) {
                            null === d && (d = g);
                            break
                        }
                        e && d && null === v.alternate && t(a, d),
                        o = i(v, o, h),
                        null === c ? u = v : c.sibling = v,
                        c = v,
                        d = g
                    }
                    if (h === l.length)
                        return n(a, d),
                        ao && _a(a, h),
                        u;
                    if (null === d) {
                        for (; h < l.length; h++)
                            null !== (d = p(a, l[h], s)) && (o = i(d, o, h),
                            null === c ? u = d : c.sibling = d,
                            c = d);
                        return ao && _a(a, h),
                        u
                    }
                    for (d = r(a, d); h < l.length; h++)
                        null !== (g = m(d, a, h, l[h], s)) && (e && null !== g.alternate && d.delete(null === g.key ? h : g.key),
                        o = i(g, o, h),
                        null === c ? u = g : c.sibling = g,
                        c = g);
                    return e && d.forEach((function(e) {
                        return t(a, e)
                    }
                    )),
                    ao && _a(a, h),
                    u
                }
                function g(a, l, s, u) {
                    var c = I(s);
                    if ("function" !== typeof c)
                        throw Error(o(150));
                    if (null == (s = c.call(s)))
                        throw Error(o(151));
                    for (var d = c = null, h = l, g = l = 0, v = null, y = s.next(); null !== h && !y.done; g++,
                    y = s.next()) {
                        h.index > g ? (v = h,
                        h = null) : v = h.sibling;
                        var b = f(a, h, y.value, u);
                        if (null === b) {
                            null === h && (h = v);
                            break
                        }
                        e && h && null === b.alternate && t(a, h),
                        l = i(b, l, g),
                        null === d ? c = b : d.sibling = b,
                        d = b,
                        h = v
                    }
                    if (y.done)
                        return n(a, h),
                        ao && _a(a, g),
                        c;
                    if (null === h) {
                        for (; !y.done; g++,
                        y = s.next())
                            null !== (y = p(a, y.value, u)) && (l = i(y, l, g),
                            null === d ? c = y : d.sibling = y,
                            d = y);
                        return ao && _a(a, g),
                        c
                    }
                    for (h = r(a, h); !y.done; g++,
                    y = s.next())
                        null !== (y = m(h, a, g, y.value, u)) && (e && null !== y.alternate && h.delete(null === y.key ? g : y.key),
                        l = i(y, l, g),
                        null === d ? c = y : d.sibling = y,
                        d = y);
                    return e && h.forEach((function(e) {
                        return t(a, e)
                    }
                    )),
                    ao && _a(a, g),
                    c
                }
                return function e(r, o, i, s) {
                    if ("object" === typeof i && null !== i && i.type === k && null === i.key && (i = i.props.children),
                    "object" === typeof i && null !== i) {
                        switch (i.$$typeof) {
                        case w:
                            e: {
                                for (var u = i.key, c = o; null !== c; ) {
                                    if (c.key === u) {
                                        if ((u = i.type) === k) {
                                            if (7 === c.tag) {
                                                n(r, c.sibling),
                                                (o = a(c, i.props.children)).return = r,
                                                r = o;
                                                break e
                                            }
                                        } else if (c.elementType === u || "object" === typeof u && null !== u && u.$$typeof === L && bo(u) === c.type) {
                                            n(r, c.sibling),
                                            (o = a(c, i.props)).ref = vo(r, c, i),
                                            o.return = r,
                                            r = o;
                                            break e
                                        }
                                        n(r, c);
                                        break
                                    }
                                    t(r, c),
                                    c = c.sibling
                                }
                                i.type === k ? ((o = Iu(i.props.children, r.mode, s, i.key)).return = r,
                                r = o) : ((s = Pu(i.type, i.key, i.props, null, r.mode, s)).ref = vo(r, o, i),
                                s.return = r,
                                r = s)
                            }
                            return l(r);
                        case A:
                            e: {
                                for (c = i.key; null !== o; ) {
                                    if (o.key === c) {
                                        if (4 === o.tag && o.stateNode.containerInfo === i.containerInfo && o.stateNode.implementation === i.implementation) {
                                            n(r, o.sibling),
                                            (o = a(o, i.children || [])).return = r,
                                            r = o;
                                            break e
                                        }
                                        n(r, o);
                                        break
                                    }
                                    t(r, o),
                                    o = o.sibling
                                }
                                (o = Mu(i, r.mode, s)).return = r,
                                r = o
                            }
                            return l(r);
                        case L:
                            return e(r, o, (c = i._init)(i._payload), s)
                        }
                        if (te(i))
                            return h(r, o, i, s);
                        if (I(i))
                            return g(r, o, i, s);
                        yo(r, i)
                    }
                    return "string" === typeof i && "" !== i || "number" === typeof i ? (i = "" + i,
                    null !== o && 6 === o.tag ? (n(r, o.sibling),
                    (o = a(o, i)).return = r,
                    r = o) : (n(r, o),
                    (o = zu(i, r.mode, s)).return = r,
                    r = o),
                    l(r)) : n(r, o)
                }
            }
            var wo = xo(!0)
              , Ao = xo(!1)
              , ko = Sa(null)
              , So = null
              , Eo = null
              , jo = null;
            function No() {
                jo = Eo = So = null
            }
            function Co(e) {
                var t = ko.current;
                Ea(ko),
                e._currentValue = t
            }
            function Ro(e, t, n) {
                for (; null !== e; ) {
                    var r = e.alternate;
                    if ((e.childLanes & t) !== t ? (e.childLanes |= t,
                    null !== r && (r.childLanes |= t)) : null !== r && (r.childLanes & t) !== t && (r.childLanes |= t),
                    e === n)
                        break;
                    e = e.return
                }
            }
            function Oo(e, t) {
                So = e,
                jo = Eo = null,
                null !== (e = e.dependencies) && null !== e.firstContext && (0 !== (e.lanes & t) && (bl = !0),
                e.firstContext = null)
            }
            function To(e) {
                var t = e._currentValue;
                if (jo !== e)
                    if (e = {
                        context: e,
                        memoizedValue: t,
                        next: null
                    },
                    null === Eo) {
                        if (null === So)
                            throw Error(o(308));
                        Eo = e,
                        So.dependencies = {
                            lanes: 0,
                            firstContext: e
                        }
                    } else
                        Eo = Eo.next = e;
                return t
            }
            var Lo = null;
            function Uo(e) {
                null === Lo ? Lo = [e] : Lo.push(e)
            }
            function Po(e, t, n, r) {
                var a = t.interleaved;
                return null === a ? (n.next = n,
                Uo(t)) : (n.next = a.next,
                a.next = n),
                t.interleaved = n,
                Io(e, r)
            }
            function Io(e, t) {
                e.lanes |= t;
                var n = e.alternate;
                for (null !== n && (n.lanes |= t),
                n = e,
                e = e.return; null !== e; )
                    e.childLanes |= t,
                    null !== (n = e.alternate) && (n.childLanes |= t),
                    n = e,
                    e = e.return;
                return 3 === n.tag ? n.stateNode : null
            }
            var Fo = !1;
            function zo(e) {
                e.updateQueue = {
                    baseState: e.memoizedState,
                    firstBaseUpdate: null,
                    lastBaseUpdate: null,
                    shared: {
                        pending: null,
                        interleaved: null,
                        lanes: 0
                    },
                    effects: null
                }
            }
            function Mo(e, t) {
                e = e.updateQueue,
                t.updateQueue === e && (t.updateQueue = {
                    baseState: e.baseState,
                    firstBaseUpdate: e.firstBaseUpdate,
                    lastBaseUpdate: e.lastBaseUpdate,
                    shared: e.shared,
                    effects: e.effects
                })
            }
            function Bo(e, t) {
                return {
                    eventTime: e,
                    lane: t,
                    tag: 0,
                    payload: null,
                    callback: null,
                    next: null
                }
            }
            function qo(e, t, n) {
                var r = e.updateQueue;
                if (null === r)
                    return null;
                if (r = r.shared,
                0 !== (2 & Cs)) {
                    var a = r.pending;
                    return null === a ? t.next = t : (t.next = a.next,
                    a.next = t),
                    r.pending = t,
                    Io(e, n)
                }
                return null === (a = r.interleaved) ? (t.next = t,
                Uo(r)) : (t.next = a.next,
                a.next = t),
                r.interleaved = t,
                Io(e, n)
            }
            function Do(e, t, n) {
                if (null !== (t = t.updateQueue) && (t = t.shared,
                0 !== (4194240 & n))) {
                    var r = t.lanes;
                    n |= r &= e.pendingLanes,
                    t.lanes = n,
                    yt(e, n)
                }
            }
            function Ho(e, t) {
                var n = e.updateQueue
                  , r = e.alternate;
                if (null !== r && n === (r = r.updateQueue)) {
                    var a = null
                      , o = null;
                    if (null !== (n = n.firstBaseUpdate)) {
                        do {
                            var i = {
                                eventTime: n.eventTime,
                                lane: n.lane,
                                tag: n.tag,
                                payload: n.payload,
                                callback: n.callback,
                                next: null
                            };
                            null === o ? a = o = i : o = o.next = i,
                            n = n.next
                        } while (null !== n);
                        null === o ? a = o = t : o = o.next = t
                    } else
                        a = o = t;
                    return n = {
                        baseState: r.baseState,
                        firstBaseUpdate: a,
                        lastBaseUpdate: o,
                        shared: r.shared,
                        effects: r.effects
                    },
                    void (e.updateQueue = n)
                }
                null === (e = n.lastBaseUpdate) ? n.firstBaseUpdate = t : e.next = t,
                n.lastBaseUpdate = t
            }
            function Qo(e, t, n, r) {
                var a = e.updateQueue;
                Fo = !1;
                var o = a.firstBaseUpdate
                  , i = a.lastBaseUpdate
                  , l = a.shared.pending;
                if (null !== l) {
                    a.shared.pending = null;
                    var s = l
                      , u = s.next;
                    s.next = null,
                    null === i ? o = u : i.next = u,
                    i = s;
                    var c = e.alternate;
                    null !== c && ((l = (c = c.updateQueue).lastBaseUpdate) !== i && (null === l ? c.firstBaseUpdate = u : l.next = u,
                    c.lastBaseUpdate = s))
                }
                if (null !== o) {
                    var d = a.baseState;
                    for (i = 0,
                    c = u = s = null,
                    l = o; ; ) {
                        var p = l.lane
                          , f = l.eventTime;
                        if ((r & p) === p) {
                            null !== c && (c = c.next = {
                                eventTime: f,
                                lane: 0,
                                tag: l.tag,
                                payload: l.payload,
                                callback: l.callback,
                                next: null
                            });
                            e: {
                                var m = e
                                  , h = l;
                                switch (p = t,
                                f = n,
                                h.tag) {
                                case 1:
                                    if ("function" === typeof (m = h.payload)) {
                                        d = m.call(f, d, p);
                                        break e
                                    }
                                    d = m;
                                    break e;
                                case 3:
                                    m.flags = -65537 & m.flags | 128;
                                case 0:
                                    if (null === (p = "function" === typeof (m = h.payload) ? m.call(f, d, p) : m) || void 0 === p)
                                        break e;
                                    d = z({}, d, p);
                                    break e;
                                case 2:
                                    Fo = !0
                                }
                            }
                            null !== l.callback && 0 !== l.lane && (e.flags |= 64,
                            null === (p = a.effects) ? a.effects = [l] : p.push(l))
                        } else
                            f = {
                                eventTime: f,
                                lane: p,
                                tag: l.tag,
                                payload: l.payload,
                                callback: l.callback,
                                next: null
                            },
                            null === c ? (u = c = f,
                            s = d) : c = c.next = f,
                            i |= p;
                        if (null === (l = l.next)) {
                            if (null === (l = a.shared.pending))
                                break;
                            l = (p = l).next,
                            p.next = null,
                            a.lastBaseUpdate = p,
                            a.shared.pending = null
                        }
                    }
                    if (null === c && (s = d),
                    a.baseState = s,
                    a.firstBaseUpdate = u,
                    a.lastBaseUpdate = c,
                    null !== (t = a.shared.interleaved)) {
                        a = t;
                        do {
                            i |= a.lane,
                            a = a.next
                        } while (a !== t)
                    } else
                        null === o && (a.shared.lanes = 0);
                    Fs |= i,
                    e.lanes = i,
                    e.memoizedState = d
                }
            }
            function Yo(e, t, n) {
                if (e = t.effects,
                t.effects = null,
                null !== e)
                    for (t = 0; t < e.length; t++) {
                        var r = e[t]
                          , a = r.callback;
                        if (null !== a) {
                            if (r.callback = null,
                            r = n,
                            "function" !== typeof a)
                                throw Error(o(191, a));
                            a.call(r)
                        }
                    }
            }
            var Wo = {}
              , Go = Sa(Wo)
              , Vo = Sa(Wo)
              , Zo = Sa(Wo);
            function Ko(e) {
                if (e === Wo)
                    throw Error(o(174));
                return e
            }
            function Jo(e, t) {
                switch (ja(Zo, t),
                ja(Vo, e),
                ja(Go, Wo),
                e = t.nodeType) {
                case 9:
                case 11:
                    t = (t = t.documentElement) ? t.namespaceURI : se(null, "");
                    break;
                default:
                    t = se(t = (e = 8 === e ? t.parentNode : t).namespaceURI || null, e = e.tagName)
                }
                Ea(Go),
                ja(Go, t)
            }
            function Xo() {
                Ea(Go),
                Ea(Vo),
                Ea(Zo)
            }
            function _o(e) {
                Ko(Zo.current);
                var t = Ko(Go.current)
                  , n = se(t, e.type);
                t !== n && (ja(Vo, e),
                ja(Go, n))
            }
            function $o(e) {
                Vo.current === e && (Ea(Go),
                Ea(Vo))
            }
            var ei = Sa(0);
            function ti(e) {
                for (var t = e; null !== t; ) {
                    if (13 === t.tag) {
                        var n = t.memoizedState;
                        if (null !== n && (null === (n = n.dehydrated) || "$?" === n.data || "$!" === n.data))
                            return t
                    } else if (19 === t.tag && void 0 !== t.memoizedProps.revealOrder) {
                        if (0 !== (128 & t.flags))
                            return t
                    } else if (null !== t.child) {
                        t.child.return = t,
                        t = t.child;
                        continue
                    }
                    if (t === e)
                        break;
                    for (; null === t.sibling; ) {
                        if (null === t.return || t.return === e)
                            return null;
                        t = t.return
                    }
                    t.sibling.return = t.return,
                    t = t.sibling
                }
                return null
            }
            var ni = [];
            function ri() {
                for (var e = 0; e < ni.length; e++)
                    ni[e]._workInProgressVersionPrimary = null;
                ni.length = 0
            }
            var ai = x.ReactCurrentDispatcher
              , oi = x.ReactCurrentBatchConfig
              , ii = 0
              , li = null
              , si = null
              , ui = null
              , ci = !1
              , di = !1
              , pi = 0
              , fi = 0;
            function mi() {
                throw Error(o(321))
            }
            function hi(e, t) {
                if (null === t)
                    return !1;
                for (var n = 0; n < t.length && n < e.length; n++)
                    if (!lr(e[n], t[n]))
                        return !1;
                return !0
            }
            function gi(e, t, n, r, a, i) {
                if (ii = i,
                li = t,
                t.memoizedState = null,
                t.updateQueue = null,
                t.lanes = 0,
                ai.current = null === e || null === e.memoizedState ? $i : el,
                e = n(r, a),
                di) {
                    i = 0;
                    do {
                        if (di = !1,
                        pi = 0,
                        25 <= i)
                            throw Error(o(301));
                        i += 1,
                        ui = si = null,
                        t.updateQueue = null,
                        ai.current = tl,
                        e = n(r, a)
                    } while (di)
                }
                if (ai.current = _i,
                t = null !== si && null !== si.next,
                ii = 0,
                ui = si = li = null,
                ci = !1,
                t)
                    throw Error(o(300));
                return e
            }
            function vi() {
                var e = 0 !== pi;
                return pi = 0,
                e
            }
            function yi() {
                var e = {
                    memoizedState: null,
                    baseState: null,
                    baseQueue: null,
                    queue: null,
                    next: null
                };
                return null === ui ? li.memoizedState = ui = e : ui = ui.next = e,
                ui
            }
            function bi() {
                if (null === si) {
                    var e = li.alternate;
                    e = null !== e ? e.memoizedState : null
                } else
                    e = si.next;
                var t = null === ui ? li.memoizedState : ui.next;
                if (null !== t)
                    ui = t,
                    si = e;
                else {
                    if (null === e)
                        throw Error(o(310));
                    e = {
                        memoizedState: (si = e).memoizedState,
                        baseState: si.baseState,
                        baseQueue: si.baseQueue,
                        queue: si.queue,
                        next: null
                    },
                    null === ui ? li.memoizedState = ui = e : ui = ui.next = e
                }
                return ui
            }
            function xi(e, t) {
                return "function" === typeof t ? t(e) : t
            }
            function wi(e) {
                var t = bi()
                  , n = t.queue;
                if (null === n)
                    throw Error(o(311));
                n.lastRenderedReducer = e;
                var r = si
                  , a = r.baseQueue
                  , i = n.pending;
                if (null !== i) {
                    if (null !== a) {
                        var l = a.next;
                        a.next = i.next,
                        i.next = l
                    }
                    r.baseQueue = a = i,
                    n.pending = null
                }
                if (null !== a) {
                    i = a.next,
                    r = r.baseState;
                    var s = l = null
                      , u = null
                      , c = i;
                    do {
                        var d = c.lane;
                        if ((ii & d) === d)
                            null !== u && (u = u.next = {
                                lane: 0,
                                action: c.action,
                                hasEagerState: c.hasEagerState,
                                eagerState: c.eagerState,
                                next: null
                            }),
                            r = c.hasEagerState ? c.eagerState : e(r, c.action);
                        else {
                            var p = {
                                lane: d,
                                action: c.action,
                                hasEagerState: c.hasEagerState,
                                eagerState: c.eagerState,
                                next: null
                            };
                            null === u ? (s = u = p,
                            l = r) : u = u.next = p,
                            li.lanes |= d,
                            Fs |= d
                        }
                        c = c.next
                    } while (null !== c && c !== i);
                    null === u ? l = r : u.next = s,
                    lr(r, t.memoizedState) || (bl = !0),
                    t.memoizedState = r,
                    t.baseState = l,
                    t.baseQueue = u,
                    n.lastRenderedState = r
                }
                if (null !== (e = n.interleaved)) {
                    a = e;
                    do {
                        i = a.lane,
                        li.lanes |= i,
                        Fs |= i,
                        a = a.next
                    } while (a !== e)
                } else
                    null === a && (n.lanes = 0);
                return [t.memoizedState, n.dispatch]
            }
            function Ai(e) {
                var t = bi()
                  , n = t.queue;
                if (null === n)
                    throw Error(o(311));
                n.lastRenderedReducer = e;
                var r = n.dispatch
                  , a = n.pending
                  , i = t.memoizedState;
                if (null !== a) {
                    n.pending = null;
                    var l = a = a.next;
                    do {
                        i = e(i, l.action),
                        l = l.next
                    } while (l !== a);
                    lr(i, t.memoizedState) || (bl = !0),
                    t.memoizedState = i,
                    null === t.baseQueue && (t.baseState = i),
                    n.lastRenderedState = i
                }
                return [i, r]
            }
            function ki() {}
            function Si(e, t) {
                var n = li
                  , r = bi()
                  , a = t()
                  , i = !lr(r.memoizedState, a);
                if (i && (r.memoizedState = a,
                bl = !0),
                r = r.queue,
                Fi(Ni.bind(null, n, r, e), [e]),
                r.getSnapshot !== t || i || null !== ui && 1 & ui.memoizedState.tag) {
                    if (n.flags |= 2048,
                    Ti(9, ji.bind(null, n, r, a, t), void 0, null),
                    null === Rs)
                        throw Error(o(349));
                    0 !== (30 & ii) || Ei(n, t, a)
                }
                return a
            }
            function Ei(e, t, n) {
                e.flags |= 16384,
                e = {
                    getSnapshot: t,
                    value: n
                },
                null === (t = li.updateQueue) ? (t = {
                    lastEffect: null,
                    stores: null
                },
                li.updateQueue = t,
                t.stores = [e]) : null === (n = t.stores) ? t.stores = [e] : n.push(e)
            }
            function ji(e, t, n, r) {
                t.value = n,
                t.getSnapshot = r,
                Ci(t) && Ri(e)
            }
            function Ni(e, t, n) {
                return n((function() {
                    Ci(t) && Ri(e)
                }
                ))
            }
            function Ci(e) {
                var t = e.getSnapshot;
                e = e.value;
                try {
                    var n = t();
                    return !lr(e, n)
                } catch (r) {
                    return !0
                }
            }
            function Ri(e) {
                var t = Io(e, 1);
                null !== t && nu(t, e, 1, -1)
            }
            function Oi(e) {
                var t = yi();
                return "function" === typeof e && (e = e()),
                t.memoizedState = t.baseState = e,
                e = {
                    pending: null,
                    interleaved: null,
                    lanes: 0,
                    dispatch: null,
                    lastRenderedReducer: xi,
                    lastRenderedState: e
                },
                t.queue = e,
                e = e.dispatch = Zi.bind(null, li, e),
                [t.memoizedState, e]
            }
            function Ti(e, t, n, r) {
                return e = {
                    tag: e,
                    create: t,
                    destroy: n,
                    deps: r,
                    next: null
                },
                null === (t = li.updateQueue) ? (t = {
                    lastEffect: null,
                    stores: null
                },
                li.updateQueue = t,
                t.lastEffect = e.next = e) : null === (n = t.lastEffect) ? t.lastEffect = e.next = e : (r = n.next,
                n.next = e,
                e.next = r,
                t.lastEffect = e),
                e
            }
            function Li() {
                return bi().memoizedState
            }
            function Ui(e, t, n, r) {
                var a = yi();
                li.flags |= e,
                a.memoizedState = Ti(1 | t, n, void 0, void 0 === r ? null : r)
            }
            function Pi(e, t, n, r) {
                var a = bi();
                r = void 0 === r ? null : r;
                var o = void 0;
                if (null !== si) {
                    var i = si.memoizedState;
                    if (o = i.destroy,
                    null !== r && hi(r, i.deps))
                        return void (a.memoizedState = Ti(t, n, o, r))
                }
                li.flags |= e,
                a.memoizedState = Ti(1 | t, n, o, r)
            }
            function Ii(e, t) {
                return Ui(8390656, 8, e, t)
            }
            function Fi(e, t) {
                return Pi(2048, 8, e, t)
            }
            function zi(e, t) {
                return Pi(4, 2, e, t)
            }
            function Mi(e, t) {
                return Pi(4, 4, e, t)
            }
            function Bi(e, t) {
                return "function" === typeof t ? (e = e(),
                t(e),
                function() {
                    t(null)
                }
                ) : null !== t && void 0 !== t ? (e = e(),
                t.current = e,
                function() {
                    t.current = null
                }
                ) : void 0
            }
            function qi(e, t, n) {
                return n = null !== n && void 0 !== n ? n.concat([e]) : null,
                Pi(4, 4, Bi.bind(null, t, e), n)
            }
            function Di() {}
            function Hi(e, t) {
                var n = bi();
                t = void 0 === t ? null : t;
                var r = n.memoizedState;
                return null !== r && null !== t && hi(t, r[1]) ? r[0] : (n.memoizedState = [e, t],
                e)
            }
            function Qi(e, t) {
                var n = bi();
                t = void 0 === t ? null : t;
                var r = n.memoizedState;
                return null !== r && null !== t && hi(t, r[1]) ? r[0] : (e = e(),
                n.memoizedState = [e, t],
                e)
            }
            function Yi(e, t, n) {
                return 0 === (21 & ii) ? (e.baseState && (e.baseState = !1,
                bl = !0),
                e.memoizedState = n) : (lr(n, t) || (n = ht(),
                li.lanes |= n,
                Fs |= n,
                e.baseState = !0),
                t)
            }
            function Wi(e, t) {
                var n = bt;
                bt = 0 !== n && 4 > n ? n : 4,
                e(!0);
                var r = oi.transition;
                oi.transition = {};
                try {
                    e(!1),
                    t()
                } finally {
                    bt = n,
                    oi.transition = r
                }
            }
            function Gi() {
                return bi().memoizedState
            }
            function Vi(e, t, n) {
                var r = tu(e);
                if (n = {
                    lane: r,
                    action: n,
                    hasEagerState: !1,
                    eagerState: null,
                    next: null
                },
                Ki(e))
                    Ji(t, n);
                else if (null !== (n = Po(e, t, n, r))) {
                    nu(n, e, r, eu()),
                    Xi(n, t, r)
                }
            }
            function Zi(e, t, n) {
                var r = tu(e)
                  , a = {
                    lane: r,
                    action: n,
                    hasEagerState: !1,
                    eagerState: null,
                    next: null
                };
                if (Ki(e))
                    Ji(t, a);
                else {
                    var o = e.alternate;
                    if (0 === e.lanes && (null === o || 0 === o.lanes) && null !== (o = t.lastRenderedReducer))
                        try {
                            var i = t.lastRenderedState
                              , l = o(i, n);
                            if (a.hasEagerState = !0,
                            a.eagerState = l,
                            lr(l, i)) {
                                var s = t.interleaved;
                                return null === s ? (a.next = a,
                                Uo(t)) : (a.next = s.next,
                                s.next = a),
                                void (t.interleaved = a)
                            }
                        } catch (u) {}
                    null !== (n = Po(e, t, a, r)) && (nu(n, e, r, a = eu()),
                    Xi(n, t, r))
                }
            }
            function Ki(e) {
                var t = e.alternate;
                return e === li || null !== t && t === li
            }
            function Ji(e, t) {
                di = ci = !0;
                var n = e.pending;
                null === n ? t.next = t : (t.next = n.next,
                n.next = t),
                e.pending = t
            }
            function Xi(e, t, n) {
                if (0 !== (4194240 & n)) {
                    var r = t.lanes;
                    n |= r &= e.pendingLanes,
                    t.lanes = n,
                    yt(e, n)
                }
            }
            var _i = {
                readContext: To,
                useCallback: mi,
                useContext: mi,
                useEffect: mi,
                useImperativeHandle: mi,
                useInsertionEffect: mi,
                useLayoutEffect: mi,
                useMemo: mi,
                useReducer: mi,
                useRef: mi,
                useState: mi,
                useDebugValue: mi,
                useDeferredValue: mi,
                useTransition: mi,
                useMutableSource: mi,
                useSyncExternalStore: mi,
                useId: mi,
                unstable_isNewReconciler: !1
            }
              , $i = {
                readContext: To,
                useCallback: function(e, t) {
                    return yi().memoizedState = [e, void 0 === t ? null : t],
                    e
                },
                useContext: To,
                useEffect: Ii,
                useImperativeHandle: function(e, t, n) {
                    return n = null !== n && void 0 !== n ? n.concat([e]) : null,
                    Ui(4194308, 4, Bi.bind(null, t, e), n)
                },
                useLayoutEffect: function(e, t) {
                    return Ui(4194308, 4, e, t)
                },
                useInsertionEffect: function(e, t) {
                    return Ui(4, 2, e, t)
                },
                useMemo: function(e, t) {
                    var n = yi();
                    return t = void 0 === t ? null : t,
                    e = e(),
                    n.memoizedState = [e, t],
                    e
                },
                useReducer: function(e, t, n) {
                    var r = yi();
                    return t = void 0 !== n ? n(t) : t,
                    r.memoizedState = r.baseState = t,
                    e = {
                        pending: null,
                        interleaved: null,
                        lanes: 0,
                        dispatch: null,
                        lastRenderedReducer: e,
                        lastRenderedState: t
                    },
                    r.queue = e,
                    e = e.dispatch = Vi.bind(null, li, e),
                    [r.memoizedState, e]
                },
                useRef: function(e) {
                    return e = {
                        current: e
                    },
                    yi().memoizedState = e
                },
                useState: Oi,
                useDebugValue: Di,
                useDeferredValue: function(e) {
                    return yi().memoizedState = e
                },
                useTransition: function() {
                    var e = Oi(!1)
                      , t = e[0];
                    return e = Wi.bind(null, e[1]),
                    yi().memoizedState = e,
                    [t, e]
                },
                useMutableSource: function() {},
                useSyncExternalStore: function(e, t, n) {
                    var r = li
                      , a = yi();
                    if (ao) {
                        if (void 0 === n)
                            throw Error(o(407));
                        n = n()
                    } else {
                        if (n = t(),
                        null === Rs)
                            throw Error(o(349));
                        0 !== (30 & ii) || Ei(r, t, n)
                    }
                    a.memoizedState = n;
                    var i = {
                        value: n,
                        getSnapshot: t
                    };
                    return a.queue = i,
                    Ii(Ni.bind(null, r, i, e), [e]),
                    r.flags |= 2048,
                    Ti(9, ji.bind(null, r, i, n, t), void 0, null),
                    n
                },
                useId: function() {
                    var e = yi()
                      , t = Rs.identifierPrefix;
                    if (ao) {
                        var n = Xa;
                        t = ":" + t + "R" + (n = (Ja & ~(1 << 32 - it(Ja) - 1)).toString(32) + n),
                        0 < (n = pi++) && (t += "H" + n.toString(32)),
                        t += ":"
                    } else
                        t = ":" + t + "r" + (n = fi++).toString(32) + ":";
                    return e.memoizedState = t
                },
                unstable_isNewReconciler: !1
            }
              , el = {
                readContext: To,
                useCallback: Hi,
                useContext: To,
                useEffect: Fi,
                useImperativeHandle: qi,
                useInsertionEffect: zi,
                useLayoutEffect: Mi,
                useMemo: Qi,
                useReducer: wi,
                useRef: Li,
                useState: function() {
                    return wi(xi)
                },
                useDebugValue: Di,
                useDeferredValue: function(e) {
                    return Yi(bi(), si.memoizedState, e)
                },
                useTransition: function() {
                    return [wi(xi)[0], bi().memoizedState]
                },
                useMutableSource: ki,
                useSyncExternalStore: Si,
                useId: Gi,
                unstable_isNewReconciler: !1
            }
              , tl = {
                readContext: To,
                useCallback: Hi,
                useContext: To,
                useEffect: Fi,
                useImperativeHandle: qi,
                useInsertionEffect: zi,
                useLayoutEffect: Mi,
                useMemo: Qi,
                useReducer: Ai,
                useRef: Li,
                useState: function() {
                    return Ai(xi)
                },
                useDebugValue: Di,
                useDeferredValue: function(e) {
                    var t = bi();
                    return null === si ? t.memoizedState = e : Yi(t, si.memoizedState, e)
                },
                useTransition: function() {
                    return [Ai(xi)[0], bi().memoizedState]
                },
                useMutableSource: ki,
                useSyncExternalStore: Si,
                useId: Gi,
                unstable_isNewReconciler: !1
            };
            function nl(e, t) {
                if (e && e.defaultProps) {
                    for (var n in t = z({}, t),
                    e = e.defaultProps)
                        void 0 === t[n] && (t[n] = e[n]);
                    return t
                }
                return t
            }
            function rl(e, t, n, r) {
                n = null === (n = n(r, t = e.memoizedState)) || void 0 === n ? t : z({}, t, n),
                e.memoizedState = n,
                0 === e.lanes && (e.updateQueue.baseState = n)
            }
            var al = {
                isMounted: function(e) {
                    return !!(e = e._reactInternals) && He(e) === e
                },
                enqueueSetState: function(e, t, n) {
                    e = e._reactInternals;
                    var r = eu()
                      , a = tu(e)
                      , o = Bo(r, a);
                    o.payload = t,
                    void 0 !== n && null !== n && (o.callback = n),
                    null !== (t = qo(e, o, a)) && (nu(t, e, a, r),
                    Do(t, e, a))
                },
                enqueueReplaceState: function(e, t, n) {
                    e = e._reactInternals;
                    var r = eu()
                      , a = tu(e)
                      , o = Bo(r, a);
                    o.tag = 1,
                    o.payload = t,
                    void 0 !== n && null !== n && (o.callback = n),
                    null !== (t = qo(e, o, a)) && (nu(t, e, a, r),
                    Do(t, e, a))
                },
                enqueueForceUpdate: function(e, t) {
                    e = e._reactInternals;
                    var n = eu()
                      , r = tu(e)
                      , a = Bo(n, r);
                    a.tag = 2,
                    void 0 !== t && null !== t && (a.callback = t),
                    null !== (t = qo(e, a, r)) && (nu(t, e, r, n),
                    Do(t, e, r))
                }
            };
            function ol(e, t, n, r, a, o, i) {
                return "function" === typeof (e = e.stateNode).shouldComponentUpdate ? e.shouldComponentUpdate(r, o, i) : !t.prototype || !t.prototype.isPureReactComponent || (!sr(n, r) || !sr(a, o))
            }
            function il(e, t, n) {
                var r = !1
                  , a = Na
                  , o = t.contextType;
                return "object" === typeof o && null !== o ? o = To(o) : (a = La(t) ? Oa : Ca.current,
                o = (r = null !== (r = t.contextTypes) && void 0 !== r) ? Ta(e, a) : Na),
                t = new t(n,o),
                e.memoizedState = null !== t.state && void 0 !== t.state ? t.state : null,
                t.updater = al,
                e.stateNode = t,
                t._reactInternals = e,
                r && ((e = e.stateNode).__reactInternalMemoizedUnmaskedChildContext = a,
                e.__reactInternalMemoizedMaskedChildContext = o),
                t
            }
            function ll(e, t, n, r) {
                e = t.state,
                "function" === typeof t.componentWillReceiveProps && t.componentWillReceiveProps(n, r),
                "function" === typeof t.UNSAFE_componentWillReceiveProps && t.UNSAFE_componentWillReceiveProps(n, r),
                t.state !== e && al.enqueueReplaceState(t, t.state, null)
            }
            function sl(e, t, n, r) {
                var a = e.stateNode;
                a.props = n,
                a.state = e.memoizedState,
                a.refs = {},
                zo(e);
                var o = t.contextType;
                "object" === typeof o && null !== o ? a.context = To(o) : (o = La(t) ? Oa : Ca.current,
                a.context = Ta(e, o)),
                a.state = e.memoizedState,
                "function" === typeof (o = t.getDerivedStateFromProps) && (rl(e, t, o, n),
                a.state = e.memoizedState),
                "function" === typeof t.getDerivedStateFromProps || "function" === typeof a.getSnapshotBeforeUpdate || "function" !== typeof a.UNSAFE_componentWillMount && "function" !== typeof a.componentWillMount || (t = a.state,
                "function" === typeof a.componentWillMount && a.componentWillMount(),
                "function" === typeof a.UNSAFE_componentWillMount && a.UNSAFE_componentWillMount(),
                t !== a.state && al.enqueueReplaceState(a, a.state, null),
                Qo(e, n, a, r),
                a.state = e.memoizedState),
                "function" === typeof a.componentDidMount && (e.flags |= 4194308)
            }
            function ul(e, t) {
                try {
                    var n = ""
                      , r = t;
                    do {
                        n += D(r),
                        r = r.return
                    } while (r);
                    var a = n
                } catch (o) {
                    a = "\nError generating stack: " + o.message + "\n" + o.stack
                }
                return {
                    value: e,
                    source: t,
                    stack: a,
                    digest: null
                }
            }
            function cl(e, t, n) {
                return {
                    value: e,
                    source: null,
                    stack: null != n ? n : null,
                    digest: null != t ? t : null
                }
            }
            function dl(e, t) {
                try {
                    console.error(t.value)
                } catch (n) {
                    setTimeout((function() {
                        throw n
                    }
                    ))
                }
            }
            var pl = "function" === typeof WeakMap ? WeakMap : Map;
            function fl(e, t, n) {
                (n = Bo(-1, n)).tag = 3,
                n.payload = {
                    element: null
                };
                var r = t.value;
                return n.callback = function() {
                    Ys || (Ys = !0,
                    Ws = r),
                    dl(0, t)
                }
                ,
                n
            }
            function ml(e, t, n) {
                (n = Bo(-1, n)).tag = 3;
                var r = e.type.getDerivedStateFromError;
                if ("function" === typeof r) {
                    var a = t.value;
                    n.payload = function() {
                        return r(a)
                    }
                    ,
                    n.callback = function() {
                        dl(0, t)
                    }
                }
                var o = e.stateNode;
                return null !== o && "function" === typeof o.componentDidCatch && (n.callback = function() {
                    dl(0, t),
                    "function" !== typeof r && (null === Gs ? Gs = new Set([this]) : Gs.add(this));
                    var e = t.stack;
                    this.componentDidCatch(t.value, {
                        componentStack: null !== e ? e : ""
                    })
                }
                ),
                n
            }
            function hl(e, t, n) {
                var r = e.pingCache;
                if (null === r) {
                    r = e.pingCache = new pl;
                    var a = new Set;
                    r.set(t, a)
                } else
                    void 0 === (a = r.get(t)) && (a = new Set,
                    r.set(t, a));
                a.has(n) || (a.add(n),
                e = Eu.bind(null, e, t, n),
                t.then(e, e))
            }
            function gl(e) {
                do {
                    var t;
                    if ((t = 13 === e.tag) && (t = null === (t = e.memoizedState) || null !== t.dehydrated),
                    t)
                        return e;
                    e = e.return
                } while (null !== e);
                return null
            }
            function vl(e, t, n, r, a) {
                return 0 === (1 & e.mode) ? (e === t ? e.flags |= 65536 : (e.flags |= 128,
                n.flags |= 131072,
                n.flags &= -52805,
                1 === n.tag && (null === n.alternate ? n.tag = 17 : ((t = Bo(-1, 1)).tag = 2,
                qo(n, t, 1))),
                n.lanes |= 1),
                e) : (e.flags |= 65536,
                e.lanes = a,
                e)
            }
            var yl = x.ReactCurrentOwner
              , bl = !1;
            function xl(e, t, n, r) {
                t.child = null === e ? Ao(t, null, n, r) : wo(t, e.child, n, r)
            }
            function wl(e, t, n, r, a) {
                n = n.render;
                var o = t.ref;
                return Oo(t, a),
                r = gi(e, t, n, r, o, a),
                n = vi(),
                null === e || bl ? (ao && n && eo(t),
                t.flags |= 1,
                xl(e, t, r, a),
                t.child) : (t.updateQueue = e.updateQueue,
                t.flags &= -2053,
                e.lanes &= ~a,
                Yl(e, t, a))
            }
            function Al(e, t, n, r, a) {
                if (null === e) {
                    var o = n.type;
                    return "function" !== typeof o || Lu(o) || void 0 !== o.defaultProps || null !== n.compare || void 0 !== n.defaultProps ? ((e = Pu(n.type, null, r, t, t.mode, a)).ref = t.ref,
                    e.return = t,
                    t.child = e) : (t.tag = 15,
                    t.type = o,
                    kl(e, t, o, r, a))
                }
                if (o = e.child,
                0 === (e.lanes & a)) {
                    var i = o.memoizedProps;
                    if ((n = null !== (n = n.compare) ? n : sr)(i, r) && e.ref === t.ref)
                        return Yl(e, t, a)
                }
                return t.flags |= 1,
                (e = Uu(o, r)).ref = t.ref,
                e.return = t,
                t.child = e
            }
            function kl(e, t, n, r, a) {
                if (null !== e) {
                    var o = e.memoizedProps;
                    if (sr(o, r) && e.ref === t.ref) {
                        if (bl = !1,
                        t.pendingProps = r = o,
                        0 === (e.lanes & a))
                            return t.lanes = e.lanes,
                            Yl(e, t, a);
                        0 !== (131072 & e.flags) && (bl = !0)
                    }
                }
                return jl(e, t, n, r, a)
            }
            function Sl(e, t, n) {
                var r = t.pendingProps
                  , a = r.children
                  , o = null !== e ? e.memoizedState : null;
                if ("hidden" === r.mode)
                    if (0 === (1 & t.mode))
                        t.memoizedState = {
                            baseLanes: 0,
                            cachePool: null,
                            transitions: null
                        },
                        ja(Us, Ls),
                        Ls |= n;
                    else {
                        if (0 === (1073741824 & n))
                            return e = null !== o ? o.baseLanes | n : n,
                            t.lanes = t.childLanes = 1073741824,
                            t.memoizedState = {
                                baseLanes: e,
                                cachePool: null,
                                transitions: null
                            },
                            t.updateQueue = null,
                            ja(Us, Ls),
                            Ls |= e,
                            null;
                        t.memoizedState = {
                            baseLanes: 0,
                            cachePool: null,
                            transitions: null
                        },
                        r = null !== o ? o.baseLanes : n,
                        ja(Us, Ls),
                        Ls |= r
                    }
                else
                    null !== o ? (r = o.baseLanes | n,
                    t.memoizedState = null) : r = n,
                    ja(Us, Ls),
                    Ls |= r;
                return xl(e, t, a, n),
                t.child
            }
            function El(e, t) {
                var n = t.ref;
                (null === e && null !== n || null !== e && e.ref !== n) && (t.flags |= 512,
                t.flags |= 2097152)
            }
            function jl(e, t, n, r, a) {
                var o = La(n) ? Oa : Ca.current;
                return o = Ta(t, o),
                Oo(t, a),
                n = gi(e, t, n, r, o, a),
                r = vi(),
                null === e || bl ? (ao && r && eo(t),
                t.flags |= 1,
                xl(e, t, n, a),
                t.child) : (t.updateQueue = e.updateQueue,
                t.flags &= -2053,
                e.lanes &= ~a,
                Yl(e, t, a))
            }
            function Nl(e, t, n, r, a) {
                if (La(n)) {
                    var o = !0;
                    Fa(t)
                } else
                    o = !1;
                if (Oo(t, a),
                null === t.stateNode)
                    Ql(e, t),
                    il(t, n, r),
                    sl(t, n, r, a),
                    r = !0;
                else if (null === e) {
                    var i = t.stateNode
                      , l = t.memoizedProps;
                    i.props = l;
                    var s = i.context
                      , u = n.contextType;
                    "object" === typeof u && null !== u ? u = To(u) : u = Ta(t, u = La(n) ? Oa : Ca.current);
                    var c = n.getDerivedStateFromProps
                      , d = "function" === typeof c || "function" === typeof i.getSnapshotBeforeUpdate;
                    d || "function" !== typeof i.UNSAFE_componentWillReceiveProps && "function" !== typeof i.componentWillReceiveProps || (l !== r || s !== u) && ll(t, i, r, u),
                    Fo = !1;
                    var p = t.memoizedState;
                    i.state = p,
                    Qo(t, r, i, a),
                    s = t.memoizedState,
                    l !== r || p !== s || Ra.current || Fo ? ("function" === typeof c && (rl(t, n, c, r),
                    s = t.memoizedState),
                    (l = Fo || ol(t, n, l, r, p, s, u)) ? (d || "function" !== typeof i.UNSAFE_componentWillMount && "function" !== typeof i.componentWillMount || ("function" === typeof i.componentWillMount && i.componentWillMount(),
                    "function" === typeof i.UNSAFE_componentWillMount && i.UNSAFE_componentWillMount()),
                    "function" === typeof i.componentDidMount && (t.flags |= 4194308)) : ("function" === typeof i.componentDidMount && (t.flags |= 4194308),
                    t.memoizedProps = r,
                    t.memoizedState = s),
                    i.props = r,
                    i.state = s,
                    i.context = u,
                    r = l) : ("function" === typeof i.componentDidMount && (t.flags |= 4194308),
                    r = !1)
                } else {
                    i = t.stateNode,
                    Mo(e, t),
                    l = t.memoizedProps,
                    u = t.type === t.elementType ? l : nl(t.type, l),
                    i.props = u,
                    d = t.pendingProps,
                    p = i.context,
                    "object" === typeof (s = n.contextType) && null !== s ? s = To(s) : s = Ta(t, s = La(n) ? Oa : Ca.current);
                    var f = n.getDerivedStateFromProps;
                    (c = "function" === typeof f || "function" === typeof i.getSnapshotBeforeUpdate) || "function" !== typeof i.UNSAFE_componentWillReceiveProps && "function" !== typeof i.componentWillReceiveProps || (l !== d || p !== s) && ll(t, i, r, s),
                    Fo = !1,
                    p = t.memoizedState,
                    i.state = p,
                    Qo(t, r, i, a);
                    var m = t.memoizedState;
                    l !== d || p !== m || Ra.current || Fo ? ("function" === typeof f && (rl(t, n, f, r),
                    m = t.memoizedState),
                    (u = Fo || ol(t, n, u, r, p, m, s) || !1) ? (c || "function" !== typeof i.UNSAFE_componentWillUpdate && "function" !== typeof i.componentWillUpdate || ("function" === typeof i.componentWillUpdate && i.componentWillUpdate(r, m, s),
                    "function" === typeof i.UNSAFE_componentWillUpdate && i.UNSAFE_componentWillUpdate(r, m, s)),
                    "function" === typeof i.componentDidUpdate && (t.flags |= 4),
                    "function" === typeof i.getSnapshotBeforeUpdate && (t.flags |= 1024)) : ("function" !== typeof i.componentDidUpdate || l === e.memoizedProps && p === e.memoizedState || (t.flags |= 4),
                    "function" !== typeof i.getSnapshotBeforeUpdate || l === e.memoizedProps && p === e.memoizedState || (t.flags |= 1024),
                    t.memoizedProps = r,
                    t.memoizedState = m),
                    i.props = r,
                    i.state = m,
                    i.context = s,
                    r = u) : ("function" !== typeof i.componentDidUpdate || l === e.memoizedProps && p === e.memoizedState || (t.flags |= 4),
                    "function" !== typeof i.getSnapshotBeforeUpdate || l === e.memoizedProps && p === e.memoizedState || (t.flags |= 1024),
                    r = !1)
                }
                return Cl(e, t, n, r, o, a)
            }
            function Cl(e, t, n, r, a, o) {
                El(e, t);
                var i = 0 !== (128 & t.flags);
                if (!r && !i)
                    return a && za(t, n, !1),
                    Yl(e, t, o);
                r = t.stateNode,
                yl.current = t;
                var l = i && "function" !== typeof n.getDerivedStateFromError ? null : r.render();
                return t.flags |= 1,
                null !== e && i ? (t.child = wo(t, e.child, null, o),
                t.child = wo(t, null, l, o)) : xl(e, t, l, o),
                t.memoizedState = r.state,
                a && za(t, n, !0),
                t.child
            }
            function Rl(e) {
                var t = e.stateNode;
                t.pendingContext ? Pa(0, t.pendingContext, t.pendingContext !== t.context) : t.context && Pa(0, t.context, !1),
                Jo(e, t.containerInfo)
            }
            function Ol(e, t, n, r, a) {
                return mo(),
                ho(a),
                t.flags |= 256,
                xl(e, t, n, r),
                t.child
            }
            var Tl, Ll, Ul, Pl, Il = {
                dehydrated: null,
                treeContext: null,
                retryLane: 0
            };
            function Fl(e) {
                return {
                    baseLanes: e,
                    cachePool: null,
                    transitions: null
                }
            }
            function zl(e, t, n) {
                var r, a = t.pendingProps, i = ei.current, l = !1, s = 0 !== (128 & t.flags);
                if ((r = s) || (r = (null === e || null !== e.memoizedState) && 0 !== (2 & i)),
                r ? (l = !0,
                t.flags &= -129) : null !== e && null === e.memoizedState || (i |= 1),
                ja(ei, 1 & i),
                null === e)
                    return uo(t),
                    null !== (e = t.memoizedState) && null !== (e = e.dehydrated) ? (0 === (1 & t.mode) ? t.lanes = 1 : "$!" === e.data ? t.lanes = 8 : t.lanes = 1073741824,
                    null) : (s = a.children,
                    e = a.fallback,
                    l ? (a = t.mode,
                    l = t.child,
                    s = {
                        mode: "hidden",
                        children: s
                    },
                    0 === (1 & a) && null !== l ? (l.childLanes = 0,
                    l.pendingProps = s) : l = Fu(s, a, 0, null),
                    e = Iu(e, a, n, null),
                    l.return = t,
                    e.return = t,
                    l.sibling = e,
                    t.child = l,
                    t.child.memoizedState = Fl(n),
                    t.memoizedState = Il,
                    e) : Ml(t, s));
                if (null !== (i = e.memoizedState) && null !== (r = i.dehydrated))
                    return function(e, t, n, r, a, i, l) {
                        if (n)
                            return 256 & t.flags ? (t.flags &= -257,
                            Bl(e, t, l, r = cl(Error(o(422))))) : null !== t.memoizedState ? (t.child = e.child,
                            t.flags |= 128,
                            null) : (i = r.fallback,
                            a = t.mode,
                            r = Fu({
                                mode: "visible",
                                children: r.children
                            }, a, 0, null),
                            (i = Iu(i, a, l, null)).flags |= 2,
                            r.return = t,
                            i.return = t,
                            r.sibling = i,
                            t.child = r,
                            0 !== (1 & t.mode) && wo(t, e.child, null, l),
                            t.child.memoizedState = Fl(l),
                            t.memoizedState = Il,
                            i);
                        if (0 === (1 & t.mode))
                            return Bl(e, t, l, null);
                        if ("$!" === a.data) {
                            if (r = a.nextSibling && a.nextSibling.dataset)
                                var s = r.dgst;
                            return r = s,
                            Bl(e, t, l, r = cl(i = Error(o(419)), r, void 0))
                        }
                        if (s = 0 !== (l & e.childLanes),
                        bl || s) {
                            if (null !== (r = Rs)) {
                                switch (l & -l) {
                                case 4:
                                    a = 2;
                                    break;
                                case 16:
                                    a = 8;
                                    break;
                                case 64:
                                case 128:
                                case 256:
                                case 512:
                                case 1024:
                                case 2048:
                                case 4096:
                                case 8192:
                                case 16384:
                                case 32768:
                                case 65536:
                                case 131072:
                                case 262144:
                                case 524288:
                                case 1048576:
                                case 2097152:
                                case 4194304:
                                case 8388608:
                                case 16777216:
                                case 33554432:
                                case 67108864:
                                    a = 32;
                                    break;
                                case 536870912:
                                    a = 268435456;
                                    break;
                                default:
                                    a = 0
                                }
                                0 !== (a = 0 !== (a & (r.suspendedLanes | l)) ? 0 : a) && a !== i.retryLane && (i.retryLane = a,
                                Io(e, a),
                                nu(r, e, a, -1))
                            }
                            return hu(),
                            Bl(e, t, l, r = cl(Error(o(421))))
                        }
                        return "$?" === a.data ? (t.flags |= 128,
                        t.child = e.child,
                        t = Nu.bind(null, e),
                        a._reactRetry = t,
                        null) : (e = i.treeContext,
                        ro = ua(a.nextSibling),
                        no = t,
                        ao = !0,
                        oo = null,
                        null !== e && (Va[Za++] = Ja,
                        Va[Za++] = Xa,
                        Va[Za++] = Ka,
                        Ja = e.id,
                        Xa = e.overflow,
                        Ka = t),
                        t = Ml(t, r.children),
                        t.flags |= 4096,
                        t)
                    }(e, t, s, a, r, i, n);
                if (l) {
                    l = a.fallback,
                    s = t.mode,
                    r = (i = e.child).sibling;
                    var u = {
                        mode: "hidden",
                        children: a.children
                    };
                    return 0 === (1 & s) && t.child !== i ? ((a = t.child).childLanes = 0,
                    a.pendingProps = u,
                    t.deletions = null) : (a = Uu(i, u)).subtreeFlags = 14680064 & i.subtreeFlags,
                    null !== r ? l = Uu(r, l) : (l = Iu(l, s, n, null)).flags |= 2,
                    l.return = t,
                    a.return = t,
                    a.sibling = l,
                    t.child = a,
                    a = l,
                    l = t.child,
                    s = null === (s = e.child.memoizedState) ? Fl(n) : {
                        baseLanes: s.baseLanes | n,
                        cachePool: null,
                        transitions: s.transitions
                    },
                    l.memoizedState = s,
                    l.childLanes = e.childLanes & ~n,
                    t.memoizedState = Il,
                    a
                }
                return e = (l = e.child).sibling,
                a = Uu(l, {
                    mode: "visible",
                    children: a.children
                }),
                0 === (1 & t.mode) && (a.lanes = n),
                a.return = t,
                a.sibling = null,
                null !== e && (null === (n = t.deletions) ? (t.deletions = [e],
                t.flags |= 16) : n.push(e)),
                t.child = a,
                t.memoizedState = null,
                a
            }
            function Ml(e, t) {
                return (t = Fu({
                    mode: "visible",
                    children: t
                }, e.mode, 0, null)).return = e,
                e.child = t
            }
            function Bl(e, t, n, r) {
                return null !== r && ho(r),
                wo(t, e.child, null, n),
                (e = Ml(t, t.pendingProps.children)).flags |= 2,
                t.memoizedState = null,
                e
            }
            function ql(e, t, n) {
                e.lanes |= t;
                var r = e.alternate;
                null !== r && (r.lanes |= t),
                Ro(e.return, t, n)
            }
            function Dl(e, t, n, r, a) {
                var o = e.memoizedState;
                null === o ? e.memoizedState = {
                    isBackwards: t,
                    rendering: null,
                    renderingStartTime: 0,
                    last: r,
                    tail: n,
                    tailMode: a
                } : (o.isBackwards = t,
                o.rendering = null,
                o.renderingStartTime = 0,
                o.last = r,
                o.tail = n,
                o.tailMode = a)
            }
            function Hl(e, t, n) {
                var r = t.pendingProps
                  , a = r.revealOrder
                  , o = r.tail;
                if (xl(e, t, r.children, n),
                0 !== (2 & (r = ei.current)))
                    r = 1 & r | 2,
                    t.flags |= 128;
                else {
                    if (null !== e && 0 !== (128 & e.flags))
                        e: for (e = t.child; null !== e; ) {
                            if (13 === e.tag)
                                null !== e.memoizedState && ql(e, n, t);
                            else if (19 === e.tag)
                                ql(e, n, t);
                            else if (null !== e.child) {
                                e.child.return = e,
                                e = e.child;
                                continue
                            }
                            if (e === t)
                                break e;
                            for (; null === e.sibling; ) {
                                if (null === e.return || e.return === t)
                                    break e;
                                e = e.return
                            }
                            e.sibling.return = e.return,
                            e = e.sibling
                        }
                    r &= 1
                }
                if (ja(ei, r),
                0 === (1 & t.mode))
                    t.memoizedState = null;
                else
                    switch (a) {
                    case "forwards":
                        for (n = t.child,
                        a = null; null !== n; )
                            null !== (e = n.alternate) && null === ti(e) && (a = n),
                            n = n.sibling;
                        null === (n = a) ? (a = t.child,
                        t.child = null) : (a = n.sibling,
                        n.sibling = null),
                        Dl(t, !1, a, n, o);
                        break;
                    case "backwards":
                        for (n = null,
                        a = t.child,
                        t.child = null; null !== a; ) {
                            if (null !== (e = a.alternate) && null === ti(e)) {
                                t.child = a;
                                break
                            }
                            e = a.sibling,
                            a.sibling = n,
                            n = a,
                            a = e
                        }
                        Dl(t, !0, n, null, o);
                        break;
                    case "together":
                        Dl(t, !1, null, null, void 0);
                        break;
                    default:
                        t.memoizedState = null
                    }
                return t.child
            }
            function Ql(e, t) {
                0 === (1 & t.mode) && null !== e && (e.alternate = null,
                t.alternate = null,
                t.flags |= 2)
            }
            function Yl(e, t, n) {
                if (null !== e && (t.dependencies = e.dependencies),
                Fs |= t.lanes,
                0 === (n & t.childLanes))
                    return null;
                if (null !== e && t.child !== e.child)
                    throw Error(o(153));
                if (null !== t.child) {
                    for (n = Uu(e = t.child, e.pendingProps),
                    t.child = n,
                    n.return = t; null !== e.sibling; )
                        e = e.sibling,
                        (n = n.sibling = Uu(e, e.pendingProps)).return = t;
                    n.sibling = null
                }
                return t.child
            }
            function Wl(e, t) {
                if (!ao)
                    switch (e.tailMode) {
                    case "hidden":
                        t = e.tail;
                        for (var n = null; null !== t; )
                            null !== t.alternate && (n = t),
                            t = t.sibling;
                        null === n ? e.tail = null : n.sibling = null;
                        break;
                    case "collapsed":
                        n = e.tail;
                        for (var r = null; null !== n; )
                            null !== n.alternate && (r = n),
                            n = n.sibling;
                        null === r ? t || null === e.tail ? e.tail = null : e.tail.sibling = null : r.sibling = null
                    }
            }
            function Gl(e) {
                var t = null !== e.alternate && e.alternate.child === e.child
                  , n = 0
                  , r = 0;
                if (t)
                    for (var a = e.child; null !== a; )
                        n |= a.lanes | a.childLanes,
                        r |= 14680064 & a.subtreeFlags,
                        r |= 14680064 & a.flags,
                        a.return = e,
                        a = a.sibling;
                else
                    for (a = e.child; null !== a; )
                        n |= a.lanes | a.childLanes,
                        r |= a.subtreeFlags,
                        r |= a.flags,
                        a.return = e,
                        a = a.sibling;
                return e.subtreeFlags |= r,
                e.childLanes = n,
                t
            }
            function Vl(e, t, n) {
                var r = t.pendingProps;
                switch (to(t),
                t.tag) {
                case 2:
                case 16:
                case 15:
                case 0:
                case 11:
                case 7:
                case 8:
                case 12:
                case 9:
                case 14:
                    return Gl(t),
                    null;
                case 1:
                case 17:
                    return La(t.type) && Ua(),
                    Gl(t),
                    null;
                case 3:
                    return r = t.stateNode,
                    Xo(),
                    Ea(Ra),
                    Ea(Ca),
                    ri(),
                    r.pendingContext && (r.context = r.pendingContext,
                    r.pendingContext = null),
                    null !== e && null !== e.child || (po(t) ? t.flags |= 4 : null === e || e.memoizedState.isDehydrated && 0 === (256 & t.flags) || (t.flags |= 1024,
                    null !== oo && (iu(oo),
                    oo = null))),
                    Ll(e, t),
                    Gl(t),
                    null;
                case 5:
                    $o(t);
                    var a = Ko(Zo.current);
                    if (n = t.type,
                    null !== e && null != t.stateNode)
                        Ul(e, t, n, r, a),
                        e.ref !== t.ref && (t.flags |= 512,
                        t.flags |= 2097152);
                    else {
                        if (!r) {
                            if (null === t.stateNode)
                                throw Error(o(166));
                            return Gl(t),
                            null
                        }
                        if (e = Ko(Go.current),
                        po(t)) {
                            r = t.stateNode,
                            n = t.type;
                            var i = t.memoizedProps;
                            switch (r[pa] = t,
                            r[fa] = i,
                            e = 0 !== (1 & t.mode),
                            n) {
                            case "dialog":
                                Br("cancel", r),
                                Br("close", r);
                                break;
                            case "iframe":
                            case "object":
                            case "embed":
                                Br("load", r);
                                break;
                            case "video":
                            case "audio":
                                for (a = 0; a < Ir.length; a++)
                                    Br(Ir[a], r);
                                break;
                            case "source":
                                Br("error", r);
                                break;
                            case "img":
                            case "image":
                            case "link":
                                Br("error", r),
                                Br("load", r);
                                break;
                            case "details":
                                Br("toggle", r);
                                break;
                            case "input":
                                J(r, i),
                                Br("invalid", r);
                                break;
                            case "select":
                                r._wrapperState = {
                                    wasMultiple: !!i.multiple
                                },
                                Br("invalid", r);
                                break;
                            case "textarea":
                                ae(r, i),
                                Br("invalid", r)
                            }
                            for (var s in ye(n, i),
                            a = null,
                            i)
                                if (i.hasOwnProperty(s)) {
                                    var u = i[s];
                                    "children" === s ? "string" === typeof u ? r.textContent !== u && (!0 !== i.suppressHydrationWarning && _r(r.textContent, u, e),
                                    a = ["children", u]) : "number" === typeof u && r.textContent !== "" + u && (!0 !== i.suppressHydrationWarning && _r(r.textContent, u, e),
                                    a = ["children", "" + u]) : l.hasOwnProperty(s) && null != u && "onScroll" === s && Br("scroll", r)
                                }
                            switch (n) {
                            case "input":
                                G(r),
                                $(r, i, !0);
                                break;
                            case "textarea":
                                G(r),
                                ie(r);
                                break;
                            case "select":
                            case "option":
                                break;
                            default:
                                "function" === typeof i.onClick && (r.onclick = $r)
                            }
                            r = a,
                            t.updateQueue = r,
                            null !== r && (t.flags |= 4)
                        } else {
                            s = 9 === a.nodeType ? a : a.ownerDocument,
                            "http://www.w3.org/1999/xhtml" === e && (e = le(n)),
                            "http://www.w3.org/1999/xhtml" === e ? "script" === n ? ((e = s.createElement("div")).innerHTML = "<script><\/script>",
                            e = e.removeChild(e.firstChild)) : "string" === typeof r.is ? e = s.createElement(n, {
                                is: r.is
                            }) : (e = s.createElement(n),
                            "select" === n && (s = e,
                            r.multiple ? s.multiple = !0 : r.size && (s.size = r.size))) : e = s.createElementNS(e, n),
                            e[pa] = t,
                            e[fa] = r,
                            Tl(e, t, !1, !1),
                            t.stateNode = e;
                            e: {
                                switch (s = be(n, r),
                                n) {
                                case "dialog":
                                    Br("cancel", e),
                                    Br("close", e),
                                    a = r;
                                    break;
                                case "iframe":
                                case "object":
                                case "embed":
                                    Br("load", e),
                                    a = r;
                                    break;
                                case "video":
                                case "audio":
                                    for (a = 0; a < Ir.length; a++)
                                        Br(Ir[a], e);
                                    a = r;
                                    break;
                                case "source":
                                    Br("error", e),
                                    a = r;
                                    break;
                                case "img":
                                case "image":
                                case "link":
                                    Br("error", e),
                                    Br("load", e),
                                    a = r;
                                    break;
                                case "details":
                                    Br("toggle", e),
                                    a = r;
                                    break;
                                case "input":
                                    J(e, r),
                                    a = K(e, r),
                                    Br("invalid", e);
                                    break;
                                case "option":
                                default:
                                    a = r;
                                    break;
                                case "select":
                                    e._wrapperState = {
                                        wasMultiple: !!r.multiple
                                    },
                                    a = z({}, r, {
                                        value: void 0
                                    }),
                                    Br("invalid", e);
                                    break;
                                case "textarea":
                                    ae(e, r),
                                    a = re(e, r),
                                    Br("invalid", e)
                                }
                                for (i in ye(n, a),
                                u = a)
                                    if (u.hasOwnProperty(i)) {
                                        var c = u[i];
                                        "style" === i ? ge(e, c) : "dangerouslySetInnerHTML" === i ? null != (c = c ? c.__html : void 0) && de(e, c) : "children" === i ? "string" === typeof c ? ("textarea" !== n || "" !== c) && pe(e, c) : "number" === typeof c && pe(e, "" + c) : "suppressContentEditableWarning" !== i && "suppressHydrationWarning" !== i && "autoFocus" !== i && (l.hasOwnProperty(i) ? null != c && "onScroll" === i && Br("scroll", e) : null != c && b(e, i, c, s))
                                    }
                                switch (n) {
                                case "input":
                                    G(e),
                                    $(e, r, !1);
                                    break;
                                case "textarea":
                                    G(e),
                                    ie(e);
                                    break;
                                case "option":
                                    null != r.value && e.setAttribute("value", "" + Y(r.value));
                                    break;
                                case "select":
                                    e.multiple = !!r.multiple,
                                    null != (i = r.value) ? ne(e, !!r.multiple, i, !1) : null != r.defaultValue && ne(e, !!r.multiple, r.defaultValue, !0);
                                    break;
                                default:
                                    "function" === typeof a.onClick && (e.onclick = $r)
                                }
                                switch (n) {
                                case "button":
                                case "input":
                                case "select":
                                case "textarea":
                                    r = !!r.autoFocus;
                                    break e;
                                case "img":
                                    r = !0;
                                    break e;
                                default:
                                    r = !1
                                }
                            }
                            r && (t.flags |= 4)
                        }
                        null !== t.ref && (t.flags |= 512,
                        t.flags |= 2097152)
                    }
                    return Gl(t),
                    null;
                case 6:
                    if (e && null != t.stateNode)
                        Pl(e, t, e.memoizedProps, r);
                    else {
                        if ("string" !== typeof r && null === t.stateNode)
                            throw Error(o(166));
                        if (n = Ko(Zo.current),
                        Ko(Go.current),
                        po(t)) {
                            if (r = t.stateNode,
                            n = t.memoizedProps,
                            r[pa] = t,
                            (i = r.nodeValue !== n) && null !== (e = no))
                                switch (e.tag) {
                                case 3:
                                    _r(r.nodeValue, n, 0 !== (1 & e.mode));
                                    break;
                                case 5:
                                    !0 !== e.memoizedProps.suppressHydrationWarning && _r(r.nodeValue, n, 0 !== (1 & e.mode))
                                }
                            i && (t.flags |= 4)
                        } else
                            (r = (9 === n.nodeType ? n : n.ownerDocument).createTextNode(r))[pa] = t,
                            t.stateNode = r
                    }
                    return Gl(t),
                    null;
                case 13:
                    if (Ea(ei),
                    r = t.memoizedState,
                    null === e || null !== e.memoizedState && null !== e.memoizedState.dehydrated) {
                        if (ao && null !== ro && 0 !== (1 & t.mode) && 0 === (128 & t.flags))
                            fo(),
                            mo(),
                            t.flags |= 98560,
                            i = !1;
                        else if (i = po(t),
                        null !== r && null !== r.dehydrated) {
                            if (null === e) {
                                if (!i)
                                    throw Error(o(318));
                                if (!(i = null !== (i = t.memoizedState) ? i.dehydrated : null))
                                    throw Error(o(317));
                                i[pa] = t
                            } else
                                mo(),
                                0 === (128 & t.flags) && (t.memoizedState = null),
                                t.flags |= 4;
                            Gl(t),
                            i = !1
                        } else
                            null !== oo && (iu(oo),
                            oo = null),
                            i = !0;
                        if (!i)
                            return 65536 & t.flags ? t : null
                    }
                    return 0 !== (128 & t.flags) ? (t.lanes = n,
                    t) : ((r = null !== r) !== (null !== e && null !== e.memoizedState) && r && (t.child.flags |= 8192,
                    0 !== (1 & t.mode) && (null === e || 0 !== (1 & ei.current) ? 0 === Ps && (Ps = 3) : hu())),
                    null !== t.updateQueue && (t.flags |= 4),
                    Gl(t),
                    null);
                case 4:
                    return Xo(),
                    Ll(e, t),
                    null === e && Hr(t.stateNode.containerInfo),
                    Gl(t),
                    null;
                case 10:
                    return Co(t.type._context),
                    Gl(t),
                    null;
                case 19:
                    if (Ea(ei),
                    null === (i = t.memoizedState))
                        return Gl(t),
                        null;
                    if (r = 0 !== (128 & t.flags),
                    null === (s = i.rendering))
                        if (r)
                            Wl(i, !1);
                        else {
                            if (0 !== Ps || null !== e && 0 !== (128 & e.flags))
                                for (e = t.child; null !== e; ) {
                                    if (null !== (s = ti(e))) {
                                        for (t.flags |= 128,
                                        Wl(i, !1),
                                        null !== (r = s.updateQueue) && (t.updateQueue = r,
                                        t.flags |= 4),
                                        t.subtreeFlags = 0,
                                        r = n,
                                        n = t.child; null !== n; )
                                            e = r,
                                            (i = n).flags &= 14680066,
                                            null === (s = i.alternate) ? (i.childLanes = 0,
                                            i.lanes = e,
                                            i.child = null,
                                            i.subtreeFlags = 0,
                                            i.memoizedProps = null,
                                            i.memoizedState = null,
                                            i.updateQueue = null,
                                            i.dependencies = null,
                                            i.stateNode = null) : (i.childLanes = s.childLanes,
                                            i.lanes = s.lanes,
                                            i.child = s.child,
                                            i.subtreeFlags = 0,
                                            i.deletions = null,
                                            i.memoizedProps = s.memoizedProps,
                                            i.memoizedState = s.memoizedState,
                                            i.updateQueue = s.updateQueue,
                                            i.type = s.type,
                                            e = s.dependencies,
                                            i.dependencies = null === e ? null : {
                                                lanes: e.lanes,
                                                firstContext: e.firstContext
                                            }),
                                            n = n.sibling;
                                        return ja(ei, 1 & ei.current | 2),
                                        t.child
                                    }
                                    e = e.sibling
                                }
                            null !== i.tail && Xe() > Hs && (t.flags |= 128,
                            r = !0,
                            Wl(i, !1),
                            t.lanes = 4194304)
                        }
                    else {
                        if (!r)
                            if (null !== (e = ti(s))) {
                                if (t.flags |= 128,
                                r = !0,
                                null !== (n = e.updateQueue) && (t.updateQueue = n,
                                t.flags |= 4),
                                Wl(i, !0),
                                null === i.tail && "hidden" === i.tailMode && !s.alternate && !ao)
                                    return Gl(t),
                                    null
                            } else
                                2 * Xe() - i.renderingStartTime > Hs && 1073741824 !== n && (t.flags |= 128,
                                r = !0,
                                Wl(i, !1),
                                t.lanes = 4194304);
                        i.isBackwards ? (s.sibling = t.child,
                        t.child = s) : (null !== (n = i.last) ? n.sibling = s : t.child = s,
                        i.last = s)
                    }
                    return null !== i.tail ? (t = i.tail,
                    i.rendering = t,
                    i.tail = t.sibling,
                    i.renderingStartTime = Xe(),
                    t.sibling = null,
                    n = ei.current,
                    ja(ei, r ? 1 & n | 2 : 1 & n),
                    t) : (Gl(t),
                    null);
                case 22:
                case 23:
                    return du(),
                    r = null !== t.memoizedState,
                    null !== e && null !== e.memoizedState !== r && (t.flags |= 8192),
                    r && 0 !== (1 & t.mode) ? 0 !== (1073741824 & Ls) && (Gl(t),
                    6 & t.subtreeFlags && (t.flags |= 8192)) : Gl(t),
                    null;
                case 24:
                case 25:
                    return null
                }
                throw Error(o(156, t.tag))
            }
            function Zl(e, t) {
                switch (to(t),
                t.tag) {
                case 1:
                    return La(t.type) && Ua(),
                    65536 & (e = t.flags) ? (t.flags = -65537 & e | 128,
                    t) : null;
                case 3:
                    return Xo(),
                    Ea(Ra),
                    Ea(Ca),
                    ri(),
                    0 !== (65536 & (e = t.flags)) && 0 === (128 & e) ? (t.flags = -65537 & e | 128,
                    t) : null;
                case 5:
                    return $o(t),
                    null;
                case 13:
                    if (Ea(ei),
                    null !== (e = t.memoizedState) && null !== e.dehydrated) {
                        if (null === t.alternate)
                            throw Error(o(340));
                        mo()
                    }
                    return 65536 & (e = t.flags) ? (t.flags = -65537 & e | 128,
                    t) : null;
                case 19:
                    return Ea(ei),
                    null;
                case 4:
                    return Xo(),
                    null;
                case 10:
                    return Co(t.type._context),
                    null;
                case 22:
                case 23:
                    return du(),
                    null;
                default:
                    return null
                }
            }
            Tl = function(e, t) {
                for (var n = t.child; null !== n; ) {
                    if (5 === n.tag || 6 === n.tag)
                        e.appendChild(n.stateNode);
                    else if (4 !== n.tag && null !== n.child) {
                        n.child.return = n,
                        n = n.child;
                        continue
                    }
                    if (n === t)
                        break;
                    for (; null === n.sibling; ) {
                        if (null === n.return || n.return === t)
                            return;
                        n = n.return
                    }
                    n.sibling.return = n.return,
                    n = n.sibling
                }
            }
            ,
            Ll = function() {}
            ,
            Ul = function(e, t, n, r) {
                var a = e.memoizedProps;
                if (a !== r) {
                    e = t.stateNode,
                    Ko(Go.current);
                    var o, i = null;
                    switch (n) {
                    case "input":
                        a = K(e, a),
                        r = K(e, r),
                        i = [];
                        break;
                    case "select":
                        a = z({}, a, {
                            value: void 0
                        }),
                        r = z({}, r, {
                            value: void 0
                        }),
                        i = [];
                        break;
                    case "textarea":
                        a = re(e, a),
                        r = re(e, r),
                        i = [];
                        break;
                    default:
                        "function" !== typeof a.onClick && "function" === typeof r.onClick && (e.onclick = $r)
                    }
                    for (c in ye(n, r),
                    n = null,
                    a)
                        if (!r.hasOwnProperty(c) && a.hasOwnProperty(c) && null != a[c])
                            if ("style" === c) {
                                var s = a[c];
                                for (o in s)
                                    s.hasOwnProperty(o) && (n || (n = {}),
                                    n[o] = "")
                            } else
                                "dangerouslySetInnerHTML" !== c && "children" !== c && "suppressContentEditableWarning" !== c && "suppressHydrationWarning" !== c && "autoFocus" !== c && (l.hasOwnProperty(c) ? i || (i = []) : (i = i || []).push(c, null));
                    for (c in r) {
                        var u = r[c];
                        if (s = null != a ? a[c] : void 0,
                        r.hasOwnProperty(c) && u !== s && (null != u || null != s))
                            if ("style" === c)
                                if (s) {
                                    for (o in s)
                                        !s.hasOwnProperty(o) || u && u.hasOwnProperty(o) || (n || (n = {}),
                                        n[o] = "");
                                    for (o in u)
                                        u.hasOwnProperty(o) && s[o] !== u[o] && (n || (n = {}),
                                        n[o] = u[o])
                                } else
                                    n || (i || (i = []),
                                    i.push(c, n)),
                                    n = u;
                            else
                                "dangerouslySetInnerHTML" === c ? (u = u ? u.__html : void 0,
                                s = s ? s.__html : void 0,
                                null != u && s !== u && (i = i || []).push(c, u)) : "children" === c ? "string" !== typeof u && "number" !== typeof u || (i = i || []).push(c, "" + u) : "suppressContentEditableWarning" !== c && "suppressHydrationWarning" !== c && (l.hasOwnProperty(c) ? (null != u && "onScroll" === c && Br("scroll", e),
                                i || s === u || (i = [])) : (i = i || []).push(c, u))
                    }
                    n && (i = i || []).push("style", n);
                    var c = i;
                    (t.updateQueue = c) && (t.flags |= 4)
                }
            }
            ,
            Pl = function(e, t, n, r) {
                n !== r && (t.flags |= 4)
            }
            ;
            var Kl = !1
              , Jl = !1
              , Xl = "function" === typeof WeakSet ? WeakSet : Set
              , _l = null;
            function $l(e, t) {
                var n = e.ref;
                if (null !== n)
                    if ("function" === typeof n)
                        try {
                            n(null)
                        } catch (r) {
                            Su(e, t, r)
                        }
                    else
                        n.current = null
            }
            function es(e, t, n) {
                try {
                    n()
                } catch (r) {
                    Su(e, t, r)
                }
            }
            var ts = !1;
            function ns(e, t, n) {
                var r = t.updateQueue;
                if (null !== (r = null !== r ? r.lastEffect : null)) {
                    var a = r = r.next;
                    do {
                        if ((a.tag & e) === e) {
                            var o = a.destroy;
                            a.destroy = void 0,
                            void 0 !== o && es(t, n, o)
                        }
                        a = a.next
                    } while (a !== r)
                }
            }
            function rs(e, t) {
                if (null !== (t = null !== (t = t.updateQueue) ? t.lastEffect : null)) {
                    var n = t = t.next;
                    do {
                        if ((n.tag & e) === e) {
                            var r = n.create;
                            n.destroy = r()
                        }
                        n = n.next
                    } while (n !== t)
                }
            }
            function as(e) {
                var t = e.ref;
                if (null !== t) {
                    var n = e.stateNode;
                    e.tag,
                    e = n,
                    "function" === typeof t ? t(e) : t.current = e
                }
            }
            function os(e) {
                var t = e.alternate;
                null !== t && (e.alternate = null,
                os(t)),
                e.child = null,
                e.deletions = null,
                e.sibling = null,
                5 === e.tag && (null !== (t = e.stateNode) && (delete t[pa],
                delete t[fa],
                delete t[ha],
                delete t[ga],
                delete t[va])),
                e.stateNode = null,
                e.return = null,
                e.dependencies = null,
                e.memoizedProps = null,
                e.memoizedState = null,
                e.pendingProps = null,
                e.stateNode = null,
                e.updateQueue = null
            }
            function is(e) {
                return 5 === e.tag || 3 === e.tag || 4 === e.tag
            }
            function ls(e) {
                e: for (; ; ) {
                    for (; null === e.sibling; ) {
                        if (null === e.return || is(e.return))
                            return null;
                        e = e.return
                    }
                    for (e.sibling.return = e.return,
                    e = e.sibling; 5 !== e.tag && 6 !== e.tag && 18 !== e.tag; ) {
                        if (2 & e.flags)
                            continue e;
                        if (null === e.child || 4 === e.tag)
                            continue e;
                        e.child.return = e,
                        e = e.child
                    }
                    if (!(2 & e.flags))
                        return e.stateNode
                }
            }
            function ss(e, t, n) {
                var r = e.tag;
                if (5 === r || 6 === r)
                    e = e.stateNode,
                    t ? 8 === n.nodeType ? n.parentNode.insertBefore(e, t) : n.insertBefore(e, t) : (8 === n.nodeType ? (t = n.parentNode).insertBefore(e, n) : (t = n).appendChild(e),
                    null !== (n = n._reactRootContainer) && void 0 !== n || null !== t.onclick || (t.onclick = $r));
                else if (4 !== r && null !== (e = e.child))
                    for (ss(e, t, n),
                    e = e.sibling; null !== e; )
                        ss(e, t, n),
                        e = e.sibling
            }
            function us(e, t, n) {
                var r = e.tag;
                if (5 === r || 6 === r)
                    e = e.stateNode,
                    t ? n.insertBefore(e, t) : n.appendChild(e);
                else if (4 !== r && null !== (e = e.child))
                    for (us(e, t, n),
                    e = e.sibling; null !== e; )
                        us(e, t, n),
                        e = e.sibling
            }
            var cs = null
              , ds = !1;
            function ps(e, t, n) {
                for (n = n.child; null !== n; )
                    fs(e, t, n),
                    n = n.sibling
            }
            function fs(e, t, n) {
                if (ot && "function" === typeof ot.onCommitFiberUnmount)
                    try {
                        ot.onCommitFiberUnmount(at, n)
                    } catch (l) {}
                switch (n.tag) {
                case 5:
                    Jl || $l(n, t);
                case 6:
                    var r = cs
                      , a = ds;
                    cs = null,
                    ps(e, t, n),
                    ds = a,
                    null !== (cs = r) && (ds ? (e = cs,
                    n = n.stateNode,
                    8 === e.nodeType ? e.parentNode.removeChild(n) : e.removeChild(n)) : cs.removeChild(n.stateNode));
                    break;
                case 18:
                    null !== cs && (ds ? (e = cs,
                    n = n.stateNode,
                    8 === e.nodeType ? sa(e.parentNode, n) : 1 === e.nodeType && sa(e, n),
                    Ht(e)) : sa(cs, n.stateNode));
                    break;
                case 4:
                    r = cs,
                    a = ds,
                    cs = n.stateNode.containerInfo,
                    ds = !0,
                    ps(e, t, n),
                    cs = r,
                    ds = a;
                    break;
                case 0:
                case 11:
                case 14:
                case 15:
                    if (!Jl && (null !== (r = n.updateQueue) && null !== (r = r.lastEffect))) {
                        a = r = r.next;
                        do {
                            var o = a
                              , i = o.destroy;
                            o = o.tag,
                            void 0 !== i && (0 !== (2 & o) || 0 !== (4 & o)) && es(n, t, i),
                            a = a.next
                        } while (a !== r)
                    }
                    ps(e, t, n);
                    break;
                case 1:
                    if (!Jl && ($l(n, t),
                    "function" === typeof (r = n.stateNode).componentWillUnmount))
                        try {
                            r.props = n.memoizedProps,
                            r.state = n.memoizedState,
                            r.componentWillUnmount()
                        } catch (l) {
                            Su(n, t, l)
                        }
                    ps(e, t, n);
                    break;
                case 21:
                    ps(e, t, n);
                    break;
                case 22:
                    1 & n.mode ? (Jl = (r = Jl) || null !== n.memoizedState,
                    ps(e, t, n),
                    Jl = r) : ps(e, t, n);
                    break;
                default:
                    ps(e, t, n)
                }
            }
            function ms(e) {
                var t = e.updateQueue;
                if (null !== t) {
                    e.updateQueue = null;
                    var n = e.stateNode;
                    null === n && (n = e.stateNode = new Xl),
                    t.forEach((function(t) {
                        var r = Cu.bind(null, e, t);
                        n.has(t) || (n.add(t),
                        t.then(r, r))
                    }
                    ))
                }
            }
            function hs(e, t) {
                var n = t.deletions;
                if (null !== n)
                    for (var r = 0; r < n.length; r++) {
                        var a = n[r];
                        try {
                            var i = e
                              , l = t
                              , s = l;
                            e: for (; null !== s; ) {
                                switch (s.tag) {
                                case 5:
                                    cs = s.stateNode,
                                    ds = !1;
                                    break e;
                                case 3:
                                case 4:
                                    cs = s.stateNode.containerInfo,
                                    ds = !0;
                                    break e
                                }
                                s = s.return
                            }
                            if (null === cs)
                                throw Error(o(160));
                            fs(i, l, a),
                            cs = null,
                            ds = !1;
                            var u = a.alternate;
                            null !== u && (u.return = null),
                            a.return = null
                        } catch (c) {
                            Su(a, t, c)
                        }
                    }
                if (12854 & t.subtreeFlags)
                    for (t = t.child; null !== t; )
                        gs(t, e),
                        t = t.sibling
            }
            function gs(e, t) {
                var n = e.alternate
                  , r = e.flags;
                switch (e.tag) {
                case 0:
                case 11:
                case 14:
                case 15:
                    if (hs(t, e),
                    vs(e),
                    4 & r) {
                        try {
                            ns(3, e, e.return),
                            rs(3, e)
                        } catch (g) {
                            Su(e, e.return, g)
                        }
                        try {
                            ns(5, e, e.return)
                        } catch (g) {
                            Su(e, e.return, g)
                        }
                    }
                    break;
                case 1:
                    hs(t, e),
                    vs(e),
                    512 & r && null !== n && $l(n, n.return);
                    break;
                case 5:
                    if (hs(t, e),
                    vs(e),
                    512 & r && null !== n && $l(n, n.return),
                    32 & e.flags) {
                        var a = e.stateNode;
                        try {
                            pe(a, "")
                        } catch (g) {
                            Su(e, e.return, g)
                        }
                    }
                    if (4 & r && null != (a = e.stateNode)) {
                        var i = e.memoizedProps
                          , l = null !== n ? n.memoizedProps : i
                          , s = e.type
                          , u = e.updateQueue;
                        if (e.updateQueue = null,
                        null !== u)
                            try {
                                "input" === s && "radio" === i.type && null != i.name && X(a, i),
                                be(s, l);
                                var c = be(s, i);
                                for (l = 0; l < u.length; l += 2) {
                                    var d = u[l]
                                      , p = u[l + 1];
                                    "style" === d ? ge(a, p) : "dangerouslySetInnerHTML" === d ? de(a, p) : "children" === d ? pe(a, p) : b(a, d, p, c)
                                }
                                switch (s) {
                                case "input":
                                    _(a, i);
                                    break;
                                case "textarea":
                                    oe(a, i);
                                    break;
                                case "select":
                                    var f = a._wrapperState.wasMultiple;
                                    a._wrapperState.wasMultiple = !!i.multiple;
                                    var m = i.value;
                                    null != m ? ne(a, !!i.multiple, m, !1) : f !== !!i.multiple && (null != i.defaultValue ? ne(a, !!i.multiple, i.defaultValue, !0) : ne(a, !!i.multiple, i.multiple ? [] : "", !1))
                                }
                                a[fa] = i
                            } catch (g) {
                                Su(e, e.return, g)
                            }
                    }
                    break;
                case 6:
                    if (hs(t, e),
                    vs(e),
                    4 & r) {
                        if (null === e.stateNode)
                            throw Error(o(162));
                        a = e.stateNode,
                        i = e.memoizedProps;
                        try {
                            a.nodeValue = i
                        } catch (g) {
                            Su(e, e.return, g)
                        }
                    }
                    break;
                case 3:
                    if (hs(t, e),
                    vs(e),
                    4 & r && null !== n && n.memoizedState.isDehydrated)
                        try {
                            Ht(t.containerInfo)
                        } catch (g) {
                            Su(e, e.return, g)
                        }
                    break;
                case 4:
                default:
                    hs(t, e),
                    vs(e);
                    break;
                case 13:
                    hs(t, e),
                    vs(e),
                    8192 & (a = e.child).flags && (i = null !== a.memoizedState,
                    a.stateNode.isHidden = i,
                    !i || null !== a.alternate && null !== a.alternate.memoizedState || (Ds = Xe())),
                    4 & r && ms(e);
                    break;
                case 22:
                    if (d = null !== n && null !== n.memoizedState,
                    1 & e.mode ? (Jl = (c = Jl) || d,
                    hs(t, e),
                    Jl = c) : hs(t, e),
                    vs(e),
                    8192 & r) {
                        if (c = null !== e.memoizedState,
                        (e.stateNode.isHidden = c) && !d && 0 !== (1 & e.mode))
                            for (_l = e,
                            d = e.child; null !== d; ) {
                                for (p = _l = d; null !== _l; ) {
                                    switch (m = (f = _l).child,
                                    f.tag) {
                                    case 0:
                                    case 11:
                                    case 14:
                                    case 15:
                                        ns(4, f, f.return);
                                        break;
                                    case 1:
                                        $l(f, f.return);
                                        var h = f.stateNode;
                                        if ("function" === typeof h.componentWillUnmount) {
                                            r = f,
                                            n = f.return;
                                            try {
                                                t = r,
                                                h.props = t.memoizedProps,
                                                h.state = t.memoizedState,
                                                h.componentWillUnmount()
                                            } catch (g) {
                                                Su(r, n, g)
                                            }
                                        }
                                        break;
                                    case 5:
                                        $l(f, f.return);
                                        break;
                                    case 22:
                                        if (null !== f.memoizedState) {
                                            ws(p);
                                            continue
                                        }
                                    }
                                    null !== m ? (m.return = f,
                                    _l = m) : ws(p)
                                }
                                d = d.sibling
                            }
                        e: for (d = null,
                        p = e; ; ) {
                            if (5 === p.tag) {
                                if (null === d) {
                                    d = p;
                                    try {
                                        a = p.stateNode,
                                        c ? "function" === typeof (i = a.style).setProperty ? i.setProperty("display", "none", "important") : i.display = "none" : (s = p.stateNode,
                                        l = void 0 !== (u = p.memoizedProps.style) && null !== u && u.hasOwnProperty("display") ? u.display : null,
                                        s.style.display = he("display", l))
                                    } catch (g) {
                                        Su(e, e.return, g)
                                    }
                                }
                            } else if (6 === p.tag) {
                                if (null === d)
                                    try {
                                        p.stateNode.nodeValue = c ? "" : p.memoizedProps
                                    } catch (g) {
                                        Su(e, e.return, g)
                                    }
                            } else if ((22 !== p.tag && 23 !== p.tag || null === p.memoizedState || p === e) && null !== p.child) {
                                p.child.return = p,
                                p = p.child;
                                continue
                            }
                            if (p === e)
                                break e;
                            for (; null === p.sibling; ) {
                                if (null === p.return || p.return === e)
                                    break e;
                                d === p && (d = null),
                                p = p.return
                            }
                            d === p && (d = null),
                            p.sibling.return = p.return,
                            p = p.sibling
                        }
                    }
                    break;
                case 19:
                    hs(t, e),
                    vs(e),
                    4 & r && ms(e);
                case 21:
                }
            }
            function vs(e) {
                var t = e.flags;
                if (2 & t) {
                    try {
                        e: {
                            for (var n = e.return; null !== n; ) {
                                if (is(n)) {
                                    var r = n;
                                    break e
                                }
                                n = n.return
                            }
                            throw Error(o(160))
                        }
                        switch (r.tag) {
                        case 5:
                            var a = r.stateNode;
                            32 & r.flags && (pe(a, ""),
                            r.flags &= -33),
                            us(e, ls(e), a);
                            break;
                        case 3:
                        case 4:
                            var i = r.stateNode.containerInfo;
                            ss(e, ls(e), i);
                            break;
                        default:
                            throw Error(o(161))
                        }
                    } catch (l) {
                        Su(e, e.return, l)
                    }
                    e.flags &= -3
                }
                4096 & t && (e.flags &= -4097)
            }
            function ys(e, t, n) {
                _l = e,
                bs(e, t, n)
            }
            function bs(e, t, n) {
                for (var r = 0 !== (1 & e.mode); null !== _l; ) {
                    var a = _l
                      , o = a.child;
                    if (22 === a.tag && r) {
                        var i = null !== a.memoizedState || Kl;
                        if (!i) {
                            var l = a.alternate
                              , s = null !== l && null !== l.memoizedState || Jl;
                            l = Kl;
                            var u = Jl;
                            if (Kl = i,
                            (Jl = s) && !u)
                                for (_l = a; null !== _l; )
                                    s = (i = _l).child,
                                    22 === i.tag && null !== i.memoizedState ? As(a) : null !== s ? (s.return = i,
                                    _l = s) : As(a);
                            for (; null !== o; )
                                _l = o,
                                bs(o, t, n),
                                o = o.sibling;
                            _l = a,
                            Kl = l,
                            Jl = u
                        }
                        xs(e)
                    } else
                        0 !== (8772 & a.subtreeFlags) && null !== o ? (o.return = a,
                        _l = o) : xs(e)
                }
            }
            function xs(e) {
                for (; null !== _l; ) {
                    var t = _l;
                    if (0 !== (8772 & t.flags)) {
                        var n = t.alternate;
                        try {
                            if (0 !== (8772 & t.flags))
                                switch (t.tag) {
                                case 0:
                                case 11:
                                case 15:
                                    Jl || rs(5, t);
                                    break;
                                case 1:
                                    var r = t.stateNode;
                                    if (4 & t.flags && !Jl)
                                        if (null === n)
                                            r.componentDidMount();
                                        else {
                                            var a = t.elementType === t.type ? n.memoizedProps : nl(t.type, n.memoizedProps);
                                            r.componentDidUpdate(a, n.memoizedState, r.__reactInternalSnapshotBeforeUpdate)
                                        }
                                    var i = t.updateQueue;
                                    null !== i && Yo(t, i, r);
                                    break;
                                case 3:
                                    var l = t.updateQueue;
                                    if (null !== l) {
                                        if (n = null,
                                        null !== t.child)
                                            switch (t.child.tag) {
                                            case 5:
                                            case 1:
                                                n = t.child.stateNode
                                            }
                                        Yo(t, l, n)
                                    }
                                    break;
                                case 5:
                                    var s = t.stateNode;
                                    if (null === n && 4 & t.flags) {
                                        n = s;
                                        var u = t.memoizedProps;
                                        switch (t.type) {
                                        case "button":
                                        case "input":
                                        case "select":
                                        case "textarea":
                                            u.autoFocus && n.focus();
                                            break;
                                        case "img":
                                            u.src && (n.src = u.src)
                                        }
                                    }
                                    break;
                                case 6:
                                case 4:
                                case 12:
                                case 19:
                                case 17:
                                case 21:
                                case 22:
                                case 23:
                                case 25:
                                    break;
                                case 13:
                                    if (null === t.memoizedState) {
                                        var c = t.alternate;
                                        if (null !== c) {
                                            var d = c.memoizedState;
                                            if (null !== d) {
                                                var p = d.dehydrated;
                                                null !== p && Ht(p)
                                            }
                                        }
                                    }
                                    break;
                                default:
                                    throw Error(o(163))
                                }
                            Jl || 512 & t.flags && as(t)
                        } catch (f) {
                            Su(t, t.return, f)
                        }
                    }
                    if (t === e) {
                        _l = null;
                        break
                    }
                    if (null !== (n = t.sibling)) {
                        n.return = t.return,
                        _l = n;
                        break
                    }
                    _l = t.return
                }
            }
            function ws(e) {
                for (; null !== _l; ) {
                    var t = _l;
                    if (t === e) {
                        _l = null;
                        break
                    }
                    var n = t.sibling;
                    if (null !== n) {
                        n.return = t.return,
                        _l = n;
                        break
                    }
                    _l = t.return
                }
            }
            function As(e) {
                for (; null !== _l; ) {
                    var t = _l;
                    try {
                        switch (t.tag) {
                        case 0:
                        case 11:
                        case 15:
                            var n = t.return;
                            try {
                                rs(4, t)
                            } catch (s) {
                                Su(t, n, s)
                            }
                            break;
                        case 1:
                            var r = t.stateNode;
                            if ("function" === typeof r.componentDidMount) {
                                var a = t.return;
                                try {
                                    r.componentDidMount()
                                } catch (s) {
                                    Su(t, a, s)
                                }
                            }
                            var o = t.return;
                            try {
                                as(t)
                            } catch (s) {
                                Su(t, o, s)
                            }
                            break;
                        case 5:
                            var i = t.return;
                            try {
                                as(t)
                            } catch (s) {
                                Su(t, i, s)
                            }
                        }
                    } catch (s) {
                        Su(t, t.return, s)
                    }
                    if (t === e) {
                        _l = null;
                        break
                    }
                    var l = t.sibling;
                    if (null !== l) {
                        l.return = t.return,
                        _l = l;
                        break
                    }
                    _l = t.return
                }
            }
            var ks, Ss = Math.ceil, Es = x.ReactCurrentDispatcher, js = x.ReactCurrentOwner, Ns = x.ReactCurrentBatchConfig, Cs = 0, Rs = null, Os = null, Ts = 0, Ls = 0, Us = Sa(0), Ps = 0, Is = null, Fs = 0, zs = 0, Ms = 0, Bs = null, qs = null, Ds = 0, Hs = 1 / 0, Qs = null, Ys = !1, Ws = null, Gs = null, Vs = !1, Zs = null, Ks = 0, Js = 0, Xs = null, _s = -1, $s = 0;
            function eu() {
                return 0 !== (6 & Cs) ? Xe() : -1 !== _s ? _s : _s = Xe()
            }
            function tu(e) {
                return 0 === (1 & e.mode) ? 1 : 0 !== (2 & Cs) && 0 !== Ts ? Ts & -Ts : null !== go.transition ? (0 === $s && ($s = ht()),
                $s) : 0 !== (e = bt) ? e : e = void 0 === (e = window.event) ? 16 : Jt(e.type)
            }
            function nu(e, t, n, r) {
                if (50 < Js)
                    throw Js = 0,
                    Xs = null,
                    Error(o(185));
                vt(e, n, r),
                0 !== (2 & Cs) && e === Rs || (e === Rs && (0 === (2 & Cs) && (zs |= n),
                4 === Ps && lu(e, Ts)),
                ru(e, r),
                1 === n && 0 === Cs && 0 === (1 & t.mode) && (Hs = Xe() + 500,
                Ba && Ha()))
            }
            function ru(e, t) {
                var n = e.callbackNode;
                !function(e, t) {
                    for (var n = e.suspendedLanes, r = e.pingedLanes, a = e.expirationTimes, o = e.pendingLanes; 0 < o; ) {
                        var i = 31 - it(o)
                          , l = 1 << i
                          , s = a[i];
                        -1 === s ? 0 !== (l & n) && 0 === (l & r) || (a[i] = ft(l, t)) : s <= t && (e.expiredLanes |= l),
                        o &= ~l
                    }
                }(e, t);
                var r = pt(e, e === Rs ? Ts : 0);
                if (0 === r)
                    null !== n && Ze(n),
                    e.callbackNode = null,
                    e.callbackPriority = 0;
                else if (t = r & -r,
                e.callbackPriority !== t) {
                    if (null != n && Ze(n),
                    1 === t)
                        0 === e.tag ? function(e) {
                            Ba = !0,
                            Da(e)
                        }(su.bind(null, e)) : Da(su.bind(null, e)),
                        ia((function() {
                            0 === (6 & Cs) && Ha()
                        }
                        )),
                        n = null;
                    else {
                        switch (xt(r)) {
                        case 1:
                            n = $e;
                            break;
                        case 4:
                            n = et;
                            break;
                        case 16:
                        default:
                            n = tt;
                            break;
                        case 536870912:
                            n = rt
                        }
                        n = Ru(n, au.bind(null, e))
                    }
                    e.callbackPriority = t,
                    e.callbackNode = n
                }
            }
            function au(e, t) {
                if (_s = -1,
                $s = 0,
                0 !== (6 & Cs))
                    throw Error(o(327));
                var n = e.callbackNode;
                if (Au() && e.callbackNode !== n)
                    return null;
                var r = pt(e, e === Rs ? Ts : 0);
                if (0 === r)
                    return null;
                if (0 !== (30 & r) || 0 !== (r & e.expiredLanes) || t)
                    t = gu(e, r);
                else {
                    t = r;
                    var a = Cs;
                    Cs |= 2;
                    var i = mu();
                    for (Rs === e && Ts === t || (Qs = null,
                    Hs = Xe() + 500,
                    pu(e, t)); ; )
                        try {
                            yu();
                            break
                        } catch (s) {
                            fu(e, s)
                        }
                    No(),
                    Es.current = i,
                    Cs = a,
                    null !== Os ? t = 0 : (Rs = null,
                    Ts = 0,
                    t = Ps)
                }
                if (0 !== t) {
                    if (2 === t && (0 !== (a = mt(e)) && (r = a,
                    t = ou(e, a))),
                    1 === t)
                        throw n = Is,
                        pu(e, 0),
                        lu(e, r),
                        ru(e, Xe()),
                        n;
                    if (6 === t)
                        lu(e, r);
                    else {
                        if (a = e.current.alternate,
                        0 === (30 & r) && !function(e) {
                            for (var t = e; ; ) {
                                if (16384 & t.flags) {
                                    var n = t.updateQueue;
                                    if (null !== n && null !== (n = n.stores))
                                        for (var r = 0; r < n.length; r++) {
                                            var a = n[r]
                                              , o = a.getSnapshot;
                                            a = a.value;
                                            try {
                                                if (!lr(o(), a))
                                                    return !1
                                            } catch (l) {
                                                return !1
                                            }
                                        }
                                }
                                if (n = t.child,
                                16384 & t.subtreeFlags && null !== n)
                                    n.return = t,
                                    t = n;
                                else {
                                    if (t === e)
                                        break;
                                    for (; null === t.sibling; ) {
                                        if (null === t.return || t.return === e)
                                            return !0;
                                        t = t.return
                                    }
                                    t.sibling.return = t.return,
                                    t = t.sibling
                                }
                            }
                            return !0
                        }(a) && (2 === (t = gu(e, r)) && (0 !== (i = mt(e)) && (r = i,
                        t = ou(e, i))),
                        1 === t))
                            throw n = Is,
                            pu(e, 0),
                            lu(e, r),
                            ru(e, Xe()),
                            n;
                        switch (e.finishedWork = a,
                        e.finishedLanes = r,
                        t) {
                        case 0:
                        case 1:
                            throw Error(o(345));
                        case 2:
                        case 5:
                            wu(e, qs, Qs);
                            break;
                        case 3:
                            if (lu(e, r),
                            (130023424 & r) === r && 10 < (t = Ds + 500 - Xe())) {
                                if (0 !== pt(e, 0))
                                    break;
                                if (((a = e.suspendedLanes) & r) !== r) {
                                    eu(),
                                    e.pingedLanes |= e.suspendedLanes & a;
                                    break
                                }
                                e.timeoutHandle = ra(wu.bind(null, e, qs, Qs), t);
                                break
                            }
                            wu(e, qs, Qs);
                            break;
                        case 4:
                            if (lu(e, r),
                            (4194240 & r) === r)
                                break;
                            for (t = e.eventTimes,
                            a = -1; 0 < r; ) {
                                var l = 31 - it(r);
                                i = 1 << l,
                                (l = t[l]) > a && (a = l),
                                r &= ~i
                            }
                            if (r = a,
                            10 < (r = (120 > (r = Xe() - r) ? 120 : 480 > r ? 480 : 1080 > r ? 1080 : 1920 > r ? 1920 : 3e3 > r ? 3e3 : 4320 > r ? 4320 : 1960 * Ss(r / 1960)) - r)) {
                                e.timeoutHandle = ra(wu.bind(null, e, qs, Qs), r);
                                break
                            }
                            wu(e, qs, Qs);
                            break;
                        default:
                            throw Error(o(329))
                        }
                    }
                }
                return ru(e, Xe()),
                e.callbackNode === n ? au.bind(null, e) : null
            }
            function ou(e, t) {
                var n = Bs;
                return e.current.memoizedState.isDehydrated && (pu(e, t).flags |= 256),
                2 !== (e = gu(e, t)) && (t = qs,
                qs = n,
                null !== t && iu(t)),
                e
            }
            function iu(e) {
                null === qs ? qs = e : qs.push.apply(qs, e)
            }
            function lu(e, t) {
                for (t &= ~Ms,
                t &= ~zs,
                e.suspendedLanes |= t,
                e.pingedLanes &= ~t,
                e = e.expirationTimes; 0 < t; ) {
                    var n = 31 - it(t)
                      , r = 1 << n;
                    e[n] = -1,
                    t &= ~r
                }
            }
            function su(e) {
                if (0 !== (6 & Cs))
                    throw Error(o(327));
                Au();
                var t = pt(e, 0);
                if (0 === (1 & t))
                    return ru(e, Xe()),
                    null;
                var n = gu(e, t);
                if (0 !== e.tag && 2 === n) {
                    var r = mt(e);
                    0 !== r && (t = r,
                    n = ou(e, r))
                }
                if (1 === n)
                    throw n = Is,
                    pu(e, 0),
                    lu(e, t),
                    ru(e, Xe()),
                    n;
                if (6 === n)
                    throw Error(o(345));
                return e.finishedWork = e.current.alternate,
                e.finishedLanes = t,
                wu(e, qs, Qs),
                ru(e, Xe()),
                null
            }
            function uu(e, t) {
                var n = Cs;
                Cs |= 1;
                try {
                    return e(t)
                } finally {
                    0 === (Cs = n) && (Hs = Xe() + 500,
                    Ba && Ha())
                }
            }
            function cu(e) {
                null !== Zs && 0 === Zs.tag && 0 === (6 & Cs) && Au();
                var t = Cs;
                Cs |= 1;
                var n = Ns.transition
                  , r = bt;
                try {
                    if (Ns.transition = null,
                    bt = 1,
                    e)
                        return e()
                } finally {
                    bt = r,
                    Ns.transition = n,
                    0 === (6 & (Cs = t)) && Ha()
                }
            }
            function du() {
                Ls = Us.current,
                Ea(Us)
            }
            function pu(e, t) {
                e.finishedWork = null,
                e.finishedLanes = 0;
                var n = e.timeoutHandle;
                if (-1 !== n && (e.timeoutHandle = -1,
                aa(n)),
                null !== Os)
                    for (n = Os.return; null !== n; ) {
                        var r = n;
                        switch (to(r),
                        r.tag) {
                        case 1:
                            null !== (r = r.type.childContextTypes) && void 0 !== r && Ua();
                            break;
                        case 3:
                            Xo(),
                            Ea(Ra),
                            Ea(Ca),
                            ri();
                            break;
                        case 5:
                            $o(r);
                            break;
                        case 4:
                            Xo();
                            break;
                        case 13:
                        case 19:
                            Ea(ei);
                            break;
                        case 10:
                            Co(r.type._context);
                            break;
                        case 22:
                        case 23:
                            du()
                        }
                        n = n.return
                    }
                if (Rs = e,
                Os = e = Uu(e.current, null),
                Ts = Ls = t,
                Ps = 0,
                Is = null,
                Ms = zs = Fs = 0,
                qs = Bs = null,
                null !== Lo) {
                    for (t = 0; t < Lo.length; t++)
                        if (null !== (r = (n = Lo[t]).interleaved)) {
                            n.interleaved = null;
                            var a = r.next
                              , o = n.pending;
                            if (null !== o) {
                                var i = o.next;
                                o.next = a,
                                r.next = i
                            }
                            n.pending = r
                        }
                    Lo = null
                }
                return e
            }
            function fu(e, t) {
                for (; ; ) {
                    var n = Os;
                    try {
                        if (No(),
                        ai.current = _i,
                        ci) {
                            for (var r = li.memoizedState; null !== r; ) {
                                var a = r.queue;
                                null !== a && (a.pending = null),
                                r = r.next
                            }
                            ci = !1
                        }
                        if (ii = 0,
                        ui = si = li = null,
                        di = !1,
                        pi = 0,
                        js.current = null,
                        null === n || null === n.return) {
                            Ps = 1,
                            Is = t,
                            Os = null;
                            break
                        }
                        e: {
                            var i = e
                              , l = n.return
                              , s = n
                              , u = t;
                            if (t = Ts,
                            s.flags |= 32768,
                            null !== u && "object" === typeof u && "function" === typeof u.then) {
                                var c = u
                                  , d = s
                                  , p = d.tag;
                                if (0 === (1 & d.mode) && (0 === p || 11 === p || 15 === p)) {
                                    var f = d.alternate;
                                    f ? (d.updateQueue = f.updateQueue,
                                    d.memoizedState = f.memoizedState,
                                    d.lanes = f.lanes) : (d.updateQueue = null,
                                    d.memoizedState = null)
                                }
                                var m = gl(l);
                                if (null !== m) {
                                    m.flags &= -257,
                                    vl(m, l, s, 0, t),
                                    1 & m.mode && hl(i, c, t),
                                    u = c;
                                    var h = (t = m).updateQueue;
                                    if (null === h) {
                                        var g = new Set;
                                        g.add(u),
                                        t.updateQueue = g
                                    } else
                                        h.add(u);
                                    break e
                                }
                                if (0 === (1 & t)) {
                                    hl(i, c, t),
                                    hu();
                                    break e
                                }
                                u = Error(o(426))
                            } else if (ao && 1 & s.mode) {
                                var v = gl(l);
                                if (null !== v) {
                                    0 === (65536 & v.flags) && (v.flags |= 256),
                                    vl(v, l, s, 0, t),
                                    ho(ul(u, s));
                                    break e
                                }
                            }
                            i = u = ul(u, s),
                            4 !== Ps && (Ps = 2),
                            null === Bs ? Bs = [i] : Bs.push(i),
                            i = l;
                            do {
                                switch (i.tag) {
                                case 3:
                                    i.flags |= 65536,
                                    t &= -t,
                                    i.lanes |= t,
                                    Ho(i, fl(0, u, t));
                                    break e;
                                case 1:
                                    s = u;
                                    var y = i.type
                                      , b = i.stateNode;
                                    if (0 === (128 & i.flags) && ("function" === typeof y.getDerivedStateFromError || null !== b && "function" === typeof b.componentDidCatch && (null === Gs || !Gs.has(b)))) {
                                        i.flags |= 65536,
                                        t &= -t,
                                        i.lanes |= t,
                                        Ho(i, ml(i, s, t));
                                        break e
                                    }
                                }
                                i = i.return
                            } while (null !== i)
                        }
                        xu(n)
                    } catch (x) {
                        t = x,
                        Os === n && null !== n && (Os = n = n.return);
                        continue
                    }
                    break
                }
            }
            function mu() {
                var e = Es.current;
                return Es.current = _i,
                null === e ? _i : e
            }
            function hu() {
                0 !== Ps && 3 !== Ps && 2 !== Ps || (Ps = 4),
                null === Rs || 0 === (268435455 & Fs) && 0 === (268435455 & zs) || lu(Rs, Ts)
            }
            function gu(e, t) {
                var n = Cs;
                Cs |= 2;
                var r = mu();
                for (Rs === e && Ts === t || (Qs = null,
                pu(e, t)); ; )
                    try {
                        vu();
                        break
                    } catch (a) {
                        fu(e, a)
                    }
                if (No(),
                Cs = n,
                Es.current = r,
                null !== Os)
                    throw Error(o(261));
                return Rs = null,
                Ts = 0,
                Ps
            }
            function vu() {
                for (; null !== Os; )
                    bu(Os)
            }
            function yu() {
                for (; null !== Os && !Ke(); )
                    bu(Os)
            }
            function bu(e) {
                var t = ks(e.alternate, e, Ls);
                e.memoizedProps = e.pendingProps,
                null === t ? xu(e) : Os = t,
                js.current = null
            }
            function xu(e) {
                var t = e;
                do {
                    var n = t.alternate;
                    if (e = t.return,
                    0 === (32768 & t.flags)) {
                        if (null !== (n = Vl(n, t, Ls)))
                            return void (Os = n)
                    } else {
                        if (null !== (n = Zl(n, t)))
                            return n.flags &= 32767,
                            void (Os = n);
                        if (null === e)
                            return Ps = 6,
                            void (Os = null);
                        e.flags |= 32768,
                        e.subtreeFlags = 0,
                        e.deletions = null
                    }
                    if (null !== (t = t.sibling))
                        return void (Os = t);
                    Os = t = e
                } while (null !== t);
                0 === Ps && (Ps = 5)
            }
            function wu(e, t, n) {
                var r = bt
                  , a = Ns.transition;
                try {
                    Ns.transition = null,
                    bt = 1,
                    function(e, t, n, r) {
                        do {
                            Au()
                        } while (null !== Zs);
                        if (0 !== (6 & Cs))
                            throw Error(o(327));
                        n = e.finishedWork;
                        var a = e.finishedLanes;
                        if (null === n)
                            return null;
                        if (e.finishedWork = null,
                        e.finishedLanes = 0,
                        n === e.current)
                            throw Error(o(177));
                        e.callbackNode = null,
                        e.callbackPriority = 0;
                        var i = n.lanes | n.childLanes;
                        if (function(e, t) {
                            var n = e.pendingLanes & ~t;
                            e.pendingLanes = t,
                            e.suspendedLanes = 0,
                            e.pingedLanes = 0,
                            e.expiredLanes &= t,
                            e.mutableReadLanes &= t,
                            e.entangledLanes &= t,
                            t = e.entanglements;
                            var r = e.eventTimes;
                            for (e = e.expirationTimes; 0 < n; ) {
                                var a = 31 - it(n)
                                  , o = 1 << a;
                                t[a] = 0,
                                r[a] = -1,
                                e[a] = -1,
                                n &= ~o
                            }
                        }(e, i),
                        e === Rs && (Os = Rs = null,
                        Ts = 0),
                        0 === (2064 & n.subtreeFlags) && 0 === (2064 & n.flags) || Vs || (Vs = !0,
                        Ru(tt, (function() {
                            return Au(),
                            null
                        }
                        ))),
                        i = 0 !== (15990 & n.flags),
                        0 !== (15990 & n.subtreeFlags) || i) {
                            i = Ns.transition,
                            Ns.transition = null;
                            var l = bt;
                            bt = 1;
                            var s = Cs;
                            Cs |= 4,
                            js.current = null,
                            function(e, t) {
                                if (ea = Yt,
                                fr(e = pr())) {
                                    if ("selectionStart"in e)
                                        var n = {
                                            start: e.selectionStart,
                                            end: e.selectionEnd
                                        };
                                    else
                                        e: {
                                            var r = (n = (n = e.ownerDocument) && n.defaultView || window).getSelection && n.getSelection();
                                            if (r && 0 !== r.rangeCount) {
                                                n = r.anchorNode;
                                                var a = r.anchorOffset
                                                  , i = r.focusNode;
                                                r = r.focusOffset;
                                                try {
                                                    n.nodeType,
                                                    i.nodeType
                                                } catch (w) {
                                                    n = null;
                                                    break e
                                                }
                                                var l = 0
                                                  , s = -1
                                                  , u = -1
                                                  , c = 0
                                                  , d = 0
                                                  , p = e
                                                  , f = null;
                                                t: for (; ; ) {
                                                    for (var m; p !== n || 0 !== a && 3 !== p.nodeType || (s = l + a),
                                                    p !== i || 0 !== r && 3 !== p.nodeType || (u = l + r),
                                                    3 === p.nodeType && (l += p.nodeValue.length),
                                                    null !== (m = p.firstChild); )
                                                        f = p,
                                                        p = m;
                                                    for (; ; ) {
                                                        if (p === e)
                                                            break t;
                                                        if (f === n && ++c === a && (s = l),
                                                        f === i && ++d === r && (u = l),
                                                        null !== (m = p.nextSibling))
                                                            break;
                                                        f = (p = f).parentNode
                                                    }
                                                    p = m
                                                }
                                                n = -1 === s || -1 === u ? null : {
                                                    start: s,
                                                    end: u
                                                }
                                            } else
                                                n = null
                                        }
                                    n = n || {
                                        start: 0,
                                        end: 0
                                    }
                                } else
                                    n = null;
                                for (ta = {
                                    focusedElem: e,
                                    selectionRange: n
                                },
                                Yt = !1,
                                _l = t; null !== _l; )
                                    if (e = (t = _l).child,
                                    0 !== (1028 & t.subtreeFlags) && null !== e)
                                        e.return = t,
                                        _l = e;
                                    else
                                        for (; null !== _l; ) {
                                            t = _l;
                                            try {
                                                var h = t.alternate;
                                                if (0 !== (1024 & t.flags))
                                                    switch (t.tag) {
                                                    case 0:
                                                    case 11:
                                                    case 15:
                                                    case 5:
                                                    case 6:
                                                    case 4:
                                                    case 17:
                                                        break;
                                                    case 1:
                                                        if (null !== h) {
                                                            var g = h.memoizedProps
                                                              , v = h.memoizedState
                                                              , y = t.stateNode
                                                              , b = y.getSnapshotBeforeUpdate(t.elementType === t.type ? g : nl(t.type, g), v);
                                                            y.__reactInternalSnapshotBeforeUpdate = b
                                                        }
                                                        break;
                                                    case 3:
                                                        var x = t.stateNode.containerInfo;
                                                        1 === x.nodeType ? x.textContent = "" : 9 === x.nodeType && x.documentElement && x.removeChild(x.documentElement);
                                                        break;
                                                    default:
                                                        throw Error(o(163))
                                                    }
                                            } catch (w) {
                                                Su(t, t.return, w)
                                            }
                                            if (null !== (e = t.sibling)) {
                                                e.return = t.return,
                                                _l = e;
                                                break
                                            }
                                            _l = t.return
                                        }
                                h = ts,
                                ts = !1
                            }(e, n),
                            gs(n, e),
                            mr(ta),
                            Yt = !!ea,
                            ta = ea = null,
                            e.current = n,
                            ys(n, e, a),
                            Je(),
                            Cs = s,
                            bt = l,
                            Ns.transition = i
                        } else
                            e.current = n;
                        if (Vs && (Vs = !1,
                        Zs = e,
                        Ks = a),
                        i = e.pendingLanes,
                        0 === i && (Gs = null),
                        function(e) {
                            if (ot && "function" === typeof ot.onCommitFiberRoot)
                                try {
                                    ot.onCommitFiberRoot(at, e, void 0, 128 === (128 & e.current.flags))
                                } catch (t) {}
                        }(n.stateNode),
                        ru(e, Xe()),
                        null !== t)
                            for (r = e.onRecoverableError,
                            n = 0; n < t.length; n++)
                                a = t[n],
                                r(a.value, {
                                    componentStack: a.stack,
                                    digest: a.digest
                                });
                        if (Ys)
                            throw Ys = !1,
                            e = Ws,
                            Ws = null,
                            e;
                        0 !== (1 & Ks) && 0 !== e.tag && Au(),
                        i = e.pendingLanes,
                        0 !== (1 & i) ? e === Xs ? Js++ : (Js = 0,
                        Xs = e) : Js = 0,
                        Ha()
                    }(e, t, n, r)
                } finally {
                    Ns.transition = a,
                    bt = r
                }
                return null
            }
            function Au() {
                if (null !== Zs) {
                    var e = xt(Ks)
                      , t = Ns.transition
                      , n = bt;
                    try {
                        if (Ns.transition = null,
                        bt = 16 > e ? 16 : e,
                        null === Zs)
                            var r = !1;
                        else {
                            if (e = Zs,
                            Zs = null,
                            Ks = 0,
                            0 !== (6 & Cs))
                                throw Error(o(331));
                            var a = Cs;
                            for (Cs |= 4,
                            _l = e.current; null !== _l; ) {
                                var i = _l
                                  , l = i.child;
                                if (0 !== (16 & _l.flags)) {
                                    var s = i.deletions;
                                    if (null !== s) {
                                        for (var u = 0; u < s.length; u++) {
                                            var c = s[u];
                                            for (_l = c; null !== _l; ) {
                                                var d = _l;
                                                switch (d.tag) {
                                                case 0:
                                                case 11:
                                                case 15:
                                                    ns(8, d, i)
                                                }
                                                var p = d.child;
                                                if (null !== p)
                                                    p.return = d,
                                                    _l = p;
                                                else
                                                    for (; null !== _l; ) {
                                                        var f = (d = _l).sibling
                                                          , m = d.return;
                                                        if (os(d),
                                                        d === c) {
                                                            _l = null;
                                                            break
                                                        }
                                                        if (null !== f) {
                                                            f.return = m,
                                                            _l = f;
                                                            break
                                                        }
                                                        _l = m
                                                    }
                                            }
                                        }
                                        var h = i.alternate;
                                        if (null !== h) {
                                            var g = h.child;
                                            if (null !== g) {
                                                h.child = null;
                                                do {
                                                    var v = g.sibling;
                                                    g.sibling = null,
                                                    g = v
                                                } while (null !== g)
                                            }
                                        }
                                        _l = i
                                    }
                                }
                                if (0 !== (2064 & i.subtreeFlags) && null !== l)
                                    l.return = i,
                                    _l = l;
                                else
                                    e: for (; null !== _l; ) {
                                        if (0 !== (2048 & (i = _l).flags))
                                            switch (i.tag) {
                                            case 0:
                                            case 11:
                                            case 15:
                                                ns(9, i, i.return)
                                            }
                                        var y = i.sibling;
                                        if (null !== y) {
                                            y.return = i.return,
                                            _l = y;
                                            break e
                                        }
                                        _l = i.return
                                    }
                            }
                            var b = e.current;
                            for (_l = b; null !== _l; ) {
                                var x = (l = _l).child;
                                if (0 !== (2064 & l.subtreeFlags) && null !== x)
                                    x.return = l,
                                    _l = x;
                                else
                                    e: for (l = b; null !== _l; ) {
                                        if (0 !== (2048 & (s = _l).flags))
                                            try {
                                                switch (s.tag) {
                                                case 0:
                                                case 11:
                                                case 15:
                                                    rs(9, s)
                                                }
                                            } catch (A) {
                                                Su(s, s.return, A)
                                            }
                                        if (s === l) {
                                            _l = null;
                                            break e
                                        }
                                        var w = s.sibling;
                                        if (null !== w) {
                                            w.return = s.return,
                                            _l = w;
                                            break e
                                        }
                                        _l = s.return
                                    }
                            }
                            if (Cs = a,
                            Ha(),
                            ot && "function" === typeof ot.onPostCommitFiberRoot)
                                try {
                                    ot.onPostCommitFiberRoot(at, e)
                                } catch (A) {}
                            r = !0
                        }
                        return r
                    } finally {
                        bt = n,
                        Ns.transition = t
                    }
                }
                return !1
            }
            function ku(e, t, n) {
                e = qo(e, t = fl(0, t = ul(n, t), 1), 1),
                t = eu(),
                null !== e && (vt(e, 1, t),
                ru(e, t))
            }
            function Su(e, t, n) {
                if (3 === e.tag)
                    ku(e, e, n);
                else
                    for (; null !== t; ) {
                        if (3 === t.tag) {
                            ku(t, e, n);
                            break
                        }
                        if (1 === t.tag) {
                            var r = t.stateNode;
                            if ("function" === typeof t.type.getDerivedStateFromError || "function" === typeof r.componentDidCatch && (null === Gs || !Gs.has(r))) {
                                t = qo(t, e = ml(t, e = ul(n, e), 1), 1),
                                e = eu(),
                                null !== t && (vt(t, 1, e),
                                ru(t, e));
                                break
                            }
                        }
                        t = t.return
                    }
            }
            function Eu(e, t, n) {
                var r = e.pingCache;
                null !== r && r.delete(t),
                t = eu(),
                e.pingedLanes |= e.suspendedLanes & n,
                Rs === e && (Ts & n) === n && (4 === Ps || 3 === Ps && (130023424 & Ts) === Ts && 500 > Xe() - Ds ? pu(e, 0) : Ms |= n),
                ru(e, t)
            }
            function ju(e, t) {
                0 === t && (0 === (1 & e.mode) ? t = 1 : (t = ct,
                0 === (130023424 & (ct <<= 1)) && (ct = 4194304)));
                var n = eu();
                null !== (e = Io(e, t)) && (vt(e, t, n),
                ru(e, n))
            }
            function Nu(e) {
                var t = e.memoizedState
                  , n = 0;
                null !== t && (n = t.retryLane),
                ju(e, n)
            }
            function Cu(e, t) {
                var n = 0;
                switch (e.tag) {
                case 13:
                    var r = e.stateNode
                      , a = e.memoizedState;
                    null !== a && (n = a.retryLane);
                    break;
                case 19:
                    r = e.stateNode;
                    break;
                default:
                    throw Error(o(314))
                }
                null !== r && r.delete(t),
                ju(e, n)
            }
            function Ru(e, t) {
                return Ve(e, t)
            }
            function Ou(e, t, n, r) {
                this.tag = e,
                this.key = n,
                this.sibling = this.child = this.return = this.stateNode = this.type = this.elementType = null,
                this.index = 0,
                this.ref = null,
                this.pendingProps = t,
                this.dependencies = this.memoizedState = this.updateQueue = this.memoizedProps = null,
                this.mode = r,
                this.subtreeFlags = this.flags = 0,
                this.deletions = null,
                this.childLanes = this.lanes = 0,
                this.alternate = null
            }
            function Tu(e, t, n, r) {
                return new Ou(e,t,n,r)
            }
            function Lu(e) {
                return !(!(e = e.prototype) || !e.isReactComponent)
            }
            function Uu(e, t) {
                var n = e.alternate;
                return null === n ? ((n = Tu(e.tag, t, e.key, e.mode)).elementType = e.elementType,
                n.type = e.type,
                n.stateNode = e.stateNode,
                n.alternate = e,
                e.alternate = n) : (n.pendingProps = t,
                n.type = e.type,
                n.flags = 0,
                n.subtreeFlags = 0,
                n.deletions = null),
                n.flags = 14680064 & e.flags,
                n.childLanes = e.childLanes,
                n.lanes = e.lanes,
                n.child = e.child,
                n.memoizedProps = e.memoizedProps,
                n.memoizedState = e.memoizedState,
                n.updateQueue = e.updateQueue,
                t = e.dependencies,
                n.dependencies = null === t ? null : {
                    lanes: t.lanes,
                    firstContext: t.firstContext
                },
                n.sibling = e.sibling,
                n.index = e.index,
                n.ref = e.ref,
                n
            }
            function Pu(e, t, n, r, a, i) {
                var l = 2;
                if (r = e,
                "function" === typeof e)
                    Lu(e) && (l = 1);
                else if ("string" === typeof e)
                    l = 5;
                else
                    e: switch (e) {
                    case k:
                        return Iu(n.children, a, i, t);
                    case S:
                        l = 8,
                        a |= 8;
                        break;
                    case E:
                        return (e = Tu(12, n, t, 2 | a)).elementType = E,
                        e.lanes = i,
                        e;
                    case R:
                        return (e = Tu(13, n, t, a)).elementType = R,
                        e.lanes = i,
                        e;
                    case O:
                        return (e = Tu(19, n, t, a)).elementType = O,
                        e.lanes = i,
                        e;
                    case U:
                        return Fu(n, a, i, t);
                    default:
                        if ("object" === typeof e && null !== e)
                            switch (e.$$typeof) {
                            case j:
                                l = 10;
                                break e;
                            case N:
                                l = 9;
                                break e;
                            case C:
                                l = 11;
                                break e;
                            case T:
                                l = 14;
                                break e;
                            case L:
                                l = 16,
                                r = null;
                                break e
                            }
                        throw Error(o(130, null == e ? e : typeof e, ""))
                    }
                return (t = Tu(l, n, t, a)).elementType = e,
                t.type = r,
                t.lanes = i,
                t
            }
            function Iu(e, t, n, r) {
                return (e = Tu(7, e, r, t)).lanes = n,
                e
            }
            function Fu(e, t, n, r) {
                return (e = Tu(22, e, r, t)).elementType = U,
                e.lanes = n,
                e.stateNode = {
                    isHidden: !1
                },
                e
            }
            function zu(e, t, n) {
                return (e = Tu(6, e, null, t)).lanes = n,
                e
            }
            function Mu(e, t, n) {
                return (t = Tu(4, null !== e.children ? e.children : [], e.key, t)).lanes = n,
                t.stateNode = {
                    containerInfo: e.containerInfo,
                    pendingChildren: null,
                    implementation: e.implementation
                },
                t
            }
            function Bu(e, t, n, r, a) {
                this.tag = t,
                this.containerInfo = e,
                this.finishedWork = this.pingCache = this.current = this.pendingChildren = null,
                this.timeoutHandle = -1,
                this.callbackNode = this.pendingContext = this.context = null,
                this.callbackPriority = 0,
                this.eventTimes = gt(0),
                this.expirationTimes = gt(-1),
                this.entangledLanes = this.finishedLanes = this.mutableReadLanes = this.expiredLanes = this.pingedLanes = this.suspendedLanes = this.pendingLanes = 0,
                this.entanglements = gt(0),
                this.identifierPrefix = r,
                this.onRecoverableError = a,
                this.mutableSourceEagerHydrationData = null
            }
            function qu(e, t, n, r, a, o, i, l, s) {
                return e = new Bu(e,t,n,l,s),
                1 === t ? (t = 1,
                !0 === o && (t |= 8)) : t = 0,
                o = Tu(3, null, null, t),
                e.current = o,
                o.stateNode = e,
                o.memoizedState = {
                    element: r,
                    isDehydrated: n,
                    cache: null,
                    transitions: null,
                    pendingSuspenseBoundaries: null
                },
                zo(o),
                e
            }
            function Du(e) {
                if (!e)
                    return Na;
                e: {
                    if (He(e = e._reactInternals) !== e || 1 !== e.tag)
                        throw Error(o(170));
                    var t = e;
                    do {
                        switch (t.tag) {
                        case 3:
                            t = t.stateNode.context;
                            break e;
                        case 1:
                            if (La(t.type)) {
                                t = t.stateNode.__reactInternalMemoizedMergedChildContext;
                                break e
                            }
                        }
                        t = t.return
                    } while (null !== t);
                    throw Error(o(171))
                }
                if (1 === e.tag) {
                    var n = e.type;
                    if (La(n))
                        return Ia(e, n, t)
                }
                return t
            }
            function Hu(e, t, n, r, a, o, i, l, s) {
                return (e = qu(n, r, !0, e, 0, o, 0, l, s)).context = Du(null),
                n = e.current,
                (o = Bo(r = eu(), a = tu(n))).callback = void 0 !== t && null !== t ? t : null,
                qo(n, o, a),
                e.current.lanes = a,
                vt(e, a, r),
                ru(e, r),
                e
            }
            function Qu(e, t, n, r) {
                var a = t.current
                  , o = eu()
                  , i = tu(a);
                return n = Du(n),
                null === t.context ? t.context = n : t.pendingContext = n,
                (t = Bo(o, i)).payload = {
                    element: e
                },
                null !== (r = void 0 === r ? null : r) && (t.callback = r),
                null !== (e = qo(a, t, i)) && (nu(e, a, i, o),
                Do(e, a, i)),
                i
            }
            function Yu(e) {
                return (e = e.current).child ? (e.child.tag,
                e.child.stateNode) : null
            }
            function Wu(e, t) {
                if (null !== (e = e.memoizedState) && null !== e.dehydrated) {
                    var n = e.retryLane;
                    e.retryLane = 0 !== n && n < t ? n : t
                }
            }
            function Gu(e, t) {
                Wu(e, t),
                (e = e.alternate) && Wu(e, t)
            }
            ks = function(e, t, n) {
                if (null !== e)
                    if (e.memoizedProps !== t.pendingProps || Ra.current)
                        bl = !0;
                    else {
                        if (0 === (e.lanes & n) && 0 === (128 & t.flags))
                            return bl = !1,
                            function(e, t, n) {
                                switch (t.tag) {
                                case 3:
                                    Rl(t),
                                    mo();
                                    break;
                                case 5:
                                    _o(t);
                                    break;
                                case 1:
                                    La(t.type) && Fa(t);
                                    break;
                                case 4:
                                    Jo(t, t.stateNode.containerInfo);
                                    break;
                                case 10:
                                    var r = t.type._context
                                      , a = t.memoizedProps.value;
                                    ja(ko, r._currentValue),
                                    r._currentValue = a;
                                    break;
                                case 13:
                                    if (null !== (r = t.memoizedState))
                                        return null !== r.dehydrated ? (ja(ei, 1 & ei.current),
                                        t.flags |= 128,
                                        null) : 0 !== (n & t.child.childLanes) ? zl(e, t, n) : (ja(ei, 1 & ei.current),
                                        null !== (e = Yl(e, t, n)) ? e.sibling : null);
                                    ja(ei, 1 & ei.current);
                                    break;
                                case 19:
                                    if (r = 0 !== (n & t.childLanes),
                                    0 !== (128 & e.flags)) {
                                        if (r)
                                            return Hl(e, t, n);
                                        t.flags |= 128
                                    }
                                    if (null !== (a = t.memoizedState) && (a.rendering = null,
                                    a.tail = null,
                                    a.lastEffect = null),
                                    ja(ei, ei.current),
                                    r)
                                        break;
                                    return null;
                                case 22:
                                case 23:
                                    return t.lanes = 0,
                                    Sl(e, t, n)
                                }
                                return Yl(e, t, n)
                            }(e, t, n);
                        bl = 0 !== (131072 & e.flags)
                    }
                else
                    bl = !1,
                    ao && 0 !== (1048576 & t.flags) && $a(t, Ga, t.index);
                switch (t.lanes = 0,
                t.tag) {
                case 2:
                    var r = t.type;
                    Ql(e, t),
                    e = t.pendingProps;
                    var a = Ta(t, Ca.current);
                    Oo(t, n),
                    a = gi(null, t, r, e, a, n);
                    var i = vi();
                    return t.flags |= 1,
                    "object" === typeof a && null !== a && "function" === typeof a.render && void 0 === a.$$typeof ? (t.tag = 1,
                    t.memoizedState = null,
                    t.updateQueue = null,
                    La(r) ? (i = !0,
                    Fa(t)) : i = !1,
                    t.memoizedState = null !== a.state && void 0 !== a.state ? a.state : null,
                    zo(t),
                    a.updater = al,
                    t.stateNode = a,
                    a._reactInternals = t,
                    sl(t, r, e, n),
                    t = Cl(null, t, r, !0, i, n)) : (t.tag = 0,
                    ao && i && eo(t),
                    xl(null, t, a, n),
                    t = t.child),
                    t;
                case 16:
                    r = t.elementType;
                    e: {
                        switch (Ql(e, t),
                        e = t.pendingProps,
                        r = (a = r._init)(r._payload),
                        t.type = r,
                        a = t.tag = function(e) {
                            if ("function" === typeof e)
                                return Lu(e) ? 1 : 0;
                            if (void 0 !== e && null !== e) {
                                if ((e = e.$$typeof) === C)
                                    return 11;
                                if (e === T)
                                    return 14
                            }
                            return 2
                        }(r),
                        e = nl(r, e),
                        a) {
                        case 0:
                            t = jl(null, t, r, e, n);
                            break e;
                        case 1:
                            t = Nl(null, t, r, e, n);
                            break e;
                        case 11:
                            t = wl(null, t, r, e, n);
                            break e;
                        case 14:
                            t = Al(null, t, r, nl(r.type, e), n);
                            break e
                        }
                        throw Error(o(306, r, ""))
                    }
                    return t;
                case 0:
                    return r = t.type,
                    a = t.pendingProps,
                    jl(e, t, r, a = t.elementType === r ? a : nl(r, a), n);
                case 1:
                    return r = t.type,
                    a = t.pendingProps,
                    Nl(e, t, r, a = t.elementType === r ? a : nl(r, a), n);
                case 3:
                    e: {
                        if (Rl(t),
                        null === e)
                            throw Error(o(387));
                        r = t.pendingProps,
                        a = (i = t.memoizedState).element,
                        Mo(e, t),
                        Qo(t, r, null, n);
                        var l = t.memoizedState;
                        if (r = l.element,
                        i.isDehydrated) {
                            if (i = {
                                element: r,
                                isDehydrated: !1,
                                cache: l.cache,
                                pendingSuspenseBoundaries: l.pendingSuspenseBoundaries,
                                transitions: l.transitions
                            },
                            t.updateQueue.baseState = i,
                            t.memoizedState = i,
                            256 & t.flags) {
                                t = Ol(e, t, r, n, a = ul(Error(o(423)), t));
                                break e
                            }
                            if (r !== a) {
                                t = Ol(e, t, r, n, a = ul(Error(o(424)), t));
                                break e
                            }
                            for (ro = ua(t.stateNode.containerInfo.firstChild),
                            no = t,
                            ao = !0,
                            oo = null,
                            n = Ao(t, null, r, n),
                            t.child = n; n; )
                                n.flags = -3 & n.flags | 4096,
                                n = n.sibling
                        } else {
                            if (mo(),
                            r === a) {
                                t = Yl(e, t, n);
                                break e
                            }
                            xl(e, t, r, n)
                        }
                        t = t.child
                    }
                    return t;
                case 5:
                    return _o(t),
                    null === e && uo(t),
                    r = t.type,
                    a = t.pendingProps,
                    i = null !== e ? e.memoizedProps : null,
                    l = a.children,
                    na(r, a) ? l = null : null !== i && na(r, i) && (t.flags |= 32),
                    El(e, t),
                    xl(e, t, l, n),
                    t.child;
                case 6:
                    return null === e && uo(t),
                    null;
                case 13:
                    return zl(e, t, n);
                case 4:
                    return Jo(t, t.stateNode.containerInfo),
                    r = t.pendingProps,
                    null === e ? t.child = wo(t, null, r, n) : xl(e, t, r, n),
                    t.child;
                case 11:
                    return r = t.type,
                    a = t.pendingProps,
                    wl(e, t, r, a = t.elementType === r ? a : nl(r, a), n);
                case 7:
                    return xl(e, t, t.pendingProps, n),
                    t.child;
                case 8:
                case 12:
                    return xl(e, t, t.pendingProps.children, n),
                    t.child;
                case 10:
                    e: {
                        if (r = t.type._context,
                        a = t.pendingProps,
                        i = t.memoizedProps,
                        l = a.value,
                        ja(ko, r._currentValue),
                        r._currentValue = l,
                        null !== i)
                            if (lr(i.value, l)) {
                                if (i.children === a.children && !Ra.current) {
                                    t = Yl(e, t, n);
                                    break e
                                }
                            } else
                                for (null !== (i = t.child) && (i.return = t); null !== i; ) {
                                    var s = i.dependencies;
                                    if (null !== s) {
                                        l = i.child;
                                        for (var u = s.firstContext; null !== u; ) {
                                            if (u.context === r) {
                                                if (1 === i.tag) {
                                                    (u = Bo(-1, n & -n)).tag = 2;
                                                    var c = i.updateQueue;
                                                    if (null !== c) {
                                                        var d = (c = c.shared).pending;
                                                        null === d ? u.next = u : (u.next = d.next,
                                                        d.next = u),
                                                        c.pending = u
                                                    }
                                                }
                                                i.lanes |= n,
                                                null !== (u = i.alternate) && (u.lanes |= n),
                                                Ro(i.return, n, t),
                                                s.lanes |= n;
                                                break
                                            }
                                            u = u.next
                                        }
                                    } else if (10 === i.tag)
                                        l = i.type === t.type ? null : i.child;
                                    else if (18 === i.tag) {
                                        if (null === (l = i.return))
                                            throw Error(o(341));
                                        l.lanes |= n,
                                        null !== (s = l.alternate) && (s.lanes |= n),
                                        Ro(l, n, t),
                                        l = i.sibling
                                    } else
                                        l = i.child;
                                    if (null !== l)
                                        l.return = i;
                                    else
                                        for (l = i; null !== l; ) {
                                            if (l === t) {
                                                l = null;
                                                break
                                            }
                                            if (null !== (i = l.sibling)) {
                                                i.return = l.return,
                                                l = i;
                                                break
                                            }
                                            l = l.return
                                        }
                                    i = l
                                }
                        xl(e, t, a.children, n),
                        t = t.child
                    }
                    return t;
                case 9:
                    return a = t.type,
                    r = t.pendingProps.children,
                    Oo(t, n),
                    r = r(a = To(a)),
                    t.flags |= 1,
                    xl(e, t, r, n),
                    t.child;
                case 14:
                    return a = nl(r = t.type, t.pendingProps),
                    Al(e, t, r, a = nl(r.type, a), n);
                case 15:
                    return kl(e, t, t.type, t.pendingProps, n);
                case 17:
                    return r = t.type,
                    a = t.pendingProps,
                    a = t.elementType === r ? a : nl(r, a),
                    Ql(e, t),
                    t.tag = 1,
                    La(r) ? (e = !0,
                    Fa(t)) : e = !1,
                    Oo(t, n),
                    il(t, r, a),
                    sl(t, r, a, n),
                    Cl(null, t, r, !0, e, n);
                case 19:
                    return Hl(e, t, n);
                case 22:
                    return Sl(e, t, n)
                }
                throw Error(o(156, t.tag))
            }
            ;
            var Vu = "function" === typeof reportError ? reportError : function(e) {
                console.error(e)
            }
            ;
            function Zu(e) {
                this._internalRoot = e
            }
            function Ku(e) {
                this._internalRoot = e
            }
            function Ju(e) {
                return !(!e || 1 !== e.nodeType && 9 !== e.nodeType && 11 !== e.nodeType)
            }
            function Xu(e) {
                return !(!e || 1 !== e.nodeType && 9 !== e.nodeType && 11 !== e.nodeType && (8 !== e.nodeType || " react-mount-point-unstable " !== e.nodeValue))
            }
            function _u() {}
            function $u(e, t, n, r, a) {
                var o = n._reactRootContainer;
                if (o) {
                    var i = o;
                    if ("function" === typeof a) {
                        var l = a;
                        a = function() {
                            var e = Yu(i);
                            l.call(e)
                        }
                    }
                    Qu(t, i, e, a)
                } else
                    i = function(e, t, n, r, a) {
                        if (a) {
                            if ("function" === typeof r) {
                                var o = r;
                                r = function() {
                                    var e = Yu(i);
                                    o.call(e)
                                }
                            }
                            var i = Hu(t, r, e, 0, null, !1, 0, "", _u);
                            return e._reactRootContainer = i,
                            e[ma] = i.current,
                            Hr(8 === e.nodeType ? e.parentNode : e),
                            cu(),
                            i
                        }
                        for (; a = e.lastChild; )
                            e.removeChild(a);
                        if ("function" === typeof r) {
                            var l = r;
                            r = function() {
                                var e = Yu(s);
                                l.call(e)
                            }
                        }
                        var s = qu(e, 0, !1, null, 0, !1, 0, "", _u);
                        return e._reactRootContainer = s,
                        e[ma] = s.current,
                        Hr(8 === e.nodeType ? e.parentNode : e),
                        cu((function() {
                            Qu(t, s, n, r)
                        }
                        )),
                        s
                    }(n, t, e, a, r);
                return Yu(i)
            }
            Ku.prototype.render = Zu.prototype.render = function(e) {
                var t = this._internalRoot;
                if (null === t)
                    throw Error(o(409));
                Qu(e, t, null, null)
            }
            ,
            Ku.prototype.unmount = Zu.prototype.unmount = function() {
                var e = this._internalRoot;
                if (null !== e) {
                    this._internalRoot = null;
                    var t = e.containerInfo;
                    cu((function() {
                        Qu(null, e, null, null)
                    }
                    )),
                    t[ma] = null
                }
            }
            ,
            Ku.prototype.unstable_scheduleHydration = function(e) {
                if (e) {
                    var t = St();
                    e = {
                        blockedOn: null,
                        target: e,
                        priority: t
                    };
                    for (var n = 0; n < Ut.length && 0 !== t && t < Ut[n].priority; n++)
                        ;
                    Ut.splice(n, 0, e),
                    0 === n && zt(e)
                }
            }
            ,
            wt = function(e) {
                switch (e.tag) {
                case 3:
                    var t = e.stateNode;
                    if (t.current.memoizedState.isDehydrated) {
                        var n = dt(t.pendingLanes);
                        0 !== n && (yt(t, 1 | n),
                        ru(t, Xe()),
                        0 === (6 & Cs) && (Hs = Xe() + 500,
                        Ha()))
                    }
                    break;
                case 13:
                    cu((function() {
                        var t = Io(e, 1);
                        if (null !== t) {
                            var n = eu();
                            nu(t, e, 1, n)
                        }
                    }
                    )),
                    Gu(e, 1)
                }
            }
            ,
            At = function(e) {
                if (13 === e.tag) {
                    var t = Io(e, 134217728);
                    if (null !== t)
                        nu(t, e, 134217728, eu());
                    Gu(e, 134217728)
                }
            }
            ,
            kt = function(e) {
                if (13 === e.tag) {
                    var t = tu(e)
                      , n = Io(e, t);
                    if (null !== n)
                        nu(n, e, t, eu());
                    Gu(e, t)
                }
            }
            ,
            St = function() {
                return bt
            }
            ,
            Et = function(e, t) {
                var n = bt;
                try {
                    return bt = e,
                    t()
                } finally {
                    bt = n
                }
            }
            ,
            Ae = function(e, t, n) {
                switch (t) {
                case "input":
                    if (_(e, n),
                    t = n.name,
                    "radio" === n.type && null != t) {
                        for (n = e; n.parentNode; )
                            n = n.parentNode;
                        for (n = n.querySelectorAll("input[name=" + JSON.stringify("" + t) + '][type="radio"]'),
                        t = 0; t < n.length; t++) {
                            var r = n[t];
                            if (r !== e && r.form === e.form) {
                                var a = wa(r);
                                if (!a)
                                    throw Error(o(90));
                                V(r),
                                _(r, a)
                            }
                        }
                    }
                    break;
                case "textarea":
                    oe(e, n);
                    break;
                case "select":
                    null != (t = n.value) && ne(e, !!n.multiple, t, !1)
                }
            }
            ,
            Ce = uu,
            Re = cu;
            var ec = {
                usingClientEntryPoint: !1,
                Events: [ba, xa, wa, je, Ne, uu]
            }
              , tc = {
                findFiberByHostInstance: ya,
                bundleType: 0,
                version: "18.3.1",
                rendererPackageName: "react-dom"
            }
              , nc = {
                bundleType: tc.bundleType,
                version: tc.version,
                rendererPackageName: tc.rendererPackageName,
                rendererConfig: tc.rendererConfig,
                overrideHookState: null,
                overrideHookStateDeletePath: null,
                overrideHookStateRenamePath: null,
                overrideProps: null,
                overridePropsDeletePath: null,
                overridePropsRenamePath: null,
                setErrorHandler: null,
                setSuspenseHandler: null,
                scheduleUpdate: null,
                currentDispatcherRef: x.ReactCurrentDispatcher,
                findHostInstanceByFiber: function(e) {
                    return null === (e = We(e)) ? null : e.stateNode
                },
                findFiberByHostInstance: tc.findFiberByHostInstance || function() {
                    return null
                }
                ,
                findHostInstancesForRefresh: null,
                scheduleRefresh: null,
                scheduleRoot: null,
                setRefreshHandler: null,
                getCurrentFiber: null,
                reconcilerVersion: "18.3.1-next-f1338f8080-20240426"
            };
            if ("undefined" !== typeof __REACT_DEVTOOLS_GLOBAL_HOOK__) {
                var rc = __REACT_DEVTOOLS_GLOBAL_HOOK__;
                if (!rc.isDisabled && rc.supportsFiber)
                    try {
                        at = rc.inject(nc),
                        ot = rc
                    } catch (ce) {}
            }
            t.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED = ec,
            t.createPortal = function(e, t) {
                var n = 2 < arguments.length && void 0 !== arguments[2] ? arguments[2] : null;
                if (!Ju(t))
                    throw Error(o(200));
                return function(e, t, n) {
                    var r = 3 < arguments.length && void 0 !== arguments[3] ? arguments[3] : null;
                    return {
                        $$typeof: A,
                        key: null == r ? null : "" + r,
                        children: e,
                        containerInfo: t,
                        implementation: n
                    }
                }(e, t, null, n)
            }
            ,
            t.createRoot = function(e, t) {
                if (!Ju(e))
                    throw Error(o(299));
                var n = !1
                  , r = ""
                  , a = Vu;
                return null !== t && void 0 !== t && (!0 === t.unstable_strictMode && (n = !0),
                void 0 !== t.identifierPrefix && (r = t.identifierPrefix),
                void 0 !== t.onRecoverableError && (a = t.onRecoverableError)),
                t = qu(e, 1, !1, null, 0, n, 0, r, a),
                e[ma] = t.current,
                Hr(8 === e.nodeType ? e.parentNode : e),
                new Zu(t)
            }
            ,
            t.findDOMNode = function(e) {
                if (null == e)
                    return null;
                if (1 === e.nodeType)
                    return e;
                var t = e._reactInternals;
                if (void 0 === t) {
                    if ("function" === typeof e.render)
                        throw Error(o(188));
                    throw e = Object.keys(e).join(","),
                    Error(o(268, e))
                }
                return e = null === (e = We(t)) ? null : e.stateNode
            }
            ,
            t.flushSync = function(e) {
                return cu(e)
            }
            ,
            t.hydrate = function(e, t, n) {
                if (!Xu(t))
                    throw Error(o(200));
                return $u(null, e, t, !0, n)
            }
            ,
            t.hydrateRoot = function(e, t, n) {
                if (!Ju(e))
                    throw Error(o(405));
                var r = null != n && n.hydratedSources || null
                  , a = !1
                  , i = ""
                  , l = Vu;
                if (null !== n && void 0 !== n && (!0 === n.unstable_strictMode && (a = !0),
                void 0 !== n.identifierPrefix && (i = n.identifierPrefix),
                void 0 !== n.onRecoverableError && (l = n.onRecoverableError)),
                t = Hu(t, null, e, 1, null != n ? n : null, a, 0, i, l),
                e[ma] = t.current,
                Hr(e),
                r)
                    for (e = 0; e < r.length; e++)
                        a = (a = (n = r[e])._getVersion)(n._source),
                        null == t.mutableSourceEagerHydrationData ? t.mutableSourceEagerHydrationData = [n, a] : t.mutableSourceEagerHydrationData.push(n, a);
                return new Ku(t)
            }
            ,
            t.render = function(e, t, n) {
                if (!Xu(t))
                    throw Error(o(200));
                return $u(null, e, t, !1, n)
            }
            ,
            t.unmountComponentAtNode = function(e) {
                if (!Xu(e))
                    throw Error(o(40));
                return !!e._reactRootContainer && (cu((function() {
                    $u(null, null, e, !1, (function() {
                        e._reactRootContainer = null,
                        e[ma] = null
                    }
                    ))
                }
                )),
                !0)
            }
            ,
            t.unstable_batchedUpdates = uu,
            t.unstable_renderSubtreeIntoContainer = function(e, t, n, r) {
                if (!Xu(n))
                    throw Error(o(200));
                if (null == e || void 0 === e._reactInternals)
                    throw Error(o(38));
                return $u(e, t, n, !1, r)
            }
            ,
            t.version = "18.3.1-next-f1338f8080-20240426"
        }
        ,
        4391: (e, t, n) => {
            var r = n(7950);
            t.createRoot = r.createRoot,
            t.hydrateRoot = r.hydrateRoot
        }
        ,
        7950: (e, t, n) => {
            !function e() {
                if ("undefined" !== typeof __REACT_DEVTOOLS_GLOBAL_HOOK__ && "function" === typeof __REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE)
                    try {
                        __REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE(e)
                    } catch (t) {
                        console.error(t)
                    }
            }(),
            e.exports = n(2730)
        }
        ,
        4358: (e, t) => {
            const n = /^[\u0021-\u003A\u003C\u003E-\u007E]+$/
              , r = /^[\u0021-\u003A\u003C-\u007E]*$/
              , a = /^([.]?[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)([.][a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)*$/i
              , o = /^[\u0020-\u003A\u003D-\u007E]*$/
              , i = Object.prototype.toString
              , l = ( () => {
                const e = function() {};
                return e.prototype = Object.create(null),
                e
            }
            )();
            function s(e, t, n) {
                do {
                    const n = e.charCodeAt(t);
                    if (32 !== n && 9 !== n)
                        return t
                } while (++t < n);
                return n
            }
            function u(e, t, n) {
                for (; t > n; ) {
                    const n = e.charCodeAt(--t);
                    if (32 !== n && 9 !== n)
                        return t + 1
                }
                return n
            }
            function c(e) {
                if (-1 === e.indexOf("%"))
                    return e;
                try {
                    return decodeURIComponent(e)
                } catch (t) {
                    return e
                }
            }
        }
        ,
        1153: (e, t, n) => {
            var r = n(5043)
              , a = Symbol.for("react.element")
              , o = Symbol.for("react.fragment")
              , i = Object.prototype.hasOwnProperty
              , l = r.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactCurrentOwner
              , s = {
                key: !0,
                ref: !0,
                __self: !0,
                __source: !0
            };
            function u(e, t, n) {
                var r, o = {}, u = null, c = null;
                for (r in void 0 !== n && (u = "" + n),
                void 0 !== t.key && (u = "" + t.key),
                void 0 !== t.ref && (c = t.ref),
                t)
                    i.call(t, r) && !s.hasOwnProperty(r) && (o[r] = t[r]);
                if (e && e.defaultProps)
                    for (r in t = e.defaultProps)
                        void 0 === o[r] && (o[r] = t[r]);
                return {
                    $$typeof: a,
                    type: e,
                    key: u,
                    ref: c,
                    props: o,
                    _owner: l.current
                }
            }
            t.Fragment = o,
            t.jsx = u,
            t.jsxs = u
        }
        ,
        4202: (e, t) => {
            var n = Symbol.for("react.element")
              , r = Symbol.for("react.portal")
              , a = Symbol.for("react.fragment")
              , o = Symbol.for("react.strict_mode")
              , i = Symbol.for("react.profiler")
              , l = Symbol.for("react.provider")
              , s = Symbol.for("react.context")
              , u = Symbol.for("react.forward_ref")
              , c = Symbol.for("react.suspense")
              , d = Symbol.for("react.memo")
              , p = Symbol.for("react.lazy")
              , f = Symbol.iterator;
            var m = {
                isMounted: function() {
                    return !1
                },
                enqueueForceUpdate: function() {},
                enqueueReplaceState: function() {},
                enqueueSetState: function() {}
            }
              , h = Object.assign
              , g = {};
            function v(e, t, n) {
                this.props = e,
                this.context = t,
                this.refs = g,
                this.updater = n || m
            }
            function y() {}
            function b(e, t, n) {
                this.props = e,
                this.context = t,
                this.refs = g,
                this.updater = n || m
            }
            v.prototype.isReactComponent = {},
            v.prototype.setState = function(e, t) {
                if ("object" !== typeof e && "function" !== typeof e && null != e)
                    throw Error("setState(...): takes an object of state variables to update or a function which returns an object of state variables.");
                this.updater.enqueueSetState(this, e, t, "setState")
            }
            ,
            v.prototype.forceUpdate = function(e) {
                this.updater.enqueueForceUpdate(this, e, "forceUpdate")
            }
            ,
            y.prototype = v.prototype;
            var x = b.prototype = new y;
            x.constructor = b,
            h(x, v.prototype),
            x.isPureReactComponent = !0;
            var w = Array.isArray
              , A = Object.prototype.hasOwnProperty
              , k = {
                current: null
            }
              , S = {
                key: !0,
                ref: !0,
                __self: !0,
                __source: !0
            };
            function E(e, t, r) {
                var a, o = {}, i = null, l = null;
                if (null != t)
                    for (a in void 0 !== t.ref && (l = t.ref),
                    void 0 !== t.key && (i = "" + t.key),
                    t)
                        A.call(t, a) && !S.hasOwnProperty(a) && (o[a] = t[a]);
                var s = arguments.length - 2;
                if (1 === s)
                    o.children = r;
                else if (1 < s) {
                    for (var u = Array(s), c = 0; c < s; c++)
                        u[c] = arguments[c + 2];
                    o.children = u
                }
                if (e && e.defaultProps)
                    for (a in s = e.defaultProps)
                        void 0 === o[a] && (o[a] = s[a]);
                return {
                    $$typeof: n,
                    type: e,
                    key: i,
                    ref: l,
                    props: o,
                    _owner: k.current
                }
            }
            function j(e) {
                return "object" === typeof e && null !== e && e.$$typeof === n
            }
            var N = /\/+/g;
            function C(e, t) {
                return "object" === typeof e && null !== e && null != e.key ? function(e) {
                    var t = {
                        "=": "=0",
                        ":": "=2"
                    };
                    return "$" + e.replace(/[=:]/g, (function(e) {
                        return t[e]
                    }
                    ))
                }("" + e.key) : t.toString(36)
            }
            function R(e, t, a, o, i) {
                var l = typeof e;
                "undefined" !== l && "boolean" !== l || (e = null);
                var s = !1;
                if (null === e)
                    s = !0;
                else
                    switch (l) {
                    case "string":
                    case "number":
                        s = !0;
                        break;
                    case "object":
                        switch (e.$$typeof) {
                        case n:
                        case r:
                            s = !0
                        }
                    }
                if (s)
                    return i = i(s = e),
                    e = "" === o ? "." + C(s, 0) : o,
                    w(i) ? (a = "",
                    null != e && (a = e.replace(N, "$&/") + "/"),
                    R(i, t, a, "", (function(e) {
                        return e
                    }
                    ))) : null != i && (j(i) && (i = function(e, t) {
                        return {
                            $$typeof: n,
                            type: e.type,
                            key: t,
                            ref: e.ref,
                            props: e.props,
                            _owner: e._owner
                        }
                    }(i, a + (!i.key || s && s.key === i.key ? "" : ("" + i.key).replace(N, "$&/") + "/") + e)),
                    t.push(i)),
                    1;
                if (s = 0,
                o = "" === o ? "." : o + ":",
                w(e))
                    for (var u = 0; u < e.length; u++) {
                        var c = o + C(l = e[u], u);
                        s += R(l, t, a, c, i)
                    }
                else if (c = function(e) {
                    return null === e || "object" !== typeof e ? null : "function" === typeof (e = f && e[f] || e["@@iterator"]) ? e : null
                }(e),
                "function" === typeof c)
                    for (e = c.call(e),
                    u = 0; !(l = e.next()).done; )
                        s += R(l = l.value, t, a, c = o + C(l, u++), i);
                else if ("object" === l)
                    throw t = String(e),
                    Error("Objects are not valid as a React child (found: " + ("[object Object]" === t ? "object with keys {" + Object.keys(e).join(", ") + "}" : t) + "). If you meant to render a collection of children, use an array instead.");
                return s
            }
            function O(e, t, n) {
                if (null == e)
                    return e;
                var r = []
                  , a = 0;
                return R(e, r, "", "", (function(e) {
                    return t.call(n, e, a++)
                }
                )),
                r
            }
            function T(e) {
                if (-1 === e._status) {
                    var t = e._result;
                    (t = t()).then((function(t) {
                        0 !== e._status && -1 !== e._status || (e._status = 1,
                        e._result = t)
                    }
                    ), (function(t) {
                        0 !== e._status && -1 !== e._status || (e._status = 2,
                        e._result = t)
                    }
                    )),
                    -1 === e._status && (e._status = 0,
                    e._result = t)
                }
                if (1 === e._status)
                    return e._result.default;
                throw e._result
            }
            var L = {
                current: null
            }
              , U = {
                transition: null
            }
              , P = {
                ReactCurrentDispatcher: L,
                ReactCurrentBatchConfig: U,
                ReactCurrentOwner: k
            };
            function I() {
                throw Error("act(...) is not supported in production builds of React.")
            }
            t.Children = {
                map: O,
                forEach: function(e, t, n) {
                    O(e, (function() {
                        t.apply(this, arguments)
                    }
                    ), n)
                },
                count: function(e) {
                    var t = 0;
                    return O(e, (function() {
                        t++
                    }
                    )),
                    t
                },
                toArray: function(e) {
                    return O(e, (function(e) {
                        return e
                    }
                    )) || []
                },
                only: function(e) {
                    if (!j(e))
                        throw Error("React.Children.only expected to receive a single React element child.");
                    return e
                }
            },
            t.Component = v,
            t.Fragment = a,
            t.Profiler = i,
            t.PureComponent = b,
            t.StrictMode = o,
            t.Suspense = c,
            t.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED = P,
            t.act = I,
            t.cloneElement = function(e, t, r) {
                if (null === e || void 0 === e)
                    throw Error("React.cloneElement(...): The argument must be a React element, but you passed " + e + ".");
                var a = h({}, e.props)
                  , o = e.key
                  , i = e.ref
                  , l = e._owner;
                if (null != t) {
                    if (void 0 !== t.ref && (i = t.ref,
                    l = k.current),
                    void 0 !== t.key && (o = "" + t.key),
                    e.type && e.type.defaultProps)
                        var s = e.type.defaultProps;
                    for (u in t)
                        A.call(t, u) && !S.hasOwnProperty(u) && (a[u] = void 0 === t[u] && void 0 !== s ? s[u] : t[u])
                }
                var u = arguments.length - 2;
                if (1 === u)
                    a.children = r;
                else if (1 < u) {
                    s = Array(u);
                    for (var c = 0; c < u; c++)
                        s[c] = arguments[c + 2];
                    a.children = s
                }
                return {
                    $$typeof: n,
                    type: e.type,
                    key: o,
                    ref: i,
                    props: a,
                    _owner: l
                }
            }
            ,
            t.createContext = function(e) {
                return (e = {
                    $$typeof: s,
                    _currentValue: e,
                    _currentValue2: e,
                    _threadCount: 0,
                    Provider: null,
                    Consumer: null,
                    _defaultValue: null,
                    _globalName: null
                }).Provider = {
                    $$typeof: l,
                    _context: e
                },
                e.Consumer = e
            }
            ,
            t.createElement = E,
            t.createFactory = function(e) {
                var t = E.bind(null, e);
                return t.type = e,
                t
            }
            ,
            t.createRef = function() {
                return {
                    current: null
                }
            }
            ,
            t.forwardRef = function(e) {
                return {
                    $$typeof: u,
                    render: e
                }
            }
            ,
            t.isValidElement = j,
            t.lazy = function(e) {
                return {
                    $$typeof: p,
                    _payload: {
                        _status: -1,
                        _result: e
                    },
                    _init: T
                }
            }
            ,
            t.memo = function(e, t) {
                return {
                    $$typeof: d,
                    type: e,
                    compare: void 0 === t ? null : t
                }
            }
            ,
            t.startTransition = function(e) {
                var t = U.transition;
                U.transition = {};
                try {
                    e()
                } finally {
                    U.transition = t
                }
            }
            ,
            t.unstable_act = I,
            t.useCallback = function(e, t) {
                return L.current.useCallback(e, t)
            }
            ,
            t.useContext = function(e) {
                return L.current.useContext(e)
            }
            ,
            t.useDebugValue = function() {}
            ,
            t.useDeferredValue = function(e) {
                return L.current.useDeferredValue(e)
            }
            ,
            t.useEffect = function(e, t) {
                return L.current.useEffect(e, t)
            }
            ,
            t.useId = function() {
                return L.current.useId()
            }
            ,
            t.useImperativeHandle = function(e, t, n) {
                return L.current.useImperativeHandle(e, t, n)
            }
            ,
            t.useInsertionEffect = function(e, t) {
                return L.current.useInsertionEffect(e, t)
            }
            ,
            t.useLayoutEffect = function(e, t) {
                return L.current.useLayoutEffect(e, t)
            }
            ,
            t.useMemo = function(e, t) {
                return L.current.useMemo(e, t)
            }
            ,
            t.useReducer = function(e, t, n) {
                return L.current.useReducer(e, t, n)
            }
            ,
            t.useRef = function(e) {
                return L.current.useRef(e)
            }
            ,
            t.useState = function(e) {
                return L.current.useState(e)
            }
            ,
            t.useSyncExternalStore = function(e, t, n) {
                return L.current.useSyncExternalStore(e, t, n)
            }
            ,
            t.useTransition = function() {
                return L.current.useTransition()
            }
            ,
            t.version = "18.3.1"
        }
        ,
        5043: (e, t, n) => {
            e.exports = n(4202)
        }
        ,
        579: (e, t, n) => {
            e.exports = n(1153)
        }
        ,
        7234: (e, t) => {
            function n(e, t) {
                var n = e.length;
                e.push(t);
                e: for (; 0 < n; ) {
                    var r = n - 1 >>> 1
                      , a = e[r];
                    if (!(0 < o(a, t)))
                        break e;
                    e[r] = t,
                    e[n] = a,
                    n = r
                }
            }
            function r(e) {
                return 0 === e.length ? null : e[0]
            }
            function a(e) {
                if (0 === e.length)
                    return null;
                var t = e[0]
                  , n = e.pop();
                if (n !== t) {
                    e[0] = n;
                    e: for (var r = 0, a = e.length, i = a >>> 1; r < i; ) {
                        var l = 2 * (r + 1) - 1
                          , s = e[l]
                          , u = l + 1
                          , c = e[u];
                        if (0 > o(s, n))
                            u < a && 0 > o(c, s) ? (e[r] = c,
                            e[u] = n,
                            r = u) : (e[r] = s,
                            e[l] = n,
                            r = l);
                        else {
                            if (!(u < a && 0 > o(c, n)))
                                break e;
                            e[r] = c,
                            e[u] = n,
                            r = u
                        }
                    }
                }
                return t
            }
            function o(e, t) {
                var n = e.sortIndex - t.sortIndex;
                return 0 !== n ? n : e.id - t.id
            }
            if ("object" === typeof performance && "function" === typeof performance.now) {
                var i = performance;
                t.unstable_now = function() {
                    return i.now()
                }
            } else {
                var l = Date
                  , s = l.now();
                t.unstable_now = function() {
                    return l.now() - s
                }
            }
            var u = []
              , c = []
              , d = 1
              , p = null
              , f = 3
              , m = !1
              , h = !1
              , g = !1
              , v = "function" === typeof setTimeout ? setTimeout : null
              , y = "function" === typeof clearTimeout ? clearTimeout : null
              , b = "undefined" !== typeof setImmediate ? setImmediate : null;
            function x(e) {
                for (var t = r(c); null !== t; ) {
                    if (null === t.callback)
                        a(c);
                    else {
                        if (!(t.startTime <= e))
                            break;
                        a(c),
                        t.sortIndex = t.expirationTime,
                        n(u, t)
                    }
                    t = r(c)
                }
            }
            function w(e) {
                if (g = !1,
                x(e),
                !h)
                    if (null !== r(u))
                        h = !0,
                        U(A);
                    else {
                        var t = r(c);
                        null !== t && P(w, t.startTime - e)
                    }
            }
            function A(e, n) {
                h = !1,
                g && (g = !1,
                y(j),
                j = -1),
                m = !0;
                var o = f;
                try {
                    for (x(n),
                    p = r(u); null !== p && (!(p.expirationTime > n) || e && !R()); ) {
                        var i = p.callback;
                        if ("function" === typeof i) {
                            p.callback = null,
                            f = p.priorityLevel;
                            var l = i(p.expirationTime <= n);
                            n = t.unstable_now(),
                            "function" === typeof l ? p.callback = l : p === r(u) && a(u),
                            x(n)
                        } else
                            a(u);
                        p = r(u)
                    }
                    if (null !== p)
                        var s = !0;
                    else {
                        var d = r(c);
                        null !== d && P(w, d.startTime - n),
                        s = !1
                    }
                    return s
                } finally {
                    p = null,
                    f = o,
                    m = !1
                }
            }
            "undefined" !== typeof navigator && void 0 !== navigator.scheduling && void 0 !== navigator.scheduling.isInputPending && navigator.scheduling.isInputPending.bind(navigator.scheduling);
            var k, S = !1, E = null, j = -1, N = 5, C = -1;
            function R() {
                return !(t.unstable_now() - C < N)
            }
            function O() {
                if (null !== E) {
                    var e = t.unstable_now();
                    C = e;
                    var n = !0;
                    try {
                        n = E(!0, e)
                    } finally {
                        n ? k() : (S = !1,
                        E = null)
                    }
                } else
                    S = !1
            }
            if ("function" === typeof b)
                k = function() {
                    b(O)
                }
                ;
            else if ("undefined" !== typeof MessageChannel) {
                var T = new MessageChannel
                  , L = T.port2;
                T.port1.onmessage = O,
                k = function() {
                    L.postMessage(null)
                }
            } else
                k = function() {
                    v(O, 0)
                }
                ;
            function U(e) {
                E = e,
                S || (S = !0,
                k())
            }
            function P(e, n) {
                j = v((function() {
                    e(t.unstable_now())
                }
                ), n)
            }
            t.unstable_IdlePriority = 5,
            t.unstable_ImmediatePriority = 1,
            t.unstable_LowPriority = 4,
            t.unstable_NormalPriority = 3,
            t.unstable_Profiling = null,
            t.unstable_UserBlockingPriority = 2,
            t.unstable_cancelCallback = function(e) {
                e.callback = null
            }
            ,
            t.unstable_continueExecution = function() {
                h || m || (h = !0,
                U(A))
            }
            ,
            t.unstable_forceFrameRate = function(e) {
                0 > e || 125 < e ? console.error("forceFrameRate takes a positive int between 0 and 125, forcing frame rates higher than 125 fps is not supported") : N = 0 < e ? Math.floor(1e3 / e) : 5
            }
            ,
            t.unstable_getCurrentPriorityLevel = function() {
                return f
            }
            ,
            t.unstable_getFirstCallbackNode = function() {
                return r(u)
            }
            ,
            t.unstable_next = function(e) {
                switch (f) {
                case 1:
                case 2:
                case 3:
                    var t = 3;
                    break;
                default:
                    t = f
                }
                var n = f;
                f = t;
                try {
                    return e()
                } finally {
                    f = n
                }
            }
            ,
            t.unstable_pauseExecution = function() {}
            ,
            t.unstable_requestPaint = function() {}
            ,
            t.unstable_runWithPriority = function(e, t) {
                switch (e) {
                case 1:
                case 2:
                case 3:
                case 4:
                case 5:
                    break;
                default:
                    e = 3
                }
                var n = f;
                f = e;
                try {
                    return t()
                } finally {
                    f = n
                }
            }
            ,
            t.unstable_scheduleCallback = function(e, a, o) {
                var i = t.unstable_now();
                switch ("object" === typeof o && null !== o ? o = "number" === typeof (o = o.delay) && 0 < o ? i + o : i : o = i,
                e) {
                case 1:
                    var l = -1;
                    break;
                case 2:
                    l = 250;
                    break;
                case 5:
                    l = 1073741823;
                    break;
                case 4:
                    l = 1e4;
                    break;
                default:
                    l = 5e3
                }
                return e = {
                    id: d++,
                    callback: a,
                    priorityLevel: e,
                    startTime: o,
                    expirationTime: l = o + l,
                    sortIndex: -1
                },
                o > i ? (e.sortIndex = o,
                n(c, e),
                null === r(u) && e === r(c) && (g ? (y(j),
                j = -1) : g = !0,
                P(w, o - i))) : (e.sortIndex = l,
                n(u, e),
                h || m || (h = !0,
                U(A))),
                e
            }
            ,
            t.unstable_shouldYield = R,
            t.unstable_wrapCallback = function(e) {
                var t = f;
                return function() {
                    var n = f;
                    f = t;
                    try {
                        return e.apply(this, arguments)
                    } finally {
                        f = n
                    }
                }
            }
        }
        ,
        8853: (e, t, n) => {
            e.exports = n(7234)
        }
    }
      , t = {};
    function n(r) {
        var a = t[r];
        if (void 0 !== a)
            return a.exports;
        var o = t[r] = {
            exports: {}
        };
        return e[r](o, o.exports, n),
        o.exports
    }
    n.m = e,
    n.d = (e, t) => {
        for (var r in t)
            n.o(t, r) && !n.o(e, r) && Object.defineProperty(e, r, {
                enumerable: !0,
                get: t[r]
            })
    }
    ,
    n.f = {},
    n.e = e => Promise.all(Object.keys(n.f).reduce(( (t, r) => (n.f[r](e, t),
    t)), [])),
    n.u = e => "static/js/" + e + ".9c4565b6.chunk.js",
    n.miniCssF = e => {}
    ,
    n.o = (e, t) => Object.prototype.hasOwnProperty.call(e, t),
    ( () => {
        var e = {}
          , t = "front:";
        n.l = (r, a, o, i) => {
            if (e[r])
                e[r].push(a);
            else {
                var l, s;
                if (void 0 !== o)
                    for (var u = document.getElementsByTagName("script"), c = 0; c < u.length; c++) {
                        var d = u[c];
                        if (d.getAttribute("src") == r || d.getAttribute("data-webpack") == t + o) {
                            l = d;
                            break
                        }
                    }
                l || (s = !0,
                (l = document.createElement("script")).charset = "utf-8",
                l.timeout = 120,
                n.nc && l.setAttribute("nonce", n.nc),
                l.setAttribute("data-webpack", t + o),
                l.src = r),
                e[r] = [a];
                var p = (t, n) => {
                    l.onerror = l.onload = null,
                    clearTimeout(f);
                    var a = e[r];
                    if (delete e[r],
                    l.parentNode && l.parentNode.removeChild(l),
                    a && a.forEach((e => e(n))),
                    t)
                        return t(n)
                }
                  , f = setTimeout(p.bind(null, void 0, {
                    type: "timeout",
                    target: l
                }), 12e4);
                l.onerror = p.bind(null, l.onerror),
                l.onload = p.bind(null, l.onload),
                s && document.head.appendChild(l)
            }
        }
    }
    )(),
    n.r = e => {
        "undefined" !== typeof Symbol && Symbol.toStringTag && Object.defineProperty(e, Symbol.toStringTag, {
            value: "Module"
        }),
        Object.defineProperty(e, "__esModule", {
            value: !0
        })
    }
    ,
    n.p = "/",
    ( () => {
        var e = {
            792: 0
        };
        n.f.j = (t, r) => {
            var a = n.o(e, t) ? e[t] : void 0;
            if (0 !== a)
                if (a)
                    r.push(a[2]);
                else {
                    var o = new Promise(( (n, r) => a = e[t] = [n, r]));
                    r.push(a[2] = o);
                    var i = n.p + n.u(t)
                      , l = new Error;
                    n.l(i, (r => {
                        if (n.o(e, t) && (0 !== (a = e[t]) && (e[t] = void 0),
                        a)) {
                            var o = r && ("load" === r.type ? "missing" : r.type)
                              , i = r && r.target && r.target.src;
                            l.message = "Loading chunk " + t + " failed.\n(" + o + ": " + i + ")",
                            l.name = "ChunkLoadError",
                            l.type = o,
                            l.request = i,
                            a[1](l)
                        }
                    }
                    ), "chunk-" + t, t)
                }
        }
        ;
        var t = (t, r) => {
            var a, o, i = r[0], l = r[1], s = r[2], u = 0;
            if (i.some((t => 0 !== e[t]))) {
                for (a in l)
                    n.o(l, a) && (n.m[a] = l[a]);
                if (s)
                    s(n)
            }
            for (t && t(r); u < i.length; u++)
                o = i[u],
                n.o(e, o) && e[o] && e[o][0](),
                e[o] = 0
        }
          , r = self.webpackChunkfront = self.webpackChunkfront || [];
        r.forEach(t.bind(null, 0)),
        r.push = t.bind(null, r.push.bind(r))
    }
    )();
    var r = {};
    n.r(r),
    n.d(r, {
        hasBrowserEnv: () => Wr,
        hasStandardBrowserEnv: () => Vr,
        hasStandardBrowserWebWorkerEnv: () => Zr,
        navigator: () => Gr,
        origin: () => Kr
    });
    var a = n(5043)
      , o = n(4391);
    function i(e) {
        return i = "function" == typeof Symbol && "symbol" == typeof Symbol.iterator ? function(e) {
            return typeof e
        }
        : function(e) {
            return e && "function" == typeof Symbol && e.constructor === Symbol && e !== Symbol.prototype ? "symbol" : typeof e
        }
        ,
        i(e)
    }
    function l(e) {
        var t = function(e, t) {
            if ("object" != i(e) || !e)
                return e;
            var n = e[Symbol.toPrimitive];
            if (void 0 !== n) {
                var r = n.call(e, t || "default");
                if ("object" != i(r))
                    return r;
                throw new TypeError("@@toPrimitive must return a primitive value.")
            }
            return ("string" === t ? String : Number)(e)
        }(e, "string");
        return "symbol" == i(t) ? t : t + ""
    }
    function s(e, t, n) {
        return (t = l(t))in e ? Object.defineProperty(e, t, {
            value: n,
            enumerable: !0,
            configurable: !0,
            writable: !0
        }) : e[t] = n,
        e
    }
    function u(e, t) {
        var n = Object.keys(e);
        if (Object.getOwnPropertySymbols) {
            var r = Object.getOwnPropertySymbols(e);
            t && (r = r.filter((function(t) {
                return Object.getOwnPropertyDescriptor(e, t).enumerable
            }
            ))),
            n.push.apply(n, r)
        }
        return n
    }
    function c(e) {
        for (var t = 1; t < arguments.length; t++) {
            var n = null != arguments[t] ? arguments[t] : {};
            t % 2 ? u(Object(n), !0).forEach((function(t) {
                s(e, t, n[t])
            }
            )) : Object.getOwnPropertyDescriptors ? Object.defineProperties(e, Object.getOwnPropertyDescriptors(n)) : u(Object(n)).forEach((function(t) {
                Object.defineProperty(e, t, Object.getOwnPropertyDescriptor(n, t))
            }
            ))
        }
        return e
    }
    function d(e, t) {
        if (null == e)
            return {};
        var n, r, a = function(e, t) {
            if (null == e)
                return {};
            var n = {};
            for (var r in e)
                if ({}.hasOwnProperty.call(e, r)) {
                    if (t.includes(r))
                        continue;
                    n[r] = e[r]
                }
            return n
        }(e, t);
        if (Object.getOwnPropertySymbols) {
            var o = Object.getOwnPropertySymbols(e);
            for (r = 0; r < o.length; r++)
                n = o[r],
                t.includes(n) || {}.propertyIsEnumerable.call(e, n) && (a[n] = e[n])
        }
        return a
    }
    n(4358);
    const p = ["page"]
      , f = ["page", "matches"]
      , m = ["onClick", "discover", "prefetch", "relative", "reloadDocument", "replace", "state", "target", "to", "preventScrollReset", "viewTransition"]
      , h = ["aria-current", "caseSensitive", "className", "end", "style", "to", "viewTransition", "children"]
      , g = ["discover", "fetcherKey", "navigate", "reloadDocument", "replace", "state", "method", "action", "onSubmit", "relative", "preventScrollReset", "viewTransition"];
    var v = "popstate";
    function y() {
        return E((function(e, t) {
            let {pathname: n, search: r, hash: a} = e.location;
            return A("", {
                pathname: n,
                search: r,
                hash: a
            }, t.state && t.state.usr || null, t.state && t.state.key || "default")
        }
        ), (function(e, t) {
            return "string" === typeof t ? t : k(t)
        }
        ), null, arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : {})
    }
    function b(e, t) {
        if (!1 === e || null === e || "undefined" === typeof e)
            throw new Error(t)
    }
    function x(e, t) {
        if (!e) {
            "undefined" !== typeof console && console.warn(t);
            try {
                throw new Error(t)
            } catch (n) {}
        }
    }
    function w(e, t) {
        return {
            usr: e.state,
            key: e.key,
            idx: t
        }
    }
    function A(e, t) {
        let n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : null
          , r = arguments.length > 3 ? arguments[3] : void 0;
        return c(c({
            pathname: "string" === typeof e ? e : e.pathname,
            search: "",
            hash: ""
        }, "string" === typeof t ? S(t) : t), {}, {
            state: n,
            key: t && t.key || r || Math.random().toString(36).substring(2, 10)
        })
    }
    function k(e) {
        let {pathname: t="/", search: n="", hash: r=""} = e;
        return n && "?" !== n && (t += "?" === n.charAt(0) ? n : "?" + n),
        r && "#" !== r && (t += "#" === r.charAt(0) ? r : "#" + r),
        t
    }
    function S(e) {
        let t = {};
        if (e) {
            let n = e.indexOf("#");
            n >= 0 && (t.hash = e.substring(n),
            e = e.substring(0, n));
            let r = e.indexOf("?");
            r >= 0 && (t.search = e.substring(r),
            e = e.substring(0, r)),
            e && (t.pathname = e)
        }
        return t
    }
    function E(e, t, n) {
        let r = arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : {}
          , {window: a=document.defaultView, v5Compat: o=!1} = r
          , i = a.history
          , l = "POP"
          , s = null
          , u = d();
        function d() {
            return (i.state || {
                idx: null
            }).idx
        }
        function p() {
            l = "POP";
            let e = d()
              , t = null == e ? null : e - u;
            u = e,
            s && s({
                action: l,
                location: m.location,
                delta: t
            })
        }
        function f(e) {
            let t = "null" !== a.location.origin ? a.location.origin : a.location.href
              , n = "string" === typeof e ? e : k(e);
            return n = n.replace(/ $/, "%20"),
            b(t, "No window.location.(origin|href) available to create URL for href: ".concat(n)),
            new URL(n,t)
        }
        null == u && (u = 0,
        i.replaceState(c(c({}, i.state), {}, {
            idx: u
        }), ""));
        let m = {
            get action() {
                return l
            },
            get location() {
                return e(a, i)
            },
            listen(e) {
                if (s)
                    throw new Error("A history only accepts one active listener");
                return a.addEventListener(v, p),
                s = e,
                () => {
                    a.removeEventListener(v, p),
                    s = null
                }
            },
            createHref: e => t(a, e),
            createURL: f,
            encodeLocation(e) {
                let t = f(e);
                return {
                    pathname: t.pathname,
                    search: t.search,
                    hash: t.hash
                }
            },
            push: function(e, t) {
                l = "PUSH";
                let r = A(m.location, e, t);
                n && n(r, e),
                u = d() + 1;
                let c = w(r, u)
                  , p = m.createHref(r);
                try {
                    i.pushState(c, "", p)
                } catch (f) {
                    if (f instanceof DOMException && "DataCloneError" === f.name)
                        throw f;
                    a.location.assign(p)
                }
                o && s && s({
                    action: l,
                    location: m.location,
                    delta: 1
                })
            },
            replace: function(e, t) {
                l = "REPLACE";
                let r = A(m.location, e, t);
                n && n(r, e),
                u = d();
                let a = w(r, u)
                  , c = m.createHref(r);
                i.replaceState(a, "", c),
                o && s && s({
                    action: l,
                    location: m.location,
                    delta: 0
                })
            },
            go: e => i.go(e)
        };
        return m
    }
    function j(e, t) {
        return N(e, t, arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : "/", !1)
    }
    function N(e, t, n, r) {
        let a = D(("string" === typeof t ? S(t) : t).pathname || "/", n);
        if (null == a)
            return null;
        let o = C(e);
        !function(e) {
            e.sort(( (e, t) => e.score !== t.score ? t.score - e.score : function(e, t) {
                let n = e.length === t.length && e.slice(0, -1).every(( (e, n) => e === t[n]));
                return n ? e[e.length - 1] - t[t.length - 1] : 0
            }(e.routesMeta.map((e => e.childrenIndex)), t.routesMeta.map((e => e.childrenIndex)))))
        }(o);
        let i = null;
        for (let l = 0; null == i && l < o.length; ++l) {
            let e = q(a);
            i = M(o[l], e, r)
        }
        return i
    }
    function C(e) {
        let t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : []
          , n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : []
          , r = arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : ""
          , a = (e, a, o) => {
            let i = {
                relativePath: void 0 === o ? e.path || "" : o,
                caseSensitive: !0 === e.caseSensitive,
                childrenIndex: a,
                route: e
            };
            i.relativePath.startsWith("/") && (b(i.relativePath.startsWith(r), 'Absolute route path "'.concat(i.relativePath, '" nested under path "').concat(r, '" is not valid. An absolute child route path must start with the combined path of all its parent routes.')),
            i.relativePath = i.relativePath.slice(r.length));
            let l = G([r, i.relativePath])
              , s = n.concat(i);
            e.children && e.children.length > 0 && (b(!0 !== e.index, 'Index routes must not have child routes. Please remove all child routes from route path "'.concat(l, '".')),
            C(e.children, t, s, l)),
            (null != e.path || e.index) && t.push({
                path: l,
                score: z(l, e.index),
                routesMeta: s
            })
        }
        ;
        return e.forEach(( (e, t) => {
            var n;
            if ("" !== e.path && null !== (n = e.path) && void 0 !== n && n.includes("?"))
                for (let r of R(e.path))
                    a(e, t, r);
            else
                a(e, t)
        }
        )),
        t
    }
    function R(e) {
        let t = e.split("/");
        if (0 === t.length)
            return [];
        let[n,...r] = t
          , a = n.endsWith("?")
          , o = n.replace(/\?$/, "");
        if (0 === r.length)
            return a ? [o, ""] : [o];
        let i = R(r.join("/"))
          , l = [];
        return l.push(...i.map((e => "" === e ? o : [o, e].join("/")))),
        a && l.push(...i),
        l.map((t => e.startsWith("/") && "" === t ? "/" : t))
    }
    var O = /^:[\w-]+$/
      , T = 3
      , L = 2
      , U = 1
      , P = 10
      , I = -2
      , F = e => "*" === e;
    function z(e, t) {
        let n = e.split("/")
          , r = n.length;
        return n.some(F) && (r += I),
        t && (r += L),
        n.filter((e => !F(e))).reduce(( (e, t) => e + (O.test(t) ? T : "" === t ? U : P)), r)
    }
    function M(e, t) {
        let n = arguments.length > 2 && void 0 !== arguments[2] && arguments[2]
          , {routesMeta: r} = e
          , a = {}
          , o = "/"
          , i = [];
        for (let l = 0; l < r.length; ++l) {
            let e = r[l]
              , s = l === r.length - 1
              , u = "/" === o ? t : t.slice(o.length) || "/"
              , c = B({
                path: e.relativePath,
                caseSensitive: e.caseSensitive,
                end: s
            }, u)
              , d = e.route;
            if (!c && s && n && !r[r.length - 1].route.index && (c = B({
                path: e.relativePath,
                caseSensitive: e.caseSensitive,
                end: !1
            }, u)),
            !c)
                return null;
            Object.assign(a, c.params),
            i.push({
                params: a,
                pathname: G([o, c.pathname]),
                pathnameBase: V(G([o, c.pathnameBase])),
                route: d
            }),
            "/" !== c.pathnameBase && (o = G([o, c.pathnameBase]))
        }
        return i
    }
    function B(e, t) {
        "string" === typeof e && (e = {
            path: e,
            caseSensitive: !1,
            end: !0
        });
        let[n,r] = function(e) {
            let t = arguments.length > 1 && void 0 !== arguments[1] && arguments[1]
              , n = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
            x("*" === e || !e.endsWith("*") || e.endsWith("/*"), 'Route path "'.concat(e, '" will be treated as if it were "').concat(e.replace(/\*$/, "/*"), '" because the `*` character must always follow a `/` in the pattern. To get rid of this warning, please change the route path to "').concat(e.replace(/\*$/, "/*"), '".'));
            let r = []
              , a = "^" + e.replace(/\/*\*?$/, "").replace(/^\/*/, "/").replace(/[\\.*+^${}|()[\]]/g, "\\$&").replace(/\/:([\w-]+)(\?)?/g, ( (e, t, n) => (r.push({
                paramName: t,
                isOptional: null != n
            }),
            n ? "/?([^\\/]+)?" : "/([^\\/]+)")));
            e.endsWith("*") ? (r.push({
                paramName: "*"
            }),
            a += "*" === e || "/*" === e ? "(.*)$" : "(?:\\/(.+)|\\/*)$") : n ? a += "\\/*$" : "" !== e && "/" !== e && (a += "(?:(?=\\/|$))");
            let o = new RegExp(a,t ? void 0 : "i");
            return [o, r]
        }(e.path, e.caseSensitive, e.end)
          , a = t.match(n);
        if (!a)
            return null;
        let o = a[0]
          , i = o.replace(/(.)\/+$/, "$1")
          , l = a.slice(1);
        return {
            params: r.reduce(( (e, t, n) => {
                let {paramName: r, isOptional: a} = t;
                if ("*" === r) {
                    let e = l[n] || "";
                    i = o.slice(0, o.length - e.length).replace(/(.)\/+$/, "$1")
                }
                const s = l[n];
                return e[r] = a && !s ? void 0 : (s || "").replace(/%2F/g, "/"),
                e
            }
            ), {}),
            pathname: o,
            pathnameBase: i,
            pattern: e
        }
    }
    function q(e) {
        try {
            return e.split("/").map((e => decodeURIComponent(e).replace(/\//g, "%2F"))).join("/")
        } catch (t) {
            return x(!1, 'The URL path "'.concat(e, '" could not be decoded because it is is a malformed URL segment. This is probably due to a bad percent encoding (').concat(t, ").")),
            e
        }
    }
    function D(e, t) {
        if ("/" === t)
            return e;
        if (!e.toLowerCase().startsWith(t.toLowerCase()))
            return null;
        let n = t.endsWith("/") ? t.length - 1 : t.length
          , r = e.charAt(n);
        return r && "/" !== r ? null : e.slice(n) || "/"
    }
    function H(e, t, n, r) {
        return "Cannot include a '".concat(e, "' character in a manually specified `to.").concat(t, "` field [").concat(JSON.stringify(r), "].  Please separate it out to the `to.").concat(n, '` field. Alternatively you may provide the full path as a string in <Link to="..."> and the router will parse it for you.')
    }
    function Q(e) {
        return e.filter(( (e, t) => 0 === t || e.route.path && e.route.path.length > 0))
    }
    function Y(e) {
        let t = Q(e);
        return t.map(( (e, n) => n === t.length - 1 ? e.pathname : e.pathnameBase))
    }
    function W(e, t, n) {
        let r, a = arguments.length > 3 && void 0 !== arguments[3] && arguments[3];
        "string" === typeof e ? r = S(e) : (r = c({}, e),
        b(!r.pathname || !r.pathname.includes("?"), H("?", "pathname", "search", r)),
        b(!r.pathname || !r.pathname.includes("#"), H("#", "pathname", "hash", r)),
        b(!r.search || !r.search.includes("#"), H("#", "search", "hash", r)));
        let o, i = "" === e || "" === r.pathname, l = i ? "/" : r.pathname;
        if (null == l)
            o = n;
        else {
            let e = t.length - 1;
            if (!a && l.startsWith("..")) {
                let t = l.split("/");
                for (; ".." === t[0]; )
                    t.shift(),
                    e -= 1;
                r.pathname = t.join("/")
            }
            o = e >= 0 ? t[e] : "/"
        }
        let s = function(e) {
            let t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "/"
              , {pathname: n, search: r="", hash: a=""} = "string" === typeof e ? S(e) : e
              , o = n ? n.startsWith("/") ? n : function(e, t) {
                let n = t.replace(/\/+$/, "").split("/");
                return e.split("/").forEach((e => {
                    ".." === e ? n.length > 1 && n.pop() : "." !== e && n.push(e)
                }
                )),
                n.length > 1 ? n.join("/") : "/"
            }(n, t) : t;
            return {
                pathname: o,
                search: Z(r),
                hash: K(a)
            }
        }(r, o)
          , u = l && "/" !== l && l.endsWith("/")
          , d = (i || "." === l) && n.endsWith("/");
        return s.pathname.endsWith("/") || !u && !d || (s.pathname += "/"),
        s
    }
    var G = e => e.join("/").replace(/\/\/+/g, "/")
      , V = e => e.replace(/\/+$/, "").replace(/^\/*/, "/")
      , Z = e => e && "?" !== e ? e.startsWith("?") ? e : "?" + e : ""
      , K = e => e && "#" !== e ? e.startsWith("#") ? e : "#" + e : "";
    function J(e) {
        return null != e && "number" === typeof e.status && "string" === typeof e.statusText && "boolean" === typeof e.internal && "data"in e
    }
    var X = ["POST", "PUT", "PATCH", "DELETE"]
      , _ = (new Set(X),
    ["GET", ...X]);
    new Set(_),
    Symbol("ResetLoaderData");
    var $ = a.createContext(null);
    $.displayName = "DataRouter";
    var ee = a.createContext(null);
    ee.displayName = "DataRouterState";
    var te = a.createContext({
        isTransitioning: !1
    });
    te.displayName = "ViewTransition";
    var ne = a.createContext(new Map);
    ne.displayName = "Fetchers";
    var re = a.createContext(null);
    re.displayName = "Await";
    var ae = a.createContext(null);
    ae.displayName = "Navigation";
    var oe = a.createContext(null);
    oe.displayName = "Location";
    var ie = a.createContext({
        outlet: null,
        matches: [],
        isDataRoute: !1
    });
    ie.displayName = "Route";
    var le = a.createContext(null);
    le.displayName = "RouteError";
    function se() {
        return null != a.useContext(oe)
    }
    function ue() {
        return b(se(), "useLocation() may be used only in the context of a <Router> component."),
        a.useContext(oe).location
    }
    var ce = "You should call navigate() in a React.useEffect(), not when your component is first rendered.";
    function de(e) {
        a.useContext(ae).static || a.useLayoutEffect(e)
    }
    function pe() {
        let {isDataRoute: e} = a.useContext(ie);
        return e ? function() {
            let {router: e} = we("useNavigate")
              , t = ke("useNavigate")
              , n = a.useRef(!1);
            de(( () => {
                n.current = !0
            }
            ));
            let r = a.useCallback((async function(r) {
                let a = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {};
                x(n.current, ce),
                n.current && ("number" === typeof r ? e.navigate(r) : await e.navigate(r, c({
                    fromRouteId: t
                }, a)))
            }
            ), [e, t]);
            return r
        }() : function() {
            b(se(), "useNavigate() may be used only in the context of a <Router> component.");
            let e = a.useContext($)
              , {basename: t, navigator: n} = a.useContext(ae)
              , {matches: r} = a.useContext(ie)
              , {pathname: o} = ue()
              , i = JSON.stringify(Y(r))
              , l = a.useRef(!1);
            de(( () => {
                l.current = !0
            }
            ));
            let s = a.useCallback((function(r) {
                let a = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {};
                if (x(l.current, ce),
                !l.current)
                    return;
                if ("number" === typeof r)
                    return void n.go(r);
                let s = W(r, JSON.parse(i), o, "path" === a.relative);
                null == e && "/" !== t && (s.pathname = "/" === s.pathname ? t : G([t, s.pathname])),
                (a.replace ? n.replace : n.push)(s, a.state, a)
            }
            ), [t, n, i, o, e]);
            return s
        }()
    }
    a.createContext(null);
    function fe(e) {
        let {relative: t} = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {}
          , {matches: n} = a.useContext(ie)
          , {pathname: r} = ue()
          , o = JSON.stringify(Y(n));
        return a.useMemo(( () => W(e, JSON.parse(o), r, "path" === t)), [e, o, r, t])
    }
    function me(e, t, n, r) {
        b(se(), "useRoutes() may be used only in the context of a <Router> component.");
        let {navigator: o} = a.useContext(ae)
          , {matches: i} = a.useContext(ie)
          , l = i[i.length - 1]
          , s = l ? l.params : {}
          , u = l ? l.pathname : "/"
          , d = l ? l.pathnameBase : "/"
          , p = l && l.route;
        {
            let e = p && p.path || "";
            je(u, !p || e.endsWith("*") || e.endsWith("*?"), 'You rendered descendant <Routes> (or called `useRoutes()`) at "'.concat(u, '" (under <Route path="').concat(e, '">) but the parent route path has no trailing "*". This means if you navigate deeper, the parent won\'t match anymore and therefore the child routes will never render.\n\nPlease change the parent <Route path="').concat(e, '"> to <Route path="').concat("/" === e ? "*" : "".concat(e, "/*"), '">.'))
        }
        let f, m = ue();
        if (t) {
            var h;
            let e = "string" === typeof t ? S(t) : t;
            b("/" === d || (null === (h = e.pathname) || void 0 === h ? void 0 : h.startsWith(d)), 'When overriding the location using `<Routes location>` or `useRoutes(routes, location)`, the location pathname must begin with the portion of the URL pathname that was matched by all parent routes. The current pathname base is "'.concat(d, '" but pathname "').concat(e.pathname, '" was given in the `location` prop.')),
            f = e
        } else
            f = m;
        let g = f.pathname || "/"
          , v = g;
        if ("/" !== d) {
            let e = d.replace(/^\//, "").split("/");
            v = "/" + g.replace(/^\//, "").split("/").slice(e.length).join("/")
        }
        let y = j(e, {
            pathname: v
        });
        x(p || null != y, 'No routes matched location "'.concat(f.pathname).concat(f.search).concat(f.hash, '" ')),
        x(null == y || void 0 !== y[y.length - 1].route.element || void 0 !== y[y.length - 1].route.Component || void 0 !== y[y.length - 1].route.lazy, 'Matched leaf route at location "'.concat(f.pathname).concat(f.search).concat(f.hash, '" does not have an element or Component. This means it will render an <Outlet /> with a null value by default resulting in an "empty" page.'));
        let w = be(y && y.map((e => Object.assign({}, e, {
            params: Object.assign({}, s, e.params),
            pathname: G([d, o.encodeLocation ? o.encodeLocation(e.pathname).pathname : e.pathname]),
            pathnameBase: "/" === e.pathnameBase ? d : G([d, o.encodeLocation ? o.encodeLocation(e.pathnameBase).pathname : e.pathnameBase])
        }))), i, n, r);
        return t && w ? a.createElement(oe.Provider, {
            value: {
                location: c({
                    pathname: "/",
                    search: "",
                    hash: "",
                    state: null,
                    key: "default"
                }, f),
                navigationType: "POP"
            }
        }, w) : w
    }
    function he() {
        let e = Se()
          , t = J(e) ? "".concat(e.status, " ").concat(e.statusText) : e instanceof Error ? e.message : JSON.stringify(e)
          , n = e instanceof Error ? e.stack : null
          , r = "rgba(200,200,200, 0.5)"
          , o = {
            padding: "0.5rem",
            backgroundColor: r
        }
          , i = {
            padding: "2px 4px",
            backgroundColor: r
        }
          , l = null;
        return console.error("Error handled by React Router default ErrorBoundary:", e),
        l = a.createElement(a.Fragment, null, a.createElement("p", null, "\ud83d\udcbf Hey developer \ud83d\udc4b"), a.createElement("p", null, "You can provide a way better UX than this when your app throws errors by providing your own ", a.createElement("code", {
            style: i
        }, "ErrorBoundary"), " or", " ", a.createElement("code", {
            style: i
        }, "errorElement"), " prop on your route.")),
        a.createElement(a.Fragment, null, a.createElement("h2", null, "Unexpected Application Error!"), a.createElement("h3", {
            style: {
                fontStyle: "italic"
            }
        }, t), n ? a.createElement("pre", {
            style: o
        }, n) : null, l)
    }
    var ge = a.createElement(he, null)
      , ve = class extends a.Component {
        constructor(e) {
            super(e),
            this.state = {
                location: e.location,
                revalidation: e.revalidation,
                error: e.error
            }
        }
        static getDerivedStateFromError(e) {
            return {
                error: e
            }
        }
        static getDerivedStateFromProps(e, t) {
            return t.location !== e.location || "idle" !== t.revalidation && "idle" === e.revalidation ? {
                error: e.error,
                location: e.location,
                revalidation: e.revalidation
            } : {
                error: void 0 !== e.error ? e.error : t.error,
                location: t.location,
                revalidation: e.revalidation || t.revalidation
            }
        }
        componentDidCatch(e, t) {
            console.error("React Router caught the following error during render", e, t)
        }
        render() {
            return void 0 !== this.state.error ? a.createElement(ie.Provider, {
                value: this.props.routeContext
            }, a.createElement(le.Provider, {
                value: this.state.error,
                children: this.props.component
            })) : this.props.children
        }
    }
    ;
    function ye(e) {
        let {routeContext: t, match: n, children: r} = e
          , o = a.useContext($);
        return o && o.static && o.staticContext && (n.route.errorElement || n.route.ErrorBoundary) && (o.staticContext._deepestRenderedBoundaryId = n.route.id),
        a.createElement(ie.Provider, {
            value: t
        }, r)
    }
    function be(e) {
        let t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : []
          , n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : null;
        if (null == e) {
            if (!n)
                return null;
            if (n.errors)
                e = n.matches;
            else {
                if (0 !== t.length || n.initialized || !(n.matches.length > 0))
                    return null;
                e = n.matches
            }
        }
        let r = e
          , o = null === n || void 0 === n ? void 0 : n.errors;
        if (null != o) {
            let e = r.findIndex((e => e.route.id && void 0 !== (null === o || void 0 === o ? void 0 : o[e.route.id])));
            b(e >= 0, "Could not find a matching route for errors on route IDs: ".concat(Object.keys(o).join(","))),
            r = r.slice(0, Math.min(r.length, e + 1))
        }
        let i = !1
          , l = -1;
        if (n)
            for (let a = 0; a < r.length; a++) {
                let e = r[a];
                if ((e.route.HydrateFallback || e.route.hydrateFallbackElement) && (l = a),
                e.route.id) {
                    let {loaderData: t, errors: a} = n
                      , o = e.route.loader && !t.hasOwnProperty(e.route.id) && (!a || void 0 === a[e.route.id]);
                    if (e.route.lazy || o) {
                        i = !0,
                        r = l >= 0 ? r.slice(0, l + 1) : [r[0]];
                        break
                    }
                }
            }
        return r.reduceRight(( (e, s, u) => {
            let c, d = !1, p = null, f = null;
            n && (c = o && s.route.id ? o[s.route.id] : void 0,
            p = s.route.errorElement || ge,
            i && (l < 0 && 0 === u ? (je("route-fallback", !1, "No `HydrateFallback` element provided to render during initial hydration"),
            d = !0,
            f = null) : l === u && (d = !0,
            f = s.route.hydrateFallbackElement || null)));
            let m = t.concat(r.slice(0, u + 1))
              , h = () => {
                let t;
                return t = c ? p : d ? f : s.route.Component ? a.createElement(s.route.Component, null) : s.route.element ? s.route.element : e,
                a.createElement(ye, {
                    match: s,
                    routeContext: {
                        outlet: e,
                        matches: m,
                        isDataRoute: null != n
                    },
                    children: t
                })
            }
            ;
            return n && (s.route.ErrorBoundary || s.route.errorElement || 0 === u) ? a.createElement(ve, {
                location: n.location,
                revalidation: n.revalidation,
                component: p,
                error: c,
                children: h(),
                routeContext: {
                    outlet: null,
                    matches: m,
                    isDataRoute: !0
                }
            }) : h()
        }
        ), null)
    }
    function xe(e) {
        return "".concat(e, " must be used within a data router.  See https://reactrouter.com/en/main/routers/picking-a-router.")
    }
    function we(e) {
        let t = a.useContext($);
        return b(t, xe(e)),
        t
    }
    function Ae(e) {
        let t = a.useContext(ee);
        return b(t, xe(e)),
        t
    }
    function ke(e) {
        let t = function(e) {
            let t = a.useContext(ie);
            return b(t, xe(e)),
            t
        }(e)
          , n = t.matches[t.matches.length - 1];
        return b(n.route.id, "".concat(e, ' can only be used on routes that contain a unique "id"')),
        n.route.id
    }
    function Se() {
        var e;
        let t = a.useContext(le)
          , n = Ae("useRouteError")
          , r = ke("useRouteError");
        return void 0 !== t ? t : null === (e = n.errors) || void 0 === e ? void 0 : e[r]
    }
    var Ee = {};
    function je(e, t, n) {
        t || Ee[e] || (Ee[e] = !0,
        x(!1, n))
    }
    a.memo((function(e) {
        let {routes: t, future: n, state: r} = e;
        return me(t, void 0, r, n)
    }
    ));
    function Ne(e) {
        b(!1, "A <Route> is only ever to be used as the child of <Routes> element, never rendered directly. Please wrap your <Route> in a <Routes>.")
    }
    function Ce(e) {
        let {basename: t="/", children: n=null, location: r, navigationType: o="POP", navigator: i, static: l=!1} = e;
        b(!se(), "You cannot render a <Router> inside another <Router>. You should never have more than one in your app.");
        let s = t.replace(/^\/*/, "/")
          , u = a.useMemo(( () => ({
            basename: s,
            navigator: i,
            static: l,
            future: {}
        })), [s, i, l]);
        "string" === typeof r && (r = S(r));
        let {pathname: c="/", search: d="", hash: p="", state: f=null, key: m="default"} = r
          , h = a.useMemo(( () => {
            let e = D(c, s);
            return null == e ? null : {
                location: {
                    pathname: e,
                    search: d,
                    hash: p,
                    state: f,
                    key: m
                },
                navigationType: o
            }
        }
        ), [s, c, d, p, f, m, o]);
        return x(null != h, '<Router basename="'.concat(s, '"> is not able to match the URL "').concat(c).concat(d).concat(p, "\" because it does not start with the basename, so the <Router> won't render anything.")),
        null == h ? null : a.createElement(ae.Provider, {
            value: u
        }, a.createElement(oe.Provider, {
            children: n,
            value: h
        }))
    }
    function Re(e) {
        let {children: t, location: n} = e;
        return me(Oe(t), n)
    }
    a.Component;
    function Oe(e) {
        let t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : []
          , n = [];
        return a.Children.forEach(e, ( (e, r) => {
            if (!a.isValidElement(e))
                return;
            let o = [...t, r];
            if (e.type === a.Fragment)
                return void n.push.apply(n, Oe(e.props.children, o));
            b(e.type === Ne, "[".concat("string" === typeof e.type ? e.type : e.type.name, "] is not a <Route> component. All component children of <Routes> must be a <Route> or <React.Fragment>")),
            b(!e.props.index || !e.props.children, "An index route cannot have child routes.");
            let i = {
                id: e.props.id || o.join("-"),
                caseSensitive: e.props.caseSensitive,
                element: e.props.element,
                Component: e.props.Component,
                index: e.props.index,
                path: e.props.path,
                loader: e.props.loader,
                action: e.props.action,
                hydrateFallbackElement: e.props.hydrateFallbackElement,
                HydrateFallback: e.props.HydrateFallback,
                errorElement: e.props.errorElement,
                ErrorBoundary: e.props.ErrorBoundary,
                hasErrorBoundary: !0 === e.props.hasErrorBoundary || null != e.props.ErrorBoundary || null != e.props.errorElement,
                shouldRevalidate: e.props.shouldRevalidate,
                handle: e.props.handle,
                lazy: e.props.lazy
            };
            e.props.children && (i.children = Oe(e.props.children, o)),
            n.push(i)
        }
        )),
        n
    }
    var Te = "get"
      , Le = "application/x-www-form-urlencoded";
    function Ue(e) {
        return null != e && "string" === typeof e.tagName
    }
    var Pe = null;
    var Ie = new Set(["application/x-www-form-urlencoded", "multipart/form-data", "text/plain"]);
    function Fe(e) {
        return null == e || Ie.has(e) ? e : (x(!1, '"'.concat(e, '" is not a valid `encType` for `<Form>`/`<fetcher.Form>` and will default to "').concat(Le, '"')),
        null)
    }
    function ze(e, t) {
        let n, r, a, o, i;
        if (Ue(l = e) && "form" === l.tagName.toLowerCase()) {
            let i = e.getAttribute("action");
            r = i ? D(i, t) : null,
            n = e.getAttribute("method") || Te,
            a = Fe(e.getAttribute("enctype")) || Le,
            o = new FormData(e)
        } else if (function(e) {
            return Ue(e) && "button" === e.tagName.toLowerCase()
        }(e) || function(e) {
            return Ue(e) && "input" === e.tagName.toLowerCase()
        }(e) && ("submit" === e.type || "image" === e.type)) {
            let i = e.form;
            if (null == i)
                throw new Error('Cannot submit a <button> or <input type="submit"> without a <form>');
            let l = e.getAttribute("formaction") || i.getAttribute("action");
            if (r = l ? D(l, t) : null,
            n = e.getAttribute("formmethod") || i.getAttribute("method") || Te,
            a = Fe(e.getAttribute("formenctype")) || Fe(i.getAttribute("enctype")) || Le,
            o = new FormData(i,e),
            !function() {
                if (null === Pe)
                    try {
                        new FormData(document.createElement("form"),0),
                        Pe = !1
                    } catch (e) {
                        Pe = !0
                    }
                return Pe
            }()) {
                let {name: t, type: n, value: r} = e;
                if ("image" === n) {
                    let e = t ? "".concat(t, ".") : "";
                    o.append("".concat(e, "x"), "0"),
                    o.append("".concat(e, "y"), "0")
                } else
                    t && o.append(t, r)
            }
        } else {
            if (Ue(e))
                throw new Error('Cannot submit element that is not <form>, <button>, or <input type="submit|image">');
            n = Te,
            r = null,
            a = Le,
            i = e
        }
        var l;
        return o && "text/plain" === a && (i = o,
        o = void 0),
        {
            action: r,
            method: n.toLowerCase(),
            encType: a,
            formData: o,
            body: i
        }
    }
    function Me(e, t) {
        if (!1 === e || null === e || "undefined" === typeof e)
            throw new Error(t)
    }
    async function Be(e, t) {
        if (e.id in t)
            return t[e.id];
        try {
            let n = await import(e.module);
            return t[e.id] = n,
            n
        } catch (n) {
            return console.error("Error loading route module `".concat(e.module, "`, reloading page...")),
            console.error(n),
            window.__reactRouterContext && window.__reactRouterContext.isSpaMode,
            window.location.reload(),
            new Promise(( () => {}
            ))
        }
    }
    function qe(e) {
        return null != e && "string" === typeof e.page
    }
    function De(e) {
        return null != e && (null == e.href ? "preload" === e.rel && "string" === typeof e.imageSrcSet && "string" === typeof e.imageSizes : "string" === typeof e.rel && "string" === typeof e.href)
    }
    function He(e, t, n, r, a, o) {
        let i = (e, t) => !n[t] || e.route.id !== n[t].route.id
          , l = (e, t) => {
            var r;
            return n[t].pathname !== e.pathname || (null === (r = n[t].route.path) || void 0 === r ? void 0 : r.endsWith("*")) && n[t].params["*"] !== e.params["*"]
        }
        ;
        return "assets" === o ? t.filter(( (e, t) => i(e, t) || l(e, t))) : "data" === o ? t.filter(( (t, o) => {
            let s = r.routes[t.route.id];
            if (!s || !s.hasLoader)
                return !1;
            if (i(t, o) || l(t, o))
                return !0;
            if (t.route.shouldRevalidate) {
                var u;
                let r = t.route.shouldRevalidate({
                    currentUrl: new URL(a.pathname + a.search + a.hash,window.origin),
                    currentParams: (null === (u = n[0]) || void 0 === u ? void 0 : u.params) || {},
                    nextUrl: new URL(e,window.origin),
                    nextParams: t.params,
                    defaultShouldRevalidate: !0
                });
                if ("boolean" === typeof r)
                    return r
            }
            return !0
        }
        )) : []
    }
    function Qe(e) {
        return [...new Set(e)]
    }
    function Ye(e, t) {
        let n = new Set
          , r = new Set(t);
        return e.reduce(( (e, a) => {
            if (t && !qe(a) && "script" === a.as && a.href && r.has(a.href))
                return e;
            let o = JSON.stringify(function(e) {
                let t = {}
                  , n = Object.keys(e).sort();
                for (let r of n)
                    t[r] = e[r];
                return t
            }(a));
            return n.has(o) || (n.add(o),
            e.push({
                key: o,
                link: a
            })),
            e
        }
        ), [])
    }
    function We(e) {
        return {
            __html: e
        }
    }
    Symbol("SingleFetchRedirect");
    function Ge(e) {
        let t = "string" === typeof e ? new URL(e,"undefined" === typeof window ? "server://singlefetch/" : window.location.origin) : e;
        return "/" === t.pathname ? t.pathname = "_root.data" : t.pathname = "".concat(t.pathname.replace(/\/$/, ""), ".data"),
        t
    }
    a.Component;
    function Ve(e) {
        let {error: t, isOutsideRemixApp: n} = e;
        console.error(t);
        let r, o = a.createElement("script", {
            dangerouslySetInnerHTML: {
                __html: '\n        console.log(\n          "\ud83d\udcbf Hey developer \ud83d\udc4b. You can provide a way better UX than this when your app throws errors. Check out https://remix.run/guides/errors for more information."\n        );\n      '
            }
        });
        if (J(t))
            return a.createElement(Ze, {
                title: "Unhandled Thrown Response!"
            }, a.createElement("h1", {
                style: {
                    fontSize: "24px"
                }
            }, t.status, " ", t.statusText), o);
        if (t instanceof Error)
            r = t;
        else {
            let e = null == t ? "Unknown Error" : "object" === typeof t && "toString"in t ? t.toString() : JSON.stringify(t);
            r = new Error(e)
        }
        return a.createElement(Ze, {
            title: "Application Error!",
            isOutsideRemixApp: n
        }, a.createElement("h1", {
            style: {
                fontSize: "24px"
            }
        }, "Application Error"), a.createElement("pre", {
            style: {
                padding: "2rem",
                background: "hsla(10, 50%, 50%, 0.1)",
                color: "red",
                overflow: "auto"
            }
        }, r.stack), o)
    }
    function Ze(e) {
        var t;
        let {title: n, renderScripts: r, isOutsideRemixApp: o, children: i} = e
          , {routeModules: l} = $e();
        return null !== (t = l.root) && void 0 !== t && t.Layout && !o ? i : a.createElement("html", {
            lang: "en"
        }, a.createElement("head", null, a.createElement("meta", {
            charSet: "utf-8"
        }), a.createElement("meta", {
            name: "viewport",
            content: "width=device-width,initial-scale=1,viewport-fit=cover"
        }), a.createElement("title", null, n)), a.createElement("body", null, a.createElement("main", {
            style: {
                fontFamily: "system-ui, sans-serif",
                padding: "2rem"
            }
        }, i, r ? a.createElement(it, null) : null)))
    }
    function Ke(e) {
        return !e
    }
    function Je() {
        let e = a.useContext($);
        return Me(e, "You must render this element inside a <DataRouterContext.Provider> element"),
        e
    }
    function Xe() {
        let e = a.useContext(ee);
        return Me(e, "You must render this element inside a <DataRouterStateContext.Provider> element"),
        e
    }
    var _e = a.createContext(void 0);
    function $e() {
        let e = a.useContext(_e);
        return Me(e, "You must render this element inside a <HydratedRouter> element"),
        e
    }
    function et(e, t) {
        return n => {
            e && e(n),
            n.defaultPrevented || t(n)
        }
    }
    function tt(e, t, n) {
        if (n && !ot)
            return [e[0]];
        if (t) {
            let n = e.findIndex((e => void 0 !== t[e.route.id]));
            return e.slice(0, n + 1)
        }
        return e
    }
    function nt(e) {
        let {page: t} = e
          , n = d(e, p)
          , {router: r} = Je()
          , o = a.useMemo(( () => j(r.routes, t, r.basename)), [r.routes, t, r.basename]);
        return o ? a.createElement(at, c({
            page: t,
            matches: o
        }, n)) : (console.warn("Tried to prefetch ".concat(t, " but no routes matched.")),
        null)
    }
    function rt(e) {
        let {manifest: t, routeModules: n} = $e()
          , [r,o] = a.useState([]);
        return a.useEffect(( () => {
            let r = !1;
            return async function(e, t, n) {
                return Ye((await Promise.all(e.map((async e => {
                    let r = t.routes[e.route.id];
                    if (r) {
                        let e = await Be(r, n);
                        return e.links ? e.links() : []
                    }
                    return []
                }
                )))).flat(1).filter(De).filter((e => "stylesheet" === e.rel || "preload" === e.rel)).map((e => "stylesheet" === e.rel ? c(c({}, e), {}, {
                    rel: "prefetch",
                    as: "style"
                }) : c(c({}, e), {}, {
                    rel: "prefetch"
                }))))
            }(e, t, n).then((e => {
                r || o(e)
            }
            )),
            () => {
                r = !0
            }
        }
        ), [e, t, n]),
        r
    }
    function at(e) {
        let {page: t, matches: n} = e
          , r = d(e, f)
          , o = ue()
          , {manifest: i, routeModules: l} = $e()
          , {loaderData: s, matches: u} = Xe()
          , p = a.useMemo(( () => He(t, n, u, i, o, "data")), [t, n, u, i, o])
          , m = a.useMemo(( () => He(t, n, u, i, o, "assets")), [t, n, u, i, o])
          , h = a.useMemo(( () => {
            if (t === o.pathname + o.search + o.hash)
                return [];
            let e = new Set
              , r = !1;
            if (n.forEach((t => {
                var n;
                let a = i.routes[t.route.id];
                a && a.hasLoader && (!p.some((e => e.route.id === t.route.id)) && t.route.id in s && null !== (n = l[t.route.id]) && void 0 !== n && n.shouldRevalidate || a.hasClientLoader ? r = !0 : e.add(t.route.id))
            }
            )),
            0 === e.size)
                return [];
            let a = Ge(t);
            return r && e.size > 0 && a.searchParams.set("_routes", n.filter((t => e.has(t.route.id))).map((e => e.route.id)).join(",")),
            [a.pathname + a.search]
        }
        ), [s, o, i, p, n, t, l])
          , g = a.useMemo(( () => function(e, t) {
            return Qe(e.map((e => {
                let n = t.routes[e.route.id];
                if (!n)
                    return [];
                let r = [n.module];
                return n.imports && (r = r.concat(n.imports)),
                r
            }
            )).flat(1))
        }(m, i)), [m, i])
          , v = rt(m);
        return a.createElement(a.Fragment, null, h.map((e => a.createElement("link", c({
            key: e,
            rel: "prefetch",
            as: "fetch",
            href: e
        }, r)))), g.map((e => a.createElement("link", c({
            key: e,
            rel: "modulepreload",
            href: e
        }, r)))), v.map((e => {
            let {key: t, link: n} = e;
            return a.createElement("link", c({
                key: t
            }, n))
        }
        )))
    }
    _e.displayName = "FrameworkContext";
    var ot = !1;
    function it(e) {
        let {manifest: t, serverHandoffString: n, isSpaMode: r, renderMeta: o} = $e()
          , {router: i, static: l, staticContext: s} = Je()
          , {matches: u} = Xe()
          , d = Ke(r);
        o && (o.didRenderScripts = !0);
        let p = tt(u, null, r);
        a.useEffect(( () => {
            ot = !0
        }
        ), []);
        let f = a.useMemo(( () => {
            var r;
            let o = s ? "window.__reactRouterContext = ".concat(n, ";").concat("window.__reactRouterContext.stream = new ReadableStream({start(controller){window.__reactRouterContext.streamController = controller;}}).pipeThrough(new TextEncoderStream());") : " "
              , u = l ? "".concat(null !== (r = t.hmr) && void 0 !== r && r.runtime ? "import ".concat(JSON.stringify(t.hmr.runtime), ";") : "").concat(d ? "" : "import ".concat(JSON.stringify(t.url)), ";\n").concat(p.map(( (e, n) => "import * as route".concat(n, " from ").concat(JSON.stringify(t.routes[e.route.id].module), ";"))).join("\n"), "\n  ").concat(d ? "window.__reactRouterManifest = ".concat(JSON.stringify(function(e, t) {
                let n = new Set(t.state.matches.map((e => e.route.id)))
                  , r = t.state.location.pathname.split("/").filter(Boolean)
                  , a = ["/"];
                for (r.pop(); r.length > 0; )
                    a.push("/".concat(r.join("/"))),
                    r.pop();
                a.forEach((e => {
                    let r = j(t.routes, e, t.basename);
                    r && r.forEach((e => n.add(e.route.id)))
                }
                ));
                let o = [...n].reduce(( (t, n) => Object.assign(t, {
                    [n]: e.routes[n]
                })), {});
                return c(c({}, e), {}, {
                    routes: o
                })
            }(t, i), null, 2), ";") : "", "\n  window.__reactRouterRouteModules = {").concat(p.map(( (e, t) => "".concat(JSON.stringify(e.route.id), ":route").concat(t))).join(","), "};\n\nimport(").concat(JSON.stringify(t.entry.module), ");") : " ";
            return a.createElement(a.Fragment, null, a.createElement("script", c(c({}, e), {}, {
                suppressHydrationWarning: !0,
                dangerouslySetInnerHTML: We(o),
                type: void 0
            })), a.createElement("script", c(c({}, e), {}, {
                suppressHydrationWarning: !0,
                dangerouslySetInnerHTML: We(u),
                type: "module",
                async: !0
            })))
        }
        ), [])
          , m = p.map((e => {
            let n = t.routes[e.route.id];
            return n ? (n.imports || []).concat([n.module]) : []
        }
        )).flat(1)
          , h = ot ? [] : t.entry.imports.concat(m);
        return ot ? null : a.createElement(a.Fragment, null, d ? null : a.createElement("link", {
            rel: "modulepreload",
            href: t.url,
            crossOrigin: e.crossOrigin
        }), a.createElement("link", {
            rel: "modulepreload",
            href: t.entry.module,
            crossOrigin: e.crossOrigin
        }), (g = h,
        [...new Set(g)]).map((t => a.createElement("link", {
            key: t,
            rel: "modulepreload",
            href: t,
            crossOrigin: e.crossOrigin
        }))), f);
        var g
    }
    function lt() {
        for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++)
            t[n] = arguments[n];
        return e => {
            t.forEach((t => {
                "function" === typeof t ? t(e) : null != t && (t.current = e)
            }
            ))
        }
    }
    var st = "undefined" !== typeof window && "undefined" !== typeof window.document && "undefined" !== typeof window.document.createElement;
    try {
        st && (window.__reactRouterVersion = "7.0.2")
    } catch (sl) {}
    function ut(e) {
        let {basename: t, children: n, window: r} = e
          , o = a.useRef();
        null == o.current && (o.current = y({
            window: r,
            v5Compat: !0
        }));
        let i = o.current
          , [l,s] = a.useState({
            action: i.action,
            location: i.location
        })
          , u = a.useCallback((e => {
            a.startTransition(( () => s(e)))
        }
        ), [s]);
        return a.useLayoutEffect(( () => i.listen(u)), [i, u]),
        a.createElement(Ce, {
            basename: t,
            children: n,
            location: l.location,
            navigationType: l.action,
            navigator: i
        })
    }
    var ct = /^(?:[a-z][a-z0-9+.-]*:|\/\/)/i
      , dt = a.forwardRef((function(e, t) {
        let n, {onClick: r, discover: o="render", prefetch: i="none", relative: l, reloadDocument: s, replace: u, state: p, target: f, to: h, preventScrollReset: g, viewTransition: v} = e, y = d(e, m), {basename: w} = a.useContext(ae), A = "string" === typeof h && ct.test(h), S = !1;
        if ("string" === typeof h && A && (n = h,
        st))
            try {
                let e = new URL(window.location.href)
                  , t = h.startsWith("//") ? new URL(e.protocol + h) : new URL(h)
                  , n = D(t.pathname, w);
                t.origin === e.origin && null != n ? h = n + t.search + t.hash : S = !0
            } catch (sl) {
                x(!1, '<Link to="'.concat(h, '"> contains an invalid URL which will probably break when clicked - please update to a valid URL path.'))
            }
        let E = function(e) {
            let {relative: t} = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {};
            b(se(), "useHref() may be used only in the context of a <Router> component.");
            let {basename: n, navigator: r} = a.useContext(ae)
              , {hash: o, pathname: i, search: l} = fe(e, {
                relative: t
            })
              , s = i;
            return "/" !== n && (s = "/" === i ? n : G([n, i])),
            r.createHref({
                pathname: s,
                search: l,
                hash: o
            })
        }(h, {
            relative: l
        })
          , [j,N,C] = function(e, t) {
            let n = a.useContext(_e)
              , [r,o] = a.useState(!1)
              , [i,l] = a.useState(!1)
              , {onFocus: s, onBlur: u, onMouseEnter: c, onMouseLeave: d, onTouchStart: p} = t
              , f = a.useRef(null);
            a.useEffect(( () => {
                if ("render" === e && l(!0),
                "viewport" === e) {
                    let e = new IntersectionObserver((e => {
                        e.forEach((e => {
                            l(e.isIntersecting)
                        }
                        ))
                    }
                    ),{
                        threshold: .5
                    });
                    return f.current && e.observe(f.current),
                    () => {
                        e.disconnect()
                    }
                }
            }
            ), [e]),
            a.useEffect(( () => {
                if (r) {
                    let e = setTimeout(( () => {
                        l(!0)
                    }
                    ), 100);
                    return () => {
                        clearTimeout(e)
                    }
                }
            }
            ), [r]);
            let m = () => {
                o(!0)
            }
              , h = () => {
                o(!1),
                l(!1)
            }
            ;
            return n ? "intent" !== e ? [i, f, {}] : [i, f, {
                onFocus: et(s, m),
                onBlur: et(u, h),
                onMouseEnter: et(c, m),
                onMouseLeave: et(d, h),
                onTouchStart: et(p, m)
            }] : [!1, f, {}]
        }(i, y)
          , R = function(e) {
            let {target: t, replace: n, state: r, preventScrollReset: o, relative: i, viewTransition: l} = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {}
              , s = pe()
              , u = ue()
              , c = fe(e, {
                relative: i
            });
            return a.useCallback((a => {
                if (function(e, t) {
                    return 0 === e.button && (!t || "_self" === t) && !function(e) {
                        return !!(e.metaKey || e.altKey || e.ctrlKey || e.shiftKey)
                    }(e)
                }(a, t)) {
                    a.preventDefault();
                    let t = void 0 !== n ? n : k(u) === k(c);
                    s(e, {
                        replace: t,
                        state: r,
                        preventScrollReset: o,
                        relative: i,
                        viewTransition: l
                    })
                }
            }
            ), [u, s, c, n, r, t, e, o, i, l])
        }(h, {
            replace: u,
            state: p,
            target: f,
            preventScrollReset: g,
            relative: l,
            viewTransition: v
        });
        let O = a.createElement("a", c(c(c({}, y), C), {}, {
            href: n || E,
            onClick: S || s ? r : function(e) {
                r && r(e),
                e.defaultPrevented || R(e)
            }
            ,
            ref: lt(t, N),
            target: f,
            "data-discover": A || "render" !== o ? void 0 : "true"
        }));
        return j && !A ? a.createElement(a.Fragment, null, O, a.createElement(nt, {
            page: E
        })) : O
    }
    ));
    dt.displayName = "Link";
    var pt = a.forwardRef((function(e, t) {
        let {"aria-current": n="page", caseSensitive: r=!1, className: o="", end: i=!1, style: l, to: s, viewTransition: u, children: p} = e
          , f = d(e, h)
          , m = fe(s, {
            relative: f.relative
        })
          , g = ue()
          , v = a.useContext(ee)
          , {navigator: y, basename: x} = a.useContext(ae)
          , w = null != v && function(e) {
            let t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {}
              , n = a.useContext(te);
            b(null != n, "`useViewTransitionState` must be used within `react-router-dom`'s `RouterProvider`.  Did you accidentally import `RouterProvider` from `react-router`?");
            let {basename: r} = ht("useViewTransitionState")
              , o = fe(e, {
                relative: t.relative
            });
            if (!n.isTransitioning)
                return !1;
            let i = D(n.currentLocation.pathname, r) || n.currentLocation.pathname
              , l = D(n.nextLocation.pathname, r) || n.nextLocation.pathname;
            return null != B(o.pathname, l) || null != B(o.pathname, i)
        }(m) && !0 === u
          , A = y.encodeLocation ? y.encodeLocation(m).pathname : m.pathname
          , k = g.pathname
          , S = v && v.navigation && v.navigation.location ? v.navigation.location.pathname : null;
        r || (k = k.toLowerCase(),
        S = S ? S.toLowerCase() : null,
        A = A.toLowerCase()),
        S && x && (S = D(S, x) || S);
        const E = "/" !== A && A.endsWith("/") ? A.length - 1 : A.length;
        let j, N = k === A || !i && k.startsWith(A) && "/" === k.charAt(E), C = null != S && (S === A || !i && S.startsWith(A) && "/" === S.charAt(A.length)), R = {
            isActive: N,
            isPending: C,
            isTransitioning: w
        }, O = N ? n : void 0;
        j = "function" === typeof o ? o(R) : [o, N ? "active" : null, C ? "pending" : null, w ? "transitioning" : null].filter(Boolean).join(" ");
        let T = "function" === typeof l ? l(R) : l;
        return a.createElement(dt, c(c({}, f), {}, {
            "aria-current": O,
            className: j,
            ref: t,
            style: T,
            to: s,
            viewTransition: u
        }), "function" === typeof p ? p(R) : p)
    }
    ));
    pt.displayName = "NavLink";
    var ft = a.forwardRef(( (e, t) => {
        let {discover: n="render", fetcherKey: r, navigate: o, reloadDocument: i, replace: l, state: s, method: u=Te, action: p, onSubmit: f, relative: m, preventScrollReset: h, viewTransition: v} = e
          , y = d(e, g)
          , x = yt()
          , w = function(e) {
            let {relative: t} = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {}
              , {basename: n} = a.useContext(ae)
              , r = a.useContext(ie);
            b(r, "useFormAction must be used inside a RouteContext");
            let[o] = r.matches.slice(-1)
              , i = c({}, fe(e || ".", {
                relative: t
            }))
              , l = ue();
            if (null == e) {
                i.search = l.search;
                let e = new URLSearchParams(i.search)
                  , t = e.getAll("index");
                if (t.some((e => "" === e))) {
                    e.delete("index"),
                    t.filter((e => e)).forEach((t => e.append("index", t)));
                    let n = e.toString();
                    i.search = n ? "?".concat(n) : ""
                }
            }
            e && "." !== e || !o.route.index || (i.search = i.search ? i.search.replace(/^\?/, "?index&") : "?index");
            "/" !== n && (i.pathname = "/" === i.pathname ? n : G([n, i.pathname]));
            return k(i)
        }(p, {
            relative: m
        })
          , A = "get" === u.toLowerCase() ? "get" : "post"
          , S = "string" === typeof p && ct.test(p);
        return a.createElement("form", c(c({
            ref: t,
            method: A,
            action: w,
            onSubmit: i ? f : e => {
                if (f && f(e),
                e.defaultPrevented)
                    return;
                e.preventDefault();
                let t = e.nativeEvent.submitter
                  , n = (null === t || void 0 === t ? void 0 : t.getAttribute("formmethod")) || u;
                x(t || e.currentTarget, {
                    fetcherKey: r,
                    method: n,
                    navigate: o,
                    replace: l,
                    state: s,
                    relative: m,
                    preventScrollReset: h,
                    viewTransition: v
                })
            }
        }, y), {}, {
            "data-discover": S || "render" !== n ? void 0 : "true"
        }))
    }
    ));
    function mt(e) {
        return "".concat(e, " must be used within a data router.  See https://reactrouter.com/en/main/routers/picking-a-router.")
    }
    function ht(e) {
        let t = a.useContext($);
        return b(t, mt(e)),
        t
    }
    ft.displayName = "Form";
    var gt = 0
      , vt = () => "__".concat(String(++gt), "__");
    function yt() {
        let {router: e} = ht("useSubmit")
          , {basename: t} = a.useContext(ae)
          , n = ke("useRouteId");
        return a.useCallback((async function(r) {
            let a = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {}
              , {action: o, method: i, encType: l, formData: s, body: u} = ze(r, t);
            if (!1 === a.navigate) {
                let t = a.fetcherKey || vt();
                await e.fetch(t, n, a.action || o, {
                    preventScrollReset: a.preventScrollReset,
                    formData: s,
                    body: u,
                    formMethod: a.method || i,
                    formEncType: a.encType || l,
                    flushSync: a.flushSync
                })
            } else
                await e.navigate(a.action || o, {
                    preventScrollReset: a.preventScrollReset,
                    formData: s,
                    body: u,
                    formMethod: a.method || i,
                    formEncType: a.encType || l,
                    replace: a.replace,
                    state: a.state,
                    fromRouteId: n,
                    flushSync: a.flushSync,
                    viewTransition: a.viewTransition
                })
        }
        ), [e, t, n])
    }
    new TextEncoder;
    const bt = ""
      , xt = "/home"
      , wt = "/rating"
      , At = "/friends"
      , kt = "/classic"
      , St = "/mode-section"
      , Et = "/blitz"
      , jt = "/survival"
      , Nt = "/squads"
      , Ct = "/squads/create"
      , Rt = "/squads/list"
      , Ot = "/prizes"
      , Tt = "https://dev.lovikwami-test-bot.ru"
      , Lt = 500
      , Ut = 100
      , Pt = 5e3
      , It = 3e3
      , Ft = 1e4
      , zt = 500
      , Mt = 5e3
      , Bt = 5e3
      , qt = "classic"
      , Dt = "blitz"
      , Ht = "survival"
      , Qt = {
        [qt]: 60,
        [Dt]: 30
    };
    var Yt = n(579);
    const Wt = e => {
        let {disabled: t, children: n, ghost: r, onClick: a, variant: o} = e;
        const i = ["app-big-green-button"];
        return "boolean" === typeof r && i.push("app-big-green-button_ghost"),
        t && i.push("app-big-green-button_disabled"),
        o && i.push("app-big-green-button--".concat(o)),
        (0,
        Yt.jsx)("button", {
            disabled: t,
            className: i.join(" "),
            onClick: () => a(),
            children: n
        })
    }
    ;
    const Gt = n.p + "static/media/user.ba8f48d036d8a8a2fd89cacb95e01029.svg";
    const Vt = n.p + "static/media/prizes-nav-bottom.bebfc80f7562f09f68d07661a994553a.svg"
      , Zt = () => (0,
    Yt.jsxs)("svg", {
        width: "42",
        height: "43",
        viewBox: "0 0 42 43",
        fill: "none",
        xmlns: "http://www.w3.org/2000/svg",
        children: [(0,
        Yt.jsx)("g", {
            filter: "url(#filter0_f_3262_829)",
            children: (0,
            Yt.jsx)("circle", {
                cx: "21",
                cy: "21.5",
                r: "13",
                fill: "#87FF85",
                fillOpacity: "0.54"
            })
        }), (0,
        Yt.jsx)("defs", {
            children: (0,
            Yt.jsxs)("filter", {
                id: "filter0_f_3262_829",
                x: "0",
                y: "0.5",
                width: "42",
                height: "42",
                filterUnits: "userSpaceOnUse",
                colorInterpolationFilters: "sRGB",
                children: [(0,
                Yt.jsx)("feFlood", {
                    floodOpacity: "0",
                    result: "BackgroundImageFix"
                }), (0,
                Yt.jsx)("feBlend", {
                    mode: "normal",
                    in: "SourceGraphic",
                    in2: "BackgroundImageFix",
                    result: "shape"
                }), (0,
                Yt.jsx)("feGaussianBlur", {
                    stdDeviation: "4",
                    result: "effect1_foregroundBlur_3262_829"
                })]
            })
        })]
    })
      , Kt = () => (0,
    Yt.jsxs)("div", {
        className: "app-bottom-nav",
        children: [(0,
        Yt.jsxs)(pt, {
            to: xt,
            className: "app-bottom-nav-item",
            children: [(0,
            Yt.jsx)(Zt, {}), (0,
            Yt.jsx)("img", {
                src: "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAABYlAAAWJQFJUiTwAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAOpSURBVHgB7ZlLSBVRGMe/2zuMUolMi7xqq9z0wLCCMiUwJCqIInAhvawWqVGrSHtRFC3CTbUoLCRutIpKwcA2RYuwTZCRmdKLKOgaPaCsvv6HGfEwnZn5Zu6jhfcHf2ac8/++c87MmTnnXIkyZMgwtmHmA9BiCgliS6BG+h+g4iJoGOqikCD2FvRTdYTSDSq9xKNMp4AgpkCLP0bpBpW+0BrwEeqFmgRxDdAg9EqL76N0ggrnsBk1HBZ6xBWzOwUUkHEUnkqX6xOhc+5hdMejbAGlA9ypCDTA3lQa4mp9Yh5DidxUcQc2sD9PHTHjBZ1WVFGqQSU3WcZeLWaXMOZagKaEfgekE1eZdl4tC6EVFADfDrBhLJO84zO082myEPpM/7ahxs3s2RAEqrvRgWO5o6iTZPzSzr/LQqjH0YZSHG7juNxk9ruTO6HJUJ3jejvJ+KadD8lC6ILj74P2cSsFBb3ut1+sOBSDVmpl9wQv5BnNf17g79b8S6F26Idd1k9BQMBsQwUfoCl2eYV/e7hWy7dD4C+3vVlsLTWc5AXpwEaXSg5rni525w80T/POsq+5EdO8jS6e1SQF5j6XJGrRlm17SqHfBo8aclWGnNXQFzZ3Nmp7CqHXLnU/lDbe7e6PoI/tE46ybqjII3cUeuSRr9Wn7gpJB274JFEv1hLbm83WvqAT2mbItQpaZrheB92HTvLoe1XG/sT8Gj8Z+ipI5LnwQtlc6Lrmv8r2MHHxSxaICjU8J3h1IJ/l7HPJUQO9NfjfQ2tdYqRrJYX3rM7Wo5XQaojdL4hrNsS1sYy75AdMVYJEb9gxJNgaz1KOO2LVk48L4mQLSfZ/kTcn0PgRzjpybPfxXyYpMOew9c03cdHhbeHwHHHkirn4BjjonhkB6wyJ1BQf1TwNnDj1Wj71WXYOJTXRlVEYEHjIkaxJK4uybNz6oWbn+VreFkd5MyUCEhy1E71k7RuM8+ecPB7w6ISm5qKRlfApSgZItAkq1v6u5+SzR8uvnu56v3ZFKAT2neqFopRcPkElkUhEuvkJvanfQslvvCIXWhMkIGwH6ih17A5iDjyEMHzULw1xCjn8BAxDeRhGcYk5zBPIodQ1XqF+W50qNQfuAO7MIA7+CyoL5VVrl0X2uYQO1PGOUgmG0STotM8ncQAq1GKi2rfdxBBb66ksShd2o9pcGp9v8Kv/KTxzeNUsfIW1OSbtsLX7UnvjHra2lzM9vPl2p59AzVAuZciQYezyF5Vi8Gy0PiM3AAAAAElFTkSuQmCC",
                alt: ""
            }), (0,
            Yt.jsx)("span", {
                children: "\u0418\u0433\u0440\u0430"
            })]
        }), (0,
        Yt.jsxs)(pt, {
            to: Nt,
            className: "app-bottom-nav-item",
            children: [(0,
            Yt.jsx)(Zt, {}), (0,
            Yt.jsx)("img", {
                src: Gt,
                alt: ""
            }), (0,
            Yt.jsx)("span", {
                children: "\u041a\u043e\u043c\u0430\u043d\u0434\u044b"
            })]
        }), (0,
        Yt.jsxs)(pt, {
            to: wt,
            className: "app-bottom-nav-item",
            children: [(0,
            Yt.jsx)(Zt, {}), (0,
            Yt.jsx)("img", {
                src: "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAABYlAAAWJQFJUiTwAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAHgSURBVHgB7ZiNVcIwEMf/dQKcQJhANhA2cAPdQDegG4gT8JxAnQA3gA3KBtQJzrvX+EQNbS4kNH0vv/fyAg097qO5XA/IZDIZG0T0wGPPo+JxhyHBCo/pP1MMBVZ2ZTFgjSFwxPvfzBCYC4Rn0bJ2i5RhD4/Mxj2GrI0QkNAREA+3KShr90gVkzK7SHMzywYld2ZIDfGswoC0osAKLUjPAn1DTc5/In9WIgMnUKBDQZ6kBJDsIZ+vzNLUfA+VEmseWzPveHyaWUZdFMXWWZLx6pra83kfvJIlWoXFgA0aD6fIB0djfnjBZsAe4R6N4LABv3S2ncQvSJfnvxdsERDvS55O7TGSjTznANSHF61ZKEEjrMoL1mLO/FA2yxv6R3SwKu8ER2NJ/bFECFhQSeenREjObESJGJzJiBIxIV3ZrEVdZvu8Ur4jHupD1McA98pQzw5KfAyIWSeNocTHgJins1q2jwE3iMc1lBTK38cut+Xt61JzgyoC1HSYNcrXZrgyImUXW/sIuQqXun0i3jQencA9RcbbY9Rd2FXU0rSipvlVdchYIRbUfgpvyKFFQk3ToGqTg1i0/LFERrWx6Xg0K8TCEgFpvTzCE7nXYkC8tiP99IzIzGOcSAyZmUxmQHwBuFigndKTxiYAAAAASUVORK5CYII=",
                alt: ""
            }), (0,
            Yt.jsx)("span", {
                children: "\u0420\u0435\u0439\u0442\u0438\u043d\u0433"
            })]
        }), (0,
        Yt.jsxs)(pt, {
            to: Ot,
            className: "app-bottom-nav-item",
            children: [(0,
            Yt.jsx)(Zt, {}), (0,
            Yt.jsx)("img", {
                src: Vt,
                alt: ""
            }), (0,
            Yt.jsx)("span", {
                children: "\u041f\u0440\u0438\u0437\u044b"
            })]
        })]
    })
      , Jt = "data:image/png;base64,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"
      , Xt = e => {
        let {coins: t, big: n} = e;
        return (0,
        Yt.jsxs)("span", {
            className: "app-coins" + (n ? " app-coins_big" : " app-coins_small"),
            children: [(0,
            Yt.jsx)("img", {
                className: "app-coins--icon",
                src: Jt,
                alt: ""
            }), (0,
            Yt.jsx)("span", {
                className: "app-coins--value",
                children: t
            })]
        })
    }
      , _t = n.p + "static/media/banner-icon.aea8bc1945d5fe611ca3.png"
      , $t = () => {
        const [e,t] = (0,
        a.useState)(!1)
          , [n,r] = (0,
        a.useState)(0)
          , [o,i] = (0,
        a.useState)(!1)
          , [l,s] = (0,
        a.useState)(!1);
        return (0,
        a.useEffect)(( () => {
            const e = new Date
              , n = new Date("2025-05-02T20:59:59Z")
              , a = new Date("2025-05-03T21:00:00Z")
              , o = new Date("2025-05-12T08:59:59Z")
              , l = n - e;
            if (l <= 0 && e < a && i(!0),
            e < n) {
                const e = Math.ceil(l / 864e5);
                t(!0),
                r(e)
            }
            e >= a && e <= o && s(!0)
        }
        ), []),
        (0,
        Yt.jsxs)("div", {
            className: "app-countdown-banner",
            children: [(0,
            Yt.jsx)("div", {
                className: "app-countdown-banner--images-container",
                children: (0,
                Yt.jsx)("img", {
                    src: _t,
                    alt: "",
                    className: "app-countdown-banner--lady-image"
                })
            }), (0,
            Yt.jsxs)("div", {
                className: "app-countdown-banner--content",
                children: [l ? (0,
                Yt.jsx)("div", {
                    className: "app-countdown-banner--title",
                    children: "\u041a\u043e\u043d\u043a\u0443\u0440\u0441 \u043f\u0440\u043e\u0434\u043e\u043b\u0436\u0430\u0435\u0442\u0441\u044f!"
                }) : o ? (0,
                Yt.jsx)("div", {
                    className: "app-countdown-banner--title",
                    children: "\u041f\u0440\u0435\u043c\u044c\u0435\u0440\u0430 \u0441\u0435\u0433\u043e\u0434\u043d\u044f \u043d\u0430 \u0422\u0412-3!"
                }) : e && (0,
                Yt.jsxs)("div", {
                    className: "app-countdown-banner--title",
                    children: [n, " ", (u = n,
                    1 === u ? "\u0434\u0435\u043d\u044c" : u > 1 && u < 5 ? "\u0434\u043d\u044f" : "\u0434\u043d\u0435\u0439"), " \u0434\u043e \u043f\u0440\u0435\u043c\u044c\u0435\u0440\u044b!"]
                }), (0,
                Yt.jsx)("div", {
                    className: "app-countdown-banner--description",
                    children: l ? (0,
                    Yt.jsxs)(Yt.Fragment, {
                        children: ["\u0418\u0433\u0440\u0430\u0439 \u0438 \u0437\u0430\u0440\u0430\u0431\u0430\u0442\u044b\u0432\u0430\u0439", (0,
                        Yt.jsx)("br", {}), " \u043f\u0440\u0438\u0437\u043e\u0432\u044b\u0435 \u0431\u0430\u043b\u043b\u044b!"]
                    }) : o ? (0,
                    Yt.jsxs)(Yt.Fragment, {
                        children: ["\u0421\u043a\u0430\u043d\u0438\u0440\u0443\u0439 QR-\u043a\u043e\u0434\u044b \u0432 \u044d\u0444\u0438\u0440\u0435,", (0,
                        Yt.jsx)("br", {}), " \u0447\u0442\u043e\u0431\u044b \u043f\u043e\u043b\u0443\u0447\u0438\u0442\u044c", (0,
                        Yt.jsx)("br", {}), "\u0434\u043e ", (0,
                        Yt.jsx)("span", {
                            className: "app-countdown-banner--yellow",
                            children: "100 000"
                        }), " \u0431\u0430\u043b\u043b\u043e\u0432"]
                    }) : (0,
                    Yt.jsxs)(Yt.Fragment, {
                        children: ["\u0412 \u0434\u0435\u043d\u044c \u043f\u0440\u0435\u043c\u044c\u0435\u0440\u044b \u0441\u043a\u0430\u043d\u0438\u0440\u0443\u0439", (0,
                        Yt.jsx)("br", {}), " QR-\u043a\u043e\u0434\u044b \u0432 \u044d\u0444\u0438\u0440\u0435, \u0447\u0442\u043e\u0431\u044b", (0,
                        Yt.jsx)("br", {}), " \u043f\u043e\u043b\u0443\u0447\u0438\u0442\u044c \u0434\u043e ", (0,
                        Yt.jsx)("span", {
                            className: "app-countdown-banner--yellow",
                            children: "100 000"
                        }), " ", "\u0431\u0430\u043b\u043b\u043e\u0432!"]
                    })
                })]
            })]
        });
        var u
    }
      , en = n.p + "static/media/final-banner-icon.5a4db947f237c7247435.png"
      , tn = {
        initData: "query_id=AAGGAt8ZAAAAAIYC3xnGxGJ7&user=%7B%22id%22%3A434045574%2C%22first_name%22%3A%22Vlad%22%2C%22last_name%22%3A%22Leonchik%22%2C%22username%22%3A%22vladislav_btw%22%2C%22language_code%22%3A%22ru%22%2C%22is_premium%22%3Atrue%2C%22allows_write_to_pm%22%3Atrue%2C%22photo_url%22%3A%22https%3A%5C%2F%5C%2Ft.me%5C%2Fi%5C%2Fuserpic%5C%2F320%5C%2FZ_oisQo8cunxbIYF8FLcXp4c_-3ZbIK8jk0SLmUu_PQ.svg%22%7D&auth_date=1743436940&signature=Pt-DJjqOVMGCfC9sn64wJnDkoiQxdB1zbix718yr7YbbB9m59zpx3aLZOWDLcLW4ALBgAWz0B8_4eguht1L8AQ&hash=45160f18a00b894aa7a26d9a81fe0beba2e92f6c43d4f6f1b1e742b7a5f5cfcf",
        version: "8.4",
        platform: "ios",
        invitedBy: null,
        onEvent: () => console.log("event"),
        isVersionAtLeast: () => !0,
        setHeaderColor: () => console.log("setHeaderColor"),
        setBackgroundColor: () => console.log("setBackgroundColor"),
        setHeaderImage: () => console.log("setHeaderImage"),
        setHeaderTitle: () => console.log("setHeaderTitle"),
        openLink: () => console.log("openLink"),
        enableClosingConfirmation: () => console.log("enableClosingConfirmation"),
        disableVerticalSwipes: () => console.log("disableVerticalSwipes"),
        expand: () => console.log("expand"),
        ready: () => console.log("ready"),
        showScanQrPopup: () => console.log("showScanQrPopup")
    }
      , nn = () => (0,
    Yt.jsxs)("div", {
        className: "app-final-banner",
        onClick: () => {
            window.Telegram.WebApp.openTelegramLink("https://t.me/tv3russia")
        }
        ,
        children: [(0,
        Yt.jsx)("img", {
            src: en,
            alt: "",
            className: "app-final-banner--image"
        }), (0,
        Yt.jsxs)("div", {
            className: "app-final-banner--content",
            children: [(0,
            Yt.jsx)("div", {
                className: "app-final-banner--title",
                children: "\u041a\u043e\u043d\u043a\u0443\u0440\u0441 \u0437\u0430\u0432\u0435\u0440\u0448\u0435\u043d!"
            }), (0,
            Yt.jsxs)("div", {
                className: "app-final-banner--description",
                children: ["\u0421\u043b\u0435\u0434\u0438 \u0437\u0430 \u0440\u0435\u0437\u0443\u043b\u044c\u0442\u0430\u0442\u0430\u043c\u0438", (0,
                Yt.jsx)("br", {}), "\u0438 \u043d\u043e\u0432\u043e\u0441\u0442\u044f\u043c\u0438 \u043e \u043d\u043e\u0432\u043e\u043c \u0441\u0435\u0437\u043e\u043d\u0435", (0,
                Yt.jsx)("br", {}), "\u0432 \u043d\u0430\u0448\u0435\u043c \u0442\u0435\u043b\u0435\u0433\u0440\u0430\u043c-\u043a\u0430\u043d\u0430\u043b\u0435."]
            })]
        })]
    })
      , rn = e => {
        let {image: t, title: n, coins: r, onClick: a} = e;
        return (0,
        Yt.jsxs)("div", {
            className: "app-friend-card",
            children: [(0,
            Yt.jsx)("img", {
                src: t,
                alt: "",
                className: "app-friend-card--image"
            }), (0,
            Yt.jsxs)("div", {
                className: "app-friend-card--content",
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-friend-card--title",
                    "data-title": n
                }), (0,
                Yt.jsx)(Xt, {
                    coins: r,
                    big: !1
                })]
            })]
        })
    }
      , an = () => (0,
    Yt.jsx)("div", {
        className: "app-fullscreen-overlay"
    })
      , on = () => (0,
    Yt.jsx)("div", {
        className: "app-loading-animation"
    })
      , ln = e => {
        let {children: t, title: n, buttonText: r, fullHeight: o, onButtonClick: i, onClose: l, closed: s, type: u} = e;
        const c = (0,
        a.useRef)()
          , d = () => {
            c.current.classList.remove("app-animation"),
            window.setTimeout(( () => l()), 256)
        }
        ;
        return (0,
        Yt.jsxs)(Yt.Fragment, {
            children: [(0,
            Yt.jsx)(an, {}), (0,
            Yt.jsxs)("article", {
                ref: c,
                className: "app-popup" + (o ? " app-popup_fh" : "") + (s ? "" : " app-animation") + " " + (u ? "app-popup--".concat(u) : ""),
                children: [(0,
                Yt.jsxs)("header", {
                    className: "app-popup--header app-popup--header" + "-".concat(u),
                    children: [(0,
                    Yt.jsx)("span", {
                        children: n
                    }), (0,
                    Yt.jsx)("svg", {
                        onClick: () => d(),
                        width: "20",
                        height: "20",
                        viewBox: "0 0 20 20",
                        fill: "none",
                        xmlns: "http://www.w3.org/2000/svg",
                        children: (0,
                        Yt.jsx)("path", {
                            d: "M4.15758 3.32458C3.9918 3.32462 3.82981 3.37411 3.6923 3.4667C3.55479 3.5593 3.44802 3.6908 3.38564 3.84439C3.32326 3.99798 3.3081 4.16669 3.3421 4.32894C3.37611 4.4912 3.45773 4.63962 3.57653 4.75525L8.82067 9.99939L3.57653 15.2435C3.49655 15.3203 3.4327 15.4123 3.38871 15.5141C3.34472 15.6158 3.32148 15.7254 3.32036 15.8362C3.31923 15.9471 3.34023 16.0571 3.38214 16.1597C3.42405 16.2624 3.48602 16.3556 3.56441 16.434C3.64281 16.5124 3.73607 16.5744 3.83872 16.6163C3.94136 16.6582 4.05134 16.6792 4.16221 16.6781C4.27308 16.677 4.3826 16.6537 4.48438 16.6097C4.58615 16.5657 4.67812 16.5019 4.75491 16.4219L9.99905 11.1778L15.2432 16.4219C15.32 16.5019 15.412 16.5657 15.5137 16.6097C15.6155 16.6537 15.725 16.677 15.8359 16.6781C15.9468 16.6792 16.0567 16.6582 16.1594 16.6163C16.262 16.5744 16.3553 16.5124 16.4337 16.434C16.5121 16.3556 16.5741 16.2624 16.616 16.1597C16.6579 16.0571 16.6789 15.9471 16.6778 15.8362C16.6766 15.7254 16.6534 15.6158 16.6094 15.5141C16.5654 15.4123 16.5016 15.3203 16.4216 15.2435L11.1774 9.99939L16.4216 4.75525C16.542 4.63819 16.6242 4.48749 16.6575 4.32289C16.6908 4.15829 16.6736 3.98747 16.6082 3.83282C16.5427 3.67816 16.4321 3.54689 16.2908 3.4562C16.1494 3.36551 15.984 3.31963 15.8161 3.32458C15.5996 3.33103 15.3941 3.42151 15.2432 3.57686L9.99905 8.821L4.75491 3.57686C4.67725 3.49703 4.58438 3.43358 4.48179 3.39025C4.37919 3.34692 4.26895 3.32459 4.15758 3.32458Z",
                            fill: "#A89EAE"
                        })
                    })]
                }), (0,
                Yt.jsx)("div", {
                    className: "app-popup--body",
                    children: t
                }), !(null === r || void 0 === r || !r.length) && (0,
                Yt.jsx)("footer", {
                    className: "app-popup--footer",
                    children: (0,
                    Yt.jsx)(Wt, {
                        onClick: () => "function" === typeof i ? i() : d(),
                        children: r
                    })
                })]
            })]
        })
    }
      , sn = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALYAAAC2CAMAAABDLoc2AAAA+VBMVEUtY8kQRapJgOYJPqNGfeMRR6wNQqdMg+owZsxLguh2nud0nOVzmuQyaM4rYcdxmeIvZcoHPaElW8BOhet4n+k0atAeVLlIf+UMQaYgVrsTSa4ORKhwl+AWTLEKQKQnXcIqYMUiWL02bNIYTrIZT7QVSq8oXsQdUrc4btRgh89cgstYf8cbULZult9ehc5tlN1FfOJjitNagck6cNYjWb9WfcVBeN5DeuB5oOphiNFdhM1mjdZAdtw+ddo8c9k7ctdki9Vrkttsk9xUe8RAcs9VgtdHcsJPfNJIds1ij+Jhi9o2aMY9ab00Y7ssXLdbh9hTfMtOgeBZieGAemBYAAAQq0lEQVR42tSQX2tUQQzFR0QfRX2QqqgrbV20UmixD9YXQbku7B/6/T+NSX4ze7zEdnavi+LZO8nJSSZz2vLkv8Rfsn1/+k3/Eoq6aqerWpA6akm8dRuT90kGF5gmUGwPghZprjDDD0kKbyCi8BRSgFHR7Rw6RlqlwwUVSnUVcSwSAiX2jtYIeaNYGvxrwPb/iNdFlP8YPA9KTbpoEpT7YDQ/ScH3uqqFDkXlkDbvo7TV4iDXO8lADDARlbZR6QHmaOkFRARoEPwUevGhtW57mKgJVTBWqq1JCIBlHKkHZC1Dajk6guf+7a9kDZ0onVXwDPSjI3VhLsQP5Uj7lUsdZQzEoDTutaSFEFhrWyY65IBZTBjDitYTW4dmBV1tDWa2GWcAEQpE6LC+ClRCkwkqspxGJO6Ch0dFdJfxQ+Ohf1kNUY08UupNjegaCdEDv4cUBq8QaSM54ZftaTXrA9SsrGrlWudA4RRKddqQTAEUlRDV0pVVpaE/g9n+z/AyYhHtjIr2Z5Xs8wDprhfi3suXkIgGtYrVIcZxKgHFL2i1OLnd425lzSySGF5wwGK9tE26vbWNzF3GCn0DK3VZ0xyCMFoEAXRSfSjc81CSJAYZaQSA5gJf7qUXGYey3D4o9WjfqFFPvVdkjWFK+8HYS6BP5UQe9FwMW4wRqUjajEG1qRG4S2i3OFCPpfoJaDuEPSLkhNzpI1/ID94Kt/1foozLB3miP4CcW/1dYqSkdG0/aJ9qratNCBKqB7IryQYtnyGgMD7aBYB0mOVIHPaV6EWFgB5rUSjaS/LK4eciOSTVzgVutI+ydTLUgmIIqaihru5NwOl8s1oNwzfDMKzWm3lnPr/Xf9tsHxTzdfgdY9gcH+6F/Wy/2GHmVJ57zrUxF3lQ1LmfYgmGHhUlhQWiJN0mQI7X3+7E6pg9hvakFt7qXs8FjMYp2yo6W5dBgJipZCIHfirTV35gkTkYF+Ih7eiCC42WHa+k62Ns3OKV2/QURoku0zMMmxcHQjnEkuPhqgGHGc04/3DhVFQaMetqFJhzTcIZbD8lzaH6v7oH2d+wod61B/wDphN5VmDsV+Ml+kZGK+AhCloFaTfWV3thfSpod4oQeEYRnYjV1Z5YpRWvSB0wSCrGco9DK/f9B8H1/r61QYG9ML1OJEIDhQUWYw6CZlkBUTuitriD67NR4WfFPvsgihJJonoX23fitNNZu5EzC/yMUcNciYJAB9+TIdvTsT5rwBYnKG5xmrGe/GTf9nFPmp9NxrO67fj4OBLb48ARonYEl14Yrah9RaT4Rcmpu0++Tbf97cQXNkdClPx4UU0k6jJSxbArqBJWZ3+A1fi1PYDtyZh3rV0SPLVSZLPzQyd920x1RISherq0FEZIdlDVoCRvpeEkllo8scx+GDRaZMYYgBcSkw4rEFgnwQMf4+tLN8DngV+IyJ5cYED9xja8BuoDgsyoUCywNC2SKRjcAAfUys1WRm61ZM7AykkoUy9umlki7noYD21OPrLLMowkSEi2U5+STWNJ1P/Zf4xVMshfIB4FFdmkaBfL9OkyzectxdZh9fwSfCCJdqHZszn7sLAFFA8YgwFMlNGo+FjMwtpe/oCDDzCPRvFEahMcwLRFC+uPU1Em3hv8eYDhBphq6bkY5nc/MrcfoPQDKTBFn4UbS5cRbODswwFwaatiGz8oHwG16k4NUZTo8SEjhD2BQth8OAiezwUBl5kLZnsS1oexvZ70+HTbw11mrnfuDbHsGQFAE2hsO8Ur/7hLJhgnPkvXk+3ra1H7WU1G4Sj6iYmBp+Mdz8/0qFdG0OhSRaMwgdY4XQYBK1XeXFdnhmAJWPcjIeGGdQIvJKSBQtoXN9kCFpV7wPYUTLfNq+cRBUSpfXSe2df2845mjv2HcadGENCqbjKMAX5e0Mu2+1ZAee66BY2gUKE+j4COgtNzA4najwcoPUGV4OvYPnoGQgyiCariYyAmaUiEmEizCecHAs/cjtv6ZnsKLg/j+rL70L+3/T5LN51nDm17kZ1QkN77T1qw93woSG77LQtbTlUUb9+GJL1AQL4ddxChVRjsfcy1BOC4tASzqF6cdnOwVY7nZEJ1gapHmanzxTKML5pMIKpJprtsJjMk9rHc2k6QpFqpkPbFmyl2M2ZT3sb2NFx3DH1uMUP69du3n/zbG5/KlklTJVVN0uJOt2SA8llRkzds5POg96FOvKOqzpbtOG0VNsJtQGmgucTbNjagSCSJe3urLD8JPOiJkkCEUHCKpS648JQMnp7LrLFwQzbUwgJ/Az+HbHv/TfdRfGaUZC6O/cIlVkU0t+D56qZZEtsmmKY43lr41niLnTyJaAUHjYaEYhwBeIcWFIkUaA8tcfEnWDaf2s67eHKQEZTNthyRE1AzbnhbuNjT9U3nBekZhTQBS7wS/bu48CKbR7aU/tnTUaZfvTEj7oYvrAN0FUoAtH/2GxJUGaJKpZ8yljPQ1dHg8qILWc3KjMV8LE0+pViyOS4YCsQCl72CWQzQ9ACJX5CFrPQ8ZyzqU7LNUkSoomTKAgGMp7sZ6O/OLybjfKZVefstqoDtiVh23X0lZTya+qZsv4Mm0BDN+O7O/OeJzJFvRKnE7+xk7YjAqKoY/TgW0Uq7wJDGmNA+tbzZ5IX5MlwQ7NTagISKfY0uYglWxABU5W/1Mu6rQyKnnvQfWMFTHwz+eHcnZu+6KKKTFr0x37viS0Rcz9g7i2g/FFYietSgSJwCTwa1blxri2/2ehGOsGTxi/+yYQ6usaWlsQZK/YtOAkbtRCozB/OI2kCrhlw344svBjMOMA3xpFOxmI0sOSMiE8hiPC4UNZUASEpufL/4sjMuvs92wqO726Vz105/4/J8V9fXjx9xPy8VFbOPHNGuNkuFpBEYfW3QBXQHDZTF511Mf11oo6zYx0YFZLiUcAF+Vld2K04EQRRuRPBnoxFUvPFqr3KzrBCIgom6kiE78SJk3/9hrKqvO8ehk4xjsque6a469dNVJ4KaYFThEC6AYtUhZ/ix6le9Si9PB/vPNKlf+LfVq5dnw7lkI/zw383mVqK1U1SJ+FRMmSmZwsI63Z5Ru5JcQq0gacz9j9tmn+Zl7PArMfGQpzD10MFgCChNGJqhGgEyF6Q/vhovl7erZvMt/rX71qxul6+OzNoTyQ3GSxEOEBOqGh70iBygZjBe9Y99xWA9OGn3K7lTeilgXh0sUYF3q7yC0EcDoXNBJTNYUrlTVa6q4h0BDNIYD/g0UbJookhKr5mPo4FKoQzRbySrpbQAmFDkVzm5ulC/Tqoee0KzeN1RNR/G0yo8HQzC1TEshwTV4ygkPZURN6tEjxLtkuG9W2QZ98ty6SQyo0LenSPqwElSN5lgWPbpCREEx9XTwnqhF4KivinIPifexn826/VNYL3eNKvVcnnWFcg+G97erlBb4/NmtXz79OmL+tELO7g+6Ik1J95iufXcKlVLXiL5GNbNsuzNCzWckBxfKQYjkx+HbDPkguAYWJ5rl1256KBr2XyWuu+iNZol74sY0NmujNZUSJ3XcEFZUTnu5QqpdgVi7ndzyqybyxenI534frnJ0gy4QiXXPJbU981yyIYzy0Y06iTJSTF4qF+VPt8emvgWI153eD4pKIRbz1KbRINrHFBKVCH85vrz0oYZwrJEl4SXtDC35960Y8BIdGuIWYaD3evJ2gTYZ8evFF6b5eCD0xGNOW4mWZUGa0n3Kk3gsmtQ6kmvblwgspwInkAzH1r3YPX2T4Hs4VjeXJ8BN5OeNWeW3VyfCU2MuwzbD7UmJUSyFyW+zG6yHiTtquai66UtuYyjre4wjreqY4yneMXNrdENl+LoJrH8nvdi/XPql0jFqEF3LURWwN0s2cVaNgEWQpAlJHKHgNgOVleAzTD0oXpXVSAnKG4uhyMNfdBorbafhFr3+WVvru4Bm8mlMFQ2bxVhMyGarK+u3vux6xaKhwrEMHUpx0fQTny6zZ+YzQ6eE3gjRJcpt+qJwSt8NJWZ09YVvHeDmtgrUWTgELdBShQ9O7vrWU/Zz3YAk4Ny0mQA1ruFkMrJd5NQF1iD2noyBMjWbzmKzft7xObPZPejeX+vaNgyDSuOhShIQQlUFZtOpw+gGt22rJY9dQkw9MRJ9FGIvNp3b9wsbPB4bKY4OE6gPra0H1z4SAGNcKKu2TS2ySrEC2naB94urmNzXoQuPGkM2GVpdYcl3IdQf73o0TFENlgfXFeFf4523+avIoNlN9Jl372hkdh8lfiKIUhRhdtxBCE2HnQxfhi8X0yzgqIDUSAYxdTJcOE7YudqfJ8YjXa0ZWMPkN2Lbb3GTlwsgHOVUaMdvhE9OQfJX+P7vmg1HMaVbOWrVufzq/EIoJiIuGytQHcViyggBu8XX2yrrfXPvCHCiLCeSB6UvKCXdtZaVcvQD0CAYjzm93H3pR/I7sF8NBxSPxjzP5O9wAnt6EHRhggMdiG2WEh28IWdgIfZR3Y2Ei5EO0n8BbynP7ouqsdys1iOFvnMci3hsHvRarekBb3AEpuLGEIFhlIe0Jg/0pHl8r5dHANSU1/PLLajTjanumIAFJL1CcoSKK3seF52z2EVjsue27e4u3hw3NlelvsxYjAanMI8BSf0erRhaBhfPDhGCEAvogSCNBdUELYXfwHbeR9ST73dP/h5HAA90EeJJp5FDo6jDQtrT5Q9m4802iZyjNsnhmcpBbLmc5lLEz5AN4yIIaOZ7/YvDlIwOUiUvUouuF3ItswUFChFFlNXu/5wpOR2tsNcFKGB1C0jmeNon/8VtLMepOPl0fO/gouTZH/cDlj1pmZ12F95E992j5jDsikJd/WeN3mXnIpYdsOA8tTeQMxDSk24Myn2fUQSFIWQ5OUZTRSx0JbRjliHJcEussS0wvBcAMdVUDvF1uSFHoknzkh21QETxm/ODUk8itHH40jHih/e/DV8OEH29tjgT0OVfPqkp3XFDpx4G39sQ2Sr++6XSTYLa3BGRM0BwfDI8/hgfsJLaGmgnquwuw8fKlG4D25S5gZyxIStD5BOKEB05lwMoBjqus9EVRD0A9sPACWZySSqgJzQVgsfCsg+jHSk9pgLxI89wOIeG4EDshgvw0uoDr7COerAJVKUydtRJyMEr2D9OiEJ1wr5aAwHZypRJCFKQqjtjKREnNTRHQbTECktEFOAdEEPq6QsbhCSPfkPkey+Uyg+FO96agMm+be/gDOfOnm/YaAR4dWDtQ6DtqgiJxNHQ7WllKF5sMSDTCnTksI6SNOEyTEWJ1SRcurteVHh0MSKJ9w94VFfvWIKsRA4Pm7KpNuspk4Kakm35DIFJRtpPyToKxZDqHEYhV7XkHBmcYZkF7Z7qgwJWQbAddWvJBaChD5ULUffpJ5Z/yjSo/8Pz0K2wmf9L0Tgg9rgijxmsXOCbA1O62kEiSTP3LKJdzgmYKjRTgu0RGL5CTcCcoQYQFSeszyOjJCfJ+VqqKaf0NP7QEjnGvQEd09gvHxy8oRILbgnEFl12As1ULSU6kR0wjoOgmGKHhgh5QQTF5pfpLBAlNfmZM2oAMMS0l+y5QAY6gjpVR5eYkGDNDyQcNr2fyANfuG/7TWkHzQO7xavm/ymKgWxQ4PyVZ+8Hr3mEdYTWMqa7H3c8tZgVk1U1Eiu9KWSCcDLXB2accrpnRYICjSsQNvwe3C8krpd/wvS6/8SPwERXZqqmnlWfwAAAABJRU5ErkJggg=="
      , un = window.Telegram.WebApp
      , cn = e => {
        let {photo: t, coins: n, subscribed: r} = e;
        return (0,
        Yt.jsxs)("figure", {
            className: "app-profile-card",
            children: [(0,
            Yt.jsx)("img", {
                src: t || sn,
                alt: "",
                className: "app-profile-card--image"
            }), (0,
            Yt.jsx)("figcaption", {
                children: (0,
                Yt.jsx)(Xt, {
                    coins: n,
                    big: !0
                })
            }), !r && (0,
            Yt.jsxs)("div", {
                className: "app-profile-card--warning",
                children: ["\u0425\u043e\u0447\u0435\u0448\u044c, \u0447\u0442\u043e\u0431\u044b \u0442\u0432\u043e\u0438 \u0431\u0430\u043b\u043b\u044b \u0441\u043e\u0445\u0440\u0430\u043d\u0438\u043b\u0438\u0441\u044c \u0432\xa0\u0440\u0435\u0439\u0442\u0438\u043d\u0433\u0435?", (0,
                Yt.jsx)("br", {}), "\u041f\u0440\u043e\u0441\u0442\u043e \u043f\u043e\u0434\u043f\u0438\u0448\u0438\u0441\u044c \u043d\u0430 ", (0,
                Yt.jsx)("a", {
                    onClick: () => un.openTelegramLink("https://t.me/tv3russia"),
                    children: "\u043a\u0430\u043d\u0430\u043b \u0422\u0412-3"
                }), ", \u0438\xa0\u0442\u044b\xa0\u0432\xa0\u0438\u0433\u0440\u0435!\xa0\ud83d\ude09"]
            })]
        })
    }
      , dn = (n.p,
    e => {
        let {number: t, image: n, title: r, coins: a, active: o, error: i, isOwn: l, isEnemy: s} = e;
        return (0,
        Yt.jsxs)("div", {
            className: "app-rating-card" + (o ? " app-active" : "") + (i ? " app-error" : ""),
            children: [!l && (0,
            Yt.jsx)("div", {
                className: "app-rating-card--number" + (s ? " app-rating-card--enemy" : ""),
                children: t
            }), (0,
            Yt.jsx)("img", {
                loading: "lazy",
                src: s ? "data:image/png;base64,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" : n,
                alt: "",
                className: "app-rating-card--image" + (s ? " app-rating-card--image-enemy" : "")
            }), (0,
            Yt.jsxs)("div", {
                className: "app-rating-card--content",
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-rating-card--title",
                    "data-title": r
                }), (0,
                Yt.jsx)(Xt, {
                    coins: a,
                    big: !1
                })]
            }), l && (0,
            Yt.jsx)("div", {
                className: "app-rating-card--number-own",
                children: t
            })]
        })
    }
    )
      , pn = () => (0,
    Yt.jsx)("svg", {
        className: "app-task-card--completed",
        width: "24",
        height: "24",
        viewBox: "0 0 24 24",
        fill: "none",
        xmlns: "http://www.w3.org/2000/svg",
        children: (0,
        Yt.jsx)("path", {
            fillRule: "evenodd",
            clipRule: "evenodd",
            d: "M12 21C16.9706 21 21 16.9706 21 12C21 7.02944 16.9706 3 12 3C7.02944 3 3 7.02944 3 12C3 16.9706 7.02944 21 12 21ZM11.7682 15.6402L16.7682 9.64018L15.2318 8.35982L10.9328 13.5186L8.70711 11.2929L7.29289 12.7071L10.2929 15.7071L11.0672 16.4814L11.7682 15.6402Z",
            fill: "#87FF85"
        })
    })
      , fn = () => (0,
    Yt.jsx)("svg", {
        className: "app-task-card--arrow",
        width: "24",
        height: "24",
        viewBox: "0 0 24 24",
        fill: "none",
        xmlns: "http://www.w3.org/2000/svg",
        children: (0,
        Yt.jsx)("path", {
            d: "M9 6L15 12L9 18",
            stroke: "white",
            strokeWidth: "1.6"
        })
    })
      , mn = e => {
        let {image: t, title: n, coins: r, completed: a, onClick: o} = e;
        return (0,
        Yt.jsxs)("div", {
            className: "app-task-card",
            onClick: o,
            children: [(0,
            Yt.jsx)("img", {
                src: t,
                alt: "",
                className: "app-task-card--image"
            }), (0,
            Yt.jsxs)("div", {
                className: "app-task-card--content",
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-task-card--title",
                    children: n
                }), (0,
                Yt.jsx)(Xt, {
                    coins: r,
                    big: !1
                })]
            }), !a && (0,
            Yt.jsx)(fn, {}), a && (0,
            Yt.jsx)(pn, {})]
        })
    }
      , hn = n.p + "static/media/game-tikki-2.1b699e407696f92e2575.png"
      , gn = () => (0,
    Yt.jsxs)("div", {
        className: "app-turn-the-phone",
        children: [(0,
        Yt.jsx)("div", {
            className: "app-turn-the-phone--tikki",
            children: (0,
            Yt.jsx)("img", {
                src: hn,
                alt: ""
            })
        }), (0,
        Yt.jsxs)("div", {
            className: "app-turn-the-phone--container",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-turn-the-phone--text",
                children: ["\u041f\u0435\u0440\u0435\u0432\u0435\u0440\u043d\u0438 \u0442\u0435\u043b\u0435\u0444\u043e\u043d ", (0,
                Yt.jsx)("br", {}), "\u0432\u0435\u0440\u0442\u0438\u043a\u0430\u043b\u044c\u043d\u043e"]
            }), (0,
            Yt.jsx)("img", {
                src: "data:image/png;base64,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",
                alt: "",
                className: "app-turn-the-phone--rotate"
            })]
        })]
    });
    function vn(e) {
        if (!e)
            return {
                total: 0,
                hours: 0,
                minutes: 0,
                seconds: 0
            };
        const t = new Date
          , n = new Date(new Date(e).getTime() + 864e5) - t;
        return {
            total: n,
            hours: Math.floor(n / 36e5 % 24),
            minutes: Math.floor(n / 1e3 / 60 % 60),
            seconds: Math.floor(n / 1e3 % 60)
        }
    }
    const yn = e => {
        let {startDate: t} = e;
        const [n,r] = (0,
        a.useState)(vn(t));
        return (0,
        a.useEffect)(( () => {
            if (t) {
                const e = setInterval(( () => {
                    const n = vn(t);
                    r(n),
                    n.total <= 0 && clearInterval(e)
                }
                ), 1e3);
                return () => clearInterval(e)
            }
        }
        ), [t]),
        t ? n.total <= 0 ? (0,
        Yt.jsx)("div", {
            children: "00:00:00"
        }) : (0,
        Yt.jsxs)("div", {
            children: [n.hours.toString().padStart(2, "0"), ":", n.minutes.toString().padStart(2, "0"), ":", n.seconds.toString().padStart(2, "0")]
        }) : ""
    }
      , bn = n.p + "static/media/task-invite.5249ff9bb1222c692f91.jpg"
      , xn = e => {
        let {user: t, onCheck: n, onClose: r} = e;
        return (0,
        Yt.jsx)(ln, {
            buttonText: "\u041f\u0440\u043e\u0432\u0435\u0440\u0438\u0442\u044c",
            onButtonClick: () => n(),
            onClose: r,
            children: (0,
            Yt.jsx)("div", {
                className: "app-popup-task-emoji",
                children: (0,
                Yt.jsxs)("div", {
                    className: "app-popup--description",
                    children: ["\u0414\u043e\u0431\u0430\u0432\u044c \u0432 \u0438\u043c\u044f \u0441\u0432\u043e\u0435\u0433\u043e \u043f\u0440\u043e\u0444\u0438\u043b\u044f", (0,
                    Yt.jsx)("br", {}), "\u0432 Telegram \u0444\u0440\u0430\u0437\u0443 \xab\ud83d\udc1e \u043d\u0430 \u0422\u0412-3\xbb", (0,
                    Yt.jsx)("br", {}), "\u0438 \u043f\u043e\u043b\u0443\u0447\u0438", " ", (0,
                    Yt.jsx)("strong", {
                        children: (0,
                        Yt.jsxs)("span", {
                            children: ["+", Lt, "\xa0\u0431\u0430\u043b\u043b\u043e\u0432"]
                        })
                    })]
                })
            })
        })
    }
      , wn = () => {
        const e = e => (e = new RegExp("[?&]" + encodeURIComponent(e) + "=([^&]*)").exec(window.location.search)) ? decodeURIComponent(e[1]) : ""
          , t = () => document.documentElement.clientWidth || document.body.clientWidth || window.innerWidth
          , n = () => window.innerHeight || document.documentElement.clientHeight || document.body.clientHeight;
        return {
            arrayRange: (e, t, n) => Array.from({
                length: (t - e) / n + 1
            }, ( (t, r) => e + r * n)),
            getHeight: n,
            getRandom: (e, t) => Math.floor(Math.random() * (t - e) + e),
            getUrlSearchParameter: e,
            getWidth: t,
            randomFloat: (e, t) => Math.random() * (t - e + 1) + e,
            randomInteger: (e, t) => Math.floor(Math.random() * (t - e + 1)) + e,
            randomNum: (e, t) => Math.max(Math.random() * t, e).toFixed(1),
            setWindowSize: r => {
                const a = document.documentElement
                  , o = t()
                  , i = n()
                  , l = r.viewportStableHeight;
                a.style.setProperty("--window-width", o + "px"),
                a.style.setProperty("--window-height", i + "px"),
                a.style.setProperty("--window-width-ratio", String(o / 393)),
                a.style.setProperty("--window-height-ratio", String(i / 820));
                if ("ss" === e("show")) {
                    let e = document.querySelector(".app-debug-screen-size");
                    e || (e = document.createElement("div"),
                    e.classList.add("app-debug-screen-size"),
                    document.body.prepend(e)),
                    e.innerHTML = o + " x " + i + " [" + l + (r.isExpanded ? ", expanded" : "") + ", platform: " + (r.platform || "unknown") + "]"
                }
            }
            ,
            showAlert: e => {
                const t = window.Telegram.WebApp;
                t && t.isVersionAtLeast("6.2") ? t.showAlert(e) : alert(e)
            }
            ,
            isEmptyObject: e => null === e || "object" !== typeof e || !Object.keys(e).length,
            isTouchDevice: () => "ontouchstart"in document.documentElement,
            hashString: e => {
                let t, n, r = 0;
                if (0 === e.length)
                    return r;
                for (t = 0; t < e.length; t++)
                    n = e.charCodeAt(t),
                    r = (r << 5) - r + n,
                    r |= 0;
                return r
            }
            ,
            ymReachGoal: e => {
                "undefined" !== typeof ym && console.log("[YM.ReachGoal] > " + e)
            }
            ,
            ymHit: e => {
                "undefined" !== typeof ym && console.log("[YM.Hit] > " + e)
            }
        }
    }
      , An = (0,
    a.createContext)({
        user: null,
        setUser: e => {}
    })
      , kn = An
      , Sn = () => (0,
    a.useContext)(An)
      , En = n.p + "static/media/popup-task-invite-luka.3c48e03ccda27c188794.png"
      , jn = n.p + "static/media/popup-task-invite-lila.5657cdc3fb86cdf452b8.png"
      , Nn = "https://t.me/tv3_day_ladybug_bot?start={inviteToken}"
      , Cn = e => {
        let {onClose: t} = e;
        const {user: n} = Sn()
          , [r,o] = (0,
        a.useState)(!1);
        return (0,
        Yt.jsxs)(ln, {
            title: "\u041f\u0440\u0438\u0433\u043b\u0430\u0441\u0438 \u0434\u0440\u0443\u0433\u0430",
            buttonText: "\u041f\u0440\u0438\u0433\u043b\u0430\u0441\u0438\u0442\u044c \u0434\u0440\u0443\u0433\u0430",
            onButtonClick: () => {
                window.Telegram.WebApp.openTelegramLink("https://t.me/share/url?url=" + Nn.replace("{inviteToken}", n.telegram_id) + "&text=" + encodeURIComponent("\u0421\u043a\u043e\u0440\u0435\u0435 \u0437\u0430\u0445\u043e\u0434\u0438 \u0432 \u0438\u0433\u0440\u0443 \u043f\u043e \u044d\u0442\u043e\u0439 \u0441\u0441\u044b\u043b\u043a\u0435 \u0438 \u043f\u043e\u043c\u043e\u0433\u0438 \u043c\u043d\u0435 \u0437\u0430\u0440\u0430\u0431\u043e\u0442\u0430\u0442\u044c \u0431\u0430\u043b\u043b\u044b! \ud83d\ude09\ud83d\udc1e"))
            }
            ,
            onClose: t,
            closed: r,
            children: [(0,
            Yt.jsx)("img", {
                src: jn,
                alt: "",
                className: "app-popup-task-invite--lila"
            }), (0,
            Yt.jsx)("img", {
                src: En,
                alt: "",
                className: "app-popup-task-invite--luka"
            }), (0,
            Yt.jsxs)("div", {
                className: "app-popup-task-invite--input",
                children: [(0,
                Yt.jsx)("span", {
                    children: Nn.replace("{inviteToken}", n.telegram_id)
                }), (0,
                Yt.jsx)("svg", {
                    width: "16",
                    height: "16",
                    viewBox: "0 0 16 16",
                    fill: "none",
                    xmlns: "http://www.w3.org/2000/svg",
                    onClick: () => (navigator.clipboard.writeText(Nn.replace("{inviteToken}", n.telegram_id)),
                    wn().showAlert("\u0421\u0441\u044b\u043b\u043a\u0430 \u0441\u043a\u043e\u043f\u0438\u0440\u043e\u0432\u0430\u043d\u0430 \u0438 \u0435\u0451 \u043c\u043e\u0436\u043d\u043e \u043e\u0442\u043f\u0440\u0430\u0432\u0438\u0442\u044c \u0434\u0440\u0443\u0433\u0443!"),
                    o(!0),
                    void window.setTimeout(( () => t()), 200)),
                    children: (0,
                    Yt.jsx)("path", {
                        d: "M2.66665 1.33337C1.92998 1.33337 1.33331 1.93004 1.33331 2.66671V11.3334C1.33331 11.7014 1.63198 12 1.99998 12C2.36798 12 2.66665 11.7014 2.66665 11.3334V2.66671H11.3333C11.7013 2.66671 12 2.36804 12 2.00004C12 1.63204 11.7013 1.33337 11.3333 1.33337H2.66665ZM5.33331 4.00004C4.59665 4.00004 3.99998 4.59671 3.99998 5.33337V13.3334C3.99998 14.07 4.59665 14.6667 5.33331 14.6667H13.3333C14.07 14.6667 14.6666 14.07 14.6666 13.3334V5.33337C14.6666 4.59671 14.07 4.00004 13.3333 4.00004H5.33331ZM5.33331 5.33337H13.3333V13.3334H5.33331V5.33337Z",
                        fill: "white"
                    })
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-popup--description",
                children: ["\u0421\u043a\u043e\u043f\u0438\u0440\u0443\u0439 \u0438 \u043e\u0442\u043f\u0440\u0430\u0432\u044c \u044d\u0442\u0443 \u0441\u0441\u044b\u043b\u043a\u0443 \u0434\u0440\u0443\u0433\u0443, \u043a\u043e\u0442\u043e\u0440\u044b\u0439 \u0435\u0449\u0435 \u043d\u0435\xa0\u043f\u0440\u0438\u0441\u043e\u0435\u0434\u0438\u043d\u0438\u043b\u0441\u044f", (0,
                Yt.jsx)("br", {}), " \u043a\xa0\u0438\u0433\u0440\u0435. \u0422\u044b \u043f\u043e\u043b\u0443\u0447\u0438\u0448\u044c +", (0,
                Yt.jsx)("strong", {
                    children: (0,
                    Yt.jsxs)("span", {
                        children: [Ut, "\xa0\u0431\u0430\u043b\u043b\u043e\u0432"]
                    })
                }), " \u043f\u043e\u0441\u043b\u0435", (0,
                Yt.jsx)("br", {}), " \u0442\u043e\u0433\u043e, \u043a\u0430\u043a \u043e\u043d \u0437\u0430\u0439\u0434\u0435\u0442 \u043f\u043e\xa0\u043d\u0435\u0439 \u0438 \u0441\u044b\u0433\u0440\u0430\u0435\u0442 \u0445\u043e\u0442\u044f \u0431\u044b \u043e\u0434\u043d\u0443 \u0438\u0433\u0440\u0443!"]
            })]
        })
    }
      , Rn = n.p + "static/media/popup-task-qr-banner-tv.59a500424639ffca41aa.png"
      , On = n.p + "static/media/slepoi-banner.f9145c4c69b62e18b0c5.png"
      , Tn = n.p + "static/media/lesnik-banner.840f46b4bf2a15618c16.png"
      , Ln = n.p + "static/media/gadalok-banner.261d78bae682992e3df8.png"
      , Un = window.Telegram.WebApp
      , Pn = e => {
        let {onQrRead: t, onClose: n, isKwamiTask: r, type: o} = e;
        const [i,l] = (0,
        a.useState)("\u041f\u043e\u043d\u044f\u0442\u043d\u043e")
          , [s,u] = (0,
        a.useState)(!1)
          , c = () => {
            Un.isVersionAtLeast("6.4") ? Un.showScanQrPopup({
                text: "C\u043a\u0430\u043d\u0438\u0440\u0443\u0439 \u043a\u043e\u0434 \u0432 \u044d\u0444\u0438\u0440\u0435 \u0422\u0412-3"
            }, (e => {
                const n = ( (e, t) => {
                    let n;
                    try {
                        n = new URL(e)
                    } catch (sl) {
                        n = null
                    }
                    if (t && null !== n && "t.me" === n.host && n.searchParams.get("startapp")) {
                        const e = n.searchParams.get("startapp");
                        if ("qr_" === e.substring(0, 3))
                            return e
                    }
                    if (!t && null !== n && "t.me" === n.host && n.searchParams.get("startapp")) {
                        const e = n.searchParams.get("startapp");
                        if ("qr_" === e.substring(0, 3) && e.length >= 6)
                            return e.slice(3)
                    }
                    if (null !== n && "qrcods.ru" === n.host)
                        switch (n.pathname) {
                        case "/tv3-ladybug_bot":
                            return "qrkNl8";
                        case "/tv3-ladybug_bot_qrVxW8":
                            return "qrVxW8";
                        case "/tv3-ladybug_bot_qrVMgB":
                            return "qrVMgB";
                        case "/tv3-ladybug_bot_qrV7lk":
                            return "qrV7lk";
                        case "/tv3-ladybug_bot_qrV6PB":
                            return "qrV6PB";
                        case "/tv3-ladybug_bot_qrk1RB":
                            return "qrk1RB";
                        case "/tv3-ladybug_bot_qrBREk":
                            return "qrBREk";
                        case "/tv3-ladybug_bot_qrBaKV":
                            return "qrBaKV";
                        case "/tv3-ladybug_bot_qrB3oB":
                            return "qrB3oB";
                        case "/tv3-ladybug_bot_qr8AxB":
                            return "qr8AxB"
                        }
                    return null
                }
                )(e, r);
                return null !== n ? (console.log("[Ladybug.QR] > startParam: " + n),
                u(!1),
                t(n)) : u(!0),
                !0
            }
            )) : n()
        }
        ;
        (0,
        a.useEffect)(( () => {
            Un.isVersionAtLeast("6.4") && l("\u0421\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u0442\u044c QR \u043a\u043e\u0434")
        }
        ), []);
        const d = {
            qr: Rn,
            qr_slepoi: On,
            qr_lesnik: Tn,
            qr_gadalok: Ln
        };
        return (0,
        Yt.jsxs)(ln, {
            title: "\u0421\u043a\u0430\u043d\u0438\u0440\u0443\u0439 QR-\u043a\u043e\u0434 \u0432 \u044d\u0444\u0438\u0440\u0435",
            buttonText: !r && i,
            onButtonClick: () => c(),
            onClose: n,
            children: [(0,
            Yt.jsx)("img", {
                src: d[o],
                alt: "",
                className: "app-popup-task-qr--tv"
            }), "qr" === o && (0,
            Yt.jsxs)("div", {
                className: "app-popup--description",
                children: ["\u0412 \u0442\u0435\u0447\u0435\u043d\u0438\u0435 \u0434\u043d\u044f \u0432\xa0\u044d\u0444\u0438\u0440\u0435\xa0\u0422\u0412-3 \u0431\u0443\u0434\u0443\u0442", (0,
                Yt.jsx)("br", {}), " \u043f\u043e\u044f\u0432\u043b\u044f\u0442\u044c\u0441\u044f \u043f\u043b\u0430\u0448\u043a\u0438 \u0441\xa0QR-\u043a\u043e\u0434\u0430\u043c\u0438.", (0,
                Yt.jsx)("br", {}), " \u0421\u043a\u0430\u043d\u0438\u0440\u0443\u0439 \u0438\u0445\xa0\u043a\u0430\u043c\u0435\u0440\u043e\u0439 \u0441\u043c\u0430\u0440\u0442\u0444\u043e\u043d\u0430", (0,
                Yt.jsx)("br", {}), " \u0438\xa0\u043f\u043e\u043b\u0443\u0447\u0430\u0439 +", (0,
                Yt.jsx)("strong", {
                    children: (0,
                    Yt.jsx)("span", {
                        children: "10000\xa0\u0431\u0430\u043b\u043b\u043e\u0432"
                    })
                }), " ", (0,
                Yt.jsx)("br", {}), "\u0437\u0430\xa0\u043a\u0430\u0436\u0434\u044b\u0439\xa0\u043a\u043e\u0434"]
            }), "qr" !== o && (0,
            Yt.jsxs)("div", {
                className: "app-popup--description",
                children: ["\u0418\u0449\u0438 \u044d\u0442\u043e\u0433\u043e \u043a\u0432\u0430\u043c\u0438-\u0445\u0440\u0430\u043d\u0438\u0442\u0435\u043b\u044f \u043d\u0430 \u043f\u043b\u0430\u0448\u043a\u0435", (0,
                Yt.jsx)("br", {}), "\u0441 QR-\u043a\u043e\u0434\u043e\u043c \u0432 \u044d\u0444\u0438\u0440\u0435 \u0422\u0412-3.", (0,
                Yt.jsx)("br", {}), "\u0421\u043a\u0430\u043d\u0438\u0440\u0443\u0439 \u043a\u043e\u0434 \u2014 \u043e\u0442\u043a\u0440\u043e\u0435\u0442\u0441\u044f AR-\u0441\u0446\u0435\u043d\u0430", (0,
                Yt.jsx)("br", {}), "\u0441 \u0437\u0430\u0434\u0430\u043d\u0438\u0435\u043c. \u0412\u044b\u043f\u043e\u043b\u043d\u0438 \u0435\u0433\u043e, \u0432\u0435\u0440\u043d\u0438\u0441\u044c \u0432 \u0438\u0433\u0440\u0443", (0,
                Yt.jsx)("br", {}), "\u0438 \u043f\u043e\u043b\u0443\u0447\u0438\xa0", (0,
                Yt.jsx)("strong", {
                    children: (0,
                    Yt.jsx)("span", {
                        children: "5000\xa0\u0431\u0430\u043b\u043b\u043e\u0432"
                    })
                }), " "]
            }), s && (0,
            Yt.jsxs)("div", {
                className: "app-popup-task-qr--error",
                children: ["\u041e\u0439, \u044d\u0442\u043e \u043d\u0435\u0432\u0435\u0440\u043d\u044b\u0439 QR-\u043a\u043e\u0434 ;(", (0,
                Yt.jsx)("br", {}), " \u041f\u043e\u043f\u0440\u043e\u0431\u0443\u0439 \u0435\u0449\u0435 \u0440\u0430\u0437!"]
            })]
        })
    }
      , In = n.p + "static/media/popup-task-result-success.d71072dc5d582b4a7a9d.png"
      , Fn = n.p + "static/media/popup-task-result-error.1477bc025e8aec9cee3d.png"
      , zn = n.p + "static/media/whisper.e9d8a0a52687d5c11cbb.png"
      , Mn = e => {
        let {success: t, title: n, text: r, onClose: a, buttonText: o, done: i} = e;
        return (0,
        Yt.jsxs)(ln, {
            title: n,
            buttonText: o || "\u0417\u0430\u043a\u0440\u044b\u0442\u044c",
            onClose: a,
            children: [t && (0,
            Yt.jsx)("img", {
                src: In,
                alt: "",
                className: "app-popup-task-result--image app-popup-task-result--image_success"
            }), !t && (0,
            Yt.jsx)("img", {
                src: Fn,
                alt: "",
                className: "app-popup-task-result--image app-popup-task-result--image_error"
            }), i && (0,
            Yt.jsx)("img", {
                src: zn,
                alt: "",
                className: "app-popup-task-result--image app-popup-task-result--image_error"
            }), (0,
            Yt.jsx)("div", {
                className: "app-popup--description",
                dangerouslySetInnerHTML: {
                    __html: r
                }
            })]
        })
    }
      , Bn = e => {
        let {onCheck: t, onClose: n} = e;
        const [r,o] = (0,
        a.useState)(!1)
          , [i,l] = (0,
        a.useState)(!1)
          , [s,u] = (0,
        a.useState)(!1)
          , c = (0,
        a.useRef)(null);
        return (0,
        a.useEffect)(( () => {
            window.setTimeout(( () => u(!0)), 256)
        }
        ), []),
        (0,
        Yt.jsxs)(ln, {
            title: "\u0412\u0432\u0435\u0434\u0438 \u043a\u043e\u0434 \u0438\u0437 \u0432\u0438\u0434\u0435\u043e",
            buttonText: "\u0412\u0432\u0435\u0441\u0442\u0438 \u043a\u043e\u0434",
            onButtonClick: () => {
                l(!1),
                ( () => {
                    const e = c.current.value.trim().toUpperCase();
                    0 < e.length && t(e)
                }
                )()
            }
            ,
            onClose: n,
            closed: r,
            fullHeight: i,
            children: [(0,
            Yt.jsx)("div", {
                className: "app-popup-task-trailer--video",
                children: s && (0,
                Yt.jsx)("video", {
                    src: "https://lovikwami-test-bot.store/video/video_for_game.mp4",
                    playsInline: !0,
                    controls: !0,
                    autoPlay: !0
                })
            }), (0,
            Yt.jsx)("input", {
                ref: c,
                className: "app-popup-task-trailer--input",
                type: "text",
                placeholder: "\u041f\u043e\u0434\u0441\u043a\u0430\u0437\u043a\u0430: \u043a\u043e\u0434 \u0441\u043e\u0441\u0442\u043e\u0438\u0442 \u0438\u0437 9 \u0431\u0443\u043a\u0432",
                maxLength: 32,
                onFocusCapture: () => l(!0)
            }), !i && (0,
            Yt.jsxs)("div", {
                className: "app-popup--description",
                children: ["\u041f\u043e\u0441\u043c\u043e\u0442\u0440\u0438 \u0432\u0438\u0434\u0435\u043e, \u043d\u0430\u0439\u0434\u0438 \u0432\xa0\u043d\u0435\u043c \u0441\u043a\u0440\u044b\u0442\u044b\u0439 \u043a\u043e\u0434", (0,
                Yt.jsx)("br", {}), "\u0438 \u0432\u0432\u0435\u0434\u0438 \u0435\u0433\u043e \u0432\xa0\u0442\u0435\u043a\u0441\u0442\u043e\u0432\u043e\u0435 \u043f\u043e\u043b\u0435 \u0432\u044b\u0448\u0435.\xa0 \u0415\u0441\u043b\u0438 \u043a\u043e\u0434 \u043e\u043a\u0430\u0436\u0435\u0442\u0441\u044f \u0432\u0435\u0440\u043d\u044b\u043c, \u0442\u044b \u043f\u043e\u043b\u0443\u0447\u0438\u0448\u044c +", (0,
                Yt.jsx)("strong", {
                    children: (0,
                    Yt.jsxs)("span", {
                        children: [It, "\xa0\u0431\u0430\u043b\u043b\u043e\u0432"]
                    })
                })]
            })]
        })
    }
    ;
    function qn(e, t) {
        return function() {
            return e.apply(t, arguments)
        }
    }
    const {toString: Dn} = Object.prototype
      , {getPrototypeOf: Hn} = Object
      , Qn = (Yn = Object.create(null),
    e => {
        const t = Dn.call(e);
        return Yn[t] || (Yn[t] = t.slice(8, -1).toLowerCase())
    }
    );
    var Yn;
    const Wn = e => (e = e.toLowerCase(),
    t => Qn(t) === e)
      , Gn = e => t => typeof t === e
      , {isArray: Vn} = Array
      , Zn = Gn("undefined");
    const Kn = Wn("ArrayBuffer");
    const Jn = Gn("string")
      , Xn = Gn("function")
      , _n = Gn("number")
      , $n = e => null !== e && "object" === typeof e
      , er = e => {
        if ("object" !== Qn(e))
            return !1;
        const t = Hn(e);
        return (null === t || t === Object.prototype || null === Object.getPrototypeOf(t)) && !(Symbol.toStringTag in e) && !(Symbol.iterator in e)
    }
      , tr = Wn("Date")
      , nr = Wn("File")
      , rr = Wn("Blob")
      , ar = Wn("FileList")
      , or = Wn("URLSearchParams")
      , [ir,lr,sr,ur] = ["ReadableStream", "Request", "Response", "Headers"].map(Wn);
    function cr(e, t) {
        let n, r, {allOwnKeys: a=!1} = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : {};
        if (null !== e && "undefined" !== typeof e)
            if ("object" !== typeof e && (e = [e]),
            Vn(e))
                for (n = 0,
                r = e.length; n < r; n++)
                    t.call(null, e[n], n, e);
            else {
                const r = a ? Object.getOwnPropertyNames(e) : Object.keys(e)
                  , o = r.length;
                let i;
                for (n = 0; n < o; n++)
                    i = r[n],
                    t.call(null, e[i], i, e)
            }
    }
    function dr(e, t) {
        t = t.toLowerCase();
        const n = Object.keys(e);
        let r, a = n.length;
        for (; a-- > 0; )
            if (r = n[a],
            t === r.toLowerCase())
                return r;
        return null
    }
    const pr = "undefined" !== typeof globalThis ? globalThis : "undefined" !== typeof self ? self : "undefined" !== typeof window ? window : global
      , fr = e => !Zn(e) && e !== pr;
    const mr = (hr = "undefined" !== typeof Uint8Array && Hn(Uint8Array),
    e => hr && e instanceof hr);
    var hr;
    const gr = Wn("HTMLFormElement")
      , vr = (e => {
        let {hasOwnProperty: t} = e;
        return (e, n) => t.call(e, n)
    }
    )(Object.prototype)
      , yr = Wn("RegExp")
      , br = (e, t) => {
        const n = Object.getOwnPropertyDescriptors(e)
          , r = {};
        cr(n, ( (n, a) => {
            let o;
            !1 !== (o = t(n, a, e)) && (r[a] = o || n)
        }
        )),
        Object.defineProperties(e, r)
    }
      , xr = "abcdefghijklmnopqrstuvwxyz"
      , wr = "0123456789"
      , Ar = {
        DIGIT: wr,
        ALPHA: xr,
        ALPHA_DIGIT: xr + xr.toUpperCase() + wr
    };
    const kr = Wn("AsyncFunction")
      , Sr = ( (e, t) => {
        return e ? setImmediate : t ? (n = "axios@".concat(Math.random()),
        r = [],
        pr.addEventListener("message", (e => {
            let {source: t, data: a} = e;
            t === pr && a === n && r.length && r.shift()()
        }
        ), !1),
        e => {
            r.push(e),
            pr.postMessage(n, "*")
        }
        ) : e => setTimeout(e);
        var n, r
    }
    )("function" === typeof setImmediate, Xn(pr.postMessage))
      , Er = "undefined" !== typeof queueMicrotask ? queueMicrotask.bind(pr) : "undefined" !== typeof process && process.nextTick || Sr
      , jr = {
        isArray: Vn,
        isArrayBuffer: Kn,
        isBuffer: function(e) {
            return null !== e && !Zn(e) && null !== e.constructor && !Zn(e.constructor) && Xn(e.constructor.isBuffer) && e.constructor.isBuffer(e)
        },
        isFormData: e => {
            let t;
            return e && ("function" === typeof FormData && e instanceof FormData || Xn(e.append) && ("formdata" === (t = Qn(e)) || "object" === t && Xn(e.toString) && "[object FormData]" === e.toString()))
        }
        ,
        isArrayBufferView: function(e) {
            let t;
            return t = "undefined" !== typeof ArrayBuffer && ArrayBuffer.isView ? ArrayBuffer.isView(e) : e && e.buffer && Kn(e.buffer),
            t
        },
        isString: Jn,
        isNumber: _n,
        isBoolean: e => !0 === e || !1 === e,
        isObject: $n,
        isPlainObject: er,
        isReadableStream: ir,
        isRequest: lr,
        isResponse: sr,
        isHeaders: ur,
        isUndefined: Zn,
        isDate: tr,
        isFile: nr,
        isBlob: rr,
        isRegExp: yr,
        isFunction: Xn,
        isStream: e => $n(e) && Xn(e.pipe),
        isURLSearchParams: or,
        isTypedArray: mr,
        isFileList: ar,
        forEach: cr,
        merge: function e() {
            const {caseless: t} = fr(this) && this || {}
              , n = {}
              , r = (r, a) => {
                const o = t && dr(n, a) || a;
                er(n[o]) && er(r) ? n[o] = e(n[o], r) : er(r) ? n[o] = e({}, r) : Vn(r) ? n[o] = r.slice() : n[o] = r
            }
            ;
            for (let a = 0, o = arguments.length; a < o; a++)
                arguments[a] && cr(arguments[a], r);
            return n
        },
        extend: function(e, t, n) {
            let {allOwnKeys: r} = arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : {};
            return cr(t, ( (t, r) => {
                n && Xn(t) ? e[r] = qn(t, n) : e[r] = t
            }
            ), {
                allOwnKeys: r
            }),
            e
        },
        trim: e => e.trim ? e.trim() : e.replace(/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g, ""),
        stripBOM: e => (65279 === e.charCodeAt(0) && (e = e.slice(1)),
        e),
        inherits: (e, t, n, r) => {
            e.prototype = Object.create(t.prototype, r),
            e.prototype.constructor = e,
            Object.defineProperty(e, "super", {
                value: t.prototype
            }),
            n && Object.assign(e.prototype, n)
        }
        ,
        toFlatObject: (e, t, n, r) => {
            let a, o, i;
            const l = {};
            if (t = t || {},
            null == e)
                return t;
            do {
                for (a = Object.getOwnPropertyNames(e),
                o = a.length; o-- > 0; )
                    i = a[o],
                    r && !r(i, e, t) || l[i] || (t[i] = e[i],
                    l[i] = !0);
                e = !1 !== n && Hn(e)
            } while (e && (!n || n(e, t)) && e !== Object.prototype);
            return t
        }
        ,
        kindOf: Qn,
        kindOfTest: Wn,
        endsWith: (e, t, n) => {
            e = String(e),
            (void 0 === n || n > e.length) && (n = e.length),
            n -= t.length;
            const r = e.indexOf(t, n);
            return -1 !== r && r === n
        }
        ,
        toArray: e => {
            if (!e)
                return null;
            if (Vn(e))
                return e;
            let t = e.length;
            if (!_n(t))
                return null;
            const n = new Array(t);
            for (; t-- > 0; )
                n[t] = e[t];
            return n
        }
        ,
        forEachEntry: (e, t) => {
            const n = (e && e[Symbol.iterator]).call(e);
            let r;
            for (; (r = n.next()) && !r.done; ) {
                const n = r.value;
                t.call(e, n[0], n[1])
            }
        }
        ,
        matchAll: (e, t) => {
            let n;
            const r = [];
            for (; null !== (n = e.exec(t)); )
                r.push(n);
            return r
        }
        ,
        isHTMLForm: gr,
        hasOwnProperty: vr,
        hasOwnProp: vr,
        reduceDescriptors: br,
        freezeMethods: e => {
            br(e, ( (t, n) => {
                if (Xn(e) && -1 !== ["arguments", "caller", "callee"].indexOf(n))
                    return !1;
                const r = e[n];
                Xn(r) && (t.enumerable = !1,
                "writable"in t ? t.writable = !1 : t.set || (t.set = () => {
                    throw Error("Can not rewrite read-only method '" + n + "'")
                }
                ))
            }
            ))
        }
        ,
        toObjectSet: (e, t) => {
            const n = {}
              , r = e => {
                e.forEach((e => {
                    n[e] = !0
                }
                ))
            }
            ;
            return Vn(e) ? r(e) : r(String(e).split(t)),
            n
        }
        ,
        toCamelCase: e => e.toLowerCase().replace(/[-_\s]([a-z\d])(\w*)/g, (function(e, t, n) {
            return t.toUpperCase() + n
        }
        )),
        noop: () => {}
        ,
        toFiniteNumber: (e, t) => null != e && Number.isFinite(e = +e) ? e : t,
        findKey: dr,
        global: pr,
        isContextDefined: fr,
        ALPHABET: Ar,
        generateString: function() {
            let e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : 16
              , t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Ar.ALPHA_DIGIT
              , n = "";
            const {length: r} = t;
            for (; e--; )
                n += t[Math.random() * r | 0];
            return n
        },
        isSpecCompliantForm: function(e) {
            return !!(e && Xn(e.append) && "FormData" === e[Symbol.toStringTag] && e[Symbol.iterator])
        },
        toJSONObject: e => {
            const t = new Array(10)
              , n = (e, r) => {
                if ($n(e)) {
                    if (t.indexOf(e) >= 0)
                        return;
                    if (!("toJSON"in e)) {
                        t[r] = e;
                        const a = Vn(e) ? [] : {};
                        return cr(e, ( (e, t) => {
                            const o = n(e, r + 1);
                            !Zn(o) && (a[t] = o)
                        }
                        )),
                        t[r] = void 0,
                        a
                    }
                }
                return e
            }
            ;
            return n(e, 0)
        }
        ,
        isAsyncFn: kr,
        isThenable: e => e && ($n(e) || Xn(e)) && Xn(e.then) && Xn(e.catch),
        setImmediate: Sr,
        asap: Er
    };
    function Nr(e, t, n, r, a) {
        Error.call(this),
        Error.captureStackTrace ? Error.captureStackTrace(this, this.constructor) : this.stack = (new Error).stack,
        this.message = e,
        this.name = "AxiosError",
        t && (this.code = t),
        n && (this.config = n),
        r && (this.request = r),
        a && (this.response = a,
        this.status = a.status ? a.status : null)
    }
    jr.inherits(Nr, Error, {
        toJSON: function() {
            return {
                message: this.message,
                name: this.name,
                description: this.description,
                number: this.number,
                fileName: this.fileName,
                lineNumber: this.lineNumber,
                columnNumber: this.columnNumber,
                stack: this.stack,
                config: jr.toJSONObject(this.config),
                code: this.code,
                status: this.status
            }
        }
    });
    const Cr = Nr.prototype
      , Rr = {};
    ["ERR_BAD_OPTION_VALUE", "ERR_BAD_OPTION", "ECONNABORTED", "ETIMEDOUT", "ERR_NETWORK", "ERR_FR_TOO_MANY_REDIRECTS", "ERR_DEPRECATED", "ERR_BAD_RESPONSE", "ERR_BAD_REQUEST", "ERR_CANCELED", "ERR_NOT_SUPPORT", "ERR_INVALID_URL"].forEach((e => {
        Rr[e] = {
            value: e
        }
    }
    )),
    Object.defineProperties(Nr, Rr),
    Object.defineProperty(Cr, "isAxiosError", {
        value: !0
    }),
    Nr.from = (e, t, n, r, a, o) => {
        const i = Object.create(Cr);
        return jr.toFlatObject(e, i, (function(e) {
            return e !== Error.prototype
        }
        ), (e => "isAxiosError" !== e)),
        Nr.call(i, e.message, t, n, r, a),
        i.cause = e,
        i.name = e.name,
        o && Object.assign(i, o),
        i
    }
    ;
    const Or = Nr;
    function Tr(e) {
        return jr.isPlainObject(e) || jr.isArray(e)
    }
    function Lr(e) {
        return jr.endsWith(e, "[]") ? e.slice(0, -2) : e
    }
    function Ur(e, t, n) {
        return e ? e.concat(t).map((function(e, t) {
            return e = Lr(e),
            !n && t ? "[" + e + "]" : e
        }
        )).join(n ? "." : "") : t
    }
    const Pr = jr.toFlatObject(jr, {}, null, (function(e) {
        return /^is[A-Z]/.test(e)
    }
    ));
    const Ir = function(e, t, n) {
        if (!jr.isObject(e))
            throw new TypeError("target must be an object");
        t = t || new FormData;
        const r = (n = jr.toFlatObject(n, {
            metaTokens: !0,
            dots: !1,
            indexes: !1
        }, !1, (function(e, t) {
            return !jr.isUndefined(t[e])
        }
        ))).metaTokens
          , a = n.visitor || u
          , o = n.dots
          , i = n.indexes
          , l = (n.Blob || "undefined" !== typeof Blob && Blob) && jr.isSpecCompliantForm(t);
        if (!jr.isFunction(a))
            throw new TypeError("visitor must be a function");
        function s(e) {
            if (null === e)
                return "";
            if (jr.isDate(e))
                return e.toISOString();
            if (!l && jr.isBlob(e))
                throw new Or("Blob is not supported. Use a Buffer instead.");
            return jr.isArrayBuffer(e) || jr.isTypedArray(e) ? l && "function" === typeof Blob ? new Blob([e]) : Buffer.from(e) : e
        }
        function u(e, n, a) {
            let l = e;
            if (e && !a && "object" === typeof e)
                if (jr.endsWith(n, "{}"))
                    n = r ? n : n.slice(0, -2),
                    e = JSON.stringify(e);
                else if (jr.isArray(e) && function(e) {
                    return jr.isArray(e) && !e.some(Tr)
                }(e) || (jr.isFileList(e) || jr.endsWith(n, "[]")) && (l = jr.toArray(e)))
                    return n = Lr(n),
                    l.forEach((function(e, r) {
                        !jr.isUndefined(e) && null !== e && t.append(!0 === i ? Ur([n], r, o) : null === i ? n : n + "[]", s(e))
                    }
                    )),
                    !1;
            return !!Tr(e) || (t.append(Ur(a, n, o), s(e)),
            !1)
        }
        const c = []
          , d = Object.assign(Pr, {
            defaultVisitor: u,
            convertValue: s,
            isVisitable: Tr
        });
        if (!jr.isObject(e))
            throw new TypeError("data must be an object");
        return function e(n, r) {
            if (!jr.isUndefined(n)) {
                if (-1 !== c.indexOf(n))
                    throw Error("Circular reference detected in " + r.join("."));
                c.push(n),
                jr.forEach(n, (function(n, o) {
                    !0 === (!(jr.isUndefined(n) || null === n) && a.call(t, n, jr.isString(o) ? o.trim() : o, r, d)) && e(n, r ? r.concat(o) : [o])
                }
                )),
                c.pop()
            }
        }(e),
        t
    };
    function Fr(e) {
        const t = {
            "!": "%21",
            "'": "%27",
            "(": "%28",
            ")": "%29",
            "~": "%7E",
            "%20": "+",
            "%00": "\0"
        };
        return encodeURIComponent(e).replace(/[!'()~]|%20|%00/g, (function(e) {
            return t[e]
        }
        ))
    }
    function zr(e, t) {
        this._pairs = [],
        e && Ir(e, this, t)
    }
    const Mr = zr.prototype;
    Mr.append = function(e, t) {
        this._pairs.push([e, t])
    }
    ,
    Mr.toString = function(e) {
        const t = e ? function(t) {
            return e.call(this, t, Fr)
        }
        : Fr;
        return this._pairs.map((function(e) {
            return t(e[0]) + "=" + t(e[1])
        }
        ), "").join("&")
    }
    ;
    const Br = zr;
    function qr(e) {
        return encodeURIComponent(e).replace(/%3A/gi, ":").replace(/%24/g, "$").replace(/%2C/gi, ",").replace(/%20/g, "+").replace(/%5B/gi, "[").replace(/%5D/gi, "]")
    }
    function Dr(e, t, n) {
        if (!t)
            return e;
        const r = n && n.encode || qr;
        jr.isFunction(n) && (n = {
            serialize: n
        });
        const a = n && n.serialize;
        let o;
        if (o = a ? a(t, n) : jr.isURLSearchParams(t) ? t.toString() : new Br(t,n).toString(r),
        o) {
            const t = e.indexOf("#");
            -1 !== t && (e = e.slice(0, t)),
            e += (-1 === e.indexOf("?") ? "?" : "&") + o
        }
        return e
    }
    const Hr = class {
        constructor() {
            this.handlers = []
        }
        use(e, t, n) {
            return this.handlers.push({
                fulfilled: e,
                rejected: t,
                synchronous: !!n && n.synchronous,
                runWhen: n ? n.runWhen : null
            }),
            this.handlers.length - 1
        }
        eject(e) {
            this.handlers[e] && (this.handlers[e] = null)
        }
        clear() {
            this.handlers && (this.handlers = [])
        }
        forEach(e) {
            jr.forEach(this.handlers, (function(t) {
                null !== t && e(t)
            }
            ))
        }
    }
      , Qr = {
        silentJSONParsing: !0,
        forcedJSONParsing: !0,
        clarifyTimeoutError: !1
    }
      , Yr = {
        isBrowser: !0,
        classes: {
            URLSearchParams: "undefined" !== typeof URLSearchParams ? URLSearchParams : Br,
            FormData: "undefined" !== typeof FormData ? FormData : null,
            Blob: "undefined" !== typeof Blob ? Blob : null
        },
        protocols: ["http", "https", "file", "blob", "url", "data"]
    }
      , Wr = "undefined" !== typeof window && "undefined" !== typeof document
      , Gr = "object" === typeof navigator && navigator || void 0
      , Vr = Wr && (!Gr || ["ReactNative", "NativeScript", "NS"].indexOf(Gr.product) < 0)
      , Zr = "undefined" !== typeof WorkerGlobalScope && self instanceof WorkerGlobalScope && "function" === typeof self.importScripts
      , Kr = Wr && window.location.href || "http://localhost"
      , Jr = c(c({}, r), Yr);
    const Xr = function(e) {
        function t(e, n, r, a) {
            let o = e[a++];
            if ("__proto__" === o)
                return !0;
            const i = Number.isFinite(+o)
              , l = a >= e.length;
            if (o = !o && jr.isArray(r) ? r.length : o,
            l)
                return jr.hasOwnProp(r, o) ? r[o] = [r[o], n] : r[o] = n,
                !i;
            r[o] && jr.isObject(r[o]) || (r[o] = []);
            return t(e, n, r[o], a) && jr.isArray(r[o]) && (r[o] = function(e) {
                const t = {}
                  , n = Object.keys(e);
                let r;
                const a = n.length;
                let o;
                for (r = 0; r < a; r++)
                    o = n[r],
                    t[o] = e[o];
                return t
            }(r[o])),
            !i
        }
        if (jr.isFormData(e) && jr.isFunction(e.entries)) {
            const n = {};
            return jr.forEachEntry(e, ( (e, r) => {
                t(function(e) {
                    return jr.matchAll(/\w+|\[(\w*)]/g, e).map((e => "[]" === e[0] ? "" : e[1] || e[0]))
                }(e), r, n, 0)
            }
            )),
            n
        }
        return null
    };
    const _r = {
        transitional: Qr,
        adapter: ["xhr", "http", "fetch"],
        transformRequest: [function(e, t) {
            const n = t.getContentType() || ""
              , r = n.indexOf("application/json") > -1
              , a = jr.isObject(e);
            a && jr.isHTMLForm(e) && (e = new FormData(e));
            if (jr.isFormData(e))
                return r ? JSON.stringify(Xr(e)) : e;
            if (jr.isArrayBuffer(e) || jr.isBuffer(e) || jr.isStream(e) || jr.isFile(e) || jr.isBlob(e) || jr.isReadableStream(e))
                return e;
            if (jr.isArrayBufferView(e))
                return e.buffer;
            if (jr.isURLSearchParams(e))
                return t.setContentType("application/x-www-form-urlencoded;charset=utf-8", !1),
                e.toString();
            let o;
            if (a) {
                if (n.indexOf("application/x-www-form-urlencoded") > -1)
                    return function(e, t) {
                        return Ir(e, new Jr.classes.URLSearchParams, Object.assign({
                            visitor: function(e, t, n, r) {
                                return Jr.isNode && jr.isBuffer(e) ? (this.append(t, e.toString("base64")),
                                !1) : r.defaultVisitor.apply(this, arguments)
                            }
                        }, t))
                    }(e, this.formSerializer).toString();
                if ((o = jr.isFileList(e)) || n.indexOf("multipart/form-data") > -1) {
                    const t = this.env && this.env.FormData;
                    return Ir(o ? {
                        "files[]": e
                    } : e, t && new t, this.formSerializer)
                }
            }
            return a || r ? (t.setContentType("application/json", !1),
            function(e, t, n) {
                if (jr.isString(e))
                    try {
                        return (t || JSON.parse)(e),
                        jr.trim(e)
                    } catch (sl) {
                        if ("SyntaxError" !== sl.name)
                            throw sl
                    }
                return (n || JSON.stringify)(e)
            }(e)) : e
        }
        ],
        transformResponse: [function(e) {
            const t = this.transitional || _r.transitional
              , n = t && t.forcedJSONParsing
              , r = "json" === this.responseType;
            if (jr.isResponse(e) || jr.isReadableStream(e))
                return e;
            if (e && jr.isString(e) && (n && !this.responseType || r)) {
                const n = !(t && t.silentJSONParsing) && r;
                try {
                    return JSON.parse(e)
                } catch (sl) {
                    if (n) {
                        if ("SyntaxError" === sl.name)
                            throw Or.from(sl, Or.ERR_BAD_RESPONSE, this, null, this.response);
                        throw sl
                    }
                }
            }
            return e
        }
        ],
        timeout: 0,
        xsrfCookieName: "XSRF-TOKEN",
        xsrfHeaderName: "X-XSRF-TOKEN",
        maxContentLength: -1,
        maxBodyLength: -1,
        env: {
            FormData: Jr.classes.FormData,
            Blob: Jr.classes.Blob
        },
        validateStatus: function(e) {
            return e >= 200 && e < 300
        },
        headers: {
            common: {
                Accept: "application/json, text/plain, */*",
                "Content-Type": void 0
            }
        }
    };
    jr.forEach(["delete", "get", "head", "post", "put", "patch"], (e => {
        _r.headers[e] = {}
    }
    ));
    const $r = _r
      , ea = jr.toObjectSet(["age", "authorization", "content-length", "content-type", "etag", "expires", "from", "host", "if-modified-since", "if-unmodified-since", "last-modified", "location", "max-forwards", "proxy-authorization", "referer", "retry-after", "user-agent"])
      , ta = Symbol("internals");
    function na(e) {
        return e && String(e).trim().toLowerCase()
    }
    function ra(e) {
        return !1 === e || null == e ? e : jr.isArray(e) ? e.map(ra) : String(e)
    }
    function aa(e, t, n, r, a) {
        return jr.isFunction(r) ? r.call(this, t, n) : (a && (t = n),
        jr.isString(t) ? jr.isString(r) ? -1 !== t.indexOf(r) : jr.isRegExp(r) ? r.test(t) : void 0 : void 0)
    }
    class oa {
        constructor(e) {
            e && this.set(e)
        }
        set(e, t, n) {
            const r = this;
            function a(e, t, n) {
                const a = na(t);
                if (!a)
                    throw new Error("header name must be a non-empty string");
                const o = jr.findKey(r, a);
                (!o || void 0 === r[o] || !0 === n || void 0 === n && !1 !== r[o]) && (r[o || t] = ra(e))
            }
            const o = (e, t) => jr.forEach(e, ( (e, n) => a(e, n, t)));
            if (jr.isPlainObject(e) || e instanceof this.constructor)
                o(e, t);
            else if (jr.isString(e) && (e = e.trim()) && !/^[-_a-zA-Z0-9^`|~,!#$%&'*+.]+$/.test(e.trim()))
                o((e => {
                    const t = {};
                    let n, r, a;
                    return e && e.split("\n").forEach((function(e) {
                        a = e.indexOf(":"),
                        n = e.substring(0, a).trim().toLowerCase(),
                        r = e.substring(a + 1).trim(),
                        !n || t[n] && ea[n] || ("set-cookie" === n ? t[n] ? t[n].push(r) : t[n] = [r] : t[n] = t[n] ? t[n] + ", " + r : r)
                    }
                    )),
                    t
                }
                )(e), t);
            else if (jr.isHeaders(e))
                for (const [i,l] of e.entries())
                    a(l, i, n);
            else
                null != e && a(t, e, n);
            return this
        }
        get(e, t) {
            if (e = na(e)) {
                const n = jr.findKey(this, e);
                if (n) {
                    const e = this[n];
                    if (!t)
                        return e;
                    if (!0 === t)
                        return function(e) {
                            const t = Object.create(null)
                              , n = /([^\s,;=]+)\s*(?:=\s*([^,;]+))?/g;
                            let r;
                            for (; r = n.exec(e); )
                                t[r[1]] = r[2];
                            return t
                        }(e);
                    if (jr.isFunction(t))
                        return t.call(this, e, n);
                    if (jr.isRegExp(t))
                        return t.exec(e);
                    throw new TypeError("parser must be boolean|regexp|function")
                }
            }
        }
        has(e, t) {
            if (e = na(e)) {
                const n = jr.findKey(this, e);
                return !(!n || void 0 === this[n] || t && !aa(0, this[n], n, t))
            }
            return !1
        }
        delete(e, t) {
            const n = this;
            let r = !1;
            function a(e) {
                if (e = na(e)) {
                    const a = jr.findKey(n, e);
                    !a || t && !aa(0, n[a], a, t) || (delete n[a],
                    r = !0)
                }
            }
            return jr.isArray(e) ? e.forEach(a) : a(e),
            r
        }
        clear(e) {
            const t = Object.keys(this);
            let n = t.length
              , r = !1;
            for (; n--; ) {
                const a = t[n];
                e && !aa(0, this[a], a, e, !0) || (delete this[a],
                r = !0)
            }
            return r
        }
        normalize(e) {
            const t = this
              , n = {};
            return jr.forEach(this, ( (r, a) => {
                const o = jr.findKey(n, a);
                if (o)
                    return t[o] = ra(r),
                    void delete t[a];
                const i = e ? function(e) {
                    return e.trim().toLowerCase().replace(/([a-z\d])(\w*)/g, ( (e, t, n) => t.toUpperCase() + n))
                }(a) : String(a).trim();
                i !== a && delete t[a],
                t[i] = ra(r),
                n[i] = !0
            }
            )),
            this
        }
        concat() {
            for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++)
                t[n] = arguments[n];
            return this.constructor.concat(this, ...t)
        }
        toJSON(e) {
            const t = Object.create(null);
            return jr.forEach(this, ( (n, r) => {
                null != n && !1 !== n && (t[r] = e && jr.isArray(n) ? n.join(", ") : n)
            }
            )),
            t
        }
        [Symbol.iterator]() {
            return Object.entries(this.toJSON())[Symbol.iterator]()
        }
        toString() {
            return Object.entries(this.toJSON()).map((e => {
                let[t,n] = e;
                return t + ": " + n
            }
            )).join("\n")
        }
        get[Symbol.toStringTag]() {
            return "AxiosHeaders"
        }
        static from(e) {
            return e instanceof this ? e : new this(e)
        }
        static concat(e) {
            const t = new this(e);
            for (var n = arguments.length, r = new Array(n > 1 ? n - 1 : 0), a = 1; a < n; a++)
                r[a - 1] = arguments[a];
            return r.forEach((e => t.set(e))),
            t
        }
        static accessor(e) {
            const t = (this[ta] = this[ta] = {
                accessors: {}
            }).accessors
              , n = this.prototype;
            function r(e) {
                const r = na(e);
                t[r] || (!function(e, t) {
                    const n = jr.toCamelCase(" " + t);
                    ["get", "set", "has"].forEach((r => {
                        Object.defineProperty(e, r + n, {
                            value: function(e, n, a) {
                                return this[r].call(this, t, e, n, a)
                            },
                            configurable: !0
                        })
                    }
                    ))
                }(n, e),
                t[r] = !0)
            }
            return jr.isArray(e) ? e.forEach(r) : r(e),
            this
        }
    }
    oa.accessor(["Content-Type", "Content-Length", "Accept", "Accept-Encoding", "User-Agent", "Authorization"]),
    jr.reduceDescriptors(oa.prototype, ( (e, t) => {
        let {value: n} = e
          , r = t[0].toUpperCase() + t.slice(1);
        return {
            get: () => n,
            set(e) {
                this[r] = e
            }
        }
    }
    )),
    jr.freezeMethods(oa);
    const ia = oa;
    function la(e, t) {
        const n = this || $r
          , r = t || n
          , a = ia.from(r.headers);
        let o = r.data;
        return jr.forEach(e, (function(e) {
            o = e.call(n, o, a.normalize(), t ? t.status : void 0)
        }
        )),
        a.normalize(),
        o
    }
    function sa(e) {
        return !(!e || !e.__CANCEL__)
    }
    function ua(e, t, n) {
        Or.call(this, null == e ? "canceled" : e, Or.ERR_CANCELED, t, n),
        this.name = "CanceledError"
    }
    jr.inherits(ua, Or, {
        __CANCEL__: !0
    });
    const ca = ua;
    function da(e, t, n) {
        const r = n.config.validateStatus;
        n.status && r && !r(n.status) ? t(new Or("Request failed with status code " + n.status,[Or.ERR_BAD_REQUEST, Or.ERR_BAD_RESPONSE][Math.floor(n.status / 100) - 4],n.config,n.request,n)) : e(n)
    }
    const pa = function(e, t) {
        e = e || 10;
        const n = new Array(e)
          , r = new Array(e);
        let a, o = 0, i = 0;
        return t = void 0 !== t ? t : 1e3,
        function(l) {
            const s = Date.now()
              , u = r[i];
            a || (a = s),
            n[o] = l,
            r[o] = s;
            let c = i
              , d = 0;
            for (; c !== o; )
                d += n[c++],
                c %= e;
            if (o = (o + 1) % e,
            o === i && (i = (i + 1) % e),
            s - a < t)
                return;
            const p = u && s - u;
            return p ? Math.round(1e3 * d / p) : void 0
        }
    };
    const fa = function(e, t) {
        let n, r, a = 0, o = 1e3 / t;
        const i = function(t) {
            let o = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Date.now();
            a = o,
            n = null,
            r && (clearTimeout(r),
            r = null),
            e.apply(null, t)
        };
        return [function() {
            const e = Date.now()
              , t = e - a;
            for (var l = arguments.length, s = new Array(l), u = 0; u < l; u++)
                s[u] = arguments[u];
            t >= o ? i(s, e) : (n = s,
            r || (r = setTimeout(( () => {
                r = null,
                i(n)
            }
            ), o - t)))
        }
        , () => n && i(n)]
    }
      , ma = function(e, t) {
        let n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : 3
          , r = 0;
        const a = pa(50, 250);
        return fa((n => {
            const o = n.loaded
              , i = n.lengthComputable ? n.total : void 0
              , l = o - r
              , s = a(l);
            r = o;
            e({
                loaded: o,
                total: i,
                progress: i ? o / i : void 0,
                bytes: l,
                rate: s || void 0,
                estimated: s && i && o <= i ? (i - o) / s : void 0,
                event: n,
                lengthComputable: null != i,
                [t ? "download" : "upload"]: !0
            })
        }
        ), n)
    }
      , ha = (e, t) => {
        const n = null != e;
        return [r => t[0]({
            lengthComputable: n,
            total: e,
            loaded: r
        }), t[1]]
    }
      , ga = e => function() {
        for (var t = arguments.length, n = new Array(t), r = 0; r < t; r++)
            n[r] = arguments[r];
        return jr.asap(( () => e(...n)))
    }
      , va = Jr.hasStandardBrowserEnv ? ( (e, t) => n => (n = new URL(n,Jr.origin),
    e.protocol === n.protocol && e.host === n.host && (t || e.port === n.port)))(new URL(Jr.origin), Jr.navigator && /(msie|trident)/i.test(Jr.navigator.userAgent)) : () => !0
      , ya = Jr.hasStandardBrowserEnv ? {
        write(e, t, n, r, a, o) {
            const i = [e + "=" + encodeURIComponent(t)];
            jr.isNumber(n) && i.push("expires=" + new Date(n).toGMTString()),
            jr.isString(r) && i.push("path=" + r),
            jr.isString(a) && i.push("domain=" + a),
            !0 === o && i.push("secure"),
            document.cookie = i.join("; ")
        },
        read(e) {
            const t = document.cookie.match(new RegExp("(^|;\\s*)(" + e + ")=([^;]*)"));
            return t ? decodeURIComponent(t[3]) : null
        },
        remove(e) {
            this.write(e, "", Date.now() - 864e5)
        }
    } : {
        write() {},
        read: () => null,
        remove() {}
    };
    function ba(e, t) {
        return e && !/^([a-z][a-z\d+\-.]*:)?\/\//i.test(t) ? function(e, t) {
            return t ? e.replace(/\/?\/$/, "") + "/" + t.replace(/^\/+/, "") : e
        }(e, t) : t
    }
    const xa = e => e instanceof ia ? c({}, e) : e;
    function wa(e, t) {
        t = t || {};
        const n = {};
        function r(e, t, n, r) {
            return jr.isPlainObject(e) && jr.isPlainObject(t) ? jr.merge.call({
                caseless: r
            }, e, t) : jr.isPlainObject(t) ? jr.merge({}, t) : jr.isArray(t) ? t.slice() : t
        }
        function a(e, t, n, a) {
            return jr.isUndefined(t) ? jr.isUndefined(e) ? void 0 : r(void 0, e, 0, a) : r(e, t, 0, a)
        }
        function o(e, t) {
            if (!jr.isUndefined(t))
                return r(void 0, t)
        }
        function i(e, t) {
            return jr.isUndefined(t) ? jr.isUndefined(e) ? void 0 : r(void 0, e) : r(void 0, t)
        }
        function l(n, a, o) {
            return o in t ? r(n, a) : o in e ? r(void 0, n) : void 0
        }
        const s = {
            url: o,
            method: o,
            data: o,
            baseURL: i,
            transformRequest: i,
            transformResponse: i,
            paramsSerializer: i,
            timeout: i,
            timeoutMessage: i,
            withCredentials: i,
            withXSRFToken: i,
            adapter: i,
            responseType: i,
            xsrfCookieName: i,
            xsrfHeaderName: i,
            onUploadProgress: i,
            onDownloadProgress: i,
            decompress: i,
            maxContentLength: i,
            maxBodyLength: i,
            beforeRedirect: i,
            transport: i,
            httpAgent: i,
            httpsAgent: i,
            cancelToken: i,
            socketPath: i,
            responseEncoding: i,
            validateStatus: l,
            headers: (e, t, n) => a(xa(e), xa(t), 0, !0)
        };
        return jr.forEach(Object.keys(Object.assign({}, e, t)), (function(r) {
            const o = s[r] || a
              , i = o(e[r], t[r], r);
            jr.isUndefined(i) && o !== l || (n[r] = i)
        }
        )),
        n
    }
    const Aa = e => {
        const t = wa({}, e);
        let n, {data: r, withXSRFToken: a, xsrfHeaderName: o, xsrfCookieName: i, headers: l, auth: s} = t;
        if (t.headers = l = ia.from(l),
        t.url = Dr(ba(t.baseURL, t.url), e.params, e.paramsSerializer),
        s && l.set("Authorization", "Basic " + btoa((s.username || "") + ":" + (s.password ? unescape(encodeURIComponent(s.password)) : ""))),
        jr.isFormData(r))
            if (Jr.hasStandardBrowserEnv || Jr.hasStandardBrowserWebWorkerEnv)
                l.setContentType(void 0);
            else if (!1 !== (n = l.getContentType())) {
                const [e,...t] = n ? n.split(";").map((e => e.trim())).filter(Boolean) : [];
                l.setContentType([e || "multipart/form-data", ...t].join("; "))
            }
        if (Jr.hasStandardBrowserEnv && (a && jr.isFunction(a) && (a = a(t)),
        a || !1 !== a && va(t.url))) {
            const e = o && i && ya.read(i);
            e && l.set(o, e)
        }
        return t
    }
      , ka = "undefined" !== typeof XMLHttpRequest && function(e) {
        return new Promise((function(t, n) {
            const r = Aa(e);
            let a = r.data;
            const o = ia.from(r.headers).normalize();
            let i, l, s, u, c, {responseType: d, onUploadProgress: p, onDownloadProgress: f} = r;
            function m() {
                u && u(),
                c && c(),
                r.cancelToken && r.cancelToken.unsubscribe(i),
                r.signal && r.signal.removeEventListener("abort", i)
            }
            let h = new XMLHttpRequest;
            function g() {
                if (!h)
                    return;
                const r = ia.from("getAllResponseHeaders"in h && h.getAllResponseHeaders());
                da((function(e) {
                    t(e),
                    m()
                }
                ), (function(e) {
                    n(e),
                    m()
                }
                ), {
                    data: d && "text" !== d && "json" !== d ? h.response : h.responseText,
                    status: h.status,
                    statusText: h.statusText,
                    headers: r,
                    config: e,
                    request: h
                }),
                h = null
            }
            h.open(r.method.toUpperCase(), r.url, !0),
            h.timeout = r.timeout,
            "onloadend"in h ? h.onloadend = g : h.onreadystatechange = function() {
                h && 4 === h.readyState && (0 !== h.status || h.responseURL && 0 === h.responseURL.indexOf("file:")) && setTimeout(g)
            }
            ,
            h.onabort = function() {
                h && (n(new Or("Request aborted",Or.ECONNABORTED,e,h)),
                h = null)
            }
            ,
            h.onerror = function() {
                n(new Or("Network Error",Or.ERR_NETWORK,e,h)),
                h = null
            }
            ,
            h.ontimeout = function() {
                let t = r.timeout ? "timeout of " + r.timeout + "ms exceeded" : "timeout exceeded";
                const a = r.transitional || Qr;
                r.timeoutErrorMessage && (t = r.timeoutErrorMessage),
                n(new Or(t,a.clarifyTimeoutError ? Or.ETIMEDOUT : Or.ECONNABORTED,e,h)),
                h = null
            }
            ,
            void 0 === a && o.setContentType(null),
            "setRequestHeader"in h && jr.forEach(o.toJSON(), (function(e, t) {
                h.setRequestHeader(t, e)
            }
            )),
            jr.isUndefined(r.withCredentials) || (h.withCredentials = !!r.withCredentials),
            d && "json" !== d && (h.responseType = r.responseType),
            f && ([s,c] = ma(f, !0),
            h.addEventListener("progress", s)),
            p && h.upload && ([l,u] = ma(p),
            h.upload.addEventListener("progress", l),
            h.upload.addEventListener("loadend", u)),
            (r.cancelToken || r.signal) && (i = t => {
                h && (n(!t || t.type ? new ca(null,e,h) : t),
                h.abort(),
                h = null)
            }
            ,
            r.cancelToken && r.cancelToken.subscribe(i),
            r.signal && (r.signal.aborted ? i() : r.signal.addEventListener("abort", i)));
            const v = function(e) {
                const t = /^([-+\w]{1,25})(:?\/\/|:)/.exec(e);
                return t && t[1] || ""
            }(r.url);
            v && -1 === Jr.protocols.indexOf(v) ? n(new Or("Unsupported protocol " + v + ":",Or.ERR_BAD_REQUEST,e)) : h.send(a || null)
        }
        ))
    }
      , Sa = (e, t) => {
        const {length: n} = e = e ? e.filter(Boolean) : [];
        if (t || n) {
            let n, r = new AbortController;
            const a = function(e) {
                if (!n) {
                    n = !0,
                    i();
                    const t = e instanceof Error ? e : this.reason;
                    r.abort(t instanceof Or ? t : new ca(t instanceof Error ? t.message : t))
                }
            };
            let o = t && setTimeout(( () => {
                o = null,
                a(new Or("timeout ".concat(t, " of ms exceeded"),Or.ETIMEDOUT))
            }
            ), t);
            const i = () => {
                e && (o && clearTimeout(o),
                o = null,
                e.forEach((e => {
                    e.unsubscribe ? e.unsubscribe(a) : e.removeEventListener("abort", a)
                }
                )),
                e = null)
            }
            ;
            e.forEach((e => e.addEventListener("abort", a)));
            const {signal: l} = r;
            return l.unsubscribe = () => jr.asap(i),
            l
        }
    }
    ;
    function Ea(e, t) {
        this.v = e,
        this.k = t
    }
    function ja(e) {
        return function() {
            return new Na(e.apply(this, arguments))
        }
    }
    function Na(e) {
        var t, n;
        function r(t, n) {
            try {
                var o = e[t](n)
                  , i = o.value
                  , l = i instanceof Ea;
                Promise.resolve(l ? i.v : i).then((function(n) {
                    if (l) {
                        var s = "return" === t ? "return" : "next";
                        if (!i.k || n.done)
                            return r(s, n);
                        n = e[s](n).value
                    }
                    a(o.done ? "return" : "normal", n)
                }
                ), (function(e) {
                    r("throw", e)
                }
                ))
            } catch (e) {
                a("throw", e)
            }
        }
        function a(e, a) {
            switch (e) {
            case "return":
                t.resolve({
                    value: a,
                    done: !0
                });
                break;
            case "throw":
                t.reject(a);
                break;
            default:
                t.resolve({
                    value: a,
                    done: !1
                })
            }
            (t = t.next) ? r(t.key, t.arg) : n = null
        }
        this._invoke = function(e, a) {
            return new Promise((function(o, i) {
                var l = {
                    key: e,
                    arg: a,
                    resolve: o,
                    reject: i,
                    next: null
                };
                n ? n = n.next = l : (t = n = l,
                r(e, a))
            }
            ))
        }
        ,
        "function" != typeof e.return && (this.return = void 0)
    }
    function Ca(e) {
        return new Ea(e,0)
    }
    function Ra(e) {
        var t = {}
          , n = !1;
        function r(t, r) {
            return n = !0,
            r = new Promise((function(n) {
                n(e[t](r))
            }
            )),
            {
                done: !1,
                value: new Ea(r,1)
            }
        }
        return t["undefined" != typeof Symbol && Symbol.iterator || "@@iterator"] = function() {
            return this
        }
        ,
        t.next = function(e) {
            return n ? (n = !1,
            e) : r("next", e)
        }
        ,
        "function" == typeof e.throw && (t.throw = function(e) {
            if (n)
                throw n = !1,
                e;
            return r("throw", e)
        }
        ),
        "function" == typeof e.return && (t.return = function(e) {
            return n ? (n = !1,
            e) : r("return", e)
        }
        ),
        t
    }
    function Oa(e) {
        var t, n, r, a = 2;
        for ("undefined" != typeof Symbol && (n = Symbol.asyncIterator,
        r = Symbol.iterator); a--; ) {
            if (n && null != (t = e[n]))
                return t.call(e);
            if (r && null != (t = e[r]))
                return new Ta(t.call(e));
            n = "@@asyncIterator",
            r = "@@iterator"
        }
        throw new TypeError("Object is not async iterable")
    }
    function Ta(e) {
        function t(e) {
            if (Object(e) !== e)
                return Promise.reject(new TypeError(e + " is not an object."));
            var t = e.done;
            return Promise.resolve(e.value).then((function(e) {
                return {
                    value: e,
                    done: t
                }
            }
            ))
        }
        return Ta = function(e) {
            this.s = e,
            this.n = e.next
        }
        ,
        Ta.prototype = {
            s: null,
            n: null,
            next: function() {
                return t(this.n.apply(this.s, arguments))
            },
            return: function(e) {
                var n = this.s.return;
                return void 0 === n ? Promise.resolve({
                    value: e,
                    done: !0
                }) : t(n.apply(this.s, arguments))
            },
            throw: function(e) {
                var n = this.s.return;
                return void 0 === n ? Promise.reject(e) : t(n.apply(this.s, arguments))
            }
        },
        new Ta(e)
    }
    Na.prototype["function" == typeof Symbol && Symbol.asyncIterator || "@@asyncIterator"] = function() {
        return this
    }
    ,
    Na.prototype.next = function(e) {
        return this._invoke("next", e)
    }
    ,
    Na.prototype.throw = function(e) {
        return this._invoke("throw", e)
    }
    ,
    Na.prototype.return = function(e) {
        return this._invoke("return", e)
    }
    ;
    const La = function*(e, t) {
        let n = e.byteLength;
        if (!t || n < t)
            return void (yield e);
        let r, a = 0;
        for (; a < n; )
            r = a + t,
            yield e.slice(a, r),
            a = r
    }
      , Ua = function() {
        var e = ja((function*(e, t) {
            var n, r = !1, a = !1;
            try {
                for (var o, i = Oa(Pa(e)); r = !(o = yield Ca(i.next())).done; r = !1) {
                    const e = o.value;
                    yield*Ra(Oa(La(e, t)))
                }
            } catch (l) {
                a = !0,
                n = l
            } finally {
                try {
                    r && null != i.return && (yield Ca(i.return()))
                } finally {
                    if (a)
                        throw n
                }
            }
        }
        ));
        return function(t, n) {
            return e.apply(this, arguments)
        }
    }()
      , Pa = function() {
        var e = ja((function*(e) {
            if (e[Symbol.asyncIterator])
                return void (yield*Ra(Oa(e)));
            const t = e.getReader();
            try {
                for (; ; ) {
                    const {done: e, value: n} = yield Ca(t.read());
                    if (e)
                        break;
                    yield n
                }
            } finally {
                yield Ca(t.cancel())
            }
        }
        ));
        return function(t) {
            return e.apply(this, arguments)
        }
    }()
      , Ia = (e, t, n, r) => {
        const a = Ua(e, t);
        let o, i = 0, l = e => {
            o || (o = !0,
            r && r(e))
        }
        ;
        return new ReadableStream({
            async pull(e) {
                try {
                    const {done: t, value: r} = await a.next();
                    if (t)
                        return l(),
                        void e.close();
                    let o = r.byteLength;
                    if (n) {
                        let e = i += o;
                        n(e)
                    }
                    e.enqueue(new Uint8Array(r))
                } catch (t) {
                    throw l(t),
                    t
                }
            },
            cancel: e => (l(e),
            a.return())
        },{
            highWaterMark: 2
        })
    }
      , Fa = "function" === typeof fetch && "function" === typeof Request && "function" === typeof Response
      , za = Fa && "function" === typeof ReadableStream
      , Ma = Fa && ("function" === typeof TextEncoder ? (e => t => e.encode(t))(new TextEncoder) : async e => new Uint8Array(await new Response(e).arrayBuffer()))
      , Ba = function(e) {
        try {
            for (var t = arguments.length, n = new Array(t > 1 ? t - 1 : 0), r = 1; r < t; r++)
                n[r - 1] = arguments[r];
            return !!e(...n)
        } catch (sl) {
            return !1
        }
    }
      , qa = za && Ba(( () => {
        let e = !1;
        const t = new Request(Jr.origin,{
            body: new ReadableStream,
            method: "POST",
            get duplex() {
                return e = !0,
                "half"
            }
        }).headers.has("Content-Type");
        return e && !t
    }
    ))
      , Da = za && Ba(( () => jr.isReadableStream(new Response("").body)))
      , Ha = {
        stream: Da && (e => e.body)
    };
    var Qa;
    Fa && (Qa = new Response,
    ["text", "arrayBuffer", "blob", "formData", "stream"].forEach((e => {
        !Ha[e] && (Ha[e] = jr.isFunction(Qa[e]) ? t => t[e]() : (t, n) => {
            throw new Or("Response type '".concat(e, "' is not supported"),Or.ERR_NOT_SUPPORT,n)
        }
        )
    }
    )));
    const Ya = async (e, t) => {
        const n = jr.toFiniteNumber(e.getContentLength());
        return null == n ? (async e => {
            if (null == e)
                return 0;
            if (jr.isBlob(e))
                return e.size;
            if (jr.isSpecCompliantForm(e)) {
                const t = new Request(Jr.origin,{
                    method: "POST",
                    body: e
                });
                return (await t.arrayBuffer()).byteLength
            }
            return jr.isArrayBufferView(e) || jr.isArrayBuffer(e) ? e.byteLength : (jr.isURLSearchParams(e) && (e += ""),
            jr.isString(e) ? (await Ma(e)).byteLength : void 0)
        }
        )(t) : n
    }
      , Wa = Fa && (async e => {
        let {url: t, method: n, data: r, signal: a, cancelToken: o, timeout: i, onDownloadProgress: l, onUploadProgress: s, responseType: u, headers: d, withCredentials: p="same-origin", fetchOptions: f} = Aa(e);
        u = u ? (u + "").toLowerCase() : "text";
        let m, h = Sa([a, o && o.toAbortSignal()], i);
        const g = h && h.unsubscribe && ( () => {
            h.unsubscribe()
        }
        );
        let v;
        try {
            if (s && qa && "get" !== n && "head" !== n && 0 !== (v = await Ya(d, r))) {
                let e, n = new Request(t,{
                    method: "POST",
                    body: r,
                    duplex: "half"
                });
                if (jr.isFormData(r) && (e = n.headers.get("content-type")) && d.setContentType(e),
                n.body) {
                    const [e,t] = ha(v, ma(ga(s)));
                    r = Ia(n.body, 65536, e, t)
                }
            }
            jr.isString(p) || (p = p ? "include" : "omit");
            const a = "credentials"in Request.prototype;
            m = new Request(t,c(c({}, f), {}, {
                signal: h,
                method: n.toUpperCase(),
                headers: d.normalize().toJSON(),
                body: r,
                duplex: "half",
                credentials: a ? p : void 0
            }));
            let o = await fetch(m);
            const i = Da && ("stream" === u || "response" === u);
            if (Da && (l || i && g)) {
                const e = {};
                ["status", "statusText", "headers"].forEach((t => {
                    e[t] = o[t]
                }
                ));
                const t = jr.toFiniteNumber(o.headers.get("content-length"))
                  , [n,r] = l && ha(t, ma(ga(l), !0)) || [];
                o = new Response(Ia(o.body, 65536, n, ( () => {
                    r && r(),
                    g && g()
                }
                )),e)
            }
            u = u || "text";
            let y = await Ha[jr.findKey(Ha, u) || "text"](o, e);
            return !i && g && g(),
            await new Promise(( (t, n) => {
                da(t, n, {
                    data: y,
                    headers: ia.from(o.headers),
                    status: o.status,
                    statusText: o.statusText,
                    config: e,
                    request: m
                })
            }
            ))
        } catch (y) {
            if (g && g(),
            y && "TypeError" === y.name && /fetch/i.test(y.message))
                throw Object.assign(new Or("Network Error",Or.ERR_NETWORK,e,m), {
                    cause: y.cause || y
                });
            throw Or.from(y, y && y.code, e, m)
        }
    }
    )
      , Ga = {
        http: null,
        xhr: ka,
        fetch: Wa
    };
    jr.forEach(Ga, ( (e, t) => {
        if (e) {
            try {
                Object.defineProperty(e, "name", {
                    value: t
                })
            } catch (sl) {}
            Object.defineProperty(e, "adapterName", {
                value: t
            })
        }
    }
    ));
    const Va = e => "- ".concat(e)
      , Za = e => jr.isFunction(e) || null === e || !1 === e
      , Ka = e => {
        e = jr.isArray(e) ? e : [e];
        const {length: t} = e;
        let n, r;
        const a = {};
        for (let o = 0; o < t; o++) {
            let t;
            if (n = e[o],
            r = n,
            !Za(n) && (r = Ga[(t = String(n)).toLowerCase()],
            void 0 === r))
                throw new Or("Unknown adapter '".concat(t, "'"));
            if (r)
                break;
            a[t || "#" + o] = r
        }
        if (!r) {
            const e = Object.entries(a).map((e => {
                let[t,n] = e;
                return "adapter ".concat(t, " ") + (!1 === n ? "is not supported by the environment" : "is not available in the build")
            }
            ));
            let n = t ? e.length > 1 ? "since :\n" + e.map(Va).join("\n") : " " + Va(e[0]) : "as no adapter specified";
            throw new Or("There is no suitable adapter to dispatch the request " + n,"ERR_NOT_SUPPORT")
        }
        return r
    }
    ;
    function Ja(e) {
        if (e.cancelToken && e.cancelToken.throwIfRequested(),
        e.signal && e.signal.aborted)
            throw new ca(null,e)
    }
    function Xa(e) {
        Ja(e),
        e.headers = ia.from(e.headers),
        e.data = la.call(e, e.transformRequest),
        -1 !== ["post", "put", "patch"].indexOf(e.method) && e.headers.setContentType("application/x-www-form-urlencoded", !1);
        return Ka(e.adapter || $r.adapter)(e).then((function(t) {
            return Ja(e),
            t.data = la.call(e, e.transformResponse, t),
            t.headers = ia.from(t.headers),
            t
        }
        ), (function(t) {
            return sa(t) || (Ja(e),
            t && t.response && (t.response.data = la.call(e, e.transformResponse, t.response),
            t.response.headers = ia.from(t.response.headers))),
            Promise.reject(t)
        }
        ))
    }
    const _a = "1.7.9"
      , $a = {};
    ["object", "boolean", "number", "function", "string", "symbol"].forEach(( (e, t) => {
        $a[e] = function(n) {
            return typeof n === e || "a" + (t < 1 ? "n " : " ") + e
        }
    }
    ));
    const eo = {};
    $a.transitional = function(e, t, n) {
        function r(e, t) {
            return "[Axios v1.7.9] Transitional option '" + e + "'" + t + (n ? ". " + n : "")
        }
        return (n, a, o) => {
            if (!1 === e)
                throw new Or(r(a, " has been removed" + (t ? " in " + t : "")),Or.ERR_DEPRECATED);
            return t && !eo[a] && (eo[a] = !0,
            console.warn(r(a, " has been deprecated since v" + t + " and will be removed in the near future"))),
            !e || e(n, a, o)
        }
    }
    ,
    $a.spelling = function(e) {
        return (t, n) => (console.warn("".concat(n, " is likely a misspelling of ").concat(e)),
        !0)
    }
    ;
    const to = {
        assertOptions: function(e, t, n) {
            if ("object" !== typeof e)
                throw new Or("options must be an object",Or.ERR_BAD_OPTION_VALUE);
            const r = Object.keys(e);
            let a = r.length;
            for (; a-- > 0; ) {
                const o = r[a]
                  , i = t[o];
                if (i) {
                    const t = e[o]
                      , n = void 0 === t || i(t, o, e);
                    if (!0 !== n)
                        throw new Or("option " + o + " must be " + n,Or.ERR_BAD_OPTION_VALUE)
                } else if (!0 !== n)
                    throw new Or("Unknown option " + o,Or.ERR_BAD_OPTION)
            }
        },
        validators: $a
    }
      , no = to.validators;
    class ro {
        constructor(e) {
            this.defaults = e,
            this.interceptors = {
                request: new Hr,
                response: new Hr
            }
        }
        async request(e, t) {
            try {
                return await this._request(e, t)
            } catch (n) {
                if (n instanceof Error) {
                    let e = {};
                    Error.captureStackTrace ? Error.captureStackTrace(e) : e = new Error;
                    const t = e.stack ? e.stack.replace(/^.+\n/, "") : "";
                    try {
                        n.stack ? t && !String(n.stack).endsWith(t.replace(/^.+\n.+\n/, "")) && (n.stack += "\n" + t) : n.stack = t
                    } catch (sl) {}
                }
                throw n
            }
        }
        _request(e, t) {
            "string" === typeof e ? (t = t || {}).url = e : t = e || {},
            t = wa(this.defaults, t);
            const {transitional: n, paramsSerializer: r, headers: a} = t;
            void 0 !== n && to.assertOptions(n, {
                silentJSONParsing: no.transitional(no.boolean),
                forcedJSONParsing: no.transitional(no.boolean),
                clarifyTimeoutError: no.transitional(no.boolean)
            }, !1),
            null != r && (jr.isFunction(r) ? t.paramsSerializer = {
                serialize: r
            } : to.assertOptions(r, {
                encode: no.function,
                serialize: no.function
            }, !0)),
            to.assertOptions(t, {
                baseUrl: no.spelling("baseURL"),
                withXsrfToken: no.spelling("withXSRFToken")
            }, !0),
            t.method = (t.method || this.defaults.method || "get").toLowerCase();
            let o = a && jr.merge(a.common, a[t.method]);
            a && jr.forEach(["delete", "get", "head", "post", "put", "patch", "common"], (e => {
                delete a[e]
            }
            )),
            t.headers = ia.concat(o, a);
            const i = [];
            let l = !0;
            this.interceptors.request.forEach((function(e) {
                "function" === typeof e.runWhen && !1 === e.runWhen(t) || (l = l && e.synchronous,
                i.unshift(e.fulfilled, e.rejected))
            }
            ));
            const s = [];
            let u;
            this.interceptors.response.forEach((function(e) {
                s.push(e.fulfilled, e.rejected)
            }
            ));
            let c, d = 0;
            if (!l) {
                const e = [Xa.bind(this), void 0];
                for (e.unshift.apply(e, i),
                e.push.apply(e, s),
                c = e.length,
                u = Promise.resolve(t); d < c; )
                    u = u.then(e[d++], e[d++]);
                return u
            }
            c = i.length;
            let p = t;
            for (d = 0; d < c; ) {
                const e = i[d++]
                  , t = i[d++];
                try {
                    p = e(p)
                } catch (f) {
                    t.call(this, f);
                    break
                }
            }
            try {
                u = Xa.call(this, p)
            } catch (f) {
                return Promise.reject(f)
            }
            for (d = 0,
            c = s.length; d < c; )
                u = u.then(s[d++], s[d++]);
            return u
        }
        getUri(e) {
            return Dr(ba((e = wa(this.defaults, e)).baseURL, e.url), e.params, e.paramsSerializer)
        }
    }
    jr.forEach(["delete", "get", "head", "options"], (function(e) {
        ro.prototype[e] = function(t, n) {
            return this.request(wa(n || {}, {
                method: e,
                url: t,
                data: (n || {}).data
            }))
        }
    }
    )),
    jr.forEach(["post", "put", "patch"], (function(e) {
        function t(t) {
            return function(n, r, a) {
                return this.request(wa(a || {}, {
                    method: e,
                    headers: t ? {
                        "Content-Type": "multipart/form-data"
                    } : {},
                    url: n,
                    data: r
                }))
            }
        }
        ro.prototype[e] = t(),
        ro.prototype[e + "Form"] = t(!0)
    }
    ));
    const ao = ro;
    class oo {
        constructor(e) {
            if ("function" !== typeof e)
                throw new TypeError("executor must be a function.");
            let t;
            this.promise = new Promise((function(e) {
                t = e
            }
            ));
            const n = this;
            this.promise.then((e => {
                if (!n._listeners)
                    return;
                let t = n._listeners.length;
                for (; t-- > 0; )
                    n._listeners[t](e);
                n._listeners = null
            }
            )),
            this.promise.then = e => {
                let t;
                const r = new Promise((e => {
                    n.subscribe(e),
                    t = e
                }
                )).then(e);
                return r.cancel = function() {
                    n.unsubscribe(t)
                }
                ,
                r
            }
            ,
            e((function(e, r, a) {
                n.reason || (n.reason = new ca(e,r,a),
                t(n.reason))
            }
            ))
        }
        throwIfRequested() {
            if (this.reason)
                throw this.reason
        }
        subscribe(e) {
            this.reason ? e(this.reason) : this._listeners ? this._listeners.push(e) : this._listeners = [e]
        }
        unsubscribe(e) {
            if (!this._listeners)
                return;
            const t = this._listeners.indexOf(e);
            -1 !== t && this._listeners.splice(t, 1)
        }
        toAbortSignal() {
            const e = new AbortController
              , t = t => {
                e.abort(t)
            }
            ;
            return this.subscribe(t),
            e.signal.unsubscribe = () => this.unsubscribe(t),
            e.signal
        }
        static source() {
            let e;
            return {
                token: new oo((function(t) {
                    e = t
                }
                )),
                cancel: e
            }
        }
    }
    const io = oo;
    const lo = {
        Continue: 100,
        SwitchingProtocols: 101,
        Processing: 102,
        EarlyHints: 103,
        Ok: 200,
        Created: 201,
        Accepted: 202,
        NonAuthoritativeInformation: 203,
        NoContent: 204,
        ResetContent: 205,
        PartialContent: 206,
        MultiStatus: 207,
        AlreadyReported: 208,
        ImUsed: 226,
        MultipleChoices: 300,
        MovedPermanently: 301,
        Found: 302,
        SeeOther: 303,
        NotModified: 304,
        UseProxy: 305,
        Unused: 306,
        TemporaryRedirect: 307,
        PermanentRedirect: 308,
        BadRequest: 400,
        Unauthorized: 401,
        PaymentRequired: 402,
        Forbidden: 403,
        NotFound: 404,
        MethodNotAllowed: 405,
        NotAcceptable: 406,
        ProxyAuthenticationRequired: 407,
        RequestTimeout: 408,
        Conflict: 409,
        Gone: 410,
        LengthRequired: 411,
        PreconditionFailed: 412,
        PayloadTooLarge: 413,
        UriTooLong: 414,
        UnsupportedMediaType: 415,
        RangeNotSatisfiable: 416,
        ExpectationFailed: 417,
        ImATeapot: 418,
        MisdirectedRequest: 421,
        UnprocessableEntity: 422,
        Locked: 423,
        FailedDependency: 424,
        TooEarly: 425,
        UpgradeRequired: 426,
        PreconditionRequired: 428,
        TooManyRequests: 429,
        RequestHeaderFieldsTooLarge: 431,
        UnavailableForLegalReasons: 451,
        InternalServerError: 500,
        NotImplemented: 501,
        BadGateway: 502,
        ServiceUnavailable: 503,
        GatewayTimeout: 504,
        HttpVersionNotSupported: 505,
        VariantAlsoNegotiates: 506,
        InsufficientStorage: 507,
        LoopDetected: 508,
        NotExtended: 510,
        NetworkAuthenticationRequired: 511
    };
    Object.entries(lo).forEach((e => {
        let[t,n] = e;
        lo[n] = t
    }
    ));
    const so = lo;
    const uo = function e(t) {
        const n = new ao(t)
          , r = qn(ao.prototype.request, n);
        return jr.extend(r, ao.prototype, n, {
            allOwnKeys: !0
        }),
        jr.extend(r, n, null, {
            allOwnKeys: !0
        }),
        r.create = function(n) {
            return e(wa(t, n))
        }
        ,
        r
    }($r);
    uo.Axios = ao,
    uo.CanceledError = ca,
    uo.CancelToken = io,
    uo.isCancel = sa,
    uo.VERSION = _a,
    uo.toFormData = Ir,
    uo.AxiosError = Or,
    uo.Cancel = uo.CanceledError,
    uo.all = function(e) {
        return Promise.all(e)
    }
    ,
    uo.spread = function(e) {
        return function(t) {
            return e.apply(null, t)
        }
    }
    ,
    uo.isAxiosError = function(e) {
        return jr.isObject(e) && !0 === e.isAxiosError
    }
    ,
    uo.mergeConfig = wa,
    uo.AxiosHeaders = ia,
    uo.formToJSON = e => Xr(jr.isHTMLForm(e) ? new FormData(e) : e),
    uo.getAdapter = Ka,
    uo.HttpStatusCode = so,
    uo.default = uo;
    const co = uo
      , po = "task_invite"
      , fo = () => {
        const {user: e} = Sn()
          , [t,n] = (0,
        a.useState)(null)
          , [r,o] = (0,
        a.useState)([])
          , [i,l] = (0,
        a.useState)(0);
        return (0,
        a.useEffect)(( () => {
            wn().ymReachGoal("ladybug_game_view_friends"),
            console.log("[Ladybug.Friends] > ready"),
            co.post("".concat(Tt, "/api/ladybug-game/friends"), {
                hash: e.authToken
            }).then((e => {
                console.log("friends response", e),
                o(e.data),
                l((e.data.length || 0) * Ut)
            }
            ))
        }
        ), []),
        (0,
        Yt.jsxs)("div", {
            className: "app-friends app-hide-scroll",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-friends--list",
                children: [(0,
                Yt.jsx)("h2", {
                    children: "\u0414\u0440\u0443\u0437\u044c\u044f"
                }), (0,
                Yt.jsxs)("p", {
                    children: ["\u041e\u043d\u0438 \u0443\u0436\u0435 \u043f\u0440\u0438\u0441\u043e\u0435\u0434\u0438\u043d\u0438\u043b\u0438\u0441\u044c \u043a \u0438\u0433\u0440\u0435", (0,
                    Yt.jsx)("br", {}), " \u043f\u043e \u0442\u0432\u043e\u0435\u0439 \u0441\u0441\u044b\u043b\u043a\u0435.", (0,
                    Yt.jsx)("br", {}), "\u041d\u043e \u0447\u0442\u043e\u0431\u044b \u043f\u043e\u043b\u0443\u0447\u0438\u0442\u044c \u0431\u0430\u043b\u043b\u044b \u0437\u0430 \u043f\u0440\u0438\u0433\u043b\u0430\u0448\u0435\u043d\u0438\u0435, \u0434\u0440\u0443\u0433 \u0434\u043e\u043b\u0436\u0435\u043d \u0441\u044b\u0433\u0440\u0430\u0442\u044c \u0445\u043e\u0442\u044f \u0431\u044b \u043e\u0434\u043d\u0443 \u0438\u0433\u0440\u0443!", (0,
                    Yt.jsx)("br", {}), "\u0417\u0430 \u044d\u0442\u043e \u0442\u0435\u0431\u0435 \u043d\u0430\u0447\u0438\u0441\u043b\u0435\u043d\u044b \u0431\u0430\u043b\u043b\u044b:"]
                }), (0,
                Yt.jsx)(Xt, {
                    coins: i,
                    big: !0
                }), !r.length && (0,
                Yt.jsxs)("div", {
                    className: "app-friends--empty",
                    children: ["\u0422\u0443\u0442 \u043f\u043e\u043a\u0430 \u043d\u0438\u043a\u043e\u0433\u043e \u043d\u0435\u0442 :(", (0,
                    Yt.jsx)("br", {}), " \u041f\u0440\u0438\u0433\u043b\u0430\u0441\u0438 \u0434\u0440\u0443\u0437\u0435\u0439 \u0432 \u0438\u0433\u0440\u0443!"]
                }), !!r.length && r.map(( (e, t) => (0,
                Yt.jsx)(rn, {
                    image: e.photoPath || sn,
                    title: ((e.first_name || "") + " " + (e.last_name || "")).trim(),
                    coins: e.score
                }, "friend_card_" + t)))]
            }), (0,
            Yt.jsx)("div", {
                className: "app-friends--invite",
                children: (0,
                Yt.jsx)(mn, {
                    image: bn,
                    title: "\u041f\u0440\u0438\u0433\u043b\u0430\u0441\u0438 \u0431\u043e\u043b\u044c\u0448\u0435 \u0434\u0440\u0443\u0437\u0435\u0439!",
                    coins: Ut,
                    completed: !1,
                    onClick: () => n(po)
                })
            }), (0,
            Yt.jsx)(Kt, {}), (0,
            Yt.jsx)("div", {
                className: "app-friends--underlay"
            }), po === t && (0,
            Yt.jsx)(Cn, {
                onClose: () => n(null)
            })]
        })
    }
      , mo = e => {
        let {coins: t} = e;
        return (0,
        Yt.jsx)("div", {
            className: "app-game-coins",
            children: (0,
            Yt.jsx)(Xt, {
                coins: t,
                big: !0
            })
        })
    }
      , ho = n.p + "static/media/game-tikki.cd60f8f87755a99c8e22.png"
      , go = n.p + "static/media/game-plag.51348cff033cc07d7637.png"
      , vo = n.p + "static/media/game-banix.c4ad29fef60a286094b8.png"
      , yo = n.p + "static/media/game-pollen.4eb13e8bf0118ef165da.png"
      , bo = n.p + "static/media/game-xuppu.20d1e446975d0817cfe0.png"
      , xo = n.p + "static/media/game-trix.e23fd9a0f8b12a912110.png"
      , wo = n.p + "static/media/game-logo-tv3.81749e579e8aa6566a53.png"
      , Ao = {
        tikki: {
            code: "tikki",
            image: ho,
            coins: 3,
            freeze: !1,
            reset: !1
        },
        plag: {
            code: "plag",
            image: go,
            coins: 2,
            freeze: !1,
            reset: !1
        },
        banix: {
            code: "banix",
            image: vo,
            coins: 5,
            freeze: !1,
            reset: !1
        },
        pollen: {
            code: "pollen",
            image: yo,
            coins: 0,
            freeze: !0,
            reset: !1
        },
        trix: {
            code: "trix",
            image: xo,
            coins: 1,
            freeze: !1,
            reset: !1
        },
        acuma: {
            code: "acuma",
            image: n.p + "static/media/game-acuma-item.3619aa78364bfbe8dba3.png",
            coins: 0,
            freeze: !1,
            reset: !1,
            loseLive: !0
        },
        logoTv3: {
            code: "logoTv3",
            image: wo,
            coins: 30,
            freeze: !1,
            reset: !1
        },
        xuppu: {
            code: "xuppu",
            image: bo,
            coins: 0,
            freeze: !1,
            reset: !0,
            loseLive: !0
        }
    };
    const ko = n.p + "static/media/rectangle-left.5d622317eec049a393c96372ecdd2ee7.svg"
      , So = e => {
        let {data: t} = e;
        return (0,
        Yt.jsx)(Yt.Fragment, {
            children: (0,
            Yt.jsx)("div", {
                className: "app-game-guide--description",
                children: t
            })
        })
    }
      , Eo = () => (0,
    Yt.jsxs)("div", {
        className: "app-game-guide--description",
        children: [(0,
        Yt.jsxs)("p", {
            children: ["\u0422\u0430\u043f\u0430\u0439 \u043d\u0430 \u0422\u0438\u043a\u043a\u0438, \u041f\u043b\u0430\u0433\u0430,", (0,
            Yt.jsx)("br", {}), " \u0422\u0440\u0438\u043a\u043a\u0441 \u0438 \u041b\u043e\u0433\u043e\u0442\u0438\u043f \u0422\u0412-3", (0,
            Yt.jsx)("br", {}), " \u0438 \u0437\u0430\u0440\u0430\u0431\u0430\u0442\u044b\u0432\u0430\u0439 \u0431\u0430\u043b\u043b\u044b"]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-game-guide--kwami-wrapper",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-game-guide--kwami",
                children: [(0,
                Yt.jsxs)("div", {
                    className: "app-game-guide--trix app-game-item_success",
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "app-game-item--coins",
                        children: [(0,
                        Yt.jsxs)("span", {
                            className: "app-game-item--value",
                            children: ["+", Ao.trix.coins]
                        }), (0,
                        Yt.jsx)("img", {
                            className: "app-game-item--icon",
                            src: Jt,
                            alt: ""
                        })]
                    }), (0,
                    Yt.jsx)("img", {
                        src: Ao.trix.image,
                        alt: ""
                    })]
                }), (0,
                Yt.jsxs)("div", {
                    className: "app-game-guide--plag app-game-item_success",
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "app-game-item--coins",
                        children: [(0,
                        Yt.jsxs)("span", {
                            className: "app-game-item--value",
                            children: ["+", Ao.plag.coins]
                        }), (0,
                        Yt.jsx)("img", {
                            className: "app-game-item--icon",
                            src: Jt,
                            alt: ""
                        })]
                    }), (0,
                    Yt.jsx)("img", {
                        src: Ao.plag.image,
                        alt: ""
                    })]
                }), (0,
                Yt.jsxs)("div", {
                    className: "app-game-guide--tikki app-game-item_success",
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "app-game-item--coins",
                        children: [(0,
                        Yt.jsxs)("span", {
                            className: "app-game-item--value",
                            children: ["+", Ao.tikki.coins]
                        }), (0,
                        Yt.jsx)("img", {
                            className: "app-game-item--icon",
                            src: Jt,
                            alt: ""
                        })]
                    }), (0,
                    Yt.jsx)("img", {
                        src: Ao.tikki.image,
                        alt: ""
                    })]
                })]
            }), (0,
            Yt.jsx)("div", {
                className: "app-game-guide--kwami",
                children: (0,
                Yt.jsxs)("div", {
                    className: "app-game-guide--trix app-game-item_success",
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "app-game-item--coins",
                        children: [(0,
                        Yt.jsxs)("span", {
                            className: "app-game-item--value",
                            children: ["+", Ao.logoTv3.coins]
                        }), (0,
                        Yt.jsx)("img", {
                            className: "app-game-item--icon",
                            src: Jt,
                            alt: ""
                        })]
                    }), (0,
                    Yt.jsx)("img", {
                        src: Ao.logoTv3.image,
                        alt: ""
                    })]
                })
            })]
        })]
    })
      , jo = () => (0,
    Yt.jsxs)("div", {
        className: "app-game-guide--step3-wrapper",
        children: [(0,
        Yt.jsxs)("div", {
            className: "app-game-guide--description",
            children: [(0,
            Yt.jsxs)("p", {
                children: ["\u041d\u0435 \u0442\u0430\u043f\u0430\u0439 \u043d\u0430 \u0428\u0443\u043f\u043f\u0443, \u043e\u043d", (0,
                Yt.jsx)("br", {}), " \u043e\u0431\u043d\u0443\u043b\u0438\u0442 \u0442\u0432\u043e\u0438 \u0431\u0430\u043b\u043b\u044b!"]
            }), (0,
            Yt.jsx)("div", {
                className: "app-game-guide--kwami",
                children: (0,
                Yt.jsx)("div", {
                    className: "app-game-guide--xuppu app-game-item_danger",
                    children: (0,
                    Yt.jsx)("img", {
                        src: Ao.xuppu.image,
                        alt: ""
                    })
                })
            })]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-game-guide--description",
            children: [(0,
            Yt.jsxs)("p", {
                children: ["\u0410\u043a\u0443\u043c\u0430 \u0443\u0432\u0435\u043b\u0438\u0447\u0438\u0432\u0430\u0435\u0442", (0,
                Yt.jsx)("br", {}), " \u0441\u043a\u043e\u0440\u043e\u0441\u0442\u044c ", (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "\u0432 \u0434\u0432\u0430 \u0440\u0430\u0437\u0430"
                }), (0,
                Yt.jsx)("br", {}), "\u043d\u0430 5 \u0441\u0435\u043a\u0443\u043d\u0434"]
            }), (0,
            Yt.jsx)("div", {
                className: "app-game-guide--kwami",
                children: (0,
                Yt.jsx)("div", {
                    className: "app-game-guide--xuppu app-game-item_danger",
                    children: (0,
                    Yt.jsx)("img", {
                        src: Ao.acuma.image,
                        alt: ""
                    })
                })
            })]
        })]
    })
      , No = () => (0,
    Yt.jsxs)("div", {
        className: "app-game-guide--description",
        children: [(0,
        Yt.jsx)("div", {
            className: "app-game-guide--combo",
            children: "\u041a\u041e\u041c\u0411\u041e"
        }), (0,
        Yt.jsx)("div", {
            className: "app-game-guide--kwami-wrapper-4",
            children: (0,
            Yt.jsx)("div", {
                className: "app-game-guide--kwami",
                children: (0,
                Yt.jsx)("div", {
                    className: "app-game-guide--xuppu app-game-item_danger",
                    children: (0,
                    Yt.jsx)("img", {
                        src: Ao.tikki.image,
                        alt: ""
                    })
                })
            })
        }), (0,
        Yt.jsxs)("div", {
            className: "app-game-guide--step4-text",
            children: ["\u041a\u043e\u043c\u0431\u043e - \u0441\u043e\u0431\u0438\u0440\u0430\u0439 \u0441\u0435\u0440\u0438\u0438", (0,
            Yt.jsx)("br", {}), " \u0438\u0437 \u043a\u0432\u0430\u043c\u0438 \u0438 \u043f\u043e\u043b\u0443\u0447\u0430\u0439", (0,
            Yt.jsx)("br", {}), " \u0443\u043c\u043d\u043e\u0436\u0435\u043d\u0438\u0435 \u0431\u0430\u043b\u043b\u043e\u0432"]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-game-guide--step4-guide",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-game-guide--step4-guide-text",
                children: ["5 \u043f\u043e\u0434\u0440\u044f\u0434: ", (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "\xd71.5"
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-game-guide--step4-guide-text",
                children: ["10 \u043f\u043e\u0434\u0440\u044f\u0434: ", (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "\xd72"
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-game-guide--step4-guide-text",
                children: ["15 \u043f\u043e\u0434\u0440\u044f\u0434: ", (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "\xd72.5"
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-game-guide--step4-guide-text",
                children: ["\u041a\u0430\u0436\u0434\u044b\u0435 \u0441\u043b\u0435\u0434\u0443\u044e\u0449\u0438\u0435 +5:", (0,
                Yt.jsx)("br", {}), " ", (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "+0.5 \u043a \u043c\u043d\u043e\u0436\u0438\u0442\u0435\u043b\u044e"
                })]
            })]
        })]
    })
      , Co = () => (0,
    Yt.jsxs)("div", {
        className: "app-game-guide--description",
        children: [(0,
        Yt.jsxs)("div", {
            className: "app-game-guide--step4-text",
            children: ["\u0427\u0438\u0441\u0442\u0430\u044f \u0438\u0433\u0440\u0430 - \u0441\u043e\u0431\u0438\u0440\u0430\u0439", (0,
            Yt.jsx)("br", {}), " \u043a\u0432\u0430\u043c\u0438 \u0431\u0435\u0437 \u043e\u0448\u0438\u0431\u043e\u043a", (0,
            Yt.jsx)("br", {}), " \u0438 \u043f\u043e\u043b\u0443\u0447\u0430\u0439 ", (0,
            Yt.jsx)("span", {
                className: "app-game-guide--yellow",
                children: "\xd71.5"
            }), (0,
            Yt.jsx)("br", {}), " \u043a \u043d\u0430\u0431\u0440\u0430\u043d\u043d\u044b\u043c \u0431\u0430\u043b\u043b\u0430\u043c"]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-game-guide--images-wrapper",
            children: [(0,
            Yt.jsx)("div", {
                children: (0,
                Yt.jsx)("img", {
                    className: "app-game-guide--image-step5-rotated",
                    src: Ao.tikki.image,
                    alt: ""
                })
            }), (0,
            Yt.jsx)("div", {
                children: (0,
                Yt.jsx)("img", {
                    className: "app-game-guide--image-step5",
                    src: Ao.plag.image,
                    alt: ""
                })
            })]
        })]
    })
      , Ro = e => {
        let {onCompleted: t, gameType: n} = e;
        const [r,o] = (0,
        a.useState)(1)
          , {user: i, setUser: l} = Sn();
        (0,
        a.useEffect)(( () => wn().ymReachGoal("ladybug_game_view_guide")), []),
        (0,
        a.useEffect)(( () => {
            1 <= r && r <= 5 ? console.log("[Ladybug.Guide] > step #" + r) : (console.log("[Ladybug.Guide] > completed"),
            t())
        }
        ), [r]);
        const s = () => {
            co.post("".concat(Tt, "/api/tutorials"), {
                hash: null === i || void 0 === i ? void 0 : i.authToken,
                game_mode: n
            }).then(( () => {
                l(c(c({}, i), {}, {
                    tutorials: [...null === i || void 0 === i ? void 0 : i.tutorials, n]
                }))
            }
            )).catch(( () => {
                console.log("[Ladybug.Game] > finishTutorial failed")
            }
            ))
        }
          , u = {
            [qt]: (0,
            Yt.jsxs)("div", {
                children: ["\u041e\u0434\u043d\u0430 \u0438\u0433\u0440\u0430 \u0434\u043b\u0438\u0442\u0441\u044f", (0,
                Yt.jsx)("br", {}), (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "60 \u0441\u0435\u043a\u0443\u043d\u0434."
                }), (0,
                Yt.jsx)("br", {}), "\u0427\u0435\u043c \u0431\u043e\u043b\u044c\u0448\u0435 \u043a\u0432\u0430\u043c\u0438 \u0442\u044b", (0,
                Yt.jsx)("br", {}), " \u043f\u043e\u0439\u043c\u0430\u0435\u0448\u044c, \u0442\u0435\u043c \u0431\u043e\u043b\u044c\u0448\u0435", (0,
                Yt.jsx)("br", {}), " \u0431\u0430\u043b\u043b\u043e\u0432 \u0437\u0430\u0440\u0430\u0431\u043e\u0442\u0430\u0435\u0448\u044c"]
            }),
            [Dt]: (0,
            Yt.jsxs)("div", {
                children: ["\u041e\u0434\u043d\u0430 \u0438\u0433\u0440\u0430 \u0434\u043b\u0438\u0442\u0441\u044f", " ", (0,
                Yt.jsxs)("span", {
                    className: "app-game-guide--yellow",
                    children: ["30", (0,
                    Yt.jsx)("br", {}), " \u0441\u0435\u043a\u0443\u043d\u0434."]
                }), " ", "\u0421\u043a\u043e\u0440\u043e\u0441\u0442\u044c \u0438\u0433\u0440\u044b", (0,
                Yt.jsx)("br", {}), "\u0443\u0432\u0435\u043b\u0438\u0447\u0435\u043d\u0430."]
            }),
            [Ht]: (0,
            Yt.jsxs)("div", {
                children: ["\u0418\u0433\u0440\u0430 \u0434\u043b\u0438\u0442\u0441\u044f \u0431\u0435\u0437 \u0443\u0447\u0435\u0442\u0430", (0,
                Yt.jsx)("br", {}), " \u0432\u0440\u0435\u043c\u0435\u043d\u0438 \u0434\u043e \u0442\u0440\u0435\u0445 \u043e\u0448\u0438\u0431\u043e\u043a.", (0,
                Yt.jsx)("br", {}), " \u041a\u0430\u0436\u0434\u044b\u0435 ", (0,
                Yt.jsx)("span", {
                    className: "app-game-guide--yellow",
                    children: "15 \u0441\u0435\u043a\u0443\u043d\u0434"
                }), " \u0441\u043a\u043e\u0440\u043e\u0441\u0442\u044c", (0,
                Yt.jsx)("br", {}), " \u0443\u0432\u0435\u043b\u0438\u0447\u0438\u0432\u0430\u0435\u0442\u0441\u044f \u0438 \u043d\u0430\u0447\u0438\u0441\u043b\u044f\u044e\u0442\u0441\u044f", (0,
                Yt.jsx)("br", {}), " \u0434\u043e\u043f\u043e\u043b\u043d\u0438\u0442\u0435\u043b\u044c\u043d\u044b\u0435 \u0431\u0430\u043b\u043b\u044b."]
            })
        };
        return (0,
        Yt.jsxs)("div", {
            className: "app-game-guide",
            children: [5 !== r && (0,
            Yt.jsxs)("div", {
                onClick: () => {
                    t(),
                    s()
                }
                ,
                className: "app-game-guide--skip",
                children: [(0,
                Yt.jsx)("div", {
                    children: "\u041f\u0440\u043e\u043f\u0443\u0441\u0442\u0438\u0442\u044c"
                }), (0,
                Yt.jsx)("img", {
                    className: "app-game-guide--skip-image",
                    src: ko,
                    alt: ""
                })]
            }), 1 === r && (0,
            Yt.jsx)(So, {
                data: u[n]
            }), 2 === r && (0,
            Yt.jsx)(Eo, {}), 3 === r && (0,
            Yt.jsx)(jo, {}), 4 === r && (0,
            Yt.jsx)(No, {}), 5 === r && (0,
            Yt.jsx)(Co, {}), (0,
            Yt.jsx)("div", {
                className: "app-game-guide--button-wrapper",
                children: (0,
                Yt.jsx)(Wt, {
                    variant: 5 !== r && "outlined",
                    onClick: () => {
                        4 === r && n === Ht && (t(),
                        s()),
                        5 !== r || s(),
                        o((e => e + 1))
                    }
                    ,
                    children: 5 !== r ? "\u0414\u0430\u043b\u0435\u0435" : "\u0418\u0433\u0440\u0430\u0442\u044c"
                })
            })]
        })
    }
      , Oo = e => {
        let {image: t, coins: n, reset: r, left: o, onClick: i, onMissed: l, kek: s} = e;
        const [u,c] = (0,
        a.useState)(!1)
          , [d,p] = (0,
        a.useState)(0)
          , {multiplier: f, streak: m} = $o();
        return (0,
        a.useEffect)(( () => {
            !0 === u && i()
        }
        ), [u]),
        console.log("streak", m),
        (0,
        Yt.jsxs)("div", {
            draggable: !1,
            className: "app-game-item" + (u > 0 ? " app-game-item_clicked" : "") + (u > 0 && r ? " app-game-item_danger" : "") + (u > 0 && !r ? " app-game-item_success" : ""),
            style: {
                left: o + "%",
                top: d
            },
            onClick: e => {
                !1 === wn().isTouchDevice() && (p(e.target.getBoundingClientRect().top),
                c(!0))
            }
            ,
            onTouchEnd: e => {
                !0 === wn().isTouchDevice() && (p(e.target.getBoundingClientRect().top),
                c(!0))
            }
            ,
            onAnimationEnd: () => {
                u || l()
            }
            ,
            children: [u && n > 0 && (0,
            Yt.jsxs)("div", {
                className: "app-game-item--coins",
                children: [m && m % 5 === 0 && (0,
                Yt.jsx)("div", {
                    className: "app-game-item--combo",
                    children: "\u041a\u041e\u041c\u0411\u041e"
                }), m && m % 5 !== 0 && (0,
                Yt.jsxs)(Yt.Fragment, {
                    children: [(0,
                    Yt.jsxs)("span", {
                        className: "app-game-item--value",
                        children: ["+", n * f]
                    }), (0,
                    Yt.jsx)("img", {
                        className: "app-game-item--icon",
                        src: Jt,
                        alt: ""
                    })]
                })]
            }), (0,
            Yt.jsx)("img", {
                src: t,
                alt: "",
                className: "app-game-item--image"
            })]
        })
    }
      , To = e => {
        let {coins: t, bonus: n, onRestart: r, result: a, isSurvivalMode: o} = e;
        return (0,
        Yt.jsxs)("div", {
            className: "app-game-result",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-game-result--amount",
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-game-result--title",
                    children: "\u0422\u0432\u043e\u0439 \u0440\u0435\u0437\u0443\u043b\u044c\u0442\u0430\u0442"
                }), (0,
                Yt.jsxs)("div", {
                    className: "app-game-result--result-box",
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "app-game-result--left-result",
                        children: [(0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u0431\u0430\u043b\u043b\u044b"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u043a\u043e\u043c\u0431\u043e"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u0431\u043e\u043d\u0443\u0441 \u0422\u0412-3"
                        }), !o && (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u0431\u0435\u0437 \u043e\u0448\u0438\u0431\u043e\u043a"
                        }), o && (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u0431\u043e\u043d\u0443\u0441 \u0437\u0430 \u0432\u0440\u0435\u043c\u044f"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u043b\u043e\u0432\u0443\u0448\u043a\u0438"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--left-result-item",
                            children: "\u043a\u043e\u043c\u0430\u043d\u0434\u0430"
                        })]
                    }), (0,
                    Yt.jsxs)("div", {
                        className: "app-game-result--right-result",
                        children: [(0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.pureCoins ? "app-game-result_success" : ""),
                            children: (null === a || void 0 === a ? void 0 : a.pureCoins) || "-"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.comboCoins ? "app-game-result_success" : ""),
                            children: (null === a || void 0 === a ? void 0 : a.comboCoins) || "-"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.logoBonusCoins ? "app-game-result_success" : ""),
                            children: (null === a || void 0 === a ? void 0 : a.logoBonusCoins) || "-"
                        }), !o && (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.clearSessionCoins ? "app-game-result_success" : ""),
                            children: (null === a || void 0 === a ? void 0 : a.clearSessionCoins) || "-"
                        }), o && (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.survivalCoins ? "app-game-result_success" : ""),
                            children: (null === a || void 0 === a ? void 0 : a.survivalCoins) || "-"
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.resetCoins ? "app-game-result_negative" : ""),
                            children: "".concat(null !== a && void 0 !== a && a.resetCoins ? "-" + (null === a || void 0 === a ? void 0 : a.resetCoins) : "-")
                        }), (0,
                        Yt.jsx)("div", {
                            className: "app-game-result--right-result-item " + (null !== a && void 0 !== a && a.squadCoins ? "app-game-result_success" : ""),
                            children: (null === a || void 0 === a ? void 0 : a.squadCoins) || "-"
                        })]
                    })]
                }), (0,
                Yt.jsxs)("div", {
                    className: "app-game-result--coins",
                    children: [(0,
                    Yt.jsx)("div", {
                        className: "app-game-result--conclusion",
                        children: "\u0418\u0442\u043e\u0433"
                    }), (0,
                    Yt.jsx)(Xt, {
                        coins: t,
                        big: !0
                    })]
                }), n > 0 && (0,
                Yt.jsxs)("div", {
                    className: "app-game-result--bonus",
                    children: [(0,
                    Yt.jsx)(Xt, {
                        coins: n,
                        big: !1
                    }), " ", (0,
                    Yt.jsx)("span", {
                        children: "\u0431\u043e\u043d\u0443\u0441"
                    })]
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-game-result--buttons",
                children: [(0,
                Yt.jsx)(Wt, {
                    onClick: () => r(),
                    children: "\u0418\u0433\u0440\u0430\u0442\u044c \u0435\u0449\u0435"
                }), (0,
                Yt.jsx)(pt, {
                    to: xt,
                    children: (0,
                    Yt.jsx)(Wt, {
                        ghost: !0,
                        onClick: () => r(),
                        children: "\u041d\u0430 \u0433\u043b\u0430\u0432\u043d\u0443\u044e"
                    })
                })]
            }), (0,
            Yt.jsx)("svg", {
                className: "app-game-result--shadow",
                width: "312",
                height: "312",
                viewBox: "0 0 312 312",
                fill: "none",
                xmlns: "http://www.w3.org/2000/svg",
                children: (0,
                Yt.jsx)("circle", {
                    cx: "156",
                    cy: "156",
                    r: "156",
                    fill: "black"
                })
            })]
        })
    }
      , Lo = e => {
        let {seconds: t, onStop: n} = e;
        const [r,o] = (0,
        a.useState)(t);
        if ((0,
        a.useEffect)(( () => {
            let e = setInterval(( () => {
                o((t => 1 === t ? (clearInterval(e),
                0) : t - 1))
            }
            ), 1e3)
        }
        ), []),
        (0,
        a.useEffect)(( () => {
            0 === r && n(!0)
        }
        ), [r]),
        r > 0)
            return (0,
            Yt.jsx)("div", {
                className: "app-game-start-countdown",
                children: r
            })
    }
      , Uo = "normal"
      , Po = "warning"
      , Io = "danger"
      , Fo = e => {
        let {seconds: t, freeze: n, onEdge: r, onStop: o} = e;
        const [i,l] = (0,
        a.useState)(Uo)
          , [s,u] = (0,
        a.useState)(t)
          , [c,d] = (0,
        a.useState)(null);
        return (0,
        a.useEffect)(( () => {
            if (!0 === n)
                window.clearInterval(c);
            else {
                let e = window.setInterval(( () => {
                    u((t => 0 === t ? (window.clearInterval(e),
                    0) : t - 1))
                }
                ), 1e3);
                d(e)
            }
            return () => {
                window.clearInterval(c)
            }
        }
        ), [n]),
        (0,
        a.useEffect)(( () => {
            [50, 40, 30, 20, 10].includes(s) && r(s),
            20 === s ? l(Po) : 10 === s ? l(Io) : 0 === s && o(!0)
        }
        ), [s]),
        (0,
        Yt.jsxs)("div", {
            className: "app-game-timer app-game-timer_" + i,
            children: [(0,
            Yt.jsx)("span", {
                children: "".concat(Math.floor(s / 60)).padStart(2, 0)
            }), ":", (0,
            Yt.jsx)("span", {
                children: "".concat(s % 60).padStart(2, 0)
            })]
        })
    }
    ;
    const zo = n.p + "static/media/heart-fill.ba43898f925d6fe82d6f6d60e5056978.svg";
    const Mo = n.p + "static/media/heart.582e2d8709949712a1fe011ddcf577c3.svg"
      , Bo = e => {
        let {lives: t} = e;
        return (0,
        Yt.jsx)("div", {
            className: "game-lives",
            children: [...Array(3)].map(( (e, n) => (0,
            Yt.jsx)("img", {
                src: n < t ? zo : Mo,
                alt: "heart",
                className: "game-lives__heart"
            }, n)))
        })
    }
      , qo = n.p + "static/media/gold.a3874c5d78511bd36fc4.png"
      , Do = n.p + "static/media/silver.d586a3c85c9c65ee4d44.png"
      , Ho = e => {
        let {onClose: t, type: n="gold"} = e;
        const [r,o] = (0,
        a.useState)(!1)
          , i = {
            gold: qo,
            silver: Do
        };
        return (0,
        Yt.jsxs)(ln, {
            buttonText: "",
            onButtonClick: () => {}
            ,
            onClose: t,
            closed: r,
            type: "dark",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-popup-new-league",
                children: [(0,
                Yt.jsx)("img", {
                    src: i[n],
                    alt: "",
                    className: "app-popup-new-league--image"
                }), (0,
                Yt.jsxs)("div", {
                    className: "app-popup-new-league--wrapper",
                    children: [(0,
                    Yt.jsx)("div", {
                        className: "app-popup-new-league--title",
                        children: "\u0422\u0432\u043e\u044f \u043a\u043e\u043c\u0430\u043d\u0434\u0430 \u043f\u0435\u0440\u0435\u0448\u043b\u0430"
                    }), (0,
                    Yt.jsxs)("div", {
                        className: "app-popup-new-league--title",
                        children: ["\u0432 ", {
                            gold: "\u0437\u043e\u043b\u043e\u0442\u0443\u044e",
                            silver: "\u0441\u0435\u0440\u0435\u0431\u0440\u044f\u043d\u0443\u044e"
                        }[n], " \u043b\u0438\u0433\u0443!"]
                    })]
                }), (0,
                Yt.jsx)("div", {
                    className: "app-popup-new-league--multiplier-text",
                    children: "\u0422\u0435\u043f\u0435\u0440\u044c \u043a\u043e\u043c\u0430\u043d\u0434\u043d\u044b\u0439 \u043c\u043d\u043e\u0436\u0438\u0442\u0435\u043b\u044c"
                }), (0,
                Yt.jsxs)("div", {
                    className: "app-popup-new-league--multiplier " + (n ? "app-popup-new-league--".concat(n) : ""),
                    children: ["\xd7", {
                        gold: "1.2",
                        silver: "1.1"
                    }[n]]
                })]
            }), (0,
            Yt.jsx)("div", {
                className: "app-popup-new-league--action-wrapper",
                children: (0,
                Yt.jsx)(Wt, {
                    onClick: t,
                    children: "\u041e\u043a"
                })
            })]
        })
    }
      , Qo = window.Telegram.WebApp
      , Yo = [].concat(Array(16).fill(Ao.tikki)).concat(Array(24).fill(Ao.plag)).concat(Array(32).fill(Ao.trix)).concat(Array(1).fill(Ao.logoTv3)).concat(Array(8).fill(Ao.xuppu)).concat(Array(8).fill(Ao.acuma)).sort(( () => Math.random() - .5))
      , Wo = {
        GUIDE: "guide",
        COUNTDOWN: "countdown",
        PLAYING: "playing",
        RESULT: "result"
    }
      , Go = [700, 650, 600, 550, 500, 450]
      , Vo = {
        60: "01:00",
        30: "00:30"
    }
      , Zo = {
        [qt]: qt,
        [Dt]: Dt,
        [Ht]: Ht
    }
      , Ko = ["xuppu", "acuma"]
      , Jo = {
        [qt]: {
            1: 1,
            2: 2,
            3: 3,
            4: 4,
            5: 5,
            6: 6
        },
        [Dt]: {
            4: 1,
            5: 2,
            6: 3
        }
    }
      , Xo = "new_squad_league_popup"
      , _o = (0,
    a.createContext)()
      , $o = () => (0,
    a.useContext)(_o)
      , ei = e => {
        var t;
        let {gameType: n="", timeValue: r=""} = e;
        const {user: o, setUser: i} = Sn()
          , [l,s] = (0,
        a.useState)(null)
          , [u,d] = (0,
        a.useState)(null !== o && void 0 !== o && null !== (t = o.tutorials) && void 0 !== t && t.includes(n) ? Wo.COUNTDOWN : Wo.GUIDE)
          , [p,f] = (0,
        a.useState)(1)
          , [m,h] = (0,
        a.useState)(Go[0])
          , [g,v] = (0,
        a.useState)(!1)
          , [y,b] = (0,
        a.useState)(0)
          , [x,w] = (0,
        a.useState)(0)
          , [A,k] = (0,
        a.useState)([])
          , [S,E] = (0,
        a.useState)(3)
          , [j,N] = (0,
        a.useState)(!1)
          , [C,R] = (0,
        a.useState)(!1)
          , [O,T] = (0,
        a.useState)(1)
          , [L,U] = (0,
        a.useState)(0)
          , [P,I] = (0,
        a.useState)(!0)
          , [F,z] = (0,
        a.useState)(!1)
          , [M,B] = (0,
        a.useState)(0)
          , [q,D] = (0,
        a.useState)(0)
          , [H,Q] = (0,
        a.useState)(0)
          , [Y,W] = (0,
        a.useState)(0)
          , [G,V] = (0,
        a.useState)(0)
          , [Z,K] = (0,
        a.useState)(0)
          , [J,X] = (0,
        a.useState)(0)
          , [_,$] = (0,
        a.useState)(null)
          , [ee,te] = (0,
        a.useState)(null)
          , ne = n === Ht
          , re = (0,
        a.useRef)(y)
          , ae = () => {
            E((e => 1 === e ? (N(!0),
            k([]),
            le(l, re.current),
            d(Wo.RESULT),
            0) : e - 1))
        }
        ;
        (0,
        a.useEffect)(( () => {
            ne && I(!1)
        }
        ), [ne]),
        (0,
        a.useEffect)(( () => {
            if (u === Wo.PLAYING && ne) {
                const e = setInterval(( () => {
                    f((e => e + 1)),
                    b((e => e + 20)),
                    X((e => e + 20)),
                    console.log("\u0421\u043a\u043e\u0440\u043e\u0441\u0442\u044c \u0443\u0432\u0435\u043b\u0438\u0447\u0435\u043d\u0430, +20 \u043e\u0447\u043a\u043e\u0432")
                }
                ), 15e3);
                return () => clearInterval(e)
            }
        }
        ), [u]),
        (0,
        a.useEffect)(( () => {
            j && 0 === A.length && (console.log("Stopping game..."),
            d(Wo.RESULT))
        }
        ), [j, A]),
        (0,
        a.useEffect)(( () => {
            const e = () => {
                (document.hidden || null !== Qo && void 0 !== Qo && Qo.isClosing || !document.hasFocus()) && (u !== Wo.PLAYING || j || (console.log("[Ladybug.Game] > \u0412\u043a\u043b\u0430\u0434\u043a\u0430 \u0441\u0432\u0435\u0440\u043d\u0443\u0442\u0430, \u043e\u0441\u0442\u0430\u043d\u0430\u0432\u043b\u0438\u0432\u0430\u0435\u043c \u0438\u0433\u0440\u0443"),
                N(!0),
                k([]),
                B(0),
                D(0),
                Q(0),
                W(0),
                V(0),
                K(0),
                X(0),
                le(l, 0),
                d(Wo.RESULT)))
            }
            ;
            return document.addEventListener("visibilitychange", e),
            window.addEventListener("blur", e),
            () => {
                document.removeEventListener("visibilitychange", e),
                window.removeEventListener("blur", e)
            }
        }
        ), [u, l, j]),
        (0,
        a.useEffect)(( () => {
            console.log("gameState", u)
        }
        ), [u]),
        (0,
        a.useEffect)(( () => {
            console.log("game user", o)
        }
        ), [o]);
        const oe = pe()
          , ie = (0,
        a.useRef)(O);
        (0,
        a.useEffect)(( () => {
            ie.current = O
        }
        ), [O]),
        (0,
        a.useEffect)(( () => {
            re.current = y
        }
        ), [y]);
        const le = (e, t) => {
            P && V((e => e + (1.5 * t - t))),
            t = P ? 1.5 * t : t,
            co.post("".concat(Tt, "/api/ladybug-game/stop-game"), {
                attempt_id: e,
                score: t,
                hash: o.authToken
            }).then((e => {
                var t, n, r;
                const a = new Date >= new Date("2025-05-12T07:00:00Z");
                var l;
                (console.log("[Ladybug.Game] > stop > hash: ", e),
                console.log("[Ladybug.Game] > stop > coins: " + e.data.game.score + " bonus: " + e.data.game.bonus),
                s(null),
                b(e.data.game.score),
                K(null === e || void 0 === e || null === (t = e.data) || void 0 === t || null === (n = t.game) || void 0 === n ? void 0 : n.squadPoints),
                console.log("updated user", c(c({}, o), {}, {
                    coins: o.coins + e.data.game.score
                })),
                i(c(c({}, o), {}, {
                    coins: o.coins + (a ? 0 : e.data.game.score)
                })),
                null !== e && void 0 !== e && null !== (r = e.data) && void 0 !== r && r.newLeague) && ($(Xo),
                te({
                    type: null === e || void 0 === e || null === (l = e.data) || void 0 === l ? void 0 : l.newLeague
                }))
            }
            )).catch(( () => {
                console.log("[Ladybug.Game] > stop failed")
            }
            ))
        }
          , se = (0,
        a.useRef)(null)
          , ue = (0,
        a.useRef)(!1);
        return (0,
        a.useEffect)(( () => {
            l || (console.log("[Ladybug.Game] > start"),
            console.log("call start"),
            co.post("".concat(Tt, "/api/ladybug-game/start-game"), {
                hash: o.authToken,
                game_mode: Zo[n]
            }).then((e => {
                console.log("[Ladybug.Game] > start > hash: ", e),
                s(e.data.id)
            }
            )),
            Qo.onEvent("viewportChanged", (e => {
                e && !Qo.isExpanded && oe(xt)
            }
            )))
        }
        ), [l]),
        (0,
        a.useEffect)(( () => {
            if (u === Wo.PLAYING && !g) {
                const e = setTimeout(( () => ( () => {
                    let e = Yo.slice();
                    F && (e = e.filter((e => "logoTv3" !== e.code)));
                    const t = e.sort(( () => Math.random() - .5))
                      , n = t[wn().randomInteger(0, t.length - 1)];
                    "logoTv3" === n.code && z(!0),
                    console.log("randomGameItem", n),
                    k((e => [...e, (0,
                    Yt.jsx)(Oo, {
                        speed: p,
                        left: wn().randomInteger(2, 78),
                        image: n.image,
                        coins: n.coins,
                        reset: n.reset,
                        multiplier: ie.current,
                        streak: L,
                        onMissed: () => {
                            Ko.includes(n.code) || (ne && ae(),
                            T(1),
                            U(0),
                            I(!1))
                        }
                        ,
                        onClick: () => {
                            if ("acuma" === n.code) {
                                ue.current && clearTimeout(ue.current.timeout),
                                ue.current = {
                                    timeout: setTimeout(( () => {
                                        ue.current = !1,
                                        f(se.current),
                                        console.log("[Ladybug.Game] > acuma: \u0432\u043e\u0441\u0441\u0442\u0430\u043d\u043e\u0432\u043b\u0435\u043d\u0430 \u0441\u043a\u043e\u0440\u043e\u0441\u0442\u044c.")
                                    }
                                    ), 5e3)
                                },
                                se.current = p;
                                const e = Math.min(2 * p, 10);
                                f(e),
                                console.log("[Ladybug.Game] > acuma: \u0441\u043a\u043e\u0440\u043e\u0441\u0442\u044c x2!"),
                                T(1),
                                U(0),
                                ne && n.loseLive && ae()
                            } else if (ne && n.loseLive && n.reset) {
                                const e = re.current;
                                Q((t => t + e)),
                                b(0),
                                T(1),
                                U(0),
                                setTimeout(( () => {
                                    ae()
                                }
                                ), 50)
                            } else if ("logoTv3" === n.code)
                                B((e => e + n.coins)),
                                D((e => e + (n.coins * ie.current - n.coins))),
                                b((e => e + n.coins * ie.current));
                            else if (n.reset) {
                                const e = re.current;
                                Q((t => t + e)),
                                b(0),
                                T(1),
                                U(0)
                            } else
                                n.freeze ? !1 === g && (v(!0),
                                console.log("[Ladybug.Game] > freeze")) : U((e => {
                                    const t = e + 1
                                      , r = 1 + .5 * Math.floor(t / 5);
                                    return T(r),
                                    b((e => e + n.coins * r)),
                                    W((e => e + n.coins)),
                                    r > 1 && D((e => e + (n.coins * r - n.coins))),
                                    t
                                }
                                ));
                            "tikki" === n.code ? wn().ymReachGoal("ladybug_game_click_kwami_tikki") : "plag" === n.code ? wn().ymReachGoal("ladybug_game_click_kwami_plagg") : "trix" === n.code ? wn().ymReachGoal("ladybug_game_click_kwami_trikks") : "pollen" === n.code ? wn().ymReachGoal("ladybug_game_click_kwami_pollen") : "xuppu" === n.code && wn().ymReachGoal("ladybug_game_click_kwami_shupp")
                        }
                    }, "game_item_" + e.length)]))
                }
                )()), m * (C ? .5 : 1));
                return () => clearTimeout(e)
            }
        }
        ), [u, g, A, C]),
        (0,
        a.useEffect)(( () => {
            !0 === g && window.setTimeout(( () => {
                v(!1),
                console.log("[Ladybug.Game] > unfreeze")
            }
            ), 5e3)
        }
        ), [g]),
        (0,
        a.useEffect)(( () => console.log("[Ladybug.Game] > " + u)), [u]),
        (0,
        Yt.jsx)(_o.Provider, {
            value: {
                multiplier: O,
                streak: L
            },
            children: (0,
            Yt.jsxs)("div", {
                className: "app-game app-game_speed_" + p + "_".concat(n) + " " + "app-game_".concat(n) + " " + (g ? " app-game_freeze" : ""),
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-game--overlay-top"
                }), Wo.GUIDE === u && (0,
                Yt.jsx)(Ro, {
                    gameType: n,
                    onCompleted: () => d(Wo.COUNTDOWN)
                }), Wo.COUNTDOWN === u && (0,
                Yt.jsx)(Lo, {
                    seconds: 3,
                    onStop: () => d(Wo.PLAYING)
                }), [Wo.COUNTDOWN, Wo.PLAYING].includes(u) && (0,
                Yt.jsxs)("header", {
                    className: "app-game--header",
                    children: [Wo.COUNTDOWN === u && (0,
                    Yt.jsx)("div", {
                        className: "app-game-timer",
                        children: Vo[r] ? Vo[r] : ""
                    }), Wo.COUNTDOWN !== u && !ne && (0,
                    Yt.jsx)(Fo, {
                        seconds: r,
                        freeze: g,
                        onEdge: e => {
                            var t;
                            if (50 === e)
                                f(null === (t = Jo[n]) || void 0 === t ? void 0 : t[2]),
                                h(Go[1]),
                                console.log("[Ladybug.Game] > edge ", {
                                    time: e,
                                    speed: 1.5,
                                    respawn: Go[1]
                                });
                            else if (40 === e) {
                                var r;
                                f(null === (r = Jo[n]) || void 0 === r ? void 0 : r[3]),
                                h(Go[2]),
                                console.log("[Ladybug.Game] > edge ", {
                                    time: e,
                                    speed: 1.5,
                                    respawn: Go[2]
                                })
                            } else if (30 === e) {
                                var a;
                                f(null === (a = Jo[n]) || void 0 === a ? void 0 : a[4]),
                                h(Go[3]),
                                console.log("[Ladybug.Game] > edge ", {
                                    time: e,
                                    speed: 2.5,
                                    respawn: Go[3]
                                })
                            } else if (20 === e) {
                                var o;
                                f(null === (o = Jo[n]) || void 0 === o ? void 0 : o[5]),
                                h(Go[4]),
                                console.log("[Ladybug.Game] > edge ", {
                                    time: e,
                                    speed: 3,
                                    respawn: Go[4]
                                })
                            } else if (10 === e) {
                                var i;
                                f(null === (i = Jo[n]) || void 0 === i ? void 0 : i[6]),
                                h(Go[5]),
                                console.log("[Ladybug.Game] > edge ", {
                                    time: e,
                                    speed: 4,
                                    respawn: Go[5]
                                })
                            }
                        }
                        ,
                        onStop: () => {
                            le(l, y),
                            d(Wo.RESULT),
                            f(0)
                        }
                    }), (0,
                    Yt.jsxs)("div", {
                        className: "app-game--info-block",
                        children: [O > 1 && (0,
                        Yt.jsxs)("div", {
                            className: "app-game--combo",
                            children: ["\u041a\u043e\u043c\u0431\u043e: x", O.toFixed(1)]
                        }), 1 === O && (0,
                        Yt.jsx)("div", {
                            className: "app-game--lives"
                        }), (0,
                        Yt.jsx)(mo, {
                            coins: y
                        }), ne && (0,
                        Yt.jsx)(Bo, {
                            lives: S
                        }), !ne && (0,
                        Yt.jsx)("div", {
                            className: "app-game--lives"
                        })]
                    })]
                }), Wo.PLAYING === u && (0,
                Yt.jsx)("div", {
                    className: "app-game--items",
                    children: A.map((e => e))
                }), Wo.RESULT === u && (0,
                Yt.jsx)(To, {
                    result: {
                        logoBonusCoins: M,
                        gameCoins: y,
                        comboCoins: q,
                        resetCoins: H,
                        pureCoins: Y,
                        clearSessionCoins: G,
                        squadCoins: Z,
                        survivalCoins: J
                    },
                    isSurvivalMode: ne,
                    coins: re.current,
                    bonus: x,
                    onRestart: () => (console.log("[Ladybug.Game] > restart"),
                    co.post("".concat(Tt, "/api/ladybug-game/start-game"), {
                        hash: o.authToken,
                        game_mode: Zo[n]
                    }).then((e => {
                        s(e.data.id),
                        f(1),
                        h(Go[0]),
                        v(!1),
                        b(0),
                        Q(0),
                        B(0),
                        D(0),
                        W(0),
                        V(0),
                        X(0),
                        T(1),
                        U(0),
                        I(!0),
                        w(0),
                        k([]),
                        z(!1),
                        d(Wo.COUNTDOWN),
                        N(!1)
                    }
                    )),
                    wn().ymReachGoal("ladybug_game_click_restart"),
                    void E(3))
                }), Xo === _ && (0,
                Yt.jsx)(Ho, c({
                    onClose: () => $(null)
                }, ee))]
            })
        })
    }
      , ti = n.p + "static/media/task-tv3-subscribe.84525edf28a1047dc44b.png";
    class ni {
        static provider() {
            return this.prvdr || (this.prvdr = co.create({
                baseURL: "/8AHbSr"
            })),
            this.prvdr
        }
        static async get(e, t) {
            let n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : {};
            if (!1 === wn().isEmptyObject(t)) {
                const n = new URLSearchParams(t).toString();
                e.indexOf("?") > -1 ? e += "&" + n : e += "?" + n
            }
            return this.provider().get(e, n).then((e => this.parseResponse(e.data))).catch(this.parseErrors)
        }
        static async post(e, t) {
            return this.provider().post(e, t).then((e => this.parseResponse(e.data))).catch(this.parseErrors)
        }
        static async put(e, t) {
            return this.provider().put(e, t).then((e => this.parseResponse(e.data))).catch(this.parseErrors)
        }
        static async patch(e, t) {
            return this.provider().patch(e, t).then((e => this.parseResponse(e.data))).catch(this.parseErrors)
        }
        static delete(e) {
            return this.provider().delete(e).then((e => this.parseResponse(e.data))).catch(this.parseErrors)
        }
        static parseResponse(e) {
            return e && e.success ? e.data : (e && e.errors && e.errors.map((e => {
                console.error(e.message || "Something went wrong \ud83e\udd14")
            }
            )),
            {})
        }
        static parseErrors(e) {
            let {response: t} = e;
            const n = (null === t || void 0 === t ? void 0 : t.data) || {}
              , r = (null === t || void 0 === t ? void 0 : t.status) || -1024;
            let a;
            throw a = n && n.errors ? n.errors.map((e => (e.code = r,
            e))) : 401 === r ? [{
                message: "Please log in to access this section.",
                code: r
            }] : 500 === r ? [{
                message: "Unfortunately, the server was unable to correctly process your request on the server. We are already understanding the problem.",
                code: r
            }] : [{
                message: "Unknown error",
                code: r
            }],
            a
        }
    }
    ni.version = -1,
    ni.prvdr = null;
    const ri = e => {
        let {onClose: t, title: n, photo: r, id: o} = e;
        const [i,l] = (0,
        a.useState)(!1)
          , s = "https://t.me/tv3_day_ladybug_bot?startapp=squad_{squad_id}";
        return (0,
        Yt.jsxs)(ln, {
            title: "\u041a\u043e\u043c\u0430\u043d\u0434\u0430 \u0441\u043e\u0437\u0434\u0430\u043d\u0430!",
            buttonText: "",
            onButtonClick: () => {}
            ,
            onClose: t,
            closed: i,
            type: "dark",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-popup-squad",
                children: [(0,
                Yt.jsx)("img", {
                    src: r || "",
                    alt: "",
                    className: "app-popup-squad--image"
                }), (0,
                Yt.jsx)("div", {
                    className: "app-popup-squad--title",
                    children: n || ""
                }), (0,
                Yt.jsx)("div", {
                    className: "app-popup-squad--description",
                    dangerouslySetInnerHTML: {
                        __html: "\u041a\u0430\u043a \u0442\u043e\u043b\u044c\u043a\u043e \u043a \u0442\u0432\u043e\u0435\u0439 \u043a\u043e\u043c\u0430\u043d\u0434\u0435 \u043f\u0440\u0438\u0441\u043e\u0435\u0434\u0438\u043d\u0438\u0442\u0441\u044f\n          <br /> \u043f\u0435\u0440\u0432\u044b\u0439 \u0438\u0433\u0440\u043e\u043a, \u0442\u0435\u0431\u0435 \u0431\u0443\u0434\u0435\u0442 \u043d\u0430\u0447\u0438\u0441\u043b\u0435\u043d\u043e <span>+5000</span>\n          <br /> \u0431\u0430\u043b\u043b\u043e\u0432, \u0438 \u043a \u0432\u0430\u0448\u0438\u043c \u0438\u0433\u0440\u043e\u0432\u044b\u043c \u0431\u0430\u043b\u043b\u0430\u043c \u043d\u0430\u0447\u043d\u0435\u0442\n          <br /> \u043f\u0440\u0438\u043c\u0435\u043d\u044f\u0442\u044c\u0441\u044f \u043c\u043d\u043e\u0436\u0438\u0442\u0435\u043b\u044c \u043a\u043e\u043c\u0430\u043d\u0434\u044b"
                    }
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-popup-squad--actions-wrapper",
                children: [(0,
                Yt.jsx)(Wt, {
                    onClick: () => {
                        window.Telegram.WebApp.openTelegramLink("https://t.me/share/url?url=" + s.replace("{squad_id}", o) + "&text=" + encodeURIComponent("\u0421\u043a\u043e\u0440\u0435\u0435 \u0432\u0441\u0442\u0443\u043f\u0430\u0439 \u0432 \u043c\u043e\u044e \u043a\u043e\u043c\u0430\u043d\u0434\u0443 \u0438 \u043f\u043e\u043c\u043e\u0433\u0438 \u043c\u043d\u0435 \u0437\u0430\u0440\u0430\u0431\u043e\u0442\u0430\u0442\u044c \u0431\u0430\u043b\u043b\u044b! \ud83d\ude09\ud83d\udc1e"))
                    }
                    ,
                    children: "\u041f\u0440\u0438\u0433\u043b\u0430\u0441\u0438\u0442\u044c \u0434\u0440\u0443\u0433\u0430"
                }), (0,
                Yt.jsx)(Wt, {
                    variant: "fit",
                    onClick: () => {
                        navigator.clipboard.writeText(s.replace("{squad_id}", o)),
                        wn().showAlert("\u0421\u0441\u044b\u043b\u043a\u0430 \u0441\u043a\u043e\u043f\u0438\u0440\u043e\u0432\u0430\u043d\u0430 \u0438 \u0435\u0451 \u043c\u043e\u0436\u043d\u043e \u043e\u0442\u043f\u0440\u0430\u0432\u0438\u0442\u044c \u0434\u0440\u0443\u0433\u0443!"),
                        l(!0),
                        window.setTimeout(( () => t()), 200)
                    }
                    ,
                    children: (0,
                    Yt.jsx)("svg", {
                        width: "16",
                        height: "16",
                        viewBox: "0 0 16 16",
                        fill: "none",
                        xmlns: "http://www.w3.org/2000/svg",
                        children: (0,
                        Yt.jsx)("path", {
                            d: "M2.66665 1.33337C1.92998 1.33337 1.33331 1.93004 1.33331 2.66671V11.3334C1.33331 11.7014 1.63198 12 1.99998 12C2.36798 12 2.66665 11.7014 2.66665 11.3334V2.66671H11.3333C11.7013 2.66671 12 2.36804 12 2.00004C12 1.63204 11.7013 1.33337 11.3333 1.33337H2.66665ZM5.33331 4.00004C4.59665 4.00004 3.99998 4.59671 3.99998 5.33337V13.3334C3.99998 14.07 4.59665 14.6667 5.33331 14.6667H13.3333C14.07 14.6667 14.6666 14.07 14.6666 13.3334V5.33337C14.6666 4.59671 14.07 4.00004 13.3333 4.00004H5.33331ZM5.33331 5.33337H13.3333V13.3334H5.33331V5.33337Z",
                            fill: "white"
                        })
                    })
                })]
            })]
        })
    }
      , ai = {
        1: n.p + "static/media/squad-1.4f43ac3b20dd41d699ff.png",
        2: n.p + "static/media/squad-2.cc7b27f6c350366e65f4.png",
        3: n.p + "static/media/squad-3.c715ecc7c57e4cc016de.png",
        4: n.p + "static/media/squad-4.af648e1e4c237a5ce87f.png",
        5: n.p + "static/media/squad-5.86ef8181cfe6b38ba207.png",
        6: n.p + "static/media/squad-6.17ea84b6c9253fabf001.png",
        7: n.p + "static/media/squad-7.5870b9b295f0430c3495.png",
        8: n.p + "static/media/squad-8.9fd297b676b2d0d2fea2.png",
        9: n.p + "static/media/squad-9.b6aca7cd92cd37f5adf5.png",
        10: n.p + "static/media/squad-10.66e8df3fc5fb120595db.png",
        11: n.p + "static/media/squad-11.81301cc7907ddcdd1cf6.png",
        12: n.p + "static/media/squad-12.af9c95e949562373f3ad.png"
    }
      , oi = e => {
        let {user: t, getDailyBonus: n, onClose: r} = e;
        return (0,
        Yt.jsx)(ln, {
            buttonText: "\u041f\u043e\u043d\u044f\u0442\u043d\u043e",
            onButtonClick: () => {
                n(),
                r()
            }
            ,
            onClose: r,
            children: (0,
            Yt.jsx)("div", {
                className: "app-popup-task-emoji",
                children: (0,
                Yt.jsxs)("div", {
                    className: "app-popup--description",
                    children: ["\u0417\u0430\u0445\u043e\u0434\u0438 \u0432 \u0438\u0433\u0440\u0443 \u043a\u0430\u0436\u0434\u044b\u0439 \u0434\u0435\u043d\u044c", (0,
                    Yt.jsx)("br", {}), " \u0438 \u043f\u043e\u043b\u0443\u0447\u0430\u0439", " ", (0,
                    Yt.jsx)("strong", {
                        children: (0,
                        Yt.jsx)("span", {
                            children: "+500 \u0431\u0430\u043b\u043b\u043e\u0432!"
                        })
                    })]
                })
            })
        })
    }
      , ii = "task_emoji"
      , li = "task_invite"
      , si = "task_qr"
      , ui = "task_kwami_qr"
      , ci = "task_result"
      , di = "task_trailer"
      , pi = "task_squad"
      , fi = "task_daily"
      , mi = "yes" === document.getElementById("root").dataset.gameOver
      , hi = e => {
        var t, n, r, a, o;
        return {
            code: null === e || void 0 === e ? void 0 : e.code,
            isAxiosError: null === e || void 0 === e ? void 0 : e.isAxiosError,
            response: {
                data: null === e || void 0 === e || null === (t = e.response) || void 0 === t ? void 0 : t.data,
                status: null === e || void 0 === e || null === (n = e.response) || void 0 === n ? void 0 : n.status,
                statusText: null === e || void 0 === e || null === (r = e.response) || void 0 === r ? void 0 : r.statusText
            },
            message: (null === e || void 0 === e || null === (a = e.response) || void 0 === a || null === (o = a.data) || void 0 === o ? void 0 : o.message) || (null === e || void 0 === e ? void 0 : e.message),
            stack: null === e || void 0 === e ? void 0 : e.stack
        }
    }
      , gi = e => {
        var t, n, r, o, i, l, s, u, d, p, f;
        let {startParamValue: m} = e;
        console.log({
            gameOver: mi
        });
        const {user: h={}, setUser: g} = Sn()
          , [v,y] = (0,
        a.useState)(null)
          , [b,x] = (0,
        a.useState)(null)
          , [w,A] = (0,
        a.useState)(m || null)
          , [k,S] = (0,
        a.useState)(m || null)
          , [E,j] = (0,
        a.useState)(!1)
          , N = (ue(),
        pe())
          , C = +(null === h || void 0 === h || null === (t = h.squad) || void 0 === t || null === (n = t.creator) || void 0 === n ? void 0 : n.telegram_user_id) === +(null === h || void 0 === h ? void 0 : h.telegram_id);
        console.log("isOwnerOfSquad", C);
        (0,
        a.useEffect)(( () => {
            console.log("[Ladybug.Home] > ready"),
            wn().ymReachGoal("ladybug_game_view_home")
        }
        ), []),
        (0,
        a.useEffect)(( () => {
            const e = new Date("2025-05-12T09:00:00Z")
              , t = new Date;
            j(t < e)
        }
        ), []),
        (0,
        a.useEffect)(( () => {
            w && (console.log("[Ladybug.StartParam] > " + w),
            co.post("".concat(Tt, "/api/qr/").concat(w), {
                hash: h.authToken
            }).then((e => {
                var t, n, r;
                (console.log("[Ladybug.StartParam] > win: " + (null === e || void 0 === e ? void 0 : e.reason) + " " + (null === e || void 0 === e ? void 0 : e.score)),
                null !== e && void 0 !== e && null !== (t = e.data) && void 0 !== t && t.coins) && (x({
                    success: !0,
                    text: "<strong>QR-\u043a\u043e\u0434 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043d!</br>\u0422\u044b \u043f\u043e\u043b\u0443\u0447\u0430\u0435\u0448\u044c +<span>".concat(null === e || void 0 === e || null === (n = e.data) || void 0 === n ? void 0 : n.coins, "&nbsp;\u0431\u0430\u043b\u043b\u043e\u0432!</span></strong>"),
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                y(ci),
                g(c(c({}, h), {}, {
                    coins: h.coins + (null === e || void 0 === e || null === (r = e.data) || void 0 === r ? void 0 : r.coins)
                })))
            }
            )).catch((e => {
                var t;
                console.log("[Ladybug.Invite] > fail", e);
                const n = hi(e);
                console.log('response?.data?.message === "QR already activated by this user"', "QR already activated by this user" === (null === n || void 0 === n || null === (t = n.data) || void 0 === t ? void 0 : t.message)),
                console.log("response?.data", n),
                "QR already activated by this user" === (null === n || void 0 === n ? void 0 : n.message) && (x({
                    success: !0,
                    text: "<strong>\u0422\u044b \u0443\u0436\u0435 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043b \u044d\u0442\u043e\u0442 QR-\u043a\u043e\u0434 \u0438<br/> \u043f\u043e\u043b\u0443\u0447\u0438\u043b \u0437\u0430 \u043d\u0435\u0433\u043e \u0431\u0430\u043b\u043b\u044b!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                y(ci)),
                "Invalid QR" === (null === n || void 0 === n ? void 0 : n.message) && (x({
                    success: !1,
                    text: "<strong>\u041e\u0439, \u044d\u0442\u043e \u043d\u0435\u0432\u0435\u0440\u043d\u044b\u0439 QR-\u043a\u043e\u0434 ;(<br/>\u041f\u043e\u043f\u0440\u043e\u0431\u0443\u0439 \u0435\u0449\u0435 \u0440\u0430\u0437!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                y(ci))
            }
            )))
        }
        ), [w]),
        (0,
        a.useEffect)(( () => {
            k && (console.log("[Ladybug.StartParam] > " + k),
            co.post("".concat(Tt, "/api/tasks/help-kvami}"), {
                hash: h.authToken,
                task_type: k
            }).then((e => {
                var t, n, r;
                (console.log("[Ladybug.StartParam] > win: " + (null === e || void 0 === e ? void 0 : e.reason) + " " + (null === e || void 0 === e ? void 0 : e.score)),
                null !== e && void 0 !== e && null !== (t = e.data) && void 0 !== t && t.coins) && (x({
                    success: !0,
                    text: "<strong>QR-\u043a\u043e\u0434 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043d!</br>\u0422\u044b \u043f\u043e\u043b\u0443\u0447\u0430\u0435\u0448\u044c +<span>".concat(null === e || void 0 === e || null === (n = e.data) || void 0 === n ? void 0 : n.coins, "&nbsp;\u0431\u0430\u043b\u043b\u043e\u0432!</span></strong>"),
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                y(ci),
                g(c(c({}, h), {}, {
                    coins: h.coins + (null === e || void 0 === e || null === (r = e.data) || void 0 === r ? void 0 : r.coins)
                })))
            }
            )).catch((e => {
                console.log("[Ladybug.Invite] > fail", e);
                const t = hi(e);
                "Task already activated" === (null === t || void 0 === t ? void 0 : t.message) && (x({
                    success: !0,
                    text: "<strong>\u0422\u044b \u0443\u0436\u0435 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043b \u044d\u0442\u043e\u0442 QR-\u043a\u043e\u0434 \u0438<br/> \u043f\u043e\u043b\u0443\u0447\u0438\u043b \u0437\u0430 \u043d\u0435\u0433\u043e \u0431\u0430\u043b\u043b\u044b!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                y(ci)),
                "Invalid QR" === (null === t || void 0 === t ? void 0 : t.message) && (x({
                    success: !1,
                    text: "<strong>\u041e\u0439, \u044d\u0442\u043e \u043d\u0435\u0432\u0435\u0440\u043d\u044b\u0439 QR-\u043a\u043e\u0434 ;(<br/>\u041f\u043e\u043f\u0440\u043e\u0431\u0443\u0439 \u0435\u0449\u0435 \u0440\u0430\u0437!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                y(ci))
            }
            )))
        }
        ), [k]),
        console.log({
            finalBannerVisible: mi
        }),
        console.log("user", h);
        const R = () => {
            co.post("".concat(Tt, "/api/tasks/daily-bonus"), {
                hash: null === h || void 0 === h ? void 0 : h.authToken
            }).then((e => {
                var t;
                g(c(c({}, h), {}, {
                    coins: null === e || void 0 === e || null === (t = e.data) || void 0 === t ? void 0 : t.score,
                    tasks: [...null === h || void 0 === h ? void 0 : h.tasks, "daily_bonus"]
                }))
            }
            ))
        }
        ;
        return (0,
        Yt.jsxs)("div", {
            className: "app-home app-hide-scroll",
            children: [E ? (0,
            Yt.jsx)($t, {}) : (0,
            Yt.jsx)(nn, {}), (0,
            Yt.jsx)(cn, {
                photo: (null === h || void 0 === h ? void 0 : h.photo) || null,
                coins: null === h || void 0 === h ? void 0 : h.coins,
                subscribed: null === h || void 0 === h ? void 0 : h.chatMember
            }), (0,
            Yt.jsx)(Wt, {
                onClick: () => {
                    wn().ymReachGoal("ladybug_game_click_start_game"),
                    N(St)
                }
                ,
                children: "\u0418\u0433\u0440\u0430\u0442\u044c"
            }), (0,
            Yt.jsx)("a", {
                target: "_blank",
                className: "app-home--about-game-link",
                href: "https://telegra.ph/CHasto-zadavaemye-voprosy-po-igre-Lovi-kvami-09-20",
                children: (0,
                Yt.jsxs)("div", {
                    className: "app-home--about-game",
                    children: [(0,
                    Yt.jsx)("img", {
                        src: "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAARCAYAAAA7bUf6AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAADbSURBVHgBzZThEYMgDIWD/x1ABnABF+gAdQAW6DTtHAzQrsEaOoAD0DwvvSoGtP3lu+NyB/HjCQmGEsUYaw6OdI08gjFmWE6aBICPAfGcOCkbWA5XwHj9SUqC49HRASFPNlxN9hqA51oed8QSqBKLDdsLyqYAXySuJPn1fIbiwlLeeltYA+RWiYshkwS7j83/f93Mh19RWbipRmJWe5BDOhlESv1nya2OgHjK98qe0ALhQ3SZikUdWM2pVGyfTv7dO2kXg4y6eGkFuHgmJl73KkQScVidwDRtnok3+pyRKtBR6AMAAAAASUVORK5CYII=",
                        alt: ""
                    }), "\u041e\u0431 \u0438\u0433\u0440\u0435"]
                })
            }), (0,
            Yt.jsxs)("div", {
                className: "app-home--tasks",
                children: [(0,
                Yt.jsx)("h2", {
                    children: "\u0417\u0430\u0434\u0430\u043d\u0438\u044f"
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u0417\u0430\u0445\u043e\u0434\u0438 \u0432 \u0438\u0433\u0440\u0443",
                    coins: zt,
                    completed: null === h || void 0 === h || null === (r = h.tasks) || void 0 === r ? void 0 : r.includes("daily_bonus"),
                    onClick: () => {
                        var e;
                        null !== h && void 0 !== h && null !== (e = h.tasks) && void 0 !== e && e.includes("daily_bonus") || (y(fi),
                        x({
                            getDailyBonus: R
                        }))
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u0418\u0437\u043c\u0435\u043d\u0438 \u0438\u043c\u044f",
                    coins: Lt,
                    completed: null === h || void 0 === h || null === (o = h.tasks) || void 0 === o ? void 0 : o.includes("name"),
                    onClick: () => {
                        var e;
                        !1 === (null === h || void 0 === h || null === (e = h.tasks) || void 0 === e ? void 0 : e.includes("name")) && y(ii)
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u041d\u0430\u0439\u0434\u0438 \u043a\u043e\u0434 \u0432 \u0432\u0438\u0434\u0435\u043e",
                    coins: It,
                    completed: null === h || void 0 === h || null === (i = h.tasks) || void 0 === i ? void 0 : i.includes("trailer"),
                    onClick: () => {
                        var e;
                        !1 === (null === h || void 0 === h || null === (e = h.tasks) || void 0 === e ? void 0 : e.includes("trailer")) && (wn().ymReachGoal("ladybug_game_trailer_view"),
                        y(di))
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: ti,
                    title: "\u041f\u043e\u0434\u043f\u0438\u0448\u0438\u0441\u044c \u043d\u0430 \u043a\u0430\u043d\u0430\u043b \u0422\u0412-3",
                    coins: Pt,
                    completed: null === h || void 0 === h || null === (l = h.tasks) || void 0 === l ? void 0 : l.includes("subscription"),
                    onClick: () => {
                        var e;
                        !1 === (null === h || void 0 === h || null === (e = h.tasks) || void 0 === e ? void 0 : e.includes("subscription")) && (x({
                            success: !1,
                            title: "\u041f\u043e\u0434\u043f\u0438\u0441\u0430\u0442\u044c\u0441\u044f \u043d\u0430 \u043a\u0430\u043d\u0430\u043b",
                            text: '\u0421\u043a\u043e\u0440\u0435\u0435 \u043f\u043e\u0434\u043f\u0438\u0448\u0438\u0441\u044c<br/> \u043d\u0430 \u043d\u0430\u0448 \u043a\u0430\u043d\u0430\u043b <a href="https://t.me/tv3russia">@tv3russia</a>!'
                        }),
                        y(ci))
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u0421\u043e\u0437\u0434\u0430\u0439 \u043a\u043e\u043c\u0430\u043d\u0434\u0443",
                    coins: Mt,
                    completed: null === h || void 0 === h || null === (s = h.tasks) || void 0 === s ? void 0 : s.includes("squad"),
                    onClick: null !== h && void 0 !== h && null !== (u = h.tasks) && void 0 !== u && u.includes("squad") ? () => {}
                    : C ? () => {
                        var e, t, n;
                        y(pi),
                        x({
                            title: null === h || void 0 === h || null === (e = h.squad) || void 0 === e ? void 0 : e.name,
                            photo: ai[null === h || void 0 === h || null === (t = h.squad) || void 0 === t ? void 0 : t.photo_id],
                            id: null === h || void 0 === h || null === (n = h.squad) || void 0 === n ? void 0 : n.id
                        })
                    }
                    : () => N(Ct)
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u0421\u043a\u0430\u043d\u0438\u0440\u0443\u0439 QR-\u043a\u043e\u0434\u044b 3 \u043c\u0430\u044f",
                    coins: Ft,
                    onClick: () => {
                        wn().ymReachGoal("ladybug_game_click_invite_friends"),
                        y(si),
                        x({
                            type: "qr"
                        })
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u041f\u043e\u043c\u043e\u0433\u0438 \u043a\u0432\u0430\u043c\u0438 \xab\u0421\u043b\u0435\u043f\u043e\u0439\xbb",
                    coins: Bt,
                    completed: null === h || void 0 === h || null === (d = h.tasks) || void 0 === d ? void 0 : d.includes("qr_slepoi"),
                    onClick: () => {
                        var e;
                        !1 === (null === h || void 0 === h || null === (e = h.tasks) || void 0 === e ? void 0 : e.includes("qr_slepoi")) && (wn().ymReachGoal("ladybug_game_click_invite_friends"),
                        y(ui),
                        x({
                            type: "qr_slepoi"
                        }))
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u041f\u043e\u043c\u043e\u0433\u0438 \u043a\u0432\u0430\u043c\u0438 \xab\u041b\u0435\u0441\u043d\u0438\u043a\u0430\xbb",
                    coins: Bt,
                    completed: null === h || void 0 === h || null === (p = h.tasks) || void 0 === p ? void 0 : p.includes("qr_lesnik"),
                    onClick: () => {
                        var e;
                        !1 === (null === h || void 0 === h || null === (e = h.tasks) || void 0 === e ? void 0 : e.includes("qr_lesnik")) && (wn().ymReachGoal("ladybug_game_click_invite_friends"),
                        y(ui),
                        x({
                            type: "qr_lesnik"
                        }))
                    }
                }), (0,
                Yt.jsx)(mn, {
                    image: "data:image/png;base64,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",
                    title: "\u041f\u043e\u043c\u043e\u0433\u0438 \u043a\u0432\u0430\u043c\u0438 \xab\u0413\u0430\u0434\u0430\u043b\u043e\u043a\xbb",
                    coins: Bt,
                    completed: null === h || void 0 === h || null === (f = h.tasks) || void 0 === f ? void 0 : f.includes("qr_gadalok"),
                    onClick: () => {
                        var e;
                        !1 === (null === h || void 0 === h || null === (e = h.tasks) || void 0 === e ? void 0 : e.includes("qr_gadalok")) && (wn().ymReachGoal("ladybug_game_click_invite_friends"),
                        y(ui),
                        x({
                            type: "qr_gadalok"
                        }))
                    }
                })]
            }), (0,
            Yt.jsx)(Kt, {}), ii === v && (0,
            Yt.jsx)(xn, {
                user: h,
                onCheck: () => (console.log("[Ladybug.Emoji] > check"),
                void co.post("".concat(Tt, "/api/tasks/name"), {
                    hash: h.authToken
                }).then((e => {
                    h.coins = e.coins,
                    h.tasks.push("name"),
                    g(h),
                    console.log("[Ladybug.Emoji] > win: " + (null === e || void 0 === e ? void 0 : e.reason) + " " + (null === e || void 0 === e ? void 0 : e.score)),
                    x({
                        success: !0,
                        title: "\u0418\u0437\u043c\u0435\u043d\u0438 \u0441\u0432\u043e\u0435 \u0438\u043c\u044f",
                        text: "+<strong><span>".concat(e.coins, "&nbsp;\u0431\u0430\u043b\u043b\u043e\u0432</span> \u0443\u0436\u0435 \u043d\u0430 \u0442\u0432\u043e\u0451\u043c \u0441\u0447\u0451\u0442\u0435!</strong>")
                    }),
                    y(ci)
                }
                )).catch((e => {
                    console.log("[Ladybug.Emoji] > fail"),
                    x({
                        success: !1,
                        title: "\u0418\u0437\u043c\u0435\u043d\u0438 \u0441\u0432\u043e\u0435 \u0438\u043c\u044f",
                        text: "\u0425\u043c\u043c... \u041d\u0435 \u043f\u043e\u043b\u0443\u0447\u0438\u043b\u043e\u0441\u044c \u043d\u0430\u0439\u0442\u0438 \u0444\u0440\u0430\u0437\u0443 \xab\ud83d\udc1e \u043d\u0430 \u0422\u0412-3\xbb<br/> \u0432 \u0438\u043c\u0435\u043d\u0438 \u0442\u0432\u043e\u0435\u0433\u043e \u043f\u0440\u043e\u0444\u0438\u043b\u044f"
                    }),
                    y(ci)
                }
                ))),
                onClose: () => y(null)
            }), li === v && (0,
            Yt.jsx)(Cn, {
                onClose: () => y(null)
            }), si === v && (0,
            Yt.jsx)(Pn, c({
                onQrRead: e => A(e),
                onClose: () => {
                    y(null),
                    x(null)
                }
            }, b)), ui === v && (0,
            Yt.jsx)(Pn, c({
                onQrRead: e => S(e),
                onClose: () => {
                    y(null),
                    x(null)
                }
                ,
                isKwamiTask: !0
            }, b)), ci === v && (0,
            Yt.jsx)(Mn, c({
                success: b.success,
                title: b.title,
                text: b.text,
                onClose: () => {
                    y(null),
                    x(null)
                }
            }, b)), di === v && (0,
            Yt.jsx)(Bn, {
                onCheck: e => {
                    return t = e,
                    console.log("[Ladybug.Trailer] > check"),
                    void co.post("".concat(Tt, "/api/tasks/trailer"), {
                        hash: h.authToken,
                        code: t
                    }).then((e => {
                        new Date >= new Date("2025-05-12T07:00:00Z") && null !== e && void 0 !== e && e.data && (e.data.coins = h.coins,
                        e.data.score = 0),
                        console.log("trailer res", e),
                        h.coins = e.data.coins,
                        h.tasks.push("trailer"),
                        g(h),
                        console.log("[Ladybug.Trailer] > win: " + (null === e || void 0 === e ? void 0 : e.data.reason) + " " + (null === e || void 0 === e ? void 0 : e.data.score)),
                        x({
                            success: !0,
                            title: "\u0412\u0438\u0434\u0435\u043e",
                            text: "+<strong><span>".concat(e.data.score, "&nbsp;\u0431\u0430\u043b\u043b\u043e\u0432</span> \u0443\u0436\u0435 \u043d\u0430 \u0442\u0432\u043e\u0451\u043c \u0441\u0447\u0451\u0442\u0435!</strong>")
                        }),
                        y(ci)
                    }
                    )).catch((e => {
                        console.log("[Ladybug.Trailer] > fail"),
                        x({
                            success: !1,
                            title: "\u0412\u0438\u0434\u0435\u043e",
                            text: "\u0425\u043c\u043c... \u042d\u0442\u043e \u043d\u0435\u0432\u0435\u0440\u043d\u044b\u0439 \u043a\u043e\u0434.<br/> \u041f\u043e\u0441\u043c\u043e\u0442\u0440\u0438 \u0435\u0449\u0451 \u0440\u0430\u0437 \u043e\u0447\u0435\u043d\u044c \u0432\u043d\u0438\u043c\u0430\u0442\u0435\u043b\u044c\u043d\u043e."
                        }),
                        y(ci)
                    }
                    ));
                    var t
                }
                ,
                onClose: () => y(null)
            }), pi === v && (0,
            Yt.jsx)(ri, c({
                onClose: () => y(null)
            }, b)), fi === v && (0,
            Yt.jsx)(oi, c({
                onClose: () => y(null)
            }, b))]
        })
    }
      , vi = n.p + "static/media/new-intro-bg.fb2b99d77108b5432994.png"
      , yi = n.p + "static/media/new-intro-logo.72939229597257de8a48.png"
      , bi = e => {
        let {error: t, isChatMember: n, shouldNotReload: r} = e;
        const o = pe()
          , [i,l] = (0,
        a.useState)(!1);
        return (0,
        a.useEffect)(( () => {
            ( () => {
                const e = new Date
                  , t = new Date(2025,4,3,0,0,0);
                l(e >= t)
            }
            )()
        }
        ), []),
        (0,
        a.useEffect)(( () => wn().ymReachGoal("ladybug_game_view_intro")), []),
        (0,
        a.useEffect)(( () => {
            !1 === t ? (console.log("[Ladybug.Intro] > ready"),
            window.setTimeout(( () => {
                const e = new URLSearchParams(window.location.search);
                e.set("shouldReload", "true"),
                r ? o("/home?".concat(e.toString())) : window.location.href = "/home?".concat(e.toString())
            }
            ), 1234)) : console.error("[Ladybug.Intro] > not ready")
        }
        ), [t, o]),
        (0,
        Yt.jsxs)("div", {
            className: "app-intro",
            children: [(0,
            Yt.jsx)("img", {
                src: vi,
                alt: "",
                className: "app-intro--ball"
            }), (0,
            Yt.jsx)("div", {
                className: "app-intro--overlay-top"
            }), (0,
            Yt.jsx)("div", {
                className: "app-intro--overlay-bottom"
            }), (0,
            Yt.jsx)("img", {
                src: yi,
                alt: "",
                className: "app-intro--logo-title"
            }), (0,
            Yt.jsx)("img", {
                src: i ? "data:image/png;base64,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" : "data:image/png;base64,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",
                alt: "",
                className: "app-intro--logo-tv3 ".concat(i ? "" : "date")
            }), !t && (0,
            Yt.jsx)("div", {
                className: "app-intro--progressbar",
                children: (0,
                Yt.jsx)("div", {})
            }), !t && (0,
            Yt.jsx)("img", {
                src: "data:image/png;base64,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",
                alt: "",
                className: "app-intro--kidsme"
            }), t && (0,
            Yt.jsx)("div", {
                className: "app-intro--error",
                children: "\u0425\u043c\u043c... \u0427\u0442\u043e-\u0442\u043e \u043f\u043e\u0448\u043b\u043e \u043d\u0435 \u0442\u0430\u043a \ud83e\udd14"
            })]
        })
    }
      , xi = n.p + "static/media/rating-prize-1.29893e1cd2ff7c76ab7a.png"
      , wi = n.p + "static/media/rating-prize-2.87c1a90dd09e002964c6.png"
      , Ai = () => (0,
    Yt.jsxs)("article", {
        className: "app-rating-prize app-rating-prize_1",
        children: [(0,
        Yt.jsx)("header", {
            className: "app-rating-prize--header",
            children: "1 - 3 \u043c\u0435\u0441\u0442\u043e"
        }), (0,
        Yt.jsxs)("figure", {
            className: "app-rating-prize--figure",
            children: [(0,
            Yt.jsxs)("svg", {
                className: "app-rating-prize--ellipse-1",
                width: "126",
                height: "45",
                viewBox: "0 0 126 45",
                fill: "none",
                xmlns: "http://www.w3.org/2000/svg",
                children: [(0,
                Yt.jsx)("ellipse", {
                    cx: "63",
                    cy: "22.5",
                    rx: "63",
                    ry: "22.5",
                    fill: "url(#paint0_linear_3546_1178)"
                }), (0,
                Yt.jsx)("defs", {
                    children: (0,
                    Yt.jsxs)("linearGradient", {
                        id: "paint0_linear_3546_1178",
                        x1: "28",
                        y1: "18.5",
                        x2: "126",
                        y2: "35",
                        gradientUnits: "userSpaceOnUse",
                        children: [(0,
                        Yt.jsx)("stop", {
                            stopColor: "#BC5EFF"
                        }), (0,
                        Yt.jsx)("stop", {
                            offset: "1",
                            stopColor: "#FF0084"
                        })]
                    })
                })]
            }), (0,
            Yt.jsxs)("svg", {
                className: "app-rating-prize--circle-1",
                width: "78",
                height: "78",
                viewBox: "0 0 78 78",
                fill: "none",
                xmlns: "http://www.w3.org/2000/svg",
                children: [(0,
                Yt.jsx)("circle", {
                    cx: "39",
                    cy: "39",
                    r: "39",
                    fill: "url(#paint0_linear_3563_1115)"
                }), (0,
                Yt.jsx)("defs", {
                    children: (0,
                    Yt.jsxs)("linearGradient", {
                        id: "paint0_linear_3563_1115",
                        x1: "17.3333",
                        y1: "32.0667",
                        x2: "79.495",
                        y2: "35.8045",
                        gradientUnits: "userSpaceOnUse",
                        children: [(0,
                        Yt.jsx)("stop", {
                            stopColor: "#DFB4FE"
                        }), (0,
                        Yt.jsx)("stop", {
                            offset: "1",
                            stopColor: "#FC75BB"
                        })]
                    })
                })]
            }), (0,
            Yt.jsx)("img", {
                src: xi,
                alt: "",
                className: "app-rating-prize--image app-rating-prize--image_1"
            })]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-rating-prize--description",
            children: ["\u041d\u0430\u0443\u0448\u043d\u0438\u043a\u0438 \u041c\u0430\u0440\u0448\u0430\u043b", (0,
            Yt.jsx)("br", {}), "\u042d\u043d\u0446\u0438\u043a\u043b\u043e\u043f\u0435\u0434\u0438\u044f", (0,
            Yt.jsx)("br", {}), "\u041a\u0430\u043b\u0435\u043d\u0434\u0430\u0440\u044c", (0,
            Yt.jsx)("br", {}), "\u041a\u043e\u043c\u0438\u043a\u0441", (0,
            Yt.jsx)("br", {}), "\u041a\u043d\u0438\u0433\u0430 \u0410\u043d\u0430\u043d\u0441\u0438", (0,
            Yt.jsx)("br", {}), "\u041a\u0443\u043b\u043e\u043d"]
        })]
    })
      , ki = () => (0,
    Yt.jsxs)("article", {
        className: "app-rating-prize app-rating-prize_2",
        children: [(0,
        Yt.jsx)("header", {
            className: "app-rating-prize--header",
            children: "4 - 10 \u043c\u0435\u0441\u0442\u043e"
        }), (0,
        Yt.jsxs)("figure", {
            className: "app-rating-prize--figure",
            children: [(0,
            Yt.jsxs)("svg", {
                className: "app-rating-prize--ellipse-2",
                width: "126",
                height: "82",
                viewBox: "0 0 126 82",
                fill: "none",
                xmlns: "http://www.w3.org/2000/svg",
                children: [(0,
                Yt.jsx)("ellipse", {
                    cx: "63",
                    cy: "41",
                    rx: "63",
                    ry: "41",
                    fill: "url(#paint0_linear_3546_1274)"
                }), (0,
                Yt.jsx)("defs", {
                    children: (0,
                    Yt.jsxs)("linearGradient", {
                        id: "paint0_linear_3546_1274",
                        x1: "28",
                        y1: "33.7111",
                        x2: "127.925",
                        y2: "42.9438",
                        gradientUnits: "userSpaceOnUse",
                        children: [(0,
                        Yt.jsx)("stop", {
                            stopColor: "#BC5EFF"
                        }), (0,
                        Yt.jsx)("stop", {
                            offset: "1",
                            stopColor: "#00FFF7"
                        })]
                    })
                })]
            }), (0,
            Yt.jsx)("img", {
                src: wi,
                alt: "",
                className: "app-rating-prize--image app-rating-prize--image_2"
            })]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-rating-prize--description",
            children: ["\u042f\u043d\u0434\u0435\u043a\u0441 \u0421\u0442\u0430\u043d\u0446\u0438\u044f \u041b\u0430\u0439\u0442", (0,
            Yt.jsx)("br", {}), "\u041a\u043d\u0438\u0433\u0430 \u0410\u043d\u0430\u043d\u0441\u0438", (0,
            Yt.jsx)("br", {}), "\u041a\u043e\u043c\u0438\u043a\u0441", (0,
            Yt.jsx)("br", {}), "\u041a\u0443\u043b\u043e\u043d"]
        })]
    })
      , Si = () => (0,
    Yt.jsxs)("article", {
        className: "app-rating-prize app-rating-prize_3",
        children: [(0,
        Yt.jsxs)("header", {
            className: "app-rating-prize--header app-rating-prize--header_small",
            children: ["10 \u0441\u043b\u0443\u0447\u0430\u0439\u043d\u044b\u0445 \u0438\u0433\u0440\u043e\u043a\u043e\u0432,", (0,
            Yt.jsx)("br", {}), "\u043f\u0440\u0438\u0433\u043b\u0430\u0441\u0438\u0432\u0448\u0438\u0445", (0,
            Yt.jsx)("br", {}), "\u0442\u0440\u0451\u0445 \u0438 \u0431\u043e\u043b\u0435\u0435 \u0434\u0440\u0443\u0437\u0435\u0439"]
        }), (0,
        Yt.jsxs)("div", {
            className: "app-rating-prize--description",
            children: ["\u042d\u043d\u0446\u0438\u043a\u043b\u043e\u043f\u0435\u0434\u0438\u044f", (0,
            Yt.jsx)("br", {}), "\u041a\u043e\u043c\u0438\u043a\u0441", (0,
            Yt.jsx)("br", {}), "\u041a\u0443\u043b\u043e\u043d"]
        })]
    })
      , Ei = window.Telegram.WebApp
      , ji = e => {
        let {onClick: t} = e;
        return (0,
        Yt.jsx)("svg", {
            className: "app-rating--back",
            onClick: () => t(),
            width: "24",
            height: "24",
            viewBox: "0 0 24 24",
            fill: "none",
            xmlns: "http://www.w3.org/2000/svg",
            children: (0,
            Yt.jsx)("path", {
                d: "M15 18L9 12L15 6",
                stroke: "#9E9E9E",
                strokeWidth: "1.6"
            })
        })
    }
      , Ni = () => {
        const {user: e} = Sn()
          , [t,n] = (0,
        a.useState)(!1)
          , [r,o] = (0,
        a.useState)([])
          , [i,l] = (0,
        a.useState)(null);
        (0,
        a.useEffect)(( () => {
            wn().ymReachGoal("ladybug_game_view_rating"),
            console.log("[Ladybug.Rating] > ready"),
            co.post("".concat(Tt, "/api/ladybug-game/rating"), {
                hash: e.authToken
            }).then((e => {
                console.log("rating response", e);
                let t = 0;
                e.data.map((e => {
                    t += e.score,
                    e.active && l(e)
                }
                )),
                o(e.data)
            }
            ))
        }
        ), []),
        (0,
        a.useEffect)(( () => {
            console.log("rating users", r)
        }
        ), [r]);
        const s = e => "db2c6e86-fdf6-44cb-aefd-40ea34c67bd1" === (null === e || void 0 === e ? void 0 : e.id);
        return (0,
        Yt.jsxs)("div", {
            className: "app-rating app-hide-scroll",
            children: [!t && e && (0,
            Yt.jsx)(dn, {
                number: i ? i.position : "",
                image: e.photo || sn,
                title: ((e.firstName || "") + " " + (e.lastName || "")).trim(),
                coins: e.coins,
                active: !0,
                error: !e.chatMember,
                isOwn: !0
            }, "rating_card_me"), !t && !e.chatMember && (0,
            Yt.jsxs)("div", {
                className: "app-rating-card--warning",
                children: ["\u0425\u043e\u0447\u0435\u0448\u044c, \u0447\u0442\u043e\u0431\u044b \u0442\u0432\u043e\u0438 \u0431\u0430\u043b\u043b\u044b \u0441\u043e\u0445\u0440\u0430\u043d\u0438\u043b\u0438\u0441\u044c \u0432\xa0\u0440\u0435\u0439\u0442\u0438\u043d\u0433\u0435?", (0,
                Yt.jsx)("br", {}), "\u041f\u0440\u043e\u0441\u0442\u043e \u043f\u043e\u0434\u043f\u0438\u0448\u0438\u0441\u044c \u043d\u0430", " ", (0,
                Yt.jsx)("a", {
                    onClick: () => Ei.openTelegramLink("https://t.me/tv3russia"),
                    children: "\u043a\u0430\u043d\u0430\u043b \u0422\u0412-3"
                }), ", \u0438\xa0\u0442\u044b\xa0\u0432\xa0\u0438\u0433\u0440\u0435!\xa0\ud83d\ude09"]
            }), !t && (0,
            Yt.jsxs)("div", {
                className: "app-rating--list",
                children: [(0,
                Yt.jsx)("h2", {
                    children: "\u0420\u0435\u0439\u0442\u0438\u043d\u0433"
                }), r.map((e => (0,
                Yt.jsx)(dn, {
                    number: e.position,
                    image: e.payload.photoPath || sn,
                    title: ((e.payload.first_name || "") + " " + (e.payload.last_name || "")).trim(),
                    coins: e.payload.score,
                    active: e.active,
                    isEnemy: s(e.payload)
                }, "rating_card_" + e.position)))]
            }), !t && (0,
            Yt.jsx)(Kt, {}), t && (0,
            Yt.jsxs)("div", {
                className: "app-rating--prizes",
                children: [(0,
                Yt.jsxs)("header", {
                    children: [(0,
                    Yt.jsx)(ji, {
                        onClick: () => n(!1)
                    }), (0,
                    Yt.jsx)("h2", {
                        children: "\u041f\u0440\u0438\u0437\u044b"
                    })]
                }), (0,
                Yt.jsx)(Ai, {}), (0,
                Yt.jsx)(ki, {}), (0,
                Yt.jsx)(Si, {})]
            })]
        })
    }
      , Ci = n.p + "static/media/no-desktop-qr-code.08658621b30919d73c21.png"
      , Ri = () => (0,
    Yt.jsxs)("div", {
        className: "app-no-desktop",
        children: [(0,
        Yt.jsxs)("div", {
            className: "app-no-desktop--text",
            children: ["\u041e\u0442\u043a\u0440\u043e\u0439 \u0438\u0433\u0440\u0443", (0,
            Yt.jsx)("br", {}), " \u0441 \u043c\u043e\u0431\u0438\u043b\u044c\u043d\u043e\u0433\u043e"]
        }), (0,
        Yt.jsx)("img", {
            src: Ci,
            alt: "",
            className: "app-no-desktop--image"
        })]
    });
    const Oi = n.p + "static/media/clock.faa1ba13824dc30fb76dc12cdb6347e2.svg"
      , Ti = e => {
        let {active: t, title: n, time: r, text: a, icon: o, onClick: i, type: l} = e;
        return (0,
        Yt.jsx)(Yt.Fragment, {
            children: (0,
            Yt.jsxs)("div", {
                onClick: i,
                className: "game-mode " + (t ? "game-mode--active" : ""),
                children: [(0,
                Yt.jsx)("div", {
                    children: (0,
                    Yt.jsx)("img", {
                        src: o || "",
                        alt: ""
                    })
                }), (0,
                Yt.jsxs)("div", {
                    className: "game-mode--wrapper",
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "game-mode--title",
                        children: [(0,
                        Yt.jsx)("div", {
                            children: (0,
                            Yt.jsx)("h3", {
                                children: n || ""
                            })
                        }), (0,
                        Yt.jsxs)("div", {
                            className: "game-mode--time",
                            children: [(0,
                            Yt.jsx)("div", {
                                className: "game-mode--image-wrapper",
                                children: (0,
                                Yt.jsx)("img", {
                                    className: "game-mode--image",
                                    src: Oi,
                                    alt: ""
                                })
                            }), (0,
                            Yt.jsx)("div", {
                                children: (0,
                                Yt.jsx)("h4", {
                                    children: r || ""
                                })
                            })]
                        })]
                    }), (0,
                    Yt.jsx)("div", {
                        className: "game-mode--text-info",
                        children: a || ""
                    })]
                })]
            })
        })
    }
      , Li = [{
        title: "\u041a\u043b\u0430\u0441\u0441\u0438\u043a\u0430 \ud83d\udd79\ufe0f",
        time: "60 \u0441\u0435\u043a\u0443\u043d\u0434",
        type: qt,
        text: (0,
        Yt.jsxs)(Yt.Fragment, {
            children: ["\u0411\u0430\u0437\u043e\u0432\u0430\u044f \u0438\u0433\u0440\u0430 \u043d\u0430", (0,
            Yt.jsx)("br", {}), " \u043e\u0431\u044b\u0447\u043d\u043e\u0439 \u0441\u043a\u043e\u0440\u043e\u0441\u0442\u0438"]
        }),
        icon: "data:image/png;base64,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"
    }, {
        title: "\u0411\u043b\u0438\u0446 \u26a1",
        time: "30 \u0441\u0435\u043a\u0443\u043d\u0434",
        type: Dt,
        text: (0,
        Yt.jsxs)(Yt.Fragment, {
            children: ["\u0411\u044b\u0441\u0442\u0440\u0430\u044f \u0438\u0433\u0440\u0430, \u0432\u044b\u0441\u043e\u043a\u0430\u044f", (0,
            Yt.jsx)("br", {}), " \u0441\u043a\u043e\u0440\u043e\u0441\u0442\u044c"]
        }),
        icon: "data:image/png;base64,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"
    }, {
        title: "\u0412\u044b\u0436\u0438\u0432\u0430\u043d\u0438\u0435 \ud83d\udcaa",
        time: "\u221e",
        type: Ht,
        text: (0,
        Yt.jsxs)(Yt.Fragment, {
            children: ["\u0418\u0433\u0440\u0430 \u0431\u0435\u0437 \u0442\u0430\u0439\u043c\u0435\u0440\u0430 \u0434\u043e \u0442\u0440\u0435\u0445", (0,
            Yt.jsx)("br", {}), " \u043e\u0448\u0438\u0431\u043e\u043a, \u0441\u043b\u043e\u0436\u043d\u043e\u0441\u0442\u044c \u0440\u0430\u0441\u0442\u0435\u0442"]
        }),
        icon: "data:image/png;base64,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"
    }]
      , Ui = {
        [qt]: kt,
        [Dt]: Et,
        [Ht]: jt
    }
      , Pi = () => {
        const [e,t] = (0,
        a.useState)("")
          , n = pe();
        return (0,
        Yt.jsxs)("div", {
            className: "app-page app-page_paris",
            children: [(0,
            Yt.jsxs)("div", {
                onClick: () => n(-1),
                className: "app-page--back",
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-page--image-wrapper",
                    children: (0,
                    Yt.jsx)("img", {
                        src: ko,
                        alt: ""
                    })
                }), (0,
                Yt.jsx)("div", {
                    className: "app-page--back-text",
                    children: "\u041d\u0430\u0437\u0430\u0434"
                })]
            }), (0,
            Yt.jsx)("div", {
                className: "app-page--header-wrapper",
                children: (0,
                Yt.jsx)("h2", {
                    children: "\u0412\u044b\u0431\u0435\u0440\u0438 \u0440\u0435\u0436\u0438\u043c \u0438\u0433\u0440\u044b"
                })
            }), (0,
            Yt.jsx)("div", {
                className: "app-page--game-wrapper",
                children: Li.map(( (n, r) => (0,
                Yt.jsx)(Ti, c({
                    onClick: () => t(n.type),
                    active: e === n.type
                }, n), r)))
            }), (0,
            Yt.jsx)("div", {
                className: "app-page--button-wrapper",
                children: (0,
                Yt.jsx)(Wt, {
                    disabled: !e,
                    onClick: () => {
                        wn().ymReachGoal("ladybug_game_click_start_game"),
                        n(null === Ui || void 0 === Ui ? void 0 : Ui[e])
                    }
                    ,
                    children: "\u0418\u0433\u0440\u0430\u0442\u044c"
                })
            })]
        })
    }
      , Ii = n.p + "static/media/squads-header.dc4736450ccc3290c00b.png"
      , Fi = () => {
        const e = pe()
          , {user: t} = Sn()
          , [n,r] = (0,
        a.useState)(!0);
        return (0,
        a.useEffect)(( () => {
            vn(null === t || void 0 === t ? void 0 : t.lastSquadJoin).total <= 0 && r(!1)
        }
        ), [null === t || void 0 === t ? void 0 : t.lastSquadJoin]),
        (0,
        Yt.jsxs)("div", {
            className: "app-squads app-squads_bg",
            children: [(0,
            Yt.jsx)("div", {
                className: "app-squads--header-wrapper",
                children: (0,
                Yt.jsx)("img", {
                    src: Ii,
                    alt: ""
                })
            }), (0,
            Yt.jsx)("div", {
                className: "app-squads--header-title",
                children: "\u041a\u041e\u041c\u0410\u041d\u0414\u042b"
            }), (0,
            Yt.jsxs)("div", {
                className: "app-squads--additional-info",
                children: ["\u0421\u043e\u0437\u0434\u0430\u0439 \u0441\u0432\u043e\u044e \u043a\u043e\u043c\u0430\u043d\u0434\u0443 \u0438\u043b\u0438 \u043f\u0440\u0438\u0441\u043e\u0435\u0434\u0438\u043d\u0438\u0441\u044c", (0,
                Yt.jsx)("br", {}), " \u043a \u0434\u0440\u0443\u0433\u0438\u043c \u0438\u0433\u0440\u043e\u043a\u0430\u043c, \u0447\u0442\u043e\u0431\u044b \u0431\u044b\u0441\u0442\u0440\u0435\u0435 \u043d\u0430\u0431\u0438\u0440\u0430\u0442\u044c", (0,
                Yt.jsx)("br", {}), " \u0431\u0430\u043b\u043b\u044b \u0432 \u0440\u0435\u0439\u0442\u0438\u043d\u0433\u0435."]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-squads--additional-info",
                children: ["\u0427\u0435\u043c \u0432\u044b\u0448\u0435 \u0440\u0435\u0437\u0443\u043b\u044c\u0442\u0430\u0442\u044b \u0442\u0432\u043e\u0435\u0439 \u043a\u043e\u043c\u0430\u043d\u0434\u044b,", (0,
                Yt.jsx)("br", {}), " \u0442\u0435\u043c \u0431\u043e\u043b\u044c\u0448\u0435 \u043e\u0447\u043a\u043e\u0432 \u043f\u043e\u043b\u0443\u0447\u0438\u0448\u044c \u0442\u044b \u043b\u0438\u0447\u043d\u043e!"]
            }), (0,
            Yt.jsx)("div", {
                className: "app-squads--additional-info",
                children: (0,
                Yt.jsxs)("div", {
                    children: ["\u041f\u043e\u043b\u0443\u0447\u0438\u0442\u044c \u0431\u043e\u043d\u0443\u0441\u043d\u044b\u0435 ", (0,
                    Yt.jsx)("span", {
                        className: "app-squads--additional-info-gold",
                        children: "5000 \u0431\u0430\u043b\u043b\u043e\u0432"
                    }), (0,
                    Yt.jsx)("br", {}), "\u0437\u0430 \u0441\u043e\u0437\u0434\u0430\u043d\u0438\u0435 \u043a\u043e\u043c\u0430\u043d\u0434\u044b \u043c\u043e\u0436\u043d\u043e", (0,
                    Yt.jsx)("br", {}), "\u0442\u043e\u043b\u044c\u043a\u043e \u043e\u0434\u0438\u043d \u0440\u0430\u0437."]
                })
            }), (0,
            Yt.jsxs)("div", {
                className: "app-squads--buttons-wrapper",
                children: [!(null !== t && void 0 !== t && t.squad) && (0,
                Yt.jsx)(Wt, {
                    disabled: n,
                    onClick: () => e(Ct),
                    children: "\u0421\u043e\u0437\u0434\u0430\u0442\u044c \u043a\u043e\u043c\u0430\u043d\u0434\u0443"
                }), (0,
                Yt.jsx)(Wt, {
                    onClick: () => e(Rt),
                    variant: "outlined",
                    children: "\u0412\u044b\u0431\u0440\u0430\u0442\u044c \u043a\u043e\u043c\u0430\u043d\u0434\u0443"
                })]
            }), (0,
            Yt.jsx)(Kt, {})]
        })
    }
      , zi = "squad_created"
      , Mi = () => {
        const e = pe()
          , {user: t, setUser: n} = Sn()
          , [r,o] = (0,
        a.useState)(1)
          , [i,l] = (0,
        a.useState)(null)
          , [s,u] = (0,
        a.useState)(null);
        return (0,
        Yt.jsxs)("div", {
            className: "app-create-squads app-create-squads_bg",
            children: [(0,
            Yt.jsxs)("div", {
                onClick: () => e(-1),
                className: "app-create-squads--back",
                children: [(0,
                Yt.jsx)("div", {
                    className: "app-page--image-wrapper",
                    children: (0,
                    Yt.jsx)("img", {
                        src: ko,
                        alt: ""
                    })
                }), (0,
                Yt.jsx)("div", {
                    className: "app-create-squads--back-text",
                    children: "\u041d\u0430\u0437\u0430\u0434"
                })]
            }), (0,
            Yt.jsx)("div", {
                className: "app-create-squads--header-wrapper",
                children: (0,
                Yt.jsx)("img", {
                    src: Ii,
                    alt: ""
                })
            }), (0,
            Yt.jsxs)("div", {
                className: "app-create-squads--header-title",
                children: ["\u041a\u043e\u043c\u0430\u043d\u0434\u0430 ", null === t || void 0 === t ? void 0 : t.firstName]
            }), (0,
            Yt.jsxs)("div", {
                className: "app-create-squads--slider-wrapper",
                children: [(0,
                Yt.jsx)("img", {
                    onClick: () => {
                        o(1 === r ? 12 : r - 1)
                    }
                    ,
                    src: ko,
                    alt: ""
                }), (0,
                Yt.jsx)("div", {
                    children: (0,
                    Yt.jsx)("img", {
                        src: ai[r],
                        alt: ""
                    })
                }), (0,
                Yt.jsx)("img", {
                    className: "app-create-squads--right-icon",
                    onClick: () => {
                        o(12 === r ? 1 : r + 1)
                    }
                    ,
                    src: ko,
                    alt: ""
                })]
            }), (0,
            Yt.jsx)("div", {
                className: "app-create-squads--slider-text",
                children: "\u0412\u044b\u0431\u0435\u0440\u0438 \u0430\u0432\u0430\u0442\u0430\u0440"
            }), (0,
            Yt.jsx)("div", {
                className: "app-create-squads--button-wrapper",
                children: (0,
                Yt.jsx)(Wt, {
                    onClick: () => {
                        co.post("".concat(Tt, "/api/squads"), {
                            hash: t.authToken,
                            photo_id: r
                        }).then((e => {
                            var r, a, o;
                            console.log("response", e),
                            u({
                                title: null === e || void 0 === e || null === (r = e.data) || void 0 === r ? void 0 : r.name,
                                photo: ai[null === e || void 0 === e || null === (a = e.data) || void 0 === a ? void 0 : a.photo_id],
                                id: null === e || void 0 === e || null === (o = e.data) || void 0 === o ? void 0 : o.id
                            }),
                            l(zi),
                            n(c(c({}, t), {}, {
                                squad: null === e || void 0 === e ? void 0 : e.data
                            }))
                        }
                        ))
                    }
                    ,
                    children: "\u0421\u043e\u0437\u0434\u0430\u0442\u044c \u043a\u043e\u043c\u0430\u043d\u0434\u0443"
                })
            }), zi === i && (0,
            Yt.jsx)(ri, c({
                onClose: () => {
                    l(null),
                    e(Rt)
                }
            }, s)), (0,
            Yt.jsx)(Kt, {})]
        })
    }
      , Bi = n.p + "static/media/bronze.f407fc3eb0c5cee41ac7.png"
      , qi = "squad_popup"
      , Di = () => {
        const [e,t] = (0,
        a.useState)(1)
          , [n,r] = (0,
        a.useState)(null)
          , [o,i] = (0,
        a.useState)(null)
          , [l,s] = (0,
        a.useState)([])
          , [u,d] = (0,
        a.useState)(!0)
          , {user: p} = Sn()
          , f = l.find(( (e, t) => {
            var n;
            return e.id === (null === p || void 0 === p || null === (n = p.squad) || void 0 === n ? void 0 : n.id) && (e.place = t + 1,
            !0)
        }
        ))
          , m = {
            3: qo,
            2: Do,
            1: Bi
        }
          , h = {
            3: "gold",
            2: "silver",
            1: "bronze"
        }
          , g = () => {
            co.get("".concat(Tt, "/api/squads/list/").concat(h[e])).then((e => {
                var t;
                s(null === e || void 0 === e || null === (t = e.data) || void 0 === t ? void 0 : t.squads)
            }
            )).finally(( () => d(!1)))
        }
        ;
        (0,
        a.useEffect)(( () => {
            d(!0),
            g()
        }
        ), [e]);
        const v = function() {
            return "app-squads-list" + (arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : "")
        }
          , y = e => {
            r(qi),
            i({
                title: null === e || void 0 === e ? void 0 : e.name,
                image: ai[null === e || void 0 === e ? void 0 : e.photo_id],
                coins: (null === e || void 0 === e ? void 0 : e.coins) || 0,
                place: (null === e || void 0 === e ? void 0 : e.place) || "-",
                players: (null === e || void 0 === e ? void 0 : e.userCount) || 0,
                id: null === e || void 0 === e ? void 0 : e.id,
                creator: (null === e || void 0 === e ? void 0 : e.creator) || {},
                squad: e,
                getSquadListAPI: g
            })
        }
          , b = () => {}
        ;
        return (0,
        Yt.jsxs)("div", {
            className: "app-squads-list app-squads-list_bg",
            children: [(0,
            Yt.jsxs)("div", {
                className: v("--slider-wrapper"),
                children: [(0,
                Yt.jsx)("img", {
                    onClick: u ? b : () => {
                        t(1 === e ? 3 : e - 1)
                    }
                    ,
                    src: ko,
                    alt: ""
                }), (0,
                Yt.jsx)("img", {
                    src: m[e],
                    alt: ""
                }), (0,
                Yt.jsx)("img", {
                    className: "app-create-squads--right-icon",
                    onClick: u ? b : () => {
                        t(3 === e ? 1 : e + 1)
                    }
                    ,
                    src: ko,
                    alt: ""
                })]
            }), (0,
            Yt.jsxs)("div", {
                className: "".concat(v("--title"), " ").concat(v("--title-".concat(e))),
                children: [{
                    3: "\u0417\u043e\u043b\u043e\u0442\u0430\u044f",
                    2: "\u0421\u0435\u0440\u0435\u0431\u0440\u044f\u043d\u043d\u0430\u044f",
                    1: "\u0411\u0440\u043e\u043d\u0437\u043e\u0432\u0430\u044f"
                }[e], " \u043b\u0438\u0433\u0430"]
            }), (0,
            Yt.jsxs)("div", {
                className: "".concat(v("--bonus")),
                children: ["\u0411\u043e\u043d\u0443\u0441 \u0437\u0430 \u0438\u0433\u0440\u0443", " ", (0,
                Yt.jsxs)("span", {
                    className: "".concat(v("--bonus-".concat(e))),
                    children: ["\xd7", {
                        3: 1.2,
                        2: 1.1,
                        1: 1.05
                    }[e]]
                })]
            }), f && (null === f || void 0 === f ? void 0 : f.league) === h[e] && (0,
            Yt.jsxs)(Yt.Fragment, {
                children: [(0,
                Yt.jsx)("div", {
                    className: v("--your-squad-title"),
                    children: "\u0422\u0432\u043e\u044f \u043a\u043e\u043c\u0430\u043d\u0434\u0430"
                }), (0,
                Yt.jsx)("div", {
                    className: v("--your-squad-wrapper"),
                    children: (0,
                    Yt.jsx)(Yi, {
                        image: ai[null === f || void 0 === f ? void 0 : f.photo_id],
                        title: null === f || void 0 === f ? void 0 : f.name,
                        coins: null === f || void 0 === f ? void 0 : f.coins,
                        players: null === f || void 0 === f ? void 0 : f.userCount,
                        completed: !1,
                        onClick: () => y(f),
                        own: !0
                    })
                })]
            }), (null === l || void 0 === l ? void 0 : l.length) > 0 && (0,
            Yt.jsxs)(Yt.Fragment, {
                children: [(0,
                Yt.jsx)("div", {
                    className: v("--list-title"),
                    children: "\u0421\u043f\u0438\u0441\u043e\u043a \u043a\u043e\u043c\u0430\u043d\u0434"
                }), !f && (0,
                Yt.jsxs)("div", {
                    className: v("--list-info"),
                    children: ["\u0412\u0441\u0442\u0443\u043f\u0438 \u0432 \u043f\u043e\u043d\u0440\u0430\u0432\u0438\u0432\u0448\u0443\u044e\u0441\u044f \u043a\u043e\u043c\u0430\u043d\u0434\u0443,", (0,
                    Yt.jsx)("br", {}), " \u043f\u043e\u043a\u0430 \u0432 \u043d\u0435\u0439 \u0435\u0441\u0442\u044c \u043c\u0435\u0441\u0442\u043e!"]
                }), (0,
                Yt.jsx)("div", {
                    className: v("--list-wrapper"),
                    children: null === l || void 0 === l ? void 0 : l.map(( (e, t) => (0,
                    Yt.jsx)(Yi, {
                        image: ai[null === e || void 0 === e ? void 0 : e.photo_id],
                        players: null === e || void 0 === e ? void 0 : e.userCount,
                        title: null === e || void 0 === e ? void 0 : e.name,
                        coins: null === e || void 0 === e ? void 0 : e.coins,
                        completed: !1,
                        onClick: () => {
                            y(c(c({}, e), {}, {
                                place: t + 1
                            }))
                        }
                    }, null === e || void 0 === e ? void 0 : e.id)))
                })]
            }), 0 === (null === l || void 0 === l ? void 0 : l.length) && (0,
            Yt.jsx)("div", {
                className: v("--empty"),
                children: "\u0422\u0443\u0442 \u043f\u043e\u043a\u0430 \u043d\u0438\u043a\u043e\u0433\u043e \u043d\u0435\u0442"
            }), qi === n && (0,
            Yt.jsx)(Wi, c({
                onClose: () => r(null)
            }, o)), (0,
            Yt.jsx)(Kt, {})]
        })
    }
      , Hi = () => (0,
    Yt.jsx)("svg", {
        className: "app-squad-item--completed",
        width: "24",
        height: "24",
        viewBox: "0 0 24 24",
        fill: "none",
        xmlns: "http://www.w3.org/2000/svg",
        children: (0,
        Yt.jsx)("path", {
            fillRule: "evenodd",
            clipRule: "evenodd",
            d: "M12 21C16.9706 21 21 16.9706 21 12C21 7.02944 16.9706 3 12 3C7.02944 3 3 7.02944 3 12C3 16.9706 7.02944 21 12 21ZM11.7682 15.6402L16.7682 9.64018L15.2318 8.35982L10.9328 13.5186L8.70711 11.2929L7.29289 12.7071L10.2929 15.7071L11.0672 16.4814L11.7682 15.6402Z",
            fill: "#87FF85"
        })
    })
      , Qi = () => (0,
    Yt.jsx)("svg", {
        className: "app-squad-item--arrow",
        width: "24",
        height: "24",
        viewBox: "0 0 24 24",
        fill: "none",
        xmlns: "http://www.w3.org/2000/svg",
        children: (0,
        Yt.jsx)("path", {
            d: "M9 6L15 12L9 18",
            stroke: "white",
            strokeWidth: "1.6"
        })
    })
      , Yi = e => {
        let {image: t, title: n, coins: r, completed: a, onClick: o, own: i, players: l} = e;
        return (0,
        Yt.jsxs)("div", {
            className: "app-squad-item " + (i ? "app-squad-item--own" : ""),
            onClick: o,
            children: [(0,
            Yt.jsx)("img", {
                src: t,
                alt: "",
                className: "app-squad-item--image"
            }), (0,
            Yt.jsxs)("div", {
                className: "app-squad-item--content",
                children: [(0,
                Yt.jsxs)("div", {
                    className: "app-squad-item--title",
                    children: [n, "\xa0\xa0\xa0 ", (0,
                    Yt.jsx)("img", {
                        src: "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAwAAAANCAYAAACdKY9CAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAADsSURBVHgBjZG9EYJAEIXfnsyY0oGUIFagHWgHdqCGmiiJpNoJHWCuo9jB2QEpznjrgvwJOvqiY/ne3t4+Qk0Xnx0DrMEYZwVCoADPXZIuGKtuEDgU2CkLjCkDfTm5RUkVh9OWx29w6UH/6POwZSC04RIyaBsMIfpmMAqHWuNKZ59D5qpbDkSDFbXfkP1MMBHDPoWE1Ibh0R2jOmOhoY5CYPAaz1LQ7obixo2y/w3b6GImHefyaTd6xFkeCRapmfKwwk8rbUgrwkjlyf6CUzkPYGel0csoN3l+L8uCYTNVY0lNS3ha6lfTqdb7t56c21BIEW6IRgAAAABJRU5ErkJggg==",
                        alt: ""
                    }), "\xa0", (0,
                    Yt.jsxs)("span", {
                        className: "app-squad-item--count",
                        children: [l || 1, "/5"]
                    })]
                }), (0,
                Yt.jsx)(Xt, {
                    coins: r,
                    big: !1
                })]
            }), !a && (0,
            Yt.jsx)(Qi, {}), a && (0,
            Yt.jsx)(Hi, {})]
        })
    }
      , Wi = e => {
        var t, n, r, o, i, l;
        let {onClose: s, title: u, coins: d, place: p, players: f, image: m, id: h, creator: g, squad: v, getSquadListAPI: y, invited: b} = e;
        const {user: x, setUser: w} = Sn()
          , [A,k] = (0,
        a.useState)(!1)
          , [S,E] = (0,
        a.useState)(!1)
          , j = (null === x || void 0 === x || null === (t = x.squad) || void 0 === t || null === (n = t.creator) || void 0 === n ? void 0 : n.telegram_user_id) === (null === x || void 0 === x ? void 0 : x.telegram_id) && (null === x || void 0 === x || null === (r = x.squad) || void 0 === r ? void 0 : r.userCount) > 1
          , N = +(null === g || void 0 === g ? void 0 : g.telegram_user_id) === +(null === x || void 0 === x ? void 0 : x.telegram_id)
          , C = f > 1
          , R = 5 === +f
          , O = (null === x || void 0 === x || null === (o = x.squad) || void 0 === o ? void 0 : o.id) === h
          , T = (null === x || void 0 === x ? void 0 : x.squad) && !O && !N
          , [L,U] = (0,
        a.useState)(!0);
        (0,
        a.useEffect)(( () => {
            vn(null === x || void 0 === x ? void 0 : x.lastSquadJoin).total <= 0 && U(!1)
        }
        ), [null === x || void 0 === x ? void 0 : x.lastSquadJoin]);
        const P = "https://t.me/tv3_day_ladybug_bot?startapp=squad_{squad_id}"
          , I = () => O ? void co.post("".concat(Tt, "/api/squads/leave"), {
            hash: x.authToken
        }).then(( () => {
            w(c(c({}, x), {}, {
                squad: null
            })),
            s(),
            y()
        }
        )) : void co.post("".concat(Tt, "/api/squads/").concat(h, "/join"), {
            hash: x.authToken,
            invited: !!b || void 0
        }).then((e => {
            var t, n, r;
            s(),
            w(c(c({}, x), {}, {
                squad: c(c({}, null === e || void 0 === e ? void 0 : e.data), {}, {
                    userCount: null === e || void 0 === e || null === (t = e.data) || void 0 === t ? void 0 : t.members,
                    lastSquadJoin: null === e || void 0 === e || null === (n = e.data) || void 0 === n ? void 0 : n.lastSquadJoin
                }),
                lastSquadJoin: null === e || void 0 === e || null === (r = e.data) || void 0 === r ? void 0 : r.lastSquadJoin
            })),
            y()
        }
        ));
        return (0,
        Yt.jsxs)(ln, {
            title: u || "\u041a\u043e\u043c\u0430\u043d\u0434\u0430 \u0441\u043e\u0437\u0434\u0430\u043d\u0430!",
            buttonText: "",
            onButtonClick: () => {}
            ,
            onClose: s,
            closed: A,
            type: "dark",
            children: [(0,
            Yt.jsxs)("div", {
                className: "app-popup-squad-info",
                children: [!S && (0,
                Yt.jsxs)(Yt.Fragment, {
                    children: [(0,
                    Yt.jsx)("img", {
                        src: m,
                        alt: "",
                        className: "app-popup-squad-info--image"
                    }), (0,
                    Yt.jsxs)("div", {
                        className: "app-popup-squad-info--wrapper",
                        children: [(0,
                        Yt.jsxs)("div", {
                            className: "app-popup-squad-info--title",
                            children: ["\u0411\u0430\u043b\u043b\u044b: ", (0,
                            Yt.jsx)("span", {
                                children: d
                            }), (0,
                            Yt.jsx)("img", {
                                className: "app-popup-squad-info--icon",
                                src: Jt,
                                alt: ""
                            })]
                        }), (0,
                        Yt.jsxs)("div", {
                            className: "app-popup-squad-info--title",
                            children: ["\u041c\u0435\u0441\u0442\u043e: ", (0,
                            Yt.jsx)("span", {
                                children: p
                            })]
                        }), (0,
                        Yt.jsxs)("div", {
                            className: "app-popup-squad-info--title",
                            children: ["\u0423\u0447\u0430\u0441\u0442\u043d\u0438\u043a\u0438: ", (0,
                            Yt.jsxs)("span", {
                                children: [f, "/5"]
                            })]
                        })]
                    })]
                }), S && (0,
                Yt.jsxs)(Yt.Fragment, {
                    children: [(0,
                    Yt.jsxs)("div", {
                        className: "app-popup-squad-info--image-wrapper",
                        children: [(0,
                        Yt.jsx)("img", {
                            src: m,
                            alt: "",
                            className: "app-popup-squad-info--image-prev"
                        }), (0,
                        Yt.jsx)("img", {
                            src: ai[null === x || void 0 === x || null === (i = x.squad) || void 0 === i ? void 0 : i.photo_id],
                            alt: "",
                            className: "app-popup-squad-info--image-new"
                        })]
                    }), !L && (0,
                    Yt.jsxs)("div", {
                        className: "app-popup-squad-info---information",
                        children: ["\u0415\u0441\u043b\u0438 \u0442\u044b \u043f\u0440\u0438\u0441\u043e\u0435\u0434\u0438\u043d\u0438\u0448\u044c\u0441\u044f \u043a \u044d\u0442\u043e\u0439", (0,
                        Yt.jsx)("br", {}), " \u043a\u043e\u043c\u0430\u043d\u0434\u0435, \u0442\u043e \u0442\u044b \u0430\u0432\u0442\u043e\u043c\u0430\u0442\u0438\u0447\u0435\u0441\u043a\u0438", (0,
                        Yt.jsx)("br", {}), " \u043f\u043e\u043a\u0438\u043d\u0435\u0448\u044c \u201c", null === x || void 0 === x || null === (l = x.squad) || void 0 === l ? void 0 : l.name, "\u201d"]
                    }), L && (0,
                    Yt.jsxs)("div", {
                        className: "app-popup-squad-info---information",
                        children: ["\u0412\u0441\u0442\u0443\u043f\u0438\u0442\u044c \u0432 \u043d\u043e\u0432\u0443\u044e \u043a\u043e\u043c\u0430\u043d\u0434\u0443 \u043c\u043e\u0436\u043d\u043e", (0,
                        Yt.jsx)("br", {}), " \u043d\u0435 \u0440\u0430\u043d\u044c\u0448\u0435 \u0447\u0435\u043c \u0447\u0435\u0440\u0435\u0437 24 \u0447\u0430\u0441\u0430!"]
                    })]
                })]
            }), N && (0,
            Yt.jsxs)("div", {
                className: "app-popup-squad--actions-wrapper app-popup-squad-info--action-wrapper",
                children: [(0,
                Yt.jsx)(Wt, {
                    onClick: () => {
                        window.Telegram.WebApp.openTelegramLink("https://t.me/share/url?url=" + P.replace("{squad_id}", h) + "&text=" + encodeURIComponent("\u0421\u043a\u043e\u0440\u0435\u0435 \u0432\u0441\u0442\u0443\u043f\u0430\u0439 \u0432 \u043c\u043e\u044e \u043a\u043e\u043c\u0430\u043d\u0434\u0443 \u0438 \u043f\u043e\u043c\u043e\u0433\u0438 \u043c\u043d\u0435 \u0437\u0430\u0440\u0430\u0431\u043e\u0442\u0430\u0442\u044c \u0431\u0430\u043b\u043b\u044b! \ud83d\ude09\ud83d\udc1e"))
                    }
                    ,
                    children: "\u041f\u0440\u0438\u0433\u043b\u0430\u0441\u0438\u0442\u044c \u0434\u0440\u0443\u0433\u0430"
                }), (0,
                Yt.jsx)(Wt, {
                    variant: "fit",
                    onClick: () => {
                        navigator.clipboard.writeText(P.replace("{squad_id}", h)),
                        wn().showAlert("\u0421\u0441\u044b\u043b\u043a\u0430 \u0441\u043a\u043e\u043f\u0438\u0440\u043e\u0432\u0430\u043d\u0430 \u0438 \u0435\u0451 \u043c\u043e\u0436\u043d\u043e \u043e\u0442\u043f\u0440\u0430\u0432\u0438\u0442\u044c \u0434\u0440\u0443\u0433\u0443!"),
                        k(!0),
                        window.setTimeout(( () => s()), 200)
                    }
                    ,
                    children: (0,
                    Yt.jsx)("svg", {
                        width: "16",
                        height: "16",
                        viewBox: "0 0 16 16",
                        fill: "none",
                        xmlns: "http://www.w3.org/2000/svg",
                        children: (0,
                        Yt.jsx)("path", {
                            d: "M2.66665 1.33337C1.92998 1.33337 1.33331 1.93004 1.33331 2.66671V11.3334C1.33331 11.7014 1.63198 12 1.99998 12C2.36798 12 2.66665 11.7014 2.66665 11.3334V2.66671H11.3333C11.7013 2.66671 12 2.36804 12 2.00004C12 1.63204 11.7013 1.33337 11.3333 1.33337H2.66665ZM5.33331 4.00004C4.59665 4.00004 3.99998 4.59671 3.99998 5.33337V13.3334C3.99998 14.07 4.59665 14.6667 5.33331 14.6667H13.3333C14.07 14.6667 14.6666 14.07 14.6666 13.3334V5.33337C14.6666 4.59671 14.07 4.00004 13.3333 4.00004H5.33331ZM5.33331 5.33337H13.3333V13.3334H5.33331V5.33337Z",
                            fill: "white"
                        })
                    })
                })]
            }), !R && !S && (0,
            Yt.jsxs)("div", {
                className: N ? "app-popup-squad-info--action-wrapper-owner" : "app-popup-squad-info--action-wrapper",
                children: [!O && (0,
                Yt.jsx)(Wt, {
                    disabled: !!L || (N && C || j),
                    onClick: T ? () => E(!0) : I,
                    variant: O ? "danger" : "",
                    children: L ? (0,
                    Yt.jsx)(yn, {
                        startDate: null === x || void 0 === x ? void 0 : x.lastSquadJoin
                    }) : "\u041f\u0440\u0438\u0441\u043e\u0435\u0434\u0438\u043d\u0438\u0442\u044c\u0441\u044f"
                }), O && (0,
                Yt.jsx)(Wt, {
                    disabled: N && C,
                    onClick: I,
                    variant: "danger",
                    children: "\u041f\u043e\u043a\u0438\u043d\u0443\u0442\u044c \u043a\u043e\u043c\u0430\u043d\u0434\u0443"
                })]
            }), R && (0,
            Yt.jsx)("div", {
                className: "app-popup-squad-info--action-wrapper",
                children: (0,
                Yt.jsx)(Wt, {
                    disabled: R,
                    children: "\u0412 \u041a\u041e\u041c\u0410\u041d\u0414\u0415 \u041d\u0415\u0422 \u041c\u0415\u0421\u0422"
                })
            }), !R && S && (0,
            Yt.jsx)("div", {
                className: "app-popup-squad-info--action-wrapper",
                children: (0,
                Yt.jsx)(Wt, {
                    disabled: !!L || N && C,
                    onClick: I,
                    variant: O ? "danger" : "",
                    children: L ? (0,
                    Yt.jsx)(yn, {
                        startDate: null === x || void 0 === x ? void 0 : x.lastSquadJoin
                    }) : "\u041f\u0440\u043e\u0434\u043e\u043b\u0436\u0438\u0442\u044c"
                })
            }), !R && N && C && (0,
            Yt.jsxs)("div", {
                className: "app-popup-squad-info--tip",
                children: ["\u0422\u044b \u043d\u0435 \u043c\u043e\u0436\u0435\u0448\u044c \u043f\u043e\u043a\u0438\u043d\u0443\u0442\u044c \u0441\u0432\u043e\u044e \u043a\u043e\u043c\u0430\u043d\u0434\u0443,", (0,
                Yt.jsx)("br", {}), " \u043f\u043e\u043a\u0430 \u0432 \u043d\u0435\u0439, \u043a\u0440\u043e\u043c\u0435 \u0442\u0435\u0431\u044f \u0435\u0441\u0442\u044c \u0435\u0449\u0435 \u0445\u043e\u0442\u044f", (0,
                Yt.jsx)("br", {}), " \u0431\u044b \u043e\u0434\u0438\u043d \u0443\u0447\u0430\u0441\u0442\u043d\u0438\u043a!"]
            })]
        })
    }
      , Gi = e => {
        let {icon: t, place: n, text: r} = e;
        const a = function() {
            return "app-prize-item".concat(arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : "")
        };
        return (0,
        Yt.jsxs)("div", {
            className: a(),
            children: [(0,
            Yt.jsx)("div", {
                className: a("--place"),
                children: n
            }), (0,
            Yt.jsx)("div", {
                className: a("--icon-wrapper"),
                children: (0,
                Yt.jsx)("img", {
                    className: a("--icon"),
                    src: t,
                    alt: ""
                })
            }), (0,
            Yt.jsx)("div", {
                className: a("--prize-text-wrapper"),
                children: r
            })]
        })
    }
    ;
    const Vi = n.p + "static/media/first.6414113cfb8fbb53310434c85c59ad00.svg";
    const Zi = n.p + "static/media/second.b12c2793a0b559dd66f6f44eec6c8bd4.svg";
    const Ki = n.p + "static/media/third.617f25744fc6777c72a30292362c8490.svg";
    const Ji = n.p + "static/media/last.502eb72f9c8deae29fb10a728ff6037e.svg"
      , Xi = () => {
        const e = pe()
          , t = function() {
            return "app-prizes".concat(arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : "")
        }
          , n = [{
            icon: Vi,
            place: "1 \u043c\u0435\u0441\u0442\u043e",
            text: (0,
            Yt.jsxs)(Yt.Fragment, {
                children: ["\u0421\u0438\u0441\u0442\u0435\u043c\u0430 \u0432\u0438\u0440\u0442\u0443\u0430\u043b\u044c\u043d\u043e\u0439", (0,
                Yt.jsx)("br", {}), " \u0440\u0435\u0430\u043b\u044c\u043d\u043e\u0441\u0442\u0438 Oculus"]
            })
        }, {
            icon: Zi,
            place: "2-3 \u043c\u0435\u0441\u0442\u043e",
            text: (0,
            Yt.jsxs)(Yt.Fragment, {
                children: ["\u0418\u0433\u0440\u043e\u0432\u0430\u044f \u043a\u043e\u043d\u0441\u043e\u043b\u044c", (0,
                Yt.jsx)("br", {}), " Nintendo Switch OLED"]
            })
        }, {
            icon: Ki,
            place: "4-10 \u043c\u0435\u0441\u0442\u043e",
            text: (0,
            Yt.jsxs)(Yt.Fragment, {
                children: ["\u041f\u043e\u0440\u0442\u0430\u0442\u0438\u0432\u043d\u0430\u044f \u0438\u0433\u0440\u043e\u0432\u0430\u044f", (0,
                Yt.jsx)("br", {}), " \u043f\u0440\u0438\u0441\u0442\u0430\u0432\u043a\u0430 SUP GAME", (0,
                Yt.jsx)("br", {}), " BOX X7M"]
            })
        }, {
            icon: Ji,
            place: (0,
            Yt.jsxs)(Yt.Fragment, {
                children: ["10 \u0440\u0430\u043d\u0434\u043e\u043c\u043d\u044b\u0445", (0,
                Yt.jsx)("br", {}), " \u043f\u043e\u0431\u0435\u0434\u0438\u0442\u0435\u043b\u0435\u0439"]
            }),
            text: (0,
            Yt.jsxs)(Yt.Fragment, {
                children: ["\u042d\u043a\u0441\u043a\u043b\u044e\u0437\u0438\u0432\u043d\u044b\u0439", (0,
                Yt.jsx)("br", {}), "\u0441\u0432\u0438\u0442\u0448\u043e\u0442"]
            })
        }];
        return (0,
        Yt.jsxs)("div", {
            className: t() + " " + t("_bg"),
            children: [(0,
            Yt.jsxs)("div", {
                className: t("--header-wrapper"),
                children: [(0,
                Yt.jsx)("img", {
                    onClick: () => e(-1),
                    className: t("--image"),
                    src: ko,
                    alt: ""
                }), (0,
                Yt.jsx)("div", {
                    className: t("--header"),
                    children: "\u041f\u0440\u0438\u0437\u044b"
                })]
            }), (0,
            Yt.jsx)("div", {
                className: t("--items-wrapper"),
                children: (0,
                Yt.jsx)("div", {
                    className: t("--items-container"),
                    children: null === n || void 0 === n ? void 0 : n.map((e => (0,
                    Yt.jsx)(Gi, c({}, e), null === e || void 0 === e ? void 0 : e.place)))
                })
            }), (0,
            Yt.jsx)(Kt, {})]
        })
    }
      , _i = n.p + "static/media/error.b8e1701b239fb72f2d52.png"
      , $i = () => {
        const e = e => "app-technical-work".concat(e || "");
        return (0,
        Yt.jsx)("div", {
            className: e(),
            children: (0,
            Yt.jsxs)("div", {
                className: e("--content"),
                children: [(0,
                Yt.jsx)("div", {
                    className: e("--icon-wrapper"),
                    children: (0,
                    Yt.jsx)("img", {
                        className: e("--icon"),
                        src: _i,
                        alt: ""
                    })
                }), (0,
                Yt.jsxs)("div", {
                    className: e("--text"),
                    children: ["\u0414\u0430-\u0434\u0430, \u043c\u044b \u0442\u043e\u0436\u0435 \u043d\u0435 \u043b\u044e\u0431\u0438\u043c,", (0,
                    Yt.jsx)("br", {}), " \u043a\u043e\u0433\u0434\u0430 \u0447\u0442\u043e-\u0442\u043e \u043d\u0435 \u0440\u0430\u0431\u043e\u0442\u0430\u0435\u0442."]
                }), (0,
                Yt.jsxs)("div", {
                    className: e("--text"),
                    children: ["\u041d\u043e \u043f\u0440\u044f\u043c\u043e \u0441\u0435\u0439\u0447\u0430\u0441 \u043c\u044b", (0,
                    Yt.jsx)("br", {}), " \u0443\u0441\u0442\u0440\u0430\u043d\u044f\u0435\u043c \u043e\u0448\u0438\u0431\u043a\u0443. \u0421\u043a\u043e\u0440\u043e", (0,
                    Yt.jsx)("br", {}), " \u0432\u0441\u0451 \u0441\u043d\u043e\u0432\u0430 \u0431\u0443\u0434\u0435\u0442 \u043b\u0435\u0442\u0430\u0442\u044c!"]
                })]
            })
        })
    }
      , el = window.Telegram.WebApp || tn
      , tl = el.platform = "ios";
    console.log();
    const nl = ["macos", "tdesktop", "weba", "web"].includes(el.platform)
      , rl = "task_result"
      , al = "squad_popup"
      , ol = () => {
        var e, t, n, r;
        const [o,i] = (0,
        a.useState)(!0)
          , [l,s] = (0,
        a.useState)(!1)
          , [u,d] = (0,
        a.useState)(null)
          , [p,f] = (0,
        a.useState)(null)
          , [m,h] = (0,
        a.useState)(null)
          , [g,v] = (0,
        a.useState)(null)
          , [y,b] = (0,
        a.useState)()
          , x = +(null === p || void 0 === p || null === (e = p.squad) || void 0 === e || null === (t = e.creator) || void 0 === t ? void 0 : t.telegram_user_id) === +(null === p || void 0 === p ? void 0 : p.telegram_id);
        return console.log("hasOwnSquad", x),
        console.log("user?.squad?.creator?.telegram_user_id", null === p || void 0 === p || null === (n = p.squad) || void 0 === n || null === (r = n.creator) || void 0 === r ? void 0 : r.telegram_user_id),
        console.log("user?.telegram_user_id", null === p || void 0 === p ? void 0 : p.telegram_id),
        (0,
        a.useEffect)(( () => {
            console.log("[Ladybug.Init] > start"),
            console.log("init", {
                initData: el.initData || "",
                version: el.version || "",
                platform: tl
            });
            const e = new URLSearchParams(window.location.search).get("invitedById");
            e && console.log("[Ladybug.Init] > startParam: " + e),
            el.isVersionAtLeast("6.1") && (el.setHeaderColor("#19151B"),
            el.setBackgroundColor("#19151B"),
            console.log("[Ladybug.Init] > set header color"),
            console.log("[Ladybug.Init] > set background color")),
            el.isVersionAtLeast("6.2") && (el.enableClosingConfirmation(),
            console.log("[Ladybug.Init] > enable closing confirmation")),
            el.isVersionAtLeast("7.7") && (el.disableVerticalSwipes(),
            console.log("[Ladybug.Init] > disable vertical swipes")),
            co.post("".concat(Tt, "/api/ladybug-game/init"), {
                initData: el.initData || "",
                version: el.version || "",
                platform: tl,
                invitedBy: e
            }).then((e => {
                var t, n, r, a, o, i, l, s, u, d, p, m, g, y, x;
                e = e.data,
                console.log("response", e);
                const {telegram_user_id: w, username: A, last_name: k, first_name: S, photoPath: E, score: j, auth_token: N, guideCompleted: C, tasks: R, status: O, tutorials: T, lastSquadJoin: L} = e.user;
                let U = {
                    telegram_id: w,
                    username: A,
                    lastName: k,
                    firstName: S,
                    coins: j,
                    photo: E,
                    chatMember: "kicked" !== O && "left" !== O,
                    guideCompleted: C,
                    authToken: N,
                    tasks: R,
                    squad: null === (t = e) || void 0 === t ? void 0 : t.squad,
                    dailyBonusClaimed: null === (n = e) || void 0 === n ? void 0 : n.dailyBonusClaimed,
                    isShowBanner: null === (r = e) || void 0 === r ? void 0 : r.techBanner,
                    tutorials: T,
                    lastSquadJoin: L,
                    invite_squad_id: null === (a = e) || void 0 === a ? void 0 : a.invite_squad_id
                };
                var P, I, F, z, M;
                null !== (o = e) && void 0 !== o && o.startParam && b(null === (P = e) || void 0 === P ? void 0 : P.startParam);
                null !== (i = e) && void 0 !== i && null !== (l = i.qr_task) && void 0 !== l && l.coins && (h({
                    success: !0,
                    text: "<strong>QR-\u043a\u043e\u0434 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043d!</br>\u0422\u044b \u043f\u043e\u043b\u0443\u0447\u0430\u0435\u0448\u044c +<span>".concat(null === (I = e) || void 0 === I || null === (F = I.qr_task) || void 0 === F ? void 0 : F.coins, "&nbsp;\u0431\u0430\u043b\u043b\u043e\u0432!</span></strong>"),
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                v(rl),
                U = c(c({}, U), {}, {
                    coins: U.coins + (null === (z = e) || void 0 === z || null === (M = z.qr_task) || void 0 === M ? void 0 : M.coins)
                }));
                null !== (s = e) && void 0 !== s && null !== (u = s.qr) && void 0 !== u && u.isActivated && (h({
                    success: !0,
                    text: "<strong>\u0422\u044b \u0443\u0436\u0435 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043b \u044d\u0442\u043e\u0442 QR-\u043a\u043e\u0434 \u0438<br/> \u043f\u043e\u043b\u0443\u0447\u0438\u043b \u0437\u0430 \u043d\u0435\u0433\u043e \u0431\u0430\u043b\u043b\u044b!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                v(rl)),
                null !== (d = e) && void 0 !== d && null !== (p = d.qr_task) && void 0 !== p && p.isActivated && (h({
                    success: !0,
                    text: "<strong>\u0422\u044b \u0443\u0436\u0435 \u043e\u0442\u0441\u043a\u0430\u043d\u0438\u0440\u043e\u0432\u0430\u043b \u044d\u0442\u043e\u0442 QR-\u043a\u043e\u0434 \u0438<br/> \u043f\u043e\u043b\u0443\u0447\u0438\u043b \u0437\u0430 \u043d\u0435\u0433\u043e \u0431\u0430\u043b\u043b\u044b!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                v(rl)),
                console.log("response", e),
                null !== (m = e) && void 0 !== m && null !== (g = m.qr) && void 0 !== g && g.invalidQr && (h({
                    success: !1,
                    text: "<strong>\u041e\u0439, \u044d\u0442\u043e \u043d\u0435\u0432\u0435\u0440\u043d\u044b\u0439 QR-\u043a\u043e\u0434 ;(<br/>\u041f\u043e\u043f\u0440\u043e\u0431\u0443\u0439 \u0435\u0449\u0435 \u0440\u0430\u0437!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                v(rl)),
                null !== (y = e) && void 0 !== y && null !== (x = y.qr_task) && void 0 !== x && x.invalidQr && (h({
                    success: !1,
                    text: "<strong>\u041e\u0439, \u044d\u0442\u043e \u043d\u0435\u0432\u0435\u0440\u043d\u044b\u0439 QR-\u043a\u043e\u0434 ;(<br/>\u041f\u043e\u043f\u0440\u043e\u0431\u0443\u0439 \u0435\u0449\u0435 \u0440\u0430\u0437!</strong>",
                    buttonText: "\u0425\u043e\u0440\u043e\u0448\u043e"
                }),
                v(rl)),
                console.log("[Ladybug.Init] > user: " + U.username),
                f(U)
            }
            )).catch((e => {
                console.error("[Ladybug.Init] > error", e),
                s(!0)
            }
            )).finally(( () => {
                console.log("[Ladybug.Init] > ready"),
                i(!1),
                el.expand(),
                el.ready()
            }
            ))
        }
        ), []),
        (0,
        a.useEffect)(( () => {
            null !== p && void 0 !== p && p.invite_squad_id && co.get("".concat(Tt, "/api/squads/").concat(null === p || void 0 === p ? void 0 : p.invite_squad_id)).then((e => {
                var t, n, r, a, o, i, l;
                h({
                    title: null === e || void 0 === e || null === (t = e.data) || void 0 === t ? void 0 : t.name,
                    image: ai[null === e || void 0 === e || null === (n = e.data) || void 0 === n ? void 0 : n.photo_id],
                    coins: (null === e || void 0 === e || null === (r = e.data) || void 0 === r ? void 0 : r.coins) || 0,
                    place: (null === e || void 0 === e || null === (a = e.data) || void 0 === a ? void 0 : a.place) || "-",
                    players: (null === e || void 0 === e || null === (o = e.data) || void 0 === o ? void 0 : o.members) || 0,
                    id: null === e || void 0 === e || null === (i = e.data) || void 0 === i ? void 0 : i.id,
                    creator: (null === e || void 0 === e || null === (l = e.data) || void 0 === l ? void 0 : l.creator) || {},
                    squad: null === e || void 0 === e ? void 0 : e.data,
                    getSquadListAPI: () => {}
                    ,
                    invited: !0
                }),
                v(al)
            }
            ))
        }
        ), [null === p || void 0 === p ? void 0 : p.invite_squad_id]),
        o ? (console.log("Loading"),
        (0,
        Yt.jsx)(on, {})) : (0,
        Yt.jsxs)(kn.Provider, {
            value: {
                user: p,
                setUser: f
            },
            children: [(0,
            Yt.jsx)(ut, {
                basename: "",
                children: (0,
                Yt.jsxs)(Re, {
                    children: [(0,
                    Yt.jsx)(Ne, {
                        path: bt,
                        element: (0,
                        Yt.jsx)(bi, {
                            error: l,
                            isChatMember: null === p || void 0 === p ? void 0 : p.chatMember,
                            shouldNotReload: !!y
                        })
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: xt,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(gi, {
                            startParamValue: u
                        })
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: wt,
                        element: (0,
                        Yt.jsx)(Ni, {})
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: Nt,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : null !== p && void 0 !== p && p.squad && x ? (0,
                        Yt.jsx)(Di, {}) : (0,
                        Yt.jsx)(Fi, {})
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: Ot,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(Xi, {})
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: Ct,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(Mi, {})
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: Rt,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(Di, {})
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: At,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(fo, {})
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: kt,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(ei, {
                            timeValue: Qt[qt],
                            gameType: qt
                        })
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: Et,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(ei, {
                            gameType: Dt,
                            timeValue: Qt[Dt]
                        })
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: jt,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(ei, {
                            gameType: Ht
                        })
                    }), (0,
                    Yt.jsx)(Ne, {
                        path: St,
                        element: null !== p && void 0 !== p && p.isShowBanner ? (0,
                        Yt.jsx)($i, {}) : (0,
                        Yt.jsx)(Pi, {})
                    })]
                })
            }), (0,
            Yt.jsx)(gn, {}), nl && (0,
            Yt.jsx)(Ri, {}), rl === g && (0,
            Yt.jsx)(Mn, c({
                success: m.success,
                title: m.title,
                text: m.text,
                onClose: () => {
                    v(null),
                    h(null)
                }
            }, m)), al === g && (0,
            Yt.jsx)(Wi, c({
                onClose: () => {
                    v(null),
                    h(null)
                }
            }, m))]
        })
    }
      , il = e => {
        e && e instanceof Function && n.e(488).then(n.bind(n, 2488)).then((t => {
            let {getCLS: n, getFID: r, getFCP: a, getLCP: o, getTTFB: i} = t;
            n(e),
            r(e),
            a(e),
            o(e),
            i(e)
        }
        ))
    }
      , ll = window.Telegram.WebApp;
    wn().setWindowSize(ll),
    window.addEventListener("resize", ( () => wn().setWindowSize(ll)), !1),
    ll.onEvent("viewportChanged", (e => e && wn().setWindowSize(ll)));
    o.createRoot(document.getElementById("root")).render((0,
    Yt.jsx)(ol, {})),
    il()
}
)();
//# sourceMappingURL=main.e2d3e81b.js.map
