# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.404 ops/ms
# Warmup Iteration   2: 5.871 ops/ms
# Warmup Iteration   3: 8.939 ops/ms
Iteration   1: 9.173 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.301 ±(99.9%) 3.232 ops/ms [Average]
  (min, avg, max) = (9.173, 9.301, 9.503), stdev = 0.177
  CI (99.9%): [6.068, 12.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.090 ops/ms
# Warmup Iteration   2: 8.531 ops/ms
# Warmup Iteration   3: 9.594 ops/ms
Iteration   1: 9.826 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 10.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.058 ±(99.9%) 3.966 ops/ms [Average]
  (min, avg, max) = (9.826, 10.058, 10.257), stdev = 0.217
  CI (99.9%): [6.092, 14.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.957 ops/ms
# Warmup Iteration   2: 8.264 ops/ms
# Warmup Iteration   3: 9.192 ops/ms
Iteration   1: 9.533 ops/ms
Iteration   2: 9.258 ops/ms
Iteration   3: 9.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.402 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (9.258, 9.402, 9.533), stdev = 0.138
  CI (99.9%): [6.888, 11.916] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.969 ops/ms
# Warmup Iteration   2: 7.483 ops/ms
# Warmup Iteration   3: 8.021 ops/ms
Iteration   1: 8.266 ops/ms
Iteration   2: 8.132 ops/ms
Iteration   3: 7.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.131 ±(99.9%) 2.458 ops/ms [Average]
  (min, avg, max) = (7.996, 8.131, 8.266), stdev = 0.135
  CI (99.9%): [5.673, 10.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.770 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.005 ms/op
Iteration   1: 3.500 ±(99.9%) 0.006 ms/op
Iteration   2: 3.430 ±(99.9%) 0.007 ms/op
Iteration   3: 3.348 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.426 ±(99.9%) 1.388 ms/op [Average]
  (min, avg, max) = (3.348, 3.426, 3.500), stdev = 0.076
  CI (99.9%): [2.038, 4.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.002 ms/op
Iteration   1: 3.295 ±(99.9%) 0.005 ms/op
Iteration   2: 3.295 ±(99.9%) 0.006 ms/op
Iteration   3: 3.261 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.284 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.261, 3.284, 3.295), stdev = 0.020
  CI (99.9%): [2.922, 3.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.407 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.004 ms/op
Iteration   1: 3.395 ±(99.9%) 0.011 ms/op
Iteration   2: 3.495 ±(99.9%) 0.005 ms/op
Iteration   3: 3.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.449 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (3.395, 3.449, 3.495), stdev = 0.051
  CI (99.9%): [2.525, 4.374] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.099 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.009 ms/op
Iteration   1: 3.900 ±(99.9%) 0.013 ms/op
Iteration   2: 4.024 ±(99.9%) 0.011 ms/op
Iteration   3: 3.924 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.949 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.900, 3.949, 4.024), stdev = 0.066
  CI (99.9%): [2.744, 5.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.957 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  16.577 ms/op
                 createUser·p0.9999: 22.589 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   5.572 ms/op
                 createUser·p0.999:  24.295 ms/op
                 createUser·p0.9999: 27.161 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   3: 3.459 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  17.864 ms/op
                 createUser·p0.9999: 22.635 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284338
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15463 
    [ 2.500,  5.000) = 263648 
    [ 5.000,  7.500) = 4359 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     17.880 ms/op
     p(99.9900) =     26.331 ms/op
     p(99.9990) =     27.700 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.663 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.008 ms/op
Iteration   1: 3.238 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  9.525 ms/op
                 existUser·p0.9999: 24.496 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  18.713 ms/op
                 existUser·p0.9999: 30.409 ms/op
                 existUser·p1.00:   30.802 ms/op

Iteration   3: 3.245 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.456 ms/op
                 existUser·p0.9999: 22.199 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291005
  mean =      3.294 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20349 
    [ 2.500,  5.000) = 265514 
    [ 5.000,  7.500) = 4339 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     29.173 ms/op
     p(99.9990) =     30.710 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.046 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.008 ms/op
Iteration   1: 3.486 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  18.654 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.432 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  19.130 ms/op
                 getUser·p0.9999: 29.634 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277468
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4605 
    [ 2.500,  5.000) = 264680 
    [ 5.000,  7.500) = 6780 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     28.206 ms/op
     p(99.9990) =     29.947 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.543 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.013 ms/op
Iteration   1: 4.042 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  18.637 ms/op
                 listUser·p0.9999: 24.805 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.058 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.410 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.046 ms/op
                 listUser·p0.9999: 20.418 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237733
  mean =      4.042 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 227510 
    [ 5.000,  7.500) = 7814 
    [ 7.500, 10.000) = 1551 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     25.562 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.301 ± 3.232  ops/ms
ClientPb.existUser                       thrpt       3  10.058 ± 3.966  ops/ms
ClientPb.getUser                         thrpt       3   9.402 ± 2.514  ops/ms
ClientPb.listUser                        thrpt       3   8.131 ± 2.458  ops/ms
ClientPb.createUser                       avgt       3   3.426 ± 1.388   ms/op
ClientPb.existUser                        avgt       3   3.284 ± 0.362   ms/op
ClientPb.getUser                          avgt       3   3.449 ± 0.924   ms/op
ClientPb.listUser                         avgt       3   3.949 ± 1.206   ms/op
ClientPb.createUser                     sample  284338   3.375 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.578           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.331           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.148           ms/op
ClientPb.existUser                      sample  291005   3.294 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.173           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  277468   3.457 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.128           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  237733   4.042 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.410           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
