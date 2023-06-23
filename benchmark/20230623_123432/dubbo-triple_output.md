# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 4.377 ops/ms
# Warmup Iteration   3: 8.329 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 9.059 ops/ms
Iteration   3: 9.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.062 ±(99.9%) 4.032 ops/ms [Average]
  (min, avg, max) = (8.843, 9.062, 9.285), stdev = 0.221
  CI (99.9%): [5.030, 13.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ops/ms
# Warmup Iteration   2: 8.538 ops/ms
# Warmup Iteration   3: 9.196 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.433 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.362 ±(99.9%) 2.121 ops/ms [Average]
  (min, avg, max) = (9.228, 9.362, 9.433), stdev = 0.116
  CI (99.9%): [7.242, 11.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.518 ops/ms
# Warmup Iteration   2: 8.083 ops/ms
# Warmup Iteration   3: 9.037 ops/ms
Iteration   1: 9.395 ops/ms
Iteration   2: 9.369 ops/ms
Iteration   3: 9.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.443 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (9.369, 9.443, 9.565), stdev = 0.107
  CI (99.9%): [7.498, 11.388] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 6.757 ops/ms
# Warmup Iteration   3: 7.442 ops/ms
Iteration   1: 7.926 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 7.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.815 ±(99.9%) 2.588 ops/ms [Average]
  (min, avg, max) = (7.655, 7.815, 7.926), stdev = 0.142
  CI (99.9%): [5.227, 10.403] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.691 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.007 ms/op
Iteration   1: 3.452 ±(99.9%) 0.013 ms/op
Iteration   2: 3.490 ±(99.9%) 0.009 ms/op
Iteration   3: 3.575 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.506 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.452, 3.506, 3.575), stdev = 0.063
  CI (99.9%): [2.358, 4.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.424 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.006 ms/op
Iteration   1: 3.331 ±(99.9%) 0.007 ms/op
Iteration   2: 3.379 ±(99.9%) 0.005 ms/op
Iteration   3: 3.327 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.346 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (3.327, 3.346, 3.379), stdev = 0.029
  CI (99.9%): [2.818, 3.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.231 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.005 ms/op
Iteration   1: 3.392 ±(99.9%) 0.011 ms/op
Iteration   2: 3.454 ±(99.9%) 0.006 ms/op
Iteration   3: 3.488 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.445 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (3.392, 3.445, 3.488), stdev = 0.049
  CI (99.9%): [2.552, 4.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.611 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.010 ms/op
Iteration   1: 4.075 ±(99.9%) 0.010 ms/op
Iteration   2: 4.016 ±(99.9%) 0.015 ms/op
Iteration   3: 4.002 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.031 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (4.002, 4.031, 4.075), stdev = 0.039
  CI (99.9%): [3.323, 4.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.404 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.013 ms/op
Iteration   1: 3.484 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  19.305 ms/op
                 createUser·p0.9999: 27.480 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.561 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.441 ms/op
                 createUser·p0.999:  22.217 ms/op
                 createUser·p0.9999: 27.495 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.551 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  20.612 ms/op
                 createUser·p0.9999: 27.788 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271600
  mean =      3.531 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6210 
    [ 2.500,  5.000) = 260163 
    [ 5.000,  7.500) = 3946 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     20.165 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     29.075 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.903 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.500 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.408 ms/op
                 existUser·p0.999:  19.963 ms/op
                 existUser·p0.9999: 21.782 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.322 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  18.535 ms/op
                 existUser·p0.9999: 28.663 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.835 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.119 ms/op
                 existUser·p0.9999: 26.234 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281638
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14415 
    [ 2.500,  5.000) = 260994 
    [ 5.000,  7.500) = 5314 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     27.815 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.470 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.011 ms/op
Iteration   1: 3.755 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.835 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  21.164 ms/op
                 getUser·p0.9999: 31.097 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   2: 3.368 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 25.444 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.522 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.885 ms/op
                 getUser·p0.999:  20.922 ms/op
                 getUser·p0.9999: 26.769 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270888
  mean =      3.541 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6773 
    [ 2.500,  5.000) = 253373 
    [ 5.000,  7.500) = 8705 
    [ 7.500, 10.000) = 1489 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     21.004 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     31.299 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.163 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.014 ms/op
Iteration   1: 4.230 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  20.818 ms/op
                 listUser·p0.9999: 26.144 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.103 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.450 ms/op
                 listUser·p0.999:  16.516 ms/op
                 listUser·p0.9999: 17.708 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 4.025 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.032 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233132
  mean =      4.117 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 224613 
    [ 5.000,  7.500) = 6289 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     24.672 ms/op
     p(99.9990) =     26.914 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.062 ± 4.032  ops/ms
ClientPb.existUser                       thrpt       3   9.362 ± 2.121  ops/ms
ClientPb.getUser                         thrpt       3   9.443 ± 1.945  ops/ms
ClientPb.listUser                        thrpt       3   7.815 ± 2.588  ops/ms
ClientPb.createUser                       avgt       3   3.506 ± 1.148   ms/op
ClientPb.existUser                        avgt       3   3.346 ± 0.528   ms/op
ClientPb.getUser                          avgt       3   3.445 ± 0.892   ms/op
ClientPb.listUser                         avgt       3   4.031 ± 0.709   ms/op
ClientPb.createUser                     sample  271600   3.531 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.176           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.165           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.558           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  281638   3.406 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.616           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.815           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.147           ms/op
ClientPb.getUser                        sample  270888   3.541 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.448           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.004           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  233132   4.117 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.564           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.672           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
