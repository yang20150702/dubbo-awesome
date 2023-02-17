# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.027 ops/ms
# Warmup Iteration   2: 2.277 ops/ms
# Warmup Iteration   3: 5.347 ops/ms
Iteration   1: 5.404 ops/ms
Iteration   2: 5.483 ops/ms
Iteration   3: 5.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.486 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (5.404, 5.486, 5.572), stdev = 0.084
  CI (99.9%): [3.954, 7.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.819 ops/ms
# Warmup Iteration   2: 4.885 ops/ms
# Warmup Iteration   3: 5.946 ops/ms
Iteration   1: 6.082 ops/ms
Iteration   2: 6.149 ops/ms
Iteration   3: 6.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.144 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (6.082, 6.144, 6.200), stdev = 0.059
  CI (99.9%): [5.069, 7.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.575 ops/ms
# Warmup Iteration   2: 4.748 ops/ms
# Warmup Iteration   3: 5.832 ops/ms
Iteration   1: 5.921 ops/ms
Iteration   2: 5.802 ops/ms
Iteration   3: 5.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.891 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (5.802, 5.891, 5.948), stdev = 0.078
  CI (99.9%): [4.472, 7.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.580 ops/ms
# Warmup Iteration   2: 4.176 ops/ms
# Warmup Iteration   3: 4.921 ops/ms
Iteration   1: 5.161 ops/ms
Iteration   2: 5.127 ops/ms
Iteration   3: 5.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.200 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (5.127, 5.200, 5.311), stdev = 0.098
  CI (99.9%): [3.411, 6.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.611 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.645 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.008 ms/op
Iteration   1: 5.351 ±(99.9%) 0.018 ms/op
Iteration   2: 5.250 ±(99.9%) 0.013 ms/op
Iteration   3: 5.310 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.304 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (5.250, 5.304, 5.351), stdev = 0.051
  CI (99.9%): [4.370, 6.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.741 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.535 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.161 ±(99.9%) 0.007 ms/op
Iteration   1: 4.908 ±(99.9%) 0.012 ms/op
Iteration   2: 5.555 ±(99.9%) 0.011 ms/op
Iteration   3: 5.095 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.186 ±(99.9%) 6.079 ms/op [Average]
  (min, avg, max) = (4.908, 5.186, 5.555), stdev = 0.333
  CI (99.9%): [≈ 0, 11.265] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.095 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.437 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.283 ±(99.9%) 0.010 ms/op
Iteration   1: 5.234 ±(99.9%) 0.009 ms/op
Iteration   2: 5.079 ±(99.9%) 0.010 ms/op
Iteration   3: 5.179 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.164 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (5.079, 5.164, 5.234), stdev = 0.079
  CI (99.9%): [3.728, 6.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.078 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 7.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.004 ±(99.9%) 0.016 ms/op
Iteration   1: 6.169 ±(99.9%) 0.011 ms/op
Iteration   2: 5.815 ±(99.9%) 0.017 ms/op
Iteration   3: 6.092 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.025 ±(99.9%) 3.387 ms/op [Average]
  (min, avg, max) = (5.815, 6.025, 6.169), stdev = 0.186
  CI (99.9%): [2.638, 9.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.096 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.310 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.681 ±(99.9%) 0.023 ms/op
Iteration   1: 5.540 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  23.231 ms/op
                 createUser·p0.9999: 28.541 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 5.291 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.220 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.315 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  25.210 ms/op
                 createUser·p0.9999: 29.491 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   3: 5.324 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.451 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.242 ms/op
                 createUser·p0.99:   10.551 ms/op
                 createUser·p0.999:  24.344 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178292
  mean =      5.383 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 74357 
    [ 5.000,  7.500) = 95839 
    [ 7.500, 10.000) = 6145 
    [10.000, 12.500) = 1298 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     24.505 ms/op
     p(99.9900) =     29.464 ms/op
     p(99.9990) =     30.934 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.489 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.402 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.473 ±(99.9%) 0.020 ms/op
Iteration   1: 5.421 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.712 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   11.066 ms/op
                 existUser·p0.999:  25.229 ms/op
                 existUser·p0.9999: 27.790 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 5.130 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.029 ms/op
                 existUser·p0.95:   6.758 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  23.888 ms/op
                 existUser·p0.9999: 32.654 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   3: 5.211 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  15.037 ms/op
                 existUser·p0.9999: 30.789 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182682
  mean =      5.251 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 87173 
    [ 5.000,  7.500) = 87328 
    [ 7.500, 10.000) = 6103 
    [10.000, 12.500) = 1399 
    [12.500, 15.000) = 393 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     18.360 ms/op
     p(99.9900) =     31.492 ms/op
     p(99.9990) =     33.347 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.780 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.108 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.402 ±(99.9%) 0.018 ms/op
Iteration   1: 5.510 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.875 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.307 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  23.984 ms/op
                 getUser·p0.9999: 30.441 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   2: 5.689 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   12.419 ms/op
                 getUser·p0.999:  25.617 ms/op
                 getUser·p0.9999: 33.441 ms/op
                 getUser·p1.00:   34.865 ms/op

Iteration   3: 5.516 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.486 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  27.329 ms/op
                 getUser·p0.9999: 31.595 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172256
  mean =      5.570 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 52790 
    [ 5.000,  7.500) = 109942 
    [ 7.500, 10.000) = 6694 
    [10.000, 12.500) = 1979 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.486 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     25.296 ms/op
     p(99.9900) =     31.581 ms/op
     p(99.9990) =     34.581 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.544 ±(99.9%) 0.344 ms/op
# Warmup Iteration   2: 7.968 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.816 ±(99.9%) 0.027 ms/op
Iteration   1: 6.540 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   12.272 ms/op
                 listUser·p0.999:  28.284 ms/op
                 listUser·p0.9999: 31.922 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   2: 6.382 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.039 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.705 ms/op
                 listUser·p0.999:  28.536 ms/op
                 listUser·p0.9999: 32.636 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   3: 6.452 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.232 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  24.557 ms/op
                 listUser·p0.9999: 28.675 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148646
  mean =      6.457 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6163 
    [ 5.000,  7.500) = 123327 
    [ 7.500, 10.000) = 14734 
    [10.000, 12.500) = 3192 
    [12.500, 15.000) = 745 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.679 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     12.173 ms/op
     p(99.9000) =     27.373 ms/op
     p(99.9900) =     32.215 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.486 ± 1.532  ops/ms
ClientPb.existUser                       thrpt       3   6.144 ± 1.075  ops/ms
ClientPb.getUser                         thrpt       3   5.891 ± 1.418  ops/ms
ClientPb.listUser                        thrpt       3   5.200 ± 1.788  ops/ms
ClientPb.createUser                       avgt       3   5.304 ± 0.934   ms/op
ClientPb.existUser                        avgt       3   5.186 ± 6.079   ms/op
ClientPb.getUser                          avgt       3   5.164 ± 1.436   ms/op
ClientPb.listUser                         avgt       3   6.025 ± 3.387   ms/op
ClientPb.createUser                     sample  178292   5.383 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.451           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.505           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.464           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.293           ms/op
ClientPb.existUser                      sample  182682   5.251 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.999           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.360           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.492           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  172256   5.570 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.296           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.581           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.865           ms/op
ClientPb.listUser                       sample  148646   6.457 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.679           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.373           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.215           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
