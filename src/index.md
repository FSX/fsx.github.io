Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
sollicitudin, sapien vitae convallis luctus, nisl tortor sollicitudin
nisi, nec semper mauris mauris ac ligula. Phasellus et augue ut purus
bibendum lobortis in ut leo. Duis at lacus sapien. Praesent non blandit
mi. Phasellus ac nisi in ante interdum volutpat.

<ul class="icon-button-bar">
  <li>
    <a href="#">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 521 521" class="icon icon-menu">
        <use xlink:href="#icon-github"></use>
      </svg>
      Github
    </a>
  </li>
  <li>
    <a href="#">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 521 521" class="icon icon-menu">
        <use xlink:href="#icon-linkedin"></use>
      </svg>
      LinkedIn
    </a>
  </li>
</ul>

## Portfolio

<div class="block">
  <h3>Lorem Ipsum</h3>
  <p>Aenean facilisis, lacus ac dictum dictum, risus orci vulputate
     neque, at  vehicula augue quam ac eros. Etiam eget lorem quis odio
     tincidunt porta. In maximus, sem a tempor laoreet, magna urna
     viverra turpis, quis imperdiet velit velit sit amet mauris. </p>
</div>

<div class="block">
  <img src="http://placekitten.com/100/100" alt="cat" />
  <h3>Lorem Ipsum</h3>
  <p>Aenean facilisis, lacus ac dictum dictum, risus orci vulputate
     neque, at  vehicula augue quam ac eros. Etiam eget lorem quis odio
     tincidunt porta. In maximus, sem a tempor laoreet, magna urna
     viverra turpis, quis imperdiet velit velit sit amet mauris. </p>
</div>

## Skills

Cras non massa accumsan, blandit urna at, euismod lacus. Nullam aliquet
dolor quis est viverra, vel placerat orci dapibus. Cras feugiat nulla
non vulputate convallis. In lacinia, nisi et blandit dapibus, odio
dolor sodales turpis, ac maximus ligula nibh in metus. Quisque blandit
augue in tortor malesuada rutrum. Morbi faucibus efficitur justo, sed
sodales arcu bibendum eget. Donec ut tincidunt nibh. In quis felis
sodales, gravida mauris tempus, auctor lacus.


## Code

```
use std

pkg util =
  generic insort : (xs : @a[:], cmp : (a : @a, b : @a -> std.order) -> void)
;;

generic insort = {xs, cmp
  for var i = 1; i < xs.len; i++
    for var j = i; j > 0; j--
      match cmp(xs[j-1], xs[j])
      | `std.After: std.swap(&xs[j], &xs[j-1])
      | _: break
      ;;
    ;;
  ;;
}
```

Example.
