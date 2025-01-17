---
title: Solving Conflicts with Escape Characters
module: topic-07
permalink: /topic-07/esc-about/
---

<div class="divider-heading"></div>

As you may have discovered, HTML specifies that certain characters are "reserved" or serve a special purpose for browsers. The most obvious conflicts are the _greater-than_ and _less-than_ characters (`<`, `>`), since these identify tags to browsers in HTML. Any character that may be accidentally interpreted as HTML by the browser _should_ be replaced with its **escape code** equivalent.

There are also characters that have no easy “keyboard” equivalent, (such as the copyright symbol - &#169; ) in which case an escape code must be used.


<div class="row">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-danger">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-question-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Question:
          </h4>
        </div>
          <div class="panel-body">
            <p>So what is a developer to do if they need to write some math (or something else less stressful than including comparison operators in their page)?</p>
          </div>
      </div>
    </div>
  </div>
</div>
<div class="row">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-success">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-exclamation-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Answer:
          </h4>
        </div>
          <div class="panel-body">
            <p>Use special codes, known as escape characters, that the browser can use to render the intended character!</p>
          </div>
      </div>
    </div>
  </div>
</div>


This is not a fun process, but one that is necessary since HTML is a language.

Also, for those of you who are more "security-minded" or wanting to protect yourself and your client from "middle-man attacks," using escape characters is critical, as evidence by <a href="https://owasp-top-10-proactive-controls-2018.readthedocs.io/en/latest/c4-encode-escape-data.html" target="_new">some discussions around the web</a>.
