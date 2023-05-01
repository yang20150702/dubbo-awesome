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
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 5.147 ops/ms
# Warmup Iteration   3: 8.545 ops/ms
Iteration   1: 9.492 ops/ms
Iteration   2: 9.717 ops/ms
Iteration   3: 8.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.377 ±(99.9%) 7.476 ops/ms [Average]
  (min, avg, max) = (8.922, 9.377, 9.717), stdev = 0.410
  CI (99.9%): [1.901, 16.853] (assumes normal distribution)


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
# Warmup Iteration   1: 3.301 ops/ms
# Warmup Iteration   2: 9.097 ops/ms
# Warmup Iteration   3: 8.966 ops/ms
Iteration   1: 9.942 ops/ms
Iteration   2: 9.423 ops/ms
Iteration   3: 9.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.677 ±(99.9%) 4.739 ops/ms [Average]
  (min, avg, max) = (9.423, 9.677, 9.942), stdev = 0.260
  CI (99.9%): [4.938, 14.415] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.059 ops/ms
# Warmup Iteration   2: 8.209 ops/ms
# Warmup Iteration   3: 9.211 ops/ms
Iteration   1: 9.523 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.470 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (9.418, 9.470, 9.523), stdev = 0.053
  CI (99.9%): [8.507, 10.434] (assumes normal distribution)


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
# Warmup Iteration   1: 2.726 ops/ms
# Warmup Iteration   2: 7.089 ops/ms
# Warmup Iteration   3: 7.780 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 8.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.058 ±(99.9%) 2.612 ops/ms [Average]
  (min, avg, max) = (7.974, 8.058, 8.224), stdev = 0.143
  CI (99.9%): [5.446, 10.671] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.438 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.348 ±(99.9%) 0.007 ms/op
Iteration   2: 3.402 ±(99.9%) 0.012 ms/op
Iteration   3: 3.353 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.368 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.348, 3.368, 3.402), stdev = 0.030
  CI (99.9%): [2.823, 3.913] (assumes normal distribution)


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
# Warmup Iteration   1: 8.509 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.006 ms/op
Iteration   1: 3.353 ±(99.9%) 0.003 ms/op
Iteration   2: 3.346 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.307 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.222, 3.307, 3.353), stdev = 0.074
  CI (99.9%): [1.961, 4.652] (assumes normal distribution)


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
# Warmup Iteration   1: 8.838 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.004 ms/op
Iteration   1: 3.528 ±(99.9%) 0.006 ms/op
Iteration   2: 3.503 ±(99.9%) 0.005 ms/op
Iteration   3: 3.357 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.463 ±(99.9%) 1.679 ms/op [Average]
  (min, avg, max) = (3.357, 3.463, 3.528), stdev = 0.092
  CI (99.9%): [1.784, 5.141] (assumes normal distribution)


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
# Warmup Iteration   1: 9.769 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.006 ms/op
Iteration   1: 4.124 ±(99.9%) 0.008 ms/op
Iteration   2: 3.861 ±(99.9%) 0.015 ms/op
Iteration   3: 3.908 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.964 ±(99.9%) 2.557 ms/op [Average]
  (min, avg, max) = (3.861, 3.964, 4.124), stdev = 0.140
  CI (99.9%): [1.407, 6.522] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.928 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.406 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  21.386 ms/op
                 createUser·p0.9999: 23.843 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.046 ms/op
                 createUser·p0.999:  17.850 ms/op
                 createUser·p0.9999: 24.818 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284872
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9670 
    [ 2.500,  5.000) = 269799 
    [ 5.000,  7.500) = 4270 
    [ 7.500, 10.000) = 526 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     18.485 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.597 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 8.730 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  10.352 ms/op
                 existUser·p0.9999: 21.551 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  9.127 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.304 ms/op
                 existUser·p0.999:  12.672 ms/op
                 existUser·p0.9999: 25.100 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293650
  mean =      3.268 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11077 
    [ 2.500,  5.000) = 278803 
    [ 5.000,  7.500) = 3068 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.158 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.317 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 9.237 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
Iteration   1: 3.405 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 27.827 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  18.268 ms/op
                 getUser·p0.9999: 31.834 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   3: 3.517 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 26.080 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281058
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5723 
    [ 2.500,  5.000) = 267032 
    [ 5.000,  7.500) = 7257 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     10.746 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     32.518 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 13.384 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
Iteration   1: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.396 ms/op
                 listUser·p0.999:  20.226 ms/op
                 listUser·p0.9999: 28.281 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   2: 4.005 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.222 ms/op
                 listUser·p0.9999: 25.921 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 3.909 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241501
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 234037 
    [ 5.000,  7.500) = 5049 
    [ 7.500, 10.000) = 1669 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.704 ms/op
     p(99.9900) =     27.609 ms/op
     p(99.9990) =     29.492 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.377 ± 7.476  ops/ms
ClientPb.existUser                       thrpt       3   9.677 ± 4.739  ops/ms
ClientPb.getUser                         thrpt       3   9.470 ± 0.964  ops/ms
ClientPb.listUser                        thrpt       3   8.058 ± 2.612  ops/ms
ClientPb.createUser                       avgt       3   3.368 ± 0.545   ms/op
ClientPb.existUser                        avgt       3   3.307 ± 1.345   ms/op
ClientPb.getUser                          avgt       3   3.463 ± 1.679   ms/op
ClientPb.listUser                         avgt       3   3.964 ± 2.557   ms/op
ClientPb.createUser                     sample  284872   3.366 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.485           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.790           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.625           ms/op
ClientPb.existUser                      sample  293650   3.268 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.264           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.158           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.936           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  281058   3.413 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.401           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.746           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.015           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670           ms/op
ClientPb.listUser                       sample  241501   3.973 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.704           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.655           ms/op
