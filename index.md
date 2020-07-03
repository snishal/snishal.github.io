---
layout: default
title: Home
---
<div class="container mt-5">
    <!-- <div class="float-right p-4">
        <img src="self.jpg" style="width:15em; height:15em" alt="Image">
    </div> -->
    <div class="jumbotron text-white bg-primary">
        <h1 class="display-3 text-white">Hello, World!</h1>
        <p class="lead">
            {{site.introduction}}
        </p>
        <h4><footer class="blockquote-footer">{{ site.name }}</footer></h4>
        <hr class="my-4" style="border-color:white;">
        <div class="lead text-right">
            <a href="{{ site.github }}" target="_blank" class="text-white p-2"><i class="fa fa-github fa-3x" aria-hidden="true"></i></a>
            <a href="{{ site.facebook }}" target="_blank" class="text-white p-2"><i class="fa fa-facebook fa-3x" aria-hidden="true"></i></a>
            <a href="{{ site.linkedin }}" target="_blank" class="text-white p-2"><i class="fa fa-linkedin fa-3x" aria-hidden="true"></i></a>
            <a href="mailto:{{ site.mail }}" target="_blank" class="text-white p-2"><i class="fa fa-envelope fa-3x" aria-hidden="true"></i></a>
        </div>
    </div>
</div>