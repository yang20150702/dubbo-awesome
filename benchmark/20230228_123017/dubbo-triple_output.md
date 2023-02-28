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
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 5.761 ops/ms
# Warmup Iteration   3: 8.435 ops/ms
Iteration   1: 9.553 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.548 ±(99.9%) 0.417 ops/ms [Average]
  (min, avg, max) = (9.523, 9.548, 9.568), stdev = 0.023
  CI (99.9%): [9.131, 9.965] (assumes normal distribution)


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
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 8.408 ops/ms
# Warmup Iteration   3: 9.240 ops/ms
Iteration   1: 9.635 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.704 ±(99.9%) 4.086 ops/ms [Average]
  (min, avg, max) = (9.523, 9.704, 9.954), stdev = 0.224
  CI (99.9%): [5.618, 13.790] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.375 ±(99.9%) 3.315 ops/ms [Average]
  (min, avg, max) = (9.213, 9.375, 9.571), stdev = 0.182
  CI (99.9%): [6.060, 12.691] (assumes normal distribution)


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
# Warmup Iteration   1: 2.602 ops/ms
# Warmup Iteration   2: 7.268 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 8.322 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.178 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (8.046, 8.178, 8.322), stdev = 0.138
  CI (99.9%): [5.653, 10.703] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.250 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.009 ms/op
Iteration   1: 3.365 ±(99.9%) 0.008 ms/op
Iteration   2: 3.486 ±(99.9%) 0.005 ms/op
Iteration   3: 3.397 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.416 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (3.365, 3.416, 3.486), stdev = 0.063
  CI (99.9%): [2.272, 4.560] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.167 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.010 ms/op
Iteration   2: 3.240 ±(99.9%) 0.009 ms/op
Iteration   3: 3.288 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.239 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (3.190, 3.239, 3.288), stdev = 0.049
  CI (99.9%): [2.349, 4.130] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.782 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.007 ms/op
Iteration   1: 3.442 ±(99.9%) 0.006 ms/op
Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
Iteration   3: 3.373 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.412 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.373, 3.412, 3.442), stdev = 0.035
  CI (99.9%): [2.768, 4.056] (assumes normal distribution)


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
# Warmup Iteration   1: 11.265 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.010 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
Iteration   2: 3.833 ±(99.9%) 0.016 ms/op
Iteration   3: 3.954 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.937 ±(99.9%) 1.763 ms/op [Average]
  (min, avg, max) = (3.833, 3.937, 4.024), stdev = 0.097
  CI (99.9%): [2.174, 5.700] (assumes normal distribution)


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
# Warmup Iteration   1: 8.265 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
Iteration   1: 3.440 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  17.864 ms/op
                 createUser·p0.9999: 23.091 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.049 ms/op
                 createUser·p0.999:  21.219 ms/op
                 createUser·p0.9999: 24.763 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.364 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  19.802 ms/op
                 createUser·p0.9999: 24.124 ms/op
                 createUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277065
  mean =      3.462 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10317 
    [ 2.500,  5.000) = 259818 
    [ 5.000,  7.500) = 5839 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     25.597 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 8.524 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
Iteration   1: 3.261 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.978 ms/op
                 existUser·p0.9999: 22.956 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  23.645 ms/op
                 existUser·p0.9999: 34.112 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288481
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10096 
    [ 2.500,  5.000) = 272056 
    [ 5.000,  7.500) = 5255 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.903 ms/op
     p(99.9900) =     33.461 ms/op
     p(99.9990) =     34.938 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 9.090 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
Iteration   1: 3.407 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  20.321 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  22.381 ms/op
                 getUser·p0.9999: 26.128 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  16.911 ms/op
                 getUser·p0.9999: 27.280 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284310
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5687 
    [ 2.500,  5.000) = 272396 
    [ 5.000,  7.500) = 5185 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     17.281 ms/op
     p(99.9900) =     26.069 ms/op
     p(99.9990) =     29.048 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 11.407 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.013 ms/op
Iteration   1: 4.055 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  19.109 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 4.075 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.820 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.705 ms/op
                 listUser·p0.9999: 18.327 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 4.154 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 15.732 ms/op
                 listUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234345
  mean =      4.094 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 224455 
    [ 5.000,  7.500) = 7023 
    [ 7.500, 10.000) = 1945 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.624 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.548 ± 0.417  ops/ms
ClientPb.existUser                       thrpt       3   9.704 ± 4.086  ops/ms
ClientPb.getUser                         thrpt       3   9.375 ± 3.315  ops/ms
ClientPb.listUser                        thrpt       3   8.178 ± 2.525  ops/ms
ClientPb.createUser                       avgt       3   3.416 ± 1.144   ms/op
ClientPb.existUser                        avgt       3   3.239 ± 0.891   ms/op
ClientPb.getUser                          avgt       3   3.412 ± 0.644   ms/op
ClientPb.listUser                         avgt       3   3.937 ± 1.763   ms/op
ClientPb.createUser                     sample  277065   3.462 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.300           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.921           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  288481   3.325 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.182           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.903           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.461           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  284310   3.374 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.281           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.069           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.540           ms/op
ClientPb.listUser                       sample  234345   4.094 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.430           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
