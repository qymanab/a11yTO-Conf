Rob Dodson

@rob\_dodson

a11y cast — podcast

* What is AOM?
  * Accessibility Object Model
    * A proposed JS API to modify and eexplore web accessiblity tree
      * lill in gaps in ARIA
      * Expose computed properties
      * Enable accessiblilty for custom-drawn UI
* Filling in Gaps in ARIA
  * Attribute and property parity
    * \<element role=“tab”\>
    * $(element).role = “tab”
  * Relationships
    * no more generating IDs
    * possible solutions for labeling things in Shadow DOM
  * github whatwg/html \#3515
  * ARIA 1.2
* Custom Elements
  * provides default semantics for custom elements
  * Can do per-instance settings
  * ARIA is an explicit signal from the developer
    * ARIA\>Per Instance\> Default
* User action event
  * A semantic action triggered by Assistive Technology
    * Increment, dismiss, etc
  * 1\. Map actions to DOM events
  * 2\. Add new inputEvent types
    * Increment, decrement, dismiss, scrollPageUp, scrollPageDown
* Expose computed properties for testing
* Accessibility for custom drawn UI
  * create
  * Virtual accessibility nodes
    * Manipulate accessibility tree without having to attach it to the thing in a Dom?
    * Attaching a Node, Attaching a node, Positioning a node, listening for events
* How baked is this?
  * ARIA 1.2 Properties — pretty baked
  * Custom element semantics — waiting to be baked
  * User action events — a tricky bake
  * Virtual accessibility nodes — baking!
  * Computed accessible nodes — dessert (low priority)
* TPAC
* github.com/wicg/aom