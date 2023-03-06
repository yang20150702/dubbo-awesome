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
# Warmup Iteration   1: 1.833 ops/ms
# Warmup Iteration   2: 4.844 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 8.990 ops/ms
Iteration   2: 9.360 ops/ms
Iteration   3: 9.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.353 ±(99.9%) 6.544 ops/ms [Average]
  (min, avg, max) = (8.990, 9.353, 9.708), stdev = 0.359
  CI (99.9%): [2.809, 15.897] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.752 ops/ms
# Warmup Iteration   2: 8.935 ops/ms
# Warmup Iteration   3: 9.318 ops/ms
Iteration   1: 9.626 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 9.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.800 ±(99.9%) 2.752 ops/ms [Average]
  (min, avg, max) = (9.626, 9.800, 9.897), stdev = 0.151
  CI (99.9%): [7.048, 12.553] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 8.200 ops/ms
# Warmup Iteration   3: 8.658 ops/ms
Iteration   1: 9.247 ops/ms
Iteration   2: 9.190 ops/ms
Iteration   3: 8.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.114 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (8.904, 9.114, 9.247), stdev = 0.184
  CI (99.9%): [5.760, 12.467] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.793 ops/ms
# Warmup Iteration   2: 7.214 ops/ms
# Warmup Iteration   3: 7.720 ops/ms
Iteration   1: 7.746 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.965 ±(99.9%) 4.179 ops/ms [Average]
  (min, avg, max) = (7.746, 7.965, 8.203), stdev = 0.229
  CI (99.9%): [3.786, 12.145] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.257 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.006 ms/op
Iteration   1: 3.344 ±(99.9%) 0.016 ms/op
Iteration   2: 3.644 ±(99.9%) 0.006 ms/op
Iteration   3: 3.496 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.495 ±(99.9%) 2.741 ms/op [Average]
  (min, avg, max) = (3.344, 3.495, 3.644), stdev = 0.150
  CI (99.9%): [0.754, 6.236] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.453 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.006 ms/op
Iteration   1: 3.330 ±(99.9%) 0.005 ms/op
Iteration   2: 3.396 ±(99.9%) 0.004 ms/op
Iteration   3: 3.288 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.288, 3.338, 3.396), stdev = 0.054
  CI (99.9%): [2.350, 4.326] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.563 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.007 ms/op
Iteration   1: 3.496 ±(99.9%) 0.005 ms/op
Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
Iteration   3: 3.521 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.474 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.406, 3.474, 3.521), stdev = 0.061
  CI (99.9%): [2.370, 4.579] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.504 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
Iteration   1: 4.136 ±(99.9%) 0.008 ms/op
Iteration   2: 3.995 ±(99.9%) 0.010 ms/op
Iteration   3: 3.949 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.026 ±(99.9%) 1.777 ms/op [Average]
  (min, avg, max) = (3.949, 4.026, 4.136), stdev = 0.097
  CI (99.9%): [2.249, 5.804] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.789 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.014 ms/op
Iteration   1: 3.421 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  21.986 ms/op
                 createUser·p0.9999: 23.702 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.544 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  25.494 ms/op
                 createUser·p0.9999: 30.112 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   3: 3.542 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  23.254 ms/op
                 createUser·p0.9999: 28.735 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274092
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9399 
    [ 2.500,  5.000) = 257564 
    [ 5.000,  7.500) = 5576 
    [ 7.500, 10.000) = 1048 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     22.246 ms/op
     p(99.9900) =     29.478 ms/op
     p(99.9990) =     31.859 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.418 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 23.904 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  14.713 ms/op
                 existUser·p0.9999: 25.585 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.381 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  22.516 ms/op
                 existUser·p0.9999: 30.164 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283559
  mean =      3.384 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8961 
    [ 2.500,  5.000) = 268628 
    [ 5.000,  7.500) = 4663 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     16.064 ms/op
     p(99.9900) =     29.763 ms/op
     p(99.9990) =     30.349 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.999 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.010 ms/op
Iteration   1: 3.565 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  21.572 ms/op
                 getUser·p0.9999: 25.364 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.163 ms/op
                 getUser·p0.9999: 28.180 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.311 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283889
  mean =      3.379 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1589 
    [ 2.500,  5.000) = 276534 
    [ 5.000,  7.500) = 4374 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     21.339 ms/op
     p(99.9900) =     32.985 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.468 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.014 ms/op
Iteration   1: 4.064 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 27.042 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 4.064 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.646 ms/op
                 listUser·p0.9999: 18.333 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 4.046 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  16.725 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236666
  mean =      4.058 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 226089 
    [ 5.000,  7.500) = 8213 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     17.782 ms/op
     p(99.9900) =     25.417 ms/op
     p(99.9990) =     27.400 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.353 ± 6.544  ops/ms
ClientPb.existUser                       thrpt       3   9.800 ± 2.752  ops/ms
ClientPb.getUser                         thrpt       3   9.114 ± 3.354  ops/ms
ClientPb.listUser                        thrpt       3   7.965 ± 4.179  ops/ms
ClientPb.createUser                       avgt       3   3.495 ± 2.741   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 0.988   ms/op
ClientPb.getUser                          avgt       3   3.474 ± 1.105   ms/op
ClientPb.listUser                         avgt       3   4.026 ± 1.777   ms/op
ClientPb.createUser                     sample  274092   3.502 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.027           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.246           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.478           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  283559   3.384 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.064           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.441           ms/op
ClientPb.getUser                        sample  283889   3.379 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.450           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.985           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  236666   4.058 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.122           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.782           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.417           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.754           ms/op
