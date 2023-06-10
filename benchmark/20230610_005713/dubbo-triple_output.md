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
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 5.715 ops/ms
# Warmup Iteration   3: 8.564 ops/ms
Iteration   1: 9.001 ops/ms
Iteration   2: 9.227 ops/ms
Iteration   3: 9.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.125 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (9.001, 9.125, 9.227), stdev = 0.115
  CI (99.9%): [7.032, 11.219] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.044 ops/ms
# Warmup Iteration   2: 8.729 ops/ms
# Warmup Iteration   3: 9.106 ops/ms
Iteration   1: 9.696 ops/ms
Iteration   2: 9.252 ops/ms
Iteration   3: 9.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.555 ±(99.9%) 4.801 ops/ms [Average]
  (min, avg, max) = (9.252, 9.555, 9.719), stdev = 0.263
  CI (99.9%): [4.755, 14.356] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.834 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.930 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 9.408 ops/ms
Iteration   3: 9.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.334 ±(99.9%) 1.375 ops/ms [Average]
  (min, avg, max) = (9.257, 9.334, 9.408), stdev = 0.075
  CI (99.9%): [7.959, 10.710] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 6.884 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 8.051 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.105 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (8.051, 8.105, 8.192), stdev = 0.076
  CI (99.9%): [6.716, 9.493] (assumes normal distribution)


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
# Warmup Iteration   1: 9.930 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.010 ms/op
Iteration   1: 3.479 ±(99.9%) 0.005 ms/op
Iteration   2: 3.343 ±(99.9%) 0.012 ms/op
Iteration   3: 3.348 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 1.400 ms/op [Average]
  (min, avg, max) = (3.343, 3.390, 3.479), stdev = 0.077
  CI (99.9%): [1.990, 4.790] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.213 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.004 ms/op
Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
Iteration   3: 3.318 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.280, 3.320, 3.362), stdev = 0.041
  CI (99.9%): [2.566, 4.073] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.861 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.005 ms/op
Iteration   1: 3.421 ±(99.9%) 0.006 ms/op
Iteration   2: 3.527 ±(99.9%) 0.004 ms/op
Iteration   3: 3.383 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.383, 3.444, 3.527), stdev = 0.075
  CI (99.9%): [2.077, 4.810] (assumes normal distribution)


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
# Warmup Iteration   1: 11.308 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.014 ms/op
Iteration   1: 3.952 ±(99.9%) 0.013 ms/op
Iteration   2: 3.897 ±(99.9%) 0.015 ms/op
Iteration   3: 3.904 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.918 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.897, 3.918, 3.952), stdev = 0.030
  CI (99.9%): [3.363, 4.472] (assumes normal distribution)


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
# Warmup Iteration   1: 9.093 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.011 ms/op
Iteration   1: 3.376 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  19.476 ms/op
                 createUser·p0.9999: 24.282 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  22.005 ms/op
                 createUser·p0.9999: 26.991 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  16.105 ms/op
                 createUser·p0.9999: 22.067 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280727
  mean =      3.419 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12400 
    [ 2.500,  5.000) = 260573 
    [ 5.000,  7.500) = 6806 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     16.238 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.220 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 8.720 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  10.324 ms/op
                 existUser·p0.9999: 20.430 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  15.535 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.487 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  21.079 ms/op
                 existUser·p0.9999: 27.356 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284938
  mean =      3.367 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11745 
    [ 2.500,  5.000) = 267392 
    [ 5.000,  7.500) = 4701 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     11.978 ms/op
     p(99.9900) =     25.969 ms/op
     p(99.9990) =     28.158 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 8.630 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
Iteration   1: 3.372 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  20.294 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.426 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  21.758 ms/op
                 getUser·p0.9999: 24.958 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  18.992 ms/op
                 getUser·p0.9999: 25.845 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279652
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3149 
    [ 2.500,  5.000) = 270790 
    [ 5.000,  7.500) = 4246 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     19.520 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.670 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 12.925 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  20.101 ms/op
                 listUser·p0.9999: 22.998 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 3.991 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.662 ms/op
                 listUser·p0.9999: 22.511 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 3.963 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 22.280 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241364
  mean =      3.975 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 234836 
    [ 5.000,  7.500) = 4977 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     22.433 ms/op
     p(99.9990) =     24.687 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.125 ± 2.093  ops/ms
ClientPb.existUser                       thrpt       3   9.555 ± 4.801  ops/ms
ClientPb.getUser                         thrpt       3   9.334 ± 1.375  ops/ms
ClientPb.listUser                        thrpt       3   8.105 ± 1.388  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 1.400   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 0.754   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 1.367   ms/op
ClientPb.listUser                         avgt       3   3.918 ± 0.555   ms/op
ClientPb.createUser                     sample  280727   3.419 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.280           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.238           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.428           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  284938   3.367 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.978           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.969           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.639           ms/op
ClientPb.getUser                        sample  279652   3.431 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.520           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.951           ms/op
ClientPb.listUser                       sample  241364   3.975 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.430           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.433           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.936           ms/op
