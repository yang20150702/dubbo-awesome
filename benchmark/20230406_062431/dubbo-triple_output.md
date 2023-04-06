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
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 8.708 ops/ms
Iteration   1: 9.798 ops/ms
Iteration   2: 10.054 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.905 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (9.798, 9.905, 10.054), stdev = 0.133
  CI (99.9%): [7.471, 12.338] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ops/ms
# Warmup Iteration   2: 9.336 ops/ms
# Warmup Iteration   3: 9.823 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 10.175 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.256 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (10.175, 10.256, 10.323), stdev = 0.075
  CI (99.9%): [8.888, 11.624] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.459 ops/ms
# Warmup Iteration   2: 9.128 ops/ms
# Warmup Iteration   3: 9.430 ops/ms
Iteration   1: 9.899 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 9.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.939 ±(99.9%) 4.771 ops/ms [Average]
  (min, avg, max) = (9.699, 9.939, 10.217), stdev = 0.262
  CI (99.9%): [5.168, 14.710] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ops/ms
# Warmup Iteration   2: 7.835 ops/ms
# Warmup Iteration   3: 8.280 ops/ms
Iteration   1: 8.454 ops/ms
Iteration   2: 8.678 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.426 ±(99.9%) 4.869 ops/ms [Average]
  (min, avg, max) = (8.146, 8.426, 8.678), stdev = 0.267
  CI (99.9%): [3.557, 13.295] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.143 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.007 ms/op
Iteration   1: 3.231 ±(99.9%) 0.007 ms/op
Iteration   2: 3.141 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.147 ±(99.9%) 1.485 ms/op [Average]
  (min, avg, max) = (3.068, 3.147, 3.231), stdev = 0.081
  CI (99.9%): [1.662, 4.632] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.337 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 3.156 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.095 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (3.027, 3.095, 3.156), stdev = 0.065
  CI (99.9%): [1.912, 4.278] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.616 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
Iteration   3: 3.153 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.130 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.106, 3.130, 3.153), stdev = 0.023
  CI (99.9%): [2.708, 3.552] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.468 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.005 ms/op
Iteration   1: 3.863 ±(99.9%) 0.008 ms/op
Iteration   2: 3.750 ±(99.9%) 0.008 ms/op
Iteration   3: 3.837 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.817 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (3.750, 3.817, 3.863), stdev = 0.059
  CI (99.9%): [2.739, 4.895] (assumes normal distribution)


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
# Warmup Iteration   1: 8.525 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.009 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  11.241 ms/op
                 createUser·p0.9999: 21.899 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.363 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  17.787 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  14.140 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292604
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19286 
    [ 2.500,  5.000) = 267184 
    [ 5.000,  7.500) = 5300 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     14.142 ms/op
     p(99.9900) =     27.753 ms/op
     p(99.9990) =     29.431 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  11.836 ms/op
                 existUser·p0.9999: 18.703 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 21.031 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306415
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15736 
    [ 2.500,  5.000) = 285989 
    [ 5.000,  7.500) = 3958 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     11.635 ms/op
     p(99.9900) =     20.819 ms/op
     p(99.9990) =     22.182 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 8.266 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  15.564 ms/op
                 getUser·p0.9999: 23.543 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.211 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.044 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  20.808 ms/op
                 getUser·p0.9999: 24.446 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.463 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289608
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21376 
    [ 2.500,  5.000) = 262165 
    [ 5.000,  7.500) = 5274 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.568 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.717 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 10.166 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
Iteration   1: 3.800 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.288 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 28.508 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 3.756 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 14.860 ms/op
                 listUser·p1.00:   14.860 ms/op

Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 17.844 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251379
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 242246 
    [ 5.000,  7.500) = 6911 
    [ 7.500, 10.000) = 1400 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     27.025 ms/op
     p(99.9990) =     28.999 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.905 ± 2.433  ops/ms
ClientPb.existUser                       thrpt       3  10.256 ± 1.368  ops/ms
ClientPb.getUser                         thrpt       3   9.939 ± 4.771  ops/ms
ClientPb.listUser                        thrpt       3   8.426 ± 4.869  ops/ms
ClientPb.createUser                       avgt       3   3.147 ± 1.485   ms/op
ClientPb.existUser                        avgt       3   3.095 ± 1.183   ms/op
ClientPb.getUser                          avgt       3   3.130 ± 0.422   ms/op
ClientPb.listUser                         avgt       3   3.817 ± 1.078   ms/op
ClientPb.createUser                     sample  292604   3.279 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.142           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.753           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  306415   3.131 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.327           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.635           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.819           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.544           ms/op
ClientPb.getUser                        sample  289608   3.312 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.266           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.568           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.527           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.871           ms/op
ClientPb.listUser                       sample  251379   3.815 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.025           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.327           ms/op
