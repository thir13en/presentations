# Compilation

<arrow v-click x1="450" y1="200" x2="530" y2="200" color="#564" width="3" arrowSize="1" />

<div class="grid grid-cols-2 gap-25">
```c {all}
int fib(int n) {
  if (n == 1) return 1;
  if (n == 2) return 1;
  return fib(n-1) + fib(n-2);
}
```

<div v-click>
```wasm {all}
(module
  (table $table0 0 funcref)
  (memory $memory (;0;) (export "memory") 1)
  (func $fib (;0;) (export "fib") (param $var0 i32)
    (local $var1 i32)
    i32.const 1
    local.set $var1
    block $label0
      local.get $var0
      i32.const -1
      i32.add
      local.tee $var0
      i32.const 2
      i32.lt_u
...
)
```
</div>

</div>

<img src="assets/dt-white.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />
